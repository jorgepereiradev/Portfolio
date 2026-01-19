<template>
  <div class="projects">
    <h2>Projetos</h2>
    <div class="projects-grid">
      <div class="project-card">
        <h3>Projeto 1</h3>
        <p>Descrição breve do projeto 1.</p>
      </div>
      <div class="project-card">
        <h3>Projeto 2</h3>
        <p>Descrição breve do projeto 2.</p>
      </div>
      <div class="project-card">
        <h3>Projeto 3</h3>
        <p>Descrição breve do projeto 3.</p>
      </div>
    </div>
  </div>
</template>

<style scoped>
.projects {
  background: #2c2c2c;
  border-radius: 10px;
  padding: 20px;
  margin: 20px;
}

.projects h2 {
  font-size: 24px;
  margin-bottom: 20px;
}

.projects-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
}

.project-card {
  background: #18191c;
  padding: 20px;
  border-radius: 10px;
  transition: transform 0.3s;
}

.project-card:hover {
  transform: translateY(-5px);
}

.project-card h3 {
  margin-top: 0;
  color: #0277fdff;
}

.project-card p {
  margin-bottom: 0;
}
</style>
