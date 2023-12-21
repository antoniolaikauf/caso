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
        <section>
            <div>
                
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
</style>