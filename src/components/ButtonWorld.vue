<template>
<!-- <button>{{text}}</button>
<p>{{secondProps || "aayena"}}</p>
<p v-if="!secondProps">xainw Manish Mahesh props ma </p>
<p v-if="secondProps">xa Manish Mahesh props ma </p>
<p></p> -->
<!-- <p v-for="abc in arrayOfNumbers">{{abc}}</p> -->

<p>{{ text }}</p>

</template>

<!-- <script>
export default{
    props : {
        text : {
            type : String,
            default : "aayena"
        } ,
        secondProps : {
            // validator(value){
            //     console.log(value)
            //     return ["Manish","Mahesh"].includes(value)
            // }
        },
        arrayOfNumbers : String
    } ,
    setup(props){
        console.log(props)
        
    }
}
</script>  -->

<script setup>
const props = defineProps(['text','secondText'])
console.log(props)

</script>

