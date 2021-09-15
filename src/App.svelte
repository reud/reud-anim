<script lang="ts">
	import Share from "svelte-bootstrap-icons/lib/Share"
	import Header from "./components/Header.svelte";
	import StarRating from "./components/StarRating.svelte";
	import Pencil from "svelte-bootstrap-icons/lib/Pencil";
	import Lightbulb from "svelte-bootstrap-icons/lib/Lightbulb";
	import { fade } from 'svelte/transition';
	import TabView from "./Views/TabView.svelte";
	export let name: string;
</script>

<main>
	<Header />
	<div transition:fade="{{delay: 250}}" class="container-fluid" >
		<h1 class="title">
			reud the animation
		</h1>
		<div class="d-flex">
			<span  style="color: #768B98; font-size: 20px; margin-right: 20px">シーズン1</span>
			<StarRating />
			<span  style="color: #79b8f3; font-size: 20px; margin-left: 10px">(1)</span>
			<span  style="color: #768B98; font-size: 14px; margin-left: 20px; margin-top: 5px;">2021</span>
		</div>
		<div class="summary-text">
			どこにでも普通の青年が居た。様々な人に「reud」と呼ばれる少年はどこにでもある、平穏な日々を過ごしていた。
			ある日青年に手紙と共に一枚のお面が届く。手紙を見るとそのお面を付けて仮面舞踏会に来ないかという誘いであった。
			日常に嫌気が指していたreudは仮面舞踏会に出席することになる。その仮面舞踏会は奇妙であった。
		</div>
		<div>
			<span  style="color: #768B98; font-size: 20px; margin-top: 120px; bottom: 20px;">出演 reud</span>
			<br>
			<span  style="color: #79b8f3; font-weight: 700; font-size: 50px; margin-right: 20px; bottom: 20px;">prime</span>
			<span  style="color: white; font-weight: 700; font-size: 20px; margin-right: 20px; bottom: 20px;">シーズン1はプライム会員特典です</span>
		</div>
		<div class=" container-fluid">
			<div class="row">
				<span class="col-5" style="color: #8197a4; font-size: 16px; margin-top: 30px">このサイトはreudがCSSの練習用に作成したジョークサイトです。実際にはアニメ化されていません。</span>
				<div class="bi-text-right container-fluid col-6" style="display: block;">
					<button type="button" class="btn btn-link action-button">
						<Lightbulb />
						フィードバック
					</button>
					<button type="button" class="btn btn-link action-button">
						<Pencil style="fill: white" />
						レビューを書く
					</button>
					<button type="button" class="btn btn-link action-button" >
						<Share style="fill: white"/>
						<span>共有</span>
					</button>
				</div>
			</div>
		</div>
		<TabView />
	</div>
</main>

<style>
	a:hover {
		color: white;
		text-decoration: none;
		margin-top: 15px;
		font-size: 20px;
	}

	.action-button {
		color: white;
		text-decoration: none;
		margin-top: 15px;
		font-size: 20px;
		float: right;
	}

	.summary-text {
		color: white;
		font-size: 18px;
		margin-top: 20px;
		width: 800px;
	}
	body {
	}
	main {
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
		background: #0F171E;
		width: 100vw;
		height: 150vh;
	}
	.title {
		margin-top: 60px;
	}
	h1 {
		color: white;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>