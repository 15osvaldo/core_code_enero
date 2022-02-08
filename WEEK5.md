
### Monday

# 2

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
  # 3

```typescript

export class G964 {

    public static nbYear = (p0, percent, aug, p) => {
        // your code
      for(var res = 0; p0 < p; res++) p0 = p0 * (1 + percent / 100) + aug;
        return res;

      }    
}

```
# 4
```typescript
  export function accum(s: string): string {
   return s.split('')
    .map((elem, index) => elem.toUpperCase() + (elem.toLowerCase()).repeat(index))
    .join('-');
  }
```


# 5

```typescript

    export function warnTheSheep(queue: string[]): string {
      let wolf = queue.indexOf('wolf');

      return wolf === queue.length - 1 ? `Pls go away and stop eating my sheep` : `Oi! Sheep number ${queue.length - wolf -1}! You are about to be eaten by a wolf!`;

    }
```
