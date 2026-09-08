[index.html](https://github.com/user-attachments/files/31933257/index.html)


# Centered-Profile<!doctype html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Centered Profile Card</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;700&family=Josefin+Sans:wght@600;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <main class="page-shell">
    <article class="profile-card" aria-labelledby="profile-name">
      <div class="profile-card__topline">
        <span class="profile-card__eyebrow">Available for select projects</span>
        <span class="profile-card__status" aria-label="Available now"></span>
      </div>

      <div class="profile-card__portrait-wrap">
        <img
          class="profile-card__portrait"
          src="https://images.unsplash.com/photo-1545241047-6083a3684587?auto=format&fit=crop&w=480&q=85"
          alt="Lush green office plants"
        >
      </div>

      <div class="profile-card__content">
        <p class="profile-card__location">Naples, Florida</p>
        <h1 id="profile-name">Arianna Kidwell</h1>
        <p class="profile-card__role">Frontend Developer &amp; Interface Designer</p>
        <p class="profile-card__bio">I turn thoughtful ideas into clear, warm, and useful digital experiences.</p>
      </div>

      <div class="profile-card__divider"></div>

      <footer class="profile-card__footer">
        <div>
          <span class="profile-card__metric">24</span>
          <span class="profile-card__label">projects shipped</span>
        </div>
        <a class="profile-card__link" href="mailto:hello@ariannawells.dev">Say hello <span aria-hidden="true">↗</span></a>
      </footer>
    </article>
  </main>
</body>
</html>
