<template>
	<footer class="footer">
		<div class="footer-main">
			<div>
				<div class="footer-tab">
					<NuxtLink to="/pp"><img src="@/assets/images/logo.png" alt="repaidLogo" /></NuxtLink>
					<div class="items">
						<div class="legal">
							<span>Legal</span>
							<NuxtLink to="/pp">Privacy Policy</NuxtLink>
							<NuxtLink to="/tos">Terms of Service</NuxtLink>
						</div>
						<div class="questions">
							<span>General questions</span>
							<p>info@repaidhq.com</p>
							<span>Want to partner with us?</span>
							<p>business@repaidhq.com</p>
						</div>
						<div class="follow">
							<span>Let's talk</span>
							<div class="follow-qrcode">
								<span>Find us on Telegram: +1 936 240 8965</span>
								<span>Find us on WhatsApp: +1 352 287 3489</span>
							</div>
						</div>
					</div>
				</div>
				<div class="footer-tip">
					<div>
						<p>© 2024 Repaid Headquarter all rights reserved</p>
					</div>
				</div>
			</div>
		</div>
	</footer>
</template>

<script setup lang="ts"></script>

<style lang="scss" scoped>
.footer {
	width: 100vw;

	.footer-main {
		border-bottom: 0.08rem solid;
		border-image: linear-gradient(90deg, #77e8e9 0%, #3ab33b 100%);
		border-image-slice: 1;
		display: flex;
		flex-direction: column;
		align-items: center;
		> div {
			max-width: 16rem;
			width: 100%;
			display: flex;
			flex-direction: column;
			align-items: center;
			gap: 0.8rem;
			padding: 0.96rem 0 0.4rem;
			.footer-tab {
				width: 100%;
				display: flex;
				align-items: flex-start;
				justify-content: space-between;

				gap: 0.9rem;
				> a {
					display: flex;
					> img {
						width: 1.68rem;
						height: 0.41rem;
					}
				}

				.items {
					flex: 1;
					display: flex;
					align-items: flex-start;
					justify-content: space-between;
					> div {
						display: flex;
						flex-direction: column;
						gap: 0.32rem;
						> span {
							font-size: 0.18rem;
							color: #999;
							line-height: 0.32rem;
						}
						> p {
							font-size: 0.18rem;
							color: #000;
							line-height: 0.32rem;
						}
						> a {
							font-size: 0.18rem;
							color: #000;
							line-height: 0.32rem;
							cursor: pointer;
						}
						.follow-qrcode {
							display: flex;
							flex-direction: column;
							gap: 0.32rem;
							> span {
								font-size: 0.18rem;
								color: #000;
								line-height: 0.32rem;
							}
						}
					}
				}
			}
			.footer-tip {
				border-top: 0.02rem solid;
				border-image: linear-gradient(90deg, rgba(0, 0, 0, 0) 0%, #ebebeb 50%, rgba(235, 235, 235, 0) 100%);
				border-image-slice: 1;

				width: 100%;
				box-sizing: border-box;
				display: flex;
				flex-direction: column;
				padding-top: 0.22rem;
				gap: 0.22rem;
				> div {
					display: flex;
					justify-content: space-between;
				}
				p {
					font-size: 0.12rem;
					line-height: 0.23rem;
					color: #999;
				}
			}
		}
	}
}

@media (min-width: 1280px) and (max-width: 1439px) {
	.footer {
		width: 100vw;

		.footer-main {
			padding: 0 1rem;
			> div {
				max-width: 100%;
				width: 100%;
				display: flex;
				flex-direction: column;
				align-items: center;
				gap: 0.8rem;
				padding: 0.96rem 0 0.4rem;
				.footer-tab {
					width: 100%;
					display: flex;
					align-items: flex-start;
					justify-content: space-between;

					gap: 0.9rem;
					> a {
						display: flex;
						> img {
							width: 1.68rem;
							height: 0.41rem;
						}
					}

					.items {
						flex: 1;
						display: flex;
						align-items: flex-start;
						justify-content: space-between;
						> div {
							display: flex;
							flex-direction: column;
							gap: 0.32rem;
							> span {
								font-size: 0.14rem;
								color: #999;
								line-height: 0.24rem;
							}
							> p {
								font-size: 0.14rem;
								color: #000;
								line-height: 0.24rem;
							}
							> a {
								font-size: 0.14rem;
								color: #000;
								line-height: 0.24rem;
								cursor: pointer;
							}
							.follow-qrcode {
								display: flex;
								flex-direction: column;
								gap: 0.32rem;
								> span {
									font-size: 0.14rem;
									color: #000;
									line-height: 0.24rem;
								}
							}
						}
					}
				}
			}
		}
	}
}

@media (min-width: 768px) and (max-width: 1280px) {
	.footer {
		.footer-main {
			padding: 0 0.32rem;

			display: flex;
			flex-direction: column;
			align-items: center;
			> div {
				max-width: 100vw;
				gap: 0.2rem;
				padding: 0.4rem 0 0.4rem;
				.footer-tab {
					flex-direction: column;
					align-items: center;
					justify-content: normal;

					gap: 0.2rem;

					> a {
						> img {
							width: 3.41rem;
							height: 0.73rem;
						}
					}

					.items {
						flex: none;
						display: flex;
						flex-wrap: wrap;
						justify-content: flex-start;
						gap: 0.4rem;
						margin-top: 0.4rem;
						.follow {
							width: 100%;
						}
						.questions {
							margin-left: 1rem;
						}
						> div {
							gap: 0.4rem;
							> span {
								font-size: 0.18rem;
								line-height: 0.32rem;
							}
							> p {
								font-size: 0.18rem;
								line-height: 0.32rem;
							}
							> a {
								font-size: 0.18rem;
								line-height: 0.32rem;
							}

							.follow-qrcode {
								gap: 0;
								justify-content: space-between;
								> div {
									gap: 0.1rem;
									> img {
										width: 1.8rem;
										height: 1.8rem;
									}
									> span {
										font-size: 0.18rem;
									}
								}
							}
						}
					}
				}
				.footer-tip {
					> div {
						flex-direction: column;
						gap: 0.24rem;
						> p {
							font-size: 0.24rem;
						}
					}
				}
			}
		}
	}
}

@media (min-width: 375px) and (max-width: 767px) {
	.footer {
		.footer-main {
			padding: 0 0.16rem;

			display: flex;
			flex-direction: column;
			align-items: center;
			> div {
				max-width: 100vw;
				gap: 0.2rem;
				padding: 0.4rem 0 0.4rem;
				.footer-tab {
					flex-direction: column;
					align-items: center;
					justify-content: normal;

					gap: 0.2rem;
					> a {
						> img {
							width: 1.66rem;
							height: 0.36rem;
						}
					}

					.items {
						flex: none;
						display: flex;
						flex-wrap: wrap;
						> div {
							gap: 0.08rem;
							> span {
								font-size: 0.14rem;
								line-height: 0.24rem;
							}
							> p {
								font-size: 0.14rem;
								line-height: 0.24rem;
							}
							> a {
								font-size: 0.14rem;
								line-height: 0.24rem;
							}
							.follow-qrcode {
								display: flex;
								flex-direction: column;
								gap: 0.08rem;
								> span {
									font-size: 0.14rem;
									line-height: 0.24rem;
								}
							}
						}
					}
				}
				.footer-tip {
					> div {
						flex-direction: column;
					}
				}
			}
		}
	}
}
</style>
