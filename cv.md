Dmitry Buto
============

-------------------      ----------------------------
MyAddress                 *Minsk, Belarus*
email                     *dmitrybuto@gmail.com*
skype                     *butonidze*
phone number              *+375292661342*

About me
--------
I`m 32. I prefer healty life style. I am fond of various sports: basketball, running (half marathon, sometimes marathon), triatholon. My main hobby is fishing. y philosophy of life is constant time management. I really appreciate my time. The goal is to achieve a result, to understand whether I like programming in JS. I prefer self-education.

Skills/Experience
----------
I have 2 years of experience as an engineer (working with autocad, solidworks, kompass), working with drawings. I work with cms joomla, joomshopping component. I Created 6 sites, they are all e-shops: instrumenty.by, 1926.by, husq.by, garden.com.by, vannaja.by, smart-store.by. I run the server, monitor the administration by isp manager . In addition, I promote all sites by SEO (google,yandex), I am engaged in site optimization. I run 4 advertising accounts in Google AdWords, Google shopping (merch), Yandex Direct. I am fond of retargeting and remarketing. I own systems of analytics google analytics, yandex metric. I work with google tag manager. I run the bitrix24 CRM system, I connected IP telephony.

Education
---------

2006-2011
:   **BNTU, full-time education on a free basis, engineer .**

2011-2012
:   **English courses 4 semesters, Mr. English , Grodno .**


Code 
----------

```
<hr class="uk-article-divider">
								<?php } ?>
								</div>
								<?php if ($this->config->show_tax_in_product && $this->product->product_tax > 0){?>
									<span class="taxinfo"><?php echo productTaxInfo($this->product->product_tax);?></span>
								<?php }?>
								<?php if ($this->config->show_plus_shipping_in_product){?>
									<span class="plusshippinginfo"><?php print sprintf(_JSHOP_PLUS_SHIPPING, $this->shippinginfo);?></span>
								<?php }?>
								<?php if ($this->product->product_basic_price_show){?>
									<div class="prod_base_price"><?php echo _JSHOP_BASIC_PRICE?>: <span id="block_basic_price"><?php echo formatprice($this->product->product_basic_price_calculate)?></span> / <?php echo $this->product->product_basic_price_unit_name;?></div>
								<?php }?>	

								<?php if ($this->product->getPriceCalculate() > 160 && ($this->product->getPriceCalculate()) < 1650){ ?>
									<div class="rassrochka uk-text-small uk-text-muted">
										<i class="uk-icon-ellipsis-h"></i> от <?php print formatprice($this->product->getPriceCalculate()*0.2333333333333333333)?>/м в рассрочку . 
										<div class="uk-badge uk-badge-notification uk-badge-danger uk-contrast"><a class="uk-contrast" href="#modal" data-uk-modal title="Купить в рассрочку <?php echo $this->product->name?> в интернет-магазине instrumenty.by">Рассчитать рассрочку </a></div>
										<div id="modal" class="uk-modal">
											<div class="uk-modal-dialog">
												<a class="uk-modal-close uk-close"></a>
												<h3>Рассрочка от банка ЗАО "ВТБ банк"</h3>
												<h4><?php echo $this->product->name?> расчет стоимости рассрочки</h4>
												<table class="uk-table uk-table-hover">
													<tbody>
														<tr>
															<td>Срок, месяцев</td>
															<td>Ежемесячный платеж</td>
															<td>Предоплата</td>
															<td>Полная стоимость в рассрочку</td>
														</tr>
														<tr>
															<td>3</td>	
															<td> <?php print formatprice($this->product->getPriceCalculate()*0.2333333333333333333)?></td>
															<td> <?php print formatprice($this->product->getPriceCalculate() * 0.3)?></td>
															<td> <?php print formatprice($this->product->getPriceCalculate())?></td>
														</tr>
													</tbody>
												</table>
												<h4>Необходимые данные выслать на e-mail: inwita@gmail.com:</h4>
												<ul>
													<li>ФИО, телефон, e-mail (на который нам необходимо выслать счет). Данный счет вы сможете отнести в любое ближайшее к вам отделение банка ВТБ</li>
												</ul>
												<h3>Более подробную информацию о требованиях к предоставлению рассрочки вы можете найти <a href="/rassrochka#vtbr">тут</a></h3>
												
											</div>
										</div> <span>на 3 месяца</span>
									</div>
									<?php } elseif (($this->product->getPriceCalculate() > 1650) && ($this->product->getPriceCalculate()) < 4500){ ?>
									<div class="rassrochka uk-text-small uk-text-muted">
										<i class="uk-icon-ellipsis-h"></i> от <?php print formatprice($this->product->getPriceCalculate() * 0.173333333333264)?> BYN/м при покупке в 
										<div class="uk-badge uk-badge-notification uk-badge-danger uk-contrast"><a class="uk-contrast" href="#modal2" data-uk-modal title="Купить в рассрочку <?php echo $this->product->name?> в интернет-магазине instrumenty.by">в рассрочку</a></div>
										<div id="modal2" class="uk-modal">
											<div class="uk-modal-dialog">
												<a class="uk-modal-close uk-close"></a>
												<h4><?php echo $this->product->name?> расчет стоимости рассрочки</h4>
												<h3>Рассрочка от банка ЗАО "ВТБ банк"</h3>
												<h4><?php echo $this->product->name?> расчет стоимости рассрочки</h4>
												<table class="uk-table uk-table-hover">
													<tbody>
														<tr>
															<td>Срок, месяцев</td>
															<td>Ежемесячный платеж</td>
															<td>Предоплата</td>
															<td>Полная стоимость в рассрочку</td>
														</tr>
														<tr>
															<td>3</td>	
															<td> <?php print formatprice($this->product->getPriceCalculate()* 0.173333333333264)?></td>
															<td> <?php print formatprice($this->product->getPriceCalculate() * 0.5)?></td>
															<td> <?php print formatprice($this->product->getPriceCalculate() * 1.02)?></td>
														</tr>
													</tbody>
												</table>
												<h4>Необходимые данные выслать на e-mail: inwita@gmail.com:</h4>
												<ul>
													<li>ФИО, телефон, e-mail (на который нам необходимо выслать счет). Данный счет вы сможете отнести в любое ближайшее к вам отделение банка ВТБ</li>
												</ul>
												<h3>Более подробную информацию о требованиях к предоставлению рассрочки вы можете найти <a href="/rassrochka#vtbr">тут</a></h3>
											</div>
										</div> <span>на 3 месяца</span>
									</div>
									<hr class="uk-article-divider">
									<?php } elseif ($this->product->getPriceCalculate() > 4500) { ?>
									<h4>Рассрочка на сумму свыше 4500 BYN не предоставляется</h4>
								<?php }?>
								<?php if (count($this->attributes)){?>
									<div class="jshop_prod_attributes">
										<div class="jshop attributes">
											<?php foreach($this->attributes as $attribut){?>
												<?php if ($attribut->grshow){?>
													<div class="attributgr_title">
														<span class="attributgr_name"><?php print $attribut->groupname?></span>
													</div>
												<?php }?>
												<div class="attributes_<?php echo $attribut->attr_id?>">
													<label class="attributes_title">
														<span class="attributes_name"><?php echo $attribut->attr_name?></span>
													</label>
													<?php if ($attribut->attr_description) {?> 
														<span class="infotultip" data-uk-tooltip="{pos:'right'}" title="<?php echo $attribut->attr_description;?>"> <i class="uk-icon-info-sign"></i> </span>
													<?php } ?>
													<span id='block_attr_sel_<?php echo $attribut->attr_id?>'>
														<?php echo $attribut->selects?>
													</span>
												</div>
											<?php }?>
										</div>
									</div>
									<hr class="uk-article-divider">
								<?php }?>
								<?php if (count($this->product->freeattributes)){?>
									<div class="prod_free_attribs">
										<div class="jshop">
											<?php foreach($this->product->freeattributes as $freeattribut){?>
												<label class="freeattributes_title">
													<span class="freeattribut_name"><?php echo $freeattribut->name;?></span> 	
													<?php if ($freeattribut->description) {?> 
														<span class="infotultip" data-uk-tooltip="{pos:'right'}" title="<?php echo $freeattribut->description;?>"> <i class="uk-icon-info-sign"></i> </span>
													<?php } ?>
												</label>
												<span class="field"><?php echo $freeattribut->input_field;?></span>
												<?php if ($freeattribut->required){?>
													<span class="requiredtext" data-uk-tooltip="{pos:'right'}" title="<?php echo _JSHOP_REQUIRED?>"><i class="uk-icon-warning-sign"></i></span>
												<?php }?>
											<?php }?>
										</div>
									</div>
									<hr class="uk-article-divider">
								<?php }?>
								<div class="uk-block uk-block-muted">
									<?php if (!$this->config->hide_text_product_not_available){ ?>
										<div class="not_available" id="not_available"><?php echo $this->available?></div>
									<?php }?>
									<?php echo $this->_tmp_product_html_before_buttons;?>
									<?php if (!$this->hide_buy){?>
										<div class="prod_buttons" data-uk-margin style="<?php echo $this->displaybuttons?>">
											<div class="quantity prod_qty_input" data-uk-tooltip title="<?php echo _JSHOP_QUANTITY?>">
												<span class="quantitymore" onclick="qty=jQuery('#quantity');qty.val(parseFloat(qty.val())+1);qty.change();reloadPrices();"></span>
												<input type="text" name="quantity" id="quantity" onkeyup="reloadPrices();" class="uk-form" value="<?php echo $this->default_count_product?>" />
												<span class="quantityless" onclick="qty=jQuery('#quantity');if (parseFloat(qty.val())-1 > 0) qty.val(parseFloat(qty.val())-1);qty.change();reloadPrices();"></span>
												<?php echo $this->_tmp_qty_unit;?>
											</div>
											<div class="buttons " data-uk-margin>
												<button type="submit" class="uk-button uk-button-primary"   onclick="jQuery('#to').val('cart');" id="addtocart-cart-goods"> <i class="uk-icon-shopping-cart"></i> <?php echo _JSHOP_ADD_TO_CART?> </button>
												<?php if ($this->enable_wishlist){?>
													<button type="submit " data-uk-tooltip="{pos:'right'}" title="<?php echo _JSHOP_ADD_TO_WISHLIST?>" class="uk-button" onclick="jQuery('#to').val('wishlist');" id="addtowishlist-cart-goods"><i class="uk-icon-clock-o uk-text-large"></i></button>
												<?php }?>
												<?php echo $this->_tmp_product_html_buttons;?>	
											</div>
											<div id="jshop_image_loading" class="no_display"></div>
										</div>
									<?php }?>
								</div>
								<?php echo $this->_config_tmp;?>
							</div>
							<div class="uk-width-1-3">
								<?php if (count($modsOplata)){?>
									<div>
										<a class="uk-margin" href="#modal-oplata" data-uk-modal id="oplata-cart-goods">
											<i class="uk-icon-money"></i> Оплата
										</a>
										<div> <span data-uk-tooltip="{pos:'right'}" title="принимаем оплату картами мастеркард" id="block_price" ><a href="#modal-oplata" class="uk-icon-button uk-icon-cc-mastercard"  data-uk-modal></a></span><span data-uk-tooltip="{pos:'right'}" title="принимаем оплату картами visa" id="block_price" ><a href="#modal-oplata" class="uk-icon-button uk-icon-cc-visa" data-uk-modal></a></span><span data-uk-tooltip="{pos:'right'}" title="принимаем оплату кредитными картами банков" id="block_price" ><a href="#modal-oplata" class="uk-icon-button uk-icon-credit-card" data-uk-modal></a></span><span data-uk-tooltip="{pos:'right'}" title="принимаем оплату банковским переводом" id="block_price" ><a href="#modal-oplata" class="uk-icon-button uk-icon-bank" data-uk-modal></a></span><span data-uk-tooltip="{pos:'right'}" title="принимаем оплату наличными деньгами" id="block_price" ><a href="#modal-oplata" class="uk-icon-button uk-icon-money" data-uk-modal></a></span></div>
										
<?php if (in_array(12, $this->product->label_multiselect)) {?>								<span data-uk-tooltip="{pos:'right'}" title="<?php echo $this->product->name?> оплата карточкой рассрочки Халва от МТБ банк на 3 месяца" id="block_cred-mtb" ><a href="#modahalva" data-uk-modal title="Купить в рассрочку по карте халва <?php echo $this->product->name?> в интернет-магазине instrumenty.by"><img src="images/card-mtb.png" width="45" /></a></span>
<div id="modahalva" class="uk-modal">
											<div class="uk-modal-dialog">
												<a class="uk-modal-close uk-close"></a>
												<h4><?php echo $this->product->name?> купить в рассрочку по карте Халва от МТБ Банк .</h4>
												<table class="uk-table uk-table-hover">
													<tbody>
														<tr>
															<td>Срок, месяцев</td>
															<td>Оплата по терминалу в магазине</td>
															<td>Оплата по теримналу через интернет-эквайринг</td>
															
														</tr>
														<tr>
															<td>2</td>	
															<td> Есть</td>
															<td> Есть</td>
														</tr>
													</tbody>
												</table>
												<h3>Подробнее об условиях рассрочки по карте халва читаем <a href="rassrochka#halva">тут</a></h3>
												</div>
												</div>
<span data-uk-tooltip="{pos:'right'}" title="<?php echo $this->product->name?> оплата карточкой рассрочки Smart Карта от Москва-Минск на 2 месяца" id="block_cred-mm" ><a href="#modasmart" data-uk-modal title="Купить в рассрочку по smart-карта <?php echo $this->product->name?> в интернет-магазине instrumenty.by"><img src="images/card-smart-card.png" width="45" /></a></span>

<div id="modasmart" class="uk-modal">
											<div class="uk-modal-dialog">
												<a class="uk-modal-close uk-close"></a>
												<h4><?php echo $this->product->name?> купить в рассрочку по Smart Карта от Москва-Минск .</h4>
												<table class="uk-table uk-table-hover">
													<tbody>
														<tr>
															<td>Срок, месяцев</td>
															<td>Оплата по терминалу в магазине</td>
															<td>Оплата по теримналу через интернет-эквайринг</td>
															
														</tr>
														<tr>
															<td>3</td>	
															<td> Есть</td>
															<td> Есть</td>
														</tr>
													</tbody>
												</table>
												<h3>Подробнее об условиях рассрочки по смарт картае читаем <a href="rassrochka#mmb">тут</a></h3>
												</div>
												</div>
<span data-uk-tooltip="{pos:'right'}" title="<?php echo $this->product->name?> оплата карточкой рассрочки карта покупок от Белгазпромбанка на 4 месяца" id="block_cred-kp" ><a href="#modacartpokup" data-uk-modal title="Купить в рассрочку по карте покупок <?php echo $this->product->name?> в интернет-магазине instrumenty.by"><img src="images/belagazpriombank.png" width="45" /></a></span>

<div id="modacartpokup" class="uk-modal">
											<div class="uk-modal-dialog">
												<a class="uk-modal-close uk-close"></a>
												<h4><?php echo $this->product->name?> купить в рассрочку по Карте Покупок от Белгазпромбанка .</h4>
												<table class="uk-table uk-table-hover">
													<tbody>
														<tr>
															<td>Срок, месяцев</td>
															<td>Оплата по терминалу в магазине</td>
															<td>Оплата по теримналу через интернет-эквайринг</td>
															
														</tr>
														<tr>
															<td>4</td>	
															<td> Есть</td>
															<td> Есть</td>
														</tr>
													</tbody>
												</table>
												<h3>Подробнее об условиях рассрочки по карте покупок <a href="rassrochka#kp">тут</a></h3>
												</div>
												</div>

<span data-uk-tooltip="{pos:'right'}" title="<?php echo $this->product->name?> оплата карточкой рассрочки Черепаха от ВТБ Банка на 10 месяцев" id="block_cred-kp" ><a href="#modacherepaha" data-uk-modal title="Купить в рассрочку по Черепаха от ВТБ Банка <?php echo $this->product->name?> в интернет-магазине instrumenty.by"><img src="images/card-rcard-cgerep.png" width="45" /></a></span>
<div id="modacherepaha" class="uk-modal">
											<div class="uk-modal-dialog">
												<a class="uk-modal-close uk-close"></a>
												<h4><?php echo $this->product->name?> купить в рассрочку по карте Черепаха от ВТБ Банка .</h4>
												<table class="uk-table uk-table-hover">
													<tbody>
														<tr>
															<td>Срок, месяцев</td>
															<td>Оплата по терминалу в магазине</td>
															<td>Оплата по теримналу через интернет-эквайринг</td>
															
														</tr>
														<tr>
															<td>10</td>	
															<td> Есть</td>
															<td> Есть</td>
														</tr>
													</tbody>
												</table>
												<h3>Подробнее об условиях рассрочки по карте покупок <a href="rassrochka#vtb">тут</a></h3>
												</div>
												</div>
												<?php }?>	
</div>									
									<hr class="uk-article-divider">
								<?php } ?>
								<?php if (count($modsDostavka)){?>
									<div class="dostavka <?php if (($this->product->manufacturer_info->id == '3') || ($this->product->manufacturer_info->id == '8')) echo "uk-hidden"?>">
										<a class="uk-margin" href="#modal-dostavka" data-uk-modal id="delivery-cart-goods">
											<i class="uk-icon-truck"></i> Доставка
										</a>
										<?php if ($this->product->delivery_time && $this->product->delivery_time != '' ){ ?>
									<div class="deliverytime <?php if ($product->hide_delivery_time) echo 'uk-hidden' ?>">
										<?php print _JSHOP_DELIVERY_TIME?>: <?php print $this->product->delivery_time?>
									</div>
								<?php } ?>
										<div> <span data-uk-tooltip="{pos:'right'}" title="Самовывоз" id="block_price" ><a href="#modal-adress" class="uk-icon-button uk-icon-upload"  data-uk-modal id="adress-cart-goods"></a></span><span data-uk-tooltip="{pos:'right'}" title="Доставка грузов курьерной службой Автолайт Экспресс, доставка занимает 1 банковский день" id="block_price" ><a href="#modal-dostavka" class="uk-icon-button uk-icon-buysellads" data-uk-modal></a></span><span data-uk-tooltip="{pos:'right'}" title="Курьерской службой vozim by. Доставка составляет 1-3 дня. " id="block_price" ><a href="#modal-dostavka" class="uk-icon-button uk-icon-vimeo-square" data-uk-modal></a></span><span data-uk-tooltip="{pos:'right'}" title="Самовывоз во всех областных городах черех курьескую службу Globel 24. Срок доставки 1-2 дня." id="block_price" ><a href="#modal-dostavka" class="uk-icon-button uk-icon-get-pocket" data-uk-modal></a></span><span data-uk-tooltip="{pos:'right'}" title="Почтой по Беларуси. Наложенным платежом. Срок доставки 1-7 дней." id="block_price" ><a href="#modal-dostavka" class="uk-icon-button uk-icon-envelope" data-uk-modal></a></span><span data-uk-tooltip="{pos:'right'}" title="<?php echo $this->product->name?> доставка по Минску в течение 1 дня собственным курьером. " id="block_price" ><a href="#modal-dostavka" class="uk-icon-button uk-icon-truck"  data-uk-modal></a></span></div>
									</div>
									<hr class="uk-article-divider">
								<?php } ?>
								<div class="uk-margin-top "><?php echo $this->_tmp_product_html_after_buttons;?></div>
								<div class="telephony-s <?php if (($this->product->manufacturer_info->id == '3') || ($this->product->manufacturer_info->id == '8')) echo "uk-hidden"?>">
									<span data-uk-tooltip="{pos:'right'}" title="нажмите для отображения контактных номеров" id="block_telephones" ><a class="uk-margin" href="#modal-telephony" data-uk-modal id="telephony-cart-goods"><i class="uk-icon-phone"></i>Телефоны</a></span>
									<div id="modal-telephony" class="uk-modal">
										<div class="uk-modal-dialog">
											<a class="uk-modal-close uk-close"></a>
											<ul class="uk-list uk-list-line">
												<li><i class="uk-icon-calendar"></i><div class="uk-badge uk-badge-warning">Режим работы call-центра: ПН-ПТ 9.00-19.00/ СБ 9.00-17.00</div></li>
												<li><div class="uk-badge uk-badge-success">Минск</div></li>
												<li><i class="uk-icon-mobile"></i>  +375(29)183-11-14</li>
												<li><i class="uk-icon-mobile"></i>  +375(29)510-94-69</li>
												<li><i class="uk-icon-fax"></i>  +375(17)326-15-60</li>
												<li><div class="uk-badge uk-badge-success">Гродно</div></li>
												<li><i class="uk-icon-mobile"></i>  +375(29)781-83-18</li>
												<li><i class="uk-icon-mobile"></i>  +375(44)753-50-53</li>
												<li><i class="uk-icon-fax"></i>  +375(152)68-30-78</li>
											</ul>
										</div>
									</div>		
								</div>
								<?php if (($this->product->manufacturer_info->id == '3') || ($this->product->manufacturer_info->id == '8')){?>
								<div class="telephony-s2 ">
									<span data-uk-tooltip="{pos:'right'}" title="нажмите для отображения контактных номеров" id="block_telephones" ><a class="uk-margin" href="#modal-telephony2" data-uk-modal id="telephony-cart-goods"><i class="uk-icon-phone"></i>Телефоны</a></span>
									<div id="modal-telephony2" class="uk-modal">
										<div class="uk-modal-dialog">
											<a class="uk-modal-close uk-close"></a>
											<ul class="uk-list uk-list-line">
												<li><i class="uk-icon-calendar"></i><div class="uk-badge uk-badge-warning">Режим работы call-центра: ПН-ПТ 9.00-18.00</div></li>
												<li><div class="uk-badge uk-badge-success">Гродно</div></li>
												<li><i class="uk-icon-mobile"></i>  +375(29)781-83-18</li>
												<li><i class="uk-icon-mobile"></i>  +375(44)753-50-53</li>
												<li><i class="uk-icon-fax"></i>  +375(152)68-30-78</li>
											</ul>
										</div>
									</div>		
								</div>
								<?php }?>
								<div><span data-uk-tooltip="{pos:'right'}" title="Просто нажмите на ссылку и введите ваш номер телефона. Наши специалисты свяжутся с Вами как можно быстрее." id="block_telephones" ><a class="uk-margin" id="dockbar_callback" onclick="dockbar.toggle(this)" data-uk-tooltip="{pos:'bottom-left', delay: 100}" title="" data-cached-title="Заказать обратный звонок" id="callback-cart-goods"><i class="uk-icon-phone-square"></i> Заказать звонок</a></span></div>
								<div class="adress <?php if (($this->product->manufacturer_info->id == '3') || ($this->product->manufacturer_info->id == '8')) echo "uk-hidden"?>">
									<span data-uk-tooltip="{pos:'right'}" title="Адреса складов в Минске и Гродно" id="block_adres" ><a class="uk-margin" href="#modal-adres-sklad" data-uk-modal id="sclad-cart-goods"><i class="uk-icon-map-marker"></i>Адрес склада</a></span>
									<div id="modal-adres-sklad" class="uk-modal">
										<div class="uk-modal-dialog">
											<a class="uk-modal-close uk-close"></a>
											<ul class="uk-grid uk-grid-width-large" data-uk-grid-margin>
												<ul class="uk-grid uk-width-1-2">
													<li><h4>Минск</h4></li>
													<li><i class="uk-icon-clock-o"></i><div>ПН-ПТ 9.00-19.00/ СБ 9.00-17.00</div></li>
													<li><i class="uk-icon-map-marker"></i>  Старовиленский тракт 10</li>
													<li><i class="uk-icon-map-marker"></i>1</li>
													<li><i class="uk-icon-mobile"></i>  +375(29)510-94-69</li>
													<li><i class="uk-icon-fax"></i>  +375(17)326-15-60</li>
												</ul>
												<ul class="uk-grid uk-width-1-2">
													<li><h4>Гродно</h4></li>
													<li><i class="uk-icon-clock-o"></i><div>ПН-ПТ 9.00-18.00</div></li>
													<li><i class="uk-icon-map-marker"></i>  Ул.Белуша 20б</li>
													<li><i class="uk-icon-map-marker"></i> офис 3</li>
													<li><i class="uk-icon-mobile"></i>  +375(29)781-83-18</li>
													<li><i class="uk-icon-mobile"></i>  +375(44)753-50-53</li>
													<li><i class="uk-icon-fax"></i>  +375(152)68-30-78</li>
													<li></li>
												</ul>
											</ul>
										</div>
									</div>
								</div>
								<div>
									<a class="uk-margin" id="dockbar_feedback" onclick="dockbar.toggle(this)" id="askquastions-cart-goods"><i class="uk-icon-question-circle"></i>Задать вопрос</a>
								</div>
							</div>
						</div>
						<div class="uk-hidden-small-1-3 uk-grid uk-grid-divider uk-panel"></div>
```




* Human Languages:
--------
     * English (b1/b2)
     * French (a1/a2)
     * Russian (native)
     * Belorussian (native)
     * Polish (sound perception)
     * Lithuanian (sound perception)

