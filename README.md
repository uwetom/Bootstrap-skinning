# Bootstrap-skinning
skinning a bootstrap site to make it look less like a bootstrap site.

### Create your own CSS stylesheet

1. Create a file, call it "mystyles.css" and save it next to your index.html page
2. Add a link to the head of your index.html page to load in your new css stylesheet, put it just before the closing head tag </head>

<link rel="stylesheet" href="mystyles.css">

### Change the font
1. find a font on google fonts, select it and choose "select this style" ( I chose Questrial)
2. Copy The import code to the top of your new stylesheet

@import url('https://fonts.googleapis.com/css2?family=Questrial&display=swap');

3. Create a new style to replace the font-family or the body

body{
    font-family: 'Questrial', sans-serif;
}


