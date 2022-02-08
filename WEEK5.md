
### Monday

```typescript
                           export function squareSum(numbers: number[]): number {
                           let suma = 0;
                          let cuadrados = [];
                          let numero = number;
                          for(let i = 0; i < numero.length; i++){
                            cuadrados.push(Math.pow(numero[i],2));
                            }
                          for(let i = 0; i < cuadrados.length; i++){

                            suma += cuadrados[i];
                          }

                          return suma;
                        }
```

```typescript

export class G964 {

    public static nbYear = (p0, percent, aug, p) => {
        // your code
      for(var res = 0; p0 < p; res++) p0 = p0 * (1 + percent / 100) + aug;
        return res;

      }    
}

```
