<script>
    let Title = "I-WINDOWS"

</script>

<body>
    <div>
        <h2 class="title">{Title}</h2>
    </div>
    
    <div class="Sign">
        <p class="SignHead"> Welcome Back </p>
        <p class=SubText> Enter your credentials to continue.</p>
    </div>  
</body>

<svelte:head>
    <style>
        html {
            max-width: 100%;
            min-height: 100%;
            background-color: #212429;
        }
    </style>
</svelte:head>

<style>
    .Sign {
        position: relative;
        display: block;
        justify-content: center;
        border-radius: 65px;
        width: 57%;
        height: 60vh;
        align-items: center;
        margin: auto;
        background: linear-gradient(white, white) padding-box, linear-gradient(90deg, #48d0b8, #9889f9) border-box;
        border: 6px solid transparent;
    }

    .SignHead {
        color: #1e1e1e;
        font-size: 60px;
        position: relative;
        text-align: center;
        text-shadow: 0px 3px 2.5px #333333;
        margin: 12px 0 0 2px;
         
        font-family: 'Poppins', monospace;
    }

    .SubText {
        font-family: 'Poppins';
        text-align: center;
        padding: 0 0 0 0;
        margin: -8px 0 0 0;
        font-size: 17px;
    }

</style>