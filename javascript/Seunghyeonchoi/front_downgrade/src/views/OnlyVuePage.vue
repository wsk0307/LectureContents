<template>
    <div id="board">
        <h2>Vue + Spring 게시판 구현</h2>
        밑변: <input type="number" v-model="width">
        높이: <input type="number" v-model="height"><br><br>
        결과: {{ results }}
    </div>
</template>

<script>

export default {
    name: 'OnlyVuePage',
    data () {
        return {
            width: 0,
            height: 0
        }
    },
    computed: {
        results () {
            return this.width * this.height / 2.0;
        }
    }
}

</script>