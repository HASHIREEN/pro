# pro


<!DOCTYPE html>
<html lang="en-US">
<head>
        	
            
            
        <meta charset="UTF-8"/>
        <link rel="profile" href="http://gmpg.org/xfn/11"/>
        <link rel="pingback" href="https://www.smsa-sji.sg/xmlrpc.php"/>
                <meta name="viewport" content="width=device-width,initial-scale=1,user-scalable=no">
        
	<title>SMSA &#8211; Beyond Soccer. Pride of Lasallians.</title>
		<script type="text/javascript">
		//<![CDATA[
		LeagueManagerAjaxL10n = {
			blogUrl: "https://www.smsa-sji.sg",
			//pluginPath: "/home/customer/www/smsa-sji.sg/public_html/wp-content/plugins/leaguemanager",
			pluginUrl: "https://www.smsa-sji.sg/wp-content/plugins/leaguemanager",
			requestUrl: "https://www.smsa-sji.sg/wp-admin/admin-ajax.php",
			Edit: "Edit",
			Post: "Post",
			Save: "Save",
			Cancel: "Cancel",
			pleaseWait: "Please wait...",
			Revisions: "Page Revisions",
			Time: "Insert time",
			Options: "Options",
			Delete: "Delete"
	 	}
		//]]>
		</script>
		<script type="application/javascript">var qodeCoreAjaxUrl = "https://www.smsa-sji.sg/wp-admin/admin-ajax.php"</script><meta name='robots' content='max-image-preview:large' />
<link rel='dns-prefetch' href='//maps.googleapis.com' />
<link rel='dns-prefetch' href='//fonts.googleapis.com' />
<link rel="alternate" type="application/rss+xml" title="SMSA &raquo; Feed" href="https://www.smsa-sji.sg/feed/" />
<link rel="alternate" type="application/rss+xml" title="SMSA &raquo; Comments Feed" href="https://www.smsa-sji.sg/comments/feed/" />
		<!-- This site uses the Google Analytics by ExactMetrics plugin v7.10.0 - Using Analytics tracking - https://www.exactmetrics.com/ -->
							<script
				src="//www.googletagmanager.com/gtag/js?id=UA-109137141-1"  data-cfasync="false" data-wpfc-render="false" type="text/javascript" async></script>
			<script data-cfasync="false" data-wpfc-render="false" type="text/javascript">
				var em_version = '7.10.0';
				var em_track_user = true;
				var em_no_track_reason = '';
				
								var disableStrs = [
															'ga-disable-UA-109137141-1',
									];

				/* Function to detect opted out users */
				function __gtagTrackerIsOptedOut() {
					for (var index = 0; index < disableStrs.length; index++) {
						if (document.cookie.indexOf(disableStrs[index] + '=true') > -1) {
							return true;
						}
					}

					return false;
				}

				/* Disable tracking if the opt-out cookie exists. */
				if (__gtagTrackerIsOptedOut()) {
					for (var index = 0; index < disableStrs.length; index++) {
						window[disableStrs[index]] = true;
					}
				}

				/* Opt-out function */
				function __gtagTrackerOptout() {
					for (var index = 0; index < disableStrs.length; index++) {
						document.cookie = disableStrs[index] + '=true; expires=Thu, 31 Dec 2099 23:59:59 UTC; path=/';
						window[disableStrs[index]] = true;
					}
				}

				if ('undefined' === typeof gaOptout) {
					function gaOptout() {
						__gtagTrackerOptout();
					}
				}
								window.dataLayer = window.dataLayer || [];

				window.ExactMetricsDualTracker = {
					helpers: {},
					trackers: {},
				};
				if (em_track_user) {
					function __gtagDataLayer() {
						dataLayer.push(arguments);
					}

					function __gtagTracker(type, name, parameters) {
						if (!parameters) {
							parameters = {};
						}

						if (parameters.send_to) {
							__gtagDataLayer.apply(null, arguments);
							return;
						}

						if (type === 'event') {
							
														parameters.send_to = exactmetrics_frontend.ua;
							__gtagDataLayer(type, name, parameters);
													} else {
							__gtagDataLayer.apply(null, arguments);
						}
					}

					__gtagTracker('js', new Date());
					__gtagTracker('set', {
						'developer_id.dNDMyYj': true,
											});
															__gtagTracker('config', 'UA-109137141-1', {"forceSSL":"true"} );
										window.gtag = __gtagTracker;										(function () {
						/* https://developers.google.com/analytics/devguides/collection/analyticsjs/ */
						/* ga and __gaTracker compatibility shim. */
						var noopfn = function () {
							return null;
						};
						var newtracker = function () {
							return new Tracker();
						};
						var Tracker = function () {
							return null;
						};
						var p = Tracker.prototype;
						p.get = noopfn;
						p.set = noopfn;
						p.send = function () {
							var args = Array.prototype.slice.call(arguments);
							args.unshift('send');
							__gaTracker.apply(null, args);
						};
						var __gaTracker = function () {
							var len = arguments.length;
							if (len === 0) {
								return;
							}
							var f = arguments[len - 1];
							if (typeof f !== 'object' || f === null || typeof f.hitCallback !== 'function') {
								if ('send' === arguments[0]) {
									var hitConverted, hitObject = false, action;
									if ('event' === arguments[1]) {
										if ('undefined' !== typeof arguments[3]) {
											hitObject = {
												'eventAction': arguments[3],
												'eventCategory': arguments[2],
												'eventLabel': arguments[4],
												'value': arguments[5] ? arguments[5] : 1,
											}
										}
									}
									if ('pageview' === arguments[1]) {
										if ('undefined' !== typeof arguments[2]) {
											hitObject = {
												'eventAction': 'page_view',
												'page_path': arguments[2],
											}
										}
									}
									if (typeof arguments[2] === 'object') {
										hitObject = arguments[2];
									}
									if (typeof arguments[5] === 'object') {
										Object.assign(hitObject, arguments[5]);
									}
									if ('undefined' !== typeof arguments[1].hitType) {
										hitObject = arguments[1];
										if ('pageview' === hitObject.hitType) {
											hitObject.eventAction = 'page_view';
										}
									}
									if (hitObject) {
										action = 'timing' === arguments[1].hitType ? 'timing_complete' : hitObject.eventAction;
										hitConverted = mapArgs(hitObject);
										__gtagTracker('event', action, hitConverted);
									}
								}
								return;
							}

							function mapArgs(args) {
								var arg, hit = {};
								var gaMap = {
									'eventCategory': 'event_category',
									'eventAction': 'event_action',
									'eventLabel': 'event_label',
									'eventValue': 'event_value',
									'nonInteraction': 'non_interaction',
									'timingCategory': 'event_category',
									'timingVar': 'name',
									'timingValue': 'value',
									'timingLabel': 'event_label',
									'page': 'page_path',
									'location': 'page_location',
									'title': 'page_title',
								};
								for (arg in args) {
																		if (!(!args.hasOwnProperty(arg) || !gaMap.hasOwnProperty(arg))) {
										hit[gaMap[arg]] = args[arg];
									} else {
										hit[arg] = args[arg];
									}
								}
								return hit;
							}

							try {
								f.hitCallback();
							} catch (ex) {
							}
						};
						__gaTracker.create = newtracker;
						__gaTracker.getByName = newtracker;
						__gaTracker.getAll = function () {
							return [];
						};
						__gaTracker.remove = noopfn;
						__gaTracker.loaded = true;
						window['__gaTracker'] = __gaTracker;
					})();
									} else {
										console.log("");
					(function () {
						function __gtagTracker() {
							return null;
						}

						window['__gtagTracker'] = __gtagTracker;
						window['gtag'] = __gtagTracker;
					})();
									}
			</script>
				<!-- / Google Analytics by ExactMetrics -->
		<script type="text/javascript">
