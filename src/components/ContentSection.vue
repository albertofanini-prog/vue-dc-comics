<template>
    <div class="content_section">
        <h4> Content goes here --></h4>
    </div>
</template>

<script>
export default {
    name: 'ContentSection',
    contents:[
        {
            text:'<!-- Content goes here -->',
        }
    ]
}
</script>

<style lang="scss" scoped>
    .content_section{
        background-color: black;
        width: 100%;
        height: 100px;
        display: flex;
        align-items: center;
        justify-content: flex-start;
        h4{
            color: white;
            align-self: left;
            text-align: left;
        }
    }
</style>