<script>
export default {
    name: `AppMain`,
    data() {
        return {
            imgCard1: `./img/home-6-service-image-01.png`,
            imgCard2: `./img/home-6-service-image-03.png`,
            imgCard3: `./img/home-6-service-image-02.png`,
            imgCard4: `./img/home-6-service-image-04.png`,

            imgCourses1: `./img/course-02-480x298.jpg`,
            imgCourses2: `./img/stock-full-hd-04-480x298.jpg`,
            imgCourses3: `./img/course-featured-image-01-480x298.jpg`,
            imgCourses4: `./img/stock-full-hd-03-480x298.jpg`,
            imgCourses5: `./img/stock-full-hd-06-480x298.jpg`,
            imgCourses6: `./img/stock-full-hd-05-480x298.jpg`,

            imgAuthorComment: `./img/testimonial-avata-02.jpg`,

            logo1Sect3: `./img/client-logo-colored-01.png`,
            logo2Sect3: `./img/client-logo-colored-02.png`,
            logo3Sect3: `./img/client-logo-colored-03.png`,
            logo4Sect3: `./img/client-logo-colored-04.png`,
            logo5Sect3: `./img/client-logo-colored-05.png`,
            logo6Sect3: `./img/client-logo-colored-06.png`,

            img1Sect4: `./img/artist-blog-03-480x325.jpeg`,
            img2Sect4: `./img/artist-blog-01-480x325.jpg`,
            img3Sect4: `./img/artist-blog-02-480x325.jpg`,
        }
    }
}
</script>



