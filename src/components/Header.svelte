<header class="header container-fluid">
    <div class="row">
        <a href="https://portal.reud.net/" class="text-logo col-1" >
            reud.net
        </a>
        <a href="https://portal.reud.net/" class="d-flex delivery-info col-1">
            <div class="geo-alt-icon-centering">
                <GeoAlt  class="geo-alt" style="fill: white;"/>
            </div>
            <div class="delivery-info-data">
                <span class="delivery-info-name"> お届け先: ~~さん</span>
                <span class="delivery-info-address"> hoge市 999-9999 </span>
            </div>
        </a>
        <div class=" search-window col-5">
            <div class="row">
                <select class=" col-2" id="exampleFormControlSelect1">
                    <option>すべて</option>
                    <option>DVD</option>
                    <option>ゲーム</option>
                    <option>Audio</option>
                    <option>Products</option>
                </select>
                <input type="email" class=" col-8" id="exampleFormControlInput1" placeholder="ここに何を入力しても意味なんて・・・">
                <button type="button" class="btn btn-warning col-1">
                    <Search />
                </button>
            </div>
        </div>
        <div class="flag-icon-centering col-1">
            <Flag  style="fill: white;"/>
        </div>
        <div class="col-1 reud-column">
            <span class="username"> Guest さん</span>
            <span class="account-and-list">
                アカウント&リスト
            </span>
        </div>
        <div class="col-1 reud-column">
            <span class="username"> 返品もこちら </span>
            <span class="account-and-list">
                注文履歴
            </span>
        </div>
        <div class="flag-icon-centering col-1" >
            <Cart  style="fill: white;"/>
            <span style="color: white">
                カート
            </span>
        </div>
    </div>
</header>

<script>
    import GeoAlt from "svelte-bootstrap-icons/lib/GeoAlt"
    import Flag from "svelte-bootstrap-icons/lib/Flag"
    import Search from "svelte-bootstrap-icons/lib/Search"
    import Cart from "svelte-bootstrap-icons/lib/Cart"
</script>

<style>

.reud-column {
    display: flex;
    flex-direction: column;
}

.search-window {
    margin-top: 10px;
    margin-left: 30px;
}

.header {
    background-color: #131921;
}

.text-logo {
    font-size: 30px;
    color: white;
    text-decoration:none;
    margin: 10px;
}

.username {
    font-size: 12px;
    color: white;
    margin-top: 12px;
}

.account-and-list {
    font-size: 14px;
    line-height: 15px;
    font-weight: 700;
    color: white;
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

.flag-icon-centering {
    margin-top: 15px;
    place-items: center;
    margin-left: 0;
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