<template>
    <div>
        <nuxt :key="$route.fullPath" />
    </div>
</template>

<script>
export default {
    name: "Default"
}
</script>