<script>
    import Card from "./UI/card.svelte";

    
</script>

<Card>
    <div class="uname">Username
        <input class="ubox" type="text">
    </div>
    
    <div class="pass">Password
        <input class="pbox" type="text">
    </div>

    <div class="sin"></div>

    <div class="sup"></div>

    <button class="signin">Sign In</button>
    <button class="signup">Sign Up</button>
</Card>

<style>
    .uname{
        color: white;
        position: relative;
        bottom: 95px;

    }
    
    .ubox{
        border-radius: 50px 50px 50px 50px;
        position: relative;
        top: 10px;
        right: 65px;
    }

    .pass{
        color: white;
        position: relative;
        bottom:50px;

    }
    
    .pbox{
        border-radius: 50px 50px 50px 50px;
        position: relative;
        top: 10px;
        right: 65px;
    }

    .signin{
        position: relative;
        top: 0px;
        width: 140px;
        right: 35px;
        border-radius: 50px 50px 50px 50px;

    }

    .signup{
        position: relative;
        top: 30px;
        width: 140px;
        right: 35px;
        border-radius: 50px 50px 50px 50px;

    }

</style>