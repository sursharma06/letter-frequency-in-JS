# letter-frequency-in-JS
// Letter Frequency  // We want a function that tells us how many times each letter appears in a string. The function will return an object who's keys represent each letter and the values represent how many times that letter appeared.  function letterFrequency(str) {   var obj = {};   for(var i =0; i&lt; str.length; i++){     var key = str[i];     //console.log(key)     if(key in obj) { // >>> checking if character iis already in obj       obj[key]++; // every repeated character will be incremented     } else {       obj[key] = 1; //to assign the key variable to the object     }       }    return obj; }

function letterFrequency(str) {
  var obj = {};
  for(var i =0; i< str.length; i++){
    var key = str[i];
    //console.log(key)
    if(key in obj) { // >>> checking if character iis already in obj
      obj[key]++; // every repeated character will be incremented
    } else {
      obj[key] = 1; //to assign the key variable to the object
    }
      } 
  return obj;
}
