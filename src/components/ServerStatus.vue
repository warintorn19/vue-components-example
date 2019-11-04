<template>
<div>
   <p>sss: {{status}}</p>
   <hr>
   <button @click="changeStatus">Click</button>
</div>
</template>

<script>

export default {
    data:function(){
        return{
            status: 'OKOKOK'
        }
    },
    methods:{
        changeStatus: function(){
            this.status = 'Normal';
        }
    }
}
</script>