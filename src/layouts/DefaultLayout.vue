<template>
  <div class="flex h-full w-full">
    <Sidebar/>
    <div class="flex flex-col h-full w-full">
      <Navbar/>
      <slot/>
    </div>
  </div>
</template>

<script>
import Navbar from "@/components/Shared/Navbar.vue";
import Sidebar from "@/components/Shared/Sidebar.vue";

export default {
  name: "DefaultLayout",
  components: {Sidebar, Navbar},
  data: () => ({}),
  methods: {},
  watch: {},
  computed: {},
}
</script>

<style lang="scss" scoped>

</style>