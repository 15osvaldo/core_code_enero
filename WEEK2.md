
# Tuesday
### Respuesta de Challenge 1
```javascript

              function multiply(a, b){
               return a * b
                }
```

 ### Respuesta del challenge 2
 ```javascript

              function uniTotal (string) {
              // total up dem unicodes!
              let arr = Array.from(string);
                let suma = 0;
                for(let i = 0; i < arr.length; i++){
                  suma += arr[i].charCodeAt(0);
                }
                return suma;
              }
 ```

### Respuesta del Challenge 3
```javascript
              function getChar(c){
              // ...
              return String.fromCharCode(c);
            }
```
### Respuesta del Challenge 4
```Javascript
    function addBinary(a,b) {
    var c = a + b;
    var cBinary = c.toString(2);

    return c , cBinary;
  }
  console.log(addBinary(5,2));
  ```
  ### Respuesta del challenge 5
  ```javascript
      function finalGrade (exam, projects) {
      if(exam > 90 || projects > 10){
        return 100;
        }
      else if(exam > 75 && projects >= 5){
        return 90;
        }
      else if( exam > 50 && projects >= 2){

      return 75; 
      }
      else{
      return 0; // final grade
      }    
    }
```
# 

### Respuesta del challenge 1

```javascript

    function dutyFree(normPrice, discount, hol){
      let ahorro = Math.floor(normPrice/(100/discount));
      let respuesta = Math.floor(hol/ahorro);

      return respuesta; 
    }
```
### Respuesta del chalenge 2
```javascript
function twiceAsOld(dadYearsOld, sonYearsOld) {
  // your code here
  
  // se divide la edad del hijo dentro del padre 
  let edad = dadYearsOld/sonYearsOld;
  
  if(edad != 2 ){
     let respuesta = dadYearsOld - (sonYearsOld * 2);
     return Math.abs(respuesta);
     }else if(edad == 2){
       return 0;
     }
  

```

            
