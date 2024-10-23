<script></script>

<template>
	<section class="main__product product">
		<ul class="product__details-product details-product">
			<li class="details-product__item">
				<a
					class="details-product__link details-product__link--current"
					href="#!"
				>
					<img
						src="/images/details-product-1.jpg"
						width="70"
						height="88"
						alt="Другой ракурс."
					/>
				</a>
			</li>
			<li class="details-product__item">
				<a class="details-product__link" href="#!">
					<img
						src="/images/details-product-2.jpg"
						width="70"
						height="88"
						alt="Другой ракурс."
					/>
				</a>
			</li>
			<li class="details-product__item">
				<a class="details-product__link" href="#!">
					<img
						src="/images/details-product-3.jpg"
						width="70"
						height="88"
						alt="Другой ракурс."
					/>
				</a>
			</li>
		</ul>
		<ul class="product__slider slider">
			<li class="slider__item slider__item--current">
				<picture>
					<source
						media="(min-width: 1440px)"
						width="518"
						height="693"
						srcset="/images/product-1-desktop.jpg"
					/>
					<img
						src="/images/product-1.jpg"
						width="375"
						height="617"
						alt="Product 1."
					/>
				</picture>
			</li>
			<li class="slider__item"><img src="#!" alt="Product 2." /></li>
			<li class="slider__item"><img src="#!" alt="Product 3." /></li>
			<li class="slider__item"><img src="#!" alt="Product 4." /></li>
			<li class="slider__item"><img src="#!" alt="Product 5." /></li>
		</ul>
		<div class="product__slider-controls slider-controls">
			<input
				class="slider-controls__control slider-controls__control--current"
				type="radio"
				name="slide"
				checked
			/>
			<input class="slider-controls__control" type="radio" name="slide" />
			<input class="slider-controls__control" type="radio" name="slide" />
			<input class="slider-controls__control" type="radio" name="slide" />
			<input class="slider-controls__control" type="radio" name="slide" />
		</div>
		<div class="product__info">
			<h1 class="product__title">Жакет удлиненный, белый</h1>
			<button class="product__favorite">
				<span class="visually-hidden">Добавить в закладки.</span>
			</button>
		</div>
		<p class="product__price">8900 RUB</p>
		<div class="product__sizes sizes">
			<p class="sizes__title">Размеры</p>
			<ul class="sizes__list">
				<li class="sizes__item item">
					<button class="item__btn" type="button">XS</button>
					<span class="item__description">мало</span>
				</li>
				<li class="sizes__item">
					<button class="item__btn" type="button">S</button>
				</li>
				<li class="sizes__item">
					<button class="item__btn item__btn--disabled" type="button">M</button>
					<span class="item__description item__description--disabled"
						>подписка</span
					>
				</li>
			</ul>
		</div>
		<div class="product__colors colors">
			<p class="colors__title">Цвет: белый</p>
			<div class="colors__variants">
				<div class="button-wrap button-wrap--current">
					<button class="color__variant color__variant--1" type="button">
						<span class="visually-hidden">Белый.</span>
					</button>
				</div>
				<div class="button-wrap">
					<button class="color__variant color__variant--2" type="button">
						<span class="visually-hidden">Черный.</span>
					</button>
				</div>
				<div class="button-wrap">
					<button class="color__variant color__variant--3" type="button">
						<span class="visually-hidden">Бежевый.</span>
					</button>
				</div>
			</div>
		</div>
		<div class="product__buttons-wrap">
			<button class="product__add-to-cart" type="button">
				Добавить в корзину
			</button>
			<button class="product__add-to-favorite" type="button">
				<span class="visually-hidden">Добавить в избранное.</span>
			</button>
		</div>
		<dl class="product__about">
			<dt>Описание</dt>
			<dd></dd>
			<dt>Состав и уход</dt>
			<dd></dd>
		</dl>
	</section>
	<section class="main__other-products other-products">
		<h2 class="other-products__title">Похожие товары</h2>
		<ul class="other-products__list">
			<li class="other-products__item">
				<a href="#!">
					<picture>
						<source
							media="(min-width: 1440px)"
							width="334"
							height="444"
							srcset="/images/slider-desktop-1.jpg"
						/>
						<img
							src="/images/other-product-1.jpg"
							width="168"
							height="222"
							alt="Платье."
						/>
					</picture>
					<h3 class="other-products__heading">
						Платье с V-образным вырезом, белый
					</h3>
					<p class="other-products__price">
						<span class="old-price">14 900 RUB</span> 8 000 RUB
					</p>
				</a>
			</li>
			<li class="other-products__item">
				<a href="#!">
					<picture>
						<source
							media="(min-width: 1440px)"
							width="334"
							height="444"
							srcset="/images/slider-desktop-2.jpg"
						/>
						<img
							src="/images/other-product-2.jpg"
							width="168"
							height="222"
							alt="Костюм."
						/>
					</picture>
					<h3 class="other-products__heading">
						Жакет двубортный, <br />серо-голубой
					</h3>
					<p class="other-products__price">8 900 RUB</p>
				</a>
			</li>
			<li class="other-products__item">
				<a href="#!">
					<picture>
						<source
							media="(min-width: 1440px)"
							width="334"
							height="444"
							srcset="/images/slider-desktop-3.jpg"
						/>
						<img
							src="/images/other-product-2.jpg"
							width="168"
							height="222"
							alt="Костюм."
						/>
					</picture>
					<h3 class="other-products__heading">платье макси с ярусами, белый</h3>
					<p class="other-products__price">10 500 RUB</p>
				</a>
			</li>
			<li class="other-products__item">
				<a href="#!">
					<picture>
						<source
							media="(min-width: 1440px)"
							width="334"
							height="444"
							srcset="/images/slider-desktop-4.jpg"
						/>
						<img
							src="/images/other-product-2.jpg"
							width="168"
							height="222"
							alt="Костюм."
						/>
					</picture>
					<h3 class="other-products__heading">комбинезон со стойкой, чёрный</h3>
					<p class="other-products__price">9500 RUB</p>
				</a>
			</li>
		</ul>
	</section>
