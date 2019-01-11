<template>
  <div class="wrapper">
    <div class="search">
      <label>Search</label>
      <input name="search">
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
export default {
  name: 'search',
};
</script>
<style lang="scss" scoped>
  .wrapper {
    display: flex;
    flex-direction: column;
    align-items: center;
    margin: 0;
    padding: 30px;
    width: 100%;

    .search {
      width: 300px;
      display: flex;
      flex-direction: column;

      input {
        height: 50px;
        border: 0;
        border-bottom: 2px #000 solid;

        &:focus {
          outline: none;
        }
      }
    }
  }

</style>
