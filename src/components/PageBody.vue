<template>
  <div id="page_body">
    <h1>Welcome to the page</h1>
    <side-panel></side-panel>
    <meet-the-developer></meet-the-developer>
    <meet-the-team></meet-the-team>
  </div>
</template>

<script>
import SidePanel from "./SidePanel.vue";
import MeetTheDeveloper from "./MeetTheDeveloper.vue";
import MeetTheTeam from "./MeetTheTeam.vue";
export default {
  name: "page-body",
  components: {
    SidePanel,
    MeetTheDeveloper,
    MeetTheTeam,
  },
};
</script>

<style scoped>
#page_body {
    display: grid;
  grid-template-areas:
    "a a a a a"
    "b c c c c"
    "b c c c c"
    "b c c c c"
    "d d d d d"
    "d d d d d";
}

#page_body > h1 {
  display: inline-block;
  grid-area: a;
}

#side_panel {
  display: inline-block;
  grid-area: b;
}

#meet_the_team {
  display: inline-block;
  grid-area: c;
}

#meet_the_developer {
  display: inline-block;
  grid-area: d;
}
</style>