<template>    
    <div class="container">
        <div class="header">
            <p>AB<span>(){</span></p>     
        </div>

        <div class="search">
            <a class="reseaux" href="https://github.com/AmelieBele"><i class="fa-brands fa-github"></i></a>
            <a class="reseaux" href="https://www.linkedin.com/in/amelie-marie-benoist/"><i class="fa-brands fa-linkedin-in"></i></a>
        </div>
    </div>
</template>

<script>

export default {
  name: 'HeaderComponent',
}
</script>

<style lang="scss" scoped>
    .container {
        display:flex;
        justify-content:space-between;

    }
    .header{
        margin-left:40px;
    }
    p{
        color: white;
        font-size: 100px;
    }
    span{
        color: #700817;
        font-family: 'La belle Aurore', sans-serif;
        font-size:1rem;
    }
    .search{
        display:flex;
        align-items:center;
        padding: 10px;
        font-size:30px;
        margin-top: -50px;
    }
    a{
        padding:15px;
    }

    .button{
        font-size: 25px;
        border: none;
        padding: 15px;
    }

</style>
