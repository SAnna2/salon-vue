<template>
    <div class="btn-red">
        <button @click="add">Запись на услугу</button>
    </div>
</template>


<script>
export default{
    name:'v-btn',
    components: {
    },
    props: {},
    data(){
        return {
            title:'v-btn',
        }
    },
    computed: {},
    methods: {
        add() {
            
        }
    },
    watch: {}
}
</script>

<style scoped>
button {
    padding: 14px 40px;

    border-radius: 2px;
    border: 0;
    cursor: pointer;

    font-family: 'Raleway', sans-serif;
    font-size: 13px;
    color: #fff;
    font-weight: 600;
    text-transform: uppercase;
    text-decoration: none;
    text-align: center;

    transition: background .1s linear;
    background-color: #501b44;
}

</style>