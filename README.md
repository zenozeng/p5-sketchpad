# p5-sketchpad

普通人的IDE。

Web based IDE for p5.js

Easy to use for designers, teaching.

## Features

### Basic

- Offline 可用性

- Auto completion for standard JavaScript and p5.js

- JSHint / JSLint

- Syntax Highlight

### Import and Export

- Templates for new project

- Drag files in

- IndexedDB / LocalStorage based session

- Gif / PDF export

- Share current project with a link

    用于 demo，设计师会非常常用这个

### Live Preview

- Color Picker

- Live preview for current project

    很多人最初是有兴趣的，但是编程一开始的没有反馈会给他们带来挫败的感觉。
    所以一个即时的反馈

- Interactive documentation for current function and current params

    [此处应有图解释]

- 色彩自动高亮 (like Emacs's rainbow mode)

    [此处应有 Emacs 截图]

## FAQ

### Why browser based?

因为就我目前的观察，很多人会在下载 IDE 和安装使用他们的时候就感到挫败。
而且在浏览器还有个好处就是甚至可以在 ipad 上来使用它，而且更加易于分享。

## About Me

I am a junior student of Biosystems Engineering, Zhejiang University.
And I have 3 years of web development experience.
And I am a heavy Emacs user, I wrote some plugins for Emacs:
- yafolding.el (folding plugin)
- css-eldoc (CSS doc plugin)
- php-eldoc (PHP doc plugin)

I love coding very much and am very interested in developing an IDE.
My girl friend is a designer and wants to learn some programming for Data Visualization.
I want to teach her p5.js later this summer vacation and I want to build a easy-to-use IDE for her.

My resume: http://resume.zenozeng.com/english/

My GitHub: https://github.com/zenozeng

## API

### Dragging folder

- [mozGetDataAt](http://stackoverflow.com/questions/11620939/is-there-a-mozilla-equivalent-to-webkitgetasentry)

- webkitGetAsEntry
