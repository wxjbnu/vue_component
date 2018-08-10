<script>
export default {
  name: "{{componentNamePascal}}", // vue component name
  data() {
    return {
    }
  }
}
</script>

<template>
	<div class="{{componentName}}">
	</div>
</template>

<style scoped>
p{
	margin: 0;
}
.{{componentName}} {
	display: block;
	width: 400px;
	margin: 25px auto;
	border: 1px solid #ccc;
	background: #eaeaea;
	text-align: center;
	padding: 25px;
}
</style>