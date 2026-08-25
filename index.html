<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>KAWA - School Mode - Auto Dispatch Uganda</title>
<style>
body{margin:0;font-family:Arial;background:#f8fafc;padding-bottom:80px}
header{background:#16a34a;color:#fff;padding:12px;text-align:center}
.btn{background:#16a34a;color:#fff;padding:14px;text-decoration:none;border-radius:10px;display:block;margin:8px auto;font-weight:bold;text-align:center;width:90%;border:none;cursor:pointer}
.emergency{background:#dc2626;color:#fff;padding:10px;text-align:center;font-weight:bold}
.tabs{display:flex;justify-content:center;gap:4px;margin:6px;flex-wrap:wrap}
.tab{padding:7px 10px;border-radius:20px;border:2px solid #16a34a;background:#fff;font-weight:bold;font-size:10px;cursor:pointer}
.tab.active{background:#dc2626;color:#fff;border-color:#dc2626}
.box{background:#fff;margin:8px;padding:12px;border-radius:10px}
.card{border:1px solid #ddd;padding:10px;border-radius:8px;margin:6px 0;background:#fff7ed;font-size:12px}
.school{background:#000;color:#fff;padding:12px;border-radius:10px;margin:8px;text-align:center;border:2px solid #facc15}
.switch{width:60px;height:30px;background:#666;border-radius:20px;position:relative;display:inline-block;cursor:pointer}
.switch.on{background:#16a34a}
.dot{width:26px;height:26px;background:#fff;border-radius:50%;position:absolute;top:2px;left:2px;transition:0.3s}
.switch.on.dot{left:32px}
#chatBtn{position:fixed;bottom:15px;right:15px;background:#16a34a;color:#fff;width:60px;height:60px;border-radius:50%;border:none;font-size:28px;cursor:pointer;z-index:999}
#chatBox{position:fixed;bottom:85px;right:10px;width:300px;background:#fff;border-radius:15px;box-shadow:0 5px 20px rgba(0,0,0,0.3);display:none;z-index:998;overflow:hidden}
#chatHead{background:#16a34a;color:#fff;padding:10px;font-weight:bold;display:flex;justify-content:space-between}
#chatBody{height:220px;overflow-y:auto;padding:10px;background:#f0fdf4}
.msg{padding:7px 10px;border-radius:10px;margin:5px 0;font-size:11px}
.bot{background:#dcfce7;border-left:3px solid #16a34a}
.user{background:#16a34a;color:#fff;text-align:right;margin-left:15px}
.quickBtn{background:#fff;border:1px solid #16a34a;color:#16a34a;padding:5px 9px;border-radius:15px;font-size:10px;margin:3px;cursor:pointer;display:inline-block}
.track{background:#fef3c7;border:2px dashed #f59e0b;padding:10px;border-radius:10px;margin:8px 0;font-size:11px}
</style>
</head>
<body>
<header>
<h2 style="margin:0">KAWA - AUTO DISPATCH 🇺🇬</h2>
<p style="margin:2px;font-size:10px">School Mode ON = Business runs without your phone!</p>
</header>
<div class="school">
<h3 style="margin:0">🏫 SCHOOL MODE - CEO AT SCHOOL</h3>
<p style="font-size:11px;margin:4px">Turn ON when you enter class - system handles customers automatically</p>
<div style="display:flex;align-items:center;justify-content:center;gap:10px;margin-top:8px">
<span>OFF</span><div id="schoolSwitch" class="switch" onclick="toggleSchool()"><div class="dot"></div></div><span>ON</span>
</div>
<p id="schoolStatus" style="font-size:11px;color:#facc15;margin:5px 0">● Manual Mode - Bookings come to YOU 0792664825</p>
</div>
<div class="emergency">🚨 GARAGE NEAR ME - AUTO ASSIGN IN 30 SECONDS - 0792664825</div>
<div class="tabs">
<button class="tab" id="t-boda" onclick="showTab('boda')">Boda Near Me</button>
<button class="tab" id="t-delivery" onclick="showTab('delivery')">Delivery</button>
<button class="tab" id="t-truck" onclick="showTab('truck')">Truck Hotel</button>
<button class="tab active" id="t-garage" onclick="showTab('garage')">Garage Near Me</button>
<button class="tab" id="t-upcountry" onclick="showTab('upcountry')">Bus Near Me</button>
</div>
<div id="boda" style="display:none"><div class="box"><h3>🛵 Boda Near Me - Auto Dispatch</h3><input id="b_from" placeholder="From - e.g. Wandegeya"><input id="b_to" placeholder="To - e.g. Nakawa"><button class="btn" onclick="dispatch('Boda', 'b_from', 'b_to')">BOOK & AUTO ASSIGN</button><div id="b_track"></div></div></div>
<div id="delivery" style="display:none"><div class="box"><h3>📦 Delivery Near Me - Auto Dispatch</h3><input id="d_what" placeholder="What to deliver?"><input id="d_from" placeholder="Pickup"><input id="d_to" placeholder="Drop"><button class="btn" style="background:#ea580c" onclick="dispatch('Delivery','d_from','d_to')">BOOK & AUTO ASSIGN</button><div id="d_track"></div></div></div>
<div id="truck" style="display:none"><div class="box"><h3>🚚 Truck Hotel Near Me</h3><div class="card">Parking - Book auto</div><button class="btn" onclick="dispatch('Truck Hotel','', '')">BOOK TRUCK HOTEL</button><div id="t_track"></div></div></div>
<div id="garage" style="display:block"><div class="box"><h3>🔧 Garage Near Me - YOUR NETWORK</h3>
<div class="card">📍 <b>JINJA</b> - Mechanic - 0791862199 - 20K-150K - Auto assigned for Jinja customers</div>
<div class="card">📍 <b>TORORO</b> - Mechanic - 0782069431 - 20K-200K - Auto assigned for Tororo/Malaba</div>
<div class="card">📍 <b>KAMPALA</b> - Mechanic - 0777341255 - 10K-100K - Auto assigned for Kampala/Wandegeya</div>
<input id="g_loc" placeholder="Customer location - e.g. Jinja, Tororo, Kampala">
<input id="g_prob" placeholder="Problem - e.g. tyre, engine">
<button class="btn" style="background:#dc2626" onclick="dispatch('Garage','g_loc','g_prob')">🚨 ASSIGN NEAREST MECHANIC AUTOMATICALLY</button>
<div id="g_track"></div>
</div></div>
<div id="upcountry" style="display:none"><div class="box"><h3>🚌 Bus Near Me</h3><input id="u_from" placeholder="From"><input id="u_to" placeholder="To"><button class="btn" onclick="dispatch('Bus','u_from','u_to')">BOOK BUS</button><div id="u_track"></div></div></div>
<button id="chatBtn" onclick="toggleChat()">💬</button>
<div id="chatBox">
<div id="chatHead"><span>AUTO-BOT 🤖 <span id="botMode" style="font-size:9px;background:#000;padding:2px 5px;border-radius:10px">MANUAL</span></span><span onclick="toggleChat()">✖</span></div>
<div id="chatBody"></div>
<div style="padding:8px"><div id="quick"></div></div>
</div>
<script>
const garages = [
 {town:'jinja', name:'Jinja Mechanic', phone:'256791862199', price:'30K', time:'20 min'},
 {town:'tororo', name:'Tororo Mechanic', phone:'256782069431', price:'40K', time:'25 min'},
 {town:'kampala', name:'Kampala Mechanic Wandegeya', phone:'256777341255', price:'20K', time:'15 min'},
 {town:'busia', name:'Busia Border Mechanic', phone:'256791862199', price:'40K', time:'25 min'},
 {town:'mbale', name:'Mbale Mechanic', phone:'256782069431', price:'35K', time:'20 min'},
 {town:'mbarara', name:'Mbarara Mechanic', phone:'256777341255', price:'40K', time:'20 min'}
];
let schoolMode = false;
function toggleSchool(){
 schoolMode =!schoolMode;
 document.getElementById('schoolSwitch').classList.toggle('on');
 document.getElementById('schoolStatus').innerText = schoolMode? '● SCHOOL MODE ON - Auto dispatch to garages! You are free! 🎉' : '● Manual Mode - Bookings come to YOU 0792664825';
 document.getElementById('botMode').innerText = schoolMode? 'SCHOOL AUTO' : 'MANUAL';
 if(schoolMode){addMsg('🏫 School Mode ON! I will handle customers. Go to class! I auto-assign to your 3 garages.', 'bot');}
}
function showTab(id){['boda','delivery','truck','garage','upcountry'].forEach(x=>{document.getElementById(x).style.display=x==id?'block':'none';document.getElementById('t-'+x).classList.remove('active');});document.getElementById(id).style.display='block';document.getElementById('t-'+id).classList.add('active');}
function toggleChat(){var b=document.getElementById('chatBox');b.style.display=b.style.display=='none' || b.style.display==''?'block':'none';}
function addMsg(t,w){var d=document.getElementById('chatBody');var m=document.createElement('div');m.className='msg '+w;m.innerText=t;d.appendChild(m);d.scrollTop=d.scrollHeight;}
function setQuick(o){var q=document.getElementById('quick');q.innerHTML='';o.forEach(x=>{var b=document.createElement('span');b.className='quickBtn';b.innerText=x.t;b.onclick=x.f;q.appendChild(b);});}
function findGarage(location){
 location=location.toLowerCase();
 let found = garages.find(g=>location.includes(g.town));
 if(!found) found = garages;
 return found;
}
function dispatch(service, fromId, toId){
 let loc = fromId? document.getElementById(fromId).value : 'Kampala';
 if(!loc) loc = 'Kampala';
 let detail = toId? document.getElementById(toId).value : '';
 let garage = findGarage(loc);
 let trackId = 'KAWA-'+Math.floor(1000+Math.random()*9000);
 let msg = `TRACKING ${trackId}\nService: ${service} Near Me in ${loc}\nProblem: ${detail}\n\nCustomer needs help!`;
 let trackHtml = `<div class="track">
 ✅ <b>AUTO ASSIGNED! ID: ${trackId}</b><br>
 📍 Location: ${loc}<br>
 🔧 Assigned: ${garage.name}<br>
 📞 Garage: ${garage.phone}<br>
 ⏱️ Arriving: ${garage.time}<br>
 💰 Price: ${garage.price} (pay after work)<br>
 ${schoolMode? '🏫 CEO at school - System auto-handling!' : '📲 CEO notified - 0792664825'}<br><br>
 <button onclick="window.open('https://wa.me/${garage.phone}?text=${encodeURIComponent(msg)}','_blank')" style="background:#16a34a;color:#fff;border:none;padding:8px 12px;border-radius:8px;width:100%;margin:3px 0">📲 CONTACT ASSIGNED MECHANIC NOW</button>
 <button onclick="window.open('https://wa.me/256792664825?text=Feedback%20for%20${trackId}%20-${garage.name}%20assigned','_blank')" style="background:#000;color:#fff;border:none;padding:8px 12px;border-radius:8px;width:100%">💬 SEND FEEDBACK TO CUSTOMER</button>
 </div>`;
 if(service=='Garage') document.getElementById('g_track').innerHTML=trackHtml;
 if(service=='Boda') document.getElementById('b_track').innerHTML=trackHtml;
 if(service=='Delivery') document.getElementById('d_track').innerHTML=trackHtml;
 if(service=='Truck Hotel') document.getElementById('t_track').innerHTML=trackHtml;
 if(service=='Bus') document.getElementById('u_track').innerHTML=trackHtml;
 if(schoolMode){
   setTimeout(()=>{
     window.open(`https://wa.me/${garage.phone}?text=${encodeURIComponent('🚨 NEW KAWA CUSTOMER! '+service+' in '+loc+' - '+detail+' - Call customer ASAP! Track:'+trackId)}`,'_blank');
     addMsg(`✅ Auto-dispatched to ${garage.name} (${garage.phone}) for ${loc}. Customer got tracking ${trackId}. You can stay in class!`, 'bot');
   },800);
 } else {
   addMsg(`✅ Customer in ${loc} assigned to ${garage.name}. Tracking ${trackId} created.`, 'bot');
   window.open(`https://wa.me/256792664825?text=${encodeURIComponent(msg+' Assigned to '+garage.name)}`,'_blank');
 }
 setTimeout(()=>{
   document.getElementById('chatBox').style.display='block';
   addMsg(`🎉 Your ${service} Near Me in ${loc} is confirmed!\nID: ${trackId}\nMechanic ${garage.name} is coming in ${garage.time}!\nHe will call you now. Price ${garage.price}`, 'bot');
 },500);
}
setTimeout(()=>{document.getElementById('chatBox').style.display='block';addMsg('Hello! I am KAWA AUTO DISPATCH BOT 🤖 I work even when boss is at school! Where are you?', 'bot');setQuick([{t:'📍 Jinja - 0791862199',f:()=>{document.getElementById('g_loc').value='Jinja';showTab('garage');}},{t:'📍 Tororo - 0782069431',f:()=>{document.getElementById('g_loc').value='Tororo';showTab('garage');}},{t:'📍 Kampala - 0777341255',f:()=>{document.getElementById('g_loc').value='Kampala';showTab('garage');}}])},3000);
</script>
</body>
</html>[2]
