<template>
    <q-page class="container">
        <div class="container">
            <h2>Login</h2>
            <form>
                <div class="form-group">
                    <label for="username">Username</label>
                    <input type="text" name="username" id="username" placeholder="Enter your Username">
                </div>
                <div class="form-group">
                    <label for="username">Username</label>
                    <input type="text" name="password" id="password" placeholder="Enter your Password">
                </div>
                <div class="form-group">
                    <button type="submit">Login</button>
                </div>
                <div class="form-group message">
                    Don't have an account? <a href="#">Sign up</a>
                </div>
            </form>
        </div>
    </q-page>
</template>

<style>
body {
    font-family: Arial, sans-serif;
}

.container {
    max-width: 400px;
    margin: 0 auto;
    padding: 20px;
    background-color: #fff;
    border-radius: 5px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

h2 {
    text-align: center;
}

.form-group {
    margin-bottom: 20px;
}

.form-group label {
    display: block;
    font-weight: bold;
    margin-bottom: 5px;
}

.form-group input[type="text"],
.form-group input[type="password"] {
    width: 100%;
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 3px;
}

.form-group button {
    display: block;
    width: 100%;
    padding: 10px;
    background-color: #4caf50;
    border: none;
    color: #fff;
    font-size: 16px;
    font-weight: bold;
    border-radius: 3px;
    cursor: pointer;
}

.form-group button:hover {
    background-color: #45a049;
}

.form-group .message {
    margin-top: 10px;
    text-align: center;
    color: #888;
}
</style>
<script>
import { defineComponent } from 'vue'

export default defineComponent({
    name: 'FirstLink'

})
</script>