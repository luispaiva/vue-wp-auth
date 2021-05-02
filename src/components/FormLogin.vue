<template>
    <div class="form-login">
        <h2>
            Log into your account
        </h2>
        <form action="">
            <div class="form-input">
                <input type="text" name="login" id="login" placeholder="Login">
                <input type="password" name="password" id="password" placeholder="Password">
            </div>
            <div class="form-checkbox">
                
                <label class="keep-me-logged">
                    <input type="checkbox" name="keep" id="keep">
                    Keep me logged in
                </label>
                <a href="#">Forgot Password</a>
                
            </div>
            <button class="btn-log-in">Log In</button>
        </form>
    </div>
</template>

<script>
export default {
    name: 'FormLogin'
}
</script>
