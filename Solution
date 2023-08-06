const returnSortedArray = (inputArr) => {
    
    let tempArr = [] //Array to store 3 maximum numbers
    for (let i = 0; i < 3; i++) {
        let max = Math.max(...inputArr); //Maximum number from input Array
        tempArr.push(max);
        inputArr.splice(inputArr.indexOf(max), 1); // remove maximum number to get the next maximum number.
    }
    
    tempArr = tempArr.sort((a, b) => a - b); //Sort the maximum numbers Array
    return tempArr;
}

console.log(returnSortedArray([141, 1, 17, -7, -17, -27, 18, 541]));
