<script setup>

</script>

<template class="position-fixed">
    <div class="d-flex vh-100">
        <div class="bg-back2 p-4">
            <div class="d-flex">
                <input type="text" class="form-control rounded-end-0 border-0" placeholder="Search location...">
                <button type="button" class="btn btn-body-bg border-0 rounded-start-0 p-0 m-0"><i class="mdi mdi-magnify fs-5 px-1"></i></button>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
    input:focus{
        box-shadow:none;
    }
</style>