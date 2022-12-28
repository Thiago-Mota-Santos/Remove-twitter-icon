`function removeIcon () {  
 setInterval(() => {
[...document.querySelectorAll(".css-1dbjc4n.r-18u37iz.r-1h0z5md")].filter(div => div.innerHTML.includes("analytics")).forEach(div => div.remove())
}, 50)
};
removeIcon()
`

código javascript, apenas abra o inspecionar elemento e cole o código no console, vídeo abaixo para exemplificar.


https://user-images.githubusercontent.com/75326612/209752357-13bb7176-6329-4eed-8c66-f1943ea0a189.mp4