/* <![CDATA[ */
window._wpemojiSettings = {"baseUrl":"https:\/\/s.w.org\/images\/core\/emoji\/15.0.3\/72x72\/","ext":".png","svgUrl":"https:\/\/s.w.org\/images\/core\/emoji\/15.0.3\/svg\/","svgExt":".svg","source":{"concatemoji":"https:\/\/www.smsa-sji.sg\/wp-includes\/js\/wp-emoji-release.min.js?ver=6.5.3"}};
/*! This file is auto-generated */
!function(i,n){var o,s,e;function c(e){try{var t={supportTests:e,timestamp:(new Date).valueOf()};sessionStorage.setItem(o,JSON.stringify(t))}catch(e){}}function p(e,t,n){e.clearRect(0,0,e.canvas.width,e.canvas.height),e.fillText(t,0,0);var t=new Uint32Array(e.getImageData(0,0,e.canvas.width,e.canvas.height).data),r=(e.clearRect(0,0,e.canvas.width,e.canvas.height),e.fillText(n,0,0),new Uint32Array(e.getImageData(0,0,e.canvas.width,e.canvas.height).data));return t.every(function(e,t){return e===r[t]})}function u(e,t,n){switch(t){case"flag":return n(e,"\ud83c\udff3\ufe0f\u200d\u26a7\ufe0f","\ud83c\udff3\ufe0f\u200b\u26a7\ufe0f")?!1:!n(e,"\ud83c\uddfa\ud83c\uddf3","\ud83c\uddfa\u200b\ud83c\uddf3")&&!n(e,"\ud83c\udff4\udb40\udc67\udb40\udc62\udb40\udc65\udb40\udc6e\udb40\udc67\udb40\udc7f","\ud83c\udff4\u200b\udb40\udc67\u200b\udb40\udc62\u200b\udb40\udc65\u200b\udb40\udc6e\u200b\udb40\udc67\u200b\udb40\udc7f");case"emoji":return!n(e,"\ud83d\udc26\u200d\u2b1b","\ud83d\udc26\u200b\u2b1b")}return!1}function f(e,t,n){var r="undefined"!=typeof WorkerGlobalScope&&self instanceof WorkerGlobalScope?new OffscreenCanvas(300,150):i.createElement("canvas"),a=r.getContext("2d",{willReadFrequently:!0}),o=(a.textBaseline="top",a.font="600 32px Arial",{});return e.forEach(function(e){o[e]=t(a,e,n)}),o}function t(e){var t=i.createElement("script");t.src=e,t.defer=!0,i.head.appendChild(t)}"undefined"!=typeof Promise&&(o="wpEmojiSettingsSupports",s=["flag","emoji"],n.supports={everything:!0,everythingExceptFlag:!0},e=new Promise(function(e){i.addEventListener("DOMContentLoaded",e,{once:!0})}),new Promise(function(t){var n=function(){try{var e=JSON.parse(sessionStorage.getItem(o));if("object"==typeof e&&"number"==typeof e.timestamp&&(new Date).valueOf()<e.timestamp+604800&&"object"==typeof e.supportTests)return e.supportTests}catch(e){}return null}();if(!n){if("undefined"!=typeof Worker&&"undefined"!=typeof OffscreenCanvas&&"undefined"!=typeof URL&&URL.createObjectURL&&"undefined"!=typeof Blob)try{var e="postMessage("+f.toString()+"("+[JSON.stringify(s),u.toString(),p.toString()].join(",")+"));",r=new Blob([e],{type:"text/javascript"}),a=new Worker(URL.createObjectURL(r),{name:"wpTestEmojiSupports"});return void(a.onmessage=function(e){c(n=e.data),a.terminate(),t(n)})}catch(e){}c(n=f(s,u,p))}t(n)}).then(function(e){for(var t in e)n.supports[t]=e[t],n.supports.everything=n.supports.everything&&n.supports[t],"flag"!==t&&(n.supports.everythingExceptFlag=n.supports.everythingExceptFlag&&n.supports[t]);n.supports.everythingExceptFlag=n.supports.everythingExceptFlag&&!n.supports.flag,n.DOMReady=!1,n.readyCallback=function(){n.DOMReady=!0}}).then(function(){return e}).then(function(){var e;n.supports.everything||(n.readyCallback(),(e=n.source||{}).concatemoji?t(e.concatemoji):e.wpemoji&&e.twemoji&&(t(e.twemoji),t(e.wpemoji)))}))}((window,document),window._wpemojiSettings);
/* ]]> */
</script>
<link rel='stylesheet' id='formidable-css' href='https://www.smsa-sji.sg/wp-content/plugins/formidable/css/formidableforms.css?ver=812245' type='text/css' media='all' />
<link rel='stylesheet' id='mec-font-icons-css' href='https://www.smsa-sji.sg/wp-content/plugins/modern-events-calendar/assets/css/iconfonts.css?ver=6.5.3' type='text/css' media='all' />
<link rel='stylesheet' id='mec-frontend-style-css' href='https://www.smsa-sji.sg/wp-content/plugins/modern-events-calendar/assets/css/frontend.min.css?ver=6.5.3' type='text/css' media='all' />
<link rel='stylesheet' id='mec-google-fonts-css' href='//fonts.googleapis.com/css?family=Montserrat%3A400%2C700%7CRoboto%3A100%2C300%2C400%2C700&#038;ver=6.5.3' type='text/css' media='all' />
<link rel='stylesheet' id='mec-dynamic-styles-css' href='https://www.smsa-sji.sg/wp-content/plugins/modern-events-calendar/assets/css/dyncss.css?ver=6.5.3' type='text/css' media='all' />
<style id='mec-dynamic-styles-inline-css' type='text/css'>
.mec-wrap h1, .mec-wrap h2, .mec-wrap h3, .mec-wrap h4, .mec-wrap h5, .mec-wrap h6,.entry-content .mec-wrap h1, .entry-content .mec-wrap h2, .entry-content .mec-wrap h3,.entry-content  .mec-wrap h4, .entry-content .mec-wrap h5, .entry-content .mec-wrap h6{ font-family: 'Open Sans', Helvetica, Arial, sans-serif;}.mec-event-content p, .mec-wrap p { font-family: 'Open Sans',sans-serif; font-weight:300;}.mec-wrap.colorskin-custom .mec-color, .mec-wrap.colorskin-custom .mec-event-sharing-wrap .mec-event-sharing > li:hover a, .mec-wrap.colorskin-custom .mec-color-hover:hover, .mec-wrap.colorskin-custom .mec-color-before *:before ,.mec-wrap.colorskin-custom .mec-widget .mec-event-grid-classic.owl-carousel .owl-controls .owl-buttons i,.mec-wrap.colorskin-custom .mec-event-list-classic a.magicmore:hover,.mec-wrap.colorskin-custom .mec-event-grid-simple:hover .mec-event-title,.mec-wrap.colorskin-custom .mec-single-event .mec-event-meta dd.mec-events-event-categories:before,.mec-wrap.colorskin-custom .mec-single-event-date:before,.mec-wrap.colorskin-custom .mec-single-event-time:before,.mec-wrap.colorskin-custom .mec-events-meta-group.mec-events-meta-group-venue:before,.mec-wrap.colorskin-custom .mec-calendar .mec-calendar-side .mec-previous-month i,.mec-wrap.colorskin-custom .mec-calendar .mec-calendar-side .mec-next-month,.mec-wrap.colorskin-custom .mec-calendar .mec-calendar-side .mec-previous-month:hover,.mec-wrap.colorskin-custom .mec-calendar .mec-calendar-side .mec-next-month:hover,.mec-wrap.colorskin-custom .mec-calendar.mec-event-calendar-classic dt.mec-selected-day:hover,.mec-wrap.colorskin-custom .mec-infowindow-wp h5 a:hover, .colorskin-custom .mec-events-meta-group-countdown .mec-end-counts h3,.mec-calendar .mec-calendar-side .mec-next-month i,.mec-wrap .mec-totalcal-box i,.mec-calendar .mec-event-article .mec-event-title a:hover,.mec-attendees-list-details .mec-attendee-profile-link a:hover, .mec-next-event-details li i,.mec-next-event-details a{color: #0d723b}.mec-wrap.colorskin-custom .mec-event-sharing .mec-event-share:hover .event-sharing-icon,.mec-wrap.colorskin-custom .mec-event-grid-clean .mec-event-date,.mec-wrap.colorskin-custom .mec-event-list-modern .mec-event-sharing > li:hover a i,.mec-wrap.colorskin-custom .mec-event-list-modern .mec-event-sharing .mec-event-share:hover .mec-event-sharing-icon,.mec-wrap.colorskin-custom .mec-event-list-modern .mec-event-sharing li:hover a i,.mec-wrap.colorskin-custom .mec-calendar:not(.mec-event-calendar-classic) .mec-selected-day,.mec-wrap.colorskin-custom .mec-calendar .mec-selected-day:hover,.mec-wrap.colorskin-custom .mec-calendar .mec-calendar-row  dt.mec-has-event:hover,.mec-wrap.colorskin-custom .mec-calendar .mec-has-event:after, .mec-wrap.colorskin-custom .mec-bg-color, .mec-wrap.colorskin-custom .mec-bg-color-hover:hover, .colorskin-custom .mec-event-sharing-wrap:hover > li, .mec-wrap.colorskin-custom .mec-totalcal-box .mec-totalcal-view span.mec-totalcalview-selected,.mec-wrap .flip-clock-wrapper ul li a div div.inn,.mec-wrap .mec-totalcal-box .mec-totalcal-view span.mec-totalcalview-selected,.event-carousel-type1-head .mec-event-date-carousel,.mec-event-countdown-style3 .mec-event-date,#wrap .mec-wrap article.mec-event-countdown-style1,.mec-event-countdown-style1 .mec-event-countdown-part3 a.mec-event-button,.mec-wrap .mec-event-countdown-style2,.mec-map-get-direction-btn-cnt input[type="submit"],.mec-booking button,span.mec-marker-wrap{background-color: #0d723b;}.mec-wrap.colorskin-custom .mec-event-list-modern .mec-event-sharing > li:hover a i,.mec-wrap.colorskin-custom .mec-event-list-modern .mec-event-sharing .mec-event-share:hover .mec-event-sharing-icon,.mec-wrap.colorskin-custom .mec-event-list-standard .mec-month-divider span:before,.mec-wrap.colorskin-custom .mec-single-event .mec-social-single:before,.mec-wrap.colorskin-custom .mec-single-event .mec-frontbox-title:before,.mec-wrap.colorskin-custom .mec-calendar .mec-calendar-events-side .mec-table-side-day, .mec-wrap.colorskin-custom .mec-border-color, .mec-wrap.colorskin-custom .mec-border-color-hover:hover, .colorskin-custom .mec-single-event .mec-frontbox-title:before, .colorskin-custom .mec-single-event .mec-events-meta-group-booking form > h4:before, .mec-wrap.colorskin-custom .mec-totalcal-box .mec-totalcal-view span.mec-totalcalview-selected,.mec-wrap .mec-totalcal-box .mec-totalcal-view span.mec-totalcalview-selected,.event-carousel-type1-head .mec-event-date-carousel:after{border-color: #0d723b;}.mec-event-countdown-style3 .mec-event-date:after{border-bottom-color:#0d723b;}.mec-wrap article.mec-event-countdown-style1 .mec-event-countdown-part2:after{border-color: transparent transparent transparent #0d723b;}
</style>
<link rel='stylesheet' id='mec-custom-google-font-css' href='https://fonts.googleapis.com/css?family=Open+Sans%3A300%2C+300italic%2C+regular%2C+italic%2C+600%2C+600italic%2C+700%2C+700italic%2C+800%2C+800italic%2C+%7COpen+Sans%3A800italic%2C+800italic%2C+800italic%2C+800italic%2C+800italic%2C+800italic%2C+800italic%2C+800italic%2C+800italic%2C+800italic%2C+&#038;subset=latin%2Clatin-ext' type='text/css' media='all' />
<link rel='stylesheet' id='mec-lity-style-css' href='https://www.smsa-sji.sg/wp-content/plugins/modern-events-calendar/assets/packages/lity/lity.min.css?ver=6.5.3' type='text/css' media='all' />
<link rel='stylesheet' id='layerslider-css' href='https://www.smsa-sji.sg/wp-content/plugins/LayerSlider/static/layerslider/css/layerslider.css?ver=6.3.0' type='text/css' media='all' />
<link rel='stylesheet' id='dashicons-css' href='https://www.smsa-sji.sg/wp-includes/css/dashicons.min.css?ver=6.5.3' type='text/css' media='all' />
<link rel='stylesheet' id='thickbox-css' href='https://www.smsa-sji.sg/wp-includes/js/thickbox/thickbox.css?ver=6.5.3' type='text/css' media='all' />
<link rel='stylesheet' id='leaguemanager-css' href='https://www.smsa-sji.sg/wp-content/plugins/leaguemanager/style.css?ver=1.0' type='text/css' media='all' />
<style id='leaguemanager-inline-css' type='text/css'>

table.leaguemanager th,
div.matchlist table.leaguemanager th {
	background-color: #dddddd;
}
table.leaguemanager tr {
	background-color: #ffffff;
}
table.leaguemanager tr.alternate {
	background-color: #efefef;
}
table.standingstable tr.ascend .rank,
table.standingstable tr.ascend.alternate .rank {
	background-color: #ffffff;
}
table.standingstable .descend .rank,
table.standingstable .descend.alternate .rank {
	background-color: #ffffff;
}
table.crosstable th,
table.crosstable td {
	border: 1px solid #efefef;
}

</style>
<link rel='stylesheet' id='jquery-ui-css' href='https://www.smsa-sji.sg/wp-content/plugins/leaguemanager/css/jquery/jquery-ui.min.css?ver=1.11.4' type='text/css' media='all' />
<link rel='stylesheet' id='jquery-ui-structure-css' href='https://www.smsa-sji.sg/wp-content/plugins/leaguemanager/css/jquery/jquery-ui.structure.min.css?ver=1.11.4' type='text/css' media='all' />
<link rel='stylesheet' id='jquery-ui-theme-css' href='https://www.smsa-sji.sg/wp-content/plugins/leaguemanager/css/jquery/jquery-ui.theme.min.css?ver=1.11.4' type='text/css' media='all' />
<style id='wp-emoji-styles-inline-css' type='text/css'>

	img.wp-smiley, img.emoji {
		display: inline !important;
		border: none !important;
		box-shadow: none !important;
		height: 1em !important;
		width: 1em !important;
		margin: 0 0.07em !important;
		vertical-align: -0.1em !important;
		background: none !important;
		padding: 0 !important;
	}
</style>
<link rel='stylesheet' id='wp-block-library-css' href='https://www.smsa-sji.sg/wp-includes/css/dist/block-library/style.min.css?ver=6.5.3' type='text/css' media='all' />
<link rel='stylesheet' id='wc-block-vendors-style-css' href='https://www.smsa-sji.sg/wp-content/plugins/woocommerce/packages/woocommerce-blocks/build/vendors-style.css?ver=4.4.3' type='text/css' media='all' />
<link rel='stylesheet' id='wc-block-style-css' href='https://www.smsa-sji.sg/wp-content/plugins/woocommerce/packages/woocommerce-blocks/build/style.css?ver=4.4.3' type='text/css' media='all' />
<style id='classic-theme-styles-inline-css' type='text/css'>
/*! This file is auto-generated */
.wp-block-button__link{color:#fff;background-color:#32373c;border-radius:9999px;box-shadow:none;text-decoration:none;padding:calc(.667em + 2px) calc(1.333em + 2px);font-size:1.125em}.wp-block-file__button{background:#32373c;color:#fff;text-decoration:none}
</style>
<style id='global-styles-inline-css' type='text/css'>
body{--wp--preset--color--black: #000000;--wp--preset--color--cyan-bluish-gray: #abb8c3;--wp--preset--color--white: #ffffff;--wp--preset--color--pale-pink: #f78da7;--wp--preset--color--vivid-red: #cf2e2e;--wp--preset--color--luminous-vivid-orange: #ff6900;--wp--preset--color--luminous-vivid-amber: #fcb900;--wp--preset--color--light-green-cyan: #7bdcb5;--wp--preset--color--vivid-green-cyan: #00d084;--wp--preset--color--pale-cyan-blue: #8ed1fc;--wp--preset--color--vivid-cyan-blue: #0693e3;--wp--preset--color--vivid-purple: #9b51e0;--wp--preset--gradient--vivid-cyan-blue-to-vivid-purple: linear-gradient(135deg,rgba(6,147,227,1) 0%,rgb(155,81,224) 100%);--wp--preset--gradient--light-green-cyan-to-vivid-green-cyan: linear-gradient(135deg,rgb(122,220,180) 0%,rgb(0,208,130) 100%);--wp--preset--gradient--luminous-vivid-amber-to-luminous-vivid-orange: linear-gradient(135deg,rgba(252,185,0,1) 0%,rgba(255,105,0,1) 100%);--wp--preset--gradient--luminous-vivid-orange-to-vivid-red: linear-gradient(135deg,rgba(255,105,0,1) 0%,rgb(207,46,46) 100%);--wp--preset--gradient--very-light-gray-to-cyan-bluish-gray: linear-gradient(135deg,rgb(238,238,238) 0%,rgb(169,184,195) 100%);--wp--preset--gradient--cool-to-warm-spectrum: linear-gradient(135deg,rgb(74,234,220) 0%,rgb(151,120,209) 20%,rgb(207,42,186) 40%,rgb(238,44,130) 60%,rgb(251,105,98) 80%,rgb(254,248,76) 100%);--wp--preset--gradient--blush-light-purple: linear-gradient(135deg,rgb(255,206,236) 0%,rgb(152,150,240) 100%);--wp--preset--gradient--blush-bordeaux: linear-gradient(135deg,rgb(254,205,165) 0%,rgb(254,45,45) 50%,rgb(107,0,62) 100%);--wp--preset--gradient--luminous-dusk: linear-gradient(135deg,rgb(255,203,112) 0%,rgb(199,81,192) 50%,rgb(65,88,208) 100%);--wp--preset--gradient--pale-ocean: linear-gradient(135deg,rgb(255,245,203) 0%,rgb(182,227,212) 50%,rgb(51,167,181) 100%);--wp--preset--gradient--electric-grass: linear-gradient(135deg,rgb(202,248,128) 0%,rgb(113,206,126) 100%);--wp--preset--gradient--midnight: linear-gradient(135deg,rgb(2,3,129) 0%,rgb(40,116,252) 100%);--wp--preset--font-size--small: 13px;--wp--preset--font-size--medium: 20px;--wp--preset--font-size--large: 36px;--wp--preset--font-size--x-large: 42px;--wp--preset--spacing--20: 0.44rem;--wp--preset--spacing--30: 0.67rem;--wp--preset--spacing--40: 1rem;--wp--preset--spacing--50: 1.5rem;--wp--preset--spacing--60: 2.25rem;--wp--preset--spacing--70: 3.38rem;--wp--preset--spacing--80: 5.06rem;--wp--preset--shadow--natural: 6px 6px 9px rgba(0, 0, 0, 0.2);--wp--preset--shadow--deep: 12px 12px 50px rgba(0, 0, 0, 0.4);--wp--preset--shadow--sharp: 6px 6px 0px rgba(0, 0, 0, 0.2);--wp--preset--shadow--outlined: 6px 6px 0px -3px rgba(255, 255, 255, 1), 6px 6px rgba(0, 0, 0, 1);--wp--preset--shadow--crisp: 6px 6px 0px rgba(0, 0, 0, 1);}:where(.is-layout-flex){gap: 0.5em;}:where(.is-layout-grid){gap: 0.5em;}body .is-layout-flex{display: flex;}body .is-layout-flex{flex-wrap: wrap;align-items: center;}body .is-layout-flex > *{margin: 0;}body .is-layout-grid{display: grid;}body .is-layout-grid > *{margin: 0;}:where(.wp-block-columns.is-layout-flex){gap: 2em;}:where(.wp-block-columns.is-layout-grid){gap: 2em;}:where(.wp-block-post-template.is-layout-flex){gap: 1.25em;}:where(.wp-block-post-template.is-layout-grid){gap: 1.25em;}.has-black-color{color: var(--wp--preset--color--black) !important;}.has-cyan-bluish-gray-color{color: var(--wp--preset--color--cyan-bluish-gray) !important;}.has-white-color{color: var(--wp--preset--color--white) !important;}.has-pale-pink-color{color: var(--wp--preset--color--pale-pink) !important;}.has-vivid-red-color{color: var(--wp--preset--color--vivid-red) !important;}.has-luminous-vivid-orange-color{color: var(--wp--preset--color--luminous-vivid-orange) !important;}.has-luminous-vivid-amber-color{color: var(--wp--preset--color--luminous-vivid-amber) !important;}.has-light-green-cyan-color{color: var(--wp--preset--color--light-green-cyan) !important;}.has-vivid-green-cyan-color{color: var(--wp--preset--color--vivid-green-cyan) !important;}.has-pale-cyan-blue-color{color: var(--wp--preset--color--pale-cyan-blue) !important;}.has-vivid-cyan-blue-color{color: var(--wp--preset--color--vivid-cyan-blue) !important;}.has-vivid-purple-color{color: var(--wp--preset--color--vivid-purple) !important;}.has-black-background-color{background-color: var(--wp--preset--color--black) !important;}.has-cyan-bluish-gray-background-color{background-color: var(--wp--preset--color--cyan-bluish-gray) !important;}.has-white-background-color{background-color: var(--wp--preset--color--white) !important;}.has-pale-pink-background-color{background-color: var(--wp--preset--color--pale-pink) !important;}.has-vivid-red-background-color{background-color: var(--wp--preset--color--vivid-red) !important;}.has-luminous-vivid-orange-background-color{background-color: var(--wp--preset--color--luminous-vivid-orange) !important;}.has-luminous-vivid-amber-background-color{background-color: var(--wp--preset--color--luminous-vivid-amber) !important;}.has-light-green-cyan-background-color{background-color: var(--wp--preset--color--light-green-cyan) !important;}.has-vivid-green-cyan-background-color{background-color: var(--wp--preset--color--vivid-green-cyan) !important;}.has-pale-cyan-blue-background-color{background-color: var(--wp--preset--color--pale-cyan-blue) !important;}.has-vivid-cyan-blue-background-color{background-color: var(--wp--preset--color--vivid-cyan-blue) !important;}.has-vivid-purple-background-color{background-color: var(--wp--preset--color--vivid-purple) !important;}.has-black-border-color{border-color: var(--wp--preset--color--black) !important;}.has-cyan-bluish-gray-border-color{border-color: var(--wp--preset--color--cyan-bluish-gray) !important;}.has-white-border-color{border-color: var(--wp--preset--color--white) !important;}.has-pale-pink-border-color{border-color: var(--wp--preset--color--pale-pink) !important;}.has-vivid-red-border-color{border-color: var(--wp--preset--color--vivid-red) !important;}.has-luminous-vivid-orange-border-color{border-color: var(--wp--preset--color--luminous-vivid-orange) !important;}.has-luminous-vivid-amber-border-color{border-color: var(--wp--preset--color--luminous-vivid-amber) !important;}.has-light-green-cyan-border-color{border-color: var(--wp--preset--color--light-green-cyan) !important;}.has-vivid-green-cyan-border-color{border-color: var(--wp--preset--color--vivid-green-cyan) !important;}.has-pale-cyan-blue-border-color{border-color: var(--wp--preset--color--pale-cyan-blue) !important;}.has-vivid-cyan-blue-border-color{border-color: var(--wp--preset--color--vivid-cyan-blue) !important;}.has-vivid-purple-border-color{border-color: var(--wp--preset--color--vivid-purple) !important;}.has-vivid-cyan-blue-to-vivid-purple-gradient-background{background: var(--wp--preset--gradient--vivid-cyan-blue-to-vivid-purple) !important;}.has-light-green-cyan-to-vivid-green-cyan-gradient-background{background: var(--wp--preset--gradient--light-green-cyan-to-vivid-green-cyan) !important;}.has-luminous-vivid-amber-to-luminous-vivid-orange-gradient-background{background: var(--wp--preset--gradient--luminous-vivid-amber-to-luminous-vivid-orange) !important;}.has-luminous-vivid-orange-to-vivid-red-gradient-background{background: var(--wp--preset--gradient--luminous-vivid-orange-to-vivid-red) !important;}.has-very-light-gray-to-cyan-bluish-gray-gradient-background{background: var(--wp--preset--gradient--very-light-gray-to-cyan-bluish-gray) !important;}.has-cool-to-warm-spectrum-gradient-background{background: var(--wp--preset--gradient--cool-to-warm-spectrum) !important;}.has-blush-light-purple-gradient-background{background: var(--wp--preset--gradient--blush-light-purple) !important;}.has-blush-bordeaux-gradient-background{background: var(--wp--preset--gradient--blush-bordeaux) !important;}.has-luminous-dusk-gradient-background{background: var(--wp--preset--gradient--luminous-dusk) !important;}.has-pale-ocean-gradient-background{background: var(--wp--preset--gradient--pale-ocean) !important;}.has-electric-grass-gradient-background{background: var(--wp--preset--gradient--electric-grass) !important;}.has-midnight-gradient-background{background: var(--wp--preset--gradient--midnight) !important;}.has-small-font-size{font-size: var(--wp--preset--font-size--small) !important;}.has-medium-font-size{font-size: var(--wp--preset--font-size--medium) !important;}.has-large-font-size{font-size: var(--wp--preset--font-size--large) !important;}.has-x-large-font-size{font-size: var(--wp--preset--font-size--x-large) !important;}
.wp-block-navigation a:where(:not(.wp-element-button)){color: inherit;}
:where(.wp-block-post-template.is-layout-flex){gap: 1.25em;}:where(.wp-block-post-template.is-layout-grid){gap: 1.25em;}
:where(.wp-block-columns.is-layout-flex){gap: 2em;}:where(.wp-block-columns.is-layout-grid){gap: 2em;}
.wp-block-pullquote{font-size: 1.5em;line-height: 1.6;}
</style>
<link rel='stylesheet' id='rs-plugin-settings-css' href='https://www.smsa-sji.sg/wp-content/plugins/revslider/public/assets/css/settings.css?ver=5.4.3.1' type='text/css' media='all' />
<style id='rs-plugin-settings-inline-css' type='text/css'>
#rs-demo-id {}
</style>
<link rel='stylesheet' id='GSWPTS-frontend-css-css' href='https://www.smsa-sji.sg/wp-content/plugins/sheets-to-wp-table-live-sync/assets/public/styles/frontend.min.css?ver=2.14.0' type='text/css' media='all' />
<link rel='stylesheet' id='dls-sus-style-css' href='https://www.smsa-sji.sg/wp-content/plugins/sign-up-sheets/css/style.css?ver=6.5.3' type='text/css' media='all' />
<link rel='stylesheet' id='sportspress-general-css' href='//www.smsa-sji.sg/wp-content/plugins/sportspress/assets/css/sportspress.css?ver=2.7.15' type='text/css' media='all' />
<link rel='stylesheet' id='sportspress-icons-css' href='//www.smsa-sji.sg/wp-content/plugins/sportspress/assets/css/icons.css?ver=2.7' type='text/css' media='all' />
<link rel='stylesheet' id='sportspress-roboto-css' href='//fonts.googleapis.com/css?family=Roboto%3A400%2C500&#038;subset=cyrillic%2Ccyrillic-ext%2Cgreek%2Cgreek-ext%2Clatin-ext%2Cvietnamese&#038;ver=2.7' type='text/css' media='all' />
<link rel='stylesheet' id='sportspress-style-css' href='//www.smsa-sji.sg/wp-content/plugins/sportspress/assets/css/sportspress-style.css?ver=2.7' type='text/css' media='all' />
<link rel='stylesheet' id='sportspress-style-ltr-css' href='//www.smsa-sji.sg/wp-content/plugins/sportspress/assets/css/sportspress-style-ltr.css?ver=2.7' type='text/css' media='all' />
<style id='woocommerce-inline-inline-css' type='text/css'>
.woocommerce form .form-row .required { visibility: visible; }
</style>
<link rel='stylesheet' id='qode_startit_default_style-css' href='https://www.smsa-sji.sg/wp-content/themes/startit/style.css?ver=6.5.3' type='text/css' media='all' />
<link rel='stylesheet' id='qode_startit_modules_plugins-css' href='https://www.smsa-sji.sg/wp-content/themes/startit/assets/css/plugins.min.css?ver=6.5.3' type='text/css' media='all' />
<link rel='stylesheet' id='qode_startit_modules-css' href='https://www.smsa-sji.sg/wp-content/themes/startit/assets/css/modules.min.css?ver=6.5.3' type='text/css' media='all' />
<link rel='stylesheet' id='qodef_font_awesome-css' href='https://www.smsa-sji.sg/wp-content/themes/startit/assets/css/font-awesome/css/font-awesome.min.css?ver=6.5.3' type='text/css' media='all' />
<link rel='stylesheet' id='qodef_font_elegant-css' href='https://www.smsa-sji.sg/wp-content/themes/startit/assets/css/elegant-icons/style.min.css?ver=6.5.3' type='text/css' media='all' />
<link rel='stylesheet' id='qodef_ion_icons-css' href='https://www.smsa-sji.sg/wp-content/themes/startit/assets/css/ion-icons/css/ionicons.min.css?ver=6.5.3' type='text/css' media='all' />
<link rel='stylesheet' id='qodef_linea_icons-css' href='https://www.smsa-sji.sg/wp-content/themes/startit/assets/css/linea-icons/style.css?ver=6.5.3' type='text/css' media='all' />
<link rel='stylesheet' id='qodef_simple_line_icons-css' href='https://www.smsa-sji.sg/wp-content/themes/startit/assets/css/simple-line-icons/simple-line-icons.css?ver=6.5.3' type='text/css' media='all' />
<link rel='stylesheet' id='qodef_dripicons-css' href='https://www.smsa-sji.sg/wp-content/themes/startit/assets/css/dripicons/dripicons.css?ver=6.5.3' type='text/css' media='all' />
<link rel='stylesheet' id='qode_startit_modules_responsive-css' href='https://www.smsa-sji.sg/wp-content/themes/startit/assets/css/modules-responsive.min.css?ver=6.5.3' type='text/css' media='all' />
<link rel='stylesheet' id='qode_startit_blog_responsive-css' href='https://www.smsa-sji.sg/wp-content/themes/startit/assets/css/blog-responsive.min.css?ver=6.5.3' type='text/css' media='all' />
<link rel='stylesheet' id='qode_startit_style_dynamic_responsive-css' href='https://www.smsa-sji.sg/wp-content/themes/startit/assets/css/style_dynamic_responsive.css?ver=1613083726' type='text/css' media='all' />
<link rel='stylesheet' id='qode_startit_style_dynamic-css' href='https://www.smsa-sji.sg/wp-content/themes/startit/assets/css/style_dynamic.css?ver=1613083726' type='text/css' media='all' />
<link rel='stylesheet' id='js_composer_front-css' href='https://www.smsa-sji.sg/wp-content/plugins/js_composer/assets/css/js_composer.min.css?ver=5.1.1' type='text/css' media='all' />
<link rel='stylesheet' id='qode_startit_google_fonts-css' href='https://fonts.googleapis.com/css?family=Raleway%3A100%2C100italic%2C200%2C200italic%2C300%2C300italic%2C400%2C400italic%2C500%2C500italic%2C600%2C600italic%2C700%2C700italic%2C800%2C800italic%2C900%2C900italic%7COpen+Sans%3A100%2C100italic%2C200%2C200italic%2C300%2C300italic%2C400%2C400italic%2C500%2C500italic%2C600%2C600italic%2C700%2C700italic%2C800%2C800italic%2C900%2C900italic%7CRaleway%3A100%2C100italic%2C200%2C200italic%2C300%2C300italic%2C400%2C400italic%2C500%2C500italic%2C600%2C600italic%2C700%2C700italic%2C800%2C800italic%2C900%2C900italic&#038;subset=latin%2Clatin-ext&#038;ver=1.0.0' type='text/css' media='all' />
<link rel='stylesheet' id='evcal_google_fonts-css' href='//fonts.googleapis.com/css?family=Oswald%3A400%2C300%7COpen+Sans%3A700%2C400%2C400i%7CRoboto%3A700%2C400&#038;ver=6.5.3' type='text/css' media='screen' />
<link rel='stylesheet' id='evcal_cal_default-css' href='//www.smsa-sji.sg/wp-content/plugins/eventON/assets/css/eventon_styles.css?ver=2.6.6' type='text/css' media='all' />
<link rel='stylesheet' id='evo_font_icons-css' href='//www.smsa-sji.sg/wp-content/plugins/eventON/assets/fonts/font-awesome.css?ver=2.6.6' type='text/css' media='all' />
<link rel='stylesheet' id='eventon_dynamic_styles-css' href='//www.smsa-sji.sg/wp-content/plugins/eventON/assets/css/eventon_dynamic_styles.css?ver=6.5.3' type='text/css' media='all' />
<link rel='stylesheet' id='tablepress-default-css' href='https://www.smsa-sji.sg/wp-content/tablepress-combined.min.css?ver=42' type='text/css' media='all' />
<style type="text/css"> /* SportsPress Frontend CSS */ .sp-event-calendar tbody td a,.sp-event-calendar tbody td a:hover{background: none;}.sp-data-table th,.sp-calendar th,.sp-data-table tfoot,.sp-calendar tfoot,.sp-button,.sp-heading{background:#0d723b !important}.sp-calendar tbody a{color:#0d723b !important}.sp-data-table tbody,.sp-calendar tbody{background: #eeeeee !important}.sp-data-table tbody,.sp-calendar tbody{color: #333333 !important}.sp-data-table th,.sp-data-table th a,.sp-data-table tfoot,.sp-data-table tfoot a,.sp-calendar th,.sp-calendar th a,.sp-calendar tfoot,.sp-calendar tfoot a,.sp-button,.sp-heading{color: #ffffff !important}.sp-data-table tbody a,.sp-data-table tbody a:hover,.sp-calendar tbody a:focus{color: #0d723b !important}.sp-highlight,.sp-calendar td#today{background: #ffffff !important}.sp-data-table th,.sp-template-countdown .sp-event-venue,.sp-template-countdown .sp-event-league,.sp-template-gallery .gallery-caption{background:#0d723b !important}.sp-data-table th,.sp-template-countdown .sp-event-venue,.sp-template-countdown .sp-event-league,.sp-template-gallery .gallery-caption{border-color:#005821 !important}.sp-table-caption,.sp-data-table,.sp-data-table tfoot,.sp-template .sp-view-all-link,.sp-template-gallery .sp-gallery-group-name,.sp-template-gallery .sp-gallery-wrapper,.sp-template-countdown .sp-event-name,.sp-countdown time,.sp-template-details dl,.sp-event-statistics .sp-statistic-bar,.sp-tournament-bracket .sp-team-name,.sp-profile-selector{background:#eeeeee !important}.sp-table-caption,.sp-data-table,.sp-data-table td,.sp-template .sp-view-all-link,.sp-template-gallery .sp-gallery-group-name,.sp-template-gallery .sp-gallery-wrapper,.sp-template-countdown .sp-event-name,.sp-countdown time,.sp-countdown span,.sp-template-details dl,.sp-event-statistics .sp-statistic-bar,.sp-tournament-bracket thead th,.sp-tournament-bracket .sp-team-name,.sp-tournament-bracket .sp-event,.sp-profile-selector{border-color:#d4d4d4 !important}.sp-tournament-bracket .sp-team .sp-team-name:before{border-left-color:#d4d4d4 !important;border-right-color:#d4d4d4 !important}.sp-data-table .sp-highlight,.sp-data-table .highlighted td,.sp-template-scoreboard td:hover{background:#e8e8e8 !important}.sp-template *,.sp-data-table *,.sp-table-caption,.sp-data-table tfoot a:hover,.sp-template .sp-view-all-link a:hover,.sp-template-gallery .sp-gallery-group-name,.sp-template-details dd,.sp-template-event-logos .sp-team-result,.sp-template-event-blocks .sp-event-results,.sp-template-scoreboard a,.sp-template-scoreboard a:hover,.sp-tournament-bracket,.sp-tournament-bracket .sp-event .sp-event-title:hover,.sp-tournament-bracket .sp-event .sp-event-title:hover *{color:#333333 !important}.sp-template .sp-view-all-link a,.sp-countdown span small,.sp-template-event-calendar tfoot a,.sp-template-event-blocks .sp-event-date,.sp-template-details dt,.sp-template-scoreboard .sp-scoreboard-date,.sp-tournament-bracket th,.sp-tournament-bracket .sp-event .sp-event-title,.sp-template-scoreboard .sp-scoreboard-date,.sp-tournament-bracket .sp-event .sp-event-title *{color:rgba(51,51,51,0.5) !important}.sp-data-table th,.sp-template-countdown .sp-event-venue,.sp-template-countdown .sp-event-league,.sp-template-gallery .gallery-item a,.sp-template-gallery .gallery-caption,.sp-template-scoreboard .sp-scoreboard-nav,.sp-tournament-bracket .sp-team-name:hover,.sp-tournament-bracket thead th,.sp-tournament-bracket .sp-heading{color:#ffffff !important}.sp-template a,.sp-data-table a,.sp-tab-menu-item-active a, .sp-tab-menu-item-active a:hover,.sp-template .sp-message{color:#0d723b !important}.sp-template-gallery .gallery-caption strong,.sp-tournament-bracket .sp-team-name:hover,.sp-template-scoreboard .sp-scoreboard-nav,.sp-tournament-bracket .sp-heading{background:#0d723b !important}.sp-tournament-bracket .sp-team-name:hover,.sp-tournament-bracket .sp-heading,.sp-tab-menu-item-active a, .sp-tab-menu-item-active a:hover,.sp-template .sp-message{border-color:#0d723b !important}.sp-data-table th,.sp-data-table td{padding: 12px !important}</style><script type="text/javascript" src="https://www.smsa-sji.sg/wp-includes/js/jquery/jquery.min.js?ver=3.7.1" id="jquery-core-js"></script>
<script type="text/javascript" src="https://www.smsa-sji.sg/wp-includes/js/jquery/jquery-migrate.min.js?ver=3.4.1" id="jquery-migrate-js"></script>
<script type="text/javascript" src="https://www.smsa-sji.sg/wp-includes/js/jquery/ui/core.min.js?ver=1.13.2" id="jquery-ui-core-js"></script>
<script type="text/javascript" id="mec-frontend-script-js-extra">
/* <![CDATA[ */
var mecdata = {"day":"day","days":"days","hour":"hour","hours":"hours","minute":"minute","minutes":"minutes","second":"second","seconds":"seconds"};
/* ]]> */
</script>
<script type="text/javascript" src="https://www.smsa-sji.sg/wp-content/plugins/modern-events-calendar/assets/js/frontend.js?ver=6.5.3" id="mec-frontend-script-js"></script>
<script type="text/javascript" src="https://www.smsa-sji.sg/wp-content/plugins/modern-events-calendar/assets/js/events.js?ver=6.5.3" id="mec-events-script-js"></script>
<script type="text/javascript" src="https://www.smsa-sji.sg/wp-content/plugins/modern-events-calendar/assets/packages/lity/lity.min.js?ver=6.5.3" id="mec-lity-script-js"></script>
<script type="text/javascript" src="https://www.smsa-sji.sg/wp-content/plugins/modern-events-calendar/assets/packages/owl-carousel/owl.carousel.min.js?ver=6.5.3" id="mec-owl-carousel-script-js"></script>
<script type="text/javascript" src="https://www.smsa-sji.sg/wp-content/themes/startit/assets/js/scrolltoplugin.min.js?ver=6.5.3" id="scrollto-js"></script>
<script type="text/javascript" id="layerslider-greensock-js-extra">
/* <![CDATA[ */
var LS_Meta = {"v":"6.3.0"};
/* ]]> */
</script>
<script type="text/javascript" src="https://www.smsa-sji.sg/wp-content/plugins/LayerSlider/static/layerslider/js/greensock.js?ver=1.19.0" id="layerslider-greensock-js"></script>
<script type="text/javascript" src="https://www.smsa-sji.sg/wp-content/plugins/LayerSlider/static/layerslider/js/layerslider.kreaturamedia.jquery.js?ver=6.3.0" id="layerslider-js"></script>
<script type="text/javascript" src="https://www.smsa-sji.sg/wp-content/plugins/LayerSlider/static/layerslider/js/layerslider.transitions.js?ver=6.3.0" id="layerslider-transitions-js"></script>
<script type="text/javascript" src="https://www.smsa-sji.sg/wp-content/plugins/google-analytics-dashboard-for-wp/assets/js/frontend-gtag.min.js?ver=7.10.0" id="exactmetrics-frontend-script-js"></script>
<script data-cfasync="false" data-wpfc-render="false" type="text/javascript" id='exactmetrics-frontend-script-js-extra'>/* <![CDATA[ */
var exactmetrics_frontend = {"js_events_tracking":"true","download_extensions":"zip,mp3,mpeg,pdf,docx,pptx,xlsx,rar","inbound_paths":"[{\"path\":\"\\\/go\\\/\",\"label\":\"affiliate\"},{\"path\":\"\\\/recommend\\\/\",\"label\":\"affiliate\"}]","home_url":"https:\/\/www.smsa-sji.sg","hash_tracking":"false","ua":"UA-109137141-1","v4_id":""};/* ]]> */
</script>
<script type="text/javascript" src="https://www.smsa-sji.sg/wp-includes/js/jquery/ui/accordion.min.js?ver=1.13.2" id="jquery-ui-accordion-js"></script>
<script type="text/javascript" src="https://www.smsa-sji.sg/wp-includes/js/jquery/ui/tabs.min.js?ver=1.13.2" id="jquery-ui-tabs-js"></script>
<script type="text/javascript" src="https://www.smsa-sji.sg/wp-includes/js/jquery/ui/effect.min.js?ver=1.13.2" id="jquery-effects-core-js"></script>
<script type="text/javascript" src="https://www.smsa-sji.sg/wp-includes/js/jquery/ui/effect-slide.min.js?ver=1.13.2" id="jquery-effects-slide-js"></script>
<script type="text/javascript" src="https://www.smsa-sji.sg/wp-includes/js/tw-sack.min.js?ver=1.6.1" id="sack-js"></script>
<script type="text/javascript" id="thickbox-js-extra">
/* <![CDATA[ */
var thickboxL10n = {"next":"Next >","prev":"< Prev","image":"Image","of":"of","close":"Close","noiframes":"This feature requires inline frames. You have iframes disabled or your browser does not support them.","loadingAnimation":"https:\/\/www.smsa-sji.sg\/wp-includes\/js\/thickbox\/loadingAnimation.gif"};
/* ]]> */
</script>
<script type="text/javascript" src="https://www.smsa-sji.sg/wp-includes/js/thickbox/thickbox.js?ver=3.1-20121105" id="thickbox-js"></script>
<script type="text/javascript" src="https://www.smsa-sji.sg/wp-content/plugins/leaguemanager/leaguemanager.js?ver=4.2-RC1.3.2" id="leaguemanager-js"></script>
<script type="text/javascript" src="https://www.smsa-sji.sg/wp-content/plugins/revslider/public/assets/js/jquery.themepunch.tools.min.js?ver=5.4.3.1" id="tp-tools-js"></script>
<script type="text/javascript" src="https://www.smsa-sji.sg/wp-content/plugins/revslider/public/assets/js/jquery.themepunch.revolution.min.js?ver=5.4.3.1" id="revmin-js"></script>
<script type="text/javascript" src="https://www.smsa-sji.sg/wp-content/plugins/sheets-to-wp-table-live-sync/assets/public/common/datatables/tables/js/jquery.datatables.min.js?ver=2.14.0" id="GSWPTS-frontend-table-js"></script>
<script type="text/javascript" src="https://www.smsa-sji.sg/wp-content/plugins/sheets-to-wp-table-live-sync/assets/public/common/datatables/tables/js/datatables.semanticui.min.js?ver=2.14.0" id="GSWPTS-frontend-semantic-js"></script>
<script type="text/javascript" src="https://www.smsa-sji.sg/wp-content/plugins/woocommerce/assets/js/jquery-blockui/jquery.blockUI.min.js?ver=2.70" id="jquery-blockui-js"></script>
<script type="text/javascript" id="wc-add-to-cart-js-extra">
/* <![CDATA[ */
var wc_add_to_cart_params = {"ajax_url":"\/wp-admin\/admin-ajax.php","wc_ajax_url":"\/?wc-ajax=%%endpoint%%","i18n_view_cart":"View cart","cart_url":"https:\/\/www.smsa-sji.sg\/cart\/","is_cart":"","cart_redirect_after_add":"no"};
/* ]]> */
</script>
<script type="text/javascript" src="https://www.smsa-sji.sg/wp-content/plugins/woocommerce/assets/js/frontend/add-to-cart.min.js?ver=5.1.0" id="wc-add-to-cart-js"></script>
<script type="text/javascript" src="https://www.smsa-sji.sg/wp-content/plugins/js_composer/assets/js/vendors/woocommerce-add-to-cart.js?ver=5.1.1" id="vc_woocommerce-add-to-cart-js-js"></script>
<meta name="generator" content="Powered by LayerSlider 6.3.0 - Multi-Purpose, Responsive, Parallax, Mobile-Friendly Slider Plugin for WordPress." />
<!-- LayerSlider updates and docs at: https://layerslider.kreaturamedia.com -->
<link rel="https://api.w.org/" href="https://www.smsa-sji.sg/wp-json/" /><link rel="alternate" type="application/json" href="https://www.smsa-sji.sg/wp-json/wp/v2/pages/2476" /><link rel="EditURI" type="application/rsd+xml" title="RSD" href="https://www.smsa-sji.sg/xmlrpc.php?rsd" />
<meta name="generator" content="WordPress 6.5.3" />
<meta name="generator" content="SportsPress 2.7.15" />
<meta name="generator" content="WooCommerce 5.1.0" />
<link rel="canonical" href="https://www.smsa-sji.sg/" />
<link rel='shortlink' href='https://www.smsa-sji.sg/' />
<link rel="alternate" type="application/json+oembed" href="https://www.smsa-sji.sg/wp-json/oembed/1.0/embed?url=https%3A%2F%2Fwww.smsa-sji.sg%2F" />
<link rel="alternate" type="text/xml+oembed" href="https://www.smsa-sji.sg/wp-json/oembed/1.0/embed?url=https%3A%2F%2Fwww.smsa-sji.sg%2F&#038;format=xml" />
	<link rel="preconnect" href="https://fonts.googleapis.com">
	<link rel="preconnect" href="https://fonts.gstatic.com">
	<link href='https://fonts.googleapis.com/css2?display=swap&family=Open+Sans:wght@300;600' rel='stylesheet'><script type="text/javascript">document.documentElement.className += " js";</script>
<!--[if IE 9]><link rel="stylesheet" type="text/css" href="https://www.smsa-sji.sg/wp-content/themes/startit/assets/css/ie9_stylesheet.min.css" media="screen"><![endif]-->	<noscript><style>.woocommerce-product-gallery{ opacity: 1 !important; }</style></noscript>
	

<!-- EventON Version -->
<meta name="generator" content="EventON 2.6.6" />

<style type="text/css">.recentcomments a{display:inline !important;padding:0 !important;margin:0 !important;}</style><meta name="generator" content="Powered by Visual Composer - drag and drop page builder for WordPress."/>
<!--[if lte IE 9]><link rel="stylesheet" type="text/css" href="https://www.smsa-sji.sg/wp-content/plugins/js_composer/assets/css/vc_lte_ie9.min.css" media="screen"><![endif]--><meta name="generator" content="Powered by Slider Revolution 5.4.3.1 - responsive, Mobile-Friendly Slider Plugin for WordPress with comfortable drag and drop interface." />
<link rel="icon" href="https://www.smsa-sji.sg/wp-content/uploads/2017/10/SMSA-sm-100x100.png" sizes="32x32" />
<link rel="icon" href="https://www.smsa-sji.sg/wp-content/uploads/2017/10/SMSA-sm.png" sizes="192x192" />
<link rel="apple-touch-icon" href="https://www.smsa-sji.sg/wp-content/uploads/2017/10/SMSA-sm.png" />
<meta name="msapplication-TileImage" content="https://www.smsa-sji.sg/wp-content/uploads/2017/10/SMSA-sm.png" />
<script type="text/javascript">function setREVStartSize(e){
				try{ var i=jQuery(window).width(),t=9999,r=0,n=0,l=0,f=0,s=0,h=0;					
					if(e.responsiveLevels&&(jQuery.each(e.responsiveLevels,function(e,f){f>i&&(t=r=f,l=e),i>f&&f>r&&(r=f,n=e)}),t>r&&(l=n)),f=e.gridheight[l]||e.gridheight[0]||e.gridheight,s=e.gridwidth[l]||e.gridwidth[0]||e.gridwidth,h=i/s,h=h>1?1:h,f=Math.round(h*f),"fullscreen"==e.sliderLayout){var u=(e.c.width(),jQuery(window).height());if(void 0!=e.fullScreenOffsetContainer){var c=e.fullScreenOffsetContainer.split(",");if (c) jQuery.each(c,function(e,i){u=jQuery(i).length>0?u-jQuery(i).outerHeight(!0):u}),e.fullScreenOffset.split("%").length>1&&void 0!=e.fullScreenOffset&&e.fullScreenOffset.length>0?u-=jQuery(window).height()*parseInt(e.fullScreenOffset,0)/100:void 0!=e.fullScreenOffset&&e.fullScreenOffset.length>0&&(u-=parseInt(e.fullScreenOffset,0))}f=u}else void 0!=e.minHeight&&f<e.minHeight&&(f=e.minHeight);e.c.closest(".rev_slider_wrapper").css({height:f})					
				}catch(d){console.log("Failure at Presize of Slider:"+d)}
			};</script>
		<style type="text/css" id="wp-custom-css">
			/*
You can add your own CSS here.

Click the help icon above to learn more.
*/

footer div.qodef-footer-top-holder{ background-color: #222222 }footer div.qodef-footer-bottom-holder{ background-color: #0d723b }


.qodef-service-table table thead th:first-child{
    background-color: #7f969f;
}
.qodef-service-table table tbody td:first-child{
    background-color: #fafafa;
}
.qodef-service-table table thead th:nth-child(2n+2){
    background-color: #afcabd;
}
.qodef-service-table table tbody td:nth-child(2n+2){
    background-color: #e8efec;
}
.qodef-service-table table thead th:nth-child(2n+3){
    background-color:#c5dadb;
}
.qodef-service-table table tbody td:nth-child(2n+3){
    background-color: #fafafa;
}



.vc_responsive .home_box_wrap_test.wpb_row .vc_span2 {
float: left;
width: 0%;
padding: 0;
margin-right: 0%;
min-height: 0;
}


.home_box_wrap .home_box_last {
margin: 0 !important;
}


		</style>
			<style id="egf-frontend-styles" type="text/css">
		p {color: #333333;font-family: 'Open Sans', sans-serif;font-size: 16px;font-style: normal;font-weight: 300;line-height: 1.5;text-decoration: none;text-transform: none;} h5 {color: #333333;font-family: 'Open Sans', sans-serif;font-size: 15px;font-style: normal;font-weight: 300;} h6 {color: #333333;font-family: 'Open Sans', sans-serif;font-size: 13px;font-style: normal;font-weight: 300;} h3 {color: #333333;font-family: 'Open Sans', sans-serif;font-size: 20px;font-style: normal;font-weight: 600;line-height: 1.3;text-decoration: none;text-transform: none;} h4 {color: #0d723b;font-family: 'Open Sans', sans-serif;font-size: 12px;font-style: normal;font-weight: 300;line-height: 1.5;border-top-color: #a0a0a0;border-top-style: solid;} h1 {} h2 {} 	</style>
	<style type="text/css" id="qode_startit-custom-css">.qodef-landing-custom .qodef-ptf-category-holder{
	display:none !important;
}

.qodef-landing-custom .qodef-portfolio-list-holder-outer.qodef-ptf-standard article .qodef-item-image-holder{
	border-radius: 3px 3px 0 0;
    backface-visibility: hidden;
}

.qodef-landing-custom .qodef-item-title{
	text-align:center !important;
	padding: 28px 0 37px 0 !important;
}

.qodef-landing-custom .qodef-item-icons-holder .qodef-like,
.qodef-landing-custom .qodef-item-icons-holder .qodef-portfolio-lightbox{
	display:none !important;
}
.qodef-landing-custom .qodef-portfolio-item .qodef-portfolio-shader{
	display:none !important;
}

.qodef-landing-custom .qodef-portfolio-list-holder-outer.qodef-ptf-standard article .qodef-item-icons-holder {
    width: 100%;
    top: -25%;
    left: 0;
    bottom: 0;
    height: 100%;
    padding: 0;
    -webkit-transform: translateY(0) scale(0);
    -ms-transform: translateY(0) scale(0);
    transform: translateY(0) scale(0);
    background-color: rgba(0, 0, 0, 0.15);
	border-radius: 100%;
    padding: 50% 0;
    display: block;
	-webkit-transition: -webkit-transform .5s cubic-bezier(.4,0,.2,1),opacity .2s;
    transition: transform .5s cubic-bezier(.4,0,.2,1),opacity .2s;
}

.qodef-landing-custom .qodef-portfolio-list-holder-outer.qodef-ptf-standard article:hover .qodef-item-icons-holder {
    opacity: 1;
    -webkit-transform: translateY(0) scale(1.2);
    -ms-transform: translateY(0) scale(1.2);
    transform: translateY(0) scale(1.2);
	-webkit-transition: -webkit-transform .35s cubic-bezier(.4,0,.2,1),opacity .35s;
    transition: transform .35s cubic-bezier(.4,0,.2,1),opacity .35s;
	
}

.qodef-landing-custom .qodef-item-icons-holder .qodef-preview{
	position: absolute;
    top: 0;
	left:0;
	width:100%;
	height:100%;
	background-color: transparent !important;
	border:none !important;
	-ms-transform: translateY(0) rotate(0);
	-webkit-transform: translateY(0) rotate(0);
    transform: translateY(0) rotate(0);
}

.qodef-landing-custom .qodef-portfolio-list-holder article .qodef-item-icons-holder a:hover{
	-ms-transform: translateY(0) rotate(0);
	-webkit-transform: translateY(0) rotate(0);
    transform: translateY(0) rotate(0);
}

.qodef-landing-custom .qodef-item-icons-holder .qodef-preview:before{
	content: "\f002" !important;
    font-size: 22px;
    position: relative;
    top: 50%;
    -webkit-transform: translateY(-65%) translateX(-50%);
    -ms-transform: translateY(-75%) translateX(-50%);
    transform: translateY(-75%) translateX(-50%);
    width: 60px;
    height: 60px;
    display: block;
    background: #b2dd4c;
    border-radius: 100%;
    text-align: center;
    line-height: 60px;
    left: 50%;
}
.page-id-2689 .qodef-page-header .qodef-position-right,
.page-id-2689  .qodef-sticky-holder,
.page-id-2689  footer,
.page-id-2689 #qodef-back-to-top{
display: none !important;
}
.page-id-2689  #qodef-particles .qodef-p-content{
width:auto;
}

.qodef-va-fix {
vertical-align: middle;
}

@media only screen and (max-width: 1284px) {
      .page-id-3520.qodef-header-vertical  footer .qodef-four-columns .qodef-column {
              width: 49.5%;
              min-height: initial !important;
}
}

@media only screen and (max-width: 1024px) {
	.page-id-2476 #qodef-meetup-slider.carousel .carousel-inner .item:nth-child(1) .qodef-slider-content,
	.page-id-2476 #qodef-meetup-slider.carousel .carousel-inner .item:nth-child(3) .qodef-slider-content{
		padding-right: 80px;
	}

	.page-id-2476 #qodef-meetup-slider.carousel .carousel-inner .item:nth-child(1) .qodef-graphic-content,
	.page-id-2476 #qodef-meetup-slider.carousel .carousel-inner .item:nth-child(3) .qodef-graphic-content {
		padding-right: 0;
	}
	
	.page-id-2476 #qodef-meetup-slider.carousel .carousel-inner .item:nth-child(2) .qodef-graphic-content,
	.page-id-2476 #qodef-meetup-slider.carousel .carousel-inner .item:nth-child(4) .qodef-graphic-content {
		display: none;
	}
	
	.page-id-2476 #qodef-meetup-slider.carousel .carousel-inner .item:nth-child(2) .qodef-slider-content,
	.page-id-2476 #qodef-meetup-slider.carousel .carousel-inner .item:nth-child(4) .qodef-slider-content{
		padding-left: 80px;
	}
}

