# Lokshyna Hanna

**Contact Info:**
Minsk
*Phone number:* +375 29 506 54 63
*Email*: anna.lokshina1@gmail.com
*Skype:* AnnaLokshina
*[LinkedIn]*(https://www.linkedin.com/in/anna-lokshina-315777179/)

**Summary:** I’d like to start Junior Web-developer career in a stable company and grow to Teamlead in 5-7 years. I’m ready to quickly learn new material, learn a lot.

**Skills:**HTML/CSS(Flex, Grid, BEM, Responsive Design)/JavaScript, SVG, Canvas, Gulp, Git, Bootstrap.

**Code examples:**
`"use strict"
function vowelsCounter1(str) {
    var strArr = str.split('');
    var counter = 0;
     strArr.forEach(currentEl => { 
      if ( 'уеыаоэяию'.includes(currentEl) ) 
        counter++;
    } )
    return counter;
}
console.log(vowelsCounter1(prompt('Введите строку для подсчета гласных')));

function vowelsCounter2(str){
  var strArr = str.split('');
  var resultVowels = strArr. filter( el => 'ауеыоэяию'.includes(el));
  return resultVowels.length;
}
console.log(vowelsCounter2(prompt('Введите строку для подсчета гласных')));

function vowelsCounter3(str) {
  var strArr = str.split('');
  var resultVowels = strArr.reduce((accum, value) => {
    if('уеыаоэяию'.includes(value) == true ){
       accum++
    };
    return accum;
    }, 0);
    return resultVowels;
}
console.log(vowelsCounter3(prompt('введите строку для подсчета гласных')));`



