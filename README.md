<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Sənin Adın - Portfolio</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #f9f9f9;
      margin: 0; padding: 0;
      color: #333;
    }
    header {
      background-color: #007acc;
      color: white;
      padding: 20px 10px;
      text-align: center;
    }
    main {
      max-width: 900px;
      margin: 30px auto;
      padding: 0 20px;
    }
    h1, h2 {
      margin-bottom: 0.3em;
    }
    p {
      line-height: 1.6;
    }
    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fill,minmax(280px,1fr));
      gap: 20px;
      margin-top: 30px;
    }
    .project-card {
      background: white;
      padding: 15px 20px;
      box-shadow: 0 3px 8px rgb(0 0 0 / 0.1);
      border-radius: 8px;
      transition: transform 0.3s ease;
    }
    .project-card:hover {
      transform: translateY(-5px);
    }
    a {
      color: #007acc;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
    footer {
      text-align: center;
      padding: 20px;
      font-size: 0.9em;
      color: #777;
    }
  </style>
</head>
<body>
  <header>
    <h1>Sənin Adın</h1>
    <p>Backend & Frontend Developer | Open Source Enthusiast</p>
    <p>
      <a href="https://github.com/senin-github-adi" target="_blank" rel="noopener noreferrer" style="color:white;">GitHub</a> | 
      <a href="https://linkedin.com/in/senin-linkedin" target="_blank" rel="noopener noreferrer" style="color:white;">LinkedIn</a> | 
      <a href="mailto:emailin@example.com" style="color:white;">Email</a>
    </p>
  </header>
  <main>
    <section>
      <h2>Haqqımda</h2>
      <p>Mən proqramlaşdırma ilə məşğulam və Python/Django, JavaScript, React kimi texnologiyalarda təcrübəm var. Açıq mənbə layihələrə töhfə verir və daim özümü inkişaf etdirirəm.</p>
    </section>
    <section>
      <h2>Layihələrim</h2>
      <div class="projects">
        <div class="project-card">
          <h3><a href="https://github.com/senin-github-adi/layihe1" target="_blank">Layihə 1</a></h3>
          <p>Bu layihə Django ilə hazırlanmış e-ticarət platformasıdır.</p>
        </div>
        <div class="project-card">
          <h3><a href="https://github.com/senin-github-adi/layihe2" target="_blank">Layihə 2</a></h3>
          <p>React və REST API istifadə edilən sosial media klonu.</p>
        </div>
        <!-- Daha çox layihə əlavə edə bilərsən -->
      </div>
    </section>
  </main>
  <footer>
    &copy; 2025 Sənin Adın. Bütün hüquqlar qorunur.
  </footer>
</body>
</html>

