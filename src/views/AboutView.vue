<template>
  <div class="about">
    <div class="langs">
    <h2>Languages:</h2>
    <ul>
      <li>Python</li>
      <li>Javascript</li>
      <li>Go</li>
    </ul>
  </div>
  </div>
</template>

<style>
ul {
  list-style: none;
}
li {
  text-decoration:dotted;
}
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
