<template>
    <div class="common_container">
        <common-header />
        <main><Nuxt /></main>
    </div>
</template>

<script>
import CommonHeaderVue from "~/components/header/CommonHeader.vue";
export default {
    name: "DefaultLayout",
    components: {
        "common-header": CommonHeaderVue,
    },
    data() {
        return {
            clipped: false,
            drawer: false,
            fixed: false,
            items: [
                {
                    icon: "mdi-apps",
                    title: "Welcome",
                    to: "/",
                },
                {
                    icon: "mdi-chart-bubble",
                    title: "Inspire",
                    to: "/inspire",
                },
            ],
            miniVariant: false,
            right: true,
            rightDrawer: false,
            title: "Vuetify.js",
        };
    },
};
</script>
