<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Samiksha's Space</title>
  <style>
    body {
      margin: 0;
      font-family: Georgia, serif;
      background: #0f172a;
      color: #f8fafc;
      line-height: 1.6;
    }
    header {
      position: sticky;
      top: 0;
      backdrop-filter: blur(8px);
      animation: fadeIn 2s ease;
      text-align: center;
      padding: 60px 20px;
      background: rgba(255,255,255,0.03);
    }
    header h1 {
      font-size: 2.8rem;
      margin-bottom: 10px;
    }
    header p {
      font-size: 1.1rem;
      opacity: 0.85;
    }
    nav {
      display: flex;
      justify-content: center;
      gap: 20px;
      padding: 15px;
      background: rgba(255,255,255,0.04);
    }
    nav a {
      color: #f8fafc;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      max-width: 900px;
      margin: auto;
      padding: 40px 20px;
    }
    .card {
      animation: fadeIn 1.8s ease;
      transition: transform 0.3s ease;
      background: rgba(255,255,255,0.05);
      border-radius: 16px;
      box-shadow: 0 8px 24px rgba(0,0,0,0.2);
      padding: 25px;
      margin-top: 20px;
    }
    footer {
      text-align: center;
      padding: 25px;
      opacity: 0.7;
      font-size: 0.9rem;
    }
      .stars {
      position: fixed;
      width: 100%;
      height: 100%;
      top: 0;
      left: 0;
      pointer-events: none;
      background-image: radial-gradient(white 1px, transparent 1px);
      background-size: 50px 50px;
      opacity: 0.2;
      animation: drift 20s linear infinite;
    }
    @keyframes drift {
      from { transform: translateY(0px); }
      to { transform: translateY(50px); }
    }
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }
      to { transform: translateY(50px); }
    }
  </style>
</head>
<body>
  <div class="stars"></div>
  <header>
    <h1>SAMIKSHA'S SPACE~ॐ</h1>
    <p>An author space for poems, pauses, and unfinished thoughts.</p>
  </header>  <nav>
    <a href="#about">About Author</a>
    <a href="#poems">Poem List</a>
    <a href="#other">Other Space</a>
    <a href="#contact">Contact</a>
  </nav>  <section id="about">
    <h2>About Author</h2>
    <div class="card">
      <p>Samiksha writes in the quiet spaces between memory and meaning. This site is a living notebook, owned and shaped poem by poem.</p>
    </div>
  </section>  <section id="poems">
    <h2>Poem List</h2>
    <div class="card">
      <h3>Five More Minutes</h3>
      <p>give us five more minutes<br>
      that's all.<br>
      not to change your mind,<br>
      but just to press rewind<br>
      on memories, oh so kind.</p>
      <p>five more minutes,<br>
      please, don't make me choose,<br>
      between holding your heart close<br>
      and learning how to lose</p>
      <p>time can be cruel,<br>
      the night can be long,<br>
      but five more minutes,<br>
      can still feel like home.</p>
      <p>five more minutes-and then you can go<br>
      and i'll stay here,<br>
      trying to learn<br>
      how to let you go.</p>
      <p>~ samiksha</p>
    </div>
    <div class="card">
      <p>More poems can be added here anytime, making this your evolving archive.</p>
    </div>
  </section>  <section id="other">
    <h2>Other Space</h2>
    <div class="card">
      <p>A place for reflections, fragments, future essays, and words that do not yet call themselves poems.</p>
    </div>
  </section>  <section id="contact">
    <h2>Contact</h2>
    <div class="card">
      <p>Instagram: @introvert._samm</p>
    </div>
  </section>  <footer>
    © 2026 Samiksha Writes
  </footer>
</body>
</html>
