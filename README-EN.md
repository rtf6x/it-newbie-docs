How to Enter the IT Field?

My name is Alexander, and I have around 12 years of experience working in various IT companies. I've decided to write this text to assist beginners in the field. I hope it will be helpful.

# 1. Why Are You Here?

I entered the IT field once because it seemed interesting and was something I started to excel at. Admittedly, I wanted to become a system administrator back then. Many people nowadays pursue IT for the big money, but at the beginning of your career, no one will pay a newcomer a hefty salary.

Don't believe those who say, "Learn React and you'll immediately jump to a $250k per month salary."

What you need to understand from the very beginning:

- No one will pay you a lot right away. You need to gain experience and start with some salary.
- Ahead of you lies a long journey full of victories and setbacks (I envy you).
- Logic, critical thinking, and abstract thinking are three crucial factors without which the IT field will be very challenging.

In my view, qualities that assist in problem-solving are extremely important for a programmer. After all, that's essentially what a programmer does—solves tasks and problems.

Without abstract thinking, you won't be able to conceptualize a problem, wrap your head around it, twist it inside your mind, and come up with a solution. Similarly, abstract thinking helps you approach a problem from a different angle.

Without critical thinking, you won't be able to ask important questions, question a certain solution (whether your own or not), and consider that everything might not be as respected colleagues claim.

Yes, I might sound like a grandmother who calls someone a drug addict and insists that you won't become a programmer without mathematics. But this is my opinion, my path, and with the help of these (and other tools we'll discuss later), I solve problems.

On the other hand, if you choose a path like testing and get lucky with the start of your career, you might immediately land a salary of around $100k. But if you're that lucky, you might as well go to a casino and not waste your time on IT.

So, if you're still interested, let's continue.

# 2. Choosing a Path

Which type of programming to choose: mobile, frontend, backend, games... This is for you to decide. I'll just share my opinion on these tracks.

## 2.1. Backend

Entering pure backend development might be a consideration if you have experience as a webmaster. But then, what are you doing here? :) It's generally not advisable to choose backend at the beginning of your career for a few reasons:

- You need an understanding of databases.
- You need to grasp the principles of network operations.
- You don't "see" the results of your work.
- It's simply more complex.
- Managers usually understand you less than frontend developers (communicating thoughts is harder).

There are pros as well:

- You don't have a menagerie of devices and browsers for which your code must work flawlessly.
- Usually, the backend determines how new functionality will work on the backend.
- Managers usually understand you less than frontend developers (you can walk around looking important).

2.2. Mobile Development

Venturing into mobile development is a viable option and not significantly more complex than frontend development. There is a specific aspect to it, and if you delve into it, mobile development might even seem simpler than frontend.

Downsides include:

