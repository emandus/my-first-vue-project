<template>
  <div><p>Hi there, this is a view</p></div>
  <MyComponent />
</template>

<script lang="ts">
import { defineComponent } from "vue";
import MyComponent from "@/components/MyComponent.vue";
export default defineComponent({
  name: "MyView",
  components: {
    MyComponent,
  },
});
</script>