<template>
    <main>
        <!-- section-1 -->
        <section id="section-1">

            <div id="text-sect-1">
                <h1>
                    Let passion and determination be the guide along the way and develop at your own pace that's comfortable
                </h1>
                <div id="name-founder">fannie moreno</div>
                <div id="founder">/Founder & CEO</div>
            </div>

            <div id="person-info-course">
                <div class="info-number">
                    <div class="number">1.926</div>
                    <div class="info">finished sessions</div>
                </div>

                <div class="info-number">
                    <div class="number">3.092+</div>
                    <div class="info">enrolled learners</div>
                </div>

                <div class="info-number">
                    <div class="number">200</div>
                    <div class="info">online instructors</div>
                </div>

                <div class="info-number">
                    <div class="number">100%</div>
                    <div class="info">satisfaction rate</div>
                </div>
            </div>

            <div id="content-sect-1">

                <div id="cards-container">
                    <div id="cards-left">
                        <div class="card">
                            <h4>Graphic Design</h4>

                            <p>
                                Have a passion for graphics and arts? Show your talent with confidence and
                                self-assertiveness.
                            </p>

                            <div class="img-card-container">
                                <img :src="imgCard1">
                            </div>
                        </div>

                        <div class="card card-left-bottom">
                            <div class="img-card-container">
                                <img :src="imgCard2">
                            </div>

                            <h4>Idea Discussion</h4>

                            <p>
                                Get teamed up with the specialist who work and teach coding for years at famous
                                universities.
                            </p>
                        </div>
                    </div>

                    <div id="cards-right">
                        <div class="card card-right-top">
                            <h4>Business Administration</h4>

                            <p>
                                Leamers are encouraged to study the mechanism and structure of system administration.
                            </p>

                            <div class="img-card-container">
                                <img :src="imgCard3">
                            </div>
                        </div>

                        <div class="card">
                            <div class="img-card-container">
                                <img :src="imgCard4">
                            </div>

                            <h4>Web Development</h4>

                            <p>
                                Learn to start building a webpage from scratch. You decide your awn pace, course and speed.
                            </p>
                        </div>
                    </div>
                </div>

                <div id="text-container-sect-1">
                    <div id="top-subtitle-sect-1"> together we can create</div>
                    <h1>Service We <span>Can Provide </span>For My Clients.</h1>
                    <ul>
                        <li>
                            <span><i class="fa-solid fa-check"></i></span>
                            Select & customize courses to your preferences
                        </li>
                        <li>
                            <span><i class="fa-solid fa-check"></i></span>
                            Change the tutor and make arrangements
                        </li>
                        <li>
                            <span><i class="fa-solid fa-check"></i></span>
                            Participate in events to join others
                        </li>
                        <li>
                            <span><i class="fa-solid fa-check"></i></span>
                            Get the desired certificate delivered at house
                        </li>
                    </ul>
                    <button>Get started for free</button>
                </div>

            </div>

        </section>
        <!-- /section-1 -->


        <!-- section-2  -->
        <section id="section-2">
            <div id="top-sub-title-sect-2">choose a course to get started</div>
            <h1>Latest Featured <span>Courses</span></h1>

            <div id="content-sect-2">

                <div class="course">
                    <div class="img-container">
                        <img :src="imgCourses1" alt="">
                    </div>

                    <div class="info-course">
                        <div class="price-course"> <strong>$40.00</strong> </div>
                        <div class="type-course"> <strong>Learning to Write as a Professional Author</strong> </div>
                        <div class="number-lessons-and-students">
                            <div><i class="fa-regular fa-file-image"></i> 20 Lessons</div>
                            <div><i class="fa-regular fa-user"></i> 50 Students</div>
                        </div>
                    </div>
                </div>


                <div class="course">
                    <div class="img-container">
                        <img :src="imgCourses2" alt="">
                    </div>

                    <div class="info-course">
                        <div class="price-course"> <strong>$19.00</strong> </div>
                        <div class="type-course"> <strong>Learning to Write as a Professional Author</strong> </div>
                        <div class="number-lessons-and-students">
                            <div><i class="fa-regular fa-file-image"></i> 17 Lessons</div>
                            <div><i class="fa-regular fa-user"></i> 62 Students</div>
                        </div>
                    </div>
                </div>


                <div class="course">
                    <div class="img-container">
                        <img :src="imgCourses3" alt="">
                    </div>

                    <div class="info-course">
                        <div class="price-course"> <strong>$39.00</strong> </div>
                        <div class="type-course"> <strong>Learning to Write as a Professional Author</strong> </div>
                        <div class="number-lessons-and-students">
                            <div><i class="fa-regular fa-file-image"></i> 6 Lessons</div>
                            <div><i class="fa-regular fa-user"></i> 51 Students</div>
                        </div>
                    </div>
                </div>


                <div class="course">
                    <div class="img-container">
                        <img :src="imgCourses4" alt="">
                    </div>

                    <div class="info-course">
                        <div class="price-course"> <strong>Free</strong> </div>
                        <div class="type-course"> <strong>Learning to Write as a Professional Author</strong> </div>
                        <div class="number-lessons-and-students">
                            <div><i class="fa-regular fa-file-image"></i> 24 Lessons</div>
                            <div><i class="fa-regular fa-user"></i> 769 Students</div>
                        </div>
                    </div>
                </div>


                <div class="course">
                    <div class="img-container">
                        <img :src="imgCourses5" alt="">
                    </div>

                    <div class="info-course">
                        <div class="price-course"> <strong>$26.00</strong> </div>
                        <div class="type-course"> <strong>Learning to Write as a Professional Author</strong> </div>
                        <div class="number-lessons-and-students">
                            <div><i class="fa-regular fa-file-image"></i> 14 Lessons</div>
                            <div><i class="fa-regular fa-user"></i> 67 Students</div>
                        </div>
                    </div>
                </div>


                <div class="course">
                    <div class="img-container">
                        <img :src="imgCourses6" alt="">
                    </div>

                    <div class="info-course">
                        <div class="price-course"> <strong>$59.00</strong> </div>
                        <div class="type-course"> <strong>Learning to Write as a Professional Author</strong> </div>
                        <div class="number-lessons-and-students">
                            <div><i class="fa-regular fa-file-image"></i> 14 Lessons</div>
                            <div><i class="fa-regular fa-user"></i> 76 Students</div>
                        </div>
                    </div>
                </div>

            </div>

            <div id="btn-container">
                <button> <strong>View all courses --></strong> </button>
            </div>
        </section>
        <!-- /section-2  -->


        <!-- section-3  -->
        <section id="section-3">
            <h1>Why People Talk About <span>MaxCoach</span>?</h1>

            <div id="comment-container">
                <div id="img-container">
                    <img :src="imgAuthorComment">
                </div>

                <div id="text-comment-container">
                    <div id="comment">
                        I am free to learn at my own pace, follow my own schedule and choose the subject I like. Great study
                        portal for people like me.
                    </div>
                    <div id="author">mina hollace</div>
                    <div id="role">/ Freelancer</div>
                </div>
            </div>

            <div id="logos-container">
                <div class="img-logo">
                    <img :src="logo1Sect3" alt="logo AQUA">
                </div>
                <div class="img-logo">
                    <img :src="logo2Sect3" alt="logo AdRoll">
                </div>
                <div class="img-logo">
                    <img :src="logo3Sect3" alt="logo FOX">
                </div>
                <div class="img-logo">
                    <img :src="logo4Sect3" alt="logo Woodland">
                </div>
                <div class="img-logo">
                    <img :src="logo5Sect3" alt="logo BullFit">
                </div>
                <div class="img-logo">
                    <img :src="logo6Sect3" alt="logo sixbase">
                </div>
            </div>
        </section>
        <!-- /section-3  -->


        <!-- section-4  -->
        <section id="section-4">
            <div id="top-sub-title-sect-4">enjoy reading on maxcoach</div>
            <h1>Latest on <span>Our Blogs</span></h1>

            <div id="components-sect-4">
                <div class="components">
                    <div class="img-sect-4-container">
                        <img :src="img1Sect4" alt="">
                    </div>

                    <div class="artist">Artist</div>

                    <h4 class="title-img">Brush Strokes Energize Trees in Paintings</h4>

                    <div class="info-img">
                        <span>
                            <i class="fa-regular fa-calendar"></i>
                            May 15, 2020
                        </span>

                        <span>
                            <i class="fa-regular fa-eye"></i>
                            688 views
                        </span>
                    </div>
                </div>

                <div class="components">
                    <div class="img-sect-4-container">
                        <img :src="img2Sect4" alt="">
                    </div>

                    <div class="artist">Artist</div>

                    <h4 class="title-img">Pocket-Sized Notebooks Hold Miniature Paintings</h4>

                    <div class="info-img">
                        <span>
                            <i class="fa-regular fa-calendar"></i>
                            May 15, 2020
                        </span>

                        <span>
                            <i class="fa-regular fa-eye"></i>
                            603 views
                        </span>
                    </div>
                </div>

                <div class="components">
                    <div class="img-sect-4-container">
                        <img :src="img3Sect4" alt="">
                    </div>

                    <div class="artist">Artist</div>

                    <h4 class="title-img">Connection Between Self-Portraits and Identity</h4>

                    <div class="info-img">
                        <span>
                            <i class="fa-regular fa-calendar"></i>
                            May 15, 2020
                        </span>

                        <span>
                            <i class="fa-regular fa-eye"></i>
                            397 views
                        </span>
                    </div>
                </div>
            </div>
        </section>
        <!-- /section-4  -->


        <!-- section-5  -->
        <section id="section-5">
        </section>
        <!-- /section-5  -->


        <!-- section-6  -->
        <section id="section-6">
        </section>
        <!-- /section-6  -->
    </main>
