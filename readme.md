Blue line code tests

html
        <!--BLUE LINE START-->
        <div class="line">
            <img class="blue-line" src="svg/blue line (with spaces).svg" alt="blue-line">
        </div>
        <!--BLUE LINE END-->

        <section class="container1">
            <h1>
                <span class="h1">BRANDING LIKE</span>
                <br>
                <span class="h1">NEVER BEFORE</span>
            </h1>
        </section>

css
/* BLUE LINE START */
.line {
    display: flex;
    justify-content: center; /* for at centrere den */
}

.blue-line {
    position: absolute; /* placere den et fast sted på siden */
    margin-top: -23rem; /* hvor den kommer ind/starter fra toppen - idk det her er bare guess work*/
    width: 90rem; /* størrelse på linjen */
}
/* BLUE LINE END */