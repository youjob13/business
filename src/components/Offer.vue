<template>
    <div>
        <div class="main">
        <div>
            <h2 class="title">
            Alex_Alex
        </h2>
        <p class="text">
            Предлагает вам 
        приобрести бизнес
        </p>
        </div>
        <div class="price">
            <h3 class="price-title">
                Цена:
            </h3>
            <p class="price-value">1000000$</p>
        </div>
    </div>
    <div class="buttons">
        <button class="btn cancel">
            Отмена
        </button>
        <button class="btn buy">
            Купить
        </button>
    </div>
    </div>
</template>

<style lang="scss" scoped>
.main {
    width: 530px;
    height: 360px;
    background: linear-gradient(to bottom, #4CF030 0%, #082104 100%);
    box-shadow: 0px 0px 20px #00CB00, 0px 0px 45px #00CB00, 0px 0px 60px #00CB00;
    border-top-left-radius: 2px;
    border-top-right-radius: 60px;
    border-bottom-right-radius: 2px;
    border-bottom-left-radius: 60px;
    & .title {
        text-align: center;
        color: rgba($color: #000000, $alpha: 0.5);
        font-weight: 700;
        font-size: 32px;
        margin-top: 30px;
    }
    & .text {
        color:#fff;
        text-align: center;
        padding: 50px 120px;
        font-size: 27px;
        font-weight: 600;
    }
    & .price {
        display: flex;
        justify-content: space-between;
        padding: 0 90px 0 70px;
        align-items: center;
        &-title {
            font-weight: 700;
            font-size: 32px;
            color:rgba($color: #000000, $alpha: 0.5);
            margin-right: 20px;
        }
        &-value {
            font-weight: 700;
            font-size: 32px;
            color:#00AC00;
            border-radius: 8px;
            padding: 6px 55px;
            background: rgba($color: #000000, $alpha: 0.3);
        }
    }
}
.buttons {
    display: flex;
    justify-content: space-between;
    margin-top: 15px;
    & .btn {
        width: 180px;
        height: 75px;
        background: #020B00;
        border-top-left-radius: 2px;
        border-top-right-radius: 60px;
        border-bottom-right-radius: 2px;
        border-bottom-left-radius: 60px;
        font-size: 27px;
        font-weight: 600;
        padding: 20px 40px;
        cursor: pointer;
        &:focus {
            outline: none;
        }
    }
    & .cancel {
        border:2px solid #FF3131;
        box-shadow: 0px 0px 8px #FF3131, 0px 0px 15px #FF3131;
        color:#FF3131;
    }
    & .buy {
        border:2px solid #00CB00;
        box-shadow: 0px 0px 8px #00CB00, 0px 0px 15px #00CB00;
        color:#00AC00;
    }
}
</style>