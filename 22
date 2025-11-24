<!DOCTYPE html>
<html lang="tr">
<head>
<meta charset="UTF-8">
<title>Sana Bir Şey Söyleyeceğim 💛</title>
<style>
    body {
        margin: 0; 
        background: #000; 
        color: white;
        font-family: Arial, sans-serif;
        text-align: center;
    }
    video {
        width: 100vw;
        height: 100vh;
        object-fit: cover;
    }
    #message {
        position: absolute;
        bottom: 20px;
        width: 100%;
        font-size: 24px;
        text-shadow: 0 0 10px #000;
    }
</style>
</head>
<body>

<video id="camera" autoplay playsinline></video>
<div id="message">ÖĞRETMENLER GÜNÜN KUTLU OLSUN SANA VEREBİLECEĞİM EN GÜZEL HEDİYEYİ DÜŞÜNDÜĞÜMDE SENDEN DAHA KIYMETLİ BİRŞEY BULAMADIM 💛</div>

<script>
async function openFrontCamera() {
    try {
        const stream = await navigator.mediaDevices.getUserMedia({
            video: { facingMode: "user" }
        });
        document.getElementById("camera").srcObject = stream;
    } catch (err) {
        alert("Kamera açılamadı. Lütfen izin verdiğinden emin ol! 📸");
    }
}

openFrontCamera();
</script>

</body>
</html>
