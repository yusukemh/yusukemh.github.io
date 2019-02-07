---
layout: essay
type: essay
title: Easiest Way To Make Your Code Look Better
# All dates must be YYYY-MM-DD format!
date: 2019-02-04
labels:
  - Javascript
  - ESLint
  - Coding Style
---

# Rules to write codes? No way…
Writing codes can be hard, but looking at codes and figuring out what is going on can be much harder, even if it is your own code. Codes get longer and longer as the project itself gets larger. As I acquire the skills as a member of developers, it will be essential for me to be able to effectively, quickly, and correctly understand codes that I am looking at. But what could be one way I can assure that?

One way is to stick to a coding style. That way, I can remain consistent in terms of how I write codes. It is just simple; write codes within the rule called coding style. This helps people to write in the same manner so that even when programmers are working as a team, reading other people's codes won't be too harsh. I thought this as format in academic essays, which I really hated. I learned so much about MLA, which is one way to format an essay, but I still don't remember anything and every single time I have to write an academic essay, I have to search it up online and apply the rule to my essay, which will take me forever just for an essay. So, first time I heard about coding style, I was discouraged. I didn't like the idea because I didn't want to remember new rules that was irrelevant to language syntax. Making sure I was correctly applying the rules, I thought, would be so time-consuming and laborious! 

# Wait, coding style is fun!
However, the reality was the opposite. Sticking to coding style was so easy, thanks to the developing environment. It automatically tells me where I am violating the code style and how I can fix it. I don’t have to remember anything; just write codes freely and fix the code whenever the IDE tells me to. I could literary see my code becoming more and more neat and clean. After I learned about coding style, coding became more fun to me. Coding style dramatically increases the readability of my codes and this benefits me because now it saves people, including me, so much time to understand the code. It also prevents me from making unnecessary trivial bugs!

# Some benefits of sticking to coding style
Here are some examples of how my codes can change by using coding style:

*the code below tries to calculate the sum of a given array of numbers.*
```
let numList=[1,2,3,4,5];
let temp=[3,4,5,6,7];
function sum(numList){
  return _.reduce(numList,(memo,item)=>(memo+item),0);
}
console.log(sum(numList));
```
This changes into:
```
const numList = [1, 2, 3, 4, 5];
function sum(list) {
  return _.reduce(list, (memo, item) => (memo + item), 0);
}
console.log(sum(numList));
```
This is how the coding style enforces me to write.
Now, there are two types of changes;
First one is putting extra spaces within the code. This significantly increases the readability because the original code is squished in such a little space, making the code hard to read.
The other type of change is potentially related to preventing bugs. ‘let’ is now ‘const’, preventing the variable from changing its value by chance. Moreover, the parameter to the function is now called ’list’, making it obvious that the parameter is not necessarily the same as the global variable. The unnecessary variable ‘temp’ is now removed, because it is never used. This makes the code simple too.

One thing to note is that both the original and revised codes compile and work perfectly fine. In a sense, you can write your code however you want as long as it compiles and works fine. However, coding style does make change in terms of quality of your code, and that for sure helps you write in a better manner and saves you a lot of time.
