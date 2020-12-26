<template>
    <button class="g-button">
        <slot></slot>
    </button>
</template>

<script>
export default {
  name:'g-button'
}
</script>

<style lang="scss" scoped>
.g-button{
    font-size:14px;
    height:32px;
    padding: 0 1em;
    border-radius: 4px;
    border:1px solid ;
    background: white;
    &:hover{
        border-color: #999999;
    }
    &:active{
        background-color: transparent;
    }
    &:focus{
        outline: none;
    }
}
</style>