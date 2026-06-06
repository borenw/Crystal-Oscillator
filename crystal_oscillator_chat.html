<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Crystal oscillator: series vs parallel modes — Claude</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Source+Serif+4:ital,opsz,wght@0,8..60,400;0,8..60,600;1,8..60,400&display=swap" rel="stylesheet">
<style>
  :root{
    --bg:#FDFDFB;
    --bubble:#F0F1EC;
    --text:#2A2823;
    --strong:#1A1813;
    --meta:#8C8B83;
    --rule:#ECEAE2;
    --brand:#CC7649;
    --link:#3F6A8C;
    --serif:"Source Serif 4", Georgia, "Times New Roman", serif;
    --sans:ui-sans-serif, system-ui, -apple-system, "Segoe UI", Roboto, Helvetica, sans-serif;
  }
  *{box-sizing:border-box;}
  html,body{margin:0;padding:0;}
  body{
    background:var(--bg);
    color:var(--text);
    font-family:var(--serif);
    font-size:17px;
    line-height:1.7;
    -webkit-font-smoothing:antialiased;
    text-rendering:optimizeLegibility;
  }
  .wrap{max-width:760px;margin:0 auto;padding:28px 26px 140px;}

  /* header */
  header.bar{
    display:flex;align-items:center;gap:11px;
    padding:6px 0 26px;margin-bottom:10px;
    border-bottom:1px solid var(--rule);
  }
  header.bar .logo{flex:0 0 auto;}
  header.bar .htxt{font-family:var(--sans);line-height:1.25;}
  header.bar .htxt .t1{font-size:0.95rem;color:var(--strong);font-weight:600;}
  header.bar .htxt .t2{font-size:0.78rem;color:var(--meta);margin-top:1px;}

  /* turns */
  .turn{margin:30px 0;}
  .turn:first-of-type{margin-top:22px;}

  /* assistant */
  .resp-title{
    display:flex;align-items:center;gap:6px;
    font-family:var(--sans);font-size:0.82rem;color:var(--meta);
    margin-bottom:14px;cursor:default;user-select:none;
  }
  .resp-title svg{flex:0 0 auto;opacity:.8;}
  .assistant .body{color:var(--text);}
  .assistant .body > *:first-child{margin-top:0;}
  .assistant .body > *:last-child{margin-bottom:0;}
  .assistant p{margin:0 0 1.05em;}
  .assistant h3{
    font-family:var(--serif);font-weight:600;color:var(--strong);
    font-size:1.16rem;line-height:1.4;margin:1.7em 0 .7em;
  }
  .assistant ul,.assistant ol{margin:0 0 1.05em;padding-left:1.5em;}
  .assistant li{margin:0 0 .5em;}
  .assistant li::marker{color:var(--meta);}
  strong{color:var(--strong);font-weight:600;}
  em{font-style:italic;}
  a{color:var(--link);text-decoration:none;border-bottom:1px solid rgba(63,106,140,.32);}
  a:hover{border-bottom-color:var(--link);}
  .ok{color:#3f8a55;font-weight:600;}
  .sources{font-size:.93rem;color:var(--meta);margin-top:-.55em;margin-bottom:1.15em;}
  .sources a{color:var(--meta);border-bottom:1px dotted rgba(140,139,131,.5);}
  .sources a:hover{color:var(--link);border-bottom-color:var(--link);}

  /* table */
  .assistant table{
    width:100%;border-collapse:collapse;font-size:0.86rem;line-height:1.5;
    margin:.4em 0 1.3em;font-variant-numeric:tabular-nums;
  }
  .assistant th,.assistant td{
    text-align:left;vertical-align:top;padding:9px 12px;
    border-bottom:1px solid var(--rule);
  }
  .assistant thead th{
    color:var(--strong);font-weight:600;border-bottom:2px solid #DDD9CE;
    font-family:var(--serif);
  }
  .assistant tbody td:first-child{color:var(--strong);font-weight:600;width:21%;}
  .assistant tbody tr:last-child td{border-bottom:none;}
  .assistant tbody tr:hover{background:rgba(0,0,0,.018);}

  /* toolbar */
  .toolbar{display:flex;align-items:center;gap:2px;margin-top:14px;}
  .toolbar button{
    appearance:none;border:none;background:none;cursor:pointer;
    width:30px;height:30px;border-radius:7px;display:inline-flex;
    align-items:center;justify-content:center;color:var(--meta);
    transition:background .12s,color .12s;padding:0;
  }
  .toolbar button:hover{background:rgba(0,0,0,.05);color:var(--strong);}
  .toolbar svg{width:17px;height:17px;}
  .toolbar .ts{font-family:var(--sans);font-size:0.76rem;color:var(--meta);margin-left:8px;}

  /* user */
  .row-user{display:flex;justify-content:flex-end;}
  .user-wrap{max-width:82%;display:flex;flex-direction:column;align-items:flex-end;}
  .msg-user{
    background:var(--bubble);border-radius:17px;padding:12px 18px;
    color:var(--text);font-size:1rem;line-height:1.62;white-space:normal;
  }
  .msg-user p{margin:0 0 .7em;}
  .msg-user p:last-child{margin-bottom:0;}
  .msg-user ol{margin:.55em 0 0;padding-left:1.35em;}
  .msg-user li{margin:0;}
  .user-meta{
    display:flex;align-items:center;gap:2px;margin-top:7px;
    font-family:var(--sans);
  }
  .user-meta .ts{font-size:0.76rem;color:var(--meta);margin-right:6px;}
  .user-meta button{
    appearance:none;border:none;background:none;cursor:pointer;
    width:28px;height:28px;border-radius:7px;display:inline-flex;
    align-items:center;justify-content:center;color:var(--meta);
    transition:background .12s,color .12s;padding:0;
  }
  .user-meta button:hover{background:rgba(0,0,0,.05);color:var(--strong);}
  .user-meta svg{width:15px;height:15px;}

  footer.endmark{display:flex;justify-content:center;margin-top:46px;opacity:.9;}

  ::selection{background:#E9D9C9;}
  @media (max-width:640px){
    .wrap{padding:20px 16px 90px;}
    body{font-size:16px;}
    .user-wrap{max-width:90%;}
    .assistant tbody td:first-child{width:auto;}
    .assistant table{font-size:0.8rem;}
  }
</style>
</head>
<body>
<div class="wrap">

  <header class="bar">
    <span class="logo" aria-hidden="true">
      <svg width="26" height="26" viewBox="0 0 100 100">
        <g fill="var(--brand)">
          <rect x="46" y="6" width="8" height="34" rx="4"/>
          <rect x="46" y="60" width="8" height="34" rx="4"/>
          <rect x="6" y="46" width="34" height="8" rx="4"/>
          <rect x="60" y="46" width="34" height="8" rx="4"/>
          <g transform="rotate(45 50 50)">
            <rect x="47" y="14" width="6" height="26" rx="3"/>
            <rect x="47" y="60" width="6" height="26" rx="3"/>
            <rect x="14" y="47" width="26" height="6" rx="3"/>
            <rect x="60" y="47" width="26" height="6" rx="3"/>
          </g>
          <g transform="rotate(22.5 50 50)">
            <rect x="48" y="22" width="4" height="18" rx="2"/>
            <rect x="48" y="60" width="4" height="18" rx="2"/>
            <rect x="22" y="48" width="18" height="4" rx="2"/>
            <rect x="60" y="48" width="18" height="4" rx="2"/>
          </g>
          <g transform="rotate(67.5 50 50)">
            <rect x="48" y="22" width="4" height="18" rx="2"/>
            <rect x="48" y="60" width="4" height="18" rx="2"/>
            <rect x="22" y="48" width="18" height="4" rx="2"/>
            <rect x="60" y="48" width="18" height="4" rx="2"/>
          </g>
        </g>
      </svg>
    </span>
    <span class="htxt">
      <span class="t1">Crystal oscillator: series vs parallel modes</span>
      <span class="t2">Claude · Opus 4.8</span>
    </span>
  </header>

  <!-- ============ TURN 1 ============ -->
  <div class="turn row-user">
    <div class="user-wrap">
      <div class="msg-user">
        <p>crystal quartz has phase crossing zero at 2 different frequnecy. for example the 32.768kHz crystal, fs=32.768kHz, fp=slightly larger ~32.8kHz, how do we know or design shich of this frequency to be the oscillation freqency</p>
      </div>
      <div class="user-meta"><span class="ts">3:12 PM</span><button title="Edit" data-edit>EDIT</button><button title="Copy" data-copy>COPY</button></div>
    </div>
  </div>

  <div class="turn assistant">
    <div class="resp-title">Explaining series vs parallel resonance and which frequency oscillates<span data-chev></span></div>
    <div class="body">
      <p>Good question — and the key insight is that <strong>the crystal doesn't "decide"; the oscillator circuit around it does.</strong> The two zero-phase crossings are intrinsic to the crystal, but which one the loop locks onto is set entirely by the topology and the Barkhausen conditions. Let me walk through it.</p>

      <h3>Why there are two zero-phase points</h3>
      <p>The crystal's equivalent circuit is a motional series arm (Lm, Cm, Rm) in parallel with the static/electrode capacitance C0:</p>
      <ul>
        <li><strong>fs (series resonance):</strong> Lm and Cm resonate, the motional arm collapses to just Rm. Impedance is at a <strong>minimum and purely real</strong>. &nbsp;fs = 1 / (2π√(Lm·Cm))</li>
        <li><strong>fp (parallel / anti-resonance):</strong> just above fs the motional arm is net <em>inductive</em>, and that inductance resonates with C0. Impedance is at a <strong>maximum and purely real</strong>. &nbsp;fp = fs·√(1 + Cm/C0)</li>
      </ul>
      <p>Between these two points the crystal looks like an <strong>inductor</strong> (phase ≈ +90°). Outside the band — below fs and above fp — it looks <strong>capacitive</strong> (≈ −90°). So the impedance phase crosses zero twice: once at the low-impedance dip (fs) and once at the high-impedance peak (fp).</p>
      <p>Picture the reactance curve: plot reactance X versus frequency. It sits <strong>negative (capacitive)</strong> as you come up from below, <strong>crosses zero at fs</strong>, then shoots steeply <strong>positive (inductive)</strong> through a narrow window, hitting a <strong>pole at fp</strong> where it flips to −∞ and climbs back toward zero from below (capacitive again). That tiny window between fs and fp — only a fraction of a percent wide — is the inductive region that every parallel-mode oscillator lives in.</p>

      <h3>How the circuit picks one</h3>
      <p>Oscillation requires the Barkhausen conditions: loop gain ≥ 1 and total loop phase = 0° (or 360°). Only the frequency that satisfies both will sustain, and the surrounding network is what makes one crossing satisfy them.</p>
      <p><strong>Series-mode oscillators.</strong> Here the crystal sits in the feedback path as a series element, and the circuit is designed so the loop phase hits zero when the crystal is a <em>low resistive impedance</em>. That condition is met at the dip — so it runs at <strong>fs</strong>. The crystal is essentially acting as a frequency-selective short.</p>
      <p><strong>Parallel-mode oscillators (your 32.768 kHz case).</strong> This is the Pierce topology used in watch/RTC crystals: an inverting amplifier plus two load capacitors to ground, with the crystal bridging them. The inverter supplies 180° of phase; the π-network (crystal + the two caps) must supply the <em>other</em> 180°. A capacitor can't do that — only an inductor can. So the loop can only close where <strong>the crystal looks inductive</strong>, i.e. somewhere strictly <em>between fs and fp</em>. It physically cannot oscillate at the bare fs or fp in this topology; it lands at the <strong>load resonant frequency fL</strong>:</p>
      <p>fL = fs · (1 + Cm / (2·(C0 + CL)))</p>

      <h3>The load cap is the design knob</h3>
      <p>That formula is the practical answer to "how do we design which frequency." fL slides continuously across the inductive band depending on the load capacitance CL:</p>
      <ul>
        <li>CL → ∞ pulls fL down toward <strong>fs</strong></li>
        <li>CL → 0 pushes fL up toward <strong>fp</strong></li>
      </ul>
      <p>So the manufacturer trims the crystal so that <em>at the rated CL</em> (typically 6, 9, or 12.5 pF for a tuning-fork part), fL lands on exactly 32768.000 Hz. A subtle consequence: for a parallel-mode part, the marked "32.768 kHz" is the <em>loaded</em> frequency — the true series fs actually sits a few ppm <em>below</em> the marking, and fp a bit above. Your "fs = 32.768, fp ≈ 32.8" picture is right in spirit; just note the nameplate number is really fL.</p>
      <p>For a tuning-fork crystal with Cm ≈ 0.004 pF and C0 ≈ 1.5 pF, the whole fs→fp span is only ~1300 ppm (your ~40 Hz of headroom between 32.768 and ~32.81 kHz), and at CL = 12.5 pF you're sitting just a handful of Hz above fs inside that window. That narrowness is exactly why the part is so stable — the reactance slope through the inductive band is brutally steep, so the phase condition pins the frequency tightly.</p>
      <p>So, to summarize the decision: <strong>choose the topology</strong> (series feedback → fs; Pierce/Colpitts with load caps → between fs and fp), and within the parallel case <strong>choose CL</strong> to set the exact landing point. The datasheet's "load capacitance" spec is the contract that ties your board's effective CL to the rated frequency — get the on-board CL wrong and the oscillator runs off-frequency even though the crystal is fine.</p>
      <p>One practical gotcha worth flagging: effective CL ≈ (C_load1 · C_load2)/(C_load1 + C_load2) + C_stray, and people routinely forget the few pF of stray/pin capacitance, which pulls a 32.768 kHz RTC enough to lose minutes per day. If you're laying out a board around one, that stray term is usually where the frequency error comes from.</p>
    </div>
    <div class="toolbar" data-tools><span class="ts">3:13 PM</span></div>
  </div>

  <!-- ============ TURN 2 ============ -->
  <div class="turn row-user">
    <div class="user-wrap">
      <div class="msg-user">
        <p>make table, compare serial and parallel, which is peirce? colpitts? which LC dominant? is it adjustable by tunning external cap, etc.</p>
      </div>
      <div class="user-meta"><span class="ts">3:18 PM</span><button title="Edit" data-edit>EDIT</button><button title="Copy" data-copy>COPY</button></div>
    </div>
  </div>

  <div class="turn assistant">
    <div class="resp-title">Comparing series and parallel mode crystal oscillators<span data-chev></span></div>
    <div class="body">
      <p>Here's the comparison. The thing to anchor on first: <strong>series vs parallel are two ways of <em>operating the same crystal</em>, and the oscillator topology is what enforces one or the other.</strong></p>
      <table>
        <thead><tr><th>Attribute</th><th>Series-mode</th><th>Parallel-mode (load-resonant)</th></tr></thead>
        <tbody>
          <tr><td>Crystal behaves as</td><td>Low resistive impedance (≈ Rm) at the dip</td><td>An <strong>inductor</strong>, in the window between fs and fp</td></tr>
          <tr><td>Oscillation frequency</td><td>At / very near <strong>fs</strong></td><td>At <strong>fL</strong>, between fs and fp</td></tr>
          <tr><td>Which resonance / LC dominates</td><td>Motional <strong>Lm–Cm</strong> series resonance; C0 is a parasitic to be neutralized</td><td>Motional <strong>Lm resonating against (C0 + C_L)</strong> — the load caps are part of the resonant network</td></tr>
          <tr><td>Canonical topologies</td><td>Butler, Driscoll, two-inverter, differential</td><td><strong>Pierce, Colpitts, Clapp</strong></td></tr>
          <tr><td>Is it Pierce?</td><td>No</td><td><strong>Yes — Pierce is the parallel-mode workhorse</strong> (MCU clocks, 32.768 kHz RTC)</td></tr>
          <tr><td>Is it Colpitts?</td><td>Not the classic Colpitts</td><td><strong>Yes</strong> — crystal Colpitts is parallel-mode too; Pierce is essentially a redrawn Colpitts (same capacitive divider)</td></tr>
          <tr><td>Tunable by external cap?</td><td>Not the design intent; only a small upward pull via a <em>series</em> cap</td><td><strong>Yes — this is the trimming knob.</strong> Vary C_L (trimmer or varactor → VCXO) to pull fL</td></tr>
          <tr><td>Pull direction</td><td>Adding series Cs → frequency <strong>up</strong> (toward fp)</td><td>Larger C_L → <strong>down</strong> (toward fs); smaller C_L → up (toward fp)</td></tr>
          <tr><td>Pulling range</td><td>Small</td><td>Bounded by the fs→fp span, set by Cm/C0 (~100s of ppm for fundamental)</td></tr>
          <tr><td>Crystal spec on datasheet</td><td>"Series resonant" (no C_L given)</td><td>"Parallel resonant at C_L = 6 / 9 / 12.5 pF"</td></tr>
          <tr><td>Typical use</td><td>Overtone selection, some low-phase-noise designs</td><td>Default for cheap, stable, integrated oscillators</td></tr>
          <tr><td>Main practical hazard</td><td>C0 feedthrough can cause spurious oscillation off-resonance</td><td>Stray/pin C adds to C_L and pulls frequency</td></tr>
        </tbody>
      </table>

      <h3>Direct answers to your questions</h3>
      <p><strong>Pierce vs Colpitts:</strong> both are <strong>parallel-mode</strong>, and they're close relatives — Pierce is the Colpitts with the capacitive divider redrawn so the crystal bridges the inverting amp's input and output, with one load cap on each side to ground. Clapp is the Colpitts/Pierce with an extra series cap added to give a finer pulling/trim knob. Series-mode oscillators are a <em>different</em> family (Butler, Driscoll, two-inverter loops).</p>
      <p><strong>Which LC dominates:</strong> in series mode it's the motional <strong>Lm–Cm</strong> resonance and C0 is just a nuisance you try to trap out. In parallel mode it's the motional <strong>Lm against the total shunt capacitance C0 + C_L</strong> — which is exactly <em>why</em> the external caps set the frequency.</p>
      <p><strong>Adjustable by external cap:</strong> parallel mode, yes — that's the whole point, and it's how VCXOs work (swap the trimmer for a varactor). Series mode, only weakly, and via a <em>series</em> cap that pulls upward; the canonical design just sits at fs.</p>
      <p>So your 32.768 kHz watch crystal is a <strong>parallel-mode Pierce</strong>, the dominant resonance is Lm against (C0 + C_L), and you tune it by setting C_L — which is why the datasheet rates it "32.768 kHz at C_L = 12.5 pF" rather than just "32.768 kHz."</p>
    </div>
    <div class="toolbar" data-tools><span class="ts">3:19 PM</span></div>
  </div>

  <!-- ============ TURN 3 ============ -->
  <div class="turn row-user">
    <div class="user-wrap">
      <div class="msg-user">
        <p>series LC mode means we need external circuit to provide small negative resistance that will also draw large current through it, will small voltage drop (since it's small negative resistance), voltage swing is hidden inside crystal;</p>
        <p>parallel mode means we will provide large cap, which expose the high voltage swing to external terminal of crystal. and the cap we loaded can modulate the resonant freuqnecy.</p>
        <p>Claude, please analyze, compare with web search, argue if correct, critical thinking. if agree, please provide link of existing docoument or data that support each point</p>
      </div>
      <div class="user-meta"><span class="ts">3:24 PM</span><button title="Edit" data-edit>EDIT</button><button title="Copy" data-copy>COPY</button></div>
    </div>
  </div>

  <div class="turn assistant">
    <div class="resp-title">Analyzing the series/parallel framing against sources<span data-chev></span></div>
    <div class="body">
      <p>Your mental model is <strong>largely correct</strong> — it's actually a clean restatement of the classic series-resonance / parallel-resonance duality, applied to the crystal. Two of your points are spot-on, one needs an important correction, and one is right but rests on a model abstraction worth flagging. Let me go through it point by point with sources, then push back where it's incomplete.</p>

      <h3>Series-mode claims</h3>
      <p><strong>"Large current, small voltage drop"</strong> — <span class="ok">✅ Correct.</span> At series resonance the crystal impedance collapses to its minimum value, purely resistive and equal to Rm. At series resonance the impedance is purely resistive and equal to R0, so the current peaks (I = V/R) while the terminal voltage stays small. At resonance the impedance Z is at its minimum value, so the circuit current is at its maximum of V/R. This is exactly why a series-mode sustaining amplifier is designed for low impedance — one good reference states the amp should ideally have zero input impedance and a voltage-source output because the crystal is used in its low-impedance mode. So "large current through a low-Z element, small terminal voltage" is right.</p>
      <p class="sources">Sources: <a href="https://www.allaboutcircuits.com/textbook/designing-analog-chips/timers-and-oscillators/crystal-oscillators/">allaboutcircuits — crystal oscillators</a>, <a href="https://www.electronics-tutorials.ws/accircuits/series-resonance.html">electronics-tutorials — series resonance</a></p>

      <p><strong>"Voltage swing hidden inside crystal"</strong> — <span class="ok">✅ Correct in spirit</span> (see caveat below). Series resonance is literally called a <em>voltage-magnification</em> circuit: the voltages across the inductor and capacitor each reach Q × the applied voltage but are anti-phase, so they cancel at the terminals. Voltages across L and C can each equal Q times the source — called voltage magnification or resonance rise of voltage. With crystal Q in the 10⁴–10⁶ range, those internal reactive voltages are enormous relative to the small terminal swing — "hidden" is a fair word.</p>
      <p class="sources">Source: <a href="https://zbotic.in/resonant-circuit-series-and-parallel-lc-resonance-guide/">Zbotic — series/parallel LC resonance</a></p>

      <h3>Parallel-mode claims</h3>
      <p><strong>"We add a load cap, and it modulates the resonant frequency"</strong> — <span class="ok">✅ Fully correct</span>, and it's the basis of every VCXO. A load capacitance placed across the crystal terminals forces it into the parallel-resonance region to obtain the desired operating frequency. Replace the trimmer with a varactor and you get tuning — a VCXO is usually built with the crystal in parallel resonance, with one of the capacitors being a varactor diode, and the tuning component sets the frequency between series and parallel resonance.</p>
      <p class="sources">Sources: <a href="https://www.nutsvolts.com/questions-and-answers/crystal-oscillators-defined">Nuts &amp; Volts — crystal oscillators</a>, <a href="https://image-ppubs.uspto.gov/dirsearch-public/print/downloadPdf/6768389">US6768389</a></p>

      <p><strong>"High voltage swing exposed at the terminal"</strong> — <span class="ok">✅ Correct observation.</span> Parallel mode operates near the impedance <em>maximum</em>. The crystal offers low impedance in series-resonant mode and high impedance in anti-resonant or parallel-resonant mode, so for a given current you develop a large terminal voltage. The underlying phenomenon is the dual of the series case — <em>current</em> magnification: in a parallel circuit the Q-factor gives the current magnification, where circulating branch current exceeds the supply current. (Minor reframe in the pushback below.)</p>
      <p class="sources">Sources: <a href="https://www.electrical4u.com/crystal-oscillator/">Electrical4U</a>, <a href="https://www.electronics-tutorials.ws/accircuits/parallel-resonance.html">electronics-tutorials — parallel resonance</a></p>

      <h3>Where I'd push back — three refinements</h3>
      <p><strong>1. Negative resistance is in <em>both</em> modes, not just series.</strong> This is the main correction. Your phrasing implies series = the negative-resistance mode and parallel = the cap mode. But the parallel-mode Pierce is <em>the</em> canonical negative-resistance oscillator — its headline design metric is the <strong>negative-resistance margin</strong>, defined as the ratio of negative resistance generated by the amplifier to the equivalent series resistance of the crystal, and you want that ratio ≥ ~5. The oscillation condition is the same in both cases: the active circuit's |R_neg| must exceed the crystal's loss. The conditions are −R_neg = R_m and −X_osc = X_m: the magnitude of the negative resistance must exceed the motional resistance.</p>
      <p>Here's the twist that makes it interesting: in parallel mode the resistance you must overcome isn't Rm — it's the <em>load-transformed</em> value R_e = R_m·(1 + C0/C_L)², which is <strong>larger</strong> than Rm. So parallel mode actually demands <em>more</em> negative-resistance magnitude than pure series mode, not less. The real distinction between the two modes isn't "negative resistance vs. capacitors" — it's <em>which resonance / impedance level</em> you sit at and what the amplifier is referenced to. ST's AN2867 is the definitive treatment if you want the full derivation.</p>
      <p class="sources">Sources: <a href="https://www.st.com/resource/en/application_note/an2867-guidelines-for-oscillator-design-on-stm8afals-and-stm32-mcusmpus-stmicroelectronics.pdf">ST AN2867 (Rev 24)</a>, <a href="https://image-ppubs.uspto.gov/dirsearch-public/print/downloadPdf/10608587">US10608587</a>, <a href="https://image-ppubs.uspto.gov/dirsearch-public/print/downloadPdf/12531513">US12531513</a></p>

      <p><strong>2. "Hidden inside the crystal" is a lumped-model abstraction, not a probeable node.</strong> Lm, Cm, Rm don't physically exist — they're the electrical equivalent of the mechanical resonance (the vibrating mass of the crystal is represented as a series-resonant LC circuit with a series resistance). So the Q-magnified "internal voltage" isn't something you could scope — there's no terminal where Q × V appears. What's physically large is the <em>mechanical vibration amplitude / stored mechanical energy</em> in the quartz. The electrical voltage magnification is the model's way of bookkeeping that mechanical energy. Worth keeping straight so you don't go looking for a high-voltage node that isn't there.</p>

      <p><strong>3. The high terminal voltage comes from the high-Z anti-resonance, not from the cap being "large."</strong> Decouple two roles. The load caps set (a) the capacitive-divider ratio and (b) the pulling/frequency. The <em>high voltage</em> arises because you're operating near the impedance maximum (current magnification in the tank), not because the caps are large. In fact making C_L <strong>larger</strong> lowers the reactance and pulls frequency <em>down</em> toward fs — the opposite of "more cap → more voltage." So: caps → frequency-setting + divider; high terminal swing → operating near anti-resonance.</p>

      <h3>Corrected one-line model</h3>
      <p>Both modes are high-Q resonators that need the active circuit to supply negative resistance against loss. <strong>Series mode</strong> sits at the impedance <em>minimum</em> (low terminal V, high current, voltage magnification buried in the motional arm), and the amp must beat Rm. <strong>Parallel mode</strong> sits just below the impedance <em>maximum</em> (high terminal V, low line current, current magnification in the load tank), the amp must beat the larger R_e = Rm(1+C0/C_L)², and the load cap is your frequency knob.</p>
      <p>So — agreed on the substance, with the one real correction that negative resistance is the shared mechanism rather than the series-mode signature.</p>
    </div>
    <div class="toolbar" data-tools><span class="ts">3:27 PM</span></div>
  </div>

  <!-- ============ TURN 4 ============ -->
  <div class="turn row-user">
    <div class="user-wrap">
      <div class="msg-user">
        <p>great insightful discussion!<br>on your push back, I should reply your good points</p>
        <ol>
          <li>Correct, i understand both series and parallel need negative resistance. I am aware of the parallel mode also need negative resistance to cancel the Rm of crystal's mechanical vibration resistance. Good thing you point out shows you also understand. And yes it is load-transformed because the serialized resistance with Lm, then parallel with Co, and parallel with -R make it mathmatically complicated, yet solvable (by the transform you filled in). Intuitively we know it has to be negative R, because no matter what transform, parallel to serial will not make +R to -R. That's intuition about R's polarity. About magnitude, I wasn't very clear about the fact that larger negative resistance is needed for parallel mode. good info</li>
          <li>Your reply shows you agree with me. Just to add that an intuitive way to look at these non-exist Lm, Cm, Rm, I would say they exists in mechanical form, exactly the same for a spring loaded with weight and has friction. just that the piezo interface on both side of crystal translate mechanical displacement to voltage, so we get 2 free V-to-dx converter on both side, that can be simplified into a deceivingly simple electrical LRC model. agree that I've seem engineer thought about somehow use the large inductance value in crystal or piezo for other purpose say Buck converter's inductor, of course it's impossible to extract the Lm by removing Cm. It is a story worth passing on</li>
          <li>Agree too. the high voltage exposed in parallel mode is due to the fact that we have the resonant cap's both terminal "touch-able" in parallel mode, vs series mode it's "hidden" inside crystal because the Cm is part of mechanical model black box. What help me understood this was the fundamental LCR resonant, there are 2 ways- parallel and series, exactly match crystal's 2 mode. series mode we can add a negative, low impedance stimulus that can tolerate high current &lt;-very important for us VLSI designer, while parallel mode we need a high-z stimulus that can tolerate high voltage &lt;-again important b/c VLSI device limited by silicon's 10s V limit. which leads to why most resonant stimulus we have are doing the series mode stimulus that tolerate high current b/c vlsi driver chip</li>
        </ol>
      </div>
      <div class="user-meta"><span class="ts">3:33 PM</span><button title="Edit" data-edit>EDIT</button><button title="Copy" data-copy>COPY</button></div>
    </div>
  </div>

  <div class="turn assistant">
    <div class="resp-title">Refining passivity, the mechanical model, and the VLSI counterexample<span data-chev></span></div>
    <div class="body">
      <p>All three land, and the third is where I want to add a wrinkle.</p>
      <p><strong>1 — R polarity / passivity.</strong> Your "a parallel-to-series transform can't flip +R into −R" intuition has a formal name: any passive one-port is a <em>positive-real</em> immittance, meaning Re{Z(jω)} ≥ 0 for every ω. No amount of lossless or lossy passive manipulation can manufacture a negative real part — it has to be injected by an active device. The transform only rescales <em>magnitude</em>. And the (1+C0/C_L)² factor isn't arbitrary: it's literally a capacitive-tap impedance transformer. The two load caps form a divider that steps Rm <em>up</em> by (1+C0/C_L)² as seen by the amplifier (equivalently, steps the amplifier's −R <em>down</em> onto the crystal) — the same trick as a tapped-C matching network in RF. That's the real reason parallel mode demands more |−R|: you're fighting a loss that's been impedance-transformed upward.</p>
      <p><strong>2 — the mechanical black box.</strong> Exactly the Butterworth–Van Dyke picture, and the mapping is clean: Lm ↔ moving mass / inertia (½mv² ↔ ½Li²), Cm ↔ mechanical compliance 1/k (½kx² ↔ ½q²/C), Rm ↔ acoustic/anchor/material damping, and the piezo coupling is the transformer turns-ratio — the electromechanical coupling coefficient k² — bridging the mechanical port to the electrical one. Your "two free V-to-dx converters" are the electrodes; formally it collapses to a single electromechanical port.</p>
      <p>On borrowing the giant inductance — great story, and the numbers make it irresistible: a 32.768 kHz tuning fork has Lm on the order of <em>thousands of henries</em> (~6 kH for Cm ≈ 4 fF); even an HF crystal is tens of mH. But it's unusable as a real inductor, and your "can't remove Cm" is the first of three reasons: (a) Lm and Cm are the <em>same</em> vibration — inertia and compliance of one mode, inseparable; (b) the inductance is <em>kinetic</em>, not magnetic — there's no flux to couple to, so you can't even conceptually wind a secondary around it; (c) it only <em>looks</em> inductive in the sliver between fs and fp, and the mode is drive-limited to microwatts. A buck inductor has to carry amps broadband and store real magnetic energy. So the henries are real in the model and worthless in the field.</p>
      <p><strong>3 — the VLSI current-vs-voltage asymmetry, and a counterexample.</strong> The lens is genuinely good: CMOS is lavish with current (high gm, high current density) and stingy with voltage (breakdown-limited — a few volts at the core, tens for LDMOS/HV). So a low-Z, current-pushing, series-resonant drive maps naturally onto a silicon driver, while a high-Z, voltage-swinging, parallel-resonant drive runs straight into the breakdown wall. In switch-mode resonant power and RF (class-D/E, LLC and series-resonant converters), that's exactly how it shakes out — series-resonant tanks driven hard by low-Z switches, with resonant <em>overvoltage</em> being the thing that kills the FET (the same voltage-magnification hazard that wrecks substation insulation).</p>
      <p>But here's the tension worth chewing on: the single most ubiquitous VLSI-driven resonator on Earth — the MCU/RTC clock, billions of units — is the <strong>Pierce</strong>, which is <em>parallel</em> mode. By your logic it should be the disfavored one. Two things rescue it:</p>
      <ul>
        <li>The Pierce "stimulus" isn't a high-voltage source at all — it's a CMOS inverter acting as a <em>transconductor</em> (current-ish), so it stays CMOS-friendly even while driving a parallel-mode tank. Stimulus impedance and resonator mode aren't as rigidly bolted together as the clean duality implies.</li>
        <li>That high-Z node never reaches a dangerous voltage because the drive level is kept tiny (µW) and the amplitude self-limits within the rails. You can afford near-zero drive precisely because the crystal Q is so absurd that almost no energy sustains it.</li>
      </ul>
      <p>So the monstrous Q is exactly what lets parallel mode cohabit with low-voltage CMOS — it defuses the "high voltage" the duality threatens before it ever becomes a breakdown problem. Net: your claim holds solidly in switch-driven power/RF, but in the clock world the headcount runs the other way, and the reason is amplitude limiting plus transconductance drive — not anything intrinsic to series vs. parallel. The duality predicts the <em>stress</em>; Q decides whether that stress ever shows up.</p>
    </div>
    <div class="toolbar" data-tools><span class="ts">3:35 PM</span></div>
  </div>

  <!-- ============ TURN 5 ============ -->
  <div class="turn row-user">
    <div class="user-wrap">
      <div class="msg-user">
        <p>the wrinkle you added on the 3rd is good point. Let me follow up and see if we can close this fun discussion with great insight that we both agree.</p>
        <ol>
          <li>Your counter example is fair point. My over simplification of VLSI is broken for parallel mode implies using Ultrasonic driver, RF TX kind of application where higher power matters. while in clock oscillator world, we don't need high power (which was my assumption, I should clearly state that) Agree that crystal just need high enough voltage swing, enough for the following circuit to detect, in many cases just a Schmitt trigger. 30V voltage swing crystal oscillator wont' fly.</li>
        </ol>
      </div>
      <div class="user-meta"><span class="ts">3:39 PM</span><button title="Edit" data-edit>EDIT</button><button title="Copy" data-copy>COPY</button></div>
    </div>
  </div>

  <div class="turn assistant">
    <div class="resp-title">Synthesized power-path versus reference-path distinction to unify discussion<span data-chev></span></div>
    <div class="body">
      <p>Yes — that's the clean way to carve it, and "state the assumption explicitly" is the whole fix. Your original logic was never wrong; it was scoped to the <em>power-path</em> case and just needed the boundary drawn.</p>
      <p>The insight I'd close on: the mode choice is really decided by <strong>whether the resonator sits in the power path or the reference path.</strong></p>
      <ul>
        <li><strong>Power path</strong> (ultrasonic drive, RF PA, resonant converters): real watts transit the resonator to a load, so the driver's V/I survival limits are binding, and you match the mode to your device — low-Z, current-pushing series drive for current-happy CMOS/switches, with overvoltage as the failure mode. Your asymmetry rules here, cleanly.</li>
        <li><strong>Reference path</strong> (clocks): you extract <em>information</em> — phase/frequency — not energy. The only output spec that matters is detectability: enough swing for the next inverter/Schmitt to cross threshold with margin. So you deliberately run at minimum drive, the V/I duality never gets invoked, and the mode is chosen for integration convenience (Pierce: one inverter, two caps, two pins, pullable) rather than power handling.</li>
      </ul>
      <p>What makes the reference path so forgiving is the very Q we kept circling back to: it's so enormous that microwatts sustain oscillation, so you never approach any limit in the first place.</p>
      <p>And your "30V swing won't fly" is the perfect capstone because it's <em>doubly</em> forbidden — once from each end of the transducer. The silicon can't make it (breakdown), and even if it could, the quartz couldn't take it: that much voltage at the high-Z node means mechanical vibration amplitude past safe strain — drive-level overshoot, frequency pulling and aging, eventually a cracked tine. Silicon and quartz independently arrive at "keep the swing small," which is why every clock you've ever shipped quietly runs at the smallest swing its detector will reliably resolve.</p>
      <p>So we converge on a tidy triad: <strong>the duality predicts the stress, Q decides whether it ever appears, and power-path-vs-reference-path decides whether you ever care.</strong> The clock world is precisely the corner where Q is high enough and power low enough that the entire V/I tradeoff evaporates — which is exactly why parallel-mode Pierce won there, despite "losing" the duality argument on paper.</p>
      <p>Great thread to think through with you.</p>
    </div>
    <div class="toolbar" data-tools><span class="ts">3:42 PM</span></div>
  </div>

  <footer class="endmark" aria-hidden="true">
    <svg width="22" height="22" viewBox="0 0 100 100">
      <g fill="var(--brand)">
        <rect x="46" y="6" width="8" height="34" rx="4"/><rect x="46" y="60" width="8" height="34" rx="4"/>
        <rect x="6" y="46" width="34" height="8" rx="4"/><rect x="60" y="46" width="34" height="8" rx="4"/>
        <g transform="rotate(45 50 50)"><rect x="47" y="14" width="6" height="26" rx="3"/><rect x="47" y="60" width="6" height="26" rx="3"/><rect x="14" y="47" width="26" height="6" rx="3"/><rect x="60" y="47" width="26" height="6" rx="3"/></g>
        <g transform="rotate(22.5 50 50)"><rect x="48" y="22" width="4" height="18" rx="2"/><rect x="48" y="60" width="4" height="18" rx="2"/><rect x="22" y="48" width="18" height="4" rx="2"/><rect x="60" y="48" width="18" height="4" rx="2"/></g>
        <g transform="rotate(67.5 50 50)"><rect x="48" y="22" width="4" height="18" rx="2"/><rect x="48" y="60" width="4" height="18" rx="2"/><rect x="22" y="48" width="18" height="4" rx="2"/><rect x="60" y="48" width="18" height="4" rx="2"/></g>
      </g>
    </svg>
  </footer>

</div>

<script>
/* SVG icon templates */
const ICONS = {
  copy:'<svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.7" stroke-linecap="round" stroke-linejoin="round"><rect x="9" y="9" width="11" height="11" rx="2.2"/><path d="M5 15V5a2 2 0 0 1 2-2h8"/></svg>',
  up:'<svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.7" stroke-linecap="round" stroke-linejoin="round"><path d="M7 11v9H4a1 1 0 0 1-1-1v-7a1 1 0 0 1 1-1h3z"/><path d="M7 11l4-8a2 2 0 0 1 2.7 2.6L12.5 9H19a2 2 0 0 1 2 2.3l-1 6A2 2 0 0 1 18 19H7"/></svg>',
  down:'<svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.7" stroke-linecap="round" stroke-linejoin="round"><path d="M7 13V4H4a1 1 0 0 0-1 1v7a1 1 0 0 0 1 1h3z"/><path d="M7 13l4 8a2 2 0 0 0 2.7-2.6L12.5 15H19a2 2 0 0 0 2-2.3l-1-6A2 2 0 0 0 18 5H7"/></svg>',
  retry:'<svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.7" stroke-linecap="round" stroke-linejoin="round"><path d="M3 12a9 9 0 1 0 3-6.7L3 8"/><path d="M3 4v4h4"/></svg>',
  speak:'<svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.7" stroke-linecap="round" stroke-linejoin="round"><path d="M4 9v6h4l5 4V5L8 9H4z"/><path d="M16.5 8.5a4 4 0 0 1 0 7"/></svg>',
  edit:'<svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.7" stroke-linecap="round" stroke-linejoin="round"><path d="M12 20h9"/><path d="M16.5 3.5a2.1 2.1 0 0 1 3 3L7 19l-4 1 1-4 12.5-12.5z"/></svg>',
  chev:'<svg width="13" height="13" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M9 6l6 6-6 6"/></svg>'
};

/* assistant toolbars: prepend icon buttons before the timestamp */
document.querySelectorAll('[data-tools]').forEach(tb=>{
  const ts = tb.querySelector('.ts');
  const order = ['retry','speak','copy','up','down'];
  order.forEach(k=>{
    const b=document.createElement('button');
    b.innerHTML=ICONS[k];
    b.title=k;
    tb.insertBefore(b, ts);
  });
  // wire copy
  const body = tb.parentElement.querySelector('.body');
  tb.querySelector('button[title="copy"]').addEventListener('click',()=>copyText(body, tb));
});

/* user meta icons */
document.querySelectorAll('[data-edit]').forEach(b=>{b.innerHTML=ICONS.edit;b.title='Edit';});
document.querySelectorAll('[data-copy]').forEach(b=>{
  b.innerHTML=ICONS.copy;b.title='Copy';
  const msg=b.closest('.user-wrap').querySelector('.msg-user');
  b.addEventListener('click',()=>copyText(msg,b.parentElement));
});

/* chevrons in response titles */
document.querySelectorAll('[data-chev]').forEach(s=>{s.innerHTML=ICONS.chev;});

function copyText(el, host){
  const t = el.innerText.trim();
  try{
    navigator.clipboard.writeText(t).then(()=>flash(host),()=>fallback(t,host));
  }catch(e){ fallback(t,host); }
}
function fallback(t,host){
  const ta=document.createElement('textarea');ta.value=t;document.body.appendChild(ta);
  ta.select();try{document.execCommand('copy');}catch(e){}document.body.removeChild(ta);flash(host);
}
function flash(host){
  const note=document.createElement('span');
  note.textContent='copied';
  note.style.cssText='font-family:var(--sans);font-size:.72rem;color:var(--meta);margin-left:8px;opacity:0;transition:opacity .15s;';
  host.appendChild(note);requestAnimationFrame(()=>note.style.opacity='1');
  setTimeout(()=>{note.style.opacity='0';setTimeout(()=>note.remove(),300);},1100);
}
</script>
</body>
</html>
