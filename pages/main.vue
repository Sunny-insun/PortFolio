<template>
    <div>
        <div class="about_container">
            <p class="title">LOREM IPSUM</p>
            <p class="sub">AZIONE NELLO SPAZIO Nº1 (PILLOLE)</p>
        </div>
        <div class="skills_container"></div>
    </div>
</template>

<script>
export default {
    name: "IndexPage",
};
</script>
<style lang="scss" scoped>
.about_container {
    background-color: gray;
    height: 90vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}
.about_container .title {
    font-size: 80px;
    margin-bottom: 50px;
    color: white;
}
.about_container .sub {
    font-size: 20px;
    color: white;
}

.skills_container {
    background-color: pink;
    height: 90vh;
}
</style>
