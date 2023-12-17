HTML:
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Newspaper Website</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <h1>Newspaper Name</h1>
    <nav>
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">News</a></li>
        <li><a href="#">Sports</a></li>
        <li><a href="#">Opinion</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section>
      <h2>Latest News</h2>
      <article>
        <h3>Article Title</h3>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam euismod, nunc id aliquam lacinia, nisl nunc ultrices nunc, nec tincidunt nunc nunc id mauris.</p>
        <a href="#">Read More</a>
      </article>
      <article>
        <h3>Article Title</h3>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam euismod, nunc id aliquam lacinia, nisl nunc ultrices nunc, nec tincidunt nunc nunc id mauris.</p>
        <a href="#">Read More</a>
      </article>
    </section>

    <section>
      <h2>Sports News</h2>
      <article>
        <h3>Article Title</h3>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam euismod, nunc id aliquam lacinia, nisl nunc ultrices nunc, nec tincidunt nunc nunc id mauris.</p>
        <a href="#">Read More</a>
      </article>
      <article>
        <h3>Article Title</h3>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam euismod, nunc id aliquam lacinia, nisl nunc ultrices nunc, nec tincidunt nunc nunc id mauris.</p>
        <a href="#">Read More</a>
      </article>
    </section>
  </main>

  <footer>
    <p>&copy; 2022 Newspaper Name. All rights reserved.</p>
  </footer>
</body>
</html>
```

CSS (styles.css):
```css
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}

header {
  background-color: #333;
  color: #fff;
  padding: 20px;
}

header h1 {
  margin: 0;
}

nav ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
}

nav ul li {
  display: inline;
  margin-right: 10px;
}

nav ul li a {
  color: #fff;
  text-decoration: none;
}

main {
  padding: 20px;
}

section {
  margin-bottom: 20px;
}

h2 {
  color: #333;
}

article {
  background-color: #f2f2f2;
  padding: 10px;
  margin-bottom: 10px;
}

article h3 {
  margin: 0;
}

article p {
  margin: 10px 0;
}

article a {
  color: #333;
  text-decoration: none;
}

footer {
  background-color: #333;
  color: #fff;
  padding: 10px;
  text-align: center;
}
```

This code creates a basic newspaper website layout with a header, main content area divided into sections, and a footer. The color theme is based on shades of blue. Feel free to modify the code and add more features as needed.
