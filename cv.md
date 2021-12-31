# rsschool-cv  
## Egor rudman
### Contact information:  
**E-mail:** unek3228@gmail.com  

### About Me: 
In the past, I was a professional eSports player for about 6 years. This industry is very shaky for many reasons, so I redirected all my enthusiasm and attention towards front-end development, which captivated me headlong. For some reason, I always thought that programmers are some kind of super-humans, but when my good friends opened my eyes to the fact that everything is not so scary here and you can constantly improve yourself as in the same video games - I just fired up with happiness. My goal is to become a good specialist in this field, and I know for sure that I will definitely have enough purposefulness for this. 

### My skills:
* Advanced JS  
* HTML, CSS  
* BEM
* git, npm  
* Figma, Adobe Photoshop  
* VSCode

### Code example:

**Solution:**
``` function nextBigger(n) {  
  const arr = String(n).split("");  
  for (var i = arr.length; i > 0; i--) {  
    if (arr[i] > arr[i - 1]) {  
      let [swap, check, counter, mainCo] = [arr[i], arr[i - 1], 0, 0];  
      for (let j = i + 1; j < arr.length; j++) {  
        counter++;  
        arr[j] > check && arr[j] < swap ? (mainCo = counter, swap = arr[j]) : null;  
      }  
      arr[i + mainCo] = arr[i - 1];  
      arr[i - 1] = swap;  
      break  
    }  
  }  
  return arr.join("") === n ? -1 : arr.concat(arr.splice(i).sort((a, b) => a - b)).join("")  
};  
```
### Education: 
* Udemy:    
  * [JavaScript + React](https://www.udemy.com/course/javascript_full/)  
  * [Advanced JavaScript](https://www.udemy.com/course/javascript_practice/)  
* HTML Academy:  
  * [HTML + CSS + practice](https://htmlacademy.ru/courses)  
* [FreeCodeCamp](https://www.freecodecamp.org/)  

### Languages:
* Russian - native language  
* English - B2  
In my old job, I often had to work in English due to the multinational team.