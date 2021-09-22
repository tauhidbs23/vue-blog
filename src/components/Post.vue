<template>
  <div class="container">
    <div class="header">
      <div class="title">All Post</div>
      <div class="creat-post">
        <button>CREATE POST</button>
      </div>
    </div>
    <div class="content">
      <table>
        <thead class="mt-3 post-create">
          <th>Title</th>
          <th>Action</th>
        </thead>
        <tbody>
          <tr>
            <td>intro to css</td>
            <td>
              <i class="v-icon notranslate mdi mdi-launch theme--light"></i>
              <i class="v-icon mdi mdi-pencil theme--light"></i>
              <i class="v-icon mdi mdi-delete theme--light"></i>
            </td>
          </tr>
          <tr>
            <td>intro to css</td>
            <td>
              <i class="v-icon notranslate mdi mdi-launch theme--light"></i>
              <i class="v-icon mdi mdi-pencil theme--light"></i>
              <i class="v-icon mdi mdi-delete theme--light"></i>
            </td>
          </tr>
          <tr>
            <td>intro to css</td>
            <td>
              <i class="v-icon notranslate mdi mdi-launch theme--light"></i>
              <i class="v-icon mdi mdi-pencil theme--light"></i>
              <i class="v-icon mdi mdi-delete theme--light"></i>
            </td>
          </tr>
          <tr>
            <td>intro to css</td>
            <td>
              <i class="v-icon notranslate mdi mdi-launch theme--light"></i>
              <i class="v-icon mdi mdi-pencil theme--light"></i>
              <i class="v-icon mdi mdi-delete theme--light"></i>
            </td>
          </tr>
        </tbody>
      </table>
    </div>
  </div>
</template>

<script>
export default {
  name: "Post",
  data() {
    return {
      modalShow: false,
    };
  },
};
</script>

<style>
</style>