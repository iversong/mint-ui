<template>
  <div class="page-spinner">
    <div class="page-title">Spinner</div>

    <mt-cell title="snake">
      <mt-spinner color="#ffc900" type="snake"></mt-spinner>
    </mt-cell>

    <mt-cell title="double-bounce">
      <mt-spinner color="#ffc900" type="double-bounce"></mt-spinner>
    </mt-cell>

    <mt-cell title="triple-bounce">
      <mt-spinner color="#ffc900" type="triple-bounce"></mt-spinner>
    </mt-cell>

    <mt-cell title="fading-circle">
      <mt-spinner color="#ffc900" type="fading-circle"></mt-spinner>
    </mt-cell>
  </div>
</template>

<script>
export default {
  name: 'page-spinner',

  data() {
    return {

    };
  }
};
</script>

<style lang="css">
  @component-namespace page {
    @component spinner {
      .mint-cell {
        min-height: 50px;
      }
    }
  }
</style>