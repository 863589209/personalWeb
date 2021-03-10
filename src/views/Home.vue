<template>
  <el-container style="height:100%">
    <el-header>Header</el-header>
    <el-main>Main</el-main>
    <el-footer>
      <RecordInfo></RecordInfo>
    </el-footer>
  </el-container>
</template>

<script>
import RecordInfo from "@/components/public/RecordInfo.vue";

export default {
  name: "Home",
  components: {
    RecordInfo,
  },
};
</script>
