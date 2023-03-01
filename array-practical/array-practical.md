### 1. Function ko 1 number pass krna hai. jo number pass kia hai us number ki table print krni hai. for example 5 5*1=5 , 5*2=10

```
function table(a) {
 for (let i = 1; i <= 10; i++) {
   console.log(a + "*" + i + "=" + i * a);
 }
}

table(5);

```

## 2. Function ko 2 numbers pass krne hai. Numbers ko multiply krna hai

```
function multipleNumber(a, b) {
  console.log(a * b);
}

multipleNumber(8, 3);

```

## 3. Function ko array bnana hai and array ke sare numbers ko print krna hai

```
function array(arr) {
  for (let a = 0; a < arr.length; a++) {
    console.log(arr[a]);
  }
}

array([32, 84, 52, 04, 73, 03, 63, 23, 42, 1, 83, 01, 2]);
```

## 4. Function bnana hai. Function me ek value leni hai. agar value true hai to Yes print kro otherwise No print kro

```

function checkValue(value) {
  if (value) {
    console.log("yes");
  } else {
    console.log("no");
  }
}

checkValue(true);

```

## 5. Function bnana hai. Function ko 2 numbers pass krne hai min and max. for example 10 and 20 to tume 10 se leke 20 tak print krvana hai

```
function maxMinNumber(min, max) {
 for (let a = min; a <= max; a++) {
   console.log(a);
 }
}

maxMinNumber(10, 20);

```

## 6. function bnana hai. Function ko 1 number pass krna hai. 0 se leke us number tak jitne b Odd numbers hai vo print krne hai.

```

function oddNumber(odd) {
  for (let i = 1; i <= odd; i++) {
    if (i % 2 === 1) {
      console.log(i);
    }
  }
}

oddNumber(20);
```

## 7. function bnana hai. Function ko 1 number pass krna hai. 0 se leke us number tak jitne b Even numbers hai vo print krne hai.

```
function evenNumber(even) {
  for (let i = 1; i <= even; i++) {
    if (i % 2 === 0) {
      console.log(i);
    }
  }
}

evenNumber(20);

```

## 8. Ek function bnana hai. Is function ko 2 number pas krne hai. phla number ek number hoga

## aur dusra number maximum number hoga. fir hume phle number ke multiples max number tak print krne hai.

## for example: 5, 100

## 5 10 15 20 25...... 100

```
function multiple(a, b) {
  for (let x = 1; x <= b; x++) {
    if (x % a === 0) {
      console.log(x);
    }
  }
}

multiple(5, 100);

```
