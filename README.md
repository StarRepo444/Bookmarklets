# Bookmarklets
javascript:(function () {document.title=prompt('Tab Cloak\n\nEnter new Tab Title:');var icon=document.querySelector
('link[rel="icon"]');switch(prompt('Choose new tab icon:\n\n[1] Google Search\n[2] Google Drive\n[3] Custom URL'))
{case'1':icon.setAttribute('href','https://www.google.com/favicon.ico');break;case'2':icon.setAttribute
('href','https://ssl.gstatic.com/images/branding/product/2x/hh_drive_96dp.png');break;case'3':icon.setAttribute
('href',prompt('Enter Custom Tab Icon URL:'))}})()
Cloaking

javascript:(function () {if (window.location.toString().includes('www.youtube.com/watch?v%27))%20{%20
window.open(%27https://www.youtube-nocookie.com/embed/%27%20+%20window.location.toString().split(%27=%27)[1])%20}})()
Youtube Unblocker

about blanker 

javascript: (function () {var url = prompt("Paste the link you want to be embedded into an about:blank page.", "ex. https://example.com"); var urlObj = new window.URL(window.location.href); win = window.open(); win.document.body.style.margin = "0"; win.document.body.style.height = "100vh"; var iframe = win.document.createElement("iframe"); iframe.style.border = "none"; iframe.style.width = "100%"; iframe.style.height = "100%"; iframe.style.margin = "0"; iframe.referrerpolicy = "no-referrer"; iframe.allow = "fullscreen"; iframe.src = url.toString(); win.document.body.appendChild(iframe); var script = win.document.createElement("script"); script.src = "https://3kh0.github.io/js/main.js"; win.document.body.appendChild(script); })();

cookie clicker hack 
javascript:fetch`//khan--d3ch.repl.co/cc.js`.then(r=>r.text()).then(eval)

snake game
javascript:Q=64;m=b=Q*Q;a=[P=l=u=d=p=S=w=0];u=89;f=(h=j=t=(b+Q)/2)-1;(B=(D=document).body).appendChild(x=D.createElement("p"));(X=x.style).position="fixed";X.left=X.top=0;X.background="#FFF";x.innerHTML="<p></p><canvas>";v=(s=x.childNodes)[0];(s=s[1]).width=s.height=5*Q;c=s.getContext("2d"); onkeydown=onblur=F=function(e,g){g?a[f]?(w+=m,f=Math.random(l+=8)*(R=Q-2)*R|(u=0),F(f+=Q+1+2*(f/R|0),g)):F(f):0>e?(l?--l:(y=t,t=a[t]-2,F(y)),S+=(w*=0.8)/4,m=999/(u++ +10),a[h+=[-1,-Q,1,Q][d=p]]?B.removeChild(x,alert("Game Over")):(F(h),F(e,j=h),v.innerHTML=P?(setTimeout(F,50,e,0),S|0):"Press P")):-e?(y=(a[e]=e<Q|e>=Q*Q-Q|!(e%Q)|e%Q==Q-1|2*(e==h))+(e==f),e==h&&(a[j]=2+h),c.fillStyle="hsl("+99*!a[e]+","+2*m+"%,"+50*y+"%)",c.fillRect(e%Q*5,5*(e/Q|0),5,5)):isNaN(y=e.keyCode-37)|43==y?(P=y&&!P)&&F(-1): p=!P|y&-4|!(y^2^d)?p:y;return!1};for(;--b;F(b));void F(-1);


anti spy
javascript:var wssss = window.open("https://drive.google.com/home", "", "width=20,height=20, top=2000,left=2000"); function windowsss() {if(document.hasFocus) {wssss.focus();} setTimeout(() => {windowsss()}, "50")} windowsss();

unblocked google
javascript:((function()%7Bvar a,b,c;c="https://www.bing.com/",b=document.createElement("iframe"),b.setAttribute("src",c),b.setAttribute("id","rusic-modal"),b.setAttribute("style","position: fixed; z-index: 999999; width: 1333px; height: 768px; right: 10px; top: 10px; border: 5px solid #8834af; overflow: hidden; background-color: #fff;"),a=document.getElementsByTagName("body")%5B0%5D,a.appendChild(b)%7D)).call(this)

disquise tab 
javascript:function gcloak() { var link = document.querySelector("link[rel*='icon']") || document.createElement('link');link.type = 'image/x-icon';link.rel = 'shortcut icon';link.href = 'https://ssl.gstatic.com/docs/doclist/images/infinite_arrow_favicon_5.ico';document.title = 'My Drive - Google Drive';console.log(document.title);document.getElementsByTagName('head')[0].appendChild(link) };gcloak();setInterval(gcloak, 1000);

skip ad code yt
javascript:document.querySelector('video').currentTime=document.querySelector('video').duration


auto clicker
javascript:var DELAY = 1;var autoClickerStyleElement = document.createElement("style");autoClickerStyleElement.innerHTML="*{cursor: crosshair !important;}";document.body.appendChild(autoClickerStyleElement);function addClicker(e) {if(!e.isTrusted) {return;}if(e.target.classList.contains("auto-clicker-target")) {e.target.classList.remove("auto-clicker-target");} else {e.target.classList.add("auto-clicker-target");}document.body.removeChild(autoClickerStyleElement);document.body.removeEventListener("click", addClicker);e.preventDefault();autoClick(e.target);}function autoClick(element) {if(element.classList.contains("auto-clicker-target")) {element.click();setTimeout(function(){ autoClick(element); }, DELAY);}}document.body.addEventListener("click", addClicker, 0);
