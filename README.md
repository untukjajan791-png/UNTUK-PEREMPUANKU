<html>
<meta charset='UTF-8'/><meta content='width=device-width, initial-scale=1, user-scalable=1, minimum-scale=1, maximum-scale=5' name='viewport'/><meta content='IE=edge' http-equiv='X-UA-Compatible'/>
  
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Nunito+Sans:wght@400;700&display=swap" rel="stylesheet">
  <link href="https://fonts.googleapis.com/css2?family=Sono:wght@600&display=swap" rel="stylesheet">
  <link href="https://fonts.googleapis.com/css2?family=Nerko+One&display=swap" rel="stylesheet">

  <script src="https://cdn.jsdelivr.net/npm/sweetalert2@11.0.19/dist/sweetalert2.all.min.js"></script>
  <script src="https://unpkg.com/typeit@8.7.0/dist/index.umd.js"></script><link href="https://feeldreams.github.io/dibacadong/style.css" rel="stylesheet" type="text/css" />
  <script src="https://kit.fontawesome.com/4f3ce16e3e.js" crossorigin="anonymous"></script>
  
<head>
<title>UNTUK PEREMPUANKU - Feeldream.id</title>
<meta name="description" content="HTML Replit Coding">
<!-- 
  Made with love by Rayys!
  
     Blog: feeldream.id
     Instagram: @rayyarrr
     TikTok: @feelthisray
     Email: rayyarr73@gmail.com
     
  Thanks to all <3
-->
</head>
<body>
	
   <!-- Ganti Audio di sini -->
   <audio src="https://feeldreams.github.io/audio/seandainya.mp3" id="linkmp3" class="sembunyi"></audio>
   
   <div id="bodyblur">
     <!-- Wallpaper --><img src="https://feeldreams.github.io/papjalan2.jpeg" id="wallpaper"/>
   </div>
   
   <div id='Content'>

     <div id="ftAwal">
       <!-- Stiker Pembuka -->
       <img src="https://feeldreams.github.io/pandaputih.gif" id="ftoAwal"/>
     </div>

     <div id="loveIn">
       <!-- Tombol LOVE --><label class='lovein'>&#10084;</label>
     </div>
     <p id="ket">Sentuh LOVEnya!</p>

     <div class="kumpulanstiker">
         <!-- Stiker untuk Konten -->
         <img src="https://feeldreams.github.io/bwa2.gif" id="fotostiker"/>
         <img src="https://feeldreams.github.io/wortel.gif" id="fotostiker1"/>
         <img src="https://feeldreams.github.io/ngumpet.gif" id="fotostiker2"/>
         <img src="https://feeldreams.github.io/pusn.gif" id="fotostiker3"/>
     </div>
     
     <div class="kumpulanwp" class="sembunyi">
     	<img src="https://i.imgur.com/teDEram.jpeg" id="wallpaper2"/>
         <img src="https://i.imgur.com/laYA8ld.jpeg" id="wallpaper3"/>
         <img src="https://i.imgur.com/iyIycwd.jpeg" id="wallpaper4"/>
     </div>
     
     <div><div id='pergeseran'>
     	
        <p><b>
	        <span>halooo syngggg</span>
        </b></p>
        
        <p><b>
	        <span>kamu Nayla yaaa<br>ini spesial buat kamu</span>
        </b></p>

        <p><b>
	        <span>aku cuma mau bilang</span>
        </b></p>
        
        <p><b>
	        <span>pncet ini dlu ya 👉💌</span>
        </b></p>
        
     </div></div>

     <p id="ketgeser">Klik untuk Geser!</p>

     <div><blockquote id='bq'>
       <p id="kalimat">happy birthday cantikkk. . . 🤸🏻‍♀ 🤸🏻‍♀ cie cie sekarang kamu suda nambah tua ૮ ˙Ⱉ˙ ა semoga sehat selalu , panjang umur dan semua yang kamu mau segera tercapai . . . hmmm syngggg hebat bisa bertahan dan lalui semua masala masala yang datanggg🤭<br><br>semoga hal baik selalu ada disamping kamuu 😻🙌🏻 semogaa dii umur kamu yangg sekarangg apapun yang kamu impikann dii umur sebelumnyaa bisaa terwujud yaaa , semogaa panjangg umur, sehat selaluuUu, mudah rezeki nyaa, jangan pernah nyerah hal apapun itu ya untuk umur kamu yangg baruu dan untuk kedepannyaa 😁🙆🏻‍♀️,<br><br>ujian apapunn ituu, seberatt apapun ituu nantii kamu jalanin nya haruss kuatt okeyyyy? kamu pasti bisaa lewatin ujian yangg kamu hadapii, ingat yaaa jangan lupa baik sama diri kamu sendirii sebelum kamu baik sama orang lainn, terimakasiii sudaaaa sekuat inii, banyak hal yang udah kamu lewatii dan banyak juga yangg belum kamu alamii📝<br><br></p>semakin dewasa semakin banyak tantangan yang synggg alamii, but its okeyy selagi kamu yakin sama dirii sendirii dan takdir semua akan baikk baikk aja percaya ajaa yaa, sesedih apapun jangan lupa untuk selalu bersyukur yaaa, semoga banyak kebahagiaann yangg kembaliii pada hariii iniiii kalau sayang ada masalah tanya akuu yaaa jangan di pendam sendirii okeyyy🙇🏻‍♀️
       <p id="pesanAkhir">INTINYAA HABEDE SAYANGGG SEMOGA PANJANG UMUR SEHATT SELALUU YAAAA🫶😻stay with me. i love uuuu, FROM FINZZ🥹🤍</p>
     </blockquote></div>
     
   </div>

<script>const body = document.querySelector("body"); const iniwp = [];iden = 1; iniwp[1] = wallpaper.src; iniwp[2] = wallpaper2.src; iniwp[3] = wallpaper3.src; iniwp[4] = wallpaper4.src; katakata = kalimat.innerHTML;pesanAkhir2 = pesanAkhir.innerHTML;kalimat.innerHTML = "";pesanAkhir.innerHTML=""; const swalst = Swal.mixin({timer: 2500, allowOutsideClick: false, showConfirmButton: false, timerProgressBar: true, imageHeight: 90,}); audio = new Audio('' + linkmp3.src); ftganti=0;fungsi=0;fungsiAwal=0;deffotostiker=fotostiker.src;function berjatuhan() {const heart = document.createElement("div"); heart.className = "fas fa-heart"; heart.style.left = (Math.random() * 90)+"vw"; heart.style.animationDuration = (Math.random()*3)+2+"s"; body.appendChild(heart);} setInterval(function name(params) {var heartArr = document.querySelectorAll(".fa-heart"); if (heartArr.length > 100) {heartArr[0].remove()}},100);Content.style = "opacity:1;margin-top:14vh"; const swals = Swal.mixin({allowOutsideClick: false, cancelButtonColor: '#FF0040', imageHeight: 80,}); </script>
<script src="https://feeldreams.github.io/dibacadong/script.js"></script>
</body>
</html>
