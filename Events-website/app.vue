

<template>
  <div class="back">
    <img src="~/assets/myimage.jpg" alt="" width="100%" />
  </div>
  <div class="form-container">
    <h2>Create an account</h2>
    <form action="">
      <div>
        <legend>Name</legend>
        <input type="text" required />
      </div>

      <div class="inputs">
        <legend>Email</legend>
        <input type="Email" required />
      </div>

      <div>
        <legend>Password</legend>
        <input type="text" required />
      </div>
    </form>

    <button class="btn-sign">Sign Up</button>

    <div class="signin">
      <p>Already have an account?</p>
      <a href="">Sign in</a>
    </div>
  </div>
</template>

<style scoped lang="scss" >
img {
  margin: 0;
}
.form-container {
  max-width: 28rem;
  background: rgba(255, 255, 255, 0.438);
  padding-top: 1rem;
  padding-bottom: 2rem;
  margin-inline: auto;
  position: relative;
  z-index: 2;
  border-radius: 1rem;
  overflow: hidden;
  margin-top: 8rem;
}
.signin {
  text-align: center;
  padding-top: 2rem;
}
form {
  width: 100%;
  padding: 2rem;
}
h2 {
  text-align: center;
  font-size: 2rem;
  color: #4b494a;
}
.btn-sign {
  max-width: 20rem;
  padding: 1rem 3rem;
  transform: translate(100%);
  border: none;
  border-radius: 0.5rem;
  color: white;
  font-family: "Oswald", sans-serif;
  font-size: 1rem;
  font-weight: 500;
  background-color: #c80962;
}

legend {
  margin-bottom: 1rem;
  font-size: 1.2rem;
}

input:focus {
  border-bottom: #c80962 solid 2px;
}

input {
  outline: none;
  border: none;
  background: none;
  border-bottom: 2px solid rgb(97, 97, 97);
  width: 70%;
  margin-bottom: 2rem;
}

.inputs {
  width: 100%;
}

.back {
  height: 100%;
  width: 100%;
  position: absolute;
  margin: 0 auto;
  padding: 0;
  overflow-y: hidden;
  background: url("~/assets/myimage.jpg");
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;

  width: 100%;

  font-family: "Oswald", sans-serif;
}

template::-webkit-scrollbar {
  display: hidden;
}
</style>



