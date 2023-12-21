<script>
export default {
    Footer: "Footer"
}
</script>

<template>
    <footer>
        <section id="section-informazioni">
            <div>
                <ul>
                    <li>
                        <a href="#">
                            <h3>dc comic</h3>
                        </a>
                    </li>
                    <li>
                        <a href="#"> testo</a>
                    </li>
                    <li>
                        <a href="#"> testo</a>
                    </li>
                    <li>
                        <a href="#"> testo</a>
                    </li>
                    <li>
                        <a href="#"> testo</a>
                    </li>
                    <li>
                        <a href="#"> testo</a>
                    </li>
                    <li>
                        <a href="#"> testo</a>
                    </li>
                    <li>
                        <a href="#">
                            <h3>dc comic</h3>
                        </a>
                    </li>
                    <li>
                        <a href="#"> testo</a>
                    </li>
                    <li>
                        <a href="#"> testo</a>
                    </li>
                </ul>
                <ul>
                    <li>
                        <a href="#">
                            <h3>dc comic</h3>
                        </a>
                    </li>
                    <li>
                        <a href="#"> testo</a>
                    </li>
                    <li>
                        <a href="#"> testo</a>
                    </li>
                    <li>
                        <a href="#"> testo</a>
                    </li>
                    <li>
                        <a href="#"> testo</a>
                    </li>
                    <li>
                        <a href="#"> testo</a>
                    </li>
                    <li>
                        <a href="#"> testo</a>
                    </li>
                    <li>
                        <a href="#"> testo</a>
                    </li>
                    <li>
                        <a href="#"> testo</a>
                    </li>
                    <li>
                        <a href="#"> testo</a>
                    </li>
                    <li>
                        <a href="#"> testo</a>
                    </li>
                </ul>
                <ul>
                    <li>
                        <a href="#">
                            <h3>dc comic</h3>
                        </a>
                    </li>
                    <li>
                        <a href="#"> testo</a>
                    </li>
                    <li>
                        <a href="#"> testo</a>
                    </li>
                    <li>
                        <a href="#"> testo</a>
                    </li>
                    <li>
                        <a href="#"> testo</a>
                    </li>
                </ul>
            </div>
        </section>
        <section id="registrazione">
            <div>
                <div>
                    <a href="">sign-up now</a>
                </div>
                <ul>
                    <li><a href="">follow us</a></li>
                    <li><img src="../assets/img/footer-facebook.png" alt=""></li>
                    <li><img src="../assets/img/footer-facebook.png" alt=""></li>
                    <li><img src="../assets/img/footer-facebook.png" alt=""></li>
                    <li><img src="../assets/img/footer-facebook.png" alt=""></li>
                    <li><img src="../assets/img/footer-facebook.png" alt=""></li>
                </ul>
            </div>
        </section>
    </footer>
</template>

<style scoped lang="scss">
@use '../style/general.scss' as *;
@use '../style/partials/variable' as *;

#section-informazioni {
    background-image: url(../assets/img/footer-bg.jpg);
    padding: 20px 0;
    background-size: contain;

    div {
        width: $width_blocchi ;
        margin: $margin_blocchi;
        display: $display_flex ;

        ul {
            margin-right: 10px;
        }
    }
}

#registrazione {
    padding: 20px;
    background-color: #303030;

    div {
        width: $width_blocchi ;
        margin: $margin_blocchi;
        display: $display_flex ;
        ul{
            display: $display_flex ;
        }
    }
}
</style>