<template>
  <div class="course">
<!--     <el-container>
      <el-header>
        <Header></Header>
      </el-header>
      <el-main>
        <CourseInfo></CourseInfo>
      </el-main>
    </el-container> -->
    
    <Header></Header>
    <CourseInfo></CourseInfo>
  </div>
</template>

<script>
  import Header from '../components/Head';
  import CourseInfo from '../components/CourseInfo';
  import Login from '../components/Login';

  export default {
    components: {
      Header, Login, CourseInfo,
    },
  };

</script>


<style>

</style>
