
<!DOCTYPE html>
<html>

<head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <title>Skin.Trade | Trade your CS GO skins with bots instantly!</title>
    <meta name="description" content="Use our CS:GO trade bot to exchange items, keys, skins & knives!">
    <meta name="keywords" content="csgolounge, cs.money, csgosell, csgoswap, cs money, csgotrademe, csgo, csgotrade, cs go skin trade, cs go trade bot, cs go fast trade, csgo trade, cs go trade, csgo skin bot, csgo exchange bot, csgo online trade, cs go trade">
    <meta http-equiv="cache-control" content="no-cache">
    <meta http-equiv="expires" content="0">
    <meta name="viewport" content="width=device-width,initial-scale=1">
    <meta name="google" content="notranslate">
    <meta property="og:url" content="https://skin.trade/"/>
    <meta property="og:type" content="website"/>
    <meta property="og:title" content="Skin.Trade | Trade your CS GO skins with bots instantly!"/>
    <meta property="og:description" content="Use our CS:GO trade bot to exchange items, keys, skins & knives!"/>
    <meta property="og:image" content="https://i.hizliresim.com/nWWgZa.png"/>
	<meta name="google-site-verification" content="v9jztdruG3KE5f-EmVxdrWVQxf26WfgtyhiYhIvedGU" />
    <link rel="shortcut icon" href="img/favicon.png" type="image/x-icon">
    <link href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css" rel="stylesheet" integrity="sha384-wvfXpqpZZVQGK6TAh5PVlGOfQNHSoD2xbE+QkPxCAFlNEevoEH3Sl0sibVcOQVnN" crossorigin="anonymous">
    <link href="css/all.css?v=9" rel="stylesheet">
	<script type="text/javascript" src="js/analytics.js"></script>
    <!-- HTML5 Shim and Respond.js IE8 support of HTML5 elements and media queries -->
    <!-- WARNING: Respond.js doesn't work if you view the page via file:// -->
    <!--[if lt IE 9]>
      <script src="https://oss.maxcdn.com/libs/html5shiv/3.7.0/html5shiv.js"></script>
      <script src="https://oss.maxcdn.com/libs/respond.js/1.4.2/respond.min.js"></script>
    <![endif]-->
</head>

