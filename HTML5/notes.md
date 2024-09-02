## To add favicon
```html
<link> rel="icon" href="imglink" type="image/x-icon" </link>
```

## To link stylesheets
```html
<link> rel="stylesheet" href="link-to-stylesheet" type="text/css" </link>
```

## To create a horizontal line
```html
This is a horizontal rule
<hr>
```

## To create a newline
```html
<br>
```

## Block Element
+ They take a complete line.
+ Example: 
  ```html
  <div> <p>
  ```

## Inline Element
+ They take only the space that is required to contain, not the whole line.
+ Example:
  ```html
  <em> <strong>
  ```

## HTML Entities
+ There are some special symbols which the browser might not print directly, to print them, we need to have a special code that the browser understands.
+ These special codes, that represent a symbol are called as HTML Entitites.

## Lists
+ To create a list item `<li> </li>` element is used.
+ To create a bulleted list `<ul> </ul>` element is used.
+ To create a ordered/numbered list `<ol> </ol>` element is used.
+ To create a description list:
  ```html
  <dl>
    <dt> </dt>  // description term
    <dd> </dd>  // description list 
  </dl>