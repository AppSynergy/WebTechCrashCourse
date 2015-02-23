
# Web Technology - A Crash Course

## Mission \#1 - Get a Github account

This is an interactive repository. The idea is that multiple people can collaborate on a collective code-base, with a full shared history.

To put it another way, the contents of this repository are **simply a folder**, which you can download to your computer. You can then work on it, and send the changes back to the **master copy** (here!).

So, create an account for Github. Find out how to **fork** this repository. Do that, and you've got your own copy.

## Mission \#2 - Markdown - web copy writing made easy

- Using Github, look at the source of this file (`README.md`)
- Note the special characters and what they represent (such as this bullet-point list for example, or the bold phrases above).
- What's the difference between a single `#`, a double `#` and a `#` preceeded by a `\`? You can either look it up or work it out logically. Or ask, if you're stuck! (that goes for all points)
- What would the html equivilent of each of these be? One example: a `**` in Markdown makes things bold, which is the equivent of the `<strong>` tag.
- Give up? How about using the inspector, or developer's console in your browser? You should be able to point at an element or sentence on the page, right click, inspect element, and see the html statements behind it. Ask if you're not sure how to get this feature, it's very useful and worth experimenting with. I recommend Chrome, followed by Firefox/Safari as the best browsers for development.

## Mission \#3 - Software

Here's some software it's worth installing and experimenting with.

You should be able to Google your way to most of them, ask if you need specific instructions, or you run into problems!

### A Decent Text Editor

To make your coding less painful, you want a decent editor. Features to look for:

- Syntax highlighting - i.e. "coloring in" your code. Black and white is boring. More colors makes it easier to learn the associations and meanings behind various things, and it helps you spot mistakes.
- Code awareness - i.e. the editor knows the language you're using. It can then point out mistakes for you, or remind you of syntax.

I use **Komodo Edit**, which I can recommend. **Notepad++** is another (more lightweight). 

Ok, so got one?  Paste the following into it, and save it as

```js
var first_name = "John";
var last_name = "Smith";
var age = 6*7; // 42!
// What's the full name?
function concat_name(name) {
  return name[0]+ " " + name[1];
}
var stdOut = concat_name([first_name, last_name]);
```

And look at the pretty colors! For bonus points, what is the value of `stdOut` and how does it work? (it's an example of syntaxes and highlighting, and not how you'd go about this normally!)

### Git

**Github** is a git server. To interact with it, you'll need a **git client**.

There's graphical clients available, but to understand the basics better, I'd suggest the command-line binary. **Warning! Kinda advanced.. but worth it IMHO. Ask for help here!**

If you get it working, you should be able to clone this repository, and get a local copy on your machine.

### A Web Server

**Apache2** is one of the most popular web servers, and doesn't require much configuration out of the box. It should give you a web root (usually `/var/www`) that you can drop files (or entire repositories!) into and serve them to yourself. (e.g. http://localhost/name-of-file)
