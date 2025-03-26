<template>
<h1>Hello this is vue.js up  and runnin</h1>
<br>

  <span @mouseover="showAlert('hi')" class="p-4 rounded-lg text-center bg-blue-300 text-blue-900 text-3xl font-bold ">This is a nice looking text you know</span>

</template>

<script>
export default {
  methods: {
    showAlert(message) {
      alert(message);
    }
  }
}
</script>

