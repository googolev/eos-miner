<template>
    <div class="keyConnectForm">
        <form>
            <h3>Connect Secret Key</h3>
            <div class="wrap-input">
                <input type="text" />
            </div>
            <button>Submit</button>
        </form>
    </div>
</template>

<style lang="less">
    .keyConnectForm {
        position: relative;
        max-width: 420px;
        width: 100%;
        background: rgb(255, 255, 255);
        box-shadow: rgb(0 0 0 / 1%) 0px 0px 1px, rgb(0 0 0 / 4%) 0px 4px 8px, rgb(0 0 0 / 4%) 0px 16px 24px, rgb(0 0 0 / 1%) 0px 24px 32px;
        border-radius: 30px;
        form {
            display:flex;
            flex-direction: column;
            padding: 1rem;
            h3 {
                font-size:16px;
            }
            button {
                background: #827ffe;
                display: flex;
                justify-content: center;
                align-items: center;
                padding: 0 20px;
                min-width: 150px;
                height: 62px;
                border-radius: 31px;
                font-family: Ubuntu-Bold;
                font-size: 16px;
                color: #fff;
                line-height: 1.2;
                text-transform: uppercase;
                &:focus {
                    outline: none;
                }
            }
        }
    }
</style>