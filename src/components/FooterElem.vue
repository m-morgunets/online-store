<template>
    <footer class="footer">
        <a href="https://t.me/m_morgunets" target="_blanc" class="author">2023 Morgunets</a>
    </footer>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({})
</script>

<style lang="scss" scoped>
.footer {
    height: 30vh;
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    background: rgb(0, 0, 0);

    .author {
        color: #011AFF;
        opacity: 0.7;
        text-shadow: -2px -2px 6px, 2px 2px 6px;
    }
}
</style>