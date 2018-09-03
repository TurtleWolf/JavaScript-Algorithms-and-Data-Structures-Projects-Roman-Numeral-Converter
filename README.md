# JavaScript-Algorithms-and-Data-Structures-Projects-Roman-Numeral-Converter
[Roman Numeral Converter](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/javascript-algorithms-and-data-structures-projects/roman-numeral-converter "Free Code Camp")  
Convert the given number into a roman numeral.  

:speech_balloon: Hint: 1  
Creating two arrays, one with the Roman Numerals and one with the decimal equivalent for the new forms will be very helpful.  

:speech_balloon: Hint: 2  
If you add the numbers to the arrays that go before the new letter is introduced, like values for 4, 9, and 40, it will save you plenty of code.  

:speech_balloon: Hint: 3  
You can’t have more than three consecutive Roman numerals together.  
```
function convertToRoman(num) {
//convert num to a roman numberal
console.log(num);
 return num;
}

convertToRoman(36);
convertToRoman(2); // should return "II".  
convertToRoman(3); // should return "III".  
convertToRoman(4); // should return "IV".  
convertToRoman(5); // should return "V".  
convertToRoman(9); // should return "IX".  
convertToRoman(12); // should return "XII".  
convertToRoman(16); // should return "XVI".  
convertToRoman(29); // should return "XXIX".  
convertToRoman(44); // should return "XLIV".  
convertToRoman(45); // should return "XLV"  
convertToRoman(68); // should return "LXVIII"  
convertToRoman(83); // should return "LXXXIII"  
convertToRoman(97); // should return "XCVII"  
convertToRoman(99); // should return "XCIX"  
convertToRoman(400); // should return "CD"  
convertToRoman(500); // should return "D"  
convertToRoman(501); // should return "DI"  
convertToRoman(649); // should return "DCXLIX"  
convertToRoman(798); // should return "DCCXCVIII"  
convertToRoman(891); // should return "DCCCXCI"  
convertToRoman(1000); // should return "M"  
convertToRoman(1004); // should return "MIV"  
convertToRoman(1006); // should return "MVI"  
convertToRoman(1023); // should return "MXXIII"  
convertToRoman(2014); // should return "MMXIV"  
convertToRoman(3999); // should return "MMMCMXCIX" 
```
```
1       I  
5       V  
10      X  
50      L  
100     C  
500     D  
1000    M  
```
