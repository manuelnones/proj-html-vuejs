<script>
export default {
    name: `AppHeader`,
    data() {
        return {
            imgLogo: `./img/light-logo.png`,
            navLinks: [
                `Home`,
                `Pages`,
                `Courses`,
                `Features`,
                `Blog`,
                `Shop`,
            ]
        }
    },
}
</script>

<template>
    <header>
        <div id="nav-bar">
            <div id="logo">
                <img :src="imgLogo" alt="Logo">
            </div>

            <div id="links-nav">
                <ul>
                    <li v-for="navLink in navLinks"> {{ navLink }} <i class="fa-solid fa-chevron-down"></i></li>
                </ul>
                <i class="nav-icon fa-solid fa-cart-shopping"></i>
                <i class="nav-icon fa-regular fa-circle-user"></i>
                <input type="text" id="search-bar" placeholder="Search..">
                <button>
                    <i class="fas fa-search"></i>
                </button>
            </div>
        </div>
    </header>
</template>

<style lang="scss" scoped>
header {
    background-color: #1F1F52;
    height: 500px;

    #nav-bar {
        display: flex;
        justify-content: space-between;
        align-items: center;
        height: 80px;
        max-width: 1100px;
        margin: auto;

        #logo {
            width: 150px;

            img {
                width: 100%;
            }
        }

        #links-nav {
            display: flex;
            align-items: center;

            ul {
                display: flex;
                gap: 30px;
                font-weight: bold;

                .fa-solid {
                    font-size: 10px;
                }
            }

            .nav-icon {
                margin-left: 20px;
            }

            input {
                height: 40px;
                width: 100px;
                margin-left: 20px;
                padding-left: 20px;
                border: none;
                border-top-left-radius: 4px;
                border-bottom-left-radius: 4px;
                color: gray;
                background-color: #FFFFFF;
            }

            button {
                height: 40px;
                border: none;
                border-top-right-radius: 4px;
                border-bottom-right-radius: 4px;
                padding: 10px;
                color: #23AE97;
                background-color: #FFFFFF;
            }

            button:hover {
                background-color: #C1C1C1;
            }
        }
    }
}
</style>