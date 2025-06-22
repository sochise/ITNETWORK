# Poznámky



## Tag vs. element
![tag_element](image.png)

```html
<p>První odstavec</p>
```

## Vložení obrázku
```html
<img>
<img src="images/IMG_6237.jpg" alt="programator">
```

## Napojení CSS stylu na stránku
- vytvořím styl.css a v něm popíšeme styly.

```html
<head>
    <meta charset="utf-8" />
    <link rel="stylesheet" href="styl.css" type="text/css" />
```

- styl se pak tvoří následně

```css
h1, h2 {
    text-align: center;
}
```