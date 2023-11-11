# I made my own utility font!

## How does it look like?
<div align='center'> 
  <img src='https://i.imgur.com/yX6CWHP.png' alt='a cross with a cut' style='
  width: 200px;
  '/>
  <h5> I do not know how to import fonts into a readme so here, have an image. </h5>
</div>

## Why?
I was once looking for an x-like cross icon for my website and came across a good looking one, though I would have to mention its creator, I was not willing to do that, hence, I just create my own font with a nice x-like cross.
## Can I use it?
Yes, do whatever you want with it. I love free stuff.
## What does it do?
When using this font, all letters accept the small x will not show. the small x looks like a close button.
## How do I use it?

1. You have to download the font and place it into your project.

```
# for web development, always try to download the .woff and .woff2 files.
```

2. In your main css file, 'register' the font.

```css
@font-face {
  font-family: 'ArcadeFortune';
  src:  url('/public/ArcadeFortune-Regular.woff') format('woff'),
        url('/public/ArcadeFortune-Regular.woff2') format('woff2');
  font-weight: normal;
  font-style: normal;
}
```

3. then you can use this font just like any other fonts.

```css
.close-button {
  font-family: 'ArcadeFortune';
  user-select: none;
  /* ... */
}
```

```html
<div class='close-button'>x</div>
```

## How can I edit it?
1. Download a font editor, I use the 'High-Logic FontCreator'
2. Double click the .fcp file, there you have it.
3. Have fun.
## Is that it?
Maybe I will add more things, let me know if you want something.