<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Muhammad Hussain — Data Scientist (Interactive README)</title>
  <meta name="description" content="Interactive GitHub-style README for Muhammad Hussain — Data Science & AI." />
  <style>
    :root{
      --bg:#0f1724; --card:#0b1220; --muted:#94a3b8; --accent:#06b6d4; --glass: rgba(255,255,255,0.04);
      --glass-2: rgba(255,255,255,0.03);
    }
    *{box-sizing:border-box}
    html,body{height:100%;margin:0;font-family:Inter,ui-sans-serif,system-ui,Segoe UI,Roboto,"Helvetica Neue",Arial;color:#e6eef6;background:linear-gradient(180deg,#041028 0%, #071224 60%);}
    .wrap{max-width:980px;margin:28px auto;padding:24px;border-radius:14px;background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));box-shadow:0 6px 30px rgba(2,6,23,0.6);border:1px solid rgba(255,255,255,0.03)}
    header{display:flex;align-items:center;gap:18px}
    .avatar{width:86px;height:86px;border-radius:12px;background:linear-gradient(135deg,var(--accent),#7c3aed);display:flex;align-items:center;justify-content:center;font-weight:700;color:#052026;font-size:28px}
    h1{margin:0;font-size:22px}
    p.lead{margin:6px 0 0;color:var(--muted);font-size:14px}

    .grid{display:grid;grid-template-columns:1fr 320px;gap:18px;margin-top:20px}
    .card{background:var(--card);padding:18px;border-radius:10px;border:1px solid var(--glass);}
    .muted{color:var(--muted);font-size:13px}

    /* skill bars */
    .skill{margin:12px 0}
    .skill .title{display:flex;justify-content:space-between;font-size:13px;margin-bottom:6px}
    .bar{height:10px;border-radius:8px;background:var(--glass-2);overflow:hidden}
    .fill{height:100%;border-radius:8px;background:linear-gradient(90deg,var(--accent),#7c3aed);width:0;transition:width:900ms cubic-bezier(.2,.9,.3,1)}

    /* projects */
    .projects{display:grid;grid-template-columns:repeat(1,1fr);gap:12px}
    .proj{display:flex;flex-direction:column;padding:12px;border-radius:8px;background:linear-gradient(180deg, rgba(255,255,255,0.01), rgba(255,255,255,0.005));border:1px solid rgba(255,255,255,0.02)}
    .proj h4{margin:0 0 6px}
    .meta{font-size:13px;color:var(--muted)}
    .proj .tags{margin-top:8px}
    .tag{display:inline-block;font-size:12px;padding:6px 8px;border-radius:999px;border:1px solid rgba(255,255,255,0.04);margin-right:6px}

    /* controls */
    .controls{display:flex;gap:8px;flex-wrap:wrap}
    button, .btn{background:transparent;color:var(--accent);border:1px solid rgba(6,182,212,0.12);padding:8px 12px;border-radius:8px;cursor:pointer}
    .btn-primary{background:linear-gradient(90deg,var(--accent),#7c3aed);color:#012026;border:none}

    footer{margin-top:18px;text-align:center;color:var(--muted);font-size:13px}

    /* responsive */
    @media (max-width:880px){.grid{grid-template-columns:1fr;}.avatar{width:64px;height:64px;font-size:20px}}
  </style>
</head>
<body>
  <div class="wrap" role="main">
    <header>
      <div class="avatar" aria-hidden>MH</div>
      <div>
        <h1>Muhammad Hussain — Data Scientist</h1>
        <p class="lead">Early-career Data Scientist focused on ML, statistical modeling, and reproducible engineering. Concepts learned under Sir Nitish Singh.</p>
      </div>
    </header>

    <div class="grid" aria-label="main content">
      <section class="card" aria-labelledby="about">
        <h3 id="about">About</h3>
        <p class="muted">I build end-to-end data solutions: exploratory analysis, feature engineering, model development, and production-ready deployment. I emphasize clarity, reproducibility, and measurable impact.</p>

        <div style="margin-top:14px">
          <div style="display:flex;justify-content:space-between;align-items:center">
            <strong>Focus Areas</strong>
            <div class="muted">Open to collaborations & internships</div>
          </div>
          <div class="controls" style="margin-top:10px">
            <button class="btn" onclick="copyEmail()">Copy Email</button>
            <a class="btn" href="mailto:m.hussain@gmail.com">Email</a>
            <a class="btn" href="#projects">View Projects</a>
            <a class="btn btn-primary" href="#contact">Contact</a>
          </div>
        </div>

        <hr style="margin:14px 0;border:none;border-top:1px solid rgba(255,255,255,0.03)">

        <div>
          <strong>Skills</strong>
          <div class="skill" aria-hidden>
            <div class="title"><span>Python</span><span>95%</span></div>
            <div class="bar"><div class="fill" data-width="95%"></div></div>
          </div>
          <div class="skill">
            <div class="title"><span>Statistics & ML</span><span>88%</span></div>
            <div class="bar"><div class="fill" data-width="88%"></div></div>
          </div>
          <div class="skill">
            <div class="title"><span>Data Engineering</span><span>70%</span></div>
            <div class="bar"><div class="fill" data-width="70%"></div></div>
          </div>
          <div class="skill">
            <div class="title"><span>C++ & Algorithms</span><span>65%</span></div>
            <div class="bar"><div class="fill" data-width="65%"></div></div>
          </div>
        </div>

        <hr style="margin:14px 0;border:none;border-top:1px solid rgba(255,255,255,0.03)">
        <div class="muted" style="font-size:13px">Core tools: NumPy · Pandas · Scikit-Learn · Matplotlib · Flask · Git · VS Code</div>
      </section>

      <aside class="card" aria-labelledby="contact">
        <h3 id="contact">Contact & Links</h3>
        <div style="margin:10px 0" class="muted">Muhammad Hussain — Data Science & AI</div>
        <div style="display:grid;gap:8px;margin-top:8px">
          <a class="btn" href="https://github.com/yourusername" target="_blank">GitHub</a>
          <a class="btn" href="https://www.linkedin.com/in/yourprofile" target="_blank">LinkedIn</a>
          <a class="btn" href="mailto:m.hussain@gmail.com">Email</a>
          <a class="btn" href="#" onclick="downloadCV()">Download CV</a>
        </div>

        <hr style="margin:12px 0;border:none;border-top:1px solid rgba(255,255,255,0.03)">
        <div>
          <strong>Quick Stats</strong>
          <div style="display:flex;gap:8px;margin-top:8px">
            <div style="flex:1;text-align:center">
              <div style="font-size:18px;font-weight:700" id="repoCount">0</div>
              <div class="muted">Repos</div>
            </div>
            <div style="flex:1;text-align:center">
              <div style="font-size:18px;font-weight:700" id="starsCount">0</div>
              <div class="muted">Stars</div>
            </div>
            <div style="flex:1;text-align:center">
              <div style="font-size:18px;font-weight:700" id="followersCount">0</div>
              <div class="muted">Followers</div>
            </div>
          </div>
        </div>
      </aside>
    </div>

    <section id="projects" class="card" style="margin-top:18px">
      <h3>Selected Projects</h3>
      <div class="projects" style="margin-top:10px">
        <article class="proj">
          <h4>The Beginning of My Journey</h4>
          <div class="meta">Python exercises — control flow, data types, algorithms — foundational repository.</div>
          <div class="tags">
            <span class="tag">Python</span>
            <span class="tag">Beginners</span>
            <span class="tag">Education</span>
            <a class="btn" href="https://github.com/yourusername/the-beginning-of-my-journey" style="margin-left:auto;margin-top:8px;" target="_blank">Open</a>
          </div>
        </article>

        <article class="proj">
          <h4>Predictive Model (Example)</h4>
          <div class="meta">End-to-end ML pipeline: EDA, feature engineering, model training, evaluation, and inference wrapper.</div>
          <div class="tags"><span class="tag">ML</span><span class="tag">Pandas</span><span class="tag">Scikit-Learn</span></div>
        </article>

      </div>
    </section>

    <section class="card" style="margin-top:14px">
      <h3>How I Work</h3>
      <ol class="muted">
        <li>Define problem & success metrics</li>
        <li>Data acquisition & validation</li>
        <li>Exploratory analysis & feature engineering</li>
        <li>Modeling, evaluation, and iteration</li>
        <li>Deployment with monitoring & reproducibility</li>
      </ol>
    </section>

    <footer>
      <div class="muted">© Muhammad Hussain — Data Scientist · Concepts learned from Sir Nitish Singh</div>
    </footer>
  </div>

  <script>
    // animate skill bars
    document.addEventListener('DOMContentLoaded', ()=>{
      document.querySelectorAll('.fill').forEach(el=>{
        const w = el.getAttribute('data-width') || '60%';
        setTimeout(()=> el.style.width = w, 150);
      });

      // small animation for counters (placeholders — replace with GitHub API integration if desired)
      animateCount('repoCount', 12, 800);
      animateCount('starsCount', 34, 900);
      animateCount('followersCount', 120, 1000);
    });

    function animateCount(id, end, duration){
      const el = document.getElementById(id); if(!el) return;
      let start = 0; const stepTime = Math.max(20, Math.floor(duration / end));
      const timer = setInterval(()=>{ start++; el.textContent = start; if(start>=end) clearInterval(timer); }, stepTime);
    }

    function copyEmail(){ navigator.clipboard?.writeText('m.hussain@gmail.com').then(()=>alert('Email copied to clipboard')) }

    function downloadCV(){
      // placeholder: in GitHub, link to raw file or release; here we simulate
      alert('Download CV — add a valid link to your CV in the HTML (href) to enable direct download.');
    }
  </script>
</body>
</html>
