<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Mona Al Batrouni | Mathematics</title>

  <style>
    :root {
      --navy: #17324d;
      --blue: #2f6f9f;
      --light: #f5f7fa;
      --text: #263238;
      --muted: #607080;
      --white: #ffffff;
      --border: #dfe6ec;
    }

    * {
      box-sizing: border-box;
      scroll-behavior: smooth;
    }

    body {
      margin: 0;
      font-family: Arial, Helvetica, sans-serif;
      color: var(--text);
      background: var(--light);
      line-height: 1.7;
    }

    nav {
      position: sticky;
      top: 0;
      z-index: 100;
      background: rgba(23, 50, 77, 0.96);
      padding: 14px 8%;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    nav .name {
      color: var(--white);
      font-size: 1.1rem;
      font-weight: 700;
    }

    nav a {
      color: var(--white);
      text-decoration: none;
      margin-left: 20px;
      font-size: 0.95rem;
    }

    nav a:hover {
      text-decoration: underline;
    }

    header {
      background: linear-gradient(135deg, #17324d, #2f6f9f);
      color: var(--white);
      padding: 90px 8%;
    }

    header h1 {
      margin: 0;
      font-size: 3rem;
      line-height: 1.2;
    }

    header p {
      max-width: 720px;
      font-size: 1.15rem;
      margin: 18px 0 28px;
    }

    .buttons a {
      display: inline-block;
      margin-right: 12px;
      margin-bottom: 10px;
      padding: 11px 18px;
      border-radius: 7px;
      text-decoration: none;
      font-weight: 600;
    }

    .primary {
      background: var(--white);
      color: var(--navy);
    }

    .secondary {
      border: 1px solid var(--white);
      color: var(--white);
    }

    main {
      max-width: 1000px;
      margin: auto;
      padding: 50px 22px;
    }

    section {
      background: var(--white);
      margin-bottom: 28px;
      padding: 32px;
      border-radius: 12px;
      box-shadow: 0 5px 18px rgba(20, 40, 60, 0.07);
    }

    h2 {
      margin-top: 0;
      color: var(--navy);
      border-bottom: 2px solid var(--border);
      padding-bottom: 10px;
    }

    h3 {
      color: var(--blue);
      margin-bottom: 5px;
    }

    ul {
      padding-left: 22px;
    }

    .publication {
      margin-bottom: 24px;
    }

    .publication-title {
      font-weight: 700;
    }

    a {
      color: var(--blue);
    }

    .tag {
      display: inline-block;
      background: #e8f1f8;
      color: var(--navy);
      padding: 6px 12px;
      margin: 5px 5px 5px 0;
      border-radius: 20px;
      font-size: 0.9rem;
    }

    footer {
      text-align: center;
      color: var(--muted);
      padding: 25px;
      font-size: 0.9rem;
    }

    @media (max-width: 700px) {
      nav {
        display: block;
      }

      nav .links {
        margin-top: 8px;
      }

      nav a {
        margin: 0 12px 0 0;
      }

      header h1 {
        font-size: 2.2rem;
      }

      header {
        padding: 65px 24px;
      }

      section {
        padding: 24px;
      }
    }
  </style>
</head>

<body>

  <nav>
    <div class="name">Mona Al Batrouni</div>

    <div class="links">
      <a href="#about">About</a>
      <a href="#research">Research</a>
      <a href="#publications">Publications</a>
      <a href="#teaching">Teaching</a>
      <a href="#contact">Contact</a>
    </div>
  </nav>

  <header>
    <h1>Mona Al Batrouni</h1>

    <p>
      Mathematics researcher and instructor at the American University of
      Beirut, with research interests in complex analysis, CR geometry,
      arithmetic dynamics, and mathematical physics.
    </p>

    <div class="buttons">
      <a class="primary" href="Mona_AlBatrouni_CV.pdf" target="_blank">
        View CV
      </a>

      <a class="secondary"
         href="mailto:mab108@mail.aub.edu">
        Contact Me
      </a>
    </div>
  </header>

  <main>

    <section id="about">
      <h2>About Me</h2>

      <p>
        I hold an MSc in Mathematics from the American University of Beirut.
        My research spans complex analysis and CR geometry, arithmetic
        dynamics over function fields, and mathematical physics.
      </p>
    </section>

    <section id="research">
      <h2>Research Interests</h2>

      <span class="tag">Complex Analysis</span>
      <span class="tag">CR Geometry</span>
      <span class="tag">Arithmetic Dynamics</span>
      <span class="tag">Function Fields</span>
      <span class="tag">Mathematical Physics</span>
      <span class="tag">Spectral Theory</span>
    </section>

    <section id="publications">
      <h2>Publications and Preprints</h2>

      <div class="publication">
        <div class="publication-title">
          Group-Invariant CR Maps of the Sphere S<sup>5</sup>
        </div>

        <div>
          Mona Al Batrouni and Florian Bertrand
        </div>

        <div>
          <em>Computational Methods and Function Theory</em>, 2026
        </div>

        <a href="https://doi.org/10.1007/s40315-026-00621-x"
           target="_blank">
          DOI
        </a>
      </div>

      <div class="publication">
        <div class="publication-title">
          Maximal Arboreal Galois Images for Polynomials of Twisted Carlitz Type
        </div>

        <div>
          Mona Al Batrouni and Chien-Hua Chen
        </div>

        <div>
          arXiv preprint, 2026
        </div>

        <a href="https://arxiv.org/abs/2606.20046"
           target="_blank">
          arXiv
        </a>
      </div>
    </section>

    <section id="teaching">
      <h2>Teaching</h2>

      <h3>Instructor</h3>
      <ul>
        <li>
          <strong>MATH 101 — Calculus I</strong>,
          Summer 2026
        </li>
      </ul>

      <h3>Recitation Instructor</h3>
      <ul>
        <li>
          <strong>MATH 201 — Calculus and Analytic Geometry III</strong>,
          Spring 2026
        </li>

        <li>
          <strong>MATH 202 — Differential Equations</strong>,
          Spring 2026
        </li>

        <li>
          <strong>MATH 218 — Elementary Linear Algebra and Applications</strong>,
          Spring 2026
        </li>
      </ul>

      <h3>Graduate Teaching Assistant</h3>
      <ul>
        <li>
          <strong>MATH 218 — Elementary Linear Algebra and Applications</strong>,
          Fall 2025
        </li>

        <li>
          <strong>STAT 210 — Elementary Statistics for Sciences</strong>,
          Fall 2024
        </li>
      </ul>
    </section>

    <section id="contact">
      <h2>Contact</h2>

      <p>
        Email:
        <a href="mailto:mab108@mail.aub.edu">
          mab108@mail.aub.edu
        </a>
      </p>

      <p>
        GitHub:
        <a href="https://github.com/monaalbatrouni"
           target="_blank">
          github.com/monaalbatrouni
        </a>
      </p>
    </section>

  </main>

  <footer>
    © 2026 Mona Al Batrouni
  </footer>

</body>
</html>
