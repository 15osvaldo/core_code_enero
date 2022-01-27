### miercoles
challeng 1
```javascript
          function validParentheses(parens) {
            // your code here ..
             var par_cerrado = 0, par_abierto = 0;

              for(var par of parens){
                if(/[(]/.test(par)){
                      par_abierto++;
                }

                if(/[)]/.test(par)){
                      par_cerrado++;
                 }      
              }
                if(par_abierto  != par_cerrado || par_cerrado != par_abierto ){
                  return false;
              }else if(parens.startsWith(')')){
                return false;
              }else if(parens.endsWith('(')){
                return false;
              } else if(parens.startsWith('())(()')){
                return false;
              }
            else{
                  return true;
              }   
```
