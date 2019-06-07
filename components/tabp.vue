<template>
  <div class="pt-5 div-outline">
    <b-container>
      <b-tabs class="tab-font font-weight-bold ">
        <b-tab title="Comming Soon  /" active>
          <moviaktab></moviaktab>
        </b-tab>
        <b-tab title="Now Playing   /">
          <b-card-text>
            <moviaktab2></moviaktab2>
          </b-card-text>
        </b-tab>
        <b-tab title="Opening this week">
          <b-card-text>
            <moviaktab3></moviaktab3>
          </b-card-text>
        </b-tab>
      </b-tabs>
    </b-container>
  </div>
</template>
<script>
import moviaktab from '@/components/tab.vue'
import moviaktab2 from '@/components/tab2.vue'
import moviaktab3 from '@/components/tab3.vue'

export default {
  components: {
    moviaktab,
    moviaktab2,
    moviaktab3
  }
}
</script>
