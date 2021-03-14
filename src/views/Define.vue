<template>
  <div class="define">
    <AddPlayers />
    <SetAvailability />
    <GoBtn />
  </div>
</template>

<script>
// @ is an alias to /src
import AddPlayers from '@/components/AddPlayers.vue'
import SetAvailability from '@/components/SetAvailability.vue'
import GoBtn from '@/components/GoBtn.vue'

export default {
  name: 'Define',
  components: {
    AddPlayers,
    SetAvailability,
    GoBtn,
  }
}
</script>
