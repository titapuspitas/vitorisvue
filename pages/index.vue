<template>
  <div class="tinggi container-fluid">
    <div class="row justify-content-center">
      <div class="col-11 col-sm-8 col-md-6 col-lg-4">
        <div class="login-container">
          <div class="logo-container">
            <img src="~assets/img/logo.png" alt="Logo" class="logo" />
          </div>
          <h2>Login</h2>
          <form action="#" method="POST">
            <div class="input-group">
              <label for="username">Username:</label>
              <input type="text" id="username" name="username" required />
            </div>
            <div class="input-group">
              <label for="password">Password:</label>
              <input type="password" id="password" name="password" required />
            </div>
            <button type="submit">Login</button>
          </form>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.tinggi {
  height: 100vh;
  padding-block: 10vh;
  background-color: #005696;
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

/* Container for the login form */
.login-container {
  background-color: #fff;
  padding: 30px;
  border-radius: 8px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.5);
  width: 100%;
  max-width: 400px;
  text-align: center;
  margin-right: ;
}

/* Logo styling */
.logo-container {
  margin-bottom: 10px;
}

.logo {
  width: 225px; /* Sesuaikan ukuran logo */
  height: auto;
}

/* Title of the form */
h2 {
  margin-bottom: 20px;
  color: #005696;
}

/* Input field styles */
.input-group {
  margin-bottom: 15px;
  text-align: left;
}

label {
  display: block;
  font-weight: bold;
  margin-bottom: 5px;
}

input {
  width: 100%;
  padding: 10px;
  border: 1px solid #ddd;
  border-radius: 4px;
  font-size: 16px;
}

/* Button styling */
button {
  width: 100%;
  padding: 12px;
  background-color: #ffd700;
  color: black;
  border: none;
  border-radius: 6px;
  font-size: 16px;
  cursor: pointer;
  font-weight: bold;
}

button:hover {
  background-color: #ffc107;
}

/* Footer links styling */
.footer {
  text-align: center;
  margin-top: 15px;
}

.footer a {
  color: #ffd700;
  text-decoration: none;
}

.footer a:hover {
  text-decoration: underline;
}
</style>
