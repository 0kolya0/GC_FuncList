<div class="container first active">
    <div class="firsthalf">
        <nav style="display:flex">
            <div style="flex-grow:0.8"><i class="fa-solid fa-code"> </i>Taiga</div>
            <div> About</div>
            <div> Skills</div>
            <div> Projects</div>
            <div> Contacts</div>

        </nav>
        <img src="https://www.maavan.com/images/banner%20image.svg" style="float:right; width:300px;height:300px">

        <div class="depth"><span>Portfolio</span><br>

            <h1>Taiga</h1>

            <div class="info"></div>

        </div>
    </div>
    <svg id="wave" style="transform:rotate(0deg); transition: 0.3s" version="1.1" viewBox="0 0 1440 490"
         xmlns="http://www.w3.org/2000/svg">
        <defs>
            <linearGradient id="sw-gradient-0" x1="0" x2="0" y1="1" y2="0">
                <stop offset="0%" stop-color="rgba(42, 52, 67, 1)"></stop>
                <stop offset="100%" stop-color="rgba(42, 52, 67, 1)"></stop>
            </linearGradient>
        </defs>
        <path d="M0,196L48,179.7C96,163,192,131,288,106.2C384,82,480,65,576,114.3C672,163,768,278,864,310.3C960,343,1056,294,1152,261.3C1248,229,1344,212,1440,245C1536,278,1632,359,1728,383.8C1824,408,1920,376,2016,302.2C2112,229,2208,114,2304,130.7C2400,147,2496,294,2592,294C2688,294,2784,147,2880,114.3C2976,82,3072,163,3168,163.3C3264,163,3360,82,3456,49C3552,16,3648,33,3744,40.8C3840,49,3936,49,4032,106.2C4128,163,4224,278,4320,277.7C4416,278,4512,163,4608,138.8C4704,114,4800,180,4896,179.7C4992,180,5088,114,5184,130.7C5280,147,5376,245,5472,236.8C5568,229,5664,114,5760,114.3C5856,114,5952,229,6048,269.5C6144,310,6240,278,6336,228.7C6432,180,6528,114,6624,130.7C6720,147,6816,245,6864,294L6912,343L6912,490L6864,490C6816,490,6720,490,6624,490C6528,490,6432,490,6336,490C6240,490,6144,490,6048,490C5952,490,5856,490,5760,490C5664,490,5568,490,5472,490C5376,490,5280,490,5184,490C5088,490,4992,490,4896,490C4800,490,4704,490,4608,490C4512,490,4416,490,4320,490C4224,490,4128,490,4032,490C3936,490,3840,490,3744,490C3648,490,3552,490,3456,490C3360,490,3264,490,3168,490C3072,490,2976,490,2880,490C2784,490,2688,490,2592,490C2496,490,2400,490,2304,490C2208,490,2112,490,2016,490C1920,490,1824,490,1728,490C1632,490,1536,490,1440,490C1344,490,1248,490,1152,490C1056,490,960,490,864,490C768,490,672,490,576,490C480,490,384,490,288,490C192,490,96,490,48,490L0,490Z"
              fill="url(#sw-gradient-0)"
              style="transform:translate(0, 0px); opacity:1"></path>
    </svg>
    <div class="secondhalf" style="display:flex">
        <section class="profile" style="width:40%;font-family: 'Alata', sans-serif;color:#e5e5e5 ;    margin-top:100px;
">
            <img src="https://cdn.discordapp.com/avatars/696988079352709140/336dbfbc940738c007eb4e291b9319ea.webp?size=1024">
            Taiga
            <nav class="contactsBar" style="display:flex">
                <div><a href="https://github.com/Taiga74164"><i class="fa-brands fa-github"></i> </a></div>
                <div><a href="https://discord.com/users/696988079352709140"><i class="fa-brands fa-discord"></i></a></div>
<!--                <div><a href="https://twitter.com/Taiga74164"><i class="fa-brands fa-twitter"></i></a></div>-->
<!--                <div><a href="https://ko-fi.com/taiga74164"><i class="fa-solid fa-mug-hot"></i></a></div>-->
                <!--<div><a href="mailto:"><i class="fa-regular fa-envelope"></i></a></div>-->
            </nav>
        </section>
        <section class="about" style="width: 55%">
            <h2><i class="fa-regular fa-circle-dot"></i> About me</h2>
            I'm a hobbyist who likes to learn about software development and reverse engineering.
        </section>

    </div>
</div>

<style>
    .container{
        position: absolute;
        height : auto;
        box-shadow:0 12px 10px 10px #242a2f;
        width: 45%;
        border-radius : 8px;
        border-bottom: 0;
        left:10%;
        top:10%;
        background: rgb(32,40,51);
        background: linear-gradient(180deg, rgba(32,40,51,1) 2%, rgba(69,89,119,1) 50%,#2a3443 89%);

    }
    .active{
        z-index: 10;
    }
    .firsthalf{
        margin: 50px 0 0 50px;
        color:white;
        font-family: 'Alata', sans-serif;
    }
    nav div:not(:first-child){
        color:#8e96a1;
        margin-right: 20px;
    }
    nav{
        margin-bottom:30px
    }
    .depth{
        font-family: 'Kanit', sans-serif;
        margin-top: 100px;
        font-weight: normal;

    }
    .depth span {
        color: rgba(217, 60, 87, 0.86)
    }
    .depth h1{
        margin:0;
        font-weight: lighter;
    }
    .depth .info{
        font-weight: normal;

    }
    i{
        color: #d93c57
    }
    .secondhalf{
        width:100%;
        position: relative;
        top:25%;
        height:50%;
        background: #2a3443;
        border:0
    }
    svg{ position:relative;

        width:100.1%;
    }
    .first section{

        display:flex;
        flex-direction: column;
        justify-items: center;
        align-items: center;
    }

    .profile img {
        width:100px;
        height:100px;
        border-radius: 999px;
        border:5px solid #2a3443;
        outline: 2px solid #d93c57;
        margin-bottom:20px;
        margin-top: 30px
    }
    .contactsBar div{
        font-size:30px;
        margin: 10px 20px 20px 20px
    }
    .about{
        font-family: 'Alata', sans-serif;
        color:#e5e5e5;

    }
    h2{
        position: relative;
        left:0%;
        margin-bottom:50px;
    }
    .about{
        margin-top: 30px;
        word-break: break-word
    }
</style>

<script>
    window.onload = function ()
    {
        const name = document.getElementsByClassName("info")[0]
        const text = "Advanced Game Development Student"
        const keywords = ["Advanced Game Development Student"].map(e=>  [text.search(e),text.search(e)+e.length])
        let delay = 0
        for (let i=0;i<text.length;i++) {
            setTimeout(()=>{
                if(keywords.find(e=>e[0]==i||e[1]>i && e[0]<i)) return name.innerHTML += `<span>${text[i]}</span>`
                name.innerHTML += text[i]
            },delay+=50)
        }
    }
</script>