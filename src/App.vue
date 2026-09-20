<template>
  <section>
    <header>
      <h1>My Friends</h1>
    </header>
    <ul>
      <FriendContact />
      <FriendContact />
    </ul>
  </section>
</template>

<script>
export default {
  data() {
    return {
      friends: [
        { 
          id: 'manuel', 
          name: 'Manuel Lorenz', 
          phone: '01234 5678 991', 
          email: 'manuel@localhost.com' 
        },
        { 
          id: 'julies', 
          name: 'Julie Jones', 
          phone: '09876 543 221', 
          email: 'julie@localhost.com' 
        }
      ]
    }
  }
}
</script>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Jost&display=swap');

  * {
    box-sizing: border-box;
  }

  html {
    font-family: 'Jost', sans-serif;
  }

  body {
    margin: 0;
  }

  header {
    box-shadow: 0 2px 8px rgba(0, 0, 0, 0.26);
    margin: 3rem auto;
    border-radius: 10px;
    padding: 1rem;
    background-color: #58004d;
    color: white;
    text-align: center;
    width: 90%;
    max-width: 40rem;
  }
</style>