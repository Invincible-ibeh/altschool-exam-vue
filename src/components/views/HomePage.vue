<template>
  <main>
    <section>
      <h2>What is WebCounter?</h2>
      <p>
        WebCounter is a is a simple counter tool that allows you to count up or
        down from a starting number. A Counter App is a simple tool that allows
        you to count up or down from a starting number.
      </p>
    </section>
    <section>
      <h2>How does it work?</h2>
      <p>
        WebCounter lets you input a starting number and then provides buttons to
        increase or decrease that number. You can also reset the count back to
        the starting number (0).
      </p>
    </section>
    <section>
      <h2>Why use WebCounter?</h2>
      <p>
        WebCounter can be helpful in a variety of circumstances, including
        inventory management, game scoring, and countdown timers for significant
        occasions.
      </p>
    </section>
  </main>
  <footer>
    <p>&copy; 2023 Ibeh Miracle</p>
    <a target="_blank" href="https://github.com/Invincible-ibeh"
      >GitHub Profile</a
    >
  </footer>
</template>

<script>
export default {};
</script>
<style scoped>
main {
  margin: 40px auto;
  max-width: 800px;
  padding: 0 20px;
}

section {
  border: 1px solid #dfdee3;
  border-radius: 5px;
  margin-bottom: 20px;
  padding: 20px;
  box-shadow: 1px 1px 5px #dfdee3;
}

h2 {
  color: #ff0000;
  font-size: 24px;
  margin-bottom: 10px;
}

p {
  color: #666;
  font-size: 16px;
  line-height: 1.5;
}

footer {
  background-color: #000000;
  padding: 20px;
  display: flex;
  align-items: center;
  justify-content: center;
  column-gap: 5px;
}

footer p {
  font-size: 14px;
  color: #fff;
}
footer a {
  font-size: 14px;
  color: #f50505;
  transition: color 0.3s ease;
}
footer a:hover {
  color: #dfdee3;
}
</style>
