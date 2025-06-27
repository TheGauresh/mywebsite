<!-- <!DOCTYPE html><p>This line is inactive.</p> -->
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>My Blog</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <h1>Thought of the day ✍🏻</h1>
    <nav role="navigation">
      <ul>
        <h3><li><a href="file:///C:/Users/Administrator/OneDrive/Desktop/blogging.html
">Home</a></li>
        <li><a href="#">About</a></li>
        <li><a href="#">Gallary</a></li>
        <li><a href="#"><!-- <title>/-->Contact</title>
  <style>
    .dropdown-container {
      position: relative;
      display: inline-block;
    }

    .dropdown-content {
      display: none;
      position: absolute;
      background-color: #fff;
      border: 2px solid #ccc;
      min-width: 200px;
      padding: 2px;
      box-shadow: 0px 4px 8px rgba(0,0,0,0.1);
      z-index: 10;
    }

    .dropdown-content p {
      margin: 5px 0;
    }

    #contactLink {
      cursor: pointer;
      color: #007BFF;
      text-decoration: underline;
    }
  </style>
</head>
<body>

  <!-- Your existing hyperlink wrapped in a dropdown container -->
  <div class="dropdown-container">
    <a href="#" id="contactLink">Contact</a>
    
    <div id="contactDetails" class="dropdown-content">
      <p><strong>Email:</strong> gauresh.kumar@bhel.in</p>
      <p><strong>Phone:</strong>9759685324</p>
      <p><strong>Address:</strong> 399,VI-B, NTPV Colony Shakti Nagar, Shonebhadra(U.P.)</p>

    </div>
  </div>

  <script>
    document.getElementById('contactLink').addEventListener('click', function(event) {
      event.preventDefault(); // prevent navigation
      const dropdown = document.getElementById('contactDetails');
      dropdown.style.display = dropdown.style.display === 'block' ? 'none' : 'block';
    });

    // Optional: close dropdown when clicking outside
    window.addEventListener('click', function(event) {
      const link = document.getElementById('contactLink');
      const dropdown = document.getElementById('contactDetails');
      if (!link.contains(event.target) && !dropdown.contains(event.target)) {
        dropdown.style.display = 'none';
      }
    });
  </script>

</body>
<!-- /</html>
</li>/ -->
<li><a href="https://webmail.bhel.in/" target="_blank">Webmail</a>
<li><a href="https://web.whatsapp.com/" target="_blank">WhatsApp</a>
<li><a href="https://www.youtube.com/watch?v=OObyECFMHG0&list=RDNSOObyECFMHG0&start_radio=1
" target="_blank">News</a>
      <!-- /</ul>
    </nav>/-->
    <form role="search">
      <input type="search" placeholder="Search posts…">
      <button type="submit">🔍</button>
    </form>
  /</header>/

  <main>
    <section class="posts">
      <article class="post">
        <h2><a href="#">Honesty is the best policy</a></h2>
        <p class="lede">“Honesty is the best policy” is a timeless proverb encouraging truthfulness—even when it’s difficult. Here's a deeper look at its meaning, origin, and nuances:</p>

📚 Meaning/</p>/</a>
It teaches that truthfulness generally leads to better outcomes than deceit. Lies may offer short-term advantages, but they often result in complications, mistrust, or guilt
</p>
        <p class="meta">Posted on June 26, 2025</p>
        <p>First paragraph preview…</p>
      </article>
      <!-- Repeat article blocks -->
    </section>

    <aside class="sidebar">
      <section>
        <h>About Me</h2>
        <img src="profile.jpg" alt="Photo of me">
        <p>Short personal bio…</p>
      </section>
      <section>
        <h2>Popular Posts</h2>
        <ul>
          <li><a href="#">Popular Post 1</a></li>
          <li><a href="#">Popular Post 2</a></li>
          <li><a href="#">Popular Post 3</a></li>
          <li><a href="#">Popular Post 4
        </ul>
      </section>
      <section>
        <h2>Follow Me</h2>
        <p>Social links here</p>
      </section>
    </aside>
  </main>

  <footer>
    <p>&copy; 2025 Gauresh kumar</p>

  </footer>
</body>
</html>

