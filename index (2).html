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
    background:linear-gradient(135deg,#667eea 0%,#764ba2 100%);
    min-height:100vh;
    padding:20px;
}
.container{
    max-width:1200px;
    margin:auto;
    background:#fff;
    border-radius:16px;
    box-shadow:0 20px 60px rgba(0,0,0,.3);
    padding:40px;
}
h1{
    font-size:28px;
    font-weight:700;
    margin-bottom:8px;
    color:#1a1a1a;
}
.subtitle{
    color:#6b7280;
    font-size:14px;
    margin-bottom:32px;
}
.section-title{
    font-size:18px;
    font-weight:700;
    margin-bottom:20px;
    color:#1a1a1a;
    display:flex;
    align-items:center;
    gap:8px;
}
.section-title::before{
    content:'';
    width:4px;
    height:24px;
    background:#667eea;
    border-radius:2px;
}
.table-wrapper{
    overflow-x:auto;
    margin-bottom:24px;
    border-radius:12px;
    border:1px solid #e5e7eb;
}
table{
    width:100%;
    border-collapse:separate;
    border-spacing:0;
    min-width:900px;
}
thead{
    background:linear-gradient(135deg,#667eea,#764ba2);
}
th{
    color:#fff;
    padding:16px 12px;
    font-size:13px;
    font-weight:600;
    text-align:left;
    border-bottom:3px solid #5568d3;
}
th:nth-child(2),
th:nth-child(3),
th:nth-child(4),
th:nth-child(5),
th:nth-child(6){
    text-align:right;
}
th:first-child{border-radius:12px 0 0 0}
th:last-child{border-radius:0 12px 0 0}
td{
    padding:14px 12px;
    border-bottom:1px solid #f3f4f6;
    font-size:14px;
    background:#fff;
}
tbody tr{
    transition:all .2s;
}
tbody tr:hover{
    background:#f9fafb;
    transform:translateX(2px);
}
tbody tr:last-child td{border-bottom:none}
input{
    width:100%;
    padding:10px 12px;
    border:2px solid #e5e7eb;
    border-radius:8px;
    font-size:14px;
    transition:all .2s;
    font-family:inherit;
}
input:hover{
    border-color:#cbd5e1;
}
input:focus{
    border-color:#667eea;
    outline:none;
    box-shadow:0 0 0 4px rgba(102,126,234,0.1);
}
.btn{
    padding:12px 24px;
    border:none;
    border-radius:10px;
    cursor:pointer;
    font-weight:600;
    font-size:14px;
    margin:0 12px 12px 0;
    transition:all .2s;
    display:inline-flex;
    align-items:center;
    gap:8px;
    font-family:inherit;
}
.btn:hover{
    transform:translateY(-2px);
    box-shadow:0 8px 16px rgba(0,0,0,.15);
}
.btn:active{
    transform:translateY(0);
}
.btn-add{
    background:linear-gradient(135deg,#10b981,#059669);
    color:#fff;
}
.btn-reset{
    background:linear-gradient(135deg,#f59e0b,#d97706);
    color:#fff;
}
.btn-remove{
    background:linear-gradient(135deg,#ef4444,#dc2626);
    color:#fff;
    font-size:13px;
    padding:8px 16px;
    margin:0;
}
.input-group{
    margin-bottom:24px;
}
.input-group label{
    display:block;
    font-weight:600;
    font-size:15px;
    margin-bottom:8px;
    color:#374151;
}
.input-group input{
    padding:14px 16px;
    font-size:16px;
}
.number{
    text-align:right;
    font-family:'SF Mono',Monaco,Consolas,monospace;
    font-size:14px;
    font-weight:500;
}
.empty-state{
    text-align:center;
    color:#9ca3af;
    padding:40px;
    font-size:14px;
}
.totals-row{
    background:linear-gradient(135deg,#f3f4f6,#e5e7eb);
    font-weight:700;
    border-top:3px solid #667eea;
}
.totals-row td{
    font-size:15px;
    padding:18px 12px;
    color:#1a1a1a;
}
.discount-info{
    background:linear-gradient(135deg,#eff6ff,#dbeafe);
    border-left:4px solid #3b82f6;
    padding:20px 24px;
    margin-bottom:32px;
    border-radius:12px;
    display:flex;
    align-items:center;
    gap:16px;
}
.discount-icon{
    width:48px;
    height:48px;
    background:linear-gradient(135deg,#3b82f6,#2563eb);
    border-radius:12px;
    display:flex;
    align-items:center;
    justify-content:center;
    font-size:24px;
    flex-shrink:0;
}
.discount-content{
    flex:1;
}
.discount-amount{
    font-size:24px;
    font-weight:700;
    color:#1e40af;
    margin-bottom:4px;
}
.discount-detail{
    font-size:14px;
    color:#1e40af;
}
.toggle-container{
    display:flex;
    align-items:center;
    gap:12px;
}
.toggle-label{
    font-size:14px;
    color:#6b7280;
    font-weight:600;
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
    background:#d1d5db;
    transition:all .3s;
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
    transition:all .3s;
    border-radius:50%;
    box-shadow:0 2px 4px rgba(0,0,0,.2);
}
input:checked + .slider{
    background:linear-gradient(135deg,#667eea,#764ba2);
}
input:checked + .slider:before{
    transform:translateX(22px);
}
.decimal-selector{
    padding:6px 12px;
    border:2px solid #667eea;
    border-radius:8px;
    font-size:13px;
    background:white;
    cursor:pointer;
    transition:all .3s;
    opacity:0;
    transform:scale(0.95);
    pointer-events:none;
    font-family:inherit;
    font-weight:600;
}
.decimal-selector.active{
    opacity:1;
    transform:scale(1);
    pointer-events:all;
}
.decimal-selector:hover{
    background:#f9fafb;
    border-color:#5568d3;
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
    background:linear-gradient(135deg,#667eea,#764ba2);
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
    box-shadow:0 2px 8px rgba(102,126,234,.3);
}
.history-btn:hover{
    transform:translateY(-50%) scale(1.1);
    box-shadow:0 4px 12px rgba(102,126,234,.5);
}
.history-popup{
    position:absolute;
    background:#fff;
    border:2px solid #667eea;
    border-radius:12px;
    box-shadow:0 8px 24px rgba(0,0,0,.15);
    z-index:1000;
    min-width:300px;
    max-width:380px;
}
.history-header{
    background:linear-gradient(135deg,#667eea,#764ba2);
    color:#fff;
    padding:14px 18px;
    font-weight:700;
    font-size:14px;
    border-radius:10px 10px 0 0;
}
.history-list{
    max-height:240px;
    overflow-y:auto;
    padding:12px;
}
.history-item{
    padding:12px;
    border-bottom:1px solid #f3f4f6;
    font-size:13px;
    border-radius:6px;
    margin-bottom:8px;
}
.history-item:last-child{
    border-bottom:none;
    margin-bottom:0;
}
.history-item:hover{
    background:#f9fafb;
}
.history-expr{
    font-family:'SF Mono',Monaco,Consolas,monospace;
    color:#1a1a1a;
    font-weight:600;
    margin-bottom:4px;
}
.history-time{
    font-size:11px;
    color:#9ca3af;
}
.history-empty{
    text-align:center;
    padding:32px 20px;
    color:#9ca3af;
    font-size:13px;
    line-height:1.6;
}
.history-list::-webkit-scrollbar{
    width:8px;
}
.history-list::-webkit-scrollbar-track{
    background:#f3f4f6;
    border-radius:4px;
}
.history-list::-webkit-scrollbar-thumb{
    background:#667eea;
    border-radius:4px;
}
.history-list::-webkit-scrollbar-thumb:hover{
    background:#5568d3;
}
.result-header{
    display:flex;
    justify-content:space-between;
    align-items:center;
    margin-bottom:20px;
}
@media (max-width: 768px){
    .container{padding:24px}
    h1{font-size:24px}
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
