# Semantic-html-examples-
# Semantic HTML Examples

This repository contains simple examples showing how to implement semantic HTML effectively.

## Why Semantic HTML?
Semantic HTML improves:
- **SEO** (search engine optimization)
- **Accessibility** (screen readers, WCAG compliance)
- **Code maintainability**

## Files
- `before.html` → Non-semantic example (using only `<div>` and `<span>`).
- `after.html` → Semantic version (using `<header>`, `<main>`, `<article>`, `<footer>`).

## How to Use
1. Open `before.html` in a browser to see a non-semantic structure.
2. Open `after.html` to compare with the semantic version.
3. Notice how the structure is clearer and more accessible.

## Related Blog Post
Read the full article here: [Your Blog Post Link](https://yourblogpostlink.com)


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Non-Semantic Example</title>
</head>
<body>
  <div id="top">
    <div class="menu">Home | About | Contact</div>
  </div>

  <div id="content">
    <div class="post">
      <h2>Welcome to My Blog</h2>
      <p>This is my first post. It's using non-semantic HTML.</p>
    </div>
  </div>

  <div id="bottom">
    <p>© 2025 My Blog</p>
  </div>
</body>
</html>


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Semantic Example</title>
</head>
<body>
  <header>
    <h1>My Blog</h1>
    <nav>
      <ul>
        <li><a href="/">Home</a></li>
        <li><a href="/about">About</a></li>
        <li><a href="/contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <article>
      <h2>Welcome to My Blog</h2>
      <p>This is my first post. Now it's using semantic HTML.</p>
    </article>
  </main>

  <footer>
    <p>© 2025 My Blog</p>
  </footer>
</body>
</html>