@media only screen and (max-width: 768px) {
	.page-id-2476 #qodef-meetup-slider.carousel .carousel-inner .item:nth-child(1) .qodef-slider-content,
	.page-id-2476 #qodef-meetup-slider.carousel .carousel-inner .item:nth-child(3) .qodef-slider-content{
		padding-left: 80px;
	}

	.page-id-2476 #qodef-meetup-slider.carousel .carousel-inner .item:nth-child(1) .qodef-graphic-content,
	.page-id-2476 #qodef-meetup-slider.carousel .carousel-inner .item:nth-child(3) .qodef-graphic-content {
		display: none;
	}

      .page-id-3520.qodef-header-vertical  footer .qodef-four-columns .qodef-column {
              width: 100%;
              min-height: initial !important;
       }
}
@media only screen and (max-width: 480px) {
	.page-id-2476 #qodef-meetup-slider.carousel .carousel-inner .item:nth-child(1) .qodef-slider-content,
	.page-id-2476 #qodef-meetup-slider.carousel .carousel-inner .item:nth-child(2) .qodef-slider-content,
	.page-id-2476 #qodef-meetup-slider.carousel .carousel-inner .item:nth-child(3) .qodef-slider-content,
	.page-id-2476 #qodef-meetup-slider.carousel .carousel-inner .item:nth-child(4) .qodef-slider-content {
		padding-left: 20px;
	}
}


