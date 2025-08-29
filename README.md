```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>CrimsonCare — Smart Blood Donation & Emergency Response</title>
  <meta name="description" content="CrimsonCare is a unified blood ecosystem connecting donors, patients, hospitals, and blood banks with an emergency-first design and AI assistant." />
  <style>
    :root{
      --bg:#0b0f14;--card:#11161d;--muted:#9fb0c0;--text:#e9eef3;--brand:#ef4444;--brand-2:#f87171;--border:#1f2a36;--code:#0a0e13
    }
    *{box-sizing:border-box}
    html,body{margin:0;padding:0;background:var(--bg);color:var(--text);font:16px/1.6 system-ui,-apple-system,Segoe UI,Roboto,Ubuntu,Cantarell,Noto Sans,"Helvetica Neue",Arial,"Apple Color Emoji","Segoe UI Emoji"}
    a{color:#8dd0ff;text-decoration:none} a:hover{text-decoration:underline}
    .wrap{max-width:980px;margin:0 auto;padding:32px 20px 80px}
    .badge{display:inline-flex;align-items:center;gap:8px;padding:6px 10px;border:1px solid var(--border);border-radius:999px;background:linear-gradient(180deg,#121922,#0e141c)}
    header{display:flex;align-items:center;gap:16px;margin-bottom:24px}
    header img{width:40px;height:40px;border-radius:8px;object-fit:cover;border:1px solid var(--border)}
    h1{font-size:28px;line-height:1.15;margin:0}
    .subtitle{color:var(--muted)}
    .card{background:linear-gradient(180deg,#0f141b,#0c1117);border:1px solid var(--border);border-radius:16px;padding:22px;margin:16px 0}
    h2{font-size:22px;margin:30px 0 10px}
    h3{font-size:18px;margin:20px 0 8px}
    ul{padding-left:20px;margin:10px 0}
    .grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));gap:14px}
    .pill{display:inline-block;padding:2px 10px;border:1px solid var(--border);border-radius:999px;margin:4px 6px 0 0;color:var(--muted)}
    .cta{display:inline-block;background:var(--brand);color:white;font-weight:700;border:none;border-radius:10px;padding:12px 16px}
    .cta:hover{background:var(--brand-2)}
    pre{background:var(--code);border:1px solid var(--border);border-radius:12px;padding:14px;overflow:auto}
    code,kbd{font-family:ui-monospace,SFMono-Regular,Menlo,Monaco,Consolas,"Liberation Mono","Courier New",monospace}
    .check li{list-style:none;margin:6px 0;padding-left:26px;position:relative}
    .check li::before{content:"☐";position:absolute;left:0;color:var(--muted)}
    .muted{color:var(--muted)}
    .hr{height:1px;background:var(--border);margin:24px 0}
    .k{display:inline-block;border:1px solid var(--border);padding:2px 6px;border-radius:6px;background:#0e141b}
    .foot{margin-top:26px;color:var(--muted);font-size:14px}
  </style>
</head>
<body>
  <div class="wrap">
    <header>
      <img src="src/logo.jpg" alt="CrimsonCare logo" />
      <div>
        <h1>CrimsonCare 🩸 — Smart Blood Donation & Emergency Response</h1>
        <div class="subtitle">A unified blood ecosystem connecting donors, patients, hospitals & blood banks — with an emergency-first design.</div>
      </div>
    </header>

    <div class="grid">
      <div class="badge">⚡ Emergency-first</div>
      <div class="badge">✅ ABHA & prescription checks</div>
      <div class="badge">🤖 Azure OpenAI assistant</div>
      <div class="badge">☁️ Azure SQL & Cloud ready</div>
    </div>

    <div class="card">
      <p><strong>CrimsonCare</strong> reduces critical delays in locating compatible blood by providing a central, trusted hub with real-time visibility and verification. Time saved = lives saved.</p>
      <a class="cta" href="#getting-started">Get Started</a>
    </div>

    <nav class="card">
      <strong>Table of Contents</strong>
      <ul>
        <li><a href="#problem">Problem Statement</a></li>
        <li><a href="#solution">Solution Overview</a></li>
        <li><a href="#features">Key Features</a></li>
        <li><a href="#journey">User Journey</a></li>
        <li><a href="#stack">Tech Stack</a></li>
        <li><a href="#getting-started">Getting Started</a></li>
        <li><a href="#roadmap">Roadmap</a></li>
        <li><a href="#contributors">Contributors</a></li>
        <li><a href="#impact">Impact</a></li>
        <li><a href="#security">Security & Secrets</a></li>
      </ul>
    </nav>

    <section id="problem">
      <h2>🚨 Problem Statement</h2>
      <div class="grid">
        <div class="card"><h3>Fragmented Access</h3><p class="muted">Limited real-time visibility into donors and inventory causes delays.</p></div>
        <div class="card"><h3>Trust Deficit</h3><p class="muted">Difficulty verifying authentic requests vs. scams.</p></div>
        <div class="card"><h3>No Central Hub</h3><p class="muted">Stakeholders operate in silos; communication gaps persist.</p></div>
        <div class="card"><h3>Lives at Stake</h3><p class="muted">Every minute lost in emergencies can be fatal.</p></div>
      </div>
    </section>

    <section id="solution">
      <h2>💡 Solution — CrimsonCare</h2>
      <p>CrimsonCare unifies <strong>Donors</strong>, <strong>Patients</strong>, <strong>Hospitals</strong>, and <strong>Blood Banks</strong> on one platform with ABHA-verified authenticity, doctor’s prescription checks, and an integrated AI assistant.</p>
      <div class="pill">ABHA verification</div>
      <div class="pill">Prescription upload</div>
      <div class="pill">Role-based login</div>
      <div class="pill">Emergency request spotlight</div>
      <div class="pill">AI chatbot (Azure OpenAI)</div>
      <div class="pill">Central dashboard</div>
    </section>

    <section id="features">
      <h2>✨ Key Features</h2>
      <ul>
        <li><strong>Secure Authentication:</strong> Role-based access for User/Donor, Hospital, and Blood Bank.</li>
        <li><strong>Intuitive Dashboard:</strong> Quick actions — <em>Request Blood</em> or <em>Donate Blood</em>.</li>
        <li><strong>Emergency Prioritization:</strong> High-priority requests highlighted with a glowing “Donate” button.</li>
        <li><strong>AI Assistant:</strong> Azure OpenAI chatbot for FAQs and guidance.</li>
        <li><strong>Patient Verification:</strong> ABHA number + doctor’s prescription upload & status tracking (Pending / Verified / Missing Docs).</li>
        <li><strong>Lists & Coordination:</strong> Connect patients and eligible donors; simulate verification flows.</li>
        <li><strong>Future-ready:</strong> Geo-matching, AI stock prediction, blockchain donor records.</li>
      </ul>
    </section>

    <section id="journey">
      <h2>🧭 User Journey</h2>
      <ol>
        <li>Register / Login (Donor, Patient, Hospital, Blood Bank).</li>
        <li>Dashboard → choose <em>Request Blood</em> or <em>Donate Blood</em>.</li>
        <li>Patients provide ABHA ID & upload prescription for authenticity.</li>
        <li>System matches patient requirements with eligible donors.</li>
        <li>Emergency requests remain always-visible and prioritized.</li>
        <li>Notifications & coordination streamline donor–hospital communication.</li>
      </ol>
    </section>

    <section id="stack">
      <h2>🛠️ Tech Stack</h2>
      <ul>
        <li><strong>Frontend:</strong> React + Tailwind CSS (single-file prototype in <span class="k">index.html</span>).</li>
        <li><strong>Backend (Planned):</strong> Node.js/Express or Python (FastAPI/Django).</li>
        <li><strong>Database (Planned):</strong> Azure SQL with ABHA integration.</li>
        <li><strong>AI Assistant:</strong> Azure OpenAI (GPT deployments).</li>
        <li><strong>Hosting:</strong> Azure Cloud Services.</li>
      </ul>
    </section>

    <section id="getting-started">
      <h2>🚀 Getting Started</h2>

      <h3>1) Clone</h3>
      <pre><code>git clone https://github.com/&lt;your-username&gt;/crimsoncare.git
cd crimsoncare</code></pre>

      <h3>2) Run the Prototype</h3>
      <p>This repo contains a single HTML file with embedded React (UMD) + Babel for JSX.</p>
      <ul>
        <li>Open <span class="k">index.html</span> directly in a modern browser, or</li>
        <li>Serve locally to avoid CORS/module issues:</li>
      </ul>
      <pre><code># Using Node
npx http-server .
# or
npx serve .

# Using Python
python -m http.server 8080
# → visit http://localhost:8080</code></pre>

      <h3>3) Environment (AI Assistant)</h3>
      <p class="muted">Set your Azure OpenAI <span class="k">endpoint</span>, <span class="k">deployment name</span>, and <span class="k">API key</span> as environment variables and load them safely (never hard-code secrets in client HTML).</p>
      <pre><code># Example (server-side .env)
AZURE_OAI_ENDPOINT="https://&lt;your-resource&gt;.openai.azure.com/"
AZURE_OAI_DEPLOYMENT="gpt-4o-mini"   # example
AZURE_OAI_KEY="&lt;your-key&gt;"</code></pre>
      <p class="muted">Use a lightweight proxy (Node/Express) to call Azure OpenAI from the browser securely.</p>
    </section>

    <section id="roadmap">
      <h2>📌 Roadmap</h2>
      <ul class="check">
        <li>Geo-location based donor matching</li>
        <li>Real-time Azure SQL backend</li>
        <li>AI blood stock prediction</li>
        <li>Blockchain donor records</li>
        <li>Mobile app (React Native / Flutter)</li>
      </ul>
    </section>

    <section id="contributors">
      <h2>🤝 Contributors</h2>
      <p><strong>Team BLANK</strong> — Builders of CrimsonCare</p>
      <ul>
        <li>Hrishikesh Jeeri — Frontend Developer &amp; AI Integrator</li>
        <li>Add your teammates…</li>
      </ul>
    </section>

    <section id="impact">
      <h2>🩸 Impact</h2>
      <ul>
        <li>Expedited emergency responses</li>
        <li>Improved blood availability</li>
        <li>Trust via ABHA & prescription verification</li>
        <li>Strengthens national digital health ecosystem</li>
      </ul>
      <blockquote class="muted">“One donation can save three lives. CrimsonCare helps make it happen—faster.”</blockquote>
    </section>

    <section id="security">
      <h2>🔐 Security & Secrets</h2>
      <ul>
        <li><strong>Never</strong> commit API keys or secrets to the repo.</li>
        <li>Use a backend proxy to call Azure OpenAI; do not expose keys in client code.</li>
        <li>Store secrets in environment variables or a vault (Azure Key Vault).</li>
      </ul>
    </section>

    <div class="hr"></div>
    <footer class="foot">
      <span>© CrimsonCare — Smart Blood Donation & Emergency Response</span>
    </footer>
  </div>
</body>
</html>
```
