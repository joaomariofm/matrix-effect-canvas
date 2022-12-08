# Matrix Effect

![](https://media.giphy.com/media/XGK8r2qBMwvsbJd3O9/giphy.gif)

## Description

This is an implementation of the famous "matrix effect", built with Html canvas tag and TypeScript. The purpose of this project is to be reused in any HTML page. Since it is built with the HTML canvas tag, the script can be easily reused by importing it with npm and then loading it into your page.

## Usage

- First **install the project** as a dependency

    ```bash
        npm install matrix-effect
    ```

- Then **load the script** in your html page

    ```html
        <script src="./node_modules/matrix-effect/script/index.js" ></script>
    ```

- And finaly **add a canvas tag to your page** with the **id matrix**

    ```html
        <canvas id="matrix"></canvas>
    ```

## Important

The dimensions of the canvas will be defined by its parent, in the example shown below the canvas will have a width of 100px and a height of 80px

```html
    <div class="parent">
        <canvas id="matrix"></canvas>
    </div>
```
```css
    .parent {
        width: 100px;
        height: 80px;
    }
```
