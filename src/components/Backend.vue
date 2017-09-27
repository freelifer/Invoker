<template>
	<div class="backend">
<md-toolbar>
    <h1 class="md-title">My Title</h1>
  </md-toolbar>
	</div>
</template>

<script>
export default {
  name: 'backend',
  data () {
    return {
      msg: 'backend'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.backend {
	display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    min-height: 100%;
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -ms-flex-direction: column;
    flex-direction: column;
}
h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
