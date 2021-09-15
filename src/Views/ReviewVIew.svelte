<script>
    import StarRating from "../components/StarRating.svelte";
</script>

<div>
    <div class="container-fluid">
        <div class="row">
            <div class="col-4">
                <h4> レビュー </h4>
                <div class="d-flex">
                    <StarRating />
                    <h5 style="margin-left: 10px; margin-top: 5px"> 5つ星のうち 5.0 </h5>
                </div>
                <span>1件のグローバルレーティング</span>
                <div class="d-flex">
                    <span style="color:#8197a4;">星5つ</span>
                    <div class="progress" style="width: 200px; margin-top: 5px; margin-left: 20px">
                        <div class="progress-bar" role="progressbar" style="width: 100%" aria-valuenow="100" aria-valuemin="0" aria-valuemax="100"></div>
                    </div>
                    <span class="percent-tile-text"> 100%</span>
                </div>
                <div class="d-flex">
                    <span style="color:#8197a4;">星4つ</span>
                    <div class="progress" style="width: 200px; margin-top: 5px; margin-left: 20px">
                        <div class="progress-bar" role="progressbar" style="width: 0%" aria-valuenow="100" aria-valuemin="0" aria-valuemax="100"></div>
                    </div>
                    <span class="percent-tile-text"> 0%</span>
                </div>
                <div class="d-flex">
                    <span style="color:#8197a4;">星3つ</span>
                    <div class="progress" style="width: 200px; margin-top: 5px; margin-left: 20px">
                        <div class="progress-bar" role="progressbar" style="width: 0%" aria-valuenow="100" aria-valuemin="0" aria-valuemax="100"></div>
                    </div>
                    <span class="percent-tile-text"> 0%</span>
                </div>
                <div class="d-flex">
                    <span style="color:#8197a4;">星2つ</span>
                    <div class="progress" style="width: 200px; margin-top: 5px; margin-left: 20px">
                        <div class="progress-bar" role="progressbar" style="width: 0%" aria-valuenow="100" aria-valuemin="0" aria-valuemax="100"></div>
                    </div>
                    <span class="percent-tile-text"> 0%</span>
                </div>
                <div class="d-flex">
                    <span style="color:#8197a4;">星1つ</span>
                    <div class="progress" style="width: 200px; margin-top: 5px; margin-left: 20px">
                        <div class="progress-bar" role="progressbar" style="width: 0%" aria-valuenow="100" aria-valuemin="0" aria-valuemax="100"></div>
                    </div>
                    <span class="percent-tile-text"> 0%</span>
                </div>
            </div>
            <div class="col-5">
                <div class="d-flex">
                    <span>並べ替え: </span>
                    <select class="form-select" aria-label="Default select example" style="width: 200px; margin-left: 20px">
                        <option selected>トップレビュー</option>
                        <option value="1">One</option>
                        <option value="2">Two</option>
                        <option value="3">Three</option>
                    </select>
                </div>
            </div>
        </div>
    </div>
</div>

<style>
    h4 {
        color: white;
    }
    h5 {
        color: white;
    }
    span {
        color: #8197a4;
    }
    .percent-tile-text {
        color:#8197a4;
        width: 50px;
        text-align: right;
    }
</style>