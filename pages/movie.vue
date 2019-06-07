<template>
  <div class="home">
    <moviak-heading />
    <moviak-mainnav />
    <moviak-section />
    <moviak-tab />
    <moviak-tabp />
    <moviak-footer />
  </div>
</template>

<script>
import moviakHeading from '@/components/Header.vue'
import moviakFooter from '@/components/footer.vue'
import moviakSection from '@/components/section.vue'
import moviakMainnav from '@/components/mainnav.vue'
import moviakTab from '@/components/tab.vue'
import moviakTabp from '@/components/tabp.vue'
export default {
  components: {
    moviakHeading,
    moviakFooter,
    moviakSection,
    moviakMainnav,
    moviakTab,
    moviakTabp
  }
}
</script>
