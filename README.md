<!doctype html>

<html lang="ar" dir="rtl">
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
    .badge{background:rgba(255,255,255,0.03);padding:6px 10px;border-radius:999px;font-size:13px;border:1px solid rgba(255,255,255,0.02)}.grid{display:grid;grid-template-columns:1fr 320px;gap:20px;margin-top:22px}
.panel{background:linear-gradient(180deg, rgba(255,255,255,0.02), transparent);padding:18px;border-radius:10px;border:1px solid rgba(255,255,255,0.03)}

.tools{display:flex;gap:12px;flex-wrap:wrap}
.tool{display:flex;align-items:center;gap:8px;padding:8px 10px;border-radius:8px;background:rgba(255,255,255,0.02);font-size:14px}
.tool svg{width:18px;height:18px;opacity:0.95}

.pastworks-list{display:flex;flex-direction:column;gap:12px;margin-top:8px}
.project{display:flex;gap:12px;align-items:center;padding:12px;border-radius:10px;background:linear-gradient(180deg, rgba(255,255,255,0.01), transparent);border:1px solid rgba(255,255,255,0.02)}
.project img{width:76px;height:56px;object-fit:cover;border-radius:6px}
.project .info{flex:1}
.project .title{font-weight:600}
.project .desc{color:var(--muted);font-size:13px;margin-top:6px}
.socials{display:flex;flex-direction:column;gap:8px}
.social-row{display:flex;gap:8px;align-items:center}
.social-row a{color:#cfe6f3;text-decoration:none}

.edit-hint{font-size:12px;color:var(--muted);margin-top:8px}

/* responsive */
@media (max-width:900px){.grid{grid-template-columns:1fr}}

  </style>
</head>
<body>
  <div class="wrap">
    <div class="card">
      <header>
        <div class="avatar">
          <!-- GitHub avatar (auto) -->
          <img src="https://github.com/Mohamed-Hessein.png" alt="avatar" />
        </div>
        <div class="meta">
          <h1 id="fullname">Mohamed Hussein</h1>
          <div class="handle" id="handle">@MohamedHussein</div>
          <p class="bio" id="bio">مطور تطبيقات — هنا حط جملة قصيرة عن نفسك (مثلاً: I build mobile apps with Flutter)</p>
          <div class="badges">
            <div class="badge">Open to work</div>
            <div class="badge">🇪🇬 Cairo</div>
          </div>
        </div>
      </header><div class="grid">
    <div>
      <section class="panel">
        <h3>🛠 الأدوات</h3>
        <div class="tools" id="tools">
          <div class="tool">VS Code</div>
          <div class="tool">Flutter</div>
          <div class="tool">Dart</div>
          <div class="tool">Git</div>
        </div>
      </section>

      <section class="panel" style="margin-top:14px">
        <h3>📂 Past Works — المشاريع المميزة</h3>
        <div class="pastworks-list" id="pastworks">
          <div class="project">
          <img src="ttps://github.com/user-attachments/assets/ab9c3115-4880-48af-b9be-816ff16694da" alt="Marketiapp" width="200" />
            <div class="info">
              <div class="title">Marketia</div>
              <div class="desc"># 🛒 E-commerce Store App

A simple **E-commerce mobile application** built with **Flutter & Dart**, featuring clean UI, smooth navigation, and API integration for dynamic product data.

### ✨ Main Features
- Browse products by **Categories** and **Brands**  
- View detailed **Product Profiles**  
- Add items to **Favorites** and **Cart**  
- **Cart Details** with total calculation  
- **Dark Mode** support for better user experience  
- **API integration** to fetch real-time product data  

This project was developed during my training as a practical exercise to explore **Flutter app development, API usage, and modern UI/UX design**..</div>
            </div>
            <div>
              <a href="https://github.com/Mohamed-Hessein">GitHub</a> |
           
            </div>
          </div>
        </div>
      </section>
    </div>

    <aside>
      <div class="panel">
        <h3>🔗 التواصل والسوشيال</h3>
        <div class="socials">
          <div class="social-row">📧 <a href="mailto:mohamedkareem3345@gmail.com">mohamedkareem3345@gmail.com</a></div>
          <div class="social-row">🐙 <a href="https://github.com/Mohamed-Hessein" target="_blank">github.com/Mohamed-Hessein</a></div>
          <div class="social-row">🔗 <a href="https://www.linkedin.com/in/mohamed-mohamed-hussin">LinkedIn</a></div>
        </div>

        <div style="margin-top:12px">
          <h4>📈 GitHub stats (اختياري)</h4>
          <img src="https://github-readme-stats.vercel.app/api?username=Mohamed-Hessein&show_icons=true&theme=dark" alt="stats" style="width:100%;border-radius:8px;margin-top:8px;border:1px solid rgba(255,255,255,0.03)" />
        </div>
      </div>

      <div class="panel" style="margin-top:14px">
        <h3>📎 روابط سريعة</h3>
        <ul style="margin:8px 0 0 0;padding:0 12px;color:var(--muted)">
       
        </ul>
      </div>
    </aside>
  </div>

  <footer style="margin-top:18px;text-align:center;color:var(--muted);font-size:13px">هذا الملف HTML قابل للتعديل — احفظه كـ <code>index.html</code> وارفعه لأي استضافة أو افتحه محليًا.</footer>
</div>

  </div>
</body>
</html>
