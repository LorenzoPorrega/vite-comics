<script>
export default {

}
</script>

<template>
  <div class="container">
    <div class="row d-flex align-items-center">
      <nav class="navbar navbar-expand-lg p-0">
        <div class="container-fluid">
          <a class="navbar-brand" href="#">
            <img src="../assets/img/dc-logo.png" alt="">
          </a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse d-flex justify-content-end" id="navbarNav">
            <ul class="nav nav-underline d-flex align-items-end">
              <li class="nav-item"
              v-for="link in this.menuLinks">
                <a class="nav-link" href="#">{{link}}</a>
              </li>
            </ul>
          </div>
        </div>
      </nav>
    </div>
  </div>
</template>

<style lang="scss" scoped>
@use "../styles/partials/variables" as *;

.container{
  background-color: white;
  border: 1px solid black;
  
  .nav-underline{
    max-width: 70%;
    height: 113px;
  }
}
</style>
