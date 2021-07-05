<template>
    <div id="footer" class="footer">
<!--        <p v-text="$t('footer')">This is your footer</p>-->
        <br/>
        <br/>
        <p><strong> ©PaengE. All rights reserved. Powered by Jhipster.</strong></p>
        <br/>
        <br/>
        <p>
            <span v-text="$t('home.explore')">If you explore source code of this project, just visit my github page and find "Microservice-Book-XXX" repository!</span> <a href="https://github.com/PaengE" target="_blank" rel="noopener" v-text="$t('home.github')">GitHub</a>!
        </p>
    </div>
</template>

<script lang="ts" src="./jhi-footer.component.ts">
</script>

<style scoped>
    .footer {
        text-align: left;
    }
</style>
