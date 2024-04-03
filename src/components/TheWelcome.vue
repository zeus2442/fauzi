<script setup>
import WelcomeItem from "./WelcomeItem.vue";
import DocumentationIcon from "./icons/IconDocumentation.vue";
import ToolingIcon from "./icons/IconTooling.vue";
import EcosystemIcon from "./icons/IconEcosystem.vue";
import CommunityIcon from "./icons/IconCommunity.vue";
import SupportIcon from "./icons/IconSupport.vue";
</script>

<template>
  <WelcomeItem>
    <template #icon> </template>
    <template #heading>BIODATA DIRI</template>

    Nama saya fauzi, umur 21 , saya berasal dari kabupaten indragiri hulu
    tepatnya di rengat, saya berkuliah di salah kampus di Riau tepatnya di
    Universitas Islam Riau, saya mengambil jurusan di teknik tepatnya teknik
    informatika.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon> </template>
    <template #heading>SKILL</template>

    saya memiliki skill dalam bidang olahraga, hampir semua olahraga pernah saya
    mainkan, tapi yang lebih fokus saya ke volly.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon> </template>
    <template #heading>KEMAMPUAN</template>

    kemampuan yang saya miliki saya tertarik di bidang data science
  </WelcomeItem>

  <WelcomeItem>
    <template #icon> </template>
    <template #heading>PENGALAMAN</template>

    pengalaman yang saya miliki saya pernah bikin web sederhana mengenai sistem
    belanja
  </WelcomeItem>
</template>
