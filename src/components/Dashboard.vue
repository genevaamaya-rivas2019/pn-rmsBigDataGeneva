<template>
  <v-app id="inspire">
    <center>
      <v-content>
        <v-container class="fill-height" fluid>
          <v-card class="mx-auto elevation-12" max-width="344">
            <v-card-text>
              <div>Word of the Day</div>
              <p class="display-1 text--primary">NEW REQUEST</p>
              <p>adjective</p>
              <div class="text--primary">
                well meaning and kindly.
                <br>"a benevolent smile"
              </div>
            </v-card-text>
            <v-card-actions>
              <v-btn text color="rgb(255, 153, 0)">NEW REQUEST</v-btn>
            </v-card-actions>
          </v-card>
          <v-card class="mx-auto elevation-12" max-width="344">
            <v-card-text>
              <div>Word of the Day</div>
              <p class="display-1 text--primary">APPROVED</p>
              <p>adjective</p>
              <div class="text--primary">
                well meaning and kindly.
                <br>"a benevolent smile"
              </div>
            </v-card-text>
            <v-card-actions>
              <v-btn text color="rgb(255, 153, 0)">APPROVED</v-btn>
            </v-card-actions>
          </v-card>
          <v-card class="mx-auto elevation-12" max-width="344">
            <v-card-text>
              <div>Word of the Day</div>
              <p class="display-1 text--primary">REJECTED</p>
              <p>adjective</p>
              <div class="text--primary">
                well meaning and kindly.
                <br>"a benevolent smile"
              </div>
            </v-card-text>
            <v-card-actions>
              <v-btn text color="rgb(255, 153, 0)">REJECTED</v-btn>
            </v-card-actions>
          </v-card>
          <v-card class="mx-auto elevation-12" max-width="344">
            <v-card-text>
              <div>Word of the Day</div>
              <p class="display-1 text--primary">PENDING</p>
              <p>adjective</p>
              <div class="text--primary">
                well meaning and kindly.
                <br>"a benevolent smile"
              </div>
            </v-card-text>
            <v-card-actions>
              <v-btn text color="rgb(255, 153, 0)">PENDING</v-btn>
            </v-card-actions>
          </v-card>
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
