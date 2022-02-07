<template>
    <div class="jumbotron">
        <div class="container">
            <div class="jumbo-text">
                <h1>Jumbotron test!</h1>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ullam ab sequi ut ducimus fugiat eum repellendus vel eos magnam nihil obcaecati autem eveniet voluptate adipisci at velit numquam, ratione non!</p>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Hero'
}
</script>

<style scoped>
.jumbotron {
    margin-top: 50px;
}
.jumbo-text {
    width: 70%;
    position: absolute;
    color: white;
    top: 50%;
    left: 10%;
    transform: translateY(-50%);
}

.container {
    position: relative;
    margin: auto;
    text-align: left;
    width: 70vw;
    height: 300px;
    border-radius: 30px;
    background-image: linear-gradient(rgba(0, 0, 0, 0.5),rgba(0, 0, 0, 0.5)),url('../assets/vue.jpg');
    background-position: center;
    background-size: cover;
    background-repeat: no-repeat;
}

</style>