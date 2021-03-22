# [Codevision](https://github.com/DiscordAddons/Codevision) - Clearvision Codeblock Theme
A codeblock theme that changes the appearance of Discord's standard codeblocks using colors similar to [Clearvision](https://github.com/ClearVision/ClearVision-v6)'s colors and background image with addition colors of course.

# Picture
![image](https://user-images.githubusercontent.com/72931279/112063349-a86b5280-8b37-11eb-9539-e07d49da3902.png)

# Code
```css
.markup-2BOw-j code {
    background: url(https://clearvision.gitlab.io/images/sapphire.jpg);
    background-size: cover;
    border: 1px solid midnightblue;
}
.hljs-addition, .hljs-keyword, .hljs-selector-tag {
    background: linear-gradient(0deg, navy, lightskyblue, moccasin);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
}
.hljs-doctag, .hljs-literal, .hljs-meta .hljs-meta-string, .hljs-number, .hljs-regexp, .hljs-string {
    background: linear-gradient(0deg, lightskyblue, sandybrown, moccasin);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
}
.hljs-attr, .hljs-attribute, .hljs-class .hljs-title, .hljs-template-variable, .hljs-type, .hljs-variable {
    background: linear-gradient(0deg, sandybrown, moccasin);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
}
.hljs-name, .hljs-section, .hljs-selector-class, .hljs-selector-id, .hljs-title {
    background: linear-gradient(360deg, moccasin, pink, violet, rebeccapurple, purple);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
}
.hljs-built_in, .hljs-deletion {
    background: linear-gradient(90deg, white, slateblue);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
}
```
