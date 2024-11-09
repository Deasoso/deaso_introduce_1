<template>
  <div>
    <footer class="footer">
      <div class="container">
        <!-- <div class="columns">
          <div class="column is-4">
            <div class="content">
              <router-link class="navbar-item"
                           :to="{ name: 'Home'}">
                Home
              </router-link>
              <div class="navbar-item">
                简体中文（中国）
              </div>
              <div class="navbar-item">
                English (United State)
              </div>
              <router-link class="navbar-item">
                FAQ
              </router-link>
            </div>
          </div>
          <div class="column is-4">
            <div class="content">
              <router-link class="navbar-item"
                          :to="{ name: 'Term'}">
                Terms of Service
              </router-link>
              <router-link class="navbar-item"
                          :to="{ name: 'Privacy'}">
                Privacy Policy
              </router-link>
            </div>
          </div>
          <div class="column is-4">
            <div class="content">
              <p><span> Contact Us</span></p>
              <p>Wechat Group: add wechat friend "guanchao71"</p>
            </div>
          </div>
        </div> -->
        <div class="content has-text-centered">
          <p>
            <small>
              All rights reserved. <br>
              &copy; Copyright 2024
              <strong>Deaso</strong>
            </small>
          </p>
        </div>
      </div>
    </footer>
  </div>
</template>
<script>
export default {
  name: 'Footer'
}
</script>
<style scoped>
.footer{
  background-color: #333333;
  color: #ffffff;
  padding: 3rem 1.5rem 3rem;
}
strong {
  color: #ffffff;
}
.navbar-item{
  color: #ffffff;
  cursor: pointer;
}
.navbar-item:hover{
  color: black;
  background: white;
}
</style>
