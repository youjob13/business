<template>
    <div class="popup">
        <div class="buttons">
            <div class="text">
                Покупка совершена
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
    .text {
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
    & .text {
        background: linear-gradient(to bottom, #4CF030 0%, #082104 100%);
        box-shadow: 0px 0px 8px #4CF030, 0px 0px 15px #4CF030;
        color:#fff;
    }
}
</style>