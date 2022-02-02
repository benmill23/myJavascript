<template>
  <div>
    CUSTOMER COMPONENT
    <router-link to="/profile">view profile</router-link>
  </div>
</template>

<script>
export default {
  name: "Customer",
  props: {
    msg: String
  }
};
</script>
