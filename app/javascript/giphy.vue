<template>
    <center class="p-5 ">
        <div class="w-10/12">
            <div class="w-full mt-5 mb-5 text-left">
                <span class="mr-5 text-2xl font-bold mb-5 text-gray-600">Search GIF</span>
            </div>
            <SearchPage></SearchPage>
        </div>
    </center>
</template>

<script>

import SearchPage from './components/SearchPage.vue';
export default {
  components: {
    SearchPage
  }
}

</script>