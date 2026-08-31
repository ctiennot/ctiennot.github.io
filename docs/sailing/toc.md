---
layout: page
title: Navigations, stages et camps de voile
permalink: /sailing/
---

<style>
@import url("https://cdnjs.cloudflare.com/ajax/libs/leaflet/1.9.4/leaflet.min.css");
.sail-layout{display:flex;gap:24px;align-items:flex-start;margin-top:14px}
.sail-col{flex:1 1 50%;min-width:0}
.sail-mapwrap{flex:1 1 50%;position:sticky;top:16px}
#sailmap{height:calc(100vh - 96px);min-height:420px;border:1px solid rgba(128,128,128,.4);border-radius:10px;background:#12202a}
.sail-maphint{font-size:11px;opacity:.6;margin:6px 2px 0}
.sail-year{margin:24px 0 0;font-size:1.5em}
.sail-year:first-of-type{margin-top:0}
.sail-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(180px,1fr));gap:14px;margin:10px 0 4px}
.sail-card{display:flex;flex-direction:column;border:1px solid rgba(128,128,128,.35);border-left:4px solid var(--c,rgba(128,128,128,.4));border-radius:8px;overflow:hidden;background:rgba(128,128,128,.08);color:inherit;text-decoration:none;transition:transform .12s,box-shadow .12s}
a.sail-card:hover{transform:translateY(-3px);box-shadow:0 8px 22px rgba(0,0,0,.33)}
.sail-card.hl{box-shadow:0 0 0 2px var(--c)}
.sail-card .im{height:130px;background-size:cover;background-position:center;background-color:#12202a}
.sail-card .bd{padding:9px 11px 11px}
.sail-card .ti{font-weight:600;line-height:1.25;font-size:.95em}
.sail-card .me{display:block;margin-top:4px;font-size:11.5px;opacity:.7;line-height:1.35}
.sail-card[data-trip] .me::before{content:"";display:inline-block;width:8px;height:8px;border-radius:50%;background:var(--c);margin-right:6px;vertical-align:1px}
.sail-card.todo{opacity:.45}
.sail-card.todo .im{display:flex;align-items:center;justify-content:center;font-size:11px;letter-spacing:.09em;text-transform:uppercase}
.leaflet-container{font:inherit}
@media(max-width:900px){.sail-layout{flex-direction:column}.sail-mapwrap{position:static;width:100%;order:-1}#sailmap{height:320px;min-height:0}}
</style>

<div class="sail-layout">
<div class="sail-col">

<h2 class="sail-year">2026</h2>
<div class="sail-grid">
<a class="sail-card" data-trip="vannes2026" style="--c:#4aa3df" href="glenans_vannes_2026"><span class="im" style="background-image:url('/docs/sailing/hoedic_2026-2.jpg')"></span><span class="bd"><span class="ti">Stage Glénans — Spé Manœuvre Pogo</span><span class="me">22–27 août 2026 · Golfe du Morbihan, Houat-Hœdic</span></span></a>
<a class="sail-card" data-trip="brest2026" style="--c:#e4572e" href="brest_june_2026"><span class="im"></span><span class="bd"><span class="ti">Croisière en Mer d'Iroise</span><span class="me">14–17 mai 2026 · Brest</span></span></a>
</div>

<h2 class="sail-year">2025</h2>
<div class="sail-grid">
<a class="sail-card" data-trip="arz2025" style="--c:#9b7fc4" href="glenans_sept_2025"><span class="im" style="background-image:url('/docs/sailing/image-34.png')"></span><span class="bd"><span class="ti">Glénans N3 — Conduite Manœuvre</span><span class="me">septembre 2025 · Île d'Arz</span></span></a>
<a class="sail-card" data-trip="paimpol2025" style="--c:#2fae66" href="glenans_august_2025"><span class="im" style="background-image:url('/docs/sailing/image-18.png')"></span><span class="bd"><span class="ti">Glénans N3 — Équipier polyvalent</span><span class="me">août 2025 · Paimpol</span></span></a>
<a class="sail-card" data-trip="qube2025" style="--c:#e8b93b" href="qube_trin_2025"><span class="im" style="background-image:url('/docs/sailing/image-1.png')"></span><span class="bd"><span class="ti">Week-end Qube</span><span class="me">14–15 juin 2025 · La Trinité · Belle-Île</span></span></a>
<a class="sail-card" data-trip="anglo2025" style="--c:#d1495b" href="anglo_normandes_2025"><span class="im" style="background-image:url('/docs/sailing/image-10.png')"></span><span class="bd"><span class="ti">Croisière Anglo-Normandes</span><span class="me">avril–mai 2025 · Bréhat · Guernesey · Sark</span></span></a>
<span class="sail-card todo"><span class="im">à venir</span><span class="bd"><span class="ti">Régate Qube</span><span class="me">septembre 2025</span></span></span>
<span class="sail-card todo"><span class="im">à venir</span><span class="bd"><span class="ti">Week-end Qube Marseille</span><span class="me">avril 2025</span></span></span>
</div>

<h2 class="sail-year">2024</h2>
<div class="sail-grid">
<a class="sail-card" data-trip="lorient2024" style="--c:#00a3a3" href="lorient"><span class="im" style="background-image:url('/docs/sailing/image-5.png')"></span><span class="bd"><span class="ti">Week-end à Lorient</span><span class="me">12–13 octobre 2024 · Groix</span></span></a>
<a class="sail-card" data-trip="concarneau2024" style="--c:#f0883b" href="glenans_2024"><span class="im" style="background-image:url('/docs/sailing/image-4.png')"></span><span class="bd"><span class="ti">Glénans N2 — Perfectionnement croisière</span><span class="me">août 2024 · Concarneau</span></span></a>
<a class="sail-card" data-trip="vem2024" style="--c:#7a67ee" href="vem_2024"><span class="im" style="background-image:url('https://github.com/user-attachments/assets/8b6fdc87-e82a-45c1-9264-82f553f6e66e')"></span><span class="bd"><span class="ti">Camp Vie En Mer +</span><span class="me">juillet–août 2024 · Concarneau → Le Crouesty</span></span></a>
</div>

<h2 class="sail-year">2023</h2>
<div class="sail-grid">
<span class="sail-card todo"><span class="im">à venir</span><span class="bd"><span class="ti">Stage Glénans N2 — Saint-Malo</span><span class="me">août 2023</span></span></span>
</div>

<h2 class="sail-year">2022</h2>
<div class="sail-grid">
<span class="sail-card todo"><span class="im">à venir</span><span class="bd"><span class="ti">Vie En Mer 1</span><span class="me">2022</span></span></span>
</div>

<h2 class="sail-year">2018</h2>
<div class="sail-grid">
<span class="sail-card todo"><span class="im">à venir</span><span class="bd"><span class="ti">Mer et prière — Sables-d'Olonne</span><span class="me">2018</span></span></span>
</div>

</div>
<div class="sail-mapwrap">
<div id="sailmap"></div>
<p class="sail-maphint">Tracés approximatifs reconstitués d'après les descriptions. Fond OpenStreetMap / OpenSeaMap. Survolez une vignette pour surligner son parcours.</p>
</div>
</div>

<script src="https://cdnjs.cloudflare.com/ajax/libs/leaflet/1.9.4/leaflet.min.js"></script>
<script>
(function(){
  if(!window.L){return;}
  var TRIPS={
    vannes2026:{c:'#4aa3df',pts:[[47.638,-2.760],[47.62,-2.83],[47.548,-2.918],[47.543,-2.899],[47.50,-3.00],[47.585,-3.026],[47.45,-2.98],[47.392,-2.955],[47.343,-2.876],[47.50,-2.90],[47.543,-2.899],[47.58,-2.85],[47.616,-2.826],[47.606,-2.795],[47.638,-2.760]]},
    brest2026:{c:'#e4572e',pts:[[48.383,-4.490],[48.293,-4.265],[48.31,-4.57],[48.277,-4.593],[48.228,-4.498],[48.096,-4.329],[48.10,-4.55],[48.33,-4.78],[48.470,-4.757],[48.336,-4.665],[48.383,-4.490]]},
    arz2025:{c:'#9b7fc4',pts:[[47.591,-2.807],[47.602,-2.83],[47.586,-2.788],[47.591,-2.807]]},
    paimpol2025:{c:'#2fae66',pts:[[48.786,-2.972],[48.789,-3.104],[48.84,-3.10],[48.905,-3.087],[48.83,-3.25],[48.786,-3.230],[48.834,-3.325],[48.70,-3.05],[48.708,-2.938],[48.601,-2.824],[48.75,-2.95],[48.789,-3.104]]},
    qube2025:{c:'#e8b93b',pts:[[47.585,-3.026],[47.52,-3.05],[47.40,-3.10],[47.348,-3.156],[47.44,-3.05],[47.585,-3.026]]},
    anglo2025:{c:'#d1495b',pts:[[48.646,-2.815],[48.851,-3.000],[49.457,-2.536],[49.432,-2.362],[49.497,-2.515],[48.638,-2.257],[48.687,-2.316],[48.646,-2.815]]},
    lorient2024:{c:'#00a3a3',pts:[[47.732,-3.365],[47.706,-3.39],[47.644,-3.446],[47.70,-3.40],[47.732,-3.365]]},
    concarneau2024:{c:'#f0883b',pts:[[47.872,-3.918],[47.902,-3.977],[47.80,-3.99],[47.717,-3.998],[47.83,-4.08],[47.867,-4.108],[47.92,-4.08],[47.867,-4.108],[47.902,-3.977],[47.855,-3.98],[47.872,-3.918]]},
    vem2024:{c:'#7a67ee',pts:[[47.872,-3.918],[47.717,-3.998],[47.32,-3.13],[47.347,-2.510],[46.727,-2.339],[47.392,-2.955],[47.543,-2.899]]}
  };
  var map=L.map('sailmap',{scrollWheelZoom:false});
  L.tileLayer('https://tile.openstreetmap.org/{z}/{x}/{y}.png',{maxZoom:18,attribution:'&copy; OpenStreetMap'}).addTo(map);
  L.tileLayer('https://tiles.openseamap.org/seamark/{z}/{x}/{y}.png',{maxZoom:18,opacity:.9}).addTo(map);
  var lines={},all=[];
  Object.keys(TRIPS).forEach(function(id){
    var t=TRIPS[id];
    var card=document.querySelector('.sail-card[data-trip="'+id+'"]');
    var pl=L.polyline(t.pts,{color:t.c,weight:3,opacity:.8,lineJoin:'round',lineCap:'round'}).addTo(map);
    var name=card?card.querySelector('.ti').textContent:id;
    pl.bindTooltip(name,{sticky:true});
    if(card){
      pl.on('click',function(){location.href=card.href;});
      pl.on('mouseover',function(){set(id,true);});
      pl.on('mouseout',function(){set(id,false);});
      card.addEventListener('mouseenter',function(){set(id,true);});
      card.addEventListener('mouseleave',function(){set(id,false);});
    }
    lines[id]=pl;all.push(pl);
  });
  function set(id,on){
    var pl=lines[id];if(!pl)return;
    pl.setStyle({weight:on?6:3,opacity:on?1:.8});
    if(on)pl.bringToFront();
    var card=document.querySelector('.sail-card[data-trip="'+id+'"]');
    if(card)card.classList.toggle('hl',on);
  }
  try{map.fitBounds(L.featureGroup(all).getBounds().pad(0.08));}catch(e){map.setView([47.9,-3.2],7);}
})();
</script>
