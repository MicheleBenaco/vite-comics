<template>
    <footer>
        <div class="container-footer">

            <div class="conteiner-lu">
                <ul>
                    <h3> DC comics</h3>
                    <li v-for="(link,index) in links1" :key="index">
                        <a :href="link.url" :class="{'active':link.current}">{{link.text}}</a>
                       
                    </li>
                        <ul class="cont-shop">
                            <h3>SHOP</h3>
                            <li> <a href="">Shop dc </a> </li>
                            <li> <a href=""> Shop dc Colletions </a> </li>
                        </ul>
                </ul>
                <ul>
                    <h3> DC </h3>
                    <li v-for="(link,index) in links1" :key="index">
                        <a :href="link.url" :class="{'active':link.current}">{{link.text}}</a>
                    </li>
                </ul>
                <ul>
                    <h3> sites</h3>
                    <li v-for="(link,index) in links1" :key="index">
                        <a :href="link.url" :class="{'active':link.current}">{{link.text}}</a>
                    </li>
                </ul>
            </div>

          <img src="../assets/img/dc-logo-bg.png" alt="" >
    </div>
    
        
    </footer>
</template>

<script>
    export default {
        name:'FooterComponent',
        data() {
            return {
                links1: [
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

footer{
    background-image: url(../assets/img/footer-bg.jpg);
     height: 480px;  
     .container-footer{
        display: flex;
        justify-content: space-between;
        max-width: 1200px;
        margin:0 auto;
       .conteiner-lu{
        display: flex;
        padding: 20px;
            ul{
                padding: 20px;

                h3{
                        color: white;
                        text-transform: uppercase;
                    }

                li{
                    list-style-type: none;

                    a{
                        text-decoration: none;
                        color: gray;
                        font-weight: 100;
                        font-size: 15px;  
                     }
                }
            }
       } 
       
       .cont-shop{
        margin-left: -20px;
       }
     }   
}
</style>