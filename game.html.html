<!DOCTYPE html>
<html lang="nl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>ΘΗΡΕΥΤΗΣ · ΟΛΥΜΠΙΑ</title>
<link href="https://fonts.googleapis.com/css2?family=Lilita+One&family=Nunito:wght@700;800;900&family=Cinzel:wght@400;700;900&family=Cinzel+Decorative:wght@700&display=swap" rel="stylesheet">
<style>
*{margin:0;padding:0;box-sizing:border-box;}
body{font-family:'Lilita One',cursive;background:#050510;overflow:hidden;width:100vw;height:100vh;}



.screen{position:fixed;inset:0;display:none;z-index:10;}
.screen.active{display:flex;}

/* ── BUTTONS ── */
.gold-btn{background:linear-gradient(160deg,#ffe84a,#ffb700,#ff8c00);border:none;border-radius:14px;padding:0;cursor:pointer;box-shadow:0 5px 0 #7a4000,0 0 18px rgba(255,180,0,.4);font-family:'Lilita One',cursive;transition:all .15s;}
.gold-btn:hover{transform:translateY(-3px);box-shadow:0 8px 0 #7a4000,0 0 30px rgba(255,200,0,.7);}
.gold-btn:active{transform:translateY(2px);box-shadow:0 2px 0 #7a4000;}
.gold-btn-inner{padding:11px 28px;border-radius:12px;background:linear-gradient(180deg,rgba(255,255,255,.22)0%,transparent 45%);}
.gold-btn-text{color:#3d1a00;font-size:16px;letter-spacing:1px;}

/* ══════════════════════════════════
   LOBBY SCREEN
══════════════════════════════════ */
#screen-lobby{flex-direction:column;align-items:center;background:radial-gradient(ellipse at 50% 60%,#1a3a1a 0%,#0d1f0d 30%,#050514 70%,#02020c 100%);}
#lobby-bg-glow{position:absolute;inset:0;background:radial-gradient(ellipse 70% 55% at 50% 55%,rgba(30,180,30,.22) 0%,transparent 70%);animation:glowpulse 3s ease-in-out infinite;pointer-events:none;}
@keyframes glowpulse{0%,100%{opacity:.7}50%{opacity:1}}
#lobby-stars{position:absolute;inset:0;pointer-events:none;}
.lobby-pillar{position:absolute;bottom:0;width:34px;opacity:.12;background:linear-gradient(90deg,#c9b89a,#e8dcc8,#c9b89a);border-radius:4px 4px 0 0;}
.lobby-pillar::before{content:'';position:absolute;top:-12px;left:-6px;right:-6px;height:13px;background:linear-gradient(90deg,#c9b89a,#e8dcc8,#c9b89a);border-radius:3px;}

/* TOP BAR */
#lobby-topbar{width:100%;display:flex;align-items:center;justify-content:space-between;padding:8px 12px;flex-shrink:0;position:relative;z-index:5;background:linear-gradient(180deg,rgba(0,0,0,.65)0%,transparent 100%);}
.lb-player{display:flex;align-items:center;gap:8px;}
.lb-avatar{width:42px;height:42px;border-radius:50%;background:linear-gradient(135deg,#3a7bd5,#2c5aa0);border:3px solid #FFD700;display:flex;align-items:center;justify-content:center;font-size:20px;box-shadow:0 0 10px rgba(255,215,0,.4);}
.lb-name{color:#fff;font-size:14px;text-shadow:-1px -1px 0 #000,1px -1px 0 #000,-1px 1px 0 #000,1px 1px 0 #000;}
.lb-trophies{display:flex;align-items:center;gap:6px;background:rgba(0,0,0,.55);border:2px solid #555;border-radius:20px;padding:4px 12px;}
.lb-trophies span{color:#FFD700;font-size:13px;font-family:'Nunito',sans-serif;font-weight:900;}
.lb-coins{display:flex;align-items:center;gap:5px;background:rgba(0,0,0,.55);border:2px solid #555;border-radius:20px;padding:4px 12px;color:#FFD700;font-size:13px;font-family:'Nunito',sans-serif;font-weight:900;}
#season-bar{display:flex;align-items:center;gap:8px;position:relative;z-index:5;margin-top:2px;}
.season-badge{background:linear-gradient(145deg,#1a2a4a,#0d1830);border:2px solid #2a6aaa;border-radius:10px;padding:4px 12px;display:flex;align-items:center;gap:5px;color:#fff;font-size:11px;}
.season-badge .num{color:#FFD700;font-size:15px;font-family:'Nunito',sans-serif;font-weight:900;}
.trophy-road{display:flex;align-items:center;gap:5px;background:linear-gradient(145deg,#1a2a4a,#0d1830);border:2px solid #2a6aaa;border-radius:10px;padding:4px 12px;cursor:pointer;transition:all .2s;}
.trophy-road:hover{border-color:#FFD700;}
.trophy-road span{color:#FFD700;font-family:'Nunito',sans-serif;font-weight:900;font-size:13px;}

/* CENTER */
#lobby-center{flex:1;display:flex;position:relative;width:100%;overflow:hidden;}
#left-panel{width:90px;display:flex;flex-direction:column;gap:6px;padding:8px 6px;z-index:5;}
.lp-btn{display:flex;flex-direction:column;align-items:center;background:linear-gradient(145deg,#1a2a4a,#0d1830);border:2px solid #2a4a8a;border-radius:12px;padding:7px 4px;cursor:pointer;transition:all .2s;box-shadow:0 4px 0 #08101e;position:relative;}
.lp-btn:hover{transform:translateY(-3px);border-color:#FFD700;}
.lp-btn:active{transform:translateY(1px);}
.lp-icon{font-size:26px;}
.lp-label{color:#fff;font-size:9px;font-family:'Nunito',sans-serif;font-weight:900;letter-spacing:.5px;margin-top:2px;}
.lp-badge{position:absolute;top:-5px;right:-5px;background:#e74c3c;color:#fff;width:18px;height:18px;border-radius:50%;font-size:9px;display:flex;align-items:center;justify-content:center;border:2px solid #fff;font-family:'Nunito',sans-serif;font-weight:900;}

/* STAGE */
#stage{flex:1;position:relative;display:flex;flex-direction:column;align-items:center;justify-content:flex-end;padding-bottom:4px;}
#char-display{position:relative;width:300px;height:300px;margin-bottom:8px;cursor:pointer;}
.char-glow{position:absolute;bottom:-8px;left:50%;transform:translateX(-50%);width:200px;height:40px;background:radial-gradient(ellipse,rgba(50,200,50,.55),transparent);border-radius:50%;animation:glowpulse 2s ease-in-out infinite;}
.cartoon-char{position:absolute;inset:0;display:flex;align-items:center;justify-content:center;opacity:0;transition:opacity .4s,transform .4s;transform:scale(.85);pointer-events:none;}
.cartoon-char.active{opacity:1;transform:scale(1.35);pointer-events:all;animation:charfloat 3s ease-in-out infinite;}
@keyframes charfloat{0%,100%{transform:scale(1.35) translateY(0)}50%{transform:scale(1.35) translateY(-10px)}}

/* LEMON */
.lemon-body{position:relative;width:110px;height:130px;}
.lemon-torso{position:absolute;bottom:30px;left:50%;transform:translateX(-50%);width:70px;height:75px;background:linear-gradient(160deg,#ffe566,#ffd200,#e6b800);border-radius:40% 40% 35% 35%;border:3px solid #333;box-shadow:inset -8px -6px 0 rgba(0,0,0,.12),inset 3px 3px 0 rgba(255,255,255,.3);}
.lemon-arm{position:absolute;width:18px;height:42px;background:linear-gradient(180deg,#ffe566,#ffd200);border-radius:10px;border:3px solid #333;top:28px;}
.lemon-arm.left{left:-12px;transform:rotate(20deg);transform-origin:top center;}
.lemon-arm.right{right:-12px;transform:rotate(-20deg);transform-origin:top center;animation:armwave 2s ease-in-out infinite;}
@keyframes armwave{0%,100%{transform:rotate(-20deg)}50%{transform:rotate(-40deg)}}
.lemon-hand{position:absolute;bottom:-6px;left:50%;transform:translateX(-50%);width:14px;height:14px;background:#ffe566;border-radius:50%;border:2px solid #333;}
.lemon-leg{position:absolute;bottom:0;width:22px;height:34px;background:linear-gradient(180deg,#ffe566,#ffd200);border-radius:4px;border:3px solid #333;}
.lemon-leg.left{left:10px;}.lemon-leg.right{right:10px;}
.lemon-foot{position:absolute;bottom:-6px;width:28px;height:12px;background:#a0522d;border-radius:6px;border:2px solid #333;}
.lemon-foot.left{left:-3px;}.lemon-foot.right{right:-3px;}
.lemon-head{position:absolute;top:0;left:50%;transform:translateX(-50%);width:60px;height:60px;background:radial-gradient(circle at 35% 35%,#fff3a0,#ffe566,#ffd200);border-radius:45% 45% 40% 40%;border:3px solid #333;box-shadow:inset -6px -5px 0 rgba(0,0,0,.1);}
.lemon-head::after{content:'';position:absolute;top:-8px;left:50%;transform:translateX(-50%);width:10px;height:12px;background:#7cb518;border-radius:50% 50% 0 0;border:2px solid #333;}
.lemon-eye{position:absolute;top:20px;width:10px;height:11px;background:#222;border-radius:50%;}
.lemon-eye::after{content:'';position:absolute;top:1px;left:2px;width:3px;height:3px;background:#fff;border-radius:50%;}
.lemon-eye.left{left:11px;}.lemon-eye.right{right:11px;}
.lemon-brow{position:absolute;top:13px;height:3px;width:12px;background:#333;border-radius:2px;}
.lemon-brow.left{left:10px;transform:rotate(-5deg);}.lemon-brow.right{right:10px;transform:rotate(5deg);}
.lemon-mouth{position:absolute;bottom:12px;left:50%;transform:translateX(-50%);width:18px;height:8px;border:3px solid #333;border-top:none;border-radius:0 0 10px 10px;}
.lemon-crown{position:absolute;top:-14px;left:50%;transform:translateX(-50%);width:68px;height:20px;display:flex;align-items:flex-end;justify-content:center;gap:3px;}
.laurel-leaf{width:8px;height:14px;background:#4a9e0e;border-radius:50% 50% 30% 30%;border:1.5px solid #2d6b0a;transform-origin:bottom center;}
.laurel-leaf:nth-child(1){transform:rotate(-40deg)}.laurel-leaf:nth-child(2){transform:rotate(-20deg);height:17px}.laurel-leaf:nth-child(3){transform:rotate(-5deg);height:18px}.laurel-leaf:nth-child(4){transform:rotate(5deg);height:18px}.laurel-leaf:nth-child(5){transform:rotate(20deg);height:17px}.laurel-leaf:nth-child(6){transform:rotate(40deg)}
.lemon-sword{position:absolute;right:-28px;top:20px;width:8px;height:65px;background:linear-gradient(180deg,#ddd,#aaa,#888);border:2px solid #333;border-radius:2px;transform:rotate(15deg);}
.lemon-sword::before{content:'';position:absolute;top:-8px;left:-4px;right:-4px;height:12px;background:#888;clip-path:polygon(50% 0,100% 100%,0 100%);border-radius:2px;}
.lemon-sword::after{content:'';position:absolute;top:18px;left:-10px;width:28px;height:6px;background:#cd7f32;border:2px solid #333;border-radius:2px;}

/* ZEUS */
.zeus-body{position:relative;width:120px;height:140px;}
.zeus-torso{position:absolute;bottom:35px;left:50%;transform:translateX(-50%);width:74px;height:80px;background:linear-gradient(160deg,#e8e0d0,#d4c9a8,#c0b48a);border-radius:35% 35% 30% 30%;border:3px solid #333;box-shadow:inset -8px -6px 0 rgba(0,0,0,.12),inset 4px 4px 0 rgba(255,255,255,.4);}
.zeus-torso::before{content:'';position:absolute;inset:0;background:repeating-linear-gradient(160deg,transparent,transparent 6px,rgba(150,130,80,.2) 6px,rgba(150,130,80,.2) 8px);border-radius:inherit;}
.zeus-torso::after{content:'';position:absolute;top:8px;left:10px;width:16px;height:16px;background:radial-gradient(circle,gold,#d4a017);border-radius:50%;border:2px solid #333;}
.zeus-arm{position:absolute;width:20px;height:45px;background:linear-gradient(180deg,#c8a878,#a88858);border-radius:10px;border:3px solid #333;top:25px;}
.zeus-arm.left{left:-13px;transform:rotate(25deg);transform-origin:top center;}
.zeus-arm.right{right:-13px;transform:rotate(-35deg);transform-origin:top center;}
.zeus-hand{position:absolute;bottom:-7px;left:50%;transform:translateX(-50%);width:14px;height:14px;background:#c8a878;border-radius:50%;border:2px solid #333;}
.zeus-leg{position:absolute;bottom:0;width:24px;height:38px;background:linear-gradient(180deg,#c8a878,#a88858);border-radius:4px;border:3px solid #333;}
.zeus-leg.left{left:10px;}.zeus-leg.right{right:10px;}
.zeus-sandal{position:absolute;bottom:-7px;width:30px;height:12px;background:#8b4513;border-radius:6px;border:2px solid #333;}
.zeus-sandal::before{content:'';position:absolute;top:-4px;left:2px;right:2px;height:3px;background:#6b3410;border-radius:2px;box-shadow:0 -5px 0 #6b3410;}
.zeus-sandal.left{left:-3px;}.zeus-sandal.right{right:-3px;}
.zeus-head{position:absolute;top:0;left:50%;transform:translateX(-50%);width:64px;height:64px;background:radial-gradient(circle at 35% 35%,#ffd8a8,#e8b878,#c8a060);border-radius:50%;border:3px solid #333;box-shadow:inset -7px -6px 0 rgba(0,0,0,.12);}
.zeus-beard{position:absolute;bottom:-10px;left:50%;transform:translateX(-50%);width:48px;height:22px;background:linear-gradient(180deg,#e8e8e8,#ccc);border-radius:0 0 40% 40%;border:3px solid #333;border-top:none;overflow:hidden;}
.zeus-beard::before{content:'';position:absolute;inset:0;background:repeating-linear-gradient(90deg,transparent,transparent 5px,rgba(180,180,180,.4) 5px,rgba(180,180,180,.4) 7px);}
.zeus-hair{position:absolute;top:-6px;left:50%;transform:translateX(-50%);width:72px;height:26px;background:linear-gradient(180deg,#f0f0f0,#ccc);border-radius:50% 50% 0 0;border:3px solid #333;}
.zeus-eye{position:absolute;top:22px;width:10px;height:11px;background:#333;border-radius:50%;}
.zeus-eye::after{content:'';position:absolute;top:1px;left:2px;width:3px;height:3px;background:#fff;border-radius:50%;}
.zeus-eye.left{left:10px;}.zeus-eye.right{right:10px;}
.zeus-eyebrow{position:absolute;top:14px;height:4px;width:14px;background:#888;border-radius:2px;}
.zeus-eyebrow.left{left:9px;transform:rotate(-8deg);}.zeus-eyebrow.right{right:9px;transform:rotate(8deg);}
.zeus-crown{position:absolute;top:-16px;left:50%;transform:translateX(-50%);width:60px;height:22px;background:linear-gradient(180deg,#ffd700,#b8860b);border:2px solid #333;border-radius:4px;clip-path:polygon(0 100%,8% 50%,0 0,12% 30%,20% 0,28% 35%,33% 0,42% 40%,50% 0,58% 40%,67% 0,72% 35%,80% 0,88% 30%,100% 0,92% 50%,100% 100%);}
.zeus-bolt{position:absolute;right:-32px;top:10px;width:16px;height:60px;animation:boltglow 1s ease-in-out infinite;}
@keyframes boltglow{0%,100%{filter:drop-shadow(0 0 4px #ffe000)}50%{filter:drop-shadow(0 0 14px #ffaa00) drop-shadow(0 0 22px #ffaa00)}}
.zeus-bolt-shape{width:100%;height:100%;background:linear-gradient(180deg,#ffe000,#ffa500,#ff6600);clip-path:polygon(60% 0%,100% 35%,65% 35%,100% 65%,40% 65%,0% 100%,35% 65%,0% 35%,35% 35%);}

/* MEDUSA */
.medusa-body{position:relative;width:120px;height:140px;}
.medusa-torso{position:absolute;bottom:28px;left:50%;transform:translateX(-50%);width:68px;height:82px;background:linear-gradient(160deg,#7b2d8b,#5a1f6e,#3d1050);border-radius:35% 35% 50% 50%/30% 30% 60% 60%;border:3px solid #333;box-shadow:inset -8px -8px 0 rgba(0,0,0,.2),inset 4px 4px 0 rgba(180,100,220,.2);}
.medusa-tail{position:absolute;bottom:-30px;left:50%;transform:translateX(-50%);width:48px;height:50px;background:linear-gradient(180deg,#5a1f6e,#3d1050,#2a0c36);border-radius:30% 30% 50% 50%;border:3px solid #333;border-top:none;}
.medusa-tail::after{content:'';position:absolute;bottom:-14px;left:50%;transform:translateX(-50%);width:36px;height:16px;background:linear-gradient(135deg,#4a1a5e,#2a0c36);clip-path:polygon(0 0,50% 100%,100% 0);border-bottom:3px solid #333;}
.medusa-arm{position:absolute;width:18px;height:46px;background:linear-gradient(180deg,#7b2d8b,#5a1f6e);border-radius:10px;border:3px solid #333;top:20px;}
.medusa-arm.left{left:-11px;transform:rotate(30deg);transform-origin:top center;}
.medusa-arm.right{right:-11px;transform:rotate(-30deg);transform-origin:top center;}
.medusa-hand{position:absolute;bottom:-7px;left:50%;transform:translateX(-50%);width:13px;height:13px;background:#7b2d8b;border-radius:50%;border:2px solid #333;}
.medusa-head{position:absolute;top:0;left:50%;transform:translateX(-50%);width:64px;height:64px;background:radial-gradient(circle at 35% 35%,#c5e8b0,#8ecb6e,#60a040);border-radius:50%;border:3px solid #333;box-shadow:inset -7px -6px 0 rgba(0,0,0,.15);}
.medusa-eye{position:absolute;top:22px;width:12px;height:12px;background:radial-gradient(circle,#ff4400,#cc2200);border-radius:50%;border:2px solid #333;animation:medusaglow 2s ease-in-out infinite;}
@keyframes medusaglow{0%,100%{box-shadow:0 0 4px #ff4400}50%{box-shadow:0 0 14px #ff6600,0 0 25px rgba(255,80,0,.5)}}
.medusa-eye::after{content:'';position:absolute;top:1px;left:2px;width:3px;height:3px;background:rgba(255,255,255,.6);border-radius:50%;}
.medusa-eye.left{left:10px;}.medusa-eye.right{right:10px;}
.medusa-mouth{position:absolute;bottom:12px;left:50%;transform:translateX(-50%);width:20px;height:10px;border:3px solid #333;border-top:none;border-radius:0 0 12px 12px;background:#c0303a;}
.snake-hair{position:absolute;top:-20px;left:50%;transform:translateX(-50%);width:80px;height:36px;}
.snake{position:absolute;bottom:0;width:10px;height:28px;background:linear-gradient(180deg,#4db848,#2e8b57);border-radius:5px 5px 0 0;border:2px solid #333;transform-origin:bottom center;animation:snakewiggle 1.5s ease-in-out infinite;}
.snake::after{content:'';position:absolute;top:-5px;left:50%;transform:translateX(-50%);width:10px;height:10px;background:radial-gradient(circle at 40% 40%,#5ee855,#2e8b57);border-radius:50%;border:2px solid #333;}
.snake:nth-child(1){left:2px;height:20px;animation-delay:.0s}.snake:nth-child(2){left:12px;height:26px;animation-delay:.2s}.snake:nth-child(3){left:22px;height:30px;animation-delay:.4s}.snake:nth-child(4){left:32px;height:32px;animation-delay:.6s}.snake:nth-child(5){left:42px;height:30px;animation-delay:.4s}.snake:nth-child(6){left:52px;height:26px;animation-delay:.2s}.snake:nth-child(7){left:62px;height:20px;animation-delay:.0s}
@keyframes snakewiggle{0%,100%{transform-origin:bottom center}50%{transform:scaleX(-1)}}
.medusa-shield{position:absolute;left:-38px;top:20px;width:32px;height:38px;background:radial-gradient(circle at 40% 35%,#888,#555);border-radius:40% 40% 50% 50%;border:3px solid #333;display:flex;align-items:center;justify-content:center;font-size:14px;}

/* ATHENA */
.athena-body{position:relative;width:120px;height:140px;}
.athena-torso{position:absolute;bottom:35px;left:50%;transform:translateX(-50%);width:72px;height:78px;background:linear-gradient(160deg,#e8c840,#c9a227,#a07818);border-radius:35% 35% 30% 30%;border:3px solid #333;box-shadow:inset -8px -6px 0 rgba(0,0,0,.15),inset 4px 4px 0 rgba(255,240,100,.3);}
.athena-torso::after{content:'Ω';position:absolute;top:14px;left:50%;transform:translateX(-50%);font-size:20px;color:#ffe066;text-shadow:0 0 6px #c9a227;}
.athena-arm{position:absolute;width:18px;height:44px;background:linear-gradient(180deg,#e8c840,#c9a227);border-radius:10px;border:3px solid #333;top:24px;}
.athena-arm.left{left:-12px;transform:rotate(22deg);transform-origin:top center;}
.athena-arm.right{right:-12px;transform:rotate(-30deg);transform-origin:top center;animation:athenaarm 2.2s ease-in-out infinite;}
@keyframes athenaarm{0%,100%{transform:rotate(-30deg)}50%{transform:rotate(-50deg)}}
.athena-hand{position:absolute;bottom:-6px;left:50%;transform:translateX(-50%);width:13px;height:13px;background:#f5d9a0;border-radius:50%;border:2px solid #333;}
.athena-leg{position:absolute;bottom:0;width:22px;height:36px;background:linear-gradient(180deg,#e8c840,#c9a227);border-radius:4px;border:3px solid #333;}
.athena-leg.left{left:11px;}.athena-leg.right{right:11px;}
.athena-sandal{position:absolute;bottom:-7px;width:28px;height:11px;background:#8b4513;border-radius:6px;border:2px solid #333;}
.athena-sandal.left{left:-3px;}.athena-sandal.right{right:-3px;}
.athena-head{position:absolute;top:0;left:50%;transform:translateX(-50%);width:62px;height:62px;background:radial-gradient(circle at 35% 35%,#fde8c0,#f5d9a0,#e0b870);border-radius:50%;border:3px solid #333;box-shadow:inset -7px -6px 0 rgba(0,0,0,.12);}
.athena-eye{position:absolute;top:21px;width:10px;height:11px;background:#3a86ff;border-radius:50%;border:2px solid #333;}
.athena-eye::after{content:'';position:absolute;top:1px;left:2px;width:3px;height:3px;background:#fff;border-radius:50%;}
.athena-eye.left{left:11px;}.athena-eye.right{right:11px;}
.athena-mouth{position:absolute;bottom:12px;left:50%;transform:translateX(-50%);width:18px;height:8px;border:3px solid #a0522d;border-top:none;border-radius:0 0 10px 10px;}
.athena-helmet{position:absolute;top:-18px;left:50%;transform:translateX(-50%);width:68px;height:28px;background:linear-gradient(160deg,#e8c840,#c9a227);border-radius:50% 50% 10% 10%;border:3px solid #333;}
.athena-plume{position:absolute;top:-32px;left:50%;transform:translateX(-50%);width:14px;height:20px;background:linear-gradient(180deg,#e63946,#c1121f);border-radius:50% 50% 0 0;animation:plumesway 2s ease-in-out infinite;}
@keyframes plumesway{0%,100%{transform:translateX(-50%) rotate(-5deg)}50%{transform:translateX(-50%) rotate(5deg)}}
.athena-spear{position:absolute;right:-26px;top:10px;width:6px;height:80px;background:linear-gradient(180deg,#ddd,#c9a227,#888);border:2px solid #333;border-radius:2px;transform:rotate(8deg);}
.athena-spear::before{content:'';position:absolute;top:-10px;left:-3px;width:12px;height:14px;background:#ffe066;clip-path:polygon(50% 0,100% 100%,0 100%);border-radius:2px;}
.athena-shield{position:absolute;left:-38px;top:22px;width:30px;height:36px;background:radial-gradient(circle at 40% 35%,#e8c840,#c9a227,#a07818);border-radius:40% 40% 50% 50%;border:3px solid #333;display:flex;align-items:center;justify-content:center;font-size:12px;color:#ffe066;}

/* PELLE */
.pelle-body{position:relative;width:120px;height:140px;}
.pelle-torso{position:absolute;bottom:35px;left:50%;transform:translateX(-50%);width:72px;height:75px;background:linear-gradient(160deg,#f0a500,#e67e00,#c96800);border-radius:35% 35% 30% 30%;border:3px solid #333;box-shadow:inset -8px -6px 0 rgba(0,0,0,.12);}
.pelle-stripe{position:absolute;height:8px;left:0;right:0;background:rgba(0,0,0,.18);border-radius:2px;}
.pelle-stripe:nth-child(1){top:18px;}.pelle-stripe:nth-child(2){top:34px;}
.pelle-arm{position:absolute;width:18px;height:42px;background:linear-gradient(180deg,#ffe0b2,#ffcc80);border-radius:10px;border:3px solid #333;top:26px;}
.pelle-arm.left{left:-12px;transform:rotate(18deg);transform-origin:top center;}
.pelle-arm.right{right:-12px;transform:rotate(-22deg);transform-origin:top center;animation:pellearm 2s ease-in-out infinite;}
@keyframes pellearm{0%,100%{transform:rotate(-22deg)}50%{transform:rotate(-40deg)}}
.pelle-hand{position:absolute;bottom:-6px;left:50%;transform:translateX(-50%);width:14px;height:14px;background:#ffe0b2;border-radius:50%;border:2px solid #333;}
.pelle-leg{position:absolute;bottom:0;width:22px;height:34px;background:linear-gradient(180deg,#e67e00,#c96800);border-radius:4px;border:3px solid #333;}
.pelle-leg.left{left:10px;}.pelle-leg.right{right:10px;}
.pelle-foot{position:absolute;bottom:-6px;width:28px;height:11px;background:#5d4037;border-radius:6px;border:2px solid #333;}
.pelle-foot.left{left:-3px;}.pelle-foot.right{right:-3px;}
.pelle-head{position:absolute;top:14px;left:50%;transform:translateX(-50%);width:62px;height:62px;background:radial-gradient(circle at 35% 35%,#ffeac8,#ffe0b2,#ffcc80);border-radius:50%;border:3px solid #333;}
.pelle-blush{position:absolute;top:36px;width:11px;height:8px;background:#ffab91;border-radius:50%;opacity:.7;}
.pelle-blush.left{left:6px;}.pelle-blush.right{right:6px;}
.pelle-eye{position:absolute;top:18px;width:10px;height:12px;background:#1b5e20;border-radius:50%;border:2px solid #333;}
.pelle-eye::after{content:'';position:absolute;top:1px;left:2px;width:3px;height:3px;background:#fff;border-radius:50%;}
.pelle-eye.left{left:11px;}.pelle-eye.right{right:11px;}
.pelle-mouth{position:absolute;bottom:13px;left:50%;transform:translateX(-50%);width:18px;height:8px;border:3px solid #a0522d;border-top:none;border-radius:0 0 10px 10px;}
.pelle-pot{position:absolute;top:-40px;left:50%;transform:translateX(-50%);width:66px;height:26px;}
.pelle-pot-body{position:absolute;bottom:0;left:50%;transform:translateX(-50%);width:52px;height:20px;background:linear-gradient(160deg,#a0522d,#8b4513,#6d3410);border-radius:4px 4px 8px 8px;border:3px solid #333;}
.pelle-pot-rim{position:absolute;top:0;left:50%;transform:translateX(-50%);width:60px;height:12px;background:linear-gradient(180deg,#b5651d,#8b4513);border-radius:4px;border:3px solid #333;}
.pelle-soil{position:absolute;top:4px;left:50%;transform:translateX(-50%);width:46px;height:10px;background:#5d4037;border-radius:3px;}
.pelle-plant-stem{position:absolute;bottom:22px;left:50%;transform:translateX(-50%);width:4px;height:20px;background:#2e7d32;border:1.5px solid #1b5e20;}
.pelle-leaf{position:absolute;width:16px;height:16px;background:radial-gradient(circle at 30% 30%,#66bb6a,#2e7d32);border-radius:50% 50% 50% 0;border:2px solid #1b5e20;}
.pelle-leaf:nth-child(1){bottom:36px;left:calc(50% - 18px);transform:rotate(-40deg);}
.pelle-leaf:nth-child(2){bottom:42px;left:calc(50% + 2px);transform:rotate(30deg);}
.pelle-leaf:nth-child(3){bottom:50px;left:calc(50% - 8px);transform:rotate(-10deg);animation:leafsway 2s ease-in-out infinite;}
@keyframes leafsway{0%,100%{transform:rotate(-10deg)}50%{transform:rotate(10deg)}}

/* KONIJN */
.konijn-body{position:relative;width:120px;height:150px;}
.konijn-torso{position:absolute;bottom:40px;left:50%;transform:translateX(-50%);width:70px;height:70px;background:radial-gradient(ellipse at 50% 40%,#f8eaff,#f0d6ff,#e0aaff);border-radius:50% 50% 45% 45%;border:3px solid #9b59b6;}
.konijn-tummy{position:absolute;bottom:50px;left:50%;transform:translateX(-50%);width:40px;height:38px;background:#fff;border-radius:50%;opacity:.9;}
.konijn-arm{position:absolute;width:18px;height:36px;background:linear-gradient(180deg,#f0d6ff,#e0aaff);border-radius:10px;border:2px solid #9b59b6;top:32px;}
.konijn-arm.left{left:-10px;transform:rotate(20deg);transform-origin:top center;}
.konijn-arm.right{right:-10px;transform:rotate(-20deg);transform-origin:top center;animation:konijnarm 1.8s ease-in-out infinite;}
@keyframes konijnarm{0%,100%{transform:rotate(-20deg)}50%{transform:rotate(-38deg)}}
.konijn-hand{position:absolute;bottom:-5px;left:50%;transform:translateX(-50%);width:12px;height:12px;background:#f0d6ff;border-radius:50%;border:2px solid #9b59b6;}
.konijn-foot{position:absolute;bottom:6px;width:34px;height:13px;background:radial-gradient(ellipse,#f0d6ff,#e0aaff);border-radius:50%;border:2px solid #9b59b6;}
.konijn-foot.left{left:4px;}.konijn-foot.right{right:4px;}
.konijn-tail{position:absolute;bottom:46px;right:-4px;width:18px;height:18px;background:#fff;border-radius:50%;border:2px solid #ddd;}
.konijn-head{position:absolute;top:10px;left:50%;transform:translateX(-50%);width:68px;height:68px;background:radial-gradient(circle at 35% 35%,#fff5ff,#f0d6ff,#e0aaff);border-radius:50%;border:3px solid #9b59b6;}
.konijn-ear{position:absolute;top:-40px;width:18px;height:44px;background:linear-gradient(180deg,#f0d6ff,#e8d0ff);border-radius:9px 9px 0 0;border:2px solid #9b59b6;}
.konijn-ear-inner{position:absolute;top:4px;left:50%;transform:translateX(-50%);width:8px;height:34px;background:#f9a8d4;border-radius:5px 5px 0 0;}
.konijn-ear.left{left:12px;animation:eartwitch 3s ease-in-out infinite;}.konijn-ear.right{right:12px;animation:eartwitch 3s ease-in-out infinite .3s;}
@keyframes eartwitch{0%,90%,100%{transform:rotate(0deg)}92%{transform:rotate(-8deg)}95%{transform:rotate(5deg)}}
.konijn-eye{position:absolute;top:24px;width:12px;height:13px;background:radial-gradient(circle at 35% 35%,#a78bfa,#7c3aed);border-radius:50%;border:2px solid #333;}
.konijn-eye::after{content:'';position:absolute;top:1px;left:2px;width:4px;height:4px;background:rgba(255,255,255,.8);border-radius:50%;}
.konijn-eye.left{left:12px;}.konijn-eye.right{right:12px;}
.konijn-nose{position:absolute;top:40px;left:50%;transform:translateX(-50%);width:10px;height:8px;background:#f9a8d4;border-radius:50%;}
.konijn-mouth{position:absolute;bottom:16px;left:50%;transform:translateX(-50%);width:20px;height:10px;border:3px solid #d6a0c0;border-top:none;border-radius:0 0 12px 12px;}
.konijn-whisker{position:absolute;height:2px;background:#bbb;border-radius:1px;top:40px;}
.konijn-whisker.l1{width:20px;left:0;top:38px;transform:rotate(-5deg);}
.konijn-whisker.l2{width:20px;left:0;top:44px;transform:rotate(5deg);}
.konijn-whisker.r1{width:20px;right:0;top:38px;transform:rotate(5deg);}
.konijn-whisker.r2{width:20px;right:0;top:44px;transform:rotate(-5deg);}

/* KRONOS */
.kronos-body{position:relative;width:130px;height:155px;}
.kronos-cape{position:absolute;bottom:0;left:50%;transform:translateX(-50%);width:110px;height:110px;background:radial-gradient(ellipse at 50% 0%,#c62828,#8b0000,#4a0000);border-radius:10% 10% 50% 50%;border:3px solid #333;animation:capesway 2.5s ease-in-out infinite;}
@keyframes capesway{0%,100%{transform:translateX(-50%) scaleX(1)}50%{transform:translateX(-50%) scaleX(1.04)}}
.kronos-torso{position:absolute;bottom:50px;left:50%;transform:translateX(-50%);width:72px;height:75px;background:linear-gradient(160deg,#6a1a1a,#4a0e0e,#2d0808);border-radius:35% 35% 30% 30%;border:3px solid #333;box-shadow:inset -8px -6px 0 rgba(0,0,0,.2);}
.kronos-torso::after{content:'⏳';position:absolute;top:18px;left:50%;transform:translateX(-50%);font-size:18px;animation:hourglassglow 1.5s ease-in-out infinite;}
@keyframes hourglassglow{0%,100%{filter:drop-shadow(0 0 3px #ff6b35)}50%{filter:drop-shadow(0 0 10px #ff6b35) drop-shadow(0 0 18px #ff9a5e)}}
.kronos-armor{position:absolute;top:0;left:0;right:0;height:30px;background:linear-gradient(90deg,transparent,rgba(255,107,53,.3),transparent);border-radius:inherit;border-bottom:2px solid #ff6b35;}
.kronos-arm{position:absolute;width:20px;height:46px;background:linear-gradient(180deg,#c9a0a0,#a07070);border-radius:10px;border:3px solid #333;top:22px;}
.kronos-arm.left{left:-13px;transform:rotate(28deg);transform-origin:top center;}
.kronos-arm.right{right:-13px;transform:rotate(-32deg);transform-origin:top center;}
.kronos-hand{position:absolute;bottom:-7px;left:50%;transform:translateX(-50%);width:14px;height:14px;background:#c9a0a0;border-radius:50%;border:2px solid #333;}
.kronos-leg{position:absolute;bottom:0;width:24px;height:38px;background:linear-gradient(180deg,#4a0e0e,#2d0808);border-radius:4px;border:3px solid #333;}
.kronos-leg.left{left:10px;}.kronos-leg.right{right:10px;}
.kronos-boot{position:absolute;bottom:-8px;width:30px;height:13px;background:#1a0808;border-radius:6px;border:2px solid #333;}
.kronos-boot.left{left:-3px;}.kronos-boot.right{right:-3px;}
.kronos-head{position:absolute;top:0;left:50%;transform:translateX(-50%);width:66px;height:66px;background:radial-gradient(circle at 35% 35%,#d4a0a0,#c09080,#a07060);border-radius:50%;border:3px solid #333;box-shadow:inset -7px -6px 0 rgba(0,0,0,.15);}
.kronos-eye{position:absolute;top:20px;width:12px;height:12px;background:radial-gradient(circle,#ff4400,#cc0000);border-radius:50%;border:2px solid #333;animation:kronosglow 1.2s ease-in-out infinite;}
@keyframes kronosglow{0%,100%{box-shadow:0 0 4px #ff4400}50%{box-shadow:0 0 14px #ff6600,0 0 24px rgba(255,60,0,.5)}}
.kronos-eye::after{content:'';position:absolute;top:1px;left:2px;width:3px;height:3px;background:rgba(255,255,255,.5);border-radius:50%;}
.kronos-eye.left{left:11px;}.kronos-eye.right{right:11px;}
.kronos-brow{position:absolute;top:13px;height:4px;width:14px;background:#4a1a00;border-radius:2px;}
.kronos-brow.left{left:10px;transform:rotate(-12deg);}.kronos-brow.right{right:10px;transform:rotate(12deg);}
.kronos-beard{position:absolute;bottom:-12px;left:50%;transform:translateX(-50%);width:50px;height:22px;background:linear-gradient(180deg,#5d3a1a,#3d2010);border-radius:0 0 40% 40%;border:3px solid #333;border-top:none;}
.kronos-beard::before{content:'';position:absolute;inset:0;background:repeating-linear-gradient(90deg,transparent,transparent 4px,rgba(100,60,20,.3) 4px,rgba(100,60,20,.3) 6px);border-radius:inherit;}
.kronos-crown{position:absolute;top:-16px;left:50%;transform:translateX(-50%);width:62px;height:22px;background:linear-gradient(180deg,#c9a227,#8b6914);border:2px solid #333;border-radius:4px;clip-path:polygon(0 100%,8% 50%,0 0,15% 35%,25% 0,35% 40%,50% 0,65% 40%,75% 0,85% 35%,100% 0,92% 50%,100% 100%);animation:crownglow 2s ease-in-out infinite;}
@keyframes crownglow{0%,100%{filter:drop-shadow(0 0 4px #c9a227)}50%{filter:drop-shadow(0 0 12px #ffe066)}}
.kronos-scythe{position:absolute;right:-34px;top:5px;width:8px;height:90px;background:linear-gradient(180deg,#ccc,#888);border:2px solid #333;border-radius:3px;transform:rotate(6deg);}
.kronos-scythe::before{content:'';position:absolute;top:-2px;right:-2px;width:28px;height:32px;background:linear-gradient(135deg,#c9a227,#ffe066);clip-path:polygon(0 0,100% 20%,80% 100%,20% 80%);border:2px solid #8b6914;border-radius:4px 40% 4px 0;}

/* CHAR SELECTOR */
#char-selector{display:flex;gap:8px;padding:4px 0;z-index:5;position:relative;}
.char-thumb{width:58px;height:64px;background:linear-gradient(145deg,#1a2a4a,#0d1830);border:2px solid #2a4a8a;border-radius:12px;cursor:pointer;transition:all .2s;display:flex;flex-direction:column;align-items:center;justify-content:center;gap:2px;overflow:hidden;position:relative;box-shadow:0 4px 0 #08101e;}
.char-thumb:hover{border-color:#FFD700;transform:translateY(-3px) scale(1.05);}
.char-thumb.selected{border-color:#FFD700;box-shadow:0 0 14px rgba(255,215,0,.6),0 4px 0 #6b5500;}
.char-thumb-icon{font-size:28px;}
.char-thumb-name{color:#fff;font-size:8px;font-family:'Nunito',sans-serif;font-weight:900;letter-spacing:.5px;}
.char-thumb::before{content:'';position:absolute;inset:0;background:linear-gradient(180deg,rgba(255,255,255,.08)0%,transparent 50%);border-radius:inherit;}

/* BOTTOM BAR */
#lobby-bottom{display:flex;align-items:flex-end;padding:4px 10px 10px;gap:8px;background:linear-gradient(0deg,rgba(0,0,0,.65)0%,transparent 100%);flex-shrink:0;position:relative;z-index:5;width:100%;}
#mode-display{flex:1;background:linear-gradient(145deg,#0d1428,#060e1e);border:2px solid #1a3060;border-radius:14px;padding:8px 12px;display:flex;align-items:center;gap:10px;cursor:pointer;transition:all .2s;box-shadow:0 4px 0 #030812;}
#mode-display:hover{border-color:#4a90ff;transform:translateY(-2px);}
.mode-icon-big{font-size:28px;}
.mode-name-big{color:#fff;font-size:14px;text-shadow:-1px -1px 0 #000,1px -1px 0 #000,-1px 1px 0 #000,1px 1px 0 #000;}
.mode-sub{color:#aac8ff;font-size:10px;font-family:'Nunito',sans-serif;font-weight:700;margin-top:1px;}
#start-btn{width:135px;background:linear-gradient(160deg,#ffe84a,#ffb700,#ff8c00);border:none;border-radius:16px;padding:0;cursor:pointer;box-shadow:0 6px 0 #804400,0 0 22px rgba(255,180,0,.5);transition:all .15s;animation:startpulse 1.5s ease-in-out infinite;}
@keyframes startpulse{0%,100%{box-shadow:0 6px 0 #804400,0 0 22px rgba(255,180,0,.5)}50%{box-shadow:0 6px 0 #804400,0 0 44px rgba(255,200,0,.9),0 0 70px rgba(255,150,0,.3)}}
#start-btn:hover{transform:translateY(-4px);animation:none;box-shadow:0 10px 0 #804400,0 0 44px rgba(255,200,0,.8);}
#start-btn:active{transform:translateY(3px);box-shadow:0 3px 0 #804400;}
.start-inner{padding:12px 0 10px;border-radius:14px;background:linear-gradient(180deg,rgba(255,255,255,.25)0%,transparent 40%);display:flex;flex-direction:column;align-items:center;}
.start-text{font-size:18px;color:#3d1a00;letter-spacing:1px;}
.start-sub{font-family:'Nunito',sans-serif;font-weight:900;font-size:9px;color:rgba(60,20,0,.7);letter-spacing:2px;}

/* ══════════════════════════════════
   BRAWLERS SCREEN
══════════════════════════════════ */
#screen-brawlers{flex-direction:column;background:#1565C0;overflow:hidden;}
.bs-topbar{display:flex;align-items:center;justify-content:space-between;padding:10px 14px;background:rgba(0,0,60,.3);flex-shrink:0;}
.bs-back{width:42px;height:42px;background:linear-gradient(145deg,#1a2a6a,#0d1840);border:2px solid #4a70cc;border-radius:12px;cursor:pointer;display:flex;align-items:center;justify-content:center;font-size:20px;transition:all .2s;box-shadow:0 3px 0 #06081a;}
.bs-back:hover{transform:translateY(-2px);border-color:#FFD700;}
.bs-title{font-family:'Lilita One',cursive;font-size:20px;color:#fff;text-shadow:-1px -1px 0 #000,1px -1px 0 #000,-1px 1px 0 #000,1px 1px 0 #000;display:flex;align-items:center;gap:6px;}
.bs-title span{color:#FFD700;}
.bs-coins-bar{display:flex;align-items:center;gap:5px;background:rgba(0,0,0,.4);border:2px solid #555;border-radius:16px;padding:4px 12px;color:#FFD700;font-size:13px;font-family:'Nunito',sans-serif;font-weight:900;}
.brawlers-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:10px;padding:12px;overflow-y:auto;flex:1;}
.brawler-card{background:linear-gradient(145deg,#1a2a5a,#0d1840);border:3px solid #2a4a9a;border-radius:16px;overflow:hidden;cursor:pointer;transition:all .25s;box-shadow:0 5px 0 #060a20;position:relative;}
.brawler-card:hover{transform:translateY(-5px);border-color:#FFD700;box-shadow:0 8px 0 #060a20,0 0 20px rgba(255,215,0,.3);}
.brawler-card.selected-brawler{border-color:#FFD700;box-shadow:0 0 20px rgba(255,215,0,.5),0 5px 0 #6b5500;}
.bc-top{padding:8px;display:flex;justify-content:space-between;align-items:flex-start;}
.bc-rang{background:linear-gradient(135deg,#ff8c00,#e65c00);color:#fff;border-radius:6px;padding:2px 6px;font-size:9px;font-family:'Nunito',sans-serif;font-weight:900;}
.bc-trophies{display:flex;align-items:center;gap:3px;color:#FFD700;font-size:12px;font-family:'Nunito',sans-serif;font-weight:900;}
.bc-portrait{height:120px;display:flex;align-items:center;justify-content:center;position:relative;overflow:hidden;}
.bc-bg-glow{position:absolute;inset:0;animation:glowpulse 2s ease-in-out infinite;}
.bc-char-wrap{transform:scale(.75);transform-origin:center;}
.bc-bottom{padding:8px;background:rgba(0,0,0,.2);}
.bc-name{color:#fff;font-size:13px;text-shadow:-1px -1px 0 #000,1px -1px 0 #000;margin-bottom:4px;}
.bc-kracht-row{display:flex;align-items:center;justify-content:space-between;}
.bc-kracht{color:#aac8ff;font-size:10px;font-family:'Nunito',sans-serif;font-weight:700;}
.bc-upgrade-btn{width:100%;margin-top:6px;background:linear-gradient(160deg,#44ff6a,#00c030,#009020);border:none;border-radius:10px;padding:0;cursor:pointer;box-shadow:0 4px 0 #004810;transition:all .15s;}
.bc-upgrade-btn:hover{transform:translateY(-2px);box-shadow:0 6px 0 #004810;}
.bc-upgrade-btn:active{transform:translateY(1px);box-shadow:0 2px 0 #004810;}
.bc-upgrade-btn:disabled{background:linear-gradient(160deg,#556,#334);box-shadow:0 4px 0 #111;cursor:not-allowed;}
.bc-upgrade-inner{padding:7px 0;border-radius:9px;background:linear-gradient(180deg,rgba(255,255,255,.2)0%,transparent 50%);}
.bc-upgrade-text{color:#002010;font-size:12px;}
.bc-progress-row{display:flex;align-items:center;justify-content:center;gap:4px;margin-top:6px;background:rgba(0,0,0,.3);border-radius:8px;padding:5px;}
.bc-prog-text{color:#fff;font-size:11px;font-family:'Nunito',sans-serif;font-weight:900;}

/* ══════════════════════════════════
   QUESTS SCREEN
══════════════════════════════════ */
#screen-quests{flex-direction:column;background:linear-gradient(160deg,#1a1a3a,#0a0a20);}
.qs-topbar{display:flex;align-items:center;justify-content:space-between;padding:10px 14px;background:rgba(0,0,0,.3);flex-shrink:0;}
.qs-title{font-size:20px;color:#FFD700;text-shadow:0 0 12px rgba(255,215,0,.4);}
.quests-list{flex:1;overflow-y:auto;padding:12px;display:flex;flex-direction:column;gap:10px;}
.quest-card{background:linear-gradient(145deg,#1a2040,#0d1428);border:2px solid #2a3a7a;border-radius:14px;padding:14px;display:flex;align-items:center;gap:12px;transition:all .2s;}
.quest-card.completed{border-color:#2ecc40;background:linear-gradient(145deg,#0a2010,#0a1808);}
.quest-card.claimable{border-color:#FFD700;background:linear-gradient(145deg,#2a1a00,#1a0e00);animation:questglow .8s ease-in-out infinite;}
@keyframes questglow{0%,100%{box-shadow:0 0 0 transparent}50%{box-shadow:0 0 20px rgba(255,215,0,.4)}}
.quest-icon{font-size:32px;flex-shrink:0;}
.quest-info{flex:1;}
.quest-title{color:#fff;font-size:14px;margin-bottom:3px;}
.quest-desc{color:#aac8ff;font-size:11px;font-family:'Nunito',sans-serif;font-weight:700;margin-bottom:6px;}
.quest-prog-bar{height:8px;background:rgba(255,255,255,.1);border-radius:8px;overflow:hidden;}
.quest-prog-fill{height:100%;border-radius:8px;background:linear-gradient(90deg,#4a90ff,#7b4fff);transition:width .5s;}
.quest-prog-fill.done{background:linear-gradient(90deg,#2ecc40,#1a9e2e);}
.quest-prog-text{color:#aaa;font-size:10px;font-family:'Nunito',sans-serif;font-weight:700;margin-top:3px;}
.quest-reward{display:flex;flex-direction:column;align-items:center;gap:3px;flex-shrink:0;}
.quest-reward-icon{font-size:22px;}
.quest-reward-val{color:#FFD700;font-size:12px;font-family:'Nunito',sans-serif;font-weight:900;}
.quest-claim-btn{background:linear-gradient(160deg,#ffe84a,#ffb700,#ff8c00);border:none;border-radius:10px;padding:6px 14px;cursor:pointer;font-family:'Lilita One',cursive;font-size:12px;color:#3d1a00;box-shadow:0 3px 0 #7a4000;transition:all .15s;}
.quest-claim-btn:hover{transform:translateY(-2px);}

/* ══════════════════════════════════
   MATCHMAKING MODAL
══════════════════════════════════ */
#modal-match{position:fixed;inset:0;z-index:200;background:rgba(0,0,0,.75);backdrop-filter:blur(10px);display:none;align-items:center;justify-content:center;}
#modal-match.show{display:flex;}
.mm-box{background:linear-gradient(145deg,#0d1428,#060e1e);border:3px solid #FFD700;border-radius:20px;padding:36px 30px;text-align:center;max-width:320px;width:90%;box-shadow:0 0 60px rgba(255,215,0,.4);transform:scale(.85);transition:transform .3s;}
#modal-match.show .mm-box{transform:scale(1);}
.mm-title{font-size:26px;color:#FFD700;margin-bottom:6px;text-shadow:0 0 20px rgba(255,215,0,.6);}
.mm-sub{color:#aaa;font-family:'Nunito',sans-serif;font-weight:700;font-size:13px;margin-bottom:16px;}
.mm-progress{background:rgba(255,255,255,.1);border-radius:20px;height:8px;overflow:hidden;margin-bottom:20px;}
.mm-fill{height:100%;width:0%;background:linear-gradient(90deg,#4a90ff,#7b4fff);border-radius:20px;transition:width .3s;}
.mm-cancel{background:rgba(255,255,255,.1);border:2px solid #444;border-radius:10px;padding:10px 26px;color:#fff;font-family:'Lilita One',cursive;font-size:14px;cursor:pointer;transition:all .2s;}
.mm-cancel:hover{background:rgba(231,76,60,.3);border-color:#e74c3c;}

/* RESULT MODAL */
#modal-result{position:fixed;inset:0;z-index:200;background:rgba(0,0,0,.8);backdrop-filter:blur(12px);display:none;align-items:center;justify-content:center;}
#modal-result.show{display:flex;}
.result-box{background:linear-gradient(145deg,#0d1428,#060e1e);border:3px solid #FFD700;border-radius:20px;padding:40px 40px;text-align:center;max-width:360px;width:90%;box-shadow:0 0 80px rgba(255,215,0,.5);}
.result-title{font-size:46px;margin-bottom:6px;animation:resultpop .5s cubic-bezier(.34,1.56,.64,1);}
@keyframes resultpop{0%{transform:scale(0)}100%{transform:scale(1)}}
.result-place{color:#fff;font-size:18px;margin-bottom:16px;}
.result-rewards{display:flex;justify-content:center;gap:20px;margin-bottom:24px;flex-wrap:wrap;}
.result-reward-item{display:flex;flex-direction:column;align-items:center;gap:4px;}
.result-reward-icon{font-size:28px;}
.result-reward-val{font-family:'Nunito',sans-serif;font-weight:900;font-size:16px;}
.result-reward-val.positive{color:#2ecc40;}
.result-reward-val.negative{color:#e74c3c;}
.result-continue-btn{background:linear-gradient(160deg,#ffe84a,#ffb700,#ff8c00);border:none;border-radius:14px;padding:12px 36px;font-family:'Lilita One',cursive;font-size:18px;color:#3d1a00;cursor:pointer;box-shadow:0 5px 0 #7a4000;transition:all .15s;}
.result-continue-btn:hover{transform:translateY(-3px);box-shadow:0 8px 0 #7a4000;}

/* TOAST */
#toast{position:fixed;bottom:110px;left:50%;transform:translateX(-50%);background:rgba(0,0,0,.88);border:2px solid #FFD700;border-radius:12px;padding:8px 20px;color:#fff;font-size:14px;z-index:500;opacity:0;transition:opacity .3s;white-space:nowrap;box-shadow:0 0 20px rgba(255,215,0,.3);pointer-events:none;}
#toast.show{opacity:1;}

/* ══════════════════════════════════
   BATTLE ROYALE GAME SCREEN
══════════════════════════════════ */
#screen-game{flex-direction:column;align-items:center;justify-content:center;background:linear-gradient(135deg,#1a4d2e,#2d5f3f,#3a7049);cursor:crosshair;}
#game-timer{font-family:'Cinzel',serif;color:#f4e4c1;font-size:20px;margin-bottom:8px;text-shadow:2px 2px 4px rgba(0,0,0,.7);}
.timer-warning{color:#ff4444!important;animation:timerpulse .5s ease-in-out infinite;}
@keyframes timerpulse{0%,100%{opacity:1}50%{opacity:.6}}
#game-hud{display:flex;justify-content:space-between;width:900px;max-width:95vw;margin-bottom:10px;font-family:'Cinzel',serif;color:#f4e4c1;font-size:16px;}
.g-stat{background:linear-gradient(135deg,rgba(139,69,19,.85),rgba(101,67,33,.85));padding:8px 16px;border:3px solid #d4af37;border-radius:3px;box-shadow:0 4px 8px rgba(0,0,0,.6),inset 0 1px 0 rgba(255,255,255,.2);font-size:14px;}
#game-canvas{border:4px solid #8b4513;box-shadow:0 0 30px rgba(139,69,19,.8);border-radius:4px;}
#game-instructions{margin-top:10px;color:#f4e4c1;text-align:center;font-size:12px;text-shadow:2px 2px 4px rgba(0,0,0,.7);}
#game-over-panel{display:none;position:fixed;top:50%;left:50%;transform:translate(-50%,-50%);background:linear-gradient(135deg,rgba(20,20,20,.98),rgba(40,30,20,.98));border:5px solid #d4af37;padding:40px 60px;border-radius:8px;text-align:center;font-family:'Cinzel',serif;box-shadow:0 0 60px rgba(212,175,55,.6);z-index:300;}
#game-over-panel h1{color:#d4af37;font-size:46px;margin-bottom:16px;}
#game-over-panel p{color:#f4e4c1;font-size:18px;margin-bottom:24px;}
#game-restart-btn{background:linear-gradient(135deg,#d4af37,#aa8a2e);border:3px solid #8b6914;color:#1a1a1a;padding:12px 36px;font-size:18px;font-family:'Cinzel',serif;font-weight:700;cursor:pointer;border-radius:4px;box-shadow:0 4px 12px rgba(0,0,0,.5);transition:all .3s;}
#game-restart-btn:hover{transform:translateY(-2px);box-shadow:0 6px 16px rgba(212,175,55,.8);}

/* ══════════════════════════════════
   SHOP SCREEN
══════════════════════════════════ */
#screen-shop{
  flex-direction:column;
  background:radial-gradient(ellipse at 50% 0%,#1a0e00 0%,#0a0600 60%,#000 100%);
  overflow:hidden;
  font-family:'Cinzel',serif;
}
.shop-meander{
  height:12px;flex-shrink:0;
  background:repeating-linear-gradient(90deg,#c9a227 0,#c9a227 8px,#0a0600 8px,#0a0600 16px,#c9a227 16px,#c9a227 20px,#0a0600 20px,#0a0600 24px);
}
#shop-header{
  display:flex;align-items:center;justify-content:space-between;
  padding:12px 16px 10px;
  background:linear-gradient(180deg,#1a0e00 0%,#2a1800 100%);
  border-bottom:3px solid #c9a227;
  box-shadow:0 4px 30px #c9a22760;
  flex-shrink:0;position:relative;z-index:5;
}
.shop-title-block{display:flex;flex-direction:column;gap:2px;}
.shop-label{font-size:10px;letter-spacing:4px;color:#c9a227;}
.shop-title{
  font-family:'Cinzel Decorative',serif;font-size:20px;font-weight:700;
  background:linear-gradient(135deg,#ffe066,#c9a227,#ff9a5e);
  -webkit-background-clip:text;-webkit-text-fill-color:transparent;
}
.shop-coins-box{
  display:flex;align-items:center;gap:10px;
  background:linear-gradient(135deg,#2a1800,#3d2200);
  border:2px solid #c9a227;border-radius:40px;
  padding:8px 18px;box-shadow:0 0 20px #c9a22740;
}
.shop-coins-box .sc-label{font-size:8px;color:#c9a227;letter-spacing:2px;font-family:'Nunito',sans-serif;font-weight:900;}
.shop-coins-box .sc-val{font-size:20px;font-weight:900;color:#ffe066;font-family:'Nunito',sans-serif;}
.shop-back-btn{
  width:40px;height:40px;border-radius:12px;border:2px solid #8b6914;
  background:linear-gradient(145deg,#2a1800,#1a0e00);
  cursor:pointer;display:flex;align-items:center;justify-content:center;
  font-size:18px;color:#c9a227;transition:all .2s;box-shadow:0 3px 0 #0a0600;
}
.shop-back-btn:hover{border-color:#ffe066;transform:translateY(-2px);}

#shop-section-label{
  text-align:center;padding:16px 0 8px;
  display:flex;align-items:center;justify-content:center;gap:14px;
  flex-shrink:0;
}
.shop-divider{flex:1;height:2px;background:linear-gradient(90deg,transparent,#c9a227);}
.shop-divider.r{background:linear-gradient(90deg,#c9a227,transparent);}
.shop-section-text{color:#c9a227;font-size:11px;letter-spacing:5px;text-transform:uppercase;}

#shop-grid{
  display:grid;
  grid-template-columns:repeat(auto-fill,minmax(160px,1fr));
  gap:16px;padding:0 16px 16px;
  overflow-y:auto;flex:1;
}

.shop-card{
  background:#0a0600;
  border:2px solid #3d2200;
  border-radius:18px;overflow:hidden;
  cursor:pointer;transition:all .25s cubic-bezier(.4,2,.5,1);
  position:relative;
}
.shop-card:hover{transform:translateY(-4px) scale(1.02);border-color:#c9a227;}
.shop-card.owned{border-color:#4caf50;box-shadow:0 0 16px #4caf5040;}
.shop-card.sc-selected{border-color:#ffe066;box-shadow:0 6px 30px #ffe06660,0 0 0 1px #ffe06640;}

.sc-rarity{
  position:absolute;top:8px;left:8px;
  border-radius:7px;padding:2px 7px;
  font-size:8px;font-weight:bold;letter-spacing:1px;
  font-family:'Nunito',sans-serif;
}
.sc-tag{
  position:absolute;top:8px;right:8px;
  border-radius:7px;padding:2px 7px;
  font-size:8px;font-weight:900;letter-spacing:2px;
  font-family:'Nunito',sans-serif;
}
.sc-owned-badge{
  position:absolute;bottom:60px;right:10px;
  background:#4caf5033;border:1px solid #4caf50;
  border-radius:50%;width:24px;height:24px;
  display:flex;align-items:center;justify-content:center;
  font-size:12px;color:#4caf50;font-weight:900;
}
.sc-portrait{
  height:120px;display:flex;align-items:flex-end;justify-content:center;
  padding-bottom:6px;position:relative;
}
.sc-portrait-glow{position:absolute;inset:0;border-radius:0;}
.sc-info{padding:8px 10px 10px;}
.sc-name{font-size:15px;font-weight:900;text-align:center;font-family:'Cinzel',serif;}
.sc-desc{font-size:9px;color:#a08060;text-align:center;font-style:italic;margin:3px 0 8px;font-family:'Nunito',sans-serif;}
.sc-buy-btn{
  width:100%;border-radius:24px;padding:8px 0;
  font-family:'Cinzel',serif;font-weight:700;font-size:12px;
  cursor:pointer;letter-spacing:1px;transition:all .2s;
  display:flex;align-items:center;justify-content:center;gap:6px;
  border:2px solid;
}
.sc-buy-btn:hover:not(:disabled){transform:scale(1.04);}
.sc-buy-btn:disabled{cursor:default;}

/* particle burst */
@keyframes shopParticle{
  0%{opacity:1;transform:translateY(0) scale(1);}
  100%{opacity:0;transform:translateY(-100px) scale(0.3);}
}

/* ══════════════════════════════════
   OLYMPIC RACE SCREEN
══════════════════════════════════ */
#screen-race{flex-direction:column;align-items:center;justify-content:center;background:#0d0703;cursor:crosshair;}
.greek-frame-inner{position:absolute;inset:0;z-index:1;pointer-events:none;border:5px solid #8b6914;box-shadow:inset 0 0 0 3px #c9a84c,inset 0 0 0 7px #8b6914,inset 0 0 0 11px #c9a84c;}
#race-hud{position:absolute;top:20px;left:50%;transform:translateX(-50%);z-index:20;display:flex;gap:2.5rem;align-items:center;font-family:'Cinzel',serif;font-size:.72rem;letter-spacing:2px;color:#c9a84c;}
.rhv{font-size:1.3rem;font-weight:700;color:#f0d080;}
#race-coolbar-bg{width:80px;height:8px;background:#2a1a0a;border:1px solid #8b6914;}
#race-coolbar{height:100%;width:100%;transition:width .1s;}
#aim-hint-race{position:absolute;bottom:28px;left:50%;transform:translateX(-50%);z-index:20;display:flex;gap:1.2rem;font-family:'Cinzel',serif;font-size:.65rem;letter-spacing:1.5px;color:#8b7355;}
.kh{background:rgba(201,168,76,0.08);border:1px solid #8b6914;padding:.2rem .6rem;}
</style>
</head>
<body>

<!-- ══════════════════════════════
     LOBBY SCREEN
══════════════════════════════ -->
<div id="screen-lobby" class="screen active">
  <div id="lobby-bg-glow"></div>
  <div id="lobby-stars"></div>
  <div class="lobby-pillar" style="left:4%;height:58%"></div>
  <div class="lobby-pillar" style="left:7%;height:68%"></div>
  <div class="lobby-pillar" style="right:4%;height:58%"></div>
  <div class="lobby-pillar" style="right:7%;height:68%"></div>

  <div id="lobby-topbar">
    <div class="lb-player">
      <div class="lb-avatar">🦅</div>
      <div><div class="lb-name">ΑΧΙΛΛΕΑΣ</div></div>
    </div>
    <div id="season-bar">
      <div class="season-badge">🏛️ SEIZOEN <span class="num">0</span></div>
      <div class="trophy-road">🏆 <span id="lobby-trophies">0</span></div>
    </div>
    <div style="display:flex;gap:8px;align-items:center;">
      <div class="lb-coins">🪙 <span id="lobby-coins">0</span></div>
    </div>
  </div>
  <!-- Music toggle — fixed top-right corner, away from start button -->
  <div id="music-toggle" style="
    position:absolute;top:10px;right:12px;z-index:20;
    width:36px;height:36px;border-radius:50%;
    background:rgba(0,0,0,.55);border:2px solid #555;
    display:flex;align-items:center;justify-content:center;
    font-size:16px;cursor:pointer;transition:all .2s;
    color:#FFD700;
  " title="Muziek aan/uit">🔊</div>

  <div id="lobby-center">
    <div id="left-panel">
      <div class="lp-btn" onclick="openScreen('brawlers')">
        <div class="lp-icon">⚔️</div>
        <div class="lp-label">κυνηγοί</div>
      </div>
      <div class="lp-btn" onclick="openScreen('quests')">
        <div class="lp-icon">📜</div>
        <div class="lp-label">QUESTS</div>
        <div class="lp-badge" id="quest-badge" style="display:none">!</div>
      </div>
      <div class="lp-btn" onclick="openScreen('shop')">
        <div class="lp-icon">🏪</div>
        <div class="lp-label">WINKEL</div>
      </div>
    </div>

    <div id="stage">
      <div id="char-display">
        <div class="char-glow"></div>
        <!-- Emoji fallback for shop chars -->
        <div id="char-emoji-fallback" class="cartoon-char" style="display:none;font-size:100px;animation:charfloat 3s ease-in-out infinite;">
          <span id="char-emoji-fallback-icon">🦉</span>
        </div>
        <div class="cartoon-char active" id="char-lemon">
          <div class="lemon-body">
            <div class="lemon-sword"></div>
            <div class="lemon-torso">
              <div class="lemon-arm left"><div class="lemon-hand"></div></div>
              <div class="lemon-arm right"><div class="lemon-hand"></div></div>
            </div>
            <div class="lemon-leg left"><div class="lemon-foot left"></div></div>
            <div class="lemon-leg right"><div class="lemon-foot right"></div></div>
            <div class="lemon-head">
              <div class="lemon-crown">
                <div class="laurel-leaf"></div><div class="laurel-leaf"></div>
                <div class="laurel-leaf"></div><div class="laurel-leaf"></div>
                <div class="laurel-leaf"></div><div class="laurel-leaf"></div>
              </div>
              <div class="lemon-brow left"></div><div class="lemon-brow right"></div>
              <div class="lemon-eye left"></div><div class="lemon-eye right"></div>
              <div class="lemon-mouth"></div>
            </div>
          </div>
        </div>
        <div class="cartoon-char" id="char-zeus">
          <div class="zeus-body">
            <div class="zeus-bolt"><div class="zeus-bolt-shape"></div></div>
            <div class="zeus-torso">
              <div class="zeus-arm left"><div class="zeus-hand"></div></div>
              <div class="zeus-arm right"><div class="zeus-hand"></div></div>
            </div>
            <div class="zeus-leg left"><div class="zeus-sandal left"></div></div>
            <div class="zeus-leg right"><div class="zeus-sandal right"></div></div>
            <div class="zeus-head">
              <div class="zeus-hair"></div><div class="zeus-crown"></div>
              <div class="zeus-eyebrow left"></div><div class="zeus-eyebrow right"></div>
              <div class="zeus-eye left"></div><div class="zeus-eye right"></div>
              <div class="zeus-beard"></div>
            </div>
          </div>
        </div>
        <div class="cartoon-char" id="char-medusa">
          <div class="medusa-body">
            <div class="medusa-shield">🐍</div>
            <div class="medusa-torso">
              <div class="medusa-arm left"><div class="medusa-hand"></div></div>
              <div class="medusa-arm right"><div class="medusa-hand"></div></div>
            </div>
            <div class="medusa-tail"></div>
            <div class="medusa-head">
              <div class="snake-hair">
                <div class="snake"></div><div class="snake"></div><div class="snake"></div>
                <div class="snake"></div><div class="snake"></div><div class="snake"></div>
                <div class="snake"></div>
              </div>
              <div class="medusa-eye left"></div><div class="medusa-eye right"></div>
              <div class="medusa-mouth"></div>
            </div>
          </div>
        </div>
        <div class="cartoon-char" id="char-athena">
          <div class="athena-body">
            <div class="athena-spear"></div>
            <div class="athena-shield">Ω</div>
            <div class="athena-torso">
              <div class="athena-arm left"><div class="athena-hand"></div></div>
              <div class="athena-arm right"><div class="athena-hand"></div></div>
            </div>
            <div class="athena-leg left"><div class="athena-sandal left"></div></div>
            <div class="athena-leg right"><div class="athena-sandal right"></div></div>
            <div class="athena-head">
              <div class="athena-helmet"><div class="athena-plume"></div></div>
              <div class="athena-eye left"></div><div class="athena-eye right"></div>
              <div class="athena-mouth"></div>
            </div>
          </div>
        </div>
        <div class="cartoon-char" id="char-pelle">
          <div class="pelle-body">
            <div class="pelle-torso">
              <div class="pelle-stripe"></div><div class="pelle-stripe"></div>
              <div class="pelle-arm left"><div class="pelle-hand"></div></div>
              <div class="pelle-arm right"><div class="pelle-hand"></div></div>
            </div>
            <div class="pelle-leg left"><div class="pelle-foot left"></div></div>
            <div class="pelle-leg right"><div class="pelle-foot right"></div></div>
            <div class="pelle-head">
              <div class="pelle-pot">
                <div class="pelle-plant-stem"></div>
                <div class="pelle-leaf"></div><div class="pelle-leaf"></div><div class="pelle-leaf"></div>
                <div class="pelle-pot-rim"></div>
                <div class="pelle-pot-body"></div>
                <div class="pelle-soil"></div>
              </div>
              <div class="pelle-blush left"></div><div class="pelle-blush right"></div>
              <div class="pelle-eye left"></div><div class="pelle-eye right"></div>
              <div class="pelle-mouth"></div>
            </div>
          </div>
        </div>
        <div class="cartoon-char" id="char-konijn">
          <div class="konijn-body">
            <div class="konijn-torso">
              <div class="konijn-tummy"></div>
              <div class="konijn-arm left"><div class="konijn-hand"></div></div>
              <div class="konijn-arm right"><div class="konijn-hand"></div></div>
            </div>
            <div class="konijn-foot left"></div>
            <div class="konijn-foot right"></div>
            <div class="konijn-tail"></div>
            <div class="konijn-head">
              <div class="konijn-ear left"><div class="konijn-ear-inner"></div></div>
              <div class="konijn-ear right"><div class="konijn-ear-inner"></div></div>
              <div class="konijn-eye left"></div><div class="konijn-eye right"></div>
              <div class="konijn-nose"></div>
              <div class="konijn-whisker l1"></div><div class="konijn-whisker l2"></div>
              <div class="konijn-whisker r1"></div><div class="konijn-whisker r2"></div>
              <div class="konijn-mouth"></div>
            </div>
          </div>
        </div>
        <div class="cartoon-char" id="char-kronos">
          <div class="kronos-body">
            <div class="kronos-scythe"></div>
            <div class="kronos-cape"></div>
            <div class="kronos-torso">
              <div class="kronos-armor"></div>
              <div class="kronos-arm left"><div class="kronos-hand"></div></div>
              <div class="kronos-arm right"><div class="kronos-hand"></div></div>
            </div>
            <div class="kronos-leg left"><div class="kronos-boot left"></div></div>
            <div class="kronos-leg right"><div class="kronos-boot right"></div></div>
            <div class="kronos-head">
              <div class="kronos-crown"></div>
              <div class="kronos-brow left"></div><div class="kronos-brow right"></div>
              <div class="kronos-eye left"></div><div class="kronos-eye right"></div>
              <div class="kronos-beard"></div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <div id="lobby-bottom">
    <div id="mode-display" onclick="cycleMode()">
      <div class="mode-icon-big" id="mode-icon">⚔️</div>
      <div style="flex:1">
        <div class="mode-name-big" id="mode-name">OLYMPOS GEVECHT</div>
        <div class="mode-sub" id="mode-sub">6 spelers · Battle Royale</div>
        <div style="color:#88aaff;font-size:10px;font-family:'Nunito',sans-serif;font-weight:700;">🔄 Druk om te wisselen</div>
      </div>
      <div style="color:#4a90ff;font-size:18px;">›</div>
    </div>
    <div id="start-btn" onclick="startMatchmaking()">
      <div class="start-inner">
        <div class="start-text">⚔ SPEEL NU</div>
        <div class="start-sub">START DE STRIJD</div>
      </div>
    </div>
  </div>
</div>

<!-- ══════════════════════════════
     BRAWLERS SCREEN
══════════════════════════════ -->
<div id="screen-brawlers" class="screen">
  <div class="bs-topbar">
    <div class="bs-back" onclick="openScreen('lobby')">◀</div>
    <div class="bs-title">κυνηγοί <span>3/3</span></div>
    <div class="bs-coins-bar">🪙 <span id="bs-coins">0</span></div>
  </div>
  <div class="brawlers-grid" id="brawlers-grid"></div>
</div>

<!-- ══════════════════════════════
     QUESTS SCREEN
══════════════════════════════ -->
<div id="screen-quests" class="screen">
  <div class="qs-topbar">
    <div class="bs-back" onclick="openScreen('lobby')">◀</div>
    <div class="qs-title">📜 QUESTS</div>
    <div class="bs-coins-bar">🪙 <span id="qs-coins">0</span></div>
  </div>
  <div class="quests-list" id="quests-list"></div>
</div>

<!-- ══════════════════════════════
     BATTLE ROYALE GAME SCREEN
══════════════════════════════ -->
<div id="screen-game" class="screen">
  <div id="game-timer">⏱️ TIJD: <span id="timeLeft">120</span>s</div>
  <div id="game-hud">
    <div class="g-stat">LEVEN: <span id="playerHealth">7</span></div>
    <div class="g-stat">PIJLEN: <span id="ammoCount">3</span></div>
    <div class="g-stat">VIJANDEN: <span id="botsAlive">5</span></div>
    <div class="g-stat" id="super-hud-br" style="position:relative;">
      SUPER: <span id="superReady">🔴</span>
      <div style="width:60px;height:6px;background:rgba(255,255,255,.2);border-radius:4px;margin-top:2px;display:inline-block;vertical-align:middle;">
        <div id="super-bar-br" style="height:100%;width:0%;background:linear-gradient(90deg,#ff6b35,#ffe066);border-radius:4px;transition:width .3s;"></div>
      </div>
    </div>
  </div>
  <canvas id="game-canvas" width="900" height="500"></canvas>
  <div id="game-instructions">🏛️ WASD/Pijltjes = bewegen | Klik = schieten | <b>Rechtsklik = SUPER</b></div>
  <div id="game-over-panel">
    <h1 id="game-over-title">GAME OVER</h1>
    <p id="game-over-msg"></p>
    <button id="game-restart-btn" onclick="showResult()">RESULTATEN BEKIJKEN</button>
  </div>
</div>

<!-- ══════════════════════════════
     OLYMPIC RACE SCREEN
══════════════════════════════ -->
<div id="screen-race" class="screen">
  <div class="greek-frame-inner"></div>
  <div id="race-hud" style="display:none;">
    <div style="text-align:center"><div style="font-family:'Cinzel',serif;font-size:.72rem;letter-spacing:2px;color:#c9a84c;">RONDE</div><div class="rhv"><span id="r-laps">0</span>/10</div></div>
    <div style="text-align:center"><div style="font-family:'Cinzel',serif;font-size:.72rem;letter-spacing:2px;color:#c9a84c;">PIJL</div><div id="race-coolbar-bg"><div id="race-coolbar"></div></div></div>
    <div style="text-align:center"><div style="font-family:'Cinzel',serif;font-size:.72rem;letter-spacing:2px;color:#c9a84c;">SUPER</div>
      <div id="race-super-bar-bg" style="width:50px;height:8px;background:rgba(255,255,255,.2);border-radius:4px;margin:2px auto 0;">
        <div id="race-super-bar" style="height:100%;width:0%;background:linear-gradient(90deg,#e0aaff,#7c3aed);border-radius:4px;transition:width .3s;"></div>
      </div>
      <div style="font-size:10px;color:#fff;" id="race-super-txt">0/3</div>
    </div>
    <div style="text-align:center"><div style="font-family:'Cinzel',serif;font-size:.72rem;letter-spacing:2px;color:#c9a84c;">TIJD</div><div class="rhv"><span id="r-time">0:00</span></div></div>
  </div>
  <div id="aim-hint-race" style="display:none;">
    <span class="kh">↑↓←→/WASD — BEWEGEN</span>
    <span class="kh">MUIS — RICHTEN</span>
    <span class="kh">KLIK — SCHIETEN</span>
    <span class="kh">RECHTSKLIK — SUPER</span>
  </div>
  <canvas id="race-canvas" style="position:relative;z-index:10;display:block;cursor:crosshair;"></canvas>
</div>

<!-- ══════════════════════════════
     SHOP SCREEN
══════════════════════════════ -->
<div id="screen-shop" class="screen">
  <div class="shop-meander"></div>
  <div id="shop-header">
    <div class="shop-back-btn" onclick="openScreen('lobby')">◀</div>
    <div class="shop-title-block">
      <div class="shop-label">⚡ OLYMPUS WINKEL ⚡</div>
      <div class="shop-title">GRIEKS GEVECHT</div>
    </div>
    <div class="shop-coins-box">
      <span style="font-size:22px;">🪙</span>
      <div>
        <div class="sc-label">MUNTJES</div>
        <div class="sc-val" id="shop-coins">0</div>
      </div>
    </div>
  </div>
  <div id="shop-section-label">
    <div class="shop-divider"></div>
    <span class="shop-section-text">⚔️ κυνηγοί ⚔️</span>
    <div class="shop-divider r"></div>
  </div>
  <div id="shop-grid"></div>
  <div class="shop-meander" style="margin-top:auto;flex-shrink:0;"></div>
</div>

<!-- MODALS -->
<div id="modal-match">
  <div class="mm-box">
    <div class="mm-title">⚡ ΘΗΡΕΥΤΗΣ</div>
    <div class="mm-sub" id="mm-char-name">Zoekt tegenstanders...</div>
    <div style="color:#fff;font-family:'Lilita One',cursive;font-size:15px;margin-bottom:12px;">Matchmaking<span id="mm-dots">...</span></div>
    <div class="mm-progress"><div class="mm-fill" id="mm-fill"></div></div>
    <button class="mm-cancel" onclick="cancelMatchmaking()">✖ Annuleer</button>
  </div>
</div>

<div id="modal-result">
  <div class="result-box">
    <div class="result-title" id="result-emoji">🏆</div>
    <div class="result-place" id="result-place"></div>
    <div style="color:#aac8ff;font-size:11px;font-family:'Nunito',sans-serif;font-weight:700;margin-bottom:12px;" id="result-mode-label"></div>
    <div class="result-rewards" id="result-rewards"></div>
    <button class="result-continue-btn" onclick="closeResult()">VERDER</button>
  </div>
</div>

<div id="toast"></div>

<!-- LOBBY MUSIC -->
<audio id="lobby-music" loop preload="auto">
  <source src="Mediterranean_Hold_Theme.mp3" type="audio/mpeg">
</audio>

<script>
/* ═══════════════════════════════════
   GAME STATE
═══════════════════════════════════ */
const GS = {
  coins: 0,
  trophies: 0,
  selectedBrawler: 'lemon',
  // All 7 brawlers — first 3 free, last 4 from shop
  brawlers: {
    lemon:   { name:'Caesar Citroen', emoji:'🍋', color:'#FFD700', trophies:0, level:0, totalKills:0, upgradeCost:1000, owned:true,  shopPrice:0     },
    zeusbr:  { name:'Zeus',           emoji:'⚡', color:'#88CCFF', trophies:0, level:0, totalKills:0, upgradeCost:1000, owned:true,  shopPrice:0     },
    medusa:  { name:'Medusa',         emoji:'🐍', color:'#88FF88', trophies:0, level:0, totalKills:0, upgradeCost:1000, owned:true,  shopPrice:0     },
    athena:  { name:'Athena',         emoji:'🦉', color:'#c9a227', trophies:0, level:0, totalKills:0, upgradeCost:1000, owned:false, shopPrice:1500  },
    pelle:   { name:'Pelle',          emoji:'🪴', color:'#4caf50', trophies:0, level:0, totalKills:0, upgradeCost:1000, owned:false, shopPrice:1500  },
    konijn:  { name:'Konijn',         emoji:'🐰', color:'#e0aaff', trophies:0, level:0, totalKills:0, upgradeCost:1000, owned:false, shopPrice:1500  },
    kronos:  { name:'Kronos',         emoji:'⏳', color:'#ff6b35', trophies:0, level:0, totalKills:0, upgradeCost:1000, owned:false, shopPrice:1500  },
  },
  quests: [
    { id:'q1', title:'Eerste Bloed',   desc:'Dood 3 tegenstanders in totaal',  icon:'⚔️',  goal:3,  current:0, reward:100, claimed:false, type:'kills', mode:'battle' },
    { id:'q2', title:'Overlevende',    desc:'Eindig 3 keer in de top 2',       icon:'🛡️',  goal:3,  current:0, reward:150, claimed:false, type:'top2',  mode:'any'    },
    { id:'q3', title:'Slachter',       desc:'Dood 10 tegenstanders in totaal', icon:'💀',  goal:10, current:0, reward:300, claimed:false, type:'kills', mode:'battle' },
    { id:'q4', title:'Winnaar',        desc:'Win 2 potjes (1e plek)',          icon:'🏆',  goal:2,  current:0, reward:200, claimed:false, type:'win',   mode:'battle' },
    { id:'q5', title:'Olympische Held',desc:'Win de Olympische Race',          icon:'🏃',  goal:1,  current:0, reward:250, claimed:false, type:'win',   mode:'race'   },
    { id:'q6', title:'Marathonloper',  desc:'Voltooi 3 races (elke positie)',  icon:'🏛️',  goal:3,  current:0, reward:180, claimed:false, type:'race',  mode:'race'   },
  ],
  lastKills: 0,
  lastPlacement: 0,
  currentMode: 0, // 0 = battle royale, 1 = olympic race
  lastGameMode: 0,
};

// ── QUEST POOL: alle mogelijke quests ──
const QUEST_POOL = [
  { id:'q1',  title:'Eerste Bloed',    desc:'Dood 3 tegenstanders in totaal',   icon:'⚔️',  goal:3,  reward:100, type:'kills',    mode:'battle' },
  { id:'q2',  title:'Overlevende',     desc:'Eindig 3 keer in de top 2',        icon:'🛡️',  goal:3,  reward:150, type:'top2',     mode:'any'    },
  { id:'q3',  title:'Slachter',        desc:'Dood 10 tegenstanders in totaal',  icon:'💀',  goal:10, reward:300, type:'kills',    mode:'battle' },
  { id:'q4',  title:'Winnaar',         desc:'Win 2 potjes (1e plek)',           icon:'🏆',  goal:2,  reward:200, type:'win',      mode:'battle' },
  { id:'q5',  title:'Olympische Held', desc:'Win de Olympische Race',           icon:'🏃',  goal:1,  reward:250, type:'win',      mode:'race'   },
  { id:'q6',  title:'Marathonloper',   desc:'Voltooi 3 races (elke positie)',   icon:'🏛️',  goal:3,  reward:180, type:'race',     mode:'race'   },
  { id:'q7',  title:'Super Smasher',   desc:'Gebruik je super 5 keer',          icon:'⚡',  goal:5,  reward:220, type:'super',    mode:'any'    },
  { id:'q8',  title:'Onsterfelijk',    desc:'Eindig 2x als 1e in gevecht',      icon:'🗡️',  goal:2,  reward:280, type:'win',      mode:'battle' },
  { id:'q9',  title:'Pijlenregen',     desc:'Raak 15 tegenstanders met pijlen', icon:'🏹',  goal:15, reward:200, type:'hits',     mode:'any'    },
  { id:'q10', title:'Razendsnelle Benen',desc:'Win 3 races op rij',             icon:'🦶',  goal:3,  reward:400, type:'winsrace', mode:'race'   },
  { id:'q11', title:'Dodelijke Super', desc:'Dood iemand met je super',         icon:'💥',  goal:1,  reward:350, type:'superkill',mode:'battle' },
  { id:'q12', title:'Volhardende Racer',desc:'Voltooi 5 races (elke positie)',  icon:'🌀',  goal:5,  reward:250, type:'race',     mode:'race'   },
];

function makeQuestInstance(template) {
  return { ...template, current: 0, claimed: false };
}

function refreshQuest(q) {
  // Pick a random quest from pool that is different from current active quests
  const activeIds = GS.quests.map(x => x.id);
  const available = QUEST_POOL.filter(p => p.id !== q.id && !activeIds.includes(p.id));
  const pick = available.length > 0 ? available[Math.floor(Math.random()*available.length)] : QUEST_POOL[Math.floor(Math.random()*QUEST_POOL.length)];
  return makeQuestInstance(pick);
}
// place: 1=+10, 2=+7, 3=+5, 4=+3, 5=-4, 6=-10
// Battle royale: 6 players. Race: 6 runners (player + 5 bots)
const TROPHY_MAP_BR   = {1:10, 2:7, 3:5, 4:3, 5:-4, 6:-10};
const TROPHY_MAP_RACE = {1:10, 2:7, 3:5, 4:3, 5:-4, 6:-10};

/* ═══════════════════════════════════
   SCREEN NAVIGATION
═══════════════════════════════════ */
function openScreen(name) {
  document.querySelectorAll('.screen').forEach(s => s.classList.remove('active'));
  document.getElementById('screen-' + name).classList.add('active');
  if (name === 'brawlers') renderBrawlers();
  if (name === 'quests')   renderQuests();
  if (name === 'shop')     renderShop();
  if (name === 'lobby')    updateLobbyUI();
}

/* ═══════════════════════════════════
   LOBBY
═══════════════════════════════════ */
const starsEl = document.getElementById('lobby-stars');
for(let i=0;i<70;i++){
  const s=document.createElement('div'),sz=Math.random()*2+.5;
  s.style.cssText=`position:absolute;border-radius:50%;background:#fff;width:${sz}px;height:${sz}px;top:${Math.random()*100}%;left:${Math.random()*100}%;animation:glowpulse ${2+Math.random()*3}s ease-in-out ${Math.random()*3}s infinite;`;
  starsEl.appendChild(s);
}

function updateLobbyUI() {
  document.getElementById('lobby-trophies').textContent = GS.trophies;
  document.getElementById('lobby-coins').textContent = GS.coins;
  updateQuestBadge();
}

function updateQuestBadge() {
  const claimable = GS.quests.some(q => !q.claimed && q.current >= q.goal);
  document.getElementById('quest-badge').style.display = claimable ? 'flex' : 'none';
}

const charData = {
  lemon:  'char-lemon',
  zeusbr: 'char-zeus',
  medusa: 'char-medusa',
  athena: 'char-athena',
  pelle:  'char-pelle',
  konijn: 'char-konijn',
  kronos: 'char-kronos',
};

function selectChar(name, thumbEl) {
  const b = GS.brawlers[name];
  if (!b) return;
  if (!b.owned) { showToast('Koop deze knokker eerst in de winkel! 🏪'); return; }
  document.querySelectorAll('.cartoon-char').forEach(c => c.classList.remove('active'));
  document.querySelectorAll('.char-thumb').forEach(t => t.classList.remove('selected'));
  const fallback = document.getElementById('char-emoji-fallback');
  fallback.style.display = 'none';
  const charEl = charData[name] ? document.getElementById(charData[name]) : null;
  if (charEl) charEl.classList.add('active');
  if (thumbEl) thumbEl.classList.add('selected');
  GS.selectedBrawler = name;
  renderCharSelector();
  showToast(b.name + ' geselecteerd!');
}

function renderCharSelector() {
  const sel = document.getElementById('char-selector');
  sel.innerHTML = '';
  Object.entries(GS.brawlers).forEach(([key, b]) => {
    const isSelected = GS.selectedBrawler === key;
    const div = document.createElement('div');
    div.className = 'char-thumb' + (isSelected ? ' selected' : '') + (!b.owned ? ' locked' : '');
    div.id = 'thumb-' + key;
    div.style.cssText = b.owned ? '' : 'opacity:0.5;filter:grayscale(0.6);';
    div.innerHTML = `<div class="char-thumb-icon">${b.emoji}</div><div class="char-thumb-name">${b.name.split(' ')[0].toUpperCase()}</div>${!b.owned ? '<div style="position:absolute;top:2px;right:3px;font-size:10px;">🔒</div>' : ''}`;
    div.onclick = () => selectChar(key, div);
    sel.appendChild(div);
  });
}

const modes = [
  {icon:'⚔️', name:'OLYMPOS GEVECHT', sub:'6 spelers · Battle Royale'},
  {icon:'🏃', name:'OLYMPISCHE RACE', sub:'6 deelnemers · 10 ronden · Pijlen schieten'},
];
function cycleMode() {
  GS.currentMode = (GS.currentMode + 1) % modes.length;
  const m = modes[GS.currentMode];
  document.getElementById('mode-icon').textContent = m.icon;
  document.getElementById('mode-name').textContent = m.name;
  document.getElementById('mode-sub').textContent = m.sub;
}

/* ═══════════════════════════════════
   MATCHMAKING
═══════════════════════════════════ */
let mmInterval, mmDotsRaf, mmPct = 0;
function startMatchmaking() {
  GS.lastGameMode = GS.currentMode;
  const modal = document.getElementById('modal-match');
  document.getElementById('mm-char-name').textContent = GS.brawlers[GS.selectedBrawler].name + ' is klaar voor strijd!';
  document.getElementById('mm-fill').style.width = '0%';
  modal.classList.add('show');
  mmPct = 0;
  mmInterval = setInterval(() => {
    mmPct = Math.min(mmPct + Math.random() * 9, 100);
    document.getElementById('mm-fill').style.width = mmPct + '%';
    if (mmPct >= 100) {
      clearInterval(mmInterval);
      cancelAnimationFrame(mmDotsRaf);
      modal.classList.remove('show');
      if (GS.currentMode === 1) startRaceGame();
      else startBattleRoyale();
    }
  }, 200);
  let d = 0;
  function dotAnim() {
    d = (d+1)%4;
    const el = document.getElementById('mm-dots');
    if(el) el.textContent = '.'.repeat(d+1);
    mmDotsRaf = requestAnimationFrame(dotAnim);
  }
  dotAnim();
}
function cancelMatchmaking() {
  clearInterval(mmInterval);
  cancelAnimationFrame(mmDotsRaf);
  document.getElementById('modal-match').classList.remove('show');
}

/* ═══════════════════════════════════
   BRAWLERS SCREEN
═══════════════════════════════════ */
function getBrawlerStats(key) {
  const lvl = GS.brawlers[key].level;
  return { power: 7 + lvl, ammo: Math.min(3 + Math.floor(lvl/3), 5), speed: 2.5 + lvl*.1 };
}
function renderBrawlers() {
  document.getElementById('bs-coins').textContent = GS.coins;
  const grid = document.getElementById('brawlers-grid');
  grid.innerHTML = '';
  for (const [key, b] of Object.entries(GS.brawlers)) {
    if (!b.owned) continue; // only owned in knokkers screen
    const isSelected = GS.selectedBrawler === key;
    const canUpgrade = GS.coins >= b.upgradeCost;
    const stats = getBrawlerStats(key);
    const card = document.createElement('div');
    card.className = 'brawler-card' + (isSelected ? ' selected-brawler' : '');
    card.innerHTML = `
      <div class="bc-top">
        <div class="bc-rang">RANG ${b.level}</div>
        <div class="bc-trophies">🏆 ${b.trophies}</div>
      </div>
      <div class="bc-portrait">
        <div class="bc-bg-glow" style="background:radial-gradient(ellipse 60% 50% at 50% 60%, ${b.color}33, transparent)"></div>
        <div class="bc-char-wrap"><div style="font-size:50px;line-height:1;">${b.emoji}</div></div>
      </div>
      <div class="bc-bottom">
        <div class="bc-name">${b.name}</div>
        <div class="bc-kracht-row">
          <div class="bc-kracht">💪 KRACHT ${stats.power}</div>
          <div class="bc-kracht">🏹 PIJLEN ${stats.ammo}</div>
        </div>
        ${b.level < 10
          ? `<button class="bc-upgrade-btn" ${canUpgrade ? '' : 'disabled'} onclick="upgradeBrawler('${key}')">
              <div class="bc-upgrade-inner"><div class="bc-upgrade-text">${canUpgrade ? '⬆️ UPGRADE' : '🔒 UPGRADE'}</div></div>
             </button>
             <div class="bc-progress-row"><div class="bc-prog-text">🪙 ${GS.coins}/${b.upgradeCost}</div></div>`
          : `<div class="bc-progress-row"><div class="bc-prog-text">✅ MAX LEVEL!</div></div>`
        }
      </div>`;
    card.addEventListener('click', () => {
      GS.selectedBrawler = key;
      selectChar(key, document.getElementById('thumb-' + key));
      renderBrawlers();
    });
    grid.appendChild(card);
  }
}
function upgradeBrawler(key) {
  const b = GS.brawlers[key];
  if (GS.coins < b.upgradeCost) return;
  GS.coins -= b.upgradeCost;
  b.level++;
  showToast(`${b.name} is nu Rang ${b.level}! 🎉`);
  renderBrawlers(); updateLobbyUI();
}

/* ═══════════════════════════════════
   SHOP
═══════════════════════════════════ */
const SHOP_FIGHTERS = [
  {
    key:'athena', rarity:'Episch', rarityColor:'#9c27b0', tag:'GODIN', tagColor:'#c9a227', tagGlow:'#ffe066',
    bg:'#1a1200', glowColor:'#ffe066',
    art:`<svg viewBox="0 0 100 110" width="85" height="94">
      <ellipse cx="50" cy="85" rx="22" ry="18" fill="#c9a227"/>
      <rect x="30" y="65" width="40" height="30" rx="10" fill="#c9a227"/>
      <path d="M30 70 Q50 60 70 70" stroke="#ffe066" stroke-width="2" fill="none"/>
      <circle cx="50" cy="42" r="22" fill="#f5d9a0"/>
      <ellipse cx="50" cy="24" rx="20" ry="10" fill="#c9a227"/>
      <rect x="30" y="20" width="40" height="8" rx="4" fill="#c9a227"/>
      <ellipse cx="50" cy="14" rx="6" ry="10" fill="#e63946"/>
      <circle cx="42" cy="44" r="4" fill="#fff"/><circle cx="58" cy="44" r="4" fill="#fff"/>
      <circle cx="43" cy="45" r="2.5" fill="#3a86ff"/><circle cx="59" cy="45" r="2.5" fill="#3a86ff"/>
      <path d="M44 54 Q50 59 56 54" stroke="#a0522d" stroke-width="1.5" fill="none" stroke-linecap="round"/>
      <line x1="75" y1="20" x2="68" y2="90" stroke="#c9a227" stroke-width="3"/>
      <polygon points="75,10 72,22 78,22" fill="#ffe066"/>
      <ellipse cx="30" cy="75" rx="11" ry="13" fill="#c9a227" stroke="#ffe066" stroke-width="2"/>
      <text x="24" y="79" font-size="10" fill="#ffe066">Ω</text>
    </svg>`
  },
  {
    key:'pelle', rarity:'Zeldzaam', rarityColor:'#2196f3', tag:'VREEMD', tagColor:'#4caf50', tagGlow:'#a5d6a7',
    bg:'#001a00', glowColor:'#a5d6a7',
    art:`<svg viewBox="0 0 100 110" width="85" height="94">
      <rect x="28" y="62" width="44" height="35" rx="12" fill="#f0a500"/>
      <rect x="28" y="70" width="44" height="5" rx="2" fill="#e67e00"/>
      <rect x="28" y="80" width="44" height="5" rx="2" fill="#e67e00"/>
      <circle cx="50" cy="50" r="22" fill="#ffe0b2"/>
      <ellipse cx="50" cy="28" rx="19" ry="8" fill="#b5651d"/>
      <rect x="31" y="22" width="38" height="10" rx="4" fill="#8b4513"/>
      <ellipse cx="50" cy="22" rx="16" ry="4" fill="#5d4037"/>
      <line x1="50" y1="22" x2="50" y2="8" stroke="#2e7d32" stroke-width="2.5"/>
      <circle cx="44" cy="10" r="5" fill="#43a047"/><circle cx="56" cy="8" r="4" fill="#66bb6a"/><circle cx="50" cy="5" r="4" fill="#81c784"/>
      <circle cx="43" cy="52" r="4.5" fill="#fff"/><circle cx="57" cy="52" r="4.5" fill="#fff"/>
      <circle cx="44" cy="53" r="2.5" fill="#1b5e20"/><circle cx="58" cy="53" r="2.5" fill="#1b5e20"/>
      <circle cx="37" cy="58" r="4" fill="#ffab91" opacity="0.6"/><circle cx="63" cy="58" r="4" fill="#ffab91" opacity="0.6"/>
      <path d="M44 63 Q50 68 56 63" stroke="#a0522d" stroke-width="1.5" fill="none" stroke-linecap="round"/>
      <circle cx="22" cy="75" r="7" fill="#ffe0b2"/><circle cx="78" cy="75" r="7" fill="#ffe0b2"/>
    </svg>`
  },
  {
    key:'konijn', rarity:'Gewoon', rarityColor:'#9e9e9e', tag:'SNEL', tagColor:'#e0aaff', tagGlow:'#d0b0ff',
    bg:'#0d0020', glowColor:'#d0b0ff',
    art:`<svg viewBox="0 0 100 120" width="85" height="102">
      <ellipse cx="36" cy="22" rx="8" ry="18" fill="#f0d6ff"/><ellipse cx="64" cy="22" rx="8" ry="18" fill="#f0d6ff"/>
      <ellipse cx="36" cy="22" rx="4" ry="13" fill="#f9a8d4"/><ellipse cx="64" cy="22" rx="4" ry="13" fill="#f9a8d4"/>
      <ellipse cx="50" cy="88" rx="25" ry="22" fill="#f0d6ff"/>
      <ellipse cx="50" cy="92" rx="14" ry="12" fill="#fff"/>
      <circle cx="50" cy="52" r="24" fill="#f0d6ff"/>
      <circle cx="41" cy="50" r="6" fill="#fff"/><circle cx="59" cy="50" r="6" fill="#fff"/>
      <circle cx="42" cy="51" r="3.5" fill="#7c3aed"/><circle cx="60" cy="51" r="3.5" fill="#7c3aed"/>
      <circle cx="43" cy="50" r="1.2" fill="#fff"/><circle cx="61" cy="50" r="1.2" fill="#fff"/>
      <ellipse cx="50" cy="60" rx="4" ry="3" fill="#f9a8d4"/>
      <line x1="25" y1="59" x2="44" y2="61" stroke="#aaa" stroke-width="1"/>
      <line x1="25" y1="63" x2="44" y2="63" stroke="#aaa" stroke-width="1"/>
      <line x1="56" y1="61" x2="75" y2="59" stroke="#aaa" stroke-width="1"/>
      <line x1="56" y1="63" x2="75" y2="63" stroke="#aaa" stroke-width="1"/>
      <path d="M46 65 Q50 69 54 65" stroke="#d6a0c0" stroke-width="1.5" fill="none" stroke-linecap="round"/>
      <ellipse cx="23" cy="84" rx="7" ry="10" fill="#f0d6ff"/><ellipse cx="77" cy="84" rx="7" ry="10" fill="#f0d6ff"/>
      <ellipse cx="37" cy="107" rx="11" ry="6" fill="#f0d6ff"/><ellipse cx="63" cy="107" rx="11" ry="6" fill="#f0d6ff"/>
      <circle cx="74" cy="98" r="8" fill="#fff"/>
    </svg>`
  },
  {
    key:'kronos', rarity:'Legendarisch', rarityColor:'#ff9800', tag:'TITAN', tagColor:'#ff6b35', tagGlow:'#ff9a5e',
    bg:'#1a0500', glowColor:'#ff9a5e',
    art:`<svg viewBox="0 0 100 120" width="85" height="102">
      <path d="M20 65 Q10 95 18 115 Q50 105 82 115 Q90 95 80 65 Z" fill="#b71c1c"/>
      <rect x="28" y="58" width="44" height="45" rx="10" fill="#4a0e0e"/>
      <path d="M28 65 Q50 55 72 65" stroke="#ff6b35" stroke-width="2" fill="none"/>
      <path d="M28 75 Q50 70 72 75" stroke="#ff6b35" stroke-width="1.5" fill="none"/>
      <circle cx="50" cy="40" r="24" fill="#c9a0a0"/>
      <path d="M30 50 Q35 70 50 68 Q65 70 70 50" fill="#7b3f00"/>
      <path d="M34 55 Q36 65 50 65 Q64 65 66 55" fill="#8b4513"/>
      <path d="M28 28 Q35 18 42 25 Q50 15 58 25 Q65 18 72 28" stroke="#c9a227" stroke-width="3" fill="none"/>
      <circle cx="50" cy="17" r="4" fill="#c9a227"/><circle cx="35" cy="22" r="3" fill="#c9a227"/><circle cx="65" cy="22" r="3" fill="#c9a227"/>
      <circle cx="41" cy="38" r="5" fill="#ff6b35"/><circle cx="59" cy="38" r="5" fill="#ff6b35"/>
      <circle cx="41" cy="38" r="3" fill="#fff"/><circle cx="59" cy="38" r="3" fill="#fff"/>
      <circle cx="41" cy="38" r="1.5" fill="#ff0000"/><circle cx="59" cy="38" r="1.5" fill="#ff0000"/>
      <path d="M36 32 L46 35" stroke="#5d2f00" stroke-width="2.5" stroke-linecap="round"/>
      <path d="M54 35 L64 32" stroke="#5d2f00" stroke-width="2.5" stroke-linecap="round"/>
      <line x1="80" y1="10" x2="72" y2="100" stroke="#888" stroke-width="4" stroke-linecap="round"/>
      <path d="M80 10 Q100 20 95 38 Q88 42 72 35" stroke="#c9a227" stroke-width="3" fill="#c9a227" opacity="0.8"/>
      <text x="42" y="85" font-size="14" fill="#ff6b35">⏳</text>
    </svg>`
  },
];

let shopParticles = [];
function renderShop() {
  document.getElementById('shop-coins').textContent = GS.coins.toLocaleString();
  const grid = document.getElementById('shop-grid');
  grid.innerHTML = '';
  SHOP_FIGHTERS.forEach(f => {
    const b = GS.brawlers[f.key];
    const isOwned = b.owned;
    const canAfford = GS.coins >= b.shopPrice;
    const isSelected = GS.selectedBrawler === f.key;
    const card = document.createElement('div');
    card.className = 'shop-card' + (isOwned ? ' owned' : '') + (isSelected ? ' sc-selected' : '');
    card.innerHTML = `
      <div class="sc-rarity" style="background:${f.rarityColor}33;border:1px solid ${f.rarityColor};color:${f.rarityColor};">${f.rarity}</div>
      <div class="sc-tag" style="background:${f.tagColor}22;border:1px solid ${f.tagColor};color:${f.tagGlow};">${f.tag}</div>
      ${isOwned ? '<div class="sc-owned-badge">✓</div>' : ''}
      <div class="sc-portrait" style="background:radial-gradient(ellipse at 50% 80%, ${f.glowColor}22 0%, ${f.bg} 70%);">
        ${f.art}
      </div>
      <div class="sc-info">
        <div class="sc-name" style="color:${f.glowColor};">${b.name}</div>
        <div class="sc-desc">${getShopDesc(f.key)}</div>
        <button class="sc-buy-btn" style="
          background:${isOwned ? 'linear-gradient(135deg,#1b5e20,#2e7d32)' : `linear-gradient(135deg,${f.bg},#2a1800)`};
          border-color:${isOwned ? '#4caf50' : f.tagColor};
          color:${isOwned ? '#a5d6a7' : f.glowColor};
          box-shadow:${isOwned ? 'none' : `0 0 12px ${f.tagColor}40`};
        " ${isOwned ? 'disabled' : ''} data-key="${f.key}">
          ${isOwned ? '✓ In bezit' : `<span style="font-size:14px;">🪙</span> ${b.shopPrice.toLocaleString()}`}
        </button>
      </div>`;
    card.querySelector('.sc-buy-btn').addEventListener('click', (e) => {
      e.stopPropagation();
      buyShopFighter(f.key);
    });
    card.addEventListener('click', () => {
      if (isOwned) {
        GS.selectedBrawler = f.key;
        selectChar(f.key, null);
        renderShop();
        showToast(b.name + ' geselecteerd!');
      }
    });
    grid.appendChild(card);
  });
}

function getShopDesc(key) {
  const descs = {
    athena:'Godin van wijsheid & strijd',
    pelle:'De jongen met de bloempot',
    konijn:'Het snelste konijn van Olympus',
    kronos:'God van de Tijd & Titanen',
  };
  return descs[key] || '';
}

function buyShopFighter(key) {
  const b = GS.brawlers[key];
  if (b.owned) { showToast(b.name + ' is al van jou!'); return; }
  if (GS.coins < b.shopPrice) { showToast('Niet genoeg muntjes! 💸 Speel meer potjes.', true); return; }
  GS.coins -= b.shopPrice;
  b.owned = true;
  // Particle burst
  triggerShopParticles();
  showToast(`${b.name} ontgrendeld! 🎉 Selecteer hem in de lobby.`);
  renderShop();
  updateLobbyUI();
  renderCharSelector();
}

function triggerShopParticles() {
  const container = document.getElementById('shop-grid');
  for(let i=0;i<14;i++){
    const p=document.createElement('div');
    p.style.cssText=`position:fixed;left:${30+Math.random()*40}%;top:${30+Math.random()*40}%;width:10px;height:10px;border-radius:50%;background:#ffe066;pointer-events:none;z-index:999;animation:shopParticle 1.1s ${Math.random()*.4}s ease-out forwards;`;
    document.body.appendChild(p);
    setTimeout(()=>p.remove(),1600);
  }
}

/* ═══════════════════════════════════
   QUESTS
═══════════════════════════════════ */
function renderQuests() {
  document.getElementById('qs-coins').textContent = GS.coins;
  const list = document.getElementById('quests-list');
  list.innerHTML = '';
  GS.quests.forEach(q => {
    const done = q.current >= q.goal;
    const pct = Math.min(100, (q.current/q.goal)*100);
    const card = document.createElement('div');
    card.className = 'quest-card' + (q.claimed ? ' completed' : done ? ' claimable' : '');
    card.innerHTML = `
      <div class="quest-icon">${q.icon}</div>
      <div class="quest-info">
        <div class="quest-title">${q.title}</div>
        <div class="quest-desc">${q.desc}</div>
        <div class="quest-prog-bar"><div class="quest-prog-fill ${q.claimed||done?'done':''}" style="width:${pct}%"></div></div>
        <div class="quest-prog-text">${q.claimed ? '✅ Voltooid!' : q.current+' / '+q.goal}</div>
      </div>
      <div class="quest-reward">
        <div class="quest-reward-icon">🪙</div>
        <div class="quest-reward-val">${q.reward}</div>
        ${!q.claimed && done ? `<button class="quest-claim-btn" onclick="claimQuest('${q.id}')">CLAIM!</button>` : ''}
      </div>`;
    list.appendChild(card);
  });
}
function claimQuest(id) {
  const idx = GS.quests.findIndex(x => x.id===id);
  if (idx<0) return;
  const q = GS.quests[idx];
  if (!q||q.claimed||q.current<q.goal) return;
  q.claimed = true; GS.coins += q.reward;
  showToast(`🎉 Quest klaar! +${q.reward} 🪙 Nieuwe quest verschijnt...`);
  // Auto-refresh after short delay
  setTimeout(() => {
    GS.quests[idx] = refreshQuest(q);
    renderQuests(); updateLobbyUI();
    showToast('✨ Nieuwe quest beschikbaar!');
  }, 1200);
  renderQuests(); updateLobbyUI();
}

/* ═══════════════════════════════════
   RESULT MODAL — unified for both modes
═══════════════════════════════════ */
function showResult(kills, place, mode) {
  // mode: 'battle' or 'race'
  document.getElementById('game-over-panel').style.display = 'none';

  const trophyMap = TROPHY_MAP_BR;
  const trophyDelta = trophyMap[place] || 0;
  const coinDelta = (place <= 2) ? 100 : 0;

  GS.trophies = Math.max(0, GS.trophies + trophyDelta);
  GS.coins += coinDelta;

  const b = GS.brawlers[GS.selectedBrawler];
  b.trophies = Math.max(0, b.trophies + trophyDelta);
  b.totalKills += kills;

  // Update quests
  updateQuestsAfterGame(kills, place, mode);

  const emojis = {1:'🏆',2:'🥈',3:'🥉',4:'4️⃣',5:'5️⃣',6:'6️⃣'};
  document.getElementById('result-emoji').textContent = emojis[place] || '💀';

  const totalPlayers = 6;
  document.getElementById('result-place').innerHTML = `<span style="color:#FFD700;font-family:'Nunito',sans-serif;font-weight:900;">PLEK ${place}</span> van ${totalPlayers}`;
  document.getElementById('result-mode-label').textContent = mode === 'race' ? '🏃 OLYMPISCHE RACE' : '⚔️ OLYMPOS GEVECHT';

  let html = `
    <div class="result-reward-item">
      <div class="result-reward-icon">🏆</div>
      <div class="result-reward-val ${trophyDelta >= 0 ? 'positive' : 'negative'}">${trophyDelta >= 0 ? '+' : ''}${trophyDelta}</div>
    </div>`;
  if (coinDelta > 0) html += `
    <div class="result-reward-item">
      <div class="result-reward-icon">🪙</div>
      <div class="result-reward-val positive">+${coinDelta}</div>
    </div>`;
  if (mode === 'battle') html += `
    <div class="result-reward-item">
      <div class="result-reward-icon">⚔️</div>
      <div class="result-reward-val positive">${kills} kills</div>
    </div>`;

  document.getElementById('result-rewards').innerHTML = html;
  document.getElementById('modal-result').classList.add('show');
  updateLobbyUI();
}

function updateQuestsAfterGame(kills, place, mode) {
  GS.quests.forEach(q => {
    if (q.claimed) return;
    if (q.type==='kills'    && mode==='battle')                       q.current = Math.min(q.goal, q.current + kills);
    if (q.type==='top2'     && place<=2)                              q.current = Math.min(q.goal, q.current + 1);
    if (q.type==='win'      && place===1 && mode==='battle')          q.current = Math.min(q.goal, q.current + 1);
    if (q.type==='win'      && place===1 && mode==='race')            q.current = Math.min(q.goal, q.current + 1);
    if (q.type==='race'     && mode==='race')                         q.current = Math.min(q.goal, q.current + 1);
    if (q.type==='winsrace' && place===1 && mode==='race')            q.current = Math.min(q.goal, q.current + 1);
  });
  updateQuestBadge();
}

function closeResult() {
  document.getElementById('modal-result').classList.remove('show');
  // Stop any running games
  raceRunning = false;
  gameRunning = false;
  openScreen('lobby');
}

/* ═══════════════════════════════════
   TOAST
═══════════════════════════════════ */
let toastTimer;
function showToast(msg, isError) {
  const t = document.getElementById('toast');
  t.textContent = msg;
  t.style.borderColor = isError ? '#f44' : '#FFD700';
  t.classList.add('show');
  clearTimeout(toastTimer);
  toastTimer = setTimeout(() => t.classList.remove('show'), 2500);
}

/* ═══════════════════════════════════════════════════════
   ██████╗  █████╗ ████████╗████████╗██╗     ███████╗
   ██╔══██╗██╔══██╗╚══██╔══╝╚══██╔══╝██║     ██╔════╝
   ██████╔╝███████║   ██║      ██║   ██║     █████╗
   ██╔══██╗██╔══██║   ██║      ██║   ██║     ██╔══╝
   ██████╔╝██║  ██║   ██║      ██║   ███████╗███████╗
   ROYALE GAME ENGINE
═══════════════════════════════════════════════════════ */
const brCanvas = document.getElementById('game-canvas');
const brCtx = brCanvas.getContext('2d');

const PLAYER_SPEED_BASE = 2.5, BOT_SPEED_BASE = 1.5, BULLET_SPEED = 8;
const MAX_SHOOT_DISTANCE = 350, SHOOT_COOLDOWN = 5000;
const ENTITY_RADIUS = 15, BULLET_RADIUS = 5;
const GAME_DURATION = 120000, TILE_SIZE = 30;
const MAP_W = Math.ceil(900/TILE_SIZE), MAP_H = Math.ceil(500/TILE_SIZE);

let terrainMap=[], buildings=[], lightningStrikes=[];
let brPlayer, brBots, brBullets, brMouseX=0, brMouseY=0, brKeys={};
let gameRunning=false, gameStartTime=0;
let zoneRadius, zoneCX=450, zoneCY=250;
let gameKills=0, playersAliveAtDeath=6;
let brRafId=null;

function generateTerrain() {
  terrainMap=[];
  for(let y=0;y<MAP_H;y++){terrainMap[y]=[];for(let x=0;x<MAP_W;x++)terrainMap[y][x]='land';}
  createWaterBody(3,2,4,5);createWaterBody(20,2,5,6);createWaterBody(22,12,4,4);
  addBeaches();addForests();
  buildings=[];
  [{x:230,y:90,w:60,h:50,type:'temple'},{x:600,y:200,w:50,h:40,type:'house'},
   {x:380,y:320,w:55,h:45,type:'house'},{x:130,y:280,w:45,h:40,type:'house'},
   {x:710,y:100,w:65,h:50,type:'temple'},{x:480,y:160,w:50,h:42,type:'house'},
   {x:280,y:390,w:48,h:42,type:'house'}].forEach(l=>{
    const tx=Math.floor(l.x/TILE_SIZE),ty=Math.floor(l.y/TILE_SIZE);
    if(tx>=0&&tx<MAP_W&&ty>=0&&ty<MAP_H&&terrainMap[ty][tx]!=='water')
      buildings.push({x:l.x,y:l.y,width:l.w,height:l.h,type:l.type});
  });
}
function createWaterBody(sx,sy,w,h){for(let y=sy;y<sy+h&&y<MAP_H;y++)for(let x=sx;x<sx+w&&x<MAP_W;x++)if(Math.random()<.85||(x>sx&&x<sx+w-1&&y>sy&&y<sy+h-1))terrainMap[y][x]='water';}
function addBeaches(){for(let y=0;y<MAP_H;y++)for(let x=0;x<MAP_W;x++)if(terrainMap[y][x]==='land'){let nw=false;for(let dy=-1;dy<=1;dy++)for(let dx=-1;dx<=1;dx++){const ny=y+dy,nx=x+dx;if(ny>=0&&ny<MAP_H&&nx>=0&&nx<MAP_W&&terrainMap[ny][nx]==='water')nw=true;}if(nw&&Math.random()<.4)terrainMap[y][x]='sand';}}
function addForests(){[{x:8,y:10},{x:17,y:6},{x:12,y:2},{x:24,y:9}].forEach(c=>{for(let dy=-2;dy<=2;dy++)for(let dx=-2;dx<=2;dx++){const x=c.x+dx,y=c.y+dy;if(x>=0&&x<MAP_W&&y>=0&&y<MAP_H&&terrainMap[y][x]==='land'&&Math.random()<.4)terrainMap[y][x]='forest';}});}
function isWalkable(x,y){const tx=Math.floor(x/TILE_SIZE),ty=Math.floor(y/TILE_SIZE);if(tx<0||tx>=MAP_W||ty<0||ty>=MAP_H)return false;if(terrainMap[ty][tx]==='water')return false;for(let b of buildings)if(x>=b.x&&x<=b.x+b.width&&y>=b.y&&y<=b.y+b.height)return false;return true;}
function bulletHitsBuilding(b){for(let bld of buildings)if(b.x>=bld.x&&b.x<=bld.x+bld.width&&b.y>=bld.y&&b.y<=bld.y+bld.height)return true;return false;}
function inZone(x,y){const dx=x-zoneCX,dy=y-zoneCY;return Math.sqrt(dx*dx+dy*dy)<=zoneRadius;}
function findValidSpawn(ax,ay){for(let i=0;i<100;i++){const x=80+Math.random()*820,y=30+Math.random()*440,dx=x-(ax||450),dy=y-(ay||250);if(isWalkable(x,y)&&Math.sqrt(dx*dx+dy*dy)>80)return{x,y};}return{x:450,y:250};}

function startBattleRoyale() {
  openScreen('game');
  generateTerrain();
  gameKills=0;playersAliveAtDeath=6;zoneRadius=Math.max(900,500)*.8;gameStartTime=Date.now();gameRunning=true;brBullets=[];lightningStrikes=[];brSuperCharge=0;
  const stats=getBrawlerStats(GS.selectedBrawler),spawn=findValidSpawn();
  brPlayer={x:spawn.x,y:spawn.y,health:stats.power,maxHealth:stats.power,ammo:stats.ammo,maxAmmo:stats.ammo,lastShot:0,angle:0,lastZoneDamage:0,kills:0};
  brBots=[];
  const botColors=['#e74c3c','#e67e22','#9b59b6','#1abc9c','#e91e63'];
  for(let i=0;i<5;i++){const s=findValidSpawn(brPlayer.x,brPlayer.y);brBots.push({x:s.x,y:s.y,health:7,maxHealth:7,ammo:3,maxAmmo:3,lastShot:0,vx:0,vy:0,color:botColors[i],lastZoneDamage:0,alive:true});}
  if(brRafId)cancelAnimationFrame(brRafId);
  document.getElementById('game-over-panel').style.display='none';
  brGameLoop();
}

brCanvas.addEventListener('mousemove',e=>{const r=brCanvas.getBoundingClientRect();brMouseX=e.clientX-r.left;brMouseY=e.clientY-r.top;});
brCanvas.addEventListener('click',()=>{if(!gameRunning)return;brShoot(brPlayer,brMouseX,brMouseY,'#c74444',true);});
brCanvas.addEventListener('contextmenu',e=>{e.preventDefault();if(!gameRunning)return;brUseSuper();});

// Super state
let brSuperCharge = 0; // 0..1 (1 kill = ready)
const BR_SUPER_KILLS_NEEDED = 1;

function brUseSuper() {
  if(brSuperCharge < 1) { showToast('Super nog niet klaar! Dood eerst een vijand. 💀'); return; }
  brSuperCharge = 0;
  // Fire 3 bullets in a spread toward mouse
  for(let s=-1;s<=1;s++){
    const baseAngle = Math.atan2(brMouseY-brPlayer.y, brMouseX-brPlayer.x);
    const angle = baseAngle + s*0.25;
    brBullets.push({x:brPlayer.x,y:brPlayer.y,vx:Math.cos(angle)*BULLET_SPEED*1.3,vy:Math.sin(angle)*BULLET_SPEED*1.3,owner:brPlayer,color:'#ffe066',isPlayer:true,isSuper:true,damage:3});
  }
  // Flash effect
  brCtx.save();brCtx.fillStyle='rgba(255,220,50,0.35)';brCtx.fillRect(0,0,900,500);brCtx.restore();
  showToast('⚡ SUPER! Drievoudige aanval!');
  GS.quests.filter(q=>!q.claimed&&(q.type==='super')).forEach(q=>{ q.current=Math.min(q.goal,q.current+1); });
  updateQuestBadge();
}

function brShoot(entity,tx,ty,color,isPlayer){
  const now=Date.now();
  if(entity.ammo<=0||now-entity.lastShot<SHOOT_COOLDOWN)return;
  const dx=tx-entity.x,dy=ty-entity.y,dist=Math.sqrt(dx*dx+dy*dy);
  if(dist>MAX_SHOOT_DISTANCE)return;
  const angle=Math.atan2(dy,dx);
  brBullets.push({x:entity.x,y:entity.y,vx:Math.cos(angle)*BULLET_SPEED,vy:Math.sin(angle)*BULLET_SPEED,owner:entity,color,isPlayer:isPlayer||false});
  entity.ammo--;entity.lastShot=now;
}

function brUpdatePlayer(){
  if(!gameRunning)return;
  const stats=getBrawlerStats(GS.selectedBrawler);
  let dx=0,dy=0;
  if(brKeys['ArrowLeft']||brKeys['a'])dx-=1;
  if(brKeys['ArrowRight']||brKeys['d'])dx+=1;
  if(brKeys['ArrowUp']||brKeys['w'])dy-=1;
  if(brKeys['ArrowDown']||brKeys['s'])dy+=1;
  if(dx&&dy){dx*=.707;dy*=.707;}
  const nx=brPlayer.x+dx*stats.speed,ny=brPlayer.y+dy*stats.speed;
  if(isWalkable(nx,brPlayer.y))brPlayer.x=nx;
  if(isWalkable(brPlayer.x,ny))brPlayer.y=ny;
  brPlayer.x=Math.max(ENTITY_RADIUS,Math.min(900-ENTITY_RADIUS,brPlayer.x));
  brPlayer.y=Math.max(ENTITY_RADIUS,Math.min(500-ENTITY_RADIUS,brPlayer.y));
  brPlayer.angle=Math.atan2(brMouseY-brPlayer.y,brMouseX-brPlayer.x);
  const now=Date.now();
  if(now-brPlayer.lastShot>=SHOOT_COOLDOWN)brPlayer.ammo=Math.min(brPlayer.maxAmmo,brPlayer.ammo+1);
  if(!inZone(brPlayer.x,brPlayer.y)&&now-brPlayer.lastZoneDamage>=1000){brPlayer.health--;brPlayer.lastZoneDamage=now;if(brPlayer.health<=0)playersAliveAtDeath=brBots.filter(b=>b.alive).length+1;}
}

function brUpdateBots(){
  const now=Date.now();
  brBots.forEach((bot,idx)=>{
    if(!bot.alive)return;
    const targets=[...(brPlayer.health>0?[brPlayer]:[]),...brBots.filter((_,i)=>i!==idx&&brBots[i].alive)];
    let nearest=null,nearDist=Infinity;
    targets.forEach(t=>{if(t.health<=0)return;const dx=t.x-bot.x,dy=t.y-bot.y,d=Math.sqrt(dx*dx+dy*dy);if(d<nearDist){nearDist=d;nearest=t;}});
    if(!inZone(bot.x,bot.y)){const dzx=zoneCX-bot.x,dzy=zoneCY-bot.y,zd=Math.sqrt(dzx*dzx+dzy*dzy);bot.vx=(dzx/zd)*BOT_SPEED_BASE*1.5;bot.vy=(dzy/zd)*BOT_SPEED_BASE*1.5;}
    else if(nearest){const dx=nearest.x-bot.x,dy=nearest.y-bot.y;if(nearDist>200){bot.vx=(dx/nearDist)*BOT_SPEED_BASE;bot.vy=(dy/nearDist)*BOT_SPEED_BASE;}else if(nearDist<100){bot.vx=-(dx/nearDist)*BOT_SPEED_BASE;bot.vy=-(dy/nearDist)*BOT_SPEED_BASE;}else{bot.vx=-(dy/nearDist)*BOT_SPEED_BASE*.5;bot.vy=(dx/nearDist)*BOT_SPEED_BASE*.5;}if(Math.random()<.02&&nearDist<MAX_SHOOT_DISTANCE)brShoot(bot,nearest.x,nearest.y,bot.color,false);}
    const nx=bot.x+bot.vx,ny=bot.y+bot.vy;
    if(isWalkable(nx,bot.y))bot.x=nx;if(isWalkable(bot.x,ny))bot.y=ny;
    bot.x=Math.max(ENTITY_RADIUS,Math.min(900-ENTITY_RADIUS,bot.x));bot.y=Math.max(ENTITY_RADIUS,Math.min(500-ENTITY_RADIUS,bot.y));
    if(now-bot.lastShot>=SHOOT_COOLDOWN)bot.ammo=Math.min(bot.maxAmmo,bot.ammo+1);
    if(!inZone(bot.x,bot.y)&&now-bot.lastZoneDamage>=1000){bot.health--;bot.lastZoneDamage=now;if(bot.health<=0){bot.alive=false;}}
    bot.vx*=.95;bot.vy*=.95;
  });
}

function brUpdateBullets(){
  brBullets=brBullets.filter(bullet=>{
    bullet.x+=bullet.vx;bullet.y+=bullet.vy;
    if(bullet.x<0||bullet.x>900||bullet.y<0||bullet.y>500)return false;
    if(bulletHitsBuilding(bullet))return false;
    const dmg = bullet.damage||1;
    // Hit player
    if(bullet.owner!==brPlayer&&brPlayer.health>0){
      const dx=bullet.x-brPlayer.x,dy=bullet.y-brPlayer.y;
      if(Math.sqrt(dx*dx+dy*dy)<ENTITY_RADIUS+BULLET_RADIUS){
        brPlayer.health-=dmg;
        if(brPlayer.health<=0)playersAliveAtDeath=brBots.filter(bot=>bot.alive).length+1;
        return false;
      }
    }
    // Hit bots
    for(let bot of brBots){
      if(!bot.alive||bullet.owner===bot)continue;
      const dx=bullet.x-bot.x,dy=bullet.y-bot.y;
      if(Math.sqrt(dx*dx+dy*dy)<ENTITY_RADIUS+BULLET_RADIUS){
        bot.health-=dmg;
        if(bot.health<=0){
          bot.alive=false;
          if(bullet.isPlayer){
            gameKills++;brPlayer.kills=(brPlayer.kills||0)+1;
            brSuperCharge=Math.min(1,brSuperCharge+1);
            if(bullet.isSuper) GS.quests.filter(q=>!q.claimed&&q.type==='superkill').forEach(q=>{q.current=Math.min(q.goal,q.current+1);});
          }
        } else {
          if(bullet.isPlayer) GS.quests.filter(q=>!q.claimed&&q.type==='hits').forEach(q=>{q.current=Math.min(q.goal,q.current+1);});
        }
        return false;
      }
    }
    return true;
  });
}

function brUpdateZone(){
  const elapsed=Date.now()-gameStartTime,progress=Math.min(elapsed/GAME_DURATION,1);
  const maxR=Math.max(900,500)*.8;
  zoneRadius=maxR-(maxR-50)*progress;
  const lchance=.01+progress*.04;
  if(Math.random()<lchance){const angle=Math.random()*Math.PI*2,dist=zoneRadius+Math.random()*100+20;lightningStrikes.push({x:zoneCX+Math.cos(angle)*dist,y:zoneCY+Math.sin(angle)*dist,time:Date.now(),duration:300});}
  lightningStrikes=lightningStrikes.filter(l=>Date.now()-l.time<l.duration);
}

function brDrawTerrain(){
  for(let y=0;y<MAP_H;y++)for(let x=0;x<MAP_W;x++){
    const px=x*TILE_SIZE,py=y*TILE_SIZE;
    switch(terrainMap[y][x]){
      case'water':const wave=Math.sin((x+y)*.5+Date.now()*.001)*10;brCtx.fillStyle=`hsl(205,50%,${45+wave}%)`;break;
      case'sand':brCtx.fillStyle='#e8d4a8';break;
      case'forest':brCtx.fillStyle='#2d5016';break;
      default:const v=Math.sin(x*3+y*2)*5;brCtx.fillStyle=`hsl(100,30%,${40+v}%)`;
    }
    brCtx.fillRect(px,py,TILE_SIZE,TILE_SIZE);
    brCtx.strokeStyle='rgba(0,0,0,.1)';brCtx.lineWidth=1;brCtx.strokeRect(px,py,TILE_SIZE,TILE_SIZE);
    if(terrainMap[y][x]==='forest'){brCtx.fillStyle='#1a3010';brCtx.beginPath();brCtx.arc(px+TILE_SIZE/2,py+TILE_SIZE/2,8,0,Math.PI*2);brCtx.fill();}
  }
}

function brDrawBuildings(){
  buildings.forEach(b=>{
    const{x,y,width:w,height:h,type}=b;
    if(type==='temple'){brCtx.fillStyle='#8b7355';brCtx.fillRect(x-2,y+h-8,w+4,8);brCtx.fillStyle='#d4c4a8';const cc=4,cw=6,sp=(w-cc*cw)/(cc+1);for(let i=0;i<cc;i++){const cx=x+sp+i*(cw+sp);brCtx.fillRect(cx,y+12,cw,h-20);}brCtx.fillStyle='#c9a876';brCtx.beginPath();brCtx.moveTo(x-5,y+12);brCtx.lineTo(x+w+5,y+12);brCtx.lineTo(x+w/2,y);brCtx.closePath();brCtx.fill();brCtx.strokeStyle='#8b7355';brCtx.lineWidth=2;brCtx.stroke();}
    else{brCtx.fillStyle='#d4c4a8';brCtx.fillRect(x,y+h/3,w,h*2/3);brCtx.strokeStyle='#8b7355';brCtx.lineWidth=2;brCtx.strokeRect(x,y+h/3,w,h*2/3);brCtx.fillStyle='#b8956f';brCtx.beginPath();brCtx.moveTo(x-3,y+h/3);brCtx.lineTo(x+w+3,y+h/3);brCtx.lineTo(x+w/2,y);brCtx.closePath();brCtx.fill();brCtx.strokeStyle='#8b7355';brCtx.stroke();brCtx.fillStyle='#654321';brCtx.fillRect(x+w/2-6,y+h-15,12,15);}
    brCtx.fillStyle='rgba(0,0,0,.3)';brCtx.fillRect(x+w,y+h/2,8,h/2);
  });
}

function brDrawZone(){
  const thick = 60;
  const progress = Math.min((Date.now()-gameStartTime)/GAME_DURATION, 1);

  // Only draw fog when storm has meaningfully started (after ~15% progress)
  if(progress > 0.08) {
    brCtx.save();
    // Use clipping: invert clip to fill OUTSIDE the safe zone only
    brCtx.beginPath();
    brCtx.rect(0, 0, 900, 500);
    brCtx.arc(zoneCX, zoneCY, zoneRadius + thick*0.5, 0, Math.PI*2, true); // true = counterclockwise = hole
    brCtx.fillStyle = `rgba(8,4,20,${Math.min(0.78, progress * 1.1)})`;
    brCtx.fill('evenodd');
    brCtx.restore();
  }

  // Storm edge: glowing purple ring
  brCtx.save();
  brCtx.shadowBlur = 0;
  for(let angle=0; angle<Math.PI*2; angle+=0.18){
    for(let r=zoneRadius; r<zoneRadius+thick; r+=9){
      const x=zoneCX+Math.cos(angle)*r, y=zoneCY+Math.sin(angle)*r;
      if(x>=-30&&x<=930&&y>=-30&&y<=530){
        const op = 0.5*(1-(r-zoneRadius)/thick);
        brCtx.fillStyle=`rgba(160,100,255,${op})`;
        brCtx.beginPath();brCtx.arc(x,y,8+Math.random()*5,0,Math.PI*2);brCtx.fill();
      }
    }
  }
  brCtx.restore();

  // Lightning
  lightningStrikes.forEach(l=>{
    const alpha=1-(Date.now()-l.time)/l.duration;
    brCtx.strokeStyle=`rgba(200,160,255,${alpha})`;
    brCtx.lineWidth=3;brCtx.shadowBlur=15;brCtx.shadowColor='#aa88ff';
    brCtx.beginPath();brCtx.moveTo(l.x,l.y-40);brCtx.lineTo(l.x+5,l.y-20);brCtx.lineTo(l.x-3,l.y-10);brCtx.lineTo(l.x+4,l.y);brCtx.stroke();
    brCtx.shadowBlur=0;
  });
}

function brDrawEntity(entity,color,isPlayer){
  if(entity.health<=0)return;
  brCtx.beginPath();brCtx.ellipse(entity.x,entity.y+18,ENTITY_RADIUS-2,6,0,0,Math.PI*2);brCtx.fillStyle='rgba(0,0,0,.3)';brCtx.fill();
  brCtx.beginPath();brCtx.arc(entity.x,entity.y,ENTITY_RADIUS,0,Math.PI*2);brCtx.fillStyle=color;brCtx.fill();
  brCtx.strokeStyle=isPlayer?'#8b4513':'#654321';brCtx.lineWidth=3;brCtx.stroke();
  if(isPlayer){brCtx.font='16px serif';brCtx.textAlign='center';brCtx.textBaseline='middle';brCtx.fillText(GS.brawlers[GS.selectedBrawler].emoji,entity.x,entity.y);}
  brCtx.beginPath();brCtx.moveTo(entity.x-8,entity.y-12);brCtx.quadraticCurveTo(entity.x,entity.y-20,entity.x+8,entity.y-12);brCtx.fillStyle=isPlayer?'#1e40af':'#991b1b';brCtx.fill();
  const bw=32,bh=5,bx=entity.x-bw/2,by=entity.y-ENTITY_RADIUS-12;
  brCtx.fillStyle='rgba(0,0,0,.6)';brCtx.fillRect(bx,by,bw,bh);
  brCtx.fillStyle=entity.health/entity.maxHealth>.5?'#10b981':entity.health/entity.maxHealth>.25?'#f59e0b':'#ef4444';brCtx.fillRect(bx,by,bw*(entity.health/entity.maxHealth),bh);
  brCtx.strokeStyle='#000';brCtx.lineWidth=1;brCtx.strokeRect(bx,by,bw,bh);
}

function brDrawPlayer(){
  brDrawEntity(brPlayer,GS.brawlers[GS.selectedBrawler].color,true);
  const len=28,ex=brPlayer.x+Math.cos(brPlayer.angle)*len,ey=brPlayer.y+Math.sin(brPlayer.angle)*len;
  brCtx.beginPath();brCtx.moveTo(brPlayer.x,brPlayer.y);brCtx.lineTo(ex,ey);brCtx.strokeStyle='#8b4513';brCtx.lineWidth=4;brCtx.stroke();
  brCtx.beginPath();brCtx.arc(ex,ey,3,0,Math.PI*2);brCtx.fillStyle='#d4af37';brCtx.fill();
}

function brDrawBullets(){
  brBullets.forEach(b=>{
    const angle=Math.atan2(b.vy,b.vx);brCtx.save();brCtx.translate(b.x,b.y);brCtx.rotate(angle);
    brCtx.beginPath();brCtx.moveTo(-8,0);brCtx.lineTo(8,0);brCtx.strokeStyle='#654321';brCtx.lineWidth=3;brCtx.stroke();
    brCtx.beginPath();brCtx.moveTo(8,0);brCtx.lineTo(4,-4);brCtx.lineTo(4,4);brCtx.closePath();brCtx.fillStyle=b.color;brCtx.fill();
    brCtx.restore();
  });
}

function brUpdateHUD(){
  document.getElementById('playerHealth').textContent=Math.max(0,brPlayer.health);
  document.getElementById('ammoCount').textContent=brPlayer.ammo;
  document.getElementById('botsAlive').textContent=brBots.filter(b=>b.alive).length;
  const tl=Math.max(0,Math.ceil((GAME_DURATION-(Date.now()-gameStartTime))/1000));
  const tel=document.getElementById('timeLeft');tel.textContent=tl;
  if(tl<=30)tel.parentElement.classList.add('timer-warning');else tel.parentElement.classList.remove('timer-warning');
  // Super bar
  const pct = Math.round(brSuperCharge*100);
  document.getElementById('super-bar-br').style.width = pct+'%';
  document.getElementById('superReady').textContent = brSuperCharge>=1 ? '🟡' : '🔴';
}

function brCheckEnd(){
  if(brPlayer.health<=0){brEndGame('VERSLAGEN!','De vijandelijke krijgers hebben gezegevierd.');return true;}
  if(brBots.filter(b=>b.alive).length===0){brEndGame('VICTORIE!','Olympia is bevrijd!');return true;}
  if(GAME_DURATION-(Date.now()-gameStartTime)<=0){brEndGame('TIJD OM!','De strijd eindigt...');return true;}
  return false;
}

function brEndGame(title,msg){
  gameRunning=false;
  const aliveCount=brBots.filter(b=>b.alive).length;
  let place;
  if(brPlayer.health<=0){place=playersAliveAtDeath;}
  else{place=aliveCount===0?1:1;}
  place=Math.max(1,Math.min(6,place));
  GS.lastPlacement=place;GS.lastKills=gameKills;
  document.getElementById('game-over-title').textContent=title;
  document.getElementById('game-over-msg').textContent=msg;
  document.getElementById('game-over-panel').style.display='block';
  // Override the restart button to go to results
  document.getElementById('game-restart-btn').onclick=()=>showResult(gameKills,place,'battle');
}

function brGameLoop(){
  if(!gameRunning)return;
  // 1. Draw terrain (bright, clear)
  brDrawTerrain();
  // 2. Update logic
  brUpdatePlayer();brUpdateBots();brUpdateBullets();brUpdateZone();
  // 3. Draw buildings
  brDrawBuildings();
  // 4. Draw storm fog BEFORE entities so entities are always on top
  brDrawZone();
  // 5. Draw entities on top of fog — always visible
  brDrawBullets();
  brBots.forEach(b=>{if(b.alive)brDrawEntity(b,b.color,false);});
  brDrawPlayer();
  // 6. HUD
  brUpdateHUD();
  if(!brCheckEnd())brRafId=requestAnimationFrame(brGameLoop);
}

/* ═══════════════════════════════════════════════════════
   ██████╗  █████╗  ██████╗███████╗
   ██╔══██╗██╔══██╗██╔════╝██╔════╝
   ██████╔╝███████║██║     █████╗
   ██╔══██╗██╔══██║██║     ██╔══╝
   ██║  ██║██║  ██║╚██████╗███████╗
   OLYMPIC RACE ENGINE
═══════════════════════════════════════════════════════ */
const raceCanvas = document.getElementById('race-canvas');
const rCtx = raceCanvas.getContext('2d');

const RS = Math.min(window.innerWidth * 0.88, window.innerHeight * 0.82);
raceCanvas.width = RS; raceCanvas.height = RS;
const RCX = RS/2, RCY = RS/2;
const R_OUT = RS * 0.46, R_IN = RS * 0.28, R_MID = (R_OUT+R_IN)/2;

const RACE_PLAYER_SPEED = 0.95;
const RACE_BOT_SPEEDS   = [0.72, 0.78, 0.82, 0.68, 0.75];
const RACE_BULLET_SPEED = 230;
const RACE_SHOOT_CD     = 5000;
const RACE_STUN_DUR     = 3000;
const RACE_LAP_GOAL     = 10;
const RDOT_R            = RS * 0.028;
const RARROW_LEN        = RS * 0.045;

const RACE_BOT_DATA = [
  {name:'ARES',   color:'#e05030'},
  {name:'HERMES', color:'#5090e0'},
  {name:'APOLLO', color:'#d4a017'},
  {name:'ZEUS',   color:'#a050d0'},
  {name:'ATHENA', color:'#40b070'},
];

let raceKeys={}, raceMX=RCX, raceMY=RCY;
let raceLastT=0, raceElapsed=0, raceStartT=0;
let racePlayer, raceBots, raceArrows, raceRafId;
let raceRunning=false;

// Shared keyboard handler (we combine both)
window.addEventListener('keydown', e => {
  brKeys[e.key] = true;
  raceKeys[e.code] = true;
  if(['Space','ArrowUp','ArrowDown','ArrowLeft','ArrowRight'].includes(e.code)) e.preventDefault();
  if(e.code==='Space' && raceRunning) raceTryShoot();
});
window.addEventListener('keyup', e => {
  brKeys[e.key] = false;
  raceKeys[e.code] = false;
});

let raceSuperHits = 0; // charges: 3 hits = super ready
const RACE_SUPER_HITS_NEEDED = 3;

raceCanvas.addEventListener('mousemove', e => {
  const r = raceCanvas.getBoundingClientRect();
  raceMX = e.clientX - r.left;
  raceMY = e.clientY - r.top;
});
raceCanvas.addEventListener('click', () => { if(raceRunning) raceTryShoot(); });
raceCanvas.addEventListener('contextmenu', e => { e.preventDefault(); if(raceRunning) raceUseSuper(); });

function raceUseSuper() {
  if(raceSuperHits < RACE_SUPER_HITS_NEEDED) { showToast('Super nog niet klaar! Raak eerst 3 tegenstanders. 🏹'); return; }
  raceSuperHits = 0;
  // Stun 3 random non-stunned bots for 3 seconds
  const targets = raceBots.filter(b => b.stun <= 0 && !b.won);
  const shuffled = targets.sort(() => Math.random()-0.5).slice(0, 3);
  shuffled.forEach(b => { b.stun = 3000; });
  showToast(`⚡ SUPER! ${shuffled.length} tegenstanders gestuned voor 3 seconden!`);
  GS.quests.filter(q=>!q.claimed&&q.type==='super').forEach(q=>{q.current=Math.min(q.goal,q.current+1);});
  updateQuestBadge();
}

function mkRacer(angle, isPlayer, bi) {
  const brawler = GS.brawlers[GS.selectedBrawler];
  return {
    angle, isPlayer,
    color: isPlayer ? brawler.color : RACE_BOT_DATA[bi].color,
    name:  isPlayer ? brawler.name.split(' ')[0].toUpperCase() : RACE_BOT_DATA[bi].name,
    emoji: isPlayer ? brawler.emoji : null,
    speed: isPlayer ? RACE_PLAYER_SPEED : RACE_BOT_SPEEDS[bi],
    laps:0, cumAngle:0, prevAngle:angle,
    stun:0, shotCd:0, won:false,
    botShootTimer: 1000+Math.random()*3000,
  };
}

function startRaceGame() {
  openScreen('race');
  document.getElementById('race-hud').style.display = 'flex';
  document.getElementById('aim-hint-race').style.display = 'flex';
  racePlayer = mkRacer(Math.PI/2, true, -1);
  raceBots = RACE_BOT_DATA.map((_,i) => mkRacer(Math.PI/2+(i+1)*0.22, false, i));
  raceArrows = [];
  raceKeys = {};
  raceSuperHits = 0;
  raceStartT = performance.now();
  raceElapsed = 0; raceLastT = raceStartT;
  raceRunning = true;
  if(raceRafId) cancelAnimationFrame(raceRafId);
  raceRafId = requestAnimationFrame(raceLoop);
}

function raceGetXY(r) {
  return { x: RCX + Math.cos(r.angle)*R_MID, y: RCY + Math.sin(r.angle)*R_MID };
}
function raceAllRunners() { return [racePlayer, ...raceBots]; }

function raceTryShoot() {
  if(!racePlayer||racePlayer.stun>0||racePlayer.shotCd>0) return;
  racePlayer.shotCd = RACE_SHOOT_CD;
  raceFireArrow(racePlayer, raceMX, raceMY);
}

function raceFireArrow(runner, tx, ty) {
  let p=raceGetXY(runner);
  let dx=tx-p.x,dy=ty-p.y,len=Math.hypot(dx,dy)||1;
  raceArrows.push({x:p.x,y:p.y,vx:(dx/len)*RACE_BULLET_SPEED,vy:(dy/len)*RACE_BULLET_SPEED,owner:runner,life:2.8,ang:Math.atan2(dy,dx)});
}

function raceUpdateLaps(runner) {
  let da=runner.angle-runner.prevAngle;
  while(da>Math.PI)da-=2*Math.PI;
  while(da<-Math.PI)da+=2*Math.PI;
  runner.cumAngle+=da;
  let lapsNow=Math.floor(-runner.cumAngle/(2*Math.PI));
  if(lapsNow>runner.laps){runner.laps=lapsNow;if(runner.laps>=RACE_LAP_GOAL)runner.won=true;}
  runner.prevAngle=runner.angle;
}

function raceBotAI(bot, dt) {
  if(bot.won||bot.stun>0)return;
  bot.angle-=bot.speed*dt;
  raceUpdateLaps(bot);
  bot.botShootTimer-=dt*1000;
  if(bot.botShootTimer<=0&&bot.shotCd<=0){
    let targets=raceAllRunners().filter(r=>r!==bot&&r.stun<=0);
    if(targets.length){
      let target=targets[Math.floor(Math.random()*targets.length)];
      let tp=raceGetXY(target),bp=raceGetXY(bot);
      if(Math.hypot(tp.x-bp.x,tp.y-bp.y)<RS*0.6){
        raceFireArrow(bot,tp.x+(Math.random()-.5)*35,tp.y+(Math.random()-.5)*35);
        bot.shotCd=RACE_SHOOT_CD;
      }
    }
    bot.botShootTimer=1500+Math.random()*3500;
  }
}

function raceLoop(ts) {
  if(!raceRunning)return;
  let dt=Math.min((ts-raceLastT)/1000,0.1);
  raceLastT=ts; raceElapsed=(ts-raceStartT)/1000;

  if(racePlayer.stun<=0){
    let moved=false;
    if(raceKeys['ArrowLeft']||raceKeys['KeyA']){racePlayer.angle+=racePlayer.speed*dt;moved=true;}
    else if(raceKeys['ArrowRight']||raceKeys['KeyD']){racePlayer.angle-=racePlayer.speed*dt;moved=true;}
    else if(raceKeys['ArrowUp']||raceKeys['KeyW']){racePlayer.angle-=racePlayer.speed*dt;moved=true;}
    else if(raceKeys['ArrowDown']||raceKeys['KeyS']){racePlayer.angle+=racePlayer.speed*dt;moved=true;}
    if(moved)raceUpdateLaps(racePlayer);
  }

  raceAllRunners().forEach(r=>{
    if(r.shotCd>0)r.shotCd-=dt*1000;
    if(r.stun>0)r.stun-=dt*1000;
  });

  raceBots.forEach(b=>raceBotAI(b,dt));

  raceArrows=raceArrows.filter(a=>a.life>0);
  raceArrows.forEach(a=>{
    a.x+=a.vx*dt;a.y+=a.vy*dt;a.life-=dt;
    if(a.x<-20||a.x>RS+20||a.y<-20||a.y>RS+20){a.life=0;return;}
    raceAllRunners().forEach(r=>{
      if(r===a.owner||r.stun>0)return;
      let p=raceGetXY(r);
      if(Math.hypot(a.x-p.x,a.y-p.y)<RDOT_R*1.15){
        r.stun=RACE_STUN_DUR;a.life=0;
        // If player's arrow hit someone, charge super
        if(a.owner===racePlayer){
          raceSuperHits=Math.min(RACE_SUPER_HITS_NEEDED,raceSuperHits+1);
          GS.quests.filter(q=>!q.claimed&&q.type==='hits').forEach(q=>{q.current=Math.min(q.goal,q.current+1);});
          updateQuestBadge();
        }
      }
    });
  });

  // Check winner
  let winner = raceAllRunners().find(r=>r.won);
  if(winner){raceEndGame(winner);return;}

  raceDraw();
  raceUpdateRaceHUD();
  raceRafId=requestAnimationFrame(raceLoop);
}

function raceEndGame(winner) {
  raceRunning=false;
  document.getElementById('race-hud').style.display='none';
  document.getElementById('aim-hint-race').style.display='none';

  // Determine placement: sort by progress
  const runners = raceAllRunners().slice().sort((a,b)=>{
    const aP=a.laps*2*Math.PI+(-a.cumAngle%(2*Math.PI));
    const bP=b.laps*2*Math.PI+(-b.cumAngle%(2*Math.PI));
    return bP-aP;
  });
  const place = runners.findIndex(r=>r.isPlayer) + 1;
  const finalPlace = Math.max(1, Math.min(6, place));

  // Show result after short delay
  setTimeout(()=> showResult(0, finalPlace, 'race'), 500);
}

function raceUpdateRaceHUD(){
  document.getElementById('r-laps').textContent=Math.min(racePlayer.laps,RACE_LAP_GOAL);
  document.getElementById('r-time').textContent=raceFmt(raceElapsed);
  let pct=Math.max(0,1-racePlayer.shotCd/RACE_SHOOT_CD);
  const bar=document.getElementById('race-coolbar');
  bar.style.width=(pct*100)+'%';
  bar.style.background=pct>=1?'#f0d080':'#6b4a10';
  // Super bar
  const sPct = (raceSuperHits/RACE_SUPER_HITS_NEEDED)*100;
  document.getElementById('race-super-bar').style.width = sPct+'%';
  document.getElementById('race-super-txt').textContent = raceSuperHits+'/'+RACE_SUPER_HITS_NEEDED;
}
function raceFmt(s){return `${Math.floor(s/60)}:${Math.floor(s%60).toString().padStart(2,'0')}`;}

/* ─── RACE DRAW ─── */
function raceDraw(){
  rCtx.clearRect(0,0,RS,RS);
  raceDrawBG();raceDrawTrack();raceDrawAimLine();raceDrawArrows();raceDrawRunners();raceDrawLeaderboard();
}

function raceDrawBG(){rCtx.fillStyle='#0d0703';rCtx.fillRect(0,0,RS,RS);}

function raceDrawTrack(){
  rCtx.beginPath();rCtx.arc(RCX,RCY,R_OUT+4,0,Math.PI*2);rCtx.fillStyle='#110a02';rCtx.fill();
  rCtx.beginPath();rCtx.arc(RCX,RCY,R_OUT,0,Math.PI*2);rCtx.fillStyle='#3a2508';rCtx.fill();
  rCtx.beginPath();rCtx.arc(RCX,RCY,R_IN,0,Math.PI*2);rCtx.fillStyle='#1c3a10';rCtx.fill();
  rCtx.beginPath();rCtx.arc(RCX,RCY,R_IN*.5,0,Math.PI*2);rCtx.fillStyle='#142d0c';rCtx.fill();
  raceDrawFlame();
  rCtx.save();rCtx.strokeStyle='rgba(201,168,76,0.12)';rCtx.lineWidth=1.5;rCtx.setLineDash([12,9]);
  rCtx.beginPath();rCtx.arc(RCX,RCY,R_MID,0,Math.PI*2);rCtx.stroke();rCtx.setLineDash([]);rCtx.restore();
  rCtx.strokeStyle='rgba(201,168,76,0.5)';rCtx.lineWidth=2;
  rCtx.beginPath();rCtx.arc(RCX,RCY,R_OUT,0,Math.PI*2);rCtx.stroke();
  rCtx.beginPath();rCtx.arc(RCX,RCY,R_IN,0,Math.PI*2);rCtx.stroke();
  for(let i=0;i<10;i++){
    let a=Math.PI/2-(i/10)*Math.PI*2;
    let mx=RCX+Math.cos(a)*(R_IN-RS*.022),my=RCY+Math.sin(a)*(R_IN-RS*.022);
    rCtx.beginPath();rCtx.arc(mx,my,RS*.007,0,Math.PI*2);
    rCtx.fillStyle=i===0?'#f0d080':'rgba(201,168,76,0.25)';rCtx.fill();
  }
  rCtx.save();rCtx.translate(RCX,RCY);rCtx.rotate(Math.PI/2);
  rCtx.fillStyle='rgba(240,208,128,0.55)';rCtx.fillRect(-2.5,R_IN,5,R_OUT-R_IN);rCtx.restore();
  rCtx.font=`bold ${RS*.02}px Cinzel`;rCtx.fillStyle='rgba(201,168,76,0.35)';rCtx.textAlign='center';
  rCtx.fillText('ΟΛΥΜΠΙΑ',RCX,RCY+RS*.07);
}

function raceDrawFlame(){
  let t=performance.now()/400;
  let fr=R_IN*.2,fx=RCX,fy=RCY-R_IN*.08;
  [{r:fr*1.1,color:'#ff4400',alpha:.5},{r:fr*.8,color:'#ff8800',alpha:.65},{r:fr*.55,color:'#ffcc00',alpha:.8},{r:fr*.3,color:'#fff0a0',alpha:.9}].forEach((l,i)=>{
    let flicker=Math.sin(t*1.3+i)*.12;
    rCtx.beginPath();rCtx.ellipse(fx,fy-l.r*.4,l.r*(.45+flicker),l.r,0,0,Math.PI*2);
    rCtx.fillStyle=l.color;rCtx.globalAlpha=l.alpha;rCtx.fill();
  });
  rCtx.globalAlpha=1;
}

function raceDrawAimLine(){
  if(!racePlayer||racePlayer.stun>0)return;
  let pos=raceGetXY(racePlayer);
  let dx=raceMX-pos.x,dy=raceMY-pos.y,len=Math.hypot(dx,dy)||1;
  let nx=dx/len,ny=dy/len,ready=racePlayer.shotCd<=0;
  rCtx.save();rCtx.setLineDash([6,5]);
  rCtx.strokeStyle=ready?'rgba(240,208,128,0.6)':'rgba(139,99,20,0.4)';rCtx.lineWidth=1.5;
  rCtx.beginPath();rCtx.moveTo(pos.x+nx*RDOT_R*1.3,pos.y+ny*RDOT_R*1.3);rCtx.lineTo(pos.x+nx*R_MID*.8,pos.y+ny*R_MID*.8);rCtx.stroke();
  rCtx.setLineDash([]);
  if(ready){let ex=pos.x+nx*R_MID*.8,ey=pos.y+ny*R_MID*.8;rCtx.strokeStyle='#f0d080';rCtx.lineWidth=2;rCtx.beginPath();rCtx.moveTo(ex-nx*10-ny*5,ey-ny*10+nx*5);rCtx.lineTo(ex,ey);rCtx.lineTo(ex-nx*10+ny*5,ey-ny*10-nx*5);rCtx.stroke();}
  rCtx.restore();
}

function raceDrawArrows(){
  raceArrows.forEach(a=>{
    rCtx.save();rCtx.translate(a.x,a.y);rCtx.rotate(a.ang);
    rCtx.globalAlpha=.22;rCtx.strokeStyle='#f0d080';rCtx.lineWidth=5;rCtx.beginPath();rCtx.moveTo(-RARROW_LEN*1.2,0);rCtx.lineTo(-RARROW_LEN*.6,0);rCtx.stroke();rCtx.globalAlpha=1;
    rCtx.strokeStyle='#c8a050';rCtx.lineWidth=2.5;rCtx.beginPath();rCtx.moveTo(-RARROW_LEN*.8,0);rCtx.lineTo(RARROW_LEN*.6,0);rCtx.stroke();
    rCtx.fillStyle='#f0e060';rCtx.beginPath();rCtx.moveTo(RARROW_LEN*.6,0);rCtx.lineTo(RARROW_LEN*.6-9,-4.5);rCtx.lineTo(RARROW_LEN*.6-9,4.5);rCtx.closePath();rCtx.fill();
    rCtx.strokeStyle='#c1440e';rCtx.lineWidth=1.5;rCtx.beginPath();rCtx.moveTo(-RARROW_LEN*.65,0);rCtx.lineTo(-RARROW_LEN*.8,-6);rCtx.stroke();rCtx.beginPath();rCtx.moveTo(-RARROW_LEN*.65,0);rCtx.lineTo(-RARROW_LEN*.8,6);rCtx.stroke();
    rCtx.restore();
  });
}

function raceDrawRunners(){[...raceBots,racePlayer].forEach(r=>{let p=raceGetXY(r);raceDrawDot(r,p.x,p.y);});}

function hex2rgb(hex){return[parseInt(hex.slice(1,3),16),parseInt(hex.slice(3,5),16),parseInt(hex.slice(5,7),16)];}

function raceDrawDot(runner,x,y){
  let stunned=runner.stun>0,c=stunned?'#555555':runner.color;
  let[r,g,b]=hex2rgb(c),t=performance.now();
  rCtx.save();rCtx.translate(x,y);
  rCtx.beginPath();rCtx.ellipse(0,RDOT_R*.8,RDOT_R*.7,RDOT_R*.22,0,0,Math.PI*2);rCtx.fillStyle='rgba(0,0,0,0.45)';rCtx.fill();
  if(!stunned){let glow=rCtx.createRadialGradient(0,0,RDOT_R*.7,0,0,RDOT_R*1.8);glow.addColorStop(0,`rgba(${r},${g},${b},0.35)`);glow.addColorStop(1,`rgba(${r},${g},${b},0)`);rCtx.beginPath();rCtx.arc(0,0,RDOT_R*1.8,0,Math.PI*2);rCtx.fillStyle=glow;rCtx.fill();}
  let grad=rCtx.createRadialGradient(-RDOT_R*.3,-RDOT_R*.35,RDOT_R*.05,0,0,RDOT_R);
  grad.addColorStop(0,stunned?'#888':`rgb(${Math.min(255,r+90)},${Math.min(255,g+90)},${Math.min(255,b+90)})`);
  grad.addColorStop(.6,c);grad.addColorStop(1,stunned?'#333':`rgb(${Math.max(0,r-50)},${Math.max(0,g-50)},${Math.max(0,b-50)})`);
  rCtx.beginPath();rCtx.arc(0,0,RDOT_R,0,Math.PI*2);rCtx.fillStyle=grad;
  if(!stunned){rCtx.shadowColor=c;rCtx.shadowBlur=12;}rCtx.fill();rCtx.shadowBlur=0;
  rCtx.beginPath();rCtx.ellipse(-RDOT_R*.28,-RDOT_R*.3,RDOT_R*.28,RDOT_R*.15,-.5,0,Math.PI*2);rCtx.fillStyle='rgba(255,255,255,0.25)';rCtx.fill();
  rCtx.strokeStyle=stunned?'#666':`rgb(${Math.min(255,r+40)},${Math.min(255,g+40)},${Math.min(255,b+40)})`;rCtx.lineWidth=2;rCtx.globalAlpha=.65;rCtx.beginPath();rCtx.arc(0,0,RDOT_R,0,Math.PI*2);rCtx.stroke();rCtx.globalAlpha=1;

  // Show player emoji inside dot
  if(runner.isPlayer && runner.emoji && !stunned){
    rCtx.font=`${RDOT_R*.9}px serif`;rCtx.textAlign='center';rCtx.textBaseline='middle';
    rCtx.fillText(runner.emoji,0,0);
  }

  if(stunned){for(let i=0;i<3;i++){let sa=t/270+i/3*Math.PI*2;rCtx.font=`${RDOT_R*.65}px serif`;rCtx.textAlign='center';rCtx.textBaseline='middle';rCtx.fillText('★',Math.cos(sa)*RDOT_R*1.5,Math.sin(sa)*RDOT_R*1.5);}}
  if(runner.isPlayer&&!stunned){let dx=raceMX-x,dy=raceMY-y,len=Math.hypot(dx,dy)||1;rCtx.beginPath();rCtx.arc(dx/len*RDOT_R*.5,dy/len*RDOT_R*.5,RDOT_R*.16,0,Math.PI*2);rCtx.fillStyle='#0d0703';rCtx.fill();}
  if(runner.isPlayer&&runner.shotCd>0){let frac=1-runner.shotCd/RACE_SHOOT_CD;rCtx.strokeStyle='#c9a84c';rCtx.lineWidth=3.5;rCtx.beginPath();rCtx.arc(0,0,RDOT_R+6,-Math.PI/2,-Math.PI/2+frac*Math.PI*2);rCtx.stroke();}
  rCtx.font=`bold ${RS*.016}px Cinzel`;rCtx.fillStyle=stunned?'rgba(100,100,100,0.9)':'rgba(240,208,128,0.95)';rCtx.textAlign='center';rCtx.textBaseline='alphabetic';rCtx.shadowColor='#000';rCtx.shadowBlur=5;
  rCtx.fillText(runner.name,0,-RDOT_R*1.45);rCtx.shadowBlur=0;
  rCtx.restore();
}

function raceDrawLeaderboard(){
  let runners=raceAllRunners().slice().sort((a,b)=>{
    let aP=a.laps*2*Math.PI+(-a.cumAngle%(2*Math.PI));
    let bP=b.laps*2*Math.PI+(-b.cumAngle%(2*Math.PI));
    return bP-aP;
  });
  let px=RS*.016,py=RS*.048,lh=RS*.033;
  rCtx.fillStyle='rgba(13,7,3,0.72)';rCtx.fillRect(px-5,py-lh*.9,RS*.22,(runners.length+1.5)*lh);
  rCtx.font=`bold ${RS*.019}px Cinzel`;rCtx.fillStyle='rgba(201,168,76,0.7)';rCtx.textAlign='left';rCtx.textBaseline='alphabetic';
  rCtx.fillText('RANGLIJST',px,py);
  runners.forEach((r,i)=>{
    let[rr,gg,bb]=hex2rgb(r.stun>0?'#666666':r.color);
    rCtx.font=`${i===0?'bold ':' '}${RS*.017}px Cinzel`;rCtx.fillStyle=`rgb(${rr},${gg},${bb})`;
    rCtx.fillText(`${i+1}. ${r.name}  ${r.laps}${r.stun>0?' ★':''}`,px,py+(i+1.2)*lh);
  });
}

// Initial static draw for race
rCtx.fillStyle='#0d0703';rCtx.fillRect(0,0,RS,RS);

// Init lobby - silently set up default char
GS.selectedBrawler = 'lemon';
updateLobbyUI();
renderCharSelector();
document.getElementById('char-lemon').classList.add('active');



// ── LOBBY MUSIC ──
const lobbyMusic = document.getElementById('lobby-music');
lobbyMusic.volume = 0.45;

// Start music on first any interaction
let musicStarted = false;
function startMusicOnce() {
  if (musicStarted) return;
  musicStarted = true;
  lobbyMusic.play().catch(() => {});
}
document.addEventListener('click',   startMusicOnce);
document.addEventListener('keydown', startMusicOnce);

// Pause when game starts, resume in lobby
const _origStartBR = startBattleRoyale;
startBattleRoyale = function() { lobbyMusic.pause(); _origStartBR(); };
const _origStartRace = startRaceGame;
startRaceGame = function() { lobbyMusic.pause(); _origStartRace(); };
const _origCloseResult = closeResult;
closeResult = function() { _origCloseResult(); if(musicStarted) lobbyMusic.play().catch(()=>{}); };
const _origCancelMM = cancelMatchmaking;
cancelMatchmaking = function() { _origCancelMM(); };

// Music toggle button
document.getElementById('music-toggle').addEventListener('click', (e) => {
  e.stopPropagation(); // don't trigger startMusicOnce again
  if(!musicStarted){ startMusicOnce(); return; }
  if (lobbyMusic.paused) {
    lobbyMusic.play().catch(()=>{});
    document.getElementById('music-toggle').textContent = '🔊';
  } else {
    lobbyMusic.pause();
    document.getElementById('music-toggle').textContent = '🔇';
  }
});
</script>
</body>
</html>
