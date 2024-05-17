<template>
  <div>
    <header>
      <input type="text" placeholder="Suche..." />
    </header>
  </div>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style scoped>
header {
  background-color: yellow;
  height: 120px;
  padding: 16px;
  display: flex;
  align-items: flex-end;
  border-bottom-left-radius: 8px;
  border-bottom-right-radius: 8px;
}
</style>
