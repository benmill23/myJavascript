<template>
  <div>
    ADMIN PAGE
    <button>
      <router-link to="/profile">view profile</router-link>
    </button>
  </div>
</template>

<script>
export default {
  name: "Admin",
  props: {
    msg: String
  }
};
</script>
