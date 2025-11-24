<input id="user"><br>
<input id="pass" type="password"><br>
<button onclick="login()">Login</button>
<p id="result"></p>

<script>
function login() {
    let user = document.getElementById("user").value;
    let pass = document.getElementById("pass").value;

    if (user === "admin" && pass === "1234") {
        document.getElementById("result").innerHTML = "Login Successful!";
    } else {
        document.getElementById("result").innerHTML = "Invalid Credentials.";
    }
}
</script>
