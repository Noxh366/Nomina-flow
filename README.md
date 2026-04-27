<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>NóminaFlow Fiscal 2026</title>
<style>
@import url('https://fonts.googleapis.com/css2?family=IBM+Plex+Sans:wght@400;500&family=IBM+Plex+Mono:wght@400;500&display=swap');
*{box-sizing:border-box;margin:0;padding:0}
:root{
  --bg:#F5F4F1;--sur:#fff;--sur2:#ECEAE4;--bdr:#DDD9D0;
  --tx:#1C1917;--tx2:#6B6560;--tx3:#9C9890;
  --blue:#1D4ED8;--bl2:#EEF2FF;--bl3:#1e3a8a;
  --grn:#0F6E56;--gr2:#E1F5EE;
  --amb:#92400E;--am2:#FEF3C7;
  --red:#991B1B;--re2:#FEF2F2;
  --pur:#5B21B6;--pu2:#EDE9FE;
  --teal:#0F766E;--tl2:#F0FDFA;
}
body{font-family:'IBM Plex Sans',sans-serif;background:var(--bg);color:var(--tx);font-size:13px}
.topbar{background:#1C1917;color:#fff;padding:11px 18px;display:flex;align-items:center;justify-content:space-between;position:sticky;top:0;z-index:200}
.brand{display:flex;align-items:center;gap:9px}
.bico{width:28px;height:28px;background:var(--blue);border-radius:6px;display:flex;align-items:center;justify-content:center;font-size:11px;font-weight:500;color:#fff;flex-shrink:0}
.bnm{font-size:13px;font-weight:500}.bsb{font-size:10px;color:rgba(255,255,255,.4);margin-top:1px}
.nav{background:var(--sur);border-bottom:1px solid var(--bdr);padding:0 18px;display:flex;overflow-x:auto}
.nb{padding:10px 14px;border:none;background:none;font-family:'IBM Plex Sans',sans-serif;font-size:12px;color:var(--tx2);cursor:pointer;border-bottom:2px solid transparent;white-space:nowrap}
.nb.on{color:var(--blue);border-bottom-color:var(--blue);font-weight:500}
.nb:hover:not(.on){background:var(--sur2);color:var(--tx)}
.main{padding:18px;max-width:1200px;margin:0 auto}
.stats{display:grid;grid-template-columns:repeat(4,1fr);gap:10px;margin-bottom:14px}
.stat{background:var(--sur);border:1px solid var(--bdr);border-radius:8px;padding:13px}
.slbl{font-size:10px;color:var(--tx3);text-transform:uppercase;letter-spacing:.5px;margin-bottom:4px}
.sval{font-size:18px;font-weight:500;font-family:'IBM Plex Mono',monospace;letter-spacing:-.5px}
.ssub{font-size:10px;color:var(--tx3);margin-top:3px}
.cbl{color:var(--blue)}.cgr{color:var(--grn)}.cam{color:var(--amb)}.crd{color:var(--red)}.cpr{color:var(--pur)}.ctl{color:var(--teal)}
.card{background:var(--sur);border:1px solid var(--bdr);border-radius:12px;overflow:hidden;margin-bottom:14px}
.ch{padding:12px 16px;border-bottom:1px solid var(--bdr);display:flex;align-items:center;justify-content:space-between;flex-wrap:wrap;gap:8px}
.ct{font-size:13px;font-weight:500}
.btn{padding:6px 12px;border-radius:8px;border:1px solid var(--bdr);font-family:'IBM Plex Sans',sans-serif;font-size:12px;cursor:pointer;display:inline-flex;align-items:center;gap:5px;background:var(--sur);color:var(--tx)}
.btn:hover{background:var(--sur2)}
.bp{background:var(--blue);color:#fff;border-color:var(--blue)}.bp:hover{background:#1637b0}
.bg{background:var(--grn);color:#fff;border-color:var(--grn)}.bg:hover{background:#0a5040}
.bd{background:var(--re2);color:var(--red);border-color:#fecaca}
.btl{background:var(--tl2);color:var(--teal);border-color:#99f6e4}
.sm{padding:4px 8px;font-size:11px}
.br{display:flex;gap:7px;flex-wrap:wrap;align-items:center}
table{width:100%;border-collapse:collapse;font-size:12px}
thead th{text-align:left;padding:8px 10px;font-size:10px;color:var(--tx3);text-transform:uppercase;letter-spacing:.4px;background:var(--bg);border-bottom:1px solid var(--bdr);font-weight:500;white-space:nowrap}
tbody tr{border-bottom:1px solid var(--bdr)}
tbody tr:last-child{border-bottom:none}
tbody tr:hover{background:var(--sur2)}
td{padding:9px 10px;vertical-align:middle}
.num{font-family:'IBM Plex Mono',monospace;font-size:12px;white-space:nowrap}
.fg{display:flex;flex-direction:column;gap:4px}
.fg label{font-size:11px;color:var(--tx2);font-weight:500}
input[type=text],input[type=number],input[type=date],select{padding:7px 10px;border:1px solid var(--bdr);border-radius:8px;font-family:'IBM Plex Sans',sans-serif;font-size:12px;color:var(--tx);background:var(--sur);width:100%}
input:focus,select:focus{outline:none;border-color:var(--blue)}
.fw{position:relative}.fw input{padding-left:20px}
.fws{position:absolute;left:8px;top:50%;transform:translateY(-50%);font-size:12px;color:var(--tx3);pointer-events:none}
.ov{position:fixed;inset:0;background:rgba(0,0,0,.42);display:flex;align-items:center;justify-content:center;z-index:999;padding:16px}
.modal{background:var(--sur);border-radius:12px;width:100%;max-width:520px;max-height:93vh;overflow-y:auto}
.mh{padding:16px 20px 12px;border-bottom:1px solid var(--bdr);display:flex;align-items:center;justify-content:space-between}
.mt{font-size:15px;font-weight:500}
.mb{padding:16px 20px}
.mf{padding:12px 20px;border-top:1px solid var(--bdr);display:flex;justify-content:flex-end;gap:8px}
.cx{background:none;border:none;cursor:pointer;color:var(--tx3);font-size:18px;line-height:1}
.badge{display:inline-flex;align-items:center;padding:2px 7px;border-radius:20px;font-size:10px;font-weight:500}
.bsm{background:var(--am2);color:var(--amb)}.bqn{background:var(--bl2);color:var(--bl3)}
.av{display:flex;align-items:center;justify-content:center;border-radius:50%;font-weight:500;color:#fff;flex-shrink:0}
.dbox{background:var(--bg);border:1px solid var(--bdr);border-radius:8px;overflow:hidden}
.dr{display:flex;justify-content:space-between;align-items:center;padding:7px 11px;border-bottom:1px solid var(--bdr);font-size:12px}
.dr:last-child{border-bottom:none}
.drs{background:var(--sur2);font-size:10px;font-weight:500;text-transform:uppercase;letter-spacing:.5px;color:var(--tx2)}
.drt{background:var(--bl2);font-weight:500;color:var(--bl3)}
.drn{background:var(--gr2);font-weight:500;color:var(--grn);font-size:13px}
.drb{background:var(--tl2);font-weight:500;color:var(--teal);font-size:13px}
.ded{color:var(--red)}
.dlbl{color:var(--tx2)}.dval{font-family:'IBM Plex Mono',monospace;font-weight:500}
.dz{border:2px dashed var(--bdr);border-radius:12px;padding:28px;text-align:center;cursor:pointer;background:var(--bg)}
.dz:hover{border-color:var(--blue);background:var(--bl2)}
.info{background:var(--bl2);border:1px solid #c7d7f7;border-radius:8px;padding:9px 12px;font-size:11px;color:var(--bl3);margin-bottom:12px;line-height:1.6}
.infotl{background:var(--tl2);border:1px solid #99f6e4;border-radius:8px;padding:9px 12px;font-size:11px;color:var(--teal);margin-bottom:12px;line-height:1.6}
.warn{background:var(--am2);border:1px solid #fcd34d;border-radius:8px;padding:9px 12px;font-size:11px;color:var(--amb);line-height:1.6}
.g2{display:grid;grid-template-columns:1fr 1fr;gap:12px}
.pbar{background:var(--sur);border:1px solid var(--bdr);border-radius:8px;padding:9px 13px;display:flex;align-items:center;gap:10px;flex-wrap:wrap;margin-bottom:13px}
.pbar label{font-size:11px;color:var(--tx2);font-weight:500;white-space:nowrap}
.ptabs{display:flex;background:var(--bg);border:1px solid var(--bdr);border-radius:8px;padding:3px;gap:2px}
.pt{flex:1;padding:5px 10px;border-radius:6px;border:none;font-family:'IBM Plex Sans',sans-serif;font-size:11px;cursor:pointer;background:none;color:var(--tx2);text-align:center}
.pt.on{background:var(--sur);color:var(--tx);font-weight:500}
.empty{text-align:center;padding:36px;color:var(--tx3)}
.bono-row{display:flex;align-items:center;gap:8px;padding:7px 10px;border-bottom:1px solid var(--bdr);font-size:12px;background:var(--tl2)}
.bono-row:last-child{border-bottom:none}
#toast{position:fixed;bottom:18px;right:18px;background:#1C1917;color:#fff;padding:9px 15px;border-radius:8px;font-size:12px;z-index:9999;display:none}
</style>
</head>
<body>
<div id="app">
  <div class="topbar">
    <div class="brand">
      <div class="bico">NF</div>
      <div><div class="bnm">NóminaFlow Fiscal 2026</div><div class="bsb">ISR + IMSS + INFONAVIT + Bonos — Tablas oficiales SAT/IMSS</div></div>
    </div>
    <div style="font-size:10px;color:rgba(255,255,255,.35);font-family:'IBM Plex Mono',monospace" id="fdate"></div>
  </div>
  <nav class="nav" id="nav">
    <button class="nb on" onclick="goTab('emp')">Plantilla</button>
    <button class="nb" onclick="goTab('calc')">Cálculo de nómina</button>
    <button class="nb" onclick="goTab('hist')">Historial</button>
    <button class="nb" onclick="goTab('imp')">Importar BD</button>
    <button class="nb" onclick="goTab('rep')">Reportes</button>
  </nav>
  <div class="main" id="ct"></div>
</div>
<div id="toast"></div>
<script src="https://cdnjs.cloudflare.com/ajax/libs/xlsx/0.18.5/xlsx.full.min.js"></script>
<script>
// ═══════════════════════════════════════
// CONSTANTES FISCALES 2026
// ═══════════════════════════════════════
var UMA_D=113.14, UMA_M=UMA_D*30.4, SM_M=315.04*30.4;

var ISR_T=[
  {li:0.01,      ls:844.59,      cf:0,         p:1.92},
  {li:844.60,    ls:7168.51,     cf:16.22,     p:6.40},
  {li:7168.52,   ls:12598.02,    cf:420.95,    p:10.88},
  {li:12598.03,  ls:14644.64,    cf:1011.68,   p:16.00},
  {li:14644.65,  ls:17533.64,    cf:1339.14,   p:17.92},
  {li:17533.65,  ls:35362.83,    cf:1856.84,   p:21.36},
  {li:35362.84,  ls:55736.68,    cf:5665.16,   p:23.52},
  {li:55736.69,  ls:106410.50,   cf:10457.09,  p:30.00},
  {li:106410.51, ls:141880.66,   cf:25659.23,  p:32.00},
  {li:141880.67, ls:425641.99,   cf:37009.69,  p:34.00},
  {li:425642.00, ls:1e15,        cf:133488.54, p:35.00}
];

function r2(n){ return Math.round((Number(n)||0)*100)/100; }

function calcISR(base, per){
  if(base<=0) return {bruto:0, sub:0, neto:0};
  var f = per==='mensual'?1 : per==='quincenal'?0.5 : 0.23077;
  var bM=base/f, brutoM=0;
  for(var i=0;i<ISR_T.length;i++){
    var t=ISR_T[i];
    if(bM>=t.li && bM<=t.ls){ brutoM=t.cf+(bM-t.li)*t.p/100; break; }
  }
  var subM = bM<=11492.66 ? 536.22 : 0;
  return { bruto:r2(brutoM*f), sub:r2(subM*f), neto:r2(Math.max(0,brutoM-subM)*f) };
}

function getCEAV(s){
  var sm=SM_M;
  if(s<=sm)       return s*0.03150;
  if(s<=sm*1.5)   return s*0.03281;
  if(s<=sm*2)     return s*0.03683;
  if(s<=sm*2.5)   return s*0.04085;
  if(s<=sm*3)     return s*0.04487;
  if(s<=sm*3.5)   return s*0.04889;
  if(s<=sm*4)     return s*0.05291;
  return s*0.07513;
}

// nominal = sueldo dado de alta en Hacienda (base gravable)
// total   = lo que recibe el empleado en total
// libre   = total - nominal  (calculado automáticamente)
// bono    = extra libre de impuestos en este periodo
function calcNomina(nominal, total, per, bono){
  var nom  = r2(Number(nominal)||0);
  var tot  = r2(Number(total)||0);
  var lib  = r2(Math.max(0, tot - nom));   // sueldo libre = total - nominal
  var bon  = r2(Number(bono)||0);          // bono del periodo (libre de impuestos)
  var f    = per==='mensual'?1 : per==='quincenal'?0.5 : 0.23077;
  var nomM = r2(nom/f);
  var sdD  = r2(nomM/30.4);
  var sbcM = r2(Math.min(sdD*1.0493*30.4, UMA_D*25*30.4));
  var exc3 = Math.max(0, sbcM - UMA_M*3);

  // IMSS obrero mensual
  var obM={
    emExc: exc3*0.0040,
    emDin: sbcM*0.0025,
    pens:  sbcM*0.00375,
    inv:   sbcM*0.00625,
    ceav:  sbcM*0.01125
  };
  obM.total = obM.emExc+obM.emDin+obM.pens+obM.inv+obM.ceav;

  // IMSS patronal mensual
  var patM={
    emFija: UMA_M*0.2040,
    emExc:  exc3*0.0110,
    emDin:  sbcM*0.0070,
    pens:   sbcM*0.00375,
    inv:    sbcM*0.01750,
    riesgo: sbcM*0.0054,
    guard:  sbcM*0.0100,
    retiro: sbcM*0.0200,
    ceav:   getCEAV(sbcM)
  };
  patM.total = patM.emFija+patM.emExc+patM.emDin+patM.pens+patM.inv+patM.riesgo+patM.guard+patM.retiro+patM.ceav;

  var infoM = sbcM*0.05;

  // Escalar al periodo
  function sc(o){
    var res={};
    Object.keys(o).forEach(function(k){ res[k]=r2(o[k]*f); });
    return res;
  }
  var ob=sc(obM), pat=sc(patM), info=r2(infoM*f);

  // ISR sobre el sueldo nominal del periodo
  var baseISR = r2(Math.max(0, nom - ob.total));
  var isr = calcISR(baseISR, per);

  // Deducciones
  var ded  = r2(isr.neto + ob.total);

  // Neto base (sin bono)
  var netoBase = r2(tot - ded);

  // Neto final (con bono, libre de impuestos)
  var netoFinal = r2(netoBase + bon);

  // Costo empresa = sueldo total + cuotas patronales (bono no genera cuotas)
  var costo = r2(tot + pat.total + info);

  return {
    nom:nom, lib:lib, tot:tot, bon:bon,
    baseISR:baseISR,
    isrBruto:isr.bruto, subsidio:isr.sub, isrNeto:isr.neto,
    ob:ob, pat:pat, info:info,
    ded:ded, netoBase:netoBase, netoFinal:netoFinal,
    costo:costo, sbc:sbcM, sdDiario:sdD
  };
}

// ═══════════════════════════════════════
// UTILS
// ═══════════════════════════════════════
function fmt(n){ return(Number(n)||0).toLocaleString('es-MX',{style:'currency',currency:'MXN',minimumFractionDigits:2}); }
function fmts(n){ var v=Number(n)||0; if(v>=1e6)return'$'+(v/1e6).toFixed(2)+'M'; if(v>=1000)return'$'+(v/1000).toFixed(1)+'K'; return fmt(v); }
function gid(){ return Date.now().toString(36)+Math.random().toString(36).slice(2,6); }
function hoy(){ return new Date().toLocaleDateString('es-MX',{day:'2-digit',month:'short',year:'numeric'}); }
function isoHoy(){ return new Date().toISOString().slice(0,10); }
function isoIni(){ return isoHoy().slice(0,8)+'01'; }
var COLS=['#1D4ED8','#0F6E56','#92400E','#991B1B','#5B21B6','#065F46','#0F766E'];
function avc(n){ var h=0; for(var i=0;i<n.length;i++) h+=n.charCodeAt(i); return COLS[h%COLS.length]; }
function ini(n){ return n.split(' ').slice(0,2).map(function(p){ return p[0]||''; }).join('').toUpperCase(); }
function esc(s){ return String(s||'').replace(/&/g,'&amp;').replace(/"/g,'&quot;').replace(/</g,'&lt;').replace(/>/g,'&gt;'); }
function showToast(msg){ var t=document.getElementById('toast'); t.textContent=msg; t.style.display='block'; clearTimeout(window._tt); window._tt=setTimeout(function(){ t.style.display='none'; },2600); }

// ═══════════════════════════════════════
// ESTADO
// ═══════════════════════════════════════
var S={
  emp:[], hist:[],
  tab:'emp', period:'quincenal', search:'',
  rpNombre:'', rpIni:isoIni(), rpFin:isoHoy(),
  bonos:{},        // { empId: monto } — bonos del periodo actual en cálculo
  prestamos:{},    // { empId: monto } — descuento préstamo del periodo actual
  modalType:null, editId:null,
  detId:null, detPer:'mensual'
};

function persist(){
  try{
    localStorage.setItem('nf5_emp',JSON.stringify(S.emp));
    localStorage.setItem('nf5_hist',JSON.stringify(S.hist));
  }catch(e){}
}
function loadData(){
  try{
    var e=localStorage.getItem('nf5_emp'), h=localStorage.getItem('nf5_hist');
    if(e) S.emp=JSON.parse(e);
    if(h) S.hist=JSON.parse(h);
  }catch(e){}
}

// ═══════════════════════════════════════
// RENDER
// ═══════════════════════════════════════
var TABS=['emp','calc','hist','imp','rep'];
function goTab(name){
  S.tab=name;
  document.querySelectorAll('#nav .nb').forEach(function(b,i){ b.classList.toggle('on',TABS[i]===name); });
  renderAll();
}
function removeOv(){ var m=document.getElementById('_mc'),d=document.getElementById('_dc'); if(m)m.remove(); if(d)d.remove(); }
function renderAll(){
  removeOv();
  var el=document.getElementById('ct');
  if(S.tab==='emp')       el.innerHTML=pageEmp();
  else if(S.tab==='calc') el.innerHTML=pageCalc();
  else if(S.tab==='hist') el.innerHTML=pageHist();
  else if(S.tab==='imp')  el.innerHTML=pageImp();
  else if(S.tab==='rep')  el.innerHTML=pageRep();
  if(S.modalType) buildModal();
  if(S.detId) buildDet();
}

function stHTML(lbl,val,cls,sub){
  return '<div class="stat"><div class="slbl">'+lbl+'</div><div class="sval '+cls+'">'+val+'</div><div class="ssub">'+sub+'</div></div>';
}

// ═══════════════════════════════════════
// PLANTILLA
// ═══════════════════════════════════════
function pageEmp(){
  var fil=S.emp.filter(function(e){
    if(!S.search) return true;
    var s=S.search.toLowerCase();
    return (e.nombre||'').toLowerCase().indexOf(s)>=0||(e.puesto||'').toLowerCase().indexOf(s)>=0;
  });
  var tNom=0,tLib=0,tCosto=0;
  S.emp.forEach(function(e){
    tNom+=Number(e.nominal)||0;
    tLib+=r2(Math.max(0,(Number(e.total)||0)-(Number(e.nominal)||0)));
    tCosto+=calcNomina(e.nominal,e.total,'mensual',0).costo;
  });
  var rows='';
  fil.forEach(function(e){
    var r=calcNomina(e.nominal,e.total,'mensual',0);
    rows+='<tr onclick="openDet(\''+e.id+'\')" style="cursor:pointer">'+
      '<td><div style="display:flex;align-items:center;gap:8px">'+
        '<div class="av" style="width:28px;height:28px;font-size:10px;background:'+avc(e.nombre)+'">'+ini(e.nombre)+'</div>'+
        '<div><div style="font-weight:500">'+esc(e.nombre)+'</div><div style="font-size:10px;color:var(--tx3)">'+esc(e.puesto||'—')+'</div></div>'+
      '</div></td>'+
      '<td><span class="badge '+(e.freq==='semanal'?'bsm':'bqn')+'">'+(e.freq==='semanal'?'Semanal':'Quincenal')+'</span></td>'+
      '<td class="num cam">'+fmt(e.nominal)+'</td>'+
      '<td class="num" style="color:var(--tx2)">'+fmt(r.lib)+'</td>'+
      '<td class="num" style="font-size:11px;color:var(--tx2)">'+fmt(r.tot)+'</td>'+
      '<td class="num crd" style="font-size:11px">'+fmt(r.isrNeto)+'</td>'+
      '<td class="num" style="font-size:11px">'+fmt(r.ob.total)+'</td>'+
      '<td class="num cbl" style="font-weight:500">'+fmt(r.netoBase)+'</td>'+
      '<td onclick="event.stopPropagation()"><div style="display:flex;gap:5px">'+
        '<button class="btn sm" onclick="openEdit(\''+e.id+'\')">✏</button>'+
        '<button class="btn sm bd" onclick="delEmp(\''+e.id+'\')">✕</button>'+
      '</div></td>'+
    '</tr>';
  });
  var tbl = fil.length===0
    ? '<div class="empty">'+(S.emp.length===0?'Sin empleados — usa + Agregar':'Sin resultados')+'</div>'
    : '<div style="overflow-x:auto"><table><thead><tr>'+
        '<th>Empleado</th><th>Frec.</th><th>Nómina Hacienda</th><th>Sueldo libre</th><th>Total recibe</th><th>ISR mes</th><th>IMSS obrero</th><th>Neto base</th><th></th>'+
      '</tr></thead><tbody>'+rows+'</tbody></table></div>';
  return '<div class="stats">'+
    stHTML('Empleados',S.emp.length,'cbl','en plantilla')+
    stHTML('Nómina Hacienda mensual',fmts(tNom),'cam','base gravable')+
    stHTML('Sueldo libre mensual',fmts(tLib),'cgr','libre de impuestos')+
    stHTML('Costo empresa mensual',fmts(tCosto),'cpr','incl. cuotas patronales')+
  '</div>'+
  '<div class="card"><div class="ch"><div class="ct">Plantilla de empleados</div>'+
    '<div class="br">'+
      '<input type="text" placeholder="Buscar..." value="'+esc(S.search)+'" oninput="S.search=this.value;renderAll()" style="width:160px;padding:5px 8px">'+
      '<button class="btn bp" onclick="openAdd()">+ Agregar</button>'+
    '</div></div>'+tbl+'</div>';
}

// ═══════════════════════════════════════
// CÁLCULO DE NÓMINA (con bonos)
// ═══════════════════════════════════════
function getBono(id){ return r2(Number(S.bonos[id])||0); }
function getPrestamo(id){ return r2(Number(S.prestamos[id])||0); }

function setBono(id, val){
  S.bonos[id]=r2(Number(val)||0);
  // Actualizar solo la celda del bono y los totales sin re-renderizar todo
  var inp=document.getElementById('bono_'+id);
  if(inp) inp.value=S.bonos[id]||'';
  recalcTotals();
}

function recalcTotals(){
  var p=S.period;
  var tNeto=0,tISR=0,tOb=0,tCosto=0,tBono=0,tNetoFinal=0,tPrest=0;
  S.emp.forEach(function(e){
    var bon=getBono(e.id);
    var prest=getPrestamo(e.id);
    var r=calcNomina(e.nominal,e.total,p,bon);
    var netoConPrest=r2(r.netoFinal - prest);
    tNeto+=r.netoBase; tISR+=r.isrNeto; tOb+=r.ob.total;
    tCosto+=r.costo; tBono+=bon; tNetoFinal+=netoConPrest; tPrest+=prest;
    // actualizar fila
    var cells=['_tneto_'+e.id,'_tbono_'+e.id,'_tprest_'+e.id,'_tfinal_'+e.id,'_tcosto_'+e.id];
    var vals=[fmt(r.netoBase),fmt(bon),fmt(prest),fmt(netoConPrest),fmt(r.costo)];
    cells.forEach(function(cid,i){
      var el=document.getElementById(cid);
      if(el) el.textContent=vals[i];
    });
  });
  // totales de la tabla
  ['_tot_netobase','_tot_bono','_tot_prest','_tot_neto','_tot_costo'].forEach(function(id,i){
    var el=document.getElementById(id);
    if(el) el.textContent=[fmt(tNeto),fmt(tBono),fmt(tPrest),fmt(tNetoFinal),fmt(tCosto)][i];
  });
  // stats cards
  var statsMap={
    '_st_neto':fmt(tNetoFinal), '_st_isr':fmt(tISR),
    '_st_ob':fmt(tOb), '_st_costo':fmt(tCosto)
  };
  Object.keys(statsMap).forEach(function(id){
    var el=document.getElementById(id);
    if(el) el.textContent=statsMap[id];
  });
}

function pageCalc(){
  var p=S.period;
  var tNeto=0,tISR=0,tOb=0,tCosto=0,tBono=0,tNetoFinal=0,tPrest=0;
  var rows='';
  S.emp.forEach(function(e){
    var bon=getBono(e.id);
    var prest=getPrestamo(e.id);
    var r=calcNomina(e.nominal,e.total,p,bon);
    var netoConPrest=r2(r.netoFinal - prest);
    tNeto+=r.netoBase; tISR+=r.isrNeto; tOb+=r.ob.total;
    tCosto+=r.costo; tBono+=bon; tNetoFinal+=netoConPrest; tPrest+=prest;
    rows+='<tr>'+
      '<td><div style="display:flex;align-items:center;gap:8px">'+
        '<div class="av" style="width:24px;height:24px;font-size:9px;background:'+avc(e.nombre)+'">'+ini(e.nombre)+'</div>'+
        '<span style="font-weight:500">'+esc(e.nombre)+'</span>'+
      '</div></td>'+
      '<td class="num cam">'+fmt(r.nom)+'</td>'+
      '<td class="num" style="color:var(--tx2)">'+fmt(r.lib)+'</td>'+
      '<td class="num crd">'+fmt(r.isrNeto)+'</td>'+
      '<td class="num">'+fmt(r.ob.total)+'</td>'+
      '<td class="num cbl" id="_tneto_'+e.id+'">'+fmt(r.netoBase)+'</td>'+
      '<td>'+
        '<div class="fw" style="width:120px">'+
          '<span class="fws">$</span>'+
          '<input type="number" id="bono_'+e.id+'" min="0" step="0.01" value="'+(bon||'')+'" '+
            'oninput="S.bonos[\''+e.id+'\']=parseFloat(this.value)||0;recalcTotals()" '+
            'style="padding:4px 6px 4px 18px;font-size:12px;font-family:\'IBM Plex Mono\',monospace;border-radius:6px;border:1px solid var(--bdr);color:var(--teal);width:100%">'+
        '</div>'+
      '</td>'+
      '<td class="num ctl" style="font-weight:500" id="_tbono_'+e.id+'">'+fmt(bon)+'</td>'+
      '<td>'+
        '<div class="fw" style="width:120px">'+
          '<span class="fws">$</span>'+
          '<input type="number" id="prest_'+e.id+'" min="0" step="0.01" value="'+(prest||'')+'" '+
            'oninput="S.prestamos[\''+e.id+'\']=parseFloat(this.value)||0;recalcTotals()" '+
            'style="padding:4px 6px 4px 18px;font-size:12px;font-family:\'IBM Plex Mono\',monospace;border-radius:6px;border:1px solid #fecaca;color:var(--red);width:100%">'+
        '</div>'+
      '</td>'+
      '<td class="num crd" style="font-weight:500" id="_tprest_'+e.id+'">'+fmt(prest)+'</td>'+
      '<td class="num cbl" style="font-weight:500;font-size:13px" id="_tfinal_'+e.id+'">'+fmt(netoConPrest)+'</td>'+
      '<td class="num cpr" style="font-size:11px" id="_tcosto_'+e.id+'">'+fmt(r.costo)+'</td>'+
      '<td><button class="btn sm" onclick="openDetCalc(\''+e.id+'\',\''+p+'\')">Detalle</button></td>'+
    '</tr>';
  });

  var pn=p.charAt(0).toUpperCase()+p.slice(1);
  var cuerpo = S.emp.length===0
    ? '<div class="empty">Agrega empleados en Plantilla primero</div>'
    : '<div style="overflow-x:auto"><table><thead><tr>'+
        '<th>Empleado</th><th>Nómina Hacienda</th><th>Sueldo libre</th>'+
        '<th>ISR</th><th>IMSS obrero</th><th>Neto base</th>'+
        '<th>Bono (libre imp.)</th><th>Bono $</th><th>Desc. Préstamo</th><th>Préstamo $</th><th>Neto final</th><th>Costo empresa</th><th></th>'+
      '</tr></thead><tbody>'+rows+'</tbody>'+
      '<tfoot><tr style="background:var(--bg);font-weight:500">'+
        '<td colspan="5" style="padding:9px 10px">Totales del periodo</td>'+
        '<td class="num cbl" style="padding:9px 10px" id="_tot_netobase">'+fmt(tNeto)+'</td>'+
        '<td colspan="1"></td>'+
        '<td class="num ctl" style="padding:9px 10px" id="_tot_bono">'+fmt(tBono)+'</td>'+
        '<td colspan="1"></td>'+
        '<td class="num crd" style="padding:9px 10px" id="_tot_prest">'+fmt(tPrest)+'</td>'+
        '<td class="num cbl" style="padding:9px 10px;font-size:14px" id="_tot_neto">'+fmt(tNetoFinal)+'</td>'+
        '<td class="num cpr" style="padding:9px 10px" id="_tot_costo">'+fmt(tCosto)+'</td>'+
        '<td></td>'+
      '</tr></tfoot></table></div>';

  return '<div style="display:flex;align-items:center;justify-content:space-between;margin-bottom:12px;flex-wrap:wrap;gap:8px">'+
    '<div style="font-size:17px;font-weight:500">Cálculo de nómina</div>'+
    '<div style="display:flex;align-items:center;gap:8px;flex-wrap:wrap">'+
      '<span style="font-size:11px;color:var(--tx2)">Periodo de pago:</span>'+
      '<div class="ptabs">'+
        '<button class="pt '+(p==='semanal'?'on':'')+'" onclick="S.period=\'semanal\';S.bonos={};renderAll()">Semanal</button>'+
        '<button class="pt '+(p==='quincenal'?'on':'')+'" onclick="S.period=\'quincenal\';S.bonos={};renderAll()">Quincenal</button>'+
        '<button class="pt '+(p==='mensual'?'on':'')+'" onclick="S.period=\'mensual\';S.bonos={};renderAll()">Mensual</button>'+
      '</div>'+
    '</div>'+
  '</div>'+
  '<div class="pbar">'+
    '<label>Nombre del reporte:</label>'+
    '<input type="text" placeholder="Ej. 1a quincena abril 2026" value="'+esc(S.rpNombre)+'" oninput="S.rpNombre=this.value" style="width:210px;padding:5px 8px">'+
    '<label style="margin-left:4px">Del:</label>'+
    '<input type="date" value="'+S.rpIni+'" onchange="S.rpIni=this.value" style="width:138px;padding:5px 8px">'+
    '<label>al:</label>'+
    '<input type="date" value="'+S.rpFin+'" onchange="S.rpFin=this.value" style="width:138px;padding:5px 8px">'+
    '<button class="btn sm bd" onclick="S.bonos={};S.prestamos={};renderAll()" style="margin-left:auto">✕ Limpiar bonos y préstamos</button>'+
  '</div>'+
  '<div class="stats">'+
    '<div class="stat"><div class="slbl">Neto final empleados</div><div class="sval cbl" id="_st_neto">'+fmt(tNetoFinal)+'</div><div class="ssub">base + bonos ('+pn+')</div></div>'+
    '<div class="stat"><div class="slbl">ISR — enterar SAT</div><div class="sval crd" id="_st_isr">'+fmt(tISR)+'</div><div class="ssub">retención nómina</div></div>'+
    '<div class="stat"><div class="slbl">IMSS obrero total</div><div class="sval cam" id="_st_ob">'+fmt(tOb)+'</div><div class="ssub">descontar nómina</div></div>'+
    '<div class="stat"><div class="slbl">Costo total empresa</div><div class="sval cpr" id="_st_costo">'+fmt(tCosto)+'</div><div class="ssub">incl. cuotas patronales</div></div>'+
  '</div>'+
  '<div class="infotl">Los bonos son libres de impuestos: no generan ISR, cuotas IMSS ni INFONAVIT. Se suman directamente al neto del trabajador en este periodo.</div>'+
  '<div class="info" style="margin-bottom:14px">El descuento de préstamo se captura de forma manual por empleado y se resta del neto final en este periodo. No afecta el cálculo fiscal.</div>'+
  '<div class="card"><div class="ch">'+
    '<div>'+
      '<div class="ct">Desglose por empleado — '+pn+'</div>'+
      (S.rpNombre||S.rpIni?'<div style="font-size:10px;color:var(--tx3);margin-top:2px">'+(S.rpNombre?esc(S.rpNombre)+' · ':'')+S.rpIni+' al '+S.rpFin+'</div>':'')+'</div>'+
    '<div class="br">'+
      '<button class="btn bg" onclick="guardar()">💾 Guardar</button>'+
      '<button class="btn" onclick="excelCalc()">📊 Excel</button>'+
      '<button class="btn" onclick="pdfCalc()">📄 PDF</button>'+
    '</div></div>'+cuerpo+'</div>';
}

// ═══════════════════════════════════════
// HISTORIAL
// ═══════════════════════════════════════
function pageHist(){
  if(!S.hist.length) return '<div style="font-size:17px;font-weight:500;margin-bottom:12px">Historial de nóminas</div><div class="card"><div class="empty">Sin historial — guarda un cálculo desde "Cálculo de nómina"</div></div>';
  var html='<div style="font-size:17px;font-weight:500;margin-bottom:12px">Historial de nóminas</div>'+
    '<div class="br" style="margin-bottom:12px"><button class="btn bd sm" onclick="limpiarHist()">🗑 Limpiar todo</button></div>';
  for(var i=S.hist.length-1;i>=0;i--){
    var reg=S.hist[i], rows2='';
    reg.emp.forEach(function(e){
      rows2+='<tr>'+
        '<td>'+esc(e.nombre)+'</td>'+
        '<td class="num cam">'+fmt(e.nom)+'</td>'+
        '<td class="num" style="color:var(--tx2)">'+fmt(e.lib)+'</td>'+
        '<td class="num crd">'+fmt(e.isrNeto)+'</td>'+
        '<td class="num">'+fmt(e.ob)+'</td>'+
        '<td class="num cbl">'+fmt(e.netoBase)+'</td>'+
        '<td class="num ctl">'+fmt(e.bon)+'</td>'+
        '<td class="num crd">'+fmt(e.prest||0)+'</td>'+
        '<td class="num cbl" style="font-weight:500">'+fmt(e.netoFinal)+'</td>'+
        '<td class="num cpr" style="font-size:11px">'+fmt(e.costo)+'</td>'+
      '</tr>';
    });
    var titulo=reg.rpNombre||('Nómina '+reg.periodo);
    html+='<div class="card">'+
      '<div class="ch"><div>'+
        '<div style="font-size:10px;color:var(--tx3);font-family:\'IBM Plex Mono\',monospace;margin-bottom:2px">'+reg.fecha+' · '+reg.periodo.toUpperCase()+'</div>'+
        '<div class="ct">'+esc(titulo)+'</div>'+
        '<div style="font-size:10px;color:var(--tx3);margin-top:2px">'+reg.ini+' — '+reg.fin+' · '+reg.numEmp+' empleados</div>'+
      '</div><div style="text-align:right">'+
        '<div style="font-size:10px;color:var(--tx3)">Neto final total</div>'+
        '<div style="font-size:16px;font-weight:500;color:var(--blue);font-family:\'IBM Plex Mono\',monospace">'+fmt(reg.totNetoFinal)+'</div>'+
      '</div></div>'+
      '<div style="overflow-x:auto;max-height:175px;overflow-y:auto">'+
        '<table style="font-size:11px"><thead><tr><th>Empleado</th><th>Hacienda</th><th>Libre</th><th>ISR</th><th>IMSS ob.</th><th>Neto base</th><th>Bono</th><th>Desc. Préstamo</th><th>Neto final</th><th>Costo emp.</th></tr></thead>'+
        '<tbody>'+rows2+'</tbody></table></div>'+
      '<div style="padding:8px 12px;border-top:1px solid var(--bdr);display:flex;gap:6px">'+
        '<button class="btn sm" onclick="excelHist('+i+')">📊 Excel</button>'+
        '<button class="btn sm" onclick="pdfHist('+i+')">📄 PDF</button>'+
        '<button class="btn sm bd" onclick="borrarHist('+i+')">✕ Eliminar</button>'+
      '</div></div>';
  }
  return html;
}

function guardar(){
  if(!S.emp.length){ showToast('Sin empleados'); return; }
  var p=S.period, totNetoBase=0, totNetoFinal=0, totCosto=0, totBono=0, totPrest=0;
  var emps=S.emp.map(function(e){
    var bon=getBono(e.id);
    var prest=getPrestamo(e.id);
    var r=calcNomina(e.nominal,e.total,p,bon);
    var netoConPrest=r2(r.netoFinal - prest);
    totNetoBase+=r.netoBase; totNetoFinal+=netoConPrest;
    totCosto+=r.costo; totBono+=bon; totPrest+=prest;
    return{ nombre:e.nombre, puesto:e.puesto||'', nom:r.nom, lib:r.lib, isrNeto:r.isrNeto, ob:r.ob.total, netoBase:r.netoBase, bon:bon, prest:prest, netoFinal:netoConPrest, costo:r.costo };
  });
  S.hist.push({ id:gid(), fecha:hoy(), periodo:p, rpNombre:S.rpNombre, ini:S.rpIni, fin:S.rpFin, numEmp:S.emp.length, totNetoBase:totNetoBase, totNetoFinal:totNetoFinal, totBono:totBono, totPrest:totPrest, totCosto:totCosto, emp:emps });
  persist(); showToast('✓ Guardado en historial'); renderAll();
}
function limpiarHist(){ if(!confirm('¿Limpiar todo el historial?'))return; S.hist=[]; persist(); renderAll(); }
function borrarHist(idx){ S.hist.splice(idx,1); persist(); renderAll(); }

// ═══════════════════════════════════════
// IMPORTAR
// ═══════════════════════════════════════
var _impData=[];
function pageImp(){
  return '<div style="font-size:17px;font-weight:500;margin-bottom:12px">Importar base de datos</div>'+
    '<div class="info">Columnas reconocidas: <strong>Nombre</strong> · <strong>Sueldo Nominal</strong> (Hacienda) · <strong>Sueldo Total</strong> · <strong>Puesto</strong> · <strong>Frecuencia</strong> · <strong>RFC</strong><br>'+
    'El sistema calcula automáticamente: <em>Sueldo Libre = Sueldo Total − Sueldo Nominal</em></div>'+
    '<div class="card"><div class="ch"><div class="ct">Subir archivo</div></div><div style="padding:16px">'+
      '<div class="dz" id="dz" onclick="document.getElementById(\'fi\').click()" ondragover="event.preventDefault();this.style.borderColor=\'var(--blue)\'" ondragleave="this.style.borderColor=\'\'" ondrop="hdrop(event)">'+
        '<input type="file" id="fi" accept=".xlsx,.xls,.csv" onchange="hfile(this.files[0])">'+
        '<div style="font-size:22px;margin-bottom:7px">📂</div>'+
        '<div style="font-weight:500;margin-bottom:3px">Arrastra tu archivo aquí o haz clic</div>'+
        '<div style="font-size:11px;color:var(--tx3)">Formatos: .xlsx, .xls, .csv</div>'+
      '</div><div id="ipv"></div><div id="iac"></div></div></div>'+
    '<div class="card"><div class="ch"><div class="ct">Descargar plantilla</div></div><div style="padding:16px">'+
      '<div style="font-size:12px;color:var(--tx2);margin-bottom:10px">Descarga, llena y sube:</div>'+
      '<button class="btn bp" onclick="dlTpl()">⬇ Descargar plantilla Excel</button>'+
    '</div></div>';
}
function hdrop(e){ e.preventDefault(); var f=e.dataTransfer.files[0]; if(f) hfile(f); }
function hfile(file){
  if(!file) return;
  var reader=new FileReader();
  reader.onload=function(ev){
    try{
      var data;
      if(file.name.slice(-4)==='.csv') data=parseCSV(ev.target.result);
      else{ var wb=XLSX.read(ev.target.result,{type:'array'}); data=XLSX.utils.sheet_to_json(wb.Sheets[wb.SheetNames[0]],{defval:''}); }
      procImp(data);
    }catch(err){ showToast('Error: '+err.message); }
  };
  if(file.name.slice(-4)==='.csv') reader.readAsText(file,'UTF-8');
  else reader.readAsArrayBuffer(file);
}
function parseCSV(txt){
  var lines=txt.split('\n').filter(function(l){ return l.trim(); });
  if(!lines.length) return [];
  var hds=lines[0].split(',').map(function(h){ return h.trim().replace(/"/g,''); });
  return lines.slice(1).map(function(line){
    var vals=line.split(',').map(function(v){ return v.trim().replace(/"/g,''); });
    var obj={}; hds.forEach(function(h,i){ obj[h]=vals[i]||''; }); return obj;
  });
}
function nk(k){ return k.toLowerCase().normalize('NFD').replace(/[\u0300-\u036f]/g,'').trim(); }
function findVal(row,words){
  var keys=Object.keys(row), found='';
  for(var i=0;i<keys.length;i++){
    var n=nk(keys[i]);
    for(var j=0;j<words.length;j++){ if(n.indexOf(words[j])>=0){ found=row[keys[i]]; break; } }
    if(found) break;
  }
  return found;
}
function procImp(rows){
  _impData=[];
  rows.forEach(function(r){
    var nombre  = String(findVal(r,['nombre','name','empleado'])||'').trim();
    var nominal = parseFloat(String(findVal(r,['nominal','hacienda','nomina hacienda','sueldo nominal','sueldo hacienda'])||'0').replace(/[$,]/g,''))||0;
    var total   = parseFloat(String(findVal(r,['total','sueldo total','salario total','total recibe'])||'0').replace(/[$,]/g,''))||0;
    var puesto  = String(findVal(r,['puesto','cargo','posicion','job'])||'').trim();
    var freqR   = String(findVal(r,['frecuencia','periodo','frequency'])||'quincenal').toLowerCase();
    var freq    = freqR.indexOf('sem')>=0?'semanal':'quincenal';
    var rfc     = String(findVal(r,['rfc','curp','id'])||'').trim();
    if(nombre && nominal>0) _impData.push({nombre:nombre, nominal:nominal, total:total||nominal, puesto:puesto, freq:freq, rfc:rfc});
  });
  var pv=document.getElementById('ipv'), ac=document.getElementById('iac');
  if(!pv) return;
  if(!_impData.length){ pv.innerHTML='<div class="warn" style="margin-top:10px">No se encontraron registros válidos. Verifica los encabezados.</div>'; ac.innerHTML=''; return; }
  var rws=_impData.map(function(e){
    return '<div style="display:flex;gap:8px;padding:3px 0;border-bottom:1px solid var(--bdr);font-size:11px">'+
      '<span style="flex:2;overflow:hidden;text-overflow:ellipsis;white-space:nowrap">'+esc(e.nombre)+'</span>'+
      '<span style="flex:1">'+fmt(e.nominal)+'</span>'+
      '<span style="flex:1">'+fmt(e.total)+'</span>'+
      '<span style="flex:1;color:var(--tx3)">'+esc(e.puesto||'—')+'</span>'+
      '<span style="flex:1;color:var(--tx3)">'+e.freq+'</span>'+
    '</div>';
  }).join('');
  pv.innerHTML='<div style="background:var(--bg);border:1px solid var(--bdr);border-radius:8px;padding:10px;margin-top:10px;max-height:180px;overflow-y:auto">'+
    '<div style="display:flex;gap:8px;padding:2px 0 5px;border-bottom:1px solid var(--bdr);font-size:10px;font-weight:500;color:var(--tx3);text-transform:uppercase;letter-spacing:.4px">'+
      '<span style="flex:2">Nombre</span><span style="flex:1">Nominal</span><span style="flex:1">Total</span><span style="flex:1">Puesto</span><span style="flex:1">Frec.</span>'+
    '</div>'+rws+'</div>';
  ac.innerHTML='<div style="margin-top:10px;display:flex;gap:8px;flex-wrap:wrap">'+
    '<button class="btn bg" onclick="doImp(false)">➕ Agregar '+_impData.length+' empleados</button>'+
    '<button class="btn bd" onclick="doImp(true)">🔄 Reemplazar plantilla</button>'+
  '</div>';
}
function doImp(replace){
  if(!_impData.length) return;
  var toAdd=_impData.map(function(e){ return Object.assign({id:gid(),alta:hoy()},e); });
  S.emp=replace?toAdd:S.emp.concat(toAdd);
  persist(); showToast('✓ '+toAdd.length+' empleados importados'); goTab('emp');
}
function dlTpl(){
  var wb=XLSX.utils.book_new();
  var ws=XLSX.utils.aoa_to_sheet([
    ['Nombre','Sueldo Nominal','Sueldo Total','Puesto','Frecuencia','RFC'],
    ['Juan Pérez García',18000,23000,'Contador','quincenal','PEGJ900101AB1'],
    ['María López Ruiz',12000,14000,'Asistente','quincenal','LORM850201CD2'],
    ['Carlos Soto Díaz',9000,10500,'Mensajero','semanal','SODC920315EF3']
  ]);
  ws['!cols']=[{wch:28},{wch:15},{wch:14},{wch:20},{wch:12},{wch:20}];
  XLSX.utils.book_append_sheet(wb,ws,'Plantilla');
  XLSX.writeFile(wb,'plantilla_nomina.xlsx');
}

// ═══════════════════════════════════════
// REPORTES
// ═══════════════════════════════════════
function pageRep(){
  var tN=0,tLib=0,tISR=0,tOb=0,tPat=0,tInfo=0,tNeto=0,tCosto=0;
  S.emp.forEach(function(e){
    var r=calcNomina(e.nominal,e.total,'mensual',0);
    tN+=r.nom; tLib+=r.lib; tISR+=r.isrNeto; tOb+=r.ob.total;
    tPat+=r.pat.total; tInfo+=r.info; tNeto+=r.netoBase; tCosto+=r.costo;
  });
  var sorted=S.emp.slice().sort(function(a,b){ return Number(b.nominal)-Number(a.nominal); }).slice(0,5);
  var topRows=sorted.map(function(e,i){
    var r=calcNomina(e.nominal,e.total,'mensual',0);
    var pct=tNeto?((r.netoBase/tNeto)*100).toFixed(1):'0';
    return '<tr>'+
      '<td style="font-size:10px;color:var(--tx3);width:16px">'+(i+1)+'</td>'+
      '<td>'+esc(e.nombre)+'</td>'+
      '<td class="num cam">'+fmt(r.nom)+'</td>'+
      '<td class="num" style="color:var(--tx2)">'+fmt(r.lib)+'</td>'+
      '<td class="num cbl" style="font-weight:500">'+fmt(r.netoBase)+'</td>'+
      '<td><div style="display:flex;align-items:center;gap:5px"><div style="flex:1;background:var(--bg);border-radius:3px;height:5px;overflow:hidden"><div style="width:'+pct+'%;background:var(--blue);height:100%"></div></div><span style="font-size:10px;color:var(--tx3)">'+pct+'%</span></div></td>'+
    '</tr>';
  }).join('');
  var pN=tN+(tLib)>0?Math.round(tN/(tN+tLib)*100):50, pL=100-pN;
  function fi(l,v,c){ return '<div style="display:flex;justify-content:space-between;font-size:12px"><span style="color:var(--tx2)">'+l+'</span><span style="font-family:\'IBM Plex Mono\',monospace;color:'+c+'">'+v+'</span></div>'; }
  return '<div style="font-size:17px;font-weight:500;margin-bottom:12px">Reportes y análisis</div>'+
    '<div class="g2" style="margin-bottom:14px">'+
      '<div class="card" style="margin:0"><div class="ch"><div class="ct">Composición nómina mensual</div></div><div style="padding:16px;display:flex;flex-direction:column;gap:8px">'+
        fi('Nómina Hacienda (gravable)',fmt(tN),'var(--amb)')+
        fi('Sueldo libre de impuestos',fmt(tLib),'var(--grn)')+
        '<div style="height:8px;border-radius:4px;overflow:hidden;display:flex;margin:4px 0">'+
          '<div style="flex:'+pN+';background:var(--amb);border-radius:4px 0 0 4px"></div>'+
          '<div style="flex:'+pL+';background:var(--grn);border-radius:0 4px 4px 0"></div>'+
        '</div>'+
        '<div style="border-top:1px solid var(--bdr);padding-top:8px">'+
          fi('ISR mensual — enterar SAT',fmt(tISR),'var(--red)')+
          fi('IMSS obrero total',fmt(tOb),'var(--tx2)')+
          fi('IMSS patronal total',fmt(tPat),'var(--pur)')+
          fi('INFONAVIT patronal',fmt(tInfo),'var(--pur)')+
        '</div>'+
        '<div style="display:flex;justify-content:space-between;font-weight:500;font-size:13px;margin-top:4px"><span>Costo total empresa</span><span style="font-family:\'IBM Plex Mono\',monospace;color:var(--pur)">'+fmt(tCosto)+'</span></div>'+
      '</div></div>'+
      '<div class="card" style="margin:0"><div class="ch"><div class="ct">Resumen general</div></div><div style="padding:16px">'+
        '<div class="stats" style="grid-template-columns:1fr 1fr;margin-bottom:12px">'+
          stHTML('Empleados',S.emp.length,'cbl','en plantilla')+
          stHTML('Historial',S.hist.length,'cgr','nóminas guardadas')+
          stHTML('Semanales',S.emp.filter(function(e){ return e.freq==='semanal'; }).length,'cam','empleados')+
          stHTML('Quincenales',S.emp.filter(function(e){ return e.freq!=='semanal'; }).length,'cbl','empleados')+
        '</div>'+
        '<div class="br">'+
          '<button class="btn" onclick="excelRep()">📊 Excel completo</button>'+
          '<button class="btn" onclick="pdfRep()">📄 PDF reporte</button>'+
        '</div>'+
      '</div></div>'+
    '</div>'+
    '<div class="card"><div class="ch"><div class="ct">Top 5 nóminas nominales más altas</div></div>'+
      (sorted.length===0?'<div class="empty">Sin datos</div>':'<div style="overflow-x:auto"><table><thead><tr><th>#</th><th>Empleado</th><th>Nómina Hacienda</th><th>Sueldo libre</th><th>Neto base</th><th>% del total</th></tr></thead><tbody>'+topRows+'</tbody></table></div>')+
    '</div>';
}

// ═══════════════════════════════════════
// MODAL ADD/EDIT
// ═══════════════════════════════════════
function openAdd(){ S.modalType='add'; S.editId=null; renderAll(); }
function openEdit(id){ S.modalType='edit'; S.editId=id; renderAll(); }
function closeModal(){ S.modalType=null; S.editId=null; renderAll(); }

function prow(lbl,val,color){
  return '<div style="display:flex;justify-content:space-between;padding:5px 10px;border-bottom:1px solid var(--bdr);font-size:12px">'+
    '<span style="color:var(--tx2)">'+lbl+'</span>'+
    '<span style="font-family:\'IBM Plex Mono\',monospace;font-weight:500;color:'+color+'">'+val+'</span>'+
  '</div>';
}

function prevC(){
  var el=document.getElementById('pv'); if(!el) return;
  var nom=parseFloat(document.getElementById('fnm').value)||0;
  var tot=parseFloat(document.getElementById('ftt').value)||0;
  var frq=document.getElementById('ff').value;
  if(nom<=0){ el.innerHTML=''; return; }
  if(tot<nom){ el.innerHTML='<div class="warn">El sueldo total no puede ser menor al sueldo nominal.</div>'; return; }
  var lib=r2(tot-nom);
  var r=calcNomina(nom,tot,frq,0);
  el.innerHTML='<div style="border:1px solid var(--bdr);border-radius:8px;overflow:hidden">'+
    prow('Sueldo nominal Hacienda',fmt(r.nom),'var(--amb)')+
    prow('Sueldo libre (calculado automáticamente)',fmt(lib),'var(--grn)')+
    prow('Total que recibe el empleado',fmt(r.tot),'var(--tx)')+
    '<div style="padding:5px 10px;background:var(--sur2);font-size:10px;text-transform:uppercase;letter-spacing:.4px;color:var(--tx2);font-weight:500">Deducciones del trabajador</div>'+
    prow('Base gravable ISR (nominal − IMSS obrero)',fmt(r.baseISR),'var(--tx2)')+
    prow('ISR bruto',fmt(r.isrBruto),'var(--tx2)')+
    prow('Subsidio al empleo',r.subsidio>0?'− '+fmt(r.subsidio):'$0.00','var(--grn)')+
    prow('ISR neto a retener al SAT',fmt(r.isrNeto),'var(--red)')+
    prow('IMSS obrero total',fmt(r.ob.total),'var(--amb)')+
    prow('Total deducciones empleado',fmt(r.ded),'var(--red)')+
    '<div style="display:flex;justify-content:space-between;padding:8px 10px;background:#E1F5EE;font-size:13px;font-weight:500;color:var(--grn)">'+
      '<span>Neto base del empleado ('+frq+', sin bonos)</span>'+
      '<span style="font-family:\'IBM Plex Mono\',monospace">'+fmt(r.netoBase)+'</span>'+
    '</div>'+
    prow('Costo total empresa (incl. cuotas patronales)',fmt(r.costo),'var(--pur)')+
  '</div>';
}

function buildModal(){
  var e=S.editId?S.emp.find(function(x){ return x.id===S.editId; }):null;
  var nom=e?esc(e.nombre):'', pue=e?esc(e.puesto||''):'', frq=e?e.freq:'quincenal';
  var nml=e?(e.nominal||''):'', tot=e?(e.total||''):'', rfc=e?esc(e.rfc||''):'';
  var cont=document.createElement('div'); cont.id='_mc';
  cont.innerHTML=
    '<div class="ov" onclick="if(event.target===this)closeModal()"><div class="modal">'+
    '<div class="mh"><div class="mt">'+(e?'Editar empleado':'Agregar empleado')+'</div><button class="cx" onclick="closeModal()">✕</button></div>'+
    '<div class="mb">'+
      '<div class="info">Captura el <strong>sueldo nominal Hacienda</strong> y el <strong>sueldo total</strong>. El sueldo libre se calcula automáticamente como la diferencia.</div>'+
      '<div style="display:grid;grid-template-columns:1fr 1fr;gap:12px">'+
        '<div class="fg" style="grid-column:1/-1"><label>Nombre completo *</label><input id="fn" type="text" value="'+nom+'"></div>'+
        '<div class="fg"><label>Puesto / Cargo</label><input id="fp" type="text" value="'+pue+'"></div>'+
        '<div class="fg"><label>Frecuencia de pago</label>'+
          '<select id="ff" onchange="prevC()">'+
            '<option value="quincenal"'+(frq!=='semanal'?' selected':'')+'>Quincenal</option>'+
            '<option value="semanal"'+(frq==='semanal'?' selected':'')+'>Semanal</option>'+
          '</select></div>'+
        '<div class="fg">'+
          '<label>Sueldo nominal Hacienda (por periodo) *</label>'+
          '<div class="fw"><span class="fws">$</span><input id="fnm" type="number" min="0" step="0.01" value="'+nml+'" oninput="prevC()"></div>'+
          '<div style="font-size:10px;color:var(--tx3);margin-top:2px">Base gravable — reportado al SAT, base para ISR e IMSS</div>'+
        '</div>'+
        '<div class="fg">'+
          '<label>Sueldo total que recibe el empleado (por periodo) *</label>'+
          '<div class="fw"><span class="fws">$</span><input id="ftt" type="number" min="0" step="0.01" value="'+tot+'" oninput="prevC()"></div>'+
          '<div style="font-size:10px;color:var(--grn);margin-top:2px">Sueldo libre = Total − Nominal (calculado auto)</div>'+
        '</div>'+
        '<div class="fg" style="grid-column:1/-1"><label>RFC / CURP / No. empleado</label><input id="fr" type="text" value="'+rfc+'"></div>'+
      '</div>'+
      '<div id="pv" style="margin-top:11px"></div>'+
    '</div>'+
    '<div class="mf">'+
      '<button class="btn" onclick="closeModal()">Cancelar</button>'+
      '<button class="btn bp" onclick="saveEmp()">💾 '+(e?'Guardar cambios':'Agregar')+'</button>'+
    '</div></div></div>';
  document.body.appendChild(cont);
  prevC();
}

function saveEmp(){
  var nom=(document.getElementById('fn').value||'').trim();
  var pue=(document.getElementById('fp').value||'').trim();
  var frq=document.getElementById('ff').value;
  var nml=parseFloat(document.getElementById('fnm').value)||0;
  var tot=parseFloat(document.getElementById('ftt').value)||0;
  var rfc=(document.getElementById('fr').value||'').trim();
  if(!nom){ alert('El nombre es obligatorio'); return; }
  if(nml<=0){ alert('El sueldo nominal es obligatorio'); return; }
  if(tot<nml){ alert('El sueldo total no puede ser menor al sueldo nominal'); return; }
  if(tot===0) tot=nml;
  if(S.editId){
    var idx=S.emp.findIndex(function(x){ return x.id===S.editId; });
    if(idx>=0) S.emp[idx]={ id:S.editId, nombre:nom, puesto:pue, freq:frq, nominal:nml, total:tot, rfc:rfc, alta:S.emp[idx].alta };
    showToast('✓ Empleado actualizado');
  } else {
    S.emp.push({ id:gid(), nombre:nom, puesto:pue, freq:frq, nominal:nml, total:tot, rfc:rfc, alta:hoy() });
    showToast('✓ Empleado agregado');
  }
  S.modalType=null; S.editId=null; persist(); renderAll();
}
function delEmp(id){ if(!confirm('¿Eliminar este empleado?'))return; S.emp=S.emp.filter(function(e){ return e.id!==id; }); persist(); showToast('Eliminado'); renderAll(); }

// ═══════════════════════════════════════
// DETALLE FISCAL
// ═══════════════════════════════════════
function openDet(id){ S.detId=id; S.detPer='mensual'; renderAll(); }
function openDetCalc(id,per){ S.detId=id; S.detPer=per; renderAll(); }
function closeDet(){ S.detId=null; renderAll(); }
function refreshDet(){ var d=document.getElementById('_dc'); if(d) d.remove(); buildDet(); }

function buildDet(){
  var e=S.emp.find(function(x){ return x.id===S.detId; });
  if(!e) return;
  var p=S.detPer||'mensual';
  var bon=getBono(e.id);
  var r=calcNomina(e.nominal,e.total,p,bon);

  function dr(lbl,val,cls,ind){
    return '<div class="dr'+(cls?' '+cls:'')+'">'+
      '<span class="dlbl"'+(ind?' style="padding-left:12px"':'')+'>'+lbl+'</span>'+
      '<span class="dval">'+val+'</span>'+
    '</div>';
  }
  function ds(lbl){ return '<div class="dr drs"><span>'+lbl+'</span></div>'; }

  var cont=document.createElement('div'); cont.id='_dc';
  cont.innerHTML=
    '<div class="ov" onclick="if(event.target===this)closeDet()"><div class="modal" style="max-width:510px">'+
    '<div class="mh">'+
      '<div style="display:flex;align-items:center;gap:9px">'+
        '<div class="av" style="width:34px;height:34px;font-size:12px;background:'+avc(e.nombre)+'">'+ini(e.nombre)+'</div>'+
        '<div><div class="mt">'+esc(e.nombre)+'</div>'+
          '<div style="font-size:11px;color:var(--tx3)">'+esc(e.puesto||'Sin cargo')+' · <span class="badge '+(e.freq==='semanal'?'bsm':'bqn')+'">'+e.freq+'</span></div>'+
        '</div>'+
      '</div>'+
      '<div style="display:flex;align-items:center;gap:7px">'+
        '<div class="ptabs">'+
          '<button class="pt'+(p==='semanal'?' on':'')+'" onclick="S.detPer=\'semanal\';refreshDet()">Sem</button>'+
          '<button class="pt'+(p==='quincenal'?' on':'')+'" onclick="S.detPer=\'quincenal\';refreshDet()">Qnc</button>'+
          '<button class="pt'+(p==='mensual'?' on':'')+'" onclick="S.detPer=\'mensual\';refreshDet()">Mes</button>'+
        '</div>'+
        '<button class="cx" onclick="closeDet()">✕</button>'+
      '</div>'+
    '</div>'+
    '<div class="mb" style="padding:13px 16px">'+
      '<div class="dbox">'+
        ds('Percepciones')+
        dr('Sueldo nominal Hacienda (gravable)',fmt(r.nom),'cam')+
        dr('Sueldo libre de impuestos (= total − nominal)',fmt(r.lib),'cgr')+
        dr('Total que recibe el empleado',fmt(r.tot))+
        ds('Deducciones del trabajador')+
        dr('IMSS obrero — total',fmt(r.ob.total),'ded')+
        dr('E&M excedente (0.40%)',fmt(r.ob.emExc),'',true)+
        dr('E&M prest. en dinero (0.25%)',fmt(r.ob.emDin),'',true)+
        dr('Gastos méd. pensionados (0.375%)',fmt(r.ob.pens),'',true)+
        dr('Invalidez y vida (0.625%)',fmt(r.ob.inv),'',true)+
        dr('CEAV obrero (1.125%)',fmt(r.ob.ceav),'',true)+
        dr('Base gravable ISR (nominal − IMSS obrero)',fmt(r.baseISR))+
        dr('ISR bruto calculado',fmt(r.isrBruto))+
        dr('Subsidio al empleo',r.subsidio>0?'− '+fmt(r.subsidio):'$0.00','cgr')+
        dr('ISR neto — enterar al SAT',fmt(r.isrNeto),'ded')+
        '<div class="dr drt"><span class="dlbl">Total deducciones trabajador</span><span class="dval">'+fmt(r.ded)+'</span></div>'+
        '<div class="dr drn"><span>Neto base ('+p+', sin bono)</span><span class="dval">'+fmt(r.netoBase)+'</span></div>'+
        (bon>0?ds('Bono del periodo')+dr('Bono asignado (libre de impuestos)',fmt(bon),'ctl')+'<div class="dr drb"><span>Neto final (base + bono)</span><span class="dval">'+fmt(r.netoFinal)+'</span></div>':'')+
        ds('Cuotas patronales (costo adicional empresa)')+
        dr('IMSS patronal — total',fmt(r.pat.total),'cpr')+
        dr('E&M cuota fija (20.4% UMA)',fmt(r.pat.emFija),'',true)+
        dr('E&M excedente (1.10%)',fmt(r.pat.emExc),'',true)+
        dr('E&M prest. en dinero (0.70%)',fmt(r.pat.emDin),'',true)+
        dr('Gastos méd. pensionados (0.375%)',fmt(r.pat.pens),'',true)+
        dr('Invalidez y vida (1.75%)',fmt(r.pat.inv),'',true)+
        dr('Riesgo de trabajo (0.54%)',fmt(r.pat.riesgo),'',true)+
        dr('Guarderías (1.00%)',fmt(r.pat.guard),'',true)+
        dr('Retiro (2.00%)',fmt(r.pat.retiro),'',true)+
        dr('CEAV patronal 2026',fmt(r.pat.ceav),'',true)+
        dr('INFONAVIT patronal (5.00%)',fmt(r.info),'cpr')+
        '<div class="dr" style="background:var(--pu2);color:var(--pur);font-weight:500;font-size:13px">'+
          '<span>Costo total empresa ('+p+')</span><span class="dval">'+fmt(r.costo)+'</span>'+
        '</div>'+
      '</div>'+
      '<div class="warn" style="margin-top:10px;font-size:11px">'+
        'SBC mensual: '+fmt(r.sbc)+' · SDI: $'+r.sdDiario+'/día · UMA 2026: $'+UMA_D+'/día · Fuente: Anexo 8 RMF 2026 (DOF 28/12/2025)'+
      '</div>'+
    '</div>'+
    '<div class="mf">'+
      '<button class="btn" onclick="closeDet()">Cerrar</button>'+
      '<button class="btn bp" onclick="closeDet();openEdit(\''+e.id+'\')">✏ Editar</button>'+
    '</div></div></div>';
  document.body.appendChild(cont);
}

// ═══════════════════════════════════════
// EXPORTACIONES
// ═══════════════════════════════════════
function buildXls(emps,per,bonos,prestamos){
  var hd=['Empleado','Puesto','Frec.','Nómina Hacienda','Sueldo Libre','Total Recibe','Base ISR','ISR Bruto','Subsidio','ISR Neto','IMSS Obrero','Neto Base','Bono Periodo','Desc. Préstamo','Neto Final','IMSS Patronal','INFONAVIT','Costo Empresa'];
  return [hd].concat(emps.map(function(e){
    var bon=bonos?(bonos[e.id]||e.bon||0):(e.bon||0);
    var prest=prestamos?(prestamos[e.id]||e.prest||0):(e.prest||0);
    var r=calcNomina(e.nominal||e.nom, e.total||e.tot, per, bon);
    var netoConPrest=r2(r.netoFinal - prest);
    return[e.nombre,e.puesto||'',e.freq||'quincenal',r.nom,r.lib,r.tot,r.baseISR,r.isrBruto,r.subsidio,r.isrNeto,r.ob.total,r.netoBase,bon,prest,netoConPrest,r.pat.total,r.info,r.costo];
  }));
}

function excelCalc(){
  var wb=XLSX.utils.book_new();
  var ws=XLSX.utils.aoa_to_sheet(buildXls(S.emp,S.period,S.bonos,S.prestamos));
  ws['!cols']=[{wch:26},{wch:16},{wch:10}].concat(Array(14).fill({wch:14}));
  XLSX.utils.book_append_sheet(wb,ws,'Nomina');
  XLSX.writeFile(wb,'nomina_'+S.period+'_'+Date.now()+'.xlsx');
  showToast('✓ Excel descargado');
}
function excelHist(idx){
  var reg=S.hist[idx], wb=XLSX.utils.book_new();
  var hd=['Empleado','Puesto','Nómina Hacienda','Sueldo Libre','ISR Neto','IMSS Obrero','Neto Base','Bono','Neto Final','Costo Empresa'];
  var rows=[hd].concat(reg.emp.map(function(e){ return[e.nombre,e.puesto||'',e.nom,e.lib,e.isrNeto,e.ob,e.netoBase,e.bon,e.netoFinal,e.costo]; }));
  XLSX.utils.book_append_sheet(wb,XLSX.utils.aoa_to_sheet(rows),'Nomina');
  XLSX.writeFile(wb,'nomina_hist_'+Date.now()+'.xlsx');
  showToast('✓ Excel descargado');
}
function excelRep(){
  var wb=XLSX.utils.book_new();
  var ws=XLSX.utils.aoa_to_sheet(buildXls(S.emp,'mensual',{}));
  ws['!cols']=[{wch:26},{wch:16},{wch:10}].concat(Array(14).fill({wch:14}));
  XLSX.utils.book_append_sheet(wb,ws,'Reporte');
  XLSX.writeFile(wb,'reporte_'+Date.now()+'.xlsx');
  showToast('✓ Excel descargado');
}

function makePDF(titulo,emps,per,bonos,prestamos,rpN,ini,fin){
  var pStr=rpN?(rpN+(ini?' ('+ini+' al '+fin+')':'')):ini?(ini+' al '+fin):per.toUpperCase();
  var tNeto=0,tISR=0,tCosto=0,tBono=0,tPrest=0;
  var rows=emps.map(function(e){
    var bon=bonos?(bonos[e.id]||e.bon||0):(e.bon||0);
    var prest=prestamos?(prestamos[e.id]||e.prest||0):(e.prest||0);
    var r=calcNomina(e.nominal||e.nom, e.total||e.tot, per, bon);
    var netoConPrest=r2(r.netoFinal - prest);
    tNeto+=netoConPrest; tISR+=r.isrNeto; tCosto+=r.costo; tBono+=bon; tPrest+=prest;
    return '<tr>'+
      '<td>'+e.nombre+'</td><td>'+(e.puesto||'—')+'</td>'+
      '<td>'+fmt(r.nom)+'</td><td style="color:#0F6E56">'+fmt(r.lib)+'</td>'+
      '<td style="color:#991B1B">'+fmt(r.isrNeto)+'</td>'+
      '<td>'+fmt(r.ob.total)+'</td>'+
      '<td>'+fmt(r.netoBase)+'</td>'+
      '<td style="color:#0F766E">'+fmt(bon)+'</td>'+
      '<td style="color:#991B1B">'+fmt(prest)+'</td>'+
      '<td style="font-weight:600;color:#1D4ED8">'+fmt(netoConPrest)+'</td>'+
      '<td style="color:#5B21B6;font-size:10px">'+fmt(r.costo)+'</td>'+
    '</tr>';
  }).join('');
  return '<!DOCTYPE html><html><head><meta charset="UTF-8"><title>'+titulo+'</title>'+
    '<style>body{font-family:Arial,sans-serif;margin:26px;font-size:11px;color:#1C1917}'+
    'table{width:100%;border-collapse:collapse;margin-top:12px}'+
    'th{background:#F5F4F1;padding:5px 6px;text-align:left;font-size:9px;text-transform:uppercase;border-bottom:2px solid #DDD9D0}'+
    'td{padding:5px 6px;border-bottom:1px solid #DDD9D0}'+
    '.hd{display:flex;justify-content:space-between;margin-bottom:14px;padding-bottom:11px;border-bottom:2px solid #1C1917}'+
    '.brand{font-size:18px;font-weight:700}.meta{color:#6B6560;font-size:10px;margin-top:2px}'+
    '.tb{background:#EEF2FF;border:1px solid #c7d7f7;border-radius:6px;padding:12px;margin-top:13px;display:flex;gap:20px}'+
    '.tb div{text-align:center}.tl{font-size:9px;color:#6B6560;text-transform:uppercase;margin-bottom:3px}.tv{font-size:15px;font-weight:700}'+
    '.disc{margin-top:14px;font-size:9px;color:#9C9890;text-align:center}</style></head><body>'+
    '<div class="hd"><div><div class="brand">NóminaFlow Fiscal 2026</div><div class="meta">Tablas ISR Anexo 8 RMF 2026 (DOF 28/12/2025) · UMA 2026 $'+UMA_D+'/día</div></div>'+
    '<div style="text-align:right"><div style="font-size:15px;font-weight:600">'+titulo+'</div><div class="meta">'+pStr+'</div></div></div>'+
    '<table><thead><tr>'+
      '<th>Empleado</th><th>Puesto</th><th>Hacienda</th><th>Libre</th>'+
      '<th>ISR</th><th>IMSS Obrero</th><th>Neto Base</th><th>Bono</th><th>Desc. Préstamo</th><th>Neto Final</th><th>Costo Empresa</th>'+
    '</tr></thead><tbody>'+rows+'</tbody></table>'+
    '<div class="tb">'+
      '<div><div class="tl">Neto final empleados</div><div class="tv" style="color:#1D4ED8">'+fmt(tNeto)+'</div></div>'+
      '<div><div class="tl">Total bonos</div><div class="tv" style="color:#0F766E">'+fmt(tBono)+'</div></div>'+
      '<div><div class="tl">Total desc. préstamos</div><div class="tv" style="color:#991B1B">'+fmt(tPrest)+'</div></div>'+
      '<div><div class="tl">ISR a enterar SAT</div><div class="tv" style="color:#991B1B">'+fmt(tISR)+'</div></div>'+
      '<div><div class="tl">Costo total empresa</div><div class="tv" style="color:#5B21B6">'+fmt(tCosto)+'</div></div>'+
    '</div>'+
    '<div class="disc">Cálculo informativo · Art. 96 LISR, Anexo 8 RMF 2026, Arts. 25,106,107,147,168,211 LSS · Los bonos son libres de impuestos · No sustituye asesoría fiscal · '+hoy()+'</div>'+
  '</body></html>';
}

function openPDF(html){ var w=window.open('','_blank'); if(w){ w.document.write(html); w.document.close(); setTimeout(function(){ w.print(); },600); } showToast('✓ PDF listo'); }
function pdfCalc(){ openPDF(makePDF('Nómina '+S.period, S.emp, S.period, S.bonos, S.prestamos, S.rpNombre, S.rpIni, S.rpFin)); }
function pdfHist(idx){
  var reg=S.hist[idx];
  var emps=reg.emp.map(function(e){ return Object.assign({},e,{nominal:e.nom,total:r2((e.nom||0)+(e.lib||0)),freq:'quincenal'}); });
  openPDF(makePDF(reg.rpNombre||'Nómina '+reg.periodo, emps, reg.periodo, null, null, reg.rpNombre, reg.ini, reg.fin));
}
function pdfRep(){ openPDF(makePDF('Reporte de plantilla', S.emp, 'mensual', {}, {}, 'Reporte mensual','','')); }

// ═══════════════════════════════════════
// INIT
// ═══════════════════════════════════════
document.getElementById('fdate').textContent=hoy();
loadData();
renderAll();
</script>
</body>
</html>
