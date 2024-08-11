# Experiment1
### index.html
```html 
<html>
    <head>
        <link rel="stylesheet" href="style.css">
        <title>Exp2</title>
        <style>
            body{
                background-image: url("./back.jpg");
                background-size: cover;
                display: flex;
                justify-content: space-between;
                backdrop-filter: blur(3px);
                margin: 0;
            }
            .image{
                background-image: url("./TheDev.jpeg");
                background-size: cover;
                border-radius: 100%;
                height: 20em;
                width: 20em;
                margin: auto;
            }
        </style>
    </head>
    <body>
        <div style="width: 33em; margin: auto 2em;">

            <h1>Hello</h1>
            <h1>I am Gafoor</h1>
            <p>
                i am computer science undergraduate student at seshadri rao gudlavalleru engineering college. i am writing this to filling pages with this paragraph, please dont mind if you are reading this. i think i am a pro developer why are you reading this you noob.
            </p>
            <div id="links">
                <a href="https://linkedin.com/in/Gafoor2005">Linked In</a>
                <a href="https://github.com/Gafoor2005">GitHub</a>
                <a href="https://reddit.com/u/Gafoor_">Reddit</a>
            </div>
        </div>
        <div class="image"></div>
    </body>
</html>
```

### style.css
```css style
@import url('https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Inter:ital,opsz,wght@0,14..32,100..900;1,14..32,100..900&display=swap');
*{
    color: white;
}
h1{
    font-family: "Bebas Neue", sans-serif;
    font-weight: 400;
    font-style: normal;
    margin: 0;
}
p{
    font-family: "Inter", sans-serif;
  font-optical-sizing: auto;
  /* font-weight: 500; */
  /* font-style: normal; */
}
#links{
    display: flex;
    gap: 2em;
}
#links a{
    text-decoration: none;
    font-family: "Inter", sans-serif;
    font-optical-sizing: auto;
    font-weight: 800;
    color: white;
    background-color: blue;
    padding: 1em 2em;
}
#links a:hover{
    cursor: url('./cursor.cur'), auto;
}
```
### output
![output image](./output.png)