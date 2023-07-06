<template>
    <appHeader></appHeader>
    <KreyativHero></KreyativHero>
    <KreyativIntro></KreyativIntro>
    <KreyativAbout></KreyativAbout>
    <KreyativSponsorShip></KreyativSponsorShip>
    <KreyativBlog></KreyativBlog>
    <KreyativCta></KreyativCta>
    <appFooter></appFooter>
</template>

<script setup>
import appHeader from "@/components/appHeader.vue"
import appFooter from "./components/appFooter.vue"
import KreyativHero from "@/components/KreyativHero.vue"
import KreyativIntro from "./components/KreyativIntro.vue";
import KreyativAbout from "./components/KreyativAbout.vue";
import KreyativCta from "./components/KreyativCta.vue";
import KreyativBlog from "./components/KreyativBlog.vue";
import KreyativSponsorShip from "./components/KreyativSponsorShip.vue"
</script>