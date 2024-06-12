<template>
    <v-row>
      <v-col md="12">
        <h3 class="pt-10 pl-10" style="color:blue;text-align: center;">Para onde estão indo os recursos arrecadados? </h3>
      </v-col>
    </v-row>
    <v-row class="d-flex justify-center">
      <v-col md="6">
        <GraphicWhereDonation class="pa-10" />
      </v-col>

      <v-col class="pt-10" md="12" style="text-align:center;">
        <span>
          A Fundação Mãos Unidas possui 5 pontos estratégicos adotados como centros para distribuição das doações.
          <br>Você pode fazer a sua doação através de nossa plataforma online, ou também em nossas unidades físicas!

        </span>
      </v-col>
    </v-row>

    <v-row class="d-flex justify-center">
      <v-col md="12">
        <h3 class="pt-10 pl-10" style="color:blue;text-align: center;">Valores totais repassados até o momento (mil) </h3>
      </v-col>

      <v-col md="6">
        <CircleTotalDonation class="pa-10" />
      </v-col>
    </v-row>

    <v-row class="d-flex justify-center">
      <v-col md="12">
        <h3 class="pt-10 pl-10" style="color:blue;text-align: center;">Balança de Arrecadações ao longo dos meses (mil) </h3>
      </v-col>

      <v-col md="6">
        <LineFutureDonation class="pa-10" />
      </v-col>
    </v-row>
</template>

<script setup>
import GraphicWhereDonation from '../components/graphic-where-donation.vue'
import CircleTotalDonation from '../components/circle-total-donation.vue'
import LineFutureDonation from '../components/line-future-donation.vue'

</script>