.landing-new-custom .qodef-portfolio-item .qodef-portfolio-shader{
	background-color: rgba(34, 34, 34, 0.8);
	-webkit-transform: scale(1);
    -ms-transform: scale(1);
    transform: scale(1);
	border-radius:0;
	top:0;
	left:0;
	padding:0;
	border-radius: 15px;
}

.landing-new-custom  .qodef-portfolio-list-holder-outer .qodef-item-title{
	font-size:22px;
	color:#fff;
	font-weight:700;
}

.landing-new-custom  .qodef-portfolio-list-holder-outer .qodef-item-text-holder .qodef-ptf-category-holder{
	display:none;
}

.landing-new-custom  .qodef-portfolio-list-holder-outer article{
	border-radius: 15px;
	overflow:hidden;
box-shadow: 4px 4px 15px #c3c3c3;
transform: translateZ(0px);
}
.landing-new-custom  .qodef-portfolio-filter-holder .qodef-portfolio-filter-holder-inner ul li span{
	font-size:16px;
	color: #686868;
}
.landing-new-custom  .qodef-portfolio-filter-holder .qodef-portfolio-filter-holder-inner ul li span:hover{
	color:#b2dd4c;
}

.landing-new-custom  .qodef-portfolio-filter-holder{
	margin-bottom: 86px;
}

.qodef-content ol, .qodef-content ul {
    list-style-position: outside;
    margin-left: 20px !important;
}

.qodef-tabs .qodef-tabs-nav {
    text-align: right;
}

@media screen and (max-width: 680px){
    .qodef-title .qodef-title-image img{
        height: 150px;
        max-width: none;
        width: auto;
        left: -50%;
    }
    .qodef-title .qodef-title-holder h1{
        font-size: 30px;
        line-height: 30px;
    }
}


@media (min-width: 1000px){
    .qodef-pie-chart-pie-holder .qodef-pie-legend ul li p {
        width: 350px !important;
    }
}
@media (max-width: 1000px){
    .qodef-pie-chart-pie canvas#pie9944 {
        width: 300px !important;
        height: 200px !important;
    }
    .qodef-pie-chart-pie-holder .qodef-pie-legend ul li p {
        width: 200px !important;
    }
}


.qodef-service-table table thead th:first-child{
    background-color: #888888;
}
.qodef-service-table table tbody td:first-child{
    background-color: #dddddd;
}
.qodef-service-table table thead th:nth-child(2n+2){
    background-color: #6888a1;
}
.qodef-service-table table tbody td:nth-child(2n+2){
    background-color: #cfdce6;
}
.qodef-service-table table thead th:nth-child(2n+3){
    background-color: #7f9e98;
}
.qodef-service-table table tbody td:nth-child(2n+3){
    background-color: #dbe2e1;
}

