<template>
  <div class="hello">
    <nav class="navbar navbar-expand-sm bg-light">

      <!-- Links -->
      <ul class="nav justify-content-center">
        <li class="nav-item">
          <a class="nav-link" href="#">首页</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">目的地</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">旅游攻略</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">酒店</a>
        </li>
        <li class="nav-item li-login">
          <a class="nav-link" href="#">注册</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">登陆</a>
        </li>
      </ul>

    </nav>
  </div>
</template>

<script>
  export default {
    name: 'IndexNavbar',
    data () {
      return {
        msg: 'Welcome to Your Vue.js App'
      }
    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  ul{
    font-size: 1.5rem;
    margin-left: 15%;
  }
  a {
    color: #42b983;
  }
  .li-login{
    margin-left: 15rem;
  }

</style>
