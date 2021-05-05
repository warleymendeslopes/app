<script>
	//export let name;
</script>

<main>
	<section class="banner-inicial">
		<!--<h1>cardapio de {name}!</h1> -->
	</section>
	<div class="cardapio">
		<h2>MENU</h2>
		<span class="divider">★</span>
	</div>
	<ul>
		<li>
			<span>Lorem ipsum</span>
			<span class="dotted" />
			<span class="price">R$30,00</span>
		</li>
		<li>
			<span>Aliquam</span>
			<span class="dotted" />
			<span class="price">R$30,00</span>
		</li>
		<li>
			<span>Vestibulum</span>
			<span class="dotted" />
			<span class="price">R$30,00</span>
		</li>
		<li>
			<span>Lorem</span>
			<span class="dotted" />
			<span class="price">R$30,00</span>
		</li>
		<li>
			<span>Aliquam tincidunt</span>
			<span class="dotted" />
			<span class="price">R$30,00</span>
		</li>
		<li>
			<span>Vestibulum auct</span>
			<span class="dotted" />
			<span class="price">R$30,00</span>
		</li>
		<li>
			<span>Lorem ipsum</span>
			<span class="dotted" />
			<span class="price">R$30,00</span>
		</li>
		<li>
			<span>Aliquam tinci</span>
			<span class="dotted" />
			<span class="price">R$30,00</span>
		</li>
		<li>
			<span>Vestibulum</span>
			<span class="dotted" />
			<span class="price">R$30,00</span>
		</li>
		<li>
			<span>Lorem ipsum</span>
			<span class="dotted" />
			<span class="price">R$30,00</span>
		</li>
		<li>
			<span>Aliquam</span>
			<span class="dotted" />
			<span class="price">R$30,00</span>
		</li>
		<li>
			<span>Vestibulum</span>
			<span class="dotted" />
			<span class="price">R$30,00</span>
		</li>
		<li>
			<span>Lorem</span>
			<span class="dotted" />
			<span class="price">R$30,00</span>
		</li>
		<li>
			<span>Aliquam tincidunt</span>
			<span class="dotted" />
			<span class="price">R$30,00</span>
		</li>
		<li>
			<span>Vestibulum auct</span>
			<span class="dotted" />
			<span class="price">R$30,00</span>
		</li>
		<li>
			<span>Lorem ipsum</span>
			<span class="dotted" />
			<span class="price">R$30,00</span>
		</li>
		<li>
			<span>Aliquam tinci</span>
			<span class="dotted" />
			<span class="price">R$30,00</span>
		</li>
		<li>
			<span>Vestibulum</span>
			<span class="dotted" />
			<span class="price">R$90,00</span>
		</li>
	</ul>
</main>

<style>
	.banner-inicial {
		width: 100%;
		height: 96vh;
		background: red;
		padding: 1px;
		background-image: url(/images/banners/banner1.webp);
		background-size: 100% 39%;
		background-position: 0% 101%;
		background-repeat: no-repeat;
	}
	div.cardapio {
		position: relative;
		margin-top: 3px;
		border: 1px solid #777;
		background: rgba(255, 255, 255, 0);
		width: 100%;
		z-index: 1000;
		text-align: center;
		transform: translateX(0.1em) translateY(-0.25em);
	}
	div.cardapio:before {
		content: "";
		position: absolute;
		top: -1px;
		left: -1px;
		right: -1px;
		bottom: -1px;
		z-index: 999;
		border-left: 1px solid #777;
		border-bottom: 1px solid #777;
		transform: translateX(-0.25em) translateY(0.25em);
	}

	h2 {
		margin: 0;
		font-size: 3em;
		text-shadow: -0.05em 0.05em 0 white, -0.08em 0.08em 0 #777;
		line-height: 2;
		letter-spacing: 0.1em;
	}

	span.divider {
		position: relative;
		display: inline-block;
		font-size: 2em;
		color: #777;
		text-shadow: -0.05em 0.05em 0 white, -0.08em 0.08em 0 #777;
		line-height: 1;
		width: 100%;
		margin-bottom: 30px;
	}
	span.divider:after,
	span.divider:before {
		content: "";
		position: absolute;
		top: 0.5em;
		height: 0.1em;
		background: #777;
		box-shadow: 0 0.05em 0 white, 0 0.1em 0 #777;
	}
	span.divider:after {
		left: 60%;
		right: 0;
	}
	span.divider:before {
		left: 0;
		right: 60%;
	}

	ul {
		margin: 0;
		padding: 0;
		text-align: left;
	}
	ul li {
		display: flex;
		justify-content: space-between;
		align-items: baseline;
		list-style: none;
		line-height: 1.8;
		font-size: 20px;
		color: #f7f7f7;
		margin-right: 22px;
		margin-left: 22px;
	}

	ul span.price {
		float: right;
	}
	ul span.dotted {
		height: 0.15em;
		background-image: linear-gradient(to left, #777 50%, white 50%);
		background-size: 0.15em;
		background-repeat: repeat-x;
		flex-grow: 2;
		margin: 0 0.3em;
	}
</style>
