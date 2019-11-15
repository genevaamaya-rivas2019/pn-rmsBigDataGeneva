<template>
  <v-app id="inspire">
    <center>
      <v-content>
        <v-container class="fill-height" fluid>
          <v-row align="center" justify="center">
            <v-col cols="12" sm="8" md="4">
              <v-card class="elevation-12">
                <v-card-text>New Requests</v-card-text>
              </v-card>
            </v-col>
          </v-row>
          <v-row align="center" justify="center">
            <v-col cols="12" sm="8" md="4">
              <v-card class="elevation-12">
                <v-card-text>Approved</v-card-text>
              </v-card>
            </v-col>
          </v-row>
          <v-row align="center" justify="center">
            <v-col cols="12" sm="8" md="4">
              <v-card class="elevation-12">
                <v-card-text>Rejected</v-card-text>
              </v-card>
            </v-col>
          </v-row>
          <v-row align="center" justify="center">
            <v-col cols="12" sm="8" md="4">
              <v-card class="elevation-12">
                <v-card-text>Pending</v-card-text>
              </v-card>
            </v-col>
          </v-row>
        </v-container>
      </v-content>
    </center>
  </v-app>
</template>

<script>
export default {
  data: () => ({})
};
</script>
