# Alijon Jumanazarov

## Junior Frontend Developer

## Contact Information:

- **Phone:** +998 99 894 40 88
- **E-mail:** [alexlions310@gmail.com](mailto:alexlions310@gmail.com)
- **Telegram:** [https://t.me/Adamantine1](https://t.me/Adamantine1)
- **Linkedin:** [https://www.linkedin.com/in/alijon-jumanazarov-9133a9161](https://www.linkedin.com/in/alijon-jumanazarov-9133a9161)
- **GitHub:** [https://github.com/Alexlions310](https://github.com/Alexlions310)

## Briefly About Myself:

I am a front-end web developer with 1+ years of remote working experience and I hold a university degree as a software engineer. I love creating websites which is why I chose this field 3 years ago when I did my university internship at Robotics Lab. From that moment I felt front-end development was the thing that I had been looking for years

## Skills and Proficiency:

- HTML
- CSS(Framework Bootstrap, Preprocessor SCSS, Methodology BEM)
- JavaScript(OOP, ES5, ES6, ES7, DOM)
- React.js(Framework Next.js)
- Redux(Redux-toolkit)
- Typescript
- Version Control: Git(Remote Servie GitHUB and GitLAB)
- Figma(for Web Development)
- Node.js basics(Framework Express.js)
- MongoDB basics(ODM Mongoose)

## Code Example:

### Anagram Detection:

An anagram is the result of rearranging the letters of a word to produce a new word (see wikipedia). Note: anagrams are case insensitive
Complete the function to return true if the two arguments given are anagrams of each other; return false otherwise.

```
   var isAnagram = function(test, original) {
  test = test.toLowerCase();
  original = original.toLowerCase();
  if(test.length!=original.length){
    return false;
  }
  for(let i=0; i<test.length;i++){
    let testCounter = 0;
    let originalCounter=0;
    for(let k=0; k<test.length;k++){
       if(test[i]===test[k]){
         testCounter++;
       }
      if(test[i] === original[k]){
        originalCounter++;
      }
    }

   if(testCounter!==originalCounter){
     return false;
   }
    else{
      originalCounter = 0;
      testCounter = 0;
    }
  }
  return true;
};
```
