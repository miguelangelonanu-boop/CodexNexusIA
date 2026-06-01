@import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap');
*{margin:0;padding:0;box-sizing:border-box}
:root{--bg:#050608;--s1:#0b0d10;--s2:#111418;--sf:#12161b;--sf2:#1a2027;--bd:#26303a;--bd2:#3a4652;--t1:#f3f4f6;--t2:#a7b0bc;--t3:#687381;--ac:#64748b;--ac2:#475569;--ac3:#cbd5e1;--gn:#16a34a;--rd:#dc2626;--am:#d97706}
html,body{height:100%;overflow:hidden}
body{font-family:'Inter',system-ui,sans-serif;background:radial-gradient(circle at 50% -10%,rgba(100,116,139,.13),transparent 35%),linear-gradient(180deg,#050608,#080a0d 55%,#050608);color:var(--t1);display:flex;letter-spacing:.01em}

/* SIDEBAR */
.sb{width:260px;background:rgba(11,13,16,.96);backdrop-filter:blur(10px);border-right:1px solid var(--bd);display:flex;flex-direction:column;flex-shrink:0;transition:transform .22s ease;z-index:40}
.sb.shut{transform:translateX(-260px);position:absolute;height:100%}
.sb-top{padding:12px 14px;border-bottom:1px solid var(--bd);display:flex;align-items:center;justify-content:space-between}
.sb-top h2{font-size:13px;font-weight:700}
.nb{padding:4px 10px;background:var(--ac);border:none;border-radius:4px;color:#fff;font-size:9px;font-weight:600;cursor:pointer;font-family:inherit}

/* Tabs */
.sb-tabs{display:flex;border-bottom:1px solid var(--bd)}
.sb-tab{flex:1;padding:8px 0;text-align:center;font-size:9px;font-weight:600;color:var(--t3);cursor:pointer;border-bottom:2px solid transparent;transition:.15s}
.sb-tab.on{color:var(--ac);border-color:var(--ac)}
.sb-tab:hover{color:var(--t2)}

.sb-panel{flex:1;overflow-y:auto;display:none}
.sb-panel.on{display:flex;flex-direction:column}
.sb-panel::-webkit-scrollbar{width:2px}
.sb-panel::-webkit-scrollbar-thumb{background:var(--bd)}

/* Chat list */
.ci{padding:8px 10px;border-radius:5px;cursor:pointer;margin:1px 6px;display:flex;align-items:center;justify-content:space-between;gap:4px;transition:.1s}
.ci:hover{background:var(--sf2)}
.ci.on{background:var(--sf2);outline:1px solid var(--bd2)}
.ci-n{font-size:10px;font-weight:500;white-space:nowrap;overflow:hidden;text-overflow:ellipsis;flex:1}
.ci-d{font-size:8px;color:var(--t3)}
.ci-x{width:18px;height:18px;border:none;background:none;color:var(--t3);font-size:9px;cursor:pointer;border-radius:3px;display:none;align-items:center;justify-content:center}
.ci:hover .ci-x{display:flex}
.ci-x:hover{color:var(--rd)}

/* Room panel */
.room-sec{padding:10px 14px}
.room-sec label{font-size:9px;font-weight:600;color:var(--t3);text-transform:uppercase;letter-spacing:.5px;display:block;margin-bottom:4px}
.room-inp{width:100%;padding:6px 8px;background:var(--sf);border:1px solid var(--bd);border-radius:4px;color:var(--t1);font-size:11px;font-family:inherit;outline:none}
.room-inp:focus{border-color:var(--ac)}
.room-btn{width:100%;padding:6px;background:var(--ac);border:none;border-radius:4px;color:#fff;font-size:10px;font-weight:600;cursor:pointer;font-family:inherit;margin-top:6px}
.room-info{margin-top:10px;padding:8px;background:var(--sf);border:1px solid var(--bd);border-radius:4px;font-size:9px;color:var(--t2);line-height:1.5}
.room-info b{color:var(--ac3)}
.user-list{margin-top:8px}
.user-item{padding:3px 0;font-size:10px;color:var(--t2);display:flex;align-items:center;gap:4px}
.user-dot{width:5px;height:5px;border-radius:50%;background:var(--gn)}

/* Memory */
.mem-sec{padding:10px 14px}
.mem-b{background:var(--sf);border:1px solid var(--bd);border-radius:4px;padding:6px;max-height:120px;overflow-y:auto;font-size:9px;color:var(--t3);line-height:1.5}
.mi{padding:2px 0;border-bottom:1px solid rgba(255,255,255,.02);font-size:9px;color:var(--t2)}
.mi:last-child{border:none}
.mc-btn{margin-top:4px;padding:2px 6px;background:none;border:1px solid var(--bd);border-radius:3px;color:var(--t3);font-size:7px;cursor:pointer;font-family:inherit}
.mc-btn:hover{border-color:var(--rd);color:var(--rd)}

/* OVERLAY */
.ov{display:none;position:fixed;inset:0;background:rgba(0,0,0,.6);z-index:35}
.ov.show{display:block}

/* MAIN */
.mn{flex:1;display:flex;flex-direction:column;min-width:0}
.hd{background:rgba(11,13,16,.92);backdrop-filter:blur(10px);border-bottom:1px solid var(--bd);padding:8px 14px;display:flex;align-items:center;justify-content:space-between;flex-shrink:0;box-shadow:0 1px 20px rgba(0,0,0,.18)}
.hd-l{display:flex;align-items:center;gap:8px}
.hm{width:28px;height:28px;background:var(--sf);border:1px solid var(--bd);border-radius:4px;color:var(--t2);font-size:12px;cursor:pointer;display:flex;align-items:center;justify-content:center}
.hm:hover{border-color:var(--ac);color:var(--ac)}
.hb{font-size:13px;font-weight:700}
.hb small{font-size:8px;font-weight:400;color:var(--t3);margin-left:4px}
.hd-r{display:flex;align-items:center;gap:5px}
.ms{padding:2px 6px;border-radius:3px;font-size:8px;font-weight:600;background:var(--sf);border:1px solid var(--bd);color:var(--t2);cursor:pointer;font-family:inherit;outline:none}
.ms option{background:var(--s1);color:var(--t1)}
.hs{display:flex;align-items:center;gap:3px;font-size:8px;color:var(--t3)}
.hd-dot{width:4px;height:4px;border-radius:50%;background:var(--gn)}
.exp-btn{padding:2px 6px;border-radius:3px;font-size:8px;font-weight:600;background:none;border:1px solid var(--bd);color:var(--t3);cursor:pointer;font-family:inherit}
.exp-btn:hover{border-color:var(--ac);color:var(--ac)}

/* Chat */
.cc{flex:1;overflow-y:auto;padding:16px 14px;scroll-behavior:smooth}
.cc::-webkit-scrollbar{width:3px}
.cc::-webkit-scrollbar-thumb{background:var(--bd);border-radius:2px}

/* Welcome */
.wel{display:flex;flex-direction:column;align-items:center;justify-content:center;height:100%;text-align:center;animation:fi .3s}
@keyframes fi{from{opacity:0;transform:translateY(4px)}to{opacity:1;transform:translateY(0)}}
.wel h2{font-size:18px;font-weight:700;margin-bottom:3px}
.wel>p{color:var(--t3);font-size:11px;max-width:380px;line-height:1.5;margin-bottom:14px}
.cmds{display:flex;flex-direction:column;gap:3px;max-width:340px;width:100%;margin-bottom:14px}
.cm{display:flex;align-items:center;gap:6px;padding:5px 8px;background:var(--sf);border:1px solid var(--bd);border-radius:4px;font-size:9px}
.cm code{font-weight:600;color:var(--ac3);font-family:inherit}
.cm span{color:var(--t3)}
.sgs{display:grid;grid-template-columns:1fr 1fr;gap:5px;max-width:380px;width:100%}
.sg{background:var(--sf);border:1px solid var(--bd);border-radius:5px;padding:8px;cursor:pointer;transition:.12s;text-align:left}
.sg:hover{border-color:var(--ac);background:var(--sf2)}
.sg b{font-size:9px;color:var(--t2);display:block;margin-bottom:1px}
.sg span{font-size:8px;color:var(--t3)}

/* Messages */
.msg{display:flex;gap:7px;margin-bottom:12px;animation:mi .22s ease-out;max-width:700px;margin-left:auto;margin-right:auto}
@keyframes mi{from{opacity:0;transform:translateY(6px) scale(.995)}to{opacity:1;transform:translateY(0) scale(1)}}
.msg.u{flex-direction:row-reverse}
.msg.sys{justify-content:center}
.msg.sys .m-c{background:none;border:none;color:var(--t3);font-size:9px;font-style:italic;padding:4px 0}
.av{width:24px;height:24px;border-radius:4px;display:flex;align-items:center;justify-content:center;font-size:9px;flex-shrink:0;margin-top:1px;font-weight:800}
.msg.a .av{background:var(--ac);color:#fff}
.msg.u .av{background:var(--sf2);color:var(--t2)}
.msg.peer .av{background:var(--am);color:#fff}
.m-b{max-width:75%}
.m-c{padding:8px 12px;border-radius:7px;font-size:12px;line-height:1.75}
.msg.a .m-c{background:var(--sf);border:1px solid var(--bd);border-top-left-radius:2px}
.msg.u .m-c{background:var(--ac2);border-top-right-radius:2px}
.msg.peer .m-c{background:var(--sf);border:1px solid var(--bd);border-top-left-radius:2px}
.m-c .sender{font-size:9px;font-weight:700;color:var(--am);margin-bottom:2px;display:block}
.m-c p{margin-bottom:4px}.m-c p:last-child{margin-bottom:0}
.m-c strong{color:var(--ac3)}.m-c em{color:var(--t2)}
.m-c h2,.m-c h3,.m-c h4{color:var(--ac3);margin:6px 0 3px;font-size:12px}
.m-c code{background:rgba(0,0,0,.4);padding:1px 3px;border-radius:2px;font-size:10px;font-family:'Courier New',monospace}
.m-c pre{background:#0c0c10;padding:10px;border-radius:4px;overflow-x:auto;margin:4px 0;position:relative;border:1px solid var(--bd)}
.m-c pre code{background:none;padding:0;white-space:pre;font-size:10px;line-height:1.5}
.m-c ul,.m-c ol{margin:3px 0;padding-left:14px}.m-c li{margin-bottom:1px}
.cpb{position:absolute;top:2px;right:2px;background:var(--sf2);border:1px solid var(--bd);color:var(--t3);padding:1px 5px;border-radius:2px;font-size:7px;cursor:pointer;font-family:inherit}
.cpb:hover{background:var(--ac);color:#fff;border-color:var(--ac)}
.m-m{display:flex;align-items:center;gap:4px;margin-top:2px}
.m-t{font-size:7px;color:var(--t3);opacity:.5}
.msg.u .m-m{justify-content:flex-end}

/* HTML Preview */
.html-preview{margin:6px 0;border:1px solid var(--bd);border-radius:4px;overflow:hidden}
.html-preview-bar{padding:4px 8px;background:var(--sf2);border-bottom:1px solid var(--bd);display:flex;align-items:center;justify-content:space-between;font-size:8px;color:var(--t3)}
.html-preview-bar button{padding:1px 6px;background:var(--ac);border:none;border-radius:2px;color:#fff;font-size:7px;font-weight:600;cursor:pointer;font-family:inherit}
.html-preview iframe{width:100%;height:200px;border:none;background:#fff}

/* Typing */
.typ{display:flex;gap:3px;padding:4px 0}
.typ span{width:4px;height:4px;background:var(--ac);border-radius:50%;animation:tb 1.4s ease-in-out infinite}
.typ span:nth-child(2){animation-delay:.2s}
.typ span:nth-child(3){animation-delay:.4s}
@keyframes tb{0%,60%,100%{transform:translateY(0);opacity:.3}30%{transform:translateY(-4px);opacity:1}}
.err-m{background:rgba(239,68,68,.06)!important;border-color:rgba(239,68,68,.15)!important;color:#fca5a5!important}

/* Input */
.ia{background:var(--s1);border-top:1px solid var(--bd);padding:10px 14px;flex-shrink:0}
.iw{max-width:700px;margin:0 auto;display:flex;gap:5px;align-items:flex-end}
.ib{flex:1;background:var(--sf);border:1px solid var(--bd);border-radius:7px;padding:7px 10px;transition:.15s}
.ib:focus-within{border-color:var(--ac);box-shadow:0 0 0 2px rgba(59,130,246,.1)}
.ib textarea{width:100%;background:transparent;border:none;color:var(--t1);font-size:12px;font-family:inherit;resize:none;outline:none;max-height:70px;line-height:1.4}
.ib textarea::placeholder{color:var(--t3)}
.sb2{width:34px;height:34px;background:var(--ac);border:none;border-radius:5px;color:#fff;font-size:13px;cursor:pointer;display:flex;align-items:center;justify-content:center;flex-shrink:0}
.sb2:hover{background:var(--ac2)}
.sb2:disabled{opacity:.2;cursor:not-allowed}
.if{max-width:700px;margin:3px auto 0;display:flex;justify-content:space-between;align-items:center}
.if span{font-size:7px;color:var(--t3);opacity:.4}
.cb{background:none;border:1px solid var(--bd);color:var(--t3);padding:1px 5px;border-radius:2px;font-size:7px;cursor:pointer;font-family:inherit}
.cb:hover{border-color:var(--rd);color:var(--rd)}
.auto-btn{background:linear-gradient(135deg,var(--ac),#8b5cf6);border:none;color:#fff;padding:2px 7px;border-radius:3px;font-size:7px;font-weight:700;cursor:pointer;font-family:inherit;margin-left:4px}
.auto-btn:hover{filter:brightness(1.12)}
.acc-btn{padding:2px 7px;border-radius:3px;font-size:8px;font-weight:700;background:var(--sf);border:1px solid var(--bd);color:var(--t2);cursor:pointer;font-family:inherit;max-width:110px;white-space:nowrap;overflow:hidden;text-overflow:ellipsis}
.acc-btn:hover{border-color:var(--ac3);color:var(--t1)}
.attach-btn{width:34px;height:34px;background:var(--sf);border:1px solid var(--bd);border-radius:5px;color:var(--t2);font-size:14px;cursor:pointer;display:flex;align-items:center;justify-content:center;flex-shrink:0}
.attach-btn:hover{border-color:var(--ac3);color:var(--t1)}
.img-strip{max-width:700px;margin:0 auto 6px;display:none;gap:6px;flex-wrap:wrap}
.img-strip.on{display:flex}
.img-chip{position:relative;width:54px;height:54px;border:1px solid var(--bd);border-radius:6px;overflow:hidden;background:var(--sf)}
.img-chip img{width:100%;height:100%;object-fit:cover;display:block}
.img-chip button{position:absolute;top:2px;right:2px;width:16px;height:16px;border:none;border-radius:50%;background:rgba(0,0,0,.72);color:#fff;font-size:10px;cursor:pointer}
.msg-imgs{display:flex;gap:6px;flex-wrap:wrap;margin:0 0 6px}
.msg-imgs img{max-width:180px;max-height:180px;border-radius:6px;border:1px solid var(--bd);object-fit:cover}
.chain-hint{max-width:440px;width:100%;margin:0 0 10px;padding:7px 9px;background:rgba(100,116,139,.08);border:1px solid rgba(148,163,184,.18);border-radius:5px;font-size:8px;color:var(--t2);line-height:1.45}
.chain-hint code{color:var(--ac3);font-family:inherit;font-weight:700}

/* REFINE BOX */
.rfb{max-width:700px;margin:0 auto 10px;background:var(--s1);border:1px solid var(--bd);border-radius:6px;overflow:hidden;animation:mi .2s}
.rfh{padding:8px 12px;background:var(--sf);border-bottom:1px solid var(--bd);display:flex;align-items:center;justify-content:space-between;font-size:10px;font-weight:600}
.rfh .sp{display:inline-block;animation:sp .7s linear infinite}
@keyframes sp{to{transform:rotate(360deg)}}
.rfh .sub{font-size:8px;color:var(--t3);margin-left:5px;font-weight:400}
.rfs{padding:2px 6px;background:none;border:1px solid var(--bd);border-radius:2px;color:var(--t3);font-size:8px;cursor:pointer;font-family:inherit}
.rfs:hover{border-color:var(--rd);color:var(--rd)}
.rfp{padding:5px 12px;border-bottom:1px solid rgba(255,255,255,.01)}
.pb{height:2px;background:var(--bd);border-radius:1px;overflow:hidden;margin-bottom:2px}
.pf{height:100%;border-radius:1px;background:var(--ac);transition:width .3s}
.rpi{display:flex;justify-content:space-between;font-size:7px;color:var(--t3)}
.rpi .sc{font-weight:800}
.sc-h{color:var(--gn)}.sc-m{color:var(--am)}.sc-l{color:var(--rd)}
.rv{border-bottom:1px solid rgba(255,255,255,.01)}
.rvh{padding:5px 12px;display:flex;align-items:center;justify-content:space-between;cursor:pointer;font-size:9px}
.rvh:hover{background:rgba(255,255,255,.01)}
.rvh .vn{font-weight:800;color:var(--ac3);margin-right:4px}
.rvh .vs{font-weight:800;font-size:8px}
.rvb{padding:0 12px 8px;font-size:10px;line-height:1.6;display:none}
.rvb.op{display:block}
.rve{margin-top:4px;padding:4px 6px;background:rgba(239,68,68,.03);border-left:2px solid var(--rd);font-size:8px;color:rgba(239,68,68,.6)}
.rvi{margin-top:2px;padding:4px 6px;background:rgba(34,197,94,.03);border-left:2px solid var(--gn);font-size:8px;color:rgba(34,197,94,.6)}
.rfd{padding:6px 12px;background:var(--sf);border-top:1px solid var(--bd);font-size:9px;color:var(--t3)}


/* Account modal + builders */
.modal{display:none;position:fixed;inset:0;z-index:80;background:rgba(0,0,0,.72);align-items:center;justify-content:center;padding:18px;animation:fi .18s ease}
.modal.show{display:flex}
.card{width:min(420px,100%);background:var(--s1);border:1px solid var(--bd);border-radius:10px;box-shadow:0 24px 80px rgba(0,0,0,.45);overflow:hidden}
.card-h{padding:14px 16px;border-bottom:1px solid var(--bd);display:flex;align-items:center;justify-content:space-between}
.card-h b{font-size:13px}.card-h button{background:none;border:1px solid var(--bd);color:var(--t3);border-radius:4px;padding:2px 7px;cursor:pointer}
.card-b{padding:14px 16px}.card-b label{display:block;font-size:9px;color:var(--t3);font-weight:800;text-transform:uppercase;letter-spacing:.6px;margin:8px 0 4px}
.card-b input{width:100%;padding:9px 10px;background:var(--sf);border:1px solid var(--bd);border-radius:6px;color:var(--t1);outline:none;font-family:inherit;font-size:12px}
.card-b input:focus{border-color:var(--ac3)}.card-b small{display:block;color:var(--t3);font-size:8px;margin-top:8px;line-height:1.5}
.card-actions{display:flex;gap:8px;margin-top:12px}.card-actions button{flex:1;padding:8px;background:var(--ac2);border:none;border-radius:6px;color:#fff;font-size:11px;font-weight:800;cursor:pointer;font-family:inherit}.card-actions .ghost{background:transparent;border:1px solid var(--bd);color:var(--t2)}
.builders{max-width:440px;width:100%;margin:0 0 10px;display:grid;grid-template-columns:repeat(3,1fr);gap:6px}.build{padding:9px 8px;background:linear-gradient(180deg,var(--sf),rgba(18,22,27,.75));border:1px solid var(--bd);border-radius:6px;text-align:left;cursor:pointer;transition:.15s}.build:hover{border-color:var(--ac3);transform:translateY(-1px)}.build b{display:block;font-size:9px;color:var(--t1);margin-bottom:2px}.build span{font-size:7px;color:var(--t3);line-height:1.3}
.mem-row{display:flex;gap:4px;margin-top:6px}.mem-row input{flex:1;padding:6px;background:var(--sf);border:1px solid var(--bd);border-radius:4px;color:var(--t1);font-size:10px;outline:none}.mem-row button,.mi button{padding:3px 6px;background:var(--sf2);border:1px solid var(--bd);border-radius:3px;color:var(--t2);font-size:8px;cursor:pointer;font-family:inherit}.mi{display:flex;align-items:center;justify-content:space-between;gap:5px}.mi.off span{opacity:.42;text-decoration:line-through}.mi-actions{display:flex;gap:3px;flex-shrink:0}.mem-toggle{display:flex;align-items:center;justify-content:space-between;margin-bottom:6px;font-size:9px;color:var(--t2)}
@media(max-width:520px){.builders{grid-template-columns:1fr}.attach-btn{width:28px;height:28px}.img-chip{width:44px;height:44px}}

/* RESPONSIVE */
@media(max-width:1024px){.sb{position:absolute;height:100%}}
@media(max-width:768px){
.sb{width:240px}.hb small{display:none}.hd .ms,.exp-btn{max-width:80px;font-size:7px}
.m-b{max-width:88%}.m-c{padding:7px 10px;font-size:11px}.sgs{grid-template-columns:1fr}
.msg{gap:5px;margin-bottom:10px}.av{width:20px;height:20px;font-size:8px;border-radius:3px}
.ia{padding:8px 10px}.ib{padding:6px 8px}.ib textarea{font-size:11px}.sb2{width:30px;height:30px;font-size:11px}
.wel h2{font-size:16px}.wel>p{font-size:10px;max-width:300px}
.cmds{max-width:300px}.cm{font-size:8px;padding:4px 6px}.sg{padding:6px}.sg b{font-size:8px}.sg span{font-size:7px}
.m-c pre code{font-size:9px}.cpb{font-size:6px}
}
@media(max-width:480px){
.sb{width:100%}.sb.shut{transform:translateX(-100%)}.sb:not(.shut){width:100%}
.hd{padding:5px 8px}.hm{width:26px;height:26px;font-size:11px}.hb{font-size:11px}
.hd .ms{display:none}.exp-btn{display:none}
.cc{padding:10px 6px}.m-b{max-width:92%}.m-c{padding:6px 8px;font-size:10.5px;line-height:1.6;border-radius:5px}
.ia{padding:6px}.ib{padding:5px 7px;border-radius:5px}.ib textarea{font-size:10.5px}
.sb2{width:28px;height:28px;font-size:10px;border-radius:4px}
.if span{font-size:6px}.cb{font-size:6px}
.wel{padding:0 6px}.wel h2{font-size:14px}.wel>p{font-size:9px;max-width:260px}
.cmds{max-width:260px;gap:2px}.cm{font-size:7px;padding:3px 5px}.sgs{max-width:260px;gap:3px}
.msg{gap:4px;margin-bottom:8px}.av{width:18px;height:18px;font-size:7px}
}
