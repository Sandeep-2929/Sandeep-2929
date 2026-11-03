<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>YOUR NAME | DevOps Engineer</title>
<style>
  :root{
    --bg:#0d1117; --panel:#161b22; --border:#30363d;
    --text:#e6edf3; --muted:#8b949e;
    --green:#2ea043; --blue:#58a6ff;
    --mono:'JetBrains Mono','Fira Code',Consolas,monospace;
  }
  *{box-sizing:border-box;margin:0;padding:0}
  html{scroll-behavior:smooth}
  body{background:var(--bg);color:var(--text);font-family:system-ui,-apple-system,'Segoe UI',sans-serif;line-height:1.6}
  body::before{content:"";position:fixed;inset:0;z-index:-1;
    background:
      radial-gradient(600px 300px at 80% -5%,rgba(88,166,255,.14),transparent),
      radial-gradient(500px 300px at 5% 10%,rgba(46,160,67,.14),transparent),
      linear-gradient(var(--bg),var(--bg));}
  a{color:var(--blue);text-decoration:none}
  .wrap{max-width:1000px;margin:0 auto;padding:0 20px}

  nav{position:sticky;top:0;backdrop-filter:blur(10px);background:rgba(13,17,23,.8);border-bottom:1px solid var(--border);z-index:10}
  nav .wrap{display:flex;justify-content:space-between;align-items:center;height:56px}
  .logo{font-family:var(--mono);color:var(--green);font-weight:700}
  nav ul{display:flex;gap:22px;list-style:none;font-size:14px}
  nav a{color:var(--muted);transition:.2s}
  nav a:hover{color:var(--text)}

  .hero{padding:90px 0 60px}
  .tag{display:inline-flex;align-items:center;gap:8px;font-size:13px;color:var(--green);
    border:1px solid rgba(46,160,67,.4);background:rgba(46,160,67,.1);padding:4px 12px;border-radius:99px}
  .dot{width:8px;height:8px;border-radius:50%;background:var(--green);animation:pulse 1.6s infinite}
  @keyframes pulse{0%{box-shadow:0 0 0 0 rgba(46,160,67,.7)}100%{box-shadow:0 0 0 10px rgba(46,160,67,0)}}
  h1{font-size:clamp(2.2rem,6vw,3.8rem);line-height:1.1;margin:20px 0 14px}
  .grad{background:linear-gradient(90deg,var(--green),var(--blue));-webkit-background-clip:text;background-clip:text;color:transparent}
  .lead{color:var(--muted);max-width:600px;font-size:1.1rem}
  .cta{margin-top:28px;display:flex;gap:12px;flex-wrap:wrap}
  .btn{padding:10px 20px;border-radius:8px;font-weight:600;font-size:14px;border:1px solid var(--border);color:var(--text);transition:.2s}
  .btn.primary{background:var(--green);border-color:var(--green);color:#fff}
  .btn:hover{transform:translateY(-2px);border-color:var(--blue)}

  .term{margin-top:40px;background:var(--panel);border:1px solid var(--border);border-radius:12px;overflow:hidden;font-family:var(--mono);font-size:14px}
  .term .bar{background:#1c2128;padding:10px 14px;display:flex;gap:7px}
  .term .bar i{width:11px;height:11px;border-radius:50%}
  .term .bar i:nth-child(1){background:#ff5f56}.term .bar i:nth-child(2){background:#ffbd2e}.term .bar i:nth-child(3){background:#27c93f}
  .term pre{padding:18px;overflow-x:auto}
  .g{color:var(--green)}.m{color:var(--muted)}.b{color:var(--blue)}
  .cursor{display:inline-block;width:8px;height:15px;background:var(--green);vertical-align:middle;animation:blink 1s steps(1) infinite}
  @keyframes blink{50%{opacity:0}}

  section{padding:60px 0}
  h2{font-size:1.6rem;margin-bottom:6px}
  h2 span{color:var(--green);font-family:var(--mono)}
  .sub{color:var(--muted);margin-bottom:28px}

  .grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));gap:18px}
  .card{background:var(--panel);border:1px solid var(--border);border-radius:12px;padding:22px;transition:.25s}
  .card:hover{transform:translateY(-4px);border-color:var(--blue);box-shadow:0 10px 30px rgba(0,0,0,.35)}
  .card h3{font-size:1.05rem;margin-bottom:8px}
  .card p{color:var(--muted);font-size:.92rem}
  .chips{display:flex;flex-wrap:wrap;gap:6px;margin-top:14px}
  .chip{font-family:var(--mono);font-size:11px;padding:3px 9px;border-radius:99px;background:#1f2630;color:var(--blue);border:1px solid var(--border)}

  .stack{display:flex;flex-wrap:wrap;gap:10px}
  .stack .chip{font-size:13px;padding:6px 14px}

  .timeline{border-left:2px solid var(--border);padding-left:22px}
  .item{position:relative;margin-bottom:26px}
  .item::before{content:"";position:absolute;left:-29px;top:6px;width:12px;height:12px;border-radius:50%;background:var(--green);box-shadow:0 0 0 4px var(--bg)}
  .item h3{font-size:1rem}
  .item small{color:var(--muted);font-family:var(--mono)}
  .item p{color:var(--muted);font-size:.92rem;margin-top:4px}

  footer{border-top:1px solid var(--border);padding:30px 0;text-align:center;color:var(--muted);font-size:14px;font-family:var(--mono)}

  @media (max-width:640px){nav ul{display:none}.hero{padding-top:60px}}
  @media (prefers-reduced-motion:reduce){*{animation:none!important;transition:none!important}}
</style>
</head>
<body>

<nav><div class="wrap">
  <span class="logo">~/yourname</span>
  <ul>
    <li><a href="#about">about</a></li>
    <li><a href="#stack">stack</a></li>
    <li><a href="#projects">projects</a></li>
    <li><a href="#experience">experience</a></li>
    <li><a href="#contact">contact</a></li>
  </ul>
</div></nav>

<header class="hero"><div class="wrap">
  <span class="tag"><span class="dot"></span> Open to opportunities</span>
  <h1>Hi, I'm <span class="grad">YOUR NAME</span><br>DevOps &amp; Platform Engineer</h1>
  <p class="lead">I build reliable CI/CD pipelines, Kubernetes platforms and automated infrastructure that help teams ship faster with confidence.</p>
  <div class="cta">
    <a class="btn primary" href="#projects">View projects</a>
    <a class="btn" href="https://github.com/YOUR_USERNAME">GitHub</a>
    <a class="btn" href="https://linkedin.com/in/YOUR_LINKEDIN">LinkedIn</a>
  </div>

  <div class="term">
    <div class="bar"><i></i><i></i><i></i></div>
<pre><span class="g">$</span> kubectl get engineer -o wide
<span class="m">NAME         ROLE        STATUS    FOCUS</span>
yourname     devops      <span class="g">Ready</span>     ci-cd, iac, k8s, observability
<span class="g">$</span> <span class="cursor"></span></pre>
  </div>
</div></header>

<section id="about"><div class="wrap">
  <h2><span>01.</span> About</h2>
  <p class="sub">What I care about</p>
  <div class="grid">
    <div class="card"><h3>Automation first</h3><p>If I do it twice, it becomes code. Repeatable, reviewed and version-controlled.</p></div>
    <div class="card"><h3>Reliability</h3><p>SLOs, alerting that matters and blameless postmortems that lead to real fixes.</p></div>
    <div class="card"><h3>Security built in</h3><p>Image scanning, secrets management and policy checks inside the pipeline.</p></div>
  </div>
</div></section>

<section id="stack"><div class="wrap">
  <h2><span>02.</span> Toolchain</h2>
  <p class="sub">Tools I use day to day</p>
  <div class="stack">
    <span class="chip">AWS</span><span class="chip">Azure</span><span class="chip">Docker</span><span class="chip">Kubernetes</span>
    <span class="chip">Helm</span><span class="chip">Argo CD</span><span class="chip">Terraform</span><span class="chip">Ansible</span>
    <span class="chip">GitHub Actions</span><span class="chip">Jenkins</span><span class="chip">Prometheus</span><span class="chip">Grafana</span>
    <span class="chip">Trivy</span><span class="chip">Vault</span><span class="chip">Bash</span><span class="chip">Python</span>
  </div>
</div></section>

<section id="projects"><div class="wrap">
  <h2><span>03.</span> Projects</h2>
  <p class="sub">Selected work</p>
  <div class="grid">
    <a class="card" href="https://github.com/YOUR_USERNAME/project-one"><h3>Terraform AWS Platform</h3><p>Reusable modules for multi-environment infrastructure with automated plan and apply.</p><div class="chips"><span class="chip">Terraform</span><span class="chip">AWS</span></div></a>
    <a class="card" href="https://github.com/YOUR_USERNAME/project-two"><h3>GitOps Delivery</h3><p>Declarative Kubernetes deployments with automated sync and rollback.</p><div class="chips"><span class="chip">Argo CD</span><span class="chip">Helm</span></div></a>
    <a class="card" href="https://github.com/YOUR_USERNAME/project-three"><h3>Observability Stack</h3><p>Dashboards and SLO-based alerting across services.</p><div class="chips"><span class="chip">Prometheus</span><span class="chip">Grafana</span></div></a>
  </div>
</div></section>

<section id="experience"><div class="wrap">
  <h2><span>04.</span> Experience</h2>
  <p class="sub">Where I've worked</p>
  <div class="timeline">
    <div class="item"><h3>DevOps Engineer — Company Name</h3><small>2023 – Present</small><p>Cut deployment time by X% with pipeline optimisation and containerised releases.</p></div>
    <div class="item"><h3>Junior DevOps Engineer — Company Name</h3><small>2021 – 2023</small><p>Automated provisioning with Terraform and Ansible across environments.</p></div>
  </div>
</div></section>

<section id="contact"><div class="wrap" style="text-align:center">
  <h2><span>05.</span> Get in touch</h2>
  <p class="sub">Open to DevOps / SRE roles and collaboration</p>
  <a class="btn primary" href="mailto:you@example.com">you@example.com</a>
</div></section>

<footer>© 2026 YOUR NAME · built with HTML &amp; CSS</footer>

</body>
</html>
