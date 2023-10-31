<script setup>
import Header from "@/components/Header.vue"
import Footer from "@/components/Footer.vue"
import Slider from "@/components/Slider.vue"
import Image from "@/components/Image.vue"
import ImgText from "@/components/ImgText.vue"
import Card from "@/components/Card.vue"
import Banner from "@/components/Banner.vue"
import Text from "@/components/Text.vue"
</script>

<template>
  <Header element="nexon" />
  <main>
    <Slider element="nexon" />
    <Image element="section nexon" title="포트폴리오가 실력이다." />
    <ImgText element="section nexon gray" title="이미지 텍스트 유형" />
    <Card element="section nexon" title="웹스토리보이 강의" />
    <Banner element="nexon" title="배너 영역" />
    <Text element="section nexon" title="텍스트 유형01" />
  </main>
  <Footer element="nexon section gray" />
</template>