<body>
    <div class="main">
    <div class="info_bar">
        <div class="pull-left info_left"><i class="fa fa-plus-circle"></i>&nbsp;Add to your Steam nickname “SKIN.TRADE” and get +2% bonus!<a class="bonus_linktext" data-toggle="modal" data-target="#popup_bonus">&nbsp;(How do I do this?)</a></div>
        <div class="pull-right info_right" title="Users Online"><i class="fa fa-user-times"></i>&nbsp;<span class="userCount">-</span></div>
    </div>
    <nav class="navbar navbar-default" role="navigation">
        <div class="container-fluid menu_fluid">
            <div class="navbar-header">
                 <button type="button" class="navbar-toggle"><span class="sr-only"></span> <span class="icon-bar"></span> <span class="icon-bar"></span> <span class="icon-bar"></span></button>
                 <a class="navbar-brand" href="/"></a>
				 <div class="tcount">
					<p class="tcount_head">Total Trades:</p>
					<p class="tcount_number"><span class="tradeCount">- - -</span></p>
				 </div>
                <ul class="nav navbar-nav navbar-right navbar_right_media">
                    
                    <a href="/authenticate" class="steam_link_mobile"><img src="img/signSteam_mobile.png"></a>
                    
                </ul>
            </div>
            <div class="collapse navbar-right terr navbar-collapse navbar_collapse_media" id="bs-example-navbar-collapse-1">
                <div class="menu_container">
                    <ul class="nav navbar-nav menu">
                        <li><a href="/">TRADE</a></li>
                        <li><a href="/about">ABOUT</a></li>
                        <li class="language_container">
                            <div class="language_link">
                                <div class="language_menu">
                                    <div class="language_menu_passive">
                                        <div id="language_current"></div>
                                    </div>
                                    <div class="language_menu_active_container">
                                        <div class="language_menu_active">
                                            <div>
												<a lang="en" class="language_menu_img_spoiler"><img src="img/lang/en.png"> en</a><br>
                                                <a lang="ru" class="language_menu_img_spoiler"><img src="img/lang/ru.png"> ru</a><br>
												<a lang="tr" class="language_menu_img_spoiler"><img src="img/lang/tr.png"> tr</a><br>
												<!--<a lang="sv" class="language_menu_img_spoiler"><img src="img/lang/sv.png"> sv</a><br>-->
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </li>
                    </ul>
                </div>
                <ul class="nav navbar-nav navbar_right_desktop">
                    
                    <a href="/authenticate" class="steam_link_desktop"><img src="img/signSteam_desktop.png"></a>
                    
                </ul>
            </div>
        </div>
    </nav>
    <div class="container-fluid content">
        <div class="row">
            <div class="steam_unvailable_container" style="display:none">
                <div class="steam_unvailable">STEAM IS UNAVAILABLE NOW!</div>
            </div>
            <div class="trade">
                <div class="make_trade_button_mobile" data-target="" data-toggle="modal" data-backdrop="static">TRADE</div>
            </div>
            <div class="col-lg-5 col-sm-6 col-xs-6">
                <div class="offer_container box_line">
                    <div class="offer_head">
                        <div class="row">
                            <div class="col-xs-6">
                                <div class="offer_header">YOUR OFFER</div>
                            </div>
                            <div class="col-xs-6">
                                <div class="offer_money" id="user_offer_sum">0.00<span class="currency_symbol"> $</span>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="offer_text_container">
                        <div class="offer_container_receive">
                            <div class="offer_text" id="inventory_user_offer_text" style="display:block">SELECT THE ITEMS YOU WANT TO OFFER FROM BELOW
                                <br><br>
								<div>
								<svg version="1.1" xmlns="http://www.w3.org/2000/svg" class="tcon-svgchevron" viewBox="0 0 30 36">
								<path class="a3" d="M0,0l15,16L30,0"></path>
								<path class="a2" d="M0,10l15,16l15-16"></path>
								<path class="a1" d="M0,20l15,16l15-16"></path>
								</svg>
								</div>
                            </div>
                            <div class="invertory_container" id="inventory_user_offer" style="display:none"></div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="col-lg-2 col-sm-2 trade_lg">
				<!--- <div style="text-align: center;"><a target="blank_" href="https://goo.gl/Id2QQf "><img src="https://i.hizliresim.com/Ly9YrV.jpg" class="giveawayimg"></a></div>---!>
                <div class="make_trade_button" data-target="" data-toggle="modal" data-backdrop="static" data-keyboard="false">TRADE</div>
				<div data-toggle="modal" data-target="#popup_tutorial" class="tutorial_button">How to trade?</div>
            </div>
            <div class="col-lg-5 col-sm-6 col-xs-6 col-sm-offset-0 col-lg-offset-0">
                <div class="receive_container box_line">
                    <div class="receive_head">
                        <div class="row">
                            <div class="col-xs-6">
                                <div class="receive_money" id="bots_offer_sum">0.00<span class="currency_symbol"> $</span>
                                </div>
                            </div>
                            <div class="col-xs-6">
                                <div class="receive_header">YOU RECEIVE</div>
                            </div>
                        </div>
                    </div>
                    <div class="offer_text_container">
                        <div class="offer_container_receive">
                            <div id="inventory_bots_offer_text" class="offer_text" style="display:block">SELECT THE ITEMS YOU WANT TO RECEIVE FROM BELOW
                                <br><br>
								<div>
								<svg version="1.1" xmlns="http://www.w3.org/2000/svg" class="tcon-svgchevron" viewBox="0 0 30 36">
								<path class="a3" d="M0,0l15,16L30,0"></path>
								<path class="a2" d="M0,10l15,16l15-16"></path>
								<path class="a1" d="M0,20l15,16l15-16"></path>
								</svg>
								</div>
                            </div>
                            <div id="inventory_bots_offer" class="invertory_container" style="display:block"></div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div class="container-fluid content">
        <div class="row">
            <div class="col-sm-6 col-lg-5">
                <div class="user_things_container box_line">
                    <div class="user_col_lg_head">
                        <div class="row">
                            <div class="col-sm-1 col-xs-1" id="refresh_user_inventory"><img src="img/refresh.svg" class="refresh_user">
                            </div>
                            <div class="col-md-4 col-sm-5 col-xs-7">
                                <div class="order">
								<div class="user_container_text">ORDER BY
									<div class="arrow_static_container">
									<svg version="1.1" class="arrow_static" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 161.2 161.2" enable-background="new 0 0 161.2 161.2" xml:space="preserve">
									<polyline class="svg_cross_popup" fill="none" stroke-width="10" stroke-linecap="round" stroke-miterlimit="10" points="40,5 40,50"></polyline>
									<polyline class="svg_cross_popup" fill="none" stroke-width="10" stroke-linecap="round" stroke-miterlimit="5" points="40,50 20,30"></polyline>
									<polyline class="svg_cross_popup" fill="none" stroke-width="10" stroke-linecap="round" stroke-miterlimit="5" points="40,50 60,30"></polyline>
									</svg>
									</div>
									<div class="user_order_spoiler" style="display: none; margin-top: 5px;">
									<a class="order_link user_sort" type_sort="recent">MOST RECENT</a>
									<a class="order_link user_sort" type_sort="highest">HIGHEST PRICE</a>
									<a class="order_link user_sort" type_sort="lowest">LOWEST PRICE</a>
									</div>
								</div>
								</div>
                            </div>
                            <div class="col-xs-4 col-md-offset-3 col-lg-4 col-md-4 col-sm-6">
                                <div class="offer_input_container">
                                    <div class="input-group">
                                        <input type="text" id="search_left" class="search_form" placeholder="SEARCH...">
										<span class="input_group_offer">
										<div class="offer_search_container_img">
										<img src="img/search.svg" class="offer_search_img">
										</div>
										</span>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="invertory_text_container">
                        <div class="offer_text_user">
                            <div class="offer_container_receive">
								
								<div id="offer_text_user_inventory" class="offer_text" style="display:block">
								<a>
								To create a Trade Offer you need to
								</br></br>
								<a style="cursor: pointer; color: #64ec7b;" href="/authenticate"><img src="img/login_icon.png" class="offer_text_login_img"> Sign-in with Steam</a>
								</br></br>
								Be sure set your inventory privacy to public and enable Steam Guard.
								</a>
								</div>
								<div class="user_icon_box">
								<div><div class="head">%100 Safe</div><i class="fa fa-shield"></i></div>
								<div><div class="head">+%2 Bonus</div><i class="fa fa-gift"></i></div>
								<div><div class="head">Fast Trading</div><i class="fa fa-refresh"></i></div>
								</div>
								
                                <div id="circle_user_inventory" style="display:none">
                                    <div id="circleG_1" class="circleG"></div>
                                    <div id="circleG_2" class="circleG"></div>
                                    <div id="circleG_3" class="circleG"></div>
                                </div>
                                <div id="inventory_user" class="invertory_container" style="display:block"></div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="col-lg-2 market">
			<div class="market_main_container">
			<div class="filter_head">BOT FILTERS</div>

