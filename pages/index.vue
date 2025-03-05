<template>
  <div class="container">
    <div class="login-container">
      <div class="logo-container">
        <img src="/img/logo.png" alt="Logo" class="logo" />
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
</template>

<style scoped>
/* Pastikan tinggi halaman penuh dan menggunakan Flexbox */
.container {
  height: 98vh;
  display: flex;
  justify-content: center; /* Posisi horizontal tengah */
  align-items: center; /* Posisi vertikal tengah */
  background-color: #005696;
}

/* Styling login box */
.login-container {
  background-color: #fff;
  padding: 30px;
  border-radius: 8px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.5);
  height: 400px;
  width: 100%;
  max-width: 400px;
  text-align: center;
}

/* Styling logo */
.logo-container {
  margin-bottom: 5px;
}

.logo {
  width: 225px;
  height: auto;
}

/* Styling form */
h2 {
  margin-top: 5px;
  margin-bottom: 20px;
  color: #005696;
}

.input-group {
  margin-bottom: 15px;
  margin-right: 20px;
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

/* Styling tombol */
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
</style>