</template>



<style lang="scss" scoped>
$greenColor: #20AD96;

main {

    // section-1 ---------------------------
    #section-1 {
        padding-top: 89px;
        padding-bottom: 90px;

        #text-sect-1 {
            width: 500px;
            margin: auto;
            text-align: center;
            margin-top: 150px;

            h1 {
                font-size: 2em;
            }

            #name-founder {
                margin-top: 30px;
                text-transform: uppercase;
                font-weight: 700;
            }

            #founder {
                color: gray;
                font-size: 0.9em;
                margin-top: 10px;
            }
        }

        #person-info-course {
            display: flex;
            justify-content: space-between;
            width: 900px;
            margin: auto;
            margin-top: 100px;

            .info-number {
                text-align: center;

                .number {
                    font-size: 2em;
                    font-weight: 700;
                    color: $greenColor;
                }

                .info {
                    text-transform: uppercase;
                    font-size: 0.8em;
                }
            }
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
                width: 55%;

                .card {
                    width: 230px;
                    padding-bottom: 20px;
                    box-shadow: 10px 0px 40px #C4C4C4;


                    .img-card-container {
                        height: 170px;
                        width: 80%;
                        margin: auto;
                        margin-top: 20px;
                        padding-top: 20px;

                        img {
                            height: 100%;
                            width: 100%;
                        }
                    }

                    h4 {
                        padding-top: 20px;
                        margin-left: 15px;
                        color: #3F3A6D;
                    }

                    p {
                        padding-top: 5px;
                        margin-left: 15px;
                        color: #5F6468;
                    }
                }

                #cards-right {
                    margin-top: 70px;

                    .card-right-top {
                        margin-bottom: 20px;

                        .img-card-container {
                            width: 60%;
                            margin: auto;
                            margin-top: 20px;
                        }
                    }
                }

                #cards-left {
                    .card-left-bottom {
                        margin-top: 20px;

                        .img-card-container {
                            width: 60%;
                            margin-top: 20px;
                            margin-left: 0;
                        }
                    }
                }
            }

            #text-container-sect-1 {
                margin-top: 150px;
                margin-left: 70px;

                #top-subtitle-sect-1 {
                    margin-bottom: 15px;
                    text-transform: uppercase;
                    color: gray;
                }

                h1 {
                    width: 380px;
                    margin-bottom: 40px;
                    font-size: 3em;

                    span {
                        color: $greenColor;
                        font-weight: normal;
                    }
                }

                ul {
                    margin-bottom: 30px;

                    li {
                        margin-top: 15px;

                        span {
                            color: $greenColor;
                        }
                    }
                }

                button {
                    padding: 10px 20px;
                    background-color: $greenColor;
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
            text-align: center;
            color: gray;
            text-transform: uppercase;
            font-size: 0.7em;
        }

        h1 {
            text-align: center;
            margin-top: 20px;
            font-size: 2em;

            span {
                color: $greenColor;
                text-transform: inherit;
                font-weight: normal;
            }
        }

        #content-sect-2 {
            width: 850px;
            height: 450px;
            // /prova 
            display: flex;
            flex-flow: column wrap;
            gap: 50px;
            margin: auto;
            margin-top: 70px;

            .course {
                display: flex;
                align-items: center;
                gap: 20px;
                width: 50%;
                height: calc(100% / 3 - 50px);

                .img-container {
                    height: 130px;
                    width: 150px;
                    border-radius: 50%;
                    overflow: hidden;

                    img {
                        height: 100%;
                        object-position: -40px;
                    }
                }

                .info-course {
                    .price-course {
                        color: $greenColor;
                    }

                    .number-lessons-and-students {
                        display: flex;
                        gap: 20px;
                        margin-top: 10px;
                        color: gray;
                    }
                }
            }
        }

        #btn-container {
            width: 204px;
            margin: auto;

            button {
                padding: 10px 40px;
                background-color: $greenColor;
                border: none;
                border-radius: 4px;
                margin-top: 20px;
            }
        }
    }

    // /section-2 ----------------------


    // section-3 ----------------------
    #section-3 {
        padding-top: 50px;

        h1 {
            text-align: center;
            font-size: 2em;

            span {
                color: $greenColor;
                font-weight: normal;
            }
        }

        #comment-container {
            display: flex;
            align-items: center;
            width: 900px;
            margin: auto;
            margin-top: 70px;

            #img-container {
                height: 180px;
                width: 180px;
                border-radius: 50%;
                overflow: hidden;

                img {
                    width: 100%;
                }
            }

            #text-comment-container {
                width: 520px;
                padding-left: 80px;

                #comment {
                    font-size: 1.5em;
                }

                #author {
                    text-transform: uppercase;
                    margin-top: 30px;
                    font-weight: 700;
                }

                #role {
                    color: gray;
                    margin-top: 10px;
                }
            }
        }

        #logos-container {
            display: flex;
            justify-content: space-between;
            align-items: center;
            width: 1000px;
            margin: auto;
            margin-top: 80px;
            margin-bottom: 60px;

            .img-logo {
                width: 120px;
                height: 70px;

                img {
                    width: 100%;
                    height: 100%;
                    object-fit: contain;
                }
            }
        }
    }

    //  /section-3 


    // section-4 ----------------------
    #section-4 {
        padding-top: 80px;
        padding-bottom: 90px;
        background-color: #F8F8F8;

        #top-sub-title-sect-4 {
            text-align: center;
            color: gray;
            text-transform: uppercase;
            font-size: 0.7em;
        }

        h1 {
            text-align: center;
            margin-top: 20px;
            font-size: 2em;

            span {
                color: $greenColor;
                text-transform: inherit;
                font-weight: normal;
            }
        }

        #components-sect-4 {
            display: flex;
            gap: 30px;
            width: 900px;
            margin: auto;
            margin-top: 50px;

            .components {
                width: calc(100% / 3);

                .img-sect-4-container {
                    img {
                        width: 100%;
                    }
                }

                .artist {
                    text-transform: uppercase;
                    margin-top: 15px;
                    font-size: 0.9em;
                    font-weight: 700;
                    color: gray;
                }

                .title-img {
                    margin-top: 10px;
                    font-size: 1.2em;
                }

                .info-img {
                    margin-top: 20px;
                    color: gray;

                    span {
                        padding-right: 20px;

                        i {
                            margin-right: 5px;
                        }
                    }
                }
            }
        }
    }

    // /section-4 ----------------------

}
</style>