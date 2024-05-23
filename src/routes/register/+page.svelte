<script>
    let userName;
    let password;
    let email;

</script>


<div class="backdrop">
    <p class="register">Register Here</p>
    <p class="details">Enter your details to create an account!</p>
    <form>

        <label class="inp" for="userName">Username:</label>
        <input class="txt" type="text" id="userName" bind:value={userName}>
        <p></p>

        <label class="inp" for="password">Password:</label>
        <input class="txt" type="text" id="password" bind:value={password}>
        <p></p>

        <label class="inp" for="email">Email:</label>
        <input class="txt" type="text" id="email" bind:value={email}>

        <!-- <p class="inp">Username: <input class="txt" type="text" bind:value={userName}></p>
        <p class="inp">Password: <input class="txt" type="text" bind:value={password}></p>
        <p class="inp">Email: <input class="txt" type="text" bind:value={email}></p> -->

    </form>
    <button class="button">Create Account</button>
    <p class="return">Return to login page</p>
</div>


<svelte:head>
    <style>
        html {
            max-width: 100%;
            min-height: 100%;
            background: linear-gradient(to top right, #48D0B8, #9889F9);
        }
    </style>
</svelte:head>

<style> 

    /* .background{
        width: 110%;
        height: 110%;
        margin-left: -5%;
        margin-top: -5%;
        margin-bottom: 5%;
        padding-bottom: 100px;
        position: fixed;
       
        background: linear-gradient(to top right, #48D0B8, #9889F9);
    } */

    .backdrop{ 
        padding: 10px;
        max-width: 60%;
        margin-left: 20%;
        margin-right: 20%;
        margin-top: 7%;
        background: linear-gradient(white, white) padding-box,
              linear-gradient(to left,  #48D0B8,  #9889F9) border-box;
        border-radius: 55px;
        border: 6px solid transparent;
        box-shadow: 2px 2px 10px gray;
    }

    .register{
        color: black;
        font-size: 4.7em;
        text-align: center;
        word-wrap:break-word;
        margin-bottom: 0%;
        margin-top: 5%;
        text-shadow: 2px 2px 2px gray;
    }

    .details{
        color: black;
        text-align: center;
        word-wrap:break-word;
        font-size: 2.7em;
        margin-top: 0%;
        margin-bottom: 5%;
    }
    
    .inp{
        color: black;
        word-wrap:break-word;
        font-size: 2.9em;
       
        /* text-align: right;
        margin-left: -20%;
        margin-bottom: 2%;
        margin-top:0%; */
       
    }

    .txt{
        width: 50%;
        height: 40px;
        margin-left: 20px;
        word-wrap: break-word;
        border-radius: 6px;
        display: inline-block;
        border:2px solid #212429;
        border-color: gray;
    }


    .button{
        text-align: center;
        padding: 10px 24px;
        display: block;
        margin-top: 7%;
        margin-left: 30%;
        margin-right: 30%;
        border-radius: 18px;
        background-color: #0F4253;
        font-size: 3.0em;
        color: white;
    }

    .return{
        text-align: center;
        color: #0F4253;
        font-size: 2.5em;
        margin-top: 0%;
        margin-bottom: 5%;
    }

</style>