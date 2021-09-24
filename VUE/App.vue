<!--1. template : 화면에 표시할 요소를 정의-->
<template>
    <div id="#app">
        {{message}}
    </div>
</template>

<!--2. script : 뷰컴포넌트 내용정의-->
<script>
import Login from './login.vue'

export default ({
    data() {
        return {
            message:'intro to vue with vue2'
        }
    }
})
</script>

<!--3. style : 템플릿에 적용할 css 스타일 정의 -->
<style>
    div{
        font-size: 20px;
    }
</style>
