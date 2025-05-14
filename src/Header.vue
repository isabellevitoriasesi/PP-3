
<script setup>

</script>

<template>
   <header>
    <div class="container-header">
      <div class="foto-perfil">
        <img src="/isa.jpg" alt="Foto de Isabelle Vitoria dos Santos" />
      </div>
      <div class="info-header">
        <h1>Isabelle Vitoria dos Santos</h1>
        <p>Estudante | Apaixonada por Desenvolvimento e Odontologia</p>
      </div>
    </div>
  </header>
  
</template>

<style scoped>
header {
  background-color: #3a4b5c; /* azul petróleo */
  color: #f9f9f9;
  padding: 40px 20px;
  border-radius: 8px;
}

.container-header {
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 20px;
  flex-wrap: wrap;
}

.foto-perfil img {
  width: 140px;
  height: 140px;
  object-fit: cover;
  border-radius: 50%;
  border: 4px solid #e6d6c3;
  box-shadow: 0 0 12px rgba(0, 0, 0, 0.15);
}

.info-header h1 {
  font-size: 2.5em;
  margin-bottom: 10px;
  color: #e6d6c3;
}

.info-header p {
  font-size: 1.1em;
  color: #dcdcdc;
}

</style>
