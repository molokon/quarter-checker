##Quarter Checker

<span>A simple JavaScript project which allows
to identify a point quarter based on
input values of its 'x' and 'y' axis.</span>

Here is its code:

```javascript
 if(isNaN(x) || isNaN(y)) {
        print('Some coordinate was passed with incorrect value');
  }

 if(x == '' || y == '') {
        print('Some coordinate value is empty');
}if (x > 0 && y > 0) {
    print('Point is in the first QUARTER!');
} else if (x < 0 && y > 0) {
      print('Point is in the second QUARTER!');
 } else if (x < 0 && y < 0) {
      print('Point is in the third QUARTER!');
} else if (x > 0 && y < 0) {
      print('Point is in the fourth QUARTER!');
} else if (x == 0 && y > 0) {
       print('Point is in the 1st or in the 2nd QUARTER!');
} else if (x == 0 && y < 0) {
       print('Point is in the 3rd or in the 2nd QUARTER!');
} else if (x < 0 && y == 0) {
       print('Point is in the 3rd or in the 4th QUARTER!');
} else if (x > 0 && y == 0) {
       print('Point is in the 1st or in the 4th QUARTER!');
 } else if (x == 0 && y == 0){
       print('Point is in beggining of coordinate system');
    }
   ```
   
  Project published:https://molokon.github.io/quarter-checker/
   