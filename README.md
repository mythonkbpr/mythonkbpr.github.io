<!DOCTYPE html>
<html>
<meta charset='UTF-8'/>
<meta content='width=device-width, initial-scale=1, user-scalable=1, minimum-scale=1, maximum-scale=5' name='viewport'/><script src="https://cdn.jsdelivr.net/npm/sweetalert2@11.0.19/dist/sweetalert2.all.min.js"></script>
<meta content='IE=edge' http-equiv='X-UA-Compatible'/><link href="https://drive.google.com/uc?export=view&id=13iETBw-nS1hNeBcWUbkRyc69WByi_IpO" rel="stylesheet" type="text/css" />

<head>
<title>Script HTML Untukmu</title>
<meta name="description" content="Script HTML Replit">

  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Josefin+Sans:wght@400;700&display=swap" rel="stylesheet">
</head>
<body>
    
   <!-- Ganti Audio di sini --><audio src="https://mythonkbpr.github.io/sound.mp3" id="linkmp3"></audio><script>audio = new Audio('' + linkmp3.src);</script>
   
   <div id="bodyblur">
     <!-- Wallpaper --><img src="https://mythonkbpr.github.io/20220930_183506.jpg" id="wallpaper"/>
   </div>

   <div id='Content'>
       
     <div id="suratin" onClick="memulai();">
       <!-- Tombol Surat --><img src="https://rayyscoding.github.io/envelope.png"/>
     </div>
     <p id="ket">Klik Pesannya!</p>
   
     <div>
         <!-- Stiker untuk Konten -->
         <img src="https://feeldreams.github.io/peach22.gif" id="fotoakhir"/>
         <img src="https://feeldreams.github.io/peachgetar.gif" id="fotoakhir1"/>
         <img src="https://feeldreams.github.io/peachhoam.gif" id="fotoakhir2"/>
         <img src="https://feeldreams.github.io/peachktw2.gif" id="fotoakhir3"/>

         <img src="https://feeldreams.github.io/peachktw.gif" id="fotoAkhir"/>
     </div>
     <div><blockquote id='bq'>
  
       <!-- Konten Penerapan -->
       <p id="kalimat">Hai sayang, Kamu mau jadi pacar aku ?😍😘😘</p>
       <p id="kalimata">If you do not want😘😘</p>
       <p id="kalimatb">I will cry</p>
       <p id="kalimatc">Huuuu Huuuu</p>

       <!-- Konten Pertanyaan -->
       <p id="kalimat2">Becanda sha🤣❤️</p>

       <!-- Konten Jawaban -->
       <p id="kalimat3">Your answer: </p>
       <p id="kalimatb3">jawaban anda krim ke chat aku ya. </p>
     </blockquote></div>
   
     <!-- Tombol Multifungsi -->
     <div id="Tombol">
       <a id="By" onClick="multifungsi()">
         <b id="tmbl">Lanjut</b>
         <b id="tmbl2">💌 Balas</b>
       </a>
     </div>
     
   </div>

<!-- Jangan Edit Bagian Ini --><script>
  const swalst = Swal.mixin({timer: 2777, allowOutsideClick: false, showConfirmButton: false, timerProgressBar: true, imageHeight: 100,}); ftom=0;jikatom=0;ftganti=0;fungsi=0;const swals = Swal.mixin({allowOutsideClick: false, cancelButtonColor: '#FF0040', imageWidth: 100, imageHeight: 100,}); const body = document.querySelector("body");function createHeart() {const heart = document.createElement("div"); heart.className = "fas fa-heart"; heart.style.left = (Math.random() * 90)+"vw"; heart.style.animationDuration = (Math.random()*3)+2+"s"; body.appendChild(heart);} setInterval(function name(params) {var heartArr = document.querySelectorAll(".fa-heart"); if (heartArr.length > 100) {heartArr[0].remove()}},100);
  function mulaikonten() {fungsi=1;suratin.style="display:none";ket.style="display:none";Content.style = "opacity:1;margin-top:4vh;";bodyblur.style="opacity:.3;animation:none";wallpaper.style="transform: scale(1);";bq.style = "position:relative;opacity:1;visibility:visible;margin-top:0;";audio.play();ftganti=0;ftmuncul();
                          setTimeout(fmketik1,1500);setTimeout(mketik1,1500);
                          setTimeout(fmketik2,3800);setTimeout(mketik2,3800);
                          setTimeout(fmketik3,5200);setTimeout(mketik3,5200);
                          setTimeout(fmketik4,7200);setTimeout(mketik4,7200);
                         }

   async function jawab(){
           var { value: jawaban } = await swals.fire({
               title: 'Sayank sama aku kan?😁 &#128073;&#128072;', input: 'text', allowOutsideClick: false, showCancelButton: false,
           });
           if(jawaban && jawaban.length < 19){
               window.jawaban = jawaban;
               pesanwhatsapp = jawaban;
               balasan = jawaban;
               otomatis3();setTimeout(stakhir,1000);
           } else {
               await swals.fire('Ups!', 'Jawaban ga boleh kosong atau lebih dari 18 karakter sha.');jawab();
           }
       }
   
   async function menuju(){await swals.fire('OK!', 'Kirim pesan ke WhatsApp aku, ya!', 'success');window.location = "https://api.whatsapp.com/send?phone=&text=" + pesanwhatsapp;Tombol.style="margin-top:15px;opacity:1;transform: scale(1);";}
</script>
<script 
//src="https://feeldreams.github.io/bukahiya.js"></script>
<!-- Sampai Sini -->
</body>
</html>
