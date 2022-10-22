
<header>
{% if site.theme_config.show_navbar == true %}
  {% include horizontal_list.html collection=site.data.home.navbar_entries %}
  <div class="dashed"></div>
{% endif %}
</header>


Vítejte! (: Pracuji na překladu knih pro <a href="https://braiins.com/category/publishing">Braiins Publishing</a> 
a píšu na <a href="https://bitperia.cz/">Bitperia.cz</a>. 👀 Na této stránce nabízím přehled většiny mých prací - 
primárně kvalitních, podnětných a povětšinou dlouhých textů o Bitcoinu přeložených kompletně do češtiny. 
Postupně však budou přibývat i mé vlastní výtvory...

### Value For Value 🧡

je koncept podpory tvůrce od publika na základě čistě dobrovolných příspěvků v rámci poděkování za poskytnutí 
hodnoty. Překlad dlouhých, technicky specifických textů je časově náročný a psaní vlastních článků zase vyžaduje 
vedle samotného tvůrčího procesu spoustu studia a rešerší.<br>
Pokud vám moje tvorba přináší hodnotu, oceňte to, prosím, dle svého uvážení a možností. Jakákoli podpora je 
povznášejícím impulsem k další činnosti. Svou náklonnost můžete projevit zasláním ₿ satů na

> <img src="tweetoshiMini.png" alt="Tweetoshi" align="left" style="float:left">
  <big><a href="https://twitter.com/TweetoshiApp"> Tweetoshi</a> - twitter 
  handle <a href="https://twitter.com/nekonecnik">@nekonecnik</a> (DMs open)<br>
> ⚡ lightning adresu <a href="lightning:nekonecnik@fountain.fm">nekonecnik@fountain.fm</a><br>
> 🔗 on-chain na Samourai PayNym 🤖 <a href="https://paynym.is/+muddydarkness33F">+muddydarkness33F</a><br>
</big>

Tento projekt běží v bitcoinovém duchu kompletně open source. Máte-li jakékoliv dotazy, připomínky nebo chyby k odstranění, neváhejte 
otevřít <a href="https://github.com/sifrant/jednadvacet">issue nebo pull request na githubu</a>.



{% if site.theme_config.show_footer == true %}
  <footer>
    <div class="dashed"></div>
    {% include horizontal_list.html collection=site.data.home.footer_entries %}
  </footer>
{% endif %}
