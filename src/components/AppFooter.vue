<template>
    <footer>
        <div class="container">
            <button>
                Sign-up now
            </button>

            <div class="social">
                <h2>Follow Us</h2>
                <ul>
                    <li v-for="(item, index) in socialLinks" :key="index">
                        <img :src="require(`../assets/footer-${item.name}.png`)" alt="">
                    </li>
                </ul>
            </div>
        </div>
    </footer>
</template>

<script>
export default {
    name: "AppFooter",
    data: function() {
        return {
            socialLinks: [
                {
                    name: "facebook",
                    url: "#",
                },
                {
                    name: "twitter",
                    url: "#",
                },
                {
                    name: "youtube",
                    url: "#",
                },
                {
                    name: "pinterest",
                    url: "#",
                },
                {
                    name: "periscope",
                    url: "#",
                },
            ]
        }
    }
}
</script>

<style lang="scss" scoped>
@import "../style/variables.scss";

    footer {
        width: 100%;
        height: 150px;
        background-color: $darkgray-color;
        // background-color: $darkgray-color;

        .container {
            height: 100%;
            display: flex;
            justify-content: space-between;
            align-items: center;

            button {
                background-color: $darkgray-color;
                padding: 1rem;
                border: 4px solid $blue-color;
                color: white;
                text-transform: uppercase;
                font-size: 1.7rem;
                cursor: pointer;
            };

            .social {
                display: flex;
                align-items: center;

                h2 {
                    color: white;
                    text-transform: uppercase;
                    font-size: 1.7rem;
                    padding-right: 2rem;
                }

                ul {
                    display: flex;

                    li {
                        cursor: pointer;
                        margin-left: 1.7rem;
                        
                        img {
                            width: 3.5rem;
                        }
                    }
                }
            }
        }
    }
</style>