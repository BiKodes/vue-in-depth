<template>

<BaseInput
  v-model="searchText"
  @keydown.enter="search"/>

<BaseButton @click="search">
  <BaseIcon name="search"/>
</BaseButton>

</template>

<script>

import BaseButton from './BaseButton.vue'
import BaseIcon from './BaseIcon.vue'
import BaseInput from './BaseInput.vue'

export default {
    components: {
        BaseButton,
        BaseIcon,
        BaseInput
    }

}
</script>

<style>

</style>