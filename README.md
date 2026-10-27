# craftland.maps
<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<meta name="theme-color" content="#07110c">
<title>Craftland Maps</title>
<style>
:root{--bg:#07110c;--panel:#101c15;--panel2:#14251a;--green:#9cff57;--muted:#9eb2a2;--line:#263a2b;--white:#f3fff5}
*{box-sizing:border-box}body{margin:0;background:radial-gradient(ellipse at top,#16321e 0,#07110c 55%);color:var(--white);font-family:system-ui,-apple-system,Segoe UI,Roboto,Arial,sans-serif;min-height:100vh}
.wrap{max-width:980px;margin:auto;padding:22px 16px 50px}.top{display:flex;align-items:center;justify-content:space-between;gap:12px;margin-bottom:42px}.brand{display:flex;align-items:center;gap:10px;font-weight:900;letter-spacing:.4px;font-size:19px}.logo{display:grid;place-items:center;width:42px;height:42px;border-radius:13px;background:var(--green);color:#10210d;font-weight:1000;font-size:20px;box-shadow:0 0 26px #9cff5733}.pill{border:1px solid #3c583f;color:var(--green);border-radius:999px;padding:7px 11px;font-size:12px;font-weight:750}
.hero{text-align:center;max-width:720px;margin:0 auto 30px}.eyebrow{color:var(--green);font-size:12px;font-weight:850;letter-spacing:2px;text-transform:uppercase}.hero h1{font-size:clamp(34px,7vw,62px);line-height:1.02;margin:12px 0 14px;letter-spacing:-2px}.hero h1 span{color:var(--green)}.hero p{color:var(--muted);line-height:1.6;margin:0 auto 25px;max-width:550px}
.searchbox{display:flex;gap:9px;padding:8px;background:#0b1710;border:1px solid #35513a;border-radius:17px;box-shadow:0 14px 50px #0005;max-width:690px;margin:auto}.searchbox input{flex:1;min-width:0;background:transparent;border:0;outline:0;color:var(--white);padding:11px 12px;font-size:15px}.searchbox input::placeholder{color:#738879}.searchbox button,.primary{border:0;background:var(--green);color:#11200d;border-radius:11px;padding:12px 17px;font-weight:900;cursor:pointer}.searchbox button:hover,.primary:hover{filter:brightness(1.08)}.hint{color:#7f9685;font-size:12px;margin-top:12px}
.stats{display:grid;grid-template-columns:repeat(3,1fr);gap:12px;margin:34px 0}.stat{background:#0c1810;border:1px solid var(--line);border-radius:14px;padding:15px;text-align:center}.stat strong{display:block;font-size:22px;color:var(--green)}.stat span{font-size:12px;color:var(--muted)}
.sectionhead{display:flex;align-items:center;justify-content:space-between;gap:10px;margin:28px 0 14px}.sectionhead h2{font-size:18px;margin:0}.sectionhead span{color:var(--muted);font-size:12px}
.results{display:grid;grid-template-columns:repeat(2,minmax(0,1fr));gap:14px}.mapcard{background:linear-gradient(145deg,#14231a,#0c1710);border:1px solid var(--line);border-radius:17px;overflow:hidden}.cover{height:128px;display:flex;align-items:end;padding:14px;background:linear-gradient(130deg,#274b29,#142b1d 52%,#0a120c);position:relative;isolation:isolate}.cover:before{content:"";position:absolute;inset:0;background:radial-gradient(circle at 75% 25%,#b4ff7033,transparent 28%),linear-gradient(135deg,transparent 45%,#9cff5715 45% 48%,transparent 48%);z-index:-1}.cover .mode{font-size:10px;font-weight:900;letter-spacing:1px;border:1px solid #8ecb7d66;background:#08150bbd;border-radius:6px;padding:5px 8px;color:#d6ffd1}.cover .mapglyph{position:absolute;right:18px;top:16px;font-size:43px;opacity:.8;filter:drop-shadow(0 4px 14px #9cff5733)}.cardbody{padding:15px}.cardbody h3{margin:0 0 7px;font-size:17px}.meta{display:flex;flex-wrap:wrap;gap:7px;color:var(--muted);font-size:12px;margin-bottom:13px}.tag{background:#203525;color:#c9e7ca;border-radius:6px;padding:4px 7px}.codebox{display:flex;align-items:center;justify-content:space-between;gap:8px;background:#08110b;border:1px solid #293e2c;border-radius:9px;padding:9px 10px;font-family:ui-monospace,monospace;color:var(--green);font-size:13px}.copy{background:#1b2b1e;border:1px solid #38533b;color:#e4ffe0;border-radius:7px;padding:6px 9px;cursor:pointer;font-size:11px}.cardfoot{display:flex;justify-content:space-between;align-items:center;margin-top:12px;color:var(--muted);font-size:12px}.details{background:var(--panel);border:1px solid var(--line);border-radius:16px;padding:18px;margin-top:18px;display:none}.details h3{margin:0 0 8px}.notice{margin-top:28px;padding:14px 16px;background:#191b11;border:1px solid #494326;border-radius:12px;color:#c8c7a4;font-size:12px;line-height:1.55}.notice strong{color:#f0e9a2}.empty{display:none;text-align:center;padding:30px 15px;border:1px dashed #38533b;border-radius:15px;color:var(--muted);grid-column:1/-1}.footer{text-align:center;color:#6f8575;font-size:11px;margin-top:30px}
@media(max-width:600px){.wrap{padding:16px 13px 35px}.top{margin-bottom:34px}.pill{font-size:10px}.hero h1{letter-spacing:-1px}.searchbox{flex-wrap:wrap}.searchbox input{flex-basis:100%;padding:12px 10px}.searchbox button{width:100%}.stats{gap:7px;margin:25px 0}.stat{padding:12px 5px}.stat strong{font-size:19px}.stat span{font-size:10px}.results{grid-template-columns:1fr}.cover{height:115px}}
</style>
</head>
<body>
<div class="wrap">
  <header class="top">
    <div class="brand"><div class="logo">C</div><span>CRAFTLAND <span style="color:var(--green)">MAPS</span></span></div>
    <div class="pill">FREE FIRE • COMUNIDADE</div>
  </header>
  <main>
    <section class="hero">
      <div class="eyebrow">Encontre seu próximo mapa</div>
      <h1>Seu mapa.<br><span>Sua próxima partida.</span></h1>
      <p>Pesquise mapas de Craftland pelo nome ou código e descubra modos para jogar com a tropa.</p>
      <form class="searchbox" id="searchForm">
        <input id="query" aria-label="Pesquisar mapa" placeholder="Digite o nome ou código do mapa..." autocomplete="off">
        <button type="submit">⌕ Pesquisar mapas</button>
      </form>
      <div class="hint">Experimente: “Bermuda”, “2v2” ou “CL-2048”</div>
    </section>
    <section class="stats">
      <div class="stat"><strong id="mapCount">04</strong><span>mapas de demonstração</span></div>
      <div class="stat"><strong>3</strong><span>modos diferentes</span></div>
      <div class="stat"><strong>24/7</strong><span>busca nesta prévia</span></div>
    </section>
    <div class="sectionhead"><h2 id="resultsTitle">Mapas para explorar</h2><span id="resultCount">4 resultados</span></div>
    <section class="results" id="results"></section>
    <div class="details" id="details"></div>
    <div class="notice"><strong>Importante:</strong> esta é uma prévia funcional com dados fictícios para demonstrar o visual e a pesquisa. Ela ainda não consulta a API real da comunidade. Para ativar dados reais, será necessário configurar a API e guardar a chave com segurança no servidor.</div>
  </main>
  <footer class="footer">CRAFTLAND MAPS • Projeto comunitário independente • Não afiliado à Garena</footer>
</div>
<script>
const maps=[
 {name:"Bermuda 4x4",code:"CL-2048",mode:"Contra Squad",players:"4v4",desc:"Arena compacta para partidas rápidas entre equipes.",tags:["Bermuda","Competitivo"],icon:"⚔️",likes:"Popular"},
 {name:"Treino de Capa",code:"CL-7712",mode:"Treinamento",players:"1-8",desc:"Espaço de treino para melhorar mira e movimentação.",tags:["Treino","Mira"],icon:"🎯",likes:"Treino"},
 {name:"Arena 2v2",code:"CL-5520",mode:"Duelo",players:"2v2",desc:"Confrontos curtos para jogar em dupla.",tags:["2v2","Duelo"],icon:"🛡️",likes:"Duplas"},
 {name:"Corrida Neon",code:"CL-3901",mode:"Corrida",players:"1-6",desc:"Percurso de obstáculos com visual neon.",tags:["Corrida","Parkour"],icon:"🏁",likes:"Casual"}
];
const results=document.getElementById("results"), query=document.getElementById("query"), count=document.getElementById("resultCount"), title=document.getElementById("resultsTitle"), details=document.getElementById("details");
function render(list,term=""){
 results.innerHTML="";
 document.getElementById("mapCount").textContent=String(list.length).padStart(2,"0");
 count.textContent=list.length+" resultado"+(list.length===1?"":"s");
 title.textContent=term?'Resultados da pesquisa':'Mapas para explorar';
 details.style.display="none";
 if(!list.length){results.innerHTML='<div class="empty" style="display:block">Nenhum mapa encontrado nesta prévia.<br><small>Tente pesquisar por outro nome ou código.</small></div>';return}
 list.forEach((m,i)=>{
  const card=document.createElement("article");card.className="mapcard";
  card.innerHTML=`<div class="cover"><span class="mode">${m.mode.toUpperCase()}</span><span class="mapglyph">${m.icon}</span></div><div class="cardbody"><h3>${m.name}</h3><div class="meta"><span>${m.players} jogadores</span><span>•</span><span>${m.likes}</span></div><p style="color:var(--muted);font-size:13px;line-height:1.5;min-height:39px;margin:0 0 12px">${m.desc}</p><div class="codebox"><span>${m.code}</span><button class="copy" data-code="${m.code}">Copiar código</button></div><div class="cardfoot"><span>${m.tags.map(t=>'#'+t).join(' ')}</span><button class="copy" data-details="${i}">Ver detalhes ↗</button></div></div>`;
  results.appendChild(card);
 });
 results.querySelectorAll("[data-code]").forEach(b=>b.addEventListener("click",async()=>{const code=b.dataset.code;try{await navigator.clipboard.writeText(code);b.textContent="Copiado ✓"}catch(e){b.textContent=code}setTimeout(()=>b.textContent="Copiar código",1300)}));
 results.querySelectorAll("[data-details]").forEach(b=>b.addEventListener("click",()=>{const m=list[Number(b.dataset.details)];details.style.display="block";details.innerHTML=`<h3>${m.icon} ${m.name}</h3><p style="color:var(--muted);line-height:1.6">${m.desc}</p><p><strong>Modo:</strong> ${m.mode} &nbsp; <strong>Jogadores:</strong> ${m.players}</p><p><strong>Código demonstrativo:</strong> <span style="color:var(--green)">${m.code}</span></p><small style="color:var(--muted)">Os dados acima são fictícios e servem apenas para testar a interface.</small>`;details.scrollIntoView({behavior:"smooth",block:"nearest"})}));
}
function search(){const term=query.value.trim().toLocaleLowerCase("pt-BR");const filtered=maps.filter(m=>[m.name,m.code,m.mode,m.players,...m.tags].join(" ").toLocaleLowerCase("pt-BR").includes(term));render(filtered,term)}
document.getElementById("searchForm").addEventListener("submit",e=>{e.preventDefault();search()});
query.addEventListener("input",search);
render(maps);
</script>
</body>
</html>