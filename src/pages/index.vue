<template>
  <div>
    <v-row>
      <v-col cols="12" xs="12" sm="12" md="4" lg="4" xl="4" >
        <v-form></v-form>
      </v-col>
      <v-col cols="12" xs="12" sm="12" md="8" lg="8" xl="8" >
        <v-list>
          <v-list-item></v-list-item>
        </v-list>
      </v-col>
    </v-row>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "@vue/composition-api";

export default defineComponent({
  setup() {}
});
</script>