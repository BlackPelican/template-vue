<template>
  <div id="app">Hello</div>
</template>

<script>
export default {
  name: "App",
  components: {}
};
</script>

<style>
/*---Resets---*/
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

button,
input,
button:focus,
input:focus {
  outline: none;
  border: 1px solid black;
  font-size: 1rem;
}

ul {
  list-style: none;
}

li {
  text-decoration: none;
}

::selection {
  background: var(--secondary);
  color: var(--black);
}

html,
body {
  position: relative;
  width: 100%;
  min-height: 100%;
  font-family: "Open Sans";
}

/*---vars---*/
:root {
  --primary: #6200ee;
  --primary-variant: #3700b3;
  --secondary: #03dac6;
  --secondary-variant: #018786;
  --background: #eeeeee;
  --surface: #ffffff;
  --error: #b00020;
  --on-primary: #ffffff;
  --on-secondary: #222222ee;
}
</style>
