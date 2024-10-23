<template>
	<header class="header">
		<ul class="header__menu menu">
			<li class="menu__item">
				<a href="#!" class="menu__link menu__link--user">
					<span class="visually-hidden">User</span></a
				>
			</li>
			<li class="menu__item menu__item--first">
				<a href="#!" class="menu__link menu__link--search">
					<span class="visually-hidden">Search</span>
				</a>
			</li>
			<li class="menu__item menu__item--second">
				<a href="#!" class="menu__link menu__link--favorite">
					<span class="visually-hidden">Favorite</span>
				</a>
			</li>
		</ul>
		<a class="header__logo" href="#!">
			<img src="/images/logo-mobile.svg" width="38" height="17" alt="Logo Stik." />
		</a>
		<a class="header__cart" href="#!">
			<span class="visually-hidden">Cart</span>
		</a>
	</header>
</template>

<script setup></script>

<style lang="scss" scoped>
.header {
	display: flex;
	box-sizing: border-box;
	width: 375px;
	margin-right: auto;
	margin-left: auto;
	padding: 15px 16px 12px;

	@media (min-width: 1440px) {
		align-items: center;
		width: 1440px;
		margin-right: auto;
		margin-left: auto;
		padding: 29px 46px 27px 53px;
	}
}

.menu {
	display: flex;
	margin: 0;
	padding: 0;
	list-style: none;
	gap: 13px;

	@media (min-width: 1440px) {
		display: flex;
		margin-right: 20px;
		margin-left: auto;
	}
}

.menu__item {
	@media (min-width: 1440px) {
		&--first {
			order: -2;
		}

		&--second {
			order: -1;
		}
	}
}

.menu__link {
	position: relative;
	display: block;
	width: 20px;
	height: 20px;

	&::before {
		content: '';
		position: absolute;
		background-repeat: no-repeat;
		background-position: 50% 50%;
	}

	&--user::before {
		top: 0;
		left: 0;
		width: 20px;
		height: 20px;
		background-image: url('/images/icons/user.svg');
	}

	&--search::before {
		top: 0;
		left: 0;
		width: 20px;
		height: 20px;
		background-image: url('/images/icons/search.svg');
	}

	&--favorite {
		display: none;
	}

	@media (min-width: 1440px) {
		&--user::before {
			top: -1px;
			left: 3px;
		}

		&--search::before {
			top: -1px;
			left: -2px;
		}

		&--favorite {
			display: block;
		}

		&--favorite::before {
			top: 0;
			left: 0;
			display: block;
			width: 20px;
			height: 20px;
			background-image: url('/images/icons/favorite-desktop.svg');
		}
	}
}

.header__logo {
	margin-top: 2px;
	margin-left: 87px;

	@media (min-width: 1440px) {
		order: -1;
		margin-left: 641px;

		& img {
			width: 54px;
			height: 24px;
		}
	}
}

.header__cart {
	position: relative;
	display: block;
	width: 20px;
	height: 20px;
	margin-top: 1px;
	margin-left: auto;

	&::before {
		content: '';
		position: absolute;
		top: 0;
		left: 0;
		width: 20px;
		height: 20px;
		background-image: url('/images/icons/cart.svg');
		background-repeat: no-repeat;
		background-position: 50% 50%;
	}

	@media (min-width: 1440px) {
		margin: 0;

		&::before {
			top: -1px;
			left: -1px;
		}
	}
}
</style>
