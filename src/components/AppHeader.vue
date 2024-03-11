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

        

    </div>
  
</template>

<style lang="scss">

    .headerContainer {
        height: 800px;
        background-image: url("C:\Users\alexa\OneDrive\Desktop\Boolean 118\VITE\proj-html-vuejs\src\assets\images\hero-07-2x.jpg");
        object-fit: cover;

        .topNav {
            display: flex;
            flex-direction: row;
            justify-content: space-between;
            margin-left: 164px;
            margin-right: 144px;

            .logo {
                img {
                    height: 132px;
                    width: 132px;
                    object-fit: cover;
                    cursor: pointer;
                }
            }

            ul {
                display: flex;
                gap: 44px;
                
                li {
                    list-style-type: none;
                    cursor: pointer;
                    padding-top: 46px;
                }
            }
        }
        
    }

</style>