- You need to delve into pure mobile languages: Kotlin for Android or Swift for iOS (though I've heard about backend Swift, but that's for enthusiasts. Similarly, there's a similar opinion about Node.js).
- You need to go through trials and tribulations before anything starts to make sense.

2.3. Game Development

Starting your career on this path isn't recommended. Game studios are few. If you're interested, consider studying this path as a pet project; that would make more sense in my opinion. However, if you're pursuing serious game development, you're unlikely to achieve much without these elements:

- Understanding shaders.
- 3D modeling.
- Proficiency in tools (game engines, IDEs, Blender).
- Knowledge of algorithms and algebra (pathfinding, graphic optimization).

On the flip side, there's quite a bit of information available online about Unity.

2.4. Full Stack

There's also "full stack," which means a person is skilled in both frontend and backend, but this isn't an option for beginners.

2.5. Frontend

Saved the best for last. Frontend is a viable path for beginners. Furthermore, frontend developers are even paid more (though I can't understand why the hell).

There are downsides:

- A diverse range of browsers (though this is resolved with PostCSS and Babel).
- High competition in the market.

There are pros as well:

- The results of your work are visual.
- Tasks are clearer than on other paths (creating buttons, for instance).

Let's dive into frontend for the discussion.

## 3. What a Frontend Developer Needs to Know

A frontend developer needs to know three fundamental languages:

- `HTML`
- `CSS`
- `JavaScript` (don't confuse it with `Java`, that's an entirely different story)

### 3.1. HTML

So, what is `HTML`? It stands for Hyper-Text Markup Language.
It's a language of hypertext markup.
It's the language from which a browser constructs components on a webpage.
Buttons, menus, text—these are all made using `HTML`.

Here's what it looks like:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <title>RootFox</title>
    <link rel="stylesheet" href="rtf6x/index.css">
</head>
<body>
<main class="content">
    <h1>Hello World!</h1>
</main>
</body>
</html>
```

How to learn HTML:

- Read [MDN's HTML documentation](https://developer.mozilla.org/ru/docs/Web/HTML/Element).
- Write something in `HTML`.
- Validate that something using the [W3C Validator](https://validator.w3.org/).
- Discard everything.
- Write it again.
- Repeat this process 420 times.

### 3.2. CSS

What is `CSS`? Cascade Style Sheets—cascading style sheets. 
It's also a language that is used to define styles for elements in `HTML`.
For instance, in the above example, there's an H1 element, and you want to make the text inside it blue.
You achieve this like so:

```css
h1 {
  color: #0000ff;
}
```

Or like this (though this is less recommended):

```css
h1 {
  color: blue;
}
```

CSS is linked to `HTML` like this:

```html
<head>
    <link rel="stylesheet" href="https://rootfox.cc/rtf6x/index.css">
    <link rel="stylesheet" href="rtf6x/index.css">
    <link rel="stylesheet" href="/rtf6x/index.css">
</head>
```

Here, we see three different ways to link the same file:

- The first file is linked using the complete URL (the browser recognizes this with the double slash (https://)).
- The second is linked relative to the URL in the browser's address bar (from the last "/"). For instance, if the page is open at `https://rootfox.cc/funny/mad-news/`, in this case, the path to the second file will be: `https://rootfox.cc/funny/mad-news/rtf6x/index.css`.
- The third is linked relative to the website's root (/), regardless of how nested the page is. Whether it's the main page or `/funny/mad-news/`, everything after the root slash will be discarded: `https://rootfox.cc/rtf6x/index.css`.

How to learn CSS:

- Read [MDN's CSS documentation](https://developer.mozilla.org/ru/docs/Web/CSS).
- Write something in `CSS`.
- Check your layout in a different browser.
- Realize that something isn't working as you expected.
- Read about the styles you're using on [CanIUse](https://caniuse.com/css3-colors).
- Discard everything.
- Write it again.
- Repeat this process 15 times.
- ...
- Finally read about `PostCSS`.
- Not understand anything.
- Repeat this process 4 times.
- ...
- Finally understand how to use `PostCSS`.
- Be glad that everything works in a different browser, hoping it dies.

#### Important:
In CSS, it's crucial to understand selector specificity theory. You can read about it here:
- [ru.hexlet.io](https://ru.hexlet.io/courses/layout-designer-basics/lessons/css-cascade/theory_unit)
- [doka.guide](https://doka.guide/css/specificity/)
- [MDN](https://developer.mozilla.org/ru/docs/Web/CSS/Specificity)

#### Media Queries
In `CSS`, there are also `Media Queries`.
They're used to adjust the layout for specific screens or devices.
For instance, if you want the text color to be red when the screen width is less than 800 pixels (commonly, pixels are used in layout, but other options exist: em, rem, %, vw, vh...):

```css
@media (max-width: 800px) {
  h1 {
    color: #ff0000;
  }
}
```

#### SCSS, SASS, LESS
There's also `SCSS`, `SASS`, `LESS`, and `Stylus`! If you're proficient in `CSS`, dealing with these fellows won't be much of a challenge. Primarily, they add nested elements and inline functions. And variables, for example. Here's how it looks in SCSS:

```scss
$background: #2d2d2d;

@mixin clearfix() {
  &:after {
    content: "";
    display: table;
    clear: both;
  }
}

@mixin border_radius($radius: 5px) {
  -webkit-border-radius: $radius;
  -moz-border-radius: $radius;
  -ms-border-radius: $radius;
  border-radius: $radius;
}

@mixin boxed() {
  padding: 5px 10px;
  border: 1px solid darken($link_color, 5);
  background: $box_background;
  text-align: center;
}

.wrapper {
  background: $background;
  padding: 0;
  margin: 0 auto;

  .header {
    @include clearfix();
    padding: 0 0 20px;
    
    .header-logo {
      @include boxed();
      float: left;
    }
    
    .header-contacts {
      @include boxed();
      @include border_radius(10px);
      float: right;
    }
  }
}
```

Once, I created a few pages for comparison (to personally understand the differences):

- [SCSS](https://rootfox.cc/tests/css/scss/)
- [SASS](https://rootfox.cc/tests/css/sass/)
- [LESS](https://rootfox.cc/tests/css/less/)

#### What Else about CSS?
What else is worth studying in the context of `CSS`:
- Selector priorities in `CSS`
- Blocks - inlines
- Pseudo-elements and pseudo-classes
- `BEM`
- `CSS` preprocessors (mentioned above: `LESS`/`SASS`)

### 3.3. JavaScript

JavaScript (JS) is the foundational language for a frontend developer. If you're proficient in HTML and CSS, it doesn't grant you the title of a frontend developer. For that, you need JavaScript.

#### What is JavaScript?

JavaScript is a scripting language executed in a browser (or in the Node.js environment, which has its own intricacies, but the V8 engine is used everywhere).

Script files, like CSS files, are linked in HTML like this:
```html
<script type="text/javascript" src="test.js"></script>
```

The script file itself might look something like this:
```javascript
var something = 'test';
console.log('something', something);
alert('This is not appropriate!');
```

#### What Can You Do with JavaScript?

- You can attach events to elements in the DOM (HTML).
- You can change or add elements.
- You can modify classes and other attributes of elements.
- You can call specific functions.
- You can define variables and store important (and not-so-important) information in them.
- You can make requests to external sources (APIs).

#### What's Important to Know in JavaScript from the Start?

- `window`
- Data types
- Methods of variable declaration
- Methods and attributes of variable types
- Concurrency (executing multiple operations in parallel)

#### 3.3.1. Window

`window` is the global object in a browser's page (in Node.js environment, it doesn't exist, and instead, `global` is used). Essentially, any variable declared in the global context becomes a part of `window`. This means you can access such a variable directly or through `window`.

For example:
```javascript
var something = 'something';
console.log('something', something); // "something"
console.log('window.something', window.something); // "something"
```

There are other global objects like `document`, `screen`, `navigator`, etc. You might want to explore what they represent or read about them on [w3c](https://www.w3schools.com/js/js_window.asp).

From `navigator`, you can extract the user's language, for instance:
```javascript
const lang = navigator.language || navigator.userLanguage || 'en';
```

`document` is used to get HTML elements, add new ones, and create events:
```javascript
document.addEventListener('DOMContentLoaded', function (event) {
  document.querySelector('a').addEventListener('click', function (e) {
    alert('CLICK!');
    document.querySelector('p').innerText = 'CLICK!';
    return false;
  });
  
  const p = document.createElement("p");
  p.innerHTML = "Lorem ipsum";
  p.className = "someClass";
  p.setAttribute("id", "someId");
  document.body.appendChild(p);
});
```

#### 3.3.2. Data Types

You can read about data types [here](https://developer.mozilla.org/ru/docs/Web/JavaScript/Data_structures).

It's important to note that primitives are passed to functions as values, while "complex" ones are passed as references. For example:

```javascript
const someObject = { a: 1, b: 2 };
const someString = 'test';

const someFunc = (obj, str) => {
  obj.a = 2;
  str = 'hello?';
}

someFunc(someObject, someString);

console.log(someObject); // { a: 2, b: 2 }
console.log(someString); // 'test'
```

So, what happened?
1. The object passed into the function `someFunc` by reference was modified. But isn't it a constant? No, the constant is the reference to the object itself, but its internals can be changed.
2. The string passed by value was only changed within the function and didn't change outside of it.

#### 3.3.3. Methods of Variable Declaration

There are 3 methods:
- `var something = 'something';`
- `const something = 'something';`
- `let something = 'something';`

To understand the issue better, read about [closures](https://developer.mozilla.org/ru/docs/Web/JavaScript/Closures).

`var` is an outdated method, yet still functional and can be used under certain conditions. Its peculiarity is that a declaration with `var` is hoisted higher than closures (if the closure is in the same context). For example:

```javascript
for (var i = 0; i < 1; i++) {
  var myVar = 'bloop';
}

console.log(myVar); // "bloop"
```

The variable declared with `var` doesn't hoist out of the function because each function has its own local context.

`let` and `const` don't hoist out of their code blocks (closures). Also, there's a difference between them: `const` is a constant (you can't change

 it).

```javascript
for (var i = 0; i < 1; i++) {
  const myVar = 'bloop';
}

console.log(myVar); // Error: myVar is undefined
```

It's advised to always use `const` if you don't intend to change the variable. It's both correct and conventional. If you're dealing with non-primitive data types, declare them as constants right away, unless you plan to change the reference itself.

```javascript
const myVar = 'bloop'; // Fine
let myVar2 = 'bloop'; // Variable doesn't change, should be const
let myVar3 = { a: 1 }; // Reference doesn't change, should be const
const myVar4 = { a: 1 }; // Reference changes, should be let
const myVar5 = { a: 1 }; // Fine

myVar5.b = 2; // myVar5 = { a: 1, b: 2 }
myVar4 = { b: 1 }; // TypeError: invalid assignment to const
```

#### 3.3.4. Methods and Attributes of Variable Types

Newcomers often struggle to understand what can be done with variables. It's important to learn these tools and try to utilize them.

For example, arrays have the following methods and attributes:
- `length` - the number of elements in an array.
- `map()` - transforms an array into a slightly different one.
- `forEach()` - similar to `map`, but iterates over the array (faster, as it doesn't create a new array).
- `reduce()` - a powerful tool that can be complex for beginners. It can be used to calculate various aggregates, not just the sum of animal paws. Also useful in the zoo...
- `filter()` - creates a new array with elements that satisfy certain conditions.
- `find()` - finds and returns the first element of an array that satisfies a condition.
- `reverse()` - reverses the array.
- `indexOf()` - helps determine if a specific element is in the array.
- `slice()` - creates a new array from elements between index X and index Y.
- `splice()` - removes elements from the array between index X and index Y and returns them.
- `pop()` - removes an element from the end of the array and returns it.
- `shift()` - removes an element from the beginning of the array and returns it.
- `push()` - adds an element to the end of the array.
- `unshift()` - adds an element to the beginning of the array.
- [And more](https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Global_Objects/Array)

Strings have a few interesting methods and attributes:
- You can partially treat strings as arrays.
- `length` - like for arrays.
- `toUpperCase()` - capitalizes a string (dog => DOG).
- `toLowerCase()` - lowercases a string (DOG => dog).
- `replace()` - replaces a part of the string with something else.
- `split()` - splits a string into an array of substrings (opposite: `Array.join()`).
- `indexOf()` - helps determine if specific characters are in the string.
- `substring()` - extracts a part of the string between characters X and Y.
- `trim()` - removes whitespace from the beginning and end of the string.
- [And more](https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Global_Objects/String)

Objects have a couple of important functions:
- `keys()` - returns an array of an object's keys (properties).
- `values()` - returns an array of an object's values (the object without keys).
- [And more](https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Global_Objects/Object)

#### 3.3.5. Concurrency (Executing Multiple Operations in Parallel)

It's important to understand that JavaScript is a single-threaded language (with some workarounds for concurrency).

In Node.js, concurrency is achieved by running multiple processes (if you're interested, look into the cluster mode).

However, certain tasks can run concurrently due to being processed differently by various engine subsystems.

I recommend getting acquainted with the Event Loop documentation (but don't get too deep into it, as it's more advanced):

- [Event Loop](https://developer.mozilla.org/ru/docs/Web/JavaScript/EventLoop)
- [YouTube (5m)](https://www.youtube.com/watch?v=377qAu37OTE)
- [YouTube (18m)](https://www.youtube.com/watch?v=vIZs5tH-HGQ)

### 3.4. Frameworks

### 4. Starting Point

A gentleman's toolkit for a developer:

- A Google account (often needed for accessing various services).
- An Integrated Development Environment (IDE), a code editor.
- `Node.js` (whether for frontend or backend development) (needed for `NPM`).
- `Git`.
- Browsers for testing. At this stage, you might not need to worry too much, but increasingly there are websites that don't work in my good old Firefox, which can be quite frustrating.
    - An alternative is BrowserStack. It lets you view websites (including local ones with a plugin) on cloud-based virtual machines.

What companies use:

- Task management is often done in `Jira` or `Trello` (but there are plenty of alternatives). I suggest giving `Trello` a try, as it's free.
- Voice communication usually happens via `Google Hangouts`, `Zoom`, `Slack`, or `Discord`.
- Text communication often happens in `Slack` or `Discord` (I personally like Discord, but it might not be the best fit for more serious organizations).
- Documentation is usually kept in `Confluence` or `Notion`. Sometimes, documentation is kept in `Google Docs` / `Google Drive`, but it's not the most convenient option.
- Code is typically stored in `GitHub` / `GitLab` / `BitBucket`. Often, these are self-hosted solutions, meaning companies run their own instances of, for example, `GitLab`.

### 4.1. IDE

I use `JetBrains` products. I like `WebStorm` and don't want to give it up—I'm used to it. However, it's a paid option, and at the beginning of your journey, you might not be paid yet to afford such a useful tool.

Therefore, I recommend `Visual Studio Code` ([VSCode](https://code.visualstudio.com/)). It's quite good, especially when you install the right plugins. It's now the standard for beginners, and many senior developers use it too.

You can choose what suits you best, but it's important to understand that using the wrong tool might lead to unpredictable results.

### 4.2. NPM

NPM stands for Node Package Manager. It's like a package manager for packages—a package of packages. Kind of like Bower (which is outdated). The idea is that in every Node.js application (including frontend), there's a `package.json` file describing the NPM packages.

So that every developer doesn't need to struggle with finding the right packages for the application, they're all listed in this file. You just run `npm install` in the project folder, and everything you need gets installed in the `node_modules` folder.

Also, `package.json` is the second file a developer looks at after `readme.md` when opening a new project. It contains scripts for running tasks and a list of packages (which most people just glance over).

#### Where to download NPM / Node.js: [nodejs.org](https://nodejs.org/en/download/)

You should download the LTS (Long Term Support) version. The Current version has new features and new bugs. For development, LTS is the way to go.

You can check when a version becomes LTS [here](https://nodejs.org/en/about/releases/).

#### Quick List of NPM Commands:

This command creates a `package.json` in the current directory (interactively - it will ask questions, request your passport number, grant you a credit...):
```shell
npm init
```

This command installs packages listed in the `package.json`:
```shell
npm install
```

This command installs the "moment" package:
```shell
npm install moment
```

This command installs the "moment" package and adds it to the `dependencies` block in `package.json`:
```shell
npm install moment --save
```

This command installs the "moment" package and adds it to the `devDependencies` block in `package.json`:
```shell
npm install moment --save-dev
```

This command runs the `start` script from `package.json` (if it exists):
```shell
npm start
```

The same as the previous command (there's a shortcut only for `start`, other scripts need to be executed using `run`):
```shell
npm run start
```

#### Purpose of the devDependencies List:

If you are developing an NPM module that will be used in other projects, the `dependencies` section should only include packages necessary for your module's normal functioning. All development-related packages for this module (testers, linters, etc.) should go into `devDependencies`.

It's generally a good practice to separate `devDeps` from regular dependencies. However, at the initial stages, don't stress over it too much, as you'll already have a lot on your plate. Just remember that this explanation exists and come back to it when things calm down.

### 4.3. Git

Git is a version control system. GitHub, GitLab, BitBucket are specific instances of Git servers. Roughly speaking, Git is a repository for files that also keeps track of all changes (and records who made those changes). Git retains the entire history of your project until you decide to remove it.

Where to download Git: [git-scm.com](https://git-scm.com/downloads)

With Git, you can store both private (closed) repositories and public ones that anyone can access (like this repository where you're currently reading `readme.md`).

## 5. Front-End Development:

There are three types of layout techniques that I've encountered:
- Table-based (obsolete, but still used for email layouts)
- Block-based (also known as "div-based", still used but outdated)
- FlexBox (layout using flex containers)

### 5.1. Table-Based Layout

Table-based layout is how websites were built in the 90s and 2000s. While it's still functional, it's significantly outdated, and there's no need to learn it. Moreover, there's not much to learn there. The idea is to represent the entire webpage as a table.

You can divide the page into four sections:

- Header
- Left menu
- Content
- Footer

In tables, we create the header and footer as table rows (with `rowspan=2`), while the menu and content are separate table columns:

```html
<table>
  <tr>
    <td colspan="2">
      Header
    </td>
  </tr>
  <tr>
    <td>
      Left Menu
    </td>
    <td>
      Content
    </td>
  </tr>
  <tr>
    <td colspan="2">
      Footer
    </td>
  </tr>
</table>
```

Alternatively, you can nest another table within the middle row:

```html
<table>
  <tr>
    <td>
      Header
    </td>
  </tr>
  <tr>
    <td>
      <table>
        <td>
          Left Menu
        </td>
        <td>
          Content
        </td>
      </table>
    </td>
  </tr>
  <tr>
    <td>
      Footer
    </td>
  </tr>
</table>
```

### 5.2. Block-Based Layout

### 5.3. Flex Layout

Flex layout is a modern approach to web layout using the Flexbox model. It's designed to provide an efficient and predictable way to distribute space and align content. With Flexbox, you can create complex layouts with ease, making it a preferred choice for modern web development.

## 6. Applying Your Skills

Strive to write code more frequently. Just start doing things!

I recommend beginning with a pet project. It could be an idea you've taken from someone else's repository. Download it, install the packages, run it, make changes... Work with the code, brainstorm what can be improved, and then go ahead and implement those changes. Don't be afraid to make mistakes; in fact, deliberately make them! Break things and then fix them!

## 7. Best Practices

At the beginning of your journey, carefully validate your work. Strive to do things right and build your foundation on proper methods. This will benefit you in the long run.

Furthermore, continuously learn new approaches and methodologies. Select and discuss them, and aim to understand them deeply. In your first year, it's important to take a challenging path and cover as much ground as possible. Yes, it might feel overwhelming, but as the Germans say: "Quadratisch, Praktisch, Gut" (square, practical, good).

Moving forward:
- Regularly update your resume.
- Continuously improve your tools and skillset.
- Publish your pet projects on GitHub; they become a part of your portfolio.
- Get accustomed to using company tools like Git, Slack, Trello, etc. (or others depending on the company's choices).

There are a few additional points that can help you:

#### Search Methods

If your Google search isn't yielding results in Russian, try using English. English is essential for programmers since most documentation is written in it.

Also, avoid asking Google for advice or using unnecessary phrases like "Google, sweetheart, please tell me how to patch KDE on FreeBSD?"

You need to provide the search engine with keywords, and it will provide you with the most relevant answer:
"KDE FreeBSD patch" is all that matters from your initial query.

#### StackOverflow

There's a term called "StackOverflow developer" - a programmer who solves problems using StackOverflow.

But that's not the point now. The important thing is that this site contains a wealth of programming-related questions and answers. I strongly recommend making active use of it.

## 9. Entering the Job Market

Our little one has grown up... and saved China. (c) Mushu

At this stage, you can enter the job market and aim for a Junior Frontend Developer position. You'll face numerous rejections, be prepared for that and don't worry. If one company turns you down, others will too. The hundred-and-fiftieth will hire you.

The future is uncertain. It depends on the team you join. They will teach you the ropes, no doubt.

"They advised him to catch another fox, but he replied: Too much patience will be spent, not for the sake of catching, but for the sake of loving it."

Patience to you, young padawan. May the force be with you.

# Additional Information

## What to Learn Next?

- Promises
- REST
- [Localstorage, SessionStorage](https://learn.javascript.ru/localstorage)
- [Cookies](https://learn.javascript.ru/cookie)
- [Coding Style](https://learn.javascript.ru/coding-style)
- [ESLint](https://eslint.org/)
- EcmaScript Standards
- Debugging

- EventLoop
- Garbage Collector
- GraphQL
- WebSockets
- TypeScript
- TSLint
- Grunt / Gulp / WebPack / Rollup
- Node.js
- SSR
- Next.js (React) / Nuxt.js (Vue)
- Read Tech Blogs / Listen to Podcasts
- Attend Conferences
- Frontend Testing
- CI/CD Methods (how to test and deploy your code)
- Development Speed, Pomodoro Technique

## Principles

I recommend reading and studying principles and methodologies.

DRY - Don't Repeat Yourself.

This principle is about extracting repetitive code into a common container, be it a module, a helper function, or even a class - it's up to you.

KISS - Keep It Stupid Simple.

This principle encourages you to avoid overcomplicating things where it's not needed. Keep it simple. You could say it's the Occam's Razor of programming.

SOLID.

Some interviewers ask about SOLID principles. I'm almost certain they don't practice OOP extensively in frontend, but if they're asking, it must matter to them...

## Advice

### Advice #1

Never run `npm audit fix --force`!

### Advice #2

Always question the input variables. Check what's being passed to functions (and whether anything is being passed at all).

## Useful Links

### FontSquirrel
If you need to install a non-standard font on your website, the squirrel will help. Although it's worth searching for fonts on Google Fonts first:
- [Google Fonts](https://fonts.google.com/)
- [FontSquirrel](https://www.fontsquirrel.com/)

