<template>
    <div>
        <!-- <div class="container">
            <div class="row">
                <div class="col-md-4">拍照</div>
                <div class="col-md-4">语音</div>
                <div class="col-md-4">新建</div>
            </div>
            <div class="row">
                <div class="col-xs-4 col-md-6">拍照</div>
                <div class="col-xs-4 col-md-3">语音</div>
                <div class="col-xs-4 col-md-3">新建</div>
            </div>
        </div> -->
        <header>
            <div><img src="../assets/pic.png"></div>
            <div><img src="../assets/mic2.png"></div>
            <div><img src="../assets/edit.png"></div>
        </header>
    </div>
</template>

<style>
    .container {
        background: #eee;
    }
    
    header {
        display: flex;
        justify-content: space-around;
        align-items: center;
        height: 330px;
        background: #5e9ecc;
        color: #fff;
    }
    header img{
        height:48px;
        width:48px;
    }
</style>
