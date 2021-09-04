<header class="header container-fluid">
    <div class="d-flex">
        <a href="https://portal.reud.net/" class="text-logo" >
            reud.net
        </a>
        <a href="https://portal.reud.net/" class="d-flex delivery-info">
            <div class="geo-alt-icon-centering">
                <GeoAlt  class="geo-alt" style="fill: white;"/>
            </div>
            <div class="delivery-info-data">
                <span class="delivery-info-name"> お届け先: ~~さん</span>
                <span class="delivery-info-address"> hoge市 999-9999 </span>
            </div>
        </a>
    </div>
</header>

<script>
    import GeoAlt from "svelte-bootstrap-icons/lib/GeoAlt"
</script>

<style>
.header {
    background-color: #131921;
}

.text-logo {
    font-size: 30px;
    color: white;
    text-decoration:none;
    margin: 10px;
}

.delivery-info {
    margin-left: 20px;
    color: white;
}

.delivery-info-data {
    display: flex;
    flex-direction: column;
    margin-left: 4px;
}

.delivery-info-name {
    font-size: 12px;
    color: #cccccc;
    margin-top: 12px;

}

.delivery-info-address {
    font-size: 14px;
    line-height: 15px;
    font-weight: 700;
}

a {
    text-decoration: none;
}

.geo-alt-icon-centering {
    display: grid;
    place-items: center;
}


a:hover.text-logo a:visited.text-logo {
    color: white;
}

a:hover.geo-alt a:visited.geo-alt {
    color: white;
    text-decoration:none;
    font-size: 30px;
}

</style>