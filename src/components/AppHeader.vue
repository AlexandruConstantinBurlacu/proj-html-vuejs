<script>
    export default {
        name: 'AppHeader',
    }
</script>

<template>
    <div class="headerContainer">
        <div class="topNav">
            <div class="logo">
                <img src="C:\Users\alexa\OneDrive\Desktop\Boolean 118\VITE\proj-html-vuejs\src\assets\images\author-logo-round-200x205.png" alt="Logo Avada">
            </div>
            <ul>
                <li>Home</li>
                <li>About Me</li>
                <li>Testimonials</li>
                <li>MyBlog</li>
                <li>Meetups</li>
                <li>Shop</li>
                <li>Contact Me</li>
                <li><i class="fa-solid fa-cart-shopping"></i></li>
            </ul>

        </div>

        <div class="introduction">
            <h1>Damon Vaughn</h1>
            <h2>
                Best-Selling author and the most influential public
                intellectual in the western world right now.
            </h2>

            <h4>- The New York Times</h4>

            <div class="arrow_container">
                <i class="fa-solid fa-arrow-left"></i>
                <i class="fa-solid fa-arrow-right"></i>
            </div>
        </div>

        <div class="latestBook">

            <div class="miniContainer">
                <img src="" alt="">
                <div class="lbRelease">
                    <h3>
                        Latest Book Release
                    </h3>
                    <h4>
                        d. vaughn autobiography
                    </h4>
                    <p>
                        Lorem, ipsum dolor sit amet consectetur adipisicing elit.
                    </p>
                </div>
            </div>

            <div>
                <button class="buy angles">
                    <i class="fa-brands fa-amazon"></i>
                     Buy On Amazon
                </button>
                <button class="buy angles_2">
                    <i class="fa-brands fa-apple"></i>
                    Buy On AppStore
                </button>
            </div>
            
        </div>

        

    </div>
  
</template>

<style lang="scss">

    .headerContainer * {
        color: white;
    }

    .headerContainer {

        
        
        position: relative;
        height: 534px;
        background-image: url("../assets/images/hero-07-2x.jpg");
        background-size: cover;
        background-position: center;
        overflow: hidden;

        &::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: linear-gradient(to bottom, transparent, #000000);
            pointer-events: none;
        }
        


        .topNav {
            position: relative;
            display: flex;
            flex-direction: row;
            justify-content: space-between;
            margin-left: 110px;
            margin-right: 96px;

            .logo {
                img {
                    margin-top: 18px;
                    position: relative;
                    height: 88px;
                    width: 88px;
                    object-fit: cover;
                    cursor: pointer;
                }
            }

            ul {
                position: relative;
                display: flex;
                gap: 30px;
                
                li {
                    list-style-type: none;
                    cursor: pointer;
                    padding-top: 31px;
                }
            }
        }

        .introduction {
            position: absolute;
            top: 157px;
            left: 157px;
            max-width: 467px;

            h1 {
                color: #f4b429;
                font-size: 38px;
                margin-bottom: 32px;
            }

            h2 {
                font-size: 20px;
            }

            h4 {
                color: #a3a3a3;
                font-style: italic;
                margin-top: 31px;
                margin-bottom: 30px;
            }

            .arrow_container {
                display: flex;
                gap: 1px;
            }

            .arrow_container i {
                background-color: #0a0a0a;
                padding: 12px;
                cursor: pointer;
            }

            .arrow_container i:first-of-type {
                border-radius: 6px 0 0 6px;
            }

            .arrow_container i:last-of-type {
                border-radius: 0 6px 6px 0;
            }
        }

        .latestBook {
            display: flex;
            flex-direction: column;
            align-items: center;
            height: 267px;
            width: 459px;
            background-color: white;
            position: absolute;
            bottom: 0;
            right: 0;

            .miniContainer {
                display: flex;
                gap: 16px;
                margin-left: 47px;
                margin-right: 47px;
                margin-top: 36px;

                img {
                    flex: 50%;
                    height: 137px;
                    width: 167px;
                    border: 1px solid black;
                }

                .lbRelease {
                    flex: 50%;
                }

                .lbRelease h3 , .lbRelease p {
                    color: black;
                }

                .lbRelease h4 {
                    color: #f4b429;
                    text-transform: uppercase;
                }
            }

            .buy {
                cursor: pointer;
                background-color: white;
                color: black;
                border: 1px solid #49a987;
                padding: 12px 42px;
                margin-top: 28px;

                i {
                    margin-right: 6px;
                }
            }

            .angles {
                border-radius: 10px 0 0 10px;
            }

            .angles_2 {
                border-radius: 0 10px 10px 0;
            }

            
        }
        
    }

</style>