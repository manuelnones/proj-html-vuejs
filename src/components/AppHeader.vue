<script>
export default {
    name: `AppHeader`,
    data() {
        return {
            imgLogo: `./img/light-logo.png`,
            imgHeaderLeft: `./img/home-6-hero-left-person.png`,
            imgHeaderCenter: `./img/home-6-hero-poster-final.jpg`,
            imgHeaderRight: `./img/home-6-hero-right-person.png`,
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
    <!-- header -->
    <header>
        <!-- nav-bar -->
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
        <!-- /nav-bar -->

        <div id="text-header">
            <h1>Learn At Your Own Pace!</h1>
            <div id="sub-title">Get teamed up width people of the same will.</div>
            <button>Get started for free</button>
        </div>

        <div id="imgs-header">
            <div id="img-left">
                <img :src="imgHeaderLeft" alt="">
            </div>
            <div id="img-center">
                <img :src="imgHeaderCenter" alt="">
            </div>
            <div id="img-right">
                <img :src="imgHeaderRight" alt="">
            </div>
        </div>
    </header>
    <!-- /header -->
</template>

<style lang="scss" scoped>
header {
    background-color: #1F1F52;
    height: 700px;

    // nav-bar
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
                cursor: pointer;

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
                cursor: pointer;
            }

            button:hover {
                background-color: #C1C1C1;
            }
        }
    }

    // /nav-bar

    #text-header {
        margin: auto;
        text-align: center;
        margin-top: 80px;
        cursor: default;

        h1 {
            font-size: 2.5em;
        }

        #sub-title {
            color: lightgray;
            margin-bottom: 30px;
        }

        button {
            padding: 15px 40px;
            border: none;
            border-radius: 4px;
            background-color: #20AD96;
            font-weight: bold;
            cursor: pointer;
        }

        button:hover {
            background-color: #FFFFFF;
            color: #20AD96;
        }
    }

    #imgs-header {
        display: flex;
        height: 440px;
        max-width: 1200px;
        margin: auto;
        margin-top: 30px;

        #img-left {
            width: 310px;
            height: 100%;

            img {
                height: 100%;
            }
        }

        #img-center {
            width: calc(100% - 310px - 200px);
            height: 100%;
            border-radius: 15px;
            background-color: #FFFFFF;
            box-shadow: 10px 10px 80px #333333;
            overflow-x: hidden;

            img {
                margin-top: 20px;
                margin-left: 18px;
                height: 90%;
                width: 95%;
            }
        }

        #img-right {
            position: relative;
            width: 200px;
            height: 100%;
            overflow: hidden;

            img {
                position: absolute;
                bottom: -150px;
                right: 0;
                width: 100%;
            }
        }
    }
}
</style>