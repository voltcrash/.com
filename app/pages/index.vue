<template>
  <div class="container">
    <h1>Work in progress</h1>
    <h2>Visit my socials</h2>
    <div class="social-links">
      <a href="https://github.com/voltcrash" target="_blank">Github</a>
      <a href="https://twitter.com/lakshmitanmay" target="_blank">Twitter</a>
      <a href="https://linkedin.com/in/lakshmitanmay" target="_blank">Linkedin</a>
    </div>
  </div>
</template>

<style scoped>
.container {
  padding: 2rem;
  text-align: center;
}

h1 {
  font-size: 2.5rem;
  color: #333;
  margin-bottom: 1rem;
}

h2 {
  font-size: 1.5rem;
  color: #666;
  margin-bottom: 2rem;
}

.social-links {
  display: flex;
  gap: 1rem;
  justify-content: center;
  flex-wrap: wrap;
}

.social-links a {
  padding: 0.75rem 1.5rem;
  background-color: #f0f0f0;
  color: #333;
  text-decoration: none;
  border-radius: 6px;
  transition: background-color 0.3s ease;
}

.social-links a:hover {
  background-color: #e0e0e0;
}
</style>