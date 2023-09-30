```js
let cleanPoints = function (points)
{
    for (let point of points)
    {
        let xFound=false;
        let yFound=false;
        let zFound=false;  
        for (let prop in point)
        {
            if(prop == "x"){
                xFound = true;
            } else if(prop == "y"){
                yFound = true;
            } else if(prop == "z"){
                zFound = true;
            } else {
                point.pop;
            }
        }

        if(xFound == false){
            point.x = 0;
        }
        if(!yFound){
            point.y = 0;
        }
        if(!zFound){
            point.z = 0;
        }
    }
    return points;
}

  

let points = [
    {x:5, y:7, z:6},
    {y:17, z:10},
    {y:17},
    {y:17, dist:10},
    {x:5, y:7, z:6, w:9},
    {a:5, b:7, c:6},
    {c:6, x:8, y:5},
    {},
    {x:9},
    {x:5}
];

let points_cleaned = cleanPoints(points);
  
function printPoint()
{
    console.log(`x = ${this.x} , y = ${this.y} , z = ${this.z}`);
}

for (let cleanPoint of points_cleaned)
{
    let cPoint = cleanPoint;
    printPoint.call(cPoint);
}
```