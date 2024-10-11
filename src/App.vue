<template>
  <div class="bg-gray-100 text-white p-4 sm:p-6">
    <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
      <div class="grid grid-cols-1 gap-4">
        <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
          <ResilienceBox />
          <GrowthBox />
        </div>
        <VisioningBox />
      </div>
      <div class="grid grid-cols-1 gap-4">
        <EngagementBox />
        <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
          <GoalOrientationBox />
          <SelfBeliefBox />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import ResilienceBox from '/src/components/ResilienceBox.vue'
import GrowthBox from '/src/components/GrowthBox.vue'
import VisioningBox from '/src/components/VisioningBox.vue'
import EngagementBox from '/src/components/EngagementBox.vue'
import GoalOrientationBox from '/src/components/GoalOrientationBox.vue'
import SelfBeliefBox from '/src/components/SelfBeliefBox.vue'

export default {
  name: 'App',
  components: {
    ResilienceBox,
    GrowthBox,
    VisioningBox,
    EngagementBox,
    GoalOrientationBox,
    SelfBeliefBox
  }
}
</script>