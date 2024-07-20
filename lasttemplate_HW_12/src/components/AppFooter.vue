<template>
    <v-footer id="footer">
      <v-container class="footer_container">
        <v-row>
          <v-col>
            <p>Sample text. Click to select the text box. Click again or double click to start editing the text.</p>
          </v-col>
        </v-row>
      </v-container>
    </v-footer>
</template>
<script>
export default {
  name: 'AppFooter'
}
</script>
<style scoped>
#footer{
  background-color: rgb(39, 44, 49);
  .footer_container {
    width: 40vw;
    height: 43vh;
  }
  p{
    text-align: center;
    text-decoration: none;
    font-size: 14px;
    color: rgb(255, 255, 255);
  }
}
</style>
