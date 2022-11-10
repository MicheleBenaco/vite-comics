<template>
   <header class="conteiner">
        <!-- logo img -->
        <img src="../assets/img/dc-logo.png" alt="" class="logo">

        <!-- nav con lista contatti -->
        <nav>
            <ul>
             <li v-for="(link,index) in links" :key="index">
             <a :href="link.url" :class="{'active':link.current}">{{link.text}}</a>
             </li>
            </ul>
        </nav>
    
   </header>
</template>

<script>
    export default {
        name:'HeaderComponent',
        data() {
            return {
                links: [
                {
                    text: "Characters",
                    url: "#",
                    current: false,
                },
                {
                    text: "Comics",
                    url: "#",
                    current: true,
                },
                {
                    text: "Movies",
                    url: "#",
                    current: false,
                },
                {
                    text: "TV",
                    url: "#",
                    current: false,
                },
                {
                    text: "Game",
                    url: "#",
                    current: false,
                },
                {
                    text: "Collectibles",
                    url: "#",
                    current: false,
                },
                {
                    text: "Videos",
                    url: "#",
                    current: false,
                },
                {
                    text: "Fans",
                    url: "#",
                    current: false,
                },
                {
                    text: "News",
                    url: "#",
                    current: false,
                },
                {
                    text: "Shop",
                    url: "#",
                    current: false,
                },
            ]

            }
        },
    }
</script>

<style lang="scss" scoped>
@use '../assets/styles/partials/-variables.scss' as*;
@use '../assets/styles/general.scss' as*;
header{
    display: flex;
    justify-content: space-between;
    max-width: 1200px;
    margin: 0 auto;
    align-items: center;
    
    .logo{
        width: 100px;
        height: 100px;
    }

    ul{
        display: flex;
        
        li{
            margin: 15px;
            list-style-type: none;
            
            a{
                text-decoration: none;
                text-transform: uppercase;
                color: $dark;
                font-weight: 600;  
            }
        }
        

    }

}
</style>