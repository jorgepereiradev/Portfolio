<template>
  <div class="skills">
    <h2>Habilidades</h2>
    <ul class="skills-list">
      <li>JavaScript</li>
      <li>TypeScript</li>
      <li>Vue.js</li>
      <li>React</li>
      <li>Node.js</li>
      <li>Python</li>
    </ul>
  </div>
</template>

<style scoped>
.skills {
  background: #2c2c2c;
  border-radius: 10px;
  padding: 20px;
  margin: 20px;
}

.skills h2 {
  font-size: 24px;
  margin-bottom: 20px;
}

.skills-list {
  list-style: none;
  padding: 0;
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
  gap: 15px;
}

.skills-list li {
  background: #18191c;
  padding: 10px;
  border-radius: 5px;
  text-align: center;
}
</style>
