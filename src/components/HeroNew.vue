<template>
    <b-container fluid style="height: 100vh;">
        <b-row style="text-align: center; position: relative; justify-content: center;">
        <!-- 
            <img src="../assets/sam-372-cropped.jpg" width="250px;" height="150px;" class="img-sam" alt=""> -->
            <b-col lg="12" sm="12" cols="12">
                <div class="name">SAMRMDHN'S PORTFOLIO</div>
            </b-col>
            <b-col lg="4" sm="4" md="4" cols="4">
                <p>{{dayjs().format()}}</p>
            </b-col>
            <b-col lg="4" sm="4" md="4" cols="4">
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Beatae suscipit quaerat quam.</p>
            </b-col>
            <b-col lg="4" sm="4" md="4" cols="4">
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Corrupti quisquam repellendus earum ipsa voluptatibus vitae?</p>
            </b-col>
        </b-row>
    </b-container>
</template>
<script>
export default {
    name: 'HeroNew',
    data(){
        return{
           
        }
    }
}
</script>

<style scoped>

    .img-sam{
        height: auto;
        max-width: 100%;
        position: absolute;
        margin-top: 110px;
    }
    
    .name{
        font-size: 7rem;
    }

    @media only screen and (max-width: 429px){
        .name{
            font-size: 3rem;
        }

        
    }
</style>