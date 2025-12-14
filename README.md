# Ex.05 Book Cover Page Design
## Date:14-12-2025

## AIM:
To design a book back cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:

```
cover.html
<html>
    <head>
        <title>About The Book</title>
        <link rel="stylesheet" href="styles.css">
    </head>

<body>
    <div class="container">
        <h1>About The Book</h1>
        <hr class="title-line">
        <p>
            This book <span class="highlight">A Different Look At Artifical Intelligence</span>
            Artificial Intelligence is like a mirror for human creativity.
             Instead of thinking on its own, it reflects the ideas, 
             patterns, and possibilities we feed into it.
              The more we shape it, the more it reshapes how we work, 
              learn, and imagine the future.
        </p>
        <div class="quote">
            “AI is not replacing human intelligence; it is revealing
             how much more we can create when imagination meets computation.”
        </div>
        <div class="author">
            <img src="img.png.jpeg" class="aut-img">
            <div class="author-text">
                <h3>SAHANA SATHYANARAYANAN</h3>
                <p>
                    Sahana Sathyanarayan is a determined and caring person who works
                     hard to grow and make her loved ones proud. She is curious,
                      thoughtful, and always looking for ways to improve herself
                       and understand the world better.
                </p>
            </div>
        </div>
        <div class="footer">
            <span class="publisher">SEC PUBLISHER</span>
            <span class="price">Price:₹499</span>
        </div>

    </div>
    <footer>
        <p>Sahana S(25004522)</p>
    </footer>
</body>
</html>

styles.css
body {
    margin: 0;
    padding: 0;
    background: rgb(255, 255, 255);
}

.container {
    width: 470px;
    height: 600px;
    background-image: url('bg.png');
    background-size: cover;
    background-position: center;
    border: 4px solid rgb(47, 106, 10);
    border-radius: 12px;
    box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    text-align: left;
    padding: 30px;
    margin: 40px auto;
}


h1 {
    color: rgb(35, 73, 38);
    margin-bottom: 20px;
}

.highlight {
    background: darkseagreen;
}

.title-line {
    border: none;
    height: 3px;
    background-color: rgb(99, 145, 102);  
    width: 2xpx;
    margin: 0 0 15px 0;
}


.quote {
    background: rgb(153, 200, 159);
    border-left: 5px solid rgb(53, 114, 52);
    padding: 15px;
    margin: 25px 0;
    font-style: italic;
}

.author {
    display: flex;
    align-items: center;
    background: rgb(85, 105, 90);
    padding: 10px;
    border-radius: 8px;
    margin-top: 10px;

}

.aut-img {
    width: 70px;
    height: 80px;
    border-radius: 5px;
    margin-right: 15px;
    object-fit: cover;
}

.footer {
    margin-top: 30px;
    display: flex;
    justify-content: space-between;
    background: rgb(96, 150, 91);
    color: white;
    padding: 12px 20px;
    border-radius: 6px;
    font-weight: bold;
}

.publisher {
    color: rgb(47, 86, 49);
}

footer{
    text-align: center;
    background-color:rgb(132, 185, 132);
    position: relative;
    bottom: 30px;

}
```


## OUTPUT:
![alt text](<Screenshot (28).png>)

## RESULT:
The program for designing book back cover page using HTML and CSS is completed successfully.
