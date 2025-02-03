# goit-js-hw-03

test 1

function slugify(title){
  const titleSlug = title.toLowerCase();
  return titleSlug.split("-");
}

test 2

function makeArray(firstArray,secondArray,maxLength){
  const combinedArray = firstArray.concat(secondArray);

  if (combinedArray.length > maxLength) {
    return combinedArray.slice(0, maxLength);
  }
  return combinedArray;
}
}

test 3

function filterArray(numbers, value){

}
