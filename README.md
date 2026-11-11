<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<meta name="description" content="Kalukuri Praneeth: ECE diploma student in Hyderabad building a foundation in digital electronics, Verilog and RTL design, with a goal to start a VLSI company.">
<meta name="theme-color" content="#0d0d0d">
<meta property="og:type" content="website">
<meta property="og:title" content="Kalukuri Praneeth – ECE Student Portfolio">
<meta property="og:description" content="Building my foundation in electronics and VLSI RTL design. Goal: a VLSI startup by 2030.">
<meta name="twitter:card" content="summary">
<link rel="icon" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 64 64'%3E%3Crect width='64' height='64' rx='14' fill='%230d0d0d'/%3E%3Ccircle cx='32' cy='32' r='10' fill='%23ff3b30'/%3E%3C/svg%3E">
<script type="application/ld+json">{"@context":"https://schema.org","@type":"Person","name":"Kalukuri Praneeth","jobTitle":"ECE diploma student","email":"mailto:prnxth@gmail.com","address":{"@type":"PostalAddress","addressLocality":"Hyderabad","addressCountry":"IN"},"alumniOf":"Central Institute of Tool Design","sameAs":["https://www.linkedin.com/in/kalukuri-praneeth-3b67b1384","https://www.instagram.com/tbd.prnxth/"]}</script>
<title>Kalukuri Praneeth – ECE Student Portfolio</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Doto:wght@400..900&family=Inter:wght@400;500;600;700&family=JetBrains+Mono:wght@400;600&display=swap" rel="stylesheet">
<style>
:root{
  --bg:#0d0d0d;--card:#141414;--card2:#1a1a1a;--line:#2a2a2a;--text:#f2f2f2;--mute:#a1a1a1;--ink:#0d0d0d;--red:#ff3b30;
  --dot:"Doto","JetBrains Mono",ui-monospace,Menlo,Consolas,monospace;
  --sans:"Inter",system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;
  --mono:"JetBrains Mono",ui-monospace,Menlo,Consolas,monospace;
  color-scheme:dark;
}
*,*::before,*::after{box-sizing:border-box}
html{background:var(--bg);-webkit-text-size-adjust:100%}
body{margin:0;background-color:var(--bg);background-image:radial-gradient(rgba(255,255,255,.07) 1px,transparent 1.3px);background-size:22px 22px;color:var(--text);font:400 15px/1.7 var(--sans);-webkit-font-smoothing:antialiased;padding:env(safe-area-inset-top,0px) 0 env(safe-area-inset-bottom,0px)}
a{color:inherit;text-decoration:none}
p,h1,h2,h3,ul,ol{margin:0}
ul,ol{padding:0;list-style:none}
:focus-visible{outline:2px solid #fff;outline-offset:3px;border-radius:6px}
.wrap{max-width:880px;margin:0 auto;padding:0 24px}
.mute{color:var(--mute)}
em{font-style:normal;font-weight:600;color:var(--text)}
.skip{position:absolute;left:-999px;top:8px;background:#fff;color:var(--ink);padding:8px 16px;border-radius:99px;font:600 13px var(--sans);z-index:60}
.skip:focus{left:12px}

/* nav */
nav{display:flex;justify-content:space-between;align-items:center;padding:24px 0}
.logo{font:800 22px var(--dot);letter-spacing:.02em}
.logo i{color:var(--red);font-style:normal}
nav ul{display:flex;gap:6px}
nav ul a{display:block;padding:7px 14px;border-radius:99px;font:500 13px var(--sans);color:var(--mute)}
nav ul a:hover{color:var(--text);background:var(--card2)}
@media(max-width:560px){nav ul a{padding:6px 9px;font-size:12px}nav ul li:nth-child(3){display:none}}

/* buttons */
.btns{display:flex;flex-wrap:wrap;gap:12px;margin-bottom:26px}
.pill{display:inline-flex;align-items:center;justify-content:center;gap:10px;height:46px;padding:0 26px;border-radius:99px;font:600 14px var(--sans);cursor:pointer;border:1px solid #fff;background:#fff;color:var(--ink)}
.pill:hover{background:var(--red);border-color:var(--red);color:#fff}
.pill.ghost{background:transparent;color:var(--text);border
.tags{display:flex;flex-wrap:wrap;gap:8px}
.tag{font:500 12px var(--sans);color:var(--mute);border:1px solid var(--line);border-radius:99px;padding:4px 12px}
.chip{font:500 13px var(--sans);color:var(--mute);border:1px solid var(--line);border-radius:99px;padding:7px 16px}
.chip:hover{color:var(--text);border-color:#666}

/* hero */
.hero{display:grid;gap:40px;padding:44px 0 56px;align-items:center}
.status{display:inline-flex;align-items:center;gap:10px;border:1px solid var(--line);background:var(--card);border-radius:99px;padding:7px 16px;font:500 13px var(--sans);color:var(--mute);margin-bottom:26px}
.status .dot{width:8px;height:8px;border-radius:50%;background:var(--red);box-shadow:0 0 8px var(--red)}
.status b{font:700 15px var(--dot);color:var(--text);letter-spacing:.04em}
.hero h1{font:800 clamp(46px,9vw,88px)/1.02 var(--dot);letter-spacing:.01em;margin-bottom:24px}
.hero h1 span{display:block}
.hero h1 span::after{content:"";display:inline-block;width:.38em;height:.7em;background:var(--red);margin-left:.18em;vertical-align:baseline}
.lead{font-size:17px;line-height:1.75;color:var(--mute);max-width:46ch;margin-bottom:30px}
.social{display:flex;flex-wrap:wrap;gap:8px}
.profile{border:1px solid var(--line);border-radius:28px;background:var(--card);padding:8px 24px}
.profile div{display:flex;justify-content:space-between;gap:20px;padding:16px 0;border-bottom:1px solid var(--line)}
.profile div:last-child{border-bottom:0}
.profile dt{font:500 12px var(--sans);letter-spacing:.08em;text-transform:uppercase;color:var(--mute);flex:none}
.profile dd{margin:0;font:500 14px var(--sans);text-align:right}
.profile dd.red{color:var(--red);font:800 20px/1 var(--dot)}

/* stats */
.stats{display:grid;grid-template-columns:repeat(3,1fr);gap:12px;padding:0 0 56px}
.stat{border:1px solid var(--line);border-radius:24px;padding:22px 20px;background:var(--card)}
.stat b{display:block;font:800 clamp(30px,7vw,52px)/1 var(--dot)}
.stat.red b{color:var(--red)}
.stat span{display:block;margin-top:10px;font:500 13px/1.4 var(--sans);color:var(--mute)}

/* sections */
section{padding:64px 0;border-top:1px solid var(--line)}
.head{display:flex;align-items:baseline;gap:16px;margin-bottom:32px}
.head .no{font:800 22px var(--dot);color:var(--red)}
.head h2{font:800 clamp(34px,6vw,54px)/1.05 var(--dot)}
.head .sub{font:500 13px var(--sans);color:var(--mute);margin-left:auto;display:none}
@media(min-width:720px){.head .sub{display:block}}

/* cards */
.cards{display:grid;gap:14px}
.box{border:1px solid var(--line);border-radius:24px;padding:24px;background:var(--card)}
.box:hover{border-color:#555}
.box.light{background:#fff;color:var(--ink);border-color:#fff}
.box.light:hover{border-color:#fff}
.box h3{font:600 16px/1.35 var(--sans);margin-bottom:10px}
.box p{font:400 14px/1.75 var(--sans);color:var(--mute)}
.box.light p{color:#3a3a3a}
@media(min-width:620px){.cards.c2,.cards.c4{grid-template-columns:repeat(2,1fr)}}
@media(min-width:960px){.cards.c3{grid-template-columns:repeat(3,1fr)}}

/* about */
.about{display:grid;gap:32px}
@media(min-width:900px){.about{grid-template-columns:1.3fr 1fr;gap:56px}}
.hello{font:500 22px/1.55 var(--sans);letter-spacing:-.01em;color:var(--mute)}
.about .mute{margin-top:18px;max-width:56ch}

/* education */
.edu{display:grid;gap:14px}
@media(min-width:820px){.edu{grid-template-columns:1fr 1fr}}
.meta{display:flex;flex-wrap:wrap;gap:8px;margin-top:16px}
.box.light .tag{color:#444;border-color:#ccc}

/* journey */
.rows{border-top:1px solid var(--line)}
.row{display:grid;grid-template-columns:140px 1fr;gap:20px;padding:20px 18px;border-bottom:1px solid var(--line);font:400 14px/1.6 var(--sans)}
.row small{display:block;color:var(--mute);font-size:12px}
.row b{font-weight:600;font-size:15px}
.row.on{background:#fff;color:var(--ink);border-radius:16px 16px 0 0}
.row.on small{color:#555}
.total{text-align:right;margin-top:22px;color:var(--mute);font-size:14px}
@media(max-width:520px){.row{grid-template-columns:1fr;gap:6px}}

/* code */
.code-head{display:flex;justify-content:space-between;font:500 12px var(--sans);color:var(--mute);margin-bottom:14px}
.code{margin:0;overflow-x:auto;font:400 13px/1.85 var(--mono);color:#d8d8d8;white-space:pre}
.code .k{color:#ff5a4d}.code .n{color:#7fd1ff}.code .c{color:#6f6f6f}

/* projects */
.pjh{display:flex;justify-content:space-between;align-items:center;margin-bottom:18px}
.pjh .no{font:800 26px var(--dot);color:var(--red)}
.pjh .st{font:600 12px var(--sans);border:1px solid var(--line);border-radius:99px;padding:3px 12px;color:var(--mute)}
.box.light .pjh .st{color:var(--ink);border-color:#bbb}
.pj .box{display:flex;flex-direction:column}
.pj .box h3{font-size:17px;min-height:2.7em}
.pj .box p{margin-bottom:18px}
.pj .tags{margin-top:auto}
.note{margin-top:20px;font-size:13px;color:var(--mute)}

/* roadmap */
.road{display:grid;gap:10px}
.road li{display:grid;grid-template-columns:auto 1fr auto;gap:18px;align-items:center;border:1px solid var(--line);border-radius:20px;padding:16px 22px;background:var(--card);font:500 15px var(--sans)}
.road .no{font:800 22px var(--dot);color:var(--mute)}
.road .st{font:600 12px var(--sans);color:var(--mute);border:1px solid var(--line);border-radius:99px;padding:4px 12px}
.road li.now{background:#fff;color:var(--ink);border-color:#fff}
.road li.now .no{color:var(--red)}
.road li.now .st{color:var(--ink);border-color:#bbb}

/* contact */
.contact{display:grid;gap:44px}
@media(min-width:860px){.contact{grid-template-columns:1fr 1fr;gap:72px}}
form{display:grid;gap:16px}
label{display:block;font:500 13px var(--sans);color:var(--mute);margin-bottom:8px}
input,textarea{width:100%;background:var(--card);border:1px solid var(--line);border-radius:16px;padding:14px 18px;color:var(--text);font:400 15px var(--sans)}
input:focus,textarea:focus{outline:none;border-color:#fff}
textarea{min-height:140px;resize:vertical}
input::placeholder,textarea::placeholder{color:#666}
.fstatus{font:500 13px var(--sans);color:var(--mute);min-height:20px}
.bigname{font:800 clamp(44px,8vw,72px)/1.04 var(--dot)}
.bigname span{display:block}
.bigname small{display:block;margin-top:12px;font:500 14px var(--sans);color:var(--mute)}
.channels{display:grid;grid-template-columns:1fr 1fr;gap:10px;margin-top:28px}
.channels a{text-align:center;border:1px solid var(--line);border-radius:99px;padding:12px;font:500 14px var(--sans);color:var(--mute)}
.channels a:hover{color:var(--text);border-color:var(--red)}
.channels a:last-child{grid-column:1/-1}
footer{border-top:1px solid var(--line);padding:28px 0 44px;font:400 13px var(--sans);color:var(--mute);display:flex;justify-content:space-between;flex-wrap:wrap;gap:8px}
</style>
</head>
<body>
<a class="skip" href="#about">Skip to content</a>
<div class="wrap">

<nav aria-label="Main">
  <a class="logo" href="#top">praneeth<i>.</i></a>
  <ul>
    <li><a href="#about">About</a></li>
    <li><a href="#journey">Journey</a></li>
    <li><a href="#projects">Projects</a></li>
    <li><a href="#contact">Contact</a></li>
  </ul>
</nav>

<header class="hero" id="top">
  <div>
    <div class="status"><i class="dot" aria-hidden="true"></i><span>Hyderabad, IN</span><b id="clk" aria-label="Local time">--:--</b></div>
    <h1>Building <span>My Foundation</span></h1>
    <p class="lead">My goal is to <em>start a VLSI RTL design company</em>. I learn something new every day and use <em>AI</em> to get more done.</p>
    <div class="btns">
      <a class="pill" href="#projects">View projects →</a>
      <a class="pill ghost" href="mailto:prnxth@gmail.com">Contact me</a>
    </div>
    <div class="social">
      <a class="chip" href="https://www.linkedin.com/in/kalukuri-praneeth-3b67b1384">LinkedIn</a>
      <a class="chip" href="https://www.instagram.com/tbd.prnxth/">Instagram</a>
      <a class="chip" href="mailto:prnxth@gmail.com">E-mail</a>
    </div>
  </div>
</header>

<div class="stats" aria-label="Quick facts">
  <div class="stat"><b>2nd</b><span>year of diploma</span></div>
  <div class="stat red"><b>2030</b><span>startup goal</span></div>
  <div class="stat"><b>1+</b><span>new thing learned daily</span></div>
</div>

<section id="about">
  <div class="head"><span class="no">01</span><h2>About</h2></div>
  <div class="about">
    <div>
      <p class="hello">Hello! I’m <em>Kalukuri Praneeth</em>, a <em>second-year Diploma student</em> in Electronics &amp; Communication Engineering at the Central Institute of Tool Design, Hyderabad. I graduate in 2028.</p>
      <p class="mute">I’m an AI orchestrator. My long-term goal is to set up a startup in VLSI RTL design. Outside class I watch anime, read books and pick up something new every day.</p>
    </div>
    <div class="cards">
      <div class="box light"><h3>Currently studying</h3><p>Network Analysis / Electronic Measuring Instruments / Digital Electronics</p></div>
      <div class="box"><h3>Hobbies</h3><p>Anime / Reading books / Learning new things daily</p></div>
    </div>
  </div>
</section>

<section id="skills">
  <div class="head"><span class="no">02</span><h2>Skills</h2><span class="sub">Topics and tools I work with</span></div>
  <div class="cards c4">
    <div class="box light"><h3>AI orchestration</h3><p>Prompting / AI workflows / Automation / Choosing the right AI tool</p></div>
    <div class="box"><h3>Coding</h3><p>Python / C / Programming basics</p></div>
    <div class="box"><h3>Electronics</h3><p>Network analysis / Measurements / Circuit basics</p></div>
    <div class="box"><h3>Soft skills</h3><p>Self-learning / Curiosity / Reading / Consistency</p></div>
  </div>
</section>

<section id="education">
  <div class="head"><span class="no">03</span><h2>Education</h2></div>
  <div class="edu">
    <div class="box light"><h3>Central Institute of Tool Design</h3><p>Diploma in Electronics &amp; Communication Engineering</p><div class="meta"><span class="tag">Hyderabad</span><span class="tag">2025 – 2028</span><span class="tag">Now in 2nd year</span></div></div>
    <div class="box"><h3>Sri Venkateswara Bala Kuteer</h3><p>School education</p><div class="meta"><span class="tag">Guntur, Andhra Pradesh</span></div></div>
  </div>
</section>
<section id="journey">
  <div class="head"><span class="no">04</span><h2>Journey</h2></div>
  <div class="rows">
    <div class="row on"><div>2025 – now<small>2nd year</small></div><div><b>CITD, Hyderabad</b><br>Diploma in Electronics &amp; Communication Engineering</div></div>
    <div class="row"><div>Before 2025<small>School</small></div><div><b>Sri Venkateswara Bala Kuteer</b><br>Guntur, Andhra Pradesh</div></div>
    <div class="row"><div>Goal<small>2030 and beyond</small></div><div><b>VLSI RTL design startup</b><br>Learning the digital design skills to get there</div></div>
  </div>
  <p class="total">Still studying, <em>building my foundation</em></p>
</section>

<section id="focus">
  <div class="head"><span class="no">05</span><h2>Focus areas</h2></div>
  <div class="cards c2">
    <div class="box light"><h3>Projects</h3><p>Mini projects are planned in the Projects section. Each one switches from Planned to Done as I finish it.</p></div>
    <div class="box"><h3>Path to VLSI</h3><p>Digital electronics / Verilog and RTL design / FPGA basics / Chip design flow</p></div>
    <div class="box"><div class="code-head"><span>counter.v</span><span>where I’m heading</span></div><pre class="code" aria-label="Example Verilog counter"><span class="c">// 4-bit counter, a first RTL building block</span>
<span class="k">module</span> <span class="n">counter</span>(
  <span class="k">input</span>  clk, rst,
  <span class="k">output reg</span> [3:0] q
);
  <span class="k">always</span> @(<span class="k">posedge</span> clk) <span class="k">begin</span>
    <span class="k">if</span> (rst) q &lt;= 4'd0;
    <span class="k">else</span>     q &lt;= q + 1;
  <span class="k">end</span>
<span class="k">endmodule</span></pre></div>
    <div class="box"><h3>Using AI</h3><p>Orchestrating AI tools to learn faster and get more done</p></div>
  </div>
</section>

<section id="projects">
  <div class="head"><span class="no">06</span><h2>Projects</h2></div>
  <div class="cards c3 pj">
    <div class="box light"><div class="pjh"><span class="no">01</span><span class="st">Planned</span></div><h3>Internet of Things (IoT) &amp; Smart Home</h3><p>Connected devices and automation for a smart home.</p><ul class="tags"><li class="tag">IoT</li><li class="tag">Smart Home</li></ul></div>
    <div class="box"><div class="pjh"><span class="no">02</span><span class="st">Planned</span></div><h3>Gesture-Controlled Robotic Arm</h3><p>A robotic arm controlled by hand gestures.</p><ul class="tags"><li class="tag">Robotics</li><li class="tag">Gesture Control</li></ul></div>
    <div class="box"><div class="pjh"><span class="no">03</span><span class="st">Planned</span></div><h3>Digital Design &amp; Arithmetic, Verilog &amp; Memory, Communication Protocols</h3><p>Arithmetic blocks, memory and communication protocols in Verilog.</p><ul class="tags"><li class="tag">Verilog</li><li class="tag">Memory</li><li class="tag">Protocols</li></ul></div>
  </div>
  <p class="note">I only mark a project Done when it is finished.</p>
</section>

<section id="roadmap">
  <div class="head"><span class="no">07</span><h2>Roadmap</h2><span class="sub">My learning path to VLSI</span></div>
  <ol class="road">
    <li class="now"><span class="no">01</span><span>Digital Electronics</span><span class="st">In progress</span></li>
    <li><span class="no">02</span><span>Verilog and RTL design</span><span class="st">Next</span></li>
    <li><span class="no">03</span><span>FPGA basics</span><span class="st">Next</span></li>
    <li><span class="no">04</span><span>Chip design flow</span><span class="st">Next</span></li>
  </ol>
</section>

<section id="contact">
  <div class="head"><span class="no">08</span><h2>Contact</h2></div>
  <div class="contact">
    <form id="f" novalidate>
      <div><label for="n">Name</label><input id="n" name="name" autocomplete="name" placeholder="Your name" required></div>
      <div><label for="e">Email</label><input id="e" name="email" type="email" autocomplete="email" placeholder="you@example.com" required></div>
      <div><label for="m">Message</label><textarea id="m" name="message" placeholder="How can I help?" required></textarea></div>
      <div><button class="pill" type="submit">Send message →</button></div>
      <div class="fstatus" id="s" role="status"></div>
    </form>
    <div>
      <div class="bigname">Kalukuri<span>Praneeth</span><small>ECE diploma student</small></div>
      <div class="channels">
        <a href="https://www.linkedin.com/in/kalukuri-praneeth-3b67b1384">LinkedIn</a>
        <a href="https://www.instagram.com/tbd.prnxth/">Instagram</a>
        <a href="mailto:prnxth@gmail.com">E-mail</a>
        <a href="#top">Back to top</a>
      </div>
    </div>
  </div>
</section>

<footer><span>Handcrafted by me</span><span>© 2026 Kalukuri Praneeth</span></footer>
</div>

<script>
document.getElementById('f').addEventListener('submit',function(ev){
  ev.preventDefault();
  var s=document.getElementById('s'),n=this.name.value.trim(),e=this.email.value.trim(),m=this.message.value.trim();
  if(!n||!e||!m){s.textContent='Fill in your name, email and message.';return;}
  var body=encodeURIComponent(m+'\n\n– '+n+' ('+e+')');
  window.location.href='mailto:prnxth@gmail.com?subject='+encodeURIComponent('Message from '+n)+'&body='+body;
  s.textContent='Opening your email app to send the message.';
});
function tick(){try{document.getElementById('clk').textContent=new Date().toLocaleTimeString('en-GB',{timeZone:'Asia/Kolkata',hour:'2-digit',minute:'2-digit'});}catch(e){}}
tick();setInterval(tick,15000);
</script>
</body>
</html>
