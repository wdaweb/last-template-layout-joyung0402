<template>
  <div style="width: 100%; background-color: #fffeef; padding: 20px;">
    <v-row align="center" >
      <v-col cols="auto">
        <img src="../assets/logo01.png" alt="Logo" style="height: 50px;">
      </v-col>

      <v-spacer></v-spacer>

      <v-col cols="auto">
        <v-menu>
          <template v-slot:activator="{ props }">
            <v-btn v-bind="props" text>
              Activator slot
            </v-btn>
          </template>
        </v-menu>
      </v-col>

      <v-col cols="auto">
        <v-btn text>
          Parent activator

          <v-menu activator="parent">
          </v-menu>
        </v-btn>
      </v-col>

      <v-col cols="auto">
        <v-btn id="menu-activator" text>
          Sibling activator
        </v-btn>

      </v-col>
    </v-row>
  </div>
</template>

<script>
export default {
  data: () => ({
    items: [
      { title: 'Click Me' },
      { title: 'Click Me' },
      { title: 'Click Me' },
      { title: 'Click Me 2' },
    ],
  }),
}
</script>

<style>
.v-btn--variant-elevated, .v-btn--variant-flat {
  background: none!important;
    color: black!important;
    box-shadow: none!important;
}
</style>
