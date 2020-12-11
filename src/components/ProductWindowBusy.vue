<template>
    <div class="container_1">
        <div class="container_2">
            <div class="container_3">
                    <header class="header">
                        <h2 class="header-title">Бизнес</h2>
                        <p class="header-content">24/7</p>
                    </header>
                <div class="main">
                    <div class="characteristics">
                        <div>
                            <h3>Название</h3>
                            <h3>Прибыль</h3>
                            <h3>Владелец</h3>
                        </div>
                        <div>
                            <p>Супермаркет</p>
                            <p>1520$</p>
                            <p>Отсутствует</p>
                        </div>
                    </div>
                    <div class="price">
                        <h3 class="price-title">Цена:</h3>
                        <p class="price-value">152000$</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
.container_1 {
    width: 750px;
    height: 415px;
    background: #AC9B00;
    box-shadow: 0px 0px 20px #AC9B00, 0px 0px 35px #AC9B00;
    border-top-left-radius: 4px;
    border-top-right-radius: 360px;
    position: relative;
    z-index: 3;
    border-bottom-right-radius: 2px;
    border-bottom-left-radius: 60px;
}
.container_2 {
    width: 720px;
    height: 415px;
    background: #E6E992;
    position: relative;
    z-index: 2;
    border-top-left-radius: 4px;
    border-top-right-radius: 360px;
    border-bottom-right-radius: 2px;
    border-bottom-left-radius: 60px;
}
.container_3 {
    margin: auto;
    width: 690px;
    height: 415px;
    background: linear-gradient(145deg, #F0C330 0%, #210E04 100%);
    border-top-left-radius: 4px;
    border-top-right-radius: 360px;
    border-bottom-right-radius: 2px;
    border-bottom-left-radius: 60px;
    position: relative;
    z-index: 1;
}
.header {
        display: flex;
        align-items: center;
        padding-top: 20px;
        &-title {
            color:#fff;
            font-weight: 700;
            font-size: 27px;
            padding:10px 40px;
            background: rgba($color: #000000, $alpha: 0.3);
            border-top-right-radius:4px;
            border-bottom-right-radius:4px;
            margin-right: 45px;
        }
        &-content {
            width: 30%;
            color:rgba($color: #000000, $alpha: 0.5);
            font-size: 27px;
            font-weight: 700;
            margin-top: 12px;
            padding-left: 10px;
            padding-bottom: 8px;
            border-bottom: 2px solid rgba($color: #000000, $alpha: 0.3);
        }
}
.main {
    margin-top: 85px;
    padding: 0 250px 0 40px;
    & .characteristics {
        margin-bottom: 48px;
        display: flex;
        align-items: center;
        h3 {
            font-size: 22px;
            font-weight: 600;
            padding-right: 120px;
            color:rgba($color: #000000, $alpha: 0.7);
            border-bottom: 2px solid rgba($color: #000000, $alpha: 0.5);
            padding-bottom: 4px;
            margin-bottom: 10px;
        }
        p {
            line-height: 1.3;
            font-size: 21px;
            color:rgba($color: #000000, $alpha: 0.7);
            font-weight: 500;
            margin-bottom: 10px;
            padding-bottom: 4px;
            font-style: italic;
            border-bottom: 2px solid rgba($color: #000000, $alpha: 0.5);
        }
    }
    & .buttons {
        display: flex;
        text-align: center;
        align-items: center;
        margin-bottom: 90px;
        .btn {
            display: flex;
            align-items: center;
            width: 200px;
            justify-content: center;
            color:#fff;
            font-weight: 400;
            font-size: 19px;
            padding:8px 10px;
            border:2px solid #fff;
            border-radius: 6px;
            box-shadow: 0px 0px 8px #fff;
            &:first-child {
                margin-right: 15px;
            }
            cursor: pointer;
            &:focus {
                outline: none;
            }
            &:hover {
                background: #fff;
                color:rgb(0, 0, 0);
            }
        }
    }
    & .price {
        display: flex;
        align-items: center;
        &-title {
            font-size: 27px;
            font-weight: 600;
            color:#fff;
            margin-right: 14px;
        }
        &-value {
            font-weight: 700;
            font-size: 27px;
            color: rgba(255, 255, 255,0.5);
            background: rgba(0,0,0,0.3);
            padding: 10px 400px 10px 40px;
            border-top-left-radius: 8px;
            border-bottom-left-radius: 8px;
        }
    }
}
</style>