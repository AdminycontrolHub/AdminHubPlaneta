<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Cambio de forma de pago · Admin Hub</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Nunito+Sans:opsz,wght@6..12,400;6..12,600;6..12,700;6..12,800&display=swap" rel="stylesheet">
<style>
:root{
  /* Paleta «claro corporativo»: azul corporativo + acento arena */
  --navy:#1D3557; --navy2:#1D3557; --cyan:#F4C27A; --cyan-d:#E0A955; --teal:#2B4C7E;
  --cream:#FFFFFF; --cream2:#EEF2F6; --line:#D5DEE8; --page:#E9EEF3;
  --ink:#12222F; --muted:#5F6B78;
  --amber:#FFB547; --amber-bg:#FFF1D6; --amber-ink:#7A4A00;
  --green-bg:#DDF5EA; --green-ink:#0F5A3A; --red:#FF8A95;
  --row:rgba(255,255,255,.09);
  --font:'Nunito Sans',system-ui,-apple-system,'Segoe UI',sans-serif;
}
*{box-sizing:border-box;margin:0;padding:0}
body{font-family:var(--font);color:var(--ink);background:var(--page);min-height:100vh;padding:28px 24px 60px;font-variant-numeric:tabular-nums;font-size:14px;line-height:1.5}
.wrap{max-width:1180px;margin:0 auto;display:flex;flex-direction:column;gap:20px}
.hidden{display:none!important}
.num{font-variant-numeric:tabular-nums;font-weight:700}

