<template>
<h2>
    {{subtitle}}
</h2>
<div id=caracs>
    <span v-for="(key,value) in caracs" >
       {{key.getvalue()}} 
       <input type="text"  value="value"> 
    </span>
</div>
</template>
<script>
export default {
    data() {
        return {
            subtitle : 'Caractéristiques & Attributs',
            caracs:[
                {APP:2, Prestance:0},
                {CON:0, Endurance:0},
                {FOR:0, Agilité:0},
                {TAI:0, Puissance:0},
                {Édu:0, Corpulence:0},
                {INT:0, Intuition:0},
                {POU:0, Volonté:0},
                ],
                



        }
    },
}
</script>