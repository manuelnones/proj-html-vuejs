<script>
export default {
    name: `AppFooter`,
    data() {
        return {
            addressLinks: [
                `382 NE 191st St # 87394 Miami, FL 33179-3899`,
                `+1 (305) 547-9909 (9am - 5pm EST, Monday - Friday)`,
                `support@maxcoach.com`,
            ],

            exploreLinks: [
                `Start here`,
                `Blog`,
                `About us`,
                `Success story`,
                `Courses`,
                `Contact us`,
            ],

            informationLinks: [
                `Memebership`,
                `Purchase guide`,
                `Privacy policy`,
                `Terms of services`,
            ]
        }
    }
}
</script>

<template>
    <footer>

        <div id="footer-container">
            <div id="footer-top">
                <div id="footer-top-left">
                    <h4>Address</h4>

                    <ul>
                        <li v-for="link in addressLinks">{{ link }}</li>
                    </ul>

                    <div id="logos-footer">
                        <i class="fa-brands fa-facebook"></i>
                        <i class="fa-brands fa-twitter"></i>
                        <i class="fa-brands fa-instagram"></i>
                        <i class="fa-brands fa-linkedin"></i>
                    </div>
                </div>

                <div id="footer-top-right">
                    <div id="explore-links">
                        <h4>Explore</h4>

                        <ul>
                            <li v-for="link in exploreLinks">{{ link }}</li>
                        </ul>
                    </div>

                    <div id="information-links">
                        <h4>Information</h4>

                        <ul>
                            <li v-for="link in informationLinks">{{ link }}</li>
                        </ul>
                    </div>
                </div>
            </div>

            <div id="footer-bottom">@ 2020 Maxcoach. All Rights Reserved</div>

            <button><i class="fa-solid fa-arrow-up-long"></i></button>
        </div>

    </footer>
</template>

<style lang="scss" scoped>
footer {
    position: relative;
    background-color: #F8F8F8;
    padding-bottom: 50px;
    padding-top: 60px;

    #footer-container {
        width: 70%;
        margin: auto;

        #footer-top {
            display: flex;
            justify-content: space-between;

            #footer-top-left {

                ul {
                    li {
                        margin-top: 15px;
                    }
                }

                #logos-footer {
                    margin-top: 40px;

                    .fa-brands {
                        margin-right: 30px;
                        font-size: 1.5em;
                        color: #B1B1B1;
                    }
                }
            }

            #footer-top-right {
                display: flex;
                justify-content: space-between;

                #explore-links {

                    margin-right: 100px;

                    h4 {
                        margin-bottom: 20px;
                    }

                    ul {

                        li {
                            margin-top: 10px;
                        }
                    }
                }

                #information-links {
                    h4 {
                        margin-bottom: 20px;
                    }

                    ul {

                        li {
                            margin-top: 10px;
                        }
                    }
                }
            }
        }
    }

    #footer-bottom {
        text-align: center;
        margin-top: 80px;
        font-weight: 700;
        color: #B1B1B1;
    }

    button {
        position: absolute;
        right: 20px;
        bottom: 20px;
        height: 45px;
        width: 45px;
        border: none;
        border-radius: 50%;
        background-color: #20AD96;
        cursor: pointer;
    }

    button:hover {
        background-color: #FFFFFF;
        color: #20AD96;
        border: 1px solid #20AD96;
    }
}
</style>