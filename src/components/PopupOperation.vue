<template>
    <div class="popup">
        <div class="buttons-container">
            <div class="buttons">
            <button class="btn cancel">
                ID
            </button>
            <input class="text"  placeholder="Введите id"/>
            <button class="btn buy">
                Назад
            </button>
        </div>
        <div class="buttons">
            <button class="btn cancel">
                Сумма
            </button>
                <input class="text"  placeholder="Введите сумму"/>
            <button class="btn buy">
                Далее
            </button>
        </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
    .popup {
        background: rgba(0,0,0,0.5);
        height: 100vh;
        left: 0;
        bottom: 0;
        position: absolute;
        top: 0;
        z-index: 11;
        right: 0;
        display: flex;
        justify-content: center;
        align-items: center;
    }
    .buttons {
    display: flex;
    justify-content: space-between;
    margin-top: 15px;
    width: 1000px;
    &:nth-child(2) {
        margin-left: 60px;
        margin-top: 30px;
    }
    & .btn {
        width: 200px;
    }
    & .btn,.text {
        background: #020B00;
        border-top-left-radius: 2px;
        border-top-right-radius: 60px;
        border-bottom-right-radius: 2px;
        border-bottom-left-radius: 60px;
        font-size: 27px;
        font-weight: 600;
        padding: 20px 40px;
        &:focus {
            outline: none;
        }
    }
    & .cancel {
        border:2px solid #FF3131;
        box-shadow: 0px 0px 8px #FF3131, 0px 0px 15px #FF3131;
        cursor: pointer;
        color:#FF3131;
    }
    & .text {
        background: #000;
        box-shadow: 0px 0px 8px #4CF030, 0px 0px 15px #4CF030;
        color:#fff;
    }
    & .buy {
        border:2px solid #00CB00;
        box-shadow: 0px 0px 8px #00CB00, 0px 0px 15px #00CB00;
        cursor: pointer;
        color:#00AC00;
    }
}
</style>