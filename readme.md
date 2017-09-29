# Programming 001

## Learning Objectives
* Define programming and explain what a programming language is.
* Look at a program and describe what it is doing.
* Write your first program!

## What is programming?
You probably interact with computers on a daily basis, but lets define concretely what we mean when we talk about computers in relation to programming. A computer, at its root, is a machine that processes and stores information. 

Programming is telling the computer how to ingest, process, and then store that data. When someone writes a program, that person is giving the computer a set of commands that it must follow. 

When we write programs, we are writing instructions that the computer will follow. Computers are very literal -- they will take our instructions and follow them exactly, but we must lay them out in a very detailed way so that they understand us.

Programming, at its core, is taking a big problem and breaking it into smaller and smaller problems until they  are small enough that we can tell the computer to solve that problem.

## Where can you see programs in use?
Anywhere! From your operating system on your computer through complex websites, all are written using code! Older (and newer!) cell phones, fancy coffee machines, self driving cars, and most TVs use code to run in addition to your desktop or laptop computer.

## What are programming languages?
Computers can't understand natural language by default, though they are getting closer and closer to being able to!

At their root, computers run on a series of microscopic on and off switches, and when we write code we are toggling them on and off -- just like a light switch! Computers use a numerical system called binary to use these on and off switches. Binary is a numerical system comprised of 1s and 0s that is similar to our Arabic numeral system which uses 0-9.

Thankfully, a lot of really smart people before our time thought of a way that we can talk to our computers without zeros and ones. Instead, we use programming languages which can be interpreted by our computer, similar to how language interpreters can translate Spanish to English or even English to sign language. These look a lot more like English than binary, but they still have a lot more symbols and fewer ways of doing things than natural language. 

There are **tons** of programming languages out there, similar to how there are lots of languages spoken around the world. Some, like Assembly, C, or Bash are very low level and don't really resemble how we speak. Others, like Python and Ruby closely resemble human language. There are trade offs between performance and ease of use, but when you learn how to code I would highly recommend one that is closer to normal language!

## Putting it together: code in practice

Let's look at a program in practice versus the code for it! I wrote a simple version of the Simon game you may have played. The game is hosted here: https://aspittel.github.io/simon/. Take some time and look at the code on this repository (or folder of code): https://github.com/aspittel/simon. The code is in the `index.html`, `script.js`, and `style.css`. Let's walk through the code together.

The `index.html` contains the basic elements that make up the visual of the web page. For example, the `div` elements make up the squares on the Simon board.

The `style.css` contains styling for the app -- the color `background-color` codes tell the browser which color the squares should be. 

The `script.js` contains the actual game logic and its interactivity. It utilizes an algorithm that makes the code faster and simpler instead of coding out every possible outcome.

## Your turn: Writing your first program!

Let's go to https://codepen.io/pen/. CodePen is a website that allows us to write code in the browser without installing everything! Once you write code that you want to deploy, or put on your own website, you will want to write the code elsewhere, but this is a great sandbox for practicing! 

In the `HTML` window, write:
```html
<h1>Hello, World!</h1>
```
Whenever programmers learn a new programming language or technology, the tradition is to start with a Hello World! Congrats on your first program! You can see it render on the webpage below the code!

Try changing the h1's to `<p>` or `<h2>`. What happens? How about changing the inside of the tags to say `Hello, <your name here>!`? 

Let's try styling our component now! In the `css` tab type out:
```css
h1 {
  color: red;
}
```
What happens? Try changing the color!

Now, in the `js` tab, try writing:
```js
alert('Hello, world!')
```
Congrats! You just wrote your second "Hello, world!" app!

## Questions

## Next Steps
- [CodeAcademy](https://www.codecademy.com/)
    * I would recommend HTML, CSS, Python, or Ruby here!
_ [Django Girls](https://www.gitbook.com/book/djangogirls/djangogirls-tutorial)
- [Khan Academy](https://www.khanacademy.org/computing/computer-programming)

## Reach Out!
- [Github](https://github.com/aspittel)
- [Twitter](https://twitter.com/ASpittel)
- https://aspittel.github.io