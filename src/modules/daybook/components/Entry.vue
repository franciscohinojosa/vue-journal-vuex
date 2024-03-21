<!-- eslint-disable -->

<template>
    <div class="entry-container mb-3 pointer p-2"
    @click="$router.push({ name: 'entry', params: { id:10 } })">
        <!-- titulo -->
        <div class="entry-title d-flex">
            <span class="text-success fs-5 fw-bold">yeah</span>
            <span class="mx-1 fs-5">yeah2</span>
            <span class="mx-2 fw-light">yeah3</span>
        </div>
        
        <div class="entry-description">
            Dolore sint minim nisi id cillum non magna amet velit. Aliquip velit ex sit laborum culpa. Occaecat ipsum in aliquip occaecat quis dolore et proident pariatur excepteur in aliqua dolor reprehenderit. Mollit cillum exercitation irure id voluptate do officia velit adipisicing sunt proident reprehenderit. Consequat nostrud consequat Lorem ad elit nulla sint tempor ex fugiat reprehenderit quis. In mollit cillum dolor commodo eu aute. Veniam quis cillum aliquip commodo aliquip commodo sit aliqua dolore anim.
        </div>

    </div>
</template>

<script>
export default {

    
    
}
</script>

<style lang="scss" scoped>
.entry-container{
    border-bottom: 1px solid #2c3e50;
    transition: 0.2s all ease-in;

    &:hover{
        background-color: lighten($color: grey, $amount:45);
        transition: 0.2s all ease-in;
    }

    .entry-description{
        font-size: 12px;
    }   
}


</style>