
# Lunes 
challeng 1
```javascript
          function likes(names) {
            // TODO
            var lista = [] ;
            let no = 'no one likes this'

            if( names != null) {
              lista.push(names);
               if(lista.length == 1){
                console.log(` ${lista[0]} likes this `)
              }else if( lista.length == 2){
                console.log(`${lista[0]} and ${lista[1]} likes this`)
              }else if(lista.length == 3){
                consolelog(`${lista[0]}, ${lista[1]} and ${lista[2]} likes this`)
              }else if(lista.length > 3){
                console.log(`${lista[0]}, ${lista[1]} and ${lista.length - 2} likes this`)
              }
             }else if(names = null) {
               console.log(no);
             }else if(names = undefined){
               console.log(no)
             }

          }

```
challeng 2
```javascript
 
           var countBits = function(n) {
            // Program Me
             let num = n;
            let binary = (num % 2).toString();
            let bit = 0;
            for(; num > 1 ;){
              num = parseInt(num / 2);
              binary = (num % 2 ) + binary;
            }

            for(let i = 0, length = binary.length; i < length; i++){
              if(binary[i] == 1 ){
                bit++;
              }
            }
            //console.log(binary);
            return bit;

          };
 
```
challeng 3
```javascript

          decodeMorse = function(morseCode){
            //your code here
           return morseCode.split("   ").map(word => word.split(" ").map(character => MORSE_CODE[character]).join('')).join(' ').trim()
          }
```





# miercoles
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
