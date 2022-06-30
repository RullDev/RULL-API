<p align="center"> 
 <img src="https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/ea5fe983-3ed6-4652-84a4-933a663d784b/deytppn-e87cdb19-ad39-4247-b629-9dcede510a32.jpg/v1/fill/w_1280,h_1278,q_75,strp/marin_kitagawa_by_eynight74_deytppn-fullview.jpg?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOjdlMGQxODg5ODIyNjQzNzNhNWYwZDQxNWVhMGQyNmUwIiwiaXNzIjoidXJuOmFwcDo3ZTBkMTg4OTgyMjY0MzczYTVmMGQ0MTVlYTBkMjZlMCIsIm9iaiI6W1t7ImhlaWdodCI6Ijw9MTI3OCIsInBhdGgiOiJcL2ZcL2VhNWZlOTgzLTNlZDYtNDY1Mi04NGE0LTkzM2E2NjNkNzg0YlwvZGV5dHBwbi1lODdjZGIxOS1hZDM5LTQyNDctYjYyOS05ZGNlZGU1MTBhMzIuanBnIiwid2lkdGgiOiI8PTEyODAifV1dLCJhdWQiOlsidXJuOnNlcnZpY2U6aW1hZ2Uub3BlcmF0aW9ucyJdfQ.pFnKndipzybcE3VAU2em7bK1wORwu9UZGgFUDpccpsw" alt="MARIN MD" width="250"/> 
  
  
 </p> 
 <p align="center"> 
 <a href="#"><img title="MARIN MD" src="https://img.shields.io/badge/GANTI SESSIONNYA DULU SEBELUM PAKAI,DAN JANGAN LUPA GANTI APIKEY NYA SEBELUM PAKAI-red?colorA=%255ff0000&colorB=%23017e40&style=for-the-badge"></a> 
 </p> 
 <p align="center"> 
 </p> 
 <a href="#"><img title="PENTING" src="https://img.shields.io/badge/BAGI USER TERMUX HARAP BACA README-red?colorA=%255ff0000&colorB=%23971920&style=for-the-badge"></a> 
 </p> 
 <p align="center"> 
 </p> 
 <p align="center"> 
 <a href="https://github.com/FahriAdison/Marin-MD/network/members"><img title="Forks" src="https://img.shields.io/github/forks/FahriAdison/Marin-MD?label=Forks&color=blue&style=flat-square"></a> 
 <a href="https://github.com/FahriAdison/Marin-MD/watchers"><img title="Watchers" src="https://img.shields.io/github/watchers/FahriAdison/Marin-MD?label=Watchers&color=green&style=flat-square"></a> 
 <a href="https://github.com/FahriAdison/Marin-MD/stargazers"><img title="Stars" src="https://img.shields.io/github/stars/FahriAdison/Marin-MD?label=Stars&color=yellow&style=flat-square"></a> 
 <a href="https://github.com/FahriAdison/Marin-MD/graphs/contributors"><img title="Contributors" src="https://img.shields.io/github/contributors/FahriAdison/Marin-MD?label=Contributors&color=blue&style=flat-square"></a> 
 <a href="https://github.com/FahriAdison/Marin-MD/issues"><img title="Issues" src="https://img.shields.io/github/issues/FahriAdison/Marin-MD?label=Issues&color=success&style=flat-square"></a> 
 <a href="https://github.com/FahriAdison/Marin-MD/issues?q=is%3Aissue+is%3Aclosed"><img title="Issues" src="https://img.shields.io/github/issues-closed/FahriAdison/Marin-MD?label=Issues&color=red&style=flat-square"></a> 
 <a href="https://github.com/FahriAdison/Marin-MD/pulls"><img title="Pull Request" src="https://img.shields.io/github/issues-pr/FahriAdison/Marin-MD?label=PullRequest&color=success&style=flat-square"></a> 
 <a href="https://github.com/FahriAdison/Marin-MD/pulls?q=is%3Apr+is%3Aclosed"><img title="Pull Request" src="https://img.shields.io/github/issues-pr-closed/FahriAdison/Marin-MD?label=PullRequest&color=red&style=flat-square"></a> 
 </p> 
  
 --- 
  
 # Marin Whatsapp MD 
 ## Information 
 > Marin whatsapp using a Baileys library. 
 > Jika kamu menemukan semacam bug, harap untuk dimaklumi sementara 
 > 
 > • NOTE: INI SC GAK BISA BUAT SESSION DI TERMUX YA, JADI KALIAN CARI SESSION DULU PAKAI SC LAIN  
 > • rekomendasi sc buat cari session [disini](https://github.com/ilmanhdyt/ShiraoriBOT-Md) 
 > 
 > • NOTE: Pastikan Jaringan kalian lancar dan device kalian bagus:v,  
 >  
 > • Kalo pake termux mungkin bakal lama respon nya, saya sarankan pake heroku 
 >  
  
 <h3 align="center">Made by :</h3> 
 <p align="center"> 
   </a href="https://github.com/ilmanhdyt"><img src="https://github.com/Paquito1923.png?size=128" height="128" width="128" /></a> 
   </a href="https://github.com/ilmanhdyt"><img src="https://github.com/ilmanhdyt.png?size=128" height="128" width="128" /></a> 
   <a href="https://github.com/BochilGaming"><img src="https://github.com/BochilGaming.png?size=128" height="128" width="128" /></a> 
   <h3 align="center">Recode By :</h3> 
 <p align="center"> 
   </a href="https://github.com/FahriAdison"><img src="https://github.com/FahriAdison.png?size=128" height="128"  
 </p> 
  
 ## How To Change Menu Display 
 ---- 
 ### Gif Menu Display 
 ```ts 
  let message = await prepareWAMessageMedia({ video: fs.readFileSync('./media/menu.mp4'), gifPlayback: true }, { upload: conn.waUploadToServer }) 
      const template = generateWAMessageFromContent(m.chat, proto.Message.fromObject({ 
      templateMessage: { 
          hydratedTemplate: { 
            videoMessage: message.videoMessage, 
            hydratedContentText: text.trim(), 
            hydratedFooterText: wm, 
            hydratedButtons: [{ 
 ``` 
  
 ### Image Menu Display 
 ```ts 
 let message = await prepareWAMessageMedia({ image: fs.readFileSync('./media/elyas.jpg')}, { upload: conn.waUploadToServer }) 
      const template = generateWAMessageFromContent(m.chat, proto.Message.fromObject({ 
      templateMessage: { 
          hydratedTemplate: { 
            imageMessage: message.imageMessage, 
            hydratedContentText: text.trim(), 
            hydratedFooterText: wm, 
            hydratedButtons: [{ 
 ``` 
  
 ### Location Menu Display 
 ```ts 
  const template = generateWAMessageFromContent(m.chat, proto.Message.fromObject({ 
      templateMessage: { 
          hydratedTemplate: { 
            hydratedContentText: text.trim(), 
            locationMessage: {  
            jpegThumbnail: fs.readFileSync('./media/elyas.jpg') }, 
            hydratedFooterText: wm, 
            hydratedButtons: [{        
 ``` 
  
 ### Video Menu Display 
 ```ts 
 let message = await prepareWAMessageMedia({ video: fs.readFileSync('./media/menu.mp4')}, { upload: conn.waUploadToServer }) 
      const template = generateWAMessageFromContent(m.chat, proto.Message.fromObject({ 
      templateMessage: { 
          hydratedTemplate: { 
            videoMessage: message.videoMessage, 
            hydratedContentText: text.trim(), 
            hydratedFooterText: wm, 
            hydratedButtons: [{                    
 ``` 
 ----            
  
  
 ## HOW TO CONNECT TO MONGODB WHEN RUN IN HEROKU 
  
 * Create account and database in mongodb atlas [`watch here`](https://youtu.be/rPqRyYJmx2g) 
 * when you already have a database, you just need to take mongourl 
 * Put mongourl in Procfile `web: node . --db 'mongourl'` 
 * Example `worker: node . --db 'mongodb+srv://Paquito1923:<password>@cluster0.wwdwr.mongodb.net/myFirstDatabase?retryWrites=true&w=majority'` 
  
  
 ## UNTUK PENGGUNA WINDOWS/VPS/RDP 
  
 * Unduh & Instal Git [`Klik Disini`](https://git-scm.com/downloads) 
 * Unduh & Instal NodeJS [`Klik Disini`](https://nodejs.org/en/download) 
 * Unduh & Instal FFmpeg [`Klik Disini`](https://ffmpeg.org/download.html) (**Jangan Lupa Tambahkan FFmpeg ke variabel lingkungan PATH**) 
 * Unduh & Instal ImageMagick [`Klik Disini`](https://imagemagick.org/script/download.php) 
  
 ```bash 
 git clone https://github.com/FahriAdison/Marin-MD 
 cd Marin-MD 
 npm install 
 npm update 
 npm index 
 ``` 
  
 --------- 
  
 ## UNTUK PENGGUNA TERMUX 
 ```bash 
  
 CARI SESSION DULU PAKAI SC BOT MD YANG LAIN🙏 
 pkg update && pkg upgrade 
 pkg install git 
 pkg install nodejs 
 pkg install ffmpeg 
 pkg install imagemagick 
 pkg install yarn 
 git clone https://github.com/FahriAdison/Marin-MD 
 cd Marin-MD 
 yarn 
 mc 
 ganti session 
 node . 
 ``` 
 Download Modules 
 [Here](https://drive.google.com/file/d/1Rr4xDLfA1OBpJ86PCrUFlNTuJX3KSCHN/view?usp=sharing) 
  
 ## UNTUK PENGGUNA HEROKU 
  
 ### Instal Buildpack 
 * heroku/nodejs 
 * https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest.git 
 * https://github.com/DuckyTeam/heroku-buildpack-imagemagick.git* 
  
 ## Installing the FFmpeg for Windows 
 * Unduh salah satu versi FFmpeg yang tersedia dengan mengklik [di sini](https://www.gyan.dev/ffmpeg/builds/). 
 * Extract file ke `C:\` path. 
 * Ganti nama folder yang telah di-extract menjadi `ffmpeg`. 
 * Run Command Prompt as Administrator. 
 * Jalankan perintah berikut:: 
 ```cmd 
 > setx /m PATH "C:\ffmpeg\bin;%PATH%" 
 ``` 
 Jika berhasil, akan memberikanmu pesan seperti: `SUCCESS: specified value was saved`. 
 * Sekarang setelah Anda menginstal FFmpeg, verifikasi bahwa itu berhasil dengan menjalankan perintah ini untuk melihat versi: 
 ```cmd 
 > ffmpeg -version 
 ``` 
  
 # Thanks to 
  [![Nurutomo](https://github.com/Nurutomo.png?size=150)](https://github.com/Nurutomo) | [![Ariffb](https://github.com/ariffb25.png?size=250)](https://github.com/ariffb25) | [![F](https://github.com/Alfarqun.png?size=80)](https://github.com/Alfarqun) 
 ----|----|---- 
 [Nurutomo](https://github.com/Nurutomo) | [Ariffb](https://github.com/ariffb25) | [F](https://github.com/Alfarqun) 
  Author | suhu | suhu
