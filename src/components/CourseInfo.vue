<template>
  <div class="course-info">
    <img style="border: 1px solid #ddd" src='../assets/img/course1.jpeg' width="100%" height="100%">
    <img style="border: 1px solid #ddd" src='../assets/img/course2.jpeg' width="100%" height="100%">
    <div><img style="margin-top: 20px; margin-bottom: 30px" src=../assets/footer.png height="50%" width="50%"></div>
  </div>
</template>

<script>
  export default {
    name: 'Course',
  };

</script>



<style>
  .course-info{
    position: relative;
    margin-top: 120px;
    margin-left: 100px;
    margin-right: 100px;
    /*height: 100%;*/
    z-index: 1;
    /*border: 1px solid #ddd*/
  }


</style>
