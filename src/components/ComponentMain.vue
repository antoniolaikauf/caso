<script>
export default {
    Main: "Main"
}
</script>

<template>
    <main>
        <section id="section-content">
            <div>
                <strong>
                    -- content goes there --
                </strong>
            </div>
        </section>
        <section id="section-utility">
            <div>
                <ul>
                    <li>
                        <a href="#"><img src="../assets/img/buy-comics-digital-comics.png" alt=""></a>
                        <span>testo</span>
                    </li>
                    <li>
                        <a href="#"><img src="../assets/img/buy-comics-digital-comics.png" alt=""></a>
                        <span>testo</span>
                    </li>
                    <li>
                        <a href="#"><img src="../assets/img/buy-comics-digital-comics.png" alt=""></a>
                        <span>testo</span>
                    </li>
                    <li>
                        <a href="#"><img src="../assets/img/buy-comics-digital-comics.png" alt=""></a>
                        <span>testo</span>
                    </li>
                    <li>
                        <a href="#"><img src="../assets/img/buy-comics-digital-comics.png" alt=""></a>
                        <span>testo</span>
                    </li>
                </ul>
            </div>
        </section>
    </main>
</template>

<style scoped lang="scss">
@use '../style/general.scss' as *;
@use '../style/partials/variable' as *;


#section-content {
    background-color: black;
    color: white;
    padding: 30px 0;

    div {
        width: $width_blocchi ;
        margin: $margin_blocchi;
    }
}

#section-utility {

    background-color: #0282f9;
    padding: 30px 0;
    

    div {
        width: $width_blocchi ;
        margin: $margin_blocchi;
        text-align: center;

        ul{
            display:$display_flex;
            justify-content: center;
            li{
                display:$display_flex;
                align-items:$specific_align ;
                img{
                    width: 50px;
                }
            }
        }
    }
}
</style>