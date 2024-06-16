<script setup>
import WelcomeItem from './WelcomeItem.vue'
import Firebrand_icon from './icons/Firebrand_icon.vue'
import Druid_icon from './icons/Druid_icon.vue'
import Reaper_icon from './icons/Reaper_icon.vue'
import Renegade_icon from './icons/Renegade_icon.vue'
import Scourge_icon from './icons/Scourge_icon.vue'
import Scrapper_icon from './icons/Scrapper_icon.vue'
import Holosmith_icon from './icons/Vindicator_icon.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <Firebrand_icon />
    </template>
    <template #heading>FB burn</template>
    <a href="https://metabattle.com/wiki/Build:Firebrand_-_SA_Burn_(GvG)">build</a>
  </WelcomeItem>
  <WelcomeItem>
    <template #icon>
      <Druid_icon />
    </template>
    <template #heading>Druid Support</template>
    <a href="https://metabattle.com/wiki/Build:Druid_-_Support_Druid_(GvG)">build</a>
  </WelcomeItem>
  <WelcomeItem>
    <template #icon>
      <Reaper_icon />
    </template>
    <template #heading>Reaper Condi</template>
    <a href="https://metabattle.com/wiki/Build:Reaper_-_Cele_Shouts_(GvG)">build</a>
  </WelcomeItem>
  <WelcomeItem>
    <template #icon>
      <Renegade_icon />
    </template>
    <template #heading>Renegade Condi Alac</template>
    <a href="https://metabattle.com/wiki/Build:Renegade_-_Cele_Renegade_(GvG)">build</a>
  </WelcomeItem>
  <WelcomeItem>
    <template #icon>
      <Scourge_icon />
    </template>
    <template #heading>Scrouge Cele transfu</template>
    <a href="https://metabattle.com/wiki/Build:Scourge_-_Condition_Scourge">build</a>
  </WelcomeItem>
  <WelcomeItem>
    <template #icon>
      <Scrapper_icon />
    </template>
    <template #heading>Scrapper Supp</template>
    <a href="https://metabattle.com/wiki/Build:Scrapper_-_Med_Kit_Scrapper">build</a>
  </WelcomeItem>
  <WelcomeItem>
    <template #icon>
      <Holosmith_icon />
    </template>
    <template #heading>Holosmith DPS</template>
    <a href="https://metabattle.com/wiki/Build:Holosmith_-_DPS_Holo">build</a>
  </WelcomeItem>

</template>
