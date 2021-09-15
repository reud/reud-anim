<div class="star-ratings-css">
    <div class="star-ratings-css-top" style="width: 100%"><span>★</span><span>★</span><span>★</span><span>★</span><span>★</span></div>
    <div class="star-ratings-css-bottom"><span>★</span><span>★</span><span>★</span><span>★</span><span>★</span></div>
</div>
<style>
    @import url(http://fonts.googleapis.com/css?family=Open+Sans:400,600,700);
    .star-ratings-css {
        unicode-bidi: bidi-override;
        color: #c5c5c5;
        font-size: 25px;
        position: relative;
        text-shadow: 0px 1px 0 #a2a2a2;
        bottom: 5px;

    }
    .star-ratings-css-top {
        color: #e7711b;
        padding: 0;
        position: absolute;
        z-index: 1;
        display: block;
        top: 0;
        left: 0;
        overflow: hidden;
    }
    .star-ratings-css-bottom {
        padding: 0;
        display: block;
        z-index: 0;
    }
    body {
        margin: 50px;
        text-align: center;
        font-family: 'Open Sans', sans-serif;
        background: #f2fbff;
    }
    em {
        font-style: italic;
    }
    span {
        place-items: center;
        margin-bottom: 10px;
    }

</style>