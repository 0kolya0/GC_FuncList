<script>
    import Project from "./project.svelte";

    const projects = [
        
    ]
</script>

<div class="container second" style="background: #202833">
    <div class="end"></div>
    <svg viewBox="0 0 1440 320" xmlns="http://www.w3.org/2000/svg">
        <path d="M0,64L48,74.7C96,85,192,107,288,106.7C384,107,480,85,576,85.3C672,85,768,107,864,138.7C960,171,1056,213,1152,224C1248,235,1344,213,1392,202.7L1440,192L1440,0L1392,0C1344,0,1248,0,1152,0C1056,0,960,0,864,0C768,0,672,0,576,0C480,0,384,0,288,0C192,0,96,0,48,0L0,0Z"
              fill="#455876"
              fill-opacity="1"></path>
    </svg>
    <div class="skillsAndStuff" style="display:flex;flex-direction:column;">
        <div style="text-align:center">

            <i class="fa-regular fa-square-check"></i> Skills
            <div class="skills">
                <div class="skill cpp"><img class="language" src="https://cdn.worldvectorlogo.com/logos/c.svg">
                    <div class="progress cpp"></div>
                </div>
                <div class="skill cs"><img class="language" src="https://cdn.worldvectorlogo.com/logos/c--4.svg">
                    <div class="progress cs"></div>
                </div>
                <div class="skill js"><img class="language" src="https://cdn.worldvectorlogo.com/logos/logo-javascript.svg">
                    <div class="progress js"></div>
                </div>
                <div class="skill python"><img class="language" src="https://cdn.worldvectorlogo.com/logos/python-5.svg">
                    <div class="progress python"></div>
                </div>
                <div class="skill lua"><img class="language" src="https://cdn.worldvectorlogo.com/logos/lua-5.svg">
                    <div class="progress lua"></div>
                </div>
            </div>
        </div>
        <div></div>
        <div></div>
    </div>
    <div style="text-align:center;">
        <h1><i class="fa-regular fa-square-check"></i> Projects </h1>
        <div class="projects" style="display:grid;padding-top:30px;grid-template-columns:50% 3fr;">
            {#each projects as project}
                <Project {...project}/>

            {/each}
        </div>

    </div>

</div>

<style>
    .second {
        position: absolute;
        box-shadow: 0 12px 10px 10px #242a2f;
        width: 45%;
        border-radius: 8px;
        border-bottom: 0;
        left: 50%;
        top: 0;
        height: 100%;
        transition: all 0.2s linear;
    }

    .skillsAndStuff {
        font-family: 'Alata', sans-serif;
        color: #e5e5e5;
        font-size: 25px;
        height: 30%
    }

    .skills {
        display: flex;
        margin: 40px 0 40px 0;
        width: 100%;
    }

    i {
        color: #d93c57
    }

    .cpp {
        display: flex;
        flex-direction: column
    }

    .progress {
        margin-top: 20px;
        width: 100px;
        height: 9px;
        border-radius: 2px
    }

    .progress.cpp {
        background: linear-gradient(to right, cornflowerblue 75%, #151b24 25%);
    }

    .progress.cs {
        background: linear-gradient(to right, #a179dc 50%, #151b24 50%);
    }

    .progress.js {
        background: linear-gradient(to right, yellow 20%, #151b24 20%);
    }

    .progress.python {
        background: linear-gradient(to right, #376f9e 20%, #151b24 20%);
    }

    .progress.lua {
        background: linear-gradient(to right, #0a0a97 20%, #151b24 20%);
    }

    .language {
        width: 70px;
        height: 70px
    }

    h1 {
        font-family: 'Alata', sans-serif;
        color: #e5e5e5;
        font-size: 25px;
        font-weight: normal;
    }

    .skill {
        justify-content: center;
        align-items: center;
        display: flex;
        flex-direction: column;
        width: 33.333%;
        height: 33.333%;
        margin-left: 10px;
    }

    #project img {
        width: 100%;
        border-radius: 10px;
        height: 110px;
    }

    .container:hover {
        height: 100vh;
        left: 25%;
        width: 55%;
        z-index: 30
    }

    .end {
        width: 100%;
        background-color: #1a212b;
        height: 80px;
        top: 90%;
        position: absolute;
        border-bottom: solid 2px #d93c57;
    }
</style>
