<!DOCTYPE html>
<html lang="en"><head><meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Prorate Calculator</title>
<style>
/* ---------- Design tokens: vibrant gradient aesthetic matching the reference ---------- */
:root{
  --canvas-bg: #0b0c1e;
  --card: #ffffff;
  --ink: #1e1b4b;
  --mut: #64748b;
  --line: #e2e8f0;
  --line-light: #f1f5f9;
  --field: #f8fafc;
  --field-focus: #ffffff;
  
  /* Primary & Accent Gradients */
  --grad-primary: linear-gradient(90deg, #4f46e5 0%, #7c3aed 45%, #c026d3 75%, #db2777 100%);
  --grad-badge: linear-gradient(135deg, #6366f1 0%, #a855f7 50%, #ec4899 100%);
  --grad-green: linear-gradient(135deg, #059669 0%, #10b981 100%);
  --grad-teal: linear-gradient(90deg, #0d9488 0%, #059669 50%, #0284c7 100%);
  
  /* Solid Accents */
  --brand: #6366f1;
  --brand-d: #4f46e5;
  --brand-bg: #f5f3ff;
  --brand-border: #ddd6fe;
  --on-brand: #ffffff;
  
  --disc: #059669;
  --disc-d: #047857;
  --disc-bg: #ecfdf5;
  --disc-border: #a7f3d0;
  
  --tax: #d97706;
  --tax-d: #b45309;
  --tax-bg: #fffbeb;
  --tax-border: #fde68a;
  
  --bad: #e11d48;
  --bad-bg: #fff1f2;
  --bad-border: #fecdd3;

  box-sizing: border-box;
  padding-top: env(safe-area-inset-top, 0px);
  padding-bottom: env(safe-area-inset-bottom, 0px);
}

html{scroll-padding-top:env(safe-area-inset-top,0px)}
*{box-sizing:border-box}

/* Atmospheric Cosmic Glowing Background */
body{
  margin: 0;
  background-color: var(--canvas-bg);
  background-image: 
    radial-gradient(circle at 10% 25%, rgba(219, 39, 119, 0.42) 0%, transparent 45%),
    radial-gradient(circle at 90% 35%, rgba(59, 130, 246, 0.38) 0%, transparent 45%),
    radial-gradient(circle at 50% 90%, rgba(139, 92, 246, 0.32) 0%, transparent 50%),
    radial-gradient(circle at 30% 70%, rgba(16, 185, 129, 0.15) 0%, transparent 40%);
  background-attachment: fixed;
  color: var(--ink);
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  padding: 40px 18px;
  line-height: 1.5;
  -webkit-font-smoothing: antialiased;
}

/* Floating White Main Container */
.box{
  max-width: 1040px;
  margin: auto;
  background: var(--card);
  border-radius: 28px;
  box-shadow: 0 25px 60px -12px rgba(0, 0, 0, 0.55), 0 0 0 1px rgba(255, 255, 255, 0.15);
  overflow: hidden;
}

/* Clean Header with Vibrant Gradient Title */
.hero{
  background: #ffffff;
  padding: 32px 36px 16px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 16px;
  border-bottom: 1px solid var(--line-light);
}

.hero h1{
  font-size: 32px;
  margin: 0 0 6px;
  font-weight: 800;
  letter-spacing: -0.025em;
  background: var(--grad-primary);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  display: inline-block;
}

.hero .sub{
  color: var(--mut);
  margin: 0;
  font-size: 15px;
  font-weight: 400;
}

.in{
  padding: 24px 36px 36px;
}

/* Step Headings with Radiant Rounded Badges */
.step{
  display: flex;
  align-items: center;
  gap: 12px;
  font-weight: 700;
  margin: 32px 0 16px;
  font-size: 17px;
  color: #1e1b4b;
  letter-spacing: -0.01em;
}

.step:first-child{margin-top: 10px}

.step i{
  font-style: normal;
  width: 32px;
  height: 32px;
  border-radius: 10px;
  background: var(--grad-badge);
  color: #ffffff;
  display: grid;
  place-items: center;
  font-size: 14px;
  font-weight: 800;
  box-shadow: 0 4px 12px rgba(168, 85, 247, 0.4);
}

/* Form Controls & Step 1 Cards */
.set{
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 16px;
  margin-bottom: 8px;
}

.set>div{
  background: #ffffff;
  border: 1.5px solid #e2e8f0;
  border-radius: 18px;
  padding: 18px 20px;
  box-shadow: 0 4px 14px rgba(15, 23, 42, 0.03);
  transition: transform 0.15s ease, box-shadow 0.15s ease, border-color 0.15s ease;
}

.set>div:hover{
  border-color: #cbd5e1;
  box-shadow: 0 8px 20px rgba(99, 102, 241, 0.08);
}

label{
  display: block;
  font-size: 13.5px;
  font-weight: 700;
  margin-bottom: 8px;
  color: #334155;
  letter-spacing: -0.01em;
}

input, select{
  width: 100%;
  padding: 11px 14px;
  border: 1.5px solid #e2e8f0;
  border-radius: 12px;
  font: inherit;
  font-size: 14.5px;
  background: var(--field);
  color: var(--ink);
  transition: all 0.2s ease;
}

input:hover, select:hover{
  border-color: #cbd5e1;
}

input:focus, select:focus, button:focus-visible{
  outline: none;
  background: var(--field-focus);
  border-color: #7c3aed;
  box-shadow: 0 0 0 3.5px rgba(124, 58, 237, 0.16);
}

input.bad{
  border-color: var(--bad) !important;
  background: var(--bad-bg) !important;
  color: var(--bad) !important;
}

.hint{
  font-size: 13px;
  color: var(--mut);
  margin: 6px 0 0;
}

.ev{
  display: block;
  font-size: 12.5px;
  font-weight: 700;
  color: #6366f1;
  text-align: right;
  min-height: 18px;
  margin-top: 6px;
  font-variant-numeric: tabular-nums;
}

.ev.bad{color: var(--bad) !important}

.amtbox{display: flex; gap: 8px; align-items: center}

/* Calculation Info Button */
.inf{
  background: #f5f3ff;
  color: #7c3aed;
  padding: 0;
  width: 32px;
  height: 32px;
  font-size: 16px;
  font-weight: 700;
  line-height: 1;
  border-radius: 9px;
  border: 1px solid #ddd6fe;
  display: grid;
  place-items: center;
  transition: all 0.2s ease;
  flex: none;
}

.inf:hover, .inf[aria-expanded="true"]{
  background: #7c3aed;
  color: #ffffff;
  border-color: #7c3aed;
  box-shadow: 0 4px 10px rgba(124, 58, 237, 0.3);
  transform: translateY(-1px);
}

/* Primary Green Action Button */
button{
  font: inherit;
  font-size: 14.5px;
  border: 0;
  border-radius: 12px;
  padding: 11px 22px;
  cursor: pointer;
  color: #ffffff;
  background: var(--grad-green);
  font-weight: 700;
  box-shadow: 0 4px 14px rgba(16, 185, 129, 0.35);
  transition: all 0.2s ease;
}

button:hover{
  filter: brightness(1.06);
  box-shadow: 0 6px 18px rgba(16, 185, 129, 0.45);
  transform: translateY(-1px);
}

button:active{
  transform: translateY(0);
}

/* Red Coral Pill Remove Button */
button.x{
  background: #ffe4e6;
  color: #e11d48;
  border: 1px solid #fecdd3;
  padding: 7px 12px;
  box-shadow: none;
  font-size: 13px;
  border-radius: 8px;
  font-weight: 700;
}

button.x:hover{
  background: #e11d48;
  color: #ffffff;
  border-color: #e11d48;
  box-shadow: 0 4px 12px rgba(225, 29, 72, 0.3);
  transform: scale(1.05);
}

.bar{
  display: flex;
  gap: 14px;
  margin-top: 18px;
  flex-wrap: wrap;
  align-items: center;
}

kbd{
  font: inherit;
  font-size: 12px;
  font-weight: 700;
  border: 1px solid #cbd5e1;
  border-bottom: 2px solid #94a3b8;
  border-radius: 6px;
  padding: 2px 8px;
  background: #f8fafc;
  color: #334155;
  box-shadow: 0 1px 2px rgba(0,0,0,0.05);
}

.err{
  color: var(--bad);
  font-size: 13.5px;
  font-weight: 600;
  min-height: 18px;
  margin-top: 10px;
}

/* Decimal Modern Pill Switch */
.sw{
  margin: 0;
  display: flex;
  align-items: center;
  flex: none;
  line-height: 0;
}

.sw input{
  -webkit-appearance: none;
  appearance: none;
  width: 46px;
  height: 26px;
  padding: 0;
  margin: 0;
  border-radius: 999px;
  background: #cbd5e1;
  border: 2px solid transparent;
  position: relative;
  cursor: pointer;
  transition: all 0.25s cubic-bezier(0.4, 0, 0.2, 1);
}

.sw input::after{
  content: "";
  position: absolute;
  top: 2px;
  left: 2px;
  width: 18px;
  height: 18px;
  border-radius: 50%;
  background: #ffffff;
  box-shadow: 0 2px 5px rgba(0,0,0,0.25);
  transition: transform 0.25s cubic-bezier(0.34, 1.56, 0.64, 1);
}

.sw input:checked{
  background: linear-gradient(135deg, #6366f1, #a855f7);
}

.sw input:checked::after{
  transform: translateX(20px);
}

.sw input:focus-visible{
  outline: 2px solid #a855f7;
  outline-offset: 3px;
}

/* Table with Radiant Purple Gradient Header */
tr.blank button.x{visibility: hidden}

.wrap{
  overflow-x: auto;
  border: 1px solid #e2e8f0;
  border-radius: 18px;
  background: #ffffff;
  box-shadow: 0 4px 16px rgba(15, 23, 42, 0.04);
}

table{
  width: 100%;
  border-collapse: separate;
  border-spacing: 0;
  min-width: 920px;
}

th, td{
  padding: 12px 14px;
  border-bottom: 1px solid #f1f5f9;
  text-align: right;
  font-variant-numeric: tabular-nums;
  vertical-align: middle;
}

th:first-child, td:first-child{text-align: left}

/* Purple-to-Pink Radiant Gradient Header */
thead tr{
  background: var(--grad-primary);
}

thead th{
  font-size: 13.5px;
  font-weight: 700;
  letter-spacing: 0.02em;
  color: #ffffff !important;
  border-bottom: none;
  padding: 15px 14px;
  background: transparent !important;
}

tbody tr:nth-child(even){
  background: #fafbff;
}

tbody tr:hover{
  background: rgba(99, 102, 241, 0.04);
}

td{padding-top: 10px; padding-bottom: 10px;}
td input{padding: 8px 11px; font-size: 14px; background: #ffffff; border-radius: 8px;}
td:first-child input{min-width: 140px}
td:nth-child(2) input{min-width: 130px; text-align: right}
td:nth-child(2){min-width: 210px}
td:nth-child(4), td:nth-child(6){min-width: 140px}
td:nth-child(4) input, td:nth-child(6) input{min-width: 110px; text-align: right}
td:nth-child(4) input::placeholder, td:nth-child(6) input::placeholder{color: var(--mut); opacity: 0.7}

td:nth-child(4) .ev{color: var(--disc)}
td:nth-child(6) .ev{color: var(--tax)}
td:nth-child(4) .ev.bad, td:nth-child(6) .ev.bad{color: var(--bad)}

/* Distinct Soft Color Highlights for Discount, Tax, & Final */
td:nth-child(4){
  color: var(--disc);
  background: rgba(236, 253, 245, 0.65);
}

td:nth-child(6){
  color: var(--tax);
  background: rgba(254, 243, 199, 0.55);
}

td:nth-child(7){
  color: #4f46e5;
  background: rgba(245, 243, 255, 0.85);
  font-weight: 800;
  font-size: 15px;
}

/* Table Footer */
tfoot td{
  font-weight: 800;
  font-size: 14.5px;
  border-bottom: 0;
  background: #f8fafc;
  color: #1e1b4b;
  padding: 15px 14px;
  border-top: 2px solid #e2e8f0;
}

tfoot td:nth-child(4){
  color: var(--disc);
  background: #ecfdf5;
}

tfoot td:nth-child(6){
  color: var(--tax);
  background: #fffbeb;
}

tfoot td:nth-child(7){
  color: #4338ca;
  background: #eef2ff;
}

/* Teal-Cyan Gradient Explanation Callout Banner */
.explain{
  margin-top: 20px;
  padding: 16px 20px;
  background: linear-gradient(135deg, rgba(13, 148, 136, 0.08) 0%, rgba(99, 102, 241, 0.08) 100%);
  border-radius: 14px;
  font-size: 14px;
  line-height: 1.6;
  border: 1.5px solid rgba(13, 148, 136, 0.25);
  border-left: 5px solid #0d9488;
  color: #0f172a;
}

/* Result Cards in Step 3 */
.cards{
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(160px, 1fr));
  gap: 16px;
}

.card{
  border-radius: 18px;
  padding: 18px 20px;
  border: 1.5px solid #e2e8f0;
  box-shadow: 0 4px 14px rgba(15, 23, 42, 0.03);
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.card:hover{
  transform: translateY(-2px);
  box-shadow: 0 8px 22px rgba(15, 23, 42, 0.08);
}

.card span{
  display: block;
  font-size: 13px;
  font-weight: 700;
  margin-bottom: 6px;
  opacity: 0.9;
}

.card strong{
  font-size: 24px;
  font-weight: 800;
  font-variant-numeric: tabular-nums;
  letter-spacing: -0.02em;
}

.c1{
  background: #ffffff;
  color: #1e1b4b;
  border-color: #e2e8f0;
}

.c2{
  background: #ecfdf5;
  color: var(--disc-d);
  border-color: var(--disc-border);
}

.c3{
  background: #f5f3ff;
  color: #4f46e5;
  border-color: #ddd6fe;
}

.c4{
  background: #fffbeb;
  color: var(--tax-d);
  border-color: var(--tax-border);
}

/* Final Highlight Banner */
.final{
  margin-top: 18px;
  background: var(--grad-primary);
  color: #ffffff;
  border-radius: 18px;
  padding: 22px 28px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  font-size: 20px;
  font-weight: 700;
  gap: 14px;
  flex-wrap: wrap;
  box-shadow: 0 10px 25px rgba(124, 58, 237, 0.35);
  border: 1px solid rgba(255, 255, 255, 0.2);
}

.final b{
  font-size: 34px;
  font-weight: 800;
  font-variant-numeric: tabular-nums;
  letter-spacing: -0.025em;
  text-shadow: 0 2px 4px rgba(0,0,0,0.2);
}

/* Navigation Pill Button */
.pwr{
  display: flex;
  justify-content: center;
  padding: 6px 36px 32px;
}

a.power{
  display: inline-flex;
  align-items: center;
  gap: 10px;
  text-decoration: none;
  font: inherit;
  font-size: 14.5px;
  font-weight: 700;
  color: #4f46e5;
  background: #ffffff;
  border: 1.5px solid #e2e8f0;
  border-radius: 999px;
  padding: 10px 24px 10px 14px;
  transition: all 0.2s ease;
  box-shadow: 0 4px 12px rgba(15, 23, 42, 0.05);
}

a.power .pi{
  display: grid;
  place-items: center;
  width: 30px;
  height: 30px;
  border-radius: 50%;
  background: var(--grad-badge);
  color: #ffffff;
  font-size: 16px;
  line-height: 1;
  transition: transform 0.2s ease;
}

a.power:hover, a.power:focus-visible{
  background: var(--grad-badge);
  color: #ffffff;
  border-color: transparent;
  box-shadow: 0 8px 22px rgba(168, 85, 247, 0.4);
  transform: translateY(-1px);
  outline: none;
}

a.power:hover .pi, a.power:focus-visible .pi{
  background: #ffffff;
  color: #a855f7;
  transform: rotate(90deg);
}

.note{
  font-size: 13.5px;
  color: var(--mut);
  padding: 0 36px 24px;
  margin: 0;
  line-height: 1.6;
}

/* Calculation Details Popup */
.pop{
  position: fixed;
  z-index: 100;
  width: min(400px, calc(100vw - 20px));
  max-height: 75vh;
  overflow: auto;
  background: #ffffff;
  color: var(--ink);
  border: 1.5px solid #e2e8f0;
  border-top: 4px solid #7c3aed;
  border-radius: 16px;
  box-shadow: 0 20px 40px rgba(15, 23, 42, 0.25);
  padding: 18px 20px;
  font-size: 13.5px;
  text-align: left;
  font-weight: 400;
  animation: popIn 0.15s ease-out;
}

@keyframes popIn{
  from{opacity: 0; transform: translateY(-4px);}
  to{opacity: 1; transform: translateY(0);}
}

.pop[hidden]{display: none}

.pt{
  font-weight: 800;
  font-size: 15px;
  color: #4f46e5;
  margin-bottom: 8px;
  padding-bottom: 5px;
  border-bottom: 1px solid #f1f5f9;
}

.pl{
  padding: 6px 0;
  border-top: 1px dashed #e2e8f0;
  overflow-wrap: anywhere;
  font-variant-numeric: tabular-nums;
}

.pl span{color: var(--mut)}
.pl span:after{content: ": "}
.pl b{font-weight: 700; color: #1e1b4b}
.pl.d b{color: var(--disc)}
.pl.t b{color: var(--tax)}
.pl.f b{color: #4f46e5}

.pn{font-size: 12px; color: var(--mut); padding: 4px 0}
.pe{color: var(--bad); font-weight: 600; margin: 6px 0}

@media (max-width: 600px){
  body{padding: 12px}
  .box{border-radius: 20px}
  .hero{padding: 22px 18px 12px}
  .hero h1{font-size: 26px}
  .in{padding: 18px 16px 24px}
  .pwr, .note{padding-left: 16px; padding-right: 16px}
  .final{padding: 18px 20px}
  .final b{font-size: 28px}
}
</style>
</head>
<body>
<div class="box">
<div class="hero"><div><h1>Prorate calculator</h1>
<p class="sub">Split one discount fairly across your items, then add tax.</p></div>
<label class="sw" title="More decimals (off = 3 decimals)"><input type="checkbox" id="dec" role="switch" aria-label="Show more decimals" autocomplete="off"></label></div>
<div class="in">

<div class="step"><i>1</i>Enter the discount and tax</div>
<div class="set">
  <div><label for="mode">Discount type</label>
    <select id="mode"><option value="amount">Total discount amount (prorated)</option><option value="percent">Discount % on each item</option></select></div>
  <div><label for="disc" id="discLabel">Total discount amount (₹)</label><input id="disc" type="text" inputmode="text" autocomplete="off" value=""><span class="ev" id="discEv"></span></div>
  <div><label for="tax" id="taxLabel">Total tax amount (+ or −)</label><input id="tax" type="text" inputmode="text" autocomplete="off" value=""><span class="ev" id="taxEv"></span></div>
</div>

<div class="step"><i>2</i>List your items</div>
<div class="wrap">
<table>
<thead><tr><th>Item</th><th>Price (₹)</th><th>% of total</th><th>Discount (−)</th><th>Price after discount</th><th id="taxHead">Tax / Adj. (±)</th><th>You pay</th><th></th></tr></thead>
<tbody id="rows"></tbody>
<tfoot><tr><td>Total</td><td id="tA">0.000</td><td id="tS">0%</td><td id="tD">0.000</td><td id="tAD">0.000</td><td id="tT">0.000</td><td id="tF">0.000</td><td></td></tr></tfoot>
</table>
</div>
<div class="err" id="err" role="status"></div>
<div class="bar"><button id="add">+ Add item</button><span class="hint" style="margin:0">or tap <kbd>Alt</kbd> on its own &middot; each press adds one new row below your last item</span></div>

<div class="explain" id="explain"></div>

<div class="step"><i>3</i>See the result</div>
<div class="cards">
  <div class="card c1"><span>Original total</span><strong id="sO">0.000</strong></div>
  <div class="card c2"><span>Total discount</span><strong id="sD">0.000</strong></div>
  <div class="card c3"><span>After discount</span><strong id="sAD">0.000</strong></div>
  <div class="card c4"><span id="sTL">Total tax / adj.</span><strong id="sT">0.000</strong></div>
</div>
<div class="final"><span>Final total to pay</span><b id="sF">0.000</b></div>
</div>
<p class="note">Calculations always use full precision. The decimal toggle only changes how many decimals are shown, so a displayed total can differ from the sum of displayed rows by a small rounding amount.</p>
<!-- Power button: only navigates (same tab) to the separate calculator page. To change the destination, edit the href below. -->
<div class="pwr"><a id="powerBtn" class="power" href="prorate-calculator.html" target="_self" title="Open Prorate Calculator" aria-label="Open Prorate Calculator"><span class="pi" aria-hidden="true">&#x23FB;</span>Open Prorate Calculator</a></div>
</div>

<div id="pop" class="pop" role="dialog" aria-label="Calculation details" hidden></div>
<script>
var rowsEl=document.getElementById("rows"),n=0;
var $=function(id){return document.getElementById(id)};
/* ---------- Number display: values are kept at full precision; only the display changes ----------
   Toggle OFF: exactly 3 decimals (71.429).  Toggle ON: up to 6 decimals (71.428571...), "..." when more digits exist. */
var moreOn=function(){return $("dec").checked};
function clean(v){v=Math.round(v*1e9)/1e9;if(v===0)v=0;return isFinite(v)?v:0}   /* removes float noise and -0 */
function fmt(v,group){
  v=clean(v);var more=moreOn();
  var s=v.toLocaleString("en-IN",{minimumFractionDigits:3,maximumFractionDigits:more?6:3,useGrouping:!!group});
  if(more&&Math.abs(v-Math.round(v*1e6)/1e6)>1e-9)s+="...";
  return s;
}
function fmtIn(v){   /* text put back into an input box after Enter: no commas, no "..." */
  return clean(v).toLocaleString("en-US",{minimumFractionDigits:3,maximumFractionDigits:moreOn()?6:3,useGrouping:false});
}
var f=function(v){return fmt(v,true)};
var nf=function(v){return fmt(v,false)};
var rs=function(v){v=clean(v);return (v<0?"\u2212":"")+"\u20b9"+f(Math.abs(v))};   /* ₹ amount for display */

/* ---------- Safe formula evaluator (no eval) ----------
   Grammar: expr = term {(+|-) term}; term = unary {(*|/|%) unary};
   unary = (+|-) unary | postfix; postfix = primary {%}; primary = number | ( expr )
   A "%" is a postfix percent only when NOT followed by a number or "(" - otherwise it is modulo.
   Calculator-style: "a + b%" adds b% OF a, "a - b%" subtracts b% of a; "a * b%" is a*b/100.
   pctField=true: the field is already a percent, so a postfix % leaves the value unchanged. */
var num=function(x){return String(Math.round(x*1e6)/1e6)};
function prettyExpr(t){
  var isOp=function(x){return x!==undefined&&(x==="("||/^[\d.]/.test(x))},out="";
  for(var i=0;i<t.length;i++){
    var k=t[i],prev=t[i-1],next=t[i+1];
    if(/^[\d.]/.test(k)||k==="("||k===")")out+=k;
    else if(k==="%")out+=isOp(next)?" % ":"%";
    else{
      var un=(k==="+"||k==="-")&&(prev===undefined||prev==="("||/^[+\-*\/]$/.test(prev));
      out+=un?k:" "+(k==="*"?"×":k==="/"?"÷":k)+" ";
    }
  }
  return out;
}
function evaluate(src,pctField){
  var s=String(src==null?"":src).replace(/[₹,\s]/g,"");
  if(s==="")return {v:0,plain:true,empty:true,pretty:"0",notes:[]};
  if(!/^[0-9+\-*\/%().x×÷]+$/i.test(s))return {v:NaN};
  s=s.replace(/[x×]/gi,"*").replace(/÷/g,"/");
  var t=s.match(/\d*\.\d+|\d+\.?|[+\-*\/%()]/g)||[];
  if(t.join("")!==s)return {v:NaN};
  var p=0,bad=false,notes=[];
  var isOperand=function(x){return x!==undefined&&(x==="("||/^[\d.]/.test(x))};
  function expr(){
    var v=term().v;
    while(t[p]==="+"||t[p]==="-"){
      var o=t[p++],q=term();
      if(q.pct){var amt=v*q.v;notes.push(num(q.v*100)+"% of "+num(v)+" = "+num(amt));q={v:amt}}
      v=o==="+"?v+q.v:v-q.v;
    }
    return {v:v}.v}
  function term(){
    var r=unary(),v=r.v,pct=r.pct;
    while(t[p]==="*"||t[p]==="/"||t[p]==="%"){
      pct=false;
      var o=t[p++],w=unary().v;
      if(o==="*")v*=w;else if(o==="/"){if(w===0)bad=true;v/=w}else{if(w===0)bad=true;v%=w}}
    return {v:v,pct:pct}}
  function unary(){
    if(t[p]==="-"){p++;var r=unary();return {v:-r.v,pct:r.pct}}
    if(t[p]==="+"){p++;return unary()}
    var v=primary(),pc=false;
    while(t[p]==="%"&&!isOperand(t[p+1])){p++;pc=true;if(!pctField)v/=100}
    return {v:v,pct:pc&&!pctField}}
  function primary(){
    var x=t[p++];
    if(x==="("){var v=expr();if(t[p++]!==")")bad=true;return v}
    if(x!==undefined&&/^[\d.]/.test(x)){var n=parseFloat(x);if(isNaN(n))bad=true;return n}
    bad=true;return 0}
  var v=expr();
  if(bad||p!==t.length||!isFinite(v))return {v:NaN};
  return {v:v,plain:/^\d*\.?\d+$|^\d+\.$/.test(s),pretty:prettyExpr(t),notes:notes};
}
/* Read a field: returns the evaluation (invalid -> v=0, bad=true); flags the input and shows "= result" for formulas.
   The text typed by the user is never changed, so the original expression is preserved. */
function readField(input,evEl,pctField){
  var src=input.dataset.expr||input.value;   /* committed (Enter) fields keep their formula in data-expr */
  var r=evaluate(src,pctField),ok=!isNaN(r.v);
  input.classList.toggle("bad",!ok);
  if(evEl){evEl.classList.toggle("bad",!ok);
    evEl.textContent=!ok?"Invalid formula":(r.plain||r.empty?"":"= "+nf(r.v));}
  r.bad=!ok;r.expr=src;if(!ok)r.v=0;
  return r;
}

/* Tax / adjustment field: any +,-,%,fixed formula, applied to a base amount B as  B <expr>.
   Because the result is  c + (1+k)*B,  we evaluate at B=0 and B=1 to get the fixed part c and the percent-like part k. */
function readAdj(input,evEl,isDisc){
  var raw=input.dataset.expr||input.value,s=raw.replace(/[₹,\s]/g,""),res={expr:raw,norm:"",src:"",c:0,k:0,empty:false,bad:false};
  if(s==="")res.empty=true;
  else{
    var pre=/^[+\-*\/x×÷]/i.test(s)?"":"+";
    var r0=evaluate("0"+pre+s,false),r1=evaluate("1"+pre+s,false);
    if(isNaN(r0.v)||isNaN(r1.v))res.bad=true;
    else{res.c=r0.v;res.k=r1.v-r0.v-1;res.src=pre+s;res.norm=(pre+raw.trim()).replace(/\s+/g,"");}
  }
  if(Math.abs(res.k)<1e-12)res.k=0;
  input.classList.toggle("bad",res.bad);
  var parts=[];
  if(res.k!==0){var kp=Math.round(res.k*1e6)/1e4;parts.push((kp<0?"−":"+")+Math.abs(kp)+(isDisc?"% of the total bill":"% of each item"));}
  if(res.c!==0)parts.push((res.c<0?"−":"+")+nf(Math.abs(res.c))+(isDisc?" fixed":" fixed, shared by price"));
  evEl.classList.toggle("bad",res.bad);
  evEl.textContent=res.bad?"Invalid formula":(res.empty?"":parts.join("; ")||"No change");
  return res;
}

/* Per-row Discount / Tax box: any formula. Result = c + k*B, where B is the base the row's amount is taken on
   (price for Discount, price after discount for Tax). "20%" -> 20% of B; "20", "50+10", "100*20%", "(100-20)*10%" -> fixed amounts. */
function readRowAdj(input){
  var raw=input.dataset.expr||input.value,s=raw.replace(/[₹,\s]/g,""),res={expr:raw,c:0,k:0,empty:false,bad:false};
  if(s==="")res.empty=true;
  else{
    var pre=/^[+\-*\/x×÷]/i.test(s)?"":"+";
    var r0=evaluate("0"+pre+s,false),r1=evaluate("1"+pre+s,false);
    if(isNaN(r0.v)||isNaN(r1.v))res.bad=true;
    else{res.c=r0.v;res.k=Math.round((r1.v-r0.v-1)*1e12)/1e12;}   /* strips float noise: 1.2-1 -> exactly 0.2 */
  }
  input.classList.toggle("bad",res.bad);
  return res;
}

/* Split `total` across weights in proportion, at full precision (no rounding) */
function share(total,w){
  var S=w.reduce(function(x,y){return x+y},0);
  if(S<=0||total<=0)return w.map(function(){return 0});
  return w.map(function(x){return total*x/S});
}

function addRow(name,amt,focus){
  var tr=document.createElement("tr");
  tr.innerHTML='<td><input type="text" class="nm" placeholder="Item name / description" autocomplete="off"></td>'+
    '<td><div class="amtbox"><input type="text" inputmode="decimal" autocomplete="off" class="amt" placeholder="e.g. 100*5+20"><button class="inf" type="button" aria-label="Show calculation" aria-expanded="false" title="Show calculation">&#9432;</button></div><span class="ev"></span></td>'+
    '<td class="sh">0%</td><td class="d"><input type="text" inputmode="text" autocomplete="off" class="dsc" placeholder="0.000" aria-label="Discount for this item"><span class="ev dev"></span></td><td class="ad">0.000</td><td class="tx"><input type="text" inputmode="text" autocomplete="off" class="txr" placeholder="0.000" aria-label="Tax for this item"><span class="ev tev"></span></td><td class="fi">0.000</td>'+
    '<td><button class="x" aria-label="Remove item">&#10005;</button></td>';
  if(name)tr.querySelector(".nm").value=name;   /* stays blank unless a name is given */
  if(amt!=null&&amt!=="")tr.querySelector(".amt").value=amt;   /* blank by default */
  rowsEl.appendChild(tr);
  if(focus)tr.scrollIntoView({block:"nearest"});   /* new row is scrolled into view; no automatic entry prompt/focus */
}

/* Rows are never added automatically. The list starts with one empty row; a new empty row is added
   only when the user presses Alt (or the "+ Add item" button), exactly one per press. */
function ensureOneEmpty(){
  if(rowsEl.children.length===0)addRow("","",false);   /* only the very first row, or if the last row was removed */
  var rows=[].slice.call(rowsEl.children);
  rows.forEach(function(r){r.classList.toggle("blank",rows.length===1);});   /* the only row can't be removed */
}
function focusBlank(){
  addRow("","",true);   /* exactly one new empty row below the current items; existing rows are untouched */
  calc();
  var rows=rowsEl.children,last=rows[rows.length-1];
  last.scrollIntoView({block:"nearest"});last.querySelector(".nm").focus();
}

function calc(){
  var mode=$("mode").value, anyBad=false;
  var dvR=mode==="percent"?readField($("disc"),$("discEv"),true):readAdj($("disc"),$("discEv"),true), dv=dvR.v||0;   /* empty = 0 */
  var trR=readAdj($("tax"),$("taxEv"));
  anyBad=dvR.bad||trR.bad;
  ensureOneEmpty();
  var rows=[].slice.call(rowsEl.children);
  var infos=rows.map(function(r){
    var x=readField(r.querySelector(".amt"),r.querySelector(".ev"),false);
    if(x.bad)anyBad=true;
    r._i={x:x,name:r.querySelector(".nm").value||"Item"};
    return x});
  var a=infos.map(function(x){return x.v});
  var S=a.reduce(function(x,y){return x+y},0), err="";

  /* Order is always: Price -> Discount -> Tax -> Final.
     A row with its own Discount / Tax entry uses it; other rows use the global boxes above. */
  rows.forEach(function(r){
    var i=r._i;
    i.dR=readRowAdj(r.querySelector(".dsc"));i.tR=readRowAdj(r.querySelector(".txr"));
    if(i.dR.bad||i.tR.bad)anyBad=true;
    i.dOv=!i.dR.empty;i.tOv=!i.tR.empty;
  });
  var dOv=rows.map(function(r){return r._i.dOv}),tOv=rows.map(function(r){return r._i.tOv});
  var ag=a.map(function(x,i){return dOv[i]?0:x});
  var Sg=ag.reduce(function(x,y){return x+y},0);
  var d=a.map(function(){return 0}),D=0,capped=false;

  /* discount */
  if(mode==="percent"){
    d=a.map(function(x,i){return dOv[i]?0:x*dv/100});
  }else{
    /* manual total discount: fixed part + percent of the total bill, e.g. 100, +100, 10%, 100+50, (500-100)/2 */
    D=dvR.c+dvR.k*Sg;
    if(Math.abs(D)<1e-12)D=0;
    if(D>Sg+1e-9&&Sg>0){D=Sg;err="Discount is larger than the total, so it was capped at "+f(Sg)+".";}
    d=share(Math.abs(D),ag).map(function(x){return D<0?-x:x});
  }
  /* a row's own discount: amount = fixed part + percent part x that row's price */
  rows.forEach(function(r,i){
    if(!dOv[i])return;
    var R=r._i.dR;d[i]=R.c+R.k*a[i];
    if(a[i]>=0&&d[i]>a[i]+1e-9){d[i]=a[i];capped=true}
  });
  if(capped&&!err)err="A discount was larger than its item's price, so it was capped at the price.";
  var ad=a.map(function(x,i){return x-d[i]});
  var ADs=ad.reduce(function(x,y){return x+y},0);

  /* tax / adjustment is worked out on the price AFTER discount */
  var adg=ad.map(function(x,i){return tOv[i]?0:x});
  var ADg=adg.reduce(function(x,y){return x+y},0);
  var kp=ad.map(function(x,i){return tOv[i]?0:x*trR.k});
  var C=trR.c;
  var cs=share(Math.abs(C),adg).map(function(x){return C<0?-x:x});
  var nShare=adg.filter(function(x){return x>0}).length;
  var tx=ad.map(function(x,i){if(tOv[i]){var R=rows[i]._i.tR;return R.c+R.k*x}return kp[i]+cs[i]});

  var tot={a:0,d:0,ad:0,t:0,f:0};
  rows.forEach(function(r,i){
    var fin=ad[i]+tx[i],I=r._i;I.a=a[i];I.d=d[i];I.ad=ad[i];I.tx=tx[i];I.kp=kp[i];I.cs=cs[i];I.fin=fin;
    r.querySelector(".sh").textContent=S?(a[i]/S*100).toFixed(1)+"%":"0%";
    /* Discount and Tax cells: show the calculated amount right away (like the Price box) */
    var dI=r.querySelector(".dsc"),tI=r.querySelector(".txr"),dE=r.querySelector(".dev"),tE=r.querySelector(".tev");
    dE.classList.toggle("bad",I.dR.bad);dE.textContent=I.dR.bad?"Invalid formula":(I.dR.empty?"":"= "+rs(d[i]));
    tE.classList.toggle("bad",I.tR.bad);tE.textContent=I.tR.bad?"Invalid formula":(I.tR.empty?"":"= "+rs(tx[i]));
    dI.placeholder=f(d[i]);tI.placeholder=f(tx[i]);
    if(dI.dataset.expr&&document.activeElement!==dI)dI.value=fmtIn(d[i]);
    if(tI.dataset.expr&&document.activeElement!==tI)tI.value=fmtIn(tx[i]);
    r.querySelector(".ad").textContent=f(ad[i]);
    r.querySelector(".fi").textContent=f(fin);
    tot.a+=a[i];tot.d+=d[i];tot.ad+=ad[i];tot.t+=tx[i];tot.f+=fin;
  });
  var set=function(id,v){$(id).textContent=f(v)};
  set("tA",tot.a);set("tD",tot.d);set("tAD",tot.ad);set("tT",tot.t);set("tF",tot.f);
  set("sO",tot.a);set("sD",tot.d);set("sAD",tot.ad);set("sT",tot.t);set("sF",tot.f);
  $("tS").textContent=S?"100%":"0%";

  /* total discount / tax amounts, shown right under the two boxes (display only; values stay at full precision) */
  var gd=0;rows.forEach(function(r,i){if(!dOv[i])gd+=d[i]});
  var discAmt=mode==="percent"?(Sg>0?gd:null):D;      /* global box: % mode = sum of each item's discount */
  var taxAmt=trR.c+trR.k*ADg;                            /* tax is on the price AFTER discount */
  if(!dvR.bad&&!dvR.empty)$("discEv").textContent=discAmt!==null?"= "+rs(discAmt):(dvR.plain?"":"= "+nf(dv)+"%");
  if(!trR.bad&&!trR.empty)$("taxEv").textContent="= "+rs(taxAmt);

  ctx={DiscAmt:discAmt,TaxAmt:taxAmt,dvR:dvR,adj:trR,C:C,nShare:nShare,mode:mode,S:Sg,ADs:ADg,Dtot:gd,Ttot:tot.t};
  if(openRow)renderPop();

  /* tax labels */
  if(anyBad)err="Some formulas are not valid and were counted as 0. Use numbers, + - * / % and brackets.";
  $("err").textContent=err;

  /* explanation */
  var taxTxt=trR.empty?"no tax is added.":"your tax / adjustment <b>"+esc(trR.norm||"")+"</b> is applied to what is left"+(trR.c!==0&&rows.length>1?" (a fixed amount is shared by price)":"")+".";
  var ex="",i0=a.findIndex(function(x,j){return x>0&&!dOv[j]});
  if(mode==="percent"){
    ex=dv===0?"<b>How it works:</b> no discount is entered. Then "+taxTxt:"<b>How it works:</b> every item gets "+(Math.round(dv*1e4)/1e4)+"% off its price. Then "+taxTxt;
  }else if(D===0){
    ex="<b>How it works:</b> no discount is entered. Then "+taxTxt;
  }else if(i0>=0){
    var nm=rows[i0].querySelector(".nm").value||"Item";
    var pc=(a[i0]/Sg*100).toFixed(1);
    ex="<b>How it works:</b> the "+f(D)+" discount is shared by price. <b>"+nm.replace(/</g,"&lt;")+"</b> is "+pc+"% of the total ("+f(a[i0])+" of "+f(Sg)+"), so it takes "+pc+"% of the discount = <b>"+f(d[i0])+"</b>. Then "+taxTxt;
  }else ex="Enter a price for at least one item to see how the discount is shared.";
  if(dOv.concat(tOv).some(Boolean))ex+=" Items with their own Discount or Tax entry use that instead. Tax is always worked out on the price after discount.";
  $("explain").innerHTML=ex;
}

/* ---------- Events ---------- */
$("mode").addEventListener("change",function(){
  var p=this.value==="percent",dd=$("disc");
  if(dd.dataset.expr){dd.value=dd.dataset.expr;delete dd.dataset.expr;}
  $("discLabel").textContent=p?"Discount (%)":"Total discount amount (₹)";
  calc();
});
$("add").addEventListener("click",focusBlank);
$("dec").addEventListener("change",function(){
  [].forEach.call(rowsEl.querySelectorAll("input.amt"),function(inp){   /* refresh amounts already committed with Enter */
    if(inp.dataset.expr){var r=evaluate(inp.dataset.expr,false);if(!isNaN(r.v))inp.value=fmtIn(r.v);}
  });
  calc();
  ["disc","tax"].forEach(function(id){
    var inp=$(id);
    if(inp.dataset.expr){var v=finalOf(inp,inp.dataset.expr);if(v!==null)inp.value=fmtIn(v);}
  });
});
rowsEl.addEventListener("click",function(e){
  var b=e.target.closest&&e.target.closest("button.x");
  if(b){b.closest("tr").remove();calc();return;}
  var inf=e.target.closest&&e.target.closest("button.inf");
  if(inf){var tr=inf.closest("tr");if(openRow===tr)closePop();else openPop(tr,inf);}
});

/* ---------- Enter in an amount box: show the final amount; the formula is kept and comes back when you edit ---------- */
rowsEl.addEventListener("keydown",function(e){
  var inp=e.target;
  if(e.key==="Enter"&&inp.classList&&(inp.classList.contains("dsc")||inp.classList.contains("txr"))){
    e.preventDefault();
    var R=readRowAdj(inp),tr=inp.closest("tr"),isD=inp.classList.contains("dsc");
    if(R.bad||R.empty||/^\d*\.?\d+$/.test(inp.value.replace(/[₹,\s]/g,"")))return;
    calc();inp.dataset.expr=inp.value;inp.value=fmtIn(isD?tr._i.d:tr._i.tx);calc();inp.select();return;
  }
  if(e.key!=="Enter"||!inp.classList||!inp.classList.contains("amt"))return;
  e.preventDefault();
  var src=inp.dataset.expr||inp.value,r=evaluate(src,false);
  if(!isNaN(r.v)&&!r.plain&&!r.empty){
    inp.dataset.expr=src;
    inp.value=fmtIn(r.v);
  }
  calc();inp.select();
});
rowsEl.addEventListener("input",function(e){          /* typing replaces the stored formula */
  if(/\b(amt|dsc|txr)\b/.test(e.target.className))delete e.target.dataset.expr;
});
rowsEl.addEventListener("focusin",function(e){        /* clicking back in restores the formula for editing */
  var inp=e.target;
  if(/\b(amt|dsc|txr)\b/.test(inp.className)&&inp.dataset.expr){inp.value=inp.dataset.expr;delete inp.dataset.expr;inp.select();calc();}
});

/* ---------- Enter in the Discount / Tax box: show the final amount; the formula is kept and comes back when you click in ---------- */
function finalOf(inp,src){
  if(inp.id==="disc"&&$("mode").value==="percent"){var r=evaluate(src,true);return isNaN(r.v)?null:r.v;}
  return ctx?(inp.id==="disc"?ctx.DiscAmt:ctx.TaxAmt):null;
}
["disc","tax"].forEach(function(id){
  var inp=$(id);
  inp.addEventListener("keydown",function(e){
    if(e.key!=="Enter")return;
    e.preventDefault();
    var src=inp.dataset.expr||inp.value,r=evaluate(src,id==="disc"&&$("mode").value==="percent");
    if(isNaN(r.v)||r.plain||r.empty)return;
    calc();
    var v=finalOf(inp,src);
    if(v===null)return;
    inp.dataset.expr=src;inp.value=fmtIn(v);
    calc();inp.select();
  });
  inp.addEventListener("input",function(){delete inp.dataset.expr;});   /* typing replaces the stored formula */
  inp.addEventListener("focus",function(){                               /* clicking back in restores the formula */
    if(inp.dataset.expr){inp.value=inp.dataset.expr;delete inp.dataset.expr;inp.select();calc();}
  });
});

/* ---------- Calculation details popup (the ⓘ icon) ---------- */
var pop=$("pop"),openRow=null,openBtn=null,ctx=null;
var esc=function(s){return String(s).replace(/[&<>"]/g,function(c){return {"&":"&amp;","<":"&lt;",">":"&gt;",'"':"&quot;"}[c]})};
var sgn=function(c){return (c<0?" − ":" + ")+f(Math.abs(c))};
var L=function(label,html,cls){return '<div class="pl '+(cls||"")+'"><span>'+label+'</span><b>'+html+'</b></div>'};
function closePop(){
  pop.hidden=true;
  if(openBtn)openBtn.setAttribute("aria-expanded","false");
  openRow=openBtn=null;
}
function openPop(tr,btn){
  closePop();openRow=tr;openBtn=btn;
  btn.setAttribute("aria-expanded","true");
  pop.hidden=false;renderPop();
}
function placePop(){
  var r=openBtn.getBoundingClientRect(),w=pop.offsetWidth,h=pop.offsetHeight;
  var left=Math.max(8,Math.min(r.left,window.innerWidth-w-8));
  var top=r.bottom+6;
  if(top+h>window.innerHeight-8)top=Math.max(8,r.top-h-6);
  pop.style.left=left+"px";pop.style.top=top+"px";
}
function inputNote(label,R){
  if(R.bad)return '<div class="pe">'+label+' "'+esc(R.expr)+'" is not valid and was counted as 0.</div>';
  if(R.src!==undefined){return (R.empty||/^[\d.,\s]+$/.test(R.expr))?"":'<div class="pn">'+label+' entered as '+esc(R.expr.trim())+'</div>';}
  if(R.plain||R.empty)return "";
  return '<div class="pn">'+label+' entered as '+esc(R.expr)+' ('+esc(R.pretty)+' = '+nf(R.v)+')'+(R.notes.length?' - '+esc(R.notes.join("; ")):"")+'</div>';
}
function renderPop(){
  if(!openRow||!document.body.contains(openRow)||!openRow._i||!ctx||openRow._i.a===undefined){closePop();return}
  var i=openRow._i,x=i.x,h='<div class="pt">'+esc(i.name)+'</div>';
  var sh=ctx.S?(i.a/ctx.S*100).toFixed(1):"0.0";
  if(x.bad){
    h+='<div class="pe">Invalid formula "'+esc(x.expr)+'" - counted as 0. Use numbers, + - * / % and brackets.</div>';
  }else{
    h+=L("You entered",esc(x.expr.trim()||"(empty)"));
    h+=L("Calculation",(x.plain||x.empty)?esc(nf(x.v))+" (entered directly)":esc(x.pretty)+" = "+esc(nf(x.v)));
    if(x.notes.length)h+='<div class="pn">'+esc(x.notes.join("; "))+'</div>';
  }
  if(i.dOv){
    h+=L("Discount",esc(i.dR.expr.trim())+" = "+f(i.d),"d")+(i.dR.bad?'<div class="pe">Invalid formula - counted as 0.</div>':"");
  }else{
  h+=L("Share of total",f(i.a)+" ÷ "+f(ctx.S)+" = "+sh+"%");
  if(ctx.mode==="percent"){
    h+=L("Discount",f(i.a)+" × "+num(ctx.dvR.v)+"% = "+f(i.d),"d")+inputNote("Discount %",ctx.dvR);
  }else{
    h+=L("Discount",f(ctx.Dtot)+" total × "+sh+"% = "+f(i.d),"d")+inputNote("Discount",ctx.dvR);
  }
  }
  h+=L("After discount",f(i.a)+" − "+f(i.d)+" = "+f(i.ad));
  var A=ctx.adj;
  h+=L("Amount","₹"+f(i.ad));
  if(i.tOv){
    h+=L("Tax",esc(i.tR.expr.trim()),"t");
    h+=L("Calculation","tax on "+f(i.ad)+" = "+f(i.tx)+" → "+f(i.ad)+sgn(i.tx)+" = "+f(i.fin));
  }else if(A.empty||A.bad){
    h+=L("Tax","none","t");
  }else{
    h+=L(A.k!==0?"Tax":"Adjustment",esc(A.norm),"t");
    var calcTxt;
    if(A.c!==0&&ctx.nShare>1){
      calcTxt=f(i.ad)+(A.k!==0?sgn(i.kp):"")+sgn(i.cs);
      if(A.k!==0)h+='<div class="pn">Percent part: '+num(A.k*100)+'% of '+f(i.ad)+' = '+f(i.kp)+'</div>';
      h+='<div class="pn">Fixed part '+(ctx.C<0?"−":"+")+f(Math.abs(ctx.C))+' is split by price: '+f(i.ad)+' ÷ '+f(ctx.ADs)+' → '+f(i.cs)+'</div>';
    }else{
      var ev=evaluate("1"+A.src,false);
      calcTxt=f(i.ad)+ev.pretty.slice(1);
    }
    h+=L("Calculation",esc(calcTxt)+" = "+f(i.fin));
  }
  h+=L("Final Amount","₹"+f(i.fin),"f");
  pop.innerHTML=h;placePop();
}
document.addEventListener("click",function(e){
  if(openRow&&!pop.contains(e.target)&&!(e.target.closest&&e.target.closest(".inf")))closePop();
});
document.addEventListener("keydown",function(e){if(e.key==="Escape"&&openRow){var b=openBtn;closePop();b.focus();}});
window.addEventListener("resize",function(){if(openRow)closePop();});
window.addEventListener("scroll",function(e){if(openRow&&!pop.contains(e.target))closePop();},true);
document.addEventListener("input",calc);

/* ---------- Alt key: a lone press-and-release adds a row ----------
   Fires on keyup, and only if no other key or mouse button was used while Alt was held,
   so Alt+Tab, Alt+Arrow, Alt+letter shortcuts etc. keep working as normal. */
var altSolo=false;
document.addEventListener("keydown",function(e){
  if(e.key==="Alt"){ if(!e.repeat&&!e.ctrlKey&&!e.shiftKey&&!e.metaKey)altSolo=true; }
  else altSolo=false;
});
document.addEventListener("mousedown",function(){altSolo=false;});
window.addEventListener("blur",function(){altSolo=false;});
document.addEventListener("keyup",function(e){
  if(e.key==="Alt"&&altSolo){
    altSolo=false;
    e.preventDefault();            /* stops the browser menu bar from grabbing focus on Windows */
    focusBlank();
  }
});

/* ---------- Start ---------- */
/* Items list starts completely empty: no sample rows. Add items with the button or the Alt key. */
calc();
</script>
</body></html>
