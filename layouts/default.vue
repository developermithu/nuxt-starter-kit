<template>
    <div>
        <TheHeader/>

            <div class="container mx-auto px-16">
                <Nuxt/>
            </div>

        <TheFooter/>
    </div>
</template>

<script>
export default {

}
</script>

<style>
/* home route and active route will show in semi-bold as it matches / and /about */
/* a.nuxt-link-exact-active {
  font-weight: 600;
} */

/* exact link will show the primary color for only the exact matching link */
a.nuxt-link-exact-active {
  color: #00c58e;
}
</style>