# ⭐ Star Agency Website

A simple and accessible HTML5 website for a fictional agency, built with clean semantic structure, accessibility features, and SEO-friendly content.

## 📌 Project Overview

The **Star Agency Website** is a single-page HTML project that demonstrates:

- Semantic HTML5 structure (`<header>`, `<main>`, `<section>`, etc.)
- Proper heading hierarchy for content clarity and SEO
- Accessibility enhancements (ARIA labels, `alt` text, language attribute)
- Responsive meta tags for mobile-friendly display

## 🚀 Live Demo

You can view the live version of the site here:  
👉 [GitHub Pages Link](https://abdiibrahimaden.github.io/star-agency-website-/)  
> *(Make sure GitHub Pages is enabled under repository settings > Pages)*

## 📁 Project Structure

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="description" content="Welcome to EcoWeb, your source for sustainable living tips, news, and eco-friendly lifestyle ideas." />
  <meta name="keywords" content="eco-friendly, sustainability, green living, environment, lifestyle" />
  <meta name="author" content="EcoWeb Team" />
  <title>EcoWeb - Sustainable Living Made Simple</title>
</head>
<body>
  <header role="banner">
    <h1>EcoWeb</h1>
    <nav role="navigation" aria-label="Main navigation">
      <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#articles">Articles</a></li>
        <li><a href="#tips">Tips</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <main role="main">
    <section id="about" aria-labelledby="about-heading">
      <h2 id="about-heading">About EcoWeb</h2>
      <p>EcoWeb is dedicated to promoting a sustainable and eco-conscious lifestyle. We provide readers with practical tips, news, and resources to help them make greener choices.</p>
    </section>

    <section id="articles" aria-labelledby="articles-heading">
      <h2 id="articles-heading">Latest Articles</h2>
      <article>
        <h3>10 Easy Ways to Reduce Plastic Waste</h3>
        <p>Learn simple steps you can take daily to minimize your plastic consumption and reduce environmental impact.</p>
      </article>
      <article>
        <h3>Why Renewable Energy Matters in 2025</h3>
        <p>Explore how renewable energy is shaping the future and what role you can play in supporting clean energy initiatives.</p>
      </article>
    </section>

    <section id="tips" aria-labelledby="tips-heading">
      <h2 id="tips-heading">Eco-Friendly Living Tips</h2>
      <ul>
        <li>Use reusable shopping bags</li>
        <li>Turn off lights when not in use</li>
        <li>Buy local and organic produce</li>
      </ul>
    </section>
  </main>

  <footer role="contentinfo">
    <section id="contact" aria-labelledby="contact-heading">
      <h2 id="contact-heading">Contact Us</h2>
      <address>
        <p>Email: <a href="mailto:contact@ecoweb.com">contact@ecoweb.com</a></p>
        <p>Follow us on 
          <a href="https://twitter.com/ecoweb" aria-label="EcoWeb Twitter">Twitter</a> and 
          <a href="https://facebook.com/ecoweb" aria-label="EcoWeb Facebook">Facebook</a>
        </p>
      </address>
    </section>
    <p>&copy; 2025 EcoWeb. All rights reserved.</p>
  </footer>
</body>
</html>
