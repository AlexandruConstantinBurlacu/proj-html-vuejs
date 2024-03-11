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
                <li>Carrello Shopping</li>
            </ul>

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
                        Lorem, ipsum dolor sit amet consectetur adipisicing elit. Nemo fugiat saepe commodi at, inventore non!
                    </p>
                </div>
            </div>

            <div>
                <div class="buy">
                    LOGO AMAZON Buy On Amazon
                </div>
                <div class="buy">
                    LOGO APPLE Buy On AppStore
                </div>
            </div>
            
        </div>

        

    </div>
  
</template>

<style lang="scss">

    .headerContainer {

        
        
        position: relative;
        height: 800px;
        background-image: url("../assets/images/hero-07-2x.jpg");
        background-size: cover;
        background-position: center;


        .topNav {
            position: relative;
            display: flex;
            flex-direction: row;
            justify-content: space-between;
            margin-left: 164px;
            margin-right: 144px;

            .logo {
                img {
                    margin-top: 26px;
                    position: relative;
                    height: 132px;
                    width: 132px;
                    object-fit: cover;
                    cursor: pointer;
                }
            }

            ul {
                position: relative;
                display: flex;
                gap: 44px;
                
                li {
                    list-style-type: none;
                    cursor: pointer;
                    padding-top: 46px;
                }
            }
        }

        .latestBook {
            height: 400px;
            width: 688px;
            background-color: white;
            position: absolute;
            bottom: 0;
            right: 0;

            .miniContainer {
                display: flex;
                gap: 24px;
                margin-left: 70px;
                margin-right: 70px;
                margin-top: 54px;

                img {
                height: 205px;
                width: 250px;
                border: 1px solid black;
                }

                .lbRelease h3 , .lbRelease p {
                    color: black;
                }

                .lbRelease h4 {
                    color: #f4b429;
                    text-transform: uppercase;
                }
            }

            
        }
        
    }

</style>