<!--- Filter ---!>

<div class="filter_container">
   <div class="filter_slider_container">
      <div class="filter_cost_container"><input id="minCost" class="cost_min" pattern="[0-9]*" value="" type="text"><i class="fa fa-usd" style="font-size: 22px;"></i><input id="maxCost" class="cost_max" pattern="[0-9]*" value="" type="text"></div>
      <div id="slider" class="ui-slider ui-corner-all ui-slider-horizontal ui-widget ui-widget-content">
         <div class="ui-slider-range ui-corner-all ui-widget-header" style="left: 0%;"></div>
         <span tabindex="0" class="ui-slider-handle ui-corner-all ui-state-default" style="left: 0%;"></span><span tabindex="0" class="ui-slider-handle ui-corner-all ui-state-default" style="left: 100%;"></span>
      </div>
   </div>
   <div class="filter_type_container">
      <div class="filter_type_header" id="current_type">TYPE <span class="fa fa-caret-down"></span></div>
      <div class="filter_type_spoiler">
         <a class="filter_link type_weapon" type="all">All Types</a>
         <div class="filter_type_delimiter"></div>
         <a class="filter_link type_weapon" type="1">Keys</a>
         <div class="filter_type_delimiter"></div>
         <a class="filter_link type_weapon" type="13">Gloves</a>
         <div class="filter_type_delimiter"></div>
         <a class="filter_link type_weapon" type="2">Knife</a>
         <div class="filter_type_delimiter"></div>
         <a class="filter_link type_weapon" type="3">Rifle</a>
         <div class="filter_type_delimiter"></div>
         <a class="filter_link type_weapon" type="4">Sniper Rifle</a>
         <div class="filter_type_delimiter"></div>
         <a class="filter_link type_weapon" type="5">Pistol</a>
         <div class="filter_type_delimiter"></div>
         <a class="filter_link type_weapon" type="6">SMG</a>
         <div class="filter_type_delimiter"></div>
         <a class="filter_link type_weapon" type="7">Shotgun</a>
         <div class="filter_type_delimiter"></div>
         <a class="filter_link type_weapon" type="8">Machinegun</a>
         <div class="filter_type_delimiter"></div>
         <a class="filter_link type_weapon" type="9">Pin</a>
         <div class="filter_type_delimiter"></div>
         <a class="filter_link type_weapon" type="10">Sticker</a>
         <div class="filter_type_delimiter"></div>
         <a class="filter_link type_weapon" type="14">Graffiti</a>
      </div>
   </div>
   <div class="filter_exterior_container">
      <div class="filter_exterior_header" id="current_exterior">EXTERIOR <span class="fa fa-caret-down"></span></div>
      <div class="filter_exterion_spoiler">
         <a class="filter_link exterior" exterior="all">All Exteriors</a>
         <div class="filter_exterior_delimiter"></div>
         <a class="filter_link exterior" exterior="FN">Factory New</a>
         <div class="filter_exterior_delimiter"></div>
         <a class="filter_link exterior" exterior="MW">Minimal Wear</a>
         <div class="filter_exterior_delimiter"></div>
         <a class="filter_link exterior" exterior="FT">Field-Tested</a>
         <div class="filter_exterior_delimiter"></div>
         <a class="filter_link exterior" exterior="WW">Well-Worn</a>
         <div class="filter_exterior_delimiter"></div>
         <a class="filter_link exterior" exterior="BS">Battle-Scarred</a>
      </div>
   </div>
   <div class="preloader"></div>
   <div class="filter_checkbox_container filter_checkbox_container_1">
   <input id="checkbox-id_1_label" onchange="changeBox(1)" type="checkbox">
   <label for="checkbox-id_1_label"></label>
   <label class="filter_checbox_text" for="checkbox-id_1_label">StatTrak™</label>
   </div>
   <div class="filter_checkbox_container">
   <input id="checkbox-id_1_label2" onchange="changeBox(2)" type="checkbox">
   <label for="checkbox-id_1_label2"></label>
   <label class="filter_checbox_text" for="checkbox-id_1_label2">Sticker</label>
   </div>
