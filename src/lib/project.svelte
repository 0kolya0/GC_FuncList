<style>
    @media only screen  and (min-width: 600px) {
        #project {
            font-family: 'Kanit', sans-serif;
            position: relative;
            width: 100%;
            height: 100%;
            background-color: #2a3443;
            border-radius: 5px;
            color: white;
            z-index: 10;
        }

        .coe {
            position: relative;
            left: 20%;
            width: 55%;
            height: 205px;
            border-radius: 5px;
            overflow: hidden;
            z-index: 9
        }

        img {
            object-fit: contain;
            width: 100%;
            border-radius: 10px;
            height: 100px;
            overflow: hidden;
        }

        .bookmark {
            position: absolute;
            width: 90%;
            height: 39px;
            background: #d93c57;
            border-radius: 50000px;
            z-index: 9;
            margin-left: 10px;
            overflow: visible
        }

        .languages {
            display: flex;
            flex-wrap: wrap;
            margin: 25px
        }

        .language {
            border: 2px solid #d93c57;
            color: #d93c57;
            width: auto;
            padding: 0 10px 0 10px;
            height: 18px;
            border-radius: 10px;
            text-align: center;
            font-size: 12px;
            margin: 10px 5px 0 0
        }

        .insides {
            text-align: left;
            margin: 10px;
            position: relative;
            padding-top: 10px;
            top: 0;
            transition: all 0.5s ease-in-out
        }

        .indepth {
            position: relative;
            transition: left 1s ease-in-out;
            left: 1px
        }

        .coe:hover .insides {
            top: -50%;
        }

        .coe:hover img {
            visibility: hidden;
        }

        .coe:hover .indepth {
            left: 15px;
        }

        .coe:hover .languages {
            margin: 10px
        }

        button {
            position: relative;
            width: 80%;
            height: 40px;
            padding: 20px;
            background: #202833;
            border: 0;
            border-radius: 4px;
            left: 33.33px;
            text-align: center;
            line-height: 0px;
            color: #d93c57;
            cursor: pointer;
        }
    }
</style>

<div class="coe">
    <div class="bookmark"></div>
    <div id="project">

        <div class="insides">
            <img src={image}>
            <div class="indepth">
                <span style="font-weight: normal;font-size:15px;left:5px;position:relative;">⦾ {name}</span><br>
                <span style="font-size:13px;font-family: 'Alata', sans-serif;">{description}</span><br>
            </div>
            <div class="languages">
                {#each languages as language}
                    <div class="language">{language}</div>
                {/each}
            </div>
            <button on:click={location.href= link}>Page</button>
        </div>

    </div>
</div>

<script>
    export let image;
    export let name;
    export let description;
    export let languages;
    export let link

</script>

<svelte:head>
    <link href="https://fonts.googleapis.com/css2?family=Alata&display=swap" rel="stylesheet">
</svelte:head>