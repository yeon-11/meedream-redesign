<template>
  <div>
    <FaceQuestion/>
    <FaceLiftingTabs/>
    <FaceLiftingChart/>
    <FacePrecautions/>
  </div>
</template>

<script setup>
// 컴포넌트 불러오기
import FaceQuestion from '@/components/FaceQuestion.vue'
import FaceLiftingTabs from '@/components/FaceLiftingTabs.vue'
import FaceLiftingChart from '@/components/FaceLiftingChart.vue'
import FacePrecautions from '@/components/FacePrecautions.vue'
</script>
