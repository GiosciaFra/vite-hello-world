<script>

import AppTitle from './AppTitle.vue';

export default {
    name: 'AppHero',
    components: { AppTitle }
}

</script>

<template>
    <div id="jumbo">
        <div class="title">
            <AppTitle></AppTitle>
            <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Tenetur ad rem numquam hic autem voluptas excepturi
                dolorem fuga sit eveniet et, iure exercitationem quisquam illum molestiae ipsam ducimus corrupti commodi!
                Officiis quia voluptates, vitae nostrum nisi alias? Necessitatibus voluptatem explicabo unde? Nisi aliquam
                voluptates harum quod, sunt dignissimos modi magni est explicabo iusto mollitia suscipit dicta illum,
                doloremque quasi asperiores?

            </p>
        </div>

        <hr>

        <div class="photo">
            <img src="../assets/img/mario.png" alt="">


        </div>


    </div>
</template>

<style>

#app {
    display: flex;
    justify-content: center;
}

#jumbo, #jumbo .title p {
    padding-bottom: 50px;
}

#jumbo .photo {
    padding-top: 40px;
    text-align: center;
}

#jumbo .photo img {
    height: 350px;
}

</style>