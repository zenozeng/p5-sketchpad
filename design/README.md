# IDE Design

This is a browser based p5.js IDE designed to
make coding accessible for artists, designers, educators, and beginners.

## Overview

Here is an overview of the IDE for introducing some core concepts later.
Note that the UI will be redesigned when the project starts.

![Overview](overview.png)

## Features

### Basic

- Offline availability

    Using Appcache, Local Storage and IndexedDB.

- JSHint / JSLint

- Syntax Highlight

- Auto completion for standard JavaScript and p5.js.

    A completion menu with icon, syntax and category for each function.

    ![Auto completion](auto-completion.png)

### Import and Export

- Templates for new project

- Drag files to current project

- IndexedDB / LocalStorage based session

- Gif / PDF export

### Live Preview and Documentation

- Live preview for current project

    Render result of current project using iframe for unblocking experience.

- Interactive documentation for current function and current parameters

    Simple preview for the whole project is not enough.
    When writing the parameters of a function,
    it's better to show current result of current function.

    Because the result of current function may not shown until some events happens (onclick for example)
    or frameCount greater than certain value.

    And our target users may not have direct feelings about numbers,
    but with an interactive documentation they can easily adjust parameters.

    ![Interactive Documentation](interactive-documentation.png)

    ![Interactive Documentation - Stroke Width](interactive-documentation-2.png)

- Highlight colors (like Emacs's rainbow mode)

    Expressions like `background(255, 255, 255)` will be highlighted based on its parameters.

    ![Rainbow Mode](rainbow.png)

- Color Picker

    ![Color Picker](color-picker.png)

    Artists and designers may not have direct feeling for RGB.
    A color picker may be better for them.
    When click on expressions like `background(255, 255, 255)`,
    a color picker will be displayed to help them choose the desired color.

- Builtin Getting Started

- Builtin Reference (with interactive search)

- Builtin FAQ

### Presentation and Social

- Presentation Mode

    Use Full Screen API

- Share current project with a link (Node.js)

    Upload current project to server and generate a link for easy distribution.

## FAQ

### Why browser based IDE?

Many people feel frustrated when downloading and installing IDE.
A web browser based IDE is much easy to use, simply open tab.
And we can use browser based IDE in iPad or Android tablet.
Also, it's easy to share your project with your friends if it's in browser.

### Why yet another browser based IDE?

Although there are many browser based IDEs,
this one is designed for p5.js and want to make coding accessible for artists, designers, educators, and beginners.

### Will this IDE add support for git and Emacs/VIM keybinding?

Maybe later. For now, the main target is to provide a easy to use environment for ordinary people.

### Tech stacks?

- React / Vue.js

- Browserify and JavaScript (maybe some es6)

- gulp

- Node.js / io.js

(Maybe change later)

### About Me

I am a junior student of Biosystems Engineering, Zhejiang University.
And I have 3 years of web development experience (both frontend and backend).
By the way, I am a heavy Emacs user, I wrote some plugins for Emacs:

- yafolding.el (folding plugin)
- css-eldoc (CSS doc plugin)
- php-eldoc (PHP doc plugin)

I love coding very much and I am very interested in developing an IDE.
My girl friend is a designer and wants to learn some programming skills for Data Visualization.
I want to teach her p5.js later this summer vacation and I want to build a easy-to-use IDE for her.

My resume: https://zenozeng.github.io/resume/english/

My GitHub: https://github.com/zenozeng

My Email: zenoofzeng@gmail.com

## Special Thanks (alphabetical ordered)

Special thanks to the following people for give me suggestions to this project.

- [Chiyo](http://chiyo.me) (Designer)

- [DreaminginCodeZH](https://github.com/DreaminginCodeZH) (Android Developer)

- [Senorsen](https://github.com/Senorsen) (devOps)

## Related API and Libraries

### Dragging folder

- [mozGetDataAt](http://stackoverflow.com/questions/11620939/is-there-a-mozilla-equivalent-to-webkitgetasentry)

- webkitGetAsEntry

## Reference

- [The Processing Environment](https://processing.org/reference/environment/)

- [Getting Started](https://processing.org/tutorials/gettingstarted/)
