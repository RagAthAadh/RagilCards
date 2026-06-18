<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
<meta name="apple-mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-status-bar-style" content="black">
<meta name="apple-mobile-web-app-title" content="Cards">
<meta name="theme-color" content="#0a0a0f">
<title>Ragil — Card Tracker</title>
<style>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&family=JetBrains+Mono:wght@400;500;600&display=swap');
:root {
  --bg:#0a0a0f; --bg2:#111118; --bg3:#18181f; --bg4:#22222c;
  --border:rgba(255,255,255,0.07); --border2:rgba(255,255,255,0.12);
  --text:#f0f0f5; --text2:#9090a8; --text3:#55556a;
  --red:#ff4466; --red-bg:rgba(255,68,102,0.1);
  --amber:#ffaa33; --amber-bg:rgba(255,170,51,0.1);
  --green:#33cc88; --green-bg:rgba(51,204,136,0.1);
  --blue:#4499ff; --blue-bg:rgba(68,153,255,0.1);
  --purple:#aa77ff; --purple-bg:rgba(170,119,255,0.1);
  --r:14px; --r-sm:8px; --r-xs:6px;
  --safe-bottom: env(safe-area-inset-bottom, 0px);
}
*{box-sizing:border-box;margin:0;padding:0;-webkit-tap-highlight-color:transparent;}
html,body{height:100%;background:var(--bg);color:var(--text);font-family:'Inter',sans-serif;overflow-x:hidden;}
body{padding-bottom:calc(64px + var(--safe-bottom));}

/* TOPBAR */
.topbar{position:sticky;top:0;z-index:100;background:rgba(10,10,15,0.92);backdrop-filter:blur(20px);-webkit-backdrop-filter:blur(20px);border-bottom:0.5px solid var(--border);padding:12px 16px 10px;display:flex;justify-content:space-between;align-items:center;}
.topbar-left .title{font-size:17px;font-weight:600;letter-spacing:-0.3px;}
.topbar-left .sub{font-size:11px;color:var(--text3);margin-top:1px;}
.topbar-right{display:flex;align-items:center;gap:8px;}
.live-dot{width:7px;height:7px;border-radius:50%;background:var(--green);box-shadow:0 0 8px var(--green);}
.salary-chip{font-size:11px;font-weight:500;background:var(--green-bg);color:var(--green);padding:3px 8px;border-radius:20px;}

/* BOTTOM NAV */
.bnav{position:fixed;bottom:0;left:0;right:0;z-index:100;background:rgba(10,10,15,0.96);backdrop-filter:blur(20px);-webkit-backdrop-filter:blur(20px);border-top:0.5px solid var(--border);display:flex;height:calc(56px + var(--safe-bottom));padding-bottom:var(--safe-bottom);}
.nb{flex:1;display:flex;flex-direction:column;align-items:center;justify-content:center;gap:3px;background:none;border:none;cursor:pointer;color:var(--text3);font-size:10px;font-weight:500;font-family:'Inter',sans-serif;padding:6px 2px;transition:color .15s;}
.nb.active{color:var(--purple);}
.nb svg{width:20px;height:20px;}
.nb-label{font-size:9px;}

/* PAGES */
.page{display:none;padding:14px 16px;min-height:100%;}
.page.active{display:block;}

/* SECTION LABEL */
.sl{font-size:10px;font-weight:600;color:var(--text3);text-transform:uppercase;letter-spacing:.1em;margin:20px 0 10px;}
.sl:first-child{margin-top:0;}

/* METRIC GRID */
.mg{display:grid;grid-template-columns:1fr 1fr;gap:10px;margin-bottom:14px;}
.mg-3{grid-template-columns:1fr 1fr 1fr;}
.mc{background:var(--bg2);border:0.5px solid var(--border);border-radius:var(--r);padding:12px 14px;}
.mc-label{font-size:10px;color:var(--text3);margin-bottom:5px;font-weight:500;}
.mc-val{font-family:'JetBrains Mono',monospace;font-size:19px;font-weight:600;}
.mc-sub{font-size:10px;color:var(--text3);margin-top:2px;}

