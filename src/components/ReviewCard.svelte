<script>
    import StarRating from "./StarRating.svelte";
</script>

<div class="card card-self">
    <span class="card-title card-title-self">
        <img src="images/toilet.png" alt="background image" />
        <span class="clickable"> reud.net カスタマー </span>
        <span class="mini"> 2021/09/18に日本でレビュー済み </span>
    </span>
    <span class="card-body">
        <div class="d-flex">
            <StarRating />
            <span style="color: white; margin-left: 10px; font-size: 20px; font-weight: 700;"> 楽しみ～ </span>
        </div>
        <span style="color: white; font-size: 16px;">
            楽しみなので星5
        </span>
        <br>
        <span class="mini"> 2020人のお客様がこれが役に立ったと考えています </span>
        <br>
        <button type="button" class="btn btn-yakunitatta">役に立った</button>
        <button class="clickable btn"> 不正行為の報告 </button>
    </span>
</div>

<style>
    .btn-yakunitatta {
        background-color: #425265;
        color: white;
        margin-top: 5px;
        height: 40px;
        width: 100px;
    }
    img {
        width: 32px;
        border-radius: 50%;
    }
    .card-title-self {
        margin: 5px;
    }
    .card-self {
        background-color: #1b2530;
    }
    .clickable {
        color: #79b8f3;
    }
    .mini {
        color: #8197a4;
    }
</style>