/* cabecera */
header{display:flex;align-items:center;justify-content:space-between;gap:16px;flex-wrap:wrap}
.brand{display:flex;align-items:center;gap:14px}
.orb{width:44px;height:44px;border-radius:50%;background:var(--navy);color:var(--cyan);display:grid;place-items:center}
h1{font-size:23px;font-weight:800;color:var(--navy);line-height:1.2}
.sub{font-size:11.5px;font-weight:700;letter-spacing:1.4px;text-transform:uppercase;color:var(--teal);margin-top:3px;display:flex;align-items:center;gap:10px;flex-wrap:wrap}
.pill{font-size:11px;font-weight:700;letter-spacing:.6px;padding:2px 10px;border-radius:999px;background:#DCE3EB;color:#4A5B70;text-transform:uppercase}
.pill.chg{background:var(--amber-bg);color:var(--amber-ink)}
.hbtns{display:flex;gap:10px;flex-wrap:wrap}

/* botones */
.btn{font-family:var(--font);font-size:13.5px;font-weight:700;color:var(--navy);background:#fff;border:1.5px solid var(--navy);border-radius:10px;padding:8px 14px;cursor:pointer;transition:.15s;display:inline-flex;align-items:center;gap:8px;text-decoration:none;min-height:42px}
.btn:hover{background:#EEF3F9;box-shadow:0 0 0 3px rgba(244,194,122,.18)}
.btn:focus-visible{outline:2px solid var(--cyan-d);outline-offset:2px}
.btn.solid{background:var(--cyan);color:var(--navy);border-color:var(--cyan-d);font-weight:800}
.btn.solid:hover{background:#F7D29D}
.btn svg{flex:none}
.bubble .btn{background:var(--row);color:var(--cyan);border-color:var(--cyan);min-height:36px;padding:6px 12px;font-size:13px}
.bubble .btn:hover{background:rgba(244,194,122,.15)}

/* tarjetas claras */
.card{background:var(--cream);border:1px solid var(--line);border-radius:18px;padding:22px}
.ttl{font-size:12.5px;font-weight:800;letter-spacing:1.5px;text-transform:uppercase;color:var(--teal);margin-bottom:14px;display:flex;align-items:center;gap:10px}
.ttl::after{content:"";flex:1;height:1px;background:linear-gradient(90deg,rgba(43,76,126,.3),transparent)}
.ttl .tag{font-size:11px;font-weight:700;letter-spacing:.6px;color:var(--muted);display:inline-flex;align-items:center;gap:5px}
.lab{font-size:11px;font-weight:700;letter-spacing:1px;text-transform:uppercase;color:var(--muted)}

/* zona HM */
.drop{border:2px dashed #AFC0D3;border-radius:18px;background:#fff;padding:20px 24px;display:flex;align-items:center;gap:18px;flex-wrap:wrap;transition:.15s}
.drop.big{padding:34px 24px}
.drop.over{border-color:var(--navy);background:#F4F7FB}
.drop .ic{width:52px;height:52px;border-radius:14px;background:var(--cream2);display:grid;place-items:center;color:var(--teal);flex:none}
.drop.loaded .ic{background:var(--green-bg);color:var(--green-ink)}
.drop .tx{flex:1 1 280px;display:flex;flex-direction:column;gap:2px}
.drop .tx b{font-size:16.5px;font-weight:800;color:var(--navy)}
.drop .tx span{font-size:13.5px;color:var(--muted)}
.drop .tx .warn{color:var(--amber-ink);font-weight:600}
.drop .acts{display:flex;gap:10px;flex-wrap:wrap}

/* datos alumno */
.dgrid{display:grid;grid-template-columns:repeat(auto-fit,minmax(200px,1fr));gap:14px 22px}
.dgrid div{display:flex;flex-direction:column;gap:2px;min-width:0}
.dgrid .v{font-size:15px;font-weight:600;overflow-wrap:anywhere}
.dgrid .wide{grid-column:span 2}
@media(max-width:560px){.dgrid .wide{grid-column:auto}}

/* paneles */
.grid{display:grid;grid-template-columns:1fr 1fr;gap:22px;align-items:stretch}
.grid>.card,.grid>.bubble{display:flex;flex-direction:column}
.grid .ttl{min-height:24px}
@media(max-width:900px){.grid{grid-template-columns:1fr}}
.prow{display:flex;justify-content:space-between;align-items:center;gap:12px;padding:4px 12px;border-bottom:1px dashed var(--line);font-size:14px;min-height:50px}
.prow:last-child{border-bottom:none}
.prow>span:first-child{color:var(--muted)}
.prow b{font-weight:700;text-align:right}
.prow small{display:block;font-size:12px;color:var(--muted);font-weight:400}
.prow.strong>span:first-child{color:var(--ink);font-weight:700}
.prow.strong b{font-weight:800;color:var(--navy);font-size:15px}
.prow.total{background:var(--navy);border-radius:10px;border:none;padding:4px 12px;margin:2px 0;min-height:46px}
.prow.total>span:first-child{color:#fff;font-weight:800;font-size:14.5px}
.prow.total b{color:var(--cyan);font-size:19px;font-weight:800}

/* burbuja azul marino */
.bubble{background:var(--navy2);color:#fff;border-radius:18px;padding:22px;box-shadow:0 14px 36px rgba(29,53,87,.22)}
.bubble .ttl{color:var(--cyan)}
.bubble .ttl::after{background:linear-gradient(90deg,rgba(244,194,122,.4),transparent)}
.bubble .ttl .tag{color:rgba(255,255,255,.65)}
.bubble fieldset{border:none;min-width:0}
.line{display:flex;justify-content:space-between;align-items:center;gap:10px;flex-wrap:wrap;padding:4px 12px;border-radius:9px;background:var(--row);margin-bottom:4px;min-height:46px}
.line>span:first-child,.line>label{color:rgba(255,255,255,.88);font-size:14px}
.line .v{font-weight:700}
.line .ctl{display:flex;align-items:center;gap:8px;flex-wrap:wrap;justify-content:flex-end}
.line .amt{font-size:13px;color:rgba(255,255,255,.7);min-width:84px;text-align:right}
.line.hl{border:1px solid rgba(244,194,122,.5)}
.line.hl .v{color:var(--cyan);font-weight:800}
.line.big .v{font-size:21px}
.line.total{background:var(--cyan);border:none;min-height:46px}
.line.total>span:first-child{color:var(--navy);font-weight:800;font-size:15px}
.line.total .v{color:var(--navy)!important;font-size:24px;font-weight:800}
.line.total.chg{box-shadow:inset 4px 0 0 var(--amber)}
.line.chg{box-shadow:inset 3px 0 0 var(--amber)}
.line.chg .v,.line.chg .amt{color:var(--amber)}
.line .lock{display:inline-flex;align-items:center;gap:6px;color:rgba(255,255,255,.75);font-weight:600}
.secl{font-size:11px;font-weight:800;letter-spacing:1.3px;text-transform:uppercase;color:var(--cyan);opacity:.85;margin:14px 0 7px}
.bubble input,.bubble select{font:600 14px var(--font);color:#fff;background:rgba(4,28,46,.6);border:1px solid rgba(244,194,122,.55);border-radius:9px;height:36px;padding:0 10px;color-scheme:dark;outline:none;font-variant-numeric:tabular-nums}
.bubble input:focus,.bubble select:focus{border-color:var(--cyan);box-shadow:0 0 0 3px rgba(244,194,122,.22)}
.bubble input[type=number]{width:86px;text-align:right;padding:0 8px}
.bubble input.eur{width:108px}
.bubble select{min-width:104px}
.hint{font-size:12px;color:rgba(255,255,255,.65)}
.aviso{margin-top:12px;padding:12px 14px;border-radius:10px;border:1px solid rgba(244,194,122,.45);background:rgba(244,194,122,.08);display:flex;flex-wrap:wrap;align-items:center;justify-content:space-between;gap:10px;font-size:13.5px}
.aviso span{flex:1 1 220px}
.aviso.err{border-color:var(--red);background:rgba(255,92,108,.12);color:#FFD4D8}
.empty-hint{padding:12px 14px;border-radius:10px;border:1px dashed rgba(244,194,122,.45);font-size:13.5px;color:rgba(255,255,255,.8);margin-bottom:12px}
.bubble fieldset:disabled .line{opacity:.55}

/* observaciones desplegables */
.lnk{display:inline-flex;align-items:center;gap:4px;background:none;border:none;padding:4px 6px;border-radius:6px;font:700 12.5px var(--font);letter-spacing:0;text-transform:none;color:var(--muted);cursor:pointer}
.lnk:hover{color:var(--navy);background:var(--cream2)}
.lnk:focus-visible{outline:2px solid var(--navy);outline-offset:1px}
.obsprev{margin-top:10px;font-size:14px;color:var(--ink);white-space:pre-wrap}
/* observaciones y campos claros */
textarea{width:100%;min-height:92px;font:400 14.5px/1.55 var(--font);color:var(--ink);background:#fff;border:1.5px solid #D9D0C1;border-radius:10px;padding:10px 12px;resize:vertical;outline:none}
.card input{font:600 14px var(--font);color:var(--ink);background:#fff;border:1.5px solid #D9D0C1;border-radius:10px;height:42px;padding:0 12px;width:100%;outline:none}
textarea:focus,.card input:focus{border-color:var(--cyan-d);box-shadow:0 0 0 3px rgba(244,194,122,.22)}

/* aviso de cambio de facturación */
.fact{display:flex;flex-wrap:wrap;align-items:baseline;gap:2px 10px;padding:8px 14px;border-radius:10px;margin-bottom:10px;background:var(--cream2);border:1px solid var(--line);font-size:13px}
.fact b{font-weight:800;color:var(--navy)}
.fact span{color:var(--muted)}
.fact.si{background:var(--amber-bg);border:1.5px solid var(--amber)}
.fact.si b{color:var(--amber-ink);font-size:13.5px}
.fact.si span{color:var(--navy);font-weight:700}
/* elección de marca al abrir */
.chooser{position:fixed;inset:0;z-index:90;background:radial-gradient(900px 500px at 80% -10%,rgba(0,180,255,.12),transparent 60%),#041C2E;display:flex;align-items:center;justify-content:center;padding:16px}
.ch-box{background:#fff;border-radius:18px;width:min(460px,100%);padding:28px 24px 20px;text-align:center;box-shadow:0 0 0 1px rgba(0,212,240,.25),0 24px 60px rgba(0,0,0,.45)}
.ch-title{font-size:18px;font-weight:800;color:#1D3557}
.ch-sub{font-size:13.5px;color:var(--muted);margin:4px 0 20px}
.ch-opts{display:grid;grid-template-columns:1fr 1fr;gap:14px}
.ch-opt{display:flex;flex-direction:column;align-items:center;gap:6px;padding:20px 10px 16px;border-radius:14px;border:1.5px solid #D5DEE8;background:#F7F9FB;cursor:pointer;font-family:var(--font);transition:transform .15s,box-shadow .15s,border-color .15s}
.ch-opt img{height:30px;max-width:150px;object-fit:contain;margin-bottom:4px}
.ch-opt b{font-size:20px;font-weight:800;letter-spacing:1px;color:#1D3557}
.ch-opt small{font-size:11.5px;color:var(--muted)}
.ch-opt[data-m="OBS"]:hover,.ch-opt[data-m="OBS"]:focus-visible{border-color:#1D3557;box-shadow:0 8px 22px rgba(29,53,87,.18);transform:translateY(-2px);outline:none}
.ch-opt[data-m="ESD"] b{color:#C9421C}
.ch-opt[data-m="ESD"]:hover,.ch-opt[data-m="ESD"]:focus-visible{border-color:#E8562F;box-shadow:0 8px 22px rgba(232,86,47,.2);transform:translateY(-2px);outline:none}
.ch-back{display:inline-block;margin-top:16px;font-size:12.5px;color:var(--muted);text-decoration:none}
.ch-back:hover{color:#1D3557;text-decoration:underline}
body.enmodal .ch-back,body.vclaude .ch-back{display:none}
/* selector de marca */
.marcas{display:inline-flex;border:1.5px solid var(--navy);border-radius:10px;overflow:hidden;background:#fff}
.marcas button{font:800 13px var(--font);letter-spacing:.6px;padding:0 14px;min-height:39px;border:none;background:transparent;color:var(--navy);cursor:pointer}
.marcas button[aria-pressed="true"]{background:var(--navy);color:#fff}
.marcas button:focus-visible{outline:2px solid var(--cyan-d);outline-offset:-3px}
/* Tema ESD: grafito y naranja ESDesign */
body[data-marca="ESD"]{--navy:#2A2A2E;--navy2:#2A2A2E;--cyan:#F58A66;--cyan-d:#E8562F;--teal:#4A4A52;--page:#EFEDEB;--line:#DDD8D3;--cream2:#F3F0ED}
body[data-marca="ESD"] .card.resumen{background:#F7E6DE;border-color:#EDB49C}
body[data-marca="ESD"] .card.resumen .ttl{color:#C9421C}
body[data-marca="ESD"] .ib{border-color:#C9421C;color:#C9421C}
body[data-marca="ESD"] .ib:hover,body[data-marca="ESD"] .ib:focus-visible{background:#2A2A2E;color:#fff;border-color:#2A2A2E}
body[data-marca="ESD"] .headline .arrow{color:#E8562F}
body[data-marca="ESD"] .orb{color:#F58A66}
body[data-marca="ESD"] .sub{color:#C9421C}
/* recuadro del resumen: color propio */
.card.resumen{background:#DCE8F5;border:1.5px solid #9DB8D9}
.card.resumen .ttl{color:#0B5394}
.rhead{display:flex;align-items:center;gap:14px;margin-bottom:14px;flex-wrap:wrap}
.ibtns{display:flex;gap:8px}
.ib{position:relative;width:42px;height:42px;border-radius:10px;border:1.5px solid #0B5394;background:#fff;color:#0B5394;display:grid;place-items:center;cursor:pointer;transition:.15s}
.ib:hover,.ib:focus-visible{background:var(--navy);color:#fff;border-color:var(--navy);outline:none}
.ib[data-tip]::after{content:attr(data-tip);position:absolute;bottom:calc(100% + 8px);right:0;white-space:nowrap;background:var(--navy);color:#fff;font-size:12.5px;font-weight:700;padding:6px 10px;border-radius:8px;border:1px solid var(--navy);opacity:0;pointer-events:none;transform:translateY(4px);transition:.15s;z-index:5}
.ib:hover::after,.ib:focus-visible::after{opacity:1;transform:translateY(0)}
/* resumen: antes / ahora */
.two{display:grid;grid-template-columns:1fr 1fr;gap:14px}
@media(max-width:640px){.two{grid-template-columns:1fr}}
.col{background:#fff;border:1px solid var(--line);border-radius:12px;padding:14px 16px}
.col.now{border:2px solid var(--navy);padding:13px 15px}
.col h3{font-size:11.5px;font-weight:800;letter-spacing:1.2px;text-transform:uppercase;color:var(--muted);margin-bottom:6px}
.col.now h3{color:var(--navy)}
.kv{display:flex;justify-content:space-between;align-items:baseline;gap:12px;padding:8px 0;border-top:1px dashed var(--line);font-size:14px}
.kv:first-of-type{border-top:none}
.kv>span:first-child{color:var(--muted)}
.kv>span:last-child{text-align:right}
.col.now .kv>span:last-child{font-weight:800;color:var(--navy)}
.kv.tot>span:first-child{color:var(--ink);font-weight:700}
.col.now .kv.tot>span:last-child{font-size:16px}
/* resumen */
.headline{background:#fff;border:1px solid var(--line);border-radius:12px;padding:14px 16px;font-size:15px;line-height:1.6;margin-bottom:14px}
.headline b{font-weight:800;color:var(--navy)}
.headline .arrow{color:#C98A2E;font-weight:800;margin:0 4px}
.tw{overflow-x:auto;background:#fff;border:1px solid var(--line);border-radius:12px}
table.rs{width:100%;border-collapse:collapse;font-size:14px;min-width:560px}
table.rs th{font-size:11px;font-weight:800;letter-spacing:1px;text-transform:uppercase;color:var(--muted);text-align:right;padding:10px 14px;border-bottom:1px solid var(--line);background:var(--cream2)}
table.rs th:first-child,table.rs td:first-child{text-align:left}
table.rs td{padding:10px 14px;border-bottom:1px solid var(--line);text-align:right}
table.rs tr:last-child td{border-bottom:none}
table.rs td.b{color:var(--muted)}
table.rs td.a{font-weight:800;color:var(--navy)}
table.rs tr.key td{background:#FFFCF5}
.df{display:inline-block;font-size:12.5px;font-weight:700;padding:2px 9px;border-radius:999px;background:var(--amber-bg);color:var(--amber-ink);white-space:nowrap}
.df.down{background:var(--green-bg);color:var(--green-ink)}
.vacio{padding:14px;border-radius:10px;background:var(--cream2);color:var(--muted)}
.meta{display:flex;flex-wrap:wrap;gap:6px 20px;margin-top:14px;padding-top:12px;border-top:1px dashed var(--line);font-size:13px;color:var(--muted)}

/* correo */
.mgrid{display:grid;grid-template-columns:90px minmax(0,1fr);gap:10px 12px;align-items:center;margin-bottom:12px}
.mbody{background:#fff;border:1px solid var(--line);border-radius:10px;padding:16px 18px;font-size:14px;line-height:1.6;overflow-x:auto}
.foot{display:flex;flex-wrap:wrap;justify-content:flex-end;gap:10px}

body.ext #btnVolver{display:none!important}
/* Enlace externo de una marca: sin selector ni elección de la otra marca */
body.bloq .marcas,body.bloq #chooser{display:none!important}
/* Abierto dentro del modal del hub: el hub ya tiene su botón de cerrar */
body.enmodal #btnVolver,body.enmodal #btnLink{display:none!important}
body.enmodal{padding-top:18px}
/* Vista compartida desde Claude: sin enlaces al hub ni el .eml (la plataforma no permite descargar ese formato) */
body.vclaude #btnVolver,body.vclaude #btnLink,body.vclaude #btnEml,body.vclaude .solo-hub{display:none!important}

.toast{position:fixed;bottom:24px;left:50%;transform:translateX(-50%) translateY(20px);opacity:0;background:var(--navy);border:1px solid var(--cyan);color:var(--cyan);font-size:13.5px;font-weight:700;padding:10px 18px;border-radius:10px;transition:.25s;z-index:80;pointer-events:none;max-width:92vw;text-align:center}
.toast.on{opacity:1;transform:translateX(-50%) translateY(0)}
.toast.err{border-color:var(--red);color:#FFD4D8}
</style>
</head>
<body>

<svg width="0" height="0" style="position:absolute" aria-hidden="true">
  <symbol id="i-up" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><path d="M14 3v4a1 1 0 0 0 1 1h4"/><path d="M17 21H7a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h7l5 5v11a2 2 0 0 1-2 2z"/><path d="M12 11v6M9 14l3-3 3 3"/></symbol>
  <symbol id="i-ok" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><path d="M14 3v4a1 1 0 0 0 1 1h4"/><path d="M17 21H7a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h7l5 5v11a2 2 0 0 1-2 2z"/><path d="M9 15l2 2 4-4"/></symbol>
  <symbol id="i-lock" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="5" y="11" width="14" height="10" rx="2"/><path d="M8 11V7a4 4 0 0 1 8 0v4"/></symbol>
  <symbol id="i-back" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M19 12H5M11 6l-6 6 6 6"/></symbol>
  <symbol id="i-reset" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M3 12a9 9 0 1 0 3-6.7L3 8"/><path d="M3 3v5h5"/></symbol>
  <symbol id="i-copy" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="9" y="9" width="12" height="12" rx="2"/><path d="M5 15H4a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1h10a1 1 0 0 1 1 1v1"/></symbol>
  <symbol id="i-down" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.2" stroke-linecap="round" stroke-linejoin="round"><path d="M12 4v12"/><path d="M6 11l6 6 6-6"/><path d="M5 20h14"/></symbol>
  <symbol id="i-mail" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><rect x="3" y="5" width="18" height="14" rx="2"/><path d="M3 7l9 6 9-6"/></symbol>
  <symbol id="i-link" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M10 14a4 4 0 0 0 5.7 0l3-3a4 4 0 0 0-5.7-5.7l-1 1"/><path d="M14 10a4 4 0 0 0-5.7 0l-3 3a4 4 0 0 0 5.7 5.7l1-1"/></symbol>
  <symbol id="i-clip" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" stroke-linejoin="round"><path d="M20.5 11.5l-8.2 8.2a5 5 0 0 1-7.1-7.1l8.6-8.6a3.4 3.4 0 0 1 4.8 4.8l-8.4 8.4a1.7 1.7 0 0 1-2.4-2.4l7.6-7.6"/></symbol>
  <symbol id="i-pdf" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><path d="M14 3v4a1 1 0 0 0 1 1h4"/><path d="M17 21H7a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h7l5 5v11a2 2 0 0 1-2 2z"/><path d="M12 11v6M9.5 14.5L12 17l2.5-2.5"/></symbol>
  <symbol id="i-edit" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M4 20h4L19 9l-4-4L4 16z"/></symbol>
  <symbol id="i-card" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><rect x="2.5" y="5" width="19" height="14" rx="2"/><path d="M2.5 10h19M6.5 15h4"/></symbol>
</svg>

<div class="wrap">
  <header>
    <div class="brand">
      <div class="orb"><svg width="22" height="22" aria-hidden="true"><use href="#i-card"/></svg></div>
      <div>
        <h1>Cambio de forma de pago</h1>
        <div class="sub">Admin Hub · Cobros · <span id="marcaTxt">OBS Business School</span> <span class="pill" id="estado">Sin HM</span></div>
      </div>
    </div>
    <div class="hbtns">
      <div class="marcas" role="group" aria-label="Marca">
        <button type="button" data-m="OBS" aria-pressed="true">OBS</button>
        <button type="button" data-m="ESD" aria-pressed="false">ESD</button>
      </div>
      <a class="btn" id="btnVolver" href="index.html"><svg width="16" height="16" aria-hidden="true"><use href="#i-back"/></svg>Volver a Cobros</a>
      <button class="btn" id="btnLink" type="button" title="Copiar enlace externo para compartir"><svg width="16" height="16" aria-hidden="true"><use href="#i-link"/></svg><span>Enlace externo</span></button>
      <button class="btn" id="btnLimpiar" type="button" title="Reiniciar: borra la HM cargada y todos los cambios"><svg width="16" height="16" aria-hidden="true"><use href="#i-reset"/></svg>Limpiar</button>
    </div>
  </header>

  <section class="drop big" id="drop" aria-label="Zona para arrastrar la HM">
    <div class="ic"><svg width="26" height="26" aria-hidden="true"><use id="dropIco" href="#i-up"/></svg></div>
    <div class="tx">
      <b id="dropTitle">Arrastra aquí la HM</b>
      <span id="dropSub"></span>
      <span id="dropWarn" class="warn hidden"></span>
    </div>
    <div class="acts">
      <input type="file" id="file" accept=".pdf,.docx,.doc,application/pdf,application/vnd.openxmlformats-officedocument.wordprocessingml.document" class="hidden">
      <button class="btn" type="button" id="btnEjemplo">Ver ejemplo</button>
      <button class="btn solid" type="button" id="btnFile">Seleccionar HM</button>
    </div>
  </section>

  <section class="card">
    <h2 class="ttl">Datos del alumno y programa</h2>
    <div class="dgrid">
      <div><span class="lab">Alumno</span><span class="v" id="a-nombre">—</span></div>
      <div><span class="lab">ID oportunidad</span><span class="v" id="a-id">—</span></div>
      <div><span class="lab">Email</span><span class="v" id="a-email">—</span></div>
      <div><span class="lab">Asesor</span><span class="v" id="a-asesor">—</span></div>
      <div class="wide"><span class="lab">Programa</span><span class="v" id="a-prog">—</span></div>
      <div><span class="lab">Convocatoria</span><span class="v" id="a-conv">—</span></div>
    </div>
  </section>

  <div class="grid">
    <section class="card" id="partida"></section>
    <section class="bubble" id="mod"></section>
  </div>

  <section class="card" id="secObs">
    <h2 class="ttl" style="margin:0">Observaciones <button class="lnk" id="btnObs" type="button" aria-expanded="false" aria-controls="obsBox"><svg width="12" height="12" aria-hidden="true"><use href="#i-plus"/></svg><span>Añadir</span></button></h2>
    <p class="obsprev hidden" id="obsPrev"></p>
    <div id="obsBox" class="hidden" style="margin-top:12px">
      <textarea id="f-obs" aria-label="Observaciones" placeholder="Motivo del cambio, quién lo solicita y cualquier acuerdo con el alumno."></textarea>
    </div>
  </section>

  <section class="card resumen" id="secResumen">
    <div class="rhead">
      <h2 class="ttl" style="margin:0;flex:1">Resumen de lo modificado <span class="tag" id="nCambios"></span></h2>
      <div class="ibtns">
        <button class="ib" id="btnMail" type="button" aria-label="Correo en Outlook con el PDF adjunto" data-tip="Correo en Outlook con el PDF adjunto"><svg width="20" height="20" aria-hidden="true"><use href="#i-mail"/></svg></button>
        <button class="ib" id="btnPdf" type="button" aria-label="Descargar PDF" data-tip="Descargar PDF"><svg width="20" height="20" aria-hidden="true"><use href="#i-pdf"/></svg></button>
      </div>
    </div>
    <div id="resumen"></div>
    <div class="meta">
      <span>HM origen: <b id="r-hm">—</b></span>
      <span>Fecha del cambio: <b id="r-hoy"></b></span>
    </div>
  </section>
</div>

<div class="toast" id="toast" role="status" aria-live="polite"></div>

<!-- Elección de marca al abrir el módulo (si no llega ya elegida desde el hub) -->
<div class="chooser hidden" id="chooser">
  <div class="ch-box" role="dialog" aria-modal="true" aria-labelledby="chTitle">
    <p class="ch-title" id="chTitle">Cambio de forma de pago (CFP)</p>
    <p class="ch-sub">¿Para qué marca es la HM?</p>
    <div class="ch-opts">
      <button type="button" class="ch-opt" data-m="OBS"><img id="chLogoOBS" alt=""><b>OBS</b><small>Business School</small></button>
      <button type="button" class="ch-opt" data-m="ESD"><img id="chLogoESD" alt=""><b>ESD</b><small>ESDesign</small></button>
    </div>
    <a class="ch-back" id="chBack" href="index.html">Volver a Cobros</a>
  </div>
</div>

<script>
(function(){
/* ======================= CONFIG ======================= */
/* Logo de la HM (PNG transparente) y letra Poppins para el PDF: incrustados al final del archivo */
var LIBS = {
  pdfjs:     'https://cdn.jsdelivr.net/npm/pdfjs-dist@4.10.38/build/pdf.min.mjs',
  pdfWorker: 'https://cdn.jsdelivr.net/npm/pdfjs-dist@4.10.38/build/pdf.worker.min.mjs',
  jszip:     'https://cdnjs.cloudflare.com/ajax/libs/jszip/3.10.1/jszip.min.js',
  jspdf:     'https://cdnjs.cloudflare.com/ajax/libs/jspdf/2.5.1/jspdf.umd.min.js'
};
/* Destinatario de los CFP según la marca */
function paraMarca(){ return MARCAS[MARCA].para; }
/* Marcas: logo y colores del PDF y del correo. La marca llega del hub (?marca=ESD), se puede cambiar arriba
   y se detecta en la HM por el campus («OBS Online» / «ESDESIGN Online»). */
var MARCAS = {
  OBS: { nombre:'OBS Business School', para:'atencioncobros@obsbusiness.school', logo:function(){return LOGO_HM;},  logoW:52, logoH:52*83/420,
         pdfAcento:[11,83,148], pdfOscuro:[4,28,46], pdfClaro:[0,230,255], pdfSeccion:[11,110,124], mailAhora:'#00B8CC', mailTitulo:'#0B6E7C' },
  ESD: { nombre:'ESDesign', para:'administracion@esdesignbarcelona.com', logo:function(){return LOGO_ESD;}, logoW:48, logoH:48*53/256,
         pdfAcento:[201,66,28], pdfOscuro:[38,38,42], pdfClaro:[245,138,102], pdfSeccion:[74,74,82], mailAhora:'#E8562F', mailTitulo:'#C9421C' }
};
var MARCA = 'OBS';
var DTO_CONTADO_DEFECTO = 10;   // % que se propone al añadir el dto. contado si la HM no lo traía
var TXT_DROP = 'Acepta PDF o Word (.docx). Se lee el importe master, el total final a pagar y el dto. de contado; las ayudas y otros dtos. se calculan con esos datos.';

var FORMAS = [
  {id:'aplazado',     txt:'Aplazado'},
  {id:'contado',      txt:'Contado'},
  {id:'contado_dias', txt:'Contado en días'},
  {id:'contado_2',    txt:'Contado 2 veces'}
];

/* ======================= UTILIDADES ======================= */
var $ = function(id){ return document.getElementById(id); };
var eurF = new Intl.NumberFormat('es-ES',{style:'currency',currency:'EUR',minimumFractionDigits:2,maximumFractionDigits:2,useGrouping:'always'});
function eur(n){ return (n==null||isNaN(n)) ? '—' : eurF.format(n); }
function pctTxt(n){ return (n==null||isNaN(n)) ? '—' : Number(n).toLocaleString('es-ES',{maximumFractionDigits:2})+' %'; }
function r2(x){ return Math.round(Number((x*100).toFixed(6)))/100; }
function num(v){ var n=parseFloat(String(v).replace(',','.')); return isNaN(n)?0:n; }
function esc(s){ return String(s==null?'':s).replace(/[&<>"']/g,function(c){return {'&':'&amp;','<':'&lt;','>':'&gt;','"':'&quot;',"'":'&#39;'}[c];}); }
function dmy(iso){ if(!iso) return '—'; var p=iso.split('-'); return p[2]+'/'+p[1]+'/'+p[0]; }
function isoDe(s){ var m=/(\d{1,2})\/(\d{1,2})\/(\d{4})/.exec(s||''); return m ? m[3]+'-'+('0'+m[2]).slice(-2)+'-'+('0'+m[1]).slice(-2) : ''; }
function toISO(d){ return d.getFullYear()+'-'+('0'+(d.getMonth()+1)).slice(-2)+'-'+('0'+d.getDate()).slice(-2); }
function addMonth(iso){ var t=new Date(iso+'T00:00:00'); t.setMonth(t.getMonth()+1); return toISO(t); }
var HOY = toISO(new Date());
function formaTxt(id){ var f=FORMAS.filter(function(x){return x.id===id;})[0]; return f?f.txt:'—'; }

/* "7,950.00" · "5.077,54" · "-1,351.50" · "507.75" -> número */
function parseNum(s){
  s=String(s||'').replace(/[€\s ]/g,'');
  var neg=/^-/.test(s); s=s.replace(/^[-+]/,'');
  if(!s) return NaN;
  var c=s.lastIndexOf(','), d=s.lastIndexOf('.');
  if(c>-1 && d>-1){ var dec=c>d?',':'.'; s=s.split(dec==','?'.':',').join(''); s=s.replace(dec,'.'); }
  else if(c>-1){ s=/,\d{1,2}$/.test(s) ? s.replace(/\./g,'').replace(',','.') : s.replace(/,/g,''); }
  else if(d>-1){ if(!/\.\d{1,2}$/.test(s) || (s.match(/\./g)||[]).length>1) s=s.replace(/\.(?=\d{3}(\.|$))/g,''); }
  var n=parseFloat(s); return isNaN(n)?NaN:(neg?-n:n);
}

var toastT;
function toast(t,err,ms){ var e=$('toast'); e.textContent=t; e.classList.toggle('err',!!err); e.classList.add('on'); clearTimeout(toastT); toastT=setTimeout(function(){e.classList.remove('on');},ms||3000); }

var cargadas={};
function loadScript(url){
  if(!cargadas[url]) cargadas[url]=new Promise(function(ok,ko){ var s=document.createElement('script'); s.src=url; s.onload=ok; s.onerror=function(){ delete cargadas[url]; ko(new Error('No se pudo cargar '+url)); }; document.head.appendChild(s); });
  return cargadas[url];
}

/* ======================= LECTURA DE LA HM ======================= */
async function lineasPDF(file){
  var pdfjsLib = await import(LIBS.pdfjs);
  pdfjsLib.GlobalWorkerOptions.workerSrc = LIBS.pdfWorker;
  var pdf = await pdfjsLib.getDocument({data:new Uint8Array(await file.arrayBuffer())}).promise;
  var out=[];
  for(var p=1;p<=pdf.numPages;p++){
    var page=await pdf.getPage(p), tc=await page.getTextContent(), filas=[];
    tc.items.forEach(function(it){
      if(!it.str || !it.str.trim()) return;
      var x=it.transform[4], y=it.transform[5], f=null;
      for(var i=0;i<filas.length;i++){ if(Math.abs(filas[i].y-y)<3){ f=filas[i]; break; } }
      if(!f){ f={y:y,items:[]}; filas.push(f); }
      f.items.push({x:x,w:it.width||0,s:it.str});
    });
    filas.sort(function(a,b){return b.y-a.y;}).forEach(function(f){
      f.items.sort(function(a,b){return a.x-b.x;});
      var t='', fin=null;
      f.items.forEach(function(it){ if(fin!==null && it.x-fin>1) t+=' '; t+=it.s; fin=it.x+it.w; });
      out.push(t.replace(/\s+/g,' ').trim());
    });
  }
  return out;
}

async function lineasDOCX(file){
  await loadScript(LIBS.jszip);
  var zip=await JSZip.loadAsync(await file.arrayBuffer());
  var xml=await zip.file('word/document.xml').async('string');
  var doc=new DOMParser().parseFromString(xml,'application/xml');
  var W='http://schemas.openxmlformats.org/wordprocessingml/2006/main', out=[];
  function textoP(p){
    var t=''; var walker=doc.createTreeWalker(p,NodeFilter.SHOW_ELEMENT);
    for(var n=walker.currentNode;n;n=walker.nextNode()){
      if(n.namespaceURI!==W) continue;
      if(n.localName==='t') t+=n.textContent; else if(n.localName==='tab'||n.localName==='br') t+=' ';
    }
    return t.replace(/\s+/g,' ').trim();
  }
  function recorrer(el){
    Array.prototype.forEach.call(el.childNodes,function(n){
      if(n.nodeType!==1) return;
      if(n.namespaceURI!==W){ recorrer(n); return; }
      if(n.localName==='p'){ var t=textoP(n); if(t) out.push(t); }
      else if(n.localName==='tbl'){
        Array.prototype.forEach.call(n.getElementsByTagNameNS(W,'tr'),function(tr){
          var celdas=Array.prototype.filter.call(tr.childNodes,function(c){return c.nodeType===1&&c.localName==='tc';})
            .map(function(tc){ return Array.prototype.map.call(tc.getElementsByTagNameNS(W,'p'),textoP).filter(Boolean).join(' '); })
            .filter(Boolean);
          if(celdas.length) out.push(celdas.join('   '));
        });
      }
      else recorrer(n);
    });
  }
  recorrer(doc.documentElement);
  return out;
}

/* Busca el dto. pago de contado en la tabla de descuentos (% Desc / Importe Descuento).
   Funciona con una fila por descuento y también cuando la HM agrupa varios en la misma celda («-5%-8%», «-274.28 €-477.00 €»). */
function buscarContado(lineas){
  var RE_PCT=/-?\s*\d+(?:[.,]\d+)?\s*%/g, RE_IMP=/-\s*\d[\d.,]*\s*€/g;
  var ini=-1, fin=lineas.length;
  lineas.forEach(function(l,i){ if(ini<0 && /%\s*(?:Desc|Disc)/i.test(l)) ini=i; });
  lineas.forEach(function(l,i){ if(ini>-1 && i>ini && fin===lineas.length && /Importe Total Final|Total Amount Payable/i.test(l)) fin=i; });
  var res={pct:0, importe:0, encontrado:false, dudoso:false};
  if(ini>-1){
    var grupos=[], g=null;
    for(var i=ini+1;i<fin;i++){
      var l=lineas[i], pcts=l.match(RE_PCT)||[], imps=l.match(RE_IMP)||[];
      if(pcts.length || imps.length){ g={txt:l.replace(RE_PCT,' ').replace(RE_IMP,' '), pcts:pcts, imps:imps}; grupos.push(g); }
      else if(g) g.txt+=' '+l;
    }
    grupos.forEach(function(g){
      var txt=g.txt.replace(/\s+/g,' ').trim();
      if(!/contado/i.test(txt)) return;
      var idx=0;
      if(g.pcts.length>1 || g.imps.length>1){
        /* Los nombres pueden venir pegados («…en díasDescuento ESDESIGNER»): se corta en cada inicio de concepto, con o sin espacio */
        var et=txt.replace(/([a-záéíóúñ])(?=(?:Descuento|Dto\.|Ayuda|Beca|Referid|Bonificaci|Promoci|Discount))/g,'$1 ').split(/(?=\b(?:Descuento|Dto\.?|Ayuda|Beca|Referid\w*|Bonificaci\w*|Promoci\w*|Discount)\b)/i).map(function(s){return s.trim();}).filter(Boolean);
        idx=-1; et.forEach(function(e,k){ if(idx<0 && /contado/i.test(e)) idx=k; });
        if(et.length!==Math.max(g.pcts.length,g.imps.length) || idx<0){ res.dudoso=true; return; }
      }
      res.encontrado=true;
      res.pct=g.pcts[idx]?Math.abs(parseNum(g.pcts[idx].replace('%',''))):0;
      res.importe=g.imps[idx]?Math.abs(parseNum(g.imps[idx])):0;
    });
  }
  if(!res.encontrado && !res.dudoso){
    lineas.forEach(function(l){
      if(res.encontrado || !/contado/i.test(l) || /Forma pago|payment method/i.test(l)) return;
      var im=l.match(RE_IMP); if(!im) return;
      var pc=l.match(RE_PCT);
      res.encontrado=true; res.importe=Math.abs(parseNum(im[im.length-1])); res.pct=pc?Math.abs(parseNum(pc[pc.length-1].replace('%',''))):0;
    });
  }
  return res;
}

function interpretarHM(lineas, archivo){
  lineas=lineas.reduce(function(acc,l){ var prev=acc[acc.length-1]; if(prev!=null && /:\s*$/.test(prev) && !/:\s*$/.test(l)) acc[acc.length-1]=prev+' '+l; else acc.push(l); return acc; },[]);
  var txt=lineas.join('\n');
  function m(re){ var r=re.exec(txt); return r?r[1].trim():''; }
  function n(re){ var v=m(re); return v?parseNum(v):NaN; }

  var H={
    archivo:archivo,
    /* Cada dato admite la etiqueta en español o en inglés (HM «Oferta Ganada … ENG») */
    fechaMatricula: isoDe(m(/(?:Fecha de matr[ií]cula|Enrol?ment date)\s*:?\s*(\d{1,2}\/\d{1,2}\/\d{4})/i)),
    programa: m(/^\s*(?:Programa|Programme|Program)\s*:\s*(.+)$/im),
    convocatoria: m(/^\s*(?:Convocatoria|Call for Applications)\s*:\s*(.+)$/im),
    nombre: m(/^\s*(?:Nombre|Name)\s*:\s*(.+)$/im),
    apellidos: m(/^\s*(?:Apellidos|Surname)\s*:\s*(.+)$/im),
    idOportunidad: m(/^\s*ID\s*:\s*(\S+)/im),
    email: m(/^\s*Email\s*:\s*(\S+@\S+)/im),
    asesor: m(/(?:Asesor|Admissions Advisor)\s*:\s*(.+)$/im),
    formaRaw: m(/(?:Forma pago seleccionada|Selected payment method)\s*:\s*(.+)$/im),
    master: n(/Importe programa\s*:\s*([-\d.,]+)/i),
    total: n(/(?:Importe Total Final a Pagar|Total Amount Payable)\s*:\s*([-\d.,]+)/i),
    inscPct: n(/%\s*Inscripci[oó]n\s*:\s*([\d.,]+)\s*%/i),
    inscHM: n(/(?:Importe Inscripci[oó]n|Enrol?ment Fee)\s*:\s*(?:[\d.,]+\s*%\s*)?([\d.,]+)/i),
    fecha: isoDe(m(/(?:Fecha Primera Cuota|First Instal?ment Date)\s*:?[ \t]*(\d{1,2}\/\d{1,2}\/\d{4})/i)),
    restoHM: n(/(?:Resto a Abonar en Cuotas|Remaining Balance to be Paid(?: in Instal?ments)?)\s*:?[ \t]*([\d.,]+)/i),
    cuotas: parseInt(m(/(?:N[uú]mero (?:de )?Cuotas|Number of Instal?ments)\s*:[ \t]*(\d+)/i),10)||1,
    cuotaHM: n(/(?:Importe cuota \(Mensual\)|Instal?ment Amount \(Monthly\))\s*:[ \t]*([\d.,]+)/i),
    avisos:[]
  };
  if(isNaN(H.master)){
    // Alternativa: primera línea de «Detalle de Conceptos» con importe positivo
    /* Un importe es negativo solo si el signo va pegado a la cifra («-1,464.00 €»); el guion con espacio
       del nombre del programa («Identidad visual - 6,100.00 €») no cuenta. Se para en el total final. */
    var dc=lineas.findIndex(function(l){return /Detalle de Conceptos|Items? Details/i.test(l);});
    for(var i=dc+1;dc>-1&&i<lineas.length;i++){
      if(/Importe Total Final|Total Amount Payable|%\s*(?:Desc|Disc)/i.test(lineas[i])) break;
      var imps=[], re=/(-?)(\d{1,3}(?:[.,]\d{3})*[.,]\d{2})\s*€/g, mm;
      while((mm=re.exec(lineas[i]))) imps.push(mm);
      if(!imps.length) continue;
      var ult=imps[imps.length-1];
      if(ult[1]!=='-' && !/^\s*Descuento/i.test(lineas[i])){ H.master=parseNum(ult[2]); break; }
    }
  }
  if(isNaN(H.master)) throw new Error('No se encontró el importe del programa (master). Revisa que el archivo sea una HM.');
  if(isNaN(H.total)) throw new Error('No se encontró el «Importe Total Final a Pagar» («Total Amount Payable») en la HM.');

  var c=buscarContado(lineas);
  H.contado=c.importe; H.contadoPct=c.pct;
  if(c.dudoso) H.avisos.push('Hay un dto. de contado agrupado con otros descuentos y no se pudo separar: revisa su importe en la modificación.');
  H.descuentos=r2(H.master-H.total-H.contado);
  /* Control: los importes negativos de la HM (de «Detalle de Conceptos» al total) deben sumar master − total */
  (function(){
    var dc=lineas.findIndex(function(l){return /Detalle de Conceptos|Items? Details/i.test(l);}); if(dc<0) return;
    var suma=0, hay=false, re=/-(\d{1,3}(?:[.,]\d{3})*[.,]\d{2})\s*€/g, mm;
    for(var i=dc+1;i<lineas.length && !/Importe Total Final|Total Amount Payable/i.test(lineas[i]);i++){ re.lastIndex=0; while((mm=re.exec(lineas[i]))){ suma+=parseNum(mm[1]); hay=true; } }
    if(hay && Math.abs(r2(suma)-r2(H.master-H.total))>0.02)
      H.avisos.push('Revisa la HM: sus descuentos suman '+eur(suma)+' pero master − total da '+eur(H.master-H.total)+'.');
  })();
  if(H.descuentos<-0.005) H.avisos.push('Los descuentos calculados salen negativos: revisa el importe master y el total de la HM.');

  var t=(H.formaRaw||'').toLowerCase();
  H.forma = /aplazad/.test(t) ? 'aplazado' : /(2|dos)\s*(veces|pagos)/.test(t) ? 'contado_2' : /d[ií]as/.test(t) ? 'contado_dias' : /contado/.test(t) ? 'contado' : (H.cuotas>1?'aplazado':'contado');
  /* ESD: «Importe Inscripción: 10% 463.60 €» (porcentaje e importe en la misma línea) */
  var insc2=/(?:Importe Inscripci[oó]n|Enrol?ment Fee)\s*:\s*([\d.,]+)\s*%/i.exec(txt);
  if(isNaN(H.inscPct) && insc2) H.inscPct=parseNum(insc2[1]);
  var campus=m(/^\s*Campus\s*:\s*(.+)$/im);
  H.marca = /ESDESIGN|ESDesign|\bESD\b/.test(campus) ? 'ESD' : /OBS/i.test(campus) ? 'OBS'
          : /ESDESIGN/i.test(txt) ? 'ESD' : /OBS Business/i.test(txt) ? 'OBS' : null;
  if(isNaN(H.inscPct)) H.inscPct = (!isNaN(H.inscHM) && H.total) ? r2(H.inscHM/H.total*100) : 0;
  H.insc   = isNaN(H.inscHM)  ? r2(H.total*H.inscPct/100) : H.inscHM;
  H.resto  = isNaN(H.restoHM) ? r2(H.total-H.insc) : H.restoHM;
  H.cuota  = isNaN(H.cuotaHM) ? r2(H.resto/Math.max(1,H.cuotas)) : H.cuotaHM;
  return H;
}

/* ======================= CÁLCULO ======================= */
/* Total = master − descuentos − dto. contado. Inscripción = % sobre el total. Resto = total − inscripción. */
function calcular(){
  var desc=num(S.desc), dto=S.dtoAplica==='aplicar'?num(S.dtoImp):0;
  var total=r2(H.master-desc-dto), insc=r2(num(S.inscImp)), resto=r2(total-insc);
  var n=S.forma==='aplazado' ? Math.max(1,Math.round(num(S.cuotas))||1) : 1;
  return {desc:desc, dto:dto, total:total, insc:insc, resto:resto, cuotas:n, cuota:r2(resto/n)};
}
function baseContado(){ return r2(H.master-num(S.desc)); }

/* ======================= ESTADO ======================= */
var H=null, S=null, S0=null, R=null;

function estadoInicial(){
  return {
    desc:H.descuentos.toFixed(2),
    dtoAplica:H.contado>0?'aplicar':'quitar',
    dtoImp:(H.contado>0?H.contado:0).toFixed(2),
    dtoPct:String(H.contadoPct||DTO_CONTADO_DEFECTO),
    inscImp:H.insc.toFixed(2), forma:H.forma, fecha:H.fecha, cuotas:String(H.cuotas)
  };
}

function filas(){
  var M=calcular(), intacto=JSON.stringify(S)===JSON.stringify(S0), rows=[];
  function add(k,label,b,a,o){ var r={k:k,label:label,b:b,a:intacto?b:a}; for(var x in (o||{})) r[x]=o[x]; if(intacto&&r.money) r.d=0; r.changed=r.a!==r.b; rows.push(r); }
  var dtoA = M.dto>0 ? eur(M.dto) : (H.contado>0?'Retirado':'Sin dto.');
  add('master','Importe master',eur(H.master),eur(H.master));
  add('desc','Descuentos',eur(H.descuentos),eur(M.desc),{money:true,d:M.desc-H.descuentos});
  add('dto','Dto. pago de contado',H.contado>0?eur(H.contado):'Sin dto.',dtoA,{money:true,d:M.dto-H.contado});
  add('total','Importe total final a pagar',eur(H.total),eur(M.total),{money:true,d:M.total-H.total,key:true});
  add('insc','Inscripción',eur(H.insc),eur(M.insc),{money:true,d:M.insc-H.insc});
  add('forma','Forma de pago',formaTxt(H.forma),formaTxt(S.forma),{key:true});
  add('fecha','Fecha primera cuota',dmy(H.fecha),dmy(S.fecha));
  add('cuotas','Número de cuotas',String(H.cuotas),String(M.cuotas),{key:true});
  add('resto','Resto a abonar en cuotas',eur(H.resto),eur(M.resto),{money:true,d:M.resto-H.resto});
  add('cuota','Importe cuota (mensual)',eur(H.cuota),eur(M.cuota),{money:true,d:M.cuota-H.cuota,key:true});
  return {rows:rows, M:M};
}

function aviso(){
  var ap=S.forma==='aplazado', dto=S.dtoAplica==='aplicar';
  if(ap && dto) return {txt:'Aplazado: se propone quitar el dto. pago de contado.', btn:'Quitar dto. contado', act:'quitar'};
  if(ap) return {txt:'Aplazado: las cuotas son libres desde la fecha de primera cuota.'};
  if(S.forma==='contado_2'){
    var lim=H.fechaMatricula?addMonth(H.fechaMatricula):'';
    if(lim && (!S.fecha || S.fecha<=lim)) return {err:true, txt:'Contado 2 veces: el pago tiene que ser a más de un mes de la inscripción (después del '+dmy(lim)+'). 1 cuota.'};
    return {txt:'Contado 2 veces: pago a más de un mes de la inscripción. 1 cuota.'+(dto?'':' Puedes aplicar el dto. pago de contado.'), btn:dto?null:'Aplicar dto. contado', act:'aplicar'};
  }
  var base = S.forma==='contado_dias' ? 'Contado en días: 1 cuota.' : 'Contado: 1 cuota.';
  return {txt: dto ? base : base+' Puedes aplicar el dto. pago de contado.', btn:dto?null:'Aplicar dto. contado', act:'aplicar'};
}

/* Filas del resumen Antes / Ahora (cuotas e importe de cuota en una sola línea) */
function dtoTxtAntes(){ return H.contado>0 ? (H.contadoPct?pctTxt(H.contadoPct)+' · ':'')+eur(H.contado) : 'Sin dto.'; }
function dtoTxtAhora(M){ return M.dto>0 ? pctTxt(num(S.dtoPct))+' · '+eur(M.dto) : (H.contado>0?'Retirado':'Sin dto.'); }
function filasResumen(todas){
  var by={}; R.rows.forEach(function(r){by[r.k]=r;});
  var M=R.M, intacto=JSON.stringify(S)===JSON.stringify(S0), out=[];
  function add(k,label,b,a,ch,o){ var r={k:k,label:label,b:b,a:intacto?b:a,changed:!intacto&&ch}; for(var x in (o||{})) r[x]=o[x]; if(todas||r.changed) out.push(r); }
  add('master','Importe master',eur(H.master),eur(H.master),false);
  add('desc','Descuentos (ayudas y otros dtos.)',eur(H.descuentos),eur(M.desc),by.desc.changed);
  add('dto','Dto. pago de contado',dtoTxtAntes(),dtoTxtAhora(M),by.dto.changed);
  add('total','Total final a pagar',eur(H.total),eur(M.total),by.total.changed,{tot:true});
  add('insc','Inscripción',eur(H.insc),eur(M.insc),by.insc.changed);
  add('forma','Forma de pago',formaTxt(H.forma),formaTxt(S.forma),by.forma.changed);
  add('cuotas','Cuotas',H.cuotas+' × '+eur(H.cuota),M.cuotas+' × '+eur(M.cuota),by.cuotas.changed||by.cuota.changed);
  add('fecha','Fecha 1.ª cuota',dmy(H.fecha),dmy(S.fecha),by.fecha.changed);
  return out;
}

/* Frase que resume el cambio */
function titular(M){
  var antes='<b>'+esc(formaTxt(H.forma))+' · '+H.cuotas+' cuota'+(H.cuotas===1?'':'s')+' de '+eur(H.cuota)+'</b>';
  var ahora='<b>'+esc(formaTxt(S.forma))+' · '+M.cuotas+' cuota'+(M.cuotas===1?'':'s')+' de '+eur(M.cuota)+'</b>';
  var fecha=S.fecha?(M.cuotas===1?' el ':' desde el ')+'<b>'+dmy(S.fecha)+'</b>':'';
  return 'Pasa de '+antes+'<span class="arrow">→</span>'+ahora+fecha+'.';
}
/* ¿Cambia la facturación (importe total final a pagar)? */
function facturacion(M){
  var d=r2(M.total-H.total), cambia=Math.abs(d)>=0.005;
  return {cambia:cambia, b:eur(H.total), a:eur(M.total), d:d,
    titulo: cambia?'Hay cambio de facturación':'Sin cambio de facturación',
    detalle: cambia ? 'De '+eur(H.total)+' a '+eur(M.total) : 'El total final a pagar se mantiene en '+eur(H.total)};
}
function factTexto(){ var f=facturacion(R.M); return (f.cambia?f.titulo.toUpperCase():f.titulo)+': '+f.detalle+'.'; }
function titularTexto(M){ return titular(M).replace(/<span class="arrow">→<\/span>/,' a ').replace(/<[^>]+>/g,''); }

/* ======================= RENDER ======================= */
function lock(){ return '<svg width="14" height="14" aria-hidden="true"><use href="#i-lock"/></svg>'; }
var ETIQ=['Importe master','Descuentos','Dto. pago de contado','Importe total final a pagar','Inscripción','Forma de pago','Fecha primera cuota','Número de cuotas','Resto a abonar en cuotas','Importe cuota (mensual)'];

function renderPartida(){
  var el=$('partida'), h='<h2 class="ttl">HM original <span class="tag">'+lock()+'Solo lectura</span></h2>';
  if(!H){ el.innerHTML=h+ETIQ.map(function(l,i){ return '<div class="prow'+(i===3?' total':i===9?' strong':'')+'"><span>'+l+'</span><b>—</b></div>'; }).join(''); return; }
  h+='<div class="prow"><span>Importe master</span><b>'+eur(H.master)+'</b></div>';
  h+='<div class="prow"><span>Descuentos<small>Ayudas y otros dtos.</small></span><b>− '+eur(H.descuentos)+'</b></div>';
  h+='<div class="prow"><span>Dto. pago de contado</span><b>'+(H.contado>0?(H.contadoPct?pctTxt(H.contadoPct)+' · ':'')+'− '+eur(H.contado):'Sin dto.')+'</b></div>';
  h+='<div class="prow total"><span>Importe total final a pagar</span><b>'+eur(H.total)+'</b></div>';
  h+='<div class="prow"><span>Inscripción ('+pctTxt(H.inscPct)+')</span><b>'+eur(H.insc)+'</b></div>';
  h+='<div class="prow"><span>Forma de pago</span><b>'+esc(H.formaRaw||formaTxt(H.forma))+'</b></div>';
  h+='<div class="prow"><span>Fecha primera cuota</span><b>'+dmy(H.fecha)+'</b></div>';
  h+='<div class="prow"><span>Número de cuotas</span><b>'+H.cuotas+'</b></div>';
  h+='<div class="prow"><span>Resto a abonar en cuotas</span><b>'+eur(H.resto)+'</b></div>';
  h+='<div class="prow strong"><span>Importe cuota (mensual)</span><b>'+eur(H.cuota)+'</b></div>';
  el.innerHTML=h;
}

function renderModEstructura(){
  var el=$('mod');
  if(!H){
    el.innerHTML='<h2 class="ttl">Modificación</h2>'+
      '<div class="empty-hint">Cuando cargues la HM se habilitan aquí los campos para modificar: descuentos, dto. pago de contado, inscripción, forma de pago, fecha de primera cuota y número de cuotas.</div>'+
      '<fieldset disabled>'+ETIQ.map(function(l,i){ return '<div class="line'+(i===3?' total':i===9?' hl':'')+'"><span>'+l+'</span><span class="v">—</span></div>'; }).join('')+'</fieldset>';
    return;
  }
  var h='<h2 class="ttl">Modificación <span class="tag">Los cambios se marcan en ámbar</span></h2><fieldset>';
  h+='<div class="line"><span>Importe master</span><span class="lock">'+lock()+eur(H.master)+'</span></div>';
  h+='<div class="line" data-k="desc"><label for="f-desc">Descuentos <span class="hint">· Ayudas y otros dtos.</span></label><span class="ctl"><input class="eur" id="f-desc" type="number" step="0.01" min="0"><span class="hint">€</span></span></div>';
  h+='<div class="line" data-k="dto"><label for="f-dtoa">Dto. pago de contado</label><span class="ctl"><select id="f-dtoa"><option value="aplicar">Aplicar</option><option value="quitar">Quitar</option></select>'+
     '<span id="dtoBox" class="ctl"><input id="f-dtop" type="number" step="0.01" min="0" max="100" aria-label="Porcentaje del dto. pago de contado"><span class="hint">%</span><input class="eur" id="f-dtoi" type="number" step="0.01" min="0" aria-label="Importe del dto. pago de contado"><span class="hint">€</span></span></span></div>';
  h+='<div class="line total" data-k="total"><span>Importe total final a pagar</span><span class="v" id="m-total"></span></div>';
  h+='<div class="line" data-k="insc"><label for="f-insc">Inscripción</label><span class="ctl"><span class="hint" id="m-insc"></span><input class="eur" id="f-insc" type="number" step="0.01" min="0"><span class="hint">€</span></span></div>';
  h+='<div class="line" data-k="forma"><label for="f-forma">Forma de pago</label><select id="f-forma">'+FORMAS.map(function(f){return '<option value="'+f.id+'">'+f.txt+'</option>';}).join('')+'</select></div>';
  h+='<div class="line" data-k="fecha"><label for="f-fecha">Fecha primera cuota</label><input id="f-fecha" type="date"></div>';
  h+='<div class="line" data-k="cuotas"><label for="f-cuotas">Número de cuotas</label><span class="ctl"><input id="f-cuotas" type="number" min="1" step="1"><span class="lock hidden" id="cuotaFija">'+lock()+'1 cuota fija</span></span></div>';
  h+='<div class="line" data-k="resto"><span>Resto a abonar en cuotas</span><span class="v" id="m-resto"></span></div>';
  h+='<div class="line hl big" data-k="cuota"><span>Importe cuota (mensual)</span><span class="v" id="m-cuota"></span></div>';
  h+='</fieldset><div class="aviso" id="aviso"><span id="avisoTxt"></span><button class="btn" type="button" id="btnAviso"></button></div>';
  el.innerHTML=h;
  volcar();
}
function volcar(){
  $('f-desc').value=S.desc; $('f-dtoa').value=S.dtoAplica; $('f-dtop').value=S.dtoPct; $('f-dtoi').value=S.dtoImp;
  $('f-insc').value=S.inscImp; $('f-forma').value=S.forma; $('f-fecha').value=S.fecha; $('f-cuotas').value=S.cuotas;
}

function render(){
  var est=$('estado');
  if(!H){ est.className='pill'; est.textContent='Sin HM'; renderResumenVacio(); return; }
  var F=filas(), M=F.M; R=F;
  var by={}; F.rows.forEach(function(r){by[r.k]=r;});

  $('dtoBox').classList.toggle('hidden',S.dtoAplica!=='aplicar');
  $('m-total').textContent=eur(by.total.a==='—'?M.total:parseNum(by.total.a));
  $('m-insc').textContent=by.insc.changed?'Modificada a mano':'Fija (HM'+(H.inscPct?' · '+pctTxt(H.inscPct):'')+')';
  $('m-resto').textContent=by.resto.a;
  $('m-cuota').textContent=by.cuota.a;
  var ap=S.forma==='aplazado';
  $('f-cuotas').classList.toggle('hidden',!ap);
  $('cuotaFija').classList.toggle('hidden',ap);
  document.querySelectorAll('#mod .line[data-k]').forEach(function(l){ var r=by[l.dataset.k]; l.classList.toggle('chg',!!(r&&r.changed)); });

  var av=aviso();
  $('aviso').classList.toggle('err',!!av.err);
  $('avisoTxt').textContent=av.txt;
  var b=$('btnAviso'); b.classList.toggle('hidden',!av.btn); b.textContent=av.btn||''; b.dataset.act=av.act||'';

  var cambios=F.rows.filter(function(r){return r.changed;}), n=cambios.length;
  est.className='pill'+(n?' chg':''); est.textContent=n?'Borrador · '+n+' cambio'+(n===1?'':'s'):'Sin cambios';
  var nr=filasResumen(false).length; $('nCambios').textContent=n?nr+' concepto'+(nr===1?'':'s')+' modificado'+(nr===1?'':'s'):'';

  var h, fr=filasResumen(false);
  if(!n) h='<div class="vacio">Sin cambios respecto a la HM. Modifica algún campo de la burbuja para generar el resumen.</div>';
  else{
    var col=function(cls,tit,campo){ return '<div class="col'+cls+'"><h3>'+tit+'</h3>'+fr.map(function(r){ return '<div class="kv'+(r.tot?' tot':'')+'"><span>'+esc(r.label)+'</span><span>'+esc(r[campo])+'</span></div>'; }).join('')+'</div>'; };
    var fa=facturacion(M);
    h='<div class="fact'+(fa.cambia?' si':'')+'"><b>'+fa.titulo+'</b><span>'+esc(fa.detalle)+'</span></div><div class="headline">'+titular(M)+'</div><div class="two">'+col('','Antes (HM)','b')+col(' now','Ahora','a')+'</div>';
  }
  $('resumen').innerHTML=h;
}

function renderResumenVacio(){
  $('nCambios').textContent='';
  $('resumen').innerHTML='<div class="vacio">Aquí aparecerá el resumen: una frase con lo que cambia y, debajo, los conceptos modificados en dos columnas (antes y ahora).</div>';
}

function renderAlumno(){
  var v=function(id,t){ $(id).textContent=t||'—'; };
  v('a-nombre',H?nombreAlumno():''); v('a-id',H&&H.idOportunidad); v('a-email',H&&H.email);
  v('a-prog',H&&H.programa); v('a-conv',H&&H.convocatoria); v('a-asesor',H&&H.asesor);
  v('r-hm',H&&H.archivo); $('r-hoy').textContent=dmy(HOY);
}

function renderDrop(estado){
  var d=$('drop');
  d.classList.toggle('big',!H); d.classList.toggle('loaded',!!H);
  $('dropIco').setAttribute('href',H?'#i-ok':'#i-up');
  if(estado==='leyendo'){ $('dropTitle').textContent='Leyendo HM…'; return; }
  $('dropTitle').textContent=H?H.archivo:'Arrastra aquí la HM';
  $('dropSub').textContent=H?(nombreAlumno()+(H.convocatoria?' · '+H.convocatoria:'')+' · Leída correctamente. Arrastra otra HM para reemplazarla.'):TXT_DROP;
  var w=$('dropWarn'); w.classList.toggle('hidden',!(H&&H.avisos.length)); w.textContent=H?H.avisos.join(' '):'';
  $('btnFile').textContent=H?'Cambiar HM':'Seleccionar HM';
  $('btnEjemplo').classList.toggle('hidden',!!H);
}

function todo(){ renderDrop(); renderAlumno(); renderPartida(); renderModEstructura(); render(); }

/* ======================= TEXTOS ======================= */
function nombreAlumno(){ return [H.nombre,H.apellidos].filter(Boolean).join(' ')||'alumno'; }
function asunto(){ return 'CFP · '+nombreAlumno()+(H.idOportunidad?' · ID '+H.idOportunidad:''); }
function bloquesTexto(){
  var fr=filasResumen(false);
  if(!fr.length) return 'Sin cambios respecto a la HM.';
  var fila=function(r,c){ return '· '+r.label+': '+r[c]; };
  return 'ANTES (HM)\n'+fr.map(function(r){return fila(r,'b');}).join('\n')+'\n\nAHORA\n'+fr.map(function(r){return fila(r,'a');}).join('\n');
}
function cuerpoCorreo(){
  var obs=$('f-obs').value.trim(), hay=filasResumen(false).length>0;
  return ['Buenos días,','',
    'Por favor, solicitamos gestionar el CFP de '+nombreAlumno()+(H.idOportunidad?' (ID '+H.idOportunidad+')':'')+' con el siguiente detalle:',
    H.email?'Email del alumno: '+H.email:'', '',
    hay?factTexto():'', hay?titularTexto(R.M):'', '',
    bloquesTexto(), '',
    obs?'Observaciones: '+obs:'', '',
    'Adjuntamos el PDF con el detalle.','','Muchas gracias.','Un saludo,'].join('\n').replace(/\n{3,}/g,'\n\n').trim();
}
/* Bloque con formato para pegar en el correo: tablas y estilos en línea (lo que admiten Outlook y Gmail) */
function correoHTML(conSaludo){
  var NAVY=MARCA==='ESD'?'#26262A':'#041C2E', MUT='#5F6B78', LIN='#E1D8C7', CYAN=MARCAS[MARCA].mailAhora, FNT="font-family:Calibri,Arial,Helvetica,sans-serif;";
  var fr=filasResumen(false), obs=$('f-obs').value.trim();
  var p=function(t,st){ return '<p style="'+FNT+'margin:0 0 12px;font-size:14px;line-height:1.5;color:'+NAVY+';'+(st||'')+'">'+t+'</p>'; };
  var caja=function(tit,campo,ahora){
    var filas=fr.map(function(r,i){
      var val=esc(r[campo]), lab=esc(r.label);
      return '<tr><td style="'+FNT+'padding:7px 14px;font-size:13.5px;color:'+(r.tot?NAVY:MUT)+';'+(r.tot?'font-weight:bold;':'')+(i?'border-top:1px dashed '+LIN+';':'')+'">'+lab+'</td>'+
             '<td align="right" style="'+FNT+'padding:7px 14px;font-size:'+(r.tot&&ahora?'15px':'13.5px')+';color:'+(ahora?NAVY:MUT)+';'+(ahora||r.tot?'font-weight:bold;':'')+(i?'border-top:1px dashed '+LIN+';':'')+'white-space:nowrap">'+val+'</td></tr>';
    }).join('');
    return '<table role="presentation" width="100%" cellpadding="0" cellspacing="0" style="border-collapse:separate;background:#FFFFFF;border:'+(ahora?'2px solid '+CYAN:'1px solid '+LIN)+';border-radius:10px">'+
      '<tr><td colspan="2" style="'+FNT+'padding:10px 14px 4px;font-size:11px;font-weight:bold;letter-spacing:1px;color:'+(ahora?MARCAS[MARCA].mailTitulo:MUT)+'">'+tit+'</td></tr>'+filas+'</table>';
  };
  var h='';
  if(conSaludo){
    h+=p('Buenos días,');
    h+=p('Por favor, solicitamos gestionar el CFP de <b>'+esc(nombreAlumno())+'</b>'+(H.idOportunidad?' (ID '+esc(H.idOportunidad)+')':'')+' con el siguiente detalle:');
    if(H.email) h+=p('Email del alumno: <a href="mailto:'+esc(H.email)+'" style="color:#0B6E7C">'+esc(H.email)+'</a>','margin-top:-6px');
  } else {
    h+=p('<b>CFP · '+esc(nombreAlumno())+(H.idOportunidad?' · ID '+esc(H.idOportunidad):'')+'</b>'+(H.email?'<br><span style="color:'+MUT+'">Email del alumno: '+esc(H.email)+'</span>':''));
  }
  if(fr.length){
    var fa=facturacion(R.M);
    h+='<table role="presentation" width="100%" cellpadding="0" cellspacing="0" style="max-width:680px;margin:0 0 10px"><tr><td style="'+FNT+'background:'+(fa.cambia?'#FFF1D6':'#EEE8DF')+';border:'+(fa.cambia?'1.5px solid #FFB547':'1px solid '+LIN)+';border-radius:10px;padding:7px 12px;font-size:12.5px;line-height:1.5;color:'+NAVY+'">'+
       '<b style="color:'+(fa.cambia?'#7A4A00':NAVY)+'">'+fa.titulo+':</b> '+(fa.cambia?'<b>':'')+esc(fa.detalle)+(fa.cambia?'</b>':'')+'</td></tr></table>';
    h+='<table role="presentation" width="100%" cellpadding="0" cellspacing="0" style="max-width:680px;margin:0 0 12px"><tr><td style="'+FNT+'background:#F5F0E8;border:1px solid '+LIN+';border-radius:10px;padding:10px 14px;font-size:14px;line-height:1.5;color:'+NAVY+'">'+titular(R.M).replace(/<span class="arrow">→<\/span>/,' → ')+'</td></tr></table>';
    h+='<table role="presentation" width="100%" cellpadding="0" cellspacing="0" style="max-width:680px;margin:0 0 14px"><tr>'+
       '<td valign="top" width="50%" style="padding-right:6px">'+caja('ANTES (HM)','b',false)+'</td>'+
       '<td valign="top" width="50%" style="padding-left:6px">'+caja('AHORA','a',true)+'</td></tr></table>';
  } else h+=p('Sin cambios respecto a la HM.');
  if(obs) h+=p('<b>Observaciones:</b> '+esc(obs));
  if(conSaludo) h+=p('Adjuntamos el PDF con el detalle.')+p('Muchas gracias.<br>Un saludo,');
  return '<div style="'+FNT+'color:'+NAVY+'">'+h+'</div>';
}
/* Copia al portapapeles con formato (y texto plano de respaldo) */
function copiarRico(html,texto){
  if(navigator.clipboard && window.ClipboardItem && window.isSecureContext){
    return navigator.clipboard.write([new ClipboardItem({'text/html':new Blob([html],{type:'text/html'}),'text/plain':new Blob([texto],{type:'text/plain'})})]).then(function(){return true;}).catch(function(){ return copiarSel(html); });
  }
  return Promise.resolve(copiarSel(html));
}
function copiarSel(html){
  var d=document.createElement('div'); d.contentEditable='true'; d.innerHTML=html;
  d.style.cssText='position:fixed;left:-9999px;top:0;opacity:0;background:#fff'; document.body.appendChild(d);
  var r=document.createRange(); r.selectNodeContents(d); var sel=getSelection(); sel.removeAllRanges(); sel.addRange(r);
  var ok=false; try{ ok=document.execCommand('copy'); }catch(e){} sel.removeAllRanges(); d.remove(); return ok;
}
function resumenTexto(){
  var obs=$('f-obs').value.trim(), hay=filasResumen(false).length>0;
  return ['CFP · '+nombreAlumno()+(H.idOportunidad?' · ID '+H.idOportunidad:''),
    H.email?'Email del alumno: '+H.email:'', '',
    hay?factTexto():'', hay?titularTexto(R.M):'', '',
    bloquesTexto(), '',
    obs?'Observaciones: '+obs:'', '',
    'HM: '+H.archivo+' · '+dmy(HOY)
  ].join('\n').replace(/\n{3,}/g,'\n\n').trim();
}

/* ======================= CARGA ======================= */
async function cargar(file){
  var ext=(file.name.split('.').pop()||'').toLowerCase();
  if(ext==='doc'){ toast('Ese Word es del formato antiguo (.doc). Guárdalo como .docx o PDF y vuelve a arrastrarlo.',true); return; }
  if(ext!=='pdf' && ext!=='docx'){ toast('Formato no admitido. Usa una HM en PDF o Word (.docx).',true); return; }
  renderDrop('leyendo');
  try{
    var lineas = ext==='pdf' ? await lineasPDF(file) : await lineasDOCX(file);
    var nuevo = interpretarHM(lineas, file.name);
    if(nuevo.marca && nuevo.marca!==MARCA && bloqueada()) throw new Error('Esta HM es de '+MARCAS[nuevo.marca].nombre+'. Este enlace es solo para '+MARCAS[MARCA].nombre+'.');
    if(nuevo.marca && nuevo.marca!==MARCA){ nuevo.avisos.unshift('La HM es de '+MARCAS[nuevo.marca].nombre+': se ha cambiado la marca a '+nuevo.marca+'.'); setMarca(nuevo.marca); }
    H=nuevo; S=estadoInicial(); S0=JSON.parse(JSON.stringify(S)); resetObs();
    todo();
    toast(H.avisos.length?'HM leída con avisos: revísalos arriba':'HM leída correctamente');
  }catch(e){
    console.error(e); renderDrop();
    toast(/cargar/.test(e.message)?'No se pudo cargar el lector. Comprueba la conexión a internet.':e.message,true);
  }
}

function ejemplo(){
  var lineas=[
    'Fecha de matrícula: 15/10/2026',
    'Programa: Máster de ejemplo en Dirección Comercial - 2704',
    'Importe programa: 7,950.00 €','Convocatoria: Abril 2027',
    'ID: 0000-000000000','Nombre: Alumno','Apellidos: De Ejemplo','Email: alumno@ejemplo.com',
    'Forma pago seleccionada: Contado en días Máster',
    'Detalle de Conceptos',
    'Descuento Fecha Matriculación Máster de ejemplo -1,351.50 €',
    'Descripción % Desc Importe Descuento',
    'Descuento por Apertura -5% -267.24 €','Convocatoria -10% -593.87 €','Descuento Pago de Contado en -10% -659.85 €','días',
    'Importe Total Final a Pagar: 5.077,54 €','%Inscripción: 10%','Importe Inscripción: 507.75 €',
    'Fecha Primera Cuota: 30/10/2026','Resto a Abonar en Cuotas: 4,569.79 €','Número Cuotas: 1','Importe cuota (Mensual): 4,569.79 €',
    'Asesor: Asesor de ejemplo'
  ];
  H=interpretarHM(lineas,'HM_ejemplo.pdf'); S=estadoInicial(); S0=JSON.parse(JSON.stringify(S)); resetObs();
  todo(); toast('Ejemplo cargado: así se ve con una HM');
}

/* ======================= PDF (jsPDF) ======================= */
async function crearPDF(){
  if(!H){ toast('Carga una HM primero.',true); return null; }
  if(aviso().err){ toast('Revisa la fecha de primera cuota antes de continuar.',true); return null; }
  try{ await loadScript(LIBS.jspdf); }catch(e){ toast('No se pudo cargar el generador de PDF. Comprueba la conexión.',true); return null; }
  var doc=new window.jspdf.jsPDF({unit:'mm',format:'a4'}), W=210, X=15, Y;
  /* Letra Poppins incrustada; si fallara, Helvetica */
  var F='helvetica';
  try{
    doc.addFileToVFS('Poppins-Regular.ttf',FONT_PDF_R); doc.addFont('Poppins-Regular.ttf','Poppins','normal');
    doc.addFileToVFS('Poppins-Bold.ttf',FONT_PDF_B);    doc.addFont('Poppins-Bold.ttf','Poppins','bold');
    doc.setFont('Poppins','normal'); F='Poppins';
  }catch(e){ console.warn('Poppins no disponible, se usa Helvetica',e); }
  var T=function(s){ s=String(s==null?'':s).replace(/[  ]/g,' '); return F==='Poppins'?s:s.replace(/[−–]/g,'-').replace(/→/g,'>'); };
  /* Reduce el tamaño solo si el texto no cabe en el ancho disponible */
  var ajustar=function(txt,maxW,sz,min){ while(sz>(min||7) && doc.getTextWidth(txt)>maxW){ sz-=0.5; doc.setFontSize(sz); } return sz; };
  var fnt=function(b,sz,col){ doc.setFont(F,b?'bold':'normal'); doc.setFontSize(sz); doc.setTextColor.apply(doc,col||NAVY); };
  var MK=MARCAS[MARCA], BLUE=MK.pdfAcento, NAVY=MK.pdfOscuro, CYAN=MK.pdfClaro, TEAL=MK.pdfSeccion, MUTED=[95,107,120], CREAM=[245,240,232], LINE=[225,216,199], AMBER=[255,241,214];
  var M=R.M, filasT=filasResumen(true), hay=filasT.some(function(r){return r.changed;});

  /* Cabecera: logo de la HM + fecha e ID */
  try{ doc.addImage(MK.logo(),'PNG',X,12,MK.logoW,MK.logoH); }catch(e){ fnt(true,12); doc.text(T(MK.nombre),X,19); }
  fnt(false,8,MUTED); doc.text('Fecha: '+dmy(HOY),W-X,15,{align:'right'});
  if(H.idOportunidad) doc.text(T('ID oportunidad: '+H.idOportunidad),W-X,20,{align:'right'});
  doc.setDrawColor.apply(doc,NAVY); doc.setLineWidth(0.6); doc.line(X,27,W-X,27);
  fnt(true,16,BLUE); doc.text('Cambio de forma de pago',X,37);

  Y=46;
  function seccion(t){ fnt(true,7.5,TEAL); var tt=T(t.toUpperCase()); doc.text(tt,X,Y); doc.setDrawColor.apply(doc,LINE); doc.setLineWidth(0.3); doc.line(X+doc.getTextWidth(tt)+3,Y-1,W-X,Y-1); Y+=6; }
  function par(lab,val,x,w){ fnt(false,7,MUTED); doc.text(T(lab),x,Y); fnt(false,9); var v=T(val||'—'); if(!/\s/.test(v)) ajustar(v,w,9,6.5); var ls=doc.splitTextToSize(v,w); doc.text(ls,x,Y+4.2); return ls.length; }

  seccion('Datos del alumno');
  var h1=Math.max(par('Alumno',nombreAlumno(),X,74),par('Email',H.email,X+78,62),par('ID oportunidad',H.idOportunidad,X+145,35)); Y+=4.2*h1+5;
  var h2=Math.max(par('Programa',H.programa,X,135),par('Convocatoria',H.convocatoria,X+145,35)); Y+=4.2*h2+6;

  seccion('Resultado del cambio');
  var fa=facturacion(M);
  doc.setFillColor.apply(doc,fa.cambia?AMBER:CREAM); doc.roundedRect(X,Y-4,W-2*X,6.5,1.5,1.5,'F');
  if(fa.cambia){ doc.setFillColor(255,181,71); doc.rect(X,Y-4,1.2,6.5,'F'); }
  fnt(true,7.5,fa.cambia?[122,74,0]:NAVY); var ft=T(fa.titulo+':'); doc.text(ft,X+4,Y+0.6);
  var fw=doc.getTextWidth(ft); fnt(fa.cambia,7.5,NAVY); doc.text(T(fa.detalle),X+4+fw+2,Y+0.6);
  Y+=8.5;
  fnt(false,9); var tl=doc.splitTextToSize(T(hay?titularTexto(M):'Sin cambios respecto a la HM.'),W-2*X); doc.text(tl,X,Y); Y+=tl.length*4.2+3;
  var kp=[['Total a pagar','total'],['Forma de pago','forma'],['Cuotas','cuotas'],['Fecha 1.ª cuota','fecha']], bw=(W-2*X-3*4)/4;
  kp.forEach(function(k,i){
    var r=filasT.filter(function(x){return x.k===k[1];})[0], bx=X+i*(bw+4), tot=k[1]==='total';
    doc.setFillColor.apply(doc,tot?NAVY:(r.changed?AMBER:CREAM)); doc.roundedRect(bx,Y,bw,18,2,2,'F');
    fnt(false,6.5,tot?CYAN:MUTED); doc.text(T(k[0].toUpperCase()),bx+3,Y+4.6);
    if(r.changed){ fnt(false,7.5,tot?[176,190,200]:MUTED); var tb=T(r.b); ajustar(tb,bw-6,7.5,6); doc.text(tb,bx+3,Y+9); var tw=doc.getTextWidth(tb); doc.setDrawColor.apply(doc,tot?[176,190,200]:MUTED); doc.setLineWidth(0.25); doc.line(bx+3,Y+8.2,bx+3+tw,Y+8.2); }
    fnt(true,tot?12:10.5,tot?[255,255,255]:NAVY); ajustar(T(r.a),bw-6,tot?12:10.5,7.5); doc.text(T(r.a),bx+3,Y+14.8);
  });
  Y+=25;

  seccion('Comparativa');
  var cA=X+5, cB=128, cC=172;
  doc.setFillColor.apply(doc,NAVY); doc.rect(X,Y-4.2,W-2*X,6.6,'F');
  fnt(true,7.5,[255,255,255]); doc.text('CONCEPTO',cA,Y); doc.text('ANTES (HM)',cB,Y,{align:'center'}); doc.text('AHORA',cC,Y,{align:'center'});
  Y+=6.8;
  filasT.forEach(function(r){
    var hh=6.6;
    if(r.changed){ doc.setFillColor.apply(doc,AMBER); doc.rect(X,Y-4.4,W-2*X,hh,'F'); }
    fnt(r.tot,r.tot?9.5:8.5,r.tot?BLUE:NAVY); doc.text(T(r.label),cA,Y);
    fnt(false,r.tot?9.5:8.5,MUTED); doc.text(T(r.b),cB,Y,{align:'center'});
    fnt(r.changed||r.tot,r.tot?9.5:8.5,r.tot?BLUE:NAVY); doc.text(T(r.a),cC,Y,{align:'center'});
    doc.setDrawColor.apply(doc,LINE); doc.setLineWidth(0.2); doc.line(X,Y-4.4+hh,W-X,Y-4.4+hh);
    Y+=hh;
  });
  fnt(false,7,MUTED); doc.text(T('Filas resaltadas: modificadas respecto a la HM. Descuentos: ayudas y otros dtos.'),X,Y+1); Y+=10;

  var obs=$('f-obs').value.trim();
  fnt(false,8.5); var ol=doc.splitTextToSize(T(obs||'—'),W-2*X-8), oh=ol.length*4.1+7;
  if(Y+oh+30>282){ doc.addPage(); Y=20; }
  seccion('Observaciones');
  doc.setDrawColor.apply(doc,LINE); doc.setLineWidth(0.3); doc.roundedRect(X,Y-3,W-2*X,oh,2,2,'S');
  fnt(false,8.5); doc.text(ol,X+4,Y+2.4); Y+=oh+18;

  if(Y>280){ doc.addPage(); Y=40; }
  doc.setDrawColor(154,166,178); doc.setLineWidth(0.3); doc.line(X,Y,X+80,Y); doc.line(W-X-80,Y,W-X,Y);
  fnt(false,8,MUTED); doc.text(T('Asesor: '+(H.asesor||'')),X,Y+4.4); doc.text('Conforme alumno',W-X-80,Y+4.4);

  var pages=doc.getNumberOfPages();
  for(var p=1;p<=pages;p++){ doc.setPage(p); fnt(false,6.5,MUTED); doc.text(T('CFP · '+nombreAlumno()+(H.idOportunidad?' · ID '+H.idOportunidad:'')+' · HM: '+H.archivo),X,290); doc.text(p+' / '+pages,W-X,290,{align:'right'}); }

  return doc;
}
/* ¿Se está viendo como enlace compartido de Claude? Allí las descargas pasan por la plataforma */
function enClaude(){ return !!(window.claude && typeof window.claude.use==='function'); }
async function guardarEnClaude(nombre,blob){
  var d=null; try{ d=await window.claude.use('downloads'); }catch(e){}
  if(!d) return 'no_disponible';
  try{ await d.save({filename:nombre,data:blob}); return 'ok'; }
  catch(e){ return (e&&e.code)||'error'; }
}
async function descargarPDF(){
  var doc=await crearPDF(); if(!doc) return;
  if(enClaude()){
    var r=await guardarEnClaude(nombrePDF(),doc.output('blob'));
    if(r==='ok') toast('PDF descargado: '+nombrePDF());
    else if(r!=='declined') toast('No se pudo descargar el PDF en esta vista.',true);
    return;
  }
  doc.save(nombrePDF());
  toast('PDF descargado: '+nombrePDF());
}

/* ======================= CORREO PARA OUTLOOK (.eml con el PDF adjunto) =======================
   Outlook de escritorio abre el .eml como borrador listo para enviar (cabecera X-Unsent). */
function b64Texto(t){ var b=new TextEncoder().encode(t), s=''; for(var i=0;i<b.length;i+=0x8000) s+=String.fromCharCode.apply(null,b.subarray(i,i+0x8000)); return btoa(s); }
function b64Bytes(buf){ var b=new Uint8Array(buf), s=''; for(var i=0;i<b.length;i+=0x8000) s+=String.fromCharCode.apply(null,b.subarray(i,i+0x8000)); return btoa(s); }
function lineas76(b64){ return b64.replace(/.{1,76}/g,'$&\r\n'); }
function cabecera(t){ return /^[\x20-\x7E]*$/.test(t) ? t : '=?UTF-8?B?'+b64Texto(t)+'?='; }
async function correoOutlook(){
  var para=paraMarca();
  var doc=await crearPDF(); if(!doc) return;
  var pdf=b64Bytes(doc.output('arraybuffer')), nombre=nombrePDF(), cc='';
  var html='<!DOCTYPE html><html><head><meta charset="utf-8"></head><body>'+correoHTML(true)+'</body></html>';
  var B1='==CFP_mixed_'+Date.now(), B2='==CFP_alt_'+Date.now();
  var eml=[
    'To: '+para, cc?'Cc: '+cc:null, 'Subject: '+cabecera(asunto()), 'X-Unsent: 1', 'MIME-Version: 1.0',
    'Content-Type: multipart/mixed; boundary="'+B1+'"', '',
    '--'+B1, 'Content-Type: multipart/alternative; boundary="'+B2+'"', '',
    '--'+B2, 'Content-Type: text/plain; charset="utf-8"', 'Content-Transfer-Encoding: base64', '', lineas76(b64Texto(cuerpoCorreo())),
    '--'+B2, 'Content-Type: text/html; charset="utf-8"', 'Content-Transfer-Encoding: base64', '', lineas76(b64Texto(html)),
    '--'+B2+'--', '',
    '--'+B1, 'Content-Type: application/pdf; name="'+nombre+'"', 'Content-Disposition: attachment; filename="'+nombre+'"', 'Content-Transfer-Encoding: base64', '', lineas76(pdf),
    '--'+B1+'--', ''
  ].filter(function(x){return x!==null;}).join('\r\n');
  var a=document.createElement('a'); a.href=URL.createObjectURL(new Blob([eml],{type:'message/rfc822'}));
  a.download=nombre.replace(/\.pdf$/,'.eml'); document.body.appendChild(a); a.click(); a.remove();
  setTimeout(function(){ URL.revokeObjectURL(a.href); },4000);
  toast('Correo listo con el PDF adjunto: ábrelo y Outlook lo mostrará para enviar.',false,6000);
}

/* ======================= ENLACE EXTERNO ======================= */
function esExterno(){ return /^#externo$/i.test(location.hash) || /[?&]externo\b/i.test(location.search); }
function copiarEnlaceExterno(){
  if(location.protocol==='file:'){ toast('Abre la página desde GitHub para tener un enlace que compartir.',true); return; }
  /* El enlace lleva la marca seleccionada y queda bloqueado a ella: quien lo abre no ve la otra marca */
  var url=location.origin+location.pathname+'?marca='+MARCA+'#externo';
  var ok=function(){ toast('Enlace externo de '+MARCA+' copiado: solo muestra '+MARCAS[MARCA].nombre+'.',false,5000); };
  var manual=function(){ var ta=document.createElement('textarea'); ta.value=url; ta.style.cssText='position:fixed;opacity:0'; document.body.appendChild(ta); ta.select(); var r=false; try{ r=document.execCommand('copy'); }catch(e){} ta.remove(); r?ok():toast('No se pudo copiar. Enlace: '+url,true); };
  if(navigator.clipboard && window.isSecureContext) navigator.clipboard.writeText(url).then(ok).catch(manual); else manual();
}
function enModal(){ try{ return window.self!==window.top && !enClaude(); }catch(e){ return true; } }
function setMarca(m){
  if(!MARCAS[m]) return;
  MARCA=m; document.body.dataset.marca=m;
  $('marcaTxt').textContent=MARCAS[m].nombre;
  $('btnLink').title='Copiar el enlace externo de '+m+' (solo muestra '+MARCAS[m].nombre+')';
  $('btnLink').querySelector('span').textContent='Enlace externo '+m;
  document.querySelectorAll('.marcas button').forEach(function(b){ b.setAttribute('aria-pressed',b.dataset.m===m?'true':'false'); });
  try{ localStorage.setItem('cfp_marca',m); }catch(e){}
}
function marcaInicial(){
  var q=/[?&]marca=(OBS|ESD)\b/i.exec(location.search); if(q) return q[1].toUpperCase();
  try{ var g=localStorage.getItem('cfp_marca'); if(MARCAS[g]) return g; }catch(e){}
  return 'OBS';
}
document.querySelectorAll('.marcas button').forEach(function(b){ b.onclick=function(){
  setMarca(b.dataset.m);
  if(H && H.marca && H.marca!==MARCA) toast('Atención: la HM cargada es de '+H.marca+'.',true);
  if(H) render();
}; });
function bloqueada(){ return esExterno() && /[?&]marca=(OBS|ESD)\b/i.test(location.search); }
function aplicarModo(){ document.body.classList.toggle('bloq',bloqueada()); document.body.classList.toggle('ext',esExterno()); document.body.classList.toggle('vclaude',enClaude()); document.body.classList.toggle('enmodal',enModal()); }
window.addEventListener('hashchange',aplicarModo);
/* Dentro del modal del hub: Esc pide al hub que cierre el modal */
document.addEventListener('keydown',function(e){ if(e.key==='Escape' && enModal()){ try{ window.parent.postMessage({cfp:'cerrar'},location.origin); }catch(err){} } });
function nombrePDF(){
  var b=[H.nombre,H.apellidos].filter(Boolean).join('_')+(H.idOportunidad?'_'+H.idOportunidad:'');
  b=b.normalize('NFD').replace(/[̀-ͯ]/g,'').replace(/[^A-Za-z0-9]+/g,'_').replace(/^_|_$/g,'');
  return 'CFP_'+(b||'HM')+'.pdf';
}

/* ======================= COPIAR / CORREO / LIMPIAR ======================= */
function copiar(){
  if(!H){ toast('Carga una HM antes de copiar el resumen.',true); return; }
  copiarRico(correoHTML(false),resumenTexto()).then(function(ok){ toast(ok?'Resumen copiado con formato':'No se pudo copiar el resumen.',!ok); });
}
/* Texto del correo para el enlace mailto: completo pero compacto (Outlook limita la longitud del enlace) */
function cuerpoMailto(conFrase){
  var fr=filasResumen(false), obs=$('f-obs').value.trim();
  return ['Buenos días,','',
    'Por favor, solicitamos gestionar el CFP de '+nombreAlumno()+(H.idOportunidad?' (ID '+H.idOportunidad+')':'')+' con el siguiente detalle:',
    H.email?'Email del alumno: '+H.email:'', '',
    fr.length?factTexto():'Sin cambios respecto a la HM.',
    fr.length&&conFrase?titularTexto(R.M):'', '',
    fr.length?'Cambios (antes → ahora):':'',
    fr.map(function(r){ return '- '+r.label+': '+r.b+' → '+r.a; }).join('\n'), '',
    obs?'Observaciones: '+obs:'', '',
    'Adjuntamos el PDF con el detalle.','','Muchas gracias.','Un saludo,'].join('\n').replace(/\n{3,}/g,'\n\n').trim();
}
function enviar(){
  if(!H){ toast('Carga una HM antes de enviar.',true); return; }
  if(aviso().err){ toast('Revisa la fecha de primera cuota antes de enviar.',true); return; }
  /* En el hub / GitHub: correo de Outlook con formato y el PDF ya adjunto (.eml).
     En el enlace compartido de Claude ese formato no se puede descargar: se abre el correo en texto. */
  if(!enClaude()){ correoOutlook(); return; }
  var base='mailto:'+encodeURIComponent(paraMarca())+'?subject='+encodeURIComponent(asunto());
  var url=base+'&body='+encodeURIComponent(cuerpoMailto(true));
  if(url.length>1900) url=base+'&body='+encodeURIComponent(cuerpoMailto(false));
  var abrir=function(u){ if(enClaude()||enModal()){ var a=document.createElement('a'); a.href=u; a.target=enModal()?'_top':'_blank'; a.rel='noopener'; document.body.appendChild(a); a.click(); a.remove(); } else location.href=u; };
  /* Además se copia la versión con formato (recuadros), por si se prefiere pegarla encima */
  copiarRico(correoHTML(true),cuerpoCorreo()).then(function(ok){
    abrir(url);
    toast(ok ? 'Correo abierto con el detalle. Adjunta el PDF. Si lo quieres con formato: en el cuerpo, Ctrl+A y Ctrl+V.' : 'Correo abierto con el detalle. Adjunta el PDF.', false, 7000);
  });
}
/* Reset completo: quita la HM, los cambios, las observaciones y vuelve al inicio */
function limpiar(){ H=null; S=null; S0=null; R=null; $('file').value=''; resetObs(); todo(); window.scrollTo({top:0,behavior:'smooth'}); if(!enModal() && !bloqueada()) abrirChooser(); else toast('Reiniciado: listo para otra HM'); }

/* ======================= EVENTOS ======================= */
var drop=$('drop');
['dragenter','dragover'].forEach(function(ev){ document.addEventListener(ev,function(e){ e.preventDefault(); drop.classList.add('over'); }); });
['dragleave','drop'].forEach(function(ev){ document.addEventListener(ev,function(e){ e.preventDefault(); if(ev==='drop'||!e.relatedTarget) drop.classList.remove('over'); }); });
document.addEventListener('drop',function(e){ var f=e.dataTransfer&&e.dataTransfer.files[0]; if(f) cargar(f); });
$('btnFile').onclick=function(){ $('file').click(); };
$('file').onchange=function(e){ var f=e.target.files[0]; if(f) cargar(f); e.target.value=''; };
$('btnEjemplo').onclick=ejemplo;
$('btnLimpiar').onclick=limpiar;
$('btnPdf').onclick=descargarPDF;
$('btnMail').onclick=enviar;
$('btnLink').onclick=copiarEnlaceExterno;
aplicarModo();
/* Observaciones: el cuadro de texto solo aparece al pulsar «Añadir» o si ya hay texto */
function obsAbierta(){ return !$('obsBox').classList.contains('hidden'); }
function pintarObs(){
  var t=$('f-obs').value.trim(), ab=obsAbierta();
  $('btnObs').setAttribute('aria-expanded',ab?'true':'false');
  $('btnObs').querySelector('span').textContent=ab?'Ocultar':(t?'Editar':'Añadir');
  $('btnObs').querySelector('use').setAttribute('href',ab?'#i-x':(t?'#i-edit':'#i-plus'));
  $('obsPrev').classList.toggle('hidden',ab||!t); $('obsPrev').textContent=t;
}
function resetObs(){ $('f-obs').value=''; $('obsBox').classList.add('hidden'); pintarObs(); }
$('btnObs').onclick=function(){ var ab=!obsAbierta(); $('obsBox').classList.toggle('hidden',!ab); pintarObs(); if(ab) $('f-obs').focus(); };
$('f-obs').addEventListener('input',function(){ pintarObs(); if(H) render(); });
pintarObs();

function dtoDesdePct(){ S.dtoImp=r2(baseContado()*num(S.dtoPct)/100).toFixed(2); $('f-dtoi').value=S.dtoImp; }
$('mod').addEventListener('input',function(e){
  if(!H) return; var t=e.target;
  if(t.id==='f-desc'){ S.desc=t.value; }
  else if(t.id==='f-dtop'){ S.dtoPct=t.value; dtoDesdePct(); }
  else if(t.id==='f-dtoi'){ S.dtoImp=t.value; var b=baseContado(); if(b>0){ S.dtoPct=String(r2(num(t.value)/b*100)); $('f-dtop').value=S.dtoPct; } }
  else if(t.id==='f-insc') S.inscImp=t.value;
  else if(t.id==='f-fecha') S.fecha=t.value;
  else if(t.id==='f-cuotas') S.cuotas=t.value;
  else return;
  render();
});
function aplicarDto(v){
  S.dtoAplica=v; $('f-dtoa').value=v;
  if(v==='aplicar' && num(S.dtoImp)<=0){ if(!num(S.dtoPct)) S.dtoPct=String(DTO_CONTADO_DEFECTO); $('f-dtop').value=S.dtoPct; dtoDesdePct(); }
  render();
}
$('mod').addEventListener('change',function(e){
  if(!H) return; var t=e.target;
  if(t.id==='f-dtoa') aplicarDto(t.value);
  else if(t.id==='f-forma'){ S.forma=t.value; render(); }
});
$('mod').addEventListener('click',function(e){
  var b=e.target.closest('#btnAviso');
  if(H && b) aplicarDto(b.dataset.act==='quitar'?'quitar':'aplicar');
});

setMarca(marcaInicial());
/* Si el módulo no llega con la marca elegida (?marca=OBS|ESD), se pregunta al abrir, como en la calculadora */
function marcaEnEnlace(){ return /[?&]marca=(OBS|ESD)\b/i.test(location.search); }
function abrirChooser(){
  $('chooser').classList.remove('hidden'); document.body.style.overflow='hidden';
  var b=document.querySelector('.ch-opt[data-m="'+MARCA+'"]'); if(b) b.focus();
}
function cerrarChooser(){ $('chooser').classList.add('hidden'); document.body.style.overflow=''; }
document.querySelectorAll('.ch-opt').forEach(function(b){ b.onclick=function(){ setMarca(b.dataset.m); cerrarChooser(); if(H) render(); }; });
document.addEventListener('DOMContentLoaded',function(){ try{ $('chLogoOBS').src=LOGO_HM; $('chLogoESD').src=LOGO_ESD; }catch(e){} });
if(!marcaEnEnlace()) abrirChooser();
todo();
})();
</script>
<script>
/* Logo de la cabecera de la HM, usado en el PDF */
var LOGO_HM='data:image/png;base64,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';
/* Logo de ESDesign (cabecera de la HM de ESD), usado en el PDF */
var LOGO_ESD='data:image/png;base64,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';
/* Poppins (SIL Open Font License), reducida a los caracteres latinos que usa el PDF */
var FONT_PDF_R='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AQsAAAEqAFgCmQBBAmwALAIZAD8CUwAZASMAZAI/AC4BOgAXAxgAMQHCACEBzQAtAooAKQInADoB/QA0AYMAEQGaABwCrgBYAUoAHgFMABcA9wARAoUATQJUAB8A1AAvARAAEQDEABkBtAAhAc0AMgKAACYCowAkAsUAIwIHAC4CogAhAqIAIQKiACECogAhAqIAIQKiACEDhAAMAwQAKwIBAE0CAQBNAgEATQIBAE0A9gAHAPYABwD2//AA9v/1AtUACQK/AE0DEgArAxIAKwMSACsDEgArAxIAKwKDAGcDEgAjAqMASwKjAEsCowBLAqMASwJIABMCQwBNAqkAPAKkACsCpAArAqQAKwKkACsCpAArAqQAKwRJACsCXwArAmwAKwJsACsCbAArAmwAKwD2AAcA9gAHAPb/8AD2//UCfgArAoAATQKAACsCgAArAoAAKwKAACsCgAArApEATgKAACYCgABIAoAASAKAAEgCgABIAjMADAKkAE0CMwAMAPYATQE3ABEA8wAPAVkAEQKlAEwDdQBMANsAGADbACABfAAYAXwAIAJFACwDKwAZAicATAABAAAEGv6iAGQJ7f3t+W4KBwABAAAAAAAAAAAAAAAAAAAAzQAEA1MBkAAFAAACigJYAAAASwKKAlgAAAFeADIBSAAAAAAFAAAAAAAAAAAAAAMAAAAAAAAAAAAAAABJVEZPAMAAICISBBr+ogBkBG8CcwAAAAEAAAAAAiQCugAAACAABAAAAAIAAAADAAAAFAADAAEAAAAUAAQAWAAAABIAEAADAAIAfgD/IBQgGSAdICYgrCIS//8AAAAgAKAgEyAYIBwgJiCsIhL////h/8DgseCu4KzgpOAf3roAAQAAAAAAAAAAAAAAAAAAAAAAAAAAAA0AogADAAEECQAAAKIAAAADAAEECQABAA4AogADAAEECQACAA4AsAADAAEECQADADwAvgADAAEECQAEAB4A+gADAAEECQAFAAoBGAADAAEECQAGAB4BIgADAAEECQAIACYBQAADAAEECQAJAFwBZgADAAEECQALADoBwgADAAEECQANASIB/AADAAEECQAOADYDHgADAAEECQATAK4DVABDAG8AcAB5AHIAaQBnAGgAdAAgADIAMAAyADAAIABUAGgAZQAgAFAAbwBwAHAAaQBuAHMAIABQAHIAbwBqAGUAYwB0ACAAQQB1AHQAaABvAHIAcwAgACgAaAB0AHQAcABzADoALwAvAGcAaQB0AGgAdQBiAC4AYwBvAG0ALwBpAHQAZgBvAHUAbgBkAHIAeQAvAFAAbwBwAHAAaQBuAHMAKQBQAG8AcABwAGkAbgBzAFIAZQBnAHUAbABhAHIASQBUAEYATwA7ACAAUABvAHAAcABpAG4AcwAgAFIAZQBnAHUAbABhAHIAOwAgADQALgAwADAANABiADgAUABvAHAAcABpAG4AcwAgAFIAZQBnAHUAbABhAHIANAAuADAAMAA0AFAAbwBwAHAAaQBuAHMALQBSAGUAZwB1AGwAYQByAEkAbgBkAGkAYQBuACAAVAB5AHAAZQAgAEYAbwB1AG4AZAByAHkATgBpAG4AYQBkACAASwBhAGwAZQAgACgARABlAHYAYQBuAGEAZwBhAHIAaQApACwAIABKAG8AbgBuAHkAIABQAGkAbgBoAG8AcgBuACAAKABMAGEAdABpAG4AKQBoAHQAdABwAHMAOgAvAC8AaQBuAGQAaQBhAG4AdAB5AHAAZQBmAG8AdQBuAGQAcgB5AC4AYwBvAG0AVABoAGkAcwAgAEYAbwBuAHQAIABTAG8AZgB0AHcAYQByAGUAIABpAHMAIABsAGkAYwBlAG4AcwBlAGQAIAB1AG4AZABlAHIAIAB0AGgAZQAgAFMASQBMACAATwBwAGUAbgAgAEYAbwBuAHQAIABMAGkAYwBlAG4AcwBlACwAIABWAGUAcgBzAGkAbwBuACAAMQAuADEALgAgAFQAaABpAHMAIABsAGkAYwBlAG4AcwBlACAAaQBzACAAYQB2AGEAaQBsAGEAYgBsAGUAIAB3AGkAdABoACAAYQAgAEYAQQBRACAAYQB0ADoAIABoAHQAdABwAHMAOgAvAC8AcwBjAHIAaQBwAHQAcwAuAHMAaQBsAC4AbwByAGcALwBPAEYATABoAHQAdABwAHMAOgAvAC8AcwBjAHIAaQBwAHQAcwAuAHMAaQBsAC4AbwByAGcALwBPAEYATAk4CS0JQAAgCS4JKAlBCTcJTQkvCUsJAgAgCRUJSwAgCRcJTAkwCTUAIAkUCTAAIAkFCScJPwkVCT4JMAlLCQIAIAkVCUcAIAkuCT4JLgkyCUcAIAkuCUcJAgAgCRwJKAlNCS4JHAk+CSQAIAk4CU0JNQkkCSgJTQkkCU0JMAkkCT4AIAkUCTAAIAk4CS4JPgkoCSQJPgAgCSoJTQkwCT4JKglNCSQAIAk5CUgJZAADAAAAAAAA/7UAMgAAAAAAAAAAAAAAAAAAAAAAAAAAAAEAAAAKABwAHgABREZMVAAIAAQAAAAA//8AAAAAAAAAAQAAAAoALAAuAANERkxUABRkZXYyAB5kZXZhAB4ABAAAAAD//wAAAAAAAAAAAAA=';
var FONT_PDF_B='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AGwAZQAgACgARABlAHYAYQBuAGEAZwBhAHIAaQApACwAIABKAG8AbgBuAHkAIABQAGkAbgBoAG8AcgBuACAAKABMAGEAdABpAG4AKQBoAHQAdABwAHMAOgAvAC8AaQBuAGQAaQBhAG4AdAB5AHAAZQBmAG8AdQBuAGQAcgB5AC4AYwBvAG0AVABoAGkAcwAgAEYAbwBuAHQAIABTAG8AZgB0AHcAYQByAGUAIABpAHMAIABsAGkAYwBlAG4AcwBlAGQAIAB1AG4AZABlAHIAIAB0AGgAZQAgAFMASQBMACAATwBwAGUAbgAgAEYAbwBuAHQAIABMAGkAYwBlAG4AcwBlACwAIABWAGUAcgBzAGkAbwBuACAAMQAuADEALgAgAFQAaABpAHMAIABsAGkAYwBlAG4AcwBlACAAaQBzACAAYQB2AGEAaQBsAGEAYgBsAGUAIAB3AGkAdABoACAAYQAgAEYAQQBRACAAYQB0ADoAIABoAHQAdABwAHMAOgAvAC8AcwBjAHIAaQBwAHQAcwAuAHMAaQBsAC4AbwByAGcALwBPAEYATABoAHQAdABwAHMAOgAvAC8AcwBjAHIAaQBwAHQAcwAuAHMAaQBsAC4AbwByAGcALwBPAEYATAk4CS0JQAAgCS4JKAlBCTcJTQkvCUsJAgAgCRUJSwAgCRcJTAkwCTUAIAkUCTAAIAkFCScJPwkVCT4JMAlLCQIAIAkVCUcAIAkuCT4JLgkyCUcAIAkuCUcJAgAgCRwJKAlNCS4JHAk+CSQAIAk4CU0JNQkkCSgJTQkkCU0JMAkkCT4AIAkUCTAAIAk4CS4JPgkoCSQJPgAgCSoJTQkwCT4JKglNCSQAIAk5CUgJZAADAAAAAAAA/7UAMgAAAAAAAAAAAAAAAAAAAAAAAAAAAAEAAAAKABwAHgABREZMVAAIAAQAAAAA//8AAAAAAAAAAQAAAAoALAAuAANERkxUABRkZXYyAB5kZXZhAB4ABAAAAAD//wAAAAAAAAAAAAA=';
</script>
</body>
</html>
