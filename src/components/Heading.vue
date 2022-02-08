<template>
    <div class="container-sm ">
        <div class="row">
            <div class="col-sm-2"></div>
            <div class="col-sm-8 heading-style">
                {{headingValue}}
            </div>
            <div class="col-sm-2"></div>
        </div>
        
    </div>
</template>
<script>
export default {
    name: "Heading",
    props: [
        'headingValue'
    ]
}
</script>
<style scoped>
.heading-style{
    font-size: 200%;
    background-color: rgb(83, 238, 252);
    padding: 2%;
    margin: 2%;
    border-style: double;
    border-color: white;
    font-weight: bold;
}
</style>