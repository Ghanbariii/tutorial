<template>
    <div>
        <Header />
        <nuxt />
    </div>
</template>


<script>
import Header from '~/components/Header'
 export default {
    components :{
            Header
        },
 }
</script>
<style>
    
    html{
        font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
        font-size: 16px;
        word-spacing: 1px;
        -ms-text-size-adjust: 100%;
        -webkit-text-size-adjust: 100%;
        -moz-osx-font-smoothing: grayscale;
        -webkit-font-smoothing: antialiased;
        box-sizing: border-box;
    }
    *,*:before , *:after
    {
        box-sizing: border-box;
        margin: 0;
    }
    .button--green {
        display: inline-block;
        border-radius: 4px;
        border: 1px solid #3b8070;
        text-decoration: none;
        padding: 10px 30px;
    }
    .button--green:hover {
            color: #fff;
            background-color: #3b8070;
    }
    .button--gray {
        display: inline-block;
        border-radius: 4px;
        border: 1px solid #35495e;
        color: #35495e;
        text-decoration: none;
        padding: 10px 30px;
    }
    .button--gray:hover {
            color: #fff;
            background-color: #35495e;
    }
</style>