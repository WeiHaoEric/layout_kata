# W1 - Pixel Perfect kata
- created: 2021.07.03
- Eric-小偉哥
---
## Intro
- This is 1st challenge for `2021網頁切版直播班`. I'll do more than 5 practices to improve my emmet performance.

## Kata Time
|   week   |   time   |   remark |
| -------- | -------- | -------- |
| 1     |      |      |
| 2     |      |      |
| 3     |      |      |
| 4     |      |      |
| 5     |      |      |


---
## Useful Tools
#### Fake Img
- set this src URL to get resized-image`<img src="https://fakeimg.pl/250x100/">`



## Target Emmet Cmd
- Just organize some good emmet cmds to improve I finish this kata.
### Syntax


---
### HTML
#### Child: >
`nav>ul>li`
```html=
<nav>
    <ul>
        <li></li>
    </ul>
</nav>
```

#### Grouping: ()
`div>(header>ul>li*2>a)+footer>p`
```html=
<div>
    <header>
        <ul>
            <li><a href=""></a></li>
            <li><a href=""></a></li>
        </ul>
    </header>
    <footer>
        <p></p>
    </footer>
</div>
```

#### Text: {}
- `a{Click me}`
```html=
<a href="">Click me</a>
```
- `p>{Click }+a{here}+{ to continue}`
```html=
<p>Click <a href="">here</a> to continue</p>
```

#### image
- `img:srcset, img:s`=> `<img srcset="" src="" alt="" />`
- `img:sizes, img:z` => `<img sizes="" srcset="" src="" alt="" />`
---
### CSS
#### flex
- `d:f`=> `display:flex`
- `jc` => `justify-content:_;`;
- `jc:c`=> `justify-content:center;`;
- `jc:fe` => `justify-content:flex-end;`
- `jc:fs` => `justify-content:flex-start;`
- `jc:sa` => `justify-content:space-around;`
- `jc:sb` => `justify-content:space-between;`

#### margin
- `m`  => `margin:;`
- `m:a ` => `margin:auto;`
- `mt  ` => `margin-top:;`
- `mt:a` => `margin-top:auto;`
- `mr  ` => `margin-right:;`
- `mr:a` => `margin-right:auto;`
- `mb  ` => `margin-bottom:;`
- `mb:a` => `margin-bottom:auto;`
- `ml  ` => `margin-left:;`
- `ml:a` => `margin-left:auto;`


#### padding
- `p ` => `padding:;`
- `pt` => `padding-top:;`
- `pr` => `padding-right:;`
- `pb` => `padding-bottom:;`
- `pl` => `padding-left:;`
---

