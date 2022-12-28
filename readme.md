function removeIcon () {  
 setInterval(() => {
[...document.querySelectorAll(".css-1dbjc4n.r-18u37iz.r-1h0z5md")].filter(div => div.innerHTML.includes("analytics")).forEach(div => div.remove())
}, 50)
};
removeIcon()

código javascript, apenas abra o inspecionar elemento e cole o código no console, vídeo abaixo para exemplificar.
