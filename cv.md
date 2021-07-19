* Name: Anastasiya Timina
* Phone:+375297657560(A1)
* Professional: I am an engineer. I work in a telecommunications company. I want to change my life and I start it with a change of profession. I believe that I will succeed. 
* Skills: I studied СSS, HTML and JS.
* <code> 
<script>

  function quadraticEquation(a, b, c)  {
    var D= (b*b) -(4*a*c);
    var x, x1, x2;
    var bResult = ((b>1)&&('+'))||((b<0)&&('-'))||((b===0)&&(""));
    var cResult = ((c>1)&&('+'))||((c<0)&&('-'))||((c===0)&&(""));
    var d, z, y; 

        if (a==1||a==-1){
        d = 'уравнение ' +  'x^2';
    } else {
        d = 'уравнение ' +  a + 'x^2';
    }
    if (b==1||b==-1){
        z =' ' + bResult + ' ' + 'x';
    } else if (b==0){
        z = bResult ;
    } else {
        z = ' ' + bResult +  ' ' + Math.abs(b) + 'x';
    }
    if (c==0){
        y = ' ' + cResult  +  ' =' + ' 0';
    } else {
        y = ' ' + cResult +' ' +  Math.abs(c) +  ' =' + ' 0';
    }
        if (a == 0) {
        console.log ('недопустимое значение');
    } else if (D<0) {
         console.log (d + z + y + ' не имеет вещественных корней');
    } else if (D==0) {
      x=(-b)/(2*a);
      console.log (d + z + y + ' имеет один корень ' + 'x' + '=' + x );
     } else if (D>0) {
        x1=((-b)+ Math.sqrt(D))/(2*a);
        x2=((-b)- Math.sqrt(D))/(2*a);
        console.log (d + z + y +' имеет корни ' + 'x1' + '=' + x1 + ' и ' + 'x2' + '=' + x2);
  }
    }
    quadraticEquation(1, -8, 72);
    quadraticEquation(1, 12, 36);
           </script>
* Position:Junior Dev
* Education: BSUIR, course on website development 

