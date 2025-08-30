<!doctype html>
<html lang="en" dir="ltr">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Mohamed Hussein — Profile</title>
  <style>
    :root{--bg:#0f1724;--card:#0b1220;--muted:#94a3b8;--accent:#0ea5a4}
    *{box-sizing:border-box;font-family:Inter, system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial}
    body{margin:0;background:linear-gradient(180deg,#071125 0%, #051428 100%);color:#e6eef6;min-height:100vh;display:flex;align-items:center;justify-content:center;padding:28px}
    .wrap{width:980px;max-width:100%;}
    .card{background:radial-gradient(1200px 600px at 10% 10%, rgba(14,165,164,0.06), transparent), var(--card);border-radius:14px;padding:28px;box-shadow:0 8px 30px rgba(2,6,23,0.7)}
    header{display:flex;gap:20px;align-items:center}
    .avatar{width:110px;height:110px;border-radius:14px;overflow:hidden;flex:0 0 110px;border:2px solid rgba(255,255,255,0.06)}
    .avatar img{width:100%;height:100%;object-fit:cover;display:block}
    .meta{flex:1}
    h1{margin:0;font-size:22px}
    .handle{color:var(--muted);margin-top:6px}
    .bio{margin-top:12px;color:#cfe6f3}
    .badges{margin-top:14px;display:flex;gap:8px;flex-wrap:wrap}
    .badge{background:rgba(255,255,255,0.03);padding:6px 10px;border-radius:999px;font-size:13px;border:1px solid rgba(255,255,255,0.02)}
    .grid{display:grid;grid-template-columns:1fr 320px;gap:20px;margin-top:22px}
    .panel{background:linear-gradient(180deg, rgba(255,255,255,0.02), transparent);padding:18px;border-radius:10px;border:1px solid rgba(255,255,255,0.03)}
    .tools{display:flex;gap:12px;flex-wrap:wrap}
    .tool{display:flex;align-items:center;gap:8px;padding:8px 10px;border-radius:8px;background:rgba(255,255,255,0.02);font-size:14px}
    .tool svg{width:18px;height:18px;opacity:0.95}
    .socials{display:flex;flex-direction:column;gap:8px}
    .social-row{display:flex;gap:8px;align-items:center}
    .social-row a{color:#cfe6f3;text-decoration:none}
    footer{margin-top:18px;text-align:center;color:var(--muted);font-size:13px}
    @media (max-width:900px){.grid{grid-template-columns:1fr}}
  </style>
</head>
<body>
  <div class="wrap">
    <div class="card">
      <header>
        <div class="avatar">
          <img src="https://github.com/Mohamed-Hessein.png" alt="avatar" />
        </div>
        <div class="meta">
          <h1 id="fullname">Mohamed Hussein</h1>
          <div class="handle" id="handle">@MohamedHussein</div>
          <p class="bio" id="bio">Flutter Developer</p>
          <div class="badges">
            <div class="badge">Open to work</div>
            <div class="badge">🇪🇬 Cairo</div>
          </div>
        </div>
      </header>

      <div class="grid">
        <div>
          <section class="panel">
            <h3>🛠 Tools</h3>
            <div class="tools" id="tools">
              <div class="tool">
                <!-- VS Code icon -->
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" width="18" height="18" />
                VS Code
              </div>
              <div class="tool">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/flutter/flutter-original.svg" width="18" height="18" />
                Flutter
              </div>
              <div class="tool">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/dart/dart-original.svg" width="18" height="18" />
                Dart
              </div>
              <div class="tool">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" width="18" height="18" />
                Git
              </div>
            </div>
          </section>

          <section class="panel" style="margin-top:14px">
            <h3>📱 Project: E-commerce App</h3>
            <p>
              A simple <b>E-commerce mobile application</b> built with <b>Flutter & Dart</b>, featuring clean UI,
              smooth navigation, and API integration for dynamic product data.
            </p>
            <ul>
              <li>Browse products by Categories & Brands</li>
              <li>View detailed Product Profiles</li>
              <li>Favorites & Cart with details</li>
              <li>Dark Mode support</li>
              <li>API integration for real-time data</li>
            </ul>
          </section>
        </div>

        <aside>
          <div class="panel">
            <h3>🔗 Socials</h3>
            <div class="socials">
              <div class="social-row">📧 <a href="mailto:mohamedkareem3345@gmail.com">mohamedkareem3345@gmail.com</a></div>
              <div class="social-row">🐙 <a href="https://github.com/Mohamed-Hessein" target="_blank">GitHub</a></div>
              <div class="social-row">💼 <a href="https://www.linkedin.com/in/mohamed-mohamed-hussin" target="_blank">LinkedIn</a></div>
            </div>
            <div style="margin-top:12px">
              <h4>📈 GitHub stats</h4>
              <img src="https://github-readme-stats.vercel.app/api?username=Mohamed-Hessein&show_icons=true&theme=dark" alt="stats" style="width:100%;border-radius:8px;margin-top:8px;border:1px solid rgba(255,255,255,0.03)" />
            </div>
          </div>
        </aside>
      </div>
    </div>
    <footer>This HTML profile card is editable — save as <code>index.html</code> and host anywhere.</footer>
  </div>
</body>
</html>