</template>

<style lang="scss" scoped>
.product {
	@media (min-width: 1440px) {
		display: grid;
		grid-template-columns: 70px 571px 465px;
		grid-template-rows: 20px 20px 60px 60px 84px 77px 400px;
		width: 1106px;
		margin-right: auto;
		margin-left: auto;
		padding-left: 12px;
	}
}

.details-product {
	display: none;

	@media (min-width: 1440px) {
		display: block;
		grid-row: 1 / 5;
		margin: 0;
		padding: 0;
		list-style: none;
	}
}

.details-product__link--current {
	opacity: 0.5;
}

.product__slider {
	width: 375px;
	margin: 0;
	margin-right: auto;
	margin-left: auto;
	padding: 0;
	list-style: 0;

	@media (min-width: 1440px) {
		width: 518px;
		margin-left: 30px;
	}
}

.slider__item {
	display: none;

	&--current {
		display: block;
	}
}

.slider-controls {
	position: relative;
	top: -33px;
	left: 155px;
}

.slider-controls__control {
	display: inline-block;
	width: 7px;
	height: 7px;
	margin: 3px;
	background-color: rgba(#ffffff, 40%);
	border: none;
	border-radius: 50%;
	cursor: pointer;
	appearance: none;

	&:checked {
		background-color: #ffffff;
	}
}

.product__info {
	display: flex;
	width: 375px;
	margin-right: auto;
	margin-left: auto;

	@media (min-width: 1440px) {
		display: block;
		grid-column: 3 / -1;
		grid-row: 1 / 2;
		width: 465px;
	}
}

.product__title {
	margin: 0;
	margin: 7px 17px;
	font-weight: 400;
	font-size: 12px;
	line-height: 16px;
	color: #333333;
	text-transform: uppercase;

	@media (min-width: 1440px) {
		margin: 0;
		margin-left: 38px;
	}
}

.product__favorite {
	width: 24px;
	height: 24px;
	margin-top: 1px;
	margin-right: 10px;
	margin-left: auto;
	background: none;
	background-image: url('/images/icons/favorite.svg');
	background-repeat: no-repeat;
	background-position: 50% 50%;
	border: none;
	cursor: pointer;

	@media (min-width: 1440px) {
		display: none;
	}
}

.product__price {
	margin: 0;
	margin-top: 1px;
	margin-left: 17px;
	font-size: 12px;
	line-height: 16px;
	color: #333333;

	@media (min-width: 1440px) {
		grid-column: 3 / -1;
		grid-row: 2 / 3;
		margin-top: 3px;
		margin-left: 38px;
	}
}

.sizes {
	margin: 30px 136px 20px 16px;

	@media (min-width: 1440px) {
		grid-column: 3 / -1;
		grid-row: 3 / 4;
		margin: 0;
		margin-top: 28px;
		margin-left: 38px;
	}
}

.sizes__title {
	margin: 0;
	margin-bottom: 11px;
	font-size: 10px;
	line-height: 14px;
	color: #4f4f4f;
}

.sizes__list {
	display: flex;
	margin: 0;
	padding: 0;
	list-style: none;
	gap: 14px;
}

.sizes__item {
	display: flex;
	flex-direction: column;
	align-items: center;
}

.item__btn {
	width: 65px;
	height: 31px;
	margin-bottom: 6px;
	font-size: 10px;
	text-align: center;
	background: none;
	border: 1px solid #333333;
	cursor: pointer;

	&--disabled {
		color: #bdbdbd;
		border-color: #bdbdbd;
	}
}

.item__description {
	font-size: 10px;
	color: #828282;

	&--disabled {
		color: #bdbdbd;
	}
}

.colors {
	padding: 12px 17px 5px;

	@media (min-width: 1440px) {
		grid-column: 3 / -1;
		grid-row: 5/ 6;
		padding: 12px 17px 32px;
		padding-top: 15px;
		padding-left: 38px;
	}
}

.colors__title {
	margin: 0;
	margin-bottom: 8px;
	font-size: 10px;
	line-height: 14px;
	color: #4f4f4f;
}

.colors__variants {
	display: flex;
	gap: 10px;
}

.color__variant {
	width: 28px;
	height: 27px;
	border: none;
	border-radius: 0;
	cursor: pointer;

	&--1 {
		background-color: #ffffff;
		border: 1px solid #bdbdbd;
	}

	&--2 {
		background-color: #000000;
	}

	&--3 {
		background-color: #f9f1dc;
	}
}

.product__buttons-wrap {
	display: none;

	@media (min-width: 1440px) {
		display: block;
		display: flex;
		justify-content: space-between;
		align-items: center;
		grid-column: 3 / -1;
		grid-row: 6 / 7;
		width: 360px;
		margin-top: 7px;
		margin-left: 38px;
	}
}

.product__add-to-cart {
	width: 306px;
	padding: 15px 25px;
	font-size: 11px;
	line-height: 15px;
	color: #ffffff;
	text-transform: uppercase;
	background-color: #000000;
	border: none;
	cursor: pointer;
}

.product__add-to-favorite {
	position: relative;
	width: 44px;
	height: 44px;
	background: none;
	border: 1px solid #000000;
	cursor: pointer;

	&::before {
		content: '';
		position: absolute;
		top: 13px;
		left: 14px;
		width: 24px;
		height: 24px;
		background-image: url('/images/icons/favorite.svg');
		background-repeat: no-repeat;
	}
}

.button-wrap {
	display: flex;
	justify-content: center;
	width: 34px;
	padding-bottom: 3px;

	&--current {
		border-bottom: 1px solid #4f4f4f;
	}
}

.product__about {
	margin: 0;
	margin-top: 27px;
	margin-right: 16px;
	margin-left: 16px;
	border-top: 1px solid #e0e0e0;

	& dt {
		position: relative;
		padding-top: 12px;
		padding-bottom: 13px;
		font-size: 10px;
		line-height: 14px;
		color: #333333;
		text-transform: uppercase;
		border-bottom: 1px solid #e0e0e0;
		cursor: pointer;

		&::before {
			content: '';
			position: absolute;
			top: 14px;
			right: 6px;
			width: 12px;
			height: 12px;
			background-image: url('/images/icons/plus.svg');
			background-repeat: no-repeat;
		}
	}

	@media (min-width: 1440px) {
		grid-column: 3 / -1;
		grid-row: 7 / 8;
		margin-top: 27px;
		margin-right: 66px;
		margin-left: 36px;
	}
}

.other-products {
	width: 375px;
	margin: 0;
	margin-right: auto;
	margin-left: auto;
	padding-top: 42px;
	padding-right: 14px;
	padding-left: 15px;

	@media (min-width: 1440px) {
		width: 1360px;
		margin-right: auto;
		margin-left: auto;
		padding-top: 16px;
	}
}

.other-products__title {
	margin: 0;
	margin-bottom: 29px;
	font-weight: 400;
	font-size: 12px;
	line-height: 16px;
	color: #333333;
	text-transform: uppercase;
}

.other-products__list {
	display: flex;
	flex-wrap: wrap;
	margin: 0;
	margin-bottom: 70px;
	padding: 0;
	list-style: none;
	gap: 8px;
}

.other-products__item {
	box-sizing: border-box;
	width: 168px;

	& a {
		text-decoration: none;
	}

	@media (min-width: 1440px) {
		width: 334px;
	}
}

.other-products__heading {
	margin: 0;
	padding: 2px 9px;
	font-weight: 400;
	font-size: 10px;
	line-height: 14px;
	color: #333333;
	text-transform: uppercase;

	@media (min-width: 1440px) {
		padding-top: 10px;
		padding-left: 17px;

		& br {
			display: none;
		}
	}
}

.other-products__price {
	margin: 0;
	margin-top: 2px;
	margin-left: 8px;
	font-size: 10px;
	line-height: 14px;
	color: #828282;

	& span {
		text-decoration: line-through;
	}

	@media (min-width: 1440px) {
		margin-top: 7px;
		margin-left: 17px;
	}
}
</style>
