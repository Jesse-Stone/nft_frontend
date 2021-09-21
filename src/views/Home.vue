<template>
<div class="home">
  <v-content class="my-16 mx-16">
   <v-card
    :loading="loading"
    class="mx-auto my-12"
    max-width="600"
    max-height="800"
  >
  <v-card-title class= "justify-center">Insert cool logo here</v-card-title>
  <div class="text-center mx-auto my-12">
    <v-btn class="grey lighten-3 pink--text mx-3 justify-center">DXSTAKE</v-btn>
  <v-btn class="grey lighten-3 pink--text mx-3">METRICS</v-btn>
        </div>
  <div class="text-center mx-auto my-5">
    Wallet Balace = 420.69
        </div>
  
      <v-form v-model="valid">
      <v-container class ="justify-center">
        <v-row>
          <v-col
            
        
          >
          
            <v-text-field class="ml-5 justify-center"
              v-model="firstname"
              :rules="nameRules"
              label="0"
              required
            ></v-text-field>
          </v-col>
            <v-btn rounded class="teal white--text mx-9 my-9">STAKE</v-btn>
        </v-row>
        <v-row>

          <v-col>
            <v-text-field class="ml-5 justify-center"
              v-model="lastname"
              :rules="nameRules"
              label="0"
              required
            ></v-text-field>
          </v-col>
   <v-btn rounded class="teal white--text mx-9 my-9">UNSTAKE</v-btn>
        </v-row>
      </v-container>
    </v-form>
    <div class="text-center mx-auto my-5">
    Staking Rewards: 0
    </div>
        <div class="text-center mx-auto my-5">
     <v-btn class="pink white--text mx-3 my-5 justify-center">REINVEST</v-btn>
  <v-btn class="teal white--text mx-3 my-5 justify-center">REINVEST</v-btn>
  <v-btn class="pink white--text mx-3 my-5 justify-center">REINVEST</v-btn>
    </div>
   </v-card>
  </v-content>
</div>
</template>

<script>


export default {

  }
</script>
