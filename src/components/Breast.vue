<template>
  <div>
    <BreastQuestion/>
    <BreastDesign/>
    <BreastIncisionGuide/>
    <BreastMentorInfo/>
    <BreastMentotPoint/>
    <BreastSurgeryInfo/>
    <BreastAfterCare/>
    <BreastPrecautions/>
  </div>
</template>

<script setup>
// 컴포넌트 불러오기
import BreastQuestion from '@/components/BreastQuestion.vue'
import BreastDesign from '@/components/BreastDesign.vue'
import BreastIncisionGuide from '@/components/IncisionGuide.vue'
import BreastMentorInfo from '@/components/MentorInfo.vue'
import BreastMentotPoint from '@/components/MentotPoint.vue'
import BreastAfterCare from '@/components/BreastAfterCare.vue'
import BreastSurgeryInfo from '@/components/BreastSurgeryInfo.vue'
import BreastPrecautions from '@/components/BreastPrecautions.vue'
</script>