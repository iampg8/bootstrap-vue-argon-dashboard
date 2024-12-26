<template>
  <footer class="footer px-4">
    <b-row align-v="center" class="justify-content-lg-between">
      <b-col lg="6">
        <div class="copyright text-center text-lg-left text-muted">
          © {{year}} <a href="#" class="font-weight-bold ml-1">iampg</a>
        </div>
      </b-col>
      <b-col lg="6">
        <b-nav align="center" class="nav-footer justify-content-lg-end">
          <b-nav-item href="#"  target="_blank">
            Footer 1
          </b-nav-item>
          <b-nav-item href="#" target="_blank">
            Footer 2
          </b-nav-item>
          <b-nav-item href="#" target="_blank">
            Footer 3
          </b-nav-item>
          <b-nav-item href="#" target="_blank">
            Footer 4
          </b-nav-item>
        </b-nav>
      </b-col>
    </b-row>
  </footer>
</template>
<script>
export default {
  data() {
    return {
      year: new Date().getFullYear()
    };
  }
};
</script>
<style></style>
