<script>
export default {
    Main: "Main"
}
</script>

<template>
    <main>
        <section id="section-content">
            <!-- contenitore  -->
            <div>
                <strong>
                    -- content goes there --
                </strong>
            </div>
        </section>
        <section id="section-utility">
            <div>
                <ul><!--list acon dentro utility-->
                    <li>
                        <a href="#"><img src="../assets/img/buy-comics-digital-comics.png" alt="#"></a>
                        <span>DIGITAL COMICS</span>
                    </li>
                    <li>
                        <a href="#"><img src="../assets/img/buy-comics-merchandise.png" alt="#"></a>
                        <span>DC MERCHANDISE</span>
                    </li>
                    <li>
                        <a href="#"><img src="../assets/img/buy-comics-subscriptions.png" alt="#"></a>
                        <span>SUBSCRIPTION</span>
                    </li>
                    <li>
                        <a href="#"><img src="../assets/img/buy-comics-shop-locator.png" alt="#"></a>
                        <span>COMIC SHOP LOCATOR</span>
                    </li>
                    <li>
                        <a href="#"><img src="../assets/img/buy-dc-power-visa.svg" alt="#"></a>
                        <span>DC POWER VISA</span>
                    </li>
                </ul>
            </div>
        </section>
    </main>
</template>

<style scoped lang="scss">
@use '../style/general.scss' as *;
@use '../style/partials/variable' as *;

// sezione dove c'è il contenuto 
#section-content {
    background-color: black;
    color: white;
    padding: 30px 0;

    div {
        width: $width_blocchi ;
        margin: $margin_blocchi;
    }
}

// sezione condentro l'utility 
#section-utility {

    background-color: #0282f9;
    padding: 30px 0;
    

    div {
        width: $width_blocchi ;
        margin: $margin_blocchi;
        text-align: center;
        // caratteristiche di ul e tag al suo interno 
        ul{
            display:$display_flex;
            justify-content: center;
            li{
                display:$display_flex;
                align-items:$specific_align ;
                margin: 0 5px;
                img{
                    width: 50px;
                    margin-right: 5px;
                }
            }
        }
    }
}
</style>