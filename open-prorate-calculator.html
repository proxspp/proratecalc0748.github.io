<!DOCTYPE html>

<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Prorate Calculator</title>

<style>
*{margin:0;padding:0;box-sizing:border-box}
body{
    font-family:-apple-system,BlinkMacSystemFont,'Segoe UI',Roboto,sans-serif;
    background: linear-gradient(135deg, #1f1c2c 0%, #928DAB 100%), 
                radial-gradient(circle at 10% 20%, rgba(255, 107, 107, 0.3) 0%, transparent 40%),
                radial-gradient(circle at 90% 80%, rgba(78, 205, 196, 0.3) 0%, transparent 40%);
    background-attachment: fixed;
    min-height:100vh;
    padding:20px;
}
.container{
    max-width:1200px;
    margin:auto;
    background:#ffffff;
    border-radius:20px;
    box-shadow:0 25px 70px rgba(31, 28, 44, 0.35), 0 0 0 1px rgba(255, 255, 255, 0.2);
    padding:40px;
    position: relative;
    overflow: hidden;
}
.container::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    height: 6px;
    background: linear-gradient(90deg, #ff6b6b, #feca57, #48dbfb, #ff9ff3, #54a0ff, #5f27cd);
}
h1{
    font-size:32px;
    font-weight:800;
    margin-bottom:8px;
    background: linear-gradient(135deg, #4f46e5 0%, #7c3aed 50%, #db2777 100%);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    display: inline-block;
    letter-spacing: -0.5px;
}
.subtitle{
    color:#64748b;
    font-size:14px;
    margin-bottom:32px;
    font-weight: 500;
}
.section-title{
    font-size:19px;
    font-weight:800;
    margin-bottom:20px;
    color:#1e1b4b;
    display:flex;
    align-items:center;
    gap:10px;
}
.section-title::before{
    content:'';
    width:5px;
    height:24px;
    background: linear-gradient(180deg, #4f46e5, #ec4899);
    border-radius:4px;
}
.table-wrapper{
    overflow-x:auto;
    margin-bottom:24px;
    border-radius:14px;
    border:1px solid #e2e8f0;
    box-shadow:0 4px 15px rgba(0,0,0,0.03);
}
table{
    width:100%;
    border-collapse:separate;
    border-spacing:0;
    min-width:900px;
}
thead{
    background:linear-gradient(135deg, #312e81 0%, #4338ca 50%, #6366f1 100%);
}
th{
    color:#ffffff;
    padding:16px 14px;
    font-size:13px;
    font-weight:700;
    text-align:left;
    letter-spacing: 0.5px;
    text-transform: uppercase;
    border-bottom:3px solid #4f46e5;
}
th:nth-child(2),
th:nth-child(3),
th:nth-child(4),
th:nth-child(5),
th:nth-child(6){
    text-align:right;
}
th:first-child{border-radius:13px 0 0 0}
th:last-child{border-radius:0 13px 0 0}
td{
    padding:14px 14px;
    border-bottom:1px solid #f1f5f9;
    font-size:14px;
    background:#ffffff;
    color: #334155;
}
tbody tr{
    transition:all .2s ease;
}
tbody tr:hover{
    background:#f8fafc;
    transform:translateX(3px);
}
tbody tr:last-child td{border-bottom:none}
input{
    width:100%;
    padding:10px 14px;
    border:2px solid #e2e8f0;
    border-radius:10px;
    font-size:14px;
    transition:all .2s ease;
    font-family:inherit;
    background:#fafafa;
    color:#1e293b;
}
input:hover{
    border-color:#cbd5e1;
    background:#fff;
}
input:focus{
    border-color:#6366f1;
    background:#fff;
    outline:none;
    box-shadow:0 0 0 4px rgba(99, 102, 241, 0.15);
}
.btn{
    padding:12px 24px;
    border:none;
    border-radius:10px;
    cursor:pointer;
    font-weight:700;
    font-size:14px;
    margin:0 12px 12px 0;
    transition:all .25s ease;
    display:inline-flex;
    align-items:center;
    gap:8px;
    font-family:inherit;
}
.btn:hover{
    transform:translateY(-2px);
    box-shadow:0 10px 20px rgba(0,0,0,.15);
}
.btn:active{
    transform:translateY(0);
}
.btn-add{
    background:linear-gradient(135deg, #059669 0%, #10b981 100%);
    color:#fff;
    box-shadow: 0 4px 12px rgba(16, 185, 129, 0.3);
}
.btn-add:hover{
    box-shadow: 0 6px 16px rgba(16, 185, 129, 0.45);
}
.btn-reset{
    background:linear-gradient(135deg, #d97706 0%, #f59e0b 100%);
    color:#fff;
    box-shadow: 0 4px 12px rgba(245, 158, 11, 0.3);
}
.btn-reset:hover{
    box-shadow: 0 6px 16px rgba(245, 158, 11, 0.45);
}
.btn-remove{
    background:linear-gradient(135deg, #e11d48 0%, #f43f5e 100%);
    color:#fff;
    font-size:13px;
    padding:8px 16px;
    margin:0;
    box-shadow: 0 3px 8px rgba(244, 63, 94, 0.25);
}
.btn-remove:hover{
    box-shadow: 0 5px 12px rgba(244, 63, 94, 0.4);
}
.input-group{
    margin-bottom:24px;
}
.input-group label{
    display:block;
    font-weight:700;
    font-size:14px;
    margin-bottom:8px;
    color:#475569;
    letter-spacing: 0.2px;
}
.input-group input{
    padding:14px 16px;
    font-size:16px;
    background:#ffffff;
}
.number{
    text-align:right;
    font-family:'SF Mono',Monaco,Consolas,monospace;
    font-size:14px;
    font-weight:600;
}
#outputRows td:nth-child(2){ color: #4338ca; }
#outputRows td:nth-child(3){ color: #0284c7; }
#outputRows td:nth-child(4){ color: #d97706; }
#outputRows td:nth-child(5){ color: #059669; font-weight: 700; }
#outputRows td:nth-child(6){ color: #e11d48; }

.empty-state{
    text-align:center;
    color:#94a3b8;
    padding:40px;
    font-size:14px;
    font-style: italic;
}
.totals-row{
    background:linear-gradient(135deg, #1e1b4b 0%, #312e81 100%) !important;
    font-weight:700;
    border-top:3px solid #6366f1;
}
.totals-row td{
    font-size:15px;
    padding:18px 14px;
    color:#ffffff !important;
    background: transparent;
}
#tProrated {
    color: #34d399 !important;
    font-weight: 800;
}
#tDiscount {
    color: #f472b6 !important;
    font-weight: 800;
}
.discount-info{
    background:linear-gradient(135deg, #ecfdf5 0%, #d1fae5 100%);
    border: 1px solid #a7f3d0;
    border-left:5px solid #10b981;
    padding:20px 24px;
    margin-bottom:32px;
    border-radius:14px;
    display:flex;
    align-items:center;
    gap:16px;
    box-shadow: 0 4px 15px rgba(16, 185, 129, 0.08);
}
.discount-icon{
    width:52px;
    height:52px;
    background:linear-gradient(135deg, #10b981 0%, #059669 100%);
    border-radius:12px;
    display:flex;
    align-items:center;
    justify-content:center;
    font-size:24px;
    color: #fff;
    flex-shrink:0;
    box-shadow: 0 4px 12px rgba(16, 185, 129, 0.3);
}
.discount-content{
    flex:1;
}
.discount-amount{
    font-size:26px;
    font-weight:800;
    color:#065f46;
    margin-bottom:4px;
}
.discount-detail{
    font-size:14px;
    font-weight: 600;
    color:#047857;
}
.toggle-container{
    display:flex;
    align-items:center;
    gap:12px;
}
.toggle-label{
    font-size:14px;
    color:#475569;
    font-weight:700;
}
.toggle-switch{
    position:relative;
    display:inline-block;
    width:48px;
    height:26px;
}
.toggle-switch input{
    opacity:0;
    width:0;
    height:0;
}
.slider{
    position:absolute;
    cursor:pointer;
    top:0;
    left:0;
    right:0;
    bottom:0;
    background:#cbd5e1;
    transition:all .3s cubic-bezier(0.4, 0, 0.2, 1);
    border-radius:26px;
}
.slider:before{
    position:absolute;
    content:"";
    height:20px;
    width:20px;
    left:3px;
    bottom:3px;
    background:white;
    transition:all .3s cubic-bezier(0.4, 0, 0.2, 1);
    border-radius:50%;
    box-shadow:0 2px 5px rgba(0,0,0,.25);
}
input:checked + .slider{
    background:linear-gradient(135deg, #6366f1, #a855f7);
}
input:checked + .slider:before{
    transform:translateX(22px);
}
.decimal-selector{
    padding:6px 14px;
    border:2px solid #6366f1;
    border-radius:8px;
    font-size:13px;
    background:white;
    color: #4f46e5;
    cursor:pointer;
    transition:all .3s;
    opacity:0;
    transform:scale(0.95);
    pointer-events:none;
    font-family:inherit;
    font-weight:700;
}
.decimal-selector.active{
    opacity:1;
    transform:scale(1);
    pointer-events:all;
}
.decimal-selector:hover{
    background:#f5f3ff;
    border-color:#4f46e5;
}
.button-group{
    display:flex;
    gap:12px;
    margin-bottom:32px;
    flex-wrap:wrap;
}
.history-btn{
    position:absolute;
    right:10px;
    top:50%;
    transform:translateY(-50%);
    background:linear-gradient(135deg, #6366f1, #8b5cf6);
    color:#fff;
    border:none;
    border-radius:50%;
    width:28px;
    height:28px;
    font-size:15px;
    cursor:pointer;
    display:flex;
    align-items:center;
    justify-content:center;
    transition:all .2s;
    font-weight:bold;
    box-shadow:0 2px 8px rgba(99, 102, 241, 0.35);
}
.history-btn:hover{
    transform:translateY(-50%) scale(1.1);
    box-shadow:0 4px 12px rgba(99, 102, 241, 0.5);
}
.history-popup{
    position:absolute;
    background:#fff;
    border:2px solid #6366f1;
    border-radius:14px;
    box-shadow:0 12px 30px rgba(0,0,0,.15);
    z-index:1000;
    min-width:300px;
    max-width:380px;
    overflow: hidden;
}
.history-header{
    background:linear-gradient(135deg, #4f46e5, #7c3aed);
    color:#fff;
    padding:14px 18px;
    font-weight:700;
    font-size:14px;
}
.history-list{
    max-height:240px;
    overflow-y:auto;
    padding:12px;
}
.history-item{
    padding:12px;
    border-bottom:1px solid #f1f5f9;
    font-size:13px;
    border-radius:8px;
    margin-bottom:6px;
    transition: background .2s;
}
.history-item:last-child{
    border-bottom:none;
    margin-bottom:0;
}
.history-item:hover{
    background:#f8fafc;
}
.history-expr{
    font-family:'SF Mono',Monaco,Consolas,monospace;
    color:#1e293b;
    font-weight:700;
    margin-bottom:4px;
}
.history-time{
    font-size:11px;
    color:#94a3b8;
}
.history-empty{
    text-align:center;
    padding:32px 20px;
    color:#94a3b8;
    font-size:13px;
    line-height:1.6;
}
.history-list::-webkit-scrollbar{
    width:6px;
}
.history-list::-webkit-scrollbar-track{
    background:#f1f5f9;
    border-radius:4px;
}
.history-list::-webkit-scrollbar-thumb{
    background:#a5b4fc;
    border-radius:4px;
}
.history-list::-webkit-scrollbar-thumb:hover{
    background:#6366f1;
}
.result-header{
    display:flex;
    justify-content:space-between;
    align-items:center;
    margin-bottom:20px;
}
@media (max-width: 768px){
    .container{padding:24px}
    h1{font-size:26px}
    .result-header{
        flex-direction:column;
        align-items:flex-start;
        gap:16px;
    }
    table{font-size:12px;min-width:850px}
    th,td{padding:12px 10px}
}
</style>

</head>

<body>
<div class="container">
<h1>Prorate Calculator</h1>
<p class="subtitle">Professional bill proration tool</p>

<h2 class="section-title">Items</h2>

<div class="table-wrapper">
<table>
<thead>
<tr>
<th>Name</th>
<th>Original Amount (₹)</th>
<th>Action</th>
</tr>
</thead>
<tbody id="itemRows"></tbody>
</table>
</div>

<div class="button-group">
<button class="btn btn-add" onclick="addItem()">➕ Add Item</button>
<button class="btn btn-reset" onclick="resetAll()">🔄 Reset</button>
</div>

<div class="input-group">
<label for="totalBill">Total Bill Amount (₹)</label>
<div style="position:relative">
<input type="text" id="totalBill" value="" placeholder="Enter amount or expression (e.g., 45-34)" style="padding-right:45px">
<button class="history-btn" data-field="totalBill" title="View calculation history">ⓘ</button>
</div>
</div>

<div class="input-group">
<label for="afterDiscount">Total Bill After Discount (₹)</label>
<div style="position:relative">
<input type="text" id="afterDiscount" value="" placeholder="Enter amount or expression (e.g., 100x0.8)" style="padding-right:45px">
<button class="history-btn" data-field="afterDiscount" title="View calculation history">ⓘ</button>
</div>
</div>

<div class="discount-info" id="discountInfo" style="display:none">
<div class="discount-icon">📊</div>
<div class="discount-content">
<div class="discount-amount" id="discountAmount">₹0.00</div>
<div class="discount-detail" id="discountDetail">Total Discount</div>
</div>
</div>

<div class="result-header">
<h2 class="section-title" style="margin:0">Proration Result</h2>
<div class="toggle-container">
<span class="toggle-label">Custom Decimals</span>
<label class="toggle-switch">
<input type="checkbox" id="decimalToggle">
<span class="slider"></span>
</label>
<select id="decimalSelector" class="decimal-selector">
<option value="0">0 decimals</option>
<option value="1">1 decimal</option>
<option value="2">2 decimals</option>
<option value="3" selected>3 decimals</option>
<option value="4">4 decimals</option>
</select>
</div>
</div>

<div class="table-wrapper">
<table>
<thead>
<tr>
<th>Item</th>
<th>Original (₹)</th>
<th>% of Bill</th>
<th>Discount Rate</th>
<th>Prorated (₹)</th>
<th>Discount (₹)</th>
</tr>
</thead>
<tbody id="outputRows">
<tr><td colspan="6" class="empty-state">Add items and amounts to see calculations</td></tr>
</tbody>
<tfoot>
<tr class="totals-row">
<td style="text-align:left">TOTAL</td>
<td id="tOriginal" class="number">₹0.000</td>
<td class="number">100%</td>
<td id="tDiscountRate" class="number">0%</td>
<td id="tProrated" class="number">₹0.000</td>
<td id="tDiscount" class="number">₹0.000</td>
</tr>
</tfoot>
</table>
</div>
</div>

<script>
let items=[];
let nextId=1;
let useCustomDecimals=false;
let decimalPlaces=3;
let calculationHistory={};

function addItem(){
    items.push({id:nextId++,name:'',amount:0});
    renderTable();
}

function removeItem(id){
    if(items.length===1){
        alert('At least one item required');
        return;
    }
    items=items.filter(m=>m.id!==id);
    renderTable();
}

function updateName(id, val){
    const m=items.find(x=>x.id===id);
    if(m) m.name=val;
}

function updateAmount(id, val){
    const m=items.find(x=>x.id===id);
    if(m){
        m.amount=parseFloat(val)||0;
        calculate();
    }
}

function evaluateExpression(expr){
    try{
        expr = expr.replace(/\s/g, '').replace(/x|X/gi, '*');
        const result = Function('"use strict"; return (' + expr + ')')();
        return isFinite(result) ? result : 0;
    }catch(e){
        return null;
    }
}

function addToHistory(fieldId, expression, result){
    if(!calculationHistory[fieldId]){
        calculationHistory[fieldId] = [];
    }
    if(/[\+\-\*\/xX\(\)]/.test(expression)){
        calculationHistory[fieldId].unshift({
            expr: expression,
            result: result,
            time: new Date().toLocaleTimeString()
        });
        if(calculationHistory[fieldId].length > 20){
            calculationHistory[fieldId].pop();
        }
    }
}

function showHistory(fieldId, inputElement){
    hideAllHistories();
    
    const history = calculationHistory[fieldId] || [];
    
    const rect = inputElement.getBoundingClientRect();
    const popup = document.createElement('div');
    popup.className = 'history-popup';
    popup.id = 'active-history';
    popup.style.top = (rect.bottom + window.scrollY + 5) + 'px';
    popup.style.left = (rect.left + window.scrollX) + 'px';
    
    let html = '<div class="history-header">Calculation History</div>';
    
    if(history.length === 0){
        html += '<div class="history-empty">No calculations yet.<br>Type an expression and press Enter.</div>';
    } else {
        html += '<div class="history-list">';
        history.forEach((item, idx) => {
            html += `<div class="history-item">
                <div class="history-expr">${item.expr} = ${item.result}</div>
                <div class="history-time">${item.time}</div>
            </div>`;
        });
        html += '</div>';
    }
    
    popup.innerHTML = html;
    document.body.appendChild(popup);
}

function hideAllHistories(){
    const existing = document.getElementById('active-history');
    if(existing) existing.remove();
}

function renderTable(){
    const tbody=document.getElementById('itemRows');
    const focusedId=document.activeElement?.dataset?.id;
    const focusedType=document.activeElement?.className;
    const cursorPos=document.activeElement?.selectionStart;
    
    tbody.innerHTML='';
    
    items.forEach(m=>{
        const tr=document.createElement('tr');
        
        tr.innerHTML=`
        <td>
            <input type="text" value="${m.name}" data-id="${m.id}" class="name-input"
                placeholder="Enter name">
        </td>
        <td style="position:relative">
            <input type="text" value="${m.amount||''}" data-id="${m.id}" class="amount-input"
                placeholder="0 or 45-34" style="padding-right:40px">
            <button class="history-btn" data-field="item-${m.id}" title="View calculation history">ⓘ</button>
        </td>
        <td>
            <button class="btn btn-remove" data-id="${m.id}">✕</button>
        </td>`;
        tbody.appendChild(tr);
    });
    
    tbody.querySelectorAll('.name-input').forEach(input=>{
        input.addEventListener('input', (e)=>{
            updateName(parseInt(e.target.dataset.id), e.target.value);
        });
    });
    
    tbody.querySelectorAll('.amount-input').forEach(input=>{
        input.addEventListener('input', (e)=>{
            updateAmount(parseInt(e.target.dataset.id), e.target.value);
        });
        input.addEventListener('keydown', (e)=>{
            if(e.key === 'Enter'){
                e.preventDefault();
                const expr = e.target.value;
                const result = evaluateExpression(expr);
                if(result !== null){
                    const fieldId = 'item-' + e.target.dataset.id;
                    addToHistory(fieldId, expr, result);
                    e.target.value = result;
                    updateAmount(parseInt(e.target.dataset.id), result.toString());
                }
            }
        });
    });
    
    tbody.querySelectorAll('.history-btn').forEach(btn=>{
        btn.addEventListener('click', (e)=>{
            e.stopPropagation();
            const fieldId = e.target.dataset.field;
            const input = tbody.querySelector(`[data-id="${fieldId.split('-')[1]}"].amount-input`);
            showHistory(fieldId, input);
        });
    });
    
    tbody.querySelectorAll('.btn-remove').forEach(btn=>{
        btn.addEventListener('click', (e)=>{
            removeItem(parseInt(e.target.dataset.id));
        });
    });
    
    if(focusedId){
        const elementToFocus=tbody.querySelector(`[data-id="${focusedId}"].${focusedType}`);
        if(elementToFocus){
            elementToFocus.focus();
            if(cursorPos!==undefined && elementToFocus.setSelectionRange){
                elementToFocus.setSelectionRange(cursorPos, cursorPos);
            }
        }
    }
    
    calculate();
}

function calculate(){
    const totalBill=parseFloat(totalBillInput.value)||0;
    const after=parseFloat(afterDiscountInput.value)||0;

    if(after>totalBill && totalBill>0){
        afterDiscountInput.value=totalBill;
        return;
    }

    const out=document.getElementById('outputRows');
    const discountInfo=document.getElementById('discountInfo');
    const discountAmount=document.getElementById('discountAmount');
    const discountDetail=document.getElementById('discountDetail');
    
    out.innerHTML='';

    // Calculate sum of all items
    const sumOfItems = items.reduce((s,m)=>s+m.amount,0);

    if(!sumOfItems || totalBill===0){
        out.innerHTML='<tr><td colspan="6" class="empty-state">Add items and amounts to see calculations</td></tr>';
        tOriginal.textContent='₹0.000';
        tProrated.textContent='₹0.000';
        tDiscount.textContent='₹0.000';
        tDiscountRate.textContent='0%';
        discountInfo.style.display='none';
        return;
    }

    const decimals=useCustomDecimals?decimalPlaces:3;
    const discountRate = ((totalBill - after) / totalBill) * 100;
    const totalDiscountAmount = totalBill - after;
    
    // Show discount info
    discountInfo.style.display='flex';
    discountAmount.textContent = '₹' + totalDiscountAmount.toFixed(2);
    discountDetail.textContent = `Total Discount (${discountRate.toFixed(2)}% of ₹${totalBill.toFixed(2)})`;
    
    let sumProrated=0, sumDiscount=0;

    items.forEach(m=>{
        if(!m.amount) return;
        
        const percentOfBill = (m.amount / totalBill) * 100;
        const prorated = m.amount * (after / totalBill);
        const discount = m.amount - prorated;
        
        sumProrated += prorated;
        sumDiscount += discount;

        const tr=document.createElement('tr');
        tr.innerHTML=`
        <td style="text-align:left">${m.name||'Unnamed'}</td>
        <td class="number">₹${m.amount.toFixed(decimals)}</td>
        <td class="number">${percentOfBill.toFixed(2)}%</td>
        <td class="number">${discountRate.toFixed(2)}%</td>
        <td class="number">₹${prorated.toFixed(decimals)}</td>
        <td class="number">₹${discount.toFixed(decimals)}</td>`;
        out.appendChild(tr);
    });

    // TOTAL row sums from items, not from input fields
    tOriginal.textContent='₹'+sumOfItems.toFixed(decimals);
    tDiscountRate.textContent=discountRate.toFixed(2)+'%';
    tProrated.textContent='₹'+sumProrated.toFixed(decimals);
    tDiscount.textContent='₹'+sumDiscount.toFixed(decimals);
}

function resetAll(){
    items=[{id:1,name:'',amount:0}];
    nextId=2;
    totalBillInput.value='';
    afterDiscountInput.value='';
    decimalToggle.checked=false;
    useCustomDecimals=false;
    decimalSelector.classList.remove('active');
    decimalSelector.value='3';
    decimalPlaces=3;
    calculationHistory={};
    document.getElementById('discountInfo').style.display='none';
    renderTable();
}

const totalBillInput=document.getElementById('totalBill');
const afterDiscountInput=document.getElementById('afterDiscount');
const decimalToggle=document.getElementById('decimalToggle');
const decimalSelector=document.getElementById('decimalSelector');

totalBillInput.addEventListener('input', calculate);
afterDiscountInput.addEventListener('input', calculate);

totalBillInput.addEventListener('keydown', (e)=>{
    if(e.key === 'Enter'){
        e.preventDefault();
        const expr = e.target.value;
        const result = evaluateExpression(expr);
        if(result !== null){
            addToHistory('totalBill', expr, result);
            e.target.value = result;
            calculate();
        }
    }
});

afterDiscountInput.addEventListener('keydown', (e)=>{
    if(e.key === 'Enter'){
        e.preventDefault();
        const expr = e.target.value;
        const result = evaluateExpression(expr);
        if(result !== null){
            addToHistory('afterDiscount', expr, result);
            e.target.value = result;
            calculate();
        }
    }
});

document.querySelectorAll('.history-btn').forEach(btn=>{
    btn.addEventListener('click', (e)=>{
        e.stopPropagation();
        const fieldId = e.target.dataset.field;
        const input = document.getElementById(fieldId);
        showHistory(fieldId, input);
    });
});

document.addEventListener('click', (e)=>{
    if(!e.target.closest('.history-popup') && !e.target.closest('.history-btn')){
        hideAllHistories();
    }
});

/* Trigger addItem when Alt key is pressed */
document.addEventListener('keydown', (e)=>{
    if(e.key === 'Alt'){
        e.preventDefault();
        addItem();
    }
});

decimalToggle.addEventListener('change', (e)=>{
    useCustomDecimals=e.target.checked;
    decimalSelector.classList.toggle('active', useCustomDecimals);
    calculate();
});

decimalSelector.addEventListener('change', (e)=>{
    decimalPlaces=parseInt(e.target.value);
    calculate();
});

items=[{id:1,name:'',amount:0}];
nextId=2;
renderTable();
</script>

</body>
</html>
