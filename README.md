<html lang="ru">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width,initial-scale=1,viewport-fit=cover">
<meta name="theme-color" content="#f4a7c4">
<title>Мой Бьюти-дневник ♡</title>
<style>
:root{
  --bg:#fff9fb;--surface:#ffffff;--surface2:#fff1f6;--text:#3f3940;--muted:#8f858e;
  --primary:#e889ad;--primary2:#f7c2d6;--accent:#caa8e8;--success:#8ecdb8;--danger:#dd8c8c;
  --border:rgba(74,55,66,.10);--shadow:0 14px 40px rgba(91,52,72,.09);--radius:24px;
}
/* Custom pastel scrollbars — thin, rounded, tinted to match the active theme, thickens on hover. */
*{scrollbar-width:thin;scrollbar-color:var(--primary2) transparent}
::-webkit-scrollbar{width:10px;height:10px}
::-webkit-scrollbar-track{background:transparent}
::-webkit-scrollbar-thumb{background-color:var(--primary2);background-image:linear-gradient(180deg,var(--primary2),var(--accent));border-radius:99px;border:3px solid transparent;background-clip:padding-box;transition:border-width .15s ease,background-image .2s ease}
::-webkit-scrollbar-thumb:hover{background-image:linear-gradient(180deg,var(--primary),var(--accent));border-width:2px}
::-webkit-scrollbar-thumb:active{background-image:linear-gradient(180deg,var(--primary),var(--primary))}
::-webkit-scrollbar-corner{background:transparent}
*{box-sizing:border-box}html,body{margin:0;padding:0;background:linear-gradient(180deg,var(--bg),var(--surface));color:var(--text);font-family:Inter,ui-sans-serif,system-ui,-apple-system,BlinkMacSystemFont,"Segoe UI",sans-serif}
button,input,select,textarea{font:inherit}button{cursor:pointer;border:0}.hidden{display:none!important}.muted{color:var(--muted)}
.app{min-height:100vh;display:grid;grid-template-columns:250px 1fr}.sidebar{position:sticky;top:0;height:100vh;padding:22px 14px;border-right:1px solid var(--border);background:color-mix(in srgb,var(--surface) 78%,transparent);backdrop-filter:blur(16px);display:flex;flex-direction:column;gap:14px}
.brand{padding:10px 12px 14px}.brand h1{font-family:Georgia,serif;margin:0;font-size:24px}.brand p{margin:7px 0 0;color:var(--muted);font-size:12px}.nav{display:flex;flex-direction:column;gap:6px;overflow-y:auto;overflow-x:visible;padding-right:2px;padding-left:6px}.nav button{background:transparent;color:var(--muted);padding:11px 12px;border-radius:15px;text-align:left;display:flex;align-items:center;gap:10px;height:44px}.nav button:hover,.nav button.active{background:var(--surface2);color:var(--text)}.nav button::before{content:"";position:absolute;left:-1.2px;top:-0.6px;height:22px;width:27px;border-style:solid;border-color:color-mix(in srgb,var(--primary) 82%,var(--accent) 18%);border-left-width:5.5px;border-top-width:1.6px;border-bottom:none;border-radius:15.8px 0 0 0;background:transparent;z-index:-1;opacity:0;transform:scaleY(.88);transform-origin:bottom;-webkit-mask-image:linear-gradient(to right,black 30%,rgba(0,0,0,.55) 58%,rgba(0,0,0,.18) 80%,transparent 98%);mask-image:linear-gradient(to right,black 30%,rgba(0,0,0,.55) 58%,rgba(0,0,0,.18) 80%,transparent 98%);box-shadow:0 0 1px 0 color-mix(in srgb,var(--primary) 70%,transparent),0 0 5px 0 color-mix(in srgb,var(--primary) 32%,transparent),0 0 14px 1px color-mix(in srgb,var(--accent) 22%,transparent);transition:opacity .28s ease,transform .28s cubic-bezier(.34,1.56,.64,1)}
.nav button::after{content:"";position:absolute;left:-1.2px;bottom:-0.6px;height:22px;width:36px;border-style:solid;border-color:color-mix(in srgb,var(--primary) 82%,var(--accent) 18%);border-left-width:5.5px;border-bottom-width:1.6px;border-top:none;border-radius:0 0 0 15.8px;background:transparent;z-index:-1;opacity:0;transform:scaleY(.88);transform-origin:top;-webkit-mask-image:linear-gradient(to right,black 42%,rgba(0,0,0,.55) 65%,rgba(0,0,0,.18) 85%,transparent 99%);mask-image:linear-gradient(to right,black 42%,rgba(0,0,0,.55) 65%,rgba(0,0,0,.18) 85%,transparent 99%);box-shadow:0 0 1px 0 color-mix(in srgb,var(--primary) 70%,transparent),0 0 5px 0 color-mix(in srgb,var(--primary) 32%,transparent),0 0 14px 1px color-mix(in srgb,var(--accent) 22%,transparent);transition:opacity .28s ease,transform .28s cubic-bezier(.34,1.56,.64,1)}
.nav button.active::before,.nav button.active::after{opacity:.9;transform:scaleY(1)}
.nav button.active{box-shadow:none}.nav button{position:relative;user-select:none;transition:transform .16s ease,opacity .16s ease,background .16s ease}.nav button[draggable='true']{cursor:grab}.nav button[draggable='true']:active{cursor:grabbing}.nav button.dragging{opacity:.45;transform:scale(.98)}.nav button.drag-over{outline:2px dashed var(--primary);outline-offset:2px;background:var(--surface2)}.nav button .nav-drag-handle{margin-left:auto;opacity:.38;font-size:14px;pointer-events:none}.nav button{position:relative;user-select:none;transition:transform .16s ease,opacity .16s ease,background .16s ease}.nav button[draggable="true"]{cursor:grab}.nav button[draggable="true"]:active{cursor:grabbing}.nav button.dragging{opacity:.45;transform:scale(.98)}.nav button.drag-over{outline:2px dashed var(--primary);outline-offset:2px;background:var(--surface2)}.nav button .nav-drag-handle{margin-left:auto;opacity:.38;font-size:14px;letter-spacing:-2px;pointer-events:none}.nav button:hover .nav-drag-handle,.nav button.active .nav-drag-handle{opacity:.7}.sidebar-bottom{margin-top:auto}.main{min-width:0}.topbar{position:sticky;top:0;z-index:20;display:flex;align-items:center;justify-content:space-between;padding:16px 22px;background:color-mix(in srgb,var(--surface) 72%,transparent);backdrop-filter:blur(14px);border-bottom:1px solid var(--border)}.topbar-title{display:flex;align-items:center;gap:10px}.topbar-title h2{font-size:20px;margin:0}.icon-btn{width:42px;height:42px;border-radius:14px;background:var(--surface);border:1px solid var(--border);box-shadow:var(--shadow)}.content{padding:22px;max-width:1500px;margin:auto}.grid{display:grid;gap:16px}.grid-4{grid-template-columns:repeat(4,minmax(0,1fr))}.grid-3{grid-template-columns:repeat(3,minmax(0,1fr))}.grid-2{grid-template-columns:repeat(2,minmax(0,1fr))}.card{background:var(--surface);border:1px solid var(--border);border-radius:var(--radius);box-shadow:var(--shadow);padding:18px}.hero{padding:24px;background:linear-gradient(135deg,var(--surface),var(--surface2));position:relative;overflow:hidden}.hero:after{content:"♡";position:absolute;right:24px;top:14px;font-size:56px;opacity:.11}.hero h1{font-family:Georgia,serif;margin:0 0 4px;font-size:34px}.hero p{margin:0;color:var(--muted)}.row{display:flex;align-items:center;gap:10px}.between{justify-content:space-between}.wrap{flex-wrap:wrap}.btn{padding:11px 15px;border-radius:15px;background:var(--primary);color:#fff;box-shadow:0 8px 18px rgba(232,137,173,.22)}.btn.secondary{background:var(--surface2);color:var(--text);box-shadow:none}.btn.ghost{background:transparent;color:var(--text);box-shadow:none;border:1px solid var(--border)}.btn.danger{background:var(--danger)}.btn.small{padding:8px 11px;border-radius:12px;font-size:13px}.stat{padding:16px;border-radius:20px;background:var(--surface2)}.stat b{display:block;font-size:25px;margin-top:4px}.label{font-size:12px;color:var(--muted);text-transform:uppercase;letter-spacing:.08em}.progress{height:10px;border-radius:99px;background:#f2e6eb;overflow:hidden}.progress>i{display:block;height:100%;border-radius:inherit;background:linear-gradient(90deg,var(--primary),var(--accent));transition:width .4s ease}.circle{width:138px;height:138px;border-radius:50%;display:grid;place-items:center;background:conic-gradient(var(--primary) calc(var(--p)*1%),#f2e9ee 0);position:relative;flex:0 0 auto}.circle:after{content:"";position:absolute;inset:10px;border-radius:50%;background:var(--surface)}.circle .inside{position:relative;z-index:1;text-align:center}.circle strong{display:block;font-size:30px}.small-circle{width:88px;height:88px}.small-circle .inside strong{font-size:20px}.section-title{font-size:20px;margin:0 0 12px;font-family:Georgia,serif}.subtle{font-size:13px;color:var(--muted)}.task-list{display:grid;gap:10px}.task{padding:13px;border:1px solid var(--border);border-radius:18px;display:flex;align-items:center;gap:12px;background:var(--surface2)}.task.done{background:color-mix(in srgb,var(--success) 18%,var(--surface2))}.check{width:32px;height:32px;border-radius:10px;border:1px solid var(--border);display:grid;place-items:center;background:var(--surface);flex:0 0 auto}.check.done{background:var(--success);color:#fff}.tag{display:inline-flex;align-items:center;gap:6px;padding:6px 10px;border-radius:999px;background:var(--surface2);font-size:12px}.kbd{font-family:ui-monospace;font-size:11px;padding:4px 7px;border-radius:7px;background:#f4eef1}.list{display:grid;gap:10px}.item{padding:14px;border:1px solid var(--border);border-radius:18px}.item h4{margin:0 0 5px}.item p{margin:0;color:var(--muted);font-size:13px;line-height:1.5}.empty{padding:28px;text-align:center;border:1px dashed var(--border);border-radius:20px;color:var(--muted)}.form{display:grid;gap:12px}.field{min-width:0}.field label{display:block;font-size:12px;color:var(--muted);margin-bottom:6px}.field input,.field select,.field textarea{width:100%;max-width:100%;min-width:0;box-sizing:border-box;padding:12px 13px;border-radius:14px;border:1px solid var(--border);background:#fff;color:var(--text);outline:none}.field textarea{min-height:96px;resize:vertical}.modal-backdrop{position:fixed;inset:0;background:rgba(47,32,43,.34);display:grid;place-items:center;padding:18px;z-index:100}.modal{width:min(680px,100%);max-height:88vh;overflow:auto;background:var(--surface);border-radius:26px;padding:20px;box-shadow:0 24px 80px rgba(24,13,20,.25)}.modal h3{font-family:Georgia,serif;margin:0 0 12px;font-size:22px}.modal-actions{display:flex;justify-content:flex-end;gap:10px;margin-top:14px}.pet{font-size:76px;line-height:1}.pet-stage{font-family:Georgia,serif;font-size:21px}.mood{padding:8px 10px;border-radius:999px;background:#f9eef4}.achievement{min-height:170px;position:relative;overflow:hidden}.achievement.locked{filter:grayscale(1);opacity:.55}.achievement.unlocked{background:linear-gradient(135deg,color-mix(in srgb,var(--surface) 88%,#fff),var(--surface2))}.achievement .icon{font-size:34px}.achievement .lock{position:absolute;right:14px;top:14px}.challenge.done{background:#f0fbf7}.calendar{display:grid;grid-template-columns:repeat(7,1fr);gap:7px}.cal-head{font-size:11px;color:var(--muted);text-align:center;padding:7px 0}.cal-day{min-height:84px;padding:8px;border:1px solid var(--border);border-radius:13px;background:var(--surface);color:var(--text)}.cal-day .d{color:var(--text);font-weight:600}.cal-day:visited,.cal-day:hover{color:var(--text)}.cal-day.dim{opacity:.35}.cal-day.today{outline:2px solid var(--primary2)}.cal-day .d{font-size:12px}.cal-day .meter{margin-top:18px;height:7px;border-radius:99px;background:#f1e6ec;overflow:hidden}.cal-day .meter i{display:block;height:100%;background:linear-gradient(90deg,var(--primary),var(--accent))}.article{cursor:pointer}.article:hover{transform:translateY(-2px)}.article{transition:transform .2s ease}.photo-grid{display:grid;grid-template-columns:repeat(3,minmax(0,1fr));gap:12px}.photo-card{border:1px solid var(--border);border-radius:18px;overflow:hidden;background:#fff}.photo-card img{width:100%;height:180px;object-fit:cover;display:block}.photo-card .body{padding:11px}.bar-row{display:grid;grid-template-columns:100px 1fr 44px;gap:8px;align-items:center;margin:8px 0}.toast-stack{position:fixed;right:18px;bottom:18px;z-index:200;display:grid;gap:10px}.toast{padding:13px 16px;border-radius:15px;background:#2f2830;color:#fff;box-shadow:0 15px 35px rgba(0,0,0,.15)}.bottom-nav{display:none}.mobile-more{display:none}.split{display:flex;gap:16px;align-items:stretch}.split>.card{flex:1}.kpi{font-size:30px;font-weight:700}.rainbow{background:linear-gradient(90deg,var(--primary),var(--accent),var(--success));-webkit-background-clip:text;background-clip:text;color:transparent}.timeline{position:relative;padding-left:22px}.timeline:before{content:"";position:absolute;left:7px;top:4px;bottom:4px;width:2px;background:var(--primary2)}.timeline-item{position:relative;padding:0 0 18px}.timeline-item:before{content:"";position:absolute;left:-20px;top:4px;width:12px;height:12px;border-radius:50%;background:var(--primary);border:3px solid #fff}.chip-tabs{display:flex;gap:8px;flex-wrap:wrap}.chip-tabs button{background:var(--surface);border:1px solid var(--border);padding:8px 11px;border-radius:999px;color:var(--muted)}.chip-tabs button.active{background:var(--surface2);color:var(--text);border-color:var(--primary2)}
@media(max-width:1000px){.app{grid-template-columns:1fr}.sidebar{display:none}.bottom-nav{display:flex;position:fixed;left:10px;right:10px;bottom:10px;z-index:40;background:color-mix(in srgb,var(--surface) 90%,transparent);backdrop-filter:blur(16px);border:1px solid var(--border);border-radius:20px;box-shadow:var(--shadow);padding:7px}.bottom-nav button{flex:1;background:transparent;color:var(--muted);padding:8px 4px;border-radius:14px;font-size:11px}.bottom-nav button.active{background:var(--surface2);color:var(--text)}.content{padding-bottom:90px}.grid-4{grid-template-columns:repeat(2,minmax(0,1fr))}.grid-3{grid-template-columns:1fr}.split{flex-direction:column}}
@media(max-width:640px){.content{padding:14px}.topbar{padding:12px 14px}.hero h1{font-size:28px}.grid-2,.grid-4{grid-template-columns:1fr}.circle{width:118px;height:118px}.photo-grid{grid-template-columns:repeat(2,minmax(0,1fr))}.photo-card img{height:150px}.calendar{gap:4px}.cal-day{min-height:62px;padding:5px}.cal-day .meter{margin-top:10px}.bar-row{grid-template-columns:80px 1fr 40px}}

/* Fantasy avatar frame collection — shop only */
body [data-avatar][data-frame="vampire"]{border:3px solid #8d102d!important;box-shadow:0 0 0 4px #1b0810,0 0 28px rgba(170,20,55,.7)!important}
body [data-avatar][data-frame="fairy"]{border:3px solid #9adf8b!important;box-shadow:0 0 0 4px #e8f8d9,0 0 24px rgba(92,190,105,.55)!important}
body [data-avatar][data-frame="goblincore"]{border:3px solid #477b38!important;box-shadow:0 0 0 4px #dcebc9,0 0 25px rgba(58,120,48,.6)!important}
body [data-avatar][data-frame="zombie"]{border:3px solid #6d8051!important;box-shadow:0 0 0 4px #252d1d,0 0 25px rgba(117,145,75,.65)!important}
body [data-avatar][data-frame="mermaid"]{border:3px solid #52c9cf!important;box-shadow:0 0 0 4px #d8f7f4,0 0 25px rgba(55,194,210,.6)!important}
body [data-avatar][data-frame="angel"]{border:3px solid #eee5ff!important;box-shadow:0 0 0 4px #fff,0 0 30px rgba(210,200,255,.9)!important}
body [data-avatar][data-frame="witch"]{border:3px solid #713f9e!important;box-shadow:0 0 0 4px #21112d,0 0 27px rgba(115,57,170,.7)!important}
body [data-avatar][data-frame="mushroom"]{border:3px solid #b86b46!important;box-shadow:0 0 0 4px #f2dfc9,0 0 24px rgba(160,95,60,.55)!important}
body [data-avatar][data-frame="vampire"]::before{content:"🕷️"!important} body [data-avatar][data-frame="vampire"]::after{content:"🍷"!important}
body [data-avatar][data-frame="fairy"]::before{content:"🧚‍♀️"!important} body [data-avatar][data-frame="fairy"]::after{content:"🌿"!important}
body [data-avatar][data-frame="goblincore"]::before{content:"🧝🏻‍♀️"!important} body [data-avatar][data-frame="goblincore"]::after{content:"🍄‍🟫"!important}
body [data-avatar][data-frame="zombie"]::before{content:"🧟‍♀️"!important} body [data-avatar][data-frame="zombie"]::after{content:"🧟"!important}
body [data-avatar][data-frame="mermaid"]::before{content:"🧜🏻‍♀️"!important} body [data-avatar][data-frame="mermaid"]::after{content:"🐚"!important}
body [data-avatar][data-frame="angel"]::before{content:"🪽"!important} body [data-avatar][data-frame="angel"]::after{content:"✨"!important}
body [data-avatar][data-frame="witch"]::before{content:"🧙‍♀️"!important} body [data-avatar][data-frame="witch"]::after{content:"🔮"!important}
body [data-avatar][data-frame="mushroom"]::before{content:"🍄"!important} body [data-avatar][data-frame="mushroom"]::after{content:"🍃"!important}
</style>
<style>
/* Dark-theme readability: strong contrast, readable controls and cards. */
body[data-theme="vampire"] .card,body[data-theme="witch"] .card,body[data-theme="darkrose"] .card,
body[data-theme="noir"] .card,body[data-theme="bloodmoon"] .card,body[data-theme="darkforest"] .card,
body[data-theme="obsidian"] .card,body[data-theme="cyberpunk"] .card,body[data-theme="midnight"] .card,
body[data-theme="darkacademia"] .card,body[data-theme="inkandbone"] .card,body[data-theme="rlyeh"] .card,
body[data-theme="salem"] .card,body[data-theme="vampiresilver"] .card{
  color:var(--text);
}
body[data-theme="vampire"] .subtle,body[data-theme="witch"] .subtle,body[data-theme="darkrose"] .subtle,
body[data-theme="noir"] .subtle,body[data-theme="bloodmoon"] .subtle,body[data-theme="darkforest"] .subtle,
body[data-theme="obsidian"] .subtle,body[data-theme="cyberpunk"] .subtle,body[data-theme="midnight"] .subtle,
body[data-theme="darkacademia"] .subtle,body[data-theme="inkandbone"] .subtle,body[data-theme="rlyeh"] .subtle,
body[data-theme="salem"] .subtle,body[data-theme="vampiresilver"] .subtle{
  color:var(--muted);
}
body[data-theme="vampire"] input,body[data-theme="vampire"] select,body[data-theme="vampire"] textarea,
body[data-theme="witch"] input,body[data-theme="witch"] select,body[data-theme="witch"] textarea,
body[data-theme="darkrose"] input,body[data-theme="darkrose"] select,body[data-theme="darkrose"] textarea,
body[data-theme="noir"] input,body[data-theme="noir"] select,body[data-theme="noir"] textarea,
body[data-theme="bloodmoon"] input,body[data-theme="bloodmoon"] select,body[data-theme="bloodmoon"] textarea,
body[data-theme="darkforest"] input,body[data-theme="darkforest"] select,body[data-theme="darkforest"] textarea,
body[data-theme="obsidian"] input,body[data-theme="obsidian"] select,body[data-theme="obsidian"] textarea,
body[data-theme="cyberpunk"] input,body[data-theme="cyberpunk"] select,body[data-theme="cyberpunk"] textarea,
body[data-theme="midnight"] input,body[data-theme="midnight"] select,body[data-theme="midnight"] textarea,
body[data-theme="darkacademia"] input,body[data-theme="darkacademia"] select,body[data-theme="darkacademia"] textarea,
body[data-theme="inkandbone"] input,body[data-theme="inkandbone"] select,body[data-theme="inkandbone"] textarea,
body[data-theme="rlyeh"] input,body[data-theme="rlyeh"] select,body[data-theme="rlyeh"] textarea,
body[data-theme="salem"] input,body[data-theme="salem"] select,body[data-theme="salem"] textarea,
body[data-theme="vampiresilver"] input,body[data-theme="vampiresilver"] select,body[data-theme="vampiresilver"] textarea{
  color:var(--text);background:var(--surface2);border-color:var(--border);
}
body[data-theme="vampire"] .nav button,body[data-theme="witch"] .nav button,body[data-theme="darkrose"] .nav button,
body[data-theme="noir"] .nav button,body[data-theme="bloodmoon"] .nav button,body[data-theme="darkforest"] .nav button,
body[data-theme="obsidian"] .nav button,body[data-theme="cyberpunk"] .nav button,body[data-theme="midnight"] .nav button,
body[data-theme="darkacademia"] .nav button,body[data-theme="inkandbone"] .nav button,body[data-theme="rlyeh"] .nav button,
body[data-theme="salem"] .nav button,body[data-theme="vampiresilver"] .nav button{color:var(--text)}
body[data-theme="vampire"] .nav button.active,body[data-theme="witch"] .nav button.active,
body[data-theme="darkrose"] .nav button.active,body[data-theme="noir"] .nav button.active,
body[data-theme="bloodmoon"] .nav button.active,body[data-theme="darkforest"] .nav button.active,
body[data-theme="obsidian"] .nav button.active,body[data-theme="cyberpunk"] .nav button.active,
body[data-theme="midnight"] .nav button.active,body[data-theme="darkacademia"] .nav button.active,
body[data-theme="gothic"] .nav button.active,body[data-theme="neon80"] .nav button.active,
body[data-theme="dark"] .nav button.active,body[data-theme="inkandbone"] .nav button.active,
body[data-theme="rlyeh"] .nav button.active,body[data-theme="salem"] .nav button.active,
body[data-theme="vampiresilver"] .nav button.active{
  box-shadow:0 0 18px color-mix(in srgb,var(--primary) 22%,transparent);
}


/* Avatar/profile frames. Any element marked data-avatar gets the matching frame. */
body[data-theme="vampire"] [data-avatar],body[data-theme="bloodmoon"] [data-avatar]{
  border:3px solid #c51f3d!important;
  box-shadow:0 0 0 4px #2a1018,0 0 24px rgba(210,31,60,.55)!important;
}
body[data-theme="witch"] [data-avatar]{
  border:3px solid #9b5cff!important;
  box-shadow:0 0 0 4px #241b31,0 0 24px rgba(155,92,255,.5)!important;
}
body[data-theme="darkrose"] [data-avatar]{
  border:3px solid #e14b72!important;
  box-shadow:0 0 0 4px #2b131d,0 0 24px rgba(225,75,114,.5)!important;
}
body[data-theme="noir"] [data-avatar]{
  border:3px solid #d9d9d9!important;
  box-shadow:0 0 0 4px #1d2026,0 0 20px rgba(255,255,255,.2)!important;
}
body[data-theme="darkforest"] [data-avatar]{
  border:3px solid #56c77a!important;
  box-shadow:0 0 0 4px #122319,0 0 24px rgba(86,199,122,.38)!important;
}
body[data-theme="obsidian"] [data-avatar]{
  border:3px solid #8da2ff!important;
  box-shadow:0 0 0 4px #171b2b,0 0 24px rgba(141,162,255,.42)!important;
}
body[data-theme="cyberpunk"] [data-avatar]{
  border:3px solid #ff2bd6!important;
  box-shadow:0 0 0 4px #241330,0 0 18px #ff2bd6,0 0 34px rgba(0,246,255,.45)!important;
}
body[data-theme="midnight"] [data-avatar]{
  border:3px solid #6aa8ff!important;
  box-shadow:0 0 0 4px #121d32,0 0 24px rgba(106,168,255,.42)!important;
}
body[data-theme="darkacademia"] [data-avatar]{
  border:3px solid #b08a4b!important;
  box-shadow:0 0 0 4px #292116,0 0 20px rgba(176,138,75,.4)!important;
}
/* Frames for the remaining themes, so every theme (not just the 10 dark ones) gets a matching avatar look. */
body[data-theme="pink"] [data-avatar]{border:3px solid #e889ad!important;box-shadow:0 0 0 4px #fbdce9,0 10px 24px rgba(232,137,173,.32)!important}
body[data-theme="lavender"] [data-avatar]{border:3px solid #9f8ee8!important;box-shadow:0 0 0 4px #e7e2fb,0 10px 24px rgba(159,142,232,.3)!important}
body[data-theme="mint"] [data-avatar]{border:3px solid #72bfa9!important;box-shadow:0 0 0 4px #dcf3ec,0 10px 24px rgba(114,191,169,.3)!important}
body[data-theme="dark"] [data-avatar]{border:3px solid #e69ab9!important;box-shadow:0 0 0 4px #3a2530,0 10px 24px rgba(230,154,185,.35)!important}
body[data-theme="gothic"] [data-avatar]{border:3px solid #c51f3d!important;box-shadow:0 0 0 4px #2a1018,0 0 22px rgba(197,31,61,.5)!important}
body[data-theme="neon80"] [data-avatar]{border:3px solid #ff2bd6!important;box-shadow:0 0 0 4px #1c1030,0 0 18px #ff2bd6,0 0 30px rgba(0,229,255,.4)!important}
body[data-theme="inkandbone"] [data-avatar]{border:3px solid #8a2331!important;box-shadow:0 0 0 4px #1e1613,0 10px 24px rgba(138,35,49,.35)!important}
body[data-theme="rlyeh"] [data-avatar]{border:3px solid #6f2023!important;box-shadow:0 0 0 4px #0e1615,0 10px 24px rgba(126,168,155,.3)!important}
body[data-theme="salem"] [data-avatar]{border:3px solid #7a1f2b!important;box-shadow:0 0 0 4px #17151d,0 10px 24px rgba(122,31,43,.4)!important}
body[data-theme="vampiresilver"] [data-avatar]{border:3px solid #b31f36!important;box-shadow:0 0 0 4px #221319,0 10px 24px rgba(179,31,54,.4)!important}
/* Gothic/vampire ornamental corners for avatar containers. */
body[data-theme="vampire"] [data-avatar]::before,
body[data-theme="vampire"] [data-avatar]::after{
  content:"✦";position:absolute;color:#d21f3c;font-size:16px;pointer-events:none;
}
body[data-theme="vampire"] [data-avatar]::before{left:-7px;top:-8px}
body[data-theme="vampire"] [data-avatar]::after{right:-7px;bottom:-8px}

/* Matching stickers for the remaining themes' auto frames. */
body[data-theme="pink"] [data-avatar]::before,body[data-theme="lavender"] [data-avatar]::before,body[data-theme="mint"] [data-avatar]::before,body[data-theme="dark"] [data-avatar]::before,body[data-theme="gothic"] [data-avatar]::before,body[data-theme="neon80"] [data-avatar]::before,body[data-theme="inkandbone"] [data-avatar]::before,body[data-theme="rlyeh"] [data-avatar]::before,body[data-theme="salem"] [data-avatar]::before,body[data-theme="vampiresilver"] [data-avatar]::before{position:absolute;font-size:16px;left:-9px;top:-7px;transform:rotate(-14deg);line-height:1;pointer-events:none;filter:drop-shadow(0 2px 3px rgba(0,0,0,.28));z-index:2}
body[data-theme="pink"] [data-avatar]::after,body[data-theme="lavender"] [data-avatar]::after,body[data-theme="mint"] [data-avatar]::after,body[data-theme="dark"] [data-avatar]::after,body[data-theme="gothic"] [data-avatar]::after,body[data-theme="neon80"] [data-avatar]::after,body[data-theme="inkandbone"] [data-avatar]::after,body[data-theme="rlyeh"] [data-avatar]::after,body[data-theme="salem"] [data-avatar]::after,body[data-theme="vampiresilver"] [data-avatar]::after{position:absolute;font-size:16px;right:-9px;bottom:-7px;transform:rotate(12deg);line-height:1;pointer-events:none;filter:drop-shadow(0 2px 3px rgba(0,0,0,.28));z-index:2}
body[data-theme="pink"] [data-avatar]::before{content:"🌸"}
body[data-theme="pink"] [data-avatar]::after{content:"💗"}
body[data-theme="lavender"] [data-avatar]::before{content:"🪻"}
body[data-theme="lavender"] [data-avatar]::after{content:"✨"}
body[data-theme="mint"] [data-avatar]::before{content:"🍃"}
body[data-theme="mint"] [data-avatar]::after{content:"🌿"}
body[data-theme="dark"] [data-avatar]::before{content:"🌙"}
body[data-theme="dark"] [data-avatar]::after{content:"✨"}
body[data-theme="gothic"] [data-avatar]::before{content:"🩸"}
body[data-theme="gothic"] [data-avatar]::after{content:"🕸️"}
body[data-theme="neon80"] [data-avatar]::before{content:"🪩"}
body[data-theme="neon80"] [data-avatar]::after{content:"⚡"}
body[data-theme="inkandbone"] [data-avatar]::before{content:"🖋️"}
body[data-theme="inkandbone"] [data-avatar]::after{content:"🦴"}
body[data-theme="rlyeh"] [data-avatar]::before{content:"🐙"}
body[data-theme="rlyeh"] [data-avatar]::after{content:"🌊"}
body[data-theme="salem"] [data-avatar]::before{content:"🕯️"}
body[data-theme="salem"] [data-avatar]::after{content:"🌙"}
body[data-theme="vampiresilver"] [data-avatar]::before{content:"🩸"}
body[data-theme="vampiresilver"] [data-avatar]::after{content:"🗡️"}

/* Base avatar look — the actual photo/place the theme frames above attach to. */
[data-avatar]{width:84px;height:84px;border-radius:50%;position:relative;display:grid;place-items:center;background:var(--surface2);border:3px solid var(--border);box-shadow:var(--shadow);flex:0 0 auto;cursor:pointer;transition:transform .16s ease}
[data-avatar]:hover{transform:scale(1.03)}
[data-avatar] img{width:100%;height:100%;object-fit:cover;display:block;border-radius:50%}
[data-avatar] .avatar-fallback{font-size:34px}
[data-avatar].avatar-lg{width:104px;height:104px;cursor:default}
/* Purchased avatar frames: these become selectable in Settings only after purchase. */
body [data-avatar][data-frame="kitty"]{border:3px solid #f3a8c6!important;box-shadow:0 0 0 4px #fff0f7,0 0 22px rgba(243,168,198,.42)!important}
body [data-avatar][data-frame="kuromi"]{border:3px solid #4b334d!important;box-shadow:0 0 0 4px #f1d9ee,0 0 24px rgba(75,51,77,.38)!important}
body [data-avatar][data-frame="sakura"]{border:3px solid #f2a9c5!important;box-shadow:0 0 0 4px #fff0f6,0 0 22px rgba(242,169,197,.42)!important}
body [data-avatar][data-frame="strawberry"]{border:3px solid #ed6f91!important;box-shadow:0 0 0 4px #ffe0e9,0 0 24px rgba(237,111,145,.42)!important}
body [data-avatar][data-frame="mint"]{border:3px solid #75cdb4!important;box-shadow:0 0 0 4px #e1f8f0,0 0 22px rgba(117,205,180,.4)!important}
body [data-avatar][data-frame="coquette"]{border:3px solid #df86b0!important;box-shadow:0 0 0 4px #ffe1ef,0 0 26px rgba(223,134,176,.45)!important}
body [data-avatar][data-frame="royal"]{border:3px solid #d4a83f!important;box-shadow:0 0 0 4px #fff1b8,0 0 28px rgba(212,168,63,.5)!important}
body [data-avatar][data-frame="cozy"]{border:3px solid #c98d63!important;box-shadow:0 0 0 4px #f7e5d4,0 0 22px rgba(201,141,99,.4)!important}
body [data-avatar][data-frame="lavender-bloom"]{border:3px solid #aa8de4!important;box-shadow:0 0 0 4px #eee6ff,0 0 24px rgba(170,141,228,.42)!important}
body [data-avatar][data-frame="midnight-glow"]{border:3px solid #7188d9!important;box-shadow:0 0 0 4px #20294b,0 0 28px rgba(113,136,217,.52)!important}
/* Manually selectable avatar frames — independent of the active interface theme, chosen in Settings. */
body [data-avatar][data-frame="heart"]{border:3px solid #e8789f!important;box-shadow:0 0 0 4px #ffe1ec,0 10px 26px rgba(232,120,159,.35)!important}
body [data-avatar][data-frame="lavender"]{border:3px solid #9f7fe0!important;box-shadow:0 0 0 4px #ece3ff,0 10px 26px rgba(159,127,224,.35)!important}
body [data-avatar][data-frame="glass"]{border:3px solid rgba(255,255,255,.85)!important;box-shadow:0 0 0 4px rgba(255,255,255,.35),0 10px 26px rgba(120,120,160,.25)!important}
body [data-avatar][data-frame="pearl"]{border:3px solid #f3ead9!important;box-shadow:0 0 0 4px #fffaf0,0 10px 26px rgba(210,190,150,.35)!important}
body [data-avatar][data-frame="dream"]{border:3px solid transparent!important;background-image:linear-gradient(var(--surface2),var(--surface2)),linear-gradient(135deg,#ffb6d9,#c6b6ff,#b6e6ff)!important;background-origin:border-box!important;background-clip:padding-box,border-box!important;box-shadow:0 10px 30px rgba(180,150,230,.35)!important}
body [data-avatar][data-frame="gothic"]{border:3px solid #c51f3d!important;box-shadow:0 0 0 4px #2a1018,0 0 24px rgba(210,31,60,.55)!important}
body [data-avatar][data-frame="midnight"]{border:3px solid #6aa8ff!important;box-shadow:0 0 0 4px #121d32,0 0 24px rgba(106,168,255,.42)!important}
body [data-avatar][data-frame="forest"]{border:3px solid #56c77a!important;box-shadow:0 0 0 4px #122319,0 0 24px rgba(86,199,122,.38)!important}
body [data-avatar][data-frame="cyber"]{border:3px solid #ff2bd6!important;box-shadow:0 0 0 4px #241330,0 0 18px #ff2bd6,0 0 34px rgba(0,246,255,.45)!important}
body [data-avatar][data-frame="gold"]{border:3px solid #cf9a35!important;box-shadow:0 0 0 4px #2c2410,0 0 24px rgba(207,154,53,.5)!important}
/* Themed "sticker" decorations — small PNG-style emoji badges pinned to each frame's corners. */
body [data-avatar][data-frame]::before,body [data-avatar][data-frame]::after{position:absolute;line-height:1;pointer-events:none;filter:drop-shadow(0 2px 3px rgba(0,0,0,.28));z-index:2}
body [data-avatar].avatar-lg[data-frame]::before,body [data-avatar].avatar-lg[data-frame]::after{font-size:22px}
body [data-avatar][data-frame]::before{font-size:16px;left:-9px;top:-7px;transform:rotate(-14deg)}
body [data-avatar][data-frame]::after{font-size:16px;right:-9px;bottom:-7px;transform:rotate(12deg)}
body [data-avatar][data-frame="heart"]::before{content:"💗"!important}body [data-avatar][data-frame="heart"]::after{content:"🎀"!important}
body [data-avatar][data-frame="lavender"]::before{content:"🪻"!important}body [data-avatar][data-frame="lavender"]::after{content:"✨"!important}
body [data-avatar][data-frame="glass"]::before{content:"🫧"!important}body [data-avatar][data-frame="glass"]::after{content:"💧"!important}
body [data-avatar][data-frame="pearl"]::before{content:"🤍"!important}body [data-avatar][data-frame="pearl"]::after{content:"✨"!important}
body [data-avatar][data-frame="dream"]::before{content:"☁️"!important}body [data-avatar][data-frame="dream"]::after{content:"⭐"!important}
body [data-avatar][data-frame="gothic"]::before{content:"🖤"!important}body [data-avatar][data-frame="gothic"]::after{content:"🥀"!important}
body [data-avatar][data-frame="midnight"]::before{content:"🌙"!important}body [data-avatar][data-frame="midnight"]::after{content:"⭐"!important}
body [data-avatar][data-frame="forest"]::before{content:"🍃"!important}body [data-avatar][data-frame="forest"]::after{content:"🍄"!important}
body [data-avatar][data-frame="cyber"]::before{content:"⚡"!important}body [data-avatar][data-frame="cyber"]::after{content:"💠"!important}
body [data-avatar][data-frame="gold"]::before{content:"👑"!important}body [data-avatar][data-frame="gold"]::after{content:"💎"!important}
.frame-swatches{display:flex;flex-wrap:wrap;gap:12px;margin-top:8px}
.frame-swatch-wrap{display:flex;flex-direction:column;align-items:center;gap:4px}
.frame-swatch{background:transparent;padding:2px;border-radius:50%}
.frame-swatch.active{outline:2px solid var(--primary);outline-offset:3px}
.frame-swatch-label{font-size:10px;text-align:center;color:var(--muted);max-width:56px}
.sidebar-avatar-wrap{display:flex;flex-direction:column;align-items:center;padding:4px 0 12px}
.avatar-editor{display:flex;align-items:center;gap:16px;margin-bottom:16px}
.avatar-editor .avatar-actions{display:flex;flex-direction:column;align-items:flex-start;gap:8px}
.avatar-editor .subtle{max-width:220px}
</style>

<style>
/* Atmospheric theme effects */
body[data-theme="gothic"]{
  background:
    radial-gradient(circle at 12% 10%, rgba(197,31,61,.13), transparent 30%),
    radial-gradient(circle at 88% 80%, rgba(123,16,39,.15), transparent 32%),
    var(--bg);
}
body[data-theme="gothic"] .card,
body[data-theme="gothic"] .sidebar,
body[data-theme="gothic"] .topbar{
  border-color:rgba(197,31,61,.28);
}
body[data-theme="gothic"] .btn:not(.secondary):not(.ghost),
body[data-theme="gothic"] .tag{
  box-shadow:0 0 18px rgba(197,31,61,.16);
}
body[data-theme="gothic"] h1,
body[data-theme="gothic"] h2,
body[data-theme="gothic"] h3{
  letter-spacing:.01em;
}

body[data-theme="neon80"]{
  background:
    radial-gradient(circle at 15% 15%, rgba(255,43,214,.18), transparent 28%),
    radial-gradient(circle at 85% 75%, rgba(0,229,255,.16), transparent 30%),
    linear-gradient(135deg,#100b1c,#17102b 48%,#100b1c);
}
body[data-theme="neon80"] .card,
body[data-theme="neon80"] .sidebar,
body[data-theme="neon80"] .topbar{
  border-color:rgba(255,43,214,.34);
  box-shadow:0 10px 35px rgba(0,0,0,.3),0 0 22px rgba(0,229,255,.05);
}
body[data-theme="neon80"] .btn:not(.secondary):not(.ghost){
  box-shadow:0 0 16px rgba(255,43,214,.28);
}
body[data-theme="neon80"] .tag{
  border-color:rgba(0,229,255,.38);
  box-shadow:0 0 14px rgba(0,229,255,.15);
}
body[data-theme="neon80"] .brand h1{
  text-shadow:0 0 12px rgba(255,43,214,.55),0 0 22px rgba(0,229,255,.25);
}
</style>

<style id="hair-growth-pro-style">
.mjx-hg-hero{display:grid;grid-template-columns:1.25fr .75fr;gap:18px;align-items:stretch}
.mjx-hg-hero-main{position:relative;overflow:hidden;border-radius:30px;padding:26px;background:radial-gradient(circle at 85% 15%,rgba(201,159,180,.18),transparent 34%),linear-gradient(145deg,var(--surface),var(--surface2));border:1px solid var(--border)}
.mjx-hg-hero-main:after{content:'✦';position:absolute;right:20px;bottom:-18px;font-size:110px;opacity:.06;transform:rotate(10deg)}
.mjx-hg-kicker{text-transform:uppercase;letter-spacing:.12em;font-size:11px;font-weight:800;color:var(--muted)}
.mjx-hg-title{font-size:clamp(28px,5vw,42px);margin:6px 0 10px;font-family:Georgia,serif;font-weight:700}
.mjx-hg-sub{color:var(--muted);max-width:650px;line-height:1.55}
.mjx-hg-ring{width:180px;height:180px;border-radius:50%;display:grid;place-items:center;background:conic-gradient(var(--primary) calc(var(--p)*1%),rgba(190,165,177,.18) 0);margin:auto;position:relative;box-shadow:0 18px 40px rgba(84,54,69,.08)}
.mjx-hg-ring:before{content:"";position:absolute;inset:12px;border-radius:50%;background:var(--surface);box-shadow:inset 0 0 0 1px var(--border)}
.mjx-hg-ring .inside{position:relative;z-index:1;width:132px;height:132px;border-radius:50%;display:grid;place-items:center;text-align:center;padding:15px}
.mjx-hg-ring strong{font-size:28px;line-height:1}
.mjx-hg-ring span{font-size:12px;color:var(--muted);margin-top:6px}
.mjx-hg-stats{display:grid;grid-template-columns:repeat(4,minmax(0,1fr));gap:12px;margin:16px 0}
.mjx-hg-stat{padding:16px 18px;border:1px solid var(--border);border-radius:22px;background:var(--surface);box-shadow:0 10px 28px rgba(77,49,63,.05)}
.mjx-hg-stat .n{font-size:28px;font-weight:800;letter-spacing:-.02em}.mjx-hg-stat .l{color:var(--muted);font-size:12px;margin-top:4px}
.mjx-hg-period{display:flex;gap:8px;flex-wrap:wrap}.mjx-hg-period button.active{background:var(--primary);color:#fff;border-color:var(--primary)}
.mjx-hg-chart{height:310px;border:1px solid var(--border);border-radius:24px;background:linear-gradient(180deg,var(--surface),var(--surface2));padding:14px;overflow:hidden}
.mjx-hg-chart svg{width:100%;height:100%;display:block}
.mjx-hg-timeline{display:flex;gap:0;overflow:auto;padding:8px 2px 16px}.mjx-hg-node{min-width:150px;position:relative;padding-top:22px}.mjx-hg-node:before{content:"";position:absolute;left:0;right:0;top:8px;height:2px;background:var(--border)}.mjx-hg-node:first-child:before{left:30px}.mjx-hg-node:last-child:before{right:calc(100% - 30px)}.mjx-hg-dot{position:absolute;top:0;left:24px;width:16px;height:16px;border-radius:50%;background:var(--surface);border:4px solid var(--primary);z-index:1}.mjx-hg-node:first-child .mjx-hg-dot{box-shadow:0 0 0 5px rgba(188,129,150,.12)}
.mjx-hg-insight{display:grid;grid-template-columns:1.2fr .8fr;gap:14px}.mjx-hg-insight .quote{padding:20px;border-radius:22px;background:linear-gradient(135deg,var(--surface2),var(--surface));border:1px solid var(--border);font-size:17px;line-height:1.5}.mjx-hg-note{padding:20px;border-radius:22px;background:var(--surface);border:1px solid var(--border)}
.mjx-hg-empty{padding:28px;border-radius:24px;border:1px dashed var(--border);background:linear-gradient(180deg,var(--surface),var(--surface2));text-align:center;color:var(--muted)}
@media(max-width:850px){.mjx-hg-hero,.mjx-hg-insight{grid-template-columns:1fr}.mjx-hg-stats{grid-template-columns:repeat(2,minmax(0,1fr))}.mjx-hg-ring{width:150px;height:150px}.mjx-hg-ring .inside{width:108px;height:108px}}
</style>

<style id="mjx-style">
.mjx-shell{display:grid;gap:16px}.mjx-grid{display:grid;gap:16px}.mjx-grid-2{grid-template-columns:repeat(2,minmax(0,1fr))}.mjx-grid-3{grid-template-columns:repeat(3,minmax(0,1fr))}.mjx-grid-4{grid-template-columns:repeat(4,minmax(0,1fr))}
.mjx-shop-item{position:relative;overflow:hidden;transition:transform .22s ease,box-shadow .22s ease}.mjx-shop-item:hover{transform:translateY(-4px)}
.mjx-art{height:150px;border-radius:22px;background:linear-gradient(145deg,var(--surface2),var(--surface));display:grid;place-items:center;overflow:hidden;border:1px solid var(--border);margin-bottom:12px}.mjx-art img{width:100%;height:100%;object-fit:cover}.mjx-art .emoji{font-size:64px;filter:drop-shadow(0 10px 12px rgba(0,0,0,.08))}
.mjx-rarity{font-size:11px;padding:6px 9px;border-radius:999px;background:var(--surface2);border:1px solid var(--border)}
.mjx-collection{overflow:hidden}.mjx-collection-head{padding:18px;border-radius:22px;background:linear-gradient(135deg,var(--surface),var(--surface2));position:relative}.mjx-collection-head:after{content:'✦';position:absolute;right:20px;top:12px;font-size:42px;opacity:.12}.mjx-collection-progress{height:8px;border-radius:99px;background:rgba(130,100,120,.12);overflow:hidden}.mjx-collection-progress i{display:block;height:100%;border-radius:inherit;background:linear-gradient(90deg,var(--primary),var(--accent));transition:width .5s ease}
.mjx-box{min-height:250px;display:grid;place-items:center;text-align:center;background:radial-gradient(circle at 50% 35%,var(--surface2),var(--surface));border-radius:30px;border:1px solid var(--border);position:relative;overflow:hidden}.mjx-box .gift{font-size:96px;animation:mjxFloat 2.8s ease-in-out infinite}.mjx-box.open .gift{animation:mjxPop .5s ease}.mjx-spark{position:absolute;inset:0;pointer-events:none}.mjx-spark span{position:absolute;font-size:18px;opacity:0;animation:mjxSpark 1.2s ease forwards}.mjx-spark span:nth-child(1){left:18%;top:28%}.mjx-spark span:nth-child(2){left:74%;top:22%;animation-delay:.08s}.mjx-spark span:nth-child(3){left:28%;top:68%;animation-delay:.16s}.mjx-spark span:nth-child(4){left:68%;top:66%;animation-delay:.24s}
@keyframes mjxFloat{0%,100%{transform:translateY(0) rotate(-2deg)}50%{transform:translateY(-7px) rotate(2deg)}}@keyframes mjxPop{0%{transform:scale(1)}55%{transform:scale(1.16) rotate(-5deg)}100%{transform:scale(1)}}@keyframes mjxSpark{0%{opacity:0;transform:scale(.6) translateY(8px)}30%{opacity:1}100%{opacity:0;transform:scale(1.25) translateY(-28px)}}
.mjx-chat{display:grid;gap:10px;max-height:520px;overflow:auto;padding:8px}.mjx-msg{max-width:84%;padding:12px 14px;border-radius:18px;line-height:1.55}.mjx-msg.user{justify-self:end;background:var(--primary);color:#fff;border-bottom-right-radius:7px}.mjx-msg.bot{justify-self:start;background:var(--surface2);border:1px solid var(--border);border-bottom-left-radius:7px}.mjx-ingredient{display:flex;gap:10px;align-items:flex-start;padding:12px;border:1px solid var(--border);border-radius:16px;background:var(--surface)}.mjx-dot{width:12px;height:12px;border-radius:50%;margin-top:5px;flex:0 0 auto}.mjx-dot.green{background:#62b58a}.mjx-dot.yellow{background:#e2ba63}.mjx-dot.red{background:#d97887}.mjx-dot.gray{background:#a7a0a7}.mjx-filter{display:flex;gap:8px;flex-wrap:wrap}.mjx-filter button{background:var(--surface);border:1px solid var(--border);padding:8px 11px;border-radius:999px}.mjx-filter button.active{background:var(--surface2);border-color:var(--primary2)}
.mjx-chart{height:270px;border:1px solid var(--border);border-radius:22px;background:linear-gradient(180deg,var(--surface),var(--surface2));padding:12px}.mjx-chart svg{width:100%;height:100%;display:block}.mjx-stat-big{font-size:36px;font-weight:800}.mjx-measure{display:grid;grid-template-columns:1.1fr .8fr .8fr auto;gap:10px;align-items:end}.mjx-hair-ring{width:150px;height:150px;border-radius:50%;display:grid;place-items:center;background:conic-gradient(var(--primary) calc(var(--p)*1%),#eee5ea 0)}.mjx-hair-ring:after{content:"";position:absolute}.mjx-hair-ring .inside{width:116px;height:116px;border-radius:50%;display:grid;place-items:center;background:var(--surface);text-align:center}.mjx-furniture{display:grid;grid-template-columns:repeat(4,1fr);gap:10px}.mjx-furniture button{min-height:96px;border:1px solid var(--border);border-radius:18px;background:var(--surface);display:grid;place-items:center;padding:8px}.mjx-furniture button.active{outline:2px solid var(--primary2)}
.mjx-season-banner{position:relative;overflow:hidden;border-radius:26px;padding:22px;background:linear-gradient(135deg,var(--surface2),var(--surface));border:1px solid var(--border)}
.mjx-season-banner:after{content:'✦';position:absolute;right:22px;top:10px;font-size:70px;opacity:.08}.mjx-lesson{cursor:pointer;transition:transform .18s ease}.mjx-lesson:hover{transform:translateY(-2px)}.mjx-source{font-size:11px;color:var(--muted)}
.mjx-quick-sheet{position:fixed;inset:0;background:rgba(35,24,31,.36);backdrop-filter:blur(8px);display:flex;align-items:center;justify-content:center;padding:18px;z-index:300}.mjx-quick-panel{width:min(360px,100%);max-height:min(520px,80vh);overflow:auto;background:var(--surface);border-radius:22px;padding:16px;box-shadow:0 22px 70px rgba(0,0,0,.22);animation:mjxSheet .2s ease}.mjx-quick-grid{display:grid;grid-template-columns:repeat(2,minmax(0,1fr));gap:8px}.mjx-quick-grid button{padding:11px;border-radius:14px;text-align:left;background:var(--surface2);border:1px solid var(--border)}.mjx-quick-grid button strong{font-size:13px}.mjx-quick-grid button .subtle{font-size:11px}@keyframes mjxSheet{from{transform:translateY(10px) scale(.97);opacity:.3}to{transform:translateY(0) scale(1);opacity:1}}
@media(max-width:900px){.mjx-grid-4,.mjx-grid-3{grid-template-columns:repeat(2,minmax(0,1fr))}.mjx-measure{grid-template-columns:1fr 1fr}.mjx-furniture{grid-template-columns:repeat(3,1fr)}}@media(max-width:650px){.mjx-grid-2,.mjx-grid-3,.mjx-grid-4{grid-template-columns:1fr}.mjx-quick-grid{grid-template-columns:1fr}.mjx-measure{grid-template-columns:1fr}.mjx-furniture{grid-template-columns:repeat(2,1fr)}}
</style>

<style id="smart-plan-events-style">
.smart-plan-hero{display:grid;grid-template-columns:1.25fr .75fr;gap:16px;margin-top:16px}
.smart-plan-main,.smart-plan-side{border:1px solid var(--border);border-radius:26px;background:linear-gradient(145deg,var(--surface),var(--surface2));padding:22px}
.smart-plan-main{position:relative;overflow:hidden}
.smart-plan-main:after{content:'✦';position:absolute;right:18px;bottom:-25px;font-size:110px;opacity:.06}
.smart-plan-kicker{font-size:11px;text-transform:uppercase;letter-spacing:.12em;color:var(--muted);font-weight:800}
.smart-plan-title{font-family:Georgia,serif;font-size:30px;margin:6px 0 8px}
.smart-plan-sub{color:var(--muted);line-height:1.55;margin:0}
.smart-plan-list{display:grid;gap:9px;margin-top:16px}
.smart-plan-item{display:flex;gap:11px;align-items:flex-start;padding:12px 14px;border:1px solid var(--border);border-radius:16px;background:var(--surface)}
.smart-plan-item .ico{font-size:19px;flex:0 0 25px}
.smart-plan-item.done{opacity:.62}
.smart-plan-item.done .txt{text-decoration:line-through}
.smart-plan-item button{margin-left:auto;flex:0 0 auto}
.smart-plan-avoid{margin-top:16px;padding:15px;border-radius:18px;background:color-mix(in srgb,var(--danger) 7%,var(--surface));border:1px solid color-mix(in srgb,var(--danger) 20%,var(--border))}
.smart-plan-avoid-title{font-weight:800;margin-bottom:8px}
.smart-plan-chips{display:flex;gap:7px;flex-wrap:wrap;margin-top:14px}
.smart-plan-actions{display:flex;gap:8px;flex-wrap:wrap;margin-top:16px}
.smart-plan-side h4{margin:0 0 12px}
.smart-plan-score{font-size:44px;font-weight:800;letter-spacing:-.04em}
.smart-plan-mini{color:var(--muted);font-size:12px;line-height:1.5}
.smart-plan-factor{display:flex;justify-content:space-between;gap:10px;padding:9px 0;border-bottom:1px solid var(--border);font-size:13px}
.smart-plan-factor:last-child{border-bottom:0}
.event-panel{margin-top:16px}
.event-grid{display:grid;grid-template-columns:repeat(3,minmax(0,1fr));gap:10px;margin-top:14px}
.event-btn{padding:15px 12px;border-radius:18px;border:1px solid var(--border);background:var(--surface);color:var(--text);text-align:left;cursor:pointer;transition:.18s ease}.event-btn strong,.event-btn span{color:var(--text)}.event-btn span{color:var(--muted)}
.event-btn:hover{transform:translateY(-2px);border-color:var(--primary2)}
.event-btn.active{background:var(--surface2);border-color:var(--primary);box-shadow:0 0 0 2px color-mix(in srgb,var(--primary) 14%,transparent)}
.event-btn .event-ico{font-size:25px;display:block;margin-bottom:7px}
.event-btn strong{font-size:13px;display:block}
.event-btn span{font-size:11px;color:var(--muted);display:block;margin-top:3px}
.event-result{margin-top:16px;padding:18px;border-radius:22px;border:1px solid var(--border);background:linear-gradient(145deg,var(--surface2),var(--surface))}
.event-result h4{margin:0 0 6px}
.event-steps{display:grid;gap:8px;margin-top:12px;counter-reset:step}
.event-step{display:flex;gap:10px;align-items:flex-start;padding:10px 12px;border-radius:14px;background:var(--surface);border:1px solid var(--border)}
.event-step b{width:25px;height:25px;border-radius:50%;display:grid;place-items:center;background:var(--primary);color:#fff;font-size:12px;flex:0 0 25px}
.event-empty{color:var(--muted);line-height:1.5}
.smart-note{font-size:11px;color:var(--muted);line-height:1.5;margin-top:13px}
@media(max-width:850px){
 .smart-plan-hero{grid-template-columns:1fr}
 .event-grid{grid-template-columns:repeat(2,minmax(0,1fr))}
}
@media(max-width:520px){
 .event-grid{grid-template-columns:1fr}
 .smart-plan-title{font-size:25px}
}
</style>


<style id="elf-frame-shop-style">
body [data-avatar][data-frame="elf-garden"]{position:relative!important;border:3px solid #8fbd78!important;box-shadow:0 0 0 4px #e9f4df,0 0 24px rgba(104,158,78,.38)!important}
body [data-avatar][data-frame="elf-garden"]::before{content:"🧝🏻‍♀️";position:absolute;left:-10px;top:-10px;font-size:18px;line-height:1;transform:rotate(-10deg);pointer-events:none;z-index:3;filter:drop-shadow(0 2px 3px rgba(54,90,44,.28))}
body [data-avatar][data-frame="elf-garden"]::after{content:"🍃 🌿";position:absolute;right:-12px;bottom:-10px;font-size:16px;line-height:1;transform:rotate(10deg);pointer-events:none;z-index:3;white-space:nowrap;filter:drop-shadow(0 2px 3px rgba(54,90,44,.28))}
</style>
</head>
<body>
<div id="app" class="app"></div>
<div id="modalRoot"></div>
<div id="toasts" class="toast-stack"></div>
<script>
(() => {
'use strict';

window.addEventListener('error', (e) => {
  const app=document.getElementById('app');
  if(app) app.innerHTML=`<main style="min-height:100vh;display:grid;place-items:center;padding:24px;background:#fff9fb;font-family:system-ui"><section style="max-width:560px;background:#fff;border:1px solid rgba(74,55,66,.1);border-radius:24px;padding:24px;box-shadow:0 14px 40px rgba(91,52,72,.09)"><h1 style="font-family:Georgia,serif">Ой, что-то пошло не так ♡</h1><p style="color:#8f858e;line-height:1.6">Приложение попыталось запуститься, но браузер столкнулся с ошибкой. Попробуй обновить страницу. Данные не должны пропасть.</p><details><summary>Техническая информация</summary><pre style="white-space:pre-wrap;overflow:auto">${String(e?.error?.stack||e?.message||e)}</pre></details><button onclick="location.reload()" style="margin-top:14px;padding:11px 15px;border:0;border-radius:15px;background:#e889ad;color:#fff">Перезапустить</button></section></main>`;
});
window.addEventListener('unhandledrejection', (e) => {
  const app=document.getElementById('app');
  if(app && !app.querySelector('section')) app.innerHTML='<div style="padding:30px;font-family:system-ui">Не удалось выполнить действие. Перезапусти приложение ♡</div>';
});

const STORAGE_KEY='myBeautyJournal_v3';
const imgDB='myBeautyJournalImages';
const uid=()=>Date.now().toString(36)+Math.random().toString(36).slice(2,8);
const localKey=d=>{const x=d||new Date();return `${x.getFullYear()}-${String(x.getMonth()+1).padStart(2,'0')}-${String(x.getDate()).padStart(2,'0')}`};
const todayKey=()=>localKey();
const dateObj=s=>new Date(s+'T12:00:00');
const clamp=(n,a=0,b=100)=>Math.max(a,Math.min(b,n));
const fmtDate=s=>new Intl.DateTimeFormat('ru-RU',{day:'numeric',month:'long',year:'numeric'}).format(dateObj(s));
const pct=(a,b)=>b?Math.round(a/b*100):0;
const esc=s=>String(s??'').replace(/[&<>"]/g,m=>({'&':'&amp;','<':'&lt;','>':'&gt;','"':'&quot;'}[m]));
const BASE_AVATAR_FRAMES=[['','🎨','По теме'],['heart','💗','Сердечки'],['lavender','🪻','Лаванда'],['glass','🫧','Стекло'],['pearl','🤍','Жемчуг'],['dream','☁️','Мечта'],['gothic','🖤','Готика'],['midnight','🌌','Полночь'],['forest','🍃','Лес'],['cyber','⚡','Кибер'],['gold','👑','Золото']];
function getAvatarFrames(){
 const purchased=(data?.shop?.owned||[]).map(id=>SHOP_CATALOG.find(x=>x.id===id)).filter(x=>x&&x.type==='frame'&&x.shopAvatarFrame);
 return [...BASE_AVATAR_FRAMES,...purchased.map(x=>[x.frameId||x.id,x.icon,x.title])];
}
let AVATAR_FRAMES=BASE_AVATAR_FRAMES;
const sleep=ms=>new Promise(r=>setTimeout(r,ms));

const themes={
 pink:{name:'Нежная роза',vars:{'--bg':'#fff9fb','--surface':'#ffffff','--surface2':'#fff1f6','--primary':'#e889ad','--primary2':'#f7c2d6','--accent':'#caa8e8','--success':'#8ecdb8'}},
 lavender:{name:'Лавандовая',vars:{'--bg':'#faf9ff','--surface':'#ffffff','--surface2':'#f1eeff','--primary':'#9f8ee8','--primary2':'#d7cff7','--accent':'#b999db','--success':'#8ecdb8'}},
 mint:{name:'Мятная',vars:{'--bg':'#f8fffc','--surface':'#ffffff','--surface2':'#eafaf4','--primary':'#72bfa9','--primary2':'#bfe6d9','--accent':'#9bb8e6','--success':'#74c9a5'}},
 dark:{name:'Ночная',vars:{'--bg':'#171419','--surface':'#211d23','--surface2':'#2b222b','--text':'#f4edf2','--muted':'#b8aab5','--primary':'#e69ab9','--primary2':'#6d4758','--accent':'#ad90d1','--success':'#77b9a1','--border':'rgba(255,255,255,.08)'}}
,
gothic:{name:'🩸 Готическая ночь',vars:{
  '--bg':'#100b0e','--surface':'#1a1116','--surface2':'#26171d','--text':'#f4e8eb','--muted':'#bda7ad',
  '--primary':'#c51f3d','--primary2':'#7b1027','--accent':'#e7b7c1','--danger':'#ff3558',
  '--border':'#43202a','--shadow':'0 18px 45px rgba(0,0,0,.55)'
}},
neon80:{name:'🪩 Неоновые 80-е',vars:{
  '--bg':'#100b1c','--surface':'#19122b','--surface2':'#24183d','--text':'#fff7ff','--muted':'#cbb9d8',
  '--primary':'#ff2bd6','--primary2':'#00e5ff','--accent':'#ffe600','--danger':'#ff3b30',
  '--border':'#5c2d72','--shadow':'0 18px 45px rgba(0,0,0,.5)'
}},
vampire:{name:'🧛 Вампирская кровь',vars:{'--bg':'#0d080b','--surface':'#171014','--surface2':'#25151b','--text':'#fff0f2','--muted':'#d0aeb5','--primary':'#d21f3c','--primary2':'#7d0c21','--accent':'#f3c4cc','--danger':'#ff3d5a','--border':'#57202d','--shadow':'0 18px 50px rgba(0,0,0,.65)'}},
witch:{name:'🔮 Ведьмин круг',vars:{'--bg':'#0b0b12','--surface':'#14131d','--surface2':'#211d2d','--text':'#f5f0ff','--muted':'#c5bdd7','--primary':'#9b5cff','--primary2':'#4e2a7f','--accent':'#b8ff7a','--danger':'#ff5277','--border':'#46335d','--shadow':'0 18px 50px rgba(0,0,0,.62)'}},
darkrose:{name:'🥀 Тёмная роза',vars:{'--bg':'#10090d','--surface':'#1b1117','--surface2':'#2a1721','--text':'#fff1f5','--muted':'#cfb1bc','--primary':'#e14b72','--primary2':'#7c2442','--accent':'#ffb4c9','--danger':'#ff4e68','--border':'#5a263a','--shadow':'0 18px 50px rgba(0,0,0,.62)'}},
noir:{name:'🖤 Noir',vars:{'--bg':'#08090b','--surface':'#111317','--surface2':'#1c2026','--text':'#f5f7fa','--muted':'#b7bdc7','--primary':'#d9d9d9','--primary2':'#858b95','--accent':'#ffffff','--danger':'#e34b4b','--border':'#343943','--shadow':'0 18px 50px rgba(0,0,0,.7)'}},
bloodmoon:{name:'🌑 Кровавая луна',vars:{'--bg':'#09080d','--surface':'#151018','--surface2':'#24151e','--text':'#fff2f0','--muted':'#cdb8b6','--primary':'#e32929','--primary2':'#651616','--accent':'#ff9b73','--danger':'#ff3434','--border':'#522225','--shadow':'0 18px 55px rgba(0,0,0,.7)'}},
darkforest:{name:'🌲 Тёмный лес',vars:{'--bg':'#07100c','--surface':'#0f1a14','--surface2':'#18271e','--text':'#effff3','--muted':'#b3cbb9','--primary':'#56c77a','--primary2':'#23613a','--accent':'#b9f58b','--danger':'#e45c65','--border':'#294b36','--shadow':'0 18px 50px rgba(0,0,0,.65)'}},
obsidian:{name:'🪨 Обсидиан',vars:{'--bg':'#090a0e','--surface':'#12141a','--surface2':'#1c2028','--text':'#f3f5ff','--muted':'#b9becd','--primary':'#8da2ff','--primary2':'#46558e','--accent':'#d9e0ff','--danger':'#ff5b6e','--border':'#343c55','--shadow':'0 18px 55px rgba(0,0,0,.72)'}},
cyberpunk:{name:'⚡ Киберпанк',vars:{'--bg':'#080a12','--surface':'#101425','--surface2':'#181d34','--text':'#f5fbff','--muted':'#aeb9cc','--primary':'#ff2bd6','--primary2':'#7133d1','--accent':'#00f6ff','--danger':'#ff365f','--border':'#3b2e62','--shadow':'0 18px 55px rgba(0,0,0,.7)'}},
midnight:{name:'🌌 Полночь',vars:{'--bg':'#070b16','--surface':'#0f1727','--surface2':'#17223a','--text':'#f1f6ff','--muted':'#b4c0d4','--primary':'#6aa8ff','--primary2':'#31568e','--accent':'#b5d6ff','--danger':'#ff6374','--border':'#2b4266','--shadow':'0 18px 55px rgba(0,0,0,.7)'}},
darkacademia:{name:'📜 Dark Academia',vars:{'--bg':'#100e0a','--surface':'#191611','--surface2':'#282119','--text':'#f6efe0','--muted':'#c8baa2','--primary':'#b08a4b','--primary2':'#684e2d','--accent':'#e5c77b','--danger':'#b94a43','--border':'#55432b','--shadow':'0 18px 50px rgba(0,0,0,.65)'}},
inkandbone:{name:'🖋️ Чернила и кость',vars:{
  '--bg':'#0b0a09','--surface':'#161311','--surface2':'#231d1a','--text':'#f1e9e2','--muted':'#b7a89d',
  '--primary':'#8a2331','--primary2':'#451319','--accent':'#a8a5a0','--danger':'#c0392b',
  '--border':'#3a2f29','--shadow':'0 18px 50px rgba(0,0,0,.65)'
}},
rlyeh:{name:'🐙 Зов Ктулху',vars:{
  '--bg':'#07090a','--surface':'#101514','--surface2':'#182121','--text':'#e8f0ed','--muted':'#a4beb8',
  '--primary':'#6f2023','--primary2':'#3a1315','--accent':'#7ea89b','--danger':'#b33a3a',
  '--border':'#293735','--shadow':'0 18px 55px rgba(0,0,0,.7)'
}},
salem:{name:'🕯️ Салемская готика',vars:{
  '--bg':'#0a0a0d','--surface':'#141319','--surface2':'#1f1c25','--text':'#ebe9f0','--muted':'#a7a3b4',
  '--primary':'#7a1f2b','--primary2':'#3f1219','--accent':'#c2c4cc','--danger':'#c0392b',
  '--border':'#2f2c39','--shadow':'0 18px 55px rgba(0,0,0,.68)'
}},
vampiresilver:{name:'🩸 Вампирское серебро',vars:{
  '--bg':'#0c0a0b','--surface':'#171216','--surface2':'#251c21','--text':'#f4ecee','--muted':'#b9aeb4',
  '--primary':'#b31f36','--primary2':'#5c0f1c','--accent':'#cacdd6','--danger':'#ff3b30',
  '--border':'#3d2b30','--shadow':'0 18px 55px rgba(0,0,0,.68)'
}}};

const skinTips={
 normal:['Сохраняй мягкое очищение и не перегружай рутину лишними активами.','Увлажнение утром и вечером помогает поддерживать комфорт кожи.'],
 dry:['Старайся не использовать слишком горячую воду и добавь мягкое увлажнение.','В холодную или сухую погоду особенно полезен защитный крем.'],
 oily:['Не пытайся пересушить кожу: мягкое очищение и лёгкое увлажнение обычно комфортнее.','В жару держи рутину минималистичной и не забывай про SPF.'],
 combination:['Можно распределять уход по зонам: более лёгкие текстуры на Т-зону, больше комфорта на сухие участки.','Следи за реакцией отдельных зон, а не только за общим состоянием кожи.'],
 sensitive:['Чем проще рутина, тем легче понять реакцию кожи. Вводи новые средства постепенно.','При раздражении лучше сократить количество активов и оставить базовый уход.']
};
const hairTips={
 normal:['Регулярный кондиционер и аккуратное расчесывание помогут сохранить длину комфортной.'],
 dry:['Сфокусируйся на кондиционировании, защите длины и снижении горячего воздействия.'],
 oily:['Не перегружай кожу головы тяжёлыми средствами и подбирай частоту мытья по комфорту.'],
 damaged:['Теплозащита и аккуратное обращение с длиной особенно важны при повреждённых волосах.'],
 colored:['Защищай цвет от частого сильного нагрева и поддерживай мягкое кондиционирование.']
};

function blankData(){
 const d=todayKey();
 return {
  settings:{name:'Красотка',skinType:'normal',hairType:'normal',city:'',theme:'pink',animations:true,notifications:false,weather:null,lastWeatherAt:0,avatar:'',avatarFrame:''},
  routines:[
   {id:uid(),startDate:d,title:'Мягкое очищение',category:'skin',slot:'morning',days:[1,2,3,4,5,6,0],time:'08:00',frequency:'daily',notes:'',productId:''},
   {id:uid(),startDate:d,title:'Увлажнение',category:'skin',slot:'morning',days:[1,2,3,4,5,6,0],time:'08:10',frequency:'daily',notes:'',productId:''},
   {id:uid(),startDate:d,title:'SPF',category:'skin',slot:'morning',days:[1,2,3,4,5,6,0],time:'08:15',frequency:'daily',notes:'',productId:''},
   {id:uid(),startDate:d,title:'Вечернее очищение',category:'skin',slot:'evening',days:[1,2,3,4,5,6,0],time:'21:00',frequency:'daily',notes:'',productId:''},
   {id:uid(),startDate:d,title:'Уход за длиной',category:'hair',slot:'extra',days:[2,5],time:'20:00',frequency:'weekly',notes:'',productId:''}
  ],
  logs:{}, products:[], photos:[], notes:[], goals:[], events:[], xp:0, level:1, unlocked:[],
  pet:{name:'Луна',kind:'котёнок',stage:1,hunger:70,happiness:72,energy:80,lastSeen:Date.now(),points:0,feedCount:0,playCount:0},
  challenges:[
   {id:'c1',title:'7 дней без пропусков',description:'Поддерживай уход каждый день.',goal:7,progress:0,reward:120,type:'auto-streak',done:false,builtIn:true},
   {id:'c2',title:'Фото-дневник',description:'Добавь 10 фотографий прогресса.',goal:10,progress:0,reward:150,type:'auto-photos',done:false,builtIn:true},
   {id:'c3',title:'30 дней ухода',description:'Накопи 30 выполненных дней.',goal:30,progress:0,reward:250,type:'auto-care-days',done:false,builtIn:true},
   {id:'c4',title:'Пять идеальных вечеров',description:'Заверши весь вечерний блок 5 раз.',goal:5,progress:0,reward:130,type:'auto-evening',done:false,builtIn:true}
  ],
  articlesRead:[], weatherChecks:0, themeChanges:0
 };
}

let data;
function load(){try{data=JSON.parse(localStorage.getItem(STORAGE_KEY))||blankData()}catch{data=blankData()} normalize();}
function normalize(){
 const base=blankData();
 if(!data || typeof data!=='object' || Array.isArray(data)) data=base;
 for(const k of Object.keys(base)) if(data[k]===undefined || data[k]===null) data[k]=structuredCloneSafe(base[k]);
 data.settings=(data.settings && typeof data.settings==='object' && !Array.isArray(data.settings))?{...base.settings,...data.settings}:{...base.settings};
 data.pet=(data.pet && typeof data.pet==='object' && !Array.isArray(data.pet))?{...base.pet,...data.pet}:{...base.pet};
 if(!Array.isArray(data.routines))data.routines=[]; if(!Array.isArray(data.products))data.products=[]; if(!Array.isArray(data.photos))data.photos=[]; if(!Array.isArray(data.notes))data.notes=[]; if(!Array.isArray(data.goals))data.goals=[]; if(!Array.isArray(data.events))data.events=[]; if(!Array.isArray(data.challenges))data.challenges=structuredCloneSafe(base.challenges);
 if(!data.logs || typeof data.logs!=='object' || Array.isArray(data.logs))data.logs={};
 if(!Array.isArray(data.unlocked))data.unlocked=[];
 if(!Array.isArray(data.favoriteProducts))data.favoriteProducts=[];
 if(!data.productRatings || typeof data.productRatings!=='object')data.productRatings={};
 if(!Array.isArray(data.productReviews))data.productReviews=[];
 if(!Array.isArray(data.articlesRead))data.articlesRead=[];
  const defaultSidebarOrder=['home','today','care','products','favorites','shop','calendar','progress','achievements','goals','journal','pet','challenges','tips','articles','reports','settings'];
  if(!Array.isArray(data.settings.sidebarOrder)) data.settings.sidebarOrder=defaultSidebarOrder.slice();
  data.settings.sidebarOrder=[...new Set(data.settings.sidebarOrder.filter(id=>defaultSidebarOrder.includes(id)))];
  for(const id of defaultSidebarOrder) if(!data.settings.sidebarOrder.includes(id)) data.settings.sidebarOrder.push(id);
 if(!Number.isFinite(Number(data.xp)))data.xp=0; data.xp=Math.max(0,Number(data.xp)); data.level=Math.max(1,Math.floor(data.xp/500)+1);
}
function structuredCloneSafe(v){try{return typeof structuredClone==='function'?structuredClone(v):JSON.parse(JSON.stringify(v))}catch{return v}}

function save(){try{localStorage.setItem(STORAGE_KEY,JSON.stringify(data));}catch(e){console.error('Save failed',e);toast('⚠️ Не удалось сохранить — не хватает места в хранилище. Удали несколько старых фото и попробуй снова.');}}
function defaultSidebarNav(){
 return [
  ['home','⌂','Главная'],['today','♡','Сегодня'],['care','🌸','Уход'],['products','🧴','Средства'],
  ['favorites','💗','Любимчики'],['shop','🛍️','Бьюти-магазин'],['calendar','📅','Календарь'],
  ['progress','◯','Прогресс'],['achievements','✦','Достижения'],['goals','🎯','Цели'],
  ['journal','✎','Дневник'],['pet','🐾','Питомец'],['challenges','🏆','Челленджи'],
  ['tips','💡','Советы'],['articles','📖','Статьи'],['reports','📊','Отчёты'],['settings','⚙','Настройки']
 ];
}
function getSidebarNav(){
 const base=defaultSidebarNav();
 const byId=Object.fromEntries(base.map(x=>[x[0],x]));
 const order=Array.isArray(data.settings.sidebarOrder)?data.settings.sidebarOrder:[];
 const ids=[...order,...base.map(x=>x[0]).filter(id=>!order.includes(id))];
 return ids.map(id=>byId[id]).filter(Boolean);
}
function moveSidebarItem(fromId,toId){
 if(!fromId||!toId||fromId===toId)return;
 const order=getSidebarNav().map(x=>x[0]);
 const from=order.indexOf(fromId), to=order.indexOf(toId);
 if(from<0||to<0)return;
 const [item]=order.splice(from,1);
 order.splice(to,0,item);
 data.settings.sidebarOrder=order;
 save();
 renderShell(location.hash.replace(/^#/,'')||'home');
 toast('Порядок вкладок сохранён ♡');
}
function bindSidebarDnD(){
 const nav=document.querySelector('.sidebar .nav');
 if(!nav)return;
 nav.querySelectorAll('button[data-sidebar-id],button[data-route]').forEach(btn=>{
  if(btn.dataset.dndBound==='1')return;
  btn.dataset.dndBound='1';
  if(!btn.dataset.sidebarId)btn.dataset.sidebarId=btn.dataset.route;
  btn.setAttribute('draggable','true');

  btn.addEventListener('dragstart',e=>{
   nav.__draggedBtn=btn;
   btn.classList.add('dragging');
   e.dataTransfer.effectAllowed='move';
   e.dataTransfer.setData('text/plain',btn.dataset.sidebarId);
  });

  btn.addEventListener('dragend',()=>{
   nav.__draggedBtn=null;
   nav.querySelectorAll('.dragging,.drag-over').forEach(el=>el.classList.remove('dragging','drag-over'));
  });

  btn.addEventListener('dragover',e=>{
   e.preventDefault();
   const dragged=nav.__draggedBtn;
   if(!dragged||dragged===btn)return;
   btn.classList.add('drag-over');
   e.dataTransfer.dropEffect='move';
  });

  btn.addEventListener('dragleave',()=>{
   btn.classList.remove('drag-over');
  });

  btn.addEventListener('drop',e=>{
   e.preventDefault();
   e.stopPropagation();

   const dragged=nav.__draggedBtn;
   btn.classList.remove('drag-over');
   if(!dragged||dragged===btn)return;

   // Physically move the card before the target card.
   // This prevents render() from immediately snapping it back.
   const rect=btn.getBoundingClientRect();
   const insertAfter=e.clientY > rect.top + rect.height/2;

   if(insertAfter) nav.insertBefore(dragged,btn.nextSibling);
   else nav.insertBefore(dragged,btn);

   // Save the exact current DOM order.
   const order=[...nav.querySelectorAll('button[data-sidebar-id]')]
     .map(x=>x.dataset.sidebarId);

   data.settings.sidebarOrder=order;
   save();

   nav.querySelectorAll('.dragging,.drag-over').forEach(el=>el.classList.remove('dragging','drag-over'));
   nav.__draggedBtn=null;

   toast('Порядок вкладок сохранён ♡');
  });
 });
}

const THEME_VAR_KEYS=['--bg','--surface','--surface2','--text','--muted','--primary','--primary2','--accent','--success','--danger','--border','--shadow'];
function applyTheme(){
 document.body.dataset.theme=data.settings.theme||'rose';const t=themes[data.settings.theme]||themes.pink;THEME_VAR_KEYS.forEach(k=>document.documentElement.style.removeProperty(k));for(const [k,v] of Object.entries(t.vars))document.documentElement.style.setProperty(k,v);document.querySelector('meta[name="theme-color"]').setAttribute('content',t.vars['--primary']||'#e889ad');}

const achievementDefs=[
 {id:'first-care',title:'Первый шаг',desc:'Выполни первую процедуру.',icon:'🌸',cat:'Ежедневные',check:()=>totalCompleted()>=1},
 {id:'perfect-day',title:'Идеальный день',desc:'Выполни 100% ухода за день.',icon:'✨',cat:'Ежедневные',check:()=>bestPerfectDays()>=1},
 {id:'streak3',title:'Три дня',desc:'Серия достигла 3 дней.',icon:'🔥',cat:'Серии',check:()=>currentStreak()>=3||bestStreak()>=3},
 {id:'streak7',title:'Семь дней',desc:'Серия достигла 7 дней.',icon:'🎀',cat:'Серии',check:()=>bestStreak()>=7},
 {id:'streak14',title:'Две недели',desc:'Серия достигла 14 дней.',icon:'🌷',cat:'Серии',check:()=>bestStreak()>=14},
 {id:'streak30',title:'Месяц ритма',desc:'Серия достигла 30 дней.',icon:'👑',cat:'Серии',check:()=>bestStreak()>=30},
 {id:'skin10',title:'Любовь к коже',desc:'10 выполненных процедур для кожи.',icon:'💗',cat:'Кожа',check:()=>completedByCat('skin')>=10},
 {id:'skin50',title:'Кожа — приоритет',desc:'50 процедур для кожи.',icon:'🌸',cat:'Кожа',check:()=>completedByCat('skin')>=50},
 {id:'hair10',title:'Любовь к волосам',desc:'10 процедур для волос.',icon:'🎀',cat:'Волосы',check:()=>completedByCat('hair')>=10},
 {id:'hair50',title:'Волосы под защитой',desc:'50 процедур для волос.',icon:'🫶',cat:'Волосы',check:()=>completedByCat('hair')>=50},
 {id:'photo1',title:'Первое фото',desc:'Добавь первое фото прогресса.',icon:'📸',cat:'Фото',check:()=>data.photos.length>=1},
 {id:'photo10',title:'Визуальный дневник',desc:'10 фотографий прогресса.',icon:'🖼️',cat:'Фото',check:()=>data.photos.length>=10},
 {id:'challenge1',title:'Первая победа',desc:'Заверши первый челлендж.',icon:'🏆',cat:'Челленджи',check:()=>data.challenges.filter(c=>c.done).length>=1},
 {id:'challenge5',title:'Мастер челленджей',desc:'Заверши 5 челленджей.',icon:'🏅',cat:'Челленджи',check:()=>data.challenges.filter(c=>c.done).length>=5},
 {id:'pet-feed10',title:'Заботливая хозяйка',desc:'Покорми питомца 10 раз.',icon:'🐾',cat:'Питомец',check:()=>data.pet.feedCount>=10},
 {id:'pet-evo',title:'Большой рост',desc:'Питомец достиг третьей стадии.',icon:'✨',cat:'Питомец',check:()=>data.pet.stage>=3},
 {id:'weather10',title:'Погодный вайб',desc:'Проверь прогноз 10 раз.',icon:'☁️',cat:'Погода',check:()=>data.weatherChecks>=10},
 {id:'articles5',title:'Beauty-читательница',desc:'Прочитай 5 мини-статей.',icon:'📖',cat:'Знания',check:()=>data.articlesRead.length>=5},
 {id:'theme3',title:'Настроение меняется',desc:'Смени тему 3 раза.',icon:'🎨',cat:'Стили',check:()=>data.themeChanges>=3},
 {id:'night-owl',title:'Тайный ночной ритуал',desc:'Открой приложение между 03:00 и 04:00.',icon:'🌙',cat:'Скрытые',hidden:true,check:()=>new Date().getHours()===3},
 {id:'midnight',title:'После полуночи',desc:'Отметь процедуру между 00:00 и 00:59.',icon:'🌌',cat:'Скрытые',hidden:true,check:()=>Object.values(data.logs).some(v=>v?.some(x=>x.done&&x.timeStamp&&new Date(x.timeStamp).getHours()===0))}
];

function entriesForDay(key){
 const d=dateObj(key), day=d.getDay();
 return data.routines.filter(r=>{
   if(!r.days?.includes(day)) return false;
   const start=dateObj(r.startDate||key);
   if(r.frequency==='biweekly'){ const diff=Math.floor((d-start)/86400000); if(diff<0 || Math.floor(diff/7)%2!==0) return false; }
   if(r.frequency==='monthly' && d.getDate()!==start.getDate()) return false;
   return true;
 });
}
function logsFor(key){return data.logs[key]||[]}
function isDone(key,id){return logsFor(key).some(x=>x.routineId===id&&x.done)}
function completedIds(key){return logsFor(key).filter(x=>x.done).map(x=>x.routineId)}
function dayStats(key){const all=entriesForDay(key),done=all.filter(r=>isDone(key,r.id));return {all,done,p:pct(done.length,all.length)}}
function totalCompleted(){return Object.values(data.logs).flat().filter(x=>x.done).length}
function completedByCat(cat){return Object.entries(data.logs).reduce((s,[day,arr])=>s+arr.filter(x=>x.done&&data.routines.find(r=>r.id===x.routineId)?.category===cat).length,0)}
function perfectDays(){return Object.keys(data.logs).filter(k=>{const s=dayStats(k);return s.all.length&&s.p===100})}
function bestPerfectDays(){return perfectDays().length}
function currentStreak(){let n=0;let d=new Date();while(true){const k=localKey(d);const s=dayStats(k);if(s.all.length&&s.p===100)n++;else break;d.setDate(d.getDate()-1);}return n}
function bestStreak(){const dates=[...new Set(Object.keys(data.logs).concat(entriesDatesPast(400)))].sort();let best=0,run=0,prev=null;for(const k of dates){const s=dayStats(k);if(s.all.length&&s.p===100){if(prev){const dd=(dateObj(k)-dateObj(prev))/86400000;if(dd===1)run++;else run=1}else run=1;best=Math.max(best,run);prev=k}else{run=0;prev=null}}return best}
function entriesDatesPast(n){const out=[];const d=new Date();for(let i=0;i<n;i++){out.push(localKey(d));d.setDate(d.getDate()-1)}return out}
function statsRange(days){const out=[];const d=new Date();for(let i=days-1;i>=0;i--){const x=new Date(d);x.setDate(d.getDate()-i);const k=localKey(x);out.push({date:k,...dayStats(k)})}return out}
function levelInfo(){const lv=Math.floor(data.xp/500)+1;const cur=data.xp%500;return {lv,cur,next:500};}
function addXP(n,why=''){data.xp+=n;const before=data.level;data.level=levelInfo().lv;if(data.level>before)toast(`Уровень повышен! ✨ Теперь уровень ${data.level}`);if(why)toast(`+${n} XP · ${why}`);save();}
function complete(id,key=todayKey()){
 const r=data.routines.find(x=>x.id===id);if(!r)return;
 const arr=data.logs[key]||(data.logs[key]=[]);if(arr.some(x=>x.routineId===id&&x.done)){toast('Уже выполнено ♡');return}
 arr.push({routineId:id,done:true,timeStamp:Date.now()});addXP(10,r.slot==='extra'?'Дополнительный уход':'Уход');
 data.pet.happiness=clamp(data.pet.happiness+4);data.pet.hunger=clamp(data.pet.hunger+2);data.pet.points+=5;checkPetEvolution();refreshChallenges();checkAchievements();save();render();
 if(dayStats(key).p===100){addXP(25,'Идеальный день');toast(random(['Ты сделала это! ✨','Идеальный день, красотка ♡','Вся рутина закрыта — умница! 🌷']))}
}
function undo(id,key=todayKey()){if(!data.logs[key])return;data.logs[key]=data.logs[key].filter(x=>x.routineId!==id);save();render();}
function random(a){return a[Math.floor(Math.random()*a.length)]}
function toast(msg){const wrap=document.getElementById('toasts');if(!wrap)return;const el=document.createElement('div');el.className='toast';el.textContent=msg;wrap.appendChild(el);setTimeout(()=>el.remove(),2800)}

function checkAchievements(){for(const a of achievementDefs){if(data.unlocked.includes(a.id))continue;try{if(a.check()){data.unlocked.push(a.id);addXP(50,'Новое достижение');toast(`Достижение открыто: ${a.title} ${a.icon}`)}}catch{}}
save();}
function refreshChallenges(){
 const careDays=Object.keys(data.logs).filter(k=>dayStats(k).done.length>0).length;
 for(const c of data.challenges){if(c.done)continue;let p=c.progress;
  if(c.type==='auto-streak')p=currentStreak();
  if(c.type==='auto-photos')p=data.photos.length;
  if(c.type==='auto-care-days')p=careDays;
  if(c.type==='auto-evening')p=Object.keys(data.logs).filter(k=>{const rs=entriesForDay(k).filter(r=>r.slot==='evening');return rs.length>0&&rs.every(r=>isDone(k,r.id))}).length;
  c.progress=clamp(p,0,c.goal);if(c.progress>=c.goal&&!c.done){c.done=true;addXP(c.reward,'Челлендж завершён');toast(`Челлендж «${c.title}» завершён 🏆`)}
 }
 save();
}
function checkPetEvolution(){if(data.pet.points>=150)data.pet.stage=3;else if(data.pet.points>=50)data.pet.stage=2;}
function tickPet(){const now=Date.now(),diff=(now-data.pet.lastSeen)/3600000;if(diff>=1){data.pet.hunger=clamp(data.pet.hunger-diff*4);data.pet.happiness=clamp(data.pet.happiness-diff*2);data.pet.energy=clamp(data.pet.energy+diff*2);data.pet.lastSeen=now;save()}}
function petEmoji(){const s=Math.max(1,Math.min(10,Number(data.pet.stage)||1));return ['🐱','😺','😸','😽','😻','😺','😸','😻','😼','🐱'][s-1]}
function petMood(){const s=(data.pet.hunger+data.pet.happiness+data.pet.energy)/3;return s>75?'Сияет от заботы ✨':s>50?'Довольный и спокойный ♡':'Ему не хватает внимания 🥺'}
function petFeed(){const now=Date.now();if(window.__lastPetAction&&now-window.__lastPetAction<350)return;window.__lastPetAction=now;data.pet.hunger=clamp(data.pet.hunger+20);data.pet.happiness=clamp(data.pet.happiness+3);data.pet.feedCount++;addXP(5,'Забота о питомце');checkAchievements();save();render();}
function petPlay(){const now=Date.now();if(window.__lastPetAction&&now-window.__lastPetAction<350)return;window.__lastPetAction=now;if(data.pet.energy<15){toast('Питомец устал — дай ему немного отдохнуть ♡');return}data.pet.happiness=clamp(data.pet.happiness+14);data.pet.energy=clamp(data.pet.energy-15);data.pet.playCount++;addXP(5,'Игра с питомцем');save();render();}

function recommendation(){
 const st=skinTips[data.settings.skinType]||skinTips.normal;const ht=hairTips[data.settings.hairType]||hairTips.normal;const w=data.settings.weather;
 let tip=random([...st,...ht]);if(w){const desc=(w.description||'').toLowerCase();if(desc.includes('дожд')||desc.includes('snow')||desc.includes('rain'))tip='Сегодня влажно или осадки — не забывай про бережное обращение с волосами и комфортный слой увлажнения.';if(w.temp>=27)tip='Сегодня жарко: SPF, лёгкие текстуры и дополнительное внимание к коже после улицы будут особенно кстати.';if(w.temp<=5)tip='Сегодня прохладно: защити кожу от сухого воздуха и не забывай про комфортный крем.'}
 return tip;
}
async function fetchWeather(){
 const city=data.settings.city.trim();if(!city){toast('Укажи город в настройках ♡');return}
 try{toast('Ищу погоду… ☁️');const geo=await fetch(`https://geocoding-api.open-meteo.com/v1/search?name=${encodeURIComponent(city)}&count=1&language=ru&format=json`).then(r=>r.json());if(!geo.results?.[0])throw Error('city');const g=geo.results[0];const w=await fetch(`https://api.open-meteo.com/v1/forecast?latitude=${g.latitude}&longitude=${g.longitude}&current=temperature_2m,relative_humidity_2m,weather_code,wind_speed_10m&timezone=auto`).then(r=>r.json());const code=w.current.weather_code;const desc=weatherText(code);data.settings.weather={city:g.name,temp:Math.round(w.current.temperature_2m),humidity:w.current.relative_humidity_2m,wind:Math.round(w.current.wind_speed_10m),code,description:desc,at:Date.now()};data.settings.lastWeatherAt=Date.now();data.weatherChecks=(data.weatherChecks||0)+1;checkAchievements();save();toast('Погода обновлена ♡');render();}catch(e){toast('Не удалось получить погоду. Показываю последнюю сохранённую.');}}
function weatherText(code){if(code===0)return'Ясно';if([1,2,3].includes(code))return'Облачно';if([45,48].includes(code))return'Туман';if([51,53,55,56,57].includes(code))return'Морось';if([61,63,65,66,67,80,81,82].includes(code))return'Дождь';if([71,73,75,77,85,86].includes(code))return'Снег';if([95,96,99].includes(code))return'Гроза';return'Переменная погода'}
function weatherIcon(desc=''){const d=desc.toLowerCase();if(d.includes('дожд'))return'🌧️';if(d.includes('снег'))return'❄️';if(d.includes('гроза'))return'⛈️';if(d.includes('туман'))return'🌫️';if(d.includes('облач'))return'☁️';return'☀️'}


/* ================= SMART BEAUTY PLAN + AFTER EVENT ================= */
const MBJ_EVENT_DEFS = {
  workout:{icon:'🏃',title:'После тренировки',sub:'пот + душ + восстановление',
    steps:['Мягко очистить кожу после тренировки.','Принять душ и не использовать слишком горячую воду.','Увлажнить тело по ощущениям.','Сделать базовый уход за кожей.','Для волос — кондиционер на длину, если был пот/мытьё.'],
    avoid:['агрессивный скраб сразу после тренировки','долгое пребывание в потной одежде'],
    note:'Главная цель — убрать пот и вернуть комфорт коже и телу без перегруза.'},
  beach:{icon:'🏖️',title:'После пляжа',sub:'солнце + соль/песок',
    steps:['Аккуратно смыть соль, песок и солнцезащитные средства.','Мягко очистить кожу без лишнего трения.','Нанести увлажняющий уход на лицо и тело.','Для волос — кондиционер/маска на длину после контакта с морской водой.','Сегодня вечером не перегружать уход дополнительными активами.'],
    avoid:['горячую укладку','жёсткое скрабирование раздражённой кожи'],
    note:'После длительного солнца приоритет — комфорт, очищение и восстановление.'},
  sun:{icon:'☀️',title:'Много солнца',sub:'солнечная нагрузка',
    steps:['Мягко очистить открытые участки кожи.','Увлажнить кожу и тело по ощущениям.','Нанести спокойный базовый уход без экспериментов.','Волосы — кондиционер или восстанавливающий уход на длину.','Завтра снова использовать солнцезащиту перед выходом.'],
    avoid:['интенсивные домашние процедуры на раздражённой коже','горячую укладку'],
    note:'Если кожа явно раздражена или болезненна, лучше не усиливать домашний уход.'},
  pool:{icon:'🏊',title:'После бассейна',sub:'хлор + вода + волосы',
    steps:['Смыть воду бассейна с кожи и волос.','Мягко очистить кожу при необходимости.','Увлажнить лицо и тело.','Нанести кондиционер/маску на длину волос.','Не оставлять влажные волосы надолго под тугой резинкой.'],
    avoid:['оставлять хлорированную воду на волосах','жёстко тереть волосы полотенцем'],
    note:'После бассейна особенно важны мягкое очищение и кондиционирование длины.'},
  rain:{icon:'🌧️',title:'После дождя',sub:'влага + промокшие волосы',
    steps:['Переодеться в сухую одежду.','Мягко промокнуть волосы полотенцем, не растирать.','Если кожа промокла/замёрзла — вернуть ей комфорт мягким уходом.','Дать волосам спокойно подсохнуть.','Вечером выполнить обычную базовую рутину.'],
    avoid:['туго завязывать мокрые волосы','агрессивно растирать кожу и длину'],
    note:'Главное после дождя — убрать влагу аккуратно и снизить трение.'},
  wind:{icon:'💨',title:'После сильного ветра',sub:'сухость + трение',
    steps:['Мягко очистить кожу от загрязнений улицы.','Увлажнить сухие участки лица.','Нанести защитный бальзам на губы.','На длину волос — небольшое количество кондиционирующего ухода при сухости.','На ночь оставить кожу и волосы в спокойном состоянии без лишнего стайлинга.'],
    avoid:['жёсткий скраб','сильное трение полотенцем'],
    note:'Ветер часто означает больше трения и сухости — вечером лучше спокойный уход.'},
  makeup:{icon:'💄',title:'Макияж весь день',sub:'долгое ношение макияжа',
    steps:['Тщательно, но мягко снять макияж.','Умыться подходящим мягким средством.','Нанести увлажняющий уход.','Если кожа устала — оставить вечер максимально простым.','Очистить кисти/спонжи, если они использовались.'],
    avoid:['ложиться спать с макияжем','агрессивно тереть область глаз'],
    note:'После долгого макияжа полезнее качественно снять его, чем добавлять много активов.'},
  sleep:{icon:'😴',title:'Мало сна',sub:'день восстановления',
    steps:['Оставить только базовый уход.','Увлажнить кожу по ощущениям.','Сделать короткий уход за волосами без сложных процедур.','Вечером выбрать максимально спокойную рутину.','Не пытаться «компенсировать» усталость десятком средств.'],
    avoid:['перегружать кожу активами','делать длинную сложную рутину через силу'],
    note:'Сегодня задача — сохранить рутину простой и выполнимой.'},
  shower:{icon:'🚿',title:'Долгий душ',sub:'горячая вода + сухость',
    steps:['После душа аккуратно промокнуть кожу.','Нанести увлажняющий крем/лосьон на тело.','На лицо — привычный базовый увлажняющий уход.','Для волос — кондиционер, если длина стала сухой.','В следующий раз держать воду комфортно тёплой, а не очень горячей.'],
    avoid:['дополнительное агрессивное очищение','сильное растирание кожи полотенцем'],
    note:'После долгого душа особенно важен комфорт кожи и мягкое восстановление.'}
};

function ensureEventState(){
  if(!data.afterEvents) data.afterEvents={date:'',selected:[]};
  const todayKey=new Date().toISOString().slice(0,10);
  if(data.afterEvents.date!==todayKey){
    data.afterEvents={date:todayKey,selected:[]};
  }
  return data.afterEvents;
}
function smartWeatherSnapshot(){
  const w=data.settings?.weather||{};
  return {temp:Number(w.temp),humidity:Number(w.humidity),wind:Number(w.wind),uv:Number(w.uv),desc:String(w.description||'').toLowerCase()};
}
function buildSmartBeautyPlan(){
  const w=smartWeatherSnapshot();
  const plan=[], avoid=[];
  const add=(icon,text,key)=>plan.push({icon,text,key});
  const no=(icon,text)=>avoid.push({icon,text});

  if(Number.isFinite(w.uv) && w.uv>=6) add('☀️','SPF перед выходом; при длительном пребывании на улице учитывай обновление защиты.','spf');
  if(Number.isFinite(w.humidity) && w.humidity<=35) add('💧','Дополнительное увлажнение кожи; для сухой длины — кондиционер или немного несмываемого ухода.','dry');
  if(Number.isFinite(w.humidity) && w.humidity>=80) add('🌫️','Лёгкие текстуры и меньше слоёв; если волосы пушатся — немного разглаживающего ухода по длине.','humid');
  if(Number.isFinite(w.wind) && w.wind>=20) add('💨','Защити губы и сухие участки кожи; убери длину волос от постоянного трения об одежду.','wind');
  if(Number.isFinite(w.temp) && w.temp<=5) add('🛡️','Перед улицей защити открытые участки кожи; вечером выбери мягкое очищение и восстановление.','cold');
  if(Number.isFinite(w.temp) && w.temp>=27) add('🧴','Лёгкие текстуры, мягкое очищение после пота и меньше горячей укладки.','heat');
  if(/дожд|морос/.test(w.desc)) add('🌧️','Защити волосы от промокания; после улицы аккуратно промокни их, не растирая.','rain');
  if(/снег/.test(w.desc)) add('❄️','Защити губы и открытые участки кожи; не выходи с влажными волосами.','snow');
  if(/туман/.test(w.desc)) add('🌫️','При высокой влажности не перегружай волосы стайлингом и маслами.','fog');
  if(/гроза/.test(w.desc)) add('⛈️','Если остаёшься дома — выбери спокойный восстановительный вечер.','storm');

  // Персональные состояния из дневника, если они уже существуют.
  const s=data.skinToday||data.skinState||{};
  const h=data.hairToday||data.hairState||{};
  const drySkin=Number(s.dryness||s.dry||0)>=4;
  const sensitive=Number(s.sensitivity||0)>=4;
  const dryHair=Number(h.dryness||h.dry||0)>=4;
  const frizz=Number(h.frizz||h.puffiness||0)>=4;

  if(drySkin) add('🌸','Кожа сегодня отмечена как сухая — сделай акцент на комфортном увлажнении.','skin-dry');
  if(sensitive){
    add('🫧','Кожа отмечена как чувствительная — оставь только спокойный базовый уход.','sensitive');
    no('⚠️','Сегодня лучше не перегружать уход активными процедурами.');
  }
  if(dryHair) add('🎀','Волосы отмечены как сухие — кондиционер/маска + аккуратный несмываемый уход по длине.','hair-dry');
  if(frizz) add('🎀','Сегодня волосы пушатся — уменьши трение и используй небольшое количество разглаживающего ухода.','frizz');

  // Всегда сохраняем базовые пункты.
  if(!plan.some(x=>x.key==='base-skin')) add('🌸','Выполни базовый уход за кожей по своей рутине.','base-skin');
  if(!plan.some(x=>x.key==='base-hair')) add('🎀','Волосы: выполни запланированный уход, без лишней горячей укладки.','base-hair');
  add('🌙','Вечером: мягкое очищение → увлажнение → восстановление по ощущениям.','evening');

  // Что сегодня логично сократить.
  if(Number.isFinite(w.temp)&&w.temp>=27) no('🔥','Слишком горячую укладку и перегруз плотными текстурами.');
  if(Number.isFinite(w.humidity)&&w.humidity>=80) no('🌫️','Большое количество тяжёлых масел/стайлинга при сильной влажности.');
  if(Number.isFinite(w.temp)&&w.temp<=0) no('❄️','Интенсивные процедуры непосредственно перед выходом на мороз.');
  if(Number.isFinite(w.wind)&&w.wind>=25) no('💨','Лишнее трение кожи и волос: скрабы, жёсткие полотенца, тугие причёски.');
  if(Number.isFinite(w.uv)&&w.uv>=8) no('☀️','Долгое пребывание под прямым солнцем без защиты.');

  const unique=(arr)=>{const seen=new Set();return arr.filter(x=>{if(seen.has(x.text))return false;seen.add(x.text);return true;});};
  return {plan:unique(plan).slice(0,9),avoid:unique(avoid).slice(0,5)};
}
function renderSmartBeautyPlan(){
  const root=document.querySelector('[data-smart-beauty-plan]');
  if(!root)return;
  const p=buildSmartBeautyPlan();
  const w=smartWeatherSnapshot();
  const eventState=ensureEventState();
  root.innerHTML=`<section class="smart-plan-hero">
    <div class="smart-plan-main">
      <div class="smart-plan-kicker">🧠 Умный Beauty-план</div>
      <h3 class="smart-plan-title">Твой план на сегодня</h3>
      <p class="smart-plan-sub">Приложение собирает его из погоды, твоих отметок и событий дня.</p>
      <div class="smart-plan-chips">
        ${Number.isFinite(w.temp)?`<span class="tag">🌡️ ${w.temp}°C</span>`:''}
        ${Number.isFinite(w.humidity)?`<span class="tag">💧 ${w.humidity}%</span>`:''}
        ${Number.isFinite(w.wind)?`<span class="tag">💨 ${w.wind} км/ч</span>`:''}
        ${Number.isFinite(w.uv)?`<span class="tag">☀️ UV ${w.uv.toFixed(0)}</span>`:''}
      </div>
      <div class="smart-plan-list">
        ${p.plan.map((x,i)=>`<div class="smart-plan-item" data-plan-item="${i}">
          <span class="ico">${x.icon}</span><span class="txt">${esc(x.text)}</span>
          <button class="btn secondary small" data-plan-check="${i}">✓</button>
        </div>`).join('')}
      </div>
      ${p.avoid.length?`<div class="smart-plan-avoid"><div class="smart-plan-avoid-title">Сегодня лучше НЕ делать</div>
        ${p.avoid.map(x=>`<div class="row" style="gap:8px;margin-top:7px"><span>${x.icon}</span><span>${esc(x.text)}</span></div>`).join('')}
      </div>`:''}
      <div class="smart-plan-actions">
        <button class="btn" data-build-smart-plan>✨ Собрать мой день</button>
        <button class="btn secondary" data-go-events>🚿 Было событие</button>
      </div>
      <div class="smart-note">План — помощник для организации ухода. Он не заменяет медицинские рекомендации и не диагностирует состояние кожи/волос.</div>
    </div>
    <aside class="smart-plan-side">
      <h4>🎯 Фокус дня</h4>
      <div class="smart-plan-score">${Math.min(100,Math.round((p.plan.length/9)*100))}%</div>
      <div class="smart-plan-mini">насколько полно удалось учесть доступные факторы сегодня</div>
      <div style="margin-top:14px">
        <div class="smart-plan-factor"><span>Погода</span><strong>${w.desc||'—'}</strong></div>
        <div class="smart-plan-factor"><span>События</span><strong>${eventState.selected.length}</strong></div>
        <div class="smart-plan-factor"><span>Не делать</span><strong>${p.avoid.length}</strong></div>
      </div>
    </aside>
  </section>`;
}
function renderAfterEventPanel(){
  const root=document.querySelector('[data-after-events]');
  if(!root)return;
  const st=ensureEventState();
  const defs=Object.entries(MBJ_EVENT_DEFS);
  const selected=st.selected;
  let combined=[];
  let avoid=[];
  selected.forEach(k=>{const e=MBJ_EVENT_DEFS[k];if(e){combined.push(...e.steps);avoid.push(...e.avoid);}});
  const unique=a=>[...new Set(a)];
  combined=unique(combined); avoid=unique(avoid);

  root.innerHTML=`<section class="card event-panel">
    <div class="label">ПОСЛЕ СОБЫТИЯ</div>
    <h3 class="section-title">🚿 Сегодня было что-то из этого?</h3>
    <p class="subtle">Выбери всё, что было сегодня — вечерний план изменится автоматически.</p>
    <div class="event-grid">
      ${defs.map(([key,e])=>`<button class="event-btn ${selected.includes(key)?'active':''}" data-event-toggle="${key}">
        <span class="event-ico">${e.icon}</span><strong>${e.title}</strong><span>${e.sub}</span>
      </button>`).join('')}
    </div>
    ${selected.length?`<div class="event-result">
      <h4>🌙 Твой вечерний план</h4>
      <p class="subtle">Учитываем: ${selected.map(k=>MBJ_EVENT_DEFS[k].icon+' '+MBJ_EVENT_DEFS[k].title).join(' · ')}</p>
      <div class="event-steps">${combined.slice(0,8).map((x,i)=>`<div class="event-step"><b>${i+1}</b><span>${esc(x)}</span></div>`).join('')}</div>
      ${avoid.length?`<div class="smart-plan-avoid" style="margin-top:12px"><strong>Сегодня лучше не перегружать:</strong>${avoid.slice(0,5).map(x=>`<div style="margin-top:6px">❌ ${esc(x)}</div>`).join('')}</div>`:''}
      <div class="smart-note">Если одновременно выбрано несколько событий, рекомендации объединяются без дублирования.</div>
    </div>`:
    `<div class="event-result"><div class="event-empty">Пока ничего не выбрано. Отметь событие — и здесь появится персональный вечерний план.</div></div>`}
  </section>`;
}
function saveAfterEventState(){
  save();
}

function render(){
 applyTheme();tickPet();refreshChallenges();checkAchievements();
 const route=location.hash.replace(/^#/,'')||'home';
 renderShell(route);renderPage(route);maybeAutoWeather();
}
function renderShell(route){
 const titleMap={lab:'Лаборатория состава',home:'Главная',today:'Сегодня',care:'Уход',products:'Средства',calendar:'Календарь',progress:'Прогресс',achievements:'Достижения',goals:'Цели',journal:'Дневник',pet:'Питомец',challenges:'Челленджи',tips:'Советы',articles:'Мини-статьи',reports:'Отчёты','hair-growth':'Рост волос',settings:'Настройки'};
 const nav=[['home','⌂','Главная'],['today','♡','Сегодня'],['care','🌸','Уход'],['products','🧴','Средства'],['calendar','📅','Календарь'],['progress','◯','Прогресс'],['achievements','✦','Достижения'],['goals','🎯','Цели'],['journal','✎','Дневник'],['pet','🐾','Питомец'],['challenges','🏆','Челленджи'],['tips','💡','Советы'],['articles','📖','Статьи'],['reports','📊','Отчёты'],['hair-growth','📏','Рост волос'],['settings','⚙','Настройки']];
 document.getElementById('app').innerHTML=`<aside class="sidebar"><div class="brand"><h1>Мой Бьюти-дневник ♡</h1><p>Твой личный дневник ухода</p></div><div class="nav">${nav.map(([id,ic,l])=>`<button data-route="${id}" class="${route===id?'active':''}"><span>${ic}</span>${l}</button>`).join('')}</div><div class="sidebar-bottom"><div class="stat"><span class="label">Уровень</span><b>${data.level}</b><span class="subtle">${data.xp} XP</span></div></div></aside><main class="main"><header class="topbar"><div class="topbar-title"><button class="icon-btn" id="mobileMenu">☰</button><h2>${titleMap[route]||'Мой Бьюти-дневник'}</h2></div><div class="row"><span class="tag">🔥 ${currentStreak()} дней</span><button class="icon-btn" data-route="settings">⚙</button></div></header><section class="content" id="page"></section><nav class="bottom-nav">${[['home','⌂','Главная'],['today','♡','Сегодня'],['care','🌸','Уход'],['progress','◯','Прогресс'],['more','☰','Ещё']].map(([id,ic,l])=>`<button data-route="${id}" class="${route===id?'active':''}"><div>${ic}</div>${l}</button>`).join('')}</nav></main>`;
 document.querySelectorAll('[data-route]').forEach(el=>el.addEventListener('click',()=>{const r=el.dataset.route;if(r==='more')openMore();else location.hash=r}));
 document.getElementById('mobileMenu')?.addEventListener('click',()=>window.openMore());
}
function renderPage(route){const p=document.getElementById('page');const map={lab:labPage,home:homePage,today:todayPage,care:carePage,products:productsPage,calendar:calendarPage,progress:progressPage,achievements:achievementsPage,goals:goalsPage,journal:journalPage,pet:petPage,challenges:challengesPage,tips:tipsPage,articles:articlesPage,reports:reportsPage,settings:settingsPage};p.innerHTML=(map[route]||homePage)();bindPage(route)}
function openMore(){
 const links=[['products','🧴 Средства'],['calendar','📅 Календарь'],['achievements','✦ Достижения'],['goals','🎯 Цели'],['journal','✎ Дневник'],['pet','🐾 Питомец'],['challenges','🏆 Челленджи'],['tips','💡 Советы'],['articles','📖 Статьи'],['reports','📊 Отчёты'],['settings','⚙ Настройки']];
 modal(`<h3>Ещё ♡</h3><div class="list">${links.map(([id,t])=>`<button class="btn secondary" data-more="${id}">${t}</button>`).join('')}</div>`);document.querySelectorAll('[data-more]').forEach(b=>b.onclick=()=>{closeModal();location.hash=b.dataset.more});
}
function homePage(){const s=dayStats(todayKey());const si=dayStats(todayKey()).all.filter(r=>r.category==='skin');const hi=dayStats(todayKey()).all.filter(r=>r.category==='hair');const skinDone=si.filter(r=>isDone(todayKey(),r.id)).length;const hairDone=hi.filter(r=>isDone(todayKey(),r.id)).length;const lv=levelInfo();const w=data.settings.weather;return `<div class="grid" style="gap:16px"><section class="card hero"><div class="split"><div style="flex:1"><div class="label">${fmtDate(todayKey())}</div><h1>${greeting()}, ${esc(data.settings.name)} ♡</h1><p>${s.p===100?'Сегодня всё закрыто — потрясающе ✨':'Давай сделаем сегодняшний уход чуть-чуть красивее.'}</p><div class="row wrap" style="margin-top:16px"><button class="btn" data-action="quickRoutine">♡ Открыть Сегодня</button><button class="btn secondary" data-route="pet">🐾 К питомцу</button></div></div><div class="circle" style="--p:${s.p}"><div class="inside"><span class="label">Сегодня</span><strong>${s.p}%</strong><span class="subtle">${s.done.length}/${s.all.length}</span></div></div></div></section>
<section class="grid grid-4"><div class="stat"><span class="label">Streak</span><b>🔥 ${currentStreak()}</b><span class="subtle">Лучший: ${bestStreak()}</span></div><div class="stat"><span class="label">Уровень</span><b>${data.level}</b><span class="subtle">${lv.cur}/500 XP</span></div><div class="stat"><span class="label">Достижения</span><b>${data.unlocked.length}/${achievementDefs.length}</b><span class="subtle">Открыто</span></div><div class="stat"><span class="label">Питомец</span><b>${petEmoji()}</b><span class="subtle">${petMood()}</span></div></section>
<section class="grid grid-3"><div class="card"><div class="row between"><h3 class="section-title">🌸 Кожа</h3><div class="circle small-circle" style="--p:${pct(skinDone,si.length)}"><div class="inside"><strong>${pct(skinDone,si.length)}%</strong></div></div></div><p class="subtle">Сегодня выполнено ${skinDone} из ${si.length} этапов.</p></div><div class="card"><div class="row between"><h3 class="section-title">🎀 Волосы</h3><div class="circle small-circle" style="--p:${pct(hairDone,hi.length)}"><div class="inside"><strong>${pct(hairDone,hi.length)}%</strong></div></div></div><p class="subtle">Сегодня выполнено ${hairDone} из ${hi.length} этапов.</p></div><div class="card"><h3 class="section-title">☁️ Погода</h3>${w?`<div class="row"><div style="font-size:40px">${weatherIcon(w.description)}</div><div><div class="kpi">${w.temp}°</div><div class="subtle">${esc(w.city)} · ${w.description}</div></div></div><p class="subtle" style="margin-top:12px">Влажность ${w.humidity}% · Ветер ${w.wind} км/ч${w.uv!=null?` · UV ${w.uv.toFixed(1)}`:''}</p>${w.uv!=null?`<div class="tag" style="margin-top:10px">${w.uv>=8?'🔴 UV экстремальный — сократи время на солнце и обнови SPF':(w.uv>=6?'☀️ Высокий UV — SPF особенно важен':(w.uv>=3?'🌤️ UV умеренный — обычной защиты достаточно':'🌥️ UV низкий — особая защита не требуется'))}</div>`:''}`:`<div class="empty">Укажи город в настройках, чтобы добавить погоду.</div>`}<button class="btn secondary small" data-action="weather" style="margin-top:10px">Обновить погоду</button></div></section>
<section class="grid grid-2"><div class="card"><h3 class="section-title">💡 Персональный совет</h3><p style="font-size:16px;line-height:1.6">${esc(recommendation())}</p><div class="row wrap"><span class="tag">Кожа: ${skinTypeName(data.settings.skinType)}</span><span class="tag">Волосы: ${hairTypeName(data.settings.hairType)}</span></div></div><div class="card"><div class="row between"><h3 class="section-title">🐾 Твой питомец</h3><button class="btn secondary small" data-route="pet">Открыть</button></div><div class="split"><div class="pet">${petEmoji()}</div><div style="flex:1"><div class="pet-stage">${esc(data.pet.name)}</div><div class="subtle">${petMood()}</div>${bar('Счастье',data.pet.happiness)}${bar('Сытость',data.pet.hunger)}${bar('Энергия',data.pet.energy)}</div></div></div></section>
<section class="card"><div class="row between"><h3 class="section-title">🏆 Активные челленджи</h3><button class="btn secondary small" data-route="challenges">Все челленджи</button></div><div class="grid grid-3">${data.challenges.slice(0,3).map(challengeCard).join('')}</div></section>
<section class="card"><div class="row between"><h3 class="section-title">📖 Сегодняшняя мини-статья</h3><button class="btn secondary small" data-route="articles">Все статьи</button></div>${articleTeaser()}</section></div>`}
function greeting(){const h=new Date().getHours();return h<5?'Не спишь?':h<12?'Доброе утро':h<18?'Добрый день':'Добрый вечер'}
function skinTypeName(x){return {normal:'нормальная',dry:'сухая',oily:'жирная',combination:'комбинированная',sensitive:'чувствительная'}[x]||x}
function hairTypeName(x){return {normal:'нормальные',dry:'сухие',oily:'жирные',damaged:'повреждённые',colored:'окрашенные'}[x]||x}
function bar(label,val){return `<div class="bar-row"><span class="subtle">${label}</span><div class="progress"><i style="width:${val}%"></i></div><strong>${Math.round(val)}%</strong></div>`}
function challengeCard(c){return `<div class="item challenge ${c.done?'done':''}"><div class="row between"><strong>${esc(c.title)}</strong>${c.done?'✅':'🎯'}</div><p>${esc(c.description)}</p><div class="progress" style="margin-top:10px"><i style="width:${pct(c.progress,c.goal)}%"></i></div><div class="subtle" style="margin-top:6px">${c.progress}/${c.goal} · +${c.reward} XP</div></div>`}
function articleTeaser(){const a=articles[Math.floor(new Date().getDate()%articles.length)];return `<div class="item article" data-article="${a.id}"><span class="tag">${a.tag}</span><h4>${esc(a.title)}</h4><p>${esc(a.text.slice(0,190))}…</p></div>`}

function todayPage(){const s=dayStats(todayKey());const by={morning:s.all.filter(r=>r.slot==='morning'),evening:s.all.filter(r=>r.slot==='evening'),extra:s.all.filter(r=>r.slot==='extra')};return `<div class="grid grid-2"><section class="card"><div class="row between"><div><h3 class="section-title">Сегодняшний уход ♡</h3><p class="subtle">${s.done.length} из ${s.all.length} · ${s.p}%</p></div><div class="circle small-circle" style="--p:${s.p}"><div class="inside"><strong>${s.p}%</strong></div></div></div></section><section class="card"><h3 class="section-title">💡 Совет</h3><p style="line-height:1.6">${esc(recommendation())}</p></section></div><div class="grid grid-3" style="margin-top:16px">${routineBlock('Утро ♡',by.morning)}${routineBlock('Вечер ♡',by.evening)}${routineBlock('Extra Care 🎀',by.extra)}</div><div data-smart-beauty-plan></div><div data-after-events></div>`}
function routineBlock(title,items){return `<section class="card"><h3 class="section-title">${title}</h3><div class="task-list">${items.length?items.map(r=>routineRow(r)).join(''):'<div class="empty">Пока ничего не запланировано.</div>'}</div></section>`}
function routineRow(r){const done=isDone(todayKey(),r.id);const p=data.products.find(x=>x.id===r.productId);return `<div class="task ${done?'done':''}"><button class="check ${done?'done':''}" data-complete="${r.id}" title="${done?'Отменить':'Выполнить'}">${done?'✓':'○'}</button><div style="flex:1"><strong>${esc(r.title)}</strong><div class="subtle">${r.time||''}${p?' · '+esc(p.name):''}</div></div><button class="btn ghost small" data-edit-routine="${r.id}">✎</button></div>`}

function carePage(){return `<div class="row between wrap"><div><h3 class="section-title">🌸 Уход</h3><p class="subtle">Создавай и перестраивай свою рутину без кода.</p></div><div class="row"><button class="btn" data-add-routine>+ Добавить этап</button><button class="btn secondary" data-route="products">Средства</button></div></div><div class="chip-tabs" style="margin:14px 0"><button class="active" data-care-tab="all">Все</button><button data-care-tab="skin">Кожа</button><button data-care-tab="hair">Волосы</button></div><div class="card"><div class="list" id="routineManageList">${data.routines.map(r=>routineManageRow(r)).join('')}</div></div>`}
function routineManageRow(r){return `<div class="item"><div class="row between"><div><strong>${esc(r.title)}</strong><div class="subtle">${r.category==='skin'?'🌸 Кожа':'🎀 Волосы'} · ${slotName(r.slot)} · ${r.time||'без времени'}</div></div><div class="row"><button type="button" class="btn secondary small" data-edit-routine="${r.id}">Изменить</button><button type="button" class="btn danger small" data-routine-delete="${r.id}" onclick="return window.__MJ_DELETE_ROUTINE__(this.getAttribute('data-routine-delete'));">Удалить</button></div></div><p style="margin-top:8px">${esc(r.notes||'Без заметки')}</p></div>`}
function slotName(x){return {morning:'утро',evening:'вечер',extra:'дополнительно'}[x]||x}

const ARAVIA_CATALOG = [
{sku:'В002',name:'Volume Pure Shampoo 420 мл',title:'Шампунь для объёма тонких и склонных к жирности волос',category:'hair',inci:'Aqua, Sodium Laureth-5 Carboxylate, Potassium Laureth-4 Carboxylate, Cocamidopropyl Betaine, Disodium Cocoamphodiacetate, Cocamidopropyl Hydroxysultaine, Glycereth-2 Cocoate, Hydrolyzed Collagen, Hydrolizated Keratin, PEG-7 Glyceryl Cocoate, PEG-200 Glyceryl Palmate, Rosmarinus Officinalis Flower Extract, Guar Hydroxypropyltrimonium Chloride, Citric Acid, Parfum, Methylchloroisothiazolinone, Methylisothiazolinone'},
{sku:'В059',name:'Curl Hair Shampoo 420 мл',title:'Бессульфатный шампунь для кудрявых и вьющихся волос',category:'hair',inci:'Aqua, Sodium Lauroyl Sarcosinate, Cocamidopropyl Betaine, Coco-Glucoside, Polyquaternium-11, Panthenol, Hydrolyzed Rice Proteins, Linum Usitatissimum Seed Extract, Glycerin, PEG-7 Glyceryl Cocoate, PEG-200 Glyceryl Palmate, Guar Hydroxypropyltrimonium Chloride, Lactic Acid, Sodium Benzoate, Potassium Sorbate, Parfum'},
{sku:'А217',name:'Neutral Hair Shampoo 350 мл',title:'Нейтральный шампунь для всех типов волос',category:'hair',inci:'Aqua, Sodium Cocoyl Isethionate, Cocamidopropyl Betaine, Sodium Lauroyl Sarcosinate, Sodium Cocoyl Glutamate, Polyquaternium-7, Glycerin, Sodium Lactate, Camellia Sinensis (White Tea) Extract, Guar Hydroxypropyltrimonium Chloride, Sodium Chloride, Disodium EDTA, Parfum, Methylisothiazolinone, Methylchloroisothiazolinone, Linalool'},
{sku:'А227',name:'Biotin Grow Shampoo 1000 мл',title:'Шампунь-активатор для роста волос',category:'hair',inci:'Aqua, Sodium Laureth Sulfate, Sodium Lauroyl Sarcosinate, Cocamidopropyl Betaine, Coco-Glucoside, Cocamide DEA, Panthenol, Biotin, Caffeine, Niacinamide, Polyquaternium-7, Sodium Chloride, Cirtic Acid, Parfum, Methylisothiazolinone, Methylchloroisothiazolinone'},
{sku:'В066',name:'Calming Shampoo 420 мл',title:'Успокаивающий шампунь для чувствительной и сухой кожи головы',category:'hair',inci:'Aqua, Sodium Laureth Sulfate, Cocamidopropyl Betaine, Coco-Glucoside, Sodium Lauroyl Sarcosinate, Glycerin, Polyquaternium-7, Hydroxyethyl Urea, Bisabolol, Allantoin, Sodium Chloride, Parfum, Polyquaternium-10, Disodium EDTA, Methylisothiazolinone, Methylchloroisothiazolinone'},
{sku:'В021',name:'Keratin Repair Shampoo 420 мл',title:'Шампунь с кератином для повреждённых и окрашенных волос',category:'hair',inci:'Aqua, Sodium Laureth Sulfate, Sodium Chloride, Cocamidopropyl Betaine, Sodium Cocoamphoacetate, Panthenol, Hydrolyzed Keratin, Coco-Glucoside, Glycol Distearate, Polysilicone-15, Polyquaternium-10, Laureth-2, PEG/PPG-120/10 Trimethylolpropane Trioleate, PEG-7 Glyceryl Cocoate, PEG-200 Glyceryl Palmate, Citric Acid, Methylchloroisothiazolinone, Methylisothiazolinone, Parfum, Geraniol'},
{sku:'В039',name:'Total Control Shampoo 420 мл',title:'Шампунь против перхоти для глубокого очищения',category:'hair',inci:'Aqua, Sodium Laureth Sulfate, Cocamidopropyl Betaine, Coco-Glucoside, Climbazole, Allantoin, Humulus Lupulus Extract, PEG-200 Hydrogenated Glyceryl Palmate, PEG-7 Glyceryl Cocoate, Polyquaternium-10, Citric Acid, Parfum, Sodium Chloride, Methylchloroisothiazolinone, Methylisothiazolinone, D-Limonene, Eugenol, Geraniol, Linalool, Hexyl Cinnamal'},
{sku:'В001',name:'Hydra Pure Shampoo 420 мл',title:'Увлажняющий бессульфатный шампунь для сухих волос',category:'hair',inci:'Aqua, Sodium Laureth-5 Carboxylate, Cocamidopropyl Betaine, Potassium Laureth-4 Carboxylate, Disodium Cocoamphodiacetate, Polyquaternium 7, Cocamidopropyl Hydroxysultaine, Glycereth-2 Cocoate, Betaine, Panthenol, Propylene Glycol, Hydrolyzed Wheat Proteins, Hydrolyzed Rye Proteins, Hydrolyzed Oats Proteins, Hydrolyzed Rice Proteins, PEG-7 Glyceryl Cocoate, PEG-200 Glyceryl Palmate, PEG-4 Rapeseedamide, Cirtic Acid, Parfum, Methylisothiazolinone, Methylchloroisothiazolinone'},
{sku:'А218',name:'Neutral Hair Conditioner 350 мл',title:'Нейтральный кондиционер для всех типов волос',category:'hair',inci:'Aqua, Cetearyl Alcohol, Behentrimonium Chloride, Cetrimonium Chloride, Dimethicone, Glycerin, Simmondsia Chinensis (Jojoba) Seed Oil, Polyquaternium-37, Lactic Acid, Parfum, Methylisothiazolinone, Methylchloroisothiazolinone, Linalool'},
{sku:'В060',name:'Smooth Curl Conditioner 420 мл',title:'Разглаживающий кондиционер для кудрявых волос',category:'hair',inci:'Aqua, Cetearyl Alcohol, Behentrimonium Chloride, Cetrimonium Chloride, Glycerin, Polyquaternium-11, Dimethicone, Panthenol, Hydrolyzed Rice Proteins, Mauritia Flexuosa Fruit Oil, Polyquaternium-10, Lactic Acid, Sodium Benzoate, Potassium Sorbate, Parfum'},
{sku:'В006',name:'Volume Save Conditioner 420 мл',title:'Бальзам-кондиционер для объёма тонких волос',category:'hair',inci:'Aqua, Cetearyl Alcohol, Dipalmitoylethyl Hydroxyethylmonium Methosulfate, Ceteareth-20, Glycerin, Cetrimonium Chloride, Cyclopentasiloxane, Dimethicone, Vitis Vinifera (Grape) Seed Oil, Rosmarinus Officinalis Flower Extract, Soluble Collagen, Hydrolyzed Keratin, Trehalose, Panthenol, Propylene Glycol, Hydrolyzed Wheat Proteins, Hydrolyzed Rye Proteins, Hydrolyzed Oats Proteins, Hydrolyzed Rice Proteins, Polyquaternium 37, Citric Acid, Parfum, BHT, Methylisothiazolinone, Methylchloroisothiazolinone'},
{sku:'В042',name:'Total Revival Conditioner 200 мл',title:'Кондиционер для повреждённых и окрашенных волос',category:'hair',inci:'Aqua, Cocos Nucifera (Coconut) Oil, Glycerin, Cetearyl Alcohol, Dipalmitoylethyl Hydroxyethylmonium Methosulfate, Cetyl Palmitate, Ceteareth-20, Argania Spinosa Kernel Oil, Crambe Abyssinica Seed Oil, Caffeine, Panthenol, Arginine, Hydrolyzed Keratin, Hydrolyzed Oats Protein, Hydrolyzed Rye Protein, Hydrolyzed Wheat Protein, Biotin, Polyquaternium-37, BIS(C13-15 Alkoxy) PG-Amodimethicone, Cyclopentasiloxane, Dimethiconol, Propylene Glycol, Tocopheryl Acetate, Parfume, Methylchloroisothiazolinone, Methylisothiazolinone'},
{sku:'В007',name:'Hydra Save Conditioner 1000 мл',title:'Увлажняющий кондиционер для сухих волос',category:'hair',inci:'Aqua, Cetearyl Alcohol, Behentrimonium Chloride, Cetrimonium Chloride, Silicone Quaternium-16/Glycidoxy Dimethicone Crosspolymer, Undeceth-11, Undeceth-5, Isopentyldiol, Vitis Vinifera (Grape) Seed Oil, Aloe Barbadensis Leaf Juice, Betaine, Panthenol, Propylene Glycol, Hydrolyzed Wheat Proteins, Hydrolyzed Rye Proteins, Hydrolyzed Oats Proteins, Hydrolyzed Rice Proteins, Cirtic Acid, Parfum, Methylisothiazolinone, Methylchloroisothiazolinone'},
{sku:'В038',name:'Gloss & Grow Vital Mask 200 мл',title:'Маска для волос и кожи головы с биотином и абиссинским маслом',category:'hair',inci:'Aqua, Cocos Nucifera Seed Butter, Glycerin, Cetearyl Alcohol, Dipalmitoylethyl Hydroxyethylmonium Methosulfate, Cetyl Palmitate, Crambe Abyssinica Seed Oil, Polyquaternium-37, Ceteareth-20, Caffeine, Panthenol, Hydrolyzed Oats Protein, Hydrolyzed Rye Protein, Hydrolyzed Wheat Protein, Biotin, Propylene Glycol, Parfum, Methylchloroisothiazolinone, Methylosothiazolinone, BHT'},
{sku:'А212',name:'Nourishing Mask 200 мл',title:'Экстрапитательная маска для сухих волос',category:'hair',inci:'Aqua, Cetearyl Alcohol, Cocos Nucifera Seed Butter, Cyclopentasiloxane, Dipalmitoylethyl Hydroxyethylmonium Methosulfate, Glycerin, Cetrimonium Chloride, Bis(C13-15 Alkoxy) PG-Amodimethicone, Butyrospermum Parkii (Shea) Butter, Polyquaternium-37, Ceteareth-20, C14-15 Alcohols, Dimethiconol, Parfum, Argania Spinosa Kernel (Argana) Oil, BHT, Simmondsia Chinensis (Jojoba) Seed Oil, Citric Acid, Tocopheryl Acetate, Hexyl Cinnamal, Limonene, Isotridecyl Alcohol, Methylchloroisothiazolinone, Methylisothiazolinone'},
{sku:'А074',name:'Moisturizing Emollient 200 мл',title:'Увлажняющий крем для лица и тела',category:'skin',inci:'Aqua, Caprylic/Capric Triglyceride, Paraffinum Liquidum, Butyrospermum Parkii (Shea) Butter, Potassium Cetyl Phosphate, Glycerin, Ceteareth-20, Petrolatum, Phenoxyethanol, Sodium Polyacrylate, Hydroxyethyl Urea, Panthenol, Allantoin, Ethylhexylglycerin, Sodium Hyaluronate, Tocopheryl Acetate, Citric Acid'},
{sku:'А123',name:'Deep Hydration Mist Serum 110 мл',title:'Увлажняющая сыворотка-мист для лица',category:'skin',inci:'Aqua, Prunus Armeniaca (Apricot) Kernel Oil, Prunus Amygdalus Dulcis (Sweet Almond) Oil, Isononyl Isononanoate, Propylene Glycol, Glucose, Sorbitol, Sodium Glutamate, Urea, Sodium PCA, Glycine, Lactic Acid, Hydrolyzed Wheat Protein, Panthenol, Sodium Hyaluronate, Aloe Barbadensis Leaf Juice, Centaurea Cyanus Flower Extract, Vaccinium Myrtillus Fruit Extract, 1,2-Hexanediol, Tocopheryl Acetate, Parfum'},
{sku:'6363',name:'Niacinamide Serum 10% 100 мл',title:'Сыворотка с ниацинамидом и цинком',category:'skin',inci:'Aqua, Niacinamide, Glycerin, Isononyl Isononanoate, Propanediol, Potassium Cetyl Phosphate, Phenoxyethanol, Polysorbate 80, Sorbitan Stearate, Dimethicone, Squalane, Ethylparaben, Panthenol, Sodium Polyacrylate, Allantoin, Methylparaben, Xanthan Gum, Propylparaben, Parfum, Saccharomyces/Zinc Ferment, Aloe Barbadensis Leaf Extract, Butylene Glycol, Leuconostoc/Radish Root Ferment Filtrate, Bioflavonoids, Brassica Oleracea Italica (Broccoli) Extract'},
{sku:'А063',name:'Anti-Age Deep Serum 30 мл',title:'Омолаживающая сыворотка с пептидами',category:'skin',inci:'Aqua, Butylene Glycol, Glycerin, Panthenol, Niacinamide, Pentylene Glycol, Caprylyl Glycol, N-Prolyl Palmitoyl Tripeptide-56 Acetate, Hydroxyethylcellulose, Phenoxyethanol, Hydroxyacetophenone, Caprylyl Glycol, PEG-40 Hydrogenated Castor Oil, Parfum'},
{sku:'А094',name:'Total Recovery Serum 50 мл',title:'Восстанавливающая сыворотка с астаксантином и мочевиной',category:'skin',inci:'Aqua, Hydroxyethyl Urea, Glycerin, Astaxanthin, Betaine, Trehalose, Aesculus Hippocastanum Extract, Centella Asiatica Extract, Cellulose Gum, Algin, Peg-40 Hydrogenated Castor Oil, Phenoxyethanol, Ethylhexylglycerin, Parfum, CI 16185, Hexyl Cinnamal, Linalool, Geraniol, Limonene'},
{sku:'А099',name:'Sebo Renewal Serum 50 мл',title:'Себорегулирующая сыворотка с цинком и аргинином',category:'skin',inci:'Aqua, Glycerin, Arginine, Saccharomyces/Zinc Ferment, Bacillus/Soybean Ferment Extract, Sodium Hyaluronate, Folic Acid, Bidens Tripartita Flower/Leaf/Stem Extract, Cellulose Gum, Algin, PEG-40 Hydrogenated Castor Oil, Phenoxyethanol, Ethylhexylglycerin, Butylene Glycol, 1,2-Hexanediol, Parfum, CI 19140'},
{sku:'А041',name:'Anti-Acne Peeling 18% 50 мл',title:'Пилинг для проблемной кожи с комплексом кислот',category:'skin',inci:'Aqua, Ethoxydiglycol, Propanediol, Gluconolactone, Glycerin, Azelaic acid, Sodium Lactate, Mandelic Acid, Salicylic Acid, Hydroxyethylcellulose, PEG-40 Hydrogenated Castor Oil, Aloe Barbadensis Leaf Extract, Parfum, Bioflavonoids, Brassica Oleracea Italica (Broccoli) Extract'},
{sku:'А034',name:'Anti-Age Peeling 15% 50 мл',title:'Пилинг с AHA и PHA кислотами',category:'skin',inci:'Aqua, Isopentyldiol, Arginine, Lactic Acid, Gluconolactone, Glycolic Acid, Hydroxyethyl cellulose, Malic Acid, Tartaric acid, Peg-40 Hydrogenated Castor Oil, Parfum, Soluble Collagen, Butylene Glycol, Caprylyl Glycol, Pentylene Glycol, Hydroxyacetophenone'},
{sku:'А126',name:'BLACK CLEANSE MASK 100 мл',title:'Очищающая маска с вулканическим пеплом и серой',category:'skin',inci:'Aqua, Kaolin, Glycerin, Magnesium Aluminum Silicate, Butylene Glycol, Sulfurized TEA-Ricinoleate, Panthenol, Volcanic Ash, PEG-35 Castor Oil, Propylene Glycol, Carbon Black, Xanthan Gum, Parfum, Methylisothiazolinone, Methylchloroisothiazolinone, Limonene'},
{sku:'А125',name:'URBAN DETOX MASK 100 мл',title:'Лимфодренажная маска с красными водорослями и кофеином',category:'skin',inci:'Aqua, Caprylic/Capric Triglyceride, Glycerin, Isononyl Isononanoate, Isopentyldiol, Caffeine, Troxerutin, Fucus Vesiculosus Extract, Menthyl Lactate, Sodium Acrylates Copolymer, Lecithin, Parfum, Methylisothiazolinone, Methylchloroisothiazolinone, CI 16185, CI 19140'},
{sku:'9225',name:'Aqua Comfort 100 мл',title:'Увлажняющая крем-маска для лица',category:'skin',inci:'Aqua, Butyrospermum Parkii (Shea) Butter, Squalane, Glycerin, Isononyl Isononanoate, Allantoin, Tocopheryl Acetate, Sodium Acrylates Copolymer, Lecithin, Phenoxyethanol, Ethylhexylglycerin, Parfum, Hexyl Cinnamal, Linalool, Limonene'},
{sku:'А131',name:'Youth Essence Peeling 50 мл',title:'Пилинг с койевой и гликолевой кислотами',category:'skin',inci:'Aqua, Butylene Glycol, Glycolic Acid, Kojic Acid, Arginine, Sodium Hyaluronate, Hydroxyethylcellulose, Methylisothiazolinone, Methylchloroisothiazolinone'},
{sku:'6101',name:'Papaya Enzyme Peel 150 мл',title:'Энзимный пилинг с папаином',category:'skin',inci:'Aqua, Papain, Stearic Acid, Urea, Zea Mays (Corn) Germ Oil, Potassium Cetyl Phosphate, Olea Europaea (Olive) Fruit Oil, Glycerin, Triethanolamine, Allantoin, Parfum, Phenoxyethanol (and) Ethylhexylglycerin'},
{sku:'А017',name:'Antioxidant Vita Mask 100 мл',title:'Маска с антиоксидантным комплексом',category:'skin',inci:'Aqua, Olea Europaea (olive) Fruit Oil, Stearic Acid, Emulsifying Wax, Glycerin, Betaine, Hydrolyzed Collagen, Theobroma Cacao Seed Butter, Butyrospermum Parkii (Shea) Oil, Glyceryl Stearate, Kaolin, Camellia Sinensis Leaf Extract, Aloe Arberescens Leaf Extract, Pantenol, Alpha Lipoic Acid (ALA), Tocopherol, Triethanolamine, Phenoxyethanol (and) Ethylhexylglycerin, Parfum'}
];

function araviaCatalogCard(p){
 return `<div class="card"><div class="row between wrap"><div><span class="tag">ARAVIA · ${esc(p.sku)}</span><h4 style="margin:8px 0 4px">${esc(p.name)}</h4><div class="subtle">${esc(p.title)}</div></div><span class="tag">${p.category==='hair'?'🎀 Волосы':'🌸 Лицо'}</span></div><details style="margin-top:12px"><summary style="cursor:pointer;font-weight:700">Показать состав</summary><p class="subtle" style="line-height:1.65;margin-top:8px">${esc(p.inci)}</p></details><div class="row" style="margin-top:12px"><button class="btn small" data-aravia-add="${esc(p.sku)}">+ Добавить в мои средства</button><button class="btn secondary small" data-aravia-lab="${esc(p.sku)}">🧪 В лабораторию</button></div></div>`;
}
function productsPage(){
 const q=(window.__araviaSearch||'').toLowerCase();
 const shown=ARAVIA_CATALOG.filter(p=>(p.name+' '+p.title+' '+p.sku+' '+p.inci).toLowerCase().includes(q));
 return `<div class="row between wrap"><div><h3 class="section-title">🧴 Средства</h3><p class="subtle">Твои продукты + база составов ARAVIA из официальных карточек товаров.</p></div><button class="btn" data-add-product>+ Добавить средство</button></div>
 <div class="field" style="margin:14px 0"><input id="productSearch" placeholder="Поиск по моим средствам…" value=""></div>
 <div class="card" style="margin-bottom:16px"><div class="row between wrap"><div><h3 class="section-title">🧪 ARAVIA — база составов</h3><p class="subtle">Найди продукт по названию, артикулу или ингредиенту. Составы сохранены как справочная база; производитель предупреждает, что актуальный INCI может отличаться от опубликованного.</p></div><span class="tag">${ARAVIA_CATALOG.length} продукта</span></div><div class="field" style="margin:12px 0"><input id="araviaSearch" placeholder="Например: мочевина, Hydra, А217, ниацинамид…" value="${esc(window.__araviaSearch||'')}"></div><div class="grid grid-2" id="araviaGrid">${shown.map(araviaCatalogCard).join('')}</div></div>
 <div class="grid grid-3" id="productGrid">${renderProducts(data.products)}</div>`;
}
function renderProducts(items){
 return items.length?items.map(p=>`<div class="card"><div style="height:180px;border-radius:18px;background:var(--surface2);display:grid;place-items:center;overflow:hidden">${p.image?`<img src="${p.image}" style="width:100%;height:100%;object-fit:cover">`:'🧴'}</div><h4 style="margin:12px 0 4px">${esc(p.name)} ♡</h4><div class="subtle">${esc(p.brand||'Без бренда')} · ${esc(p.category||'Другое')}</div><p class="subtle">Использовано: ${p.used||0} раз</p>${p.inci?`<details><summary>Состав INCI</summary><p class="subtle" style="line-height:1.6">${esc(p.inci)}</p></details>`:''}<p>${esc(p.notes||'')}</p><div class="row"><button class="btn secondary small" data-edit-product="${p.id}">Изменить</button><button class="btn danger small" data-delete-product="${p.id}">Удалить</button></div></div>`).join(''):'<div class="empty" style="grid-column:1/-1">♡ Твоя полка ухода пока пустая.<br><br>Добавь первое средство.</div>';
}

function calendarPage(){const ref=new Date();ref.setDate(1);const year=ref.getFullYear(),month=ref.getMonth();const first=(new Date(year,month,1).getDay()+6)%7;const dim=new Date(year,month+1,0).getDate();let cells='';for(let i=0;i<first;i++)cells+='<div></div>';for(let d=1;d<=dim;d++){const k=`${year}-${String(month+1).padStart(2,'0')}-${String(d).padStart(2,'0')}`;const s=dayStats(k);const ev=data.events.filter(e=>e.date===k);cells+=`<button class="cal-day ${k===todayKey()?'today':''}" data-day="${k}"><div class="d">${d}</div><div class="meter"><i style="width:${s.p}%"></i></div><div class="subtle" style="margin-top:6px">${s.p}%${ev.length?' · ✦':''}</div></button>`}return `<div class="row between wrap"><div><h3 class="section-title">📅 Календарь</h3><p class="subtle">Нажми на день, чтобы увидеть уход и добавить событие.</p></div><div class="tag">${new Intl.DateTimeFormat('ru-RU',{month:'long',year:'numeric'}).format(ref)}</div></div><div class="card"><div class="calendar">${['Пн','Вт','Ср','Чт','Пт','Сб','Вс'].map(x=>`<div class="cal-head">${x}</div>`).join('')}${cells}</div></div>`}

function progressPage(){const r7=statsRange(7);const r30=statsRange(30);const overall7=pct(r7.reduce((s,x)=>s+x.done.length,0),r7.reduce((s,x)=>s+x.all.length,0));const skin=completedByCat('skin'),hair=completedByCat('hair');return `<div class="grid grid-4"><div class="stat"><span class="label">Всего процедур</span><b>${totalCompleted()}</b></div><div class="stat"><span class="label">Идеальных дней</span><b>${bestPerfectDays()}</b></div><div class="stat"><span class="label">Текущая серия</span><b>🔥 ${currentStreak()}</b></div><div class="stat"><span class="label">Лучший streak</span><b>🔥 ${bestStreak()}</b></div></div><div class="grid grid-3" style="margin-top:16px"><div class="card"><h3 class="section-title">🌸 Кожа</h3><div class="circle" style="--p:${clamp(skin)}"><div class="inside"><span class="label">Всего</span><strong>${clamp(skin)}</strong></div></div><p class="subtle">Выполнено ${skin} процедур.</p></div><div class="card"><h3 class="section-title">🎀 Волосы</h3><div class="circle" style="--p:${clamp(hair)}"><div class="inside"><span class="label">Всего</span><strong>${clamp(hair)}</strong></div></div><p class="subtle">Суммарно ${hair} процедур.</p></div><div class="card"><h3 class="section-title">♡ Неделя</h3><div class="kpi">${overall7}%</div><div class="progress" style="margin-top:14px"><i style="width:${overall7}%"></i></div><p class="subtle">За последние 7 дней.</p></div></div><div class="card" style="margin-top:16px"><h3 class="section-title">📈 Выполнение за 30 дней</h3><div style="display:grid;grid-template-columns:repeat(15,1fr);gap:6px;align-items:end;height:180px">${r30.map(x=>`<div title="${x.date}: ${x.p}%" style="height:${Math.max(8,x.p)}%;background:linear-gradient(180deg,var(--primary),var(--accent));border-radius:8px 8px 3px 3px"></div>`).join('')}</div></div><div class="card" style="margin-top:16px"><h3 class="section-title">📸 Визуальный прогресс</h3>${data.photos.length?`<div class="photo-grid">${data.photos.slice().reverse().slice(0,6).map(photoCard).join('')}</div>`:'<div class="empty">Добавь первое фото в разделе Дневник.</div>'}</div>`}
function photoCard(p){return `<div class="photo-card">${p.image?`<img src="${p.image}" alt="Фото прогресса">`:'<div style="height:180px;background:var(--surface2);display:grid;place-items:center">📸</div>'}<div class="body"><strong>${esc(p.date)} · ${esc(p.category)}</strong><div class="subtle">Оценка ${p.score||'—'}/10</div><p class="subtle">${esc(p.note||'')}</p></div></div>`}

function achievementsPage(){const cats=[...new Set(achievementDefs.map(a=>a.cat))];return `<div class="card hero"><div class="row between"><div><h3 class="section-title">✦ Твоя коллекция</h3><p class="subtle">Открыто ${data.unlocked.length} из ${achievementDefs.length}</p></div><div class="circle" style="--p:${pct(data.unlocked.length,achievementDefs.length)}"><div class="inside"><strong>${pct(data.unlocked.length,achievementDefs.length)}%</strong></div></div></div></div>${cats.map(cat=>`<section style="margin-top:16px"><div class="row between"><h3 class="section-title">${cat}</h3><span class="tag">${achievementDefs.filter(a=>a.cat===cat&&data.unlocked.includes(a.id)).length}/${achievementDefs.filter(a=>a.cat===cat).length}</span></div><div class="grid grid-3">${achievementDefs.filter(a=>a.cat===cat).map(a=>{const u=data.unlocked.includes(a.id);return `<div class="card achievement ${u?'unlocked':'locked'}"><span class="icon">${u?a.icon:(a.hidden?'❓':'🔒')}</span><span class="lock">${u?'UNLOCKED':'LOCKED'}</span><h4>${u?esc(a.title):a.hidden?'Секретная цель':esc(a.title)}</h4><p class="subtle">${u?esc(a.desc):a.hidden?'Попробуй открыть её сама.':esc(a.desc)}</p></div>`}).join('')}</div></section>`).join('')}`}

function goalsPage(){return `<div class="row between"><div><h3 class="section-title">🎯 Мои цели</h3><p class="subtle">Большие изменения любят маленькие шаги.</p></div><button class="btn" data-add-goal>+ Добавить цель</button></div><div class="grid grid-2" style="margin-top:16px">${data.goals.length?data.goals.map(g=>`<div class="card"><div class="row between"><h4>${esc(g.title)}</h4><button class="btn danger small" data-delete-goal="${g.id}">Удалить</button></div><p class="subtle">${esc(g.description||'')}</p><div class="row between"><strong>${g.progress}/${g.target}</strong><span class="subtle">${g.due||'без срока'}</span></div><div class="progress" style="margin:10px 0"><i style="width:${pct(g.progress,g.target)}%"></i></div><div class="row"><button class="btn secondary small" data-goal-inc="${g.id}">+1</button><span class="tag">${pct(g.progress,g.target)}%</span></div></div>`).join(''):'<div class="empty" style="grid-column:1/-1">♡ Здесь будут твои личные цели.</div>'}</div>`}

function journalPage(){return `<div class="row between"><div><h3 class="section-title">✎ Дневник</h3><p class="subtle">Заметки о коже, волосах, средствах и настроении.</p></div><button class="btn" data-add-note>+ Новая запись</button></div><div class="list" style="margin-top:16px">${data.notes.length?data.notes.slice().reverse().map(n=>`<div class="card"><div class="row between"><strong>${esc(n.date)}</strong><button class="btn danger small" data-delete-note="${n.id}">Удалить</button></div><p style="line-height:1.7">${esc(n.text)}</p></div>`).join(''):'<div class="empty">♡ Твой дневник ещё пуст. Напиши первую маленькую заметку.</div>'}</div><div class="card" style="margin-top:16px"><h3 class="section-title">📸 Добавить фото прогресса</h3><form id="photoForm" class="form"><div class="grid grid-2"><div class="field"><label>Категория</label><select name="category"><option>Skin</option><option>Hair</option></select></div><div class="field"><label>Оценка 1–10</label><input name="score" type="number" min="1" max="10"></div></div><div class="field"><label>Дата</label><input name="date" type="date" value="${todayKey()}"></div><div class="field"><label>Комментарий</label><textarea name="note" placeholder="Что изменилось?"></textarea></div><div class="field"><label>Фото</label><input name="image" type="file" accept="image/*"></div><button class="btn">Сохранить фото</button></form></div><div class="card" style="margin-top:16px"><h3 class="section-title">Before → After</h3>${data.photos.length>=2?`<div class="grid grid-2"><div><label class="subtle">До</label><select id="beforeSel" style="width:100%;padding:12px;border:1px solid var(--border);border-radius:12px">${data.photos.map(p=>`<option value="${p.id}">${p.date} · ${p.category}</option>`).join('')}</select></div><div><label class="subtle">После</label><select id="afterSel" style="width:100%;padding:12px;border:1px solid var(--border);border-radius:12px">${data.photos.map(p=>`<option value="${p.id}">${p.date} · ${p.category}</option>`).join('')}</select></div></div><div id="compare" style="margin-top:14px"></div>`:'<div class="empty">Добавь минимум два фото, чтобы сравнить их.</div>'}</div>`}

function petPage(){const p=data.pet;return `<div class="grid grid-2"><section class="card hero"><div class="row"><div class="pet">${petEmoji()}</div><div><h3 class="section-title">${esc(p.name)} ♡</h3><div class="pet-stage">${p.stage===1?'Малыш':p.stage===2?'Подрастающий': 'Взрослый хранитель'}</div><p class="subtle">${petMood()}</p><div class="row wrap"><span class="tag">Забота: ${p.points}</span><span class="tag">Кормления: ${p.feedCount}</span><span class="tag">Игры: ${p.playCount}</span></div></div></div><div class="row wrap" style="margin-top:18px"><button class="btn" data-pet-feed type="button">🍓 Покормить</button><button class="btn secondary" data-pet-play>🎀 Поиграть</button><button class="btn ghost" data-edit-pet>✎ Изменить питомца</button></div></section><section class="card"><h3 class="section-title">Состояние</h3>${bar('Счастье',p.happiness)}${bar('Сытость',p.hunger)}${bar('Энергия',p.energy)}<p class="subtle">Питомец растёт вместе с твоей заботой: процедуры и достижения дают очки.</p></section></div>`}

function challengesPage(){return `<div class="row between wrap"><div><h3 class="section-title">🏆 Челленджи</h3><p class="subtle">Чуть-чуть игры, чуть-чуть рутины — и много удовлетворения.</p></div><button class="btn" data-add-challenge>+ Свой челлендж</button></div><div class="grid grid-2" style="margin-top:16px">${data.challenges.map(challengeCardFull).join('')}</div>`}
function challengeCardFull(c){const cat=c.cat||(['skin','auto-skin'].includes(c.type)?'skin':(['hair','auto-hair'].includes(c.type)?'hair':(['auto-pet-points'].includes(c.type)?'pet':'habit')));return `<div class="card challenge challenge-card" data-cat="${cat}" ${c.done?'data-done="1"':''}><div class="row between"><div class="row"><span style="font-size:28px">${c.icon||'🏆'}</span><h4>${esc(c.title)}</h4></div><span class="tag">+${c.reward} XP</span></div><p class="subtle">${esc(c.description)}</p>${bar('Прогресс',pct(c.progress,c.goal))}<div class="row between" style="margin-top:10px"><span class="subtle">${c.progress}/${c.goal}</span>${c.builtIn?'<span class="tag">Авто</span>':`<button class="btn secondary small" data-ch-inc="${c.id}">+1</button>`}</div></div>`}

function tipsPage(){const t=[...skinTips[data.settings.skinType]||[],...(hairTips[data.settings.hairType]||[])];const weather=data.settings.weather;return `<div class="grid grid-2"><section class="card hero"><h3 class="section-title">💡 Персональные советы</h3><p style="font-size:18px;line-height:1.65">${esc(recommendation())}</p><div class="row wrap"><span class="tag">Кожа: ${skinTypeName(data.settings.skinType)}</span><span class="tag">Волосы: ${hairTypeName(data.settings.hairType)}</span>${weather?`<span class="tag">${weatherIcon(weather.description)} ${weather.temp}°</span>`:''}</div></section><section class="card"><h3 class="section-title">☁️ Погодные подсказки</h3><div class="list"><div class="item">☀️ Яркое солнце — не забывай про SPF и комфортную защиту.</div><div class="item">🌧️ Осадки — береги длину волос от лишней влаги и трения.</div><div class="item">❄️ Холод — добавь защитный слой и не переусердствуй с очищением.</div><div class="item">🔥 Жара — лёгкие текстуры и достаточное количество воды.</div></div></section></div><div class="card" style="margin-top:16px"><h3 class="section-title">🌸 Для твоего типа кожи</h3><div class="list">${t.map(x=>`<div class="item">${esc(x)}</div>`).join('')}</div></div>`}

const articles=[
 {id:'a1',tag:'Кожа',title:'Почему стабильная база важнее десяти активов',text:'Хорошая базовая рутина обычно строится вокруг очищения, увлажнения и защиты от солнца. Когда база понятна, легче увидеть, какие дополнительные шаги действительно тебе подходят.'},
 {id:'a2',tag:'Волосы',title:'Как сделать день мытья волос спокойнее',text:'Подбирай температуру воды и количество средств по комфорту кожи головы и длины. Кондиционирование и бережное сушение часто дают больше пользы, чем попытка компенсировать всё большим количеством продуктов.'},
 {id:'a3',tag:'Привычки',title:'Как не бросить уход через неделю',text:'Уменьши трение: держи продукты под рукой, привяжи этапы к уже существующим привычкам и отмечай маленький прогресс. Трекер нужен не для идеальности, а для видимости пути.'},
 {id:'a4',tag:'Погода',title:'Почему рутина может меняться по сезону',text:'Жара, холод, сухой воздух и влажность влияют на субъективный комфорт кожи и волос. Это не значит, что нужно менять всё сразу: достаточно наблюдать и делать небольшие корректировки.'},
 {id:'a5',tag:'Питомец',title:'Игровая мотивация без давления на себя',text:'Челленджи, XP и питомец работают лучше, когда они помогают заметить сделанное, а не превращают уход в систему наказаний. Пропуск — это просто пропуск, а не провал.'}
];
function articlesPage(){return `<div class="row between"><div><h3 class="section-title">📖 Мини-статьи</h3><p class="subtle">Небольшие заметки, которые хочется прочитать за пару минут.</p></div><span class="tag">Прочитано ${data.articlesRead.length}/${articles.length}</span></div><div class="grid grid-3" style="margin-top:16px">${articles.map(a=>`<div class="card article" data-article="${a.id}"><span class="tag">${a.tag}</span><h4>${esc(a.title)}</h4><p>${esc(a.text.slice(0,170))}…</p><button class="btn secondary small" style="margin-top:10px">Читать</button></div>`).join('')}</div>`}

function reportsPage(){const week=statsRange(7),month=statsRange(30),wp=pct(week.reduce((a,x)=>a+x.done.length,0),week.reduce((a,x)=>a+x.all.length,0)),mp=pct(month.reduce((a,x)=>a+x.done.length,0),month.reduce((a,x)=>a+x.all.length,0));const report=`МОЙ БЬЮТИ-ДНЕВНИК ♡\n\nДата: ${fmtDate(todayKey())}\nУход за 7 дней: ${wp}%\nУход за 30 дней: ${mp}%\nВсего процедур: ${totalCompleted()}\nИдеальных дней: ${bestPerfectDays()}\nТекущая серия: ${currentStreak()}\nЛучший streak: ${bestStreak()}\nXP: ${data.xp}\nУровень: ${data.level}\nДостижения: ${data.unlocked.length}/${achievementDefs.length}\nФото: ${data.photos.length}\nЦель: ${data.goals.filter(g=>g.progress>=g.target).length}/${data.goals.length}\nПитомец: ${data.pet.name}, стадия ${data.pet.stage}\n`;return `<div class="grid grid-2"><section class="card"><h3 class="section-title">📊 Недельный итог</h3><div class="kpi">${wp}%</div><p class="subtle">${week.filter(x=>x.p===100).length} идеальных дней из 7.</p><div class="progress"><i style="width:${wp}%"></i></div></section><section class="card"><h3 class="section-title">🗓️ Месячный итог</h3><div class="kpi">${mp}%</div><p class="subtle">${month.reduce((a,x)=>a+x.done.length,0)} выполненных этапов.</p><div class="progress"><i style="width:${mp}%"></i></div></section></div><div class="card" style="margin-top:16px"><div class="row between"><h3 class="section-title">Ваш отчёт</h3><div class="row"><button class="btn secondary" data-copy-report>Скопировать</button><button class="btn" data-download-report>Скачать .txt</button></div></div><pre style="white-space:pre-wrap;background:var(--surface2);padding:14px;border-radius:16px;line-height:1.6">${esc(report)}</pre></div>`}

function settingsPage(){return `<div class="grid grid-2"><section class="card"><h3 class="section-title">👤 Профиль</h3><form id="settingsForm" class="form"><div class="field"><label>Имя</label><input name="name" value="${esc(data.settings.name)}"></div><div class="grid grid-2"><div class="field"><label>Тип кожи</label><select name="skinType">${[['normal','Нормальная'],['dry','Сухая'],['oily','Жирная'],['combination','Комбинированная'],['sensitive','Чувствительная']].map(([v,l])=>`<option value="${v}" ${data.settings.skinType===v?'selected':''}>${l}</option>`).join('')}</select></div><div class="field"><label>Тип волос</label><select name="hairType">${[['normal','Нормальные'],['dry','Сухие'],['oily','Жирные'],['damaged','Повреждённые'],['colored','Окрашенные']].map(([v,l])=>`<option value="${v}" ${data.settings.hairType===v?'selected':''}>${l}</option>`).join('')}</select></div></div><div class="field"><label>Город для погоды</label><input name="city" value="${esc(data.settings.city)}" placeholder="Например, Таллин"></div><div class="field"><label>Тема</label><select name="theme">${Object.entries(themes).map(([v,t])=>`<option value="${v}" ${data.settings.theme===v?'selected':''}>${t.name}</option>`).join('')}</select></div><label class="row"><input type="checkbox" name="animations" ${data.settings.animations?'checked':''}> Мягкие анимации</label><label class="row"><input type="checkbox" name="notifications" ${data.settings.notifications?'checked':''}> Разрешить локальные уведомления</label><button class="btn">Сохранить настройки</button></form></section><section class="card"><h3 class="section-title">☁️ Погода</h3><p class="subtle">Погода работает без API-ключа через Open-Meteo. Нужен интернет только для обновления прогноза.</p><button class="btn" data-action="weather">Обновить погоду</button>${data.settings.weather?`<div class="item" style="margin-top:12px"><strong>${weatherIcon(data.settings.weather.description)} ${data.settings.weather.city}</strong><p>${data.settings.weather.temp}° · ${data.settings.weather.description} · влажность ${data.settings.weather.humidity}%</p></div>`:''}<h3 class="section-title" style="margin-top:18px">💾 Резервная копия</h3><div class="row wrap"><button class="btn secondary" data-export>Экспорт JSON</button><label class="btn secondary" style="cursor:pointer">Импорт JSON<input id="importFile" type="file" accept="application/json" hidden></label><button class="btn danger" data-reset>Очистить данные</button></div></section></div>`}

function bindPage(route){
 document.querySelectorAll('[data-route]').forEach(el=>el.addEventListener('click',()=>{location.hash=el.dataset.route}));
 document.querySelectorAll('[data-complete]').forEach(b=>b.onclick=()=>isDone(todayKey(),b.dataset.complete)?undo(b.dataset.complete):complete(b.dataset.complete));
 document.querySelectorAll('[data-edit-routine]').forEach(b=>b.onclick=()=>routineModal(b.dataset.editRoutine));
 document.querySelector('[data-add-routine]')?.addEventListener('click',()=>routineModal());
 document.querySelectorAll('[data-add-product]').forEach(b=>b.onclick=()=>productModal());
 document.getElementById('araviaSearch')?.addEventListener('input',e=>{window.__araviaSearch=e.target.value;const grid=document.getElementById('araviaGrid');if(grid){const q=window.__araviaSearch.toLowerCase();grid.innerHTML=ARAVIA_CATALOG.filter(p=>(p.name+' '+p.title+' '+p.sku+' '+p.inci).toLowerCase().includes(q)).map(araviaCatalogCard).join('');bindPage(route);}});
 document.querySelectorAll('[data-aravia-add]').forEach(b=>b.onclick=()=>{const p=ARAVIA_CATALOG.find(x=>x.sku===b.dataset.araviaAdd);if(!p)return;if(!data.products.some(x=>x.brand==='ARAVIA'&&x.sku===p.sku)){data.products.push({id:uid(),name:p.name,brand:'ARAVIA',category:p.category==='hair'?'Волосы':'Лицо',notes:p.title,inci:p.inci,sku:p.sku,image:'',used:0});save();render();toast('ARAVIA добавлен в твои средства ♡')}else toast('Этот продукт уже есть в твоих средствах ♡');});
 document.querySelectorAll('[data-aravia-lab]').forEach(b=>b.onclick=()=>{const p=ARAVIA_CATALOG.find(x=>x.sku===b.dataset.araviaLab);if(!p)return;data.mjx.lab.lastQuery=p.inci;save();location.hash='lab';render();});

 document.querySelectorAll('[data-edit-product]').forEach(b=>b.onclick=()=>productModal(b.dataset.editProduct));
 document.querySelectorAll('[data-delete-product]').forEach(b=>b.onclick=()=>{if(confirm('Удалить средство?')){data.products=data.products.filter(p=>p.id!==b.dataset.deleteProduct);save();render()}});
 document.getElementById('productSearch')?.addEventListener('input',e=>{const q=e.target.value.toLowerCase();document.getElementById('productGrid').innerHTML=renderProducts(data.products.filter(p=>(p.name+' '+p.brand+' '+p.category+' '+p.notes+' '+(p.inci||'')).toLowerCase().includes(q))) ;bindPage(route)});
 document.querySelectorAll('[data-day]').forEach(b=>b.onclick=()=>dayModal(b.dataset.day));
 document.querySelectorAll('[data-more]').forEach(b=>b.onclick=()=>location.hash=b.dataset.more);
 document.querySelector('[data-add-goal]')?.addEventListener('click',()=>goalModal());
 document.querySelectorAll('[data-delete-goal]').forEach(b=>b.onclick=()=>{data.goals=data.goals.filter(g=>g.id!==b.dataset.deleteGoal);save();render()});
 document.querySelectorAll('[data-goal-inc]').forEach(b=>b.onclick=()=>{const g=data.goals.find(x=>x.id===b.dataset.goalInc);if(g){g.progress=clamp(g.progress+1,0,g.target);if(g.progress===g.target)addXP(50,'Цель завершена 🎯');save();render()}});
 document.querySelector('[data-add-note]')?.addEventListener('click',()=>noteModal());
 document.querySelectorAll('[data-delete-note]').forEach(b=>b.onclick=()=>{data.notes=data.notes.filter(n=>n.id!==b.dataset.deleteNote);save();render()});
 document.querySelector('#photoForm')?.addEventListener('submit',photoSubmit);
 document.querySelectorAll('[data-pet-feed]').forEach(b=>b.onclick=petFeed);document.querySelectorAll('[data-pet-play]').forEach(b=>b.onclick=petPlay);document.querySelector('[data-edit-pet]')?.addEventListener('click',petModal);
 document.querySelector('[data-add-challenge]')?.addEventListener('click',challengeModal);document.querySelectorAll('[data-ch-inc]').forEach(b=>b.onclick=()=>{const c=data.challenges.find(x=>x.id===b.dataset.chInc);if(c&&!c.builtIn&&!c.done){c.progress=Math.min(c.goal,c.progress+1);if(c.progress===c.goal){c.done=true;addXP(c.reward,'Челлендж завершён')}}save();render()});
 document.querySelectorAll('[data-article]').forEach(b=>b.onclick=()=>articleModal(b.dataset.article));
 document.querySelector('[data-action="weather"]')?.addEventListener('click',fetchWeather);document.querySelector('[data-copy-report]')?.addEventListener('click',copyReport);document.querySelector('[data-download-report]')?.addEventListener('click',downloadReport);
 document.querySelector('#settingsForm')?.addEventListener('submit',e=>{e.preventDefault();const f=new FormData(e.target);const old=data.settings.theme;data.settings.name=f.get('name').trim()||'Красотка';data.settings.skinType=f.get('skinType');data.settings.hairType=f.get('hairType');data.settings.city=f.get('city').trim();data.settings.theme=f.get('theme');data.settings.animations=f.get('animations')==='on';data.settings.notifications=f.get('notifications')==='on';if(old!==data.settings.theme)data.themeChanges++;save();applyTheme();toast('Настройки сохранены ♡');render()});
 document.querySelector('[data-export]')?.addEventListener('click',()=>downloadBlob(JSON.stringify(data,null,2),'my-beauty-journal-backup.json','application/json'));
 document.querySelector('#importFile')?.addEventListener('change',importBackup);document.querySelector('[data-reset]')?.addEventListener('click',resetData);
 document.querySelectorAll('[data-care-tab]').forEach(b=>b.onclick=()=>{document.querySelectorAll('[data-care-tab]').forEach(x=>x.classList.remove('active'));b.classList.add('active');const mode=b.dataset.careTab;document.getElementById('routineManageList').innerHTML=data.routines.filter(r=>mode==='all'||r.category===mode).map(r=>routineManageRow(r)).join('');bindPage(route)});
 if(document.querySelector('[data-smart-beauty-plan]')) renderSmartBeautyPlan();
 if(document.querySelector('[data-after-events]')) renderAfterEventPanel();
 if(document.querySelector('[data-after-events]')){
   document.querySelectorAll('[data-event-toggle]').forEach(btn=>btn.onclick=()=>{
     const st=ensureEventState(), key=btn.dataset.eventToggle;
     const i=st.selected.indexOf(key);
     if(i>=0) st.selected.splice(i,1); else st.selected.push(key);
     save();
     renderAfterEventPanel();
     if(document.querySelector('[data-smart-beauty-plan]')) renderSmartBeautyPlan();
   });
 }
 if(document.getElementById('beforeSel')){const updateCompare=()=>{const a=data.photos.find(x=>x.id===document.getElementById('beforeSel').value),b=data.photos.find(x=>x.id===document.getElementById('afterSel').value);document.getElementById('compare').innerHTML=compareHTML(a,b);const r=document.getElementById('compareRange'),c=document.getElementById('afterClip');if(r&&c)r.addEventListener('input',()=>c.style.width=r.value+'%')};document.getElementById('beforeSel').onchange=updateCompare;document.getElementById('afterSel').onchange=updateCompare;updateCompare()}
}
function compareHTML(a,b){if(!a||!b)return '';return `<div style="position:relative;overflow:hidden;border-radius:20px;border:1px solid var(--border);background:#000;height:420px"><img src="${a.image||''}" style="position:absolute;inset:0;width:100%;height:100%;object-fit:contain"><div id="afterClip" style="position:absolute;left:50%;top:0;bottom:0;width:50%;overflow:hidden"><img src="${b.image||''}" style="position:absolute;right:0;top:0;height:100%;width:100vw;max-width:none;object-fit:contain"></div><input id="compareRange" type="range" min="0" max="100" value="50" style="position:absolute;left:10px;right:10px;bottom:10px;width:calc(100% - 20px)"><div style="position:absolute;top:10px;left:10px;padding:6px 9px;border-radius:999px;background:rgba(0,0,0,.45);color:#fff">До</div><div style="position:absolute;top:10px;right:10px;padding:6px 9px;border-radius:999px;background:rgba(0,0,0,.45);color:#fff">После</div></div>`}

function modal(inner){document.getElementById('modalRoot').innerHTML=`<div class="modal-backdrop" id="modalBg"><div class="modal">${inner}</div></div>`;document.getElementById('modalBg').onclick=e=>{if(e.target.id==='modalBg')closeModal()}}
function closeModal(){document.getElementById('modalRoot').innerHTML=''}
function routineModal(id){const r=id?data.routines.find(x=>x.id===id):{id:'',startDate:todayKey(),title:'',category:'skin',slot:'morning',days:[1,2,3,4,5,6,0],time:'08:00',frequency:'daily',notes:'',productId:''};const dayOpts=['Пн','Вт','Ср','Чт','Пт','Сб','Вс'];modal(`<h3>${id?'Изменить':'Добавить'} этап ухода</h3><form id="routineForm" class="form"><div class="field"><label>Название</label><input name="title" required value="${esc(r.title)}"></div><div class="grid grid-2"><div class="field"><label>Категория</label><select name="category"><option value="skin" ${r.category==='skin'?'selected':''}>🌸 Кожа</option><option value="hair" ${r.category==='hair'?'selected':''}>🎀 Волосы</option></select></div><div class="field"><label>Блок</label><select name="slot"><option value="morning" ${r.slot==='morning'?'selected':''}>Утро</option><option value="evening" ${r.slot==='evening'?'selected':''}>Вечер</option><option value="extra" ${r.slot==='extra'?'selected':''}>Extra Care</option></select></div></div><div class="field"><label>Дни недели</label><div class="row wrap">${dayOpts.map((x,i)=>`<label class="tag"><input type="checkbox" name="days" value="${(i+1)%7}" ${r.days?.includes((i+1)%7)?'checked':''}>${x}</label>`).join('')}</div></div><div class="grid grid-2"><div class="field"><label>Дата старта</label><input name="startDate" type="date" value="${r.startDate||todayKey()}"></div><div class="field"><label>Время</label><input name="time" type="time" value="${r.time||''}"></div><div class="field"><label>Частота</label><select name="frequency"><option value="daily" ${r.frequency==='daily'?'selected':''}>Каждый день</option><option value="weekly" ${r.frequency==='weekly'?'selected':''}>Еженедельно</option><option value="biweekly" ${r.frequency==='biweekly'?'selected':''}>Раз в 2 недели</option><option value="monthly" ${r.frequency==='monthly'?'selected':''}>Раз в месяц</option></select></div></div><div class="field"><label>Средство</label><select name="productId"><option value="">— Не привязывать —</option>${data.products.map(p=>`<option value="${p.id}" ${r.productId===p.id?'selected':''}>${esc(p.name)}</option>`).join('')}</select></div><div class="field"><label>Заметка</label><textarea name="notes">${esc(r.notes||'')}</textarea></div><div class="modal-actions"><button type="button" class="btn secondary" id="cancelModal">Отмена</button><button class="btn">Сохранить</button></div></form>`);document.getElementById('cancelModal').onclick=closeModal;document.getElementById('routineForm').onsubmit=e=>{e.preventDefault();const f=new FormData(e.target);const nr={id:r.id||uid(),title:f.get('title').trim(),category:f.get('category'),slot:f.get('slot'),days:f.getAll('days').map(Number),time:f.get('time'),frequency:f.get('frequency'),startDate:f.get('startDate')||todayKey(),productId:f.get('productId'),notes:f.get('notes')};if(id){const i=data.routines.findIndex(x=>x.id===id);data.routines[i]=nr}else data.routines.push(nr);save();closeModal();render();toast('Рутина сохранена ♡')};}
function productModal(id){
 const p=id?data.products.find(x=>x.id===id):{id:'',name:'',brand:'',category:'',notes:'',image:'',inci:'',sku:''};
 modal(`<h3>${id?'Изменить':'Добавить'} средство</h3><form id="productForm" data-product-id="${esc(p.id||'')}" class="form"><div class="grid grid-2"><div class="field"><label>Название</label><input name="name" required value="${esc(p.name)}"></div><div class="field"><label>Бренд</label><input name="brand" value="${esc(p.brand)}"></div></div><div class="grid grid-2"><div class="field"><label>Категория</label><input name="category" value="${esc(p.category)}" placeholder="Сыворотка, крем…"></div><div class="field"><label>Артикул</label><input name="sku" value="${esc(p.sku||'')}"></div></div><div class="field"><label>Состав INCI</label><textarea name="inci" placeholder="Aqua, Glycerin, Panthenol…">${esc(p.inci||'')}</textarea></div><div class="field"><label>Мои заметки</label><textarea name="notes">${esc(p.notes||'')}</textarea></div><div class="field"><label>Фото</label><input name="image" type="file" accept="image/*"></div><div class="modal-actions"><button type="button" class="btn secondary" id="cancelModal">Отмена</button><button class="btn">Сохранить</button></div></form>`);
 document.getElementById('cancelModal').onclick=closeModal;
 document.getElementById('productForm').onsubmit=async e=>{e.preventDefault();const f=new FormData(e.target);let image=p.image||'';const file=f.get('image');if(file?.size)image=await fileToDataURL(file);const np={id:p.id||uid(),name:f.get('name').trim(),brand:f.get('brand').trim(),category:f.get('category').trim(),notes:f.get('notes'),inci:f.get('inci'),sku:f.get('sku').trim(),image,used:p.used||0};if(id){const i=data.products.findIndex(x=>x.id===id);data.products[i]=np}else data.products.push(np);save();closeModal();render();};
}
function dayModal(key){const s=dayStats(key);const ev=data.events.filter(e=>e.date===key);modal(`<h3>${fmtDate(key)}</h3><p class="subtle">${s.done.length}/${s.all.length} выполнено · ${s.p}%</p><div class="list">${s.all.map(r=>`<div class="task ${isDone(key,r.id)?'done':''}"><button class="check ${isDone(key,r.id)?'done':''}" data-day-complete="${r.id}">${isDone(key,r.id)?'✓':'○'}</button><div style="flex:1"><strong>${esc(r.title)}</strong><div class="subtle">${slotName(r.slot)}</div></div></div>`).join('')}</div><h4 style="margin-top:18px">✦ События</h4>${ev.map(e=>`<div class="item"><strong>${esc(e.title)}</strong><p>${esc(e.note||'')}</p></div>`).join('')||'<div class="empty">Нет событий.</div>'}<div class="modal-actions"><button class="btn secondary" id="addEvent">+ Добавить событие</button><button class="btn ghost" id="closeDay">Закрыть</button></div>`);document.querySelectorAll('[data-day-complete]').forEach(b=>b.onclick=()=>{const rid=b.dataset.dayComplete;isDone(key,rid)?undo(rid,key):complete(rid,key);closeModal();render();});document.getElementById('closeDay').onclick=closeModal;document.getElementById('addEvent').onclick=()=>eventModal(key)}
function eventModal(date){modal(`<h3>Новое событие</h3><form id="eventForm" class="form"><div class="field"><label>Название</label><input name="title" required placeholder="Фото прогресса, маска…"></div><div class="field"><label>Заметка</label><textarea name="note"></textarea></div><div class="modal-actions"><button type="button" class="btn secondary" id="cancelModal">Отмена</button><button class="btn">Сохранить</button></div></form>`);document.getElementById('cancelModal').onclick=closeModal;document.getElementById('eventForm').onsubmit=e=>{e.preventDefault();const f=new FormData(e.target);data.events.push({id:uid(),date,title:f.get('title'),note:f.get('note')});save();closeModal();render();}}
function goalModal(){modal(`<h3>Новая цель</h3><form id="goalForm" class="form"><div class="field"><label>Название</label><input name="title" required placeholder="30 дней без пропусков"></div><div class="field"><label>Описание</label><textarea name="description"></textarea></div><div class="grid grid-2"><div class="field"><label>Цель, шагов</label><input name="target" type="number" min="1" value="30"></div><div class="field"><label>Срок</label><input name="due" type="date"></div></div><div class="modal-actions"><button type="button" class="btn secondary" id="cancelModal">Отмена</button><button class="btn">Создать</button></div></form>`);document.getElementById('cancelModal').onclick=closeModal;document.getElementById('goalForm').onsubmit=e=>{e.preventDefault();const f=new FormData(e.target);data.goals.push({id:uid(),title:f.get('title').trim(),description:f.get('description'),target:+f.get('target'),progress:0,due:f.get('due')});save();closeModal();render()}}
function noteModal(){modal(`<h3>Новая запись</h3><form id="noteForm" class="form"><div class="field"><label>Дата</label><input name="date" type="date" value="${todayKey()}"></div><div class="field"><label>Текст</label><textarea name="text" required placeholder="Сегодня кожа выглядит лучше…"></textarea></div><div class="modal-actions"><button type="button" class="btn secondary" id="cancelModal">Отмена</button><button class="btn">Сохранить</button></div></form>`);document.getElementById('cancelModal').onclick=closeModal;document.getElementById('noteForm').onsubmit=e=>{e.preventDefault();const f=new FormData(e.target);data.notes.push({id:uid(),date:f.get('date'),text:f.get('text')});save();closeModal();render()}}
function petModal(){modal(`<h3>Настроить питомца</h3><form id="petForm" class="form"><div class="field"><label>Имя</label><input name="name" value="${esc(data.pet.name)}"></div><div class="item"><strong>🐱 Твой питомец — кошечка</strong><p class="subtle">Вид закреплён: питомец всегда остаётся кошечкой ♡</p></div><div class="modal-actions"><button type="button" class="btn secondary" id="cancelModal">Отмена</button><button class="btn">Сохранить</button></div></form>`);document.getElementById('cancelModal').onclick=closeModal;document.getElementById('petForm').onsubmit=e=>{e.preventDefault();const f=new FormData(e.target);data.pet.name=f.get('name').trim()||'Луна';data.pet.kind='котёнок';save();closeModal();render()}}
function challengeModal(){modal(`<h3>Свой челлендж</h3><form id="challengeForm" class="form"><div class="field"><label>Название</label><input name="title" required></div><div class="field"><label>Описание</label><textarea name="description"></textarea></div><div class="grid grid-2"><div class="field"><label>Цель</label><input name="goal" type="number" min="1" value="7"></div><div class="field"><label>Награда XP</label><input name="reward" type="number" min="10" value="100"></div></div><div class="modal-actions"><button type="button" class="btn secondary" id="cancelModal">Отмена</button><button class="btn">Создать</button></div></form>`);document.getElementById('cancelModal').onclick=closeModal;document.getElementById('challengeForm').onsubmit=e=>{e.preventDefault();const f=new FormData(e.target);data.challenges.push({id:uid(),title:f.get('title'),description:f.get('description'),goal:+f.get('goal'),progress:0,reward:+f.get('reward'),type:'manual',done:false,builtIn:false});save();closeModal();render()}}
function articleModal(id){const a=articles.find(x=>x.id===id);if(!a)return;if(!data.articlesRead.includes(id)){data.articlesRead.push(id);addXP(5,'Прочитана статья');checkAchievements();save()}modal(`<h3>${esc(a.title)}</h3><span class="tag">${a.tag}</span><p style="line-height:1.8;margin-top:14px">${esc(a.text)}</p><div class="modal-actions"><button class="btn" id="closeArticle">Готово</button></div>`);document.getElementById('closeArticle').onclick=closeModal}
async function photoSubmit(e){e.preventDefault();const f=new FormData(e.target);const file=f.get('image');if(!file?.size){toast('Выбери фото ♡');return}const image=await fileToDataURL(file);data.photos.push({id:uid(),date:f.get('date'),category:f.get('category'),score:+f.get('score')||0,note:f.get('note'),image});addXP(15,'Фото прогресса');checkAchievements();refreshChallenges();save();render();toast('Фото сохранено 📸')}
function fileToDataURL(file){return new Promise((res,rej)=>{const r=new FileReader();r.onload=()=>res(r.result);r.onerror=rej;r.readAsDataURL(file)})}
function copyReport(){navigator.clipboard?.writeText(generateReport()).then(()=>toast('Отчёт скопирован ♡')).catch(()=>toast('Не удалось скопировать'))}
function generateReport(){const week=statsRange(7),month=statsRange(30);return `МОЙ БЬЮТИ-ДНЕВНИК ♡\nДата: ${fmtDate(todayKey())}\n\n7 дней: ${pct(week.reduce((a,x)=>a+x.done.length,0),week.reduce((a,x)=>a+x.all.length,0))}%\n30 дней: ${pct(month.reduce((a,x)=>a+x.done.length,0),month.reduce((a,x)=>a+x.all.length,0))}%\nВсего процедур: ${totalCompleted()}\nИдеальных дней: ${bestPerfectDays()}\nТекущая серия: ${currentStreak()}\nЛучший streak: ${bestStreak()}\nXP: ${data.xp}\nУровень: ${data.level}\nДостижения: ${data.unlocked.length}/${achievementDefs.length}\nФото: ${data.photos.length}`}
function downloadReport(){downloadBlob(generateReport(),'beauty-report.txt','text/plain;charset=utf-8')}
function downloadBlob(text,name,type){const blob=new Blob([text],{type});const a=document.createElement('a');a.href=URL.createObjectURL(blob);a.download=name;a.click();setTimeout(()=>URL.revokeObjectURL(a.href),1000)}
function importBackup(e){const f=e.target.files[0];if(!f)return;const r=new FileReader();r.onload=()=>{try{data=JSON.parse(r.result);normalize();save();render();toast('Бэкап импортирован ♡')}catch{toast('Файл не удалось прочитать')}};r.readAsText(f)}
function resetData(){if(confirm('Точно очистить все данные? Это нельзя отменить.')){data=blankData();save();render();toast('Данные очищены')}}


/* ===== BEAUTY PRO PACK v1: PET + SHOP + FAVORITES ===== */
const SHOP_CATALOG=[
 {id:'theme-peach',type:'theme',title:'Персиковый рассвет',icon:'🍑',cost:220,rarity:'Обычный',desc:'Тёплая сияющая тема для утреннего настроения.',vars:{'--bg':'#fffaf5','--surface':'#fffdf9','--surface2':'#fff0e6','--text':'#4a3b36','--muted':'#9b8680','--primary':'#e99f7d','--primary2':'#f6cfbe','--accent':'#d9a6e9'}},
 {id:'theme-berry',type:'theme',title:'Ягодный крем',icon:'🍓',cost:320,rarity:'Редкий',desc:'Насыщенная ягодная версия твоего дневника.',vars:{'--bg':'#fff7fb','--surface':'#fff','--surface2':'#fde8f2','--text':'#493642','--muted':'#967f8b','--primary':'#d76a9c','--primary2':'#efb0ca','--accent':'#a98add'}},
 {id:'pet-crown',type:'pet',title:'Корона для питомца',icon:'👑',cost:180,rarity:'Обычный',desc:'Маленькая корона для большого характера.'},
 {id:'pet-bow',type:'pet',title:'Бантик',icon:'🎀',cost:140,rarity:'Обычный',desc:'Милый аксессуар для ежедневного ухода.'},
 {id:'pet-halo',type:'pet',title:'Сияющий нимб',icon:'😇',cost:420,rarity:'Эпический',desc:'Редкий аксессуар для особенно заботливых хозяек.'},
 {id:'frame-heart',type:'frame',title:'Рамка «Сердечки»',icon:'💗',cost:160,rarity:'Обычный',desc:'Розовая рамка для аватарки и профиля.',shopAvatarFrame:true,frameId:'heart'},
 {id:'frame-lavender',type:'frame',title:'Рамка «Лаванда»',icon:'🪻',cost:260,rarity:'Редкий',desc:'Нежная лавандовая рамка.',shopAvatarFrame:true,frameId:'lavender'},
 {id:'frame-kitty',type:'frame',title:'Рамка «Kitty Dream»',icon:'🐱',cost:220,rarity:'Обычный',desc:'Милая кошачья рамка с ушками и сердечками.',shopAvatarFrame:true,frameId:'kitty'},
 {id:'frame-kuromi',type:'frame',title:'Рамка «Kuromi Night»',icon:'🖤',cost:360,rarity:'Редкий',desc:'Стильная тёмная рамка с дерзким характером.',shopAvatarFrame:true,frameId:'kuromi'},
 {id:'frame-sakura',type:'frame',title:'Рамка «Sakura»',icon:'🌸',cost:280,rarity:'Редкий',desc:'Нежные лепестки сакуры вокруг аватара.',shopAvatarFrame:true,frameId:'sakura'},
 {id:'frame-coquette',type:'frame',title:'Рамка «Coquette»',icon:'🎀',cost:390,rarity:'Эпический',desc:'Бантики, жемчуг и кокетливое настроение.',shopAvatarFrame:true,frameId:'coquette'},
 {id:'frame-strawberry',type:'frame',title:'Рамка «Strawberry»',icon:'🍓',cost:320,rarity:'Редкий',desc:'Сладкая ягодная рамка для яркого профиля.',shopAvatarFrame:true,frameId:'strawberry'},
 {id:'frame-mint',type:'frame',title:'Рамка «Mint Spa»',icon:'🍃',cost:300,rarity:'Редкий',desc:'Свежая мятная рамка в spa-стиле.',shopAvatarFrame:true,frameId:'mint'},
 {id:'frame-lavender-cloud',type:'frame',title:'Рамка «Lavender Cloud»',icon:'☁️',cost:340,rarity:'Эпический',desc:'Облачная рамка с лавандовыми звёздочками.',shopAvatarFrame:true,frameId:'lavender-cloud'},
 {id:'frame-cozy',type:'frame',title:'Рамка «Cozy Glow»',icon:'☕',cost:360,rarity:'Эпический',desc:'Тёплая уютная рамка с мягким свечением.',shopAvatarFrame:true,frameId:'cozy'},
 {id:'frame-royal',type:'frame',title:'Рамка «Royal Glow»',icon:'👑',cost:650,rarity:'Легендарный',desc:'Королевская рамка с золотыми искрами.',shopAvatarFrame:true,frameId:'royal'},
 {id:'frame-midnight',type:'frame',title:'Рамка «Midnight Glow»',icon:'🌙',cost:520,rarity:'Легендарный',desc:'Ночная рамка с луной и мерцающими звёздами.',shopAvatarFrame:true,frameId:'midnight'},
 {id:'sticker-sparkle',type:'sticker',title:'Наклейка «Искры»',icon:'✨',cost:90,rarity:'Обычный',desc:'Декоративная наклейка для твоих little wins.'},
 {id:'sticker-ribbon',type:'sticker',title:'Наклейка «Розовая лента»',icon:'🎀',cost:110,rarity:'Обычный',desc:'Для красивых карточек и заметок.'},
 {id:'badge-glow',type:'badge',title:'Значок «Девушка сияния»',icon:'🌸',cost:500,rarity:'Эпический',desc:'Редкий знак коллекционера beauty-прогресса.'},
 {id:'badge-queen',type:'badge',title:'Значок «Care Queen»',icon:'👑',cost:800,rarity:'Легендарный',desc:'Для тех, кто действительно держит ритм.'},
 {id:'pet-bed',type:'pet',title:'Облачная кроватка',icon:'☁️',cost:280,rarity:'Редкий',desc:'Питомец восстанавливает энергию немного быстрее.'},
 {id:'pet-garden',type:'pet',title:'Мини-сад',icon:'🌷',cost:340,rarity:'Редкий',desc:'Добавляет уют и немного счастья питомцу.'},
 {id:'season-summer',type:'season',title:'Лето в косметичке',icon:'🍹',cost:380,rarity:'Редкий',desc:'Лимитированный сезонный набор декора.'},
 {id:'season-night',type:'season',title:'Ночная рутина',icon:'🌙',cost:460,rarity:'Эпический',desc:'Тёмный комплект для вечерних ритуалов.'}
];

function ensureProData(){
 data.pet={...data.pet, name:data.pet.name||'Луна', kind:'котёнок', stage:Number(data.pet.stage)||1, hunger:Number.isFinite(Number(data.pet.hunger))?Number(data.pet.hunger):70, happiness:Number.isFinite(Number(data.pet.happiness))?Number(data.pet.happiness):72, energy:Number.isFinite(Number(data.pet.energy))?Number(data.pet.energy):80, points:Number.isFinite(Number(data.pet.points))?Number(data.pet.points):0, feedCount:Number.isFinite(Number(data.pet.feedCount))?Number(data.pet.feedCount):0, playCount:Number.isFinite(Number(data.pet.playCount))?Number(data.pet.playCount):0,food: data.pet.food||0,accessories:Array.isArray(data.pet.accessories)?data.pet.accessories:[],hungerLast:data.pet.hungerLast||Date.now(),affection:Number.isFinite(Number(data.pet.affection))?Number(data.pet.affection):68,bond:Number.isFinite(Number(data.pet.bond))?Number(data.pet.bond):0};
 data.shop={owned:Array.isArray(data.shop?.owned)?data.shop.owned:[],equipped:{...(data.shop?.equipped||{})},favorites:Array.isArray(data.shop?.favorites)?data.shop.favorites:[],lastReward:Number(data.shop?.lastReward)||0}; data.pet.kind='котёнок';
 data.favoriteProducts=Array.isArray(data.favoriteProducts)?data.favoriteProducts:[];
 data.productRatings=data.productRatings||{};
 data.productReviews=Array.isArray(data.productReviews)?data.productReviews:[];
 data.shop.favorites=Array.isArray(data.shop.favorites)?data.shop.favorites:[];
 data.pet.accessories=Array.isArray(data.pet.accessories)?data.pet.accessories:[];
}
const baseNormalize=normalize;
normalize=function(){baseNormalize();ensureProData();};

function petStageLabel(){return data.pet.stage===1?'Малыш':data.pet.stage===2?'Юный хранитель':'Взрослый хранитель'}
function petNeeds(){const p=data.pet;return p.hunger<35||p.happiness<35||p.energy<30?'Питомцу не хватает заботы ♡':p.happiness>84?'Питомец сияет от счастья ✨':'Питомец доволен твоей заботой.'}
function petEmoji(){const s=Math.max(1,Math.min(10,Number(data.pet.stage)||1));return ['🐱','😺','😸','😽','😻','😺','😸','😻','😼','🐱'][s-1];}
function petPointsNeeded(){return [0,180,520][data.pet.stage-1]||520}
function checkPetEvolution(){if(data.pet.points>=520)data.pet.stage=3;else if(data.pet.points>=180)data.pet.stage=2}
function petFeed(){ensureProData();const now=Date.now();if(window.__lastPetAction&&now-window.__lastPetAction<250)return;window.__lastPetAction=now;if(data.pet.hunger>=96){toast('Питомец уже сытый 🥹');return}data.pet.hunger=Math.min(100,data.pet.hunger+22);data.pet.happiness=Math.min(100,data.pet.happiness+5);data.pet.energy=Math.min(100,data.pet.energy+3);data.pet.feedCount++;data.pet.affection=Math.min(100,data.pet.affection+2);data.pet.bond++;data.pet.points+=8;checkPetEvolution();addXP(3,'Забота о питомце');save();checkAchievements();render();}
function petPlay(){ensureProData();const now=Date.now();if(window.__lastPetAction&&now-window.__lastPetAction<250)return;window.__lastPetAction=now;if(data.pet.energy<15){toast('Питомец устал — дай ему немного отдохнуть ♡');return}data.pet.happiness=Math.min(100,data.pet.happiness+14);data.pet.hunger=Math.max(0,data.pet.hunger-5);data.pet.energy=Math.max(0,data.pet.energy-15);data.pet.playCount++;data.pet.affection=Math.min(100,data.pet.affection+3);data.pet.bond++;data.pet.points+=12;checkPetEvolution();addXP(5,'Игра с питомцем');save();checkAchievements();render();}
function tickPet(){ensureProData();const now=Date.now();const hours=(now-(data.pet.hungerLast||now))/3600000;if(hours>=4){const steps=Math.floor(hours/4);data.pet.hunger=Math.max(0,data.pet.hunger-steps*4);data.pet.happiness=Math.max(0,data.pet.happiness-steps*2);data.pet.energy=Math.max(0,data.pet.energy-steps);data.pet.hungerLast=now;save()};checkPetEvolution()}
function equipShop(id){const item=SHOP_CATALOG.find(x=>x.id===id);if(!item)return;if(!data.shop.owned.includes(id)){toast('Сначала купи этот предмет ♡');return}if(item.type==='theme'){data.settings.theme='shop-'+id;applyShopTheme(item);data.shop.equipped.theme=id;data.themeChanges++;}else if(item.type==='pet'){if(data.pet.accessories.includes(id))data.pet.accessories=data.pet.accessories.filter(x=>x!==id);else data.pet.accessories.push(id);data.shop.equipped.pet=data.pet.accessories.at(-1)||'';}else data.shop.equipped[item.type]=id;save();toast(`${item.title} ${data.shop.equipped[item.type]===id?'включено':'обновлено'} ✨`);render()}
function applyShopTheme(item){if(!item?.vars)return;Object.entries(item.vars).forEach(([k,v])=>document.documentElement.style.setProperty(k,v));document.querySelector('meta[name="theme-color"]').setAttribute('content',item.vars['--primary']);}
const baseApplyTheme=applyTheme;
applyTheme=function(){baseApplyTheme();ensureProData();const id=data.shop?.equipped?.theme;if(id){const item=SHOP_CATALOG.find(x=>x.id===id);if(item)applyShopTheme(item)}};
function buyShop(id){ensureProData();const item=SHOP_CATALOG.find(x=>x.id===id);if(!item)return;if(data.shop.owned.includes(id)){equipShop(id);return}if(data.xp<item.cost){toast(`Нужно ещё ${item.cost-data.xp} XP ♡`);return}data.xp-=item.cost;data.shop.owned.push(id);addXP(0,'');save();toast(`Получено: ${item.title} ${item.icon}`);equipShop(id)}
function productRating(p){return data.productRatings[p.id]?.score||p.rating||0}
function productIsFav(p){return data.favoriteProducts.includes(p.id)}
function toggleFav(id){if(data.favoriteProducts.includes(id))data.favoriteProducts=data.favoriteProducts.filter(x=>x!==id);else data.favoriteProducts.push(id);save();toast(data.favoriteProducts.includes(id)?'Добавлено в любимчики ♡':'Убрано из любимчиков');render()}
function rateProductModal(id){const p=data.products.find(x=>x.id===id);if(!p)return;const r=data.productRatings[id]||{score:0,repurchase:'',effect:'',note:''};modal(`<h3>${esc(p.name)} ♡</h3><form id="ratingForm" class="form"><div class="grid grid-2"><div class="field"><label>Моя оценка</label><select name="score"><option value="0">Не оценено</option>${[1,2,3,4,5,6,7,8,9,10].map(n=>`<option value="${n}" ${r.score==n?'selected':''}>${n}/10</option>`).join('')}</select></div><div class="field"><label>Повторить покупку?</label><select name="repurchase"><option value="">Выбрать…</option><option value="yes" ${r.repurchase==='yes'?'selected':''}>Да 💗</option><option value="maybe" ${r.repurchase==='maybe'?'selected':''}>Возможно</option><option value="no" ${r.repurchase==='no'?'selected':''}>Нет</option></select></div></div><div class="field"><label>Как ощущается</label><input name="effect" value="${esc(r.effect||'')}" placeholder="Мягко, сияюще, тяжеловато…"></div><div class="field"><label>Моя заметка</label><textarea name="note" placeholder="Что особенно понравилось?">${esc(r.note||'')}</textarea></div><div class="modal-actions"><button type="button" class="btn secondary" id="cancelModal">Отмена</button><button class="btn">Сохранить оценку</button></div></form>`);document.getElementById('cancelModal').onclick=closeModal;document.getElementById('ratingForm').onsubmit=e=>{e.preventDefault();const f=new FormData(e.target);data.productRatings[id]={score:+f.get('score'),repurchase:f.get('repurchase'),effect:f.get('effect'),note:f.get('note'),updated:Date.now()};save();closeModal();toast('Оценка сохранена ♡');render()}}
function useProduct(id){const p=data.products.find(x=>x.id===id);if(!p)return;p.used=(p.used||0)+1;save();toast(`${p.name}: +1 использование ♡`);render()}
function shopInventoryPage(){return `<div class="row between wrap"><div><h3 class="section-title">🛍️ Бьюти-магазин</h3><p class="subtle">Трать XP на темы, аксессуары, рамки и редкие коллекционные предметы.</p></div><span class="tag">✨ ${data.xp} XP доступно</span></div><div class="grid grid-4" style="margin-top:16px">${SHOP_CATALOG.map(item=>{const own=data.shop.owned.includes(item.id);return `<div class="card shop-card"><div class="shop-icon">${item.icon}</div><span class="tag">${item.rarity}</span><h4>${esc(item.title)}</h4><p class="subtle">${esc(item.desc)}</p><div class="row between"><strong>${own?'Получено':'✦ '+item.cost+' XP'}</strong><button class="btn ${own?'secondary':''} small" data-shop-buy="${item.id}">${own?(data.shop.equipped.theme===item.id||data.shop.equipped.pet===item.id?'Используется':'Использовать'):'Получить'}</button></div></div>`}).join('')}</div>`}
function favoritesPage(){const fav=data.products.filter(productIsFav);const rated=data.products.filter(p=>productRating(p)>0);const avg=rated.length?(rated.reduce((s,p)=>s+productRating(p),0)/rated.length).toFixed(1):'—';return `<section class="card hero"><div class="row between wrap"><div><div class="label">Твоя полка</div><h1 style="font-family:Georgia,serif;margin:4px 0">♡ Мои любимчики</h1><p>Здесь только средства, к которым хочется возвращаться.</p></div><div class="circle" style="--p:${rated.length?avg*10:0}"><div class="inside"><span class="label">Средняя</span><strong>${avg}</strong><span class="subtle">из 10</span></div></div></div></section><div class="grid grid-3" style="margin-top:16px">${fav.length?fav.map(productLargeCard).join(''):'<div class="empty" style="grid-column:1/-1">♡ Пока пусто. Нажми сердечко у любого средства, чтобы добавить его сюда.</div>'}</div><section class="card" style="margin-top:16px"><div class="row between"><h3 class="section-title">⭐ Быстрые оценки</h3><button class="btn secondary small" data-route="products">К средствам</button></div><div class="list">${rated.sort((a,b)=>productRating(b)-productRating(a)).slice(0,6).map(p=>`<div class="item"><div class="row between"><div><strong>${esc(p.name)}</strong><div class="subtle">${esc(p.brand||'Без бренда')}</div></div><button class="btn secondary small" data-rate-product="${p.id}">♡ ${productRating(p)}/10</button></div></div>`).join('')||'<div class="empty">Поставь первую оценку своему средству ♡</div>'}</div></section>`}
function productLargeCard(p){const score=productRating(p);return `<div class="card"><div style="height:190px;border-radius:18px;background:var(--surface2);display:grid;place-items:center;overflow:hidden;position:relative">${p.image?`<img src="${p.image}" style="width:100%;height:100%;object-fit:cover">`:'🧴'}<button class="icon-btn" data-fav-product="${p.id}" style="position:absolute;right:10px;top:10px">${productIsFav(p)?'♥':'♡'}</button></div><h3 style="margin:12px 0 4px">${esc(p.name)}</h3><div class="subtle">${esc(p.brand||'Без бренда')} · ${esc(p.category||'Другое')}</div><div class="row wrap" style="margin:10px 0"><span class="tag">⭐ ${score?score+'/10':'Без оценки'}</span><span class="tag">Использовано ${p.used||0} раз</span></div><div class="row wrap"><button class="btn small" data-rate-product="${p.id}">Оценить</button><button class="btn secondary small" data-use-product="${p.id}">Использовала</button></div></div>`}
function improvedProductsPage(){return `<div class="row between wrap"><div><h3 class="section-title">🧴 Мои средства</h3><p class="subtle">Твоя полка + оценки + любимчики.</p></div><div class="row wrap"><button class="btn secondary" data-route="favorites">♡ Любимчики</button><button class="btn" data-add-product>+ Добавить средство</button></div></div><div class="grid grid-4" style="margin:14px 0"><div class="stat"><span class="label">Всего средств</span><b>${data.products.length}</b></div><div class="stat"><span class="label">Любимчики</span><b>${data.favoriteProducts.length}</b></div><div class="stat"><span class="label">Оценено</span><b>${data.products.filter(p=>productRating(p)>0).length}</b></div><div class="stat"><span class="label">Средняя оценка</span><b>${(()=>{const a=data.products.filter(p=>productRating(p)>0);return a.length?(a.reduce((s,p)=>s+productRating(p),0)/a.length).toFixed(1):'—'})()}</b></div></div><div class="field" style="margin:14px 0"><input id="productSearch" placeholder="Поиск по средствам, бренду, заметкам…"></div><div class="grid grid-3" id="productGrid">${data.products.length?data.products.map(productLargeCard).join(''):'<div class="empty" style="grid-column:1/-1">♡ Твоя полка пока пуста.</div>'}</div>`}

function enhancedPetPage(){const p=data.pet;const petOwned=SHOP_CATALOG.filter(x=>x.type==='pet'&&data.shop.owned.includes(x.id));const stageXP=p.stage===1?`${p.points}/180`:p.stage===2?`${p.points}/520`:`Максимальная стадия ✨`;return `<section class="card hero"><div class="split"><div class="pet pet-big">${petEmoji()}</div><div style="flex:1"><div class="label">Личный помощник</div><h1 style="font-family:Georgia,serif;margin:4px 0">${esc(p.name)} ♡</h1><div class="pet-stage">${petStageLabel()}</div><p>${petNeeds()}</p><div class="row wrap"><span class="tag">✨ Забота ${p.points}</span><span class="tag">🤍 Привязанность ${p.affection}</span><span class="tag">🎀 Игр ${p.playCount}</span></div></div></div><div class="row wrap" style="margin-top:18px"><button class="btn" data-pet-feed type="button">🍓 Покормить</button><button class="btn secondary" data-pet-play type="button">🎀 Поиграть</button><button class="btn ghost" data-pet-rest type="button">🌙 Отдохнуть</button><button class="btn ghost" data-edit-pet type="button">✎ Изменить</button></div></section><div class="grid grid-3" style="margin-top:16px"><div class="card"><h3 class="section-title">💗 Счастье</h3><div class="kpi">${p.happiness}%</div>${bar('Счастье',p.happiness)}</div><div class="card"><h3 class="section-title">🍓 Сытость</h3><div class="kpi">${p.hunger}%</div>${bar('Сытость',p.hunger)}</div><div class="card"><h3 class="section-title">⚡ Энергия</h3><div class="kpi">${p.energy}%</div>${bar('Энергия',p.energy)}</div></div><div class="grid grid-2" style="margin-top:16px"><section class="card"><div class="row between"><h3 class="section-title">🌱 Рост</h3><span class="tag">${stageXP}</span></div><div class="timeline"><div class="timeline-item"><strong>Малыш</strong><p class="subtle">0–179 очков заботы</p></div><div class="timeline-item"><strong>Подрастающий</strong><p class="subtle">180–519 очков заботы</p></div><div class="timeline-item"><strong>Взрослый хранитель</strong><p class="subtle">520+ очков заботы</p></div></div></section><section class="card"><div class="row between"><h3 class="section-title">🎀 Коллекция питомца</h3><button class="btn secondary small" data-route="shop">В Бьюти-магазин</button></div>${petOwned.length?`<div class="grid grid-3">${petOwned.map(i=>`<div class="item"><div style="font-size:34px">${i.icon}</div><strong>${esc(i.title)}</strong><button class="btn secondary small" data-equip-shop="${i.id}" style="margin-top:8px">${p.accessories.includes(i.id)?'Снять':'Надеть'}</button></div>`).join('')}</div>`:'<div class="empty">Пока нет аксессуаров. Питомцу пора в Бьюти-магазин ♡</div>'}</section></div>`}

function renderShell(route){
 const titleMap={home:'Главная',today:'Сегодня',care:'Уход',products:'Средства',favorites:'Мои любимчики',shop:'Бьюти-магазин',calendar:'Календарь',progress:'Прогресс',achievements:'Достижения',goals:'Цели',journal:'Дневник',pet:'Питомец',challenges:'Челленджи',tips:'Советы',articles:'Мини-статьи',reports:'Отчёты',settings:'Настройки'};
 const nav=getSidebarNav();
 document.getElementById('app').innerHTML=`<aside class="sidebar"><div class="brand"><h1>Мой Бьюти-дневник ♡</h1><p>Перетаскивай вкладки, чтобы менять их порядок</p></div><div class="nav">${nav.map(([id,ic,l])=>`<button data-route="${id}" data-sidebar-id="${id}" class="${route===id?'active':''}" title="Перетащи, чтобы изменить порядок"><span>${ic}</span>${l}<span class="nav-drag-handle" aria-hidden="true">⋮⋮</span></button>`).join('')}</div><div class="sidebar-bottom"><div class="stat"><span class="label">Уровень</span><b>${data.level}</b><span class="subtle">${data.xp} XP</span></div></div></aside><main class="main"><header class="topbar"><div class="topbar-title"><button class="icon-btn" id="mobileMenu">☰</button><h2>${titleMap[route]||'Мой Бьюти-дневник'}</h2></div><div class="row"><span class="tag">🔥 ${currentStreak()} дней</span><button class="icon-btn" data-route="settings">⚙</button></div></header><section class="content" id="page"></section><nav class="bottom-nav">${[['home','⌂','Главная'],['today','♡','Сегодня'],['care','🌸','Уход'],['progress','◯','Прогресс'],['more','☰','Ещё']].map(([id,ic,l])=>`<button data-route="${id}" class="${route===id?'active':''}"><div>${ic}</div>${l}</button>`).join('')}</nav></main>`;
 document.querySelectorAll('[data-route]').forEach(el=>el.addEventListener('click',()=>{const r=el.dataset.route;if(r==='more')openMore();else location.hash=r}));
 document.getElementById('mobileMenu')?.addEventListener('click',()=>window.openMore());
 bindSidebarDnD();
}
function renderPage(route){const p=document.getElementById('page');function afterEventPage(){
 return `<div data-after-events></div>`;
} const map={home:homePage,today:todayPage,care:carePage,products:improvedProductsPage,favorites:favoritesPage,shop:shopInventoryPage,calendar:calendarPage,progress:progressPage,achievements:achievementsPage,goals:goalsPage,journal:journalPage,pet:enhancedPetPage,challenges:challengesPage,tips:tipsPage,articles:articlesPage,reports:reportsPage,settings:settingsPage,'after-event':afterEventPage};p.innerHTML=(map[route]||homePage)();bindPage(route)}

const baseProductModal=productModal;
productModal=function(id){const p=id?data.products.find(x=>x.id===id):{id:'',name:'',brand:'',category:'',notes:'',image:'',rating:0};const r=data.productRatings[p.id]||{};modal(`<h3>${id?'Изменить':'Добавить'} средство ♡</h3><form id="productForm" data-product-id="${esc(p.id||'')}" class="form"><div class="grid grid-2"><div class="field"><label>Название</label><input name="name" required value="${esc(p.name)}"></div><div class="field"><label>Бренд</label><input name="brand" value="${esc(p.brand)}"></div></div><div class="grid grid-2"><div class="field"><label>Категория</label><input name="category" value="${esc(p.category)}" placeholder="Сыворотка, крем…"></div><div class="field"><label>Моя оценка</label><select name="score"><option value="0">Не оценено</option>${[1,2,3,4,5,6,7,8,9,10].map(n=>`<option value="${n}" ${(r.score||p.rating)==n?'selected':''}>${n}/10</option>`).join('')}</select></div></div><div class="field"><label>Мои заметки</label><textarea name="notes">${esc(p.notes||'')}</textarea></div><div class="field"><label>Фото</label><input name="image" type="file" accept="image/*"></div><div class="field"><label><input type="checkbox" name="favorite" ${productIsFav(p)?'checked':''}> Добавить в любимчики</label></div><div class="modal-actions"><button type="button" class="btn secondary" id="cancelModal">Отмена</button><button class="btn">Сохранить</button></div></form>`);document.getElementById('cancelModal').onclick=closeModal;document.getElementById('productForm').onsubmit=async e=>{e.preventDefault();const f=new FormData(e.target);let image=p.image||'';const file=f.get('image');if(file?.size)image=await fileToDataURL(file);const np={id:p.id||uid(),name:f.get('name').trim(),brand:f.get('brand').trim(),category:f.get('category').trim(),notes:f.get('notes'),image,used:p.used||0,rating:+f.get('score')||0};if(id){const i=data.products.findIndex(x=>x.id===id);data.products[i]=np}else data.products.push(np);if(+f.get('score'))data.productRatings[np.id]={score:+f.get('score'),updated:Date.now()};if(f.get('favorite')==='on'&&!data.favoriteProducts.includes(np.id))data.favoriteProducts.push(np.id);if(f.get('favorite')!=='on')data.favoriteProducts=data.favoriteProducts.filter(x=>x!==np.id);save();closeModal();render();toast('Средство сохранено ♡')}};

const baseBindPage=bindPage;
bindPage=function(route){baseBindPage(route);document.querySelectorAll('[data-shop-buy]').forEach(b=>b.onclick=()=>buyShop(b.dataset.shopBuy));document.querySelectorAll('[data-equip-shop]').forEach(b=>b.onclick=()=>equipShop(b.dataset.equipShop));document.querySelectorAll('[data-fav-product]').forEach(b=>b.onclick=()=>toggleFav(b.dataset.favProduct));document.querySelectorAll('[data-rate-product]').forEach(b=>b.onclick=()=>rateProductModal(b.dataset.rateProduct));document.querySelectorAll('[data-use-product]').forEach(b=>b.onclick=()=>useProduct(b.dataset.useProduct));};

/* product usage from completed routines */
const baseComplete=complete;
complete=function(id,key=todayKey()){baseComplete(id,key);const r=data.routines.find(x=>x.id===id);if(r?.productId){const p=data.products.find(x=>x.id===r.productId);if(p){p.used=(p.used||0)+1;save()}}};

/* extra achievements */
achievementDefs.push(
 {id:'fav3',title:'Полка любимчиков',desc:'Добавь 3 любимых средства.',icon:'💗',cat:'Средства',check:()=>data.favoriteProducts.length>=3},
 {id:'rated5',title:'Beauty-критик',desc:'Оцени 5 средств.',icon:'⭐',cat:'Средства',check:()=>Object.values(data.productRatings).filter(x=>x.score>0).length>=5},
 {id:'shop3',title:'Коллекционер',desc:'Собери 3 предмета из Бьюти-магазин.',icon:'🛍️',cat:'Shop',check:()=>data.shop.owned.length>=3},
 {id:'pet-bond',title:'Лучшие друзья',desc:'Набери 50 очков привязанности питомца.',icon:'🐾',cat:'Питомец',check:()=>data.pet.bond>=50},
 {id:'pet-accessory',title:'Стильный малыш',desc:'Надень аксессуар питомцу.',icon:'🎀',cat:'Питомец',check:()=>data.pet.accessories.length>=1},
 {id:'xp1000',title:'Тысяча заботы',desc:'Набери 1000 XP.',icon:'✨',cat:'Shop',check:()=>data.xp>=1000}
);

/* small visual polish */
const style=document.createElement('style');style.textContent=`.shop-card{position:relative;overflow:hidden}.shop-card:after{content:'✦';position:absolute;right:15px;top:9px;font-size:34px;opacity:.08}.shop-icon{height:120px;border-radius:20px;background:linear-gradient(135deg,var(--surface2),var(--surface));display:grid;place-items:center;font-size:58px;margin-bottom:12px}.pet-big{font-size:112px;filter:drop-shadow(0 14px 20px rgba(90,50,80,.15))}.shop-card h4{font-family:Georgia,serif;font-size:18px;margin:9px 0 5px}.btn.secondary:hover{transform:translateY(-1px)}
`;document.head.appendChild(style);

function petRest(){ensureProData();const now=Date.now();if(window.__lastPetAction&&now-window.__lastPetAction<250)return;window.__lastPetAction=now;data.pet.energy=Math.min(100,data.pet.energy+25);data.pet.happiness=Math.min(100,data.pet.happiness+4);data.pet.hunger=Math.max(0,data.pet.hunger-2);data.pet.points+=5;save();checkAchievements();toast('Питомец отдохнул и набрался сил 🌙');render()}

/* ===== BIG BEAUTY UPGRADE v2 ===== */
const BIG_CHALLENGES=[
 {id:'b1',title:'Утренняя корона',description:'Заверши утренний уход 7 раз.',goal:7,progress:0,reward:100,type:'auto-morning',icon:'👑',builtIn:true,cat:'habit'},
 {id:'b2',title:'Вечер без пропусков',description:'Заверши вечерний уход 14 раз.',goal:14,progress:0,reward:180,type:'auto-evening',icon:'🌙',builtIn:true,cat:'habit'},
 {id:'b3',title:'SPF-подруга',description:'Выполни процедуру со словом SPF 20 раз.',goal:20,progress:0,reward:220,type:'auto-spf',icon:'☀️',builtIn:true,cat:'skin'},
 {id:'b4',title:'Фото-история',description:'Добавь 20 фото прогресса.',goal:20,progress:0,reward:250,type:'auto-photos',icon:'📸',builtIn:true,cat:'habit'},
 {id:'b5',title:'Маленький ритуал',description:'Выполни 50 процедур.',goal:50,progress:0,reward:300,type:'auto-total',icon:'🪞',builtIn:true,cat:'habit'},
 {id:'b6',title:'Месяц заботы',description:'Собери 30 дней с хотя бы одной выполненной процедурой.',goal:30,progress:0,reward:350,type:'auto-care-days',icon:'🌸',builtIn:true,cat:'habit'},
 {id:'b7',title:'Кожа под присмотром',description:'10 выполненных процедур для кожи.',goal:10,progress:0,reward:120,type:'auto-skin',icon:'💗',builtIn:true,cat:'skin'},
 {id:'b8',title:'Волосы под присмотром',description:'10 выполненных процедур для волос.',goal:10,progress:0,reward:120,type:'auto-hair',icon:'🎀',builtIn:true,cat:'hair'},
 {id:'b9',title:'Любимица питомца',description:'Набери 100 очков заботы о питомце.',goal:100,progress:0,reward:180,type:'auto-pet-points',icon:'🐾',builtIn:true,cat:'pet'},
 {id:'b10',title:'Коллекционер',description:'Собери 5 предметов из Бьюти-магазин.',goal:5,progress:0,reward:220,type:'auto-shop',icon:'🛍️',builtIn:true,cat:'habit'},
 {id:'b11',title:'Оценка за старания',description:'Оцени 10 средств.',goal:10,progress:0,reward:180,type:'auto-rated',icon:'⭐',builtIn:true,cat:'habit'},
 {id:'b12',title:'Полка любимчиков',description:'Добавь 5 средств в любимчики.',goal:5,progress:0,reward:170,type:'auto-favorites',icon:'💞',builtIn:true,cat:'habit'},
 {id:'b13',title:'Статья за статьёй',description:'Прочитай 8 статей из раздела.',goal:8,progress:0,reward:150,type:'auto-articles',icon:'📖',builtIn:true,cat:'habit'},
 {id:'b14',title:'Погода в уме',description:'Обнови погоду 10 раз.',goal:10,progress:0,reward:100,type:'auto-weather',icon:'☁️',builtIn:true,cat:'habit'},
 {id:'b15',title:'Колесо удачи',description:'Покрути колесо 7 дней.',goal:7,progress:0,reward:200,type:'auto-wheel',icon:'🎡',builtIn:true,cat:'habit'}
];
const LUCK_PRIZES=[
 {id:'xp10',title:'+10 XP',icon:'✨',type:'xp',value:10},
 {id:'xp25',title:'+25 XP',icon:'💗',type:'xp',value:25},
 {id:'xp50',title:'+50 XP',icon:'🌸',type:'xp',value:50},
 {id:'xp100',title:'+100 XP',icon:'👑',type:'xp',value:100},
 {id:'xp150',title:'+150 XP',icon:'💎',type:'xp',value:150},
 {id:'feed',title:'Покормить питомца',icon:'🍓',type:'feed'},
 {id:'play',title:'Поиграть с питомцем',icon:'🎀',type:'play'},
 {id:'bond',title:'+5 привязанности',icon:'🤍',type:'bond',value:5},
 {id:'rare',title:'Редкий предмет',icon:'🎁',type:'rare'},
 {id:'nothing',title:'Ничего… но красиво ♡',icon:'🌙',type:'nothing'}
];
const PET_10_STAGES=[
 {n:1,label:'Крошка',need:0}, {n:2,label:'Малыш',need:20}, {n:3,label:'Исследователь',need:50}, {n:4,label:'Любимчик',need:90},
 {n:5,label:'Красавчик',need:140}, {n:6,label:'Глоу-друг',need:200}, {n:7,label:'Страж красоты',need:280}, {n:8,label:'Сияющий друг',need:380},
 {n:9,label:'Редкий хранитель',need:500}, {n:10,label:'Король / Королева ухода',need:700}
];
const PET_EMOJIS={
 'котёнок':['🥚','🐱','😺','😸','😽','😻','😼','🙀','🐯','👑'],
 'щенок':['🥚','🐶','🐕','🐩','🦮','🐕‍🦺','🐺','✨🐶','🌟🐕','👑🐶'],
 'кролик':['🥚','🐇','🐰','🐰','🥕🐰','🎀🐰','🌸🐰','✨🐰','👑🐰','👑✨'],
 'цветок':['🌱','🌿','🌷','🌹','🌺','🪻','🌸','💐','✨🌸','🌳✨']
};
const BIG_SHOP_ITEMS=[
 {id:'pet-sleepy',type:'petRoom',title:'Комната сна',icon:'🛏️',cost:260,rarity:'Обычный',desc:'Уютное место для отдыха питомца.'},
 {id:'pet-pinkroom',type:'petRoom',title:'Розовая комната',icon:'🎀',cost:520,rarity:'Редкий',desc:'Комната в стиле soft pink.'},
 {id:'pet-lilacroom',type:'petRoom',title:'Лавандовая комната',icon:'🪻',cost:620,rarity:'Редкий',desc:'Мягкая лавандовая атмосфера.'},
 {id:'pet-gardenroom',type:'petRoom',title:'Комната-сад',icon:'🌷',cost:780,rarity:'Эпический',desc:'Маленький домашний сад для питомца.'},
 {id:'pet-sparkbg',type:'petBg',title:'Фон «Искры»',icon:'✨',cost:340,rarity:'Обычный',desc:'Сияющий фон вокруг питомца.'},
 {id:'pet-nightbg',type:'petBg',title:'Фон «Ночная рутина»',icon:'🌙',cost:460,rarity:'Редкий',desc:'Тихий ночной фон.'},
 {id:'pet-cloudbg',type:'petBg',title:'Фон «Облака»',icon:'☁️',cost:540,rarity:'Редкий',desc:'Воздушный фон.'},
 {id:'pet-rainbowbg',type:'petBg',title:'Фон «Радуга»',icon:'🌈',cost:760,rarity:'Эпический',desc:'Яркий фон для особых дней.'},
 {id:'pet-toyball',type:'petToy',title:'Игрушка-мячик',icon:'🧶',cost:120,rarity:'Обычный',desc:'Добавляет питомцу настроение.'},
 {id:'pet-toycrown',type:'petToy',title:'Музыкальная шкатулка',icon:'🎵',cost:380,rarity:'Редкий',desc:'Небольшой бонус к счастью.'},
 {id:'theme-mint',type:'theme',title:'Мятное облако',icon:'🌿',cost:450,rarity:'Редкий',desc:'Свежая мятная тема.',vars:{'--bg':'#f6fffb','--surface':'#ffffff','--surface2':'#e9faf2','--text':'#31443d','--muted':'#7e9890','--primary':'#79c7a6','--primary2':'#c0ead7','--accent':'#9db7eb'}},
 {id:'theme-midnight',type:'theme',title:'Полуночный бархат',icon:'🌌',cost:900,rarity:'Легендарный',desc:'Тёмная тема для вечернего ухода.',vars:{'--bg':'#17151d','--surface':'#211e29','--surface2':'#2e2838','--text':'#f8eef5','--muted':'#b6a9b7','--primary':'#db8ab2','--primary2':'#8d6ca8','--accent':'#8fc8c5'}},
 {id:'frame-glass',type:'frame',title:'Рамка «Стекло»',icon:'🫧',cost:300,rarity:'Редкий',desc:'Прозрачная рамка для карточек.'},
 {id:'badge-sun',type:'badge',title:'Значок «Солнышко»',icon:'☀️',cost:240,rarity:'Обычный',desc:'Для ежедневной дисциплины.'},
 {id:'badge-moon',type:'badge',title:'Значок «Ночная фея»',icon:'🌙',cost:360,rarity:'Редкий',desc:'Для любительниц вечерних ритуалов.'}
];
for(const item of BIG_SHOP_ITEMS){if(typeof SHOP_CATALOG!=='undefined'&&!SHOP_CATALOG.some(x=>x.id===item.id))SHOP_CATALOG.push(item)}

// Fantasy avatar frames: these are shop items and are intentionally not themes.
const FANTASY_AVATAR_FRAMES=[
{id:'frame-vampire',type:'frame',title:'🩸 Vampire Collection',icon:'🕷️',cost:700,rarity:'Эпический',desc:'🕷️🕸️🍷⚰️🎀 Тёмная вампирская рамка для аватара.',collection:'Vampire',shopAvatarFrame:true,frameId:'vampire'},
{id:'frame-fairy',type:'frame',title:'🧚 Fairy Garden',icon:'🧚‍♀️',cost:650,rarity:'Эпический',desc:'🧚🧚‍♀️🧚‍♂️🌿🍃🌱 Волшебная лесная рамка.',collection:'Fairy',shopAvatarFrame:true,frameId:'fairy'},
{id:'frame-goblincore',type:'frame',title:'🧝🏻‍♀️ Goblincore',icon:'🍄‍🟫',cost:800,rarity:'Легендарный',desc:'🧝🏻‍♀️🧴🍄🍄‍🟫🍃💚🍸🧉 Максимально лесная goblincore-эстетика.',collection:'Goblincore',shopAvatarFrame:true,frameId:'goblincore'},
{id:'frame-zombie',type:'frame',title:'🧟‍♀️ Zombie Beauty',icon:'🧟‍♀️',cost:720,rarity:'Эпический',desc:'🧟‍♀️ Мрачная зомби-рамка.',collection:'Zombie',shopAvatarFrame:true,frameId:'zombie'},
{id:'frame-mermaid',type:'frame',title:'🧜🏻‍♀️ Mermaid Lagoon',icon:'🧜🏻‍♀️',cost:760,rarity:'Эпический',desc:'🧜🏻‍♀️🌊🐚🫧 Морская рамка с русалкой.',collection:'Mermaid',shopAvatarFrame:true,frameId:'mermaid'},
{id:'frame-angel',type:'frame',title:'🪽 Angel Aura',icon:'🪽',cost:850,rarity:'Легендарный',desc:'🪽✨🤍 Небесная ангельская рамка.',collection:'Angel',shopAvatarFrame:true,frameId:'angel'},
{id:'frame-witch',type:'frame',title:'🧙‍♀️ Witchy Beauty',icon:'🔮',cost:780,rarity:'Эпический',desc:'🧙‍♀️🔮🌙 Магическая ведьминская рамка.',collection:'Witch',shopAvatarFrame:true,frameId:'witch'},
{id:'frame-mushroom',type:'frame',title:'🍄 Mushroom Apothecary',icon:'🍄',cost:620,rarity:'Редкий',desc:'🍄🍃🌿 Грибная лесная рамка.',collection:'Mushroom',shopAvatarFrame:true,frameId:'mushroom'}
];
for(const item of FANTASY_AVATAR_FRAMES){if(!SHOP_CATALOG.some(x=>x.id===item.id))SHOP_CATALOG.push(item)}


const BIG_TIP_TOPICS={
 skin:{normal:'уход за нормальной кожей',dry:'уход за сухой кожей',oily:'уход за жирной кожей',combination:'уход за комбинированной кожей',sensitive:'уход за чувствительной кожей'},
 hair:{normal:'уход за нормальными волосами',dry:'уход за сухими волосами',oily:'уход за жирными волосами',damaged:'уход за повреждёнными волосами',colored:'уход за окрашенными волосами'}
};
const BIG_LOCAL_TIPS={
 normal:['Сохраняй умеренную рутину: база важнее количества баночек.','Новые средства лучше вводить по одному, чтобы было понятнее, что именно тебе подошло.','Даже нормальной коже нужен лёгкий увлажняющий крем утром и вечером — это профилактика, а не роскошь.','Раз в неделю можно устроить более внимательный уход: мягкий пилинг или маска для поддержания тонуса.','Не гонись за трендовыми ингредиентами — если рутина работает, необязательно её усложнять.','SPF по утрам — привычка, которая окупается годами позже, даже если кожа сейчас выглядит идеально.','Следи за реакцией кожи на смену сезона: то, что подходило зимой, не всегда комфортно летом.','Питьевой режим и сон влияют на вид кожи не меньше, чем баночки на полке.','Если кожа выглядит уставшей, для начала попробуй упростить рутину, а не добавлять новые шаги.','Раз в месяц устраивай ревизию косметички — просроченные и неиспользуемые средства только мешают.'],
 dry:['После умывания не затягивай с увлажнением: комфорт кожи важнее сложной схемы.','В сухую погоду особенно приятны мягкое очищение и более комфортный защитный слой.','Выбирай очищающие средства без спирта и агрессивных ПАВ — сухой коже комфортнее с мягкой пенкой или гелем.','Сыворотка с гиалуроновой кислотой работает лучше, если наносить её на слегка влажную кожу.','Более плотный крем на ночь помогает коже чувствовать себя комфортнее, пока ты спишь.','Если кожа шелушится, попробуй временно сократить количество активных кислот в рутине.','Увлажняющая маска пару раз в неделю — приятный способ дать коже дополнительный комфорт.','В отопительный сезон обрати внимание на увлажнитель воздуха в комнате — это тоже часть ухода.','После душа наноси крем на слегка влажную кожу — так ощущение увлажнённости обычно держится дольше.','Не забывай про губы и зону вокруг глаз — там сухость обычно чувствуется в первую очередь.'],
 oily:['Не пытайся пересушить кожу ради ощущения «скрипа» — мягкая база обычно комфортнее.','Лёгкий крем всё равно может быть полезен даже при жирности.','Двойное очищение вечером помогает справиться с себумом, но не переусердствуй с ним по утрам.','Матирующие салфетки в течение дня — более бережный вариант, чем частое умывание.','Гелевые и лёгкие текстуры обычно комфортнее плотных кремов для жирной кожи.','Ниацинамид в составе — популярный компонент для контроля блеска, но вводи его постепенно.','Не пропускай увлажнение — обезвоженная кожа иногда выглядит ещё более блестящей.','Глиняная маска раз в неделю помогает освежить вид кожи, не пересушивая её сильно.','Меняй наволочку почаще — на жирной коже это заметнее влияет на комфорт.','Солнцезащита с лёгкой текстурой без «плёнки» — то, что стоит поискать в первую очередь.'],
 combination:['Уход можно делать зонально: балансируй комфорт сухих участков и Т-зоны.','Необязательно использовать одно и то же количество продукта на всё лицо.','В Т-зоне можно использовать более лёгкую текстуру, а на щеках — чуть более питательную.','Матирующая пудра точечно на Т-зону — простой способ продержаться до вечера.','Если разные зоны ведут себя по-разному в течение года, рутину стоит менять по сезону.','Тоник без спирта помогает мягко выровнять состояние кожи после умывания.','Необязательно искать «идеальный» универсальный крем — можно комбинировать два средства.','Следи, не пересушивает ли зимой отопление именно сухие участки лица.','Лёгкая эксфолиация раз в неделю помогает выровнять текстуру в разных зонах.','Дай коже пару недель на адаптацию, прежде чем менять баланс ухода.'],
 sensitive:['Чем спокойнее рутина, тем проще отслеживать реакцию кожи.','При раздражении полезно сократить количество новых активных средств и вернуть базовый уход.','Перед новым средством стоит протестировать его на небольшом участке кожи.','Ароматизированная косметика чаще вызывает дискомфорт — обрати внимание на состав без отдушек.','Вводи одно новое средство за раз и жди хотя бы неделю, прежде чем добавлять следующее.','Мягкое умывание прохладной, а не горячей водой обычно комфортнее для чувствительной кожи.','Веди заметки о том, что вызывает покраснение — так проще находить закономерности.','Плотная текстура крема не всегда означает лучшую защиту — иногда более лёгкое средство работает мягче.','После пилингов и активных процедур дай коже пару дней на восстановление без экспериментов.','Хлопковая наволочка и бережное промакивание полотенцем — маленькие привычки, которые тоже важны.']
};
const BIG_HAIR_TIPS={
 normal:['Регулярный кондиционер и бережное расчёсывание помогают сохранять длину ухоженной.','Раз в 2-3 месяца обновляй кончики — так проще держать длину в форме.','Расчёсывайся щёткой с мягкими зубчиками, начиная с кончиков и постепенно поднимаясь выше.','Термозащита перед укладкой — привычка, которая бережёт волосы даже при нечастом использовании фена.','Маска раз в неделю — приятный способ поддержать блеск и мягкость длины.','Расчёсывай волосы перед мытьём — так проще потом распутать их после кондиционера.','Смена шампуня по сезону — нормальная практика, если волосы ведут себя по-разному летом и зимой.','Сушка на среднем режиме фена бережнее для структуры волос, чем на максимальной температуре.'],
 dry:['Для сухой длины важны кондиционирование, мягкая сушка и разумная теплозащита.','Питательное масло на кончики после мытья помогает уменьшить ощущение сухости.','Реже мой голову горячей водой — тёплая или прохладная вода бережнее для сухих волос.','Несмываемый уход перед укладкой облегчает расчёсывание и снижает ломкость.','Глубокая питательная маска раз в неделю — хорошая привычка для сухой длины.','Старайся сушить волосы естественным путём чаще, чем феном на горячем режиме.','Расчёсывай сухие волосы аккуратно, лучше расчёской с редкими зубьями.','Шампуни без сульфатов обычно мягче относятся к сухой и склонной к ломкости длине.'],
 oily:['Частоту мытья лучше подбирать по комфорту кожи головы, а не по жёсткому расписанию.','Кондиционер лучше наносить только на длину, не затрагивая корни.','Сухой шампунь на корни между мытьями помогает продлить ощущение свежести укладки.','Слишком частое расчёсывание может дополнительно распределять себум по длине.','Лёгкие текстуры стайлинга не утяжеляют корни так, как плотные кремы и масла.','Прохладная вода при последнем ополаскивании помогает волосам выглядеть чуть свежее дольше.','Массаж кожи головы при мытье лучше делать бережно — интенсивное трение может усиливать выработку себума.','Смена наволочки раз в несколько дней помогает дольше сохранять ощущение чистых корней.'],
 damaged:['Снизь лишнее тепло и добавь защиту длины перед горячими инструментами.','Реже используй утюжок и плойку, пока структура волос восстанавливается.','Восстанавливающая маска с кератином или протеинами — то, на что стоит обратить внимание.','Подрезай секущиеся кончики регулярно, чтобы повреждение не поднималось выше по длине.','Расчёсывай повреждённые волосы особенно бережно, начиная снизу вверх небольшими прядями.','Несмываемый уход перед сном помогает уменьшить трение о подушку ночью.','Ограничь агрессивные окрашивания и осветления, пока волосы восстанавливаются.','Более прохладная сушка феном бережнее относится к и без того ослабленной структуре.'],
 colored:['Для окрашенных волос особенно приятны мягкие шампуни и защита от частого перегрева.','Шампунь для окрашенных волос без сульфатов помогает дольше сохранять яркость цвета.','Прохладная вода при мытье головы бережнее закрывает кутикулу и меньше вымывает пигмент.','Термозащита перед укладкой особенно важна для окрашенной длины.','UV-фильтр в уходе помогает защитить цвет от выгорания на солнце.','Тонирующий уход раз в несколько недель освежает оттенок между окрашиваниями.','Реже мой голову в первые дни после окрашивания — так цвет обычно закрепляется лучше.','Маска для окрашенных волос обычно мягче по составу и не вымывает пигмент так, как обычная.']
};
function todayNum(){const d=new Date();return Math.floor((d-new Date(d.getFullYear(),0,0))/86400000)}
function ensureBigData(){data.pet=data.pet||{};data.pet.kind='котёнок';
 ensureProData();
 data.pet.stage=Math.max(1,Math.min(10,Number(data.pet.stage)||1));
 data.pet.points=Number(data.pet.points)||0;
 data.pet.affection=Number(data.pet.affection)||0;
 data.pet.hunger=clamp(Number(data.pet.hunger)||0); data.pet.happiness=clamp(Number(data.pet.happiness)||0); data.pet.energy=clamp(Number(data.pet.energy)||0);
 data.pet.feedCount=Number(data.pet.feedCount)||0;data.pet.playCount=Number(data.pet.playCount)||0;data.pet.bond=Number(data.pet.bond)||0;
 data.pet.room=data.pet.room||'default';data.pet.bg=data.pet.bg||'default';data.pet.toy=data.pet.toy||'';
 data.luck=data.luck&&typeof data.luck==='object'?data.luck:{lastSpin:'',spinCount:0,totalWins:0};
 data.sound=data.sound&&typeof data.sound==='object'?data.sound:{enabled:true,volume:.16}; data.music=data.music&&typeof data.music==='object'?data.music:{enabled:false};
 data.webArticles=Array.isArray(data.webArticles)?data.webArticles:[]; data.webArticlesDate=data.webArticlesDate||'';data.webArticlesQuery=data.webArticlesQuery||'';
 data.tipChoice=data.tipChoice&&typeof data.tipChoice==='object'?data.tipChoice:{skin:data.settings.skinType||'normal',hair:data.settings.hairType||'normal',focus:'all'};
 data.articleReads=data.articleReads&&typeof data.articleReads==='object'?data.articleReads:{};
 const known=new Set(data.challenges.map(c=>c.id));
 for(const c of BIG_CHALLENGES)if(!known.has(c.id))data.challenges.push(structuredCloneSafe(c));
 data.shop.owned=Array.isArray(data.shop.owned)?data.shop.owned:[];data.shop.equipped=data.shop.equipped||{};
 data.xp=Math.max(0,Math.floor(Number(data.xp)||0));data.level=levelInfo().lv;
}
normalize=function(){baseNormalize();ensureBigData()};

function petStageLabel(){const s=PET_10_STAGES[Math.max(1,Math.min(10,Number(data.pet.stage)||1))-1];return s.label}
function petStageNeed(){const s=Math.max(1,Math.min(10,Number(data.pet.stage)||1));return s>=10?700:PET_10_STAGES[s].need}
function checkPetEvolution(){let stage=1;for(const s of PET_10_STAGES)if(data.pet.points>=s.need)stage=s.n;data.pet.stage=stage}
function petEmoji(){const arr=['🐱','😺','😸','😽','😻','😺','😸','😻','😼','🐱'];return arr[Math.max(0,Math.min(9,Number(data.pet.stage||1)-1))]}
function petFeed(){ensureBigData();playSound('click');if(data.pet.hunger>=96){toast('Питомец уже сытый 🥹');return}data.pet.hunger=Math.min(100,data.pet.hunger+22);data.pet.happiness=Math.min(100,data.pet.happiness+6);data.pet.energy=Math.min(100,data.pet.energy+3);data.pet.feedCount++;data.pet.affection=Math.min(100,data.pet.affection+2);data.pet.bond+=1;data.pet.points+=9;checkPetEvolution();addXP(3,'Забота о питомце');save();checkAchievements();toast('Питомец довольно мурлычет ♡');render()}
function petPlay(){ensureBigData();playSound('click');if(data.pet.energy<15){toast('Питомец устал — дай ему отдохнуть ♡');return}data.pet.happiness=Math.min(100,data.pet.happiness+16);data.pet.hunger=Math.max(0,data.pet.hunger-5);data.pet.energy=Math.max(0,data.pet.energy-15);data.pet.playCount++;data.pet.affection=Math.min(100,data.pet.affection+3);data.pet.bond+=1;data.pet.points+=12;checkPetEvolution();addXP(5,'Игра с питомцем');save();checkAchievements();toast('Питомец счастлив и просит ещё игры 🎀');render()}
function petRest(){ensureBigData();data.pet.energy=Math.min(100,data.pet.energy+28);data.pet.happiness=Math.min(100,data.pet.happiness+5);data.pet.hunger=Math.max(0,data.pet.hunger-2);data.pet.points+=5;checkPetEvolution();save();playSound('win');toast('Питомец уютно отдохнул 🌙');render()}
function petFeedFromWheel(){ensureBigData();data.pet.hunger=Math.min(100,data.pet.hunger+15);data.pet.happiness=Math.min(100,data.pet.happiness+3);data.pet.points+=5;data.pet.feedCount++;checkPetEvolution()}
function petPlayFromWheel(){ensureBigData();data.pet.happiness=Math.min(100,data.pet.happiness+12);data.pet.energy=Math.max(0,data.pet.energy-8);data.pet.points+=6;data.pet.playCount++;checkPetEvolution()}

function startAmbient(){try{ensureBigData();if(window.__beautyMusic)return;const AC=window.AudioContext||window.webkitAudioContext;if(!AC)return;const ctx=window.__beautyAudio||new AC();window.__beautyAudio=ctx;const master=ctx.createGain();master.gain.value=.018;master.connect(ctx.destination);const notes=[261.63,329.63,392.00,523.25];const os=notes.map((f,i)=>{const o=ctx.createOscillator();o.type='sine';o.frequency.value=f;const g=ctx.createGain();g.gain.value=.0001;o.connect(g);g.connect(master);g.gain.setValueAtTime(.0001,ctx.currentTime);g.gain.linearRampToValueAtTime(.012,ctx.currentTime+1.4+i*.15);o.start();return{o,g}});window.__beautyMusic={ctx,master,os};if(ctx.state==='suspended')ctx.resume()}catch{}}
function stopAmbient(){try{if(!window.__beautyMusic)return;const m=window.__beautyMusic;for(const x of m.os)x.g.stop(m.ctx.currentTime+.2);m.master.gain.exponentialRampToValueAtTime(.0001,m.ctx.currentTime+.2);setTimeout(()=>{try{m.os.forEach(x=>x.o.stop())}catch{}},350);window.__beautyMusic=null}catch{}}

function playSound(kind='click'){try{ensureBigData();if(!data.sound.enabled)return;const AC=window.AudioContext||window.webkitAudioContext;if(!AC)return;const ctx=window.__beautyAudio||new AC();window.__beautyAudio=ctx;if(ctx.state==='suspended')ctx.resume();const o=ctx.createOscillator(),g=ctx.createGain();const now=ctx.currentTime;const map={click:[520,.06,.045],win:[740,.18,.07],wheel:[260,.08,.035],soft:[390,.12,.03]};const [freq,dur,vol]=map[kind]||map.click;o.type='sine';o.frequency.setValueAtTime(freq,now);o.frequency.exponentialRampToValueAtTime(freq*1.4,now+dur);g.gain.setValueAtTime(0,now);g.gain.linearRampToValueAtTime(vol*(data.sound.volume||.16)/.16,now+.01);g.gain.exponentialRampToValueAtTime(.0001,now+dur);o.connect(g);g.connect(ctx.destination);o.start(now);o.stop(now+dur+.02)}catch{}}

function glowScore(){
 ensureBigData();
 const care=Math.min(100,(totalCompleted()/Math.max(1,Object.keys(data.routines).length*3))*100);
 const consistency=Math.min(100,(currentStreak()/30)*100);
 const rated=data.photos.filter(p=>Number(p.overall||p.score||0)>0); const state=rated.length?Math.min(100,(rated.reduce((s,p)=>s+Number(p.overall||p.score||0),0)/rated.length)*10):50;
 const photos=Math.min(100,(data.photos.length/20)*100);
 const goals=data.goals.length?Math.min(100,data.goals.reduce((s,g)=>s+Number(g.progress||0),0)/data.goals.length):50;
 return Math.round(care*.28+consistency*.18+state*.18+photos*.12+Math.min(100,(bestStreak()/60)*100)*.12+goals*.12);
}
function glowDelta(){const today=glowScore();return Math.max(-30,Math.min(30,Math.round((today-50)*.55)))}

const SKIN_ARTICLES={
 normal:[{title:'Базовый уход за нормальной кожей',url:'https://www.cosmo.ru/beauty/',source:'Cosmopolitan',snippet:'Разбор того, как не перегружать нормальную кожу количеством продуктов и держать рутину простой.'},{title:'Что достаточно для нормальной кожи',url:'https://www.elle.ru/krasota/',source:'ELLE',snippet:'Материалы о базовой рутине и о том, когда стоит её усложнять.'}],
 dry:[{title:'Уход за сухой кожей',url:'https://www.beautyinsider.ru/',source:'Beauty Insider',snippet:'Отзывы и разборы увлажняющих средств для сухой и обезвоженной кожи.'},{title:'Как избежать шелушений',url:'https://www.cosmo.ru/beauty/',source:'Cosmopolitan',snippet:'Советы по выбору более плотных текстур и защите барьера при сухости кожи.'}],
 oily:[{title:'Уход за жирной кожей',url:'https://www.elle.ru/krasota/beauty_blog/',source:'ELLE',snippet:'Разбор мифа о том, что жирной коже не нужен крем, и как выбрать лёгкую текстуру.'},{title:'Матирующий уход без пересушивания',url:'https://www.beautyinsider.ru/',source:'Beauty Insider',snippet:'Обзоры средств для контроля блеска без агрессивного обезвоживания кожи.'}],
 combination:[{title:'Зональный уход за комбинированной кожей',url:'https://www.cosmo.ru/beauty/',source:'Cosmopolitan',snippet:'Как ухаживать за Т-зоной и сухими участками разными средствами.'},{title:'Комбинированная кожа: базовые правила',url:'https://www.elle.ru/krasota/',source:'ELLE',snippet:'Материалы о балансе увлажнения и контроля жирности в одной рутине.'}],
 sensitive:[{title:'Уход за чувствительной кожей',url:'https://www.beautyinsider.ru/',source:'Beauty Insider',snippet:'Разборы гипоаллергенных средств и того, как вводить новые продукты постепенно.'},{title:'Как успокоить раздражённую кожу',url:'https://www.cosmo.ru/beauty/',source:'Cosmopolitan',snippet:'Советы по упрощению рутины при покраснениях и повышенной чувствительности.'}]
};
const HAIR_ARTICLES={
 normal:[{title:'Уход за нормальными волосами',url:'https://www.cosmo.ru/beauty/hair/',source:'Cosmopolitan',snippet:'Базовые советы по мытью, кондиционированию и бережной укладке.'},{title:'Поддерживаем волосы в форме',url:'https://www.elle.ru/krasota/beauty_blog/',source:'ELLE',snippet:'Материалы о регулярном уходе, который сохраняет естественный блеск волос.'}],
 dry:[{title:'Увлажнение сухих волос',url:'https://www.beautyinsider.ru/',source:'Beauty Insider',snippet:'Обзоры масел и масок для восстановления сухой и ломкой длины.'},{title:'Как вернуть волосам мягкость',url:'https://www.cosmo.ru/beauty/hair/',source:'Cosmopolitan',snippet:'Советы по выбору более питательного кондиционера и щадящей сушке.'}],
 oily:[{title:'Уход за жирными волосами',url:'https://www.elle.ru/krasota/',source:'ELLE',snippet:'Разбор того, как часто мыть голову и какие текстуры не утяжеляют корни.'},{title:'Свежесть корней надолго',url:'https://www.beautyinsider.ru/',source:'Beauty Insider',snippet:'Обзоры лёгких и сухих шампуней для жирной кожи головы.'}],
 damaged:[{title:'Восстановление повреждённых волос',url:'https://www.cosmo.ru/beauty/hair/',source:'Cosmopolitan',snippet:'Советы по снижению механического повреждения и уходу за секущимися кончиками.'},{title:'Ремонт структуры волос',url:'https://www.elle.ru/krasota/beauty_blog/',source:'ELLE',snippet:'Материалы о восстанавливающих масках и щадящей укладке.'}],
 colored:[{title:'Уход за окрашенными волосами',url:'https://www.beautyinsider.ru/',source:'Beauty Insider',snippet:'Обзоры средств для сохранения цвета и блеска окрашенной длины.'},{title:'Как продлить стойкость окрашивания',url:'https://www.cosmo.ru/beauty/hair/',source:'Cosmopolitan',snippet:'Советы по бережному мытью и защите цвета от вымывания.'}]
};
function daysSinceKey(dateStr){if(!dateStr)return Infinity;const d0=new Date(dateStr+'T00:00:00');const d1=new Date(todayKey()+'T00:00:00');return Math.round((d1-d0)/86400000)}
async function fetchWebArticles(force=false){
 ensureBigData();
 const skin=data.tipChoice.skin||data.settings.skinType||'normal', hair=data.tipChoice.hair||data.settings.hairType||'normal', focus=data.tipChoice.focus||'all';
 const qKey=focus+':'+skin+':'+hair;
 const today=todayKey(); if(!force && data.webArticlesQuery===qKey && data.webArticles.length && daysSinceKey(data.webArticlesDate)<1)return true;
 const pool=focus==='skin'?(SKIN_ARTICLES[skin]||SKIN_ARTICLES.normal):focus==='hair'?(HAIR_ARTICLES[hair]||HAIR_ARTICLES.normal):[...(SKIN_ARTICLES[skin]||SKIN_ARTICLES.normal),...(HAIR_ARTICLES[hair]||HAIR_ARTICLES.normal)];
 data.webArticles=pool.slice(0,8).map((x,i)=>({id:qKey+'-'+i,title:x.title,snippet:x.snippet,url:x.url,source:x.source,rank:i+1}));
 data.webArticlesDate=today;data.webArticlesQuery=qKey;data.articleSource='Подборка редакции';save();return true;
}
function dynamicTip(){
  const skin=data.tipChoice.skin||data.settings.skinType||'normal';
  const hair=data.tipChoice.hair||data.settings.hairType||'normal';
  const focus=data.tipChoice.focus||'all';
  const weather=data.settings.weather||{};
  const local=[...(BIG_LOCAL_TIPS[skin]||BIG_LOCAL_TIPS.normal),...(BIG_HAIR_TIPS[hair]||BIG_HAIR_TIPS.normal)];
  const web=data.webArticles||[];
  const day=todayNum();

  // На главной показываем именно действие для пользователя, а не заголовок статьи.
  // Совет меняется раз в сутки и циклически проходит по персональной базе.
  const base=local.length?local[day%local.length]:'Сделай сегодня один спокойный и регулярный шаг своего ухода.';
  let prefix='';
  const temp=Number(weather.temp), humidity=Number(weather.humidity), wind=Number(weather.wind), uv=Number(weather.uv);
  if(Number.isFinite(temp)&&temp>=27) prefix='Сегодня из-за жары выбери лёгкие текстуры и не перегружай кожу или волосы. ';
  else if(Number.isFinite(humidity)&&humidity>=75) prefix='При высокой влажности сегодня лучше не перегружать волосы стайлингом и тяжёлыми маслами. ';
  else if(Number.isFinite(wind)&&wind>=25) prefix='Из-за ветра сегодня особенно бережно относись к длине волос и избегай лишнего трения. ';
  else if(Number.isFinite(uv)&&uv>=6) prefix='Сегодня при высоком UV не забывай про SPF и защиту открытых участков. ';
  else if(Number.isFinite(temp)&&temp<=0) prefix='Сегодня из-за мороза не забудь про плотный защитный крем и бальзам для губ перед выходом. ';
  else if(Number.isFinite(humidity)&&humidity<=30) prefix='Сегодня воздух особенно сухой — усиль увлажнение кожи и добавь уход для длины волос. ';
  else if(String(weather.description||'').toLowerCase().includes('дожд')) prefix='Сегодня возможен дождь — защити волосы от промокания и не планируй сложную укладку. ';
  else if(Number.isFinite(wind)&&wind<10&&Number.isFinite(uv)&&uv<3) prefix='Сегодня спокойная погода — хороший день, чтобы просто понаблюдать за состоянием кожи без лишних экспериментов. ';

  const source=web.length?web[day%web.length]:null;
  const sourceText=source?` Если захочешь углубиться, материал «${source.title}» связан с твоим профилем.`:'';
  return `${prefix}${base}${sourceText}`.trim();
}
function makePrizePng(emoji){try{const c=document.createElement('canvas');c.width=96;c.height=96;const ctx=c.getContext('2d');ctx.fillStyle='#fff7fb';ctx.beginPath();ctx.arc(48,48,42,0,Math.PI*2);ctx.fill();ctx.font='48px system-ui';ctx.textAlign='center';ctx.textBaseline='middle';ctx.fillText(emoji,48,50);return c.toDataURL('image/png')}catch{return ''}}
function luckPage(){
 ensureBigData();
 const used=data.luck.lastSpin===todayKey();
 const wheel=LUCK_PRIZES.map((p,i)=>`<div class="wheel-label" style="--i:${i}"><img src="${makePrizePng(p.icon)}" alt=""><span>${esc(p.title)}</span></div>`).join('');
 return `<section class="card hero"><div class="row between wrap"><div><div class="label">Ежедневный бонус</div><h1 style="font-family:Georgia,serif;margin:4px 0">🎡 Колесо фортуны</h1><p>${used?'Сегодня ты уже крутила колесо. Возвращайся завтра ♡':'Один шанс в день — крути и забирай случайный приз.'}</p></div><span class="tag">${used?'✓ Уже использовано':'♡ 1 вращение сегодня'}</span></div></section>
 <div class="grid grid-2" style="margin-top:16px"><section class="card luck-card"><div class="wheel-wrap"><div class="wheel-pointer">▼</div><div id="luckWheel" class="luck-wheel">${wheel}<div class="wheel-center">♡<small>УДАЧА</small></div></div></div><button class="btn" id="spinWheel" ${used?'disabled':''}>${used?'Завтра снова ♡':'Крутить колесо ✨'}</button><p class="subtle" style="margin-top:10px">Колесо ограничено одним вращением в сутки.</p></section><section class="card"><h3 class="section-title">🎁 Что можно выиграть</h3><div class="list">${LUCK_PRIZES.map((p,i)=>`<div class="item row"><img class="prize-png" src="${makePrizePng(p.icon)}" alt=""><div><strong>${esc(p.title)}</strong><div class="subtle">Шанс сектора ${i+1}/10</div></div></div>`).join('')}</div></section></div>`
}
function spinWheel(){ensureBigData();if(data.luck.lastSpin===todayKey()){toast('Колесо уже кручено сегодня ♡');return}playSound('wheel');const el=document.getElementById('luckWheel');if(!el)return;const idx=Math.floor(Math.random()*LUCK_PRIZES.length);const deg=360*8 + idx*(360/LUCK_PRIZES.length);el.style.transform=`rotate(${deg}deg)`;const btn=document.getElementById('spinWheel');if(btn)btn.disabled=true;setTimeout(()=>{const prize=LUCK_PRIZES[idx];data.luck.lastSpin=todayKey();data.luck.spinCount++;data.luck.totalWins++;if(prize.type==='xp')addXP(prize.value,'Колесо фортуны');else if(prize.type==='feed')petFeedFromWheel();else if(prize.type==='play')petPlayFromWheel();else if(prize.type==='bond'){data.pet.affection=Math.min(100,data.pet.affection+5);data.pet.bond+=5;data.pet.points+=8;checkPetEvolution()}else if(prize.type==='rare'){const owned=new Set(data.shop.owned);const options=SHOP_CATALOG.filter(x=>x.rarity==='Редкий'&&!owned.has(x.id));if(options.length){const item=options[Math.floor(Math.random()*options.length)];data.shop.owned.push(item.id);toast(`Редкая находка: ${item.title} ${item.icon}`)}else addXP(75,'Вместо редкого предмета')}refreshChallenges();checkAchievements();save();playSound(prize.type==='nothing'?'soft':'win');toast(`Колесо остановилось: ${prize.title} ${prize.icon}`);render()},3900)}

function challengesPage(){ensureBigData();const active=data.challenges.filter(c=>!c.done),done=data.challenges.filter(c=>c.done);return `<section class="card hero"><div class="row between wrap"><div><div class="label">Выбирай, что тебе нравится</div><h1 style="font-family:Georgia,serif;margin:4px 0">🏆 Челленджи</h1><p>Готовые челленджи уже здесь — можно просто выбрать и начать.</p></div><span class="tag">${done.length}/${data.challenges.length} выполнено</span></div></section><div class="chip-tabs" style="margin:14px 0"><button class="active" data-ch-filter="all">Все</button><button data-ch-filter="skin">Кожа</button><button data-ch-filter="hair">Волосы</button><button data-ch-filter="habit">Привычки</button><button data-ch-filter="pet">Питомец</button></div><div class="grid grid-2">${active.map(challengeCardFull).join('')}</div><section class="card" style="margin-top:16px"><div class="row between"><h3 class="section-title">✨ Выполненные</h3><button class="btn secondary small" data-add-challenge>+ Свой челлендж</button></div><div class="grid grid-2">${done.map(challengeCardFull).join('')||'<div class="empty">Пока нет завершённых. Самая первая победа уже близко ♡</div>'}</div></section>`}
function refreshBigChallenges(){ensureBigData();const careDays=Object.keys(data.logs).filter(k=>dayStats(k).done.length>0).length;for(const c of data.challenges){if(c.done)continue;let p=c.progress||0;switch(c.type){case'auto-streak':p=bestStreak();break;case'auto-photos':p=data.photos.length;break;case'auto-care-days':p=careDays;break;case'auto-evening':p=Object.keys(data.logs).filter(k=>{const rs=entriesForDay(k).filter(r=>r.slot==='evening');return rs.length>0&&rs.every(r=>isDone(k,r.id))}).length;break;case'auto-morning':p=Object.keys(data.logs).filter(k=>{const rs=entriesForDay(k).filter(r=>r.slot==='morning');return rs.length>0&&rs.every(r=>isDone(k,r.id))}).length;break;case'auto-spf':p=Object.entries(data.logs).flatMap(([k,arr])=>(arr||[]).filter(x=>x.done).map(x=>data.routines.find(r=>r.id===x.id))).filter(r=>r&&String(r.title||'').toLowerCase().includes('spf')).length;break;case'auto-total':p=totalCompleted();break;case'auto-skin':p=completedByCat('skin');break;case'auto-hair':p=completedByCat('hair');break;case'auto-pet-points':p=data.pet.points;break;case'auto-shop':p=data.shop.owned.length;break;case'auto-rated':p=Object.values(data.productRatings||{}).filter(x=>x.score>0).length;break;case'auto-favorites':p=data.favoriteProducts.length;break;case'auto-articles':p=Object.keys(data.articleReads||{}).length;break;case'auto-weather':p=Number(data.weatherChecks||0);break;case'auto-wheel':p=Number(data.luck?.spinCount||0);break;}c.progress=Math.min(c.goal,p);if(c.progress>=c.goal&&!c.done){c.done=true;addXP(c.reward||0,`Челлендж «${c.title}»`);toast(`Челлендж «${c.title}» завершён 🏆`)}}save()}

function tipsPage(){ensureBigData();const focus=data.tipChoice.focus||'all';return `<section class="card hero"><div class="row between wrap"><div><div class="label">Персонализация</div><h1 style="font-family:Georgia,serif;margin:4px 0">💡 Советы именно для тебя</h1><p>Выбирай тип кожи и волос — рекомендации перестроятся сразу.</p></div><button class="btn secondary small" id="refreshWebTips">↻ Обновить из интернета</button></div><div class="grid grid-3" style="margin-top:14px"><div class="field"><label>Тип кожи</label><select id="tipSkin">${Object.entries({normal:'Нормальная',dry:'Сухая',oily:'Жирная',combination:'Комбинированная',sensitive:'Чувствительная'}).map(([k,v])=>`<option value="${k}" ${(data.tipChoice.skin||data.settings.skinType)===k?'selected':''}>${v}</option>`).join('')}</select></div><div class="field"><label>Тип волос</label><select id="tipHair">${Object.entries({normal:'Нормальные',dry:'Сухие',oily:'Жирные',damaged:'Повреждённые',colored:'Окрашенные'}).map(([k,v])=>`<option value="${k}" ${(data.tipChoice.hair||data.settings.hairType)===k?'selected':''}>${v}</option>`).join('')}</select></div><div class="field"><label>Фокус</label><select id="tipFocus"><option value="all" ${focus==='all'?'selected':''}>Кожа + волосы</option><option value="skin" ${focus==='skin'?'selected':''}>Только кожа</option><option value="hair" ${focus==='hair'?'selected':''}>Только волосы</option></select></div></div></section><div class="grid grid-2" style="margin-top:16px"><section class="card"><div class="row between"><h3 class="section-title">✨ Совет дня</h3><span class="tag">Обновляется ежедневно</span></div><p style="font-size:18px;line-height:1.7">${esc(dynamicTip())}</p><div class="row wrap"><span class="tag">Кожа: ${skinTypeName(data.tipChoice.skin)}</span><span class="tag">Волосы: ${hairTypeName(data.tipChoice.hair)}</span>${data.settings.weather?`<span class="tag">${weatherIcon(data.settings.weather.description)} ${data.settings.weather.temp}°</span>`:''}</div></section><section class="card"><h3 class="section-title">🌸 База для твоего типа</h3><div class="list">${[...(BIG_LOCAL_TIPS[data.tipChoice.skin]||[]),...(BIG_HAIR_TIPS[data.tipChoice.hair]||[])].map(t=>`<div class="item">${esc(t)}</div>`).join('')}</div></section></div><section class="card" style="margin-top:16px"><div class="row between"><h3 class="section-title">🌐 Что нашлось в интернете</h3><span class="tag">${data.webArticles.length} материалов · ${esc(data.webArticles[0]?.source||'Подборка редакции')}</span></div><div class="grid grid-2" id="webTipsGrid">${data.webArticles.length?data.webArticles.map(webArticleCard).join(''):'<div class="empty" style="grid-column:1/-1">Нажми «Обновить из интернета» — я подберу материалы под твой тип.</div>'}</div><p class="subtle" style="margin-top:12px">Материалы из интернета — это информационная подборка, не медицинская диагностика.</p></section>`}
function webArticleCard(a){return `<article class="item article"><div class="label">${esc(a.source||'Интернет')}</div><h4>${esc(a.title)}</h4><p>${esc(a.snippet||'Открой материал, чтобы посмотреть подробности.')}</p><div class="row between" style="margin-top:10px"><span class="tag">📖 ${a.rank||1}</span><button class="btn secondary small" data-open-web="${esc(a.id)}">Открыть источник</button></div></article>`}

function articlesPage(){ensureBigData();return `<section class="card hero"><div class="row between wrap"><div><div class="label">Читаем по делу</div><h1 style="font-family:Georgia,serif;margin:4px 0">📖 Мини-статьи и материалы</h1><p>Локальные заметки + свежая подборка из интернета под твой профиль.</p></div><button class="btn" id="refreshArticles">↻ Подтянуть свежие материалы</button></div></section><div class="grid grid-2" style="margin-top:16px">${articles.map(a=>`<div class="card article" data-article="${a.id}"><span class="tag">${a.tag}</span><h4>${esc(a.title)}</h4><p>${esc(a.text.slice(0,170))}…</p><button class="btn secondary small" style="margin-top:10px">Читать</button></div>`).join('')}</div><section class="card" style="margin-top:16px"><h3 class="section-title">🌐 Интернет-подборка</h3><div class="grid grid-2">${data.webArticles.length?data.webArticles.map(webArticleCard).join(''):'<div class="empty" style="grid-column:1/-1">Пока нет онлайн-материалов. Нажми обновить.</div>'}</div></section>`}

function glowCard(){const g=glowScore();return `<section class="card glow-card"><div class="row between"><div><div class="label">Мой показатель сияния</div><h2 style="font-family:Georgia,serif;margin:5px 0">✨ ПОКАЗАТЕЛЬ СИЯНИЯ</h2><p class="subtle">Собран из ухода, регулярности, оценок, фото, streak и целей.</p></div><div class="glow-number">${g}</div></div><div class="glow-scale"><span>0</span><div><i style="width:${g}%"></i></div><span>50</span><span>100</span></div><p style="margin:12px 0 0;font-weight:600">${glowDelta()>=0?'✨ Ты стала на '+glowDelta()+'% стабильнее — так держать!':'🌷 Сейчас хороший момент вернуться к своему ритму.'}</p></section>`}
function homePage(){const original=dayStats(todayKey());const lv=levelInfo();return `<div class="grid" style="gap:16px"><section class="card hero"><div class="split"><div style="flex:1"><div class="label">${fmtDate(todayKey())}</div><h1>${greeting()}, ${esc(data.settings.name)} ♡</h1><p>${original.p===100?'Сегодня всё закрыто — потрясающе ✨':'Давай сделаем сегодняшний уход чуть-чуть красивее.'}</p><div class="row wrap" style="margin-top:16px"><button class="btn" data-action="quickRoutine">♡ Открыть Сегодня</button><button class="btn secondary" data-route="luck">🎡 Ежедневная удача</button><button class="btn ghost" data-route="pet">🐾 К питомцу</button></div></div><div class="circle" style="--p:${original.p}"><div class="inside"><span class="label">Сегодня</span><strong>${original.p}%</strong><span class="subtle">${original.done.length}/${original.all.length}</span></div></div></div></section>${glowCard()}<div class="grid grid-4"><div class="stat"><span class="label">🔥 Streak</span><b>${currentStreak()}</b><span class="subtle">лучший ${bestStreak()}</span></div><div class="stat"><span class="label">✨ XP</span><b>${data.xp}</b><span class="subtle">уровень ${data.level}</span></div><div class="stat"><span class="label">🐾 Питомец</span><b>${data.pet.points}</b><span class="subtle">очков заботы</span></div><div class="stat"><span class="label">💗 Любимчики</span><b>${data.favoriteProducts.length}</b><span class="subtle">из средств</span></div></div><section class="card"><div class="row between"><div><h3 class="section-title">💡 Персональный совет</h3><p class="subtle">Конкретный шаг на сегодня — с учётом твоего профиля и условий дня.</p></div><button class="btn secondary small" data-route="tips">Все советы</button></div><p style="font-size:18px;line-height:1.7">${esc(dynamicTip())}</p></section><div class="grid grid-2"><section class="card"><div class="row between"><h3 class="section-title">🐾 ${esc(data.pet.name)} сегодня</h3><button class="btn secondary small" data-route="pet">Открыть</button></div><div class="row"><div class="pet">${petEmoji()}</div><div style="flex:1">${bar('Счастье',data.pet.happiness)}${bar('Сытость',data.pet.hunger)}${bar('Энергия',data.pet.energy)}</div></div></section><section class="card"><div class="row between"><h3 class="section-title">☁️ Погода</h3><button class="btn secondary small" data-route="settings">Настроить</button></div>${data.settings.weather?`<div class="kpi">${weatherIcon(data.settings.weather.description)} ${data.settings.weather.temp}°</div><p class="subtle">${esc(data.settings.weather.city)} · ${esc(data.settings.weather.description)}</p>`:'<div class="empty">Добавь город в настройках, чтобы получать погодные подсказки.</div>'}</section></div></div>`}

function improvedShopPage(){ensureBigData();const groups=['Все','Питомец','Темы','Рамки','Бейджи','Декор'];return `<section class="card hero"><div class="row between wrap"><div><div class="label">Коллекционирование</div><h1 style="font-family:Georgia,serif;margin:4px 0">🛍️ Бьюти-магазин</h1><p>Покупай за XP предметы для питомца, темы и украшения.</p></div><div class="tag">✨ ${Number(data.xp)||0} XP</div></div></section><div class="chip-tabs" style="margin:14px 0">${groups.map(g=>`<button class="${g==='Все'?'active':''}" data-shop-filter="${g}">${g}</button>`).join('')}</div><div class="grid grid-4" id="shopGrid">${SHOP_CATALOG.map(shopCardV2).join('')}</div>`}
function shopCardV2(item){const own=data.shop.owned.includes(item.id);const usable=own;return `<div class="card shop-card"><div class="shop-icon">${item.icon}</div><span class="tag">${item.rarity}</span><h4>${esc(item.title)}</h4><p class="subtle">${esc(item.desc)}</p><div class="row between"><strong>${own?'Получено':'✦ '+item.cost+' XP'}</strong><button class="btn ${own?'secondary':''} small" data-shop-buy2="${item.id}">${own?'Использовать':'Получить'}</button></div></div>`}

function buyShopV2(id){ensureBigData();const item=SHOP_CATALOG.find(x=>x.id===id);if(!item)return;const balance=Math.floor(Number(data.xp)||0);const cost=Math.max(0,Math.floor(Number(item.cost)||0));if(data.shop.owned.includes(id)){equipShop(id);return}if(balance<cost){toast(`Нужно ещё ${cost-balance} XP ♡`);return}data.xp=balance-cost;data.shop.owned.push(id);save();playSound('win');toast(`Покупка: ${item.title} ${item.icon}`);render()}
function equipShopV2(id){ensureBigData();const item=SHOP_CATALOG.find(x=>x.id===id);if(!item||!data.shop.owned.includes(id))return;if(item.type==='theme'){data.shop.equipped.theme=item.id;data.settings.theme='shop-'+item.id;applyShopTheme(item)}else if(item.type==='pet'){if(data.pet.accessories.includes(id))data.pet.accessories=data.pet.accessories.filter(x=>x!==id);else data.pet.accessories.push(id);data.shop.equipped.pet=data.pet.accessories.at(-1)||''}else if(item.type==='frame'){data.settings.avatarFrame=data.settings.avatarFrame===item.frameId?'':item.frameId;data.shop.equipped.frame=data.settings.avatarFrame?item.id:''}else{data.shop.equipped[item.type]=data.shop.equipped[item.type]===id?'':id;if(item.type==='petRoom')data.pet.room=item.id;if(item.type==='petBg')data.pet.bg=item.id;if(item.type==='petToy')data.pet.toy=item.id}save();playSound('click');toast(`${item.title} ${data.settings.avatarFrame===item.frameId?'надета':'снята'} ✨`);render()}

function productRatingModalV2(id){const p=data.products.find(x=>x.id===id);if(!p)return;ensureBigData();const r=data.productRatings[id]||{score:productRating(p),status:'',note:''};modal(`<h3>${esc(p.name)} ♡</h3><form id="ratingFormV2" class="form"><div class="grid grid-2"><div class="field"><label>Моя оценка</label><select name="score">${Array.from({length:11},(_,n)=>`<option value="${n}" ${Number(r.score)===n?'selected':''}>${n===0?'Не оценено':n+'/10'}</option>`).join('')}</select></div><div class="field"><label>Статус</label><select name="status"><option value="" ${!r.status?'selected':''}>Без статуса</option><option value="favorite" ${r.status==='favorite'?'selected':''}>♡ Любимое</option><option value="works" ${r.status==='works'?'selected':''}>💗 Работает</option><option value="repeat" ${r.status==='repeat'?'selected':''}>🤍 Повторить</option><option value="bad" ${r.status==='bad'?'selected':''}>🚫 Не подошло</option></select></div></div><div class="field"><label>Личные впечатления</label><textarea name="note" placeholder="Текстура, запах, эффект, желание повторить…">${esc(r.note||'')}</textarea></div><div class="modal-actions"><button type="button" class="btn secondary" id="cancelRatingV2">Отмена</button><button class="btn">Сохранить оценку</button></div></form>`);document.getElementById('cancelRatingV2').onclick=closeModal;document.getElementById('ratingFormV2').onsubmit=e=>{e.preventDefault();const f=new FormData(e.target);const score=Number(f.get('score'))||0;const status=String(f.get('status')||'');data.productRatings[id]={score,status,note:String(f.get('note')||''),updated:Date.now()};if(status==='favorite'&&!data.favoriteProducts.includes(id))data.favoriteProducts.push(id);if(status!=='favorite')data.favoriteProducts=data.favoriteProducts.filter(x=>x!==id);save();closeModal();refreshBigChallenges();checkAchievements();playSound('win');render();toast('Оценка сохранена ♡')};}
function productStatus(p){const r=data.productRatings[p.id]||{};if(r.status==='favorite')return '♡ Любимое';if(r.status==='works')return '💗 Работает';if(r.status==='repeat')return '🤍 Повторить';if(r.status==='bad')return '🚫 Не подошло';return ''}
function productLargeCardV2(p){const fav=productIsFav(p),r=productRating(p),status=productStatus(p);return `<div class="card"><div class="row between"><span class="tag">${esc(p.category||'Средство')}</span><button class="icon-btn" data-fav-product="${p.id}" aria-label="Любимое">${fav?'♥':'♡'}</button></div>${p.image?`<img src="${p.image}" style="width:100%;height:180px;object-fit:cover;border-radius:18px;margin-top:10px">`:`<div class="product-placeholder">🧴</div>`}<h4>${esc(p.name)}</h4><p class="subtle">${esc(p.brand||'Без бренда')}</p><div class="row wrap"><span class="tag">⭐ ${r?r+'/10':'Нет оценки'}</span>${status?`<span class="tag">${status}</span>`:''}<span class="tag">Использовано ${p.used||0}</span></div><div class="row wrap" style="margin-top:10px"><button class="btn secondary small" data-rate-product="${p.id}">Оценить</button><button class="btn ghost small" data-use-product="${p.id}">Использовала</button></div></div>`}
function favoritesPage(){ensureBigData();const fav=data.products.filter(productIsFav),rated=data.products.filter(p=>productRating(p)>0),topUsed=[...data.products].sort((a,b)=>(b.used||0)-(a.used||0)).slice(0,3),topRate=[...rated].sort((a,b)=>productRating(b)-productRating(a)).slice(0,3);const avg=rated.length?(rated.reduce((s,p)=>s+productRating(p),0)/rated.length).toFixed(1):'—';return `<section class="card hero"><div class="row between wrap"><div><div class="label">Твоя полка</div><h1 style="font-family:Georgia,serif;margin:4px 0">💗 Мои любимчики</h1><p>Любимое, рабочее, повторить и честные оценки — всё в одном месте.</p></div><div class="circle small-circle" style="--p:${rated.length?Number(avg)*10:0}"><div class="inside"><span class="label">Средняя</span><strong>${avg}</strong><span class="subtle">/10</span></div></div></div></section><div class="grid grid-4" style="margin-top:16px"><div class="stat"><span class="label">♡ Любимые</span><b>${fav.length}</b></div><div class="stat"><span class="label">⭐ Оценено</span><b>${rated.length}</b></div><div class="stat"><span class="label">🔥 Топ по использованию</span><b>${topUsed[0]?.used||0}</b></div><div class="stat"><span class="label">✨ Средняя оценка</span><b>${avg}</b></div></div><div class="grid grid-2" style="margin-top:16px"><section class="card"><h3 class="section-title">🥇 Топ по использованию</h3><div class="list">${topUsed.map((p,i)=>`<div class="item row"><div style="font-size:24px">${['🥇','🥈','🥉'][i]}</div><div><strong>${esc(p.name)}</strong><div class="subtle">${p.used||0} использований</div></div></div>`).join('')||'<div class="empty">Пока нет истории использования.</div>'}</div></section><section class="card"><h3 class="section-title">⭐ Топ по оценке</h3><div class="list">${topRate.map((p,i)=>`<div class="item row"><div style="font-size:24px">${['🥇','🥈','🥉'][i]}</div><div><strong>${esc(p.name)}</strong><div class="subtle">${productRating(p)}/10 · ${productStatus(p)||'без статуса'}</div></div></div>`).join('')||'<div class="empty">Оцени средства — здесь появятся фавориты.</div>'}</div></section></div><section class="card" style="margin-top:16px"><h3 class="section-title">💗 Моя полка</h3><div class="grid grid-3">${fav.map(productLargeCardV2).join('')||'<div class="empty" style="grid-column:1/-1">♡ Здесь пока пусто. Открой «Средства» и нажми сердечко.</div>'}</div></section>`}

function enhancedPetPage(){ensureBigData();const p=data.pet, stage=PET_10_STAGES[p.stage-1], next=PET_10_STAGES[p.stage]||null;const room=SHOP_CATALOG.find(x=>x.id===p.room),bg=SHOP_CATALOG.find(x=>x.id===p.bg),toy=SHOP_CATALOG.find(x=>x.id===p.toy);return `<section class="card pet-world" style="--pet-bg:${bg?'var(--surface2)':'var(--surface)'}"><div class="pet-scene"><div class="pet-bg-icon">${bg?bg.icon:'♡'}</div><div class="pet-hero-emoji">${petEmoji()}</div><div class="pet-sparkles">✦ ˚₊‧ ୨୧ ‧₊˚ ✦</div></div><div class="row between wrap"><div><div class="label">${esc(data.pet.kind)} · стадия ${p.stage}/10</div><h1 style="font-family:Georgia,serif;margin:4px 0">${esc(p.name)} ♡</h1><div class="pet-stage">${stage.label}</div><p>${petNeeds()}</p></div><div class="row wrap"><span class="tag">✨ ${p.points} заботы</span><span class="tag">🤍 ${p.affection} привязанности</span><span class="tag">🎀 ${p.playCount} игр</span></div></div><div class="row wrap" style="margin-top:16px"><button class="btn" data-pet-feed>🍓 Покормить</button><button class="btn secondary" data-pet-play>🎀 Поиграть</button><button class="btn ghost" data-pet-rest>🌙 Отдых</button><button class="btn ghost" data-edit-pet>✎ Настроить</button><button class="btn secondary" data-route="shop">🛍️ Бьюти-магазин</button></div></section><div class="grid grid-3" style="margin-top:16px"><div class="card"><h3 class="section-title">💗 Счастье</h3><div class="kpi">${p.happiness}%</div>${bar('Счастье',p.happiness)}</div><div class="card"><h3 class="section-title">🍓 Сытость</h3><div class="kpi">${p.hunger}%</div>${bar('Сытость',p.hunger)}</div><div class="card"><h3 class="section-title">⚡ Энергия</h3><div class="kpi">${p.energy}%</div>${bar('Энергия',p.energy)}</div></div><section class="card" style="margin-top:16px"><div class="row between"><div><h3 class="section-title">🌱 Эволюция</h3><p class="subtle">Следующая форма: ${next?esc(next.label):'максимальная стадия ✨'}</p></div><span class="tag">${next?`${p.points}/${next.need} заботы`:'MAX ✨'}</span></div><div class="timeline pet-timeline">${PET_10_STAGES.map((s,i)=>`<div class="timeline-item ${i<p.stage?'done':''}"><strong>${s.n}. ${esc(s.label)}</strong><p class="subtle">${s.need} очков заботы · ${PET_EMOJIS[p.kind||'котёнок'][i]}</p></div>`).join('')}</div></section><section class="card" style="margin-top:16px"><h3 class="section-title">🏠 Его пространство</h3><div class="grid grid-3"><div class="item"><strong>Комната</strong><p>${room?esc(room.title):'Базовая'}</p></div><div class="item"><strong>Фон</strong><p>${bg?esc(bg.title):'Базовый'}</p></div><div class="item"><strong>Игрушка</strong><p>${toy?esc(toy.title):'Пока нет'}</p></div></div></section>`}

function settingsPage(){return `<div class="grid grid-2"><section class="card"><h3 class="section-title">👤 Профиль и персонализация</h3><form id="settingsForm" class="form"><div class="field"><label>Имя</label><input name="name" value="${esc(data.settings.name)}"></div><div class="grid grid-2"><div class="field"><label>Тип кожи</label><select name="skinType">${[['normal','Нормальная'],['dry','Сухая'],['oily','Жирная'],['combination','Комбинированная'],['sensitive','Чувствительная']].map(([v,l])=>`<option value="${v}" ${data.settings.skinType===v?'selected':''}>${l}</option>`).join('')}</select></div><div class="field"><label>Тип волос</label><select name="hairType">${[['normal','Нормальные'],['dry','Сухие'],['oily','Жирные'],['damaged','Повреждённые'],['colored','Окрашенные']].map(([v,l])=>`<option value="${v}" ${data.settings.hairType===v?'selected':''}>${l}</option>`).join('')}</select></div></div><div class="field"><label>Город для погоды</label><input name="city" value="${esc(data.settings.city)}" placeholder="Например, Таллин"></div><div class="grid grid-2"><div class="field"><label>Основная тема</label><select name="theme">${Object.entries(themes).map(([v,t])=>`<option value="${v}" ${data.settings.theme===v?'selected':''}>${t.name}</option>`).join('')}</select></div><div class="field"><label>Звуки</label><select name="sound"><option value="on" ${data.sound.enabled?'selected':''}>Включены</option><option value="off" ${!data.sound.enabled?'selected':''}>Выключены</option></select></div><div class="field"><label>Фоновая музыка</label><select name="music"><option value="on" ${data.music?.enabled?'selected':''}>Включена</option><option value="off" ${!data.music?.enabled?'selected':''}>Выключена</option></select></div></div><label class="row"><input type="checkbox" name="animations" ${data.settings.animations?'checked':''}> Мягкие анимации</label><label class="row"><input type="checkbox" name="notifications" ${data.settings.notifications?'checked':''}> Локальные уведомления</label><button class="btn">Сохранить настройки</button></form></section><section class="card"><h3 class="section-title">☁️ Погода</h3><p class="subtle">Обновление через Open-Meteo; интернет нужен только для нового прогноза.</p><button class="btn" data-action="weather">Обновить погоду</button>${data.settings.weather?`<div class="item" style="margin-top:12px"><strong>${weatherIcon(data.settings.weather.description)} ${esc(data.settings.weather.city)}</strong><p>${data.settings.weather.temp}° · ${esc(data.settings.weather.description)} · влажность ${data.settings.weather.humidity}%</p></div>`:''}<h3 class="section-title" style="margin-top:18px">💾 Резервная копия</h3><div class="row wrap"><button class="btn secondary" data-export>Экспорт JSON</button><label class="btn secondary" style="cursor:pointer">Импорт JSON<input id="importFile" type="file" accept="application/json" hidden></label><button class="btn danger" data-reset>Очистить данные</button></div></section></div>`}

/* Override render, route shell and page binding while keeping the stable core. */
const oldRenderShell=renderShell;
renderShell=function(route){const titleMap={home:'Главная',today:'Сегодня',care:'Уход',products:'Средства',favorites:'Любимчики',shop:'Бьюти-магазин',calendar:'Календарь',progress:'Прогресс',achievements:'Достижения',goals:'Цели',journal:'Дневник',pet:'Питомец',challenges:'Челленджи',tips:'Советы',articles:'Статьи',reports:'Отчёты',settings:'Настройки',luck:'Удача'};const nav=[['home','⌂','Главная'],['today','♡','Сегодня'],['care','🌸','Уход'],['products','🧴','Средства'],['favorites','💗','Любимчики'],['shop','🛍️','Бьюти-магазин'],['calendar','📅','Календарь'],['progress','◯','Прогресс'],['achievements','✦','Достижения'],['goals','🎯','Цели'],['journal','✎','Дневник'],['pet','🐾','Питомец'],['challenges','🏆','Челленджи'],['tips','💡','Советы'],['articles','📖','Статьи'],['reports','📊','Отчёты'],['luck','🎡','Удача'],['settings','⚙','Настройки']];document.getElementById('app').innerHTML=`<aside class="sidebar"><div class="brand"><div class="sidebar-avatar-wrap"><div class="avatar" data-avatar${data.settings.avatarFrame?` data-frame="${esc(data.settings.avatarFrame)}"`:''} data-route="settings" title="Открыть профиль">${data.settings.avatar?`<img src="${data.settings.avatar}" alt="Аватар">`:`<span class="avatar-fallback">🌸</span>`}</div></div><h1>Мой Бьюти-дневник ♡</h1><p>Твой личный дневник ухода</p></div><div class="nav">${nav.map(([id,ic,l])=>`<button data-route="${id}" class="${route===id?'active':''}"><span>${ic}</span>${l}</button>`).join('')}</div><div class="sidebar-bottom"><div class="stat"><span class="label">Уровень</span><b>${data.level}</b><span class="subtle">${data.xp} XP</span></div></div></aside><main class="main"><header class="topbar"><div class="topbar-title"><button class="icon-btn" id="mobileMenu">☰</button><h2>${titleMap[route]||'Мой Бьюти-дневник'}</h2></div><div class="row"><span class="tag">🔥 ${currentStreak()} дней</span><button class="icon-btn" data-route="settings">⚙</button></div></header><section class="content" id="page"></section><nav class="bottom-nav">${[['home','⌂','Главная'],['today','♡','Сегодня'],['care','🌸','Уход'],['progress','◯','Прогресс'],['more','☰','Ещё']].map(([id,ic,l])=>`<button data-route="${id}" class="${route===id?'active':''}"><div>${ic}</div>${l}</button>`).join('')}</nav></main>`;document.querySelectorAll('[data-route]').forEach(el=>el.addEventListener('click',()=>{const r=el.dataset.route;if(r==='more')openMore();else location.hash=r}));document.getElementById('mobileMenu')?.addEventListener('click',()=>window.openMore())};
const oldRenderPage=renderPage;
renderPage=function(route){const p=document.getElementById('page');const map={home:homePage,today:todayPage,care:carePage,products:improvedProductsPage,favorites:favoritesPage,shop:improvedShopPage,calendar:calendarPage,progress:progressPage,achievements:achievementsPage,goals:goalsPage,journal:journalPage,pet:enhancedPetPage,challenges:challengesPage,tips:tipsPage,articles:articlesPage,reports:reportsPage,settings:settingsPage,luck:luckPage};p.innerHTML=(map[route]||homePage)();bindBigPage(route)};
function bindBigPage(route){
  try{baseBindPage(route)}catch{}
  document.querySelectorAll('[data-shop-buy2]').forEach(b=>b.onclick=()=>buyShopV2(b.dataset.shopBuy2));
  document.querySelectorAll('[data-equip-shop]').forEach(b=>b.onclick=()=>equipShopV2(b.dataset.equipShop));
  document.querySelectorAll('[data-fav-product]').forEach(b=>b.onclick=()=>toggleFav(b.dataset.favProduct));
  document.querySelectorAll('[data-rate-product]').forEach(b=>b.onclick=()=>productRatingModalV2(b.dataset.rateProduct));
  document.querySelectorAll('[data-use-product]').forEach(b=>b.onclick=()=>useProduct(b.dataset.useProduct));
  document.querySelectorAll('[data-route]').forEach(b=>{
    if(b.__bigBound)return;
    b.__bigBound=true;
    b.addEventListener('click',()=>{const r=b.dataset.route;if(r&&!b.closest('.sidebar,.bottom-nav'))location.hash=r});
  });
  if(route==='luck'){
    document.getElementById('spinWheel')?.addEventListener('click',spinWheel);
  }
  if(route==='tips'){
    document.getElementById('tipSkin')?.addEventListener('change',e=>{data.tipChoice.skin=e.target.value;save();render()});
    document.getElementById('tipHair')?.addEventListener('change',e=>{data.tipChoice.hair=e.target.value;save();render()});
    document.getElementById('tipFocus')?.addEventListener('change',e=>{data.tipChoice.focus=e.target.value;save();render()});
    document.getElementById('refreshWebTips')?.addEventListener('click',async()=>{playSound('click');toast('Подтягиваю свежие материалы…');await fetchWebArticles(true);render()});
    document.querySelectorAll('[data-open-web]').forEach(b=>b.addEventListener('click',()=>{const a=data.webArticles.find(x=>x.id===b.dataset.openWeb);if(a)window.open(a.url,'_blank','noopener')}));
  }
  if(route==='articles'){
    document.getElementById('refreshArticles')?.addEventListener('click',async()=>{playSound('click');toast('Ищу новые материалы…');await fetchWebArticles(true);render()});
    document.querySelectorAll('[data-open-web]').forEach(b=>b.addEventListener('click',()=>{const a=data.webArticles.find(x=>x.id===b.dataset.openWeb);if(a)window.open(a.url,'_blank','noopener')}));
  }
  if(route==='challenges'){
    document.querySelectorAll('[data-ch-filter]').forEach(b=>b.addEventListener('click',()=>{
      document.querySelectorAll('[data-ch-filter]').forEach(x=>x.classList.remove('active'));b.classList.add('active');
      const f=b.dataset.chFilter;
      document.querySelectorAll('.challenge-card').forEach(c=>c.style.display=(f==='all'||c.dataset.cat===f)?'':'none');
    }));
  }
  if(route==='settings'){
    document.getElementById('settingsForm')?.addEventListener('submit',e=>{
      e.preventDefault();const f=new FormData(e.target);
      data.settings.name=String(f.get('name')||'Красотка');data.settings.skinType=String(f.get('skinType')||'normal');data.settings.hairType=String(f.get('hairType')||'normal');data.settings.city=String(f.get('city')||'');data.settings.theme=String(f.get('theme')||'pink');
      data.settings.animations=f.get('animations')==='on';data.settings.notifications=f.get('notifications')==='on';data.sound.enabled=f.get('sound')==='on';data.music.enabled=f.get('music')==='on'; if(data.music.enabled)startAmbient();else stopAmbient();
      data.tipChoice.skin=data.settings.skinType;data.tipChoice.hair=data.settings.hairType;applyTheme();save();playSound('win');toast('Настройки сохранены ♡');render();
    });
  }
  if(route==='shop'){
    document.querySelectorAll('[data-shop-filter]').forEach(b=>b.addEventListener('click',()=>{
      document.querySelectorAll('[data-shop-filter]').forEach(x=>x.classList.remove('active'));b.classList.add('active');
      const f=b.dataset.shopFilter;
      document.querySelectorAll('#shopGrid .shop-card').forEach(card=>{
        const title=card.querySelector('h4')?.textContent||'';const item=SHOP_CATALOG.find(x=>x.title===title);let show=true;
        if(f==='Питомец')show=!!item&&['pet','petRoom','petBg','petToy'].includes(item.type);
        else if(f==='Темы')show=!!item&&item.type==='theme';
        else if(f==='Рамки')show=!!item&&item.type==='frame';
        else if(f==='Бейджи')show=!!item&&item.type==='badge';
        else if(f==='Декор')show=!!item&&!['theme','frame','badge'].includes(item.type);
        card.style.display=show?'':'none';
      });
    }));
  }
}

/* Better product list on its page. */
improvedProductsPage=function(){ensureBigData();return `<div class="row between wrap"><div><h3 class="section-title">🧴 Мои средства</h3><p class="subtle">Оценки, статусы, любимчики и история использования.</p></div><div class="row wrap"><button class="btn secondary" data-route="favorites">♡ Любимчики</button><button class="btn" data-add-product>+ Добавить средство</button></div></div><div class="grid grid-4" style="margin:14px 0"><div class="stat"><span class="label">Всего</span><b>${data.products.length}</b></div><div class="stat"><span class="label">Любимчики</span><b>${data.favoriteProducts.length}</b></div><div class="stat"><span class="label">Оценено</span><b>${data.products.filter(p=>productRating(p)>0).length}</b></div><div class="stat"><span class="label">Средняя оценка</span><b>${(()=>{const a=data.products.filter(p=>productRating(p)>0);return a.length?(a.reduce((s,p)=>s+productRating(p),0)/a.length).toFixed(1):'—'})()}</b></div></div><div class="field" style="margin:14px 0"><input id="productSearch" placeholder="Поиск по средствам, бренду, заметкам…"></div><div class="grid grid-3" id="productGrid">${data.products.length?data.products.map(productLargeCardV2).join(''):'<div class="empty" style="grid-column:1/-1">♡ Твоя полка пока пуста.</div>'}</div>`}

/* Bind article reads and big shop actions globally. */
document.addEventListener('click',e=>{const a=e.target.closest?.('[data-article]');if(a&&a.dataset.article){data.articleReads=data.articleReads||{};data.articleReads[a.dataset.article]=Date.now();save()}const sb=e.target.closest?.('[data-shop-buy2]');if(sb){e.preventDefault();buyShopV2(sb.dataset.shopBuy2)}const es=e.target.closest?.('[data-equip-shop]');if(es){e.preventDefault();equipShopV2(es.dataset.equipShop)}const rp=e.target.closest?.('[data-rate-product]');if(rp){e.preventDefault();productRatingModalV2(rp.dataset.rateProduct)} });

/* Append enough visual polish for the new systems. */
(()=>{const st=document.createElement('style');st.textContent=`
.glow-card{background:linear-gradient(135deg,var(--surface),var(--surface2));overflow:hidden}.glow-number{font-size:62px;font-weight:800;font-family:Georgia,serif;background:linear-gradient(135deg,var(--primary),var(--accent));-webkit-background-clip:text;background-clip:text;color:transparent}.glow-scale{display:grid;grid-template-columns:28px 1fr 34px 38px;gap:8px;align-items:center;margin-top:14px;color:var(--muted);font-size:12px}.glow-scale div{height:14px;background:#f1e6ec;border-radius:999px;overflow:hidden}.glow-scale i{display:block;height:100%;background:linear-gradient(90deg,var(--primary),var(--accent),var(--success));border-radius:999px}.product-placeholder{height:180px;border-radius:18px;background:linear-gradient(135deg,var(--surface2),var(--surface));display:grid;place-items:center;font-size:64px;margin-top:10px}.luck-card{display:flex;flex-direction:column;align-items:center;justify-content:center;min-height:640px}.wheel-wrap{position:relative;width:min(500px,90vw);aspect-ratio:1/1;display:grid;place-items:center}.luck-wheel{width:100%;height:100%;border-radius:50%;background:conic-gradient(#f7c2d6 0 10%,#dfc4ee 10% 20%,#bfe9d7 20% 30%,#f7ddb0 30% 40%,#b9d9f2 40% 50%,#f3b2c6 50% 60%,#d7c4ed 60% 70%,#c1ebdf 70% 80%,#f6c2b7 80% 90%,#ddd6f3 90% 100%);border:14px solid #fff;box-shadow:0 24px 70px rgba(86,45,73,.18);position:relative;transition:transform 3.9s cubic-bezier(.16,.7,.14,1)}.wheel-center{position:absolute;left:50%;top:50%;transform:translate(-50%,-50%);width:116px;height:116px;border-radius:50%;background:var(--surface);display:grid;place-items:center;font-size:34px;box-shadow:0 8px 22px rgba(50,30,40,.16);z-index:4}.wheel-center small{display:block;font-size:10px;letter-spacing:.12em;color:var(--muted);margin-top:-22px}.wheel-pointer{position:absolute;top:-12px;left:50%;transform:translateX(-50%);z-index:6;font-size:34px;color:var(--text);filter:drop-shadow(0 5px 6px rgba(0,0,0,.15))}.wheel-label{position:absolute;left:50%;top:50%;width:92px;height:40px;margin:-20px -46px;transform:rotate(calc(var(--i)*36deg)) translateY(-155px) rotate(calc(var(--i)*-36deg));display:flex;flex-direction:column;align-items:center;justify-content:center;font-size:10px;text-align:center}.wheel-label img{width:36px;height:36px;display:block;margin-bottom:3px}.prize-png{width:38px;height:38px;flex:0 0 auto}.pet-world{overflow:hidden;background:linear-gradient(145deg,var(--surface),var(--surface2))}.pet-scene{min-height:260px;border-radius:28px;background:radial-gradient(circle at 20% 20%,rgba(255,255,255,.8),transparent 45%),linear-gradient(145deg,var(--surface2),var(--surface));position:relative;display:grid;place-items:center;margin-bottom:18px;overflow:hidden}.pet-hero-emoji{font-size:150px;filter:drop-shadow(0 20px 28px rgba(70,40,60,.18));z-index:2}.pet-bg-icon{position:absolute;font-size:260px;opacity:.10;right:-20px;bottom:-40px}.pet-sparkles{position:absolute;top:22px;left:22px;color:var(--primary);opacity:.65}.pet-timeline .timeline-item.done:before{background:var(--success)}.pet-timeline .timeline-item strong{font-family:Georgia,serif}.shop-card{transition:transform .18s ease,box-shadow .18s ease}.shop-card:hover{transform:translateY(-3px)}
@media (max-width:900px){.luck-card{min-height:auto}.glow-scale{grid-template-columns:24px 1fr 30px 30px}.wheel-label{transform:rotate(calc(var(--i)*36deg)) translateY(-125px) rotate(calc(var(--i)*-36deg))}}
`;document.head.appendChild(st)})();

/* Re-run important derived state on every render. */
const oldRender=render;
render=function(){ensureBigData();tickPet();refreshBigChallenges();checkAchievements();oldRender();if(location.hash.replace('#','')==='tips'||location.hash.replace('#','')==='articles'){fetchWebArticles(false).then(()=>{if(location.hash.replace('#','')==='tips'||location.hash.replace('#','')==='articles'){const p=document.getElementById('page');if(p){const r=location.hash.replace('#','');p.innerHTML=(r==='tips'?tipsPage():articlesPage());bindBigPage(r)}}})}};

window.addEventListener('hashchange',render);try{load();ensureProData();applyTheme();render();}catch(err){const app=document.getElementById('app');if(app)app.innerHTML='<main style="min-height:100vh;display:grid;place-items:center;padding:24px;background:#fff9fb;font-family:system-ui"><section style="max-width:560px;background:#fff;border:1px solid rgba(74,55,66,.1);border-radius:24px;padding:24px;box-shadow:0 14px 40px rgba(91,52,72,.09)"><h1 style="font-family:Georgia,serif">Не удалось запустить дневник ♡</h1><p style="color:#8f858e">Нажми «Сбросить локальные данные», чтобы создать чистое хранилище.</p><button onclick="localStorage.removeItem(&quot;myBeautyJournal_v3&quot;);location.reload()" style="padding:11px 15px;border:0;border-radius:15px;background:#e889ad;color:#fff">Сбросить локальные данные</button></section></main>';console.error(err)}
// BEAUTY JOURNAL UX / PET WORLD / SHOP 2.0 / PRINTABLE PDF UPGRADE
// ---------- Theme expansion ----------
themes.strawberry={name:'Клубничный зефир',vars:{'--bg':'#fff8f8','--surface':'#ffffff','--surface2':'#fff0f1','--text':'#473b40','--muted':'#9d858d','--primary':'#e97991','--primary2':'#f6b9c5','--accent':'#f0a8c0','--success':'#8fc9ae'}};
themes.minimal={name:'Минималистичная',vars:{'--bg':'#fbfbfa','--surface':'#ffffff','--surface2':'#f3f3f1','--text':'#303031','--muted':'#7e7e80','--primary':'#7d8085','--primary2':'#d8dadd','--accent':'#aaaeb5','--success':'#86b39a'}};

// ---------- Extra state ----------
function ensureUXData(){
  ensureBigData();
  data.pet.activeZone=data.pet.activeZone||'bedroom';
  data.pet.ownedZones=Array.isArray(data.pet.ownedZones)?data.pet.ownedZones:['bedroom'];
  data.shop=data.shop&&typeof data.shop==='object'?data.shop:{};
  data.shop.owned=Array.isArray(data.shop.owned)?data.shop.owned:[];
  data.shop.equipped=data.shop.equipped||{};
  data.shop.dailyDate=data.shop.dailyDate||'';
  data.shop.dailyId=data.shop.dailyId||'';
  data.shop.dailyDiscount=Number(data.shop.dailyDiscount)||25;
  data.shop.collectorStats=data.shop.collectorStats||{};
  data.ui=data.ui&&typeof data.ui==='object'?data.ui:{};
  data.ui.favoritesFilter=data.ui.favoritesFilter||'all';
  data.ui.productsSearch=data.ui.productsSearch||'';
}

const PET_ZONES=[
  {id:'bedroom',label:'Комната',title:'Розовая спальня',icon:'🏠',unlock:0,desc:'Твоя первая уютная комната для питомца.'},
  {id:'spa',label:'Лавандовая комната',title:'Лавандовый спа',icon:'🪻',unlock:500,desc:'Мягкая spa-комната после 500 XP.'},
  {id:'garden',label:'Сад',title:'Сияющий сад',icon:'🌸',unlock:1500,desc:'Сияющий сад открывается после 1500 XP.'},
  {id:'bath',label:'Ванная',title:'Облачная ванная',icon:'🛁',unlock:2200,desc:'Маленькая ванная для beauty-ритуалов.'},
  {id:'wardrobe',label:'Гардероб',title:'Гардероб с бантиками',icon:'🎀',unlock:3200,desc:'Гардероб с аксессуарами и образами.'},
  {id:'toys',label:'Игровая',title:'Сад игрушек',icon:'🧸',unlock:4500,desc:'Игровая зона с игрушками и мини-наградами.'}
];

const UX_SHOP_ITEMS=[
 {id:'room-pink',type:'petRoom',title:'Розовая спальня',icon:'🎀',cost:0,rarity:'Обычный',desc:'Стартовая комната питомца.'},
 {id:'room-lavender',type:'petRoom',title:'Лавандовый спа',icon:'🪻',cost:500,rarity:'Редкий',desc:'Лавандовая комната с мягким светом.'},
 {id:'room-glow',type:'petRoom',title:'Сияющий сад',icon:'🌸',cost:1500,rarity:'Эпический',desc:'Сад с сияющими цветами.'},
 {id:'room-cloud',type:'petRoom',title:'Облачная ванная',icon:'🛁',cost:2200,rarity:'Эпический',desc:'Облачная ванная с пушистым паром.'},
 {id:'pet-bow-pink',type:'pet',title:'Розовый бантик',icon:'🎀',cost:180,rarity:'Обычный',desc:'Нежный бантик для питомца.'},
 {id:'pet-crown',type:'pet',title:'Корона',icon:'👑',cost:900,rarity:'Легендарный',desc:'Питомец сегодня главный.'},
 {id:'pet-halo',type:'pet',title:'Сияющий нимб',icon:'😇',cost:1200,rarity:'Легендарный',desc:'Немного небесного glow.'},
 {id:'pet-teddy',type:'petToy',title:'Мишка',icon:'🧸',cost:260,rarity:'Обычный',desc:'Игрушка для счастья.'},
 {id:'pet-unicorn',type:'petToy',title:'Мини-единорог',icon:'🦄',cost:780,rarity:'Эпический',desc:'Редкая игрушка.'},
 {id:'pet-bed-luxe',type:'petRoom',title:'Роскошная кровать',icon:'🛏️',cost:650,rarity:'Редкий',desc:'Отдельная кровать для питомца.'},
 {id:'theme-strawberry-shop',type:'theme',title:'Клубничное молочко',icon:'🍓',cost:700,rarity:'Редкий',desc:'Нежная клубничная тема.',vars:themes.strawberry.vars},
 {id:'frame-pearl',type:'frame',title:'Жемчужная рамка',icon:'🤍',cost:520,rarity:'Редкий',desc:'Молочная жемчужная рамка.'},
 {id:'frame-dream',type:'frame',title:'Рамка «Мечта»',icon:'☁️',cost:950,rarity:'Эпический',desc:'Воздушная рамка.'},
 {id:'frame-kitty',type:'frame',title:'Рамка «Kitty Dream»',icon:'🐱',cost:650,rarity:'Редкий',desc:'Милая рамка с кошачьим настроением.',collection:'Kitty Dream',shopAvatarFrame:true,frameId:'kitty'},
 {id:'frame-kuromi',type:'frame',title:'Рамка «Kuromi Night»',icon:'🖤',cost:850,rarity:'Эпический',desc:'Тёмная милая рамка с вайбом ночной коллекции.',collection:'Kuromi Night',shopAvatarFrame:true,frameId:'kuromi'},
 {id:'frame-sakura',type:'frame',title:'Рамка «Sakura Bloom»',icon:'🌸',cost:720,rarity:'Редкий',desc:'Нежная сакура вокруг аватара.',collection:'Sakura',shopAvatarFrame:true,frameId:'sakura'},
 {id:'frame-strawberry',type:'frame',title:'Рамка «Strawberry Milk»',icon:'🍓',cost:780,rarity:'Редкий',desc:'Сладкая клубничная рамка.',collection:'Strawberry Summer',shopAvatarFrame:true,frameId:'strawberry'},
 {id:'frame-mint',type:'frame',title:'Рамка «Mint Spa»',icon:'🍃',cost:760,rarity:'Редкий',desc:'Свежая мятная рамка в стиле spa.',collection:'Mint Spa',shopAvatarFrame:true,frameId:'mint'},
 {id:'frame-coquette',type:'frame',title:'Рамка «Coquette Bow»',icon:'🎀',cost:900,rarity:'Эпический',desc:'Кокетливая рамка с бантиками.',collection:'Coquette',shopAvatarFrame:true,frameId:'coquette'},
 {id:'frame-royal',type:'frame',title:'Рамка «Royal Glow»',icon:'👑',cost:1300,rarity:'Легендарный',desc:'Королевская сияющая рамка.',collection:'Royal Glow',shopAvatarFrame:true,frameId:'royal'},
 {id:'frame-cozy',type:'frame',title:'Рамка «Cozy Glow»',icon:'☕',cost:680,rarity:'Редкий',desc:'Тёплая уютная рамка.',collection:'Cozy Glow',shopAvatarFrame:true,frameId:'cozy'},
 {id:'frame-lavender-bloom',type:'frame',title:'Рамка «Lavender Spa»',icon:'🪻',cost:740,rarity:'Редкий',desc:'Мягкая лавандовая рамка.',collection:'Lavender Spa',shopAvatarFrame:true,frameId:'lavender-bloom'},
 {id:'frame-midnight-glow',type:'frame',title:'Рамка «Midnight Glow»',icon:'🌙',cost:1100,rarity:'Эпический',desc:'Ночная рамка со звёздным сиянием.',collection:'Midnight Glow',shopAvatarFrame:true,frameId:'midnight-glow'},
 {id:'badge-glow',type:'badge',title:'Значок «Сияние»',icon:'✨',cost:420,rarity:'Редкий',desc:'Маленькая отметка о твоём glow.'},
 {id:'secret-moon',type:'badge',title:'Секретная луна',icon:'🌙',cost:1400,rarity:'Секретный',desc:'Предмет, который почти никто не находит.'}
];
for(const item of UX_SHOP_ITEMS){if(!SHOP_CATALOG.some(x=>x.id===item.id))SHOP_CATALOG.push(item)}

function localDateKey(d=new Date()){return localKey(d)}
function shopDailyId(){
  ensureUXData();
  const key=localDateKey();
  if(data.shop.dailyDate===key && data.shop.dailyId)return data.shop.dailyId;
  const candidates=SHOP_CATALOG.filter(x=>Number(x.cost)>100);
  const seed=key.split('-').join('');
  let n=0; for(const ch of seed)n=(n*31+ch.charCodeAt(0))>>>0;
  const id=candidates[n%candidates.length]?.id||SHOP_CATALOG[0]?.id;
  data.shop.dailyDate=key; data.shop.dailyId=id; save(); return id;
}
function shopCost(item){
  const base=Math.max(0,Math.floor(Number(item?.cost)||0));
  return item?.id===shopDailyId() && base>0 ? Math.max(1,Math.floor(base*(1-(Number(data.shop.dailyDiscount)||25)/100))) : base;
}
function shopCategory(item){
  if(['pet','petToy'].includes(item.type))return 'Питомец';
  if(item.type==='petRoom')return 'Комнаты';
  if(item.type==='theme')return 'Темы';
  if(item.type==='frame')return 'Рамки';
  if(item.type==='avatar')return 'Аватары';
  if(item.rarity==='Редкий'||item.rarity==='Эпический'||item.rarity==='Легендарный'||item.rarity==='Секретный')return 'Редкие';
  return 'Декор';
}
function rarityClass(r){return String(r||'').toLowerCase().replace(/[^а-яa-z]+/g,'-')}

// ---------- Pet world ----------
function petZoneUnlocked(z){return Number(data.xp||0)>=z.unlock}
function activePetZone(){ensureUXData();const z=PET_ZONES.find(x=>x.id===data.pet.activeZone);return petZoneUnlocked(z||PET_ZONES[0])?(z||PET_ZONES[0]):PET_ZONES[0]}
function setPetZone(id){ensureUXData();const z=PET_ZONES.find(x=>x.id===id);if(!z)return;if(!petZoneUnlocked(z)){toast(`Нужно ещё ${z.unlock-Number(data.xp||0)} XP ♡`);return}data.pet.activeZone=id;if(!data.pet.ownedZones.includes(id))data.pet.ownedZones.push(id);save();playSound('click');render()}
function petWorldVisual(z){
  const p=data.pet;
  if(z.id==='bedroom')return `<div class="world-room world-pink"><div class="world-decor">🌷 ✦ ♡ ✦ 🌷</div><div class="world-bed">🛏️</div><div class="world-pet">${petEmoji()}</div><div class="world-caption">Мягкая кроватка · любимая комната</div></div>`;
  if(z.id==='spa')return `<div class="world-room world-lavender"><div class="world-decor">🪻 🫧 🪻</div><div class="world-bath">🛁</div><div class="world-pet">${petEmoji()}</div><div class="world-caption">Лавандовый спа · отдых и спокойствие</div></div>`;
  if(z.id==='garden')return `<div class="world-room world-garden"><div class="world-decor">🌸 🌿 🌷 🦋</div><div class="world-pet">${petEmoji()}</div><div class="world-caption">Сияющий сад · маленький сад питомца</div></div>`;
  if(z.id==='bath')return `<div class="world-room world-bath"><div class="world-decor">🫧 🫧 🫧</div><div class="world-bath">🛁</div><div class="world-pet">${petEmoji()}</div><div class="world-caption">Облачная ванная · beauty spa для питомца</div></div>`;
  if(z.id==='wardrobe')return `<div class="world-room world-wardrobe"><div class="world-decor">🎀 👑 🎀</div><div class="world-wardrobe-icon">👗</div><div class="world-pet">${petEmoji()}</div><div class="world-caption">Гардероб с бантиками · образы и аксессуары</div></div>`;
  return `<div class="world-room world-toys"><div class="world-decor">🧸 🪀 🦄 🎵</div><div class="world-pet">${petEmoji()}</div><div class="world-caption">Сад игрушек · любимые игрушки</div></div>`;
}
function petWorldPage(){
  ensureUXData(); const z=activePetZone(); const next=PET_ZONES.find(x=>x.unlock>Number(data.xp||0));
  return `<section class="card hero pet-world-v3"><div class="row between wrap"><div><div class="label">Маленькая вселенная</div><h1 style="font-family:Georgia,serif;margin:4px 0">🐾 Мир ${esc(data.pet.name)} ♡</h1><p>Открывай новые зоны за XP и перемещай питомца между ними.</p></div><div class="tag">✨ ${Number(data.xp||0)} XP</div></div>${next?`<div class="pet-unlock-note">Следующая зона: <strong>${esc(next.title)}</strong> · ещё ${Math.max(0,next.unlock-Number(data.xp||0))} XP</div>`:'<div class="pet-unlock-note">✨ Весь мир питомца открыт.</div>'}</section>
  <div class="zone-grid">${PET_ZONES.map(zone=>`<button type="button" class="zone-card ${zone.id===z.id?'active':''} ${petZoneUnlocked(zone)?'unlocked':'locked'}" data-pet-zone="${zone.id}"><div class="zone-icon">${zone.icon}</div><div class="zone-name">${esc(zone.title)}</div><div class="zone-label">${esc(zone.label)}</div><div class="zone-lock">${petZoneUnlocked(zone)?'Открыто ✦':`🔒 ${zone.unlock} XP`}</div></button>`).join('')}</div>
  <section class="card pet-world-stage" style="margin-top:16px"><div class="row between wrap"><div><span class="tag">${z.icon} ${esc(z.label)}</span><h2 style="font-family:Georgia,serif;margin:10px 0 4px">${esc(z.title)}</h2><p class="subtle">${esc(z.desc)}</p></div><div class="pet-mini-status"><span>💗 ${data.pet.happiness}%</span><span>🍓 ${data.pet.hunger}%</span><span>⚡ ${data.pet.energy}%</span></div></div>${petWorldVisual(z)}</section>
  <section class="grid grid-3" style="margin-top:16px"><div class="card"><h3 class="section-title">🛏️ Сон</h3><p class="subtle">Уютная зона для отдыха и восстановления.</p><button class="btn secondary small" data-pet-rest>Отдохнуть</button></div><div class="card"><h3 class="section-title">🛁 Уход</h3><p class="subtle">Питомец тоже любит маленькие ритуалы.</p><button class="btn secondary small" data-pet-feed>Покормить</button></div><div class="card"><h3 class="section-title">🧸 Игры</h3><p class="subtle">Поддерживай счастье и привязанность.</p><button class="btn secondary small" data-pet-play>Поиграть</button></div></section>`;
}

// ---------- Shop 2.0 ----------
let __shopFilter='Все';
function shopPageV3(){
 ensureUXData(); const daily=shopDailyId(); const filters=['Все','Питомец','Комнаты','Темы','Рамки','Аватары','Редкие'];
 const list=SHOP_CATALOG.filter(x=>__shopFilter==='Все'||(__shopFilter==='Редкие'?['Редкий','Эпический','Легендарный','Секретный'].includes(x.rarity):shopCategory(x)===__shopFilter));
 const dailyItem=SHOP_CATALOG.find(x=>x.id===daily);
 return `<section class="card hero"><div class="row between wrap"><div><div class="label">Коллекция красоты</div><h1 style="font-family:Georgia,serif;margin:4px 0">🛍️ Бьюти-магазин 2.0</h1><p>Покупай, коллекционируй и открывай предметы для своего мира.</p></div><div class="tag">✨ ${Number(data.xp||0)} XP</div></div></section>
 <section class="card shop-daily" style="margin-top:16px"><div class="row between wrap"><div><span class="tag">Предмет дня</span><h3 style="font-family:Georgia,serif;margin:8px 0">${dailyItem?dailyItem.icon+' '+esc(dailyItem.title):'—'}</h3><p class="subtle">Сегодня скидка ${data.shop.dailyDiscount}% за XP.</p></div>${dailyItem?`<div class="shop-daily-price"><span class="old">${Math.floor(Number(dailyItem.cost)||0)} XP</span><strong>${shopCost(dailyItem)} XP</strong></div>`:''}</div></section>
 <div class="chip-tabs" style="margin:14px 0">${filters.map(f=>`<button type="button" class="${__shopFilter===f?'active':''}" data-shop-filter-v3="${f}">${f}</button>`).join('')}</div>
 <div class="grid grid-4" id="shopGridV3">${list.length?list.map(shopCardV3).join(''):'<div class="empty" style="grid-column:1/-1">В этой коллекции пока нет предметов.</div>'}</div>`;
}
function shopCardV3(item){
 const owned=data.shop.owned.includes(item.id); const daily=item.id===shopDailyId(); const cost=shopCost(item);
 const locked=Number(data.xp||0)<cost && !owned;
 return `<article class="card shop-card-v3 ${daily?'daily':''}"><div class="shop-card-top"><span class="rarity rarity-${rarityClass(item.rarity)}">${esc(item.rarity)}</span>${daily?'<span class="tag sale">−'+data.shop.dailyDiscount+'%</span>':''}</div><div class="shop-card-icon">${item.icon}</div><div class="shop-cat">${shopCategory(item)}</div><h4>${esc(item.title)}</h4><p class="subtle">${esc(item.desc)}</p><div class="row between"><strong>${owned?'Получено':cost+' XP'}</strong><button type="button" class="btn ${owned?'secondary':''} small" data-shop-buy-v3="${item.id}">${owned?'Надеть':'Получить'}</button></div>${locked?`<div class="shop-need">Ещё ${cost-Math.floor(Number(data.xp)||0)} XP</div>`:''}</article>`;
}
function buyShopV3(id){
 ensureUXData(); const item=SHOP_CATALOG.find(x=>x.id===id); if(!item)return;
 if(data.shop.owned.includes(id)){equipShopV3(id);return;}
 const balance=Math.max(0,Math.floor(Number(data.xp)||0)); const cost=shopCost(item);
 if(balance<cost){toast(`Не хватает ${cost-balance} XP ♡`);return;}
 data.xp=balance-cost; data.shop.owned.push(id); data.shop.collectorStats[item.type]=(Number(data.shop.collectorStats[item.type])||0)+1;
 save();playSound('win');checkAchievements();toast(`Получено: ${item.title} ${item.icon}`);render();
}
function equipShopV3(id){
 ensureUXData(); const item=SHOP_CATALOG.find(x=>x.id===id); if(!item||!data.shop.owned.includes(id))return;
 if(item.type==='theme'){data.shop.equipped.theme=id;data.settings.theme=item.id==='theme-strawberry-shop'?'strawberry':data.settings.theme; if(item.id!=='theme-strawberry-shop')data.settings.theme=data.settings.theme||'pink';applyTheme();}
 else if(item.type==='pet'){if(!data.pet.accessories.includes(id))data.pet.accessories.push(id);else data.pet.accessories=data.pet.accessories.filter(x=>x!==id);data.shop.equipped.pet=data.pet.accessories.at(-1)||'';}
 else if(item.type==='petRoom'){data.pet.room=id;data.shop.equipped.petRoom=id;}
 else if(item.type==='petToy'){data.pet.toy=id;data.shop.equipped.petToy=id;}
 else data.shop.equipped[item.type]=data.shop.equipped[item.type]===id?'':id;
 save();playSound('click');toast(`${item.title} ${data.shop.equipped[item.type]===id?'используется':'снято'} ✨`);render();
}

// ---------- Compact products & favourites ----------
function productCompactCard(p){const r=productRating(p),fav=productIsFav(p),st=productStatus(p);return `<article class="card product-card-compact"><div class="product-mini-row"><div class="product-mini-image">${p.image?`<img src="${p.image}" alt="">`:'🧴'}</div><div class="product-mini-main"><div class="row between"><div><strong>${esc(p.name)}</strong><div class="subtle">${esc(p.brand||'Без бренда')} · ${esc(p.category||'Другое')}</div></div><button type="button" class="icon-btn" data-fav-product="${p.id}">${fav?'♥':'♡'}</button></div><div class="row wrap product-mini-meta"><span class="tag">⭐ ${r?r+'/10':'—'}</span><span class="tag">Использовано ${p.used||0}</span>${st?`<span class="tag">${st}</span>`:''}</div></div></div><details><summary>Подробнее</summary><div class="product-details"><p><strong>Заметки:</strong> ${esc(p.notes||'Пока нет заметок')}</p><div class="row wrap"><button type="button" class="btn secondary small" data-rate-product="${p.id}">Оценить</button><button type="button" class="btn ghost small" data-use-product="${p.id}">Использовала</button><button type="button" class="btn ghost small" data-edit-product="${p.id}">Изменить</button><button type="button" class="btn danger small" data-delete-product="${p.id}">Удалить</button></div></div></details></article>`}
function productsV3(){ensureUXData();const q=String(data.ui.productsSearch||'').trim().toLowerCase();const items=data.products.filter(p=>!q||`${p.name} ${p.brand} ${p.category} ${p.notes}`.toLowerCase().includes(q));return `<section class="card hero"><div class="row between wrap"><div><div class="label">Твоя косметичка</div><h1 style="font-family:Georgia,serif;margin:4px 0">🧴 Средства</h1><p>Ничего лишнего — только самое важное.</p></div><button class="btn" data-add-product data-action="addProduct">+ Добавить средство</button></div><div class="field" style="margin-top:14px"><label>Поиск</label><input id="productsSearchV3" value="${esc(data.ui.productsSearch||'')}" placeholder="Название, бренд, категория, заметки…"></div></section><div class="grid grid-3" style="margin-top:16px">${items.length?items.map(productCompactCard).join(''):'<div class="empty" style="grid-column:1/-1">Ничего не найдено ♡</div>'}</div>`}
function favoritesV3(){ensureUXData();const filter=data.ui.favoritesFilter||'all';const fav=data.products.filter(productIsFav);const filtered=fav.filter(p=>filter==='all'||productStatus(p)===filter);const rated=data.products.filter(p=>productRating(p)>0);const topUsed=[...data.products].sort((a,b)=>(b.used||0)-(a.used||0)).slice(0,3);const topRated=[...rated].sort((a,b)=>productRating(b)-productRating(a)).slice(0,3);return `<section class="card hero"><div class="row between wrap"><div><div class="label">Твоя коллекция</div><h1 style="font-family:Georgia,serif;margin:4px 0">♡ Мои любимчики</h1><p>Любимые средства, оценки и маленькая личная аналитика.</p></div><div class="circle" style="--p:${rated.length?Math.round((rated.reduce((s,p)=>s+productRating(p),0)/rated.length)*10):0}"><div class="inside"><span class="label">Средняя</span><strong>${rated.length?(rated.reduce((s,p)=>s+productRating(p),0)/rated.length).toFixed(1):'—'}</strong><span class="subtle">из 10</span></div></div></div></section><div class="chip-tabs" style="margin:14px 0">${[['all','Все'],['favorite','♡ Любимое'],['works','💗 Работает'],['repeat','🤍 Повторить'],['bad','🚫 Не подошло']].map(([k,l])=>`<button type="button" class="${filter===k?'active':''}" data-fav-filter="${k}">${l}</button>`).join('')}</div><section class="card"><div class="row between"><h3 class="section-title">🏆 ТОП СРЕДСТВ</h3><span class="tag">${fav.length} любимчиков</span></div><div class="top-product-grid"><div class="item"><strong>🥇 Любимое по использованию</strong><p>${topUsed[0]?esc(topUsed[0].name):'—'}</p></div><div class="item"><strong>🥈 Самая высокая оценка</strong><p>${topRated[0]?`${esc(topRated[0].name)} · ${productRating(topRated[0])}/10`:'—'}</p></div><div class="item"><strong>🥉 Самое используемое</strong><p>${topUsed[0]?`${esc(topUsed[0].name)} · ${topUsed[0].used||0} раз`:'—'}</p></div></div></section><section class="card" style="margin-top:16px"><div class="grid grid-3">${filtered.length?filtered.map(productCompactCard).join(''):'<div class="empty" style="grid-column:1/-1">Здесь пока ничего нет ♡</div>'}</div></section>`}

// ---------- Reports / PDF ----------
function monthlyReportTextV3(){
 const month=statsRange(30); const all=month.reduce((a,x)=>a+x.all.length,0); const done=month.reduce((a,x)=>a+x.done.length,0); const score=pct(done,all); const rated=data.photos.filter(p=>Number(p.overall||p.score||0)>0); const avgPhoto=rated.length?(rated.reduce((s,p)=>s+Number(p.overall||p.score||0),0)/rated.length).toFixed(1):'—';
 return {score,total:done,perfect:month.filter(x=>x.p===100).length,streak:currentStreak(),best:bestStreak(),xp:Number(data.xp||0),level:data.level,photos:data.photos.length,avgPhoto,pet:data.pet.name,petStage:data.pet.stage,glow:glowScore()};
}
function printMonthlyPdf(){
 ensureUXData(); const r=monthlyReportTextV3(); const name=esc(data.settings.name||'Beauty');
 const w=window.open('','_blank','width=900,height=1000'); if(!w){toast('Браузер заблокировал окно печати. Разреши всплывающие окна ♡');return}
 w.document.write(`<!doctype html><html lang="ru"><head><meta charset="utf-8"><title>Мой Бьюти-дневник — отчёт</title><style>body{font-family:Arial,sans-serif;color:#3f3940;margin:0;background:#fff7fb}.page{max-width:820px;margin:0 auto;padding:42px}.hero{padding:30px;border-radius:28px;background:linear-gradient(135deg,#fff0f6,#f5efff);border:1px solid #eadde6}.logo{font-size:28px;font-weight:700}.muted{color:#8f858e}.grid{display:grid;grid-template-columns:repeat(2,1fr);gap:16px;margin-top:18px}.card{border:1px solid #eadfe6;border-radius:22px;padding:20px;background:#fff}.kpi{font-size:34px;font-weight:800}.bar{height:12px;background:#f0e8ee;border-radius:99px;overflow:hidden}.bar i{display:block;height:100%;background:linear-gradient(90deg,#e889ad,#caa8e8);width:${r.score}%}.quote{font-size:18px;line-height:1.5}.footer{margin-top:28px;color:#998c94;font-size:12px}@media print{body{background:#fff}.page{padding:0}.no-print{display:none!important}}</style><style id="mjx-style">
.mjx-shell{display:grid;gap:16px}.mjx-grid{display:grid;gap:16px}.mjx-grid-2{grid-template-columns:repeat(2,minmax(0,1fr))}.mjx-grid-3{grid-template-columns:repeat(3,minmax(0,1fr))}.mjx-grid-4{grid-template-columns:repeat(4,minmax(0,1fr))}
.mjx-shop-item{position:relative;overflow:hidden;transition:transform .22s ease,box-shadow .22s ease}.mjx-shop-item:hover{transform:translateY(-4px)}
.mjx-art{height:150px;border-radius:22px;background:linear-gradient(145deg,var(--surface2),var(--surface));display:grid;place-items:center;overflow:hidden;border:1px solid var(--border);margin-bottom:12px}.mjx-art img{width:100%;height:100%;object-fit:cover}.mjx-art .emoji{font-size:64px;filter:drop-shadow(0 10px 12px rgba(0,0,0,.08))}
.mjx-rarity{font-size:11px;padding:6px 9px;border-radius:999px;background:var(--surface2);border:1px solid var(--border)}
.mjx-collection{overflow:hidden}.mjx-collection-head{padding:18px;border-radius:22px;background:linear-gradient(135deg,var(--surface),var(--surface2));position:relative}.mjx-collection-head:after{content:'✦';position:absolute;right:20px;top:12px;font-size:42px;opacity:.12}.mjx-collection-progress{height:8px;border-radius:99px;background:rgba(130,100,120,.12);overflow:hidden}.mjx-collection-progress i{display:block;height:100%;border-radius:inherit;background:linear-gradient(90deg,var(--primary),var(--accent));transition:width .5s ease}
.mjx-box{min-height:250px;display:grid;place-items:center;text-align:center;background:radial-gradient(circle at 50% 35%,var(--surface2),var(--surface));border-radius:30px;border:1px solid var(--border);position:relative;overflow:hidden}.mjx-box .gift{font-size:96px;animation:mjxFloat 2.8s ease-in-out infinite}.mjx-box.open .gift{animation:mjxPop .5s ease}.mjx-spark{position:absolute;inset:0;pointer-events:none}.mjx-spark span{position:absolute;font-size:18px;opacity:0;animation:mjxSpark 1.2s ease forwards}.mjx-spark span:nth-child(1){left:18%;top:28%}.mjx-spark span:nth-child(2){left:74%;top:22%;animation-delay:.08s}.mjx-spark span:nth-child(3){left:28%;top:68%;animation-delay:.16s}.mjx-spark span:nth-child(4){left:68%;top:66%;animation-delay:.24s}
@keyframes mjxFloat{0%,100%{transform:translateY(0) rotate(-2deg)}50%{transform:translateY(-7px) rotate(2deg)}}@keyframes mjxPop{0%{transform:scale(1)}55%{transform:scale(1.16) rotate(-5deg)}100%{transform:scale(1)}}@keyframes mjxSpark{0%{opacity:0;transform:scale(.6) translateY(8px)}30%{opacity:1}100%{opacity:0;transform:scale(1.25) translateY(-28px)}}
.mjx-chat{display:grid;gap:10px;max-height:520px;overflow:auto;padding:8px}.mjx-msg{max-width:84%;padding:12px 14px;border-radius:18px;line-height:1.55}.mjx-msg.user{justify-self:end;background:var(--primary);color:#fff;border-bottom-right-radius:7px}.mjx-msg.bot{justify-self:start;background:var(--surface2);border:1px solid var(--border);border-bottom-left-radius:7px}.mjx-ingredient{display:flex;gap:10px;align-items:flex-start;padding:12px;border:1px solid var(--border);border-radius:16px;background:var(--surface)}.mjx-dot{width:12px;height:12px;border-radius:50%;margin-top:5px;flex:0 0 auto}.mjx-dot.green{background:#62b58a}.mjx-dot.yellow{background:#e2ba63}.mjx-dot.red{background:#d97887}.mjx-dot.gray{background:#a7a0a7}.mjx-filter{display:flex;gap:8px;flex-wrap:wrap}.mjx-filter button{background:var(--surface);border:1px solid var(--border);padding:8px 11px;border-radius:999px}.mjx-filter button.active{background:var(--surface2);border-color:var(--primary2)}
.mjx-chart{height:270px;border:1px solid var(--border);border-radius:22px;background:linear-gradient(180deg,var(--surface),var(--surface2));padding:12px}.mjx-chart svg{width:100%;height:100%;display:block}.mjx-stat-big{font-size:36px;font-weight:800}.mjx-measure{display:grid;grid-template-columns:1.1fr .8fr .8fr auto;gap:10px;align-items:end}.mjx-hair-ring{width:150px;height:150px;border-radius:50%;display:grid;place-items:center;background:conic-gradient(var(--primary) calc(var(--p)*1%),#eee5ea 0)}.mjx-hair-ring:after{content:"";position:absolute}.mjx-hair-ring .inside{width:116px;height:116px;border-radius:50%;display:grid;place-items:center;background:var(--surface);text-align:center}.mjx-furniture{display:grid;grid-template-columns:repeat(4,1fr);gap:10px}.mjx-furniture button{min-height:96px;border:1px solid var(--border);border-radius:18px;background:var(--surface);display:grid;place-items:center;padding:8px}.mjx-furniture button.active{outline:2px solid var(--primary2)}
.mjx-season-banner{position:relative;overflow:hidden;border-radius:26px;padding:22px;background:linear-gradient(135deg,var(--surface2),var(--surface));border:1px solid var(--border)}
.mjx-season-banner:after{content:'✦';position:absolute;right:22px;top:10px;font-size:70px;opacity:.08}.mjx-lesson{cursor:pointer;transition:transform .18s ease}.mjx-lesson:hover{transform:translateY(-2px)}.mjx-source{font-size:11px;color:var(--muted)}
.mjx-quick-sheet{position:fixed;inset:0;background:rgba(35,24,31,.36);backdrop-filter:blur(8px);display:flex;align-items:center;justify-content:center;padding:18px;z-index:300}.mjx-quick-panel{width:min(360px,100%);max-height:min(520px,80vh);overflow:auto;background:var(--surface);border-radius:22px;padding:16px;box-shadow:0 22px 70px rgba(0,0,0,.22);animation:mjxSheet .2s ease}.mjx-quick-grid{display:grid;grid-template-columns:repeat(2,minmax(0,1fr));gap:8px}.mjx-quick-grid button{padding:11px;border-radius:14px;text-align:left;background:var(--surface2);border:1px solid var(--border)}.mjx-quick-grid button strong{font-size:13px}.mjx-quick-grid button .subtle{font-size:11px}@keyframes mjxSheet{from{transform:translateY(10px) scale(.97);opacity:.3}to{transform:translateY(0) scale(1);opacity:1}}
@media(max-width:900px){.mjx-grid-4,.mjx-grid-3{grid-template-columns:repeat(2,minmax(0,1fr))}.mjx-measure{grid-template-columns:1fr 1fr}.mjx-furniture{grid-template-columns:repeat(3,1fr)}}@media(max-width:650px){.mjx-grid-2,.mjx-grid-3,.mjx-grid-4{grid-template-columns:1fr}.mjx-quick-grid{grid-template-columns:1fr}.mjx-measure{grid-template-columns:1fr}.mjx-furniture{grid-template-columns:repeat(2,1fr)}}
</style>
</head><body><div class="page"><section class="hero"><div class="logo">Мой Бьюти-дневник ♡</div><h1>Месячный бьюти-отчёт</h1><p class="muted">${name} · ${fmtDate(todayKey())}</p><p class="quote">✨ Ты продолжаешь заботиться о себе — и это уже большая победа.</p></section><div class="grid"><div class="card"><div class="muted">Уход за 30 дней</div><div class="kpi">${r.score}%</div><div class="bar"><i></i></div></div><div class="card"><div class="muted">Показатель сияния</div><div class="kpi">${r.glow}</div><div class="muted">на основе регулярности, ухода, оценок, фото, streak и целей</div></div><div class="card"><div class="muted">Streak</div><div class="kpi">🔥 ${r.streak}</div><div class="muted">Лучший: ${r.best} дней</div></div><div class="card"><div class="muted">Уровень</div><div class="kpi">${r.level}</div><div class="muted">${r.xp} XP</div></div><div class="card"><div class="muted">Фото прогресса</div><div class="kpi">${r.photos}</div><div class="muted">Средняя оценка: ${r.avgPhoto}/10</div></div><div class="card"><div class="muted">Питомец</div><div class="kpi">🐾 ${esc(r.pet)}</div><div class="muted">Стадия ${r.petStage}/10</div></div></div><section class="card" style="margin-top:18px"><h2>Твой месяц в цифрах</h2><p>Выполнено процедур: <strong>${r.total}</strong></p><p>Идеальных дней: <strong>${r.perfect}</strong></p><p>Фотографий: <strong>${r.photos}</strong></p><p>Текущий уровень: <strong>${r.level}</strong></p><p>Общий XP: <strong>${r.xp}</strong></p></section><p class="footer">Сделано в Мой Бьюти-дневник ♡ · Личный локальный отчёт</p><button class="no-print" onclick="window.print()" style="margin-top:24px;padding:12px 18px;border:0;border-radius:14px;background:#e889ad;color:#fff">Сохранить / распечатать как PDF</button></div><${'script'}>setTimeout(()=>window.print(),500)</${'script'}>






</body></html>`);w.document.close();
}
/* SHOP ADD-ON: elf frame + 3 shop-only themes */
(function(){
  const addShopOnlyItem=item=>{
    if(typeof SHOP_CATALOG!=='undefined' && !SHOP_CATALOG.some(x=>x.id===item.id)) SHOP_CATALOG.push(item);
  };
  addShopOnlyItem({id:'frame-elf-garden',type:'frame',title:'🧝🏻‍♀️ Рамка «Эльфийский лес»',icon:'🧝🏻‍♀️',cost:580,rarity:'Эпический',desc:'🧝🏻‍♀️🍃🌿 Нежная зелёная рамка с эльфийкой и лесными листочками.',collection:'Elf Garden',shopAvatarFrame:true,frameId:'elf-garden',shopOnly:true});
  addShopOnlyItem({id:'theme-vampire-silver-shop',type:'theme',title:'🩸 Вампирская — красное серебро',icon:'🩸',cost:900,rarity:'Легендарный',desc:'🩸🥀 Серебряные поверхности и глубокий кроваво-красный акцент.',shopOnly:true,vars:{'--bg':'#f4f1f3','--surface':'#ffffff','--surface2':'#ebe6e9','--text':'#321f25','--muted':'#806f76','--primary':'#a51f38','--primary2':'#d6b9c1','--accent':'#7f8994','--success':'#789b88','--border':'rgba(55,35,42,.14)'}});
  addShopOnlyItem({id:'theme-pearl-sea-shop',type:'theme',title:'🫧 Жемчужный русал',icon:'🦪',cost:820,rarity:'Легендарный',desc:'🤍🫧 Жемчуг, молочно-белые поверхности и нежный морской оттенок.',shopOnly:true,vars:{'--bg':'#f4fbfb','--surface':'#ffffff','--surface2':'#e5f3f3','--text':'#294447','--muted':'#789093','--primary':'#78bfc1','--primary2':'#c5e5e3','--accent':'#d8c7a8','--success':'#79ad98','--border':'rgba(57,104,108,.13)'}});
  addShopOnlyItem({id:'theme-gentle-forest-shop',type:'theme',title:'🌿 Нежный лес',icon:'🌱',cost:780,rarity:'Легендарный',desc:'🌿🍃 Коричневые древесные оттенки и мягкий салатово-зелёный.',shopOnly:true,vars:{'--bg':'#f5f6ec','--surface':'#fffef8','--surface2':'#e7ecd8','--text':'#3d4931','--muted':'#7f896d','--primary':'#78a65b','--primary2':'#c7dcae','--accent':'#8b6547','--success':'#72a47a','--border':'rgba(72,91,54,.14)'}});

  const shopOnlyIds=new Set(['frame-elf-garden','theme-vampire-silver-shop','theme-pearl-sea-shop','theme-gentle-forest-shop']);
  window.__beautyShopOnlyIds=shopOnlyIds;

  // Add the frame to the existing avatar picker only after purchase.
  if(typeof getAvatarFrames==='function'){
    const oldGetAvatarFrames=getAvatarFrames;
    window.getAvatarFrames=function(){
      const frames=oldGetAvatarFrames();
      if(data?.shop?.owned?.includes('frame-elf-garden') && !frames.some(x=>x[0]==='elf-garden')) frames.push(['elf-garden','🧝🏻‍♀️','Эльфийский лес']);
      return frames;
    };
    if(typeof AVATAR_FRAMES!=='undefined') AVATAR_FRAMES=window.getAvatarFrames();
  }
})();


function reportsV3(){const base=monthlyReportTextV3();return `<section class="card hero"><div class="row between wrap"><div><div class="label">Твой красивый итог</div><h1 style="font-family:Georgia,serif;margin:4px 0">📊 Отчёты</h1><p>Месячный бьюти-отчёт с цифрами, Показатель сияния и прогрессом.</p></div><button class="btn" data-print-pdf>Экспорт в PDF</button></div></section><div class="grid grid-4" style="margin-top:16px"><div class="card"><div class="label">Уход</div><div class="kpi">${base.score}%</div></div><div class="card"><div class="label">Glow</div><div class="kpi">${base.glow}</div></div><div class="card"><div class="label">Streak</div><div class="kpi">🔥 ${base.streak}</div></div><div class="card"><div class="label">XP</div><div class="kpi">${base.xp}</div></div></div><div class="card" style="margin-top:16px"><h3 class="section-title">💗 Месяц в цифрах</h3><div class="grid grid-2"><div class="item">Процедуры: <strong>${base.total}</strong></div><div class="item">Идеальные дни: <strong>${base.perfect}</strong></div><div class="item">Фото: <strong>${base.photos}</strong></div><div class="item">Оценка фото: <strong>${base.avgPhoto}/10</strong></div></div></div>`}

// ---------- UI transitions ----------
const uxStyle=document.createElement('style');uxStyle.textContent=`
#page{animation:beautyPageIn .20s ease both}.card,.item,.zone-card{animation:beautyCardIn .22s ease both}.grid > :nth-child(2){animation-delay:.02s}.grid > :nth-child(3){animation-delay:.04s}.grid > :nth-child(4){animation-delay:.06s}.grid > :nth-child(5){animation-delay:.08s}.grid > :nth-child(6){animation-delay:.1s}
@keyframes beautyPageIn{from{opacity:0;transform:translateY(7px)}to{opacity:1;transform:none}}@keyframes beautyCardIn{from{opacity:0;transform:translateY(8px)}to{opacity:1;transform:none}}
.progress i,.circle{transition:width .25s ease,transform .25s ease,background-position .25s ease}.btn,.icon-btn,.zone-card,.shop-card-v3{transition:transform .18s ease,box-shadow .18s ease,opacity .18s ease}.btn:hover,.icon-btn:hover,.zone-card:hover,.shop-card-v3:hover{transform:translateY(-2px)}
.skeleton{background:linear-gradient(90deg,var(--surface2) 25%,rgba(255,255,255,.65) 37%,var(--surface2) 63%);background-size:400% 100%;animation:skeleton 1.1s ease-in-out infinite;border-radius:18px;min-height:110px}@keyframes skeleton{0%{background-position:100% 50%}100%{background-position:0 50%}}
.zone-grid{display:grid;grid-template-columns:repeat(6,1fr);gap:12px;margin-top:16px}.zone-card{border:1px solid var(--border);border-radius:22px;background:var(--surface);color:var(--text);padding:16px;text-align:left;box-shadow:var(--shadow)}.zone-card.active{outline:2px solid var(--primary)}.zone-card.locked{opacity:.55;filter:saturate(.65)}.zone-icon{font-size:38px}.zone-name{font-weight:700;margin-top:8px;color:var(--text)}.zone-label{font-size:12px;color:var(--muted);margin-top:2px}.zone-lock{font-size:12px;color:var(--muted);margin-top:8px}.pet-unlock-note{margin-top:14px;padding:12px 14px;border-radius:16px;background:var(--surface2)}
.pet-world-stage{overflow:hidden}.pet-world-v3 .pet-scene{min-height:0}.world-room{min-height:330px;margin-top:14px;border-radius:28px;position:relative;overflow:hidden;display:grid;place-items:center;box-shadow:inset 0 0 0 1px rgba(255,255,255,.45)}.world-pink{background:radial-gradient(circle at 20% 20%,#ffeef5 0 25%,transparent 26%),linear-gradient(135deg,#ffe7f0,#fff8fb 60%,#f6edf8)}.world-lavender{background:linear-gradient(135deg,#eee9ff,#fbf8ff 60%,#f2ecff)}.world-garden{background:radial-gradient(circle at 20% 18%,#ffffff 0 7%,transparent 8%),radial-gradient(circle at 70% 30%,#fff 0 5%,transparent 6%),linear-gradient(135deg,#eaf9ef,#f7fff9)}.world-bath{background:linear-gradient(135deg,#eaf6ff,#f9fbff 55%,#eaf6f4)}.world-wardrobe{background:linear-gradient(135deg,#fff0f6,#fff 55%,#f7eefc)}.world-toys{background:linear-gradient(135deg,#fff9e8,#fff 55%,#ffeef7)}.world-pet{font-size:120px;filter:drop-shadow(0 16px 20px rgba(80,50,70,.16));z-index:2}.world-decor{position:absolute;top:22px;left:22px;right:22px;font-size:28px;display:flex;justify-content:space-between;opacity:.8}.world-bed,.world-bath,.world-wardrobe-icon{position:absolute;font-size:92px;bottom:24px;left:24px;opacity:.9}.world-caption{position:absolute;bottom:18px;right:20px;padding:10px 14px;border-radius:14px;background:rgba(255,255,255,.72);backdrop-filter:blur(8px);font-size:12px}.pet-mini-status{display:flex;gap:8px;flex-wrap:wrap}.pet-mini-status span{padding:8px 11px;border-radius:999px;background:var(--surface2);font-size:12px}
.shop-daily{background:linear-gradient(135deg,var(--surface2),var(--surface))}.shop-daily-price{display:flex;flex-direction:column;align-items:flex-end}.shop-daily-price .old{text-decoration:line-through;color:var(--muted);font-size:12px}.shop-daily-price strong{font-size:26px}.sale{background:var(--primary);color:#fff}.shop-card-v3{position:relative;overflow:hidden}.shop-card-v3.daily{box-shadow:0 16px 40px rgba(232,137,173,.18)}.shop-card-top{display:flex;justify-content:space-between;align-items:center}.shop-card-icon{height:150px;display:grid;place-items:center;font-size:72px;background:linear-gradient(135deg,var(--surface2),var(--surface));border-radius:22px;margin:12px 0}.shop-cat{font-size:11px;color:var(--muted);text-transform:uppercase;letter-spacing:.08em}.shop-card-v3 h4{font-family:Georgia,serif;margin:7px 0}.shop-need{font-size:12px;color:var(--danger);margin-top:8px}.rarity{padding:5px 9px;border-radius:999px;font-size:11px;background:var(--surface2)}.rarity-редкий{color:#7b5fd0}.rarity-эпический{color:#b15ea8}.rarity-легендарный{color:#a96b1f}.rarity-секретный{color:#6c4c80;font-weight:700}
.product-card-compact{padding:14px}.product-mini-row{display:flex;gap:12px}.product-mini-image{width:74px;height:74px;border-radius:18px;background:var(--surface2);display:grid;place-items:center;overflow:hidden;flex:none;font-size:32px}.product-mini-image img{width:100%;height:100%;object-fit:cover}.product-mini-main{min-width:0;flex:1}.product-mini-meta{margin-top:9px}.product-details{padding-top:10px;border-top:1px dashed var(--border);margin-top:10px}.product-card-compact details summary{cursor:pointer;color:var(--primary);font-size:13px}.top-product-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:12px}
@media(max-width:1100px){.zone-grid{grid-template-columns:repeat(3,1fr)}}@media(max-width:720px){.zone-grid{grid-template-columns:repeat(2,1fr)}.top-product-grid{grid-template-columns:1fr}.world-room{min-height:270px}.world-pet{font-size:92px}.world-bed,.world-bath,.world-wardrobe-icon{font-size:68px}}
@media(prefers-reduced-motion:reduce){#page,.card,.item,.zone-card{animation:none!important;transition:none!important}.progress i,.circle{transition:none!important}}
@media print{body{background:#fff!important}.sidebar,.topbar,.bottom-nav,.no-print{display:none!important}.main{display:block!important}.content{padding:0!important}.card{box-shadow:none!important;border:1px solid #ddd!important;break-inside:avoid}}
`;
document.head.appendChild(uxStyle);

function articlesPageV3(){ensureUXData();return `<section class="card hero"><div class="row between wrap"><div><div class="label">Читаем по делу</div><h1 style="font-family:Georgia,serif;margin:4px 0">📖 Мини-статьи и интернет</h1><p>Локальные мини-статьи + свежая подборка под твой профиль.</p></div><button class="btn" id="refreshArticlesV3">↻ Обновить</button></div></section><div class="grid grid-2" style="margin-top:16px">${articles.map(a=>`<article class="card article" data-article="${a.id}"><span class="tag">${a.tag}</span><h4>${esc(a.title)}</h4><p>${esc(a.text.slice(0,170))}…</p><button class="btn secondary small" style="margin-top:10px">Читать</button></article>`).join('')}</div><section class="card" style="margin-top:16px"><div class="row between"><h3 class="section-title">🌐 Свежая подборка</h3><span class="tag">${data.webArticles.length?data.webArticles.length+' материалов':'Обновляется ежедневно'}</span></div><div class="grid grid-2" id="webArticlesGridV3">${data.webArticles.length?data.webArticles.map(webArticleCard).join(''):'<div class="skeleton"></div><div class="skeleton"></div>'}</div></section>`}

// ---------- Override pages ----------
const __oldRenderPageV3=renderPage;
renderPage=function(route){
  ensureUXData();
  const p=document.getElementById('page');
  const map={home:homePage,today:todayPage,care:carePage,products:productsV3,favorites:favoritesV3,shop:shopPageV3,calendar:calendarPage,progress:progressPage,achievements:achievementsPage,goals:goalsPage,journal:journalPage,pet:petWorldPage,challenges:challengesPage,tips:tipsPage,articles:articlesPageV3,reports:reportsV3,settings:settingsPage,luck:luckPage};
  p.innerHTML=(map[route]||homePage)();
  bindBigPage(route);
  if(route==='tips'||route==='articles'){
    const has=data.webArticles&&data.webArticles.length&&data.webArticlesDate===todayKey();
    if(!has){setTimeout(()=>{const grid=document.getElementById(route==='articles'?'webArticlesGridV3':'webTipsGrid');if(grid)grid.innerHTML='<div class="skeleton"></div><div class="skeleton"></div>'},0);fetchWebArticles(false).then(()=>{if(location.hash.replace('#','')===route){renderPage(route)}})}
  }
};

// use v3 shop filter / pet zone / PDF buttons after page render
const __oldBindBigPageV3=bindBigPage;
bindBigPage=function(route){
  try{__oldBindBigPageV3(route)}catch{}
  document.querySelectorAll('[data-shop-filter-v3]').forEach(b=>b.onclick=()=>{__shopFilter=b.dataset.shopFilterV3;renderPage('shop')});
  document.querySelectorAll('[data-shop-buy-v3]').forEach(b=>b.onclick=()=>buyShopV3(b.dataset.shopBuyV3));
  document.querySelectorAll('[data-pet-zone]').forEach(b=>b.onclick=()=>setPetZone(b.dataset.petZone));
  document.querySelectorAll('[data-fav-filter]').forEach(b=>b.onclick=()=>{ensureUXData();data.ui.favoritesFilter=b.dataset.favFilter;save();renderPage('favorites')});
  document.querySelectorAll('[data-print-pdf]').forEach(b=>b.onclick=printMonthlyPdf);
  document.getElementById('refreshArticlesV3')?.addEventListener('click',()=>fetchWebArticles(true).then(()=>renderPage('articles')));
  document.querySelectorAll('[data-pet-feed]').forEach(b=>b.onclick=petFeed);
  document.querySelectorAll('[data-pet-play]').forEach(b=>b.onclick=petPlay);
  document.querySelectorAll('[data-pet-rest]').forEach(b=>b.onclick=petRest);
  const ps=document.getElementById('productsSearchV3'); if(ps){ps.oninput=()=>{ensureUXData();data.ui.productsSearch=ps.value;renderPage('products');const np=document.getElementById('productsSearchV3');if(np){np.focus();np.setSelectionRange(np.value.length,np.value.length)}}}
};

// safer buy override for legacy shop button names too
buyShopV2=buyShopV3;

// ---------- Keep original theme picker, now with new themes ----------
const originalSettingsPageV3=settingsPage;
settingsPage=function(){return originalSettingsPageV3()};

// ---------- Final render refresh ----------
try{ensureUXData();applyTheme();render()}catch(err){console.error('UX upgrade error',err)}

// ================= PREMIUM UX 2.0 LAYER =================
// These additions intentionally sit on top of the existing application so all existing data and flows remain intact.

function ensurePremiumData(){
  data.settings=data.settings||{};
  data.settings.cardStyle=data.settings.cardStyle||'soft';
  data.settings.density=data.settings.density||'comfortable';
  data.settings.motion=data.settings.motion||'full';
  data.settings.seasonalAtmosphere=data.settings.seasonalAtmosphere!==false;
  data.settings.privacyMode=data.settings.privacyMode||false;
  data.settings.showPetWidget=data.settings.showPetWidget!==false;
  data.settings.uvEnabled=data.settings.uvEnabled!==false;
  data.settings.lastSavedAt=data.settings.lastSavedAt||Date.now();
  if(!Array.isArray(data.events)) data.events=[];
  if(!data.pet) data.pet=blankData().pet;
}

const premiumThemes={
  strawberry:{name:'Клубничный зефир',vars:{'--bg':'#fff7f8','--surface':'#fffdfc','--surface2':'#ffedf1','--text':'#3d3539','--muted':'#94858b','--primary':'#dc7f9b','--primary2':'#f4becb','--accent':'#c9addf','--success':'#9ccbb8'}},
  minimal:{name:'Минималистичная',vars:{'--bg':'#f8f7f5','--surface':'#fffefd','--surface2':'#f1efec','--text':'#2f2d2b','--muted':'#8c8883','--primary':'#8b7770','--primary2':'#d8ccc6','--accent':'#ad9a91','--success':'#9cb7a9'}},
  midnight2:{name:'Полуночная красота',vars:{'--bg':'#171519','--surface':'#211e23','--surface2':'#29242c','--text':'#f3edf2','--muted':'#b9adb7','--primary':'#c79ccf','--primary2':'#5a465e','--accent':'#8e7bb6','--success':'#82b09e','--border':'rgba(255,255,255,.08)'}}
};
Object.assign(themes,premiumThemes);

function applyPremiumTheme(){
  const key=data.settings.theme||'pink';
  const t=themes[key]||themes.pink;
  const defaults={'--bg':'#fff9fb','--surface':'#ffffff','--surface2':'#fff1f6','--text':'#3e343a','--muted':'#8f858e','--primary':'#e889ad','--primary2':'#f7c2d6','--accent':'#caa8e8','--success':'#8ecdb8','--border':'rgba(74,55,66,.1)'};
  for(const [k,v] of Object.entries(defaults)) document.documentElement.style.setProperty(k,v);
  for(const [k,v] of Object.entries(t.vars||{})) document.documentElement.style.setProperty(k,v);
  document.documentElement.dataset.cardStyle=data.settings.cardStyle;
  document.documentElement.dataset.density=data.settings.density;
  document.documentElement.dataset.motion=data.settings.motion;
  document.documentElement.dataset.seasonal=data.settings.seasonalAtmosphere?'on':'off';
}

const premiumWeatherCodes={};
function weatherUvLabel(uv){
  const n=Number(uv);
  if(!Number.isFinite(n)) return null;
  if(n>=8) return {level:'Очень высокий',icon:'☀️',tone:'danger'};
  if(n>=6) return {level:'Высокий',icon:'☀️',tone:'warn'};
  if(n>=3) return {level:'Умеренный',icon:'🌤️',tone:'normal'};
  return {level:'Низкий',icon:'☁️',tone:'calm'};
}
function weatherAdvice(){
  const w=data.settings?.weather;
  if(!w) return {
    title:'Погода пока не настроена',
    text:'Укажи город в настройках — приложение будет подстраивать рекомендации под температуру, влажность, ветер, осадки и UV.',
    why:'После обновления погоды рекомендации пересчитываются автоматически.',
    chips:[],tips:[],evening:[],home:[],outdoor:[],alerts:[],personal:[],forecast:{today:null,tomorrow:null},feelsLike:null,rainSoon:null,trend:null
  };

  const temp=Number(w.temp), humidity=Number(w.humidity), wind=Number(w.wind), uvN=Number(w.uv);
  const desc=String(w.description||'').toLowerCase();
  const chips=[], tips=[], evening=[], home=[], outdoor=[], alerts=[], personal=[];
  const add=(icon,text)=>tips.push({icon,text});
  const addEvening=(icon,text)=>evening.push({icon,text});
  const addHome=(icon,text)=>home.push({icon,text});
  const addOutdoor=(icon,text)=>outdoor.push({icon,text});
  const addAlert=(icon,text)=>alerts.push({icon,text});
  const addPersonal=(icon,text)=>personal.push({icon,text});

  const uv=weatherUvLabel(w.uv);
  if(uv) chips.push(`${uv.icon} UV: ${uv.level}`);
  if(Number.isFinite(humidity)) chips.push(`💧 Влажность ${humidity}%`);
  if(Number.isFinite(wind)) chips.push(`💨 Ветер ${wind} км/ч`);
  chips.push(`🌡️ ${Number.isFinite(temp)?temp:'—'}°C`);
  if(Number.isFinite(Number(w.feelsLike)) && Number(w.feelsLike)!==temp) chips.push(`🤔 Ощущается как ${Math.round(Number(w.feelsLike))}°C`);
  if(Number.isFinite(Number(w.rainSoon))) chips.push(`☔ Дождь скоро: ${Math.round(Number(w.rainSoon))}%`);

  /* Скорый дождь: предупреждаем заранее, а не постфактум, если сейчас сухо, но осадки вероятны. */
  if(Number.isFinite(Number(w.rainSoon)) && Number(w.rainSoon)>=55 && !(desc.includes('дожд')||desc.includes('морос'))){
    addAlert('☔',`Вероятность дождя в ближайшие часы ${Math.round(Number(w.rainSoon))}% — если собираешься гулять, заранее защити волосы (капюшон/зонт) и не планируй сложную укладку.`);
    addAlert('🌂','Если дождь начнётся неожиданно на длинной прогулке, лёгкий компактный зонт в сумке экономит и время, и укладку.');
  }

  /* Температура: отдельные диапазоны, а не одно правило «холодно/жарко». */
  if(temp<=-10){
    add('🛡️','Кожа: перед выходом нанеси привычный защитный крем на щёки, нос и другие открытые зоны; не экспериментируй с большим количеством активов.');
    add('💋','Губы: используй плотный защитный бальзам и обновляй его после еды/питья.');
    add('🫧','Очищение: вечером выбирай мягкое средство и не используй горячую воду для умывания.');
    add('🎀','Волосы: убери длину от воротника и шарфа, чтобы уменьшить трение и спутывание.');
    addAlert('❄️','Экстремальный холод: не выходи с влажными волосами и не делай интенсивные процедуры непосредственно перед выходом.');
    addAlert('🥶','Резкий перепад температур (улица/помещение) в мороз — дополнительный стресс для кожи; сведи количество таких переходов к минимуму, если это возможно.');
    add('🧤','Руки: плотный крем для рук перед выходом — кожа рук на морозе сохнет так же быстро, как лицо.');
    add('👃','Нос и уши: тонкая кожа здесь особенно уязвима к морозу — не забывай про них при нанесении защитного крема.');
    add('🧣','Шарф или горловина: закрывай нижнюю часть лица на сильном морозе, но старайся не дышать прямо в ткань — влага от дыхания усиливает раздражение.');
    add('🚪','После возвращения домой: дай коже 10–15 минут адаптироваться к тёплому воздуху, прежде чем наносить активный уход.');
    addEvening('🌙','Вечером: мягкое очищение → увлажнение/восстановление барьера → бальзам для губ.');
    addEvening('🎀','Для волос: кондиционер или маска на длину, особенно если она стала сухой и электризуется.');
    addEvening('💧','Вечером стоит также восполнить влагу самому организму — тёплое питьё поддерживает и общее самочувствие, и состояние кожи.');
    addEvening('🧤','Перед сном можно нанести более плотный крем на руки и надеть хлопковые перчатки — так кожа рук восстанавливается заметнее.');
  }else if(temp<=0){
    add('🛡️','Кожа: защитный крем на открытые участки перед улицей, особенно если лицо быстро краснеет или стягивается.');
    add('💋','Губы: защитный бальзам до выхода и после возвращения домой.');
    add('🎀','Волосы: не выходи с влажной длиной; при трении о шарф лучше собрать её мягко.');
    add('🫧','После улицы: не отогревай лицо очень горячей водой — дай коже постепенно вернуться к комфортной температуре.');
    add('🧤','Руки: перчатки на улице и питательный крем после — кожа рук так же чувствительна к холоду, как и лицо.');
    add('🌬️','Если поднимается ветер, добавь дополнительный слой защиты на скулы и нос — именно эти зоны обычно продувает сильнее всего.');
    add('🚿','После прогулки: не умывайся сразу же горячей водой — дай коже пару минут привыкнуть к комнатной температуре.');
    add('👄','Питьевой режим: в холодное время легко забыть пить достаточно воды — это тоже сказывается на ощущении кожи.');
    addEvening('🌙','Вечером: мягкое очищение и спокойный увлажняющий уход без лишнего наслаивания активов.');
    addEvening('🧴','Вечером можно добавить более насыщенный слой ухода, чем обычно, если кожа весь день провела на холоде.');
  }else if(temp<=5){
    add('🛡️','Кожа: комфортный крем особенно уместен на щеках, вокруг носа и других сухих участках.');
    add('💋','Губы: держи бальзам под рукой — холод и ветер быстро усиливают сухость.');
    add('🫧','Очищение: мягкое, без скрабирования и лишнего трения.');
    add('🎀','Волосы: защищай длину от одежды и резких перепадов температуры.');
    add('🧤','Руки и локти: в прохладную погоду эти зоны часто незаслуженно выпадают из рутины — не забывай про них.');
    add('🌬️','При ветре добавь бальзам на открытые участки перед выходом, а не только по факту стянутости.');
    add('☕','Тёплые напитки — приятный бонус в прохладную погоду, но не заменяют обычный питьевой режим для кожи.');
    add('🧣','Более плотный шарф или горловина снижают трение о ткань, если волосы распущены.');
    addEvening('🌙','Вечером: увлажнение кожи и кондиционирующий уход для длины.');
    addEvening('🌸','Вечером хорошее время для более насыщенной маски — кожа обычно легче воспринимает уход после прохладного дня.');
  }else if(temp<=15){
    add('🧴','Кожа: ориентируйся на комфорт — лёгкий или средний увлажняющий слой без ощущения плёнки.');
    add('🎀','Волосы: после мытья используй кондиционер, если длина ощущается сухой.');
    add('🌬️','На улице: если поднимается ветер, дополнительно защити губы и участки кожи, которые быстро сохнут.');
    add('🌤️','Переходная погода: рутина может меняться день ото дня — ориентируйся на реальное состояние кожи, а не на календарь.');
    add('💧','Лёгкое увлажнение утром помогает коже чувствовать себя комфортно и при прохладе, и при небольшом потеплении в течение дня.');
    add('🧴','Если планируешь смену сезонного крема, прохладная погода — удобное время постепенно ввести более плотную текстуру.');
    addEvening('🌙','Вечером: базовый уход обычно достаточен; усиливай восстановление только при стянутости или сухости.');
    addEvening('🎀','Вечером можно чуть больше внимания уделить кончикам волос — переходный сезон часто отражается именно на них.');
  }else if(temp<=25){
    add('🌸','Кожа: комфортная температура — не нужно менять всю рутину, достаточно следить за ощущением кожи.');
    add('☀️','Перед длительной прогулкой проверь UV и используй SPF по ситуации.');
    add('🎀','Волосы: обычный уход подходит, но при влажности следи за пушением.');
    add('💧','Комфортная погода — хороший момент попробовать новый продукт: кожа реже реагирует непредсказуемо в спокойных условиях.');
    add('🧴','Если планируешь долгий день на улице, возьми с собой лёгкий увлажняющий спрей или термальную воду.');
    add('🎀','Волосы в такую погоду обычно ведут себя предсказуемо — можно спокойно поэкспериментировать с укладкой.');
    addEvening('🌙','Вечером: обычная рутина, без необходимости компенсировать погоду десятком дополнительных средств.');
    addEvening('🪞','Хороший вечер, чтобы сделать паузу и просто понаблюдать за состоянием кожи без добавления новых шагов.');
  }else if(temp<=30){
    add('🧴','Кожа: выбирай более лёгкие текстуры и не перегружай лицо плотными слоями.');
    add('☀️','SPF особенно важен при выходе на улицу; при длительном пребывании защита требует обновления.');
    add('💦','После улицы: мягкое очищение, затем увлажнение по ощущениям.');
    add('🎀','Волосы: меньше горячей укладки, больше защиты длины от солнца и трения.');
    add('🧴','Гель или лёгкая эмульсия вместо крема — в такую погоду кожа обычно комфортнее ощущает себя с более жидкой текстурой.');
    add('💦','Мицеллярная вода или спрей помогут освежить лицо в течение дня, не перегружая кожу дополнительным уходом.');
    add('🧢','Головной убор снижает нагрузку от прямого солнца и помогает волосам меньше пересыхать за день.');
    add('🥤','Не забывай про воду в течение дня — обезвоживание организма тоже отражается на виде кожи.');
    addEvening('🌙','Вечером: мягко очисти кожу от пота/солнцезащитных средств и верни комфорт увлажняющим уходом.');
    addEvening('🚿','Вечером — прохладный (не холодный) душ помогает коже быстрее прийти в комфортное состояние после жаркого дня.');
  }else{
    add('☀️','Очень жарко: сократи длительное пребывание под прямым солнцем и планируй прогулки на менее жаркое время.');
    add('🧴','Кожа: лёгкие не перегружающие текстуры; не пытайся компенсировать жару большим количеством средств.');
    add('💦','После улицы: мягко очисти кожу и восстанови увлажнение.');
    add('🎀','Волосы: минимизируй горячую укладку и защищай длину от солнца.');
    addAlert('🔥','Жара + тренировка: после занятия переоденься и мягко очисти лицо/тело от пота; не оставляй пот и плотный SPF на коже надолго.');
    addAlert('🌡️','Экстремальная жара: старайся избегать физической активности на солнце в часы пиковой температуры.');
    add('🧢','Головной убор и тень — простая, но эффективная защита в дополнение к SPF в очень жаркие часы.');
    add('💦','Термальная вода или прохладный компресс на лицо помогают быстро вернуть коже комфорт в течение дня.');
    add('🥤','Питьевой режим особенно важен в жару — обезвоженная кожа выглядит более уставшей.');
    add('🎀','Собранные волосы снижают дискомфорт от жары и уменьшают контакт длины с потом и солнцем.');
    addEvening('🌙','Вечером: мягкое очищение → лёгкое увлажнение → спокойный уход за длиной волос.');
    addEvening('🧊','Вечером: прохладный (не ледяной) уход помогает коже расслабиться после жаркого дня — резкий холод может, наоборот, раздражать.');
  }

  /* Влажность */
  if(humidity>=90){
    add('💧','Влажность 90%+: кожа и волосы могут ощущаться более липкими; не наслаивай много тяжёлых текстур.');
    add('💇‍♀️','Волосы: несмываемый кондиционер в небольшом количестве или анти-фриз уход по длине, если пушение усиливается.');
    add('🌬️','При очень высокой влажности старайся давать коже "дышать" — избегай плотных многослойных текстур в течение дня.');
    add('🧴','Матирующие салфетки или лёгкая пудра помогут контролировать ощущение липкости без пересушивания.');
    addHome('🏠','Дома: проветри помещение, если это комфортно, и не перегружай кожу дополнительными слоями.');
    addHome('🪟','Дома в такую влажность имеет смысл проветривать чаще обычного, если это комфортно.');
    addEvening('🎀','Вечером: лёгкий кондиционирующий уход для длины вместо большого количества масел и стайлинга.');
    addEvening('🎀','Вечером — лёгкий несмываемый уход для длины вместо тяжёлых масел, которые в такую влажность утяжеляют волосы ещё сильнее.');
  }else if(humidity>=80){
    add('💧','Высокая влажность: делай уход тоньше — несколько лёгких слоёв лучше, чем один очень плотный.');
    add('🎀','Волосы: контролируй пушение небольшим количеством несмываемого средства.');
    add('🧴','При высокой влажности крем "впитывается" дольше — дай ему немного времени перед нанесением макияжа или следующего слоя.');
    add('🎀','Лёгкий спрей-антифриз для волос поможет держать укладку стабильнее в течение дня.');
  }else if(humidity>=60){
    add('💧','Влажность комфортная: ориентируйся на состояние кожи и волос, без специальных изменений рутины.');
    add('🌸','Комфортная влажность обычно не требует специальных корректировок — можно ориентироваться на обычную рутину.');
  }else if(humidity>=36){
    add('💧','Умеренно сухой воздух: поддерживай обычное увлажнение кожи и длины волос.');
    add('💧','Умеренная влажность — нейтральные условия для кожи и волос, специальных мер не требуется.');
  }else{
    add('💧','Сухой воздух: сделай акцент на увлажнении кожи и не переусердствуй с очищением.');
    add('🎀','Волосы: добавь увлажняющий уход на длину, если она сухая или электризуется.');
    add('💋','Губы: профилактически используй бальзам, особенно перед выходом.');
    add('🧴','Сухой воздух особенно ощущается вокруг глаз и на скулах — им можно уделить чуть больше внимания.');
    add('💧','Увлажняющий спрей в течение дня помогает поддерживать комфорт кожи, если находишься в помещении с сухим воздухом.');
    add('🎀','Волосы в сухом воздухе электризуются активнее — небольшое количество несмываемого ухода снижает этот эффект.');
    addHome('🏠','Если весь день дома: не компенсируй сухость кожи агрессивным умыванием — лучше поддерживать мягкое очищение и регулярное увлажнение.');
    addHome('💦','Дома увлажнитель воздуха — простой способ сделать сухую погоду комфортнее и для кожи, и для волос.');
    addEvening('🌙','Вечером: восстановительный увлажняющий уход для кожи и длины волос особенно уместен.');
    addEvening('🧴','Вечером плотный слой увлажняющего крема помогает компенсировать сухость воздуха, накопленную за день.');
  }

  /* Ветер */
  if(wind>=40){
    add('💨','Ветер 40+ км/ч: защити открытые участки кожи и губы от пересушивания.');
    add('🎀','Волосы: мягкая коса/низкий хвост или другая щадящая укладка уменьшит спутывание и трение.');
    addAlert('🌬️','Очень ветрено: по возможности сократи длительное пребывание на открытом воздухе.');
    addAlert('💨','Сильный порывистый ветер может дополнительно травмировать сухую или потрескавшуюся кожу губ и рук — держи бальзам под рукой.');
    add('🧣','При очень сильном ветре собери волосы в низкий хвост или косу — так они меньше путаются и меньше подвержены трению.');
    add('🛡️','Более плотный защитный крем на открытые участки лица снижает ощущение стянутости после сильного ветра.');
    addEvening('💋','Вечером проверь губы и сухие участки кожи; при необходимости добавь более защитный слой.');
    addEvening('🎀','Вечером расчёсывай волосы особенно бережно — после сильного ветра длина может быть более спутанной и уязвимой.');
  }else if(wind>=30){
    add('💨','Сильный ветер: защити губы и сухие участки кожи, а длину волос убери от постоянного контакта с одеждой.');
    add('🎀','Небольшое количество несмываемого ухода на длину снижает эффект "пушения" от ветра.');
  }else if(wind>=20){
    add('💨','Ветрено: не забывай про защиту губ и сухих участков кожи.');
    add('🎀','Убери длину от постоянного контакта с одеждой.');
    add('💋','Бальзам для губ стоит обновлять чаще обычного — ветер быстро сушит эту зону.');
    add('🧴','Лёгкий защитный слой на лицо перед выходом снижает ощущение стянутости от ветра.');
  }

  /* Осадки и явления */
  if(desc.includes('дожд')||desc.includes('морос')){
    add('🌧️','Дождь: если хочешь меньше пушения, защити волосы от промокания капюшоном или зонтом.');
    add('🧴','После возвращения домой: не растирай кожу и волосы полотенцем — промокни их мягко.');
    add('🎀','Волосы: не запирай мокрую длину под плотной резинкой; сначала дай ей подсохнуть.');
    add('☂️','Если есть возможность, держи зонт или капюшон под рукой — так укладка и кожа меньше страдают от неожиданного дождя.');
    add('💧','После дождя лицо может ощущаться свежее обычного — это нормально, не обязательно сразу наносить дополнительный уход.');
    add('🎀','Слегка влажный воздух после дождя иногда помогает волосам выглядеть менее сухими — используй это по ощущениям.');
    addEvening('🌙','Вечером: мягкое очищение и обычный увлажняющий уход; лишний раз не пересушивай кожу.');
    addEvening('🛁','Вечером — тёплый (не горячий) душ помогает смыть уличную влагу и восстановить комфорт кожи.');
  }
  if(desc.includes('снег')){
    add('❄️','Снег: холодный влажный воздух всё равно может усиливать ощущение сухости — ориентируйся на комфорт кожи.');
    add('🎀','Не выходи на улицу с влажной длиной.');
    add('💋','Губы: защитный бальзам особенно полезен при снегопаде и ветре.');
    add('🧤','Перчатки защищают руки не только от холода, но и от лишней влаги при контакте со снегом.');
    add('👢','Если снег попадает на волосы, дай им подсохнуть естественным путём, прежде чем убирать под шапку.');
    add('🛡️','Плотный крем перед выходом снижает ощущение стянутости от контраста холодного снега и тёплого дыхания.');
    addEvening('🌙','Вечером: спокойный защитно-восстановительный уход.');
    addEvening('❄️','Вечером — восстанавливающий уход для кожи лица и рук после дня на снегу и холоде.');
  }
  if(desc.includes('туман')){
    add('🌫️','Туман: высокая влажность у поверхности воздуха — не перегружай волосы стайлингом.');
    add('🎀','Если волосы пушатся, лучше небольшое количество разглаживающего ухода по длине.');
    add('💧','В туман волосы особенно быстро теряют объём у корней — сухой шампунь поможет продержаться дольше.');
    add('🧴','Лёгкий некомедогенный крем достаточно в туманную погоду — тяжёлые текстуры только усилят ощущение влажности на коже.');
  }
  if(desc.includes('гроза')){
    add('⛈️','Гроза: если нет необходимости долго быть на улице, выбери спокойный домашний beauty-вечер.');
    add('🕯️','Гроза — неплохой повод устроить себе спокойный ритуал ухода при свечах или мягком свете, если вдруг отключат электричество.');
    addHome('🏠','Дома: отличный день для мягкого очищения, маски для волос или другого привычного восстановительного этапа.');
    addHome('🎬','Домашний beauty-вечер во время грозы — время для того, что обычно откладываешь: масла для кутикулы, скраб для тела, длинная маска для волос.');
  }

  /* UV: 0–2, 3–5, 6–7, 8–10, 11+ */
  if(Number.isFinite(uvN)){
    if(uvN>=11){
      addAlert('☀️','UV экстремальный: по возможности избегай прямого солнца в часы максимальной активности, используй SPF и физическую защиту — одежду, головной убор, тень.');
      addAlert('🕶️','При экстремальном UV даже недолгое пребывание на солнце ощутимо — солнцезащитные очки и тень обязательны, а не по желанию.');
    }else if(uvN>=8){
      add('☀️','UV очень высокий: сокращай прямое солнце, используй SPF и не забывай про головной убор/тень.');
      add('🧴','Обновляй SPF каждые 2 часа при активном пребывании на солнце — один раз с утра недостаточно для такого уровня UV.');
    }else if(uvN>=6){
      add('☀️','UV высокий: SPF важен даже при комфортной температуре; при длительной прогулке защита должна оставаться актуальной.');
      add('🕶️','Солнцезащитные очки — не только про глаза: они снижают привычку щуриться, а значит и количество мимических складок вокруг глаз.');
    }else if(uvN>=3){
      add('🌤️','UV умеренный: SPF пригодится при длительном пребывании на улице, особенно на открытых участках.');
      add('🧢','Даже при умеренном UV панама или кепка — простой бонус для кожи головы и волос при долгой прогулке.');
    }else{
      add('🌥️','UV низкий: отдельная усиленная солнцезащита по UV обычно не требуется, но ориентируйся на свою обычную рутину.');
      add('🌥️','Низкий UV — комфортное время для активностей на улице без особых беспокойств о солнцезащите, помимо привычной рутины.');
    }
  }

  /* Комбинации дают отдельные, более полезные сценарии. */
  if(temp>=27 && humidity>=70){
    add('🔥','Жара + влажность: выбирай лёгкие текстуры, держи волосы максимально свободными от лица и не перегружай кожу стайлингом/маслами.');
    add('🧊','Жара с высокой влажностью особенно утомляет кожу — короткие перерывы в прохладе в течение дня облегчают состояние.');
  }
  if(temp<=5 && wind>=20){
    addAlert('🥶','Холод + ветер: ощущаемая нагрузка выше — особенно внимательно защищай щёки, губы и открытые участки кожи.');
    addAlert('🌬️','Холодный ветер сушит кожу быстрее, чем просто холод сам по себе — плотный крем и бальзам для губ обязательны перед выходом.');
  }
  if(temp>=25 && humidity<=35){
    add('☀️','Жара + сухой воздух: сочетай лёгкую текстуру с хорошим увлажнением, а не переходи на полностью обезжиренный уход.');
    add('💧','Жара и сухой воздух одновременно — сочетание, которое особенно быстро обезвоживает кожу; увлажнение в течение дня, а не только утром/вечером.');
  }
  if(wind>=25 && humidity<=40){
    add('🌬️','Ветер + сухой воздух: это сочетание особенно легко усиливает сухость губ, кожи и электризацию волос.');
    add('💋','При таком сочетании губы и кутикула страдают быстрее всего — держи бальзам и питательное масло под рукой.');
  }

  /* Поведенческие сценарии */
  addOutdoor('🚶‍♀️','Если предстоит долгая прогулка: ориентируйся не только на температуру, но и на UV, ветер и влажность.');
  addOutdoor('🧴','Возьми с собой мини-версию своего базового ухода — на случай, если погода изменится в течение дня.');
  if(temp>=27){ addOutdoor('🥤','В жару планируй тень и перерывы; после тренировки не оставляй пот на коже надолго.'); addOutdoor('🧢','В жару выбирай светлую одежду и головной убор — это ощутимо снижает нагрев кожи и волос на солнце.'); }
  if(wind>=25){ addOutdoor('🧣','При ветре уменьши трение волос о шарф, воротник и одежду.'); addOutdoor('💋','При ветре держи бальзам для губ в кармане или сумке — обновлять его удобнее на ходу, чем ждать возвращения домой.'); }
  if(desc.includes('дожд')||desc.includes('снег')){ addOutdoor('☂️','При осадках держи волосы максимально сухими и после возвращения аккуратно промокни их.'); addOutdoor('👜','В сумку стоит положить небольшое полотенце или салфетки — пригодятся, если волосы или лицо намокнут.'); }
  if(temp<=5){ addOutdoor('🧤','В холодный день не делай интенсивные домашние процедуры прямо перед выходом.'); addOutdoor('🧣','Закрывай шею и нижнюю часть лица в холодную погоду — так меньше замерзаешь и меньше раздражаешь кожу морозным воздухом.'); }
  if(uvN>=6){ addOutdoor('🧴','При высоком UV приоритет — защита открытой кожи и сокращение прямого солнца.'); addOutdoor('🕶️','Солнцезащитные очки и тень — приоритет наравне с SPF при высоком UV на длительной прогулке.'); }

  addHome('🏠','Если весь день дома: не нужно автоматически делать больше процедур — сохрани базовую рутину и используй погоду только для небольших корректировок.');
  addHome('🕯️','Дома проще экспериментировать без спешки — сегодняшний день неплохо подходит, чтобы попробовать шаг, до которого обычно не доходят руки.');
  if(temp>=27){ addHome('🧊','В жаркий день дома: держи уход лёгким и не перегревай кожу горячей водой или длительными горячими процедурами.'); addHome('🧊','Дома в жару — прохладный компресс на лицо на пару минут освежает не хуже специального ухода.'); }
  if(temp<=5 || humidity<=35){ addHome('🫧','В прохладе или сухом воздухе: поддерживай комфорт кожи мягким очищением и увлажнением.'); addHome('🫖','Дома в холод или сухость — тёплое питьё и увлажнитель воздуха работают на кожу не меньше, чем баночки в ванной.'); }

  /* Персонализация под тип кожи и волос: та же погода по-разному влияет на разные профили,
     поэтому эти советы выводятся отдельным приоритетным блоком "специально для тебя". */
  const skin=data.settings?.skinType, hair=data.settings?.hairType;
  if(skin==='oily' && humidity>=65){ addPersonal('✨','Жирная кожа + высокая влажность: держи под рукой матирующие салфетки и не наслаивай плотные текстуры — Т-зона заблестит быстрее обычного.'); addPersonal('✨','Лёгкая эссенция вместо крема днём — жирная кожа в такую влажность обычно комфортнее чувствует себя без плотного слоя.'); }
  if(skin==='oily' && temp>=27){ addPersonal('✨','Жирная кожа + жара: себум выделяется активнее — очищающий гель вместо плотного крема будет комфортнее днём.'); addPersonal('✨','Бумажные матирующие салфетки удобнее носить с собой, чем перезапускать всю рутину среди дня.'); }
  if(skin==='dry' && humidity<=40){ addPersonal('🧴','Сухая кожа + сухой воздух: сегодня стянутость может ощущаться сильнее — усиль увлажняющий слой утром и вечером.'); addPersonal('🧴','Сыворотка с гиалуроновой кислотой под крем — рабочий вариант дать коже дополнительный ресурс влаги в сухую погоду.'); }
  if(skin==='dry' && wind>=25){ addPersonal('🧴','Сухая кожа + ветер: добавь более плотный защитный крем перед выходом, чтобы не усиливать шелушение.'); addPersonal('🧴','На ветру для сухой кожи особенно важен именно защитный, а не просто увлажняющий крем — барьерный слой снижает потерю влаги.'); }
  if(skin==='combination' && temp>=25){ addPersonal('🌸','Комбинированная кожа + тепло: лёгкая текстура на Т-зону, обычный увлажняющий уход — на остальное лицо.'); addPersonal('🌸','Промакивающая салфетка для Т-зоны в течение дня — удобнее, чем повторное умывание всего лица в жару.'); }
  if(skin==='sensitive' && (wind>=20 || uvN>=6)){ addPersonal('🌾','Чувствительная кожа + сегодняшние условия: сократи количество активов в рутине и сделай акцент на успокаивающем уходе.'); addPersonal('🌾','В такие дни чувствительной коже комфортнее без новых продуктов — оставь эксперименты на более спокойную погоду.'); }
  if(skin==='sensitive' && temp<=0){ addPersonal('🌾','Чувствительная кожа + мороз: покраснение и стянутость вероятнее — минимум трения при умывании и плотный защитный крем.'); addPersonal('🌾','Плотный, но простой по составу крем обычно комфортнее для чувствительной кожи в мороз, чем многослойный уход.'); }
  if(hair==='oily' && humidity>=65){ addPersonal('🎀','Жирные волосы + влажность: прикорневой объём держится меньше — сухой шампунь в середине дня выручит.'); addPersonal('🎀','Лёгкий текстурирующий спрей у корней помогает дольше держать объём при высокой влажности.'); }
  if(hair==='dry' && (humidity<=40 || wind>=25)){ addPersonal('🎀','Сухие волосы + сухой воздух или ветер: несмываемый уход по длине защитит от лишней сухости и электризации.'); addPersonal('🎀','Сухим волосам в такую погоду особенно полезно масло на кончики перед выходом — это простая защита от дополнительной сухости.'); }
  if(hair==='damaged' && uvN>=6){ addPersonal('🎀','Повреждённые волосы + высокий UV: используй спрей с UV-фильтром для волос — солнце ослабляет и без того уязвимую структуру.'); addPersonal('🎀','Головной убор — механическая защита длины от солнца, которая работает вместе с уходовыми средствами, а не вместо них.'); }
  if(hair==='colored' && uvN>=6){ addPersonal('🎀','Окрашенные волосы + высокий UV: солнце ускоряет выцветание пигмента — сегодня особенно уместна защита от солнца для волос.'); addPersonal('🎀','Оттеночный уход или спрей с UV-фильтром для волос в такие дни особенно уместен — цвет выцветает от солнца заметнее обычного.'); }
  if(hair==='colored' && (desc.includes('дожд')||humidity>=80)){ addPersonal('🎀','Окрашенные волосы + высокая влажность/дождь: пигмент может вымываться быстрее — минимизируй лишние умывания головы сегодня.'); addPersonal('🎀','Если волосы всё же намокли, дай им подсохнуть естественным путём — так меньше риска, что пигмент вымоется активнее из-за трения полотенцем.'); }

  const unique=(arr)=>{
    const seen=new Set();
    return arr.filter(x=>{if(seen.has(x.text))return false;seen.add(x.text);return true;});
  };
  const uniqTips=unique(tips), uniqEvening=unique(evening), uniqHome=unique(home), uniqOutdoor=unique(outdoor), uniqAlerts=unique(alerts), uniqPersonal=unique(personal);

  let title='Спокойный beauty-day', text='Сегодня можно оставить привычную рутину и сделать несколько небольших поправок под условия на улице.';
  if(temp>=30){title='Жаркий beauty-day';text='Сегодня важнее лёгкость, защита от солнца, контроль пота и спокойное восстановление вечером.';}
  else if(temp>=25){title='Тёплый день';text='Лёгкие текстуры, солнцезащита и меньше перегруза — лучший ответ на сегодняшнюю погоду.';}
  else if(temp<=-10){title='Морозный день';text='Главная задача — защитить кожу, губы и волосы от холода, ветра и перепадов температуры.';}
  else if(temp<=0){title='Холодный день';text='Сделай упор на защиту кожи и губ, мягкое очищение и бережное отношение к волосам.';}
  else if(temp<=5){title='Прохладный день';text='Комфортный защитный уход и меньше трения помогут коже и волосам пережить холод спокойнее.';}
  else if(desc.includes('гроза')){title='День для дома';text='Если можно остаться в помещении, погода отлично подходит для спокойного восстановительного ухода.';}
  else if(desc.includes('дожд')||desc.includes('морос')){title='Влажный день';text='Сегодня важны защита волос от промокания, меньше трения и мягкий уход после улицы.';}
  else if(desc.includes('снег')){title='Снежный день';text='Холод и осадки требуют бережной защиты кожи, губ и длины волос.';}
  else if(desc.includes('туман')){title='Туманный день';text='Высокая влажность может усиливать пушение — сегодня лучше лёгкий уход и минимум перегруза.';}
  else if(humidity<=35){title='Сухой воздух';text='Сегодня особенно пригодятся увлажнение кожи, защита губ и бережное отношение к длине волос.';}
  else if(wind>=30){title='Сильный ветер';text='Защити открытые участки кожи и волосы от сухости, трения и спутывания.';}
  else if(wind>=20){title='Ветрено';text='Небольшая защита от ветра сделает день заметно комфортнее для кожи, губ и волос.';}
  else if(uvN>=8){title='Солнечный день';text='Сегодня главный beauty-приоритет — защита от высокого UV и восстановление комфорта кожи вечером.';}
  else if(temp>=15 && temp<=25 && humidity>=36 && humidity<60 && wind<20 && uvN<3){title='Идеальный beauty-day';text='Редкое сочетание комфортной температуры, влажности и UV — отличный повод попробовать что-то новое в уходе.';}
  else if(desc.includes('ясно') && temp>15 && temp<25){title='Ясный и комфортный день';text='Мягкая температура и чистое небо — удобный момент для лёгкой прогулки и обычного ухода без корректировок.';}
  else if(uvN>=3 && uvN<6){title='Умеренное солнце';text='SPF не помешает при долгой прогулке, но менять привычную рутину не обязательно.';}
  else if(humidity>=60 && humidity<80){title='Влажный, но комфортный день';text='Небольшая корректировка текстур поможет коже и волосам чувствовать себя увереннее без специальных мер.';}
  else if(wind>=10 && wind<20){title='Лёгкий ветерок';text='Почти незаметная поправка к обычному уходу — можно взять с собой бальзам для губ на всякий случай.';}
  else if(desc.includes('облач')){title='Пасмурный день';text='Без резких перепадов — хороший день для базовой рутины и небольших плановых процедур ухода.';}

  const whyParts=[];
  if(Number.isFinite(temp)) whyParts.push(`${temp}°C`);
  if(Number.isFinite(Number(w.feelsLike)) && Number(w.feelsLike)!==temp) whyParts.push(`ощущается как ${Math.round(Number(w.feelsLike))}°C`);
  if(Number.isFinite(wind)) whyParts.push(`ветер ${wind} км/ч`);
  if(Number.isFinite(humidity)) whyParts.push(`влажность ${humidity}%`);
  if(Number.isFinite(uvN)) whyParts.push(`UV ${uvN.toFixed(0)}`);
  if(desc) whyParts.push(desc);
  const why=`Почему именно сегодня: ${whyParts.join(' · ')}.`;

  return {
    title,text,why,chips,
    tips:uniqTips.slice(0,12),
    evening:uniqEvening.slice(0,5),
    home:uniqHome.slice(0,4),
    outdoor:uniqOutdoor.slice(0,5),
    alerts:uniqAlerts.slice(0,4),
    personal:uniqPersonal.slice(0,4),
    forecast:{today:w.today||null,tomorrow:w.tomorrow||null},
    feelsLike:Number.isFinite(Number(w.feelsLike))?Math.round(Number(w.feelsLike)):null,
    rainSoon:Number.isFinite(Number(w.rainSoon))?Math.round(Number(w.rainSoon)):null,
    trend:weatherTrendNote()
  };
}

// Тренд последних проверок погоды: если несколько раз подряд держится сухость/жара/мороз/влажность —
// подсказываем скорректировать уход не на один день, а на всю ближайшую неделю.
function weatherTrendNote(){
  const hist=Array.isArray(data.settings?.weatherHistory)?data.settings.weatherHistory:[];
  if(hist.length<3) return null;
  const last3=hist.slice(0,3);
  const avg=k=>last3.reduce((s,x)=>s+(Number(x[k])||0),0)/last3.length;
  const avgHum=avg('humidity'), avgTemp=avg('temp');
  if(avgHum<=35) return {icon:'🏜️',text:'Воздух держится сухим несколько проверок подряд — на этой неделе увлажнению кожи и волос стоит уделить больше внимания, чем обычно.'};
  if(avgHum>=80) return {icon:'💧',text:'Влажность высокая уже несколько раз подряд — выбирай более лёгкие текстуры и следи за пушением волос всю неделю.'};
  if(avgTemp>=27) return {icon:'🔥',text:'Жара держится несколько проверок подряд — не забывай про SPF и восстановительный уход по вечерам всю неделю.'};
  if(avgTemp<=0) return {icon:'❄️',text:'Мороз держится несколько проверок подряд — усиленная защита кожи, губ и волос сейчас особенно важна.'};
  return null;
}

// Надёжное получение погоды по городу: прямой Open-Meteo + запасной CORS-прокси.
const __weatherDirect=async(url)=>{const c=new AbortController();const t=setTimeout(()=>c.abort(),9000);try{const r=await fetch(url,{mode:'cors',cache:'no-store',signal:c.signal});if(!r.ok)throw new Error('HTTP '+r.status);return await r.json()}finally{clearTimeout(t)}};
const __weatherProxy=async(url)=>{const proxy='https://api.allorigins.win/raw?url='+encodeURIComponent(url);const c=new AbortController();const t=setTimeout(()=>c.abort(),12000);try{const r=await fetch(proxy,{cache:'no-store',signal:c.signal});if(!r.ok)throw new Error('Прокси HTTP '+r.status);return await r.json()}finally{clearTimeout(t)}};
async function __weatherRequest(url){try{return await __weatherDirect(url)}catch(e){console.warn('Прямой запрос погоды не прошёл, пробую запасной канал.',e);return await __weatherProxy(url)}}
fetchWeather=async function(){
 const city=String(data.settings?.city||'').trim();
 if(!city){toast('Сначала укажи город в настройках ♡');return;}
 try{
   toast('Получаю погоду для '+city+'… ☁️');
   const geoUrl=`https://geocoding-api.open-meteo.com/v1/search?name=${encodeURIComponent(city)}&count=1&language=ru&format=json`;
   const geo=await __weatherRequest(geoUrl);
   if(!geo?.results?.length)throw new Error('Город не найден');
   const g=geo.results[0];
   const weatherUrl=`https://api.open-meteo.com/v1/forecast?latitude=${encodeURIComponent(g.latitude)}&longitude=${encodeURIComponent(g.longitude)}&current=temperature_2m,apparent_temperature,relative_humidity_2m,weather_code,wind_speed_10m,uv_index,precipitation,is_day&hourly=precipitation_probability&daily=temperature_2m_max,temperature_2m_min,uv_index_max,precipitation_probability_max&forecast_days=2&timezone=auto`;
   const w=await __weatherRequest(weatherUrl);
   const c=w?.current||{};
   if(!Number.isFinite(Number(c.temperature_2m)))throw new Error('В прогнозе нет текущих данных');

   // Ближайший дождь: берём вероятность осадков на ближайшие ~6 часов из почасового прогноза.
   const hourly=w?.hourly||{}; const hTimes=Array.isArray(hourly.time)?hourly.time:[]; const hProb=Array.isArray(hourly.precipitation_probability)?hourly.precipitation_probability:[];
   let rainSoon=null;
   if(hTimes.length && hProb.length){
     const nowIso=String(c.time||'');
     let idx=hTimes.findIndex(t=>String(t)>=nowIso);
     if(idx<0)idx=0;
     const win=hProb.slice(idx,idx+6).map(Number).filter(Number.isFinite);
     if(win.length)rainSoon=Math.max(...win);
   }
   // Мини-прогноз на сегодня/завтра, чтобы советовать заранее, а не только по текущей минуте.
   const daily=w?.daily||{};
   const dayInfo=i=>({
     tempMax:Number(daily.temperature_2m_max?.[i]),
     tempMin:Number(daily.temperature_2m_min?.[i]),
     uvMax:Number(daily.uv_index_max?.[i]),
     rainChance:Number(daily.precipitation_probability_max?.[i])
   });
   const today=dayInfo(0), tomorrow=dayInfo(1);

   data.settings.weather={city:g.name,country:g.country||'',temp:Math.round(Number(c.temperature_2m)),feelsLike:Number.isFinite(Number(c.apparent_temperature))?Math.round(Number(c.apparent_temperature)):null,humidity:Math.round(Number(c.relative_humidity_2m)||0),wind:Math.round(Number(c.wind_speed_10m)||0),uv:Number.isFinite(Number(c.uv_index))?Number(c.uv_index):null,precipNow:Number.isFinite(Number(c.precipitation))?Number(c.precipitation):0,rainSoon,today,tomorrow,code:Number(c.weather_code),isDay:Boolean(c.is_day),description:weatherText(Number(c.weather_code)),at:Date.now(),source:'Open-Meteo'};
   data.settings.lastWeatherAt=Date.now();data.weatherChecks=(Number(data.weatherChecks)||0)+1;data.settings.lastSavedAt=Date.now();

   // Короткая история последних проверок — на её основе строим "тренд недели"
   // (например, третий сухой день подряд), а не советуем только по текущей минуте.
   data.settings.weatherHistory=Array.isArray(data.settings.weatherHistory)?data.settings.weatherHistory:[];
   data.settings.weatherHistory.unshift({temp:data.settings.weather.temp,humidity:data.settings.weather.humidity,wind:data.settings.weather.wind,uv:data.settings.weather.uv,desc:data.settings.weather.description,at:Date.now()});
   data.settings.weatherHistory=data.settings.weatherHistory.slice(0,7);

   checkAchievements();save();toast(`Погода обновлена: ${g.name} ♡`);render();
 }catch(err){
   console.error('Ошибка погоды:',err);
   if(data.settings.weather)toast('Не удалось обновить интернет-погоду — оставила последний сохранённый прогноз.');
   else toast('Не удалось получить погоду. Проверь интернет и название города.');
 }
};
// Обновлять прогноз один раз за 30 минут после указания города, без циклических render-вызовов.
function maybeAutoWeather(){
 const city=String(data.settings?.city||'').trim();
 if(!city)return;
 const fresh=Date.now()-Number(data.settings?.lastWeatherAt||0)<30*60*1000;
 if(fresh)return;
 const key=city.toLowerCase();
 if(window.__mjWeatherAuto===key)return;
 window.__mjWeatherAuto=key;
 setTimeout(()=>{fetchWeather().catch(()=>{})},120);
}

// Floating Quick Add
function ensureQuickAdd(){
  let root=document.getElementById('quickAddRoot');
  if(!root){root=document.createElement('div');root.id='quickAddRoot';document.body.appendChild(root);}
  root.innerHTML=`<button class="quick-fab" id="quickFab" aria-label="Быстро добавить">＋</button><div class="quick-panel" id="quickPanel"><button data-quick="routine">♡ Выполнила уход</button><button data-quick="product">🧴 Добавить средство</button><button data-quick="photo">📸 Добавить фото</button><button data-quick="note">✎ Написать заметку</button><button data-quick="goal">🎯 Создать цель</button><button data-quick="procedure">🎀 Добавить процедуру</button></div>`;
  const fab=root.querySelector('#quickFab'), panel=root.querySelector('#quickPanel');
  fab.onclick=()=>{panel.classList.toggle('open');fab.classList.toggle('open');playSound('click')};
  root.querySelectorAll('[data-quick]').forEach(b=>b.onclick=()=>{panel.classList.remove('open');fab.classList.remove('open');quickAction(b.dataset.quick)});
}
function quickAction(kind){
  if(kind==='routine'){location.hash='today';setTimeout(()=>toast('Выбери этап — одно нажатие и он готов ♡'),80);return;}
  if(kind==='product'){location.hash='products';setTimeout(()=>document.querySelector('[data-add-product data-action="addProduct"]')?.click(),90);return;}
  if(kind==='photo'){openPhotoModal();return;}
  if(kind==='note'){openNoteModal();return;}
  if(kind==='goal'){openGoalModal();return;}
  if(kind==='procedure'){openRoutineModal();return;}
}

function openNoteModal(){
  modal(`<h3>✎ Новая запись</h3><form id="quickNoteForm" class="form"><div class="field"><label>Что хочется сохранить?</label><textarea name="text" required placeholder="Сегодня кожа выглядит…"></textarea></div><div class="modal-actions"><button type="button" class="btn ghost" data-close>Отмена</button><button class="btn">Сохранить</button></div></form>`);
  document.getElementById('quickNoteForm')?.addEventListener('submit',e=>{e.preventDefault();const f=new FormData(e.currentTarget);data.notes.unshift({id:uid(),date:todayKey(),text:String(f.get('text')||'').trim()});addXP(3,'Запись в дневнике');save();closeModal();toast('Запись сохранена ♡');render();});
}
function openPhotoModal(){
  modal(`<h3>📸 Новое фото прогресса</h3><form id="quickPhotoForm" class="form"><div class="field"><label>Фото</label><input type="file" name="photo" accept="image/*" required></div><div class="grid grid-2"><div class="field"><label>Категория</label><select name="category"><option value="skin">Кожа</option><option value="hair">Волосы</option></select></div><div class="field"><label>Оценка</label><input type="number" min="1" max="10" name="rating" value="8"></div></div><div class="field"><label>Комментарий</label><textarea name="comment" placeholder="Что заметила?"></textarea></div><div class="modal-actions"><button type="button" class="btn ghost" data-close>Отмена</button><button class="btn">Сохранить</button></div></form>`);
  document.getElementById('quickPhotoForm')?.addEventListener('submit',async e=>{e.preventDefault();const f=e.currentTarget;const file=f.photo.files?.[0];if(!file)return;const reader=new FileReader();reader.onload=()=>{data.photos.push({id:uid(),date:todayKey(),category:f.category.value,rating:Number(f.rating.value)||0,comment:String(f.comment.value||''),image:reader.result});addXP(15,'Фото прогресса');save();closeModal();toast('Фото добавлено ♡');render()};reader.readAsDataURL(file)});
}
function openGoalModal(){
  if(typeof openGoalEditor==='function'){openGoalEditor();return;}
  modal(`<h3>🎯 Новая цель</h3><form id="quickGoalForm" class="form"><div class="field"><label>Название</label><input name="title" required placeholder="30 дней без пропусков"></div><div class="field"><label>Срок</label><input type="date" name="due"></div><div class="modal-actions"><button type="button" class="btn ghost" data-close>Отмена</button><button class="btn">Создать</button></div></form>`);
  document.getElementById('quickGoalForm')?.addEventListener('submit',e=>{e.preventDefault();const f=new FormData(e.currentTarget);data.goals.push({id:uid(),title:String(f.get('title')),description:'',due:String(f.get('due')||''),progress:0,status:'active'});save();closeModal();toast('Цель создана 🎯');render()});
}

// Calendar day as a premium bottom-sheet-like modal.
function openCalendarDay(key){
  const s=dayStats(key); const ev=data.events.filter(e=>e.date===key); const routines=s.all;
  const photoCount=data.photos.filter(p=>p.date===key).length, noteCount=data.notes.filter(n=>n.date===key).length;
  modal(`<div class="day-sheet"><div class="row between"><div><span class="label">День ухода</span><h3>${esc(fmtDate(key))}</h3></div><div class="circle small-circle" style="--p:${s.p}"><div class="inside"><strong>${s.p}%</strong></div></div></div><div class="grid grid-2"><div class="stat"><span class="label">Выполнение</span><b>${s.done.length}/${s.all.length}</b></div><div class="stat"><span class="label">Фото</span><b>${photoCount}</b></div><div class="stat"><span class="label">Заметки</span><b>${noteCount}</b></div><div class="stat"><span class="label">События</span><b>${ev.length}</b></div></div><h4 class="section-title" style="margin-top:16px">Процедуры</h4><div class="list">${routines.length?routines.map(r=>`<div class="item row between"><div><strong>${esc(r.title)}</strong><p>${r.category==='skin'?'🌸 Кожа':'🎀 Волосы'} · ${r.slot==='morning'?'Утро':r.slot==='evening'?'Вечер':'Extra'}</p></div><span class="tag">${isDone(key,r.id)?'✓ выполнено':'○ не выполнено'}</span></div>`).join(''):'<div class="empty">На этот день нет назначенных процедур.</div>'}</div><h4 class="section-title" style="margin-top:16px">🌸 События</h4><div class="list">${ev.length?ev.map(e=>`<div class="item"><strong>${esc(e.title)}</strong><p>${esc(e.note||'')}</p></div>`).join(''):'<div class="empty">Событий пока нет.</div>'}</div><div class="modal-actions"><button type="button" class="btn secondary" data-day-template="${key}">Сделать этот день шаблоном</button><button type="button" class="btn ghost" data-close>Закрыть</button></div></div>`);
}
function makeCalendarTemplate(key){
  const routines=entriesForDay(key);
  if(!routines.length){toast('В этом дне пока нет процедур.');return;}
  const ids=routines.map(r=>r.id);localStorage.setItem('myBeautyJournal_template',JSON.stringify({date:key,routineIds:ids,createdAt:Date.now()}));toast(`Шаблон ${fmtDate(key)} сохранён ♡`);
}

// Premium weather card inserted into Today/Home.
function weatherForecastRow(a){
  const fmtDay=d=>{
    if(!d||!Number.isFinite(d.tempMax))return null;
    const parts=[`${Math.round(d.tempMin)}…${Math.round(d.tempMax)}°`];
    if(Number.isFinite(d.uvMax))parts.push(`UV ${d.uvMax.toFixed(0)}`);
    if(Number.isFinite(d.rainChance))parts.push(`☔ ${Math.round(d.rainChance)}%`);
    return parts.join(' · ');
  };
  const t=fmtDay(a.forecast?.today), tm=fmtDay(a.forecast?.tomorrow);
  if(!t && !tm)return '';
  return `<div class="weather-advice-section"><div class="label">📅 НА СЕГОДНЯ И ЗАВТРА</div>
    <div class="row wrap" style="gap:8px;margin-top:6px">
      ${t?`<span class="tag">Сегодня: ${esc(t)}</span>`:''}
      ${tm?`<span class="tag">Завтра: ${esc(tm)}</span>`:''}
    </div></div>`;
}
function weatherPremiumCard(){
  const w=data.settings.weather; const a=weatherAdvice();
  const list=(arr)=>arr.map(t=>`<div class="weather-tip"><span class="weather-tip-icon">${t.icon}</span><span>${esc(t.text)}</span></div>`).join('');
  const section=(title,arr,cls='')=>arr?.length?`<div class="weather-advice-section ${cls}"><div class="label">${title}</div>${list(arr)}</div>`:'';
  return `<section class="card editorial-weather" style="margin-top:16px">
    <div class="row between wrap">
      <div style="flex:1;min-width:220px">
        <div class="label">ПОГОДА → BEAUTY-КОНСУЛЬТАНТ</div>
        <h3 class="section-title">${esc(a.title)}</h3>
        <p style="line-height:1.6;margin:0">${esc(a.text)}</p>
        ${w?`<p class="weather-why"><strong>Почему именно сегодня?</strong> ${esc(a.why)}</p>`:''}
      </div>
      <div class="weather-big">${w?weatherIcon(w.description):'☁️'}</div>
    </div>
    ${w?`<div class="weather-meta">
      <span>🌡️ ${w.temp}°C</span>${a.feelsLike!=null && a.feelsLike!==w.temp?`<span>🤔 ощущается как ${a.feelsLike}°C</span>`:''}<span>💧 ${w.humidity}%</span><span>💨 ${w.wind} км/ч</span>
      ${w.uv!=null?`<span>☀️ UV ${Number(w.uv).toFixed(0)}</span>`:''}
      <span>${weatherIcon(w.description)} ${esc(w.description||'')}</span>
    </div>`:''}
    ${w?weatherForecastRow(a):''}
    ${a.alerts?.length?section('⚠️ ОБРАТИ ВНИМАНИЕ',a.alerts,'weather-alerts'):''}
    ${a.personal?.length?section('🎯 СПЕЦИАЛЬНО ДЛЯ ТВОЕГО ТИПА КОЖИ И ВОЛОС',a.personal,'weather-personal'):''}
    ${a.trend?`<div class="weather-advice-section weather-trend"><div class="label">📈 ТРЕНД ПОСЛЕДНИХ ДНЕЙ</div><div class="weather-tip"><span class="weather-tip-icon">${a.trend.icon}</span><span>${esc(a.trend.text)}</span></div></div>`:''}
    ${section('✨ ЧТО СЕГОДНЯ ЛУЧШЕ СДЕЛАТЬ',a.tips)}
    ${section('🚶‍♀️ ЕСЛИ БУДЕШЬ ДОЛГО НА УЛИЦЕ',a.outdoor)}
    ${section('🏠 ЕСЛИ ВЕСЬ ДЕНЬ ДОМА',a.home)}
    ${section('🌙 ВЕЧЕРОМ ПОСЛЕ УЛИЦЫ',a.evening,'weather-evening')}
    <div class="row wrap" style="margin-top:14px">
      ${a.chips.map(c=>`<span class="tag">${esc(c)}</span>`).join('')}
      <button class="btn secondary small" data-weather-add>Добавить чек-лист дня в Сегодня</button>
    </div>
    ${w?`<p class="micro-note" style="margin-top:4px">Обновлено ${weatherFreshness(w.at)}.</p>`:''}
    <p class="micro-note">Советы пересчитываются по температуре, ощущаемой температуре, влажности, ветру, осадкам, вероятности дождя и UV — а «Специально для тебя» ещё и по твоему типу кожи и волос из настроек. Это beauty-рекомендации по уходу, а не медицинские назначения.</p>
  </section>`;
}
function weatherFreshness(ts){
  const min=Math.round((Date.now()-Number(ts||0))/60000);
  if(!Number.isFinite(min)||min<1)return 'только что';
  if(min<60)return `${min} мин назад`;
  const h=Math.round(min/60);
  return `${h} ч назад`;
}
function addWeatherRecommendation(){
  const a=weatherAdvice();
  const items=[];
  items.push({title:a.title,notes:a.text});
  if(a.personal?.[0]) items.push({title:'🎯 '+a.personal[0].text.split(':')[0]+' — под твой тип',notes:a.personal[0].text});
  if(a.tips?.[0]) items.push({title:'✨ Совет дня по погоде',notes:a.tips[0].text});
  if(a.evening?.[0]) items.push({title:'🌙 Вечером после улицы',notes:a.evening[0].text});

  let added=0;
  for(const it of items.slice(0,3)){
    const exists=data.routines.some(r=>r.title===it.title && r.startDate===todayKey());
    if(exists)continue;
    data.routines.push({id:uid(),startDate:todayKey(),title:it.title,category:'skin',slot:'extra',days:[new Date().getDay()],time:'15:00',frequency:'custom',customDate:todayKey(),notes:it.notes,productId:''});
    added++;
  }
  if(!added){toast('Этот чек-лист уже есть в Today ♡');return;}
  save();toast(`Добавлено в Today: ${added} пункт${added===1?'':added<5?'а':'ов'} ♡`);render();
}

// Richer personality for pet.
const PET_BEHAVIOR={happy:{icon:'🥰',title:'счастливая',text:'Мими сияет вместе с тобой!'},sleepy:{icon:'😴',title:'сонная',text:'Похоже, Мими хочется уютного отдыха.'},playful:{icon:'🎉',title:'игривая',text:'Мими готова к маленькому приключению!'},lonely:{icon:'🥺',title:'скучающая',text:'Мими немного скучает. Завтра попробуем ещё раз? ♡'},proud:{icon:'✨',title:'гордая',text:'Мими гордится твоим уходом сегодня!'}};
function petBehavior(){
  const s=dayStats(todayKey()); if(s.p===100)return PET_BEHAVIOR.proud; if(data.pet.happiness<35)return PET_BEHAVIOR.lonely; if(data.pet.energy<30)return PET_BEHAVIOR.sleepy; if(data.pet.happiness>80&&data.pet.energy>60)return PET_BEHAVIOR.playful; return PET_BEHAVIOR.happy;
}

// Interfaces & premium CSS.
const premiumCss=document.createElement('style');premiumCss.textContent=`
:root{--card-blur:blur(18px)}
body{letter-spacing:.001em}.card{background:var(--surface);border-color:color-mix(in srgb,var(--border) 82%,transparent);box-shadow:0 12px 36px rgba(55,34,46,.065)}
.hero{background:linear-gradient(145deg,var(--surface),var(--surface2));box-shadow:0 18px 44px rgba(74,44,60,.08)}
[data-cardstyle="minimal"] .card,[data-cardstyle="minimal"] .item{box-shadow:0 8px 24px rgba(53,48,45,.04);border-radius:18px}
[data-cardstyle="glass"] .card{background:color-mix(in srgb,var(--surface) 76%,transparent);backdrop-filter:var(--card-blur);-webkit-backdrop-filter:var(--card-blur)}
[data-cardstyle="paper"] .card{background:linear-gradient(180deg,color-mix(in srgb,var(--surface) 94%,#fffefc),color-mix(in srgb,var(--surface2) 92%,#faf7f2));box-shadow:0 8px 20px rgba(99,79,68,.05)}
[data-density="compact"] .card{padding:14px}.content{scroll-behavior:smooth}
[data-motion="none"] #page,[data-motion="none"] .card,[data-motion="none"] .item{animation:none!important;transition:none!important}
[data-motion="soft"] .card,[data-motion="soft"] .item{animation-duration:.16s!important}
.editorial-weather{overflow:hidden;background:linear-gradient(135deg,var(--surface),var(--surface2))}
.weather-why{margin:12px 0 0;padding:11px 13px;border-radius:15px;background:color-mix(in srgb,var(--surface2) 82%,transparent);font-size:13px;color:var(--muted);line-height:1.5}
.weather-tips{display:grid;gap:8px;margin-top:14px}
.weather-advice-section{display:grid;gap:8px;margin-top:16px}
.weather-tip{display:flex;gap:10px;align-items:flex-start;padding:11px 13px;border:1px solid var(--border);border-radius:15px;background:color-mix(in srgb,var(--surface2) 74%,transparent);font-size:13px;line-height:1.5}
.weather-tip-icon{font-size:18px;flex:0 0 24px}
.weather-alerts .weather-tip{background:color-mix(in srgb,var(--danger) 8%,var(--surface2));border-color:color-mix(in srgb,var(--danger) 24%,var(--border))}
.weather-personal .weather-tip{background:color-mix(in srgb,var(--accent) 12%,var(--surface2));border-color:color-mix(in srgb,var(--accent) 28%,var(--border))}
.weather-trend .weather-tip{background:color-mix(in srgb,var(--primary2) 24%,var(--surface2));border-color:color-mix(in srgb,var(--primary) 22%,var(--border))}
.weather-evening{padding-top:2px}
.weather-big{font-size:58px;filter:drop-shadow(0 8px 16px rgba(70,50,70,.10))}.weather-meta{display:flex;flex-wrap:wrap;gap:8px;margin-top:14px}.weather-meta span{padding:8px 11px;border-radius:999px;background:rgba(255,255,255,.64);font-size:12px}.micro-note{font-size:11px;color:var(--muted);margin-top:10px}.quick-fab{position:fixed;right:22px;bottom:24px;width:62px;height:62px;border-radius:50%;z-index:90;background:linear-gradient(145deg,var(--primary),var(--accent));color:white;font-size:30px;box-shadow:0 16px 36px rgba(111,71,93,.24);transition:transform .18s ease;display:grid;place-items:center}.quick-fab:hover,.quick-fab.open{transform:rotate(45deg) scale(1.03)}.quick-panel{position:fixed;right:22px;bottom:96px;z-index:89;display:grid;gap:8px;opacity:0;pointer-events:none;transform:translateY(8px) scale(.98);transition:opacity .18s ease,transform .18s ease}.quick-panel.open{opacity:1;pointer-events:auto;transform:none}.quick-panel button{padding:12px 14px;border-radius:15px;background:var(--surface);border:1px solid var(--border);box-shadow:0 12px 28px rgba(55,34,46,.12);text-align:left;min-width:220px;color:var(--text)}.quick-panel button:hover{transform:translateY(-1px)}
.day-sheet{display:grid;gap:12px}.day-sheet h3{font-family:Georgia,serif;font-size:24px;margin:4px 0}.day-sheet .stat{background:var(--surface2)}
.metric-pop{position:fixed;z-index:260;font-weight:800;pointer-events:none;color:var(--primary);animation:metricFloat .32s ease-out both}@keyframes metricFloat{from{opacity:0;transform:translateY(0) scale(.92)}30%{opacity:1}to{opacity:0;transform:translateY(-24px) scale(1)}}
.xp-pop{position:fixed;z-index:260;pointer-events:none;padding:8px 12px;border-radius:999px;background:var(--surface);box-shadow:0 10px 25px rgba(52,32,45,.12);border:1px solid var(--border);font-weight:800;color:var(--primary);animation:xpPop .4s ease both}@keyframes xpPop{from{opacity:0;transform:translateY(6px) scale(.94)}40%{opacity:1}to{opacity:0;transform:translateY(-24px) scale(1)}}
.seasonal-atmosphere{position:fixed;inset:0;pointer-events:none;z-index:0;opacity:.12;background:radial-gradient(circle at 10% 10%,rgba(255,180,205,.8),transparent 18%),radial-gradient(circle at 85% 15%,rgba(194,172,230,.55),transparent 16%);mix-blend-mode:multiply}.dark-seasonal{mix-blend-mode:screen;opacity:.06}
.topbar,.content,.sidebar{position:relative;z-index:1}
@media(max-width:640px){.quick-fab{right:16px;bottom:84px}.quick-panel{right:16px;bottom:158px}.quick-panel button{min-width:210px}.weather-big{font-size:46px}}
.weather-tips{display:grid;gap:8px;margin-top:16px;padding-top:14px;border-top:1px solid var(--border)}.weather-tip{display:flex;gap:10px;align-items:flex-start;padding:10px 12px;border-radius:15px;background:color-mix(in srgb,var(--surface2) 72%,transparent);line-height:1.45;font-size:13px}.weather-tip-icon{width:24px;flex:0 0 24px;font-size:17px}`;document.head.appendChild(premiumCss);

// Add seasonal atmospheric layer once.
function ensureSeasonalLayer(){
 let layer=document.getElementById('seasonalLayer');
 if(!layer){layer=document.createElement('div');layer.id='seasonalLayer';layer.className='seasonal-atmosphere';document.body.appendChild(layer);}
 layer.style.display=(data.settings.seasonalAtmosphere===false?'none':'block');
 layer.className='seasonal-atmosphere'+((data.settings.theme||'').includes('dark')||data.settings.theme==='midnight2'?' dark-seasonal':'');
}

// Expand calendar binding.
const __bindBigBeforePremium=bindBigPage;
bindBigPage=function(route){
  try{__bindBigBeforePremium(route)}catch(e){console.error(e)}
  if(route==='calendar'){
    document.querySelectorAll('[data-day]').forEach(b=>b.onclick=()=>openCalendarDay(b.dataset.day));
    document.querySelectorAll('[data-day-template]').forEach(b=>b.onclick=()=>makeCalendarTemplate(b.dataset.dayTemplate));
  }
  document.querySelectorAll('[data-weather-add]').forEach(b=>b.onclick=addWeatherRecommendation);
};

// Premium Home/Today wrappers.
const __homeBasePremium=homePage;
homePage=function(){return __homeBasePremium()+weatherPremiumCard();};
const __todayBasePremium=todayPage;
todayPage=function(){return __todayBasePremium()+weatherPremiumCard();};

// Premium settings card with UI controls and Центр данных.
const __settingsBasePremium=settingsPage;
settingsPage=function(){
  const base=__settingsBasePremium();
  return base.replace('</section></div>',`<section class="card" style="grid-column:1/-1;margin-top:16px"><div class="row between"><div><div class="label">Премиум-настройки</div><h3 class="section-title">🎨 Настройка интерфейса</h3><p class="subtle">Настрой под себя не только цвета, но и характер приложения.</p></div><span class="tag">${themes[data.settings.theme||'pink']?.name||'Тема'}</span></div><div class="grid grid-3"><div class="field"><label>Стиль карточек</label><select id="uxCardStyle"><option value="soft" ${data.settings.cardStyle==='soft'?'selected':''}>Мягкие</option><option value="minimal" ${data.settings.cardStyle==='minimal'?'selected':''}>Минимализм</option><option value="glass" ${data.settings.cardStyle==='glass'?'selected':''}>Стекло</option><option value="paper" ${data.settings.cardStyle==='paper'?'selected':''}>Бумажный журнал</option></select></div><div class="field"><label>Плотность</label><select id="uxDensity"><option value="compact" ${data.settings.density==='compact'?'selected':''}>Компактно</option><option value="comfortable" ${data.settings.density==='comfortable'?'selected':''}>Удобно</option><option value="airy" ${data.settings.density==='airy'?'selected':''}>Воздушно</option></select></div><div class="field"><label>Анимации</label><select id="uxMotion"><option value="none" ${data.settings.motion==='none'?'selected':''}>Нет</option><option value="soft" ${data.settings.motion==='soft'?'selected':''}>Немного</option><option value="full" ${data.settings.motion==='full'?'selected':''}>Полные</option></select></div></div><div class="row wrap" style="margin-top:12px"><label class="tag"><input id="seasonalAtmosphere" type="checkbox" ${data.settings.seasonalAtmosphere!==false?'checked':''}> Сезонная атмосфера</label><label class="tag"><input id="privacyMode" type="checkbox" ${data.settings.privacyMode?'checked':''}> 🔒 Приватный режим</label></div></section><section class="card" style="grid-column:1/-1;margin-top:16px"><div class="row between"><div><div class="label">Центр данных</div><h3 class="section-title">💾 Твои данные</h3><p class="subtle">Последнее сохранение: ${new Intl.DateTimeFormat('ru-RU',{dateStyle:'short',timeStyle:'short'}).format(new Date(data.settings.lastSavedAt||Date.now()))}</p></div><span class="tag">✓ Локально сохранено</span></div><div class="grid grid-3"><div class="stat"><span class="label">Процедуры</span><b>${data.routines.length}</b></div><div class="stat"><span class="label">Фото</span><b>${data.photos.length}</b></div><div class="stat"><span class="label">Средства</span><b>${data.products.length}</b></div></div><div class="row wrap" style="margin-top:12px"><button class="btn secondary" data-export>Экспортировать всё</button><label class="btn secondary" style="cursor:pointer">Импортировать<input id="importFile" type="file" accept="application/json" hidden></label></div></section></div>`);
};

// Make every save update the visible Центр данных timestamp.
const __savePremium=save;
save=function(){data.settings=data.settings||{};data.settings.lastSavedAt=Date.now();__savePremium();};

// Animated metric feedback.
function xpPop(text){
 const el=document.createElement('div');el.className='xp-pop';el.textContent=text;el.style.right='28px';el.style.top='90px';document.body.appendChild(el);setTimeout(()=>el.remove(),420);
}
const __addXPPremium=addXP;
addXP=function(n,reason){const before=Number(data.xp||0);__addXPPremium(n,reason);const delta=Math.max(0,Number(data.xp)-before);if(delta){xpPop(`+${delta} XP`);}};

// Better save feedback after important actions.
const __toastPremium=toast;
toast=function(msg){__toastPremium(msg);};

// Render wrapper: settings controls, Quick Add and atmosphere are always available.
const __renderPremiumBase=render;
render=function(){
  ensureUXData(); ensurePremiumData(); applyPremiumTheme();
  __renderPremiumBase();
  ensureSeasonalLayer(); ensureQuickAdd();
  // Apply premium selectors if settings page is visible.
  const cs=document.getElementById('uxCardStyle'); if(cs) cs.onchange=()=>{data.settings.cardStyle=cs.value;applyPremiumTheme();save();render()};
  const ds=document.getElementById('uxDensity'); if(ds) ds.onchange=()=>{data.settings.density=ds.value;applyPremiumTheme();save();render()};
  const ms=document.getElementById('uxMotion'); if(ms) ms.onchange=()=>{data.settings.motion=ms.value;applyPremiumTheme();save();render()};
  const sa=document.getElementById('seasonalAtmosphere'); if(sa) sa.onchange=()=>{data.settings.seasonalAtmosphere=sa.checked;save();applyPremiumTheme();render()};
  const pm=document.getElementById('privacyMode'); if(pm) pm.onchange=()=>{data.settings.privacyMode=pm.checked;save();toast(pm.checked?'Приватный режим включён 🔒':'Приватный режим выключен');};
};

// More drawer includes the new quick spaces.
openMore=function(){
  const links=[['products','🧴 Средства'],['favorites','💗 Любимчики'],['shop','🛍️ Бьюти-магазин'],['luck','🎡 Удача'],['calendar','📅 Календарь'],['achievements','✦ Достижения'],['goals','🎯 Цели'],['journal','✎ Дневник'],['pet','🐾 Питомец'],['challenges','🏆 Челленджи'],['tips','💡 Советы'],['articles','📖 Статьи'],['reports','📊 Отчёты'],['settings','⚙ Настройки']];
  modal(`<h3>Ещё ♡</h3><div class="list">${links.map(([id,t])=>`<button class="btn secondary" data-more-premium="${id}">${t}</button>`).join('')}</div>`);
  document.querySelectorAll('[data-more-premium]').forEach(b=>b.onclick=()=>{closeModal();location.hash=b.dataset.morePremium});
};

// Rebind expanded More.
window.addEventListener('hashchange',()=>{setTimeout(()=>{ensureQuickAdd();ensureSeasonalLayer()},0)});

// Initial premium render (after all overrides).
ensureUXData();ensurePremiumData();applyPremiumTheme();render();



/* ==================== PREMIUM BEAUTY UPDATE 3.0 ==================== */

// ---------- Robust local state for interface / pet room / shop ----------
function ensureUpdate3Data(){
  ensureUXData(); ensurePremiumData();
  data.settings=data.settings||{};
  data.settings.uiVersion=3;
  data.settings.cardStyle=data.settings.cardStyle||'soft';
  data.settings.density=data.settings.density||'comfortable';
  data.settings.motion=data.settings.motion||'soft';
  data.settings.seasonalAtmosphere=data.settings.seasonalAtmosphere!==false;
  data.settings.privacyMode=!!data.settings.privacyMode;
  data.settings.lastSavedAt=data.settings.lastSavedAt||Date.now();
  data.ui=data.ui||{};
  data.ui.language='ru';
  data.ui.statsExpanded=!!data.ui.statsExpanded;
  data.ui.shopFilter=data.ui.shopFilter||'all';
  data.ui.petFurnitureFilter=data.ui.petFurnitureFilter||'all';
  data.ui.furnitureColor=data.ui.furnitureColor||'blush';
  data.shop=data.shop||{};
  data.shop.owned=Array.isArray(data.shop.owned)?data.shop.owned:[];
  data.shop.equipped=data.shop.equipped||{};
  data.shop.dailyDate=data.shop.dailyDate||'';
  data.shop.dailyId=data.shop.dailyId||'';
  data.shop.dailyDiscount=Number(data.shop.dailyDiscount)||20;
  data.shop.collections=data.shop.collections||{};
  data.pet=data.pet||{};
  data.pet.stage=Math.max(1,Math.min(10,Number(data.pet.stage||1)));
  data.pet.room=data.pet.room||'room-pink';
  data.pet.roomFurniture=data.pet.roomFurniture&&typeof data.pet.roomFurniture==='object'?data.pet.roomFurniture:{};
  data.pet.roomColor=data.pet.roomColor||'blush';
  data.pet.behavior=data.pet.behavior||'счастливая';
  data.pet.affection=Number(data.pet.affection||data.pet.bond||0);
  data.pet.bond=Number(data.pet.bond||data.pet.affection||0);
  data.pet.accessories=Array.isArray(data.pet.accessories)?data.pet.accessories:[];
  data.logs=data.logs||{};
}
ensureUpdate3Data();

// ---------- Localized visible vocabulary ----------
const RU_TEXT={
  'Бьюти-магазин':'Бьюти-магазин','Бьюти-магазин 2.0':'Бьюти-магазин 2.0','ТОП СРЕДСТВ':'ТОП СРЕДСТВ','Премиум-настройки':'Премиум-настройки',
  'Центр данных':'Центр данных','Сезонная атмосфера':'Сезонная атмосфера','Стекло':'Стекло','Бумажный журнал':'Бумажный журнал',
  'Полуночная красота':'Полуночная красота','Розовая спальня':'Розовая спальня','Лавандовый спа':'Лавандовый спа','Сияющий сад':'Сияющий сад',
  'Облачная ванная':'Облачная ванная','Гардероб с бантиками':'Гардероб с бантиками','Сад игрушек':'Сад игрушек','Куплю снова':'Куплю снова',
  'Сейчас люблю':'Сейчас люблю','Чаще всего использую':'Чаще всего использую','Самая высокая оценка':'Самая высокая оценка','Open':'Открыть','NEW':'НОВОЕ',
  'RARE':'РЕДКОЕ','EPIC':'ЭПИЧЕСКОЕ','LEGENDARY':'ЛЕГЕНДАРНОЕ','SECRET':'СЕКРЕТНОЕ','AUTO':'АВТО'
};
function translateVisibleText(){
  const root=document.getElementById('app'); if(!root) return;
  const walker=document.createTreeWalker(root,NodeFilter.SHOW_TEXT);
  const nodes=[]; while(walker.nextNode()) nodes.push(walker.currentNode);
  for(const n of nodes){ let t=n.nodeValue; for(const [a,b] of Object.entries(RU_TEXT)) t=t.replaceAll(a,b); n.nodeValue=t; }
  document.title='Мой Бьюти-дневник — личный дневник красоты';
}

// ---------- 35+ furniture / decor items ----------
const FURNITURE_CATALOG=[
 {id:'f01',title:'Розовая кровать',icon:'🛏️',cost:180,rarity:'Обычный',colors:['blush','cream','lavender']},
 {id:'f02',title:'Лавандовая кровать',icon:'🛏️',cost:260,rarity:'Редкий',colors:['lavender','cream','mint']},
 {id:'f03',title:'Кровать с балдахином',icon:'🛏️',cost:520,rarity:'Эпический',colors:['blush','lavender','midnight']},
 {id:'f04',title:'Мягкое кресло',icon:'🪑',cost:160,rarity:'Обычный',colors:['blush','cream','mint']},
 {id:'f05',title:'Кресло-облако',icon:'🪑',cost:380,rarity:'Редкий',colors:['cream','lavender','mint']},
 {id:'f06',title:'Туалетный столик',icon:'🪞',cost:420,rarity:'Редкий',colors:['cream','blush','lavender']},
 {id:'f07',title:'Большое зеркало',icon:'🪞',cost:320,rarity:'Редкий',colors:['cream','blush','midnight']},
 {id:'f08',title:'Маленькое зеркало',icon:'🪞',cost:150,rarity:'Обычный',colors:['cream','mint','lavender']},
 {id:'f09',title:'Тумба',icon:'🗄️',cost:140,rarity:'Обычный',colors:['blush','cream','lavender']},
 {id:'f10',title:'Комод',icon:'🗄️',cost:300,rarity:'Редкий',colors:['cream','blush','mint']},
 {id:'f11',title:'Полка для косметики',icon:'🧴',cost:240,rarity:'Обычный',colors:['cream','blush','lavender']},
 {id:'f12',title:'Витрина красоты',icon:'🪟',cost:580,rarity:'Эпический',colors:['cream','lavender','midnight']},
 {id:'f13',title:'Растение в горшке',icon:'🪴',cost:120,rarity:'Обычный',colors:['mint','blush','cream']},
 {id:'f14',title:'Большой вазон',icon:'🌿',cost:220,rarity:'Обычный',colors:['mint','cream','lavender']},
 {id:'f15',title:'Ваза с цветами',icon:'💐',cost:190,rarity:'Обычный',colors:['blush','lavender','mint']},
 {id:'f16',title:'Розовый букет',icon:'🌷',cost:150,rarity:'Обычный',colors:['blush','cream','lavender']},
 {id:'f17',title:'Лавандовый букет',icon:'🪻',cost:170,rarity:'Обычный',colors:['lavender','cream','mint']},
 {id:'f18',title:'Неоновая вывеска',icon:'💡',cost:440,rarity:'Редкий',colors:['blush','lavender','midnight']},
 {id:'f19',title:'Свеча',icon:'🕯️',cost:110,rarity:'Обычный',colors:['cream','blush','lavender']},
 {id:'f20',title:'Свечи дуэтом',icon:'🕯️',cost:200,rarity:'Обычный',colors:['cream','blush','midnight']},
 {id:'f21',title:'Мягкий пуф',icon:'🟣',cost:180,rarity:'Обычный',colors:['blush','lavender','mint']},
 {id:'f22',title:'Пушистый ковёр',icon:'◻️',cost:280,rarity:'Редкий',colors:['cream','blush','lavender']},
 {id:'f23',title:'Зеркальный ковёр',icon:'◽',cost:450,rarity:'Эпический',colors:['lavender','midnight','cream']},
 {id:'f24',title:'Картина «Цветы»',icon:'🖼️',cost:160,rarity:'Обычный',colors:['blush','lavender','mint']},
 {id:'f25',title:'Картина «Луна»',icon:'🌙',cost:300,rarity:'Редкий',colors:['midnight','lavender','cream']},
 {id:'f26',title:'Сердце на стену',icon:'💗',cost:180,rarity:'Обычный',colors:['blush','lavender','cream']},
 {id:'f27',title:'Фонтанчик',icon:'⛲',cost:620,rarity:'Эпический',colors:['mint','lavender','midnight']},
 {id:'f28',title:'Мини-ванна',icon:'🛁',cost:520,rarity:'Эпический',colors:['cream','blush','lavender']},
 {id:'f29',title:'Бьюти-тележка',icon:'🛒',cost:360,rarity:'Редкий',colors:['cream','blush','mint']},
 {id:'f30',title:'Стойка с полотенцами',icon:'🧺',cost:210,rarity:'Обычный',colors:['cream','blush','lavender']},
 {id:'f31',title:'Игрушечная коробка',icon:'🧸',cost:230,rarity:'Обычный',colors:['blush','mint','lavender']},
 {id:'f32',title:'Когтеточка',icon:'🧶',cost:270,rarity:'Редкий',colors:['cream','blush','mint']},
 {id:'f33',title:'Большой домик',icon:'🏠',cost:640,rarity:'Эпический',colors:['blush','lavender','mint']},
 {id:'f34',title:'Королевский трон',icon:'👑',cost:1200,rarity:'Легендарный',colors:['lavender','blush','midnight']},
 {id:'f35',title:'Хрустальная люстра',icon:'✨',cost:980,rarity:'Легендарный',colors:['cream','lavender','midnight']},
 {id:'f36',title:'Секретная звезда',icon:'🌟',cost:1400,rarity:'Секретный',colors:['midnight','lavender','blush']}
];
for(const f of FURNITURE_CATALOG) if(!data.shop.owned.includes(f.id) && false) data.shop.owned.push(f.id);
const FURN_COLORS={blush:'#f3b7c7',cream:'#f3e8da',lavender:'#c9b6df',mint:'#b4dbc9',midnight:'#3b3145'};

// ---------- Additional achievements, including 30-day goals ----------
const UPDATE3_ACHIEVEMENTS=[
 {id:'streak30-strong',title:'30 дней вместе',desc:'Поддерживай серию 30 дней.',icon:'🔥',cat:'Серии',check:()=>bestStreak()>=30},
 {id:'care30',title:'Месяц заботы',desc:'Имей хотя бы один выполненный этап в 30 разных днях.',icon:'🌸',cat:'30 дней',check:()=>Object.keys(data.logs).filter(k=>dayStats(k).done.length>0).length>=30},
 {id:'perfect30',title:'Тридцать идеальных',desc:'Выполни весь план дня 30 раз.',icon:'✨',cat:'30 дней',check:()=>bestPerfectDays()>=30},
 {id:'photo30',title:'Тридцатый кадр',desc:'Добавь 30 фотографий прогресса.',icon:'📸',cat:'Фото',check:()=>data.photos.length>=30},
 {id:'procedures100',title:'Сто маленьких шагов',desc:'Выполни 100 процедур.',icon:'💗',cat:'Привычки',check:()=>totalCompleted()>=100},
 {id:'procedures250',title:'Большая приверженность',desc:'Выполни 250 процедур.',icon:'👑',cat:'Привычки',check:()=>totalCompleted()>=250},
 {id:'pet300',title:'Триста заботы',desc:'Набери 300 очков заботы о питомце.',icon:'🐾',cat:'Питомец',check:()=>data.pet.points>=300},
 {id:'shop10',title:'Полка коллекционера',desc:'Собери 10 предметов магазина.',icon:'🛍️',cat:'Коллекция',check:()=>data.shop.owned.length>=10},
 {id:'shop25',title:'Большая коллекция',desc:'Собери 25 предметов магазина.',icon:'💎',cat:'Коллекция',check:()=>data.shop.owned.length>=25},
 {id:'furniture10',title:'Интерьерист',desc:'Собери 10 предметов мебели.',icon:'🏠',cat:'Питомец',check:()=>data.shop.owned.filter(id=>FURNITURE_CATALOG.some(f=>f.id===id)).length>=10},
 {id:'furniture30',title:'Дизайнер мира',desc:'Собери 30 предметов мебели.',icon:'🪞',cat:'Питомец',check:()=>data.shop.owned.filter(id=>FURNITURE_CATALOG.some(f=>f.id===id)).length>=30},
 {id:'luck15',title:'Удачливая привычка',desc:'Используй колесо 15 раз.',icon:'🎡',cat:'Удача',check:()=>Number(data.luck?.spinCount||0)>=15}
];
for(const a of UPDATE3_ACHIEVEMENTS) if(!achievementDefs.some(x=>x.id===a.id)) achievementDefs.push(a);

// ---------- More challenges ----------
const UPDATE3_CHALLENGES=[
 {id:'u31',title:'30 дней мягкости',description:'30 разных дней с выполненной процедурой.',goal:30,progress:0,reward:400,type:'auto-care-days',icon:'🌸',builtIn:true,cat:'habit'},
 {id:'u32',title:'30 идеальных вечеров',description:'30 раз заверши весь вечерний блок.',goal:30,progress:0,reward:500,type:'auto-evening',icon:'🌙',builtIn:true,cat:'habit'},
 {id:'u33',title:'30 утренних ритуалов',description:'30 раз заверши весь утренний блок.',goal:30,progress:0,reward:500,type:'auto-morning',icon:'☀️',builtIn:true,cat:'habit'},
 {id:'u34',title:'100 процедур',description:'Выполни 100 этапов ухода.',goal:100,progress:0,reward:450,type:'auto-total',icon:'💗',builtIn:true,cat:'habit'},
 {id:'u35',title:'50 фотографий',description:'Собери 50 фото в beauty-дневнике.',goal:50,progress:0,reward:420,type:'auto-photos',icon:'📸',builtIn:true,cat:'habit'},
 {id:'u36',title:'10 любимчиков',description:'Добавь 10 средств в любимчики.',goal:10,progress:0,reward:250,type:'auto-favorites',icon:'💞',builtIn:true,cat:'skin'},
 {id:'u37',title:'20 оценок',description:'Оцени 20 средств.',goal:20,progress:0,reward:250,type:'auto-rated',icon:'⭐',builtIn:true,cat:'habit'},
 {id:'u38',title:'10 предметов комнаты',description:'Собери 10 предметов мебели.',goal:10,progress:0,reward:300,type:'auto-furniture',icon:'🏠',builtIn:true,cat:'pet'},
 {id:'u39',title:'30 предметов комнаты',description:'Собери 30 предметов мебели.',goal:30,progress:0,reward:650,type:'auto-furniture',icon:'🪞',builtIn:true,cat:'pet'},
 {id:'u40',title:'10 побед питомца',description:'Набери 10 успешных игровых действий с питомцем.',goal:10,progress:0,reward:180,type:'auto-pet-actions',icon:'🐾',builtIn:true,cat:'pet'},
 {id:'u41',title:'15 вращений',description:'Крути колесо удачи 15 раз.',goal:15,progress:0,reward:220,type:'auto-wheel',icon:'🎡',builtIn:true,cat:'habit'},
 {id:'u42',title:'5 полных коллекций',description:'Собери 5 тематических коллекций целиком.',goal:5,progress:0,reward:500,type:'auto-collections',icon:'👑',builtIn:true,cat:'habit'}
];
for(const c of UPDATE3_CHALLENGES) if(!data.challenges.some(x=>x.id===c.id)) data.challenges.push(c);

// Make challenge progress understand furniture / pet actions / collections.
const __refreshChallenges3=refreshBigChallenges;
refreshBigChallenges=function(){
  ensureUpdate3Data();
  const careDays=Object.keys(data.logs).filter(k=>dayStats(k).done.length>0).length;
  const furnitureCount=data.shop.owned.filter(id=>FURNITURE_CATALOG.some(f=>f.id===id)).length;
  const petActions=Number(data.pet.feedCount||0)+Number(data.pet.playCount||0);
  const collectionCount=computeCollectionCount3();
  for(const c of data.challenges){
    if(c.done) continue;
    let p=c.progress||0;
    if(c.type==='auto-furniture') p=furnitureCount;
    else if(c.type==='auto-pet-actions') p=petActions;
    else if(c.type==='auto-collections') p=collectionCount;
    else {
      // use the established engine for all existing types
      switch(c.type){
        case'auto-streak':p=bestStreak();break;case'auto-photos':p=data.photos.length;break;case'auto-care-days':p=careDays;break;
        case'auto-evening':p=Object.keys(data.logs).filter(k=>{const rs=entriesForDay(k).filter(r=>r.slot==='evening');return rs.length>0&&rs.every(r=>isDone(k,r.id))}).length;break;
        case'auto-morning':p=Object.keys(data.logs).filter(k=>{const rs=entriesForDay(k).filter(r=>r.slot==='morning');return rs.length>0&&rs.every(r=>isDone(k,r.id))}).length;break;
        case'auto-spf':p=Object.entries(data.logs).flatMap(([k,arr])=>(arr||[]).filter(x=>x.done).map(x=>data.routines.find(r=>r.id===x.id))).filter(r=>r&&String(r.title||'').toLowerCase().includes('spf')).length;break;
        case'auto-total':p=totalCompleted();break;case'auto-skin':p=completedByCat('skin');break;case'auto-hair':p=completedByCat('hair');break;
        case'auto-pet-points':p=data.pet.points;break;case'auto-shop':p=data.shop.owned.length;break;case'auto-rated':p=Object.values(data.productRatings||{}).filter(x=>x.score>0).length;break;
        case'auto-favorites':p=data.favoriteProducts.length;break;case'auto-articles':p=Object.keys(data.articleReads||{}).length;break;case'auto-weather':p=Number(data.weatherChecks||0);break;case'auto-wheel':p=Number(data.luck?.spinCount||0);break;
      }
    }
    c.progress=Math.min(c.goal,p);
    if(c.progress>=c.goal&&!c.done){c.done=true;addXP(c.reward||0,`Челлендж «${c.title}»`);toast(`Челлендж «${c.title}» завершён 🏆`)}
  }
  save();
};
function computeCollectionCount3(){
  const groups={};
  SHOP_CATALOG.forEach(x=>{const c=x.collection||x.type||'Общее';(groups[c]??=[]).push(x.id)});
  return Object.values(groups).filter(ids=>ids.length>=2&&ids.every(id=>data.shop.owned.includes(id))).length;
}

// ---------- Collections + 10 named collections ----------
const COLLECTIONS3=[
 {id:'pink',title:'Розовая мечта 🎀',ids:['pet-bow-pink','frame-pearl','badge-glow','room-pink']},
 {id:'lavender',title:'Лавандовый сон 🪻',ids:['pet-lilacroom','f01','f02','f17']},
 {id:'midnight',title:'Полуночное сияние 🌙',ids:['theme-midnight','secret-moon','f25','f36']},
 {id:'spring',title:'Весенний сад 🌷',ids:['f13','f15','f16','f27']},
 {id:'cozy',title:'Уютная осень 🍂',ids:['f19','f20','f22','f31']},
 {id:'spa',title:'Домашний спа-день 🛁',ids:['f06','f07','f28','f30']},
 {id:'royal',title:'Королевская коллекция 👑',ids:['pet-crown','f34','f35','frame-dream']},
 {id:'dream',title:'Облачная мечта ☁️',ids:['pet-cloudbg','f05','f23','f35']},
 {id:'mint',title:'Мятное утро 🍃',ids:['theme-mint','f14','f21','f29']},
 {id:'collector',title:'Большая витрина 💎',ids:['f12','f18','f33','f34']}
];
for(const col of COLLECTIONS3){ for(const id of col.ids){const it=SHOP_CATALOG.find(x=>x.id===id)||FURNITURE_CATALOG.find(x=>x.id===id); if(it && !SHOP_CATALOG.some(x=>x.id===id))SHOP_CATALOG.push({...it,collection:col.id});} }
function collectionProgress3(col){const got=col.ids.filter(id=>data.shop.owned.includes(id)).length;return {got,total:col.ids.length,pct:Math.round(got/col.ids.length*100)};}

// ---------- Make every collection item purchasable in the Beauty Shop ----------
function ensureCollectionItemsInShop3(){
  const byId=new Map(SHOP_CATALOG.map(x=>[x.id,x]));
  for(const col of COLLECTIONS3){
    for(const id of col.ids){
      if(byId.has(id)) continue;
      const furniture=FURNITURE_CATALOG.find(x=>x.id===id);
      if(furniture){
        const item={...furniture,type:'furniture',collection:col.id,desc:'Мебель и декор для комнаты питомца.'};
        SHOP_CATALOG.push(item);
        byId.set(id,item);
      }
    }
  }
  for(const col of COLLECTIONS3){
    for(const id of col.ids){
      const item=byId.get(id);
      if(item && !item.collection) item.collection=col.id;
    }
  }
}
ensureCollectionItemsInShop3();

// ---------- 15 wheel prizes ----------
LUCK_PRIZES.splice(0,LUCK_PRIZES.length,
 {id:'xp10',title:'+10 XP',icon:'✨',type:'xp',value:10},
 {id:'xp25',title:'+25 XP',icon:'💗',type:'xp',value:25},
 {id:'xp50',title:'+50 XP',icon:'🌸',type:'xp',value:50},
 {id:'xp75',title:'+75 XP',icon:'🎀',type:'xp',value:75},
 {id:'xp100',title:'+100 XP',icon:'👑',type:'xp',value:100},
 {id:'xp150',title:'+150 XP',icon:'💎',type:'xp',value:150},
 {id:'xp200',title:'+200 XP',icon:'🌟',type:'xp',value:200},
 {id:'feed',title:'Покормить питомца',icon:'🍓',type:'feed'},
 {id:'play',title:'Поиграть с питомцем',icon:'🎀',type:'play'},
 {id:'bond',title:'+5 привязанности',icon:'🤍',type:'bond',value:5},
 {id:'rare',title:'Редкий предмет',icon:'🎁',type:'rare'},
 {id:'furn',title:'Мебель для комнаты',icon:'🪑',type:'furniture'},
 {id:'theme',title:'Предмет для темы',icon:'🎨',type:'theme'},
 {id:'double',title:'Бонус x2 к следующему XP',icon:'⚡',type:'booster'},
 {id:'nothing',title:'Ничего… но красиво ♡',icon:'🌙',type:'nothing'}
);
function renderLuck3(){
 ensureUpdate3Data(); const used=data.luck?.lastSpin===todayKey();
 const wheel=LUCK_PRIZES.map((p,i)=>`<div class="wheel-label wheel-label-small" style="--i:${i}"><img src="${makePrizePng(p.icon)}" alt=""><span>${esc(p.title)}</span></div>`).join('');
 return `<section class="card hero"><div class="row between wrap"><div><div class="label">Ежедневный бонус</div><h1 style="font-family:Georgia,serif;margin:4px 0">🎡 Колесо удачи</h1><p>${used?'Сегодня бонус уже забран. Возвращайся завтра ♡':'Одно вращение в день — маленький приятный бонус.'}</p></div><span class="tag">${used?'✓ Использовано сегодня':'♡ 1 вращение сегодня'}</span></div></section>
 <div class="grid grid-2" style="margin-top:16px"><section class="card luck-card luck-card-compact"><div class="wheel-wrap wheel-wrap-compact"><div class="wheel-pointer">▼</div><div id="luckWheel" class="luck-wheel luck-wheel-small">${wheel}<div class="wheel-center">♡<small>УДАЧА</small></div></div></div><button class="btn" id="spinWheel" ${used?'disabled':''}>${used?'Завтра снова ♡':'Крутить колесо ✨'}</button><p class="subtle">Один раз в сутки. Результат сохраняется сразу.</p></section><section class="card"><div class="row between"><h3 class="section-title">🎁 Все призы</h3><span class="tag">15 вариантов</span></div><div class="grid grid-2 prize-grid">${LUCK_PRIZES.map((p,i)=>`<div class="item row"><img class="prize-png" src="${makePrizePng(p.icon)}" alt=""><div><strong>${esc(p.title)}</strong><div class="subtle">Сектор ${i+1}</div></div></div>`).join('')}</div></section></div>`;
}
luckPage=renderLuck3;

const __spinWheel3=spinWheel;
spinWheel=function(){
  ensureUpdate3Data();
  const el=document.getElementById('luckWheel'); if(!el) return __spinWheel3();
  // Temporarily use the current prize list and add support for new prize types.
  if(data.luck.lastSpin===todayKey()){toast('Колесо уже кручено сегодня ♡');return;}
  playSound('wheel');
  const idx=Math.floor(Math.random()*LUCK_PRIZES.length), seg=360/LUCK_PRIZES.length;
  el.style.setProperty('--luck-rotation',`${360*7 + idx*seg}deg`);
  el.style.transform=`rotate(${360*7 + idx*seg}deg)`;
  const btn=document.getElementById('spinWheel');if(btn)btn.disabled=true;
  setTimeout(()=>{
    const prize=LUCK_PRIZES[idx]; data.luck.lastSpin=todayKey();data.luck.spinCount=(data.luck.spinCount||0)+1;data.luck.totalWins=(data.luck.totalWins||0)+1;
    if(prize.type==='xp')addXP(prize.value,'Колесо удачи');
    else if(prize.type==='feed')petFeedFromWheel();
    else if(prize.type==='play')petPlayFromWheel();
    else if(prize.type==='bond'){data.pet.affection=Math.min(100,data.pet.affection+5);data.pet.bond+=5;data.pet.points+=8;checkPetEvolution()}
    else if(prize.type==='rare'||prize.type==='furniture'||prize.type==='theme'){
      const pool=prize.type==='furniture'?FURNITURE_CATALOG.filter(x=>!data.shop.owned.includes(x.id)):SHOP_CATALOG.filter(x=>(prize.type==='theme'?x.type==='theme':x.rarity==='Редкий')&&!data.shop.owned.includes(x.id));
      if(pool.length){const it=pool[Math.floor(Math.random()*pool.length)];data.shop.owned.push(it.id);toast(`Подарок: ${it.title} ${it.icon}`)} else addXP(75,'Подарок колеса');
    }
    else if(prize.type==='booster'){data.luck.xpBoost=2;data.luck.xpBoostUntil=Date.now()+86400000;toast('Следующий XP-бонус удвоен ⚡')}
    refreshBigChallenges();checkAchievements();save();playSound(prize.type==='nothing'?'soft':'win');toast(`Выпало: ${prize.title} ${prize.icon}`);render();
  },3200);
};

// ---------- 30-day statistics with expandable chart + conclusions ----------
function statsChart3(){
 const days=statsRange(30); const W=860,H=260, pad=28; const vals=days.map(x=>x.p); const max=100; const pts=vals.map((v,i)=>`${pad+i*((W-pad*2)/29)},${H-pad-(v/max)*(H-pad*2)}`).join(' ');
 const bars=days.map((x,i)=>{const h=Math.max(4,(x.p/100)*(H-pad*2));const bw=Math.max(4,(W-pad*2)/30-4);return `<rect x="${pad+i*((W-pad*2)/29)-bw/2}" y="${H-pad-h}" width="${bw}" height="${h}" rx="5" fill="url(#g)" opacity=".18"/>`}).join('');
 return `<div class="stats-chart-wrap"><svg viewBox="0 0 ${W} ${H}" role="img" aria-label="График выполнения ухода за 30 дней"><defs><linearGradient id="g" x1="0" x2="1"><stop offset="0" stop-color="var(--primary)"/><stop offset="1" stop-color="var(--accent)"/></linearGradient></defs>${[25,50,75,100].map(v=>`<line x1="${pad}" y1="${H-pad-(v/max)*(H-pad*2)}" x2="${W-pad}" y2="${H-pad-(v/max)*(H-pad*2)}" stroke="var(--border)" stroke-width="1"/>`).join('')}${bars}<polyline points="${pts}" fill="none" stroke="url(#g)" stroke-width="5" stroke-linecap="round" stroke-linejoin="round"/>${vals.map((v,i)=>{if(i%3!==0&&i!==29)return '';const x=pad+i*((W-pad*2)/29),y=H-pad-(v/max)*(H-pad*2);return `<circle cx="${x}" cy="${y}" r="4.5" fill="var(--surface)" stroke="var(--primary)" stroke-width="3"><title>${days[i].date}: ${v}%</title></circle>`}).join('')}</svg></div>`;
}
function statsConclusions3(){
 const d=statsRange(30), avg=Math.round(d.reduce((s,x)=>s+x.p,0)/Math.max(1,d.length)), best=Math.max(...d.map(x=>x.p),0), active=d.filter(x=>x.done.length>0).length, p0=d.slice(0,15).reduce((s,x)=>s+x.p,0)/15, p1=d.slice(15).reduce((s,x)=>s+x.p,0)/15;
 const trend=Math.round(p1-p0); const lead=trend>4?'Последние две недели выглядят стабильнее первых двух.':trend<-4?'В первой половине периода уход был стабильнее — можно вернуть этот ритм.':'Ритм за месяц довольно ровный.';
 return `<div class="grid grid-4"><div class="stat"><span class="label">Среднее за 30 дней</span><b>${avg}%</b></div><div class="stat"><span class="label">Лучший день</span><b>${best}%</b></div><div class="stat"><span class="label">Дней с уходом</span><b>${active}/30</b></div><div class="stat"><span class="label">Динамика</span><b>${trend>=0?'+':''}${trend}%</b></div></div><div class="item" style="margin-top:12px"><strong>🪞 Вывод</strong><p class="subtle" style="margin-top:6px">${lead} Сейчас среднее выполнение — ${avg}%. ${currentStreak()>=7?'Ты уже держишь хороший ритм — продолжай.':'Главная точка роста — регулярность, а не максимальное количество процедур.'}</p></div>`;
}
const __progressPage3Base=progressPage;
progressPage=function(){
  const base=__progressPage3Base();
  const details=`<section class="card stats-premium" style="margin-top:16px"><div class="row between wrap"><div><div class="label">Подробная статистика</div><h3 class="section-title">📈 30 дней — график и выводы</h3><p class="subtle">Разверни, чтобы увидеть динамику ухода по дням.</p></div><button class="btn secondary" id="toggleStats30">${data.ui.statsExpanded?'Свернуть':'Развернуть график'}</button></div><div id="stats30Panel" style="display:${data.ui.statsExpanded?'block':'none'};margin-top:16px">${statsChart3()}${statsConclusions3()}</div></section>`;
  return base+details;
};

// ---------- Pet room with furniture placement and color changes ----------
function petRoom3(){
 ensureUpdate3Data();
 const colors=Object.entries(FURN_COLORS).map(([k,v])=>`<button class="color-dot" title="${k}" data-room-color="${k}" style="background:${v}"></button>`).join('');
 const owned=FURNITURE_CATALOG.filter(f=>data.shop.owned.includes(f.id));
 const placed=owned.filter(f=>data.pet.roomFurniture[f.id]);
 const canvas=placed.map(f=>{const cfg=data.pet.roomFurniture[f.id];const x=Number(cfg.x??40),y=Number(cfg.y??40);return `<button class="room-furniture placed-furniture" data-place-furniture="${f.id}" style="left:${x}%;top:${y}%;--fcolor:${FURN_COLORS[cfg.color||'blush']||FURN_COLORS.blush}" title="${esc(f.title)}">${f.icon}</button>`}).join('');
 return `<section class="card"><div class="row between wrap"><div><div class="label">Мир питомца</div><h3 class="section-title">🏠 Редактор комнаты</h3><p class="subtle">Купи предметы в магазине, поставь их и меняй цвет мебели.</p></div><div class="row wrap"><span class="tag">${placed.length}/${owned.length} установлено</span><button class="btn secondary" data-route="shop">В магазин</button></div></div><div class="room-editor"><div class="room-scene" id="roomScene">${canvas||'<div class="room-empty">Выбери мебель в магазине ✦<br><span>Тапни по предмету — он появится в комнате.</span></div>'}</div></div><div class="row wrap" style="margin-top:12px"><span class="label">Цвет выбранной мебели</span>${colors}</div><div class="grid grid-3" style="margin-top:14px">${owned.map(f=>{const on=!!data.pet.roomFurniture[f.id], cfg=data.pet.roomFurniture[f.id]||{};return `<div class="item"><div class="row between"><span style="font-size:30px">${f.icon}</span><span class="tag">${f.rarity}</span></div><strong>${esc(f.title)}</strong><div class="row wrap" style="margin-top:8px"><button class="btn secondary small" data-place-toggle="${f.id}">${on?'Убрать':'Поставить'}</button>${on?`<button class="btn ghost small" data-cycle-color="${f.id}">🎨 Цвет</button>`:''}</div></div>`}).join('')||'<div class="empty" style="grid-column:1/-1">Купи первую мебель в Бьюти-магазине.</div>'}</div></section>`;
}

const __enhancedPetPage3=enhancedPetPage;
enhancedPetPage=function(){return __enhancedPetPage3()+`<section class="card" style="margin-top:16px">${petRoom3()}</section>`};

function buyFurniture3(id){
 const item=FURNITURE_CATALOG.find(x=>x.id===id); if(!item)return;
 if(data.shop.owned.includes(id)){toast('Этот предмет уже у тебя ♡');return}
 const cost=item.cost;
 if(Number(data.xp)<cost){toast(`Не хватает ${cost-Number(data.xp)} XP`);return}
 data.xp=Math.max(0,Number(data.xp)-cost);data.shop.owned.push(id);data.pet.roomFurniture[id]={x:20+Math.random()*60,y:25+Math.random()*55,color:item.colors?.[0]||'blush'};save();checkAchievements();refreshBigChallenges();toast(`${item.title} добавлен в комнату 🏠`);render();
}
function toggleFurniture3(id){
 if(!data.shop.owned.includes(id))return; if(data.pet.roomFurniture[id])delete data.pet.roomFurniture[id];else data.pet.roomFurniture[id]={x:20+Math.random()*60,y:25+Math.random()*55,color:'blush'};save();render();
}
function cycleFurnitureColor3(id){const f=FURNITURE_CATALOG.find(x=>x.id===id);if(!f)return;const cfg=data.pet.roomFurniture[id]||(data.pet.roomFurniture[id]={x:40,y:40,color:'blush'});const list=f.colors&&f.colors.length?f.colors:['blush','cream','lavender'];const i=Math.max(0,list.indexOf(cfg.color));cfg.color=list[(i+1)%list.length];save();render();}
function setRoomColor3(c){
 const selected=document.querySelector('.placed-furniture.is-selected'); if(selected){const id=selected.dataset.placeFurniture;const cfg=data.pet.roomFurniture[id];if(cfg){cfg.color=c;save();render();return}}
 data.pet.roomColor=c;save();render();
}

// ---------- Shop 2.0: filters, collections, furniture ----------
function ensureShopDaily3(){
 ensureUpdate3Data(); const key=todayKey(); if(data.shop.dailyDate!==key){data.shop.dailyDate=key;data.shop.dailyId=SHOP_CATALOG[Math.floor(Math.random()*SHOP_CATALOG.length)]?.id||'';data.shop.dailyDiscount=15+Math.floor(Math.random()*21);save();}
}
function rarityIcon3(r){return ({'Обычный':'🌸','Редкий':'💎','Эпический':'✨','Легендарный':'👑','Секретный':'🌙'})[r]||'✦'}
function shopItemCard3(item){const own=data.shop.owned.includes(item.id), daily=data.shop.dailyId===item.id, cost=daily?Math.round(item.cost*(1-(data.shop.dailyDiscount||20)/100)):item.cost;return `<div class="card shop-card premium-shop-card"><div class="shop-icon">${item.icon}</div><div class="row between"><span class="tag">${rarityIcon3(item.rarity)} ${item.rarity}</span>${daily?`<span class="tag sale-tag">- ${data.shop.dailyDiscount}% сегодня</span>`:''}</div><h4>${esc(item.title)}</h4><p class="subtle">${esc(item.desc||'Коллекционный предмет.')}</p><div class="row between"><strong>${own?'Получено':`✦ ${cost} XP`}</strong><button class="btn ${own?'secondary':''} small" ${own?'disabled':''} data-shop3-buy="${item.id}">${own?'Получено':'Купить'}</button></div></div>`}
function shopPage3(){
 ensureCollectionItemsInShop3();
 ensureShopDaily3();
 const filter=data.ui.shopFilter||'all';
 const all=[...SHOP_CATALOG,...FURNITURE_CATALOG.filter(f=>!SHOP_CATALOG.some(x=>x.id===f.id)).map(f=>({...f,type:'furniture',desc:'Мебель и декор для комнаты питомца.'}))];
 let filtered=all.filter(x=>{
   if(filter==='all') return true;
   if(filter==='collections') return COLLECTIONS3.some(c=>c.ids.includes(x.id));
   if(filter==='furniture') return x.type==='furniture';
   if(filter==='pet') return ['pet','petToy','petBg','petRoom'].includes(x.type);
   return filter===x.rarity;
 });
 const cats=[['all','Все'],['collections','🎀 Из коллекций'],['pet','Питомец'],['furniture','Мебель'],['theme','Темы'],['frame','🖼️ Рамки'],['badge','Значки'],['Редкий','Редкие'],['Эпический','Эпические'],['Легендарный','Легендарные'],['Секретный','Секретные']];
 const collectionById={};
 COLLECTIONS3.forEach(c=>c.ids.forEach(id=>(collectionById[id]??=[]).push(c.title)));
 const cols=COLLECTIONS3.map(c=>{const p=collectionProgress3(c);return `<div class="item"><div class="row between"><strong>${esc(c.title)}</strong><span class="tag">${p.got}/${p.total}</span></div><div class="progress" style="margin-top:8px"><i style="width:${p.pct}%"></i></div>${p.got===p.total?'<p style="margin-top:7px">👑 Коллекция собрана!</p>':''}</div>`}).join('');
 const itemCards=filtered.map(item=>{
   const collections=(collectionById[item.id]||[]).map(x=>`<span class="tag" style="margin:4px 4px 0 0">🎀 ${esc(x)}</span>`).join('');
   return `<div>${shopItemCard3(item)}${collections?`<div style="padding:0 4px">${collections}</div>`:''}</div>`;
 }).join('');
 return `<section class="card hero"><div class="row between wrap"><div><div class="label">Коллекция наград</div><h1 style="font-family:Georgia,serif;margin:4px 0">🛍️ Бьюти-магазин</h1><p>Трать XP на питомца, мебель, декор, темы и редкие предметы.</p></div><span class="tag">✨ ${Number(data.xp)} XP</span></div></section><div class="chip-tabs" style="margin:14px 0">${cats.map(([k,l])=>`<button type="button" class="${filter===k?'active':''}" data-shop-filter3="${k}">${l}</button>`).join('')}</div><section class="card"><div class="row between"><h3 class="section-title">🎀 Десять коллекций</h3><span class="tag">${computeCollectionCount3()} собрано</span></div><div class="grid grid-2">${cols}</div></section><section class="card" style="margin-top:16px"><div class="row between"><h3 class="section-title">✨ Предметы</h3><span class="subtle">${filtered.length} доступно</span></div><div class="grid grid-4" style="margin-top:12px">${itemCards||'<div class="empty" style="grid-column:1/-1">В этой категории пока нет предметов.</div>'}</div></section>`;
}
const __shopPageOld3=shopInventoryPage; shopInventoryPage=shopPage3; improvedShopPage=shopPage3;

// ---------- Compact cards / English-free favourites ----------
const __favorites3=favoritesV3;
favoritesV3=function(){return __favorites3().replaceAll('ТОП СРЕДСТВ','ТОП СРЕДСТВ').replaceAll('Сейчас люблю','Сейчас люблю').replaceAll('Куплю снова','Куплю снова').replaceAll('Чаще всего использую','Чаще всего использую').replaceAll('Самая высокая оценка','Самая высокая оценка')};

// ---------- Full settings: one explicit save, plus autosave ----------
settingsPage=function(){
 ensureUpdate3Data();
 const themeEntries=Object.entries({...themes});
 AVATAR_FRAMES=getAvatarFrames();
 return `<div class="grid grid-2"><section class="card"><div class="row between"><div><div class="label">Личное пространство</div><h3 class="section-title">⚙ Настройки интерфейса</h3><p class="subtle">Все параметры ниже сохраняются в твоём браузере.</p></div><span class="tag">✓ ${new Intl.DateTimeFormat('ru-RU',{dateStyle:'short',timeStyle:'short'}).format(new Date(data.settings.lastSavedAt||Date.now()))}</span></div><div class="avatar-editor"><div class="avatar avatar-lg" data-avatar${data.settings.avatarFrame?` data-frame="${esc(data.settings.avatarFrame)}"`:''}>${data.settings.avatar?`<img src="${data.settings.avatar}" alt="Аватар">`:`<span class="avatar-fallback">🌸</span>`}</div><div class="avatar-actions"><label class="btn secondary small" style="cursor:pointer">Загрузить фото<input type="file" id="avatarInput" accept="image/*" hidden></label>${data.settings.avatar?`<button type="button" class="btn ghost small" id="removeAvatarBtn">Удалить фото</button>`:''}<span class="subtle">Фото и рамка сохраняются отдельно друг от друга ♡</span></div></div><div class="field" style="margin-bottom:16px"><label>Рамка аватарки</label><div class="frame-swatches">${AVATAR_FRAMES.map(([id,icon,label])=>`<div class="frame-swatch-wrap"><button type="button" class="frame-swatch ${(data.settings.avatarFrame||'')===id?'active':''}" data-avatar-frame="${id}" title="${label}"><span class="avatar" data-avatar${id?` data-frame="${id}"`:''} style="width:46px;height:46px;cursor:pointer">${icon}</span></button><span class="frame-swatch-label">${label}</span></div>`).join('')}</div><p class="subtle" style="margin-top:8px">Рамка не привязана к теме оформления — можно выбрать любую отдельно ♡</p></div><form id="interfaceSettingsForm" class="form"><div class="field"><label>Имя</label><input name="name" value="${esc(data.settings.name||'Красотка')}"></div><div class="grid grid-2"><div class="field"><label>Тип кожи</label><select name="skinType">${[['normal','Нормальная'],['dry','Сухая'],['oily','Жирная'],['combination','Комбинированная'],['sensitive','Чувствительная']].map(([v,l])=>`<option value="${v}" ${data.settings.skinType===v?'selected':''}>${l}</option>`).join('')}</select></div><div class="field"><label>Тип волос</label><select name="hairType">${[['normal','Нормальные'],['dry','Сухие'],['oily','Жирные'],['damaged','Повреждённые'],['colored','Окрашенные']].map(([v,l])=>`<option value="${v}" ${data.settings.hairType===v?'selected':''}>${l}</option>`).join('')}</select></div></div><div class="grid grid-2"><div class="field"><label>Город для погоды</label><input name="city" value="${esc(data.settings.city||'')}" placeholder="Например, Таллин"></div><div class="field"><label>Тема</label><select name="theme">${themeEntries.map(([v,t])=>`<option value="${v}" ${data.settings.theme===v?'selected':''}>${t.name}</option>`).join('')}</select></div></div><div class="grid grid-3"><div class="field"><label>Стиль карточек</label><select name="cardStyle"><option value="soft">Мягкие</option><option value="minimal">Минималистичные</option><option value="glass">Стеклянные</option><option value="paper">Бумажный журнал</option></select></div><div class="field"><label>Плотность</label><select name="density"><option value="compact">Компактно</option><option value="comfortable">Удобно</option><option value="airy">Воздушно</option></select></div><div class="field"><label>Анимации</label><select name="motion"><option value="none">Без анимаций</option><option value="soft">Мягкие</option><option value="full">Полные</option></select></div></div><div class="grid grid-2"><label class="tag"><input name="seasonalAtmosphere" type="checkbox" ${data.settings.seasonalAtmosphere!==false?'checked':''}> Сезонная атмосфера</label><label class="tag"><input name="privacyMode" type="checkbox" ${data.settings.privacyMode?'checked':''}> 🔒 Приватный режим</label></div><div class="row wrap"><button class="btn" type="submit">Сохранить настройки ♡</button><button class="btn secondary" type="button" id="restoreInterfaceDefaults">Вернуть стандартный вид</button></div></form></section><section class="card"><div class="label">Центр данных</div><h3 class="section-title">💾 Сохранение и резервная копия</h3><div class="grid grid-3"><div class="stat"><span class="label">Процедуры</span><b>${data.routines.length}</b></div><div class="stat"><span class="label">Фото</span><b>${data.photos.length}</b></div><div class="stat"><span class="label">Средства</span><b>${data.products.length}</b></div></div><div class="item" style="margin-top:12px"><strong>Последнее сохранение</strong><p class="subtle">${new Intl.DateTimeFormat('ru-RU',{dateStyle:'long',timeStyle:'short'}).format(new Date(data.settings.lastSavedAt||Date.now()))}</p></div><div class="row wrap" style="margin-top:12px"><button class="btn secondary" data-export>Экспортировать всё</button><label class="btn secondary" style="cursor:pointer">Импортировать<input id="importFile" type="file" accept="application/json" hidden></label><button class="btn danger" data-reset>Очистить данные</button></div></section></div>`;
};

function bindInterfaceSettings3(){
 const form=document.getElementById('interfaceSettingsForm'); if(!form)return;
 const setSelect=(name,val)=>{const el=form.elements[name];if(el)el.value=val};
 setSelect('cardStyle',data.settings.cardStyle);setSelect('density',data.settings.density);setSelect('motion',data.settings.motion);
 form.addEventListener('submit',e=>{e.preventDefault();const f=new FormData(form);data.settings.name=String(f.get('name')||'Красотка');data.settings.skinType=String(f.get('skinType')||'normal');data.settings.hairType=String(f.get('hairType')||'normal');data.settings.city=String(f.get('city')||'');data.settings.theme=String(f.get('theme')||'pink');data.settings.cardStyle=String(f.get('cardStyle')||'soft');data.settings.density=String(f.get('density')||'comfortable');data.settings.motion=String(f.get('motion')||'soft');data.settings.seasonalAtmosphere=f.has('seasonalAtmosphere');data.settings.privacyMode=f.has('privacyMode');save();applyPremiumTheme();toast('Настройки сохранены ♡');render();});
 document.getElementById('restoreInterfaceDefaults')?.addEventListener('click',()=>{data.settings.cardStyle='soft';data.settings.density='comfortable';data.settings.motion='soft';data.settings.theme='pink';data.settings.seasonalAtmosphere=true;data.settings.privacyMode=false;save();toast('Стандартный вид восстановлен');render()});
 document.getElementById('avatarInput')?.addEventListener('change',e=>{
  const file=e.target.files && e.target.files[0]; if(!file)return;
  if(!file.type.startsWith('image/')){toast('Выбери файл изображения ♡');return}
  const reader=new FileReader();
  reader.onload=ev=>{
   const img=new Image();
   img.onload=()=>{
    const size=320,canvas=document.createElement('canvas');canvas.width=size;canvas.height=size;
    const ctx=canvas.getContext('2d');const side=Math.min(img.width,img.height);
    const sx=(img.width-side)/2,sy=(img.height-side)/2;
    ctx.drawImage(img,sx,sy,side,side,0,0,size,size);
    data.settings.avatar=canvas.toDataURL('image/jpeg',0.86);
    data.settings.lastSavedAt=Date.now();save();toast('Фото профиля обновлено ♡');render();
   };
   img.onerror=()=>toast('Не получилось прочитать это изображение ♡');
   img.src=ev.target.result;
  };
  reader.readAsDataURL(file);
 });
 document.getElementById('removeAvatarBtn')?.addEventListener('click',()=>{
  data.settings.avatar='';data.settings.lastSavedAt=Date.now();save();toast('Фото профиля удалено');render();
 });
 document.querySelectorAll('[data-avatar-frame]').forEach(b=>b.addEventListener('click',()=>{
  data.settings.avatarFrame=b.dataset.avatarFrame||'';data.settings.lastSavedAt=Date.now();save();toast('Рамка аватарки обновлена ♡');render();
 }));
}

// ---------- Render-time bindings for this update ----------
const __bindBig3=bindBigPage;
bindBigPage=function(route){
 try{__bindBig3(route)}catch(e){console.error(e)}
 if(route==='settings')bindInterfaceSettings3();
 document.querySelectorAll('[data-shop-filter3]').forEach(b=>b.onclick=()=>{data.ui.shopFilter=b.dataset.shopFilter3;save();render()});
 document.querySelectorAll('[data-shop3-buy]').forEach(b=>b.onclick=()=>{const id=b.dataset.shop3Buy;const f=FURNITURE_CATALOG.find(x=>x.id===id);if(f)buyFurniture3(id);else buyShopV2(id)});
 document.querySelectorAll('[data-place-toggle]').forEach(b=>b.onclick=()=>toggleFurniture3(b.dataset.placeToggle));
 document.querySelectorAll('[data-cycle-color]').forEach(b=>b.onclick=()=>cycleFurnitureColor3(b.dataset.cycleColor));
 document.querySelectorAll('[data-room-color]').forEach(b=>b.onclick=()=>setRoomColor3(b.dataset.roomColor));
 document.querySelectorAll('[data-place-furniture]').forEach(b=>b.onclick=()=>{document.querySelectorAll('.placed-furniture').forEach(x=>x.classList.remove('is-selected'));b.classList.add('is-selected')});
 document.getElementById('toggleStats30')?.addEventListener('click',()=>{data.ui.statsExpanded=!data.ui.statsExpanded;save();render()});
 document.getElementById('spinWheel')&&(document.getElementById('spinWheel').onclick=spinWheel);
}

// ---------- Final styling ----------
const update3Style=document.createElement('style');update3Style.textContent=`[data-avatar][data-frame="kitty"]{border:3px solid #f3a7c7!important;box-shadow:0 0 0 4px #fff0f6,0 0 18px rgba(243,167,199,.45)!important}
[data-avatar][data-frame="kuromi"]{border:3px solid #51485d!important;box-shadow:0 0 0 4px #eee9f2,0 0 18px rgba(81,72,93,.35)!important}
[data-avatar][data-frame="sakura"]{border:3px solid #ef9fb7!important;box-shadow:0 0 0 4px #fff1f5,0 0 18px rgba(239,159,183,.4)!important}
[data-avatar][data-frame="coquette"]{border:3px solid #d979a4!important;box-shadow:0 0 0 4px #ffe7f0,0 0 18px rgba(217,121,164,.42)!important}
[data-avatar][data-frame="strawberry"]{border:3px solid #df6f89!important;box-shadow:0 0 0 4px #fff0f2,0 0 18px rgba(223,111,137,.42)!important}
[data-avatar][data-frame="mint"]{border:3px solid #79bfa9!important;box-shadow:0 0 0 4px #e9f8f2,0 0 18px rgba(121,191,169,.4)!important}
[data-avatar][data-frame="lavender-cloud"]{border:3px solid #a88bdd!important;box-shadow:0 0 0 4px #f1ebff,0 0 18px rgba(168,139,221,.4)!important}
[data-avatar][data-frame="cozy"]{border:3px solid #c79569!important;box-shadow:0 0 0 4px #fff4e8,0 0 18px rgba(199,149,105,.4)!important}
[data-avatar][data-frame="royal"]{border:3px solid #d6ae45!important;box-shadow:0 0 0 4px #fff8dc,0 0 20px rgba(214,174,69,.45)!important}
[data-avatar][data-frame="midnight"]{border:3px solid #6f65a8!important;box-shadow:0 0 0 4px #eeecff,0 0 20px rgba(111,101,168,.45)!important}

:root{--surface-glass:rgba(255,255,255,.62)}
[data-card-style="soft"] .card{box-shadow:0 12px 30px rgba(67,42,55,.065)}
[data-card-style="minimal"] .card{box-shadow:none;border-color:rgba(70,55,65,.08);border-radius:18px}
[data-card-style="glass"] .card{background:var(--surface-glass);backdrop-filter:blur(18px);-webkit-backdrop-filter:blur(18px);border-color:rgba(255,255,255,.55);box-shadow:0 16px 40px rgba(75,50,70,.08)}
[data-card-style="paper"] .card{background:linear-gradient(135deg,var(--surface),var(--surface2));box-shadow:0 6px 18px rgba(90,60,70,.06)}
[data-density="compact"] .card{padding:13px}.content{transition:padding .18s ease}.stats-chart-wrap{padding:8px 0;overflow:auto}.stats-chart-wrap svg{width:100%;min-width:680px;height:auto}.premium-shop-card{min-height:340px}.sale-tag{background:#ffe8ef;color:#9d536c}.luck-card-compact{display:flex;flex-direction:column;align-items:center}.wheel-wrap-compact{transform:scale(.78);transform-origin:center top;margin-bottom:-34px}.luck-wheel-small{width:320px!important;height:320px!important}.luck-wheel-small .wheel-label{font-size:9px}.luck-wheel-small .wheel-label img{width:24px;height:24px}.prize-grid{grid-template-columns:repeat(2,minmax(0,1fr))}.room-editor{margin-top:14px}.room-scene{position:relative;min-height:420px;border-radius:26px;overflow:hidden;background:radial-gradient(circle at 20% 20%,rgba(255,255,255,.9),transparent 30%),linear-gradient(135deg,var(--surface2),var(--surface));border:1px solid var(--border);box-shadow:inset 0 0 0 1px rgba(255,255,255,.4)}.room-scene:before{content:'✦  ˚₊‧ ୨୧ ‧₊˚  ✦';position:absolute;right:18px;top:16px;color:var(--primary);opacity:.25}.room-furniture{position:absolute;transform:translate(-50%,-50%);border:0;background:transparent;font-size:48px;cursor:pointer;filter:drop-shadow(0 10px 12px rgba(55,35,50,.12));transition:transform .16s ease,filter .16s ease}.placed-furniture{box-shadow:0 0 0 7px color-mix(in srgb,var(--fcolor) 18%, transparent);border-radius:18px}.placed-furniture.is-selected{transform:translate(-50%,-50%) scale(1.1);filter:drop-shadow(0 14px 18px rgba(55,35,50,.2))}.room-empty{position:absolute;inset:0;display:grid;place-items:center;text-align:center;color:var(--muted);padding:30px}.room-empty span{font-size:13px}.color-dot{width:28px;height:28px;border-radius:50%;border:2px solid white;box-shadow:0 0 0 1px var(--border);cursor:pointer}.color-dot:hover{transform:scale(1.08)}
@media(max-width:800px){.room-scene{min-height:340px}.luck-wheel-small{width:280px!important;height:280px!important}.wheel-wrap-compact{transform:scale(.70);margin-bottom:-70px}.premium-shop-card{min-height:auto}.prize-grid{grid-template-columns:1fr}}
`;
document.head.appendChild(update3Style);

// ---------- Strong save wrapper and final render ----------
const __saveUpdate3=save;
save=function(){ensureUpdate3Data();data.settings.lastSavedAt=Date.now();__saveUpdate3();};
const __renderUpdate3=render;
render=function(){ensureUpdate3Data();applyPremiumTheme();__renderUpdate3();translateVisibleText();ensureSeasonalLayer();};

// final boot: preserve current data and do not reset it
ensureUpdate3Data();
try{render()}catch(e){console.error('Premium update 3 render failed',e)}

/* ===== ДОПОЛНИТЕЛЬНЫЕ ТЕМЫ И КОЛЛЕКЦИИ ===== */
Object.assign(themes,{
  'shop-theme-kitty':{name:'Китти — розовый мир',vars:{'--bg':'#fff8f9','--surface':'#ffffff','--surface2':'#ffeef2','--text':'#3b3337','--muted':'#98868d','--primary':'#ef6f8f','--primary2':'#ffc1cf','--accent':'#111111','--success':'#9ccbb8'}},
  'shop-theme-kuromi':{name:'Куроми — чёрно-розовая ночь',vars:{'--bg':'#f8f4fb','--surface':'#ffffff','--surface2':'#eee4f5','--text':'#312a35','--muted':'#8f8294','--primary':'#8d63a8','--primary2':'#d9b7e8','--accent':'#2a2531','--success':'#8ebba9'}},
  'shop-theme-melody':{name:'Мелоди — нежный сад',vars:{'--bg':'#fffafc','--surface':'#ffffff','--surface2':'#fbeef4','--text':'#49353f','--muted':'#9b818f','--primary':'#e5a0bf','--primary2':'#f4cedd','--accent':'#b77ca3','--success':'#9dcbb5'}},
  'shop-theme-cinnamoroll':{name:'Синнаморолл — облачное небо',vars:{'--bg':'#f6fbff','--surface':'#ffffff','--surface2':'#eaf4ff','--text':'#304154','--muted':'#8293a7','--primary':'#8bb9e8','--primary2':'#cfe6ff','--accent':'#a9d6f5','--success':'#8fc5b0'}},
  'shop-theme-pompompurin':{name:'Поччи — ванильное тепло',vars:{'--bg':'#fffaf1','--surface':'#fffefb','--surface2':'#fff0c9','--text':'#4d4238','--muted':'#9c8c78','--primary':'#e2ad47','--primary2':'#f4d68d','--accent':'#8d6a43','--success':'#9ac3a6'}},
  'shop-theme-boba':{name:'Боба — клубничный чай',vars:{'--bg':'#fff7f5','--surface':'#fffdfb','--surface2':'#fbe9e4','--text':'#4b3937','--muted':'#9a817c','--primary':'#d78783','--primary2':'#f2c1b9','--accent':'#8f6fa1','--success':'#96bea8'}},
  'shop-theme-cherry':{name:'Вишнёвый лак',vars:{'--bg':'#fff8fa','--surface':'#ffffff','--surface2':'#fbe6ec','--text':'#402c35','--muted':'#967b85','--primary':'#c84c70','--primary2':'#efb3c4','--accent':'#6c3045','--success':'#92bea6'}},
  'shop-theme-sakura':{name:'Сакура — розовый рассвет',vars:{'--bg':'#fffafc','--surface':'#ffffff','--surface2':'#f7ebf2','--text':'#4b3942','--muted':'#9b8690','--primary':'#d998b2','--primary2':'#f0c6d6','--accent':'#b796bf','--success':'#9bc7b0'}},
  'shop-theme-coquette':{name:'Кокетка — ленты и жемчуг',vars:{'--bg':'#fff9fb','--surface':'#ffffff','--surface2':'#fae8f0','--text':'#43323a','--muted':'#9a818c','--primary':'#d778a0','--primary2':'#efbed2','--accent':'#c8a46e','--success':'#9ac3ae'}},
  'shop-theme-ballet':{name:'Балеткор — пудра и атлас',vars:{'--bg':'#fbf8fc','--surface':'#ffffff','--surface2':'#f1eaf4','--text':'#443b47','--muted':'#96899a','--primary':'#c49bbf','--primary2':'#ead7e5','--accent':'#a87f9e','--success':'#9fc3b0'}},
  'shop-theme-moon':{name:'Лунный сад',vars:{'--bg':'#f6f4fb','--surface':'#ffffff','--surface2':'#ebe7f6','--text':'#353140','--muted':'#878096','--primary':'#8577b7','--primary2':'#cbc4e6','--accent':'#5c5576','--success':'#8fb9aa'}}
});
const extraThemes=[
 ['theme-kitty','Китти — розовый мир','🎀',420,'Редкий','Розово-белая тема с графитовым акцентом.','shop-theme-kitty'],
 ['theme-kuromi','Куроми — чёрно-розовая ночь','🖤',520,'Эпический','Дерзкая чёрно-розовая тема с лавандовым светом.','shop-theme-kuromi'],
 ['theme-melody','Мелоди — нежный сад','🌷',460,'Редкий','Мягкий розовый сад в пастельной палитре.','shop-theme-melody'],
 ['theme-cinnamoroll','Синнаморолл — облачное небо','☁️',560,'Эпический','Небесная прохладная тема с облачным настроением.','shop-theme-cinnamoroll'],
 ['theme-pompompurin','Поччи — ванильное тепло','🍮',440,'Редкий','Кремово-золотая уютная тема.','shop-theme-pompompurin'],
 ['theme-boba','Боба — клубничный чай','🧋',380,'Обычный','Кремово-ягодная тема с чайным настроением.','shop-theme-boba'],
 ['theme-cherry','Вишнёвый лак','🍒',500,'Эпический','Глубокий вишнёвый акцент и глянцевое настроение.','shop-theme-cherry'],
 ['theme-sakura','Сакура — розовый рассвет','🌸',390,'Редкий','Пудровая весенняя тема.','shop-theme-sakura'],
 ['theme-coquette','Кокетка — ленты и жемчуг','🎀',620,'Эпический','Банты, жемчуг и мягкий пудровый контраст.','shop-theme-coquette'],
 ['theme-ballet','Балеткор — пудра и атлас','🩰',680,'Легендарный','Воздушная редакционная тема с атласным настроением.','shop-theme-ballet'],
 ['theme-moon','Лунный сад','🌙',760,'Легендарный','Тихая вечерняя тема для ночного ритуала.','shop-theme-moon']
];
for(const [id,title,icon,cost,rarity,desc] of extraThemes){if(!SHOP_CATALOG.some(x=>x.id===id))SHOP_CATALOG.push({id,type:'theme',title,icon,cost,rarity,desc});}
const extraShopItems=[
 ['pet-kitty-bow','Бантик «Розовая мечта»','🎀',240,'Редкий','Аксессуар питомца'],['pet-kuromi-ears','Ушки «Ночная звезда»','🖤',540,'Эпический','Контрастный аксессуар питомца'],['pet-wings','Крылышки','🪽',720,'Легендарный','Сияющий аксессуар питомца'],['pet-scarf','Лавандовый шарфик','🪻',300,'Редкий','Уютный аксессуар питомца'],['pet-tail','Сияющий хвостик','✨',650,'Эпический','Мягкое свечение'],
 ['frame-kitty','Рамка «Розовая лента»','🎀',280,'Редкий','Рамка профиля'],['frame-kuromi','Рамка «Ночная звезда»','🖤',390,'Редкий','Контрастная рамка'],['badge-sakura','Значок «Сакура»','🌸',260,'Обычный','Весенний значок'],['badge-coquette','Значок «Кокетка»','🎀',470,'Эпический','Коллекционный значок'],['sticker-bunny','Наклейка «Кролик»','🐰',120,'Обычный','Наклейка для дневника'],['sticker-bow','Наклейка «Большой бант»','🎀',160,'Обычный','Наклейка для карточек'],['decor-lamp','Лампа-полумесяц','🌙',340,'Редкий','Декор комнаты'],['decor-vanity','Туалетный столик','🪞',580,'Эпический','Большой предмет мебели'],['decor-rose','Ваза с розами','🌹',190,'Обычный','Декор комнаты'],['decor-cloud','Облачная полка','☁️',240,'Обычный','Полка для мелочей']
].map(([id,title,icon,cost,rarity,desc])=>({id,type:id.startsWith('pet-')?'pet':id.startsWith('frame-')?'frame':id.startsWith('badge-')?'badge':id.startsWith('sticker-')?'sticker':'decor',title,icon,cost,rarity,desc}));
for(const item of extraShopItems){if(!SHOP_CATALOG.some(x=>x.id===item.id))SHOP_CATALOG.push(item);}
const GOBLINCORE_SHOP_ITEMS=[
 {id:'theme-goblincore',type:'theme',title:'Гоблинкор — мох и грибы',icon:'🍄',cost:480,rarity:'Редкий',desc:'Мшисто-земляная лесная эстетика для маленьких лесных ритуалов ухода.',vars:{'--bg':'#eef2e6','--surface':'#f8faf2','--surface2':'#e1eace','--text':'#333f2a','--muted':'#7b8a6a','--primary':'#5f8b4c','--primary2':'#c7d9a8','--accent':'#9c6b3e','--success':'#6fa06a'}},
 {id:'theme-fairyforest',type:'theme',title:'Лесные феи',icon:'🧚',cost:560,rarity:'Эпический',desc:'Волшебная чаща с блеском фей и мягким лунным светом.',vars:{'--bg':'#eef8ee','--surface':'#ffffff','--surface2':'#def1e1','--text':'#2d4a34','--muted':'#7ea087','--primary':'#48a06a','--primary2':'#bfe8cb','--accent':'#b48ee0','--success':'#5fb583'}},
 {id:'theme-mushroomgrove',type:'theme',title:'Грибная роща',icon:'🍂',cost:640,rarity:'Эпический',desc:'Тёплый осенний лес с мухоморами и палой листвой.',vars:{'--bg':'#f6f1e3','--surface':'#fffdf7','--surface2':'#ebe0c3','--text':'#463b23','--muted':'#8f8265','--primary':'#7f6034','--primary2':'#ddc186','--accent':'#c1483c','--success':'#79965a'}},
 {id:'frame-moss',type:'frame',title:'Рамка «Мох»',icon:'🍃',cost:280,rarity:'Обычный',desc:'Мшистая рамка для аватарки в стиле гоблинкор.'},
 {id:'frame-fairywing',type:'frame',title:'Рамка «Крылья феи»',icon:'🧚',cost:420,rarity:'Редкий',desc:'Полупрозрачная рамка с блеском феи для профиля.'},
 {id:'frame-toadstool',type:'frame',title:'Рамка «Мухомор»',icon:'🍄',cost:360,rarity:'Редкий',desc:'Рамка с грибным узором в тон лесной эстетике.'}
];
for(const item of GOBLINCORE_SHOP_ITEMS){if(!SHOP_CATALOG.some(x=>x.id===item.id))SHOP_CATALOG.push(item);}
const oldApplyPremiumTheme=applyPremiumTheme;
applyPremiumTheme=function(){oldApplyPremiumTheme();const key=data.settings.theme||'pink';const t=themes[key]||themes.pink;Object.entries(t.vars||{}).forEach(([k,v])=>document.documentElement.style.setProperty(k,v));};
const finalPremiumStyle=document.createElement('style');
finalPremiumStyle.textContent=`
  .shop-card{transition:transform .18s ease,box-shadow .18s ease}.shop-card:hover{transform:translateY(-3px)}
  [data-density="compact"] .card{padding:14px}[data-density="airy"] .card{padding:24px}
  [data-card-style="glass"] .card{background:rgba(255,255,255,.62);backdrop-filter:blur(18px)}
  [data-card-style="paper"] .card{background:linear-gradient(135deg,var(--surface),var(--surface2))}
`;
document.head.appendChild(finalPremiumStyle);



(function(){
'use strict';
const MJX={};
const W=window;
const esc2=(x)=>typeof esc==='function'?esc(x):String(x??'').replace(/[&<>"']/g,m=>({'&':'&amp;','<':'&lt;','>':'&gt;','"':'&quot;',"'":'&#39;'}[m]));
const uid2=()=>typeof uid==='function'?uid():('mjx-'+Date.now().toString(36)+Math.random().toString(36).slice(2,8));
const save2=()=>{try{typeof save==='function'?save():localStorage.setItem('myBeautyJournal_v3',JSON.stringify(data));}catch(e){console.warn(e)}};
function ensure(){
  data.pet=data.pet||{}; data.pet.kind='котёнок';
  data.mjx=data.mjx||{};
  data.mjx.collections=data.mjx.collections||{};
  data.mjx.mystery=data.mjx.mystery||{date:'',opened:false};
  data.mjx.academy=data.mjx.academy||{done:[],lastOnline:''};
  data.mjx.lab=data.mjx.lab||{lastQuery:'',history:[]};
  data.mjx.hair=data.mjx.hair||{goal:60,baseLength:0,entries:[]};
  data.mjx.season=data.mjx.season||{lastRefresh:''};
  data.mjx.learnedInci=data.mjx.learnedInci||{};
}
ensure();

const seasons=[
 {month:7,title:'Клубничное лето',icon:'🍓',desc:'Светлый ягодный сезон: лёгкий уход, сияние и маленькие радости.'},
 {month:8,title:'Мягкий перезапуск',icon:'🎀',desc:'Новый ритм, спокойные ритуалы и возвращение к стабильности.'},
 {month:9,title:'Тёмная красота',icon:'🖤',desc:'Глубокие оттенки, уютный вечерний уход и немного загадочности.'},
 {month:10,title:'Уютное сияние',icon:'☕',desc:'Тёплый сезон для домашних ритуалов, масок и спокойных вечеров.'},
 {month:11,title:'Зимний Spa',icon:'❄️',desc:'Мягкость, тепло и дополнительная забота о сухости кожи и волос.'},
 {month:0,title:'Розовый reset',icon:'🌸',desc:'Свежий старт и нежное обновление.'},
 {month:1,title:'Сакура',icon:'🌸',desc:'Лёгкий весенний воздух и цветочный настрой.'},
 {month:2,title:'Лавандовый сезон',icon:'🪻',desc:'Спокойный уход и мягкая эстетика.'},
 {month:3,title:'Glow Garden',icon:'🌷',desc:'Больше света, воды и сияния.'},
 {month:4,title:'Мятное утро',icon:'🍃',desc:'Свежесть, лёгкость и воздушный уход.'},
 {month:5,title:'Клубничный пикник',icon:'🍓',desc:'Лето начинается с красивых маленьких привычек.'},
 {month:6,title:'Soft Summer',icon:'☀️',desc:'Лёгкие текстуры и бережная защита от солнца.'}
];
function currentSeason(){return seasons[new Date().getMonth()];}

function bottleSvg(label,a,b){const svg=`<svg xmlns="http://www.w3.org/2000/svg" width="520" height="380" viewBox="0 0 520 380"><defs><linearGradient id="g" x1="0" x2="1"><stop stop-color="${a}"/><stop offset="1" stop-color="${b}"/></linearGradient></defs><rect width="520" height="380" rx="40" fill="#fff9fb"/><ellipse cx="260" cy="332" rx="115" ry="20" fill="#e9dfe6" opacity=".7"/><rect x="188" y="86" width="144" height="210" rx="30" fill="url(#g)"/><rect x="211" y="54" width="98" height="48" rx="12" fill="#f1edf0" stroke="#d9ccd6" stroke-width="4"/><rect x="235" y="28" width="50" height="35" rx="10" fill="${b}"/><rect x="207" y="150" width="106" height="72" rx="18" fill="#ffffff" opacity=".85"/><text x="260" y="180" font-family="Georgia,serif" font-size="22" text-anchor="middle" fill="#4b4250">${label}</text><text x="260" y="208" font-family="Arial" font-size="13" text-anchor="middle" fill="#8b7b89">Уход питомца</text></svg>`;return 'data:image/svg+xml;charset=UTF-8,'+encodeURIComponent(svg)}

function addShop(item){if(typeof SHOP_CATALOG==='undefined')return;if(!SHOP_CATALOG.some(x=>x.id===item.id))SHOP_CATALOG.push(item);}
const extra=[];
const pushMany=(prefix,type,arr)=>arr.forEach((x,i)=>extra.push({id:`mjx-${prefix}-${i+1}`,type,title:x[0],icon:x[1],cost:x[2],rarity:x[3],desc:x[4],collection:x[5]||'' ,image:x[6]||''}));
pushMany('spa','pet',[['Шампунь «Розовое облако»','🧴',180,'Обычный','Мягкий шампунь для маленького питомца','Kitty Dream',bottleSvg('Шампунь','#f3bfd3','#d98dab')],['Кондиционер «Шёлк»','🧴',220,'Обычный','Кондиционер для мягкости','Kitty Dream',bottleSvg('Кондиционер','#ead7f2','#bca7d8')],['Маска «Лавандовый крем»','🧴',320,'Редкий','Питомец любит spa-день','Lavender Spa',bottleSvg('Маска','#d8c8ef','#a88bc8')],['Мист «Сакура»','🌸',260,'Редкий','Спрей с цветочным настроением','Sakura',bottleSvg('Мист','#ffd3e3','#e7a0b9')],['Масло «Золотое сияние»','✨',420,'Эпический','Блестящий уход за кончиками хвостика','Gold Glow',bottleSvg('Масло','#f6db9b','#cba753')],['Пенка «Мятный шёлк»','🍃',240,'Редкий','Освежающий spa-ритуал','Mint Spa',bottleSvg('Пенка','#cfe9d8','#8ebca0')],['Сыворотка «Ночная звезда»','🖤',520,'Эпический','Уход перед сном','Kuromi Night',bottleSvg('Сыворотка','#8d7a99','#3f3546')],['Спа-свеча «Кремовая»','🕯️',210,'Обычный','Уютный аксессуар для ванной','Cozy Glow',bottleSvg('Свеча','#f2dfc0','#cfaa71')]]);
pushMany('pet','pet',[['Очки «Умница»','👓',190,'Обычный','Маленькая пара очков','Kitty Dream'],['Корона «Глоу»','👑',950,'Легендарный','Редкий праздничный аксессуар','Royal Glow'],['Крылья «Сон»','🪽',780,'Легендарный','Нежные светящиеся крылышки','Dreamy Night'],['Нимб «Луна»','😇',640,'Эпический','Мягкое лунное сияние','Kuromi Night'],['Бант «Вишня»','🍒',300,'Редкий','Вишнёвая лента','Cherry Gloss'],['Шапочка «Пижама»','🧢',270,'Обычный','Уют для ночи','Cozy Glow']]);
pushMany('furn','furniture',[['Кровать «Облако»','☁️',420,'Редкий','Мягкая облачная кроватка','Lavender Spa'],['Кровать «Сакура»','🌸',520,'Эпический','Розовая кровать с лепестками','Sakura'],['Туалетный столик','🪞',700,'Эпический','Зеркало и мини-полочки','Kitty Dream'],['Спа-стойка','🧴',620,'Эпический','Полочка со средствами','Lavender Spa'],['Ванна «Молочная»','🛁',840,'Легендарный','Большая ванна для spa-дней','Winter Spa'],['Кресло «Букле»','🪑',460,'Редкий','Кремовое кресло','Cozy Glow'],['Пуф «Клубника»','🍓',290,'Обычный','Маленький мягкий пуф','Strawberry Summer'],['Коврик «Лаванда»','🪻',260,'Обычный','Пастельный коврик','Lavender Spa'],['Торшер «Полумесяц»','🌙',380,'Редкий','Тёплый вечерний свет','Midnight Glow'],['Полка «Бантики»','🎀',330,'Редкий','Полка для мелочей','Coquette'],['Картина «Розовый сад»','🌷',250,'Обычный','Нежный арт','Sakura'],['Картина «Ночная луна»','🌙',310,'Редкий','Ночной принт','Midnight Glow'],['Растение «Монстера»','🪴',170,'Обычный','Зелёный акцент','Mint Spa'],['Растение «Сакура»','🌸',320,'Редкий','Мини-дерево в горшке','Sakura'],['Свеча «Ваниль»','🕯️',140,'Обычный','Тёплая ванильная свеча','Cozy Glow'],['Диффузор «Лаванда»','🪻',240,'Обычный','Ароматный декор','Lavender Spa'],['Корзина «Полотенца»','🧺',180,'Обычный','Для ванной','Winter Spa'],['Тележка «Beauty Bar»','🛒',590,'Эпический','Мобильный spa-бар','Kitty Dream'],['Зеркало «Сердце»','💗',390,'Редкий','Зеркало в форме сердца','Coquette'],['Шкаф «Пудра»','🗄️',640,'Эпический','Гардероб и хранение','Balletcore'],['Светильник «Звезда»','⭐',280,'Обычный','Ночной свет','Midnight Glow'],['Столик «Боба»','🧋',300,'Редкий','Милый мини-столик','Boba'],['Стул «Мятный»','🍃',230,'Обычный','Лёгкий стул','Mint Spa'],['Комод «Китти»','🎀',560,'Эпический','Коллекционный комод','Kitty Dream'],['Ширма «Луна»','🌙',450,'Редкий','Зонирование комнаты','Midnight Glow'],['Подушка «Мелоди»','🌷',260,'Обычный','Мягкая подушка','Melody Garden'],['Плед «Куроми»','🖤',320,'Редкий','Тёмный уютный плед','Kuromi Night'],['Ваза «Жемчуг»','🤍',280,'Обычный','Нежный декор','Coquette'],['Ночник «Сердце»','💖',420,'Редкий','Тёплое мягкое свечение','Kitty Dream'],['Косметичка «Мини»','👛',210,'Обычный','Милая деталь','Beauty Atelier'],['Столик «Спа»','🧴',520,'Эпический','Место для маленьких ритуалов','Lavender Spa']]);
pushMany('frame','frame',[['Рамка «Китти»','🎀',320,'Редкий','Розовая рамка','Kitty Dream'],['Рамка «Куроми»','🖤',470,'Эпический','Ночная рамка','Kuromi Night'],['Рамка «Сакура»','🌸',300,'Редкий','Весенняя рамка','Sakura'],['Рамка «Лаванда»','🪻',260,'Обычный','Лавандовая рамка','Lavender Spa'],['Рамка «Зимний spa»','❄️',420,'Редкий','Снежная рамка','Winter Spa'],['Рамка «Блёстки»','✨',520,'Эпический','Сияющая рамка','Royal Glow']]);
extra.forEach(addShop);
// Дополнительные коллекционные предметы: много вариантов для заполнения коллекций.
const collectionExtras={
 'Kitty Dream':[['Подушка «Китти»','🎀','pet'],['Пижама «Китти»','👚','pet'],['Кружка «Китти»','☕','furniture'],['Зеркало «Китти»','🪞','furniture'],['Плакат «Китти»','🎀','frame'],['Розовый ковёр «Китти»','🩷','furniture']],
 'Kuromi Night':[['Плед «Куроми»','🖤','pet'],['Лампа «Куроми»','🌙','furniture'],['Маска для сна «Куроми»','😈','pet'],['Постер «Куроми»','🖤','frame'],['Чёрное зеркало','🪞','furniture'],['Ночной пуф','🌑','furniture']],
 'Lavender Spa':[['Полотенца «Лаванда»','🧺','furniture'],['Спа-полка «Лаванда»','🪻','furniture'],['Халатик «Лаванда»','🥰','pet'],['Кувшин «Лаванда»','🫖','furniture'],['Лепестки «Лаванда»','🌺','furniture'],['Спа-лампа «Лаванда»','🪻','furniture']],
 'Sakura':[['Кимоно «Сакура»','🌸','pet'],['Подушка «Сакура»','🌸','furniture'],['Ваза «Сакура»','🌷','furniture'],['Лепестки на пол','🌸','furniture'],['Ширма «Сакура»','🌸','furniture'],['Фон «Сакура»','🌸','frame']],
 'Cozy Glow':[['Плед «Уют»','☕','furniture'],['Кружка какао','☕','furniture'],['Тапочки «Облако»','🥿','pet'],['Кресло «Уют»','🪑','furniture'],['Тёплая лампа','🕯️','furniture'],['Книжка «Вечер»','📖','furniture']],
 'Midnight Glow':[['Пижама «Луна»','🌙','pet'],['Ночник «Луна»','🌙','furniture'],['Звёздный ковёр','⭐','furniture'],['Лунное зеркало','🌙','furniture'],['Постер «Созвездия»','✨','frame'],['Шкатулка «Ночь»','🌑','furniture']],
 'Strawberry Summer':[['Пикник-набор','🍓','furniture'],['Бантик «Клубника»','🍓','pet'],['Стакан «Ягодный»','🧋','furniture'],['Корзинка «Лето»','🧺','furniture'],['Подушка «Ягодка»','🍓','furniture'],['Фон «Пикник»','☀️','frame']],
 'Mint Spa':[['Повязка «Мята»','🍃','pet'],['Бутылочка «Мята»','🧴','furniture'],['Коврик «Свежесть»','🍃','furniture'],['Стакан для кисточек','🥛','furniture'],['Полка «Мята»','🍃','furniture'],['Фон «Mint Spa»','🍃','frame']],
 'Coquette':[['Большой бантик','🎀','pet'],['Жемчужная ваза','🤍','furniture'],['Лента на зеркало','🎀','furniture'],['Шкатулка «Жемчуг»','🩷','furniture'],['Туфли «Балет»','🩰','pet'],['Рамка «Жемчуг»','🤍','frame']],
 'Royal Glow':[['Королевская кровать','👑','furniture'],['Трон','👑','furniture'],['Корона питомца','👑','pet'],['Золотая рамка','👑','frame'],['Люстра «Сияние»','✨','furniture'],['Золотая шкатулка','💎','furniture']]
};
Object.entries(collectionExtras).forEach(([collection,items])=>items.forEach((it,i)=>addShop({id:`mjx-col-${collection}-${i+1}`,type:it[2],title:it[0],icon:it[1],cost:180+i*80,rarity:i%5===4?'Эпический':i%3===0?'Редкий':'Обычный',desc:`Предмет коллекции «${collection}».`,collection})));


const collectionDefs=[
 ['Kitty Dream','🎀',['Kitty Dream']],['Kuromi Night','🖤',['Kuromi Night']],['Lavender Spa','🪻',['Lavender Spa']],['Sakura','🌸',['Sakura']],['Cozy Glow','☕',['Cozy Glow']],['Midnight Glow','🌙',['Midnight Glow']],['Strawberry Summer','🍓',['Strawberry Summer']],['Mint Spa','🍃',['Mint Spa']],['Coquette','🎀',['Coquette']],['Royal Glow','👑',['Royal Glow']]
];
function collectionItems(name){return SHOP_CATALOG.filter(x=>x.collection===name||x.title.toLowerCase().includes(name.toLowerCase())).slice(0,10)}
function collectionPage(){return `<div class="mjx-shell"><div class="row between wrap"><div><h3 class="section-title">🛍️ Коллекции Бьюти-магазина</h3><p class="subtle">Собирай наборы целиком и открывай эксклюзивные награды.</p></div><span class="tag">💎 ${data.xp} XP</span></div><div class="mjx-grid mjx-grid-2">${collectionDefs.map(([n,ic])=>{const items=collectionItems(n);const owned=items.filter(x=>data.shop?.owned?.includes(x.id)).length;const total=Math.max(items.length,4);const p=Math.round(owned/total*100);return `<section class="card mjx-collection"><div class="mjx-collection-head"><div class="label">Коллекция</div><h3 style="margin:5px 0 2px">${ic} ${esc2(n)}</h3><p class="subtle">${owned}/${total} собрано</p><div class="mjx-collection-progress"><i style="width:${p}%"></i></div></div><div class="grid grid-4" style="margin-top:12px">${items.slice(0,8).map(it=>`<div class="item" style="text-align:center"><div style="font-size:28px">${it.icon}</div><div class="subtle">${esc2(it.title)}</div><div class="mjx-rarity" style="margin-top:6px">${esc2(it.rarity)}</div></div>`).join('')||'<div class="empty" style="grid-column:1/-1">Скоро появятся новые предметы.</div>'}</div>${owned>=total?'<div class="tag" style="margin-top:12px">👑 Коллекция полностью собрана · награда получена</div>':`<p class="subtle" style="margin-top:12px">Собери все предметы — получишь эксклюзивную награду.</p>`}</section>`}).join('')}</div></div>`}


function syncCollectionRewards(){ensure();data.mjx.collectionRewards=data.mjx.collectionRewards||{};for(const [name] of collectionDefs){const items=collectionItems(name);const total=Math.max(items.length,4);const owned=items.filter(x=>data.shop.owned.includes(x.id)).length;if(owned>=total&&!data.mjx.collectionRewards[name]){data.mjx.collectionRewards[name]=true;addXP(150,'Полная коллекция');toast(`👑 Коллекция «${name}» собрана! +150 XP ♡`)}}save2()}
syncCollectionRewards();
function shopPage2(){const season=currentSeason();const all=SHOP_CATALOG;const rare=all.filter(x=>['Редкий','Эпический','Легендарный','Секретный'].includes(x.rarity));const dailyIndex=Math.floor(Date.now()/86400000)%all.length;const daily=all[dailyIndex];return `<div class="mjx-shell"><div class="mjx-season-banner"><div class="label">Сезон сейчас</div><h2 style="font-family:Georgia,serif;margin:5px 0">${season.icon} ${esc2(season.title)}</h2><p class="subtle">${esc2(season.desc)}</p></div><div class="row between wrap"><div><h3 class="section-title">🛍️ Бьюти-магазин</h3><p class="subtle">Большая коллекция мебели, питомцевых spa-наборов, аксессуаров, тем и рамок.</p></div><div class="row wrap"><button class="btn secondary small" data-route="collections">Коллекции</button><span class="tag">✨ ${data.xp} XP</span></div></div><section class="card"><div class="row between"><div><span class="label">Предмет дня</span><h3 style="margin:4px 0">${daily.icon} ${esc2(daily.title)}</h3><p class="subtle">Сегодня скидка 25% на XP.</p></div><span class="tag">−25%</span></div><div class="row wrap" style="margin-top:10px"><button class="btn" data-shop-day="${daily.id}">Получить за ${Math.max(0,Math.floor(daily.cost*.75))} XP</button><span class="mjx-rarity">${esc2(daily.rarity)}</span></div></section><div class="chip-tabs" style="margin:12px 0"><button class="active" data-mjx-filter="all">Все</button><button data-mjx-filter="pet">Питомец</button><button data-mjx-filter="furniture">Комнаты и мебель</button><button data-mjx-filter="theme">Темы</button><button data-mjx-filter="rare">Редкие</button></div><div class="mjx-grid mjx-grid-4" id="mjxShopGrid">${all.slice(0,80).map(shopCard2).join('')}</div></div>`}
function shopCard2(item){const own=data.shop?.owned?.includes(item.id);const src=item.image?`<img src="${item.image}" alt="${esc2(item.title)}">`:`<div class="emoji">${item.icon}</div>`;return `<article class="card mjx-shop-item" data-mjx-shop-item="${item.id}" data-type="${item.type}" data-rarity="${item.rarity}"><div class="mjx-art">${src}</div><div class="row between"><span class="mjx-rarity">${esc2(item.rarity)}</span>${item.collection?`<span class="subtle">${esc2(item.collection)}</span>`:''}</div><h4 style="margin:10px 0 4px">${esc2(item.title)}</h4><p class="subtle">${esc2(item.desc||'Коллекционный предмет')}</p><div class="row between" style="margin-top:10px"><strong>${own?'Получено':'✦ '+item.cost+' XP'}</strong><button class="btn ${own?'secondary':''} small" data-mjx-buy="${item.id}">${own?'Использовать':'Получить'}</button></div></article>`}

function mysteryPage(){ensure();const today=new Date().toISOString().slice(0,10);const ready=data.mjx.mystery.date!==today||!data.mjx.mystery.opened;return `<div class="mjx-shell"><section class="card hero"><div class="row between wrap"><div><div class="label">Ежедневный подарок</div><h1 style="font-family:Georgia,serif;margin:4px 0">🎁 Бьюти-коробка</h1><p>Одна коробочка в день. Внутри всегда что-то приятное.</p></div><span class="tag">${ready?'Доступна сегодня':'Завтра будет новая'}</span></div></section><section class="mjx-box ${ready?'':'open'}" id="mjxMysteryBox"><div class="gift">${ready?'🎁':'✨'}</div><p>${ready?'Открыть подарок':'Подарок уже получен сегодня ♡'}</p><div class="mjx-spark">${ready?'':''}</div></section><div class="row" style="justify-content:center;margin-top:14px"><button class="btn" id="mjxOpenBox" ${ready?'':'disabled'}>${ready?'Открыть Бьюти-коробка ✨':'Приходи завтра ♡'}</button></div><section class="card"><h3 class="section-title">Что может выпасть</h3><div class="grid grid-3"><div class="item">✨ XP</div><div class="item">💎 Редкий предмет</div><div class="item">🏠 Мебель</div><div class="item">🎀 Аксессуар</div><div class="item">🎨 Тема</div><div class="item">🐾 Бустер питомца</div><div class="item">🧴 Spa-средство питомца</div><div class="item">👑 Коллекционный предмет</div><div class="item">🌙 Секретная находка</div></div></section></div>`}
function openMystery(){ensure();const today=new Date().toISOString().slice(0,10);if(data.mjx.mystery.date===today&&data.mjx.mystery.opened){toast('Бьюти-коробка уже открыта сегодня ♡');return}const pool=[{type:'xp',v:40,label:'+40 XP'},{type:'xp',v:80,label:'+80 XP'},{type:'pet',boost:12,label:'🐾 +12 счастья питомцу'},{type:'pet',boost:15,label:'🐾 +15 энергии питомца'},{type:'item',rarities:['Редкий','Эпический'],label:'💎 редкий предмет'},{type:'item',rarities:['Обычный','Редкий'],label:'🏠 мебель'},{type:'petitem',label:'🧴 spa-средство питомца'},{type:'theme',label:'🎨 пробная тема на сегодня'}];const r=pool[Math.floor(Math.random()*pool.length)];if(r.type==='xp')addXP(r.v,'Бьюти-коробка');if(r.type==='pet'){data.pet.happiness=Math.min(100,data.pet.happiness+r.boost);data.pet.energy=Math.min(100,data.pet.energy+r.boost)}if(r.type==='item'){const its=SHOP_CATALOG.filter(x=>!data.shop.owned.includes(x.id)&&r.rarities.includes(x.rarity)&&!window.__beautyShopOnlyIds?.has(x.id));const it=its[Math.floor(Math.random()*its.length)]||SHOP_CATALOG.find(x=>!window.__beautyShopOnlyIds?.has(x.id));if(it&&!data.shop.owned.includes(it.id))data.shop.owned.push(it.id)}if(r.type==='petitem'){const its=SHOP_CATALOG.filter(x=>x.type==='pet'&&!data.shop.owned.includes(x.id)&&!window.__beautyShopOnlyIds?.has(x.id));const it=its[Math.floor(Math.random()*its.length)]||SHOP_CATALOG.find(x=>x.type==='pet');if(it&&!data.shop.owned.includes(it.id))data.shop.owned.push(it.id)}if(r.type==='theme'){const freeThemes=SHOP_CATALOG.filter(x=>x.type==='theme'&&!window.__beautyShopOnlyIds?.has(x.id));data.mjx.tempTheme={until:today,item:freeThemes[Math.floor(Math.random()*freeThemes.length)]?.id||''}}data.mjx.mystery={date:today,opened:true};save2();toast('🎁 '+r.label);render()}

const academyBase=[
['Очищение без перегруза','Узнай, как выбирать мягкое очищение и не пересушивать кожу.','очищение','Очищение кожи'],
['Увлажнение','Почему увлажнение важно даже при жирной коже и как подобрать комфортную текстуру.','увлажнение','Увлажнение кожи'],
['SPF каждый день','Как встроить фотозащиту в ежедневную рутину и не забывать про повторное нанесение.','spf','Солнцезащитный крем'],
['Ниацинамид','Разбираемся, зачем он нужен в уходе и как аккуратно начать.','ниацинамид','Ниацинамид'],
['Гиалуроновая кислота','Что она делает и почему влажная кожа может чувствовать себя комфортнее.','гиалуроновая кислота','Гиалуроновая кислота'],
['Керамиды','Как поддерживать кожный барьер и чем полезны керамиды.','керамиды','Керамид'],
['Ретиноиды','Базовая теория о ретиноидах и почему постепенность важнее количества.','ретинол','Ретинол'],
['Кислоты','AHA/BHA: разные задачи, аккуратный ввод и важность переносимости.','кислоты','AHA'],
['Маски','Как понять, нужна ли тебе дополнительная маска и как не перегружать рутину.','маски','Маска для лица'],
['Термозащита','Зачем она нужна при горячих укладках и как встроить её в hair-ритуал.','термозащита','Термозащита'],
['Уход за длиной','Как уменьшать ломкость и поддерживать мягкость длины.','волосы','Уход за волосами'],
['Кожа головы','Базовые принципы мягкого ухода за кожей головы.','кожа головы','Кожа головы'],
['Повреждённые волосы','Что помогает сократить механический стресс и сохранить длину.','поврежденные волосы','Повреждение волос'],
['Окрашенные волосы','Как сохранить комфорт, блеск и бережное отношение к окрашенной длине.','окрашенные волосы','Окрашенные волосы'],
['Beauty-ритуал','Как собрать короткую устойчивую рутину, которую реально хочется выполнять.','рутина красоты','Уход за кожей']
];
const ACADEMY_SOURCES=[
{title:'Как выбрать очищение без агрессии',url:'https://www.cosmo.ru/beauty/',source:'Cosmopolitan',text:'Разбор того, как подобрать мягкое средство для умывания и не пересушить кожу ежедневным уходом.'},
{title:'Зачем увлажнение нужно любой коже',url:'https://www.elle.ru/krasota/',source:'ELLE',text:'Материалы о том, как выбрать текстуру увлажняющего крема под тип кожи, включая жирную.'},
{title:'Солнцезащита каждый день',url:'https://www.beautyinsider.ru/',source:'Beauty Insider',text:'Независимый блог бьюти-редакторов регулярно разбирает, как выбрать SPF и когда его обновлять.'},
{title:'Ниацинамид в уходе',url:'https://www.cosmo.ru/beauty/',source:'Cosmopolitan',text:'Обзоры активных компонентов и то, как аккуратно добавлять их в рутину.'},
{title:'Гиалуроновая кислота: как работает',url:'https://www.elle.ru/krasota/beauty_blog/',source:'ELLE',text:'Блог о косметических ингредиентах и их влиянии на комфорт кожи.'},
{title:'Кожный барьер и керамиды',url:'https://www.beautyinsider.ru/',source:'Beauty Insider',text:'Разборы того, что поддерживает защитный барьер кожи и как его не разрушить.'},
{title:'Ретинол: с чего начать',url:'https://www.cosmo.ru/beauty/',source:'Cosmopolitan',text:'Материалы про постепенное введение ретинола и типичные ошибки новичков.'},
{title:'AHA и BHA кислоты',url:'https://www.elle.ru/krasota/',source:'ELLE',text:'Обзор кислотных пилингов и того, как подобрать концентрацию под переносимость кожи.'},
{title:'Нужна ли тебе маска для лица',url:'https://www.beautyinsider.ru/',source:'Beauty Insider',text:'Тесты и отзывы на маски для лица от бьюти-редакторов.'},
{title:'Термозащита для волос',url:'https://www.cosmo.ru/beauty/hair/',source:'Cosmopolitan',text:'Советы по защите волос при горячих укладках и выборе термозащитных средств.'},
{title:'Как ухаживать за длиной волос',url:'https://www.cosmo.ru/beauty/hair/',source:'Cosmopolitan',text:'Практические советы по снижению ломкости и уходу за длинными волосами.'},
{title:'Уход за кожей головы',url:'https://www.beautyinsider.ru/',source:'Beauty Insider',text:'Разборы средств и привычек, которые помогают коже головы оставаться в порядке.'},
{title:'Восстановление повреждённых волос',url:'https://www.elle.ru/krasota/beauty_blog/',source:'ELLE',text:'Материалы о механическом стрессе для волос и способах его снизить.'},
{title:'Уход за окрашенными волосами',url:'https://www.cosmo.ru/beauty/hair/',source:'Cosmopolitan',text:'Советы, как сохранить блеск и бережно относиться к окрашенной длине.'},
{title:'Как собрать простую бьюти-рутину',url:'https://www.elle.ru/krasota/',source:'ELLE',text:'Идеи короткой устойчивой рутины ухода, которую реально хочется выполнять.'}
];
function academyPage(){ensure();const skin=data.settings.skinType,hair=data.settings.hairType;const pref=hair!=='normal'?`волосы ${hairTypeName(hair).toLowerCase()}`:`тип волос ${hairTypeName(hair).toLowerCase()}`;const online=Array.isArray(data.mjx.academy.online)?data.mjx.academy.online:[];return `<div class="mjx-shell"><div class="row between wrap"><div><h3 class="section-title">📚 Бьюти-академия</h3><p class="subtle">15 уроков, которые подстраиваются под твои предпочтения: кожа ${skinTypeName(skin).toLowerCase()}, ${pref}. Карточки автоматически дополняются свежими справками из интернета.</p></div><span class="tag">🎓 ${data.mjx.academy.done.length}/15</span></div><section class="card"><div class="row between"><div><h3 style="margin:0">Твой учебный маршрут</h3><p class="subtle">Онлайн-материалы подбираются по теме каждого урока.</p></div><button class="btn secondary small" id="mjxRefreshAcademy">↻ Обновить статьи</button></div></section><div class="mjx-grid mjx-grid-3">${academyBase.map((l,i)=>{const done=data.mjx.academy.done.includes(i);const tailored=(l[2].includes(skin)||l[2].includes(hair)||(['увлажнение','spf'].includes(l[2])));const web=online[i];return `<article class="card mjx-lesson" data-mjx-lesson="${i}"><div class="row between"><span class="tag">Урок ${i+1}</span><span class="tag">${done?'✓ Изучено':'+'+20+' XP'}</span></div><h3 style="margin:10px 0 5px">${esc2(l[0])}</h3><p class="subtle">${esc2(l[1])}</p>${tailored?'<span class="tag" style="margin-top:10px">♡ Под твоим профилем</span>':''}${web?`<div style="margin-top:12px;padding:12px;border-radius:16px;background:var(--surface2);border:1px solid var(--border)"><div class="label">🌐 Из интернета · ${esc2(web.source||'Подборка редакции')}</div><strong style="display:block;margin:5px 0">${esc2(web.title)}</strong><p class="subtle">${esc2(web.text||'').slice(0,260)}…</p><a class="btn secondary small" target="_blank" rel="noopener" href="${esc2(web.url)}">Читать статью</a></div>`:'<div class="item" style="margin-top:12px"><span class="subtle">🌐 Онлайн-статья подгружается…</span></div>'}</article>`}).join('')}</div></div>`}
function academyDaysSinceRefresh(){const ts=data.mjx.academy.lastOnline;if(!ts)return Infinity;return Math.floor((Date.now()-ts)/86400000)}
async function refreshAcademy(force=false){if(!force&&Array.isArray(data.mjx.academy.online)&&data.mjx.academy.online.length>=15&&academyDaysSinceRefresh()<3)return;const box=document.getElementById('mjxAcademyOnline');if(box)box.innerHTML='<div class="empty">Подбираю свежие статьи по темам уроков…</div>';data.mjx.academy.online=academyBase.map((l,i)=>ACADEMY_SOURCES[i]?{...ACADEMY_SOURCES[i]}:null);data.mjx.academy.lastOnline=Date.now();save2();if(location.hash.replace('#','')==='academy'){renderPage('academy');toast('Статьи для карточек обновлены ♡')}}
function openLesson(i){const l=academyBase[i];if(!data.mjx.academy.done.includes(i)){data.mjx.academy.done.push(i);addXP(20,'Урок академии');save2()}modal(`<h3>Урок ${i+1}: ${esc2(l[0])}</h3><p style="line-height:1.7">${esc2(l[1])}</p><div class="item"><strong>Твой профиль</strong><p>Кожа: ${esc2(skinTypeName(data.settings.skinType))}<br>Волосы: ${esc2(hairTypeName(data.settings.hairType))}</p></div><div class="modal-actions"><button class="btn" id="mjxLessonDone">Готово ✨</button></div>`);document.getElementById('mjxLessonDone').onclick=()=>{closeModal();location.hash='academy';if(location.hash.replace('#','')==='academy'){renderPage('academy')}}}

const INCI={};
const addInci=(keys,val)=>keys.forEach(k=>INCI[k.toLowerCase()]=val);
const BASIC={status:'green',fit:['normal','dry','oily','combination','sensitive'],tags:[],risk:'Функциональный косметический компонент; переносимость зависит от всей формулы и индивидуальной реакции.'};
const HUM={...BASIC,tags:['увлажнение'],risk:'Увлажняющий компонент; переносимость зависит от концентрации и всей формулы.'};
const BARRIER={...BASIC,tags:['барьер','смягчение'],risk:'Компонент ухода за кожным барьером; переносимость зависит от всей формулы.'};
const YELLOW={status:'yellow',fit:['normal','oily','combination'],tags:['актив'],risk:'Активный или потенциально раздражающий компонент; переносимость зависит от формы и концентрации.'};
const FRAG={status:'yellow',fit:['normal','oily','combination'],tags:['аромат'],risk:'Ароматический компонент; у чувствительной кожи может вызывать раздражение или сенсибилизацию.'};
const ACID={status:'yellow',fit:['normal','oily','combination'],tags:['кислота'],risk:'Кислотный актив; может повышать риск сухости или раздражения, особенно при сочетании нескольких активов.'};
const addNamed=(keys,name,extra={})=>addInci(keys,{...BASIC,name,...extra});

// Базовые увлажнители и барьерные компоненты.
addNamed(['glycerin','glycerine'],'Глицерин',{tags:['увлажнение'],risk:'Увлажняющий компонент; обычно хорошо переносится.'});
addNamed(['hyaluronic acid','гиалуроновая кислота'],'Гиалуроновая кислота',{tags:['увлажнение'],risk:'Увлажняющий компонент; комфорт зависит от формы и всей формулы.'});
addNamed(['sodium hyaluronate','гиалуронат натрия'],'Гиалуронат натрия',{tags:['увлажнение'],risk:'Форма гиалуроновой кислоты; увлажняющий компонент.'});
addNamed(['hydrolyzed hyaluronic acid'],'Гидролизованная гиалуроновая кислота',{tags:['увлажнение'],risk:'Увлажняющий компонент в гидролизованной форме.'});
addNamed(['panthenol','provitamin b5'],'Пантенол',{tags:['успокоение','увлажнение'],fit:['normal','dry','sensitive'],risk:'Увлажняющий и кондиционирующий компонент; обычно хорошо переносится.'});
addNamed(['betaine'],'Бетаин',{tags:['увлажнение','осмолит'],risk:'Увлажняющий и кондиционирующий компонент.'});
addNamed(['sorbitol'],'Сорбитол',HUM);
addNamed(['propanediol'],'Пропандиол',HUM);
addNamed(['propylene glycol'],'Пропиленгликоль',{tags:['увлажнение','растворитель'],risk:'Увлажняющий растворитель; у чувствительной кожи иногда вызывает раздражение.'});
addNamed(['butylene glycol'],'Бутиленгликоль',HUM);
addNamed(['pentylene glycol'],'Пентиленгликоль',HUM);
addNamed(['caprylyl glycol'],'Каприлилгликоль',{tags:['увлажнение','кондиционирование'],risk:'Увлажняющий и функциональный компонент, также используется в системе консервации.'});
addNamed(['1,2-hexanediol','hexylene glycol'],'Гексиленгликоль',{tags:['увлажнение','растворитель'],risk:'Функциональный увлажняющий растворитель.'});
addNamed(['urea','мочевина'],'Мочевина',{tags:['увлажнение'],fit:['dry','normal'],risk:'В низких концентрациях увлажняет; более высокие концентрации могут работать как кератолитик.'});
addNamed(['sodium pca'],'Натрий PCA',HUM);
addNamed(['sodium lactate'],'Лактат натрия',HUM);
addNamed(['trehalose'],'Трегалоза',HUM);
addNamed(['saccharide isomerate'],'Сахаридный изомерат',HUM);
addNamed(['beta-glucan','бета-глюкан'],'Бета-глюкан',{tags:['успокоение','увлажнение'],fit:['normal','dry','sensitive'],risk:'Увлажняющий и успокаивающий компонент.'});
addNamed(['allantoin','алантоин'],'Аллантоин',{tags:['успокоение'],fit:['normal','dry','sensitive'],risk:'Успокаивающий и кондиционирующий компонент.'});
addNamed(['bisabolol','бисаболол'],'Бисаболол',{tags:['успокоение'],fit:['normal','dry','sensitive'],risk:'Успокаивающий компонент; реакция индивидуальна.'});
addNamed(['ceramide','ceramide np','ceramide ap','ceramide eop','ceramide ns'],'Церамиды',{tags:['барьер'],fit:['normal','dry','sensitive'],risk:'Компоненты поддержки кожного барьера.'});
addNamed(['cholesterol'],'Холестерин',{tags:['барьер'],fit:['normal','dry','sensitive'],risk:'Липидный компонент барьерных формул.'});
addNamed(['phytosphingosine'],'Фитосфингозин',{tags:['барьер'],fit:['normal','dry','sensitive'],risk:'Липидоподобный компонент барьерной поддержки.'});
addNamed(['squalane','сквалан'],'Сквалан',{tags:['смягчение'],fit:['dry','normal','sensitive'],risk:'Смягчающий компонент; ощущение зависит от формулы.'});
addNamed(['squalene'],'Сквален',{tags:['смягчение'],fit:['dry','normal'],risk:'Липидный смягчающий компонент.'});
addNamed(['phospholipids'],'Фосфолипиды',{tags:['барьер','смягчение'],fit:['normal','dry','sensitive'],risk:'Липидные компоненты барьерных формул.'});

// Масла, эстеры и смягчители.
addNamed(['coconut oil','cocos nucifera (coconut) oil'],'Кокосовое масло',{tags:['масло','смягчение'],fit:['dry','normal'],risk:'Смягчающее масло; для части людей может ощущаться тяжёлым.'});
addNamed(['argan oil','argania spinosa kernel oil'],'Аргановое масло',{tags:['масло','смягчение'],fit:['dry','normal'],risk:'Смягчающее растительное масло.'});
addNamed(['jojoba oil','simmondsia chinensis seed oil'],'Масло жожоба',{tags:['масло','смягчение'],fit:['dry','normal','combination'],risk:'Смягчающее растительное масло.'});
addNamed(['sunflower seed oil','helianthus annuus seed oil'],'Подсолнечное масло',{tags:['масло','смягчение'],fit:['dry','normal'],risk:'Смягчающее растительное масло.'});
addNamed(['olive oil','olea europaea fruit oil'],'Оливковое масло',{tags:['масло','смягчение'],fit:['dry','normal'],risk:'Смягчающее растительное масло; может быть тяжёлым для некоторых формул/типов кожи.'});
addNamed(['sweet almond oil','prunus amygdalus dulcis oil'],'Масло сладкого миндаля',{tags:['масло','смягчение'],fit:['dry','normal'],risk:'Смягчающее растительное масло.'});
addNamed(['avocado oil','persea gratissima oil'],'Масло авокадо',{tags:['масло','смягчение'],fit:['dry','normal'],risk:'Питательное смягчающее масло.'});
addNamed(['grape seed oil','vitis vinifera seed oil'],'Масло виноградной косточки',{tags:['масло','смягчение'],fit:['dry','normal','combination'],risk:'Лёгкое смягчающее растительное масло.'});
addNamed(['rosehip oil','rosa canina fruit oil'],'Масло шиповника',{tags:['масло','смягчение'],fit:['dry','normal'],risk:'Растительное масло; переносимость индивидуальна.'});
addNamed(['shea butter','butyrospermum parkii butter'],'Масло ши',{tags:['смягчение'],fit:['dry','normal'],risk:'Плотный смягчающий компонент; часто используется в формулах для сухой кожи.'});
addNamed(['cocoa butter','theobroma cacao seed butter'],'Масло какао',{tags:['смягчение'],fit:['dry','normal'],risk:'Плотный смягчающий компонент.'});
addNamed(['mango butter','mangifera indica seed butter'],'Масло манго',{tags:['смягчение'],fit:['dry','normal'],risk:'Смягчающий растительный компонент.'});
addNamed(['cetyl alcohol'],'Цетиловый спирт',{tags:['смягчение','структурообразователь'],risk:'Жирный спирт; не относится к летучим спиртам и используется как смягчитель/структурообразователь.'});
addNamed(['cetearyl alcohol'],'Цетеариловый спирт',{tags:['смягчение','структурообразователь'],risk:'Жирный спирт; обычно используется как смягчитель и структурообразователь.'});
addNamed(['stearyl alcohol'],'Стеариловый спирт',{tags:['смягчение','структурообразователь'],risk:'Жирный спирт; используется как смягчитель и структурообразователь.'});
addNamed(['behenyl alcohol'],'Бегениловый спирт',{tags:['смягчение','структурообразователь'],risk:'Жирный спирт; используется как смягчитель и структурообразователь.'});
addNamed(['isopropyl myristate'],'Изопропилмиристат',{tags:['смягчение'],risk:'Эстер-смягчитель; у склонной к комедонам кожи переносимость может отличаться.'});
addNamed(['isopropyl palmitate'],'Изопропилпальмитат',{tags:['смягчение'],risk:'Эстер-смягчитель; переносимость индивидуальна.'});
addNamed(['ethylhexyl palmitate'],'Этилгексилпальмитат',{tags:['смягчение'],risk:'Эстер-смягчитель; переносимость индивидуальна.'});
addNamed(['caprylic/capric triglyceride','caprylic capric triglyceride'],'Каприловый/каприновый триглицерид',{tags:['смягчение'],risk:'Распространённый нейтральный смягчитель.'});

// Силиконы и кондиционирующие компоненты.
addNamed(['dimethicone'],'Диметикон',{tags:['силикон','защита'],risk:'Силиконовый компонент, создающий скользящую защитную плёнку на волосах/коже.'});
addNamed(['cyclopentasiloxane'],'Циклопентасилоксан',{tags:['силикон','скольжение'],risk:'Летучий силикон; используется для лёгкого распределения и скольжения.'});
addNamed(['cyclohexasiloxane'],'Циклогексасилоксан',{tags:['силикон','скольжение'],risk:'Летучий силикон; используется для текстуры и скольжения.'});
addNamed(['amodimethicone'],'Аmodиметикон',{tags:['силикон','волосы'],fit:['dry','normal','colored','damaged'],risk:'Кондиционирующий силикон для волос; может улучшать скольжение и внешний вид повреждённой длины.'});
addNamed(['dimethiconol'],'Диметиконол',{tags:['силикон','волосы'],fit:['dry','normal','colored','damaged'],risk:'Кондиционирующий силикон для волос.'});
addNamed(['trimethylsiloxysilicate'],'Триметилсилоксисиликат',{tags:['плёнкообразователь'],risk:'Плёнкообразующий компонент; свойства зависят от формулы.'});
addNamed(['polyquaternium-7'],'Поликватерниум-7',{tags:['кондиционирование','волосы'],fit:['dry','normal','colored','damaged'],risk:'Кондиционирующий полимер, часто используемый в средствах для волос.'});
addNamed(['polyquaternium-10'],'Поликватерниум-10',{tags:['кондиционирование','волосы'],fit:['dry','normal','colored','damaged'],risk:'Кондиционирующий полимер для волос.'});
addNamed(['guar hydroxypropyltrimonium chloride'],'Гуар гидроксипропилтримониум хлорид',{tags:['кондиционирование','волосы'],fit:['dry','normal','colored','damaged'],risk:'Кондиционирующий компонент для волос.'});

// Восстанавливающие/активные компоненты.
addNamed(['niacinamide','витамин b3','b3','nicotinamide'],'Ниацинамид',{tags:['барьер','себум'],fit:['normal','oily','combination','sensitive'],risk:'Активный компонент; высокая концентрация может раздражать чувствительную кожу.'});
addNamed(['zinc pca'],'Цинк PCA',{tags:['себум','увлажнение'],fit:['oily','combination'],risk:'Компонент для формул с фокусом на себорегуляцию и увлажнение.'});
addNamed(['azelaic acid'],'Азелаиновая кислота',{...ACID,name:'Азелаиновая кислота',fit:['normal','oily','combination','sensitive'],tags:['кислота','актив'],risk:'Активная кислота; может вызывать жжение или сухость при высокой концентрации.'});
addNamed(['salicylic acid','салициловая кислота'],'Салициловая кислота',{...ACID,name:'Салициловая кислота',fit:['oily','combination'],tags:['кислота','поры'],risk:'Кислотный актив; может сушить и раздражать чувствительную кожу.'});
addNamed(['glycolic acid','гликолевая кислота'],'Гликолевая кислота',{...ACID,name:'Гликолевая кислота',tags:['кислота','текстура'],risk:'Кислотный актив с потенциальным раздражением; вводить постепенно.'});
addNamed(['lactic acid','молочная кислота'],'Молочная кислота',{...ACID,name:'Молочная кислота',fit:['normal','dry','sensitive'],tags:['кислота','увлажнение'],risk:'AHA-кислота; потенциально может раздражать, особенно при сочетании с другими активами.'});
addNamed(['mandelic acid'],'Миндальная кислота',{...ACID,name:'Миндальная кислота',tags:['кислота','текстура'],risk:'AHA-кислота; может вызывать сухость или раздражение.'});
addNamed(['gluconolactone'],'Глюконолактон',{...ACID,name:'Глюконолактон',fit:['normal','dry','sensitive'],tags:['кислота','мягкое обновление'],risk:'Мягкий кислотный актив; переносимость индивидуальна.'});
addNamed(['salicylic acid','bha'],'Салицилаты / BHA',{...ACID,name:'BHA (салициловая кислота)',fit:['oily','combination'],tags:['кислота','поры'],risk:'Кислотный актив; может сушить и раздражать.'});
addNamed(['retinol'],'Ретинол',{...YELLOW,name:'Ретинол',tags:['ретиноид','обновление'],risk:'Ретиноид; может вызывать сухость и раздражение, вводится постепенно.'});
addNamed(['retinal','retinaldehyde'],'Ретиналь',{...YELLOW,name:'Ретиналь',tags:['ретиноид','обновление'],risk:'Ретиноид; может вызывать сухость и раздражение.'});
addNamed(['retinyl palmitate'],'Ретинилпальмитат',{...YELLOW,name:'Ретинилпальмитат',tags:['витамин A'],risk:'Производное витамина A; переносимость зависит от формулы.'});
addNamed(['ascorbic acid'],'Аскорбиновая кислота',{...YELLOW,name:'Аскорбиновая кислота',tags:['антиоксидант'],risk:'Кислая форма витамина C; может вызывать пощипывание и раздражение.'});
addNamed(['sodium ascorbyl phosphate'],'Фосфат аскорбила натрия',{...BASIC,name:'Фосфат аскорбила натрия',tags:['антиоксидант'],risk:'Стабильная производная витамина C; переносимость зависит от формулы.'});
addNamed(['magnesium ascorbyl phosphate'],'Фосфат аскорбила магния',{...BASIC,name:'Фосфат аскорбила магния',tags:['антиоксидант'],risk:'Производная витамина C; переносимость зависит от формулы.'});
addNamed(['tocopherol','vitamin e'],'Витамин E',{tags:['антиоксидант'],risk:'Антиоксидантный компонент; переносимость индивидуальна.'});
addNamed(['tocopheryl acetate'],'Токоферилацетат',{tags:['антиоксидант'],risk:'Стабильная производная витамина E.'});
addNamed(['ferulic acid'],'Феруловая кислота',{tags:['антиоксидант'],risk:'Антиоксидантный актив; переносимость зависит от формулы.'});
addNamed(['tranexamic acid'],'Транексамовая кислота',{tags:['осветление','актив'],risk:'Активный компонент в формулах для выравнивания тона; переносимость индивидуальна.'});
addNamed(['alpha-arbutin'],'Альфа-арбутин',{tags:['осветление','актив'],risk:'Активный компонент для выравнивания тона.'});
addNamed(['arbutin'],'Арбутин',{tags:['осветление','актив'],risk:'Активный компонент для выравнивания тона.'});
addNamed(['kojic acid'],'Койевая кислота',{...YELLOW,name:'Койевая кислота',tags:['осветление','актив'],risk:'Активный компонент; у чувствительной кожи возможна реакция.'});
addNamed(['licorice root extract','glycyrrhiza glabra root extract'],'Экстракт солодки',{tags:['успокоение','антиоксидант'],fit:['normal','dry','sensitive'],risk:'Растительный экстракт с успокаивающими и антиоксидантными свойствами.'});
addNamed(['centella asiatica extract','centella asiatica'],'Центелла азиатская',{tags:['успокоение'],fit:['normal','dry','sensitive'],risk:'Растительный экстракт; используется в успокаивающих формулах.'});
addNamed(['green tea extract','camellia sinensis leaf extract'],'Экстракт зелёного чая',{tags:['антиоксидант'],fit:['normal','oily','combination'],risk:'Антиоксидантный растительный экстракт.'});
addNamed(['aloe vera','aloe barbadensis leaf juice'],'Алоэ вера',{tags:['успокоение','увлажнение'],fit:['normal','dry','sensitive'],risk:'Увлажняющий растительный компонент; индивидуальная реакция возможна.'});
addNamed(['caffeine'],'Кофеин',{tags:['тонизирование'],fit:['normal','oily','combination'],risk:'Функциональный актив; переносимость зависит от формулы.'});
addNamed(['peptides'],'Пептиды',{tags:['уход','кондиционирование'],risk:'Обобщённое название пептидного комплекса; точные свойства зависят от конкретного пептида.'});
addNamed(['palmitoyl tripeptide-1'],'Пальмитоил трипептид-1',{tags:['пептид'],risk:'Пептидный компонент; используется в уходовых формулах.'});
addNamed(['palmitoyl tetrapeptide-7'],'Пальмитоил тетрапептид-7',{tags:['пептид'],risk:'Пептидный компонент; используется в уходовых формулах.'});
addNamed(['copper tripeptide-1'],'Медный трипептид-1',{tags:['пептид'],risk:'Пептидный компонент; переносимость индивидуальна.'});
addNamed(['honey','mel','mel extract'],'Мёд',{tags:['увлажнение','смягчение'],fit:['normal','dry'],risk:'Увлажняющий и смягчающий компонент; аллергическая реакция возможна у чувствительных к продуктам пчеловодства.'});

// ПАВы и очищающие компоненты.
addNamed(['sodium lauryl sulfate','sls'],'Sodium Lauryl Sulfate',{status:'yellow',fit:['oily','normal'],tags:['ПАВ','очищение'],risk:'Сильный очищающий ПАВ; может усиливать сухость или раздражение у чувствительной кожи.'});
addNamed(['sodium laureth sulfate','sles'],'Sodium Laureth Sulfate',{status:'yellow',fit:['normal','oily'],tags:['ПАВ','очищение'],risk:'Очищающий ПАВ; переносимость зависит от концентрации и формулы.'});
addNamed(['cocamidopropyl betaine'],'Кокамидопропилбетаин',{tags:['ПАВ','очищение'],risk:'Мягкий амфотерный ПАВ; у части людей возможна чувствительность.'});
addNamed(['coco-glucoside'],'Кокоглюкозид',{tags:['ПАВ','очищение'],risk:'Неионный очищающий ПАВ.'});
addNamed(['decyl glucoside'],'Децилглюкозид',{tags:['ПАВ','очищение'],risk:'Неионный очищающий ПАВ; у чувствительной кожи возможна реакция.'});
addNamed(['lauryl glucoside'],'Лаурилглюкозид',{tags:['ПАВ','очищение'],risk:'Неионный очищающий ПАВ.'});
addNamed(['sodium cocoyl isethionate'],'Изетионат натрия кокоила',{tags:['ПАВ','очищение'],risk:'Мягкий очищающий ПАВ.'});
addNamed(['disodium laureth sulfosuccinate'],'Динатрий лаурет сульфосукцинат',{tags:['ПАВ','очищение'],risk:'Очищающий ПАВ; обычно мягче некоторых сульфатов.'});
addNamed(['sodium methyl cocoyl taurate'],'Метилкокоилаурата натрия',{tags:['ПАВ','очищение'],risk:'Мягкий очищающий ПАВ.'});
addNamed(['sodium cocoyl glutamate'],'Глутамат натрия кокоила',{tags:['ПАВ','очищение'],risk:'Мягкий очищающий ПАВ.'});
addNamed(['sodium lauroyl sarcosinate'],'Лауроилсаркозинат натрия',{tags:['ПАВ','очищение'],risk:'Очищающий ПАВ.'});
addNamed(['sodium cocoyl glycinate'],'Глицинат натрия кокоила',{tags:['ПАВ','очищение'],risk:'Мягкий очищающий ПАВ.'});

// Консерванты, стабилизаторы и хелаторы.
addNamed(['phenoxyethanol'],'Феноксиэтанол',{status:'yellow',fit:['normal','oily','combination'],tags:['консервант'],risk:'Консервант; у очень чувствительной кожи иногда может вызывать раздражение.'});
addNamed(['ethylhexylglycerin'],'Этилгексилглицерин',{tags:['консервант','кондиционирование'],risk:'Функциональный компонент системы консервации.'});
addNamed(['benzoic acid'],'Бензойная кислота',{status:'yellow',fit:['normal','oily','combination'],tags:['консервант'],risk:'Консервант/регулятор; переносимость зависит от формулы.'});
addNamed(['sorbic acid'],'Сорбиновая кислота',{status:'yellow',fit:['normal','oily','combination'],tags:['консервант'],risk:'Консервант; возможна индивидуальная чувствительность.'});
addNamed(['sodium benzoate'],'Бензоат натрия',{tags:['консервант'],risk:'Консервант; переносимость зависит от формулы.'});
addNamed(['potassium sorbate'],'Сорбат калия',{tags:['консервант'],risk:'Консервант; переносимость зависит от формулы.'});
addNamed(['chlorphenesin'],'Хлорфенезин',{status:'yellow',fit:['normal','oily','combination'],tags:['консервант'],risk:'Консервант; может раздражать чувствительную кожу.'});
addNamed(['disodium edta'],'Динатрий EDTA',{tags:['хелатор','стабилизатор'],risk:'Хелатирующий стабилизатор формулы.'});
addNamed(['tetrasodium edta'],'Тетранатрий EDTA',{tags:['хелатор','стабилизатор'],risk:'Хелатирующий стабилизатор формулы.'});
addNamed(['citric acid'],'Лимонная кислота',{tags:['регулятор pH'],risk:'Чаще используется для регулирования pH; концентрированные/кислые формулы могут раздражать.'});
addNamed(['sodium citrate'],'Цитрат натрия',{tags:['регулятор pH'],risk:'Регулятор pH и буферный компонент.'});
addNamed(['sodium hydroxide'],'Гидроксид натрия',{status:'yellow',fit:['normal','oily','combination'],tags:['регулятор pH'],risk:'В косметике обычно применяется в низких концентрациях для регулирования pH; в концентрированном виде раздражающий.'});
addNamed(['potassium hydroxide'],'Гидроксид калия',{status:'yellow',fit:['normal','oily','combination'],tags:['регулятор pH'],risk:'Обычно используется для регулирования pH или омыления; переносимость зависит от концентрации.'});

// Загустители, эмульгаторы и плёнкообразователи.
addNamed(['carbomer'],'Карбомер',{tags:['загуститель'],risk:'Загуститель и стабилизатор геля.'});
addNamed(['xanthan gum'],'Ксантановая камедь',{tags:['загуститель'],risk:'Растительный/биотехнологический загуститель.'});
addNamed(['hydroxyethylcellulose'],'Гидроксиэтилцеллюлоза',{tags:['загуститель'],risk:'Загуститель и стабилизатор.'});
addNamed(['cellulose gum','carboxymethylcellulose'],'Карбоксиметилцеллюлоза',{tags:['загуститель'],risk:'Загуститель и стабилизатор.'});
addNamed(['acrylates/c10-30 alkyl acrylate crosspolymer'],'Акрилатный кроссполимер',{tags:['загуститель','стабилизатор'],risk:'Загуститель/стабилизатор эмульсий и гелей.'});
addNamed(['glyceryl stearate'],'Глицерилстеарат',{tags:['эмульгатор','смягчение'],risk:'Эмульгатор и смягчитель.'});
addNamed(['glyceryl stearate se'],'Глицерилстеарат SE',{tags:['эмульгатор','смягчение'],risk:'Эмульгатор и смягчитель.'});
addNamed(['cetearyl olivate'],'Цетеарил оливат',{tags:['эмульгатор','смягчение'],risk:'Эмульгатор/смягчитель на основе жирной кислоты и оливковых производных.'});
addNamed(['sorbitan olivate'],'Сорбитан оливат',{tags:['эмульгатор','смягчение'],risk:'Эмульгатор/смягчитель.'});
addNamed(['polysorbate 20'],'Полисорбат-20',{tags:['солюбилизатор','эмульгатор'],risk:'Солюбилизатор/эмульгатор.'});
addNamed(['polysorbate 60'],'Полисорбат-60',{tags:['эмульгатор'],risk:'Эмульгатор.'});
addNamed(['polysorbate 80'],'Полисорбат-80',{tags:['эмульгатор'],risk:'Эмульгатор/солюбилизатор.'});

// УФ-фильтры (без самостоятельной оценки соответствия солнцезащитному продукту).
const UV={status:'green',fit:['normal','dry','oily','combination','sensitive'],tags:['UV-фильтр'],risk:'UV-фильтр; эффективность продукта зависит от всей системы фильтров и заявленного SPF.'};
addInci(['zinc oxide'],{...UV,name:'Оксид цинка'});
addInci(['titanium dioxide'],{...UV,name:'Диоксид титана'});
addInci(['avobenzone','butyl methoxydibenzoylmethane'],{...UV,name:'Авобензон'});
addInci(['octocrylene'],{...UV,name:'Октокрилен'});
addInci(['octinoxate','ethylhexyl methoxycinnamate'],{...UV,name:'Этилгексилметоксициннамат'});
addInci(['octisalate','ethylhexyl salicylate'],{...UV,name:'Этилгексилсалицилат'});
addInci(['homosalate'],{...UV,name:'Гомосалат'});
addInci(['bemotrizinol','bis-ethylhexyloxyphenol methoxyphenyl triazine'],{...UV,name:'Бис-этилгексилоксифенол метоксифенил триазин'});
addInci(['bisoctrizole','methylene bis-benzotriazolyl tetramethylbutylphenol'],{...UV,name:'МББТ / Бисоктритизол'});
addInci(['ecamsule','terephthalylidene dicamphor sulfonic acid'],{...UV,name:'Экamsule'});

// Ароматические компоненты и эфирные масла.
addNamed(['parfum','fragrance','parfum/fragrance'],'Отдушка',{...FRAG,name:'Отдушка'});
addNamed(['linalool'],'Линалоол',FRAG);
addNamed(['limonene'],'Лимонен',FRAG);
addNamed(['citronellol'],'Цитронеллол',FRAG);
addNamed(['geraniol'],'Гераниол',FRAG);
addNamed(['eugenol'],'Эвгенол',FRAG);
addNamed(['citral'],'Цитраль',FRAG);
addNamed(['coumarin'],'Кумарин',FRAG);
addNamed(['benzyl alcohol'],'Бензиловый спирт',{status:'yellow',fit:['normal','oily','combination'],tags:['консервант','аромат'],risk:'Может использоваться как консервант или ароматический компонент; у чувствительной кожи возможна реакция.'});
addNamed(['benzyl salicylate'],'Бензилсалицилат',FRAG);
addNamed(['benzyl benzoate'],'Бензилбензоат',FRAG);
addNamed(['hexyl cinnamal'],'Гексилциннамаль',FRAG);
addNamed(['alpha-isomethyl ionone'],'Альфа-изометилионон',FRAG);
addNamed(['menthol'],'Ментол',{status:'yellow',fit:['normal','oily'],tags:['охлаждение','аромат'],risk:'Охлаждающий ароматический компонент; может раздражать чувствительную кожу.'});
addNamed(['peppermint oil','mentha piperita oil'],'Масло мяты',{...FRAG,name:'Масло мяты',tags:['эфирное масло','аромат'],risk:'Эфирное масло; потенциально раздражающий ароматический компонент.'});
addNamed(['tea tree oil','melaleuca alternifolia leaf oil'],'Масло чайного дерева',{...FRAG,name:'Масло чайного дерева',tags:['эфирное масло','аромат'],risk:'Эфирное масло; может раздражать чувствительную кожу.'});
addNamed(['lavender oil','lavandula angustifolia oil'],'Лавандовое масло',{...FRAG,name:'Лавандовое масло',tags:['эфирное масло','аромат'],risk:'Эфирное масло; потенциальная индивидуальная чувствительность.'});

// Волосы: белки, аминокислоты и кондиционирующие агенты.
addNamed(['hydrolyzed keratin'],'Гидролизованный кератин',{tags:['белок','волосы','кондиционирование'],fit:['dry','normal','damaged','colored'],risk:'Белковый кондиционирующий компонент для волос.'});
addNamed(['hydrolyzed wheat protein'],'Гидролизованный пшеничный протеин',{tags:['белок','волосы'],fit:['dry','normal','damaged','colored'],risk:'Белковый кондиционирующий компонент.'});
addNamed(['hydrolyzed silk'],'Гидролизованный шёлк',{tags:['белок','волосы'],fit:['dry','normal','damaged','colored'],risk:'Кондиционирующий белковый компонент.'});
addNamed(['hydrolyzed rice protein'],'Гидролизованный рисовый протеин',{tags:['белок','волосы'],fit:['dry','normal','damaged','colored'],risk:'Белковый кондиционирующий компонент.'});
addNamed(['hydrolyzed soy protein'],'Гидролизованный соевый протеин',{tags:['белок','волосы'],fit:['dry','normal','damaged','colored'],risk:'Белковый кондиционирующий компонент.'});
addNamed(['arginine'],'Аргинин',{tags:['аминокислота','волосы'],fit:['dry','normal','damaged','colored'],risk:'Аминокислотный кондиционирующий компонент.'});
addNamed(['serine'],'Серин',{tags:['аминокислота','волосы'],fit:['dry','normal','damaged','colored'],risk:'Аминокислотный компонент.'});
addNamed(['glycine'],'Глицин',{tags:['аминокислота','волосы'],fit:['dry','normal','damaged','colored'],risk:'Аминокислотный компонент.'});
addNamed(['alanine'],'Аланин',{tags:['аминокислота','волосы'],fit:['dry','normal','damaged','colored'],risk:'Аминокислотный компонент.'});
addNamed(['proline'],'Пролин',{tags:['аминокислота','волосы'],fit:['dry','normal','damaged','colored'],risk:'Аминокислотный компонент.'});
addNamed(['cystine'],'Цистин',{tags:['аминокислота','волосы'],fit:['dry','normal','damaged','colored'],risk:'Аминокислотный компонент.'});
addNamed(['hydrolyzed oat protein'],'Гидролизованный овсяный протеин',{tags:['белок','волосы'],fit:['dry','normal','damaged','colored'],risk:'Белковый кондиционирующий компонент.'});
addNamed(['behentrimonium chloride'],'Бехентримониум хлорид',{tags:['кондиционирование','волосы'],fit:['dry','normal','damaged','colored'],risk:'Катионный кондиционирующий компонент для волос; концентрация и время контакта имеют значение.'});
addNamed(['cetrimonium chloride'],'Цетримониум хлорид',{status:'yellow',fit:['dry','normal','damaged','colored'],tags:['кондиционирование','волосы'],risk:'Катионный кондиционирующий компонент; в высоких концентрациях может раздражать.'});
addNamed(['steartrimonium chloride'],'Стеартримониум хлорид',{tags:['кондиционирование','волосы'],fit:['dry','normal','damaged','colored'],risk:'Катионный кондиционирующий компонент.'});
addNamed(['cocodimonium hydroxypropyl hydrolyzed wheat protein'],'Кокодимониум гидроксипропил гидролизованный пшеничный протеин',{tags:['кондиционирование','волосы'],fit:['dry','normal','damaged','colored'],risk:'Кондиционирующий белковый компонент для волос.'});

// Частые базовые компоненты.
addInci(['aqua','water'],{...BASIC,name:'Вода',tags:['основа'],risk:'Основной растворитель/основа формулы.'});
addNamed(['alcohol denat','denat. alcohol','alcohol denat.'],'Денатурированный спирт',{status:'yellow',fit:['oily'],tags:['растворитель'],risk:'Летучий спирт; в некоторых формулах может усиливать сухость или раздражение.'});
addNamed(['isopropyl alcohol','isopropanol'],'Изопропиловый спирт',{status:'yellow',fit:['oily'],tags:['растворитель'],risk:'Летучий спирт; может усиливать сухость и раздражение.'});
addNamed(['paraffinum liquidum','mineral oil'],'Минеральное масло',{tags:['смягчение'],fit:['dry','normal','sensitive'],risk:'Окклюзивный смягчающий компонент.'});
addNamed(['petrolatum'],'Вазелин',{tags:['окклюзия','смягчение'],fit:['dry','sensitive'],risk:'Сильный окклюзивный компонент, снижающий потерю воды.'});
addNamed(['microcrystalline wax'],'Микрокристаллический воск',{tags:['текстура','защита'],fit:['dry','normal'],risk:'Воскообразный структурообразующий компонент.'});


// Дополнительное расширение INCI: эмульгаторы, загустители, силиконы, ПАВы,
// консерванты, хелаторы, экстракты, активы и частые компоненты средств для волос.
addNamed(['sodium polyacrylate'],'Полиакрилат натрия',{tags:['текстура','загуститель']});
addNamed(['carbomer'],'Карбомер',{tags:['загуститель','текстура']});
addNamed(['hydroxyethylcellulose'],'Гидроксиэтилцеллюлоза',{tags:['загуститель','текстура']});
addNamed(['cellulose gum','carboxymethylcellulose'],'Карбоксиметилцеллюлоза',{tags:['загуститель','текстура']});
addNamed(['xanthan gum'],'Ксантановая камедь',{tags:['загуститель','стабилизатор']});
addNamed(['sclerotium gum'],'Склероциумовая камедь',{tags:['загуститель','стабилизатор']});
addNamed(['guar hydroxypropyltrimonium chloride'],'Гуар гидроксипропилтримониум хлорид',{tags:['кондиционирование','волосы'],fit:['dry','normal','damaged','colored'],risk:'Катионный полимер для кондиционирования и снижения спутывания волос.'});
addNamed(['hydroxypropyl guar hydroxypropyltrimonium chloride'],'Гидроксипропилгуар гидроксипропилтримониум хлорид',{tags:['кондиционирование','волосы'],fit:['dry','normal','damaged','colored'],risk:'Кондиционирующий полимер для волос.'});
addNamed(['polyquaternium-7'],'Поликватерниум-7',{tags:['кондиционирование','волосы'],fit:['dry','normal','damaged','colored'],risk:'Кондиционирующий полимер, помогает уменьшать статическое электричество и спутывание.'});
addNamed(['polyquaternium-10'],'Поликватерниум-10',{tags:['кондиционирование','волосы'],fit:['dry','normal','damaged','colored'],risk:'Кондиционирующий полимер для волос.'});
addNamed(['polyquaternium-37'],'Поликватерниум-37',{tags:['кондиционирование','волосы'],fit:['dry','normal','damaged','colored'],risk:'Плёнкообразующий кондиционирующий полимер.'});
addNamed(['polyquaternium-51'],'Поликватерниум-51',{tags:['увлажнение','кондиционирование'],fit:['normal','dry','sensitive'],risk:'Плёнкообразующий увлажняющий компонент.'});

addNamed(['dimethicone'],'Диметикон',{tags:['силикон','разглаживание'],fit:['dry','normal','damaged','colored'],risk:'Силиконовый кондиционирующий компонент; помогает уменьшать трение и потерю влаги волосами.'});
addNamed(['dimethiconol'],'Диметиконол',{tags:['силикон','разглаживание'],fit:['dry','normal','damaged','colored'],risk:'Силиконовый кондиционирующий компонент для кожи и волос.'});
addNamed(['amodimethicone'],'Аминодиметикон',{tags:['силикон','волосы'],fit:['dry','normal','damaged','colored'],risk:'Силиконовый кондиционирующий компонент, часто используется для повреждённой длины.'});
addNamed(['cyclopentasiloxane'],'Циклопентасилоксан',{tags:['силикон','текстура'],fit:['normal','dry','oily','combination'],risk:'Летучий силикон, улучшает распределение и ощущение формулы.'});
addNamed(['cyclohexasiloxane'],'Циклогексасилоксан',{tags:['силикон','текстура'],fit:['normal','dry','oily','combination'],risk:'Летучий силикон для сенсорики и распределения.'});
addNamed(['trimethylsiloxysilicate'],'Триметилсилоксисиликат',{tags:['силикон','плёнкообразователь'],fit:['normal','oily','combination'],risk:'Плёнкообразующий силиконовый компонент.'});
addNamed(['phenyl trimethicone'],'Фенилтриметикон',{tags:['силикон','блеск'],fit:['normal','dry','damaged','colored'],risk:'Силиконовый компонент для гладкости и блеска.'});
addNamed(['polysilicone-11'],'Полисиликон-11',{tags:['силикон','плёнкообразователь'],fit:['normal','dry','oily','combination'],risk:'Силиконовый плёнкообразователь, улучшает ощущение формулы.'});
addNamed(['silicone quaternium-16'],'Силикон кватерниум-16',{tags:['силикон','волосы'],fit:['dry','normal','damaged','colored'],risk:'Кондиционирующий силикон для волос.'});

addNamed(['cocamidopropyl betaine'],'Кокамидопропилбетаин',{tags:['ПАВ','очищение'],risk:'Мягкий амфотерный поверхностно-активный компонент; у части людей возможна индивидуальная реакция.'});
addNamed(['coco betaine'],'Кокобетаин',{tags:['ПАВ','очищение'],risk:'Амфотерный ПАВ для мягкого очищения.'});
addNamed(['sodium cocoyl isethionate'],'Кокоилизетионат натрия',{tags:['ПАВ','очищение'],risk:'Мягкий очищающий ПАВ.'});
addNamed(['sodium lauroyl sarcosinate'],'Лауроилсаркозинат натрия',{tags:['ПАВ','очищение'],risk:'Очищающий ПАВ средней мягкости.'});
addNamed(['disodium laureth sulfosuccinate'],'Динатрий лауретсульфосукцинат',{tags:['ПАВ','очищение'],risk:'Очищающий ПАВ; обычно используется в мягких формулах.'});
addNamed(['sodium methyl cocoyl taurate'],'Метилкокоилтаурат натрия',{tags:['ПАВ','очищение'],risk:'Мягкий анионный ПАВ.'});
addNamed(['sodium lauryl sulfoacetate'],'Лаурилсульфоацетат натрия',{tags:['ПАВ','очищение'],risk:'Очищающий ПАВ; не следует путать с sodium lauryl sulfate.'});
addNamed(['sodium cocoyl glutamate'],'Кокоилглутамат натрия',{tags:['ПАВ','очищение'],risk:'Мягкий аминокислотный ПАВ.'});
addNamed(['disodium cocoyl glutamate'],'Динатрий кокоилглутамат',{tags:['ПАВ','очищение'],risk:'Мягкий аминокислотный ПАВ.'});
addNamed(['sodium lauroyl glutamate'],'Лауроилглутамат натрия',{tags:['ПАВ','очищение'],risk:'Мягкий аминокислотный ПАВ.'});
addNamed(['sodium lauryl glucose carboxylate'],'Лаурилглюкозид карбоксилат натрия',{tags:['ПАВ','очищение'],risk:'Мягкий очищающий ПАВ.'});
addNamed(['decyl glucoside'],'Децилглюкозид',{tags:['ПАВ','очищение'],risk:'Неионный ПАВ; обычно используется в мягких очищающих формулах.'});
addNamed(['coco glucoside'],'Кокоглюкозид',{tags:['ПАВ','очищение'],risk:'Неионный ПАВ для мягкого очищения.'});
addNamed(['lauryl glucoside'],'Лаурилглюкозид',{tags:['ПАВ','очищение'],risk:'Неионный очищающий ПАВ.'});
addNamed(['caprylyl/capryl glucoside'],'Каприлил/каприлглюкозид',{tags:['ПАВ','солюбилизатор'],risk:'Мягкий ПАВ и солюбилизатор.'});
addNamed(['sodium lauryl sulfate'],'Лаурилсульфат натрия',{status:'yellow',fit:['oily','combination'],tags:['ПАВ','очищение'],risk:'Сильный очищающий ПАВ; у сухой и чувствительной кожи может усиливать сухость.'});
addNamed(['sodium laureth sulfate'],'Лауретсульфат натрия',{status:'yellow',fit:['oily','combination'],tags:['ПАВ','очищение'],risk:'Очищающий ПАВ; переносимость зависит от формулы и времени контакта.'});
addNamed(['ammonium lauryl sulfate'],'Лаурилсульфат аммония',{status:'yellow',fit:['oily','combination'],tags:['ПАВ','очищение'],risk:'Очищающий ПАВ; может быть более ощутимым для сухой кожи.'});
addNamed(['ammonium laureth sulfate'],'Лауретсульфат аммония',{status:'yellow',fit:['oily','combination'],tags:['ПАВ','очищение'],risk:'Очищающий ПАВ.'});

addNamed(['glyceryl stearate'],'Глицерилстеарат',{tags:['эмульгатор','смягчение'],fit:['normal','dry'],risk:'Эмульгирующий и смягчающий компонент.'});
addNamed(['glyceryl stearate se'],'Глицерилстеарат SE',{tags:['эмульгатор','смягчение'],fit:['normal','dry'],risk:'Эмульгирующий и смягчающий компонент.'});
addNamed(['cetearyl alcohol'],'Цетеариловый спирт',{tags:['жирный спирт','смягчение','волосы'],fit:['normal','dry','sensitive'],risk:'Жирный спирт; используется для текстуры и кондиционирования, не равен летучему спирту.'});
addNamed(['cetyl alcohol'],'Цетиловый спирт',{tags:['жирный спирт','смягчение'],fit:['normal','dry','sensitive'],risk:'Жирный спирт для текстуры и смягчения.'});
addNamed(['stearyl alcohol'],'Стеариловый спирт',{tags:['жирный спирт','смягчение'],fit:['normal','dry','sensitive'],risk:'Жирный спирт; структурообразующий и смягчающий компонент.'});
addNamed(['behenyl alcohol'],'Бегениловый спирт',{tags:['жирный спирт','смягчение'],fit:['normal','dry','sensitive'],risk:'Жирный спирт для текстуры и смягчения.'});
addNamed(['isopropyl myristate'],'Изопропилмиристат',{tags:['эстер','смягчение'],fit:['dry','normal'],risk:'Смягчающий эфир; может ощущаться плотным у некоторых формул.'});
addNamed(['isopropyl palmitate'],'Изопропилпальмитат',{tags:['эстер','смягчение'],fit:['dry','normal'],risk:'Смягчающий эфир; переносимость индивидуальна.'});
addNamed(['ethylhexyl palmitate'],'Этилгексилпальмитат',{tags:['эстер','смягчение'],fit:['dry','normal'],risk:'Смягчающий эфир.'});
addNamed(['c12-15 alkyl benzoate'],'C12-15 Alkyl Benzoate',{tags:['смягчение','UV-формулы'],fit:['normal','oily','combination'],risk:'Лёгкий эмолент, часто используется в солнцезащитных формулах.'});
addNamed(['isoamyl laurate'],'Изоамиллаурат',{tags:['смягчение'],fit:['normal','oily','combination'],risk:'Лёгкий эмолент.'});
addNamed(['ethylhexyl cocoate'],'Этилгексилкокоат',{tags:['смягчение'],fit:['normal','dry'],risk:'Эмолент для смягчения кожи и волос.'});

addNamed(['phenoxyethanol'],'Феноксиэтанол',{status:'yellow',fit:['normal','oily','combination'],tags:['консервант'],risk:'Консервант; в разрешённых косметических концентрациях обычно используется безопасно, но чувствительность индивидуальна.'});
addNamed(['ethylhexylglycerin'],'Этилгексилглицерин',{tags:['консервирующая система','смягчение'],risk:'Функциональный компонент системы консервации и кондиционирования.'});
addNamed(['sodium benzoate'],'Бензоат натрия',{tags:['консервант'],risk:'Консервант.'});
addNamed(['potassium sorbate'],'Сорбат калия',{tags:['консервант'],risk:'Консервант.'});
addNamed(['sorbic acid'],'Сорбиновая кислота',{tags:['консервант'],risk:'Консервант.'});
addNamed(['benzyl alcohol'],'Бензиловый спирт',{status:'yellow',fit:['normal','oily','combination'],tags:['консервант','аромат'],risk:'Может использоваться как консервант или ароматический компонент; чувствительность индивидуальна.'});
addNamed(['dehydroacetic acid'],'Дегидроуксусная кислота',{tags:['консервант'],risk:'Консервант.'});
addNamed(['chlorphenesin'],'Хлорфенезин',{status:'yellow',fit:['normal','oily','combination'],tags:['консервант'],risk:'Консервант; чувствительность индивидуальна.'});
addNamed(['caprylhydroxamic acid'],'Каприлгидроксамовая кислота',{tags:['консервант','хелатор'],risk:'Компонент системы консервации.'});
addNamed(['sodium dehydroacetate'],'Дегидроацетат натрия',{tags:['консервант'],risk:'Консервант.'});
addNamed(['disodium edta'],'Динатрий EDTA',{tags:['хелатор','стабилизация'],risk:'Хелатор, помогает стабилизировать формулу; сам по себе не является активом ухода.'});
addNamed(['tetrasodium edta'],'Тетранатрий EDTA',{tags:['хелатор','стабилизация'],risk:'Хелатор и стабилизатор формулы.'});
addNamed(['sodium phytate'],'Фитат натрия',{tags:['хелатор','антиоксидантная система'],risk:'Хелатор и вспомогательный стабилизатор.'});

addNamed(['tocopherol'],'Токоферол / витамин E',{tags:['антиоксидант'],fit:['normal','dry'],risk:'Антиоксидант и компонент ухода; индивидуальная переносимость зависит от формулы.'});
addNamed(['tocopheryl acetate'],'Ацетат токоферола',{tags:['антиоксидант'],fit:['normal','dry'],risk:'Стабильная форма витамина E.'});
addNamed(['ferulic acid'],'Феруловая кислота',{...ACID,name:'Феруловая кислота',tags:['антиоксидант','кислота'],risk:'Антиоксидантный актив; может входить в формулы с витамином C и E.'});
addNamed(['azelaic acid'],'Азелаиновая кислота',{...ACID,name:'Азелаиновая кислота',fit:['normal','oily','combination'],tags:['кислота','актив'],risk:'Активная кислота; у части людей может вызывать сухость или пощипывание при начале использования.'});
addNamed(['mandelic acid'],'Миндальная кислота',{...ACID,name:'Миндальная кислота'});
addNamed(['gluconolactone'],'Глюконолактон',{status:'yellow',fit:['normal','dry','sensitive'],tags:['PHA','кислота','увлажнение'],risk:'Полигидроксикислота; обычно мягче многих AHA, но переносимость индивидуальна.'});
addNamed(['lactobionic acid'],'Лактобионовая кислота',{status:'yellow',fit:['normal','dry','sensitive'],tags:['PHA','кислота','увлажнение'],risk:'Мягкая полигидроксикислота с увлажняющими свойствами.'});
addNamed(['malic acid'],'Яблочная кислота',ACID);
addNamed(['tartaric acid'],'Винная кислота',ACID);
addNamed(['citric acid'],'Лимонная кислота',{status:'yellow',fit:['normal','oily','combination'],tags:['кислота','регулятор pH'],risk:'Часто используется для регулировки pH; в высоких концентрациях может раздражать.'});
addNamed(['gluconic acid'],'Глюконовая кислота',{status:'yellow',fit:['normal','dry','sensitive'],tags:['кислота'],risk:'Кислотный компонент; переносимость зависит от концентрации.'});

addNamed(['caffeine'],'Кофеин',{tags:['стимулирующий актив'],risk:'Функциональный актив, часто встречается в средствах для кожи вокруг глаз и кожи головы.'});
addNamed(['zinc pca'],'Цинк PCA',{tags:['себорегуляция','увлажнение'],fit:['oily','combination'],risk:'Компонент себорегулирующих и увлажняющих формул.'});
addNamed(['copper tripeptide-1'],'Медный трипептид-1',{tags:['пептид','уход'],fit:['normal','dry','combination'],risk:'Пептидный косметический актив.'});
addNamed(['palmitoyl tripeptide-1'],'Пальмитоил трипептид-1',{tags:['пептид'],fit:['normal','dry'],risk:'Пептидный косметический актив.'});
addNamed(['palmitoyl tetrapeptide-7'],'Пальмитоил тетрапептид-7',{tags:['пептид'],fit:['normal','dry'],risk:'Пептидный косметический актив.'});
addNamed(['acetyl hexapeptide-8'],'Ацетилгексапептид-8',{tags:['пептид'],fit:['normal','dry'],risk:'Пептидный косметический актив.'});
addNamed(['sh-polypeptide-1'],'sh-полипептид-1',{tags:['пептид','факторы роста'],risk:'Биоактивный косметический компонент; оценивать нужно в контексте всей формулы.'});
addNamed(['adenosine'],'Аденозин',{tags:['актив'],fit:['normal','dry'],risk:'Функциональный косметический актив.'});
addNamed(['tranexamic acid'],'Транексамовая кислота',{...ACID,name:'Транексамовая кислота',tags:['актив','осветление'],risk:'Актив для косметических формул, направленных на выравнивание тона.'});
addNamed(['alpha-arbutin'],'Альфа-арбутин',{tags:['осветление','актив'],fit:['normal','dry','oily','combination'],risk:'Осветляющий косметический актив.'});
addNamed(['arbutin'],'Арбутин',{tags:['осветление','актив'],fit:['normal','dry','oily','combination'],risk:'Осветляющий косметический актив.'});
addNamed(['licorice root extract','glycyrrhiza glabra root extract'],'Экстракт солодки',{tags:['растительный экстракт','успокоение'],fit:['normal','dry','sensitive'],risk:'Растительный экстракт; переносимость индивидуальна.'});
addNamed(['centella asiatica extract','centella asiatica leaf extract'],'Центелла азиатская',{tags:['растительный экстракт','успокоение'],fit:['normal','dry','sensitive'],risk:'Растительный успокаивающий компонент.'});
addNamed(['madecassoside'],'Мадекассосид',{tags:['успокоение','актив'],fit:['normal','dry','sensitive'],risk:'Компонент центеллы, используемый в успокаивающих формулах.'});
addNamed(['camellia sinensis leaf extract'],'Экстракт зелёного чая',{tags:['антиоксидант','растительный экстракт'],risk:'Антиоксидантный растительный компонент.'});
addNamed(['chamomilla recutita flower extract','chamomilla recutita extract'],'Экстракт ромашки',{tags:['растительный экстракт','успокоение'],fit:['normal','dry','sensitive'],risk:'Растительный успокаивающий компонент; возможна индивидуальная чувствительность.'});
addNamed(['aloe barbadensis leaf juice','aloe barbadensis leaf extract'],'Алоэ вера',{tags:['увлажнение','успокоение'],fit:['normal','dry','sensitive'],risk:'Увлажняющий растительный компонент.'});
addNamed(['hamamelis virginiana extract','hamamelis virginiana leaf extract'],'Гамамелис',{status:'green',fit:['oily','combination'],tags:['растительный экстракт','себорегуляция'],risk:'Растительный компонент; в некоторых формулах может быть вяжущим.'});
addNamed(['rosemary leaf extract','rosmarinus officinalis leaf extract'],'Экстракт розмарина',{tags:['антиоксидант','растительный экстракт'],risk:'Растительный антиоксидантный компонент.'});

// UV-фильтры, часто встречающиеся в современных солнцезащитных формулах.
addNamed(['drometrizole trisiloxane'],'Дрометризол трисилоксан',{status:'green',fit:['normal','dry','oily','combination','sensitive'],tags:['UV-фильтр'],risk:'Современный органический UV-фильтр; оценивать следует всю солнцезащитную формулу.'});
addNamed(['diethylamino hydroxybenzoyl hexyl benzoate'],'Диэтиламино гидроксибензоилгексилбензоат',{status:'green',fit:['normal','dry','oily','combination','sensitive'],tags:['UV-фильтр UVA'],risk:'UVA-фильтр в солнцезащитных формулах.'});
addNamed(['ethylhexyl triazone'],'Этилгексил триазон',{status:'green',fit:['normal','dry','oily','combination','sensitive'],tags:['UV-фильтр UVB'],risk:'Высокоэффективный UVB-фильтр.'});
addNamed(['tris-biphenyl triazine'],'Трис-бифенил триазин',{status:'green',fit:['normal','dry','oily','combination','sensitive'],tags:['UV-фильтр'],risk:'Современный органический UV-фильтр.'});
addNamed(['phenylbenzimidazole sulfonic acid'],'Фенилбензимидазолсульфоновая кислота',{status:'green',fit:['normal','dry','oily','combination','sensitive'],tags:['UV-фильтр UVB'],risk:'Водорастворимый UVB-фильтр.'});

// Частые минеральные и оптические компоненты.
addNamed(['zinc oxide'],'Оксид цинка',{status:'green',fit:['normal','dry','oily','combination','sensitive'],tags:['минеральный UV-фильтр'],risk:'Минеральный UV-фильтр и опацифицирующий компонент.'});
addNamed(['titanium dioxide'],'Диоксид титана',{status:'green',fit:['normal','dry','oily','combination','sensitive'],tags:['минеральный UV-фильтр','пигмент'],risk:'Минеральный UV-фильтр/пигмент в зависимости от формулы.'});
addNamed(['mica'],'Слюда',{tags:['текстура','пигмент'],risk:'Минеральный компонент для текстуры и оптического эффекта.'});
addNamed(['iron oxides'],'Оксиды железа',{tags:['пигмент'],risk:'Минеральные пигменты.'});
addNamed(['ultramarines'],'Ультрамарины',{tags:['пигмент'],risk:'Пигмент.'});
addNamed(['chromium oxide greens'],'Оксиды хрома',{tags:['пигмент'],risk:'Минеральный пигмент.'});



// Расширенная база INCI: часто встречающиеся увлажнители, эмульгаторы,
// консерванты, силиконы, активы, растительные экстракты и компоненты для волос.
addNamed(['hydroxyethyl urea'],'Гидроксиэтилмочевина',{tags:['увлажнение'],fit:['normal','dry','sensitive'],risk:'Увлажняющий компонент; помогает поддерживать комфорт кожи.'});
addNamed(['polyglutamic acid'],'Полиглутаминовая кислота',{tags:['увлажнение'],fit:['normal','dry','sensitive'],risk:'Плёнкообразующий увлажняющий компонент.'});
addNamed(['tremella fuciformis sporocarp extract'],'Экстракт тремеллы',{tags:['увлажнение'],fit:['normal','dry','sensitive'],risk:'Увлажняющий растительный/грибной компонент.'});
addNamed(['sodium polyglutamate'],'Полиглутамат натрия',{tags:['увлажнение'],fit:['normal','dry','sensitive'],risk:'Увлажняющий полимер.'});
addNamed(['ectoin'],'Эктоин',{tags:['увлажнение','барьер'],fit:['normal','dry','sensitive'],risk:'Осмопротектор, используемый для поддержки увлажнения и барьера.'});
addNamed(['beta glucan'],'Бета-глюкан',{tags:['увлажнение','успокоение'],fit:['normal','dry','sensitive'],risk:'Увлажняющий и успокаивающий компонент.'});
addNamed(['sodium hyaluronate crosspolymer'],'Сшитый гиалуронат натрия',{tags:['увлажнение','плёнкообразователь'],fit:['normal','dry','sensitive'],risk:'Форма гиалуроната с длительным увлажняющим и плёнкообразующим эффектом.'});
addNamed(['hydrolyzed sodium hyaluronate'],'Гидролизованный гиалуронат натрия',{tags:['увлажнение'],fit:['normal','dry','sensitive'],risk:'Низкомолекулярная форма гиалуроната; увлажняющий компонент.'});

addNamed(['ceramide ng','ceramide ns'],'Церамид NG/NS',{tags:['барьер','смягчение'],fit:['normal','dry','sensitive'],risk:'Липидный компонент поддержки кожного барьера.'});
addNamed(['ceramide as'],'Церамид AS',{tags:['барьер','смягчение'],fit:['normal','dry','sensitive'],risk:'Липидный компонент поддержки барьера.'});
addNamed(['ceramide eos'],'Церамид EOS',{tags:['барьер','смягчение'],fit:['normal','dry','sensitive'],risk:'Липидный компонент кожного барьера.'});
addNamed(['ceramide npa'],'Церамид NPA',{tags:['барьер','смягчение'],fit:['normal','dry','sensitive'],risk:'Липидный компонент барьерных формул.'});
addNamed(['linoleic acid'],'Линолевая кислота',{tags:['смягчение','барьер'],fit:['normal','dry','combination'],risk:'Жирная кислота, используемая для смягчения и поддержки липидного барьера.'});
addNamed(['oleic acid'],'Олеиновая кислота',{tags:['смягчение'],fit:['dry','normal'],risk:'Жирная кислота; смягчающий компонент.'});
addNamed(['palmitic acid'],'Пальмитиновая кислота',{tags:['смягчение'],fit:['dry','normal'],risk:'Жирная кислота и структурообразующий компонент.'});
addNamed(['stearic acid'],'Стеариновая кислота',{tags:['смягчение','структурообразователь'],fit:['dry','normal'],risk:'Жирная кислота; используется для текстуры и смягчения.'});
addNamed(['glyceryl oleate'],'Глицерилолеат',{tags:['эмульгатор','смягчение'],risk:'Эмульгирующий и смягчающий компонент.'});
addNamed(['glyceryl palmitate'],'Глицерилпальмитат',{tags:['эмульгатор','смягчение'],risk:'Эмульгирующий и смягчающий компонент.'});
addNamed(['polyglyceryl-3 diisostearate'],'Полиглицерил-3 диизостеарат',{tags:['эмульгатор','смягчение'],risk:'Эмульгатор для масляной фазы.'});
addNamed(['polyglyceryl-3 methylglucose distearate'],'Полиглицерил-3 метилглюкозы дистеарат',{tags:['эмульгатор','смягчение'],risk:'Эмульгатор и смягчающий компонент.'});
addNamed(['ceteareth-20'],'Цетеарет-20',{tags:['эмульгатор'],risk:'Неионный эмульгатор и стабилизатор эмульсии.'});
addNamed(['ceteth-20'],'Цетет-20',{tags:['эмульгатор'],risk:'Неионный эмульгатор.'});
addNamed(['steareth-20'],'Стеарет-20',{tags:['эмульгатор'],risk:'Неионный эмульгатор и стабилизатор.'});
addNamed(['glyceryl stearate citrate'],'Глицерилстеарат цитрат',{tags:['эмульгатор','смягчение'],risk:'Эмульгатор и смягчающий компонент.'});

addNamed(['phenoxyethanol'],'Феноксиэтанол',{status:'yellow',tags:['консервант'],risk:'Консервант; обычно используется в небольших концентрациях, чувствительная кожа может реагировать.'});
addNamed(['ethylhexylglycerin'],'Этилгексилглицерин',{tags:['консервант','увлажнение'],risk:'Многофункциональный компонент и усилитель системы консервации.'});
addNamed(['caprylyl glycol'],'Каприлилгликоль',{tags:['увлажнение','консервант'],risk:'Увлажняющий компонент и помощник системы консервации.'});
addNamed(['sodium benzoate'],'Бензоат натрия',{status:'yellow',tags:['консервант'],risk:'Консервант; переносимость зависит от концентрации и pH формулы.'});
addNamed(['potassium sorbate'],'Сорбат калия',{status:'yellow',tags:['консервант'],risk:'Консервант; используется преимущественно в кислых формулах.'});
addNamed(['benzyl alcohol'],'Бензиловый спирт',{status:'yellow',tags:['консервант','аромат'],risk:'Консервант или ароматический компонент; у чувствительной кожи возможна реакция.'});
addNamed(['dehydroacetic acid'],'Дегидроуксусная кислота',{status:'yellow',tags:['консервант'],risk:'Консервант; переносимость зависит от концентрации и формулы.'});
addNamed(['sodium dehydroacetate'],'Дегидроацетат натрия',{status:'yellow',tags:['консервант'],risk:'Консервант.'});
addNamed(['chlorphenesin'],'Хлорфенезин',{status:'yellow',tags:['консервант'],risk:'Консервант; у чувствительной кожи возможна индивидуальная реакция.'});
addNamed(['sorbic acid'],'Сорбиновая кислота',{status:'yellow',tags:['консервант','кислота'],risk:'Консервант; переносимость зависит от концентрации и pH.'});
addNamed(['iodopropynyl butylcarbamate'],'Йодопропинилбутилкарбамат',{status:'yellow',tags:['консервант'],risk:'Высокоактивный консервант, используется в очень низких концентрациях.'});
addNamed(['benzisothiazolinone'],'Бензизотиазолинон',{status:'yellow',tags:['консервант'],risk:'Консервант с заметным потенциалом сенсибилизации; особенно важен для чувствительной кожи.'});
addNamed(['methylisothiazolinone'],'Метилизотиазолинон',{status:'yellow',tags:['консервант'],risk:'Консервант с высоким потенциалом сенсибилизации; требует особой осторожности.'});
addNamed(['methylchloroisothiazolinone'],'Метилхлороизотиазолинон',{status:'yellow',tags:['консервант'],risk:'Консервант с потенциальным риском сенсибилизации.'});
addNamed(['methylchloroisothiazolinone and methylisothiazolinone'],'MCI/MI',{status:'yellow',tags:['консервант'],risk:'Система консервантов; потенциально сенсибилизирующая для чувствительной кожи.'});
addNamed(['parabens','methylparaben'],'Метилпарабен',{status:'yellow',tags:['консервант'],risk:'Парабеновый консервант; оценивается как часть всей системы консервации.'});
addNamed(['ethylparaben'],'Этилпарабен',{status:'yellow',tags:['консервант'],risk:'Парабеновый консервант.'});
addNamed(['propylparaben'],'Пропилпарабен',{status:'yellow',tags:['консервант'],risk:'Парабеновый консервант; переносимость зависит от формулы.'});
addNamed(['butylparaben'],'Бутилпарабен',{status:'yellow',tags:['консервант'],risk:'Парабеновый консервант.'});

addNamed(['disodium edta'],'Динатрий EDTA',{tags:['хелатор','стабилизатор'],risk:'Хелатор; связывает ионы металлов и помогает стабильности формулы.'});
addNamed(['tetrasodium edta'],'Тетранатрий EDTA',{tags:['хелатор','стабилизатор'],risk:'Хелатор и стабилизатор формулы.'});
addNamed(['trisodium edta'],'Тринатрий EDTA',{tags:['хелатор','стабилизатор'],risk:'Хелатор.'});
addNamed(['sodium phytate'],'Фитат натрия',{tags:['хелатор','антиоксидант'],risk:'Хелатор растительного происхождения, помогает стабильности формулы.'});
addNamed(['citric acid'],'Лимонная кислота',{...ACID,name:'Лимонная кислота',tags:['кислота','кислотность'],risk:'Кислота и регулятор pH; при высокой концентрации может раздражать.'});
addNamed(['sodium citrate'],'Цитрат натрия',{tags:['кислотность','стабилизатор'],risk:'Регулятор pH и буферный компонент.'});
addNamed(['tromethamine'],'Трометамин',{tags:['кислотность'],risk:'Регулятор pH.'});
addNamed(['sodium hydroxide'],'Гидроксид натрия',{status:'yellow',tags:['кислотность'],risk:'Регулятор pH; концентрация в готовом продукте обычно невелика.'});
addNamed(['potassium hydroxide'],'Гидроксид калия',{status:'yellow',tags:['кислотность'],risk:'Регулятор pH.'});

addNamed(['peg-40 hydrogenated castor oil'],'PEG-40 гидрогенизированное касторовое масло',{tags:['солюбилизатор','эмульгатор'],risk:'Солюбилизатор и эмульгирующий компонент.'});
addNamed(['polysorbate 20'],'Полисорбат-20',{tags:['солюбилизатор','эмульгатор'],risk:'Солюбилизатор и эмульгатор.'});
addNamed(['polysorbate 60'],'Полисорбат-60',{tags:['эмульгатор'],risk:'Эмульгатор.'});
addNamed(['polysorbate 80'],'Полисорбат-80',{tags:['эмульгатор','солюбилизатор'],risk:'Эмульгатор и солюбилизатор.'});
addNamed(['sorbitan olivate'],'Сорбитан оливат',{tags:['эмульгатор','смягчение'],risk:'Эмульгатор и смягчающий компонент.'});
addNamed(['sorbitan stearate'],'Сорбитан стеарат',{tags:['эмульгатор'],risk:'Эмульгатор.'});
addNamed(['sorbitan oleate'],'Сорбитан олеат',{tags:['эмульгатор','смягчение'],risk:'Эмульгатор и смягчающий компонент.'});

addNamed(['lauryl glucoside'],'Лаурилглюкозид',{tags:['ПАВ','очищение'],risk:'Неионный мягкий ПАВ.'});
addNamed(['caprylyl/capryl glucoside'],'Каприлил/каприлглюкозид',{tags:['ПАВ','солюбилизатор'],risk:'Мягкий ПАВ и солюбилизатор.'});
addNamed(['sodium cocoyl isethionate'],'Кокоилизетионат натрия',{tags:['ПАВ','очищение'],risk:'Мягкий анионный ПАВ, часто используется в syndet-очищении.'});
addNamed(['sodium methyl cocoyl taurate'],'Метилкокоилтаурат натрия',{tags:['ПАВ','очищение'],risk:'Мягкий очищающий ПАВ.'});
addNamed(['disodium laureth sulfosuccinate'],'Динатрий лауретсульфосукцинат',{tags:['ПАВ','очищение'],risk:'Мягкий анионный ПАВ.'});
addNamed(['sodium lauroyl sarcosinate'],'Лауроилсаркозинат натрия',{tags:['ПАВ','очищение'],risk:'Очищающий ПАВ; обычно мягче сильных сульфатов.'});
addNamed(['sodium cocoyl glutamate'],'Кокоилглутамат натрия',{tags:['ПАВ','очищение'],risk:'Мягкий аминокислотный ПАВ.'});
addNamed(['disodium cocoyl glutamate'],'Динатрий кокоилглутамат',{tags:['ПАВ','очищение'],risk:'Мягкий аминокислотный ПАВ.'});
addNamed(['sodium lauroyl methyl isethionate'],'Лауроилметилизетионат натрия',{tags:['ПАВ','очищение'],risk:'Мягкий очищающий ПАВ.'});
addNamed(['sodium cocoyl glycinate'],'Кокоилглицинат натрия',{tags:['ПАВ','очищение'],risk:'Мягкий аминокислотный ПАВ.'});

addNamed(['dimethicone copolyol'],'Диметикон кополиол',{tags:['силикон','кондиционирование'],risk:'Силиконовый кондиционирующий компонент.'});
addNamed(['phenyl trimethicone'],'Фенилтриметикон',{tags:['силикон','защита'],risk:'Силиконовый компонент, придающий гладкость и блеск.'});
addNamed(['bis-aminopropyl dimethicone'],'Бис-аминопропилдиметикон',{tags:['силикон','кондиционирование','волосы'],fit:['dry','normal','damaged','colored'],risk:'Кондиционирующий силикон для повреждённых волос.'});
addNamed(['silicone quaternium-16'],'Силикон кватерниум-16',{tags:['силикон','кондиционирование','волосы'],fit:['dry','normal','damaged','colored'],risk:'Катионный силикон для кондиционирования волос.'});
addNamed(['silicone quaternium-22'],'Силикон кватерниум-22',{tags:['силикон','кондиционирование','волосы'],fit:['dry','normal','damaged','colored'],risk:'Кондиционирующий силикон.'});
addNamed(['hydrolyzed wheat protein'],'Гидролизованный пшеничный протеин',{tags:['кондиционирование','волосы'],fit:['dry','normal','damaged','colored'],risk:'Гидролизованный белок для кондиционирования и визуального улучшения волос.'});
addNamed(['hydrolyzed keratin'],'Гидролизованный кератин',{tags:['кондиционирование','волосы'],fit:['dry','normal','damaged','colored'],risk:'Белковый компонент для кондиционирования волос.'});
addNamed(['hydrolyzed silk'],'Гидролизованный шёлк',{tags:['кондиционирование','волосы'],fit:['dry','normal','damaged','colored'],risk:'Белковый кондиционирующий компонент.'});
addNamed(['hydrolyzed collagen'],'Гидролизованный коллаген',{tags:['увлажнение','кондиционирование'],fit:['dry','normal','damaged','colored'],risk:'Плёнкообразующий и кондиционирующий белковый компонент.'});
addNamed(['hydrolyzed oat protein'],'Гидролизованный овсяный протеин',{tags:['кондиционирование','успокоение'],fit:['dry','normal','sensitive'],risk:'Белковый компонент с кондиционирующими свойствами.'});

addNamed(['bakuchiol'],'Бакучиол',{tags:['актив','уход'],fit:['normal','dry','combination'],risk:'Растительный косметический актив; переносимость индивидуальна.'});
addNamed(['peptide','peptides'],'Пептиды',{tags:['актив','уход'],risk:'Общее обозначение пептидного комплекса; свойства зависят от конкретного пептида.'});
addNamed(['acetyl hexapeptide-8'],'Ацетилгексапептид-8',{tags:['пептид','уход'],risk:'Косметический пептидный актив.'});
addNamed(['palmitoyl tripeptide-5'],'Пальмитоилтрипептид-5',{tags:['пептид','уход'],risk:'Косметический пептидный актив.'});
addNamed(['palmitoyl tripeptide-38'],'Пальмитоилтрипептид-38',{tags:['пептид','уход'],risk:'Косметический пептидный актив.'});
addNamed(['sh-oligopeptide-1'],'sh-олигопептид-1',{tags:['пептид','уход'],risk:'Пептидный косметический компонент.'});
addNamed(['adenosine'],'Аденозин',{tags:['уход','актив'],fit:['normal','dry','sensitive'],risk:'Косметический актив, часто используется в антивозрастных формулах.'});
addNamed(['carnosine'],'Карнозин',{tags:['антиоксидант','уход'],risk:'Антиоксидантный косметический компонент.'});
addNamed(['glutathione'],'Глутатион',{tags:['антиоксидант','уход'],risk:'Антиоксидантный компонент.'});
addNamed(['resveratrol'],'Ресвератрол',{tags:['антиоксидант','уход'],risk:'Антиоксидантный актив.'});
addNamed(['coenzyme q10','ubiquinone'],'Коэнзим Q10',{tags:['антиоксидант','уход'],risk:'Антиоксидантный косметический актив.'});

addNamed(['tranexamic acid'],'Транексамовая кислота',{tags:['осветление','актив'],risk:'Актив для формул, направленных на выравнивание тона; переносимость индивидуальна.'});
addNamed(['thiamidol'],'Тиамидол',{tags:['осветление','актив'],risk:'Осветляющий косметический актив.'});
addNamed(['4-butylresorcinol'],'4-бутилрезорцин',{tags:['осветление','актив'],risk:'Осветляющий актив; переносимость зависит от концентрации.'});
addNamed(['n-acetyl glucosamine'],'N-ацетилглюкозамин',{tags:['увлажнение','осветление','актив'],risk:'Функциональный актив с увлажняющими и осветляющими свойствами.'});
addNamed(['dipotassium glycyrrhizate'],'Дикалия глицирризат',{tags:['успокоение'],fit:['normal','dry','sensitive'],risk:'Производное солодки с успокаивающими свойствами.'});

addNamed(['centella asiatica leaf water'],'Вода центеллы азиатской',{tags:['успокоение','увлажнение'],fit:['normal','dry','sensitive'],risk:'Успокаивающий растительный компонент.'});
addNamed(['madecassoside'],'Мадекассосид',{tags:['успокоение','актив'],fit:['normal','dry','sensitive'],risk:'Компонент центеллы, используемый в успокаивающих формулах.'});
addNamed(['asiaticoside'],'Азиатикозид',{tags:['успокоение'],fit:['normal','dry','sensitive'],risk:'Компонент центеллы с успокаивающим назначением.'});
addNamed(['portulaca oleracea extract'],'Экстракт портулака',{tags:['успокоение','растительный экстракт'],fit:['normal','dry','sensitive'],risk:'Растительный успокаивающий компонент.'});
addNamed(['houttuynia cordata extract'],'Экстракт хауттюйнии',{tags:['успокоение','растительный экстракт'],fit:['normal','oily','combination','sensitive'],risk:'Растительный компонент, используемый в успокаивающих формулах.'});
addNamed(['mugwort extract','artemisia annua extract'],'Экстракт полыни',{tags:['успокоение','растительный экстракт'],fit:['normal','oily','combination','sensitive'],risk:'Растительный экстракт; переносимость индивидуальна.'});
addNamed(['rice extract','oryza sativa extract'],'Экстракт риса',{tags:['увлажнение','растительный экстракт'],fit:['normal','dry','sensitive'],risk:'Растительный кондиционирующий компонент.'});
addNamed(['soybean extract','glycine soja seed extract'],'Экстракт сои',{tags:['антиоксидант','растительный экстракт'],risk:'Растительный компонент; возможна индивидуальная чувствительность.'});
addNamed(['grape seed extract','vitis vinifera seed extract'],'Экстракт виноградных косточек',{tags:['антиоксидант','растительный экстракт'],risk:'Растительный антиоксидантный компонент.'});
addNamed(['chamomilla recutita flower water'],'Гидролат ромашки',{tags:['успокоение','растительный экстракт'],fit:['normal','dry','sensitive'],risk:'Растительный ароматический/успокаивающий компонент.'});
addNamed(['rosa damascena flower water'],'Гидролат розы',{tags:['растительный экстракт','аромат'],risk:'Ароматический растительный компонент; чувствительная кожа может реагировать.'});

addNamed(['tea tree oil','melaleuca alternifolia leaf oil'],'Масло чайного дерева',{status:'yellow',tags:['эфирное масло','аромат'],fit:['oily','combination'],risk:'Эфирное масло; может раздражать чувствительную кожу.'});
addNamed(['lavender oil','lavandula angustifolia oil'],'Масло лаванды',{status:'yellow',tags:['эфирное масло','аромат'],risk:'Эфирное масло и ароматический компонент; возможна чувствительность.'});
addNamed(['eucalyptus globulus leaf oil'],'Масло эвкалипта',{status:'yellow',tags:['эфирное масло','аромат'],risk:'Эфирное масло; может раздражать чувствительную кожу.'});
addNamed(['citrus limon peel oil'],'Масло лимонной кожуры',{status:'yellow',tags:['эфирное масло','аромат'],risk:'Цитрусовое эфирное масло; потенциально раздражающий ароматический компонент.'});

addNamed(['titanium dioxide'],'Диоксид титана',{status:'green',fit:['normal','dry','oily','combination','sensitive'],tags:['пигмент','uv-фильтр'],risk:'Минеральный пигмент и UV-фильтр в соответствующих формулах.'});
addNamed(['iron oxides'],'Оксиды железа',{tags:['пигмент'],risk:'Минеральные пигменты.'});
addNamed(['silica'],'Диоксид кремния',{tags:['текстура','абсорбент'],risk:'Минеральный текстурирующий и абсорбирующий компонент.'});
addNamed(['kaolin'],'Каолин',{tags:['абсорбент','текстура'],fit:['oily','combination'],risk:'Абсорбирующая глина; может усиливать ощущение сухости.'});
addNamed(['bentonite'],'Бентонит',{tags:['абсорбент','текстура'],fit:['oily','combination'],risk:'Абсорбирующая глина; эффект зависит от формулы.'});
addNamed(['magnesium aluminum silicate'],'Магний-алюминий силикат',{tags:['загуститель','стабилизатор'],risk:'Минеральный загуститель и стабилизатор.'});


// Расширение INCI-базы: дополнительные компоненты и русские варианты.
const EXTRA_INCI_RU = {
  'масло кокосовое':'coconut oil',
  'масло кокоса':'coconut oil',
  'масло виноградных косточек':'grape seed oil',
  'масло виноградной косточки':'grape seed oil',
  'цетилфосфат калия':'potassium cetyl phosphate',
  'изопентилдиол':'isopentyldiol',
  'сополимер акрилатов натрия':'sodium acrylates copolymer',
  'лецитин':'lecithin',
  'феноксиэтанол':'phenoxyethanol',
  'этилгексилглицерин':'ethylhexylglycerin',
  'цетеарет 20':'ceteareth-20',
  'цетеарет-20':'ceteareth-20',
  'бутилированный гидрокситолуол':'bht',
  'бутилгидрокситолуол':'bht',
  'натриевая соль пирролидонкарбоновой кислоты':'sodium pca',
  'натрий pca':'sodium pca',
  'глицин':'glycine',
  'аланин':'alanine',
  'пролин':'proline',
  'серин':'serine',
  'треонин':'threonine',
  'аргинин':'arginine',
  'лизин':'lysine',
  'глутаминовая кислота':'glutamic acid',
  'масло какао':'cocoa butter',
  'дисодиум эдта':'disodium edta',
  'динатриевая соль эдта':'disodium edta',
  'карбомер':'carbomer',
  'ксантановая камедь':'xanthan gum',
  'лимонная кислота':'citric acid',
  'бензоат натрия':'sodium benzoate',
  'сорбат калия':'potassium sorbate',
  'дегидроацетат натрия':'sodium dehydroacetate',
  'каприлилгликоль':'caprylyl glycol',
  'гидроксиацетофенон':'hydroxyacetophenone',
  'децилглюкозид':'decyl glucoside',
  'кокоглюкозид':'coco glucoside',
  'кокамидопропилбетаин':'cocamidopropyl betaine',
  'кокоилглутамат натрия':'sodium cocoyl glutamate',
  'кокоилизетионат натрия':'sodium cocoyl isethionate',
  'лауроилглутамат натрия':'sodium lauroyl glutamate',
  'лактат натрия':'sodium lactate',
  'гидроксиэтилмочевина':'hydroxyethyl urea',
  'ксилитол':'xylitol',
  'маннитол':'mannitol',
  'фруктоза':'fructose',
  'глюкоза':'glucose',
  'инулин':'inulin',
  'кофеин':'caffeine',
  'таурин':'taurine',
  'креатин':'creatine',
  'биотин':'biotin',
  'гидролизованный кератин':'hydrolyzed keratin',
  'гидролизованный шёлк':'hydrolyzed silk',
  'гидролизованный пшеничный белок':'hydrolyzed wheat protein',
  'гидролизованный рисовый белок':'hydrolyzed rice protein',
  'гидролизованный соевый белок':'hydrolyzed soy protein',
  'гидролизованный коллаген':'hydrolyzed collagen',
  'гидролизованный эластин':'hydrolyzed elastin',
  'лейцин':'leucine',
  'изолейцин':'isoleucine',
  'валин':'valine',
  'фенилаланин':'phenylalanine',
  'тирозин':'tyrosine',
  'глутамин':'glutamine',
  'аспарагиновая кислота':'aspartic acid',
  'аминокислоты':'amino acids',
  'цетримониум хлорид':'cetrimonium chloride',
  'бехентримониум хлорид':'behentrimonium chloride',
  'поликватерниум-16':'polyquaternium-16',
  'поликватерниум-37':'polyquaternium-37',
  'поликватерниум-44':'polyquaternium-44',
  'поликватерниум-68':'polyquaternium-68',
  'поликватерниум-81':'polyquaternium-81',
  'гидроксиэтилцеллюлоза':'hydroxyethylcellulose',
  'целлюлозная камедь':'cellulose gum',
  'пуллулан':'pullulan',
  'полисорбат-20':'polysorbate 20',
  'полисорбат-60':'polysorbate 60',
  'полисорбат-80':'polysorbate 80',
  'пэг-40 гидрогенизированное касторовое масло':'peg-40 hydrogenated castor oil',
  'стеарет-20':'steareth-20',
  'цетет-20':'ceteth-20',
  'цетеарилглюкозид':'cetearyl glucoside',
  'глицерилстеарат':'glyceryl stearate',
  'глицерилолеат':'glyceryl oleate',
  'каприловый каприновый триглицерид':'caprylic/capric triglyceride',
  'дикаприлиловый эфир':'dicaprylyl ether',
  'изоамиллаурат':'isoamyl laurate',
  'изододекан':'isododecane',
  'изогексадекан':'isohexadecane',
  'гидрогенизированный полидецен':'hydrogenated polydecene',
  'минеральное масло':'mineral oil',
  'пчелиный воск':'beeswax',
  'каолин':'kaolin',
  'диоксид кремния':'silica',
  'оксид алюминия':'alumina',
  'слюда':'mica',
  'токоферол':'tocopherol',
  'токоферилацетат':'tocopheryl acetate',
  'фитиновая кислота':'phytic acid',
  'гидроксид натрия':'sodium hydroxide',
  'трометамин':'tromethamine',
  'гидроксид калия':'potassium hydroxide',
  'цитрат натрия':'sodium citrate',
  'хлорид натрия':'sodium chloride'
,
  'дипропиленгликоль':'dipropylene glycol',
  'метилпропандиол':'methylpropanediol',
  'этоксидигликоль':'ethoxydiglycol',
  'диглицерин':'diglycerin',
  'мальтитол':'maltitol',
  'гидроксипропилтримониум гиалуронат':'hydroxypropyltrimonium hyaluronate',
  'ацетилированная гиалуроновая кислота':'acetylated hyaluronic acid',
  'ацетилированный гиалуронат натрия':'sodium acetylated hyaluronate',
  'сахароза':'sucrose',
  'гидроксиэктоин':'hydroxyectoine',
  'фосфатидилсерин':'phosphatidylserine',
  'альфа-линоленовая кислота':'alpha-linolenic acid',
  'миристиновая кислота':'myristic acid',
  'бегеновая кислота':'behenic acid',
  'арахиновая кислота':'arachidic acid',
  'масло чайной камелии':'camellia oleifera seed oil',
  'масло крамбе':'crambe abyssinica seed oil',
  'масло баобаба':'adansonia digitata seed oil',
  'конопляное масло':'hemp seed oil',
  'масло семян конопли':'cannabis sativa seed oil',
  'тыквенное масло':'pumpkin seed oil',
  'масло чёрного тмина':'black cumin seed oil',
  'масло чёрного тмина':'nigella sativa seed oil',
  'масло таману':'tamanu oil',
  'масло таману':'calophyllum inophyllum seed oil',
  'масло марулы':'marula seed oil',
  'масло абрикосовой косточки':'prunus armeniaca kernel oil',
  'масло мурумуру':'murumuru seed butter',
  'масло кокум':'kokum butter',
  'масло купуасу':'cupuaçu butter',
  'этилгексил изононаноат':'ethylhexyl isononanoate',
  'изононил изононаноат':'isononyl isononanoate',
  'дигептаноат неопентилгликоля':'neopentyl glycol diheptanoate',
  'триэтилгексаноин':'triethylhexanoin',
  'диизостеарилмалат':'diisostearyl malate',
  'цетримониум бромид':'cetrimonium bromide',
  'дицетилдимониум хлорид':'dicetyldimonium chloride',
  'дистеарилдиимониум хлорид':'distearyldimonium chloride',
  'кватерниум-80':'quaternium-80',
  'поликватерниум-11':'polyquaternium-11',
  'поликватерниум-22':'polyquaternium-22',
  'поликватерниум-24':'polyquaternium-24',
  'поликватерниум-28':'polyquaternium-28',
  'поликватерниум-32':'polyquaternium-32',
  'поликватерниум-39':'polyquaternium-39',
  'поликватерниум-46':'polyquaternium-46',
  'поликватерниум-47':'polyquaternium-47',
  'поликватерниум-55':'polyquaternium-55',
  'поликватерниум-67':'polyquaternium-67',
  'поликватерниум-72':'polyquaternium-72',
  'поликватерниум-73':'polyquaternium-73',
  'поликватерниум-74':'polyquaternium-74',
  'гидролизованный гороховый белок':'hydrolyzed pea protein',
  'гидролизованный кукурузный белок':'hydrolyzed corn protein',
  'гидролизованный киноа-белок':'hydrolyzed quinoa',
  'гидролизованный картофельный белок':'hydrolyzed potato protein',
  'гидролизованный люпиновый белок':'hydrolyzed lupine protein',
  'гидролизованный миндальный белок':'hydrolyzed almond protein',
  'гидролизованный гороховый пептид':'hydrolyzed pea peptide',
  'аминокислоты коллагена':'collagen amino acids',
  'аминокислоты кератина':'keratin amino acids',
  'гидрохлорид цистеина':'cysteine hcl',
  'гидрохлорид аргинина':'arginine hcl',
  'пиридоксина гидрохлорид':'pyridoxine hcl',
  'глюконат цинка':'zinc gluconate',
  'лактат цинка':'zinc lactate',
  'медь pca':'copper pca',
  'магний pca':'magnesium pca',
  'азиатиковая кислота':'asiatic acid',
  'мадекассовая кислота':'madecassic acid',
  'гидролат гамамелиса':'hamamelis virginiana water',
  'экстракт клюквы':'vaccinium macrocarpon fruit extract',
  'экстракт черники':'vaccinium myrtillus fruit extract',
  'экстракт винограда':'vitis vinifera fruit extract',
  'экстракт коры шелковицы':'morus alba bark extract',
  'экстракт женьшеня':'panax ginseng root extract',
  'экстракт шлемника байкальского':'scutellaria baicalensis root extract',
  'экстракт горца японского':'polygonum cuspidatum root extract',
  'экстракт прополиса':'propolis extract',
  'экстракт маточного молочка':'royal jelly extract',
  'экстракт мёда':'honey extract',
  'лизат бифидобактерий':'bifida ferment lysate',
  'фермент лактобактерий':'lactobacillus ferment',
  'фильтрат фермента дрожжей':'saccharomyces ferment filtrate',
  'фильтрат фермента галактомицетов':'galactomyces ferment filtrate',
  'фермент aspergillus':'aspergillus ferment',
  'экстракт фермента alteromonas':'alteromonas ferment extract',
  'бета-ситостерол':'beta-sitosterol',
  'астаксантин':'astaxanthin',
  'альфа-липоевая кислота':'alpha-lipoic acid',
  'эрготионеин':'ergothioneine',
  'эллаговая кислота':'ellagic acid',
  'галловая кислота':'gallic acid',
  'метилсиланол маннуронат':'methylsilanol mannuronate',
  'перлит':'perlite',
  'порошок угля':'charcoal powder',
  'бамбуковый уголь':'bamboo charcoal',
  'рисовый крахмал':'rice starch',
  'крахмал тапиоки':'tapioca starch',
  'кукурузный крахмал':'corn starch',
  'сера':'sulfur',
  'сульфид селена':'selenium sulfide',
  'бензоилпероксид':'benzoyl peroxide',
  'койевой дипальмитат':'kojic dipalmitate',
  'глицирретиновая кислота':'glycyrrhetinic acid',
  'диоевая кислота':'dioic acid',
  'октенидин hcl':'octenidine hcl',
  'ацетил тетрапептид-5':'acetyl tetrapeptide-5',
  'ацетил тетрапептид-2':'acetyl tetrapeptide-2',
  'пальмитоил гексапептид-12':'palmitoyl hexapeptide-12',
  'олигопептид-2':'oligopeptide-2',
  'диметилизосорбид':'dimethyl isosorbide',
  'пчелиный воск':'cera alba',
  'карнаубский воск':'carnauba wax',
  'канделильский воск':'candelilla cera',
  'озокерит':'ozokerite',
  'ланолин':'lanolin',
  'ланолиновый спирт':'lanolin alcohol',
  'холестерилгидроксистеарат':'cholesteryl hydroxystearate',
  'миристиловый спирт':'myristyl alcohol',
  'лауриловый спирт':'lauryl alcohol',
  'цетеарет-6':'ceteareth-6',
  'лаурет-7':'laureth-7',
  'лаурет-23':'laureth-23',
  'стеарет-21':'steareth-21',
  'цетеарилсульфат натрия':'sodium cetearyl sulfate',
  'стеароиллактилат натрия':'sodium stearoyl lactylate',
  'сахарозы стеарат':'sucrose stearate',
  'сахарозы пальмитат':'sucrose palmitate',
  'гидроксипропилметилцеллюлоза':'hydroxypropyl methylcellulose',
  'камедь сенегальской акации':'acacia senegal gum',
  'каррагинан':'carrageenan',
  'глюкоманнан конжака':'konjac glucomannan',
  'анизат натрия':'sodium anisate',
  'анизат калия':'potassium anisate',
  'левулиновая кислота':'levulinic acid',
  'левулинат натрия':'sodium levulinate',
  'глицерил каприлат':'glyceryl caprylate',
  'тетранатрий глутаматдиацетат':'tetrasodium glutamate diacetate',
  'тринатрий этилендиаминдисукцинат':'trisodium ethylenediamine disuccinate',
  'ретинилпропионат':'retinyl propionate',
  'гидроксипинаколона ретиноат':'hydroxypinacolone retinoate',
  'тетрагексилдецил аскорбат':'tetrahexyldecyl ascorbate',
  'аскорбилглюкозид':'ascorbyl glucoside',
  'токофериллинолеат':'tocopheryl linoleate',
  'гидролизованный бета-глюкан':'hydrolyzed beta-glucan',
  'экстракт пории':'poria cocos extract',
  'экстракт ламинарии':'laminaria japonica extract',
  'экстракт ундарии':'undaria pinnatifida extract',
  'экстракт фукуса':'fucus vesiculosus extract',
  'экстракт спирулины':'spirulina platensis extract',
  'экстракт хлореллы':'chlorella vulgaris extract',
  'экстракт красной водоросли':'porphyridium cruentum extract',
  'экстракт сахарного тростника':'saccharum officinarum extract',
  'экстракт апельсина':'citrus aurantium dulcis fruit extract',
  'экстракт брусники':'vaccinium vitis-idaea fruit extract',
  'экстракт клубники':'fragaria vesca fruit extract',
  'экстракт малины':'rubus idaeus fruit extract',
  'экстракт белой шелковицы':'morus alba fruit extract',
  'экстракт яблока':'pyrus malus fruit extract',
  'экстракт огурца':'cucumis sativus fruit extract',
  'экстракт томата':'solanum lycopersicum fruit extract',
  'экстракт брокколи':'brassica oleracea italica extract',
  'вода зелёного чая':'camellia sinensis leaf water',
  'лавандовая вода':'lavandula angustifolia flower water',
  'флёрдоранж':'citrus aurantium amara flower water',
  'вода гамамелиса':'hamamelis virginiana leaf water',
  'порошок сока алоэ':'aloe barbadensis leaf juice powder',
  'экстракт алоэ ферокс':'aloe ferox leaf extract',
  'экстракт листьев оливы':'olea europaea leaf extract',
  'экстракт коры сосны':'pinus pinaster bark extract',
  'пикногенол':'pycnogenol',
  'экстракт конского каштана':'horse chestnut extract',
  'эсцин':'escin',
  'диосмин':'diosmin',
  'рутин':'rutin',
  'гесперидин':'hesperidin',
  'кверцетин':'quercetin',
  'лютеин':'lutein',
  'бета-каротин':'beta-carotene',
  'хлорофилл':'chlorophyll',
  'мелатонин':'melatonin',
  'карнитин':'carnitine',
  'ацетилкарнитин hcl':'acetyl carnitine hcl',
  'n-ацетилцистеин':'n-acetyl cysteine',
  'ацетилцистеин':'acetyl cysteine',
  'метабисульфит натрия':'sodium metabisulfite',
  'сульфит натрия':'sodium sulfite',
  'бисульфит натрия':'sodium bisulfite',
  'гидрохинон':'hydroquinone',
  'фенилэтилрезорцинол':'phenylethyl resorcinol',
  'ундециленоиламинофенилаланин':'undecylenoyl phenylalanine',
  'олигопептид-68':'oligopeptide-68',
  'дипептид-2':'dipeptide-2',
  'дипептид-4':'dipeptide-4',
  'дипептид-7':'dipeptide-7',
  'дипептид-8':'dipeptide-8',
  'тетрапептид-21':'tetrapeptide-21',
  'тетрапептид-26':'tetrapeptide-26',
  'тетрапептид-30':'tetrapeptide-30',
};

// Дополнительные 200 популярных INCI-компонентов для кожи и волос.
addNamed(['dipropylene glycol','дипропиленгликоль'],'Дипропиленгликоль');
addNamed(['methylpropanediol','метилпропандиол'],'Метилпропандиол');
addNamed(['ethoxydiglycol','этоксидигликоль'],'Этоксидигликоль');
addNamed(['diglycerin','диглицерин'],'Диглицерин');
addNamed(['maltitol','мальтитол'],'Мальтитол');
addNamed(['hydroxypropyltrimonium hyaluronate','гидроксипропилтримониум гиалуронат'],'Гидроксипропилтримониум гиалуронат');
addNamed(['acetylated hyaluronic acid','ацетилированная гиалуроновая кислота'],'Ацетилированная гиалуроновая кислота');
addNamed(['sodium acetylated hyaluronate','ацетилированный гиалуронат натрия'],'Ацетилированный гиалуронат натрия');
addNamed(['sucrose','сахароза'],'Сахароза');
addNamed(['hydroxyectoine','гидроксиэктоин'],'Гидроксиэктоин');
addNamed(['phosphatidylserine','фосфатидилсерин'],'Фосфатидилсерин');
addNamed(['alpha-linolenic acid','альфа-линоленовая кислота'],'Альфа-линоленовая кислота');
addNamed(['myristic acid','миристиновая кислота'],'Миристиновая кислота');
addNamed(['behenic acid','бегеновая кислота'],'Бегеновая кислота');
addNamed(['arachidic acid','арахиновая кислота'],'Арахиновая кислота');
addNamed(['camellia oleifera seed oil','масло чайной камелии'],'Масло чайной камелии');
addNamed(['crambe abyssinica seed oil','масло крамбе'],'Масло крамбе');
addNamed(['adansonia digitata seed oil','масло баобаба'],'Масло баобаба');
addNamed(['hemp seed oil','конопляное масло'],'Конопляное масло');
addNamed(['cannabis sativa seed oil','масло семян конопли'],'Масло семян конопли');
addNamed(['pumpkin seed oil','тыквенное масло'],'Тыквенное масло');
addNamed(['black cumin seed oil','масло чёрного тмина'],'Масло чёрного тмина');
addNamed(['nigella sativa seed oil','масло чёрного тмина'],'Масло чёрного тмина');
addNamed(['tamanu oil','масло таману'],'Масло таману');
addNamed(['calophyllum inophyllum seed oil','масло таману'],'Масло таману');
addNamed(['marula seed oil','масло марулы'],'Масло марулы');
addNamed(['prunus armeniaca kernel oil','масло абрикосовой косточки'],'Масло абрикосовой косточки');
addNamed(['murumuru seed butter','масло мурумуру'],'Масло мурумуру');
addNamed(['kokum butter','масло кокум'],'Масло кокум');
addNamed(['cupuaçu butter','масло купуасу'],'Масло купуасу');
addNamed(['ethylhexyl isononanoate','этилгексил изононаноат'],'Этилгексил изононаноат');
addNamed(['isononyl isononanoate','изононил изононаноат'],'Изононил изононаноат');
addNamed(['neopentyl glycol diheptanoate','дигептаноат неопентилгликоля'],'Дигептаноат неопентилгликоля');
addNamed(['triethylhexanoin','триэтилгексаноин'],'Триэтилгексаноин');
addNamed(['diisostearyl malate','диизостеарилмалат'],'Диизостеарилмалат');
addNamed(['cetrimonium bromide','цетримониум бромид'],'Цетримониум бромид');
addNamed(['dicetyldimonium chloride','дицетилдимониум хлорид'],'Дицетилдимониум хлорид');
addNamed(['distearyldimonium chloride','дистеарилдиимониум хлорид'],'Дистеарилдиимониум хлорид');
addNamed(['quaternium-80','кватерниум-80'],'Кватерниум-80');
addNamed(['polyquaternium-11','поликватерниум-11'],'Поликватерниум-11');
addNamed(['polyquaternium-22','поликватерниум-22'],'Поликватерниум-22');
addNamed(['polyquaternium-24','поликватерниум-24'],'Поликватерниум-24');
addNamed(['polyquaternium-28','поликватерниум-28'],'Поликватерниум-28');
addNamed(['polyquaternium-32','поликватерниум-32'],'Поликватерниум-32');
addNamed(['polyquaternium-39','поликватерниум-39'],'Поликватерниум-39');
addNamed(['polyquaternium-46','поликватерниум-46'],'Поликватерниум-46');
addNamed(['polyquaternium-47','поликватерниум-47'],'Поликватерниум-47');
addNamed(['polyquaternium-55','поликватерниум-55'],'Поликватерниум-55');
addNamed(['polyquaternium-67','поликватерниум-67'],'Поликватерниум-67');
addNamed(['polyquaternium-72','поликватерниум-72'],'Поликватерниум-72');
addNamed(['polyquaternium-73','поликватерниум-73'],'Поликватерниум-73');
addNamed(['polyquaternium-74','поликватерниум-74'],'Поликватерниум-74');
addNamed(['hydrolyzed pea protein','гидролизованный гороховый белок'],'Гидролизованный гороховый белок');
addNamed(['hydrolyzed corn protein','гидролизованный кукурузный белок'],'Гидролизованный кукурузный белок');
addNamed(['hydrolyzed quinoa','гидролизованный киноа-белок'],'Гидролизованный киноа-белок');
addNamed(['hydrolyzed potato protein','гидролизованный картофельный белок'],'Гидролизованный картофельный белок');
addNamed(['hydrolyzed lupine protein','гидролизованный люпиновый белок'],'Гидролизованный люпиновый белок');
addNamed(['hydrolyzed almond protein','гидролизованный миндальный белок'],'Гидролизованный миндальный белок');
addNamed(['hydrolyzed pea peptide','гидролизованный гороховый пептид'],'Гидролизованный гороховый пептид');
addNamed(['collagen amino acids','аминокислоты коллагена'],'Аминокислоты коллагена');
addNamed(['keratin amino acids','аминокислоты кератина'],'Аминокислоты кератина');
addNamed(['cysteine hcl','гидрохлорид цистеина'],'Гидрохлорид цистеина');
addNamed(['arginine hcl','гидрохлорид аргинина'],'Гидрохлорид аргинина');
addNamed(['pyridoxine hcl','пиридоксина гидрохлорид'],'Пиридоксина гидрохлорид');
addNamed(['zinc gluconate','глюконат цинка'],'Глюконат цинка');
addNamed(['zinc lactate','лактат цинка'],'Лактат цинка');
addNamed(['copper pca','медь pca'],'Медь PCA');
addNamed(['magnesium pca','магний pca'],'Магний PCA');
addNamed(['asiatic acid','азиатиковая кислота'],'Азиатиковая кислота');
addNamed(['madecassic acid','мадекассовая кислота'],'Мадекассовая кислота');
addNamed(['hamamelis virginiana water','гидролат гамамелиса'],'Гидролат гамамелиса');
addNamed(['vaccinium macrocarpon fruit extract','экстракт клюквы'],'Экстракт клюквы');
addNamed(['vaccinium myrtillus fruit extract','экстракт черники'],'Экстракт черники');
addNamed(['vitis vinifera fruit extract','экстракт винограда'],'Экстракт винограда');
addNamed(['morus alba bark extract','экстракт коры шелковицы'],'Экстракт коры шелковицы');
addNamed(['panax ginseng root extract','экстракт женьшеня'],'Экстракт женьшеня');
addNamed(['scutellaria baicalensis root extract','экстракт шлемника байкальского'],'Экстракт шлемника байкальского');
addNamed(['polygonum cuspidatum root extract','экстракт горца японского'],'Экстракт горца японского');
addNamed(['propolis extract','экстракт прополиса'],'Экстракт прополиса');
addNamed(['royal jelly extract','экстракт маточного молочка'],'Экстракт маточного молочка');
addNamed(['honey extract','экстракт мёда'],'Экстракт мёда');
addNamed(['bifida ferment lysate','лизат бифидобактерий'],'Лизат бифидобактерий');
addNamed(['lactobacillus ferment','фермент лактобактерий'],'Фермент лактобактерий');
addNamed(['saccharomyces ferment filtrate','фильтрат фермента дрожжей'],'Фильтрат фермента дрожжей');
addNamed(['galactomyces ferment filtrate','фильтрат фермента галактомицетов'],'Фильтрат фермента галактомицетов');
addNamed(['aspergillus ferment','фермент aspergillus'],'Фермент Aspergillus');
addNamed(['alteromonas ferment extract','экстракт фермента alteromonas'],'Экстракт фермента Alteromonas');
addNamed(['beta-sitosterol','бета-ситостерол'],'Бета-ситостерол');
addNamed(['astaxanthin','астаксантин'],'Астаксантин');
addNamed(['alpha-lipoic acid','альфа-липоевая кислота'],'Альфа-липоевая кислота');
addNamed(['ergothioneine','эрготионеин'],'Эрготионеин');
addNamed(['ellagic acid','эллаговая кислота'],'Эллаговая кислота');
addNamed(['gallic acid','галловая кислота'],'Галловая кислота');
addNamed(['methylsilanol mannuronate','метилсиланол маннуронат'],'Метилсиланол маннуронат');
addNamed(['perlite','перлит'],'Перлит');
addNamed(['charcoal powder','порошок угля'],'Порошок угля');
addNamed(['bamboo charcoal','бамбуковый уголь'],'Бамбуковый уголь');
addNamed(['rice starch','рисовый крахмал'],'Рисовый крахмал');
addNamed(['tapioca starch','крахмал тапиоки'],'Крахмал тапиоки');
addNamed(['corn starch','кукурузный крахмал'],'Кукурузный крахмал');
addNamed(['sulfur','сера'],'Сера');
addNamed(['selenium sulfide','сульфид селена'],'Сульфид селена');
addNamed(['benzoyl peroxide','бензоилпероксид'],'Бензоилпероксид');
addNamed(['kojic dipalmitate','койевой дипальмитат'],'Койевой дипальмитат');
addNamed(['glycyrrhetinic acid','глицирретиновая кислота'],'Глицирретиновая кислота');
addNamed(['dioic acid','диоевая кислота'],'Диоевая кислота');
addNamed(['octenidine hcl','октенидин hcl'],'Октенидин HCl');
addNamed(['acetyl tetrapeptide-5','ацетил тетрапептид-5'],'Ацетил тетрапептид-5');
addNamed(['acetyl tetrapeptide-2','ацетил тетрапептид-2'],'Ацетил тетрапептид-2');
addNamed(['palmitoyl hexapeptide-12','пальмитоил гексапептид-12'],'Пальмитоил гексапептид-12');
addNamed(['oligopeptide-2','олигопептид-2'],'Олигопептид-2');
addNamed(['dimethyl isosorbide','диметилизосорбид'],'Диметилизосорбид');
addNamed(['cera alba','пчелиный воск'],'Пчелиный воск');
addNamed(['carnauba wax','карнаубский воск'],'Карнаубский воск');
addNamed(['candelilla cera','канделильский воск'],'Канделильский воск');
addNamed(['ozokerite','озокерит'],'Озокерит');
addNamed(['lanolin','ланолин'],'Ланолин');
addNamed(['lanolin alcohol','ланолиновый спирт'],'Ланолиновый спирт');
addNamed(['cholesteryl hydroxystearate','холестерилгидроксистеарат'],'Холестерилгидроксистеарат');
addNamed(['myristyl alcohol','миристиловый спирт'],'Миристиловый спирт');
addNamed(['lauryl alcohol','лауриловый спирт'],'Лауриловый спирт');
addNamed(['ceteareth-6','цетеарет-6'],'Цетеарет-6');
addNamed(['laureth-7','лаурет-7'],'Лаурет-7');
addNamed(['laureth-23','лаурет-23'],'Лаурет-23');
addNamed(['steareth-21','стеарет-21'],'Стеарет-21');
addNamed(['sodium cetearyl sulfate','цетеарилсульфат натрия'],'Цетеарилсульфат натрия');
addNamed(['sodium stearoyl lactylate','стеароиллактилат натрия'],'Стеароиллактилат натрия');
addNamed(['sucrose stearate','сахарозы стеарат'],'Сахарозы стеарат');
addNamed(['sucrose palmitate','сахарозы пальмитат'],'Сахарозы пальмитат');
addNamed(['hydroxypropyl methylcellulose','гидроксипропилметилцеллюлоза'],'Гидроксипропилметилцеллюлоза');
addNamed(['acacia senegal gum','камедь сенегальской акации'],'Камедь сенегальской акации');
addNamed(['carrageenan','каррагинан'],'Каррагинан');
addNamed(['konjac glucomannan','глюкоманнан конжака'],'Глюкоманнан конжака');
addNamed(['sodium anisate','анизат натрия'],'Анизат натрия');
addNamed(['potassium anisate','анизат калия'],'Анизат калия');
addNamed(['levulinic acid','левулиновая кислота'],'Левулиновая кислота');
addNamed(['sodium levulinate','левулинат натрия'],'Левулинат натрия');
addNamed(['glyceryl caprylate','глицерил каприлат'],'Глицерил каприлат');
addNamed(['tetrasodium glutamate diacetate','тетранатрий глутаматдиацетат'],'Тетранатрий глутаматдиацетат');
addNamed(['trisodium ethylenediamine disuccinate','тринатрий этилендиаминдисукцинат'],'Тринатрий этилендиаминдисукцинат');
addNamed(['retinyl propionate','ретинилпропионат'],'Ретинилпропионат');
addNamed(['hydroxypinacolone retinoate','гидроксипинаколона ретиноат'],'Гидроксипинаколона ретиноат');
addNamed(['tetrahexyldecyl ascorbate','тетрагексилдецил аскорбат'],'Тетрагексилдецил аскорбат');
addNamed(['ascorbyl glucoside','аскорбилглюкозид'],'Аскорбилглюкозид');
addNamed(['tocopheryl linoleate','токофериллинолеат'],'Токофериллинолеат');
addNamed(['hydrolyzed beta-glucan','гидролизованный бета-глюкан'],'Гидролизованный бета-глюкан');
addNamed(['poria cocos extract','экстракт пории'],'Экстракт пории');
addNamed(['laminaria japonica extract','экстракт ламинарии'],'Экстракт ламинарии');
addNamed(['undaria pinnatifida extract','экстракт ундарии'],'Экстракт ундарии');
addNamed(['fucus vesiculosus extract','экстракт фукуса'],'Экстракт фукуса');
addNamed(['spirulina platensis extract','экстракт спирулины'],'Экстракт спирулины');
addNamed(['chlorella vulgaris extract','экстракт хлореллы'],'Экстракт хлореллы');
addNamed(['porphyridium cruentum extract','экстракт красной водоросли'],'Экстракт красной водоросли');
addNamed(['saccharum officinarum extract','экстракт сахарного тростника'],'Экстракт сахарного тростника');
addNamed(['citrus aurantium dulcis fruit extract','экстракт апельсина'],'Экстракт апельсина');
addNamed(['vaccinium vitis-idaea fruit extract','экстракт брусники'],'Экстракт брусники');
addNamed(['fragaria vesca fruit extract','экстракт клубники'],'Экстракт клубники');
addNamed(['rubus idaeus fruit extract','экстракт малины'],'Экстракт малины');
addNamed(['morus alba fruit extract','экстракт белой шелковицы'],'Экстракт белой шелковицы');
addNamed(['pyrus malus fruit extract','экстракт яблока'],'Экстракт яблока');
addNamed(['cucumis sativus fruit extract','экстракт огурца'],'Экстракт огурца');
addNamed(['solanum lycopersicum fruit extract','экстракт томата'],'Экстракт томата');
addNamed(['brassica oleracea italica extract','экстракт брокколи'],'Экстракт брокколи');
addNamed(['camellia sinensis leaf water','вода зелёного чая'],'Вода зелёного чая');
addNamed(['lavandula angustifolia flower water','лавандовая вода'],'Лавандовая вода');
addNamed(['citrus aurantium amara flower water','флёрдоранж'],'Флёрдоранж');
addNamed(['hamamelis virginiana leaf water','вода гамамелиса'],'Вода гамамелиса');
addNamed(['aloe barbadensis leaf juice powder','порошок сока алоэ'],'Порошок сока алоэ');
addNamed(['aloe ferox leaf extract','экстракт алоэ ферокс'],'Экстракт алоэ ферокс');
addNamed(['olea europaea leaf extract','экстракт листьев оливы'],'Экстракт листьев оливы');
addNamed(['pinus pinaster bark extract','экстракт коры сосны'],'Экстракт коры сосны');
addNamed(['pycnogenol','пикногенол'],'Пикногенол');
addNamed(['horse chestnut extract','экстракт конского каштана'],'Экстракт конского каштана');
addNamed(['escin','эсцин'],'Эсцин');
addNamed(['diosmin','диосмин'],'Диосмин');
addNamed(['rutin','рутин'],'Рутин');
addNamed(['hesperidin','гесперидин'],'Гесперидин');
addNamed(['quercetin','кверцетин'],'Кверцетин');
addNamed(['lutein','лютеин'],'Лютеин');
addNamed(['beta-carotene','бета-каротин'],'Бета-каротин');
addNamed(['chlorophyll','хлорофилл'],'Хлорофилл');
addNamed(['melatonin','мелатонин'],'Мелатонин');
addNamed(['carnitine','карнитин'],'Карнитин');
addNamed(['acetyl carnitine hcl','ацетилкарнитин hcl'],'Ацетилкарнитин HCl');
addNamed(['n-acetyl cysteine','n-ацетилцистеин'],'N-ацетилцистеин');
addNamed(['acetyl cysteine','ацетилцистеин'],'Ацетилцистеин');
addNamed(['sodium metabisulfite','метабисульфит натрия'],'Метабисульфит натрия');
addNamed(['sodium sulfite','сульфит натрия'],'Сульфит натрия');
addNamed(['sodium bisulfite','бисульфит натрия'],'Бисульфит натрия');
addNamed(['hydroquinone','гидрохинон'],'Гидрохинон');
addNamed(['phenylethyl resorcinol','фенилэтилрезорцинол'],'Фенилэтилрезорцинол');
addNamed(['undecylenoyl phenylalanine','ундециленоиламинофенилаланин'],'Ундециленоиламинофенилаланин');
addNamed(['oligopeptide-68','олигопептид-68'],'Олигопептид-68');
addNamed(['dipeptide-2','дипептид-2'],'Дипептид-2');
addNamed(['dipeptide-4','дипептид-4'],'Дипептид-4');
addNamed(['dipeptide-7','дипептид-7'],'Дипептид-7');
addNamed(['dipeptide-8','дипептид-8'],'Дипептид-8');
addNamed(['tetrapeptide-21','тетрапептид-21'],'Тетрапептид-21');
addNamed(['tetrapeptide-26','тетрапептид-26'],'Тетрапептид-26');
addNamed(['tetrapeptide-30','тетрапептид-30'],'Тетрапептид-30');

// ===== Постоянная офлайн-база, пополняемая из интернета =====
// Когда лаборатория находит компонент онлайн (даже простой консервант),
// мы строим для него запись в формате локальной базы INCI и сохраняем
// её в data.mjx.learnedInci — это переживает перезагрузку страницы
// (хранится в localStorage вместе с остальными данными дневника) и
// сразу подмешивается в основной словарь INCI, чтобы такие компоненты
// в следующий раз распознавались уже офлайн, без обращения к сети.
const COSING_FUNCTION_TAGS=[
  [/preserv/i,'консервант'],
  [/emulsif/i,'эмульгатор'],
  [/surfactant|foam|cleansing|detergent/i,'пав'],
  [/humectant/i,'увлажнение'],
  [/hair.?condition/i,'кондиционирование'],
  [/skin.?condition/i,'смягчение'],
  [/emollient/i,'смягчение'],
  [/viscosity|thicken/i,'загуститель'],
  [/antioxidant/i,'антиоксидант'],
  [/chelat/i,'хелатор'],
  [/buffering|ph adjust/i,'кислотность'],
  [/solvent/i,'растворитель'],
  [/uv absorber|uv filter|sunscreen/i,'uv-фильтр'],
  [/perfum|fragrance|masking|deodor/i,'аромат'],
  [/antistatic/i,'антистатик'],
  [/film.?form/i,'плёнкообразователь'],
  [/exfoliant|keratolytic/i,'кислота'],
  [/sooth|calming|anti-?irritant/i,'успокоение'],
  [/sebum|seboregulat/i,'себорегуляция'],
  [/binding|opacif|bulking/i,'стабилизатор'],
  [/colorant|coloring/i,'краситель'],
  [/propellant/i,'растворитель']
];
function tagsFromOnlineText(text){
  const s=String(text||'');
  const tags=[];
  for(const [re,tag] of COSING_FUNCTION_TAGS){ if(re.test(s) && !tags.includes(tag)) tags.push(tag); }
  return tags;
}
function buildLearnedEntry(name,r){
  const sources=[];
  if(r?.cos) sources.push('EU CosIng');
  if(r?.pub) sources.push('PubChem');
  if(r?.web) sources.push('Интернет-поиск');
  if(r?.wiki) sources.push('Wikidata');
  const functionText=[r?.cos?.functions,r?.web?.text,r?.wiki?.description,r?.annotation].filter(Boolean).join('. ');
  let tags=tagsFromOnlineText(functionText);
  if(!tags.length) tags=['актив'];
  const yellowTags=['консервант','аромат','uv-фильтр','кислота','краситель'];
  const status = tags.some(t=>yellowTags.includes(t)) ? 'yellow' : 'green';
  const reliable = sources.length>=2;
  const confidenceNote = reliable
    ? `подтверждено ${sources.length} источниками (${sources.join(', ')})`
    : `данные найдены только в одном источнике (${sources.join(', ')||'неизвестно'}), точность ниже — стоит перепроверить`;
  const risk = `${inciFunction(tags)} Добавлено автоматически из интернета: ${confidenceNote}.`;
  const pretty = String(name||'').trim();
  return {
    name: pretty.charAt(0).toUpperCase()+pretty.slice(1),
    status,
    fit:['normal','dry','oily','combination','sensitive'],
    tags,
    risk,
    learned:true,
    reliable,
    sources,
    learnedAt: Date.now()
  };
}
function learnIngredientFromOnline(name,r){
  if(!r) return null;
  ensure();
  const key=normalizeIngredientPart(name)||String(name||'').toLowerCase().trim();
  if(!key) return null;
  const entry=buildLearnedEntry(name,r);
  entry.key=key;
  data.mjx.learnedInci=data.mjx.learnedInci||{};
  data.mjx.learnedInci[key]=entry;
  INCI[key]=entry;
  save2();
  return entry;
}
function mergeLearnedIntoInci(){
  ensure();
  const learned=data.mjx.learnedInci||{};
  for(const key of Object.keys(learned)){
    const entry=learned[key];
    if(entry && entry.name) INCI[key]=entry;
  }
}
mergeLearnedIntoInci();

const aliases={
  'витамин c':'ascorbic acid',
  'sodium hyaluronate':'sodium hyaluronate',
  'гиалуронат натрия':'sodium hyaluronate',
  'b3':'niacinamide',
  'vitamin b3':'niacinamide',
  'nicotinamide':'niacinamide',
  'vitamin e':'tocopherol',
  'denat. alcohol':'alcohol denat',
  'alcohol denat.':'alcohol denat',
  'parfum/fragrance':'parfum',
  'water':'aqua',
  'cocos nucifera (coconut) oil':'coconut oil',
  'butyrospermum parkii butter':'shea butter',
  'argania spinosa kernel oil':'argan oil',
  'simmondsia chinensis seed oil':'jojoba oil',
  'helianthus annuus seed oil':'sunflower seed oil',
  'prunus amygdalus dulcis oil':'sweet almond oil',
  'persea gratissima oil':'avocado oil',
  'vitis vinifera seed oil':'grape seed oil',
  'rosa canina fruit oil':'rosehip oil',
  'theobroma cacao seed butter':'cocoa butter',
  'mangifera indica seed butter':'mango butter',
  'ethylhexyl methoxycinnamate':'octinoxate',
  'ethylhexyl salicylate':'octisalate',
  'butyl methoxydibenzoylmethane':'avobenzone',
  'bis-ethylhexyloxyphenol methoxyphenyl triazine':'bemotrizinol',
  'methylene bis-benzotriazolyl tetramethylbutylphenol':'bisoctrizole'
};
// Дополнительные варианты названий для ARAVIA и русских составов.
Object.assign(aliases,{
  'potassium cetyl phosphate': 'potassium cetyl phosphate',
  'цетил фосфат калия': 'potassium cetyl phosphate',
  'цетилфосфат калия': 'potassium cetyl phosphate',
  'isopentyldiol': 'isopentyldiol',
  'изопентилдиол': 'isopentyldiol',
  'sodium acrylates copolymer': 'sodium acrylates copolymer',
  'сополимер акрилатов натрия': 'sodium acrylates copolymer',
  'lecithin': 'lecithin',
  'лецитин': 'lecithin',
  'bht': 'bht',
  'butylated hydroxytoluene': 'bht',
  'бутилированный гидрокситолуол': 'bht',
  'threonine': 'threonine',
  'треонин': 'threonine',
  'теонин': 'threonine',
  'lysine': 'lysine',
  'лизин': 'lysine',
  'glutamic acid': 'glutamic acid',
  'глутаминовая кислота': 'glutamic acid',
});
Object.assign(aliases,{
 'potassium cetyl phosphateisopentyldiol':'potassium cetyl phosphate',
 'isopentyldiolsodium acrylates copolymer':'isopentyldiol',
 'sodium acrylates copolymer и lecithin':'sodium acrylates copolymer',
 'lecithinbhtthreoninelysineglutamic acid':'lecithin',
 'potassium cetyl phosphate':'potassium cetyl phosphate',
 'isopentyldiol':'isopentyldiol',
 'sodium acrylates copolymer':'sodium acrylates copolymer',
 'lecithin':'lecithin',
 'bht':'bht',
 'threonine':'threonine',
 'треонин':'threonine',
 'теонин':'threonine',
 'lysine':'lysine',
 'лизин':'lysine',
 'glutamic acid':'glutamic acid',
 'глутаминовая кислота':'glutamic acid'
});

Object.assign(aliases,{
  'Гидроксиэтилмочевина': 'hydroxyethyl urea',
  'hydroxyethyl urea': 'hydroxyethyl urea',
  'Эритритол': 'erythritol',
  'erythritol': 'erythritol',
  'Сахаридный изомерат': 'saccharide isomerate',
  'saccharide isomerate': 'saccharide isomerate',
  'Лактат натрия': 'sodium lactate',
  'sodium lactate': 'sodium lactate',
  'Калий PCA': 'potassium pca',
  'potassium pca': 'potassium pca',
  'Глюконат натрия': 'sodium gluconate',
  'sodium gluconate': 'sodium gluconate',
  'Ксилитилглюкозид': 'xylitylglucoside',
  'xylitylglucoside': 'xylitylglucoside',
  'Ангидроксилитол': 'anhydroxylitol',
  'anhydroxylitol': 'anhydroxylitol',
  'Ксилитол': 'xylitol',
  'xylitol': 'xylitol',
  'Бета-глюкан': 'beta-glucan',
  'beta-glucan': 'beta-glucan',
  'Пуллулан': 'pullulan',
  'pullulan': 'pullulan',
  'Трегалоза': 'trehalose',
  'trehalose': 'trehalose',
  'Гидролизованная гиалуроновая кислота': 'hydrolyzed hyaluronic acid',
  'hydrolyzed hyaluronic acid': 'hydrolyzed hyaluronic acid',
  'Кроссполимер гиалуроната натрия': 'sodium hyaluronate crosspolymer',
  'sodium hyaluronate crosspolymer': 'sodium hyaluronate crosspolymer',
  'Гидролизованный гиалуронат натрия': 'hydrolyzed sodium hyaluronate',
  'hydrolyzed sodium hyaluronate': 'hydrolyzed sodium hyaluronate',
  'Гиалуронат натрия': 'sodium hyaluronate',
  'sodium hyaluronate': 'sodium hyaluronate',
  'Гидролизованные гликозаминогликаны': 'hydrolyzed glycosaminoglycans',
  'hydrolyzed glycosaminoglycans': 'hydrolyzed glycosaminoglycans',
  'Гликозаминогликаны': 'glycosaminoglycans',
  'glycosaminoglycans': 'glycosaminoglycans',
  'Церамид NP': 'ceramide np',
  'ceramide np': 'ceramide np',
  'Церамид AP': 'ceramide ap',
  'ceramide ap': 'ceramide ap',
  'Церамид EOP': 'ceramide eop',
  'ceramide eop': 'ceramide eop',
  'Церамид NS': 'ceramide ns',
  'ceramide ns': 'ceramide ns',
  'Церамид AS': 'ceramide as',
  'ceramide as': 'ceramide as',
  'Фитосфингозин': 'phytosphingosine',
  'phytosphingosine': 'phytosphingosine',
  'Сфингозин': 'sphingosine',
  'sphingosine': 'sphingosine',
  'Гидрогенизированный лецитин': 'hydrogenated lecithin',
  'hydrogenated lecithin': 'hydrogenated lecithin',
  'Фосфатидилхолин': 'phosphatidylcholine',
  'phosphatidylcholine': 'phosphatidylcholine',
  'Линолевая кислота': 'linoleic acid',
  'linoleic acid': 'linoleic acid',
  'Линоленовая кислота': 'linolenic acid',
  'linolenic acid': 'linolenic acid',
  'Олеиновая кислота': 'oleic acid',
  'oleic acid': 'oleic acid',
  'Пальмитиновая кислота': 'palmitic acid',
  'palmitic acid': 'palmitic acid',
  'Стеариновая кислота': 'stearic acid',
  'stearic acid': 'stearic acid',
  'Каприновая кислота': 'capric acid',
  'capric acid': 'capric acid',
  'Каприловая кислота': 'caprylic acid',
  'caprylic acid': 'caprylic acid',
  'Эфиры жожоба': 'jojoba esters',
  'jojoba esters': 'jojoba esters',
  'Масло макадамии': 'macadamia integrifolia seed oil',
  'macadamia integrifolia seed oil': 'macadamia integrifolia seed oil',
  'Масло сладкого миндаля': 'prunus amygdalus dulcis oil',
  'prunus amygdalus dulcis oil': 'prunus amygdalus dulcis oil',
  'Масло примулы вечерней': 'oenothera biennis oil',
  'oenothera biennis oil': 'oenothera biennis oil',
  'Масло шиповника': 'rosa canina fruit oil',
  'rosa canina fruit oil': 'rosa canina fruit oil',
  'Аргановое масло': 'argania spinosa kernel oil',
  'argania spinosa kernel oil': 'argania spinosa kernel oil',
  'Масло авокадо': 'persea gratissima oil',
  'persea gratissima oil': 'persea gratissima oil',
  'Масло виноградных косточек': 'vitis vinifera seed oil',
  'vitis vinifera seed oil': 'vitis vinifera seed oil',
  'Подсолнечное масло': 'helianthus annuus seed oil',
  'helianthus annuus seed oil': 'helianthus annuus seed oil',
  'Масло жожоба': 'simmondsia chinensis seed oil',
  'simmondsia chinensis seed oil': 'simmondsia chinensis seed oil',
  'Кокосовое масло': 'cocos nucifera oil',
  'cocos nucifera oil': 'cocos nucifera oil',
  'Оливковое масло': 'olea europaea fruit oil',
  'olea europaea fruit oil': 'olea europaea fruit oil',
  'Масло ши': 'butyrospermum parkii butter',
  'butyrospermum parkii butter': 'butyrospermum parkii butter',
  'Масло какао': 'theobroma cacao seed butter',
  'theobroma cacao seed butter': 'theobroma cacao seed butter',
  'Масло манго': 'mangifera indica seed butter',
  'mangifera indica seed butter': 'mangifera indica seed butter',
  'Касторовое масло': 'ricinus communis seed oil',
  'ricinus communis seed oil': 'ricinus communis seed oil',
  'Масло семян шиповника': 'rosa canina seed oil',
  'rosa canina seed oil': 'rosa canina seed oil',
  'Масло камелии': 'camellia japonica seed oil',
  'camellia japonica seed oil': 'camellia japonica seed oil',
  'Каприловый/каприновый триглицерид': 'caprylic/capric triglyceride',
  'caprylic/capric triglyceride': 'caprylic/capric triglyceride',
  'Коко-каприлат/капрат': 'coco-caprylate/caprate',
  'coco-caprylate/caprate': 'coco-caprylate/caprate',
  'Дикаприлилкарбонат': 'dicaprylyl carbonate',
  'dicaprylyl carbonate': 'dicaprylyl carbonate',
  'Дикаприлиловый эфир': 'dicaprylyl ether',
  'dicaprylyl ether': 'dicaprylyl ether',
  'Изоамиллаурат': 'isoamyl laurate',
  'isoamyl laurate': 'isoamyl laurate',
  'Бензоат C12-15 алкила': 'c12-15 alkyl benzoate',
  'c12-15 alkyl benzoate': 'c12-15 alkyl benzoate',
  'Этилгексилпальмитат': 'ethylhexyl palmitate',
  'ethylhexyl palmitate': 'ethylhexyl palmitate',
  'Этилгексилстеарат': 'ethylhexyl stearate',
  'ethylhexyl stearate': 'ethylhexyl stearate',
  'Изопропилмиристат': 'isopropyl myristate',
  'isopropyl myristate': 'isopropyl myristate',
  'Изопропилпальмитат': 'isopropyl palmitate',
  'isopropyl palmitate': 'isopropyl palmitate',
  'Октилдодеканол': 'octyldodecanol',
  'octyldodecanol': 'octyldodecanol',
  'Гидрогенизированный полиизобутен': 'hydrogenated polyisobutene',
  'hydrogenated polyisobutene': 'hydrogenated polyisobutene',
  'А модиметикон': 'amodimethicone',
  'amodimethicone': 'amodimethicone',
  'Диметикон': 'dimethicone',
  'dimethicone': 'dimethicone',
  'Диметиконол': 'dimethiconol',
  'dimethiconol': 'dimethiconol',
  'Фенилтриметикон': 'phenyl trimethicone',
  'phenyl trimethicone': 'phenyl trimethicone',
  'Триметилсилоксисиликат': 'trimethylsiloxysilicate',
  'trimethylsiloxysilicate': 'trimethylsiloxysilicate',
  'Силикон кватерниум-16': 'silicone quaternium-16',
  'silicone quaternium-16': 'silicone quaternium-16',
  'Силикон кватерниум-18': 'silicone quaternium-18',
  'silicone quaternium-18': 'silicone quaternium-18',
  'Силиконовый кондиционирующий полимер': 'bis-isobutyl peg/ppg-20/35 amino hydroxyethyl crosspolymer',
  'bis-isobutyl peg/ppg-20/35 amino hydroxyethyl crosspolymer': 'bis-isobutyl peg/ppg-20/35 amino hydroxyethyl crosspolymer',
  'Цетримониум хлорид': 'cetrimonium chloride',
  'cetrimonium chloride': 'cetrimonium chloride',
  'Бехентримониум хлорид': 'behentrimonium chloride',
  'behentrimonium chloride': 'behentrimonium chloride',
  'Бехентримониум метосульфат': 'behentrimonium methosulfate',
  'behentrimonium methosulfate': 'behentrimonium methosulfate',
  'Стеарамидопропилдиметиламин': 'stearamidopropyl dimethylamine',
  'stearamidopropyl dimethylamine': 'stearamidopropyl dimethylamine',
  'Гуар гидроксипропилтримониум хлорид': 'guar hydroxypropyltrimonium chloride',
  'guar hydroxypropyltrimonium chloride': 'guar hydroxypropyltrimonium chloride',
  'Поликватерниум-7': 'polyquaternium-7',
  'polyquaternium-7': 'polyquaternium-7',
  'Поликватерниум-10': 'polyquaternium-10',
  'polyquaternium-10': 'polyquaternium-10',
  'Поликватерниум-16': 'polyquaternium-16',
  'polyquaternium-16': 'polyquaternium-16',
  'Поликватерниум-37': 'polyquaternium-37',
  'polyquaternium-37': 'polyquaternium-37',
  'Поликватерниум-44': 'polyquaternium-44',
  'polyquaternium-44': 'polyquaternium-44',
  'Поликватерниум-68': 'polyquaternium-68',
  'polyquaternium-68': 'polyquaternium-68',
  'Гидролизованный кератин': 'hydrolyzed keratin',
  'hydrolyzed keratin': 'hydrolyzed keratin',
  'Гидролизованный шёлк': 'hydrolyzed silk',
  'hydrolyzed silk': 'hydrolyzed silk',
  'Гидролизованный пшеничный белок': 'hydrolyzed wheat protein',
  'hydrolyzed wheat protein': 'hydrolyzed wheat protein',
  'Гидролизованный рисовый белок': 'hydrolyzed rice protein',
  'hydrolyzed rice protein': 'hydrolyzed rice protein',
  'Гидролизованный соевый белок': 'hydrolyzed soy protein',
  'hydrolyzed soy protein': 'hydrolyzed soy protein',
  'Гидролизованный коллаген': 'hydrolyzed collagen',
  'hydrolyzed collagen': 'hydrolyzed collagen',
  'Гидролизованный эластин': 'hydrolyzed elastin',
  'hydrolyzed elastin': 'hydrolyzed elastin',
  'Аминокислоты пшеницы': 'wheat amino acids',
  'wheat amino acids': 'wheat amino acids',
  'Аминокислоты сои': 'soy amino acids',
  'soy amino acids': 'soy amino acids',
  'Аминокислоты шёлка': 'silk amino acids',
  'silk amino acids': 'silk amino acids',
  'Глицин': 'glycine',
  'glycine': 'glycine',
  'Аланин': 'alanine',
  'alanine': 'alanine',
  'Пролин': 'proline',
  'proline': 'proline',
  'Серин': 'serine',
  'serine': 'serine',
  'Треонин': 'threonine',
  'threonine': 'threonine',
  'Аргинин': 'arginine',
  'arginine': 'arginine',
  'Лизин': 'lysine',
  'lysine': 'lysine',
  'Глутаминовая кислота': 'glutamic acid',
  'glutamic acid': 'glutamic acid',
  'Глутамин': 'glutamine',
  'glutamine': 'glutamine',
  'Аспарагиновая кислота': 'aspartic acid',
  'aspartic acid': 'aspartic acid',
  'Лейцин': 'leucine',
  'leucine': 'leucine',
  'Изолейцин': 'isoleucine',
  'isoleucine': 'isoleucine',
  'Валин': 'valine',
  'valine': 'valine',
  'Фенилаланин': 'phenylalanine',
  'phenylalanine': 'phenylalanine',
  'Гистидин': 'histidine',
  'histidine': 'histidine',
  'Тирозин': 'tyrosine',
  'tyrosine': 'tyrosine',
  'Метионин': 'methionine',
  'methionine': 'methionine',
  'Цистеин': 'cysteine',
  'cysteine': 'cysteine',
  'Цистин': 'cystine',
  'cystine': 'cystine',
  'Триптофан': 'tryptophan',
  'tryptophan': 'tryptophan',
  'Аллантоин': 'allantoin',
  'allantoin': 'allantoin',
  'Бисаболол': 'bisabolol',
  'bisabolol': 'bisabolol',
  'Мадекассосид': 'madecassoside',
  'madecassoside': 'madecassoside',
  'Экстракт центеллы азиатской': 'centella asiatica extract',
  'centella asiatica extract': 'centella asiatica extract',
  'Сок алоэ вера': 'aloe barbadensis leaf juice',
  'aloe barbadensis leaf juice': 'aloe barbadensis leaf juice',
  'Экстракт ромашки': 'chamomilla recutita flower extract',
  'chamomilla recutita flower extract': 'chamomilla recutita flower extract',
  'Экстракт календулы': 'calendula officinalis flower extract',
  'calendula officinalis flower extract': 'calendula officinalis flower extract',
  'Экстракт зелёного чая': 'camellia sinensis leaf extract',
  'camellia sinensis leaf extract': 'camellia sinensis leaf extract',
  'Экстракт солодки': 'glycyrrhiza glabra root extract',
  'glycyrrhiza glabra root extract': 'glycyrrhiza glabra root extract',
  'Экстракт гамамелиса': 'hamamelis virginiana extract',
  'hamamelis virginiana extract': 'hamamelis virginiana extract',
  'Экстракт овса': 'avena sativa kernel extract',
  'avena sativa kernel extract': 'avena sativa kernel extract',
  'Пантенол': 'panthenol',
  'panthenol': 'panthenol',
  'Ниацинамид': 'niacinamide',
  'niacinamide': 'niacinamide',
  'Цинк PCA': 'zinc pca',
  'zinc pca': 'zinc pca',
  'Азелаиновая кислота': 'azelaic acid',
  'azelaic acid': 'azelaic acid',
  'Транексамовая кислота': 'tranexamic acid',
  'tranexamic acid': 'tranexamic acid',
  'Альфа-арбутин': 'alpha-arbutin',
  'alpha-arbutin': 'alpha-arbutin',
  'Арбутин': 'arbutin',
  'arbutin': 'arbutin',
  'Койевая кислота': 'kojic acid',
  'kojic acid': 'kojic acid',
  'Бакучиол': 'bakuchiol',
  'bakuchiol': 'bakuchiol',
  'Ретинол': 'retinol',
  'retinol': 'retinol',
  'Ретиналь': 'retinal',
  'retinal': 'retinal',
  'Адапален': 'adapalene',
  'adapalene': 'adapalene',
  'Аскорбиновая кислота': 'ascorbic acid',
  'ascorbic acid': 'ascorbic acid',
  'Этил аскорбиновый эфир': '3-o-ethyl ascorbic acid',
  '3-o-ethyl ascorbic acid': '3-o-ethyl ascorbic acid',
  'Фосфат аскорбила натрия': 'sodium ascorbyl phosphate',
  'sodium ascorbyl phosphate': 'sodium ascorbyl phosphate',
  'Фосфат аскорбила магния': 'magnesium ascorbyl phosphate',
  'magnesium ascorbyl phosphate': 'magnesium ascorbyl phosphate',
  'Токоферол': 'tocopherol',
  'tocopherol': 'tocopherol',
  'Токоферилацетат': 'tocopheryl acetate',
  'tocopheryl acetate': 'tocopheryl acetate',
  'Феруловая кислота': 'ferulic acid',
  'ferulic acid': 'ferulic acid',
  'Коэнзим Q10': 'coenzyme q10',
  'coenzyme q10': 'coenzyme q10',
  'Убихинон': 'ubiquinone',
  'ubiquinone': 'ubiquinone',
  'Кофеин': 'caffeine',
  'caffeine': 'caffeine',
  'Аденозин': 'adenosine',
  'adenosine': 'adenosine',
  'Ацетилглюкозамин': 'acetyl glucosamine',
  'acetyl glucosamine': 'acetyl glucosamine',
  'Глюкозамина гидрохлорид': 'glucosamine hcl',
  'glucosamine hcl': 'glucosamine hcl',
  'Салициловая кислота': 'salicylic acid',
  'salicylic acid': 'salicylic acid',
  'Гликолевая кислота': 'glycolic acid',
  'glycolic acid': 'glycolic acid',
  'Молочная кислота': 'lactic acid',
  'lactic acid': 'lactic acid',
  'Миндальная кислота': 'mandelic acid',
  'mandelic acid': 'mandelic acid',
  'Глюконолактон': 'gluconolactone',
  'gluconolactone': 'gluconolactone',
  'Лактобионовая кислота': 'lactobionic acid',
  'lactobionic acid': 'lactobionic acid',
  'Лимонная кислота': 'citric acid',
  'citric acid': 'citric acid',
  'Яблочная кислота': 'malic acid',
  'malic acid': 'malic acid',
  'Винная кислота': 'tartaric acid',
  'tartaric acid': 'tartaric acid',
  'Каприлоилсалициловая кислота': 'capryloyl salicylic acid',
  'capryloyl salicylic acid': 'capryloyl salicylic acid',
  'Мочевина': 'urea',
  'urea': 'urea',
  'Децилглюкозид': 'decyl glucoside',
  'decyl glucoside': 'decyl glucoside',
  'Кокоглюкозид': 'coco-glucoside',
  'coco-glucoside': 'coco-glucoside',
  'Лаурилглюкозид': 'lauryl glucoside',
  'lauryl glucoside': 'lauryl glucoside',
  'Кокамидопропилбетаин': 'cocamidopropyl betaine',
  'cocamidopropyl betaine': 'cocamidopropyl betaine',
  'Кокоилглутамат натрия': 'sodium cocoyl glutamate',
  'sodium cocoyl glutamate': 'sodium cocoyl glutamate',
  'Кокоилизетионат натрия': 'sodium cocoyl isethionate',
  'sodium cocoyl isethionate': 'sodium cocoyl isethionate',
  'Лауроилсаркозинат натрия': 'sodium lauroyl sarcosinate',
  'sodium lauroyl sarcosinate': 'sodium lauroyl sarcosinate',
  'Лауроилглутамат натрия': 'sodium lauroyl glutamate',
  'sodium lauroyl glutamate': 'sodium lauroyl glutamate',
  'Динатрий кокоамфодиацетат': 'disodium cocoamphodiacetate',
  'disodium cocoamphodiacetate': 'disodium cocoamphodiacetate',
  'Метилкокоилтаурат натрия': 'sodium methyl cocoyl taurate',
  'sodium methyl cocoyl taurate': 'sodium methyl cocoyl taurate',
  'Лауроилметилизетионат натрия': 'sodium lauroyl methyl isethionate',
  'sodium lauroyl methyl isethionate': 'sodium lauroyl methyl isethionate',
  'Цетилфосфат калия': 'potassium cetyl phosphate',
  'potassium cetyl phosphate': 'potassium cetyl phosphate',
  'Цетеарет-20': 'ceteareth-20',
  'ceteareth-20': 'ceteareth-20',
  'Цетеарилглюкозид': 'cetearyl glucoside',
  'cetearyl glucoside': 'cetearyl glucoside',
  'Глицерилстеарат': 'glyceryl stearate',
  'glyceryl stearate': 'glyceryl stearate',
  'Глицерилстеарат SE': 'glyceryl stearate se',
  'glyceryl stearate se': 'glyceryl stearate se',
  'Полиглицерил-3 метилглюкозы дистеарат': 'polyglyceryl-3 methylglucose distearate',
  'polyglyceryl-3 methylglucose distearate': 'polyglyceryl-3 methylglucose distearate',
  'Полиглицерил-10 лаурат': 'polyglyceryl-10 laurate',
  'polyglyceryl-10 laurate': 'polyglyceryl-10 laurate',
  'Сорбитан оливат': 'sorbitan olivate',
  'sorbitan olivate': 'sorbitan olivate',
  'Полисорбат-20': 'polysorbate 20',
  'polysorbate 20': 'polysorbate 20',
  'Полисорбат-60': 'polysorbate 60',
  'polysorbate 60': 'polysorbate 60',
  'Полисорбат-80': 'polysorbate 80',
  'polysorbate 80': 'polysorbate 80',
  'PEG-100 стеарат': 'peg-100 stearate',
  'peg-100 stearate': 'peg-100 stearate',
  'Стеарет-20': 'steareth-20',
  'steareth-20': 'steareth-20',
  'Цетет-20': 'ceteth-20',
  'ceteth-20': 'ceteth-20',
  'Карбомер': 'carbomer',
  'carbomer': 'carbomer',
  'Ксантановая камедь': 'xanthan gum',
  'xanthan gum': 'xanthan gum',
  'Гидроксиэтилцеллюлоза': 'hydroxyethylcellulose',
  'hydroxyethylcellulose': 'hydroxyethylcellulose',
  'Целлюлозная камедь': 'cellulose gum',
  'cellulose gum': 'cellulose gum',
  'Склероциевaя камедь': 'sclerotium gum',
  'sclerotium gum': 'sclerotium gum',
  'Агар': 'agar',
  'agar': 'agar',
  'Экстракт хондруса': 'chondrus crispus extract',
  'chondrus crispus extract': 'chondrus crispus extract',
  'Камедь рожкового дерева': 'ceratonia siliqua gum',
  'ceratonia siliqua gum': 'ceratonia siliqua gum',
  'Сополимер акрилатов': 'acrylates copolymer',
  'acrylates copolymer': 'acrylates copolymer',
  'Сополимер акрилатов натрия': 'sodium acrylates copolymer',
  'sodium acrylates copolymer': 'sodium acrylates copolymer',
  'Полиакрилатный кроссполимер-6': 'polyacrylate crosspolymer-6',
  'polyacrylate crosspolymer-6': 'polyacrylate crosspolymer-6',
  'Сополимер аммоний акрилоилдиметилтаурата/VP': 'ammonium acryloyldimethyltaurate/vp copolymer',
  'ammonium acryloyldimethyltaurate/vp copolymer': 'ammonium acryloyldimethyltaurate/vp copolymer',
  'Феноксиэтанол': 'phenoxyethanol',
  'phenoxyethanol': 'phenoxyethanol',
  'Этилгексилглицерин': 'ethylhexylglycerin',
  'ethylhexylglycerin': 'ethylhexylglycerin',
  'Каприлилгликоль': 'caprylyl glycol',
  'caprylyl glycol': 'caprylyl glycol',
  'Бензоат натрия': 'sodium benzoate',
  'sodium benzoate': 'sodium benzoate',
  'Сорбат калия': 'potassium sorbate',
  'potassium sorbate': 'potassium sorbate',
  'Дегидроацетат натрия': 'sodium dehydroacetate',
  'sodium dehydroacetate': 'sodium dehydroacetate',
  'Динатрий EDTA': 'disodium edta',
  'disodium edta': 'disodium edta',
  'Тетранатрий EDTA': 'tetrasodium edta',
  'tetrasodium edta': 'tetrasodium edta',
  'Фитат натрия': 'sodium phytate',
  'sodium phytate': 'sodium phytate',
  'Фитиновая кислота': 'phytic acid',
  'phytic acid': 'phytic acid',
  'Гидроксиацетофенон': 'hydroxyacetophenone',
  'hydroxyacetophenone': 'hydroxyacetophenone',
  '1,2-гександиол': '1,2-hexanediol',
  '1,2-hexanediol': '1,2-hexanediol',
  'Оксид цинка': 'zinc oxide',
  'zinc oxide': 'zinc oxide',
  'Диоксид титана': 'titanium dioxide',
  'titanium dioxide': 'titanium dioxide',
  'Авобензон': 'avobenzone',
  'avobenzone': 'avobenzone',
  'Октокрилен': 'octocrylene',
  'octocrylene': 'octocrylene',
  'Гомосалат': 'homosalate',
  'homosalate': 'homosalate',
  'Октисалат': 'octisalate',
  'octisalate': 'octisalate',
  'Бемотризинол': 'bemotrizinol',
  'bemotrizinol': 'bemotrizinol',
  'Бисоктриазол': 'bisoctrizole',
  'bisoctrizole': 'bisoctrizole',
  'Диэтиламино гидроксибензоилгексилбензоат': 'diethylamino hydroxybenzoyl hexyl benzoate',
  'diethylamino hydroxybenzoyl hexyl benzoate': 'diethylamino hydroxybenzoyl hexyl benzoate',
  'Бутилированный гидрокситолуол (BHT)': 'bht',
  'bht': 'bht',
  'Отдушка': 'parfum',
  'parfum': 'parfum',
  'Лимонен': 'limonene',
  'limonene': 'limonene',
  'Линалоол': 'linalool',
  'linalool': 'linalool',
  'Цитраль': 'citral',
  'citral': 'citral',
  'Гераниол': 'geraniol',
  'geraniol': 'geraniol',
  'Цитронеллол': 'citronellol',
  'citronellol': 'citronellol',
  'Эвгенол': 'eugenol',
  'eugenol': 'eugenol',
  'Кумарин': 'coumarin',
  'coumarin': 'coumarin',
});

Object.entries(EXTRA_INCI_RU).forEach(([ru,inci])=>{aliases[ru]=inci;});
Object.assign(aliases,{
  'цетил фосфат калия':'potassium cetyl phosphate',
  'цетилфосфат калия':'potassium cetyl phosphate',
  'potassium cetyl phosphate':'potassium cetyl phosphate',
  'isopentyldiol':'isopentyldiol',
  'изопентилдиол':'isopentyldiol',
  'sodium acrylates copolymer':'sodium acrylates copolymer',
  'сополимер акрилатов натрия':'sodium acrylates copolymer',
  'lecithin':'lecithin',
  'лецитин':'lecithin',
  'фенокситанол':'phenoxyethanol',
  'феноксиэтанол':'phenoxyethanol',
  'phenoxyethanol':'phenoxyethanol',
  'bht':'bht',
  'butylated hydroxytoluene':'bht',
  'бутилированный гидрокситолуол':'bht',
  'теонин':'threonine',
  'треонин':'threonine',
  'threonine':'threonine',
  'lysine':'lysine',
  'лизин':'lysine',
  'glutamic acid':'glutamic acid',
  'глутаминовая кислота':'glutamic acid',
  'disodium edta':'disodium edta',
  'дизодиум эдта':'disodium edta',
  'дисодиум эдта':'disodium edta',
  'динатриевая соль эдта':'disodium edta'
});



// Русские названия ингредиентов: пользователь может вставлять состав как INCI,
// так и русское название вещества.
Object.assign(aliases,{
  'вода':'aqua','вода очищенная':'aqua',
  'глицерин':'glycerin','гиалуроновая кислота':'hyaluronic acid','гиалуронат натрия':'sodium hyaluronate',
  'пантенол':'panthenol','провитамин b5':'panthenol','бетаин':'betaine','сорбитол':'sorbitol',
  'пропандиол':'propanediol','пропиленгликоль':'propylene glycol','бутиленгликоль':'butylene glycol',
  'пентиленгликоль':'pentylene glycol','каприлилгликоль':'caprylyl glycol','мочевина':'urea',
  'натрий pca':'sodium pca','трегалоза':'trehalose','бета-глюкан':'beta-glucan','аллантоин':'allantoin',
  'церамиды':'ceramides','холестерин':'cholesterol','сквалан':'squalane','фосфолипиды':'phospholipids',
  'кокосовое масло':'coconut oil','аргановое масло':'argan oil','масло жожоба':'jojoba oil',
  'подсолнечное масло':'sunflower seed oil','оливковое масло':'olive oil','масло авокадо':'avocado oil',
  'масло виноградной косточки':'grape seed oil','масло шиповника':'rosehip oil',
  'масло ши':'shea butter','масло какао':'cocoa butter','масло манго':'mango butter',
  'цетиловый спирт':'cetyl alcohol','цетеариловый спирт':'cetearyl alcohol',
  'стеариловый спирт':'stearyl alcohol','бегениловый спирт':'behenyl alcohol',
  'диметикон':'dimethicone','циклопентасилоксан':'cyclopentasiloxane',
  'циклогексасилоксан':'cyclohexasiloxane','амодиметикон':'amodimethicone',
  'диметиконол':'dimethiconol','поликватерниум-7':'polyquaternium-7',
  'поликватерниум-10':'polyquaternium-10','гуар гидроксипропилтримониум хлорид':'guar hydroxypropyltrimonium chloride',
  'ниацинамид':'niacinamide','витамин b3':'niacinamide','никотинамид':'niacinamide',
  'цинк pca':'zinc pca','азелаиновая кислота':'azelaic acid','салициловая кислота':'salicylic acid',
  'гликолевая кислота':'glycolic acid','молочная кислота':'lactic acid','миндальная кислота':'mandelic acid',
  'глюконолактон':'gluconolactone','ретинол':'retinol','ретиналь':'retinal',
  'ретинилпальмитат':'retinyl palmitate','аскорбиновая кислота':'ascorbic acid',
  'витамин c':'ascorbic acid','фосфат аскорбила натрия':'sodium ascorbyl phosphate',
  'фосфат аскорбила магния':'magnesium ascorbyl phosphate','витамин e':'tocopherol',
  'токоферилацетат':'tocopheryl acetate','феруловая кислота':'ferulic acid',
  'транексамовая кислота':'tranexamic acid','альфа-арбутин':'alpha-arbutin','арбутин':'arbutin',
  'койевая кислота':'kojic acid','экстракт солодки':'licorice root extract',
  'центелла азиатская':'centella asiatica extract','мадекассосид':'madecassoside',
  'экстракт зелёного чая':'camellia sinensis leaf extract','экстракт ромашки':'chamomilla recutita extract',
  'алоэ вера':'aloe barbadensis leaf juice','гамамелис':'hamamelis virginiana extract',
  'экстракт розмарина':'rosemary leaf extract',
  'отдушка':'parfum','ароматизатор':'fragrance','линалоол':'linalool','лимонен':'limonene',
  'цитронеллол':'citronellol','гераниол':'geraniol','эвгенол':'eugenol','цитраль':'citral',
  'кумарин':'coumarin','бензиловый спирт':'benzyl alcohol',
  'лауретсульфат натрия':'sodium laureth sulfate','лаурилсульфат аммония':'ammonium lauryl sulfate',
  'лауретсульфат аммония':'ammonium laureth sulfate','глицерилстеарат':'glyceryl stearate',
  'изопропилмиристат':'isopropyl myristate','изопропилпальмитат':'isopropyl palmitate',
  'этилгексилпальмитат':'ethylhexyl palmitate',
  'оксид цинка':'zinc oxide','диоксид титана':'titanium dioxide','авобензон':'avobenzone',
  'октокрилен':'octocrylene','гомосалат':'homosalate'
});


Object.assign(aliases,{
 'масло кокоса':'coconut oil',
 'масло кокосовое':'coconut oil',
 'масло виноградных косточек':'grape seed oil',
 'масло виноградной косточки':'grape seed oil',
 'цетилфосфат калия':'potassium cetyl phosphate',
 'изопентилидиол':'isopentyldiol',
 'изопентилдиол':'isopentyldiol',
 'сополимер акрилатов натрия':'sodium acrylates copolymer',
 'лецитин':'lecithin',
 'феноксиэтанол':'phenoxyethanol',
 'этилгексилглицерин':'ethylhexylglycerin',
 'цетеарет 20':'ceteareth-20',
 'цетеарет-20':'ceteareth-20',
 'бутилированный гидрокситолуол':'bht',
 'бутилгидрокситолуол':'bht',
 'натриевая соль пирролидонкарбоновой кислоты':'sodium pca',
 'пирролидонкарбоновая кислота натрия':'sodium pca',
 'глутаминовая кислота':'glutamic acid',
 'лизин':'lysine',
 'аргинин':'arginine',
 'треонин':'threonine',
 'аланин':'alanine',
 'пролин':'proline',
 'серин':'serine',
 'глицин':'glycine'
});

const conflicts=[
  ['retinol','glycolic acid','Комбинация может заметно повышать риск сухости и раздражения; удобно разводить по разным ритуалам, особенно при чувствительной коже.'],
  ['retinol','salicylic acid','Сочетание активов может усиливать сухость и раздражение; вводи постепенно и отслеживай реакцию.'],
  ['retinol','ascorbic acid','Это не строгий запрет; при чувствительной коже сочетание активов может быть слишком насыщенным, поэтому удобно разводить по времени.'],
  ['ascorbic acid','glycolic acid','Несколько кислотных/активных компонентов в одной рутине могут повышать риск раздражения.'],
  ['salicylic acid','glycolic acid','Сочетание кислот может быть слишком активным для чувствительной кожи.'],
  ['retinal','glycolic acid','Ретиноид + кислота может повышать риск сухости и раздражения.'],
  ['retinal','salicylic acid','Ретиноид + BHA может усиливать сухость и раздражение.']
];
function normalizeInciText(t){
  let s=String(t||'').toLowerCase();
  s=s.replace(/[•·]/g,',').replace(/\r/g,'\n');
  for(const [a,b] of Object.entries(aliases))s=s.replaceAll(a,b);
  return s;
}
function normalizeIngredientPart(part){
  return String(part||'')
    .toLowerCase()
    .replace(/^ingredients?\s*:\s*/,'')
    .replace(/^состав\s*:\s*/,'')
    .replace(/\[[^\]]*\]/g,'')
    .replace(/\([^)]*\)/g,' ')
    .replace(/\s+/g,' ')
    .replace(/^[-–—\d.%]+\s*/,'')
    .trim();
}
function lookupInciPart(part){
  const raw=normalizeIngredientPart(part);
  if(!raw)return null;
  const direct=INCI[raw];
  if(direct)return {...direct,key:raw};
  // Позволяем процентам/уточнениям после названия не мешать распознаванию,
  // но не используем опасный общий поиск через s.includes(key).
  const candidates=Object.keys(INCI).filter(k=>raw.startsWith(k+' ')||raw.startsWith(k+',')||raw===k);
  candidates.sort((a,b)=>b.length-a.length);
  if(candidates.length)return {...INCI[candidates[0]],key:candidates[0]};
  return null;
}
function inciFunction(tags=[]){
  const map={
    'увлажнение':'Удерживает воду и помогает уменьшать ощущение сухости.',
    'барьер':'Поддерживает защитный барьер кожи и помогает снижать потерю влаги.',
    'смягчение':'Смягчает кожу или волосы и улучшает ощущение гладкости.',
    'кондиционирование':'Улучшает мягкость, скольжение и расчёсывание волос.',
    'очищение':'Помогает удалять загрязнения, себум и остатки средств.',
    'пав':'Очищающий или эмульгирующий поверхностно-активный компонент.',
    'эмульгатор':'Помогает смешивать водную и масляную фазы и стабилизировать эмульсию.',
    'загуститель':'Придаёт продукту нужную вязкость и текстуру.',
    'стабилизатор':'Помогает сохранять стабильность и однородность формулы.',
    'растворитель':'Помогает растворять другие компоненты и равномерно распределять их.',
    'консервант':'Защищает продукт от роста бактерий, дрожжей и плесени.',
    'хелатор':'Связывает следовые ионы металлов и помогает стабилизировать формулу.',
    'антиоксидант':'Помогает защищать формулу и кожу от окислительных процессов.',
    'успокоение':'Помогает поддерживать более спокойное состояние кожи и уменьшать ощущение дискомфорта.',
    'кислота':'Кислотный актив; используется для обновления, отшелушивания или работы с текстурой.',
    'ретиноид':'Актив, связанный с обновлением кожи и регулированием клеточных процессов.',
    'аромат':'Придаёт продукту запах или маскирует запах сырья.',
    'uv-фильтр':'Поглощает или рассеивает часть ультрафиолетового излучения.',
    'ув-фильтр':'Поглощает или рассеивает часть ультрафиолетового излучения.',
    'плёнкообразователь':'Создаёт тонкую плёнку на коже или волосах и помогает удерживать эффект ухода.',
    'антистатик':'Снижает статическое электричество и помогает уменьшать пушение волос.',
    'осмолит':'Помогает удерживать воду и поддерживать комфорт при изменении влажности.',
    'себорегуляция':'Помогает контролировать ощущение жирности и избыток себума.',
    'кислотность':'Помогает регулировать pH косметической формулы.'
  };
  for(const tag of tags){ if(map[tag]) return map[tag]; }
  return 'Функциональный компонент формулы; точная роль зависит от вещества и всей рецептуры.';
}
function ingredientRatings(x){
  const tags=(x.tags||[]).map(v=>String(v).toLowerCase());
  const name=String(x.name||'').toLowerCase();
  let hydration=32, irritation=x.status==='yellow'?42:12, comedogenicity=8;
  const has=t=>tags.some(v=>v.includes(t));
  if(has('увлажнение')) hydration+=34;
  if(has('барьер')) hydration+=22;
  if(has('смягчение')) hydration+=16;
  if(has('успокоение')) hydration+=8;
  if(has('осмолит')) hydration+=8;
  if(has('кислота')) { hydration+=4; irritation+=18; }
  if(has('ретиноид')) irritation+=28;
  if(has('аромат')) irritation+=28;
  if(has('пав')) irritation+=18;
  if(has('растворитель')) irritation+=14;
  if(has('актив')) irritation+=8;
  if(name.includes('parfum')||name.includes('отдуш')) irritation+=24;
  if(name.includes('alcohol') && !name.includes('fatty') && !has('жирный спирт')) irritation+=18;
  if(has('масло')) comedogenicity=30;
  if(has('эстер')) comedogenicity=34;
  if(has('смягчение') && comedogenicity<20) comedogenicity=18;
  const highComedogenic={
    'изопропилмиристат':82,'isopropyl myristate':82,
    'изопропилпальмитат':72,'isopropyl palmitate':72,
    'этилгексилпальмитат':58,'ethylhexyl palmitate':58,
    'кокосовое масло':62,'coconut oil':62,
    'масло какао':58,'cocoa butter':58,
    'масло авокадо':42,'avocado oil':42,
    'оливковое масло':38,'olive oil':38,
    'масло ши':26,'shea butter':26,
    'масло жожоба':14,'jojoba oil':14,
    'сквалан':8,'squalane':8,
    'минеральное масло':5,'mineral oil':5,
    'вазелин':3,'petrolatum':3
  };
  if(Object.prototype.hasOwnProperty.call(highComedogenic,name)) comedogenicity=highComedogenic[name];
  return {
    hydration:clamp(Math.round(hydration),0,100),
    irritation:clamp(Math.round(irritation),0,100),
    comedogenicity:clamp(Math.round(comedogenicity),0,100)
  };
}
function productRatings(found,unknownCount){
  if(!found.length)return {hydration:0,irritation:0,comedogenicity:0,confidence:0};
  const rs=found.map(ingredientRatings);
  const avg=k=>Math.round(rs.reduce((s,r)=>s+r[k],0)/rs.length);
  const confidence=Math.max(0,Math.min(100,Math.round(100-Math.min(60,unknownCount*7))));
  return {hydration:avg('hydration'),irritation:avg('irritation'),comedogenicity:avg('comedogenicity'),confidence};
}
function ratingLabel(type,value){
  if(type==='hydration') return value>=70?'высокое':value>=45?'среднее':'умеренное';
  if(type==='irritation') return value<=20?'низкий риск':value<=45?'умеренный риск':'повышенный риск';
  return value<=15?'низкий':value<=35?'умеренный':'повышенный';
}
function ratingBar(label,value,type){
  const suffix=type==='hydration'?ratingLabel(type,value):ratingLabel(type,value);
  return `<div class="item" style="padding:12px 14px"><div class="row between"><strong>${label}</strong><span class="tag">${value}/100 · ${suffix}</span></div><div class="progress" style="margin-top:8px"><i style="width:${value}%"></i></div></div>`;
}

// Расширенная функциональная классификация для лица и волос.
// Это справочная классификация по известной роли ингредиента в косметической формуле,
// а не лабораторное измерение эффективности.
const HAIR_FACE_RULES = [
  {keys:['hydroxyethyl urea','erythritol','saccharide isomerate','sodium lactate','potassium pca','xylitylglucoside','anhydroxylitol','xylitol','trehalose'],hair:['увлажнение волос','снижение сухости'],face:['увлажнение','поддержка комфорта кожи']},
  {keys:['ceramide np','ceramide ap','ceramide eop','ceramide ns','ceramide as','phytosphingosine','sphingosine','hydrogenated lecithin','phosphatidylcholine'],hair:['поддержка защитного слоя','смягчение'],face:['поддержка кожного барьера','смягчение']},
  {keys:['hydrolyzed keratin','hydrolyzed silk','hydrolyzed wheat protein','hydrolyzed rice protein','hydrolyzed soy protein','hydrolyzed collagen','hydrolyzed elastin','wheat amino acids','soy amino acids','silk amino acids'],hair:['кондиционирование','уход за повреждёнными волосами','улучшение ощущения плотности'],face:['смягчение']},
  {keys:['behentrimonium chloride','behentrimonium methosulfate','cetrimonium chloride','stearamidopropyl dimethylamine'],hair:['кондиционирование','улучшение расчёсывания','антистатический эффект'],face:[]},
  {keys:['allantoin','bisabolol','madecassoside','centella asiatica extract','aloe barbadensis leaf juice','chamomilla recutita flower extract','calendula officinalis flower extract','avena sativa kernel extract'],hair:['успокаивающий уход за кожей головы'],face:['успокаивающий уход']},
  {keys:['azelaic acid','tranexamic acid','alpha-arbutin','arbutin','kojic acid','bakuchiol','retinol','retinal','ascorbic acid','3-o-ethyl ascorbic acid','adenosine','acetyl glucosamine'],hair:['специфическая функция для длины волос не определяется'],face:['уход за тоном и текстурой кожи']},
  {keys:['salicylic acid','glycolic acid','lactic acid','mandelic acid','gluconolactone','lactobionic acid','malic acid','tartaric acid','capryloyl salicylic acid','urea'],hair:['уход за кожей головы','работа с накоплением/себумом'],face:['обновление кожи','работа с текстурой']},
  {keys:['decyl glucoside','coco-glucoside','lauryl glucoside','cocamidopropyl betaine','sodium cocoyl glutamate','sodium cocoyl isethionate','sodium lauroyl sarcosinate','sodium lauroyl glutamate','disodium cocoamphodiacetate','sodium methyl cocoyl taurate'],hair:['очищение','удаление себума и стайлинга'],face:['очищение']},
  {keys:['caffeine'],hair:['уход за кожей головы'],face:['антиоксидантная поддержка']},
  {keys:['zinc oxide','titanium dioxide','avobenzone','octocrylene','homosalate','octisalate','bemotrizinol','bisoctrizole','diethylamino hydroxybenzoyl hexyl benzoate'],hair:[],face:['UV-защита в составе солнцезащитной системы']},
  {keys:['glycerin','glycerine','sodium hyaluronate','hyaluronic acid','panthenol','betaine','sorbitol','propanediol','butylene glycol','pentylene glycol','urea','sodium pca','sodium lactate','trehalose','saccharide isomerate','beta-glucan'],
   hair:['увлажнение волос','снижение сухости'], face:['увлажнение','поддержка комфорта кожи']},
  {keys:['ceramide','ceramide np','ceramide ap','ceramide eop','ceramide ns','cholesterol','phytosphingosine','phospholipids','squalane'],
   hair:['поддержка защитного слоя','смягчение'], face:['поддержка кожного барьера','смягчение']},
  {keys:['dimethicone','amodimethicone','dimethiconol','cyclopentasiloxane','cyclohexasiloxane'],
   hair:['скольжение','кондиционирование','визуальное сглаживание'], face:['смягчение','защитная плёнка']},
  {keys:['polyquaternium-7','polyquaternium-10','guar hydroxypropyltrimonium chloride'],
   hair:['кондиционирование','антистатический эффект','улучшение расчёсывания'], face:[]},
  {keys:['cetearyl alcohol','cetyl alcohol','stearyl alcohol','behenyl alcohol','glyceryl stearate'],
   hair:['смягчение','структура формулы'], face:['смягчение','структура эмульсии']},
  {keys:['coconut oil','argan oil','jojoba oil','sunflower seed oil','olive oil','sweet almond oil','avocado oil','grape seed oil','rosehip oil','shea butter','cocoa butter','mango butter'],
   hair:['смягчение','питательный уход','уменьшение ощущения сухости'], face:['смягчение','питательный уход']},
  {keys:['niacinamide','zinc pca'],
   hair:['поддержка кожи головы','контроль себума'], face:['поддержка барьера','контроль себума']},
  {keys:['salicylic acid','glycolic acid','lactic acid','mandelic acid','gluconolactone'],
   hair:['обновление кожи головы','работа с накоплением/себумом'], face:['обновление кожи','работа с текстурой','работа с порами']},
  {keys:['retinol','retinal','retinyl palmitate'],
   hair:['специфическая роль для волос не определяется по INCI'], face:['обновление кожи','работа с текстурой']},
  {keys:['ascorbic acid','sodium ascorbyl phosphate','magnesium ascorbyl phosphate','tocopherol','tocopheryl acetate','ferulic acid','camellia sinensis leaf extract','rosemary leaf extract'],
   hair:['антиоксидантная поддержка формулы'], face:['антиоксидантная поддержка']},
  {keys:['centella asiatica extract','madecassoside','aloe barbadensis leaf juice','allantoin','bisabolol','licorice root extract','chamomilla recutita extract'],
   hair:['успокаивающий уход за кожей головы'], face:['успокаивающий уход']},
  {keys:['parfum','fragrance','linalool','limonene','citronellol','geraniol','eugenol','citral','coumarin'],
   hair:['ароматизация'], face:['ароматизация; возможный фактор чувствительности']},
  {keys:['sodium laureth sulfate','ammonium lauryl sulfate','ammonium laureth sulfate'],
   hair:['очищение','удаление себума и стайлинга'], face:['очищение']},
  {keys:['zinc oxide','titanium dioxide','avobenzone','octocrylene','octinoxate','octisalate','homosalate','bemotrizinol','bisoctrizole'],
   hair:[], face:['UV-защита в составе солнцезащитной системы']}
];

// Резервная карта: если конкретный ингредиент не описан вручную в HAIR_FACE_RULES
// (например, он только что подтянут из интернета), выводим функцию по его тегам.
// Так даже простые консерванты, эмульгаторы и загустители получают понятное
// описание "для чего он в составе волос/лица", а не "не определена".
const TAG_HAIR_FACE_MAP={
  'консервант':{hair:'защищает формулу от бактерий, дрожжей и плесени (консервант)',face:'защищает формулу от бактерий, дрожжей и плесени (консервант)'},
  'эмульгатор':{hair:'стабилизирует текстуру формулы',face:'стабилизирует текстуру формулы'},
  'загуститель':{hair:'формирует текстуру и вязкость средства',face:'формирует текстуру и вязкость средства'},
  'пав':{hair:'участвует в очищении',face:'участвует в очищении'},
  'очищение':{hair:'очищение',face:'очищение'},
  'увлажнение':{hair:'увлажнение волос',face:'увлажнение кожи'},
  'кондиционирование':{hair:'кондиционирование волос, улучшает расчёсывание',face:'смягчает кожу'},
  'смягчение':{hair:'смягчает волосы',face:'смягчает кожу'},
  'антиоксидант':{hair:'антиоксидантная поддержка формулы',face:'антиоксидантная поддержка кожи'},
  'аромат':{hair:'ароматизация',face:'ароматизация; возможный фактор чувствительности'},
  'uv-фильтр':{hair:'',face:'UV-защита в составе солнцезащитной системы'},
  'хелатор':{hair:'стабилизирует формулу, связывает следы металлов',face:'стабилизирует формулу, связывает следы металлов'},
  'антистатик':{hair:'снижает статику и пушение волос',face:''},
  'плёнкообразователь':{hair:'фиксация укладки, тонкая плёнка на волосе',face:'тонкая плёнка на коже, удержание эффекта ухода'},
  'себорегуляция':{hair:'помогает контролировать жирность кожи головы',face:'помогает контролировать себум'},
  'растворитель':{hair:'растворяет и распределяет другие компоненты формулы',face:'растворяет и распределяет другие компоненты формулы'},
  'осмолит':{hair:'помогает удерживать влагу в волосе',face:'поддержка комфорта кожи'},
  'кислота':{hair:'обновление кожи головы',face:'обновление кожи, работа с текстурой'},
  'кислотность':{hair:'регулирует pH формулы',face:'регулирует pH формулы'},
  'стабилизатор':{hair:'поддерживает стабильность формулы',face:'поддерживает стабильность формулы'},
  'краситель':{hair:'окрашивает саму формулу (не волосы)',face:'окрашивает саму формулу'},
  'актив':{hair:'функциональный компонент формулы',face:'функциональный компонент формулы'},
  'основа':{hair:'растворитель/основа формулы',face:'растворитель/основа формулы'}
};
function getHairFaceFunctions(item){
  const keyList = [String(item.key||'').toLowerCase(), String(item.name||'').toLowerCase()];
  const out={hair:[],face:[]};
  for(const rule of HAIR_FACE_RULES){
    if(rule.keys.some(k=>keyList.includes(k) || keyList.some(x=>x && x.includes(k)))){
      for(const x of (rule.hair||[])) if(!out.hair.includes(x)) out.hair.push(x);
      for(const x of (rule.face||[])) if(!out.face.includes(x)) out.face.push(x);
    }
  }
  if(!out.hair.length || !out.face.length){
    for(const tag of (item.tags||[])){
      const m=TAG_HAIR_FACE_MAP[String(tag).toLowerCase()];
      if(!m) continue;
      if(!out.hair.length && m.hair) out.hair.push(m.hair);
      if(!out.face.length && m.face) out.face.push(m.face);
    }
  }
  if(!out.hair.length) out.hair=['Функция для волос не определена локальной базой'];
  if(!out.face.length) out.face=['Функция для лица не определена локальной базой'];
  return out;
}


// ARAVIA_GLUE_BOUNDARIES: распознаём составы, где ингредиенты склеились без разделителей.
const ARAVIA_GLUE_BOUNDARIES = [
  ['potassium cetyl phosphate','isopentyldiol'],
  ['isopentyldiol','sodium acrylates copolymer'],
  ['sodium acrylates copolymer','lecithin'],
  ['lecithin','bht'],
  ['bht','threonine'],
  ['threonine','lysine'],
  ['lysine','glutamic acid']
];

function analyzeIngredients(text){
  const normalized=normalizeInciText(text)
    .replace(/[–—]/g,'-')
    .replace(/\s+/g,' ')
    .trim();
  let parts=normalized.split(/[,;\n]+/).map(x=>x.trim()).filter(Boolean);
  // Некоторые пользовательские списки приходят без запятых между ингредиентами.
  // Разделяем их только по известным русским названиям, не ломая многословные INCI.
  const ruKeys=Object.keys(EXTRA_INCI_RU).sort((a,b)=>b.length-a.length);
  const repaired=[];
  for(const raw of parts){
    let rest=raw;
    let guard=0;
    while(rest && guard++<30){
      const hit=ruKeys.find(k=>rest===k || rest.startsWith(k+' ') || rest.startsWith(k+','));
      if(hit){
        repaired.push(hit);
        rest=rest.slice(hit.length).replace(/^[,;\s]+/,'').trim();
      }else{
        repaired.push(rest.trim());
        break;
      }
    }
  }
  parts=repaired.filter(Boolean);
  const found=[]; const unknown=[];
  for(const part of parts){
    const hit=lookupInciPart(part);
    if(hit){
      if(!found.some(x=>x.name===hit.name))found.push(hit);
    } else if(part.length>=2){
      const pretty=part.replace(/\s+/g,' ').trim();
      if(!unknown.includes(pretty))unknown.push(pretty);
    }
  }
  const fitSkin=data.settings.skinType;
  const green=found.filter(x=>x.status==='green').length;
  const yellow=found.filter(x=>x.status==='yellow').length;
  const unknownPenalty=Math.min(12,unknown.length)*1.5;
  const activePenalty=Math.min(18,yellow*6);
  const score=Math.max(35,Math.min(98,Math.round(100-activePenalty-unknownPenalty)));
  const risk=score>=80?'green':score>=60?'yellow':'red';
  const pairFind=[];
  for(const [a,b,note] of conflicts){
    if(normalized.split(/[,;\n]+/).some(x=>normalizeIngredientPart(x)===a) && normalized.split(/[,;\n]+/).some(x=>normalizeIngredientPart(x)===b))pairFind.push({a,b,note});
  }
  const ratings=productRatings(found,unknown.length);
  return {found,unknown:unknown.slice(0,18),green,yellow,score,risk,pairs:pairFind,fitSkin,ratings};
}
function labPage(){ensure();const learnedCount=Object.keys(data.mjx.learnedInci||{}).length;return `<div class="mjx-shell"><div class="row between wrap"><div><h3 class="section-title">🧪 Лаборатория состава</h3><p class="subtle">Вставь INCI или русские названия ингредиентов — приложение распознает оба варианта, подсветит компоненты и сравнит состав с твоим профилем.</p></div><div class="row wrap" style="gap:6px"><span class="tag">Кожа: ${esc2(skinTypeName(data.settings.skinType))}</span>${learnedCount?`<span class="tag">🧠 Своя офлайн-база: +${learnedCount}</span>`:''}</div></div><section class="card"><div class="mjx-chat" id="mjxChat"><div class="mjx-msg bot">Привет ♡ Пришли список ингредиентов через запятую или вставь весь INCI. Я разберу знакомые компоненты, отмечу потенциально раздражающие и покажу возможные сочетания, которые стоит разводить по времени. Незнакомые компоненты — даже простые консерванты и эмульгаторы — можно проверить в интернете сразу по нескольким источникам (EU CosIng, PubChem, Wikidata и веб-поиск), и они автоматически сохранятся в твою офлайн-базу.</div>${data.mjx.lab.lastQuery?`<div class="mjx-msg user">${esc2(data.mjx.lab.lastQuery)}</div>`:''}</div><form id="mjxLabForm" class="form" style="margin-top:12px"><div class="field"><label>Состав продукта</label><textarea id="mjxInci" placeholder="Aqua, Glycerin, Niacinamide… или: Вода, Глицерин, Ниацинамид, Пантенол, Отдушка…">${esc2(data.mjx.lab.lastQuery||'')}</textarea></div><div class="row wrap"><button class="btn">Разобрать состав</button><button type="button" class="btn secondary" id="mjxCheckOnline">🌐 Проверить состав онлайн</button><button type="button" class="btn secondary" id="mjxInternetIngredient">🌐 Найти нераспознанные в интернете</button><button type="button" class="btn ghost" id="mjxOnlyProblem">Только проблемные</button></div></form></section><section id="mjxLabResult"></section><div id="mjxLabOnline"></div><section class="card"><div class="row between"><h3 class="section-title">🔎 Сравнить два продукта</h3><span class="subtle">Сравнение сохранённых составов</span></div>${compareForm()}</section><section class="card"><div class="row between wrap"><div><h3 class="section-title">🧠 Твоя пополняемая офлайн-база</h3><p class="subtle" style="margin:4px 0 0">Компоненты, которые ты хоть раз проверила онлайн, остаются здесь и в следующий раз распознаются без интернета — даже на телефоне без сети.</p></div><span class="tag">${learnedCount} компонент${learnedCount%10===1&&learnedCount%100!==11?'':(learnedCount%10>=2&&learnedCount%10<=4&&(learnedCount%100<10||learnedCount%100>=20)?'а':'ов')}</span></div>${learnedCount?`<div class="chip-tabs" style="margin-top:10px">${Object.values(data.mjx.learnedInci).slice(-40).map(x=>`<span class="tag" title="${esc2((x.sources||[]).join(', '))}">${x.reliable?'✅':'⚠️'} ${esc2(x.name)}</span>`).join('')}</div><div class="row" style="margin-top:12px"><button class="btn ghost small" id="mjxResetLearned">Очистить офлайн-пополнения</button></div>`:'<p class="subtle" style="margin-top:8px">Пока пусто — проверь состав через «🌐 Найти нераспознанные в интернете», и новые компоненты появятся здесь.</p>'}</section><section class="card"><h3 class="section-title">💬 Подсказка</h3><p class="subtle">Это справочный косметический анализ: функционал для волос/лица определяется по распознанным ингредиентам и не является медицинской диагностикой. Наличие или отсутствие ингредиента не гарантирует переносимость продукта конкретным человеком. Онлайн-данные агрегируются из нескольких независимых источников (EU CosIng, PubChem, Wikidata, веб-поиск) — компонент помечается ✅, только если его подтвердили минимум два источника, иначе ⚠️ и стоит перепроверить вручную.</p></section></div>`}
function compareForm(){const opts=data.products.filter(p=>p.ingredients||p.composition).map(p=>`<option value="${p.id}">${esc2(p.name)}</option>`).join('');return `<div class="grid grid-2"><div class="field"><label>Продукт 1</label><select id="mjxCompareA"><option value="">Выбрать…</option>${opts}</select></div><div class="field"><label>Продукт 2</label><select id="mjxCompareB"><option value="">Выбрать…</option>${opts}</select></div></div><div class="row" style="justify-content:flex-end;margin-top:10px"><button class="btn secondary" id="mjxCompareBtn">Сравнить</button></div><div id="mjxCompareResult" style="margin-top:12px"></div>`}
function renderLabResult(res,onlyProblems=false){
  const shown=onlyProblems?res.found.filter(x=>x.status!=='green'):res.found;
  const fit=res.found.filter(x=>x.fit.includes(res.fitSkin));
  const notFit=res.found.filter(x=>!x.fit.includes(res.fitSkin));
  const ratings=res.ratings||productRatings(res.found,res.unknown.length);
  const ratingItems=res.found.map(x=>{
    const r=ingredientRatings(x);
    return `<div class="mjx-ingredient"><span class="mjx-dot ${x.status}"></span><div style="min-width:0;flex:1"><div class="row between wrap"><strong>${esc2(x.name)}</strong><span class="tag">${x.status==='green'?'✓ базовый ориентир':'⚠ требует внимания'}</span></div><div class="subtle">${(x.tags||[]).map(esc2).join(' · ')}</div><div class="grid" style="grid-template-columns:repeat(3,minmax(0,1fr));gap:6px;margin-top:8px"><span class="tag" title="Чем выше, тем выраженнее увлажняющий профиль">💧 ${r.hydration}</span><span class="tag" title="Чем выше, тем выше потенциальный риск раздражения">🔥 ${r.irritation}</span><span class="tag" title="Чем выше, тем выше потенциальная комедогенность">◌ ${r.comedogenicity}</span></div><p class="subtle" style="margin:5px 0 0"><strong>Функция:</strong> ${esc2(inciFunction(x.tags))}</p><p class="subtle" style="margin:4px 0 0">${esc2(x.risk)}</p>${(()=>{const f=getHairFaceFunctions(x);return `<div class="grid grid-2" style="margin-top:9px;gap:8px"><div class="item" style="padding:9px"><strong>💇 Для волос</strong><p class="subtle" style="margin:4px 0 0">${f.hair.map(esc2).join(' · ')}</p></div><div class="item" style="padding:9px"><strong>🧴 Для лица</strong><p class="subtle" style="margin:4px 0 0">${f.face.map(esc2).join(' · ')}</p></div></div>`})()}</div></div>`;
  }).join('');
  return `<div class="grid mjx-grid-2" style="margin-top:16px"><section class="card"><div class="row between"><div><div class="label">Итог</div><h3 style="margin:5px 0">Индекс формулы</h3></div><div class="mjx-stat-big">${res.score}</div></div><div class="tag">${res.risk==='green'?'🟢 Спокойная формула':res.risk==='yellow'?'🟡 Нужна аккуратность':'🔴 Много факторов для внимания'}</div><p class="subtle" style="margin-top:10px">Это не медицинская оценка безопасности, а внутренний ориентир по распознанным компонентам и правилам приложения.</p></section><section class="card"><h3 class="section-title">♡ Для твоего типа кожи</h3><div class="list"><div class="item"><strong>Подходят по профилю</strong><p>${fit.length?fit.map(x=>esc2(x.name)).join(', '):'Пока ничего не распознано как приоритет для профиля.'}</p></div><div class="item"><strong>С осторожностью</strong><p>${notFit.length?notFit.map(x=>esc2(x.name)).join(', '):'Явных несовпадений в базе не найдено.'}</p></div></div></section></div><section class="card" style="margin-top:16px"><div class="row between wrap"><div><h3 class="section-title">📊 Дополнительная оценка продукта</h3><p class="subtle" style="margin:0">Ориентир по распознанным ингредиентам. Для раздражения и комедогенности меньше — лучше; для увлажнения больше — лучше.</p></div><span class="tag">уверенность ${ratings.confidence}%</span></div><div class="list" style="margin-top:12px">${ratingBar('💧 Увлажнение',ratings.hydration,'hydration')}${ratingBar('🔥 Раздражение',ratings.irritation,'irritation')}${ratingBar('◌ Потенциальная комедогенность',ratings.comedogenicity,'comedogenicity')}</div><p class="subtle" style="margin:10px 0 0">Важно: это не лабораторное измерение и не диагноз. INCI не показывает точные концентрации, а индивидуальная реакция может отличаться.</p></section><section class="card" style="margin-top:16px"><div class="row between"><h3 class="section-title">Ингредиенты</h3><span class="tag">${res.found.length} распознано · ${res.unknown.length} без данных</span></div><div class="list">${(onlyProblems?res.found.filter(x=>x.status!=='green'):res.found).map(x=>{const r=ingredientRatings(x);return `<div class="mjx-ingredient"><span class="mjx-dot ${x.status}"></span><div style="min-width:0;flex:1"><div class="row between wrap"><strong>${esc2(x.name)}</strong><span class="tag">💧 ${r.hydration} · 🔥 ${r.irritation} · ◌ ${r.comedogenicity}</span></div><div class="subtle">${(x.tags||[]).map(esc2).join(' · ')}</div><p class="subtle" style="margin:5px 0 0"><strong>Функция:</strong> ${esc2(inciFunction(x.tags))}</p><p class="subtle" style="margin:4px 0 0">${esc2(x.risk)}</p></div></div>`}).join('')||'<div class="empty">Проблемных ингредиентов по текущим правилам не найдено.</div>'}</div></section><section class="card" style="margin-top:16px"><div class="row between wrap"><div><h3 class="section-title">🧩 Функциональный профиль состава</h3><p class="subtle">Что формула потенциально делает для волос и для лица по распознанным ингредиентам.</p></div></div><div class="grid mjx-grid-2"><div class="item"><strong>💇 Для волос</strong><div class="chip-tabs" style="margin-top:8px">${(()=>{const a=[...new Set(res.found.flatMap(x=>getHairFaceFunctions(x).hair))].filter(x=>!x.includes('не определена'));return a.length?a.map(x=>`<span class="tag">${esc2(x)}</span>`).join(''):'<span class="subtle">Явных функций для волос не найдено.</span>'})()}</div></div><div class="item"><strong>🧴 Для лица</strong><div class="chip-tabs" style="margin-top:8px">${(()=>{const a=[...new Set(res.found.flatMap(x=>getHairFaceFunctions(x).face))].filter(x=>!x.includes('не определена'));return a.length?a.map(x=>`<span class="tag">${esc2(x)}</span>`).join(''):'<span class="subtle">Явных функций для лица не найдено.</span>'})()}</div></div></div></section>${res.pairs.length?`<section class="card" style="margin-top:16px"><h3 class="section-title">⚠️ Возможные сочетания</h3><div class="list">${res.pairs.map(p=>`<div class="item"><strong>${esc2(p.a)} + ${esc2(p.b)}</strong><p>${esc2(p.note)}</p></div>`).join('')}</div></section>`:''}${res.unknown.length?`<section class="card" style="margin-top:16px"><h3 class="section-title">Серые зоны</h3><p class="subtle">Не все названия распознаны локальной базой. База расширена более чем на 150 дополнительных компонентов. Можно вводить ингредиенты на русском или в INCI-написании. Их можно искать отдельно через интернет.</p><div class="chip-tabs">${res.unknown.map(x=>`<span class="tag">${esc2(x)}</span>`).join('')}</div></section>`:''}`
}
async function lookupIngredientOnline(name){const chat=document.getElementById('mjxChat');if(chat)chat.insertAdjacentHTML('beforeend',`<div class="mjx-msg user">Проверь в интернете: ${esc2(name)}</div>`);try{const controller=new AbortController();const timer=setTimeout(()=>controller.abort(),9000);const url='https://pubchem.ncbi.nlm.nih.gov/rest/pug/compound/name/'+encodeURIComponent(name)+'/property/MolecularFormula,MolecularWeight,IUPACName/JSON';const response=await fetch(url,{signal:controller.signal});clearTimeout(timer);if(!response.ok)throw new Error('not found');const j=await response.json();const p=j?.PropertyTable?.Properties?.[0];if(chat)chat.insertAdjacentHTML('beforeend',`<div class="mjx-msg bot"><strong>${esc2(name)}</strong><br>Формула: ${esc2(p?.MolecularFormula||'нет данных')}<br>Молекулярная масса: ${esc2(String(p?.MolecularWeight||'нет данных'))}<br>IUPAC: ${esc2(p?.IUPACName||'нет данных')}<br><span class="subtle">Справочные химические данные: PubChem.</span></div>`);return p||null}catch(e){if(chat)chat.insertAdjacentHTML('beforeend',`<div class="mjx-msg bot"><strong>${esc2(name)}</strong><br>В PubChem точное совпадение не найдено или интернет сейчас недоступен.<br><span class="subtle">Локальная база продолжает работать.</span></div>`);return null}}

async function checkLabOnline(){
  const text=document.getElementById('mjxInci')?.value?.trim()||'';
  const box=document.getElementById('mjxLabOnline');
  if(!text){toast('Сначала вставь состав ♡');return}
  if(!box)return;

  const local=analyzeIngredients(text);

  // Проверяем ВЕСЬ введённый состав, а не только неизвестные компоненты и не только первые 12.
  // Берём каждый отдельный пункт INCI/состава и сохраняем порядок.
  const rawParts=text
    .replace(/[–—]/g,'-')
    .split(/[,;\n]+/)
    .map(x=>x.replace(/^\s*[-•·]\s*/,'').replace(/\s+/g,' ').trim())
    .filter(x=>x.length>=2);

  // Если локальный анализ смог распознать компонент, используем его каноническое название,
  // но неизвестные названия тоже обязательно отправляем в онлайн-проверку.
  const targets=[];
  const seen=new Set();
  for(const part of rawParts){
    const hit=lookupInciPart(part);
    const name=(hit?.name||part).trim();
    const key=name.toLowerCase();
    if(!seen.has(key)){
      seen.add(key);
      targets.push(name);
    }
  }

  box.innerHTML=`<section class="card" style="margin-top:16px">
    <div class="row between wrap">
      <div>
        <h3 class="section-title">🌐 Онлайн-проверка всего состава</h3>
        <p class="subtle">Проверяю каждый компонент через EU CosIng + PubChem. CosIng даёт INCI и косметическую функцию, PubChem — химическую идентификацию и дополнительные справочные сведения.</p>
      </div>
      <span class="tag">${targets.length} компонентов к проверке</span>
    </div>
    <div class="list" id="mjxOnlineList"><div class="empty">Проверяю весь состав…</div></div>
  </section>`;

  const list=document.getElementById('mjxOnlineList');
  if(!list)return;

  let found=0,miss=0,learnedCount=0;
  const rows=[];

  for(let i=0;i<targets.length;i++){
    const name=targets[i];
    const alreadyKnown=!!lookupInciPart(name);
    const p=await lookupIngredientDataSilent(name);

    if(p){
      found++;
      let learned=null;
      if(!alreadyKnown){
        learned=learnIngredientFromOnline(name,p);
        if(learned)learnedCount++;
      }
      rows.push(onlineIngredientRow(name,p,learned));
    }else{
      miss++;
      rows.push(`<div class="mjx-ingredient">
        <span class="mjx-dot gray"></span>
        <div>
          <strong>${esc2(name)}</strong>
          <div class="subtle">Точное совпадение в PubChem не найдено</div>
          <p class="subtle" style="margin:4px 0 0">Оставлен в серой зоне — возможно, это торговое/комплексное название или вариант записи INCI.</p>
        </div>
      </div>`);
    }

    list.innerHTML=rows.join('')||'<div class="empty">Состав не удалось разделить на компоненты.</div>';
    if(i<targets.length-1) await sleep(250);
  }

  if(targets.length){
    list.insertAdjacentHTML('afterbegin',`<div class="tag" style="margin-bottom:10px">✅ Найдено онлайн: ${found} · ⚪ Не найдено: ${miss} · Всего проверено: ${targets.length}${learnedCount?` · 🧠 Добавлено в офлайн-базу: ${learnedCount}`:''}</div>`);
    if(learnedCount){
      toast(`🧠 Офлайн-база пополнилась на ${learnedCount} компонент${learnedCount===1?'':'а(ов)'} ♡`);
      // Компоненты, которые раньше были "серыми", теперь распознаются локально —
      // пересчитываем результат разбора состава, чтобы это сразу отразилось.
      const refreshed=analyzeIngredients(document.getElementById('mjxInci')?.value||text);
      const resultBox=document.getElementById('mjxLabResult');
      if(resultBox)resultBox.innerHTML=renderLabResult(refreshed,false);
    }
  }else{
    list.innerHTML='<div class="empty">Не удалось найти отдельные компоненты в составе. Проверь разделители между ингредиентами.</div>';
  }
}
async function fetchJsonWithTimeout(url,ms=10000){try{const controller=new AbortController();const timer=setTimeout(()=>controller.abort(),ms);const response=await fetch(url,{signal:controller.signal,headers:{'Accept':'application/json'}});clearTimeout(timer);if(!response.ok)return null;return await response.json()}catch{return null}}
function normalizeOnlineName(name){return String(name||'').replace(/\s+/g,' ').trim().replace(/^\(|\)$/g,'')}
function prettyCosIngFunctions(v){return String(v||'').split(',').map(x=>x.trim()).filter(Boolean).map(x=>x.toLowerCase().replace(/(^|[ -])([a-z])/g,(_,a,b)=>a+b.toUpperCase())).join(', ')}
async function lookupCosIng(name){
  const q=encodeURIComponent(normalizeOnlineName(name));
  const j=await fetchJsonWithTimeout('https://api.bdapi.app/api/public/cosing/search?q='+q+'&limit=8&regulated_only=false',10000);
  const rows=Array.isArray(j?.rows)?j.rows:[];
  if(!rows.length)return null;
  const n=normalizeOnlineName(name).toLowerCase();
  const r=rows.find(x=>String(x.inci_name||'').toLowerCase()===n)||rows[0];
  return {inci:r.inci_name||name,cas:r.cas_no||'',ec:r.ec_no||'',functions:Array.isArray(r.function_names)?r.function_names.join(', '):(r.function||''),restriction:r.cosmetic_restriction||'',source:'EU CosIng'}
}
async function lookupPubChem(name){const q=encodeURIComponent(normalizeOnlineName(name));const j=await fetchJsonWithTimeout('https://pubchem.ncbi.nlm.nih.gov/rest/pug/compound/name/'+q+'/property/MolecularFormula,MolecularWeight,IUPACName,CID/JSON',10000);return j?.PropertyTable?.Properties?.[0]||null}
async function lookupPubChemAnnotations(p){if(!p?.CID)return null;const j=await fetchJsonWithTimeout('https://pubchem.ncbi.nlm.nih.gov/rest/pug_view/data/compound/'+encodeURIComponent(p.CID)+'/JSON',12000);const out=[];const walk=a=>{if(!Array.isArray(a))return;for(const x of a){if(x?.TOCHeading&&/description|use|pharmacology|chemical and physical properties|cosmetic/i.test(String(x.TOCHeading))){for(const i of (x.Information||[])){for(const v of (i.Value?.StringWithMarkup||[])){if(v.String)out.push(v.String)}}}walk(x?.Section)}};walk(j?.Record?.Section);return out.filter(Boolean).slice(0,4).join(' ').slice(0,1200)||null}
async function lookupDuckWeb(name){
  const q=encodeURIComponent('"'+normalizeOnlineName(name)+'" cosmetic ingredient function INCI');
  const j=await fetchJsonWithTimeout('https://api.duckduckgo.com/?q='+q+'&format=json&no_html=1&skip_disambig=1',10000);
  const topics=[];
  const walk=a=>{if(!Array.isArray(a))return;for(const x of a){if(x?.Text)topics.push(x.Text);walk(x?.Topics)}};
  walk(j?.RelatedTopics);
  const text=[j?.AbstractText,...topics].filter(Boolean).slice(0,4).join(' ');
  return text?{text:text.slice(0,1400),source:'Интернет-поиск'}:null;
}
async function lookupWikidata(name){
  const q=encodeURIComponent(normalizeOnlineName(name));
  const j=await fetchJsonWithTimeout('https://www.wikidata.org/w/api.php?action=wbsearchentities&search='+q+'&language=en&uselang=en&format=json&origin=*',9000);
  const hit=j?.search?.[0];
  return hit?{label:hit.label||'',description:hit.description||'',url:hit.concepturi||'',source:'Wikidata'}:null;
}
async function lookupIngredientDataSilent(name){
  const [pub,cos,web,wiki]=await Promise.all([lookupPubChem(name),lookupCosIng(name),lookupDuckWeb(name),lookupWikidata(name)]);
  if(!pub&&!cos&&!web&&!wiki)return null;
  const annotation=pub?.CID?await lookupPubChemAnnotations(pub):null;
  return {pub,cos,web,wiki,annotation};
}
function onlineFunctionText(r){
  if(r?.cos?.functions)return prettyCosIngFunctions(r.cos.functions);
  const t=String(r?.web?.text||'');
  const m=t.match(/(?:function|functions|used as|acts as|role|ingredient function)[^.;]{0,220}/i);
  if(m)return m[0].replace(/^.*?(function|functions|used as|acts as|role|ingredient function)[:\s-]*/i,'').trim();
  return 'Точная косметическая функция не подтверждена CosIng.';
}
function onlineIngredientRow(name,r,learned){
  const c=r?.cos,p=r?.pub,sourceList=[c?'EU CosIng':'',p?'PubChem':'',r?.web?'Интернет':'',r?.wiki?'Wikidata':''].filter(Boolean),source=sourceList.join(' + '),meta=[c?.cas?'CAS '+c.cas:'',c?.ec?'EC '+c.ec:'',p?.MolecularFormula?'формула '+p.MolecularFormula:'',p?.MolecularWeight?String(p.MolecularWeight)+' г/моль':''].filter(Boolean).join(' · '),restriction=c?.restriction?`<div class="tag" style="margin-top:6px">⚠️ Ограничение CosIng: ${esc2(c.restriction)}</div>`:'',desc=r?.annotation?`<p class="subtle" style="margin:6px 0 0"><strong>Что известно:</strong> ${esc2(r.annotation)}</p>`:'',web=r?.web?.text?`<p class="subtle" style="margin:6px 0 0"><strong>Из интернета:</strong> ${esc2(r.web.text)}</p>`:'',wiki=r?.wiki?.description?`<p class="subtle" style="margin:6px 0 0"><strong>Справка:</strong> ${esc2(r.wiki.description)}</p>`:'';
  const reliability = sourceList.length>=2
    ? `<span class="tag" style="background:color-mix(in srgb, var(--success) 22%, var(--surface2))">✅ подтверждено ${sourceList.length} источниками</span>`
    : `<span class="tag" style="background:color-mix(in srgb, var(--danger) 16%, var(--surface2))">⚠️ только 1 источник — уточни отдельно</span>`;
  const hairFace = learned ? getHairFaceFunctions(learned) : null;
  const hairFaceBlock = hairFace ? `<div class="grid grid-2" style="margin-top:8px;gap:8px"><div class="item" style="padding:8px 10px"><strong style="font-size:12px">💇 Для волос</strong><p class="subtle" style="margin:3px 0 0">${esc2(hairFace.hair.join(', '))}</p></div><div class="item" style="padding:8px 10px"><strong style="font-size:12px">🧴 Для лица</strong><p class="subtle" style="margin:3px 0 0">${esc2(hairFace.face.join(', '))}</p></div></div>` : '';
  const learnedBadge = learned?'<span class="tag" style="margin-top:6px">🧠 Сохранено в твоей офлайн-базе — в следующий раз распознается без интернета</span>':'';
  return `<div class="mjx-ingredient"><span class="mjx-dot ${learned?learned.status:'green'}"></span><div style="min-width:0;flex:1"><div class="row between wrap"><strong>${esc2(name)}</strong><span class="tag">${esc2(source)}</span></div><div class="row wrap" style="margin-top:4px;gap:6px">${reliability}</div><div class="subtle" style="margin-top:4px">${esc2(meta||'Онлайн-данные найдены')}</div><p class="subtle" style="margin:5px 0 0"><strong>Для чего компонент:</strong> ${esc2(onlineFunctionText(r))}</p>${hairFaceBlock}${restriction}${desc}${web}${wiki}<div style="margin-top:6px">${learnedBadge}</div></div></div>`
}
function doLab(text){const r=analyzeIngredients(text);data.mjx.lab.lastQuery=text;save2();document.getElementById('mjxLabResult').innerHTML=renderLabResult(r,false);}
function compareProducts(){const a=data.products.find(p=>p.id===document.getElementById('mjxCompareA')?.value),b=data.products.find(p=>p.id===document.getElementById('mjxCompareB')?.value);const box=document.getElementById('mjxCompareResult');if(!a||!b){box.innerHTML='<div class="empty">Выбери два продукта с сохранённым составом.</div>';return}const ra=analyzeIngredients(a.ingredients||a.composition||''),rb=analyzeIngredients(b.ingredients||b.composition||'');const sa=new Set(ra.found.map(x=>x.name)),sb=new Set(rb.found.map(x=>x.name));const same=[...sa].filter(x=>sb.has(x));const onlyA=[...sa].filter(x=>!sb.has(x));const onlyB=[...sb].filter(x=>!sa.has(x));box.innerHTML=`<div class="grid mjx-grid-3"><div class="item"><strong>Совпадают</strong><p>${same.join(', ')||'Нет распознанных совпадений'}</p></div><div class="item"><strong>${esc2(a.name)}</strong><p>${onlyA.join(', ')||'—'}</p></div><div class="item"><strong>${esc2(b.name)}</strong><p>${onlyB.join(', ')||'—'}</p></div></div>`}

function pluralRu(n,one,few,many){const num=Math.abs(Number(n))%100;const n1=num%10;if(num>10&&num<20)return many;if(n1>1&&n1<5)return few;if(n1===1)return one;return many}
function hairGrowthPage(){
  ensure();
  const h=data.mjx.hair||{goal:60,baseLength:0,entries:[]};
  const entries=[...(h.entries||[])].filter(x=>x && x.date && Number.isFinite(Number(x.length))).sort((a,b)=>a.date.localeCompare(b.date));
  const first=entries[0]?.length!=null?Number(entries[0].length):Number(h.baseLength||0);
  const last=entries.length?Number(entries[entries.length-1].length):first;
  const goal=Math.max(Number(h.goal||60), first||1);
  const totalGrowth=Math.max(0,last-first);
  const targetGrowth=Math.max(0,goal-first);
  const goalPct=targetGrowth?clamp(totalGrowth/targetGrowth*100):0;
  const startDate=entries[0]?.date||null;
  const endDate=entries.at(-1)?.date||null;
  const periodDays=startDate&&endDate?Math.max(1,Math.round((dateObj(endDate)-dateObj(startDate))/86400000)):0;
  const avgPerMonth=periodDays?totalGrowth/(periodDays/30.44):0;
  const avgPerMonthText=avgPerMonth?avgPerMonth.toFixed(2):'—';
  const deltaLabel=entries.length>1?`+${totalGrowth.toFixed(1)} см за ${periodDays} ${pluralRu(periodDays,'день','дня','дней')}`:'Добавь второе измерение, чтобы увидеть прирост за период';
  const achievementsText=entries.length>=2 ? `За выбранный период длина изменилась на ${totalGrowth.toFixed(1)} см.` : 'Пока есть только одна точка. Второе измерение позволит увидеть реальную динамику.';
  return `<div class="mjx-shell">
    <section class="mjx-hg-hero">
      <div class="mjx-hg-hero-main">
        <div class="mjx-hg-kicker">Личный бьюти-трекер</div>
        <div class="mjx-hg-title">Рост волос ♡</div>
        <p class="mjx-hg-sub">Записывай длину по датам, наблюдай реальный прирост, ставь цель и собирай свою красивую историю сантиметр за сантиметром.</p>
        <div class="row wrap" style="gap:10px;margin-top:18px">
          <button class="btn" id="mjxAddHairMeasure">＋ Добавить измерение</button>
          <button class="btn secondary" id="mjxSetHairGoal">🎯 Цель по длине</button>
        </div>
      </div>
      <div class="card" style="display:grid;place-items:center;min-height:250px">
        <div class="mjx-hg-ring" style="--p:${goalPct}"><div class="inside"><strong>${last.toFixed(1)} см</strong><span>из ${goal.toFixed(1)} см</span></div></div>
      </div>
    </section>

    <div class="mjx-hg-stats">
      <div class="mjx-hg-stat"><div class="n">${last.toFixed(1)} см</div><div class="l">Текущая длина</div></div>
      <div class="mjx-hg-stat"><div class="n">+${totalGrowth.toFixed(1)} см</div><div class="l">Всего отросло</div></div>
      <div class="mjx-hg-stat"><div class="n">${avgPerMonthText}${avgPerMonth?' см':''}</div><div class="l">Средний темп в месяц</div></div>
      <div class="mjx-hg-stat"><div class="n">${Math.max(0,goal-last).toFixed(1)} см</div><div class="l">Осталось до цели</div></div>
    </div>

    <section class="card">
      <div class="row between wrap">
        <div><h3 class="section-title" style="margin-bottom:4px">📈 Динамика длины</h3><p class="subtle" style="margin:0">${esc2(deltaLabel)}</p></div>
        <div class="mjx-hg-period">
          <button class="btn secondary small active" data-hg-period="all">Весь период</button>
          <button class="btn secondary small" data-hg-period="30">30 дней</button>
          <button class="btn secondary small" data-hg-period="90">90 дней</button>
          <button class="btn secondary small" data-hg-period="180">6 месяцев</button>
        </div>
      </div>
      <div id="mjxHairChartWrap" style="margin-top:14px">${hairChartPro(entries,'all')}</div>
    </section>

    <section class="mjx-hg-insight">
      <div class="quote"><strong>✨ Что говорит твоя история</strong><div style="margin-top:8px">${esc2(achievementsText)}</div></div>
      <div class="mjx-hg-note"><div class="label">🎯 Твоя цель</div><h3 style="margin:4px 0">${goal.toFixed(1)} см</h3><p class="subtle">Прогресс: ${goalPct.toFixed(0)}%</p><div class="progress"><i style="width:${goalPct}%"></i></div></div>
    </section>

    <section class="card">
      <div class="row between wrap"><div><h3 class="section-title" style="margin-bottom:4px">🪞 Путь от первой записи</h3><p class="subtle" style="margin:0">Каждая точка — отдельный этап твоего роста.</p></div><span class="tag">${entries.length} ${pluralRu(entries.length,'измерение','измерения','измерений')}</span></div>
      ${entries.length?`<div class="mjx-hg-timeline">${entries.map((e,i)=>{const prev=i?Number(entries[i-1].length):Number(e.length);const diff=Number(e.length)-prev;return `<div class="mjx-hg-node"><span class="mjx-hg-dot"></span><strong>${esc2(fmtDate(e.date))}</strong><div class="subtle" style="margin-top:5px">${Number(e.length).toFixed(1)} см${i?` · ${diff>=0?'+':''}${diff.toFixed(1)} см`:''}</div><div class="subtle" style="margin-top:4px">${esc2(e.note||'Без заметки')}</div><button class="btn secondary small" style="margin-top:8px" data-hg-delete="${esc(e.date)}">Удалить</button></div>`}).join('')}</div>`:`<div class="mjx-hg-empty"><div style="font-size:40px">🎀</div><h3>Начни свою историю роста</h3><p>Добавь первое измерение длины — потом появятся график, прогресс и красивые выводы.</p><button class="btn" id="mjxAddHairMeasureEmpty">＋ Первое измерение</button></div>`}
    </section>

    <section class="card">
      <h3 class="section-title">➕ Новое измерение</h3>
      <form id="mjxHairForm" class="form" autocomplete="off"><div class="mjx-measure"><div class="field"><label>Дата</label><input type="date" name="date" value="${todayKey()}" required></div><div class="field"><label>Длина, см</label><input type="number" step="0.1" min="0" name="length" required placeholder="45.5"></div><div class="field"><label>Заметка</label><input name="note" maxlength="140" placeholder="Например: после стрижки"></div><button class="btn" type="submit">Сохранить ♡</button></div></form>
    </section>
  </div>`;
}

function hairChartPro(entries,period){
  const now=new Date();
  let list=entries;
  if(period!=='all'){
    const days=Number(period)||0; const cutoff=new Date(now); cutoff.setDate(cutoff.getDate()-days); list=entries.filter(e=>dateObj(e.date)>=cutoff);
    if(list.length<2 && entries.length>=2) list=entries.slice(-2);
  }
  if(list.length<2) return '<div class="mjx-hg-empty"><div style="font-size:36px">📈</div><h3>Нужно минимум два измерения</h3><p>Добавь ещё одну дату — и здесь появится линия твоего роста.</p></div>';
  const vals=list.map(e=>Number(e.length)); const min=Math.min(...vals)-1,max=Math.max(...vals)+1; const W=980,H=290,P=46;
  const points=list.map((e,i)=>{const x=P+i*(W-2*P)/(list.length-1);const y=H-P-(Number(e.length)-min)/(max-min)*(H-2*P);return{x,y,e}});
  const poly=points.map(p=>`${p.x},${p.y}`).join(' '); const area=`${P},${H-P} ${poly} ${W-P},${H-P}`;
  const yMarks=[0,.5,1].map(t=>{const y=P+t*(H-2*P);const v=max-t*(max-min);return `<line x1="${P}" y1="${y}" x2="${W-P}" y2="${y}" stroke="currentColor" opacity=".08"/><text x="8" y="${y+4}" fill="currentColor" opacity=".5" font-size="12">${v.toFixed(1)}</text>`}).join('');
  return `<div class="mjx-hg-chart"><svg viewBox="0 0 ${W} ${H}" preserveAspectRatio="none"><defs><linearGradient id="hairArea" x1="0" x2="0" y1="0" y2="1"><stop offset="0" stop-color="var(--primary)" stop-opacity=".22"/><stop offset="1" stop-color="var(--primary)" stop-opacity="0"/></linearGradient></defs>${yMarks}<polygon points="${area}" fill="url(#hairArea)"/><polyline points="${poly}" fill="none" stroke="var(--primary)" stroke-width="6" stroke-linecap="round" stroke-linejoin="round"/>${points.map((p,i)=>`<circle cx="${p.x}" cy="${p.y}" r="7" fill="var(--surface)" stroke="var(--primary)" stroke-width="3"><title>${p.e.date} · ${Number(p.e.length).toFixed(1)} см</title></circle>`).join('')}</svg></div>`;
}

function openHairGoal(){modal(`<h3>Цель по длине ♡</h3><form id="mjxGoalHairForm" class="form"><div class="field"><label>Желаемая длина, см</label><input type="number" step="0.1" min="1" name="goal" value="${data.mjx.hair.goal}"></div><div class="modal-actions"><button type="button" class="btn secondary" id="cancelModal">Отмена</button><button class="btn">Сохранить цель</button></div></form>`);document.getElementById('cancelModal').onclick=closeModal;document.getElementById('mjxGoalHairForm').onsubmit=e=>{e.preventDefault();const f=new FormData(e.target);data.mjx.hair.goal=Number(f.get('goal'))||data.mjx.hair.goal;save2();closeModal();render()}}

function openMore2(){const sidebarButtons=[...document.querySelectorAll('.sidebar .nav button[data-route]')];const routes=sidebarButtons.map(b=>[b.dataset.route,b.querySelector('span')?.textContent?.trim()||'•',[...b.childNodes].filter(n=>n.nodeType===Node.TEXT_NODE).map(n=>n.textContent).join('').trim()||b.textContent.replace(b.querySelector('span')?.textContent||'','').replace('⋮⋮','').trim()]);const sheet=document.createElement('div');sheet.className='mjx-quick-sheet';sheet.innerHTML=`<div class="mjx-quick-panel"><div class="row between"><h3 class="section-title">Меню ♡</h3><button class="icon-btn" id="mjxCloseMore">×</button></div><div class="mjx-quick-grid">${routes.map(x=>`<button data-mjx-nav="${x[0]}"><strong>${x[1]} ${x[2]}</strong><div class="subtle">Открыть раздел</div></button>`).join('')}</div></div>`;document.body.appendChild(sheet);sheet.onclick=e=>{if(e.target===sheet){sheet.remove();return}const b=e.target.closest('[data-mjx-nav]');if(b){sheet.remove();location.hash=b.dataset.mjxNav}};document.getElementById('mjxCloseMore').onclick=()=>sheet.remove()}

function overrideNavigation(){const oldShell=renderShell;renderShell=function(route){oldShell(route);const nav=document.querySelector('.sidebar .nav');if(nav){const extra=[['academy','📚','Бьюти-академия'],['lab','🧪','Лаборатория состава'],['hair-growth','📏','Рост волос'],['collections','🛍️','Коллекции'],['mystery','🎁','Бьюти-коробка'],['seasons','🌷','Сезоны']];extra.forEach(([id,ic,l])=>{if(!nav.querySelector(`[data-route="${id}"]`))nav.insertAdjacentHTML('beforeend',`<button data-route="${id}" data-sidebar-id="${id}"><span>${ic}</span>${l}<span class="nav-drag-handle" aria-hidden="true">⋮⋮</span></button>`)});nav.querySelectorAll('[data-route]').forEach(b=>{b.onclick=()=>location.hash=b.dataset.route});if(typeof bindSidebarDnD==='function')bindSidebarDnD()}};window.openMore=openMore2;
 const oldPage=renderPage;renderPage=function(route){if(route==='academy'){document.getElementById('page').innerHTML=academyPage();bindMpx(route);return}if(route==='lab'){document.getElementById('page').innerHTML=labPage();bindMpx(route);return}if(route==='hair-growth'){document.getElementById('page').innerHTML=hairGrowthPage();bindMpx(route);return}if(route==='collections'){document.getElementById('page').innerHTML=collectionPage();bindMpx(route);return}if(route==='mystery'){document.getElementById('page').innerHTML=mysteryPage();bindMpx(route);return}if(route==='seasons'){document.getElementById('page').innerHTML=seasonsPage();bindMpx(route);return}if(route==='shop'){document.getElementById('page').innerHTML=shopPage2();bindMpx(route);return}oldPage(route)};
 const oldBind=bindPage;bindPage=function(route){oldBind(route);bindMpx(route)};
}
function bindMpx(route){
 document.querySelectorAll('[data-mjx-buy]').forEach(b=>b.onclick=()=>{const id=b.dataset.mjxBuy;typeof buyShop==='function'?buyShop(id):null;render()});
 document.querySelectorAll('[data-shop-day]').forEach(b=>b.onclick=()=>{const item=SHOP_CATALOG.find(x=>x.id===b.dataset.shopDay);if(!item)return;const price=Math.max(0,Math.floor(item.cost*.75));if(data.shop.owned.includes(item.id)){toast('Этот предмет уже у тебя ♡');return}if(data.xp<price){toast(`Не хватает ${price-data.xp} XP ♡`);return}data.xp-=price;data.shop.owned.push(item.id);save2();toast(`Получено: ${item.title} ✨`);render()});
 document.querySelectorAll('[data-mjx-filter]').forEach(b=>b.onclick=()=>{document.querySelectorAll('[data-mjx-filter]').forEach(x=>x.classList.remove('active'));b.classList.add('active');const f=b.dataset.mjxFilter;document.querySelectorAll('#mjxShopGrid [data-mjx-shop-item]').forEach(card=>{const ok=f==='all'||(f==='rare'&&['Редкий','Эпический','Легендарный','Секретный'].includes(card.dataset.rarity))||card.dataset.type===f|| (f==='furniture'&&card.dataset.type==='furniture');card.style.display=ok?'':'none'})});
 if(route==='mystery')document.getElementById('mjxOpenBox')?.addEventListener('click',openMystery);
 if(route==='academy'){document.getElementById('mjxRefreshAcademy')?.addEventListener('click',()=>refreshAcademy(true));document.querySelectorAll('[data-mjx-lesson]').forEach(b=>b.onclick=()=>openLesson(Number(b.dataset.mjxLesson)));setTimeout(()=>refreshAcademy(false),0)}
 if(route==='lab'){document.getElementById('mjxLabForm')?.addEventListener('submit',e=>{e.preventDefault();doLab(document.getElementById('mjxInci').value)});document.getElementById('mjxOnlyProblem')?.addEventListener('click',()=>{const text=document.getElementById('mjxInci').value;const r=analyzeIngredients(text);document.getElementById('mjxLabResult').innerHTML=renderLabResult(r,true)});document.getElementById('mjxCheckOnline')?.addEventListener('click',()=>checkLabOnline());document.getElementById('mjxInternetIngredient')?.addEventListener('click',async()=>{
  const text=document.getElementById('mjxInci')?.value?.trim()||'';
  if(!text){toast('Сначала вставь состав ♡');return}
  const r=analyzeIngredients(text);
  const unknown=[...new Set((r.unknown||[]).map(x=>String(x).trim()).filter(Boolean))];
  if(!unknown.length){toast('Все компоненты уже распознаны локальной базой ♡');return}
  const box=document.getElementById('mjxLabOnline');
  if(box)box.innerHTML=`<section class="card" style="margin-top:16px"><div class="row between wrap"><div><h3 class="section-title">🌐 Нераспознанные компоненты</h3><p class="subtle">Проверяю каждый компонент в EU CosIng и PubChem, а затем подтягиваю найденную косметическую функцию и справочные сведения.</p></div><span class="tag">${unknown.length} к проверке</span></div><div class="list" id="mjxOnlineList"><div class="empty">Проверяю ${unknown.length} компонентов…</div></div></section>`;
  const list=document.getElementById('mjxOnlineList');
  let found=0,miss=0,learnedCount=0; const rows=[];
  for(let i=0;i<unknown.length;i++){
    const name=unknown[i], p=await lookupIngredientDataSilent(name);
    if(p){
      found++;
      const learned=learnIngredientFromOnline(name,p);
      if(learned)learnedCount++;
      rows.push(onlineIngredientRow(name,p,learned));
    }else{
      miss++;
      rows.push(`<div class="mjx-ingredient"><span class="mjx-dot gray"></span><div><strong>${esc2(name)}</strong><div class="subtle">Точное совпадение в PubChem не найдено</div><p class="subtle" style="margin:4px 0 0">Возможно, это торговое/комплексное название или вариант записи INCI.</p></div></div>`);
    }
    if(list)list.innerHTML=rows.join('');
    if(i<unknown.length-1)await sleep(250);
  }
  if(list)list.insertAdjacentHTML('afterbegin',`<div class="tag" style="margin-bottom:10px">✅ Найдено онлайн: ${found} · ⚪ Не найдено: ${miss} · Всего проверено: ${unknown.length}${learnedCount?` · 🧠 Добавлено в офлайн-базу: ${learnedCount}`:''}</div>`);
  if(learnedCount){
    toast(`🧠 Офлайн-база пополнилась на ${learnedCount} компонент${learnedCount===1?'':'а(ов)'} ♡`);
    const refreshed=analyzeIngredients(text);
    const resultBox=document.getElementById('mjxLabResult');
    if(resultBox)resultBox.innerHTML=renderLabResult(refreshed,false);
  }
});document.getElementById('mjxCompareBtn')?.addEventListener('click',compareProducts);document.getElementById('mjxResetLearned')?.addEventListener('click',()=>{if(!confirm('Удалить все компоненты, добавленные в офлайн-базу из интернета? Основная база ARAVIA/INCI не пострадает.'))return;for(const key of Object.keys(data.mjx.learnedInci||{})){if(INCI[key]?.learned)delete INCI[key];}data.mjx.learnedInci={};save2();toast('Офлайн-пополнения очищены ♡');render()})}
 if(route==='hair-growth'){
   const addMeasure=()=>{document.getElementById('mjxHairForm')?.querySelector('input[name="length"]')?.focus()};
   document.getElementById('mjxAddHairMeasure')?.addEventListener('click',addMeasure);
   document.getElementById('mjxAddHairMeasureEmpty')?.addEventListener('click',addMeasure);
   document.getElementById('mjxSetHairGoal')?.addEventListener('click',openHairGoal);
   document.querySelectorAll('[data-hg-period]').forEach(b=>b.addEventListener('click',()=>{document.querySelectorAll('[data-hg-period]').forEach(x=>x.classList.remove('active'));b.classList.add('active');const w=document.getElementById('mjxHairChartWrap');if(w)w.innerHTML=hairChartPro([...data.mjx.hair.entries].sort((a,b)=>a.date.localeCompare(b.date)),b.dataset.hgPeriod)}));
   document.getElementById('mjxHairForm')?.addEventListener('submit',e=>{e.preventDefault();const f=new FormData(e.target);const date=String(f.get('date')||'');const length=Number(f.get('length'));if(!date||!Number.isFinite(length)||length<0){toast('Проверь дату и длину ♡');return}data.mjx.hair=data.mjx.hair||{goal:60,baseLength:0,entries:[]};data.mjx.hair.entries=data.mjx.hair.entries||[];const idx=data.mjx.hair.entries.findIndex(x=>x.date===date);const row={date,length,note:String(f.get('note')||'')};if(idx>=0)data.mjx.hair.entries[idx]=row;else data.mjx.hair.entries.push(row);data.mjx.hair.entries.sort((a,b)=>a.date.localeCompare(b.date));if(!data.mjx.hair.baseLength)data.mjx.hair.baseLength=length;save2();toast(idx>=0?'Измерение обновлено ♡':'Измерение сохранено ♡');render()});
   document.querySelectorAll('[data-hg-delete]').forEach(b=>b.addEventListener('click',()=>{const d=b.dataset.hgDelete;if(!confirm('Удалить это измерение?'))return;data.mjx.hair.entries=data.mjx.hair.entries.filter(x=>x.date!==d);save2();toast('Измерение удалено');render()}));
 }
}
function seasonsPage(){const s=currentSeason();return `<div class="mjx-shell"><section class="mjx-season-banner"><div class="label">Текущий сезон</div><h1 style="font-family:Georgia,serif;margin:6px 0">${s.icon} ${esc2(s.title)}</h1><p>${esc2(s.desc)}</p></section><div class="mjx-grid mjx-grid-3">${seasons.slice(0,12).map(x=>`<article class="card"><div style="font-size:42px">${x.icon}</div><h3 style="margin:8px 0">${esc2(x.title)}</h3><p class="subtle">${esc2(x.desc)}</p></article>`).join('')}</div><section class="card"><h3 class="section-title">Как сезоны меняют твой мир</h3><p class="subtle">Сезонный баннер влияет на атмосферу магазина, подбор предметов и советы. Данные локальные; приложение не требует регистрации.</p></section></div>`}

overrideNavigation();

// Единые надёжные обработчики критичных действий. Capture + stopImmediatePropagation
// не позволяет старым слоям повторно вызвать действие после перерисовки.
if(!window.__mjCriticalClicksBound){
  window.__mjCriticalClicksBound=true;
  document.addEventListener('click', function(ev){
    const el=ev.target.closest?.('[data-add-product], [data-action=\"addProduct\"], [data-pet-feed], [data-pet-play], [data-pet-rest]');
    if(!el)return;
    ev.preventDefault();
    ev.stopImmediatePropagation();
    if(el.matches('[data-add-product]') || el.matches('[data-action=\"addProduct\"]')){ productModal(); return; }
    if(el.matches('[data-pet-feed]')){ petFeed(); return; }
    if(el.matches('[data-pet-play]')){ petPlay(); return; }
    if(el.matches('[data-pet-rest]')){ petRest(); return; }
  }, true);
}

// Init once after the stable app has loaded.
setTimeout(()=>{try{ensure();render()}catch(e){console.error('MJX init',e)}},0);
window.renderSmartBeautyPlan=renderSmartBeautyPlan;window.renderAfterEventPanel=renderAfterEventPanel;window.ensureEventState=ensureEventState;window.saveAfterEventState=saveAfterEventState;
})();


// Обновлённая форма средства с сохранением состава для Лаборатории.
(function(){
  productModal = function(id){
    const p=id?data.products.find(x=>x.id===id):{id:'',name:'',brand:'',category:'',notes:'',image:'',ingredients:''};
    modal(`<h3>${id?'Изменить':'Добавить'} средство</h3><form id="productForm" data-product-id="${esc(p.id||'')}" class="form"><div class="grid grid-2"><div class="field"><label>Название</label><input name="name" required value="${esc(p.name)}"></div><div class="field"><label>Бренд</label><input name="brand" value="${esc(p.brand)}"></div></div><div class="field"><label>Категория</label><input name="category" value="${esc(p.category)}" placeholder="Сыворотка, крем…"></div><div class="field"><label>Состав</label><textarea name="ingredients" placeholder="Aqua, Glycerin, Niacinamide, Panthenol…">${esc(p.ingredients||p.composition||'')}</textarea></div><div class="field"><label>Мои заметки</label><textarea name="notes">${esc(p.notes||'')}</textarea></div><div class="field"><label>Фото</label><input name="image" type="file" accept="image/*"></div><div class="modal-actions"><button type="button" class="btn secondary" id="cancelModal">Отмена</button><button class="btn">Сохранить</button></div></form>`);
    document.getElementById('cancelModal').onclick=closeModal;
    document.getElementById('productForm').onsubmit=async e=>{e.preventDefault();const f=new FormData(e.target);let image=p.image||'';const file=f.get('image');if(file?.size)image=await fileToDataURL(file);const np={id:p.id||uid(),name:f.get('name').trim(),brand:f.get('brand').trim(),category:f.get('category').trim(),notes:f.get('notes'),ingredients:f.get('ingredients').trim(),image,used:p.used||0};if(id){const i=data.products.findIndex(x=>x.id===id);data.products[i]=np}else data.products.push(np);save();closeModal();render();toast('Средство сохранено ♡')};
  };
})();



// Финальная защита сохранения средства. Этот обработчик работает в capture-фазе
// и не зависит от того, какая из старых версий модального окна была открыта.
if(!window.__mjProductSaveGuard){
  window.__mjProductSaveGuard=true;
  document.addEventListener('submit', async function(ev){
    const form=ev.target;
    if(!form || form.id!=='productForm') return;
    ev.preventDefault();
    ev.stopImmediatePropagation();
    try{
      const f=new FormData(form);
      const name=String(f.get('name')||'').trim();
      if(!name){toast('Напиши название средства ♡');return;}
      const id=String(form.dataset.productId||'');
      const old=id?data.products.find(x=>x.id===id):null;
      let image=old?.image||'';
      const file=f.get('image');
      if(file&&file.size&&typeof fileToDataURL==='function') image=await fileToDataURL(file);
      const product={id:id||uid(),name,brand:String(f.get('brand')||'').trim(),category:String(f.get('category')||'').trim(),notes:String(f.get('notes')||''),ingredients:String(f.get('ingredients')||'').trim(),image,used:Number(old?.used||0),rating:Number(f.get('score')||old?.rating||0)};
      const idx=data.products.findIndex(x=>x.id===product.id);
      if(idx>=0)data.products[idx]=product;else data.products.push(product);
      if(!Array.isArray(data.favoriteProducts))data.favoriteProducts=[];
      if(f.get('favorite')==='on'&&!data.favoriteProducts.includes(product.id))data.favoriteProducts.push(product.id);
      save();closeModal();render();toast('Средство сохранено ♡');
    }catch(err){console.error(err);toast('Не удалось сохранить средство ♡');}
  },true);
}

// Защита от дублирующихся уведомлений: одно и то же сообщение не показывается дважды подряд.
if(!window.__mjToastDedup){
  window.__mjToastDedup=true;
  const __mjOriginalToast=toast;
  let __mjLastToastText='', __mjLastToastTime=0;
  toast=function(message){
    const text=String(message||''); const now=Date.now();
    if(text===__mjLastToastText && now-__mjLastToastTime<900) return;
    __mjLastToastText=text; __mjLastToastTime=now;
    return __mjOriginalToast(message);
  };
}
if(data.pet){data.pet.kind='котёнок';data.pet.type='cat';data.pet.icon='🐱';}

// Надёжное удаление этапа ухода: единственная точка входа для кнопки «Удалить».
window.__MJ_DELETE_ROUTINE__ = function(id){
  try{
    const rid=String(id||'').trim();
    if(!rid){ toast('Не удалось определить этап ухода.'); return false; }
    if(!Array.isArray(data.routines)){ data.routines=[]; }
    const idx=data.routines.findIndex(r=>String(r?.id||'')===rid);
    if(idx<0){ toast('Этап ухода уже отсутствует.'); return false; }
    if(!window.confirm('Удалить этот этап ухода?')) return false;

    // Удаляем сам этап и его записи выполнения безопасно.
    data.routines.splice(idx,1);
    if(data.logs && typeof data.logs==='object' && !Array.isArray(data.logs)){
      for(const day of Object.keys(data.logs)){
        const arr=Array.isArray(data.logs[day])?data.logs[day]:[];
        data.logs[day]=arr.filter(x=>String(x?.routineId||'')!==rid);
      }
    }

    // Сохраняем ДО обновления интерфейса. Ошибка localStorage не должна убивать страницу.
    try{ save(); }catch(saveErr){ console.error('Не удалось сохранить удаление этапа:',saveErr); }

    // Сразу убираем строку из DOM, чтобы действие было видно даже если другой блок UI временно ошибся.
    const row=document.querySelector(`[data-routine-delete=\"${CSS.escape(rid)}\"]`)?.closest('.item');
    if(row) row.remove();

    // Безопасно обновляем остальные показатели. Ошибка перерисовки не должна всплыть в глобальный обработчик.
    try{ render(); }catch(renderErr){
      console.error('Ошибка обновления интерфейса после удаления этапа:',renderErr);
      try{ location.hash='care'; }catch{}
    }

    try{ toast('Этап ухода удалён ♡'); }catch{}
    return true;
  }catch(err){
    console.error('Ошибка удаления этапа ухода:',err);
    try{ toast('Не удалось удалить этап. Попробуй ещё раз ♡'); }catch{}
    return false;
  }
};

// --- СВОДНЫЙ ПАТЧ ИСПРАВЛЕНИЙ (ЛАБОРАТОРИЯ, АКАДЕМИЯ, БАЗА) ---

// 1. Сжатие фото перед сохранением (защита от белого экрана и переполнения памяти)
window.fileToDataURL = function(file) {
  return new Promise((res, rej) => {
    const r = new FileReader();
    r.onload = e => {
      const img = new Image();
      img.onload = () => {
        const canvas = document.createElement('canvas');
        const scale = img.width > 600 ? 600 / img.width : 1;
        canvas.width = img.width * scale;
        canvas.height = img.height * scale;
        const ctx = canvas.getContext('2d');
        ctx.drawImage(img, 0, 0, canvas.width, canvas.height);
        res(canvas.toDataURL('image/jpeg', 0.6));
      };
      img.onerror = rej;
      img.src = e.target.result;
    };
    r.onerror = rej;
    r.readAsDataURL(file);
  });
};

// 2. Блокировка спам-запросов погоды
let _isFetchingWeather = false;
window.fetchWeather = async function() {
  if(_isFetchingWeather) return;
  const city = String(data.settings?.city || '').trim();
  if(!city) { try{ toast('Укажи город в настройках ♡'); }catch{} return; }
  
  _isFetchingWeather = true;
  try {
    try{ toast('Ищу погоду… ☁️'); }catch{}
    const geo = await fetch(`https://geocoding-api.open-meteo.com/v1/search?name=${encodeURIComponent(city)}&count=1&language=ru&format=json`).then(r=>r.json());
    if(!geo.results?.[0]) throw Error('city');
    const g = geo.results[0];
    const w = await fetch(`https://api.open-meteo.com/v1/forecast?latitude=${g.latitude}&longitude=${g.longitude}&current=temperature_2m,relative_humidity_2m,weather_code,wind_speed_10m&timezone=auto`).then(r=>r.json());
    
    data.settings.weather = {
      city: g.name, temp: Math.round(w.current.temperature_2m),
      humidity: w.current.relative_humidity_2m, wind: Math.round(w.current.wind_speed_10m),
      code: w.current.weather_code, description: typeof weatherText==='function'?weatherText(w.current.weather_code):'', at: Date.now()
    };
    data.settings.lastWeatherAt = Date.now();
    data.weatherChecks = (data.weatherChecks||0)+1;
    
    if(typeof save==='function') save(); 
    try{ toast('Погода обновлена ♡'); }catch{} 
    if(typeof render==='function') render();
  } catch(e) {
    try{ toast('Не удалось получить погоду.'); }catch{}
  } finally {
    _isFetchingWeather = false;
  }
};

// 3. Защита от двойных списаний XP в магазине
const _origBuyShopV3 = window.buyShopV3;
let _lastBuyTime = 0;
window.buyShopV3 = function(id) {
    if (Date.now() - _lastBuyTime < 500) return;
    _lastBuyTime = Date.now();
    if (typeof _origBuyShopV3 === 'function') _origBuyShopV3(id);
};
const _origBuyShopV2 = window.buyShopV2;
window.buyShopV2 = function(id) {
    if (Date.now() - _lastBuyTime < 500) return;
    _lastBuyTime = Date.now();
    if (typeof _origBuyShopV2 === 'function') _origBuyShopV2(id);
};

// 4. ИНТЕРНЕТ-ПОИСК СОСТАВА ДЛЯ ЛАБОРАТОРИИ
const _origLabPage = window.labPage || (typeof labPage !== 'undefined' ? labPage : null);
if (_origLabPage && !window.__labPagePatched) {
  window.__labPagePatched = true;
  window.labPage = function() {
    let html = _origLabPage();
    const searchBox = `
      <div class="field" style="margin-bottom: 16px; padding: 14px; background: var(--surface2); border-radius: 18px; border: 1px solid var(--border);">
        <label style="color: var(--primary); font-weight: bold; font-size: 13px;">🔍 Найти средство в интернете</label>
        <div class="row wrap" style="margin-top: 8px;">
          <input id="mjxSearchProductName" placeholder="Бренд и название (англ), напр: Cerave cleanser" style="flex:1; min-width:200px;">
          <button type="button" class="btn" id="mjxFetchProductBtn">Найти состав</button>
        </div>
        <p class="subtle" style="margin-top:8px; font-size:11px;">База OpenBeautyFacts. Лучше искать международные продукты на английском языке.</p>
      </div>
    `;
    return html.replace('<div class="field"><label>Состав продукта', searchBox + '<div class="field"><label>Состав продукта');
  };
}

window.fetchProductComposition = async function(productName) {
    const chat = document.getElementById('mjxChat');
    const escFunc = typeof esc2 === 'function' ? esc2 : (typeof esc === 'function' ? esc : x => x);
    if (chat) {
        chat.insertAdjacentHTML('beforeend', `<div class="mjx-msg user">Ищу состав для: ${escFunc(productName)}</div>`);
        chat.scrollTop = chat.scrollHeight;
    }
    try {
        const url = `https://world.openbeautyfacts.org/cgi/search.pl?search_terms=${encodeURIComponent(productName)}&search_simple=1&action=process&json=1`;
        const response = await fetch(url);
        const json = await response.json();
        if (json.products && json.products.length > 0) {
            const product = json.products.find(p => p.ingredients_text) || json.products[0];
            if (product.ingredients_text) {
                if (chat) chat.insertAdjacentHTML('beforeend', `<div class="mjx-msg bot">Нашла средство: <strong>${escFunc(product.product_name || productName)}</strong>. Состав загружен в поле ниже и проанализирован! ♡</div>`);
                const inciBox = document.getElementById('mjxInci');
                if (inciBox) {
                    inciBox.value = product.ingredients_text;
                    if (typeof doLab === 'function') doLab(product.ingredients_text);
                }
            } else {
                if (chat) chat.insertAdjacentHTML('beforeend', `<div class="mjx-msg bot">Я нашла <strong>${escFunc(product.product_name || productName)}</strong> в базе, но, к сожалению, кто-то еще не добавил туда его полный состав 😔.</div>`);
            }
        } else {
            if (chat) chat.insertAdjacentHTML('beforeend', `<div class="mjx-msg bot">Увы, средство не найдено в базе. Попробуй ввести название чуть иначе или укажи только бренд.</div>`);
        }
    } catch (error) {
        if (chat) chat.insertAdjacentHTML('beforeend', `<div class="mjx-msg bot">Произошла ошибка при подключении к базе данных. Проверь интернет или попробуй позже.</div>`);
    }
    if(chat) chat.scrollTop = chat.scrollHeight;
};

const _origBindMpx = window.bindMpx || (typeof bindMpx !== 'undefined' ? bindMpx : null);
if (_origBindMpx && !window.__bindMpxPatched) {
  window.__bindMpxPatched = true;
  window.bindMpx = function(route) {
      _origBindMpx(route);
      if (route === 'lab') {
          const fetchBtn = document.getElementById('mjxFetchProductBtn');
          const searchInput = document.getElementById('mjxSearchProductName');
          if (fetchBtn && searchInput) {
              fetchBtn.onclick = () => {
                  const query = searchInput.value.trim();
                  if (!query) { try{ toast('Введи название средства ♡'); } catch{} return; }
                  window.fetchProductComposition(query);
              };
              searchInput.addEventListener('keypress', function (e) {
                  if (e.key === 'Enter') { e.preventDefault(); fetchBtn.click(); }
              });
          }
      }
  };
}

})();
</script>

<script id="smart-plan-events-delegation">
document.addEventListener('click',function(ev){
  const planBtn=ev.target.closest('[data-build-smart-plan]');
  if(planBtn){renderSmartBeautyPlan();planBtn.textContent='✓ План обновлён';setTimeout(()=>{if(planBtn.isConnected)planBtn.textContent='✨ Собрать мой день'},1400);return;}
  const go=ev.target.closest('[data-go-events]');
  if(go){const el=document.querySelector('[data-after-events]');if(el)el.scrollIntoView({behavior:'smooth',block:'start'});return;}
  const chk=ev.target.closest('[data-plan-check]');
  if(chk){const item=chk.closest('[data-plan-item]');if(item)item.classList.toggle('done');return;}
  const eventBtn=ev.target.closest('[data-event-toggle]');
  if(eventBtn){const st=window.ensureEventState?.(),key=eventBtn.dataset.eventToggle,i=st.selected.indexOf(key);if(i>=0)st.selected.splice(i,1);else st.selected.push(key);window.saveAfterEventState?.();window.renderAfterEventPanel?.();window.renderSmartBeautyPlan?.();}
});
</script>
<script id="after-event-real-runtime">
(function(){
  function isAfter(){ return (location.hash||'').replace(/^#/,'') === 'after-event'; }
  function bindEvents(){
    if(!isAfter()) return;
    var root=document.querySelector('[data-after-events]');
    if(!root || typeof ensureEventState!=='function') return;
    root.querySelectorAll('[data-event-toggle]').forEach(function(btn){
      btn.onclick=function(ev){
        ev.preventDefault();
        ev.stopPropagation();
        var st=ensureEventState();
        var key=btn.getAttribute('data-event-toggle');
        if(!Array.isArray(st.selected)) st.selected=[];
        var idx=st.selected.indexOf(key);
        if(idx===-1) st.selected.push(key); else st.selected.splice(idx,1);
        try{ localStorage.setItem('myBeautyJournalData', JSON.stringify(data)); }catch(e){}
        if(typeof renderAfterEventPanel==='function') renderAfterEventPanel();
        bindEvents();
      };
    });
  }
  function refresh(){
    if(!isAfter()) return;
    if(typeof renderAfterEventPanel==='function') renderAfterEventPanel();
    bindEvents();
  }
  window.addEventListener('hashchange', function(){ setTimeout(refresh,20); });
  // render() rebuilds the page on navigation, so hook it once it exists.
  var tries=0;
  var timer=setInterval(function(){
    tries++;
    if(typeof render==='function'){
      clearInterval(timer);
      var original=render;
      window.render=function(){
        var result=original.apply(this,arguments);
        setTimeout(refresh,0);
        return result;
      };
      if(isAfter()) setTimeout(refresh,0);
    }
    if(tries>100) clearInterval(timer);
  },25);
  document.addEventListener('click', function(e){
    if(!isAfter()) return;
    var btn=e.target.closest ? e.target.closest('[data-event-toggle]') : null;
    if(!btn) return;
    // If a page-specific handler wasn't attached yet, handle it here.
    if(!btn.onclick){
      e.preventDefault();
      e.stopImmediatePropagation();
      var st=ensureEventState(), key=btn.getAttribute('data-event-toggle');
      var idx=st.selected.indexOf(key);
      if(idx===-1) st.selected.push(key); else st.selected.splice(idx,1);
      try{localStorage.setItem('myBeautyJournalData',JSON.stringify(data));}catch(err){}
      renderAfterEventPanel();
      bindEvents();
    }
  }, true);
})();

</script>
</body>
</html>