/* HERO CARD */
.hero{background:linear-gradient(135deg,#1a0a2e 0%,#0a1628 50%,#0a1a0f 100%);border:0.5px solid rgba(170,119,255,0.2);border-radius:var(--r);padding:18px;margin-bottom:14px;text-align:center;}
.hero-label{font-size:10px;color:var(--text3);text-transform:uppercase;letter-spacing:.1em;margin-bottom:6px;}
.hero-amount{font-family:'JetBrains Mono',monospace;font-size:38px;font-weight:700;color:var(--red);letter-spacing:-1px;}
.hero-sub{font-size:11px;color:var(--text3);margin-top:4px;}
.hero-bar{display:flex;gap:4px;margin-top:14px;height:5px;border-radius:5px;overflow:hidden;}

/* CARDS */
.card{background:var(--bg2);border:0.5px solid var(--border);border-radius:var(--r);padding:14px 16px;margin-bottom:10px;}
.card-danger{border-color:rgba(255,68,102,0.3);}
.card-warn{border-color:rgba(255,170,51,0.25);}
.card-ok{border-color:rgba(51,204,136,0.25);}

/* DUE CARD */
.due-card{background:var(--bg2);border:0.5px solid var(--border);border-radius:var(--r);padding:14px;margin-bottom:10px;display:flex;align-items:center;gap:12px;transition:all .2s;}
.due-card.paid{border-color:rgba(51,204,136,0.3);background:rgba(51,204,136,0.04);}
.tick{width:36px;height:36px;border-radius:50%;border:1.5px solid var(--border2);background:none;cursor:pointer;display:flex;align-items:center;justify-content:center;flex-shrink:0;transition:all .2s;font-size:16px;color:transparent;}
.tick.paid{background:var(--green);border-color:var(--green);color:var(--bg);}
.due-info{flex:1;min-width:0;}
.due-name{font-size:14px;font-weight:600;color:var(--text);}
.due-card.paid .due-name{text-decoration:line-through;color:var(--text3);}
.due-date{font-size:11px;color:var(--text3);margin-top:2px;}
.due-right{text-align:right;flex-shrink:0;}
.due-min{font-family:'JetBrains Mono',monospace;font-size:15px;font-weight:600;}
.due-bal{font-size:10px;color:var(--text3);margin-top:2px;}
.days-pill{display:inline-block;font-size:10px;font-weight:600;padding:2px 7px;border-radius:20px;margin-left:5px;}
.dp-red{background:var(--red-bg);color:var(--red);}
.dp-amb{background:var(--amber-bg);color:var(--amber);}
.dp-grn{background:var(--green-bg);color:var(--green);}

/* PROG */
.prog{height:3px;background:var(--bg4);border-radius:3px;margin-top:5px;overflow:hidden;}
.prog-f{height:3px;border-radius:3px;}

/* ROWS */
.row{display:flex;justify-content:space-between;align-items:center;padding:7px 0;border-bottom:0.5px solid var(--border);font-size:13px;}
.row:last-child{border-bottom:none;}
.rl{color:var(--text2);}
.rv{font-family:'JetBrains Mono',monospace;font-size:12px;font-weight:500;color:var(--text);}
.rv.red{color:var(--red);} .rv.grn{color:var(--green);} .rv.amb{color:var(--amber);} .rv.blu{color:var(--blue);}

/* PLAN CHIP */
.plan-chip{background:var(--bg3);border-radius:var(--r-xs);padding:8px 10px;margin-bottom:6px;}
.plan-chip-name{font-size:11px;color:var(--text3);margin-bottom:2px;}
.plan-chip-val{font-family:'JetBrains Mono',monospace;font-size:13px;font-weight:600;color:var(--text);}
.plan-chip-detail{font-size:10px;color:var(--text3);margin-top:2px;}

/* FORMS */
.form-group{margin-bottom:12px;}
.form-label{font-size:10px;font-weight:600;color:var(--text3);text-transform:uppercase;letter-spacing:.07em;margin-bottom:5px;display:block;}
.form-inp{width:100%;background:var(--bg3);border:0.5px solid var(--border2);border-radius:var(--r-sm);padding:12px 14px;font-family:'Inter',sans-serif;font-size:15px;color:var(--text);outline:none;-webkit-appearance:none;}
.form-inp:focus{border-color:var(--purple);}
.form-inp option{background:var(--bg3);}
.btn{width:100%;padding:14px;background:var(--purple);border:none;border-radius:var(--r-sm);font-family:'Inter',sans-serif;font-size:15px;font-weight:600;color:white;cursor:pointer;}
.btn:active{opacity:.8;}
.btn-sec{background:var(--bg3);border:0.5px solid var(--border2);color:var(--text2);}

/* PREDICTION */
.pred-card{background:var(--bg2);border:0.5px solid var(--border);border-radius:var(--r);padding:14px;margin-bottom:10px;}
.pred-title{font-size:13px;font-weight:600;margin-bottom:10px;}
.pred-total{background:var(--bg3);border-radius:var(--r-xs);padding:10px 12px;margin-top:8px;display:flex;justify-content:space-between;align-items:center;}

/* LOG */
.log-item{display:flex;align-items:center;padding:9px 0;border-bottom:0.5px solid var(--border);gap:10px;}
.log-item:last-child{border-bottom:none;}
.log-dot{width:7px;height:7px;border-radius:50%;flex-shrink:0;}
.log-info{flex:1;min-width:0;}
.log-name{font-size:12px;color:var(--text);}
.log-date{font-size:10px;color:var(--text3);}
.log-amt{font-family:'JetBrains Mono',monospace;font-size:12px;font-weight:600;white-space:nowrap;}
.del-btn{background:none;border:none;color:var(--text3);cursor:pointer;padding:4px 8px;font-size:13px;}

/* BAR CHART */
.bar-row{display:flex;align-items:center;gap:8px;margin-bottom:7px;}
.bar-lbl{font-size:10px;color:var(--text3);width:85px;flex-shrink:0;text-align:right;}
.bar-track{flex:1;height:16px;background:var(--bg4);border-radius:3px;overflow:hidden;}
.bar-fill{height:16px;border-radius:3px;display:flex;align-items:center;padding-left:5px;min-width:2px;}
.bar-val{font-size:10px;font-weight:600;color:rgba(255,255,255,0.85);white-space:nowrap;}

/* TIMELINE */
.tl-item{display:flex;gap:12px;padding:11px 0;border-bottom:0.5px solid var(--border);}
.tl-item:last-child{border-bottom:none;}
.tl-left{display:flex;flex-direction:column;align-items:center;}
.tl-dot{width:9px;height:9px;border-radius:50%;flex-shrink:0;margin-top:3px;}
.tl-line{width:1px;flex:1;background:var(--border);margin-top:3px;}
.tl-month{font-size:10px;font-weight:600;color:var(--text3);min-width:60px;margin-top:2px;}
.tl-desc{font-size:12px;color:var(--text);margin-bottom:3px;}
.tl-freed{font-family:'JetBrains Mono',monospace;font-size:12px;font-weight:600;color:var(--green);}
.tl-cum{font-size:10px;color:var(--text3);}

/* UPDATE */
.upd-row{display:flex;align-items:center;gap:8px;padding:9px 0;border-bottom:0.5px solid var(--border);}
.upd-row:last-child{border-bottom:none;}
.upd-label{flex:1;font-size:12px;color:var(--text2);}
.upd-cur{font-family:'JetBrains Mono',monospace;font-size:11px;color:var(--text3);width:55px;text-align:right;flex-shrink:0;}
.upd-inp{width:90px;background:var(--bg3);border:0.5px solid var(--border2);border-radius:var(--r-xs);padding:6px 8px;font-family:'JetBrains Mono',monospace;font-size:12px;color:var(--text);outline:none;flex-shrink:0;-webkit-appearance:none;}
.upd-inp:focus{border-color:var(--purple);}

/* CASHFLOW BARS */
.cf-bar-wrap{display:flex;gap:3px;align-items:flex-end;height:80px;margin-bottom:4px;}
.cf-bar{flex:1;border-radius:2px 2px 0 0;min-height:2px;}
.cf-labels{display:flex;gap:3px;}
.cf-lbl{flex:1;font-size:8px;color:var(--text3);text-align:center;overflow:hidden;}

/* PILLS */
.pill{font-size:10px;font-weight:500;padding:2px 7px;border-radius:20px;}
.pill-red{background:var(--red-bg);color:var(--red);}
.pill-grn{background:var(--green-bg);color:var(--green);}
.pill-amb{background:var(--amber-bg);color:var(--amber);}
.pill-blu{background:var(--blue-bg);color:var(--blue);}
.pill-pur{background:var(--purple-bg);color:var(--purple);}

/* DIVIDER */
.div{height:0.5px;background:var(--border);margin:14px 0;}

/* TOAST */
.toast{position:fixed;bottom:80px;left:50%;transform:translateX(-50%);background:var(--green);color:var(--bg);font-size:13px;font-weight:600;padding:10px 20px;border-radius:20px;z-index:200;opacity:0;transition:opacity .25s;pointer-events:none;white-space:nowrap;}
.toast.show{opacity:1;}

/* EMPTY */
.empty{text-align:center;padding:28px;color:var(--text3);font-size:13px;}

/* ALERT */
.alert{border:0.5px solid rgba(255,68,102,0.3);background:rgba(255,68,102,0.08);border-radius:var(--r);padding:12px 14px;margin-bottom:12px;}
.alert-t{font-size:12px;font-weight:600;color:var(--red);margin-bottom:4px;}
.alert-b{font-size:11px;color:var(--red);line-height:1.6;}

.upd-section{font-size:10px;font-weight:600;color:var(--purple);text-transform:uppercase;letter-spacing:.08em;padding:10px 0 4px;}
</style>
</head>
<body>

<div class="topbar">
  <div class="topbar-left">
    <div class="title">Ragil's Cards</div>
    <div class="sub" id="last-saved">Tap Settings to update</div>
  </div>
  <div class="topbar-right">
    <span class="salary-chip">9,000 AED</span>
    <div class="live-dot"></div>
  </div>
</div>

<!-- DUE PAGE -->
<div class="page active" id="page-due">
  <div class="sl">June 2026 — payment due</div>
  <div class="mg">
    <div class="mc"><div class="mc-label">Total min due</div><div class="mc-val" id="d-total" style="color:var(--red)">0</div><div class="mc-sub">AED this cycle</div></div>
    <div class="mc"><div class="mc-label">Still unpaid</div><div class="mc-val" id="d-unpaid" style="color:var(--amber)">0</div><div class="mc-sub">AED remaining</div></div>
  </div>
  <div id="due-list"></div>
  <div class="sl">After paying all dues</div>
  <div class="mg">
    <div class="mc"><div class="mc-label">Salary</div><div class="mc-val" style="color:var(--green)">9,000</div><div class="mc-sub">AED/month</div></div>
    <div class="mc"><div class="mc-label">Expenses</div><div class="mc-val" style="color:var(--amber)">5,350</div><div class="mc-sub">AED fixed</div></div>
    <div class="mc"><div class="mc-label">Free cash</div><div class="mc-val" style="color:var(--green)">3,650</div><div class="mc-sub">AED surplus</div></div>
    <div class="mc"><div class="mc-label">Cards budget</div><div class="mc-val" id="d-budget" style="color:var(--purple)">0</div><div class="mc-sub">AED for payments</div></div>
  </div>
</div>

<!-- TRACK PAGE -->
<div class="page" id="page-track">
  <div class="sl">Log purchase</div>
  <div class="card">
    <div class="form-group"><label class="form-label">Card used</label>
      <select id="pur-card" class="form-inp">
        <option value="NBD">Emirates NBD</option>
        <option value="EI">Emirates Islamic</option>
        <option value="CBD">CBD One</option>
        <option value="Mashreq">Mashreq Noon</option>
      </select>
    </div>
    <div class="form-group"><label class="form-label">Amount (AED)</label><input id="pur-amt" class="form-inp" type="number" inputmode="decimal" placeholder="0.00"></div>
    <div class="form-group"><label class="form-label">Description</label><input id="pur-desc" class="form-inp" type="text" placeholder="e.g. Supermarket"></div>
    <div class="form-group"><label class="form-label">Date</label><input id="pur-date" class="form-inp" type="date"></div>
    <button class="btn" onclick="addPurchase()">Add purchase</button>
  </div>
  <div class="sl">Log payment made</div>
  <div class="card">
    <div class="form-group"><label class="form-label">Card paid</label>
      <select id="pay-card" class="form-inp">
        <option value="NBD">Emirates NBD</option>
        <option value="EI">Emirates Islamic</option>
        <option value="CBD">CBD One</option>
        <option value="Mashreq">Mashreq Noon</option>
      </select>
    </div>
    <div class="form-group"><label class="form-label">Amount paid (AED)</label><input id="pay-amt" class="form-inp" type="number" inputmode="decimal" placeholder="0.00"></div>
    <div class="form-group"><label class="form-label">Date</label><input id="pay-date" class="form-inp" type="date"></div>
    <button class="btn" onclick="addPayment()">Log payment</button>
  </div>
  <div class="sl">This cycle</div>
  <div class="card"><div id="cycle-log"><div class="empty">Nothing logged yet</div></div></div>
  <div class="sl">Next month prediction</div>
  <div id="predictions"></div>
</div>

<!-- OVERVIEW PAGE -->
<div class="page" id="page-overview">
  <div class="hero">
    <div class="hero-label">Total outstanding debt</div>
    <div class="hero-amount" id="ov-total">0</div>
    <div class="hero-sub" id="ov-sub">June 2026</div>
    <div class="hero-bar" id="ov-bar"></div>
  </div>
  <div class="mg">
    <div class="mc"><div class="mc-label">Monthly interest</div><div class="mc-val" id="ov-int" style="color:var(--red)">0</div><div class="mc-sub">AED burning/month</div></div>
    <div class="mc"><div class="mc-label">Monthly EMIs</div><div class="mc-val" id="ov-emi" style="color:var(--amber)">0</div><div class="mc-sub">AED structured</div></div>
    <div class="mc"><div class="mc-label">Revolving debt</div><div class="mc-val" id="ov-rev" style="color:var(--red)">0</div><div class="mc-sub">AED @ 43.37%</div></div>
    <div class="mc"><div class="mc-label">Free cash/month</div><div class="mc-val" style="color:var(--green)">3,650</div><div class="mc-sub">AED surplus</div></div>
  </div>
  <div class="sl">Interest by plan</div>
  <div class="card"><div id="int-bars"></div></div>
  <div class="sl">EMI freedom timeline</div>
  <div class="card"><div id="tl-list"></div></div>
</div>

<!-- CARDS PAGE -->
<div class="page" id="page-cards">
  <div id="cards-list"></div>
</div>

<!-- SETTINGS PAGE -->
<div class="page" id="page-settings">
  <div class="sl">Update balances</div>
  <div class="card">
    <div class="upd-section">Emirates NBD</div>
    <div id="upd-rows-nbd"></div>
    <div class="upd-section">Emirates Islamic</div>
    <div id="upd-rows-ei"></div>
    <div class="upd-section">CBD One</div>
    <div id="upd-rows-cbd"></div>
    <div class="upd-section">Mashreq Noon</div>
    <div id="upd-rows-mash"></div>
    <div style="margin-top:14px;"><button class="btn" onclick="applyUpdates()">Save & refresh all</button></div>
  </div>
  <div class="sl">Cashflow forecast</div>
  <div class="card">
    <div style="font-size:11px;color:var(--text3);margin-bottom:10px;">Net cash after expenses + EMIs (green = surplus)</div>
    <div class="cf-bar-wrap" id="cf-bars"></div>
    <div class="cf-labels" id="cf-labels"></div>
    <div style="margin-top:10px;display:flex;gap:12px;font-size:10px;color:var(--text3);">
      <span style="display:flex;align-items:center;gap:4px;"><span style="width:8px;height:8px;border-radius:2px;background:var(--green);"></span>Surplus</span>
      <span style="display:flex;align-items:center;gap:4px;"><span style="width:8px;height:8px;border-radius:2px;background:var(--red);"></span>Deficit</span>
    </div>
  </div>
  <div class="sl">About</div>
  <div class="card" style="font-size:11px;color:var(--text3);line-height:1.8;">
    <div>Revolving rate: 43.37% p.a. (3.614%/mo)</div>
    <div>CBD EPP rate: 26.25% p.a. (2.188%/mo)</div>
    <div>NBD EPP1: 19.33% p.a. · NBD EPP2: 31.52% p.a.</div>
    <div>EI EMI2 (Scholars): 0% · EI MoI EPP: 0%</div>
    <div style="margin-top:8px;color:var(--purple);">Salary: 9,000 AED · Expenses: 5,350 AED · Free cash: 3,650 AED</div>
    <div style="margin-top:8px;color:var(--amber);">⚠️ NBD is maxed (0 available). Stop all card spending. Use debit only.</div>
  </div>
</div>

<!-- BOTTOM NAV -->
<nav class="bnav">
  <button class="nb active" onclick="showPage('due',this)">
    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><rect x="3" y="4" width="18" height="18" rx="2"/><line x1="16" y1="2" x2="16" y2="6"/><line x1="8" y1="2" x2="8" y2="6"/><line x1="3" y1="10" x2="21" y2="10"/></svg>
    <span class="nb-label">Due</span>
  </button>
  <button class="nb" onclick="showPage('track',this)">
    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><line x1="12" y1="5" x2="12" y2="19"/><line x1="5" y1="12" x2="19" y2="12"/></svg>
    <span class="nb-label">Track</span>
  </button>
  <button class="nb" onclick="showPage('overview',this)">
    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><polyline points="22 12 18 12 15 21 9 3 6 12 2 12"/></svg>
    <span class="nb-label">Overview</span>
  </button>
  <button class="nb" onclick="showPage('cards',this)">
    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><rect x="1" y="4" width="22" height="16" rx="2"/><line x1="1" y1="10" x2="23" y2="10"/></svg>
    <span class="nb-label">Cards</span>
  </button>
  <button class="nb" onclick="showPage('settings',this)">
    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><circle cx="12" cy="12" r="3"/><path d="M19.07 4.93a10 10 0 0 1 0 14.14M4.93 4.93a10 10 0 0 0 0 14.14"/></svg>
    <span class="nb-label">Settings</span>
  </button>
</nav>

<div class="toast" id="toast"></div>

<script>
const REVOLVE = 0.03614;
const SALARY = 9000, EXPENSES = 5350;

// JUNE 2026 DATA
const DEFAULT = {
  nbd: {
    revolving: 13558, // ~16500 - epps
    epp1: {bal:1442.38, emi:738.70, months:2, rate:0.01610, name:'EPP 1 (Retail)'},
    epp2: {bal:449.52, emi:157.76, months:3, rate:0.02626, name:'EPP 2 (MoI)'},
    limit:16500, avail:158.35, outstanding:15500.04
  },
  ei: {
    revolving: 11149, // outstanding - emis
    moi: {bal:1078.78, emi:154.11, months:7, rate:0, name:'MoI EPP (0%)'},
    motoray: {bal:276.17, emi:138.07, months:2, rate:0.03022, name:'Motor Ray'},
    scholars: {bal:1096.68, emi:137.08, months:8, rate:0, name:'Scholars (0%)'},
    safari: {bal:174.86, emi:87.41, months:2, rate:0.03022, name:'Safari'},
    limit:16500, avail:2749.35, outstanding:13750.65
  },
  cbd: {
    epp: {bal:11402.77, emi:626.95, months:16, rate:0.02188, name:'Cash on Call EPP'},
    limit:16500, avail:5097.23, outstanding:11402.77
  },
  mash: {
    revolving: 3494.99,
    rbt: {bal:710.31, emi:35.52, months:5, rate:0, name:'RBT (0%)'},
    limit:5500, avail:1294.71, outstanding:4205.30
  }
};

const DUE = [
  {key:'CBD', name:'CBD One', dueDay:30, dueMo:5, min:626.95, bal:11402.77, limit:16500},
  {key:'Mashreq', name:'Mashreq Noon', dueDay:3, dueMo:6, min:210.27, bal:4205.30, limit:5500},
  {key:'EI', name:'Emirates Islamic', dueDay:5, dueMo:6, min:1047.85, bal:13750.65, limit:16500},
  {key:'NBD', name:'Emirates NBD', dueDay:11, dueMo:6, min:1532.04, bal:15500.04, limit:16500},
];
const MONTHS_SHORT = ['Jan','Feb','Mar','Apr','May','Jun','Jul','Aug','Sep','Oct','Nov','Dec'];
const CARD_CLR = {NBD:'#4499ff', EI:'#aa77ff', CBD:'#33cc88', Mashreq:'#ffaa33'};

function loadState(){
  try{ const r=localStorage.getItem('ragil_v3'); if(r) return JSON.parse(r); }catch(e){}
  return {data:JSON.parse(JSON.stringify(DEFAULT)), paid:{CBD:false,EI:false,Mashreq:false,NBD:false}, purchases:[], payments:[], saved:null};
}
function saveState(){
  state.saved = new Date().toISOString();
  localStorage.setItem('ragil_v3', JSON.stringify(state));
  document.getElementById('last-saved').textContent = 'Saved ' + new Date().toLocaleTimeString([],{hour:'2-digit',minute:'2-digit'});
}
let state = loadState();
if(state.saved) document.getElementById('last-saved').textContent = 'Updated ' + new Date(state.saved).toLocaleDateString('en-AE');

function fmt(n){ return Math.round(n).toLocaleString('en-AE'); }
function fmt2(n){ return Number(n).toLocaleString('en-AE',{minimumFractionDigits:2,maximumFractionDigits:2}); }
function showToast(m){ const t=document.getElementById('toast'); t.textContent=m; t.classList.add('show'); setTimeout(()=>t.classList.remove('show'),2000); }

function daysUntil(day, mo0){
  const now=new Date(), yr=now.getFullYear();
  let d=new Date(yr,mo0,day);
  if(d<now) d=new Date(yr+1,mo0,day);
  return Math.round((d-now)/86400000);
}
function daysPill(d){
  if(d<0) return `<span class="days-pill dp-red">Overdue</span>`;
  if(d===0) return `<span class="days-pill dp-red">Today!</span>`;
  if(d<=3) return `<span class="days-pill dp-red">${d}d left</span>`;
  if(d<=7) return `<span class="days-pill dp-amb">${d}d left</span>`;
  return `<span class="days-pill dp-grn">${d}d left</span>`;
}
function utilClr(p){ return p>85?'var(--red)':p>65?'var(--amber)':'var(--green)'; }

// ─── DUE ────────────────────────────────────────
function renderDue(){
  const sorted=[...DUE].sort((a,b)=>daysUntil(a.dueDay,a.dueMo)-daysUntil(b.dueDay,b.dueMo));
  const totalMin=DUE.reduce((s,c)=>s+c.min,0);
  const paid=DUE.filter(c=>state.paid[c.key]).reduce((s,c)=>s+c.min,0);
  document.getElementById('d-total').textContent=fmt2(totalMin);
  document.getElementById('d-unpaid').textContent=fmt2(totalMin-paid);
  document.getElementById('d-budget').textContent=fmt(SALARY-EXPENSES);

  document.getElementById('due-list').innerHTML=sorted.map(c=>{
    const days=daysUntil(c.dueDay,c.dueMo);
    const isPaid=state.paid[c.key];
    const util=Math.round(c.bal/c.limit*100);
    return `<div class="due-card ${isPaid?'paid':''}">
      <button class="tick ${isPaid?'paid':''}" onclick="togglePaid('${c.key}')">✓</button>
      <div class="due-info">
        <div class="due-name">${c.name}</div>
        <div class="due-date">${c.dueDay} ${MONTHS_SHORT[c.dueMo]} ${daysPill(days)}</div>
        <div class="prog" style="width:100px;margin-top:5px;"><div class="prog-f" style="width:${util}%;background:${utilClr(util)};"></div></div>
        <div style="font-size:10px;color:var(--text3);margin-top:2px;">Util ${util}%</div>
      </div>
      <div class="due-right">
        <div class="due-min" style="color:${isPaid?'var(--green)':'var(--red)'};">${fmt2(c.min)}</div>
        <div class="due-bal">AED min due</div>
      </div>
    </div>`;
  }).join('');
}
function togglePaid(k){ state.paid[k]=!state.paid[k]; saveState(); renderDue(); showToast(state.paid[k]?'✓ Marked paid':'Marked unpaid'); }

// ─── TRACK ────────────────────────────────────────
function setDates(){ const t=new Date().toISOString().slice(0,10); document.getElementById('pur-date').value=t; document.getElementById('pay-date').value=t; }
setDates();
function addPurchase(){
  const card=document.getElementById('pur-card').value;
  const amt=parseFloat(document.getElementById('pur-amt').value);
  const desc=document.getElementById('pur-desc').value.trim()||'Purchase';
  const date=document.getElementById('pur-date').value;
  if(!amt||amt<=0){showToast('Enter amount');return;}
  state.purchases.push({card,amt,desc,date,id:Date.now()});
  document.getElementById('pur-amt').value='';
  document.getElementById('pur-desc').value='';
  saveState(); renderCycleLog(); renderPredictions();
  showToast('Added ✓');
}
function addPayment(){
  const card=document.getElementById('pay-card').value;
  const amt=parseFloat(document.getElementById('pay-amt').value);
  const date=document.getElementById('pay-date').value;
  if(!amt||amt<=0){showToast('Enter amount');return;}
  state.payments.push({card,amt,date,id:Date.now()});
  document.getElementById('pay-amt').value='';
  saveState(); renderCycleLog(); renderPredictions();
  showToast('Logged ✓');
}
function delPur(id){state.purchases=state.purchases.filter(p=>p.id!==id);saveState();renderCycleLog();renderPredictions();}
function delPay(id){state.payments=state.payments.filter(p=>p.id!==id);saveState();renderCycleLog();renderPredictions();}

function renderCycleLog(){
  const all=[...state.purchases.map(p=>({...p,type:'pur'})),...state.payments.map(p=>({...p,type:'pay'}))].sort((a,b)=>(b.date||'').localeCompare(a.date||''));
  if(!all.length){document.getElementById('cycle-log').innerHTML='<div class="empty">Nothing logged yet</div>';return;}
  document.getElementById('cycle-log').innerHTML=all.map(x=>`
    <div class="log-item">
      <div class="log-dot" style="background:${CARD_CLR[x.card]||'#888'};"></div>
      <div class="log-info">
        <div class="log-name">${x.type==='pur'?x.desc:'Payment'} · ${x.card}</div>
        <div class="log-date">${x.date}</div>
      </div>
      <div class="log-amt" style="color:${x.type==='pur'?'var(--red)':'var(--green)'};">${x.type==='pur'?'+':'-'}${fmt2(x.amt)}</div>
      <button class="del-btn" onclick="${x.type==='pur'?'delPur':'delPay'}(${x.id})">✕</button>
    </div>`).join('');
}

function getRevBal(key){
  const d=state.data;
  if(key==='NBD') return d.nbd.revolving;
  if(key==='EI') return d.ei.revolving;
  if(key==='Mashreq') return d.mash.revolving;
  return 0;
}
function getOutstanding(key){
  const d=state.data;
  if(key==='NBD') return d.nbd.outstanding;
  if(key==='EI') return d.ei.outstanding;
  if(key==='CBD') return d.cbd.outstanding;
  return d.mash.outstanding;
}

function renderPredictions(){
  const cards=[
    {key:'NBD',name:'Emirates NBD',dueDay:11,dueMo:'Jul'},
    {key:'EI',name:'Emirates Islamic',dueDay:5,dueMo:'Jul'},
    {key:'CBD',name:'CBD One',dueDay:30,dueMo:'Jun'},
    {key:'Mashreq',name:'Mashreq Noon',dueDay:3,dueMo:'Jul'},
  ];
  document.getElementById('predictions').innerHTML=cards.map(c=>{
    const bought=state.purchases.filter(p=>p.card===c.key).reduce((s,p)=>s+p.amt,0);
    const paid=state.payments.filter(p=>p.card===c.key).reduce((s,p)=>s+p.amt,0);
    const rev=getRevBal(c.key);
    const newRev=Math.max(0,rev+bought-paid);
    const interest=Math.round(newRev*REVOLVE*100)/100;
    const cur=getOutstanding(c.key);
    const predicted=Math.max(0,cur+bought-paid+interest);
    const diff=predicted-cur;
    return `<div class="pred-card">
      <div class="pred-title" style="color:${CARD_CLR[c.key]};">${c.name}</div>
      <div class="row"><span class="rl">Current balance</span><span class="rv">${fmt2(cur)}</span></div>
      <div class="row"><span class="rl">+ Purchases</span><span class="rv red">+${fmt2(bought)}</span></div>
      <div class="row"><span class="rl">− Payments</span><span class="rv grn">−${fmt2(paid)}</span></div>
      <div class="row"><span class="rl">+ Interest</span><span class="rv amb">+${fmt2(interest)}</span></div>
      <div class="pred-total">
        <span style="font-size:11px;color:var(--text3);">Predicted balance</span>
        <span style="font-family:'JetBrains Mono',monospace;font-weight:600;color:${diff>0?'var(--red)':'var(--green)'};">${fmt2(predicted)} <span style="font-size:10px;">(${diff>=0?'+':''}${fmt(Math.round(diff))})</span></span>
      </div>
      <div style="font-size:10px;color:var(--text3);margin-top:6px;">Due ${c.dueDay} ${c.dueMo}</div>
    </div>`;
  }).join('');
}

// ─── OVERVIEW ────────────────────────────────────────
function totalDebt(){
  const d=state.data;
  return d.nbd.outstanding+d.ei.outstanding+d.cbd.outstanding+d.mash.outstanding;
}
function totalInterest(){
  const d=state.data;
  return Math.round(
    d.nbd.revolving*REVOLVE + d.ei.revolving*REVOLVE + d.mash.revolving*REVOLVE +
    d.nbd.epp1.bal*d.nbd.epp1.rate + d.nbd.epp2.bal*d.nbd.epp2.rate +
    d.ei.motoray.bal*d.ei.motoray.rate + d.ei.safari.bal*d.ei.safari.rate +
    d.cbd.epp.bal*d.cbd.epp.rate
  );
}
function totalEMI(){
  const d=state.data;
  return d.nbd.epp1.emi+d.nbd.epp2.emi+d.ei.moi.emi+d.ei.motoray.emi+d.ei.scholars.emi+d.ei.safari.emi+d.cbd.epp.emi+d.mash.rbt.emi;
}
function totalRevolving(){
  const d=state.data;
  return d.nbd.revolving+d.ei.revolving+d.mash.revolving;
}

function renderOverview(){
  const total=totalDebt(), interest=totalInterest(), emi=totalEMI(), rev=totalRevolving();
  const d=state.data;
  document.getElementById('ov-total').textContent=fmt(Math.round(total))+' AED';
  document.getElementById('ov-sub').textContent='June 2026 — '+new Date().toLocaleDateString('en-AE',{month:'long'});
  document.getElementById('ov-int').textContent=fmt(interest);
  document.getElementById('ov-emi').textContent=fmt(Math.round(emi));
  document.getElementById('ov-rev').textContent=fmt(Math.round(rev));

  const bar=document.getElementById('ov-bar');
  bar.innerHTML=[
    {v:rev,c:'#ff4466'},{v:d.cbd.epp.bal,c:'#33cc88'},
    {v:d.nbd.epp1.bal+d.nbd.epp2.bal,c:'#4499ff'},{v:d.ei.moi.bal+d.ei.scholars.bal+d.ei.motoray.bal+d.ei.safari.bal,c:'#aa77ff'}
  ].map(s=>`<div style="flex:${Math.max(s.v,1)};background:${s.c};border-radius:3px;"></div>`).join('');

  const idata=[
    {l:'NBD revolving',v:Math.round(d.nbd.revolving*REVOLVE),c:'#ff4466'},
    {l:'EI revolving',v:Math.round(d.ei.revolving*REVOLVE),c:'#cc3355'},
    {l:'Mashreq rev.',v:Math.round(d.mash.revolving*REVOLVE),c:'#ffaa33'},
    {l:'CBD EPP',v:Math.round(d.cbd.epp.bal*d.cbd.epp.rate),c:'#33cc88'},
    {l:'NBD EPP1',v:Math.round(d.nbd.epp1.bal*d.nbd.epp1.rate),c:'#4499ff'},
    {l:'EI Motor Ray',v:Math.round(d.ei.motoray.bal*d.ei.motoray.rate),c:'#aa77ff'},
  ];
  const maxV=Math.max(...idata.map(r=>r.v));
  document.getElementById('int-bars').innerHTML=idata.map(r=>`
    <div class="bar-row">
      <div class="bar-lbl">${r.l}</div>
      <div class="bar-track"><div class="bar-fill" style="width:${Math.round(r.v/maxV*100)}%;background:${r.c};"><span class="bar-val">${r.v} AED</span></div></div>
    </div>`).join('');

  const events=[
    {m:'Aug 2026',desc:'NBD EPP1 + EI Safari + Motor Ray end',freed:964,c:'#4499ff'},
    {m:'Sep 2026',desc:'NBD EPP2 ends',freed:158,c:'#33cc88'},
    {m:'Nov 2026',desc:'Mashreq RBT ends',freed:36,c:'#ffaa33'},
    {m:'Jan 2027',desc:'EI MoI EPP (0%) ends',freed:154,c:'#aa77ff'},
    {m:'Feb 2027',desc:'EI Scholars (0%) ends',freed:137,c:'#9966ff'},
    {m:'Oct 2027',desc:'CBD EPP ends — debt free!',freed:627,c:'#33cc88'},
  ];
  let cum=0;
  document.getElementById('tl-list').innerHTML=events.map((e,i)=>{cum+=e.freed;return`
    <div class="tl-item">
      <div class="tl-left"><div class="tl-dot" style="background:${e.c};"></div>${i<events.length-1?'<div class="tl-line"></div>':''}</div>
      <div>
        <div class="tl-month">${e.m}</div>
        <div class="tl-desc">${e.desc}</div>
        <div class="tl-freed">+${fmt(e.freed)} AED/month freed</div>
        <div class="tl-cum">Cumulative relief: +${fmt(cum)} AED/mo</div>
      </div>
    </div>`;}).join('');
}

// ─── CARDS ────────────────────────────────────────
function renderCards(){
  const d=state.data;
  const plans=[
    {name:'NBD Revolving',bank:'Emirates NBD',bal:d.nbd.revolving,emi:'Open',mo:'Open',rate:'43.37%',int:Math.round(d.nbd.revolving*REVOLVE),p:'high',c:'#ff4466'},
    {name:'NBD EPP 1',bank:'Emirates NBD',bal:d.nbd.epp1.bal,emi:d.nbd.epp1.emi,mo:d.nbd.epp1.months,rate:'19.33%',int:Math.round(d.nbd.epp1.bal*d.nbd.epp1.rate),p:'med',c:'#4499ff'},
    {name:'NBD EPP 2 (MoI)',bank:'Emirates NBD',bal:d.nbd.epp2.bal,emi:d.nbd.epp2.emi,mo:d.nbd.epp2.months,rate:'31.52%',int:Math.round(d.nbd.epp2.bal*d.nbd.epp2.rate),p:'med',c:'#6699ff'},
    {name:'EI Revolving',bank:'Emirates Islamic',bal:d.ei.revolving,emi:'Open',mo:'Open',rate:'43.37%',int:Math.round(d.ei.revolving*REVOLVE),p:'high',c:'#aa77ff'},
    {name:'EI MoI EPP (0%)',bank:'Emirates Islamic',bal:d.ei.moi.bal,emi:d.ei.moi.emi,mo:d.ei.moi.months,rate:'0%',int:0,p:'low',c:'#33cc88'},
    {name:'EI Scholars (0%)',bank:'Emirates Islamic',bal:d.ei.scholars.bal,emi:d.ei.scholars.emi,mo:d.ei.scholars.months,rate:'0%',int:0,p:'low',c:'#55dd99'},
    {name:'EI Motor Ray',bank:'Emirates Islamic',bal:d.ei.motoray.bal,emi:d.ei.motoray.emi,mo:d.ei.motoray.months,rate:'36.27%',int:Math.round(d.ei.motoray.bal*d.ei.motoray.rate),p:'med',c:'#9955ff'},
    {name:'EI Safari',bank:'Emirates Islamic',bal:d.ei.safari.bal,emi:d.ei.safari.emi,mo:d.ei.safari.months,rate:'36.26%',int:Math.round(d.ei.safari.bal*d.ei.safari.rate),p:'med',c:'#cc88ff'},
    {name:'CBD EPP',bank:'CBD One',bal:d.cbd.epp.bal,emi:d.cbd.epp.emi,mo:d.cbd.epp.months,rate:'26.25%',int:Math.round(d.cbd.epp.bal*d.cbd.epp.rate),p:'med',c:'#33cc88'},
    {name:'Mashreq Revolving',bank:'Mashreq Noon',bal:d.mash.revolving,emi:'Open',mo:'Open',rate:'43.37%',int:Math.round(d.mash.revolving*REVOLVE),p:'high',c:'#ffaa33'},
    {name:'Mashreq RBT (0%)',bank:'Mashreq Noon',bal:d.mash.rbt.bal,emi:d.mash.rbt.emi,mo:d.mash.rbt.months,rate:'0%',int:0,p:'low',c:'#ffcc77'},
  ];
  const pC={'high':'pill-red','med':'pill-amb','low':'pill-grn'};
  const pL={'high':'High','med':'Medium','low':'0% — Low'};
  document.getElementById('cards-list').innerHTML=plans.map(p=>`
    <div class="card" style="margin-bottom:10px;">
      <div style="display:flex;justify-content:space-between;align-items:flex-start;margin-bottom:10px;">
        <div><div style="font-size:13px;font-weight:600;color:var(--text);">${p.name}</div><div style="font-size:10px;color:var(--text3);margin-top:1px;">${p.bank}</div></div>
        <div style="text-align:right;"><div style="font-family:'JetBrains Mono',monospace;font-size:15px;font-weight:600;color:${p.c};">${fmt(Math.round(p.bal))}</div><div style="font-size:10px;color:var(--text3);">AED</div></div>
      </div>
      <div style="display:flex;flex-wrap:wrap;gap:6px;">
        <div class="plan-chip" style="flex:1;min-width:80px;"><div class="plan-chip-name">EMI/month</div><div class="plan-chip-val">${typeof p.emi==='number'?fmt2(p.emi)+' AED':p.emi}</div></div>
        <div class="plan-chip" style="flex:1;min-width:60px;"><div class="plan-chip-name">Months left</div><div class="plan-chip-val">${p.mo}</div></div>
        <div class="plan-chip" style="flex:1;min-width:80px;"><div class="plan-chip-name">Mo. interest</div><div class="plan-chip-val" style="color:${p.int>200?'var(--red)':p.int>50?'var(--amber)':'var(--green)'};">${p.int>0?p.int+' AED':'—'}</div></div>
        <div class="plan-chip" style="flex:1;min-width:60px;"><div class="plan-chip-name">Rate p.a.</div><div class="plan-chip-val">${p.rate}</div></div>
      </div>
      <div style="margin-top:8px;"><span class="pill ${pC[p.p]}">${pL[p.p]} priority</span></div>
    </div>`).join('');
}

// ─── SETTINGS ────────────────────────────────────────
const UPD_FIELDS = {
  nbd: [
    {k:'nbd.revolving', l:'Revolving balance'},
    {k:'nbd.epp1.bal', l:'EPP 1 principal'},
    {k:'nbd.epp2.bal', l:'EPP 2 principal'},
    {k:'nbd.outstanding', l:'Total outstanding'},
  ],
  ei: [
    {k:'ei.revolving', l:'Revolving balance'},
    {k:'ei.moi.bal', l:'MoI EPP principal'},
    {k:'ei.motoray.bal', l:'Motor Ray principal'},
    {k:'ei.scholars.bal', l:'Scholars principal'},
    {k:'ei.safari.bal', l:'Safari principal'},
    {k:'ei.outstanding', l:'Total outstanding'},
  ],
  cbd: [
    {k:'cbd.epp.bal', l:'EPP principal'},
    {k:'cbd.outstanding', l:'Total outstanding'},
  ],
  mash: [
    {k:'mash.revolving', l:'Revolving balance'},
    {k:'mash.rbt.bal', l:'RBT principal'},
    {k:'mash.outstanding', l:'Total outstanding'},
  ]
};
function getN(obj,path){return path.split('.').reduce((o,k)=>o[k],obj);}
function setN(obj,path,val){const keys=path.split('.');const last=keys.pop();keys.reduce((o,k)=>o[k],obj)[last]=val;}

function renderUpdate(){
  ['nbd','ei','cbd','mash'].forEach(card=>{
    document.getElementById('upd-rows-'+card).innerHTML=UPD_FIELDS[card].map(f=>`
      <div class="upd-row">
        <div class="upd-label">${f.l}</div>
        <div class="upd-cur">${fmt(Math.round(getN(state.data,f.k)))}</div>
        <input class="upd-inp" type="number" inputmode="decimal" id="upd-${f.k.replace(/\./g,'-')}" value="${Math.round(getN(state.data,f.k))}">
      </div>`).join('');
  });
  renderCF();
}

function applyUpdates(){
  Object.values(UPD_FIELDS).flat().forEach(f=>{
    const el=document.getElementById('upd-'+f.k.replace(/\./g,'-'));
    const v=parseFloat(el.value);
    if(!isNaN(v)&&v>=0) setN(state.data,f.k,v);
  });
  saveState(); renderUpdate();
  renderOverview(); renderCards(); renderPredictions(); renderDue();
  showToast('All updated ✓');
}

function renderCF(){
  const months=['Jul','Aug','Sep','Oct','Nov','Dec','Jan27','Feb','Mar','Apr','May','Jun','Jul','Oct27'];
  const emis=[1740,776,619,584,584,584,447,310,310,310,310,310,310,0];
  const nets=emis.map(e=>SALARY-EXPENSES-e);
  const maxAbs=Math.max(...nets.map(Math.abs));
  document.getElementById('cf-bars').innerHTML=nets.map((v,i)=>{
    const h=Math.max(Math.round(Math.abs(v)/maxAbs*72),2);
    const pos=v>=0;
    return `<div style="flex:1;display:flex;flex-direction:column;align-items:center;justify-content:${pos?'flex-end':'flex-start'};height:80px;">
      <div class="cf-bar" style="height:${h}px;background:${pos?'var(--green)':'var(--red)'};width:100%;"></div>
    </div>`;
  }).join('');
  document.getElementById('cf-labels').innerHTML=months.map(m=>`<div class="cf-lbl">${m}</div>`).join('');
}

// ─── PAGE ROUTING ────────────────────────────────────────
function showPage(name,btn){
  document.querySelectorAll('.page').forEach(p=>p.classList.remove('active'));
  document.querySelectorAll('.nb').forEach(b=>b.classList.remove('active'));
  document.getElementById('page-'+name).classList.add('active');
  btn.classList.add('active');
  window.scrollTo(0,0);
  if(name==='due') renderDue();
  if(name==='track'){renderCycleLog();renderPredictions();}
  if(name==='overview') renderOverview();
  if(name==='cards') renderCards();
  if(name==='settings') renderUpdate();
}

// INIT
renderDue();
renderPredictions();
</script>
</body>
</html>
