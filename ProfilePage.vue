<template>
  <div>
    this is the user profile page
    <pre>
        Welcome, {{ email }}
    </pre>
    <pre>
        phonenumber: {{ phone }}
    </pre>
    <pre>
        attributes: {{ attributes }}
    </pre>
  </div>
</template>

<script>
import AmplifyStore from "../store";
export default {
  name: "Profile",
  data() {
    return {
      email: this.$store.state.user.attributes.email,
      phone: this.$store.state.user.attributes.phone_number,
      attributes: this.$store.state.user.attributes
    };
  },
  props: {
    msg: String
  }
};
</script>
