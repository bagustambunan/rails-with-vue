<template>
    <div class="justify-start w-3/12 p-3">
        <img src={{img}} title={{title}} class="rounded-lg" alt={{title}}/>
        <p class="text-sm mt-2 mb-2">{{title}}</p>
        Halo there
    </div>
</template>

<script>
    export default {
        props: ['img','title']
    }
</script>