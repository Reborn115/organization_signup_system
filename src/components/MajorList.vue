<template>
  <div>
    <div id="majorandClass">
      <h3>专业与班级</h3>
      <form>
        <div class="block">
          <span class="demonstration"></span>
          <el-cascader
            v-model="majorandclassNum"
            :options="majorData"
            :props="{ expandTrigger: 'hover' }"
          ></el-cascader>
        </div>
      </form>
    </div>
  </div>
</template>

<script>
export default {
  name: "MajorList",
  data() {
    return {
      majorandclassNum: "",
      majorData: [
        {
          value: "计算机科学与技术",
          label: "计算机科学与技术",
          children: [
            {
              value: "一班",
              label: "一班",
            },
            {
              value: "二班",
              label: "二班",
            },
            {
              value: "三班",
              label: "三班",
            },
            {
              value: "四班",
              label: "四班",
            },
          ],
        },
        {
          value: "信息安全",
          label: "信息安全",
          children: [
            {
              value: "一班",
              label: "一班",
            },
            {
              value: "二班",
              label: "二班",
            },
            {
              value: "三班",
              label: "三班",
            },
            {
              value: "四班",
              label: "四班",
            },
          ],
        },
        {
          value: "物联网",
          label: "物联网",
          children: [
            {
              value: "一班",
              label: "一班",
            },
            {
              value: "二班",
              label: "二班",
            },
          ],
        },
        {
          value: "数据科学与大数据技术",
          label: "数据科学与大数据技术",
          children: [
            {
              value: "一班",
              label: "一班",
            },
            {
              value: "二班",
              label: "二班",
            },
          ],
        },
        {
          value: "计算机科学与技术(中外合作)",
          label: "计算机科学与技术(中外合作)",
          children: [
            {
              value: "一班",
              label: "一班",
            },
            {
              value: "二班",
              label: "二班",
            },
            {
              value: "三班",
              label: "三班",
            },
            {
              value: "四班",
              label: "四班",
            },
            {
              value: "五班",
              label: "五班",
            },
            {
              value: "六班",
              label: "六班",
            },
          ],
        },
      ],
    };
  },
};
</script>

<style></style>