.qodef-vertical-align-containers .qodef-position-center:before, .qodef-vertical-align-containers .qodef-position-left:before, .qodef-vertical-align-containers .qodef-position-right:before{
    margin-right: 0;
}</style><style type="text/css" data-type="vc_shortcodes-custom-css">.vc_custom_1509371223345{padding-top: 56px !important;padding-bottom: 44px !important;background: #eeeeee url(http://www.smsa-sji.sg/wp-content/uploads/2015/11/hd_announcement-bg-1.png?id=7854) !important;background-position: center !important;background-repeat: no-repeat !important;background-size: cover !important;}.vc_custom_1446736175325{padding-top: 56px !important;padding-bottom: 44px !important;background-image: url(http://startit.select-themes.com/wp-content/uploads/2015/11/Meetup-Background-1.jpg?id=2495) !important;background-position: center !important;background-repeat: no-repeat !important;background-size: cover !important;}.vc_custom_1504621997955{padding-top: 92px !important;padding-bottom: 61px !important;background-color: #ececec !important;}</style><noscript><style type="text/css"> .wpb_animate_when_almost_visible { opacity: 1; }</style></noscript><style type="text/css">.single-mec-events.qodef-header-standard .qodef-menu-area {background: #333 !important;}

.mec-wrap .owl-buttons {text-align: center;}
.mec-wrap .owl-buttons div {display: inline-block;}</style></head>

<body class="home page-template page-template-full-width page-template-full-width-php page page-id-2476 theme-startit qode-core-1.3.1 woocommerce-no-js startit-ver-2.3 qodef-smooth-scroll qodef-smooth-page-transitions qodef-top-bar-mobile-hide qodef-header-standard qodef-sticky-header-on-scroll-down-up qodef-default-mobile-header qodef-sticky-up-mobile-header qodef-dropdown-slide-from-left qodef-light-header qodef-header-style-on-scroll qodef-search-covers-header qodef-side-menu-slide-with-content qodef-width-370 wpb-js-composer js-comp-ver-5.1.1 vc_responsive">
<section class="qodef-side-menu right">
		<div class="qodef-close-side-menu-holder">
		<div class="qodef-close-side-menu-holder-inner">
			<a href="#" target="_self" class="qodef-close-side-menu">
				<span aria-hidden="true" class="icon_close"></span>
			</a>
		</div>
	</div>
	<div id="custom_html-7" class="widget_text widget qodef-sidearea widget_custom_html"><div class="textwidget custom-html-widget"><h2><span style="color: #0d723b;">JSSL NATIONAL LEAGUE 2019/20 RESULTS</span></h2>

&nbsp;
<h3><strong><span style="color: #333333;">Stay updated with the latest league results!</span></strong></h3>
&nbsp;


<h3 style="text-align: left;"><span style="color: #ed1c2c;"><a style="color: #ed1c2c;" href="https://results.cupmanager.net/25044609,2019,en/category/25044943" target="_blank" rel="noopener">Under 7</a></span></h3>


<h3 style="text-align: left;"><span style="color: #ed1c2c;"><a style="color: #ed1c2c;" href="https://results.cupmanager.net/25044609,2019,en/category/25044944" target="_blank" rel="noopener">Under 8</a></span></h3>


<h3 style="text-align: left;"><span style="color: #ed1c2c;"><a style="color: #ed1c2c;" href="https://results.cupmanager.net/25044609,2019,en/category/25044945" target="_blank" rel="noopener">Under 9</a></span></h3>


<h3 style="text-align: left;"><span style="color: #ed1c2c;"><a style="color: #ed1c2c;" href="https://results.cupmanager.net/25044609,2019,en/category/25044946" target="_blank" rel="noopener">Under 10</a></span></h3>


<h3 style="text-align: left;"><span style="color: #ed1c2c;"><a style="color: #ed1c2c;" href="https://results.cupmanager.net/25044609,2019,en/category/25044947" target="_blank" rel="noopener">Under 11</a></span></h3>


<h3 style="text-align: left;"><span style="color: #ed1c2c;"><a style="color: #ed1c2c;" href="https://results.cupmanager.net/25044609,2019,en/category/25044949" target="_blank" rel="noopener">Under 13</a></span></h3></div></div></section>
<div class="qodef-wrapper">
    <div class="qodef-wrapper-inner">
        
<header class="qodef-page-header">
        <div class="qodef-menu-area" style="background-color:rgba(255, 255, 255, 0)">
        			<form role="search" action="https://www.smsa-sji.sg/" class="qodef-search-cover" method="get">
		<div class="qodef-container">
		<div class="qodef-container-inner clearfix">
						<div class="qodef-form-holder-outer">
				<div class="qodef-form-holder">
					<div class="qodef-form-holder-inner">
						<input type="text" placeholder="Search" name="s" class="qode_search_field no-livesearch" autocomplete="off" />
						<div class="qodef-search-close">
							<a href="#">
								<i class="qodef-icon-ion-icon ion-close " ></i>							</a>
						</div>
					</div>
				</div>
			</div>
					</div>
	</div>
	</form>            <div class="qodef-vertical-align-containers">
                <div class="qodef-position-left">
                    <div class="qodef-position-left-inner">
                        
<div class="qodef-logo-wrapper">
    <a href="https://www.smsa-sji.sg/" style="height: 143px;">
        <img class="qodef-normal-logo" src="http://www.smsa-sji.sg/wp-content/uploads/2017/08/SMSA-Assn-logo-1.png" alt="logo"/>
        <img class="qodef-dark-logo" src="http://www.smsa-sji.sg/wp-content/uploads/2017/08/logo.png" alt="dark logo"/>        <img class="qodef-light-logo" src="http://www.smsa-sji.sg/wp-content/uploads/2017/08/logo.png" alt="light logo"/>    </a>
</div>

                    </div>
                </div>
                <div class="qodef-position-right">
                    <div class="qodef-position-right-inner">
                        
<nav class="qodef-main-menu qodef-drop-down qodef-default-nav">
    <ul id="menu-main-menu" class="clearfix"><li id="nav-menu-item-24" class="menu-item menu-item-type-custom menu-item-object-custom current-menu-item current_page_item menu-item-home qodef-active-item narrow"><a href="http://www.smsa-sji.sg" class=" current "><span class="item_outer"><span class="item_inner"><span class="menu_icon_wrapper"><i class="menu_icon null fa"></i></span><span class="item_text">Home</span></span><span class="plus"></span></span></a></li>
<li id="nav-menu-item-7080" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-has-children  has_sub narrow"><a href="#" class=" no_link" style="cursor: default;" onclick="JavaScript: return false;"><span class="item_outer"><span class="item_inner"><span class="menu_icon_wrapper"><i class="menu_icon null fa"></i></span><span class="item_text">About Us</span></span><span class="plus"></span></span></a>
<div class="second"><div class="inner"><ul>
	<li id="nav-menu-item-29" class="menu-item menu-item-type-post_type menu-item-object-page "><a href="https://www.smsa-sji.sg/about-st-michaels-soccer-association/" class=""><span class="item_outer"><span class="item_inner"><span class="menu_icon_wrapper"><i class="menu_icon null fa"></i></span><span class="item_text">About St Michael&#8217;s Soccer Association</span></span><span class="plus"></span></span></a></li>
	<li id="nav-menu-item-30" class="menu-item menu-item-type-post_type menu-item-object-page "><a href="https://www.smsa-sji.sg/our-constitution/" class=""><span class="item_outer"><span class="item_inner"><span class="menu_icon_wrapper"><i class="menu_icon null fa"></i></span><span class="item_text">Our Constitution</span></span><span class="plus"></span></span></a></li>
	<li id="nav-menu-item-31" class="menu-item menu-item-type-post_type menu-item-object-page "><a href="https://www.smsa-sji.sg/committee/" class=""><span class="item_outer"><span class="item_inner"><span class="menu_icon_wrapper"><i class="menu_icon null fa"></i></span><span class="item_text">Committee</span></span><span class="plus"></span></span></a></li>
	<li id="nav-menu-item-10971" class="menu-item menu-item-type-post_type menu-item-object-page "><a href="https://www.smsa-sji.sg/sponsor-and-partner/" class=""><span class="item_outer"><span class="item_inner"><span class="menu_icon_wrapper"><i class="menu_icon blank fa"></i></span><span class="item_text">Sponsor and Partner</span></span><span class="plus"></span></span></a></li>
	<li id="nav-menu-item-32" class="menu-item menu-item-type-post_type menu-item-object-page "><a href="https://www.smsa-sji.sg/cca-faq-sheet/" class=""><span class="item_outer"><span class="item_inner"><span class="menu_icon_wrapper"><i class="menu_icon null fa"></i></span><span class="item_text">CCA FAQ Sheet</span></span><span class="plus"></span></span></a></li>
	<li id="nav-menu-item-8403" class="menu-item menu-item-type-custom menu-item-object-custom "><a href="https://www.facebook.com/pg/smsa.sji/photos/?ref=page_internal" class=""><span class="item_outer"><span class="item_inner"><span class="menu_icon_wrapper"><i class="menu_icon null fa"></i></span><span class="item_text">Photo Gallery</span></span><span class="plus"></span></span></a></li>
</ul></div></div>
</li>
<li id="nav-menu-item-7119" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-has-children  has_sub narrow"><a href="#" class=" no_link" style="cursor: default;" onclick="JavaScript: return false;"><span class="item_outer"><span class="item_inner"><span class="menu_icon_wrapper"><i class="menu_icon null fa"></i></span><span class="item_text">Programmes</span></span><span class="plus"></span></span></a>
<div class="second"><div class="inner"><ul>
	<li id="nav-menu-item-63" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-has-children sub"><a href="https://www.smsa-sji.sg/st-michaels-soccer-academy/" class=" no_link" style="cursor: default;" onclick="JavaScript: return false;"><span class="item_outer"><span class="item_inner"><span class="menu_icon_wrapper"><i class="menu_icon null fa"></i></span><span class="item_text">St Michael&#8217;s Soccer Academy</span></span><span class="plus"></span><i class="q_menu_arrow fa fa-angle-right"></i></span></a>
	<ul>
		<li id="nav-menu-item-66" class="menu-item menu-item-type-post_type menu-item-object-page "><a href="https://www.smsa-sji.sg/players-programmes/" class=""><span class="item_outer"><span class="item_inner"><span class="menu_icon_wrapper"><i class="menu_icon null fa"></i></span><span class="item_text">Players Programmes</span></span><span class="plus"></span></span></a></li>
		<li id="nav-menu-item-67" class="menu-item menu-item-type-post_type menu-item-object-page "><a href="https://www.smsa-sji.sg/players-values/" class=""><span class="item_outer"><span class="item_inner"><span class="menu_icon_wrapper"><i class="menu_icon null fa"></i></span><span class="item_text">Player Values</span></span><span class="plus"></span></span></a></li>
		<li id="nav-menu-item-6162" class="menu-item menu-item-type-custom menu-item-object-custom "><a href="http://www.smsa-sji.sg/coaching-format" class=""><span class="item_outer"><span class="item_inner"><span class="menu_icon_wrapper"><i class="menu_icon null fa"></i></span><span class="item_text">Coaching Format</span></span><span class="plus"></span></span></a></li>
		<li id="nav-menu-item-69" class="menu-item menu-item-type-post_type menu-item-object-page "><a href="https://www.smsa-sji.sg/competitions/" class=""><span class="item_outer"><span class="item_inner"><span class="menu_icon_wrapper"><i class="menu_icon null fa"></i></span><span class="item_text">Code of Conduct for Competitions</span></span><span class="plus"></span></span></a></li>
		<li id="nav-menu-item-10038" class="menu-item menu-item-type-post_type menu-item-object-page "><a href="https://www.smsa-sji.sg/?page_id=10035" class=""><span class="item_outer"><span class="item_inner"><span class="menu_icon_wrapper"><i class="menu_icon blank fa"></i></span><span class="item_text">League Table and Fixtures</span></span><span class="plus"></span></span></a></li>
		<li id="nav-menu-item-10425" class="menu-item menu-item-type-post_type menu-item-object-page "><a href="https://www.smsa-sji.sg/?page_id=10375" class=""><span class="item_outer"><span class="item_inner"><span class="menu_icon_wrapper"><i class="menu_icon blank fa"></i></span><span class="item_text">Saints League 2019</span></span><span class="plus"></span></span></a></li>
		<li id="nav-menu-item-70" class="menu-item menu-item-type-post_type menu-item-object-page "><a href="https://www.smsa-sji.sg/our-coaches/" class=""><span class="item_outer"><span class="item_inner"><span class="menu_icon_wrapper"><i class="menu_icon null fa"></i></span><span class="item_text">Our Coaches</span></span><span class="plus"></span></span></a></li>
		<li id="nav-menu-item-71" class="menu-item menu-item-type-post_type menu-item-object-page "><a href="https://www.smsa-sji.sg/schedule-locations/" class=""><span class="item_outer"><span class="item_inner"><span class="menu_icon_wrapper"><i class="menu_icon null fa"></i></span><span class="item_text">Schedule &#038; Locations</span></span><span class="plus"></span></span></a></li>
		<li id="nav-menu-item-72" class="menu-item menu-item-type-post_type menu-item-object-page "><a href="https://www.smsa-sji.sg/fees/" class=""><span class="item_outer"><span class="item_inner"><span class="menu_icon_wrapper"><i class="menu_icon null fa"></i></span><span class="item_text">Fees</span></span><span class="plus"></span></span></a></li>
	</ul>
</li>
	<li id="nav-menu-item-64" class="menu-item menu-item-type-post_type menu-item-object-page "><a href="https://www.smsa-sji.sg/epic-holiday-camp/" class=""><span class="item_outer"><span class="item_inner"><span class="menu_icon_wrapper"><i class="menu_icon null fa"></i></span><span class="item_text">EPIC Holiday Football Camp Main</span></span><span class="plus"></span></span></a></li>
	<li id="nav-menu-item-10842" class="menu-item menu-item-type-post_type menu-item-object-page "><a href="https://www.smsa-sji.sg/?page_id=10813" class=""><span class="item_outer"><span class="item_inner"><span class="menu_icon_wrapper"><i class="menu_icon blank fa"></i></span><span class="item_text">Shanghai Greenland Shenhua F.C.</span></span><span class="plus"></span></span></a></li>
</ul></div></div>
</li>
<li id="nav-menu-item-6897" class="menu-item menu-item-type-post_type menu-item-object-page  narrow"><a href="https://www.smsa-sji.sg/?page_id=6894" class=""><span class="item_outer"><span class="item_inner"><span class="menu_icon_wrapper"><i class="menu_icon null fa"></i></span><span class="item_text">Events Calendar</span></span><span class="plus"></span></span></a></li>
<li id="nav-menu-item-91" class="menu-item menu-item-type-post_type menu-item-object-page  narrow"><a href="https://www.smsa-sji.sg/?page_id=74" class=""><span class="item_outer"><span class="item_inner"><span class="menu_icon_wrapper"><i class="menu_icon null fa"></i></span><span class="item_text">Latest News</span></span><span class="plus"></span></span></a></li>
<li id="nav-menu-item-92" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-has-children  has_sub narrow"><a href="https://www.smsa-sji.sg/sign-up/" class=" no_link" style="cursor: default;" onclick="JavaScript: return false;"><span class="item_outer"><span class="item_inner"><span class="menu_icon_wrapper"><i class="menu_icon null fa"></i></span><span class="item_text">Sign Up</span></span><span class="plus"></span></span></a>
<div class="second"><div class="inner"><ul>
	<li id="nav-menu-item-93" class="menu-item menu-item-type-post_type menu-item-object-page "><a href="https://www.smsa-sji.sg/trial/" class=""><span class="item_outer"><span class="item_inner"><span class="menu_icon_wrapper"><i class="menu_icon null fa"></i></span><span class="item_text">Trial</span></span><span class="plus"></span></span></a></li>
	<li id="nav-menu-item-94" class="menu-item menu-item-type-post_type menu-item-object-page "><a href="https://www.smsa-sji.sg/new-player/" class=""><span class="item_outer"><span class="item_inner"><span class="menu_icon_wrapper"><i class="menu_icon null fa"></i></span><span class="item_text">New Player</span></span><span class="plus"></span></span></a></li>
	<li id="nav-menu-item-7893" class="menu-item menu-item-type-post_type menu-item-object-page "><a href="https://www.smsa-sji.sg/epic-holiday-football-camp-sss/" class=""><span class="item_outer"><span class="item_inner"><span class="menu_icon_wrapper"><i class="menu_icon null fa"></i></span><span class="item_text">EPIC Holiday Football Camp SSS</span></span><span class="plus"></span></span></a></li>
	<li id="nav-menu-item-6020" class="menu-item menu-item-type-post_type menu-item-object-page "><a href="https://www.smsa-sji.sg/volunteer/" class=""><span class="item_outer"><span class="item_inner"><span class="menu_icon_wrapper"><i class="menu_icon null fa"></i></span><span class="item_text">Get Involved</span></span><span class="plus"></span></span></a></li>
</ul></div></div>
</li>
<li id="nav-menu-item-95" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-has-children  has_sub narrow"><a href="https://www.smsa-sji.sg/shop/" class=" no_link" style="cursor: default;" onclick="JavaScript: return false;"><span class="item_outer"><span class="item_inner"><span class="menu_icon_wrapper"><i class="menu_icon null fa"></i></span><span class="item_text">Shop</span></span><span class="plus"></span></span></a>
<div class="second"><div class="inner"><ul>
	<li id="nav-menu-item-9929" class="menu-item menu-item-type-custom menu-item-object-custom "><a href="http://www.smsa-sji.sg/product/training-kit" class=""><span class="item_outer"><span class="item_inner"><span class="menu_icon_wrapper"><i class="menu_icon null fa"></i></span><span class="item_text">Training Kit</span></span><span class="plus"></span></span></a></li>
	<li id="nav-menu-item-9933" class="menu-item menu-item-type-custom menu-item-object-custom "><a href="http://www.smsa-sji.sg/match-kit/" class=""><span class="item_outer"><span class="item_inner"><span class="menu_icon_wrapper"><i class="menu_icon null fa"></i></span><span class="item_text">Match Kit</span></span><span class="plus"></span></span></a></li>
	<li id="nav-menu-item-97" class="menu-item menu-item-type-post_type menu-item-object-page "><a href="https://www.smsa-sji.sg/for-parents/" class=""><span class="item_outer"><span class="item_inner"><span class="menu_icon_wrapper"><i class="menu_icon null fa"></i></span><span class="item_text">For Parents and Children</span></span><span class="plus"></span></span></a></li>
</ul></div></div>
</li>
<li id="nav-menu-item-6026" class="menu-item menu-item-type-post_type menu-item-object-page  narrow"><a href="https://www.smsa-sji.sg/contact-us/" class=""><span class="item_outer"><span class="item_inner"><span class="menu_icon_wrapper"><i class="menu_icon null fa"></i></span><span class="item_text">Contact Us</span></span><span class="plus"></span></span></a></li>
</ul></nav>

                                                    
        <a 			data-icon-close-same-position="yes"                        class="qodef-search-opener" href="javascript:void(0)">
            <i class="qodef-icon-ion-icon ion-ios-search-strong " ></i>                    </a>
		            <a class="qodef-side-menu-button-opener "  href="javascript:void(0)">
            <span aria-hidden="true" class="qodef-icon-font-elegant arrow_triangle-right " ></span>        </a>

                                                </div>
                </div>
            </div>
            </div>
        
<div class="qodef-sticky-header">
    <form role="search" action="https://www.smsa-sji.sg/" class="qodef-search-cover" method="get">
		<div class="qodef-container">
		<div class="qodef-container-inner clearfix">
						<div class="qodef-form-holder-outer">
				<div class="qodef-form-holder">
					<div class="qodef-form-holder-inner">
						<input type="text" placeholder="Search" name="s" class="qode_search_field no-livesearch" autocomplete="off" />
						<div class="qodef-search-close">
							<a href="#">
								<i class="qodef-icon-ion-icon ion-close " ></i>							</a>
						</div>
					</div>
				</div>
			</div>
					</div>
	</div>
	</form>    <div class="qodef-sticky-holder">
                <div class=" qodef-vertical-align-containers">
                <div class="qodef-position-left">
                    <div class="qodef-position-left-inner">
                        
<div class="qodef-logo-wrapper">
    <a href="https://www.smsa-sji.sg/" style="height: 75px;">
        <img class="qodef-normal-logo" src="http://www.smsa-sji.sg/wp-content/uploads/2017/08/logo.png" alt="logo"/>
        <img class="qodef-dark-logo" src="http://www.smsa-sji.sg/wp-content/uploads/2017/08/logo.png" alt="dark logo"/>        <img class="qodef-light-logo" src="http://www.smsa-sji.sg/wp-content/uploads/2017/08/logo.png" alt="light logo"/>    </a>
</div>

                    </div>
                </div>
                <div class="qodef-position-right">
                    <div class="qodef-position-right-inner">

                        
<nav class="qodef-main-menu qodef-drop-down qodef-sticky-nav">
    <ul id="menu-main-menu-1" class="clearfix"><li id="sticky-nav-menu-item-24" class="menu-item menu-item-type-custom menu-item-object-custom current-menu-item current_page_item menu-item-home qodef-active-item narrow"><a href="http://www.smsa-sji.sg" class=" current "><span class="item_outer"><span class="item_inner"><span class="menu_icon_wrapper"><i class="menu_icon null fa"></i></span><span class="item_text">Home</span></span><span class="plus"></span></span></a></li>
<li id="sticky-nav-menu-item-7080" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-has-children  has_sub narrow"><a href="#" class=" no_link" style="cursor: default;" onclick="JavaScript: return false;"><span class="item_outer"><span class="item_inner"><span class="menu_icon_wrapper"><i class="menu_icon null fa"></i></span><span class="item_text">About Us</span></span><span class="plus"></span></span></a>
<div class="second"><div class="inner"><ul>
	<li id="sticky-nav-menu-item-29" class="menu-item menu-item-type-post_type menu-item-object-page "><a href="https://www.smsa-sji.sg/about-st-michaels-soccer-association/" class=""><span class="item_outer"><span class="item_inner"><span class="menu_icon_wrapper"><i class="menu_icon null fa"></i></span><span class="item_text">About St Michael&#8217;s Soccer Association</span></span><span class="plus"></span></span></a></li>
	<li id="sticky-nav-menu-item-30" class="menu-item menu-item-type-post_type menu-item-object-page "><a href="https://www.smsa-sji.sg/our-constitution/" class=""><span class="item_outer"><span class="item_inner"><span class="menu_icon_wrapper"><i class="menu_icon null fa"></i></span><span class="item_text">Our Constitution</span></span><span class="plus"></span></span></a></li>
	<li id="sticky-nav-menu-item-31" class="menu-item menu-item-type-post_type menu-item-object-page "><a href="https://www.smsa-sji.sg/committee/" class=""><span class="item_outer"><span class="item_inner"><span class="menu_icon_wrapper"><i class="menu_icon null fa"></i></span><span class="item_text">Committee</span></span><span class="plus"></span></span></a></li>
	<li id="sticky-nav-menu-item-10971" class="menu-item menu-item-type-post_type menu-item-object-page "><a href="https://www.smsa-sji.sg/sponsor-and-partner/" class=""><span class="item_outer"><span class="item_inner"><span class="menu_icon_wrapper"><i class="menu_icon blank fa"></i></span><span class="item_text">Sponsor and Partner</span></span><span class="plus"></span></span></a></li>
	<li id="sticky-nav-menu-item-32" class="menu-item menu-item-type-post_type menu-item-object-page "><a href="https://www.smsa-sji.sg/cca-faq-sheet/" class=""><span class="item_outer"><span class="item_inner"><span class="menu_icon_wrapper"><i class="menu_icon null fa"></i></span><span class="item_text">CCA FAQ Sheet</span></span><span class="plus"></span></span></a></li>
	<li id="sticky-nav-menu-item-8403" class="menu-item menu-item-type-custom menu-item-object-custom "><a href="https://www.facebook.com/pg/smsa.sji/photos/?ref=page_internal" class=""><span class="item_outer"><span class="item_inner"><span class="menu_icon_wrapper"><i class="menu_icon null fa"></i></span><span class="item_text">Photo Gallery</span></span><span class="plus"></span></span></a></li>
</ul></div></div>
</li>
<li id="sticky-nav-menu-item-7119" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-has-children  has_sub narrow"><a href="#" class=" no_link" style="cursor: default;" onclick="JavaScript: return false;"><span class="item_outer"><span class="item_inner"><span class="menu_icon_wrapper"><i class="menu_icon null fa"></i></span><span class="item_text">Programmes</span></span><span class="plus"></span></span></a>
<div class="second"><div class="inner"><ul>
	<li id="sticky-nav-menu-item-63" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-has-children sub"><a href="https://www.smsa-sji.sg/st-michaels-soccer-academy/" class=" no_link" style="cursor: default;" onclick="JavaScript: return false;"><span class="item_outer"><span class="item_inner"><span class="menu_icon_wrapper"><i class="menu_icon null fa"></i></span><span class="item_text">St Michael&#8217;s Soccer Academy</span></span><span class="plus"></span><i class="q_menu_arrow fa fa-angle-right"></i></span></a>
	<ul>
		<li id="sticky-nav-menu-item-66" class="menu-item menu-item-type-post_type menu-item-object-page "><a href="https://www.smsa-sji.sg/players-programmes/" class=""><span class="item_outer"><span class="item_inner"><span class="menu_icon_wrapper"><i class="menu_icon null fa"></i></span><span class="item_text">Players Programmes</span></span><span class="plus"></span></span></a></li>
		<li id="sticky-nav-menu-item-67" class="menu-item menu-item-type-post_type menu-item-object-page "><a href="https://www.smsa-sji.sg/players-values/" class=""><span class="item_outer"><span class="item_inner"><span class="menu_icon_wrapper"><i class="menu_icon null fa"></i></span><span class="item_text">Player Values</span></span><span class="plus"></span></span></a></li>
		<li id="sticky-nav-menu-item-6162" class="menu-item menu-item-type-custom menu-item-object-custom "><a href="http://www.smsa-sji.sg/coaching-format" class=""><span class="item_outer"><span class="item_inner"><span class="menu_icon_wrapper"><i class="menu_icon null fa"></i></span><span class="item_text">Coaching Format</span></span><span class="plus"></span></span></a></li>
		<li id="sticky-nav-menu-item-69" class="menu-item menu-item-type-post_type menu-item-object-page "><a href="https://www.smsa-sji.sg/competitions/" class=""><span class="item_outer"><span class="item_inner"><span class="menu_icon_wrapper"><i class="menu_icon null fa"></i></span><span class="item_text">Code of Conduct for Competitions</span></span><span class="plus"></span></span></a></li>
		<li id="sticky-nav-menu-item-10038" class="menu-item menu-item-type-post_type menu-item-object-page "><a href="https://www.smsa-sji.sg/?page_id=10035" class=""><span class="item_outer"><span class="item_inner"><span class="menu_icon_wrapper"><i class="menu_icon blank fa"></i></span><span class="item_text">League Table and Fixtures</span></span><span class="plus"></span></span></a></li>
		<li id="sticky-nav-menu-item-10425" class="menu-item menu-item-type-post_type menu-item-object-page "><a href="https://www.smsa-sji.sg/?page_id=10375" class=""><span class="item_outer"><span class="item_inner"><span class="menu_icon_wrapper"><i class="menu_icon blank fa"></i></span><span class="item_text">Saints League 2019</span></span><span class="plus"></span></span></a></li>
		<li id="sticky-nav-menu-item-70" class="menu-item menu-item-type-post_type menu-item-object-page "><a href="https://www.smsa-sji.sg/our-coaches/" class=""><span class="item_outer"><span class="item_inner"><span class="menu_icon_wrapper"><i class="menu_icon null fa"></i></span><span class="item_text">Our Coaches</span></span><span class="plus"></span></span></a></li>
		<li id="sticky-nav-menu-item-71" class="menu-item menu-item-type-post_type menu-item-object-page "><a href="https://www.smsa-sji.sg/schedule-locations/" class=""><span class="item_outer"><span class="item_inner"><span class="menu_icon_wrapper"><i class="menu_icon null fa"></i></span><span class="item_text">Schedule &#038; Locations</span></span><span class="plus"></span></span></a></li>
		<li id="sticky-nav-menu-item-72" class="menu-item menu-item-type-post_type menu-item-object-page "><a href="https://www.smsa-sji.sg/fees/" class=""><span class="item_outer"><span class="item_inner"><span class="menu_icon_wrapper"><i class="menu_icon null fa"></i></span><span class="item_text">Fees</span></span><span class="plus"></span></span></a></li>
	</ul>
</li>
	<li id="sticky-nav-menu-item-64" class="menu-item menu-item-type-post_type menu-item-object-page "><a href="https://www.smsa-sji.sg/epic-holiday-camp/" class=""><span class="item_outer"><span class="item_inner"><span class="menu_icon_wrapper"><i class="menu_icon null fa"></i></span><span class="item_text">EPIC Holiday Football Camp Main</span></span><span class="plus"></span></span></a></li>
	<li id="sticky-nav-menu-item-10842" class="menu-item menu-item-type-post_type menu-item-object-page "><a href="https://www.smsa-sji.sg/?page_id=10813" class=""><span class="item_outer"><span class="item_inner"><span class="menu_icon_wrapper"><i class="menu_icon blank fa"></i></span><span class="item_text">Shanghai Greenland Shenhua F.C.</span></span><span class="plus"></span></span></a></li>
</ul></div></div>
</li>
<li id="sticky-nav-menu-item-6897" class="menu-item menu-item-type-post_type menu-item-object-page  narrow"><a href="https://www.smsa-sji.sg/?page_id=6894" class=""><span class="item_outer"><span class="item_inner"><span class="menu_icon_wrapper"><i class="menu_icon null fa"></i></span><span class="item_text">Events Calendar</span></span><span class="plus"></span></span></a></li>
<li id="sticky-nav-menu-item-91" class="menu-item menu-item-type-post_type menu-item-object-page  narrow"><a href="https://www.smsa-sji.sg/?page_id=74" class=""><span class="item_outer"><span class="item_inner"><span class="menu_icon_wrapper"><i class="menu_icon null fa"></i></span><span class="item_text">Latest News</span></span><span class="plus"></span></span></a></li>
<li id="sticky-nav-menu-item-92" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-has-children  has_sub narrow"><a href="https://www.smsa-sji.sg/sign-up/" class=" no_link" style="cursor: default;" onclick="JavaScript: return false;"><span class="item_outer"><span class="item_inner"><span class="menu_icon_wrapper"><i class="menu_icon null fa"></i></span><span class="item_text">Sign Up</span></span><span class="plus"></span></span></a>
<div class="second"><div class="inner"><ul>
	<li id="sticky-nav-menu-item-93" class="menu-item menu-item-type-post_type menu-item-object-page "><a href="https://www.smsa-sji.sg/trial/" class=""><span class="item_outer"><span class="item_inner"><span class="menu_icon_wrapper"><i class="menu_icon null fa"></i></span><span class="item_text">Trial</span></span><span class="plus"></span></span></a></li>
	<li id="sticky-nav-menu-item-94" class="menu-item menu-item-type-post_type menu-item-object-page "><a href="https://www.smsa-sji.sg/new-player/" class=""><span class="item_outer"><span class="item_inner"><span class="menu_icon_wrapper"><i class="menu_icon null fa"></i></span><span class="item_text">New Player</span></span><span class="plus"></span></span></a></li>
	<li id="sticky-nav-menu-item-7893" class="menu-item menu-item-type-post_type menu-item-object-page "><a href="https://www.smsa-sji.sg/epic-holiday-football-camp-sss/" class=""><span class="item_outer"><span class="item_inner"><span class="menu_icon_wrapper"><i class="menu_icon null fa"></i></span><span class="item_text">EPIC Holiday Football Camp SSS</span></span><span class="plus"></span></span></a></li>
	<li id="sticky-nav-menu-item-6020" class="menu-item menu-item-type-post_type menu-item-object-page "><a href="https://www.smsa-sji.sg/volunteer/" class=""><span class="item_outer"><span class="item_inner"><span class="menu_icon_wrapper"><i class="menu_icon null fa"></i></span><span class="item_text">Get Involved</span></span><span class="plus"></span></span></a></li>
</ul></div></div>
</li>
<li id="sticky-nav-menu-item-95" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-has-children  has_sub narrow"><a href="https://www.smsa-sji.sg/shop/" class=" no_link" style="cursor: default;" onclick="JavaScript: return false;"><span class="item_outer"><span class="item_inner"><span class="menu_icon_wrapper"><i class="menu_icon null fa"></i></span><span class="item_text">Shop</span></span><span class="plus"></span></span></a>
<div class="second"><div class="inner"><ul>
	<li id="sticky-nav-menu-item-9929" class="menu-item menu-item-type-custom menu-item-object-custom "><a href="http://www.smsa-sji.sg/product/training-kit" class=""><span class="item_outer"><span class="item_inner"><span class="menu_icon_wrapper"><i class="menu_icon null fa"></i></span><span class="item_text">Training Kit</span></span><span class="plus"></span></span></a></li>
	<li id="sticky-nav-menu-item-9933" class="menu-item menu-item-type-custom menu-item-object-custom "><a href="http://www.smsa-sji.sg/match-kit/" class=""><span class="item_outer"><span class="item_inner"><span class="menu_icon_wrapper"><i class="menu_icon null fa"></i></span><span class="item_text">Match Kit</span></span><span class="plus"></span></span></a></li>
	<li id="sticky-nav-menu-item-97" class="menu-item menu-item-type-post_type menu-item-object-page "><a href="https://www.smsa-sji.sg/for-parents/" class=""><span class="item_outer"><span class="item_inner"><span class="menu_icon_wrapper"><i class="menu_icon null fa"></i></span><span class="item_text">For Parents and Children</span></span><span class="plus"></span></span></a></li>
</ul></div></div>
</li>
<li id="sticky-nav-menu-item-6026" class="menu-item menu-item-type-post_type menu-item-object-page  narrow"><a href="https://www.smsa-sji.sg/contact-us/" class=""><span class="item_outer"><span class="item_inner"><span class="menu_icon_wrapper"><i class="menu_icon null fa"></i></span><span class="item_text">Contact Us</span></span><span class="plus"></span></span></a></li>
</ul></nav>


        <a 			data-icon-close-same-position="yes"                        class="qodef-search-opener" href="javascript:void(0)">
            <i class="qodef-icon-ion-icon ion-ios-search-strong " ></i>                    </a>
		            <a class="qodef-side-menu-button-opener "  href="javascript:void(0)">
            <span aria-hidden="true" class="qodef-icon-font-elegant arrow_triangle-right " ></span>        </a>

    
                    </div>
                </div>
            </div>
                </div>
</div>

</header>


<header class="qodef-mobile-header">
    <div class="qodef-mobile-header-inner">
                <div class="qodef-mobile-header-holder">
            <div class="qodef-grid">
                <div class="qodef-vertical-align-containers">
                                            <div class="qodef-mobile-menu-opener">
                            <a href="javascript:void(0)">
                    <span class="qodef-mobile-opener-icon-holder">
                        <i class="qodef-icon-ion-icon ion-navicon " ></i>                    </span>
                            </a>
                        </div>
                                                                <div class="qodef-position-center">
                            <div class="qodef-position-center-inner">
                                
<div class="qodef-mobile-logo-wrapper">
    <a href="https://www.smsa-sji.sg/" style="height: 75px">
        <img src="http://www.smsa-sji.sg/wp-content/uploads/2017/08/logo.png" alt="mobile-logo"/>
    </a>
</div>

                            </div>
                        </div>
                                        <div class="qodef-position-right">
                        <div class="qodef-position-right-inner">
                                                    </div>
                    </div>
                </div> <!-- close .qodef-vertical-align-containers -->
            </div>
        </div>
        
<nav class="qodef-mobile-nav">
    <div class="qodef-grid">
        <ul id="menu-main-menu-2" class=""><li id="mobile-menu-item-24" class="menu-item menu-item-type-custom menu-item-object-custom current-menu-item current_page_item menu-item-home qodef-active-item"><a href="http://www.smsa-sji.sg" class=" current "><span>Home</span></a></li>
<li id="mobile-menu-item-7080" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-has-children  has_sub"><h4><span>About Us</span></h4><span class="mobile_arrow"><i class="qodef-sub-arrow fa fa-angle-right"></i><i class="fa fa-angle-down"></i></span>
<ul class="sub_menu">
	<li id="mobile-menu-item-29" class="menu-item menu-item-type-post_type menu-item-object-page "><a href="https://www.smsa-sji.sg/about-st-michaels-soccer-association/" class=""><span>About St Michael&#8217;s Soccer Association</span></a></li>
	<li id="mobile-menu-item-30" class="menu-item menu-item-type-post_type menu-item-object-page "><a href="https://www.smsa-sji.sg/our-constitution/" class=""><span>Our Constitution</span></a></li>
	<li id="mobile-menu-item-31" class="menu-item menu-item-type-post_type menu-item-object-page "><a href="https://www.smsa-sji.sg/committee/" class=""><span>Committee</span></a></li>
	<li id="mobile-menu-item-10971" class="menu-item menu-item-type-post_type menu-item-object-page "><a href="https://www.smsa-sji.sg/sponsor-and-partner/" class=""><span>Sponsor and Partner</span></a></li>
	<li id="mobile-menu-item-32" class="menu-item menu-item-type-post_type menu-item-object-page "><a href="https://www.smsa-sji.sg/cca-faq-sheet/" class=""><span>CCA FAQ Sheet</span></a></li>
	<li id="mobile-menu-item-8403" class="menu-item menu-item-type-custom menu-item-object-custom "><a href="https://www.facebook.com/pg/smsa.sji/photos/?ref=page_internal" class=""><span>Photo Gallery</span></a></li>
</ul>
</li>
<li id="mobile-menu-item-7119" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-has-children  has_sub"><h4><span>Programmes</span></h4><span class="mobile_arrow"><i class="qodef-sub-arrow fa fa-angle-right"></i><i class="fa fa-angle-down"></i></span>
<ul class="sub_menu">
	<li id="mobile-menu-item-63" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-has-children  has_sub"><h4><span>St Michael&#8217;s Soccer Academy</span></h4><span class="mobile_arrow"><i class="qodef-sub-arrow fa fa-angle-right"></i><i class="fa fa-angle-down"></i></span>
	<ul class="sub_menu">
		<li id="mobile-menu-item-66" class="menu-item menu-item-type-post_type menu-item-object-page "><a href="https://www.smsa-sji.sg/players-programmes/" class=""><span>Players Programmes</span></a></li>
		<li id="mobile-menu-item-67" class="menu-item menu-item-type-post_type menu-item-object-page "><a href="https://www.smsa-sji.sg/players-values/" class=""><span>Player Values</span></a></li>
		<li id="mobile-menu-item-6162" class="menu-item menu-item-type-custom menu-item-object-custom "><a href="http://www.smsa-sji.sg/coaching-format" class=""><span>Coaching Format</span></a></li>
		<li id="mobile-menu-item-69" class="menu-item menu-item-type-post_type menu-item-object-page "><a href="https://www.smsa-sji.sg/competitions/" class=""><span>Code of Conduct for Competitions</span></a></li>
		<li id="mobile-menu-item-10038" class="menu-item menu-item-type-post_type menu-item-object-page "><a href="https://www.smsa-sji.sg/?page_id=10035" class=""><span>League Table and Fixtures</span></a></li>
		<li id="mobile-menu-item-10425" class="menu-item menu-item-type-post_type menu-item-object-page "><a href="https://www.smsa-sji.sg/?page_id=10375" class=""><span>Saints League 2019</span></a></li>
		<li id="mobile-menu-item-70" class="menu-item menu-item-type-post_type menu-item-object-page "><a href="https://www.smsa-sji.sg/our-coaches/" class=""><span>Our Coaches</span></a></li>
		<li id="mobile-menu-item-71" class="menu-item menu-item-type-post_type menu-item-object-page "><a href="https://www.smsa-sji.sg/schedule-locations/" class=""><span>Schedule &#038; Locations</span></a></li>
		<li id="mobile-menu-item-72" class="menu-item menu-item-type-post_type menu-item-object-page "><a href="https://www.smsa-sji.sg/fees/" class=""><span>Fees</span></a></li>
	</ul>
</li>
	<li id="mobile-menu-item-64" class="menu-item menu-item-type-post_type menu-item-object-page "><a href="https://www.smsa-sji.sg/epic-holiday-camp/" class=""><span>EPIC Holiday Football Camp Main</span></a></li>
	<li id="mobile-menu-item-10842" class="menu-item menu-item-type-post_type menu-item-object-page "><a href="https://www.smsa-sji.sg/?page_id=10813" class=""><span>Shanghai Greenland Shenhua F.C.</span></a></li>
</ul>
</li>
<li id="mobile-menu-item-6897" class="menu-item menu-item-type-post_type menu-item-object-page "><a href="https://www.smsa-sji.sg/?page_id=6894" class=""><span>Events Calendar</span></a></li>
<li id="mobile-menu-item-91" class="menu-item menu-item-type-post_type menu-item-object-page "><a href="https://www.smsa-sji.sg/?page_id=74" class=""><span>Latest News</span></a></li>
<li id="mobile-menu-item-92" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-has-children  has_sub"><h4><span>Sign Up</span></h4><span class="mobile_arrow"><i class="qodef-sub-arrow fa fa-angle-right"></i><i class="fa fa-angle-down"></i></span>
<ul class="sub_menu">
	<li id="mobile-menu-item-93" class="menu-item menu-item-type-post_type menu-item-object-page "><a href="https://www.smsa-sji.sg/trial/" class=""><span>Trial</span></a></li>
	<li id="mobile-menu-item-94" class="menu-item menu-item-type-post_type menu-item-object-page "><a href="https://www.smsa-sji.sg/new-player/" class=""><span>New Player</span></a></li>
	<li id="mobile-menu-item-7893" class="menu-item menu-item-type-post_type menu-item-object-page "><a href="https://www.smsa-sji.sg/epic-holiday-football-camp-sss/" class=""><span>EPIC Holiday Football Camp SSS</span></a></li>
	<li id="mobile-menu-item-6020" class="menu-item menu-item-type-post_type menu-item-object-page "><a href="https://www.smsa-sji.sg/volunteer/" class=""><span>Get Involved</span></a></li>
</ul>
</li>
<li id="mobile-menu-item-95" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-has-children  has_sub"><h4><span>Shop</span></h4><span class="mobile_arrow"><i class="qodef-sub-arrow fa fa-angle-right"></i><i class="fa fa-angle-down"></i></span>
<ul class="sub_menu">
	<li id="mobile-menu-item-9929" class="menu-item menu-item-type-custom menu-item-object-custom "><a href="http://www.smsa-sji.sg/product/training-kit" class=""><span>Training Kit</span></a></li>
	<li id="mobile-menu-item-9933" class="menu-item menu-item-type-custom menu-item-object-custom "><a href="http://www.smsa-sji.sg/match-kit/" class=""><span>Match Kit</span></a></li>
	<li id="mobile-menu-item-97" class="menu-item menu-item-type-post_type menu-item-object-page "><a href="https://www.smsa-sji.sg/for-parents/" class=""><span>For Parents and Children</span></a></li>
</ul>
</li>
<li id="mobile-menu-item-6026" class="menu-item menu-item-type-post_type menu-item-object-page "><a href="https://www.smsa-sji.sg/contact-us/" class=""><span>Contact Us</span></a></li>
</ul>    </div>
</nav>

    </div>
</header> <!-- close .qodef-mobile-header -->



                    <a id='qodef-back-to-top'  href='#'>
                <span class="qodef-icon-stack">
                     <i class="qodef-icon-font-awesome fa fa-chevron-up " ></i>                </span>
            </a>
                
        <div class="qodef-content" style="margin-top: -100px">
 <div class="qodef-content-inner">	<div class="qodef-slider">
		<div class="qodef-slider-inner">
			<div id="qodef-home-main-slider"    data-qodef_responsive_graphic_coefficients = "1,1,0.8,0.7,0.6,0.5,0.4" data-qodef_responsive_title_coefficients = "1,1,0.8,0.7,0.6,0.5,0.4" data-qodef_responsive_subtitle_coefficients = "1,1,0.8,0.7,0.6,0.5,0.4" data-qodef_responsive_text_coefficients = "1,1,0.8,0.7,0.6,0.5,0.4" data-qodef_responsive_button_coefficients = "1,1,0.8,0.7,0.6,0.5,0.4" class="carousel slide  qodef-full-screen   qodef-auto-start     " data-slide_animation_timeout="6000"  data-parallax="yes" ><div class="qodef-slider-preloader"><div class="qodef-st-loader"><div class="qodef-st-loader1"><div class="pulse"></div></div></div></div><div class="carousel-inner " style="height: 100%" data-start="transform: translateY(0px);" data-1440="transform: translateY(-500px);"><div class="item light  qodef-content-vertical-middle  qodef-animate-image zoom_bottom_right" style=" padding-top: 0px;" data-qodef_animate_image='zoom_bottom_right'><div class="qodef-image" style="background-image:url(http://www.smsa-sji.sg/wp-content/uploads/2015/11/01-home2.jpg)"><img src="http://www.smsa-sji.sg/wp-content/uploads/2015/11/01-home2.jpg" alt="St Michael&#8217;s Soccer Association"></div><div class="qodef-slider-content-outer"><div class="qodef-slider-content center"   data-0=" opacity: 1;   "  data-300=" opacity: 0;  "><div class="qodef-slider-content-inner one_by_one from_bottom" style="width:100%; position:relative; "><div class="qodef-text one_by_one from_bottom " style="margin-top: 50px;"><div class="qodef-el"><h2 class="qodef-slide-title" style="color: #ffffff;font-size: 100pxpx;font-family: &#039;Open Sans&#039;;font-style: normal;text-transform: none"><span >St Michael&#8217;s Soccer Association</span></h2></div><div class="qodef-el"><h3 class="qodef-slide-text" ><span >Beyond Soccer. Pride of Lasallians.</span></h3></div><div class="qodef-el"><div class="qodef-slide-buttons-holder"><a class="qodef-btn-hover-animation qodef-btn qodef-btn-medium qodef-btn-solid" href="http://www.smsa-sji.sg/trial/" target="_self"><span class="qodef-animation-overlay"></span><span class="qodef-btn-text">SIGN UP FOR A FREE TRIAL TODAY!</span></a><a class="qodef-btn-hover-animation qodef-btn qodef-btn-medium qodef-btn-default" href="http://www.smsa-sji.sg/new-player/" target="_self"><span class="qodef-animation-overlay"></span><span class="qodef-btn-text">REGISTER NOW</span></a></div></div></div></div></div></div></div><div class="item light  qodef-content-vertical-middle  qodef-animate-image zoom_bottom_right" style=" padding-top: 0px;" data-qodef_animate_image='zoom_bottom_right'><div class="qodef-image" style="background-image:url(http://www.smsa-sji.sg/wp-content/uploads/2015/11/home04.jpg)"><img src="http://www.smsa-sji.sg/wp-content/uploads/2015/11/home04.jpg" alt="For Josephians, by Josephians."></div><div class="qodef-slider-content-outer"><div class="qodef-slider-content center"   data-0=" opacity: 1;   "  data-300=" opacity: 0;  "><div class="qodef-slider-content-inner one_by_one fade" ><div class="qodef-text one_by_one fade " style=""><div class="qodef-el"><h2 class="qodef-slide-title" ><span >For Josephians, by Josephians.</span></h2></div><div class="qodef-el"><div class="qodef-slide-buttons-holder"><a class="qodef-btn-hover-animation qodef-btn qodef-btn-medium qodef-btn-solid" href="http://www.smsa-sji.sg/trial/" target="_self"><span class="qodef-animation-overlay"></span><span class="qodef-btn-text">SIGN UP FOR A FREE TRIAL TODAY!</span></a><a class="qodef-btn-hover-animation qodef-btn qodef-btn-medium qodef-btn-default" href="http://www.smsa-sji.sg/new-player/" target="_self"><span class="qodef-animation-overlay"></span><span class="qodef-btn-text">REGISTER NOW</span></a></div></div></div></div></div></div></div><div class="item light  qodef-content-vertical-middle  qodef-animate-image zoom_center" style=" padding-top: 0px;" data-qodef_animate_image='zoom_center'><div class="qodef-image" style="background-image:url(http://www.smsa-sji.sg/wp-content/uploads/2015/11/home02.jpg)"><img src="http://www.smsa-sji.sg/wp-content/uploads/2015/11/home02.jpg" alt="Building character, deepening values."></div><div class="qodef-slider-content-outer"><div class="qodef-slider-content center"   data-0=" opacity: 1;   "  data-300=" opacity: 0;  "><div class="qodef-slider-content-inner one_by_one from_bottom" style="width:100%; position:relative; "><div class="qodef-text one_by_one from_bottom " style=""><div class="qodef-el"><h2 class="qodef-slide-title" ><span >Building character, deepening values.</span></h2></div><div class="qodef-el"><div class="qodef-slide-buttons-holder"><a class="qodef-btn-hover-animation qodef-btn qodef-btn-medium qodef-btn-solid" href="http://www.smsa-sji.sg/trial/" target="_self"><span class="qodef-animation-overlay"></span><span class="qodef-btn-text">SIGN UP FOR A FREE TRIAL TODAY!</span></a><a class="qodef-btn-hover-animation qodef-btn qodef-btn-medium qodef-btn-default" href="http://www.smsa-sji.sg/new-player/" target="_self"><span class="qodef-animation-overlay"></span><span class="qodef-btn-text">REGISTER NOW</span></a></div></div></div></div></div></div></div><div class="item light  qodef-content-vertical-middle  qodef-animate-image zoom_center" style=" padding-top: 0px;" data-qodef_animate_image='zoom_center'><div class="qodef-image" style="background-image:url(http://www.smsa-sji.sg/wp-content/uploads/2015/11/home03.jpg)"><img src="http://www.smsa-sji.sg/wp-content/uploads/2015/11/home03.jpg" alt="Parent-Child Bonding"></div><div class="qodef-slider-content-outer"><div class="qodef-slider-content center"   data-0=" opacity: 1;   "  data-300=" opacity: 0;  "><div class="qodef-slider-content-inner one_by_one from_bottom" style="width:100%; position:relative; "><div class="qodef-text one_by_one from_bottom " style=""><div class="qodef-el"><h2 class="qodef-slide-title" ><span >Parent-Child Bonding</span></h2></div><div class="qodef-el"><h3 class="qodef-slide-text" ><span >Because nothing is more rewarding and fulfilling than journeying with your child.</span></h3></div><div class="qodef-el"><div class="qodef-slide-buttons-holder"><a class="qodef-btn-hover-animation qodef-btn qodef-btn-medium qodef-btn-solid" href="http://www.smsa-sji.sg/trial/" target="_self"><span class="qodef-animation-overlay"></span><span class="qodef-btn-text">SIGN UP FOR A FREE TRIAL TODAY!</span></a><a class="qodef-btn-hover-animation qodef-btn qodef-btn-medium qodef-btn-default" href="http://www.smsa-sji.sg/new-player/" target="_self"><span class="qodef-animation-overlay"></span><span class="qodef-btn-text">REGISTER NOW</span></a></div></div></div></div></div></div></div><div class="item light  qodef-content-vertical-middle  qodef-animate-image zoom_center" style=" padding-top: 0px;" data-qodef_animate_image='zoom_center'><div class="qodef-image" style="background-image:url(http://www.smsa-sji.sg/wp-content/uploads/2015/11/home-5a-e1509331123754.jpg)"><img src="http://www.smsa-sji.sg/wp-content/uploads/2015/11/home-5a-e1509331123754.jpg" alt="Making life-long friendships."></div><div class="qodef-slider-content-outer"><div class="qodef-slider-content center"   data-0=" opacity: 1;   "  data-300=" opacity: 0;  "><div class="qodef-slider-content-inner one_by_one from_bottom" style="width:100%; position:relative; "><div class="qodef-text one_by_one from_bottom " style=""><div class="qodef-el"><h2 class="qodef-slide-title" ><span >Making life-long friendships.</span></h2></div><div class="qodef-el"><h3 class="qodef-slide-text" ><span >Creating life-long memories.</span></h3></div><div class="qodef-el"><div class="qodef-slide-buttons-holder"><a class="qodef-btn-hover-animation qodef-btn qodef-btn-medium qodef-btn-solid" href="http://www.smsa-sji.sg/trial/" target="_self"><span class="qodef-animation-overlay"></span><span class="qodef-btn-text">SIGN UP FOR A FREE TRIAL TODAY!</span></a><a class="qodef-btn-hover-animation qodef-btn qodef-btn-medium qodef-btn-default" href="http://www.smsa-sji.sg/new-player/" target="_self"><span class="qodef-animation-overlay"></span><span class="qodef-btn-text">REGISTER NOW</span></a></div></div></div></div></div></div></div></div><ol class="carousel-indicators" data-start="opacity: 1;" data-300="opacity:0;"><li data-target="#qodef-home-main-slider" data-slide-to="0" class="active"></li><li data-target="#qodef-home-main-slider" data-slide-to="1"></li><li data-target="#qodef-home-main-slider" data-slide-to="2"></li><li data-target="#qodef-home-main-slider" data-slide-to="3"></li><li data-target="#qodef-home-main-slider" data-slide-to="4"></li></ol><div class="qodef-controls-holder"><a class="left carousel-control" style="padding-top: 100px;" href="#qodef-home-main-slider" data-slide="prev" data-start="opacity: 1;" data-300="opacity:0;"><span class="qodef-prev-nav"><span class="fa fa-chevron-left"></span></span></a><a class="right carousel-control" style="padding-top: 100px;" href="#qodef-home-main-slider" data-slide="next" data-start="opacity: 1;" data-300="opacity:0;"><span class="qodef-next-nav"><span class="fa fa-chevron-right"></span></span></a></div></div>			</div>
	</div>

<div class="qodef-full-width">
<div class="qodef-full-width-inner">
						<div class="vc_row wpb_row vc_row-fluid qodef-section vc_custom_1509371223345 qodef-content-aligment-center qodef-grid-section" style=""><div class="clearfix qodef-section-inner"><div class="qodef-section-inner-margin clearfix"><div class="wpb_column vc_column_container vc_col-sm-12"><div class="vc_column-inner "><div class="wpb_wrapper">
	<div class="wpb_text_column wpb_content_element  wpb_animate_when_almost_visible wpb_fadeInDown fadeInDown" >
		<div class="wpb_wrapper">
			<h2 style="text-align: center;"><span style="color: #ed1c2c;">Important Announcement</span></h2>

		</div>
	</div>
<div class="vc_empty_space"   style="height: 22px" ><span class="vc_empty_space_inner"></span></div>

	<div class="wpb_text_column wpb_content_element " >
		<div class="wpb_wrapper">
			<h3><span style="color: #ffffff;">Our new group of Executive Committee members were voted in the 9th Annual General Meeting, held at St. Joseph&#8217;s Institution International on Saturday, 27 May 2023.</span></h3>

		</div>
	</div>
<div class="vc_empty_space"   style="height: 30px" ><span class="vc_empty_space_inner"></span></div>
<a href="http://www.smsa-sji.sg/committee/" target="_self" style="background-color: #ed1b2d;font-size: 14px;font-weight: 500" class="qodef-btn qodef-btn-large qodef-btn-solid qodef-btn-custom-hover-bg qodef-btn-hover-animation" data-hover-bg-color="#ed1b2d" >
            <span  style="background-color: #bd0616"  class="qodef-animation-overlay"></span>
        <span class="qodef-btn-text">See our new EXCO members here </span>
    <span class="qodef-btn-text-icon"></span>
</a><div class="vc_empty_space"   style="height: 30px" ><span class="vc_empty_space_inner"></span></div>
</div></div></div></div></div></div><div class="vc_row wpb_row vc_row-fluid qodef-section vc_custom_1446736175325 qodef-content-aligment-center qodef-grid-section" style=""><div class="clearfix qodef-section-inner"><div class="qodef-section-inner-margin clearfix"><div class="wpb_column vc_column_container vc_col-sm-12"><div class="vc_column-inner "><div class="wpb_wrapper">
	<div class="wpb_text_column wpb_content_element  wpb_animate_when_almost_visible wpb_bounceIn bounceIn" >
		<div class="wpb_wrapper">
			<h2 style="text-align: center;"><span style="color: #0d723b;">EPIC Holiday Football Camp</span></h2>

		</div>
	</div>
<div class="vc_empty_space"   style="height: 35px" ><span class="vc_empty_space_inner"></span></div>

	<div class="wpb_text_column wpb_content_element " >
		<div class="wpb_wrapper">
			<p>This football camp is focused on developing footwork, encouraging participation and imparting broader life skills. The ability to play is not a prerequisite to sign up. Children are grouped according to age and/or ability so that they learn within appropriate peer groups. This allows for greater support which helps them gain confidence. In addition to learning new sporting skills, emphasis is placed on fun and enjoyment, and on making new friends.</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p><b>The EPIC Holiday Football Camp takes place during the March, June, September and year-end school holidays</b>.</p>
<p><!-- The EPIC Holiday Football Camp takes place during the March, June, September and year-end school holidays.. --></p>

		</div>
	</div>
<div class="vc_empty_space"   style="height: 20px" ><span class="vc_empty_space_inner"></span></div>
<a href="#" target="_self" style="background-color: #ed1b2d;font-size: 14px;font-weight: 500" class="qodef-btn qodef-btn-large qodef-btn-solid qodef-btn-custom-hover-bg qodef-btn-hover-animation" data-hover-bg-color="#ed1b2d" >
            <span  style="background-color: #bd0616"  class="qodef-animation-overlay"></span>
        <span class="qodef-btn-text">Click here to find out</span>
    <span class="qodef-btn-text-icon"></span>
</a><div class="vc_empty_space"   style="height: 30px" ><span class="vc_empty_space_inner"></span></div>
</div></div></div></div></div></div><div class="vc_row wpb_row vc_row-fluid qodef-section vc_custom_1504621997955 qodef-content-aligment-left qodef-grid-section" style=""><div class="clearfix qodef-section-inner"><div class="qodef-section-inner-margin clearfix"><div class="wpb_animate_when_almost_visible wpb_slideInLeft slideInLeft wpb_column vc_column_container vc_col-sm-12 vc_col-md-6"><div class="vc_column-inner "><div class="wpb_wrapper">
	<div class="wpb_text_column wpb_content_element " >
		<div class="wpb_wrapper">
			<h2>Catch all the action here!</h2>

		</div>
	</div>
<div class="vc_empty_space"   style="height: 22px" ><span class="vc_empty_space_inner"></span></div>

	<div class="wpb_text_column wpb_content_element " >
		<div class="wpb_wrapper">
			<h3>Follow us on YouTube to watch all our events and match highlights.</h3>

		</div>
	</div>
<div class="vc_empty_space"   style="height: 39px" ><span class="vc_empty_space_inner"></span></div>
<a href="https://www.youtube.com/channel/UCWvcJTbIhyYX5LAYPQO-E1w/videos" target="_blank"  class="qodef-btn qodef-btn-medium qodef-btn-solid qodef-btn-icon qodef-btn-hover-animation"  >
            <span    class="qodef-animation-overlay"></span>
        <span class="qodef-btn-text">More videos</span>
    <span class="qodef-btn-text-icon"><i class="qodef-icon-font-awesome fa fa-youtube-play " ></i></span>
</a><div class="vc_empty_space"   style="height: 20px" ><span class="vc_empty_space_inner"></span></div>
</div></div></div><div class="wpb_column vc_column_container vc_col-sm-12 vc_col-md-6"><div class="vc_column-inner "><div class="wpb_wrapper">
	<div class="wpb_video_widget wpb_content_element vc_clearfix  wpb_animate_when_almost_visible wpb_bounceIn bounceIn  vc_video-aspect-ratio-169 vc_video-el-width-100 vc_video-align-left" >
		<div class="wpb_wrapper">
			
			<div class="wpb_video_wrapper"><iframe title="U10: BSS International Tournament Pattaya 1 -2 June 2019" width="1100" height="619" src="https://www.youtube.com/embed/mwtTki18dQU?feature=oembed" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></div>
		</div>
	</div>
</div></div></div></div></div></div>
<p>&nbsp;</p>
							</div>
</div>
</div> <!-- close div.content_inner -->
</div>  <!-- close div.content -->

<footer >
	<div class="qodef-footer-inner clearfix">

		
<div class="qodef-footer-top-holder">
	<div class="qodef-footer-top  qodef-footer-top-full">
		<div class="qodef-three-columns clearfix">
	<div class="qodef-three-columns-inner">
		<div class="qodef-column">
			<div class="qodef-column-inner">
				<div id="text-2" class="widget qodef-footer-column-1 widget_text"><h4 class="qodef-footer-widget-title">Contact Us</h4>			<div class="textwidget"><div class="vc_empty_space"   style="height: 10px" ><span class="vc_empty_space_inner"></span></div>


<p><b><font color="#ffffff">St Michael's Soccer Association</b><br>
3 Essex Road<br>
Singapore 309331
<br>Email: <a href="mailto:ask@smsa-sji.sg" target="_blank" rel="noopener">ask@smsa-sji.sg</a>
<br>Phone: +65 8111 0735</font></p>

<div class="vc_empty_space"   style="height: 28px" ><span class="vc_empty_space_inner"></span></div>

<div class="custom-color-row-changer">

    <span class="qodef-icon-shortcode square" style="margin: 0px -5px 0px 0px;width: 36px;height: 36px;line-height: 36px;background-color: rgba(255,255,255,0.01);border-style: solid;border-color: #b4b4b4;border-width: 1px" data-hover-border-color="#0d723b" data-hover-background-color="#0d723b" data-hover-color="#ffffff" data-color="#ffffff">
                     <a class="" href="https://www.facebook.com/smsa.sji/" target="_blank" rel="noopener">
        
        <i class="qodef-icon-font-awesome fa fa-facebook qodef-icon-element" style="color: #ffffff;font-size:18px" ></i>
                    </a>
            </span>




    <span class="qodef-icon-shortcode square" style="margin: 0px -4px 0px 0px;width: 36px;height: 36px;line-height: 36px;background-color: rgba(255,255,255,0.01);border-style: solid;border-color: #b4b4b4;border-width: 1px" data-hover-border-color="#0d723b" data-hover-background-color="#0d723b" data-hover-color="#ffffff" data-color="#ffffff">
                     <a class="" href="https://www.youtube.com/channel/UCWvcJTbIhyYX5LAYPQO-E1w/videos" target="_blank" rel="noopener">
        
        <i class="qodef-icon-font-awesome fa fa-youtube qodef-icon-element" style="color: #ffffff;font-size:18px" ></i>
                    </a>
            </span>





    <span class="qodef-icon-shortcode square" style="margin: 0px -4px 0px 0px;width: 36px;height: 36px;line-height: 36px;background-color: rgba(255,255,255,0.01);border-style: solid;border-color: #b4b4b4;border-width: 1px" data-hover-border-color="#0d723b" data-hover-background-color="#0d723b" data-hover-color="#ffffff" data-color="#ffffff">
                     <a class="" href="https://www.instagram.com/smsa_sji/" target="_blank" rel="noopener">
        
        <i class="qodef-icon-font-awesome fa fa-instagram qodef-icon-element" style="color: #ffffff;font-size:18px" ></i>
                    </a>
            </span>


</div></div>
		</div>			</div>
		</div>
		<div class="qodef-column">
			<div class="qodef-column-inner">
				<div id="text-17" class="widget qodef-footer-column-2 widget_text"><h4 class="qodef-footer-widget-title">Upcoming Events</h4>			<div class="textwidget"></div>
		</div><div id="evcalwidget-4" class="widget qodef-footer-column-2 EvcalWidget"><div id='evcal_widget' class='evo_widget'><div id='evcal_calendar_401' class='ajde_evcal_calendar ' ><div class='evo-data' data-cyear="2024" data-cmonth="6" data-runajax="1" data-evc_open="0" data-cal_ver="2.6.6" data-mapscroll="true" data-mapformat="roadmap" data-mapzoom="18" data-mapiconurl="" data-ev_cnt="0" data-show_limit="no" data-tiles="no" data-sort_by="sort_date" data-filters_on="false" data-range_start="0" data-range_end="0" data-send_unix="0" data-ux_val="0" data-accord="0" data-rtl="no"  ></div><div id='evcal_head' class='calendar_header ' ><div class='evo_cal_above'><span class='evo-gototoday-btn' style='display:none' data-mo='6' data-yr='2024' data-dy=''>Current Month</span></div><div class='evo_cal_above_content'></div><p id='evcal_cur' class='evo_month_title'> June, 2024</p><p class='evo_arrows'><span id='evcal_prev' class='evcal_arrows evcal_btn_prev' ><i class='fa fa-angle-left'></i></span><span id='evcal_next' class='evcal_arrows evcal_btn_next' ><i class='fa fa-angle-right'></i></span></p><div class='cal_arguments' style='display:none' data-hide_past="no" data-show_et_ft_img="no" data-event_order="ASC" data-ft_event_priority="no" data-lang="L1" data-month_incre="0" data-only_ft="no" data-evc_open="no" data-show_limit="no" data-etc_override="no" data-show_limit_redir="0" data-tiles="no" data-tile_height="0" data-tile_bg="0" data-tile_count="2" data-tile_style="0" data-s="" data-members_only="no" data-ux_val="0" data-show_limit_ajax="no" data-show_limit_paged="1" data-hide_mult_occur="no" data-show_repeats="no" ></div><div class='clear'></div></div><a class='evo_sort_btn'>Filter Events</a><div class='eventon_sorting_section' style='display:none'>
						<div class='eventon_sort_line evo_sortOpt' >
							<div class='evo_sortby'><p>Sort By:</p></div>
							<div class='evo_srt_sel'><p class='fa'>date</p><div class='evo_srt_options'><p data-val='sort_date' data-type='date' class='evs_btn evs_hide' >Date</p><p data-val='sort_title' data-type='title' class='evs_btn ' >Title</p></div></div><div class='clear'></div>
						</div><div class='eventon_filter_line '><div class='eventon_filter' data-filter_field='event_type' data-filter_val='all' data-filter_type='tax' data-fl_o='IN'></div><div class='eventon_filter' data-filter_field='event_type_2' data-filter_val='all' data-filter_type='tax' data-fl_o='IN'></div><div class='eventon_filter' data-filter_field='event_type_3' data-filter_val='all' data-filter_type='tax' data-fl_o='IN'></div><div class='eventon_filter' data-filter_field='event_type_4' data-filter_val='all' data-filter_type='tax' data-fl_o='IN'></div><div class='eventon_filter' data-filter_field='event_type_5' data-filter_val='all' data-filter_type='tax' data-fl_o='IN'></div><div class='eventon_filter' data-filter_field='event_location' data-filter_val='all' data-filter_type='tax' data-fl_o='IN'></div><div class='eventon_filter' data-filter_field='event_organizer' data-filter_val='all' data-filter_type='tax' data-fl_o='IN'></div></div><div class='clear'></div></div><div id='eventon_loadbar_section'><div id='eventon_loadbar'></div></div><div id='evcal_list' class='eventon_events_list'><div class='eventon_list_event'><p class='no_events' >There are currently no events planned for this month.</p></div>			<div class='clear'></div>
			</div><!-- #evcal_list-->
			<div class='clear'></div>
	
			
						</div><!-- .ajde_evcal_calendar-->

			</div></div>			</div>
		</div>
		<div class="qodef-column">
			<div class="qodef-column-inner">
				<div id="frm_show_form-2" class="widget qodef-footer-column-3 widget_frm_show_form"><div class="frm_form_widget"><h4 class="qodef-footer-widget-title">Send us a Message</h4><div class="frm_forms  with_frm_style frm_style_contact-us-form" id="frm_form_21_container" >
<form enctype="multipart/form-data" method="post" class="frm-show-form  frm_pro_form " id="form_2mcly"  >
<div class="frm_form_fields ">
<fieldset>
<legend class="frm_hidden">Enquiry Footer</legend>

<div class="frm_fields_container">
<input type="hidden" name="frm_action" value="create" />
<input type="hidden" name="form_id" value="21" />
<input type="hidden" name="frm_hide_fields_21" id="frm_hide_fields_21" value="" />
<input type="hidden" name="form_key" value="2mcly" />
<input type="hidden" name="item_meta[0]" value="" />
<input type="hidden" id="frm_submit_entry_21" name="frm_submit_entry_21" value="55de579e90" /><input type="hidden" name="_wp_http_referer" value="/" /><div id="frm_field_197_container" class="frm_form_field form-field  frm_top_container">
    <label for="field_tnigp" class="frm_primary_label">Your Name
        <span class="frm_required"></span>
    </label>
    <input type="text" id="field_tnigp" name="item_meta[197]" value=""  data-invmsg="Your Name is invalid" aria-invalid="false"  />
    
    
</div>
<div id="frm_field_199_container" class="frm_form_field form-field  frm_top_container">
    <label for="field_shmhi" class="frm_primary_label">Email Address
        <span class="frm_required"></span>
    </label>
    <input type="email" id="field_shmhi" name="item_meta[199]" value=""  data-invmsg="Email Address is invalid" aria-invalid="false"  />
    
    
</div>
<div id="frm_field_202_container" class="frm_form_field form-field  frm_top_container">
    <label for="field_5ix6x" class="frm_primary_label">Mobile Number
        <span class="frm_required"></span>
    </label>
    <input type="text" id="field_5ix6x" name="item_meta[202]" value=""  data-invmsg="Mobile Number is invalid" aria-invalid="false"  />
    
    
</div>
<div id="frm_field_201_container" class="frm_form_field form-field  frm_top_container">
    <label for="field_58gzo" class="frm_primary_label">Your Message
        <span class="frm_required"></span>
    </label>
    <textarea name="item_meta[201]" id="field_58gzo" rows="5"  data-invmsg="Your Message is invalid" aria-invalid="false"  ></textarea>
    
    
</div>
<div id="frm_field_1371_container" class="frm_form_field form-field  frm_none_container">
    <label  class="frm_primary_label">reCAPTCHA
        <span class="frm_required"></span>
    </label>
    <div id="field_tghq8" class="g-recaptcha" data-sitekey="6LfEZGMUAAAAAAAUJUMA5vZeJz0qaDOBTBMtnoh6" data-size="normal" data-theme="light"></div>
    
    
</div>
<input type="hidden" name="item_key" value="" />
	<input name="frm_state" type="hidden" value="N9FaBhvR3CK5lua9rlE3kdQ938JY1mPwb4FkMh2KmYg=" /><div class="frm_submit">

<button class="frm_button_submit frm_final_submit" type="submit"   formnovalidate="formnovalidate">Submit</button>

</div><div class="frm_verify" aria-hidden="true">
	<label for="frm_verify_21">
		If you are human, leave this field blank.	</label>
	<input type="text" class="frm_verify" id="frm_verify_21" name="frm_verify" value=""  />
</div>
</div>
</fieldset>
</div>
</form>
</div>
</div></div>			</div>
		</div>
	</div>
</div>	</div>
</div>

<div class="qodef-footer-bottom-holder">
	<div class="qodef-footer-bottom-holder-inner">
		<div class="qodef-column-inner">
	<div id="text-5" class="widget qodef-footer-text widget_text">			<div class="textwidget"><p><span style="color: #79cea0;">St Michael&#8217;s Soccer Association © Copyright 2015-2023. All Rights Reserved.</span></p>
</div>
		</div></div>		</div>
	</div>

	</div>
</footer>

</div> <!-- close div.qodef-wrapper-inner  -->
</div> <!-- close div.qodef-wrapper -->
<style type="text/css"> /* SportsPress Frontend CSS */ .sp-event-calendar tbody td a,.sp-event-calendar tbody td a:hover{background: none;}.sp-data-table th,.sp-calendar th,.sp-data-table tfoot,.sp-calendar tfoot,.sp-button,.sp-heading{background:#0d723b !important}.sp-calendar tbody a{color:#0d723b !important}.sp-data-table tbody,.sp-calendar tbody{background: #eeeeee !important}.sp-data-table tbody,.sp-calendar tbody{color: #333333 !important}.sp-data-table th,.sp-data-table th a,.sp-data-table tfoot,.sp-data-table tfoot a,.sp-calendar th,.sp-calendar th a,.sp-calendar tfoot,.sp-calendar tfoot a,.sp-button,.sp-heading{color: #ffffff !important}.sp-data-table tbody a,.sp-data-table tbody a:hover,.sp-calendar tbody a:focus{color: #0d723b !important}.sp-highlight,.sp-calendar td#today{background: #ffffff !important}.sp-data-table th,.sp-template-countdown .sp-event-venue,.sp-template-countdown .sp-event-league,.sp-template-gallery .gallery-caption{background:#0d723b !important}.sp-data-table th,.sp-template-countdown .sp-event-venue,.sp-template-countdown .sp-event-league,.sp-template-gallery .gallery-caption{border-color:#005821 !important}.sp-table-caption,.sp-data-table,.sp-data-table tfoot,.sp-template .sp-view-all-link,.sp-template-gallery .sp-gallery-group-name,.sp-template-gallery .sp-gallery-wrapper,.sp-template-countdown .sp-event-name,.sp-countdown time,.sp-template-details dl,.sp-event-statistics .sp-statistic-bar,.sp-tournament-bracket .sp-team-name,.sp-profile-selector{background:#eeeeee !important}.sp-table-caption,.sp-data-table,.sp-data-table td,.sp-template .sp-view-all-link,.sp-template-gallery .sp-gallery-group-name,.sp-template-gallery .sp-gallery-wrapper,.sp-template-countdown .sp-event-name,.sp-countdown time,.sp-countdown span,.sp-template-details dl,.sp-event-statistics .sp-statistic-bar,.sp-tournament-bracket thead th,.sp-tournament-bracket .sp-team-name,.sp-tournament-bracket .sp-event,.sp-profile-selector{border-color:#d4d4d4 !important}.sp-tournament-bracket .sp-team .sp-team-name:before{border-left-color:#d4d4d4 !important;border-right-color:#d4d4d4 !important}.sp-data-table .sp-highlight,.sp-data-table .highlighted td,.sp-template-scoreboard td:hover{background:#e8e8e8 !important}.sp-template *,.sp-data-table *,.sp-table-caption,.sp-data-table tfoot a:hover,.sp-template .sp-view-all-link a:hover,.sp-template-gallery .sp-gallery-group-name,.sp-template-details dd,.sp-template-event-logos .sp-team-result,.sp-template-event-blocks .sp-event-results,.sp-template-scoreboard a,.sp-template-scoreboard a:hover,.sp-tournament-bracket,.sp-tournament-bracket .sp-event .sp-event-title:hover,.sp-tournament-bracket .sp-event .sp-event-title:hover *{color:#333333 !important}.sp-template .sp-view-all-link a,.sp-countdown span small,.sp-template-event-calendar tfoot a,.sp-template-event-blocks .sp-event-date,.sp-template-details dt,.sp-template-scoreboard .sp-scoreboard-date,.sp-tournament-bracket th,.sp-tournament-bracket .sp-event .sp-event-title,.sp-template-scoreboard .sp-scoreboard-date,.sp-tournament-bracket .sp-event .sp-event-title *{color:rgba(51,51,51,0.5) !important}.sp-data-table th,.sp-template-countdown .sp-event-venue,.sp-template-countdown .sp-event-league,.sp-template-gallery .gallery-item a,.sp-template-gallery .gallery-caption,.sp-template-scoreboard .sp-scoreboard-nav,.sp-tournament-bracket .sp-team-name:hover,.sp-tournament-bracket thead th,.sp-tournament-bracket .sp-heading{color:#ffffff !important}.sp-template a,.sp-data-table a,.sp-tab-menu-item-active a, .sp-tab-menu-item-active a:hover,.sp-template .sp-message{color:#0d723b !important}.sp-template-gallery .gallery-caption strong,.sp-tournament-bracket .sp-team-name:hover,.sp-template-scoreboard .sp-scoreboard-nav,.sp-tournament-bracket .sp-heading{background:#0d723b !important}.sp-tournament-bracket .sp-team-name:hover,.sp-tournament-bracket .sp-heading,.sp-tab-menu-item-active a, .sp-tab-menu-item-active a:hover,.sp-template .sp-message{border-color:#0d723b !important}.sp-data-table th,.sp-data-table td{padding: 12px !important}</style><style type="text/css"> /* SportsPress Frontend CSS */ .sp-event-calendar tbody td a,.sp-event-calendar tbody td a:hover{background: none;}.sp-data-table th,.sp-calendar th,.sp-data-table tfoot,.sp-calendar tfoot,.sp-button,.sp-heading{background:#0d723b !important}.sp-calendar tbody a{color:#0d723b !important}.sp-data-table tbody,.sp-calendar tbody{background: #eeeeee !important}.sp-data-table tbody,.sp-calendar tbody{color: #333333 !important}.sp-data-table th,.sp-data-table th a,.sp-data-table tfoot,.sp-data-table tfoot a,.sp-calendar th,.sp-calendar th a,.sp-calendar tfoot,.sp-calendar tfoot a,.sp-button,.sp-heading{color: #ffffff !important}.sp-data-table tbody a,.sp-data-table tbody a:hover,.sp-calendar tbody a:focus{color: #0d723b !important}.sp-highlight,.sp-calendar td#today{background: #ffffff !important}.sp-data-table th,.sp-template-countdown .sp-event-venue,.sp-template-countdown .sp-event-league,.sp-template-gallery .gallery-caption{background:#0d723b !important}.sp-data-table th,.sp-template-countdown .sp-event-venue,.sp-template-countdown .sp-event-league,.sp-template-gallery .gallery-caption{border-color:#005821 !important}.sp-table-caption,.sp-data-table,.sp-data-table tfoot,.sp-template .sp-view-all-link,.sp-template-gallery .sp-gallery-group-name,.sp-template-gallery .sp-gallery-wrapper,.sp-template-countdown .sp-event-name,.sp-countdown time,.sp-template-details dl,.sp-event-statistics .sp-statistic-bar,.sp-tournament-bracket .sp-team-name,.sp-profile-selector{background:#eeeeee !important}.sp-table-caption,.sp-data-table,.sp-data-table td,.sp-template .sp-view-all-link,.sp-template-gallery .sp-gallery-group-name,.sp-template-gallery .sp-gallery-wrapper,.sp-template-countdown .sp-event-name,.sp-countdown time,.sp-countdown span,.sp-template-details dl,.sp-event-statistics .sp-statistic-bar,.sp-tournament-bracket thead th,.sp-tournament-bracket .sp-team-name,.sp-tournament-bracket .sp-event,.sp-profile-selector{border-color:#d4d4d4 !important}.sp-tournament-bracket .sp-team .sp-team-name:before{border-left-color:#d4d4d4 !important;border-right-color:#d4d4d4 !important}.sp-data-table .sp-highlight,.sp-data-table .highlighted td,.sp-template-scoreboard td:hover{background:#e8e8e8 !important}.sp-template *,.sp-data-table *,.sp-table-caption,.sp-data-table tfoot a:hover,.sp-template .sp-view-all-link a:hover,.sp-template-gallery .sp-gallery-group-name,.sp-template-details dd,.sp-template-event-logos .sp-team-result,.sp-template-event-blocks .sp-event-results,.sp-template-scoreboard a,.sp-template-scoreboard a:hover,.sp-tournament-bracket,.sp-tournament-bracket .sp-event .sp-event-title:hover,.sp-tournament-bracket .sp-event .sp-event-title:hover *{color:#333333 !important}.sp-template .sp-view-all-link a,.sp-countdown span small,.sp-template-event-calendar tfoot a,.sp-template-event-blocks .sp-event-date,.sp-template-details dt,.sp-template-scoreboard .sp-scoreboard-date,.sp-tournament-bracket th,.sp-tournament-bracket .sp-event .sp-event-title,.sp-template-scoreboard .sp-scoreboard-date,.sp-tournament-bracket .sp-event .sp-event-title *{color:rgba(51,51,51,0.5) !important}.sp-data-table th,.sp-template-countdown .sp-event-venue,.sp-template-countdown .sp-event-league,.sp-template-gallery .gallery-item a,.sp-template-gallery .gallery-caption,.sp-template-scoreboard .sp-scoreboard-nav,.sp-tournament-bracket .sp-team-name:hover,.sp-tournament-bracket thead th,.sp-tournament-bracket .sp-heading{color:#ffffff !important}.sp-template a,.sp-data-table a,.sp-tab-menu-item-active a, .sp-tab-menu-item-active a:hover,.sp-template .sp-message{color:#0d723b !important}.sp-template-gallery .gallery-caption strong,.sp-tournament-bracket .sp-team-name:hover,.sp-template-scoreboard .sp-scoreboard-nav,.sp-tournament-bracket .sp-heading{background:#0d723b !important}.sp-tournament-bracket .sp-team-name:hover,.sp-tournament-bracket .sp-heading,.sp-tab-menu-item-active a, .sp-tab-menu-item-active a:hover,.sp-template .sp-message{border-color:#0d723b !important}.sp-data-table th,.sp-data-table td{padding: 12px !important}</style><style type="text/css"> /* SportsPress Frontend CSS */ .sp-event-calendar tbody td a,.sp-event-calendar tbody td a:hover{background: none;}.sp-data-table th,.sp-calendar th,.sp-data-table tfoot,.sp-calendar tfoot,.sp-button,.sp-heading{background:#0d723b !important}.sp-calendar tbody a{color:#0d723b !important}.sp-data-table tbody,.sp-calendar tbody{background: #eeeeee !important}.sp-data-table tbody,.sp-calendar tbody{color: #333333 !important}.sp-data-table th,.sp-data-table th a,.sp-data-table tfoot,.sp-data-table tfoot a,.sp-calendar th,.sp-calendar th a,.sp-calendar tfoot,.sp-calendar tfoot a,.sp-button,.sp-heading{color: #ffffff !important}.sp-data-table tbody a,.sp-data-table tbody a:hover,.sp-calendar tbody a:focus{color: #0d723b !important}.sp-highlight,.sp-calendar td#today{background: #ffffff !important}.sp-data-table th,.sp-template-countdown .sp-event-venue,.sp-template-countdown .sp-event-league,.sp-template-gallery .gallery-caption{background:#0d723b !important}.sp-data-table th,.sp-template-countdown .sp-event-venue,.sp-template-countdown .sp-event-league,.sp-template-gallery .gallery-caption{border-color:#005821 !important}.sp-table-caption,.sp-data-table,.sp-data-table tfoot,.sp-template .sp-view-all-link,.sp-template-gallery .sp-gallery-group-name,.sp-template-gallery .sp-gallery-wrapper,.sp-template-countdown .sp-event-name,.sp-countdown time,.sp-template-details dl,.sp-event-statistics .sp-statistic-bar,.sp-tournament-bracket .sp-team-name,.sp-profile-selector{background:#eeeeee !important}.sp-table-caption,.sp-data-table,.sp-data-table td,.sp-template .sp-view-all-link,.sp-template-gallery .sp-gallery-group-name,.sp-template-gallery .sp-gallery-wrapper,.sp-template-countdown .sp-event-name,.sp-countdown time,.sp-countdown span,.sp-template-details dl,.sp-event-statistics .sp-statistic-bar,.sp-tournament-bracket thead th,.sp-tournament-bracket .sp-team-name,.sp-tournament-bracket .sp-event,.sp-profile-selector{border-color:#d4d4d4 !important}.sp-tournament-bracket .sp-team .sp-team-name:before{border-left-color:#d4d4d4 !important;border-right-color:#d4d4d4 !important}.sp-data-table .sp-highlight,.sp-data-table .highlighted td,.sp-template-scoreboard td:hover{background:#e8e8e8 !important}.sp-template *,.sp-data-table *,.sp-table-caption,.sp-data-table tfoot a:hover,.sp-template .sp-view-all-link a:hover,.sp-template-gallery .sp-gallery-group-name,.sp-template-details dd,.sp-template-event-logos .sp-team-result,.sp-template-event-blocks .sp-event-results,.sp-template-scoreboard a,.sp-template-scoreboard a:hover,.sp-tournament-bracket,.sp-tournament-bracket .sp-event .sp-event-title:hover,.sp-tournament-bracket .sp-event .sp-event-title:hover *{color:#333333 !important}.sp-template .sp-view-all-link a,.sp-countdown span small,.sp-template-event-calendar tfoot a,.sp-template-event-blocks .sp-event-date,.sp-template-details dt,.sp-template-scoreboard .sp-scoreboard-date,.sp-tournament-bracket th,.sp-tournament-bracket .sp-event .sp-event-title,.sp-template-scoreboard .sp-scoreboard-date,.sp-tournament-bracket .sp-event .sp-event-title *{color:rgba(51,51,51,0.5) !important}.sp-data-table th,.sp-template-countdown .sp-event-venue,.sp-template-countdown .sp-event-league,.sp-template-gallery .gallery-item a,.sp-template-gallery .gallery-caption,.sp-template-scoreboard .sp-scoreboard-nav,.sp-tournament-bracket .sp-team-name:hover,.sp-tournament-bracket thead th,.sp-tournament-bracket .sp-heading{color:#ffffff !important}.sp-template a,.sp-data-table a,.sp-tab-menu-item-active a, .sp-tab-menu-item-active a:hover,.sp-template .sp-message{color:#0d723b !important}.sp-template-gallery .gallery-caption strong,.sp-tournament-bracket .sp-team-name:hover,.sp-template-scoreboard .sp-scoreboard-nav,.sp-tournament-bracket .sp-heading{background:#0d723b !important}.sp-tournament-bracket .sp-team-name:hover,.sp-tournament-bracket .sp-heading,.sp-tab-menu-item-active a, .sp-tab-menu-item-active a:hover,.sp-template .sp-message{border-color:#0d723b !important}.sp-data-table th,.sp-data-table td{padding: 12px !important}</style>		<script type="text/javascript">
		/*<![CDATA[*/
		var gmapstyles = 'default';
		/* ]]> */
		</script>		
			<script type="text/javascript">
		(function () {
			var c = document.body.className;
			c = c.replace(/woocommerce-no-js/, 'woocommerce-js');
			document.body.className = c;
		})();
	</script>
	<div class='evo_lightboxes' style='display:block'>					<div class='evo_lightbox eventcard eventon_events_list' id='' >
						<div class="evo_content_in">													
							<div class="evo_content_inin">
								<div class="evo_lightbox_content">
									<a class='evolbclose '>X</a>
									<div class='evo_lightbox_body eventon_list_event evo_pop_body evcal_eventcard'> </div>
								</div>
							</div>							
						</div>
					</div>
					</div><link rel='stylesheet' id='animate-css-css' href='https://www.smsa-sji.sg/wp-content/plugins/js_composer/assets/lib/bower/animate-css/animate.min.css?ver=5.1.1' type='text/css' media='all' />
<script type="text/javascript" src="https://www.smsa-sji.sg/wp-includes/js/jquery/ui/datepicker.min.js?ver=1.13.2" id="jquery-ui-datepicker-js"></script>
<script type="text/javascript" id="jquery-ui-datepicker-js-after">
/* <![CDATA[ */
jQuery(function(jQuery){jQuery.datepicker.setDefaults({"closeText":"Close","currentText":"Today","monthNames":["January","February","March","April","May","June","July","August","September","October","November","December"],"monthNamesShort":["Jan","Feb","Mar","Apr","May","Jun","Jul","Aug","Sep","Oct","Nov","Dec"],"nextText":"Next","prevText":"Previous","dayNames":["Sunday","Monday","Tuesday","Wednesday","Thursday","Friday","Saturday"],"dayNamesShort":["Sun","Mon","Tue","Wed","Thu","Fri","Sat"],"dayNamesMin":["S","M","T","W","T","F","S"],"dateFormat":"MM d, yy","firstDay":1,"isRTL":false});});
/* ]]> */
</script>
<script type="text/javascript" src="https://www.smsa-sji.sg/wp-includes/js/jquery/ui/mouse.min.js?ver=1.13.2" id="jquery-ui-mouse-js"></script>
<script type="text/javascript" src="https://www.smsa-sji.sg/wp-includes/js/jquery/ui/draggable.min.js?ver=1.13.2" id="jquery-ui-draggable-js"></script>
<script type="text/javascript" id="GSWPTS-frontend-js-js-extra">
/* <![CDATA[ */
var front_end_data = {"admin_ajax":"https:\/\/www.smsa-sji.sg\/wp-admin\/admin-ajax.php","asynchronous_loading":"on","isProActive":"","iconsURL":""};
/* ]]> */
</script>
<script type="text/javascript" src="https://www.smsa-sji.sg/wp-content/plugins/sheets-to-wp-table-live-sync/assets/public/scripts/frontend/frontend.min.js?ver=2.14.0" id="GSWPTS-frontend-js-js"></script>
<script type="text/javascript" src="https://www.smsa-sji.sg/wp-content/plugins/sportspress/assets/js/jquery.dataTables.min.js?ver=1.10.4" id="jquery-datatables-js"></script>
<script type="text/javascript" id="sportspress-js-extra">
/* <![CDATA[ */
var localized_strings = {"days":"days","hrs":"hrs","mins":"mins","secs":"secs","previous":"Previous","next":"Next"};
/* ]]> */
</script>
<script type="text/javascript" src="https://www.smsa-sji.sg/wp-content/plugins/sportspress/assets/js/sportspress.js?ver=2.7.15" id="sportspress-js"></script>
<script type="text/javascript" src="https://www.smsa-sji.sg/wp-content/plugins/woocommerce/assets/js/js-cookie/js.cookie.min.js?ver=2.1.4" id="js-cookie-js"></script>
<script type="text/javascript" id="woocommerce-js-extra">
/* <![CDATA[ */
var woocommerce_params = {"ajax_url":"\/wp-admin\/admin-ajax.php","wc_ajax_url":"\/?wc-ajax=%%endpoint%%"};
/* ]]> */
</script>
<script type="text/javascript" src="https://www.smsa-sji.sg/wp-content/plugins/woocommerce/assets/js/frontend/woocommerce.min.js?ver=5.1.0" id="woocommerce-js"></script>
<script type="text/javascript" id="wc-cart-fragments-js-extra">
/* <![CDATA[ */
var wc_cart_fragments_params = {"ajax_url":"\/wp-admin\/admin-ajax.php","wc_ajax_url":"\/?wc-ajax=%%endpoint%%","cart_hash_key":"wc_cart_hash_5631fee71ec8959be269d969aa27ffc8","fragment_name":"wc_fragments_5631fee71ec8959be269d969aa27ffc8","request_timeout":"5000"};
/* ]]> */
</script>
<script type="text/javascript" src="https://www.smsa-sji.sg/wp-content/plugins/woocommerce/assets/js/frontend/cart-fragments.min.js?ver=5.1.0" id="wc-cart-fragments-js"></script>
<script type="text/javascript" id="mediaelement-core-js-before">
/* <![CDATA[ */
var mejsL10n = {"language":"en","strings":{"mejs.download-file":"Download File","mejs.install-flash":"You are using a browser that does not have Flash player enabled or installed. Please turn on your Flash player plugin or download the latest version from https:\/\/get.adobe.com\/flashplayer\/","mejs.fullscreen":"Fullscreen","mejs.play":"Play","mejs.pause":"Pause","mejs.time-slider":"Time Slider","mejs.time-help-text":"Use Left\/Right Arrow keys to advance one second, Up\/Down arrows to advance ten seconds.","mejs.live-broadcast":"Live Broadcast","mejs.volume-help-text":"Use Up\/Down Arrow keys to increase or decrease volume.","mejs.unmute":"Unmute","mejs.mute":"Mute","mejs.volume-slider":"Volume Slider","mejs.video-player":"Video Player","mejs.audio-player":"Audio Player","mejs.captions-subtitles":"Captions\/Subtitles","mejs.captions-chapters":"Chapters","mejs.none":"None","mejs.afrikaans":"Afrikaans","mejs.albanian":"Albanian","mejs.arabic":"Arabic","mejs.belarusian":"Belarusian","mejs.bulgarian":"Bulgarian","mejs.catalan":"Catalan","mejs.chinese":"Chinese","mejs.chinese-simplified":"Chinese (Simplified)","mejs.chinese-traditional":"Chinese (Traditional)","mejs.croatian":"Croatian","mejs.czech":"Czech","mejs.danish":"Danish","mejs.dutch":"Dutch","mejs.english":"English","mejs.estonian":"Estonian","mejs.filipino":"Filipino","mejs.finnish":"Finnish","mejs.french":"French","mejs.galician":"Galician","mejs.german":"German","mejs.greek":"Greek","mejs.haitian-creole":"Haitian Creole","mejs.hebrew":"Hebrew","mejs.hindi":"Hindi","mejs.hungarian":"Hungarian","mejs.icelandic":"Icelandic","mejs.indonesian":"Indonesian","mejs.irish":"Irish","mejs.italian":"Italian","mejs.japanese":"Japanese","mejs.korean":"Korean","mejs.latvian":"Latvian","mejs.lithuanian":"Lithuanian","mejs.macedonian":"Macedonian","mejs.malay":"Malay","mejs.maltese":"Maltese","mejs.norwegian":"Norwegian","mejs.persian":"Persian","mejs.polish":"Polish","mejs.portuguese":"Portuguese","mejs.romanian":"Romanian","mejs.russian":"Russian","mejs.serbian":"Serbian","mejs.slovak":"Slovak","mejs.slovenian":"Slovenian","mejs.spanish":"Spanish","mejs.swahili":"Swahili","mejs.swedish":"Swedish","mejs.tagalog":"Tagalog","mejs.thai":"Thai","mejs.turkish":"Turkish","mejs.ukrainian":"Ukrainian","mejs.vietnamese":"Vietnamese","mejs.welsh":"Welsh","mejs.yiddish":"Yiddish"}};
/* ]]> */
</script>
<script type="text/javascript" src="https://www.smsa-sji.sg/wp-includes/js/mediaelement/mediaelement-and-player.min.js?ver=4.2.17" id="mediaelement-core-js"></script>
<script type="text/javascript" src="https://www.smsa-sji.sg/wp-includes/js/mediaelement/mediaelement-migrate.min.js?ver=6.5.3" id="mediaelement-migrate-js"></script>
<script type="text/javascript" id="mediaelement-js-extra">
/* <![CDATA[ */
var _wpmejsSettings = {"pluginPath":"\/wp-includes\/js\/mediaelement\/","classPrefix":"mejs-","stretching":"responsive","audioShortcodeLibrary":"mediaelement","videoShortcodeLibrary":"mediaelement"};
/* ]]> */
</script>
<script type="text/javascript" src="https://www.smsa-sji.sg/wp-includes/js/mediaelement/wp-mediaelement.min.js?ver=6.5.3" id="wp-mediaelement-js"></script>
<script type="text/javascript" src="https://www.smsa-sji.sg/wp-includes/js/jquery/ui/slider.min.js?ver=1.13.2" id="jquery-ui-slider-js"></script>
<script type="text/javascript" src="https://www.smsa-sji.sg/wp-content/themes/startit/assets/js/third-party.min.js?ver=6.5.3" id="qode_startit_third_party-js"></script>
<script type="text/javascript" src="https://www.smsa-sji.sg/wp-content/plugins/js_composer/assets/lib/bower/isotope/dist/isotope.pkgd.min.js?ver=5.1.1" id="isotope-js"></script>
<script type="text/javascript" src="https://www.smsa-sji.sg/wp-content/themes/startit/assets/js/smoothPageScroll.js?ver=6.5.3" id="qode_startit_smooth_page_scroll-js"></script>
<script type="text/javascript" src="//maps.googleapis.com/maps/api/js?ver=6.5.3&amp;key=AIzaSyDLGXtAbg4uLCS5-wdpuu6au49UjFq86ww" id="google_map_api-js"></script>
<script type="text/javascript" id="qode_startit_modules-js-extra">
/* <![CDATA[ */
var qodefGlobalVars = {"vars":{"qodefAddForAdminBar":0,"qodefElementAppearAmount":-150,"qodefFinishedMessage":"No more posts","qodefMessage":"Loading new posts...","qodefTopBarHeight":0,"qodefStickyHeaderHeight":0,"qodefStickyHeaderTransparencyHeight":50,"qodefLogoAreaHeight":0,"qodefMenuAreaHeight":100,"qodefStickyHeight":50,"qodefMobileHeaderHeight":110}};
var qodefPerPageVars = {"vars":{"qodefStickyScrollAmount":500,"qodefHeaderTransparencyHeight":0}};
/* ]]> */
</script>
<script type="text/javascript" src="https://www.smsa-sji.sg/wp-content/themes/startit/assets/js/modules.min.js?ver=6.5.3" id="qode_startit_modules-js"></script>
<script type="text/javascript" src="https://www.smsa-sji.sg/wp-includes/js/comment-reply.min.js?ver=6.5.3" id="comment-reply-js" async="async" data-wp-strategy="async"></script>
<script type="text/javascript" src="https://www.smsa-sji.sg/wp-content/plugins/js_composer/assets/js/dist/js_composer_front.min.js?ver=5.1.1" id="wpb_composer_front_js-js"></script>
<script type="text/javascript" src="https://www.smsa-sji.sg/wp-content/themes/startit/assets/js/like.min.js?ver=1.0" id="qode_startit_like-js"></script>
<script type="text/javascript" src="//www.smsa-sji.sg/wp-content/plugins/eventON/assets/js/eventon_functions.js?ver=2.6.6" id="evcal_functions-js"></script>
<script type="text/javascript" src="https://www.smsa-sji.sg/wp-content/plugins/eventON/assets/js/jquery.mobile.min.js?ver=2.6.6" id="evo_mobile-js"></script>
<script type="text/javascript" src="//www.smsa-sji.sg/wp-content/plugins/eventON/assets/js/jquery.mousewheel.min.js?ver=2.6.6" id="evo_mouse-js"></script>
<script type="text/javascript" id="evcal_ajax_handle-js-extra">
/* <![CDATA[ */
var the_ajax_script = {"ajaxurl":"https:\/\/www.smsa-sji.sg\/wp-admin\/admin-ajax.php","postnonce":"bf5b6a2b31"};
/* ]]> */
</script>
<script type="text/javascript" src="//www.smsa-sji.sg/wp-content/plugins/eventON/assets/js/eventon_script.js?ver=2.6.6" id="evcal_ajax_handle-js"></script>
<script type="text/javascript" src="https://www.smsa-sji.sg/wp-content/plugins/js_composer/assets/lib/waypoints/waypoints.min.js?ver=5.1.1" id="waypoints-js"></script>
<script type="text/javascript" src="https://maps.googleapis.com/maps/api/js?ver=1.0&amp;key=AIzaSyDLGXtAbg4uLCS5-wdpuu6au49UjFq86ww" id="evcal_gmaps-js"></script>
<script type="text/javascript" src="//www.smsa-sji.sg/wp-content/plugins/eventON/assets/js/maps/eventon_gen_maps.js?ver=2.6.6" id="eventon_gmaps-js"></script>
<script type="text/javascript" src="//www.smsa-sji.sg/wp-content/plugins/eventON/assets/js/maps/eventon_init_gmap.js?ver=1.0" id="eventon_init_gmaps-js"></script>
<script type="text/javascript" id="formidable-js-extra">
/* <![CDATA[ */
var frm_js = {"ajax_url":"https:\/\/www.smsa-sji.sg\/wp-admin\/admin-ajax.php","images_url":"https:\/\/www.smsa-sji.sg\/wp-content\/plugins\/formidable\/images","loading":"Loading\u2026","remove":"Remove","offset":"4","nonce":"8156ee8bd6","id":"ID","no_results":"No results match","file_spam":"That file looks like Spam.","calc_error":"There is an error in the calculation in the field with key","empty_fields":"Please complete the preceding required fields before uploading a file."};
/* ]]> */
</script>
<script type="text/javascript" src="https://www.smsa-sji.sg/wp-content/plugins/formidable-pro/js/frm.min.js?ver=5.0" id="formidable-js"></script>
<script type="text/javascript" defer="defer" async="async" src="https://www.google.com/recaptcha/api.js?ver=3" id="recaptcha-api-js"></script>
<script>
/*<![CDATA[*/
/*]]>*/
</script>
</body>
</html>
<!-- Dynamic page generated in 0.543 seconds. -->
<!-- Cached page generated by WP-Super-Cache on 2024-06-03 18:20:54 -->

<!-- super cache -->
