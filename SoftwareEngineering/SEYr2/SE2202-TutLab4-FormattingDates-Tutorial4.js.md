```js
function getDateParser(format)
{
    let parser = function(...strings){
        let objArr = [];
        for(let string of strings){
            let compArr = string.split("-");
            let obj = {day : 0, month : 0, year : 0};
            if(format == "B"){
                obj.year = compArr[0];
                obj.month = compArr[1];
                obj.day = compArr[2];
            } else if(format == "L"){
                obj.year = compArr[2];
                obj.month = compArr[1];
                obj.day = compArr[0];
            } else {
                obj.year = compArr[2];
                obj.month = compArr[0];
                obj.day = compArr[1];
            }
            objArr.push(obj);
        }
        return JSON.stringify(objArr);
    }
    return parser;
}

let bigEndianParser = getDateParser("B");
let littleEndianParser = getDateParser("L");
let middleEndianParser = getDateParser("M");

module.exports.bigEndianParser = bigEndianParser;
module.exports.littleEndianParser = littleEndianParser;
module.exports.middleEndianParser = middleEndianParser;
```