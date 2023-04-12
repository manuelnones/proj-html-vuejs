<script>
export default {
    name: `AppMain`,
    data() {
        return {

        }
    }
}
</script>



<template>
    <main>
        <!-- section-1 -->
        <section id="section-1">

            <div id="text-sect-1">
                <div></div>
                <div></div>
                <div></div>
            </div>

            <div id="person-info-course"></div>

            <div id="content-sect-1">

                <div id="cards-container">
                    <div id="cards-left">
                        <div class="card"></div>
                        <div class="card card-left-bottom"></div>
                    </div>

                    <div id="cards-right">
                        <div class="card card-right-top"></div>
                        <div class="card"></div>
                    </div>
                </div>

                <div id="text-container-sect-1">
                    <div id="top-subtitle-sect-1"></div>
                    <h1></h1>
                    <ul>
                        <li></li>
                        <li></li>
                        <li></li>
                        <li></li>
                    </ul>
                    <button>Get started for free</button>
                </div>

            </div>

        </section>
        <!-- /section-1 -->


        <!-- section-2  -->
        <section id="section-2">
            <div id="top-sub-title-sect-2"></div>
            <h1></h1>

            <div id="content-sect-2">

            </div>

            <div id="btn-container">
                <button> <strong>View all courses --></strong> </button>
            </div>
        </section>
        <!-- /section-2  -->
    </main>
</template>



<style lang="scss" scoped>
main {

    // section-1 ---------------------------
    #section-1 {
        padding-top: 89px;
        padding-bottom: 90px;

        #text-sect-1 {
            width: 500px;
            height: 200px;
            background-color: red;
            // /prova
            margin: auto;
            margin-top: 150px;
        }

        #person-info-course {
            width: 900px;
            height: 80px;
            background-color: aqua;
            // /prova
            margin: auto;
            margin-top: 100px;
        }

        #content-sect-1 {
            display: flex;
            width: 950px;
            margin: auto;
            margin-top: 100px;

            #cards-container {
                display: flex;
                flex-flow: row wrap;
                gap: 20px;
                width: 40%;

                .card {
                    width: 180px;
                    height: 250px;
                    background-color: aquamarine;
                    // /prova 
                }

                #cards-right {
                    margin-top: 70px;

                    .card-right-top {
                        margin-bottom: 20px;
                    }
                }

                #cards-left {
                    .card-left-bottom {
                        margin-top: 20px;
                    }
                }
            }

            #text-container-sect-1 {
                margin-top: 150px;
                margin-left: 70px;

                #top-subtitle-sect-1 {
                    width: 150px;
                    height: 20px;
                    background-color: red;
                    // /prova 
                    margin-bottom: 15px;
                }

                h1 {
                    width: 250px;
                    height: 90px;
                    background-color: red;
                    // /prova 
                    margin-bottom: 40px;
                }

                ul {
                    width: 250px;
                    height: 120px;
                    background-color: red;
                    // /prova 
                    margin-bottom: 30px;
                }

                button {
                    padding: 10px 20px;
                    background-color: #20AD96;
                    border: none;
                    border-radius: 4px;
                }
            }
        }

    }

    // /section-1 ----------------------


    // section-2 ---------------------
    #section-2 {
        padding-top: 80px;
        padding-bottom: 90px;
        background-color: #F5F7FA;

        #top-sub-title-sect-2 {
            width: 300px;
            height: 20px;
            background-color: orange;
            // /prova 
            margin: auto;
        }

        h1 {
            width: 500px;
            height: 40px;
            background-color: orange;
            // /prova 
            margin: auto;
            margin-top: 20px;
        }

        #content-sect-2 {
            width: 800px;
            height: 500px;
            background-color: red;
            // /prova 
            margin: auto;
            margin-top: 70px;
        }

        #btn-container {
            width: 164px;
            margin: auto;

            button {
                padding: 10px 20px;
                background-color: #20AD96;
                border: none;
                border-radius: 4px;
                margin-top: 50px;
            }
        }
    }
}
</style>