# Appendix

## i++ vs. ++i

```javascript
var A = 2,
    B = 2;
A++;
++B;
console.log("A=",A,"  B=",B);

//---------------------------------------
// >> A=3  B=3
```

```javascript
var A = 2,
    B = 2;
var C = A++;
var D = ++B;
console.log("C=",C,"  D=",D);
//--------------------------------------
// >> C=2  D=3
```

C = A++ : Put A into C and then do A=A+1.

D = ++B : Do B=B+1 and then put B into D.

