<!doctype html>
<html lang="en" dir="ltr">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Mohamed Hussein — Profile</title>
  <style>
    :root{--bg:#0f1724;--card:#0b1220;--muted:#94a3b8;--accent:#0ea5a4;--blue:#3b82f6}
    *{box-sizing:border-box;font-family:Inter, system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial}
    body{margin:0;background:linear-gradient(180deg,#071125 0%, #051428 100%);color:#e6eef6;min-height:100vh;display:flex;align-items:center;justify-content:center;padding:28px}
    .wrap{width:980px;max-width:100%;}
    .card{background:radial-gradient(1200px 600px at 10% 10%, rgba(14,165,164,0.06), transparent), var(--card);border-radius:14px;padding:28px;box-shadow:0 8px 30px rgba(2,6,23,0.7)}
    header{display:flex;gap:20px;align-items:center}
    .avatar{width:110px;height:110px;border-radius:14px;overflow:hidden;flex:0 0 110px;border:2px solid rgba(255,255,255,0.06)}
    .avatar img{width:100%;height:100%;object-fit:cover;display:block}
    .meta{flex:1}
    h1{margin:0;font-size:26px;font-weight:700;color:var(--blue);overflow:hidden;white-space:nowrap;border-right:3px solid var(--blue);width:0;animation:typing 3s steps(20,end) forwards, blink 0.75s step-end infinite}
    @keyframes typing{from{width:0}to{width:100%}}
    @keyframes blink{50%{border-color:transparent}}
    .handle{color:var(--muted);margin-top:6px}
    .bio{margin-top:12px;color:#cfe6f3}
    .badges{margin-top:14px;display:flex;gap:8px;flex-wrap:wrap}
    .badge{background:rgba(255,255,255,0.03);padding:6px 10px;border-radius:999px;font-size:13px;border:1px solid rgba(255,255,255,0.02)}
    .grid{display:grid;grid-template-columns:1fr 320px;gap:20px;margin-top:22px}
    .panel{background:linear-gradient(180deg, rgba(255,255,255,0.02), transparent);padding:18px;border-radius:10px;border:1px solid rgba(255,255,255,0.03)}
    .tools{display:flex;gap:12px;flex-wrap:wrap}
    .tool{display:flex;align-items:center;gap:8px;padding:8px 10px;border-radius:8px;background:rgba(255,255,255,0.02);font-size:14px}
    .tool img{width:18px;height:18px}
    .socials{display:flex;flex-direction:column;gap:10px}
    .social-row{display:flex;gap:8px;align-items:center}
    .social-row img{width:20px;height:20px}
    .social-row a{color:#cfe6f3;text-decoration:none}
    .project-img{width:100%;border-radius:8px;margin-top:12px}
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" />
                VS Code
              </div>
              <div class="tool">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/flutter/flutter-original.svg" />
                Flutter
              </div>
              <div class="tool">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/dart/dart-original.svg" />
                Dart
              </div>
              <div class="tool">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" />
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
            <!-- Project Image -->
            <img src="https://github.com/user-attachments/assets/ab9c3115-4880-48af-b9be-816ff16694da" alt="Project Screenshot" class="project-img" />
          </section>
        </div>

        <aside>
          <div class="panel">
            <h3>🔗 Socials</h3>
            <div class="socials">
              <div class="social-row">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/google/google-original.svg" />
                <a href="mailto:mohamedkareem3345@gmail.com">Email</a>
              </div>
              <div class="social-row">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" />
                <a href="https://github.com/Mohamed-Hessein" target="_blank">GitHub</a>
              </div>
              <div class="social-row">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linkedin/linkedin-original.svg" />
                <a href="https://www.linkedin.com/in/mohamed-mohamed-hussin" target="_blank">LinkedIn</a>
              </div>
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
