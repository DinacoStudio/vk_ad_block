// ==UserScript==
// @name         Блокировщик рекламы вк
// @namespace    none
// @version      2.0.3
// @description  Заблокировать рекламу в вк
// @author       Dinaco Studio
// @match        https://*.vk.com/*
// @include      https://*.vk.com/*
// @icon         https://www.google.com/s2/favicons?domain=vk.com
// @grant        GM_webRequest
// @webRequest   [{"selector":"*://stats.vk-portal.net/web-stats/*","action":"cancel"}]
// @webRequest   [{"selector":"*://ad.mail.ru/static/admanhtml/rbadman-html5.min.js","action":"cancel"}]
// @webRequest   [{"selector":"*://www.tns-counter.ru/*","action":"cancel"}]
// @webRequest   [{"selector":"*://r3.mail.ru/k?*","action":"cancel"}]
// @webRequest   [{"selector":"https://vk.com/js/lib/px.js","action":"cancel"}]
// @webRequest   [{"selector":"https://top-fwz1.mail.ru/js/code.js","action":"cancel"}]
// @webRequest   [{"selector":"*://trk.mail.ru/i/*","action":"cancel"}]
// @webRequest   [{"selector":"*://ad.mail.ru/*","action":"cancel"}]
// @webRequest   [{"selector":"https://vk.com/ads_rotate.php?act=al_update_ad","action":"cancel"}]
// @license GNU GPLv3
// ==/UserScript==

window.onload = function() {
    setInterval(block,1000)
};

function block(){
var ad_blocks,a
    ad_blocks = document.querySelectorAll('div#ads_left,[data-ad-view],div#games_catalog_header_content');
    for (a = 0; a < ad_blocks.length; a++) {
    ad_blocks[a].outerHTML= '';
    }
}