</div>

<!--- Filter ---!>


			<div class="market_text_head">RATES</div>
			<div class="market_container">
			<div class="rates">
			<h5>Knives</h5>
			<span class="mr-1">95%</span><i class="fa fa-refresh" aria-hidden="true"></i><span class="mr-2">100%</span>
			</div>
			<div class="rates">
			<h5>Rare Weapons</h5>
			<span class="mr-1">95%</span><i class="fa fa-refresh" aria-hidden="true"></i><span class="mr-2">100%</span>
			</div>
			<div class="rates">
			<h5>Weapons</h5>
			<span class="mr-1">95%</span><i class="fa fa-refresh" aria-hidden="true"></i><span class="mr-2">100%</span>
			</div>
			<div class="rates">
			<h5>StatTrak™</h5>
			<span class="mr-1">85%</span><i class="fa fa-refresh" aria-hidden="true"></i><span class="mr-2">100%</span>
			</div>
			<div class="rates">
			<h5>Misc</h5>
			<span class="mr-1">85%</span><i class="fa fa-refresh" aria-hidden="true"></i><span class="mr-2">100%</span>
			</div>
			<i class="fa fa-info-circle depth" aria-hidden="true" data-toggle="modal" data-target="#popup_information"></i>
			
			
			<a class="market_bonus" data-toggle="modal" data-target="#popup_bonus">GET 2% BONUS</a>
            
			</div>
            </div>
			</div>
            <div class="col-sm-6 col-lg-5">
                <div class="bots_container box_line">
                    <div class="col_lg_head">
                        <div class="row">
                            <div class="col-xs-1 col-md-1" id="refresh_bots_inventory"><img src="img/refresh.svg" class="refresh_bots">
                            </div>
                            <div class="col-xs-4 col-md-4 col-sm-5 bot_media">
                                <div class="order">
								<div class="order_text">ORDER BY
									<div class="arrow_static_container">
                                    <?xml version="1.0" encoding="UTF-8" standalone="no" ?>
                                    <!DOCTYPE svg PUBLIC "-//W3C//DTD SVG 1.1//EN" "http://www.w3.org/Graphics/SVG/1.1/DTD/svg11.dtd">
									<svg version="1.1" id="Layer_1" class="arrow_static" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 161.2 161.2" enable-background="new 0 0 161.2 161.2" xml:space="preserve">
									<polyline class="svg_cross_popup" fill="none" stroke-width="10" stroke-linecap="round" stroke-miterlimit="10" points="40,5 40,50"></polyline>
									<polyline class="svg_cross_popup" fill="none" stroke-width="10" stroke-linecap="round" stroke-miterlimit="5" points="40,50 20,30"></polyline>
									<polyline class="svg_cross_popup" fill="none" stroke-width="10" stroke-linecap="round" stroke-miterlimit="5" points="40,50 60,30"></polyline>
									</svg>
									</div>
									<div class="bots_order_spoiler" style="display: none; height: 82.8667px; padding-top: 10px; margin-top: 5px; padding-bottom: 10px; margin-bottom: 0px;">
									<a class="order_link bot_sort" type_sort="highest">HIGHEST PRICE</a>
									<a class="order_link bot_sort" type_sort="lowest">LOWEST PRICE</a>
									</div>
								</div>
								</div>
                            </div>
                            <div class="col-xs-3 col-sm-5 col-md-3">
                                <div class="bot">
                                    <div class="bot_text">
                                        <span id="current_bot">ALL BOTS</span>
                                        <div class="arrow_static_container">
                                        <?xml version="1.0" encoding="UTF-8" standalone="no" ?>
                                        <!DOCTYPE svg PUBLIC "-//W3C//DTD SVG 1.1//EN" "http://www.w3.org/Graphics/SVG/1.1/DTD/svg11.dtd">
                                        <svg version="1.1" id="Layer_1" class="arrow_static" xmlns="http://www.w3.org/2000/svg" xmlns:ev="http://www.w3.org/2001/xml-events" x="0px" y="0px" viewBox="0 0 161.2 161.2" enable-background="new 0 0 161.2 161.2" xml:space="preserve">
                                        <polyline class="svg_cross_popup" fill="none" stroke-width="10" stroke-linecap="round" stroke-miterlimit="10" points="40,5 40,50" />
                                        <polyline class="svg_cross_popup" fill="none" stroke-width="10" stroke-linecap="round" stroke-miterlimit="5" points="40,50 20,30" />
                                        <polyline class="svg_cross_popup" fill="none" stroke-width="10" stroke-linecap="round" stroke-miterlimit="5" points="40,50 60,30" />
                                        </svg>
                                        </div>
                                        <div class="bots_text_spoiler" style="margin-top: 5px;">
                                        <table id="list_bots"></table>
                                        </div>
                                    </div>
                                </div>
                            </div>
                            <div class="col-lg-4 col-md-4 col-sm-6 col-xs-4">
                                <div class="offer_input_container">
                                    <div class="input-group">
                                        <input type="text" id="search_right" class="search_form" placeholder="SEARCH...">
										<span class="input_group_offer">
										<div class="offer_search_container_img"><img src="img/search.svg" class="offer_search_img"></div>
										</span>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="offer_container_inventory_steam">
						<div id="current_bot_bar" class="current_bot_bar" style="display:none"><a><i class="fa fa-info-circle"></i> You can now only select items from: <span id="current_bot_bar_span"></span></a></div>
                        <div id="offer_text_bots_inventory" class="offer_text" style="display:none"></div>
                        <div id="circle_bot_inventory" style="display:none">
                            <div id="circleG_1" class="circleG"></div>
                            <div id="circleG_2" class="circleG"></div>
                            <div id="circleG_3" class="circleG"></div>
                        </div>
                        <div class="invertory_container" id="inventory_bots"></div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div class="market_media">
        <div class="market_text_head">RATES</div>
        <div class="market_container">
			<div class="rates">
			<h5>Knives</h5>
			<span class="mr-1">95%</span><i class="fa fa-refresh" aria-hidden="true"></i><span class="mr-2">100%</span>
			</div>
			<div class="rates">
			<h5>Rare Weapons</h5>
			<span class="mr-1">95%</span><i class="fa fa-refresh" aria-hidden="true"></i><span class="mr-2">100%</span>
			</div>
			<div class="rates">
			<h5>Weapons</h5>
			<span class="mr-1">95%</span><i class="fa fa-refresh" aria-hidden="true"></i><span class="mr-2">100%</span>
			</div>
			<div class="rates">
			<h5>StatTrak™</h5>
			<span class="mr-1">85%</span><i class="fa fa-refresh" aria-hidden="true"></i><span class="mr-2">100%</span>
			</div>
			<div class="rates">
			<h5>Misc</h5>
			<span class="mr-1">85%</span><i class="fa fa-refresh" aria-hidden="true"></i><span class="mr-2">100%</span>
			</div>
			<i class="fa fa-info-circle depth" aria-hidden="true" data-toggle="modal" data-target="#popup_information"></i>
			
			
			<a class="market_bonus" data-toggle="modal" data-target="#popup_bonus">GET 2% BONUS</a>
            
        </div>
    </div>
    </div>
    <footer>
		<div class="footer-logo">
			<img src="img/skintradeicon.png" title="by MCSkillet">
		</div>
		<div class="left">
			<span>
			Skin.Trade © 2017 - <a href="/tos" style="text-decoration: none;color: #00e36a;font-size: 13px;">Terms of Service</a><br>
			<a>CS:GO Trading Marketplace.</a><br>
			<a>Skin.Trade is not affiliated with Valve Corporation.</a>
			</span>
		</div>
		<div class="mid">
		</div>
		<div class="right">
			<span>
			<a class="fa fa-steam fa-2x social" href="https://steamcommunity.com/groups/SkinTrade" target="blank_"></a>
			<a class="fa fa-twitter fa-2x social" href="https://twitter.com/SkinTrade" target="blank_"></a>
			</span>
		</div>
    </footer>

    <!-- popup -->
    <div class="modal fade" id="popup_link_trade" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true">
        <div class="modal-dialog">
            <div class="header_popup">
                <div class="close_window" data-dismiss="modal">
					<i class="fa fa-times" aria-hidden="true"></i>
                </div>
                <div class="header_popup_text">YOUR TRADING URL</div>
            </div>
            <div class="popup_link_container">
                <div class="popup_link_container_header"><a class="popup_link_link" target="_blank" href="https://steamcommunity.com/id/me/tradeoffers/privacy#trade_offer_access_url"><i class="fa fa-external-link" aria-hidden="true"></i> Click here to find your Trade URL</a>
                </div>
                
                <div class="popup_link_container_text">
                    <div class="input-group"><span class="input-group-addon">TRADE-OFFER URL:</span>
                        <input type="text" id="trade_link" class="popup_link_form_control" placeholder="Enter here your Trade URL">
                    </div>
                </div>
                <div class="popup_link_trade_button">
                    <div class="popup_link_trade_button_text" onclick="addTradeLink()">UPDATE</div>
                </div>
				<div class="alert_trade_link_update" id="alert_trade_link_update"></div>
                <div class="popup_link_trade_text">By adding your Steam Trade url you make it possible for our bots to send<br>you a trade offer without the need of adding you as a friend on Steam.<br>This is totally safe and no items can be traded before you<br>have inspected and accepted the offer from your steam page.</div>
            </div>
        </div>
    </div>
    <div class="modal fade" id="popup_tutorial" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true">
        <div class="modal-dialog">
            <div class="header_popup">
                <div class="close_window" data-dismiss="modal">
					<i class="fa fa-times" aria-hidden="true"></i>
                </div>
                <div class="header_popup_text">HOW TO TRADE?</div>
            </div>
            <div class="popup_link_container">
			<div><div style="color: #ffffff;padding: 15px;line-height: 30px;">- This is an automated CS:GO skin trading tool that allows you to trade your skins.<br>- SKIN.TRADE does not require you to "Deposit" items.<br>- We do NOT have a balance/credit system. We only offer "Item to Item" trades.</div></div>
			
			<div><div class="tutorial_text"><div class="tutorial_circle">1</div>&nbsp;Go your Steam Profile Privacy Settings and make sure your inventory is set to "Public."</div></div>
			<br><br>
			<div><div class="tutorial_text"><div class="tutorial_circle">2</div>&nbsp;Login to the site through Steam.</div></div>
			<br><br>
			<div><div class="tutorial_text"><div class="tutorial_circle">3</div>&nbsp;Set your Steam Trade URL and <img src="img/refresh.svg" style="width: 15px; height: 15px;"> refresh your inventory to make sure its updated.</div></div>
			<br><br>
			<div><div class="tutorial_text"><div class="tutorial_circle">4</div>&nbsp;Select the items you want to trade from your inventory and the bots inventory.</div></div>
			<br><br>
			<div><div class="tutorial_text"><div class="tutorial_circle">5</div>&nbsp;Click on the big "TRADE" button between your inventory and the bots inventory.</div></div>
			<br><br>
			<div><div class="tutorial_text"><div class="tutorial_circle">6</div>&nbsp;Wait until the notification disappears from your screen andyou will get the trade-offer with the items you would like to trade for on Steam.</div></div>
			<br><br><br><br>
            </div>
        </div>
    </div>
    <div class="modal fade bs-example-modal-lg" id="popup_information" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true">
        <div class="modal-dialog modal-lg">
            <div class="header_popup">
                <div class="close_window" data-dismiss="modal">
					<i class="fa fa-times" aria-hidden="true"></i>
                </div>
                <div class="header_popup_text">PRICE CALCULATION</div>
            </div>
            <div class="popup_calc_container">
        <div class="text text_big">We are trying to get the most accurate prices on the site by analysing the Steam Market.<br>In this respect, we offer you a fairer trade.</div>
        <hr>
        <div class="text text_big">Calculation example: Let's say that you have a knife. The Steam market price of that knife is estimated to be $50 and we are giving you 95% of the market price (the Market Rate). The mathematics part is going to look like this:</div>

        <div class="scheme">
            <div class="line">
                <div>50</div>
                <div>x</div>
                <div>0.95</div>
                <div>=</div>
                <div>47.5</div>
            </div>
            <div class="line">
                <div>Price of The Item</div>
                <div></div>
                <div>What We Offer</div>
                <div></div>
                <div>Amount You Will Get</div>
            </div>
        </div>
        <br><hr>
        <div class="unnaccepted">
            <ul>
                <li>Unaccepted Items:</li>
                <li><span>Too Low</span>: We do not currently accept items priced this low.</li>
                <li><span>Overstock</span>: We currently accept limited quantity of this item.</li>
                <li><span>Unstable</span>: We do not accept unstable priced items. (Low sales volume / Jumping prices).</li>
                <li><span>Too High</span>: We do not currently accept items priced this high.</li>
            </ul>
        </div>
        <hr>
        <div class="text text_big"><span class="tit">Our Cut:</span>We take a 3-5% cut on all trades (detailed information on the rates table). We think that this cut-off is fair because we take a risk and take a broad inventory to present all kinds of things to you. Due to the price fluctuations of the steam, there is a large amount of loss.</div>
            </div>
        </div>
    </div>
    <div class="modal fade bs-example-modal-lg" id="popup_bonus" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true">
        <div class="modal-dialog modal-lg">
            <div class="header_popup">
                <div class="close_window" data-dismiss="modal">
					<i class="fa fa-times" aria-hidden="true"></i>
                </div>
                <div class="header_popup_text">GET 2% BONUS</div>
            </div>
            <div class="popup_bonus_container">
        <div class="status">STATUS: 
                
                <span class="red">Bonus inactive</span>
                
        </div>
        <hr>
        <div class="step"><div>Step 1:</div>Add SKIN.TRADE to your Steam nickname. <a href="https://steamcommunity.com/id/user/edit" target="blank_" style="cursor: pointer;">(Click here to add)</a></div> 
        <hr>
        <div class="step"><div>Step 2:</div>Re-login to SKIN.TRADE <a href="/logout" target="blank_" style="cursor: pointer;">(Click here to logout)</a></div>
        <hr><br>
        <div class="result">Result: +2% on each item type.</div>

        <div class="information market_rates">
            <ul>
                <li class="tit">Before</li>
                    <li class="cat knives">Knives</li>
                    <li>95%<span>|</span>100%</li>
                    <li class="cat rare_weapons">Rare Weapons</li>
                    <li>93%<span>|</span>100%</li>
                    <li class="cat weapons">Weapons</li>
                    <li>95%<span>|</span>100%</li>
                    <li class="cat misc">Misc</li>
                    <li>85%<span>|</span>100%</li>
                    <li class="cat stattrak">StatTrak™</li>
                    <li>85%<span>|</span>100%</li>              
            </ul>
            <ul>
                <li class="tit">After</li>
                    <li class="cat knives">Knives</li>
                    <li>97%<span>|</span>100%</li>
                    <li class="cat rare_weapons">Rare Weapons</li>
                    <li>95%<span>|</span>100%</li>
                    <li class="cat weapons">Weapons</li>
                    <li>97%<span>|</span>100%</li>
                    <li class="cat misc">Misc</li>
                    <li>87%<span>|</span>100%</li>
                    <li class="cat stattrak">StatTrak™</li>
                    <li>87%<span>|</span>100%</li>          
            </ul>
        </div>
            </div>
        </div>
    </div>
    <div class="modal fade" id="myModal_wait" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true">
        <div class="modal-dialog">
            <div class="header_popup">
                <div class="close_window" id="wait_close" data-dismiss="modal" style="display: none">
					<i class="fa fa-times" aria-hidden="true"></i>
                </div>
                <div class="header_popup_text">TRADE OFFER</div>
            </div>
            <div class="popup_waiting_container">
                <div id="trade-steps-box" class="row">
                    <div class="col-md-3 col-xs-6">
                        <div class="cross_svg" id="step1"></div>
                        <div class="popup_waiting_text">Get Request</div>
                    </div>
                    <div class="col-md-3 col-xs-6">
                        <div class="checkmark" id="step2"></div>
                        <div class="popup_waiting_text">Validation<br>Request</div>
                    </div>
                    <div class="col-md-3 col-xs-6">
                        <div class="checkmark" id="step3"></div>
                        <div class="popup_waiting_text">Send Offer</div>
                    </div>
                    <div class="col-md-3 col-xs-6">
                        <div class="checkmark" id="step4"></div>
                        <div class="popup_waiting_text">Offer<br>Confirmation</div>
                    </div>
					<br>
                </div>
                <div class="popup_waiting_container_message">
                    <div class="popup_waiting_link" id="text_after_send_offer"></div>
                </div>
            </div>
        </div>
    </div>
	<!-- popup -->

    <ul class="dropdown-menu" role="menu" id="contextMenu"></ul>
<!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=UA-109410186-1"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'UA-109410186-1');
</script>
    <script type="text/javascript">
        if (typeof localStorage === 'object') {
            try {
                localStorage.setItem('localStorage', 1);
                localStorage.removeItem('localStorage');
            } catch (e) {
                Storage.prototype._setItem = Storage.prototype.setItem;
                Storage.prototype.setItem = function() {};
                alert('Your web browser does not support storing settings locally. In Safari, the most common cause of this is using "Private Browsing Mode". Some settings may not save or some features may not work properly for you.');
            }
        }
    </script>
	<script type="text/javascript" src="js/jquery.js"></script>
    <script type="text/javascript" src="js/all.js?v=27"></script>
</body>

</html>
