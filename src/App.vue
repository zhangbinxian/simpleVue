<template>
    <div class="main">
        <div class="school">
            <div class="info">
                <p>武汉纺织大学</p>
                <p>物联网工程 | 普通全日制</p>
            </div>
            <div class="undergraduate">
                <span>本科</span>
            </div>
        </div>

        <div class="biye">
            <p>毕业去向</p>
        </div>
        <div class="whereAndTime">
            <p>武汉纺织大学保卫处 (保安)</p>
            <p>签订就业协议形式就业 | 2024年4月23日</p>
        </div>
    </div>
</template>

<script>
export default {}
</script>

<style>
.main {
    width: 500px;
    position: relative;
}
.whereAndTime {
    padding-top: 3px;
    width: 350px;
    height: 100px;

    background: linear-gradient(to right, rgb(94, 110, 190), rgb(80, 127, 208));

    border-radius: 10px;
}
.biye p {
    padding-left: 1px;
    color: black;
    font-family: 微软雅黑;
    padding-top: 5px;
    font-weight: bold;
}
.undergraduate {
    font-size: 14px;
    height: 18px;
    width: 40px;
    text-align: center;
    color: aliceblue;
    margin-left: 70px;
    margin-top: 22px;
    background-color: rgb(43, 116, 7);
    border-radius: 8px;
}
p {
    padding-top: 5px;
    padding-left: 20px;
    color: aliceblue;
    font-family: 微软雅黑;
    font-size: 16px;
}

.school {
    width: 350px;
    height: 100px;
    background: linear-gradient(to right, rgb(90, 205, 140), rgb(52, 197, 114));
    border-radius: 10px;

    display: flex;
}
</style>
