<template>
    <div id="panel-main">
        <div id="panel-nav"></div>
        <div id="panel-info">
            <div id="panel-text">
                <p>To:<b>Your Recipient</b></p>
                <p>Subject:<b>Check out my new Email Signature</b></p>
            </div>
        </div>
        <div id="panel-display"></div>
    </div>
</template>

<script>
export default {
    name:'Panel'
}
</script>


<style scoped>
#panel-main{
    width: 700px;
    height: 500px;
    border-radius: 7px;
    overflow: hidden;
}
#panel-nav{
    width: 100%;
    height: 30px;
    border-bottom: 1px solid white;
    background-color: rgb(41, 41, 78);
}
#panel-info{
    width: 100%;
    height: 60px;
    background-color: rgb(41, 41, 78);
}
#panel-display{    
    width: 100%;
    height: calc(100% - 90px);
    background-color: white;
}
#panel-text{
    margin-left:20px;
    text-align: left;
    font-size: 14px;
}
#panel-text p{
    margin: 0px;
    line-height: 30px;
}
</style>