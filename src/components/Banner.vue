<template>
    <section id="bannerType" class="banner__wrap" :class="element">
        <h2 class="blind">{{ title }}</h2>
        <div class="banner__inner">
            <h3 class="title">유튜버 웹보이</h3>
            <p class="desc">
                더 다양한 강의는 유튜브를 통해 제공하고 있습니다.
                <a href="/" title="유튜브 페이지 이동">youtube.com/c/Webstoryboy</a>
            </p>
            <span class="small">배너 유형01</span>
        </div>
    </section>
</template>

<script>
export default {
    props: {
        element: String,
        title: String
    }
}
</script>