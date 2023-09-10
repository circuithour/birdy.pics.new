<div class="header">
    <h1>birdy.pics</h1>
</div>
<div id="topheading">
    <h2>Circuit Hour</h2>
</div>
<h3>@daisybushbird</h3>
<svg
    xmlns="http://www.w3.org/2000/svg"
    width="24"
    height="24"
    viewBox="0 0 24 24"
    ><path
        d="M24 4.557c-.883.392-1.832.656-2.828.775 1.017-.609 1.798-1.574 2.165-2.724-.951.564-2.005.974-3.127 1.195-.897-.957-2.178-1.555-3.594-1.555-3.179 0-5.515 2.966-4.797 6.045-4.091-.205-7.719-2.165-10.148-5.144-1.29 2.213-.669 5.108 1.523 6.574-.806-.026-1.566-.247-2.229-.616-.054 2.281 1.581 4.415 3.949 4.89-.693.188-1.452.232-2.224.084.626 1.956 2.444 3.379 4.6 3.419-2.07 1.623-4.678 2.348-7.29 2.04 2.179 1.397 4.768 2.212 7.548 2.212 9.142 0 14.307-7.721 13.995-14.646.962-.695 1.797-1.562 2.457-2.549z"
    /></svg
>
<svg
    xmlns="http://www.w3.org/2000/svg"
    width="24"
    height="24"
    viewBox="0 0 24 24"
    ><path
        d="M7 17.939h-1v-8.068c.308-.231.639-.429 1-.566v8.634zm3 0h1v-9.224c-.229.265-.443.548-.621.857l-.379-.184v8.551zm-2 0h1v-8.848c-.508-.079-.623-.05-1-.01v8.858zm-4 0h1v-7.02c-.312.458-.555.971-.692 1.535l-.308-.182v5.667zm-3-5.25c-.606.547-1 1.354-1 2.268 0 .914.394 1.721 1 2.268v-4.536zm18.879-.671c-.204-2.837-2.404-5.079-5.117-5.079-1.022 0-1.964.328-2.762.877v10.123h9.089c1.607 0 2.911-1.393 2.911-3.106 0-2.233-2.168-3.772-4.121-2.815zm-16.879-.027c-.302-.024-.526-.03-1 .122v5.689c.446.143.636.138 1 .138v-5.949z"
    /></svg
>
<svg
    xmlns="http://www.w3.org/2000/svg"
    width="24"
    height="24"
    viewBox="0 0 24 24"
    ><path
        d="M12 12.713l-11.985-9.713h23.971l-11.986 9.713zm-5.425-1.822l-6.575-5.329v12.501l6.575-7.172zm10.85 0l6.575 7.172v-12.501l-6.575 5.329zm-1.557 1.261l-3.868 3.135-3.868-3.135-8.11 8.848h23.956l-8.11-8.848z"
    /></svg
>
<svg
    clip-rule="evenodd"
    fill-rule="evenodd"
    stroke-linejoin="round"
    stroke-miterlimit="2"
    width="24"
    height="24"
    viewBox="0 0 24 24"
    xmlns="http://www.w3.org/2000/svg"
    ><path
        d="m16.843 10.211c.108-.141.157-.3.157-.456 0-.389-.306-.755-.749-.755h-8.501c-.445 0-.75.367-.75.755 0 .157.05.316.159.457 1.203 1.554 3.252 4.199 4.258 5.498.142.184.36.29.592.29.23 0 .449-.107.591-.291 1.002-1.299 3.044-3.945 4.243-5.498z"
    /></svg
>

<style>
    @import url("https://fonts.googleapis.com/css2?family=Inter&family=Libre+Baskerville&family=Playfair+Display:wght@600&family=Prompt&display=swap");

    @font-face {
        font-family: "Helvetica 93 Black Extended";
        src: url("../lib/Helvetica 93 Black Extended.otf");
    }

    * {
        color: snow;
    }

    :root {
        --bgHue: 140;
        --bgSaturation: 50%;
        --bgLightness: 15%;
        --bgColor: hsl(var(--bgHue), var(--bgSaturation), var(--bgLightness));
        --bgLightenOne: hsl(
            var(--bgHue),
            calc(var(--bgSaturation) + 5%),
            calc(var(--bgLightness) + 5%)
        );
        --bgDarkenOne: hsl(
            var(--bgHue),
            calc(var(--bgSaturation) - 10%),
            calc(var(--bgLightness) - 5%)
        );
        --bgLightenTwo: hsl(
            var(--bgHue),
            calc(var(--bgSaturation) + 5%),
            calc(var(--bgLightness) + 10%)
        );
        --bgDarkenTwo: hsl(
            var(--bgHue),
            calc(var(--bgSaturation) - 0%),
            calc(var(--bgLightness) - 10%)
        );
    }

    h1 {
        font-family: "Helvetica 93 Black Extended", sans-serif;
        margin: auto 1rem;
        padding: 0;
        user-select: none;
        cursor: pointer;
    }

    h2 {
        font-family: "Prompt", sans-serif;
        margin: 0;
        padding: 0;
    }

    h3 {
        font-family: "Playfair Display", serif;
        margin: 0;
        padding: 0;
    }

    .header {
        display: flex;
        position: sticky;
        top: 0;
        height: 55px;
        background-color: var(--bgDarkenOne);
    }

    .header::after {
        content: "";
        position: absolute;
        bottom: 0;
        left: 0;
        right: 0;
        height: 1px;
        background-image: linear-gradient(
            to right,
            var(--bgLightenOne),
            var(--bgLightenTwo),
            var(--bgLightenOne)
        );
    }

    #logo {
        position: absolute;
        left: -0.5rem;
        top: 0.5rem;
        width: 50px;
        height: 50px;
    }

    .container {
        display: flex;
        flex-direction: row;
        height: 200px;
    }

    .section1 {
        flex: auto;
        height: auto;
        background-color: var(--bgLightenOne);
    }

    .section2 {
        flex: auto;
        height: auto;
        background-color: var(--bgLightenTwo);
    }

    .section3 {
        flex: auto;
        height: auto;
        background-color: var(--bgDarkenOne);
    }

    .section4 {
        flex: auto;
        height: auto;
        background-color: var(--bgDarkenTwo);
    }
</style>
