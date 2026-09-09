# Installing Webfonts
Follow these simple Steps.

## 1.
Put `quicksand/` Folder into a Folder called `fonts/`.

## 2.
Put `quicksand.css` into your `css/` Folder.

## 3. (Optional)
You may adapt the `url('path')` in `quicksand.css` depends on your Website Filesystem.

## 4.
Import `quicksand.css` at the top of you main Stylesheet.

```
@import url('quicksand.css');
```

## 5.
You are now ready to use the following Rule in your CSS to specify the Font Style:
```
font-family: Quicksand-Variable;

```
## 6. (Optional)
Use `font-variation-settings` rule to controll axes of variable fonts:
wght 300.0

Available axes:
'wght' (range from 300.0 to 700.0

