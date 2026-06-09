<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>kentn</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{
    font-family:-apple-system,BlinkMacSystemFont,sans-serif;
    background:#311e84;
    color:white;
    display:flex;
    justify-content:center;
}

.container{
    width:100%;
    max-width:650px;
    padding:24px 16px 60px;
}

.profile{
    text-align:center;
    margin-bottom:30px;
}

.profile img{
    width:100px;
    height:100px;
    border-radius:50%;
    object-fit:cover;
    margin-bottom:12px;
}

.profile h1{
    font-size:2rem;
    margin-bottom:8px;
}

.tagline{
    opacity:.9;
}

.socials{
    display:flex;
    flex-wrap:wrap;
    justify-content:center;
    gap:12px;
    margin-top:20px;
}

.socials a{
    color:white;
    text-decoration:none;
    opacity:.9;
}

.section{
    margin-top:30px;
}

.section h2{
    text-align:center;
    margin-bottom:12px;
    font-size:1rem;
}

.card{
    display:block;
    width:100%;
    background:white;
    color:#1c205d;
    text-decoration:none;
    padding:18px;
    border-radius:10px;
    margin-bottom:12px;
    text-align:center;
    font-weight:600;
    transition:.2s;
}

.card:hover{
    transform:translateY(-2px);
}

.album{
    background:white;
    border-radius:10px;
    padding:20px;
    text-align:center;
    color:#1c205d;
}

.album img{
    width:220px;
    max-width:100%;
    border-radius:8px;
    margin-bottom:15px;
}

.jesus{
    background:white;
    color:#1c205d;
    border-radius:10px;
    padding:20px;
    line-height:1.5;
}

.footer{
    text-align:center;
    margin-top:40px;
    opacity:.8;
}
</style>
</head>

<body>

<div class="container">

    <div class="profile">

        <!-- replace with your image -->
        <img src="profile.jpg" alt="kentn">

        <h1>kentn</h1>

        <div class="tagline">
            Developer | Producer | Naturalist | Disciple
        </div>

        <div class="socials">
            <a href="https://instagram.com/_.kentn">Instagram</a>
            <a href="https://www.facebook.com/profile.php?id=100088981002549&mibextid=LQQJ4d">Facebook</a>
            <a href="https://open.spotify.com/artist/1JrKfh7chXVWb6ENrWovs8">Spotify</a>
            <a href="https://music.apple.com/us/artist/kentn/1586849757">Apple Music</a>
            <a href="https://www.youtube.com/channel/UCg-kFksh1Jg_j4uB-7aR3FA">YouTube</a>
            <a href="https://soundcloud.com/user-710840874">SoundCloud</a>
            <a href="https://www.linkedin.com/in/kentonjbell/">LinkedIn</a>
        </div>

    </div>

    <div class="section">
        <h2>Producer</h2>

        <a class="card" href="#">
            Meadow Grass - Acoustic
        </a>

        <a class="card" href="#">
            Commodity or Commotion - EP
        </a>

        <a class="card"
           href="https://drive.google.com/drive/folders/1GW7J5TbBCrj2fU7mQHBcvsX56vAhbFmY">
            VIP Access
        </a>
    </div>

    <div class="section">
        <h2>Developer</h2>

        <a class="card" href="#">
            Apple Send Later for Android
        </a>

        <a class="card" href="#">
            Top 10 iOS Shortcuts
        </a>
    </div>

    <div class="section">
        <h2>Naturalist</h2>

        <div class="album">

            <!-- replace with album image -->
            <img src="breathe.jpg" alt="breathe">

            <h3>breathe</h3>
            <p>Album</p>

        </div>
    </div>

    <div class="section">
        <h2>Disciple</h2>

        <div class="jesus">
            <strong>Jesus Texts ©</strong><br><br>

            The Jesus Texts take you on a journey through
            the words of Jesus from the devotional
            perspective of Jesus speaking directly to you.
            <br><br>

            <a href="https://www.jesustexts.com">
                www.jesustexts.com
            </a>
        </div>
    </div>

    <div class="footer">
        kentn
    </div>

</div>

</body>
</html>
