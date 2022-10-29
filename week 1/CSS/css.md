# CSS (Cascading Style Sheet)

CSS digunakan untuk menstyling HTML.

## Struktur CSS

```css
.elementHTML {
  property: "value";
}
```

## Cara Menyisipkan CSS

1. Inline Style -> menambahkan CSS pada attribute element HTML

```html
<p style="color: coral; font-size: 36px;">Ini adalah paragraf</p>
```

2. Internal CSS using <_style_><_/style_> tag

<_style_><_/style_> disisipkan pada tag <_head_>.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <style>
      .p {
        color: coral;
        font-size: 36px;
      }
    </style>
  </head>
  <body>
    <p>Ini adalah paragraf</p>
  </body>
</html>
```

3. External CSS -> menyisipkan link halaman CSS terpisah pada tag <_head_>

Jika kita membutuhkan banyak code pada CSS, direkomendasikan untuk memisahkan code CSS di file tersendiri (extension .css) dan terpisah dari file HTML.
