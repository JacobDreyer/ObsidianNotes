```javaScript
function getNumberFormatConverter(base)
{
    let decimalToBinary = function(num){
    
        let binaryNum = "";
        let remainder = 0;
        let wholeNum = 0;
        
        if(num == 0){
            binaryNum = "0";
        }

        while(num != 0){
            wholeNum = Math.floor(num/2);
            remainder = (num-(wholeNum*2));
            num = wholeNum;
            binaryNum = remainder + binaryNum;
        }

        return binaryNum;
    }

    let decimalToOctal = function(num){
        let binaryNum = "";
        let remainder = 0;
        let wholeNum = 0;
        if(num == 0){
            binaryNum = "0";
        }

        while(num != 0){
            wholeNum = Math.floor(num/8);
            remainder = (num-(wholeNum*8));
            num = wholeNum;
            binaryNum = remainder + binaryNum;
        }

        return binaryNum;
    }

    let decimalToHex = function(num){
        let binaryNum = "";
        let remainder = 0;
        let wholeNum = 0;

        if(num == 0){
            binaryNum = "0";
        }

        while(num != 0){
            wholeNum = Math.floor(num/16);
            remainder = (num-(wholeNum*16));
            num = wholeNum;
            switch(remainder){
                case 10:
                    remainder = "A";
                    break;
                case 11:
                    remainder = "B";
                    break;
                case 12:
                    remainder = "C";
                    break;
                case 13:
                    remainder = "D";
                    break;
                case 14:
                    remainder = "E";
                    break;
                case 15:
                    remainder = "F";
                    break;
                default:
                    break;
            }
            binaryNum = remainder + binaryNum;
        }

        return binaryNum;
    }

    let func;

    switch (base)
    {
        case 2:
            func = decimalToBinary;
            break;
        case 8:
            func = decimalToOctal;
            break;
        case 16:
            func = decimalToHex;
            break;
        default:
            console.log("Invalid Base");
            break;
    }
    return func;
}

let DtoB  =getNumberFormatConverter(2);
let DtoO = getNumberFormatConverter(8);
let DtoHex = getNumberFormatConverter(16);

// don't change the three lines below

module.exports.DtoB = DtoB;

module.exports.DtoO = DtoO;

module.exports.DtoHex = DtoHex;
```