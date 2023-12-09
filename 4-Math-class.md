# Mathematical Operations

#### Class `java.lang.Math` provides various mathematical operations:

- Exponential such as e<sup>x</sup> 
- Logarithmic such as log<sub>2</sub>(x)
- Trignometric such as sin(x) cos(x)
- and many more...

Examples of Math functions: 
```java
double a = 1.99, b = 2.99;
double c = Math.cos(a);     // cosine
double d = Math.acos(a);    // arc cosine
double e = Math.sin(a);     // sine
double f = Math.asin(a);    // arc sine
double g = Math.tan(a);     // tangent
double h = Math.atan(a);    // arc tangent
double i = Math.exp(a);     // e^a
double j = Math.max(a,b);   // greater of two values
double k = Math.min(a,b);   // smaller of two values
double l = Math.pow(a,b);   // a^b
double m = Math.sqrt(a);    // square root
double n = Math.random();   // random number 0.0 >= c < 1.0
```

Numeric rounding example: 
```java
int a = 11;
int b = 3;
long c = Math.round(a/b);   // c is 3
double d = Math.round(a/b); // d is 3.0
double e = Math.round((double) a/b*100)/100.0;  // e is 3.67
```
