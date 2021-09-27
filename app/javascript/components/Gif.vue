<template>
    <div class="justify-start w-3/12 p-3">
        <img :src="img" :title="title" :alt="title" class="rounded-lg"/>
        <p class="text-sm mt-2 mb-2">{{title}}</p>
    </div>
</template>

<script>
    export default {
        props: ['img','title']
    }
</script>