<style>
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap');

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{
    font-family:'Poppins',sans-serif;
    background:linear-gradient(135deg,#FFF7D6,#FFE8EF,#FFF3B0);
    overflow-x:hidden;
    position:relative;
    min-height:100vh;
}

/* Girassóis e Gérberas */
body::before{
    content:"🌻 🌼 🌻 🌼 🌻 🌼 🌻 🌼 🌻 🌼";
    position:fixed;
    inset:0;
    display:flex;
    flex-wrap:wrap;
    justify-content:space-evenly;
    align-content:space-evenly;
    font-size:90px;
    opacity:.08;
    z-index:-2;
    pointer-events:none;
}

/* Corações Flutuando */
.hearts{
    position:fixed;
    inset:0;
    overflow:hidden;
    pointer-events:none;
    z-index:-1;
}

.heart{
    position:absolute;
    bottom:-60px;
    font-size:30px;
    animation:float linear infinite;
    opacity:.8;
}

.heart:nth-child(1){left:5%;animation-duration:12s;}
.heart:nth-child(2){left:15%;animation-duration:15s;font-size:25px;}
.heart:nth-child(3){left:28%;animation-duration:18s;}
.heart:nth-child(4){left:40%;animation-duration:13s;font-size:35px;}
.heart:nth-child(5){left:52%;animation-duration:17s;}
.heart:nth-child(6){left:65%;animation-duration:14s;font-size:22px;}
.heart:nth-child(7){left:77%;animation-duration:19s;}
.heart:nth-child(8){left:90%;animation-duration:16s;font-size:28px;}

@keyframes float{
    0%{
        transform:translateY(0) scale(.7);
        opacity:0;
    }
    15%{
        opacity:1;
    }
    100%{
        transform:translateY(-120vh) rotate(360deg) scale(1.3);
        opacity:0;
    }
}

.card{
    width:90%;
    max-width:850px;
    margin:40px auto;
    background:rgba(255,255,255,.88);
    backdrop-filter:blur(12px);
    border-radius:25px;
    padding:35px;
    box-shadow:0 15px 35px rgba(0,0,0,.2);
    border:3px solid #FFD54F;
    animation:fade 1.5s ease;
}

@keyframes fade{
    from{
        opacity:0;
        transform:translateY(30px);
    }
    to{
        opacity:1;
        transform:translateY(0);
    }
}

h2{
    text-align:center;
    color:#E91E63;
    margin-bottom:20px;
}

p{
    color:#444;
}

iframe{
    margin-top:20px;
    border:none;
    border-radius:15px;
}
</style>

<div class="hearts">
    <div class="heart">❤️</div>
    <div class="heart">💛</div>
    <div class="heart">💕</div>
    <div class="heart">💖</div>
    <div class="heart">🤍</div>
    <div class="heart">❤️</div>
    <div class="heart">💛</div>
    <div class="heart">💕</div>
</div>

<div class="card">

<h2>💌 Una carta para ti</h2>

<p style="font-size:20px;line-height:1.8;">

Hola, mi amor. ❤️<br><br>

Conocerte ha sido la mejor cosa que me ha pasado en la vida. Nunca voy a olvidar la primera vez que te vi. En ese momento pensé para mí mismo:
<i>"Algún día quiero estar con ella."</i><br><br>

Con el tiempo, ese día llegó. Nos fuimos acercando poco a poco y, desde entonces, hemos estado juntos compartiendo momentos inolvidables.<br><br>

Hoy, en tu cumpleaños, quiero que sepas lo especial que eres para mí. Gracias por tu cariño, por tu compañía y por hacer mi vida mucho más feliz.<br><br>

Espero que este nuevo año de vida esté lleno de alegría, salud, sueños cumplidos y mucho amor.<br><br>

Siempre estaré a tu lado para apoyarte, cuidarte y seguir construyendo nuestra historia juntos.<br><br>

<b>Espero que te guste este pequeño detalle. Lo hice con todo mi cariño para ti. ❤️</b><br><br>

<b>👇 MIRA 👇</b>

</p>

<h2 style="margin-top:35px;">🎵 Nuestra Playlist</h2>

<iframe
style="border-radius:12px"
src="https://open.spotify.com/embed/playlist/2u7hAgL7NegOZq3F2k0Ehm?utm_source=generator"
width="100%"
height="352"
allowfullscreen
allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture"
loading="lazy">
</iframe>

</div>
