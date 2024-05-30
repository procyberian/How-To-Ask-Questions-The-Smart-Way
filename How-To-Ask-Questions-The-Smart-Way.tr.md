## Nasıl Akıllıca Soru Sorulur ?

### Eric Steven Raymond

[Thyrsus Enterprises](http://www.catb.org/~esr/)


```<esr@thyrsus.com>```


### Rick Moen


```<respond-auto@linuxmafia.com>```


Copyright © 2001,2006,2014 Eric S. Raymond, Rick Moen

| **Revision History**                                         |             |      |
| ------------------------------------------------------------ | ----------- | ---- |
| Revision 3.10                                                | 21 May 2014 | esr  |
| New section on Stack Overflow.                               |             |      |
| Revision 3.9                                                 | 23 Apr 2013 | esr  |
| URL fixes.                                                   |             |      |
| Revision 3.8                                                 | 19 Jun 2012 | esr  |
| URL fix.                                                     |             |      |
| Revision 3.7                                                 | 06 Dec 2010 | esr  |
| Helpful hints for ESL speakers.                              |             |      |
| Revision 3.7                                                 | 02 Nov 2010 | esr  |
| Several translations have disappeared.                       |             |      |
| Revision 3.6                                                 | 19 Mar 2008 | esr  |
| Minor update and new links.                                  |             |      |
| Revision 3.5                                                 | 2 Jan 2008  | esr  |
| Typo fix and some translation links.                         |             |      |
| Revision 3.4                                                 | 24 Mar 2007 | esr  |
| New section, "When asking about code".                       |             |      |
| Revision 3.3                                                 | 29 Sep 2006 | esr  |
| Folded in a good suggestion from Kai Niggemann.              |             |      |
| Revision 3.2                                                 | 10 Jan 2006 | esr  |
| Folded in edits from Rick Moen.                              |             |      |
| Revision 3.1                                                 | 28 Oct 2004 | esr  |
| Document 'Google is your friend!'                            |             |      |
| Revision 3.0                                                 | 2 Feb 2004  | esr  |
| Major addition of stuff about proper etiquette on Web forums. |             |      |

------
## İçindekiler

- [Çeviriler](#translations)
- [Sorumluluk reddi beyanı](#disclaimer)
- [Giriş](#introduction)
- [Sorunuzu Sormadan Önce](#before-you-ask)
- [Sorduğunuzda](#when-you-ask)
  * [Forumunuzu dikkatli seçin](#choose-your-forum-carefully)
  * [Stack Overflow](#stack-overflow)
  * [Web ve IRC forumları](#web-and-irc-forums)
  * [İkinci adım olarak proje posta listelerini kullanın](#as-a-second-step--use-project-mailing-lists)
  * [Anlamlı, spesifik konu başlıkları kullanın](#use-meaningful--specific-subject-headers)
  * [Yanıtlamayı kolaylaştırın](#make-it-easy-to-reply)
  * [Açık, gramer kurallarına uygun ve doğru yazılmış bir dille yazın](#write-in-clear--grammatical--correctly-spelled-language)
  * [Soruları erişilebilir, standart formatlarda gönderin](#send-questions-in-accessible--standard-formats)
  * [Sorununuz hakkında kesin ve bilgilendirici olun](#be-precise-and-informative-about-your-problem)
  * [Hacim kesin değil](#volume-is-not-precision)
  * [Bir hata bulduğunuzu iddia etmek için acele etmeyin](#don-t-rush-to-claim-that-you-have-found-a-bug)
  * [Yere kapanmak ödevinizi yapmanın yerini tutmaz](#grovelling-is-not-a-substitute-for-doing-your-homework)
  * [Tahminlerinizi değil, sorunun belirtilerini açıklayın](#describe-the-problem-s-symptoms--not-your-guesses)
  * [Sorununuzun belirtilerini kronolojik sırayla tanımlayın](#describe-your-problem-s-symptoms-in-chronological-order)
  * [Adımı değil hedefi açıklayın](#describe-the-goal--not-the-step)
  * [İnsanlardan özel e-postayla yanıt vermelerini istemeyin](#don-t-ask-people-to-reply-by-private-e-mail)
  * [Sorunuz hakkında açık olun](#be-explicit-about-your-question)
  * [Kod sorulduğunda](#when-asking-about-code)
  * [Ev ödevi soruları göndermeyin](#don-t-post-homework-questions)
  * [Anlamsız sorguları budama](#prune-pointless-queries)
  * [Sorunuz size ait olsa bile "Acil" olarak işaretlemeyin](#don-t-flag-your-question-as--urgent---even-if-it-is-for-you)
  * [Nezaket asla zarar vermez ve bazen yardımcı olur](#courtesy-never-hurts--and-sometimes-helps)
  * [Çözüme ilişkin kısa bir notla devam edin](#follow-up-with-a-brief-note-on-the-solution)
- [Yanıtlar Nasıl Yorumlanır?](#how-to-interpret-answers)
  * [RTFM ve STFW: Ciddi Bir Şekilde İşi Berbat Ettiğinizi Nasıl Anlarsınız?](#rtfm-and-stfw--how-to-tell-you-ve-seriously-screwed-up)
  * [Eğer anlamıyorsan...](#if-you-don-t-understand)
  * [Kabalıkla baş etmek](#dealing-with-rudeness)
- [Kaybeden Gibi Tepki Vermemek Üzerine](#on-not-reacting-like-a-loser)
- [Sorulmaması Gereken Sorular](#questions-not-to-ask)
- [İyi ve Kötü Sorular](#good-and-bad-questions)
- [Cevap Alamıyorsanız](#if-you-can-t-get-an-answer)
- [Sorulara Yararlı Bir Şekilde Nasıl Cevap Verilir?](#how-to-answer-questions-in-a-helpful-way)
- [Konuyla ilgili diğer kaynaklar](#related-resources)
- [Teşekkür](#acknowledgements)

## Çeviriler

Translations: [Bahasa Indonesian](http://bulsara.host.sk/index.php?p=2005) [Belorussian](https://www.dussk.co/translation/ask-smart-questions/) [Brazilo-Portuguese](http://blogofscience.com/perguntas.html) [Chinese (Traditional)](https://github.com/ryanhanwu/How-To-Ask-Questions-The-Smart-Way) [Croatian](http://www.bildelestore.dk/blog/kako-postavljati-pitanja-na-pametan-nacin) [Czech](http://scientificachievements.com/jak-se-ptat-chytry-zpusob/) [Dutch](http://docs.jaspervries.nl/smart-questions/) [Estonian](http://glory4cars.com/edu/kuidas-esitada-kusimusi-nutikas-viis/) [French](http://www.gnurou.org/documents/smart-questions-fr.html) [Georgian](http://maxo127.narod.ru/Geo/Articles/smart-questions_ge.html) [German](http://www.tty1.net/smart-questions_de.html) [Greek](http://www.dionyziz.com/howto-smart-questions-gr/) [Hindi](http://kntuniversity.org/how-to-ask-questions-the-smart-way/) [Hungarian](http://www.forallworld.com/milyen-kerdeseket-okosan/) [Irish Gaelic](http://www.autoteileprofi.ch/blog/2016/04/01/newly-sin-iarr-ar-kuestions-tkhe-smart-wai) [Indonesion](https://www.chameleonjohn.com/translations/smart-questions-Indonesian)[Japanese](http://www.ranvis.com/articles/smart-questions.ja.html) [Lithuanian](http://myscres.com/articles/kaip-uzduoti-klausimus-protinga-buda.html) [Polish](http://rtfm.killfile.pl/) [Portuguese](http://science-lakes.com/article43.html) [Romanian](http://wiki.lug.ro/mediawiki/index.php/Cum_se_pun_%C3%AEntreb%C4%83ri_%C3%AEn_mod_inteligent) [Russian](http://maddog.sitengine.ru/smart-question-ru.html) [Serbian](http://www.autoersatzteile.de/blog/how-to-ask-questions-the-smart-way-in-serbian) [Spanish](http://www.sindominio.net/ayuda/preguntas-inteligentes.html) [Uzbek](http://www.bestcarzin.com/blog/smart-questions-uzb/) If you want to copy, mirror, translate, or excerpt this document, please see my [copying policy](http://www.catb.org/~esr/copying.html).

## Sorumluluk reddi beyanı

Pek çok proje web sitesi, nasıl yardım alınabileceğine ilişkin bölümlerinde bu belgeye bağlantı verir. Sorun değil, amaçladığımız kullanım budur - ancak proje sayfanız için böyle bir bağlantı oluşturan bir web yöneticisiyseniz, lütfen bağlantının yanında *projeniz için bir yardım masası olmadığımızı* belirten dikkat çekici bir uyarıyı duyurun!

Böyle bir bildirim olmadan, bu belgeyi yayınlamanın dünyanın tüm teknik sorunlarını çözmeyi bizim işimiz haline getirdiğini düşünen aptallar tarafından defalarca rahatsız edileceğimizi zor yoldan öğrendik.

Bu belgeyi yardıma ihtiyacınız olduğu için okuyorsanız ve bu belgeyi doğrudan bu belgenin yazarlarından alabileceğiniz izlenimiyle oradan uzaklaşıyorsanız, *siz* bahsettiğimiz aptallardan birisiniz. *Bize* soru sormayın. Seni görmezden geleceğiz. Karşılaştığınız yazılım veya donanım hakkında gerçekten bilgi sahibi olan ancak %99,9 oranında biz olmayacağız kişilerden nasıl yardım alabileceğinizi size göstermek için buradayız. Yazarlardan birinin uğraştığınız konu hakkında uzman olduğundan *kesin* olarak bilmiyorsanız, bizi rahat bırakın, herkes daha mutlu olacaktır.

## Giriş

[Üstadların](http://www.catb.org/~esr/faqs/hacker-howto.html) dünyasında, teknik sorularınıza alacağınız yanıtların türü, soruları sorma şeklinize olduğu kadar bağlıdır Cevabı geliştirmenin zorluğu gibi. Bu kılavuz size, tatmin edici bir yanıt alma olasılığınız daha yüksek olacak şekilde nasıl soru soracağınızı öğretecektir.

Artık açık kaynak kullanımı yaygınlaştığından, genellikle bilgisayar üstadlarının olduğu kadar daha deneyimli kullanıcılardan da iyi yanıtlar alabilirsiniz. Bu iyi birşey; kullanıcılar, yeni başlayanların sıklıkla karşılaştığı türden hatalara karşı biraz daha hoşgörülü olma eğilimindedir. Yine de deneyimli kullanıcılara burada önerdiğimiz şekilde bilgisayar üstadları gibi davranmak genellikle onlardan yararlı yanıtlar almanın en etkili yolu olacaktır.

Anlaşılması gereken ilk şey, bilgisayar üstadlarının aslında zor problemlerden ve onlar hakkında iyi, düşündürücü sorulardan hoşlandığıdır. Eğer öyle olmasaydı burada olmazdık. Bize üzerinde duracağımız ilginç bir soru verirseniz size minnettar olacağız; İyi sorular bir teşvik ve bir hediyedir. İyi sorular anlayışımızı geliştirmemize yardımcı olur ve genellikle başka türlü fark etmediğimiz veya düşünmediğimiz sorunları ortaya çıkarır. Bilgisayar üstadları arasında "Güzel soru!" güçlü ve samimi bir iltifattır.

Buna rağmen, bilgisayar üstadları basit soruları düşmanlık veya kibir gibi görünen bir tavırla karşılama konusunda bir üne sahiptir. Bazen yeni başlayanlara ve cahillere refleks olarak kaba davranıyormuşuz gibi görünüyor. Ama bu aslında doğru değil.

Biz, soru sormadan önce düşünmeye veya kendi ödevlerini yapmaya isteksiz görünen insanlara, özür dilemeden düşmanca davranıyoruz. Bunun gibi insanlar zamanlarını tüketirler; geri vermeden alırlar ve bizim daha ilginç başka bir soruya ve cevaba daha layık başka bir kişiye harcayabileceğimiz zamanı boşa harcarlar. Bu tür insanlara "kaybedenler" diyoruz (ve tarihsel nedenlerden dolayı bazen bunu "aldatanlar" diye yazıyoruz).

Yazdığımız yazılımı sadece kullanmak isteyen, teknik detayları öğrenmekle ilgilenmeyen pek çok kişinin olduğunun farkındayız. Çoğu insan için bilgisayar yalnızca bir araçtır, amaca yönelik bir araçtır; onların yapacak daha önemli işleri ve yaşayacak hayatları var. Bunu kabul ediyoruz ve bizi ilgilendiren teknik konularla herkesin ilgilenmesini beklemiyoruz. Bununla birlikte, soruları yanıtlama tarzımız, bu tür bir ilgi *gösteren* ve problem çözmede aktif katılımcı olmaya istekli olan kişilere göre ayarlanmıştır. Bu değişmeyecek. Öyle de olmamalı; eğer öyle olsaydı, en iyi yaptığımız şeylerde daha az etkili olurduk.

Biz (büyük ölçüde) gönüllüyüz. Soruları yanıtlamak için yoğun yaşamlarımızdan zaman ayırıyoruz ve zaman zaman bu sorulardan bunalıyoruz. Bu yüzden acımasızca filtreliyoruz. Özellikle soru cevaplama zamanımızı kazananlar üzerinde daha verimli geçirmek için kaybeden gibi görünen kişilerin sorularını atıyoruz.

Bu tutumu iğrenç, küçümseyici veya kibirli buluyorsanız varsayımlarınızı kontrol edin. Sizden bize diz çökmenizi istemiyoruz - aslında, eğer bunu mümkün kılmak için gerekli çabayı gösterirseniz, çoğumuz sizinle eşit olarak ilgilenmekten ve sizi kültürümüze kabul etmekten daha fazla seveceğimiz bir şey yoktur. Ancak kendilerine yardım etmeye istekli olmayan insanlara yardım etmeye çalışmak bizim için hiç de verimli değil. Cahil olmak sorun değil; aptalı oynamak doğru değil.

Bu nedenle, bizden ilgi görmek için zaten teknik olarak yetkin olmanız gerekmese de, yetkinliğe yol açan türde bir tutum sergilemek *gereklidir* - uyanık, düşünceli, gözlemci, bir strateji geliştirmede aktif bir ortak olmaya istekli. çözüm. Bu tür bir ayrımcılıkla yaşayamıyorsanız, bilgisayar üstadlarından size kişisel olarak yardım bağışlamalarını istemek yerine, birine ticari destek sözleşmesi için ödeme yapmanızı öneririz.

Yardım için bize gelmeye karar verirseniz kaybedenlerden biri olmak istemezsiniz. Sen de öyle görünmek istemezsin. Hızlı ve duyarlı bir yanıt almanın en iyi yolu, bu soruyu akıllı, kendine güvenen ve belirli bir sorunla ilgili yardıma ihtiyaç duyan ipuçlarına sahip biri gibi sormaktır.

(Bu kılavuzda yapılacak iyileştirmeler memnuniyetle karşılanacaktır. Önerilerinizi [esr@thyrsus.com](mailto:esr@thyrsus.com) veya [respond-auto@linuxmafia.com](mailto:respond-auto@linuxmafia.com) adresine e-postayla gönderebilirsiniz. Bununla birlikte, bu belgenin [netik kuralları](http://www.ietf.org/rfc/rfc1855.txt) konusunda genel bir rehber olma niyetinde olmadığını ve özellikle yararlı bilgiler ortaya çıkarmakla ilgili olmayan önerileri teknik bir forumda genellikle reddedeceğimizi unutmayın.)

## Sorunuzu Sormadan Önce

E-posta yoluyla, bir haber grubunda veya bir web sitesinin sohbet panosunda teknik bir soru sormadan önce aşağıdakileri yapın:

1. Mesaj göndermeyi planladığınız forumun veya e-posta listesinin arşivlerini arayarak bir cevap bulmaya çalışın.
2. Web'de arama yaparak bir cevap bulmaya çalışın.
3. Kılavuzu okuyarak bir cevap bulmaya çalışın.
4. SSS'yi okuyarak bir cevap bulmaya çalışın.
5. İnceleme veya deney yaparak bir cevap bulmaya çalışın.
6. Yetenekli bir arkadaşınıza sorarak cevap bulmaya çalışın.
7. Programcıysanız kaynak kodunu okuyarak bir cevap bulmaya çalışın.

Sorunuzu sorarken öncelikle bunları yaptığınızı gösterin; bu, tembel bir sünger gibi davranıp insanların zamanını boşa harcamadığınızı anlamanıza yardımcı olacaktır. Daha da iyisi, bunları yaparak *öğrendiklerinizi* gösterin. Cevaplardan öğrenebileceklerini göstermiş kişilerin sorularını yanıtlamayı seviyoruz.

Aldığınız hata mesajının metninde Google araması yapmak ([Google gruplarını](http://groups.google.com/) ve Web sayfalarını aramak) gibi taktikleri kullanın. Bu sizi doğrudan belgeleri düzeltmeye veya sorunuza yanıt veren bir posta listesi dizisine yönlendirebilir. Öyle olmasa bile, yardım isteyen e-postalarda veya haber gönderilerinde "Aşağıdaki ifadeyi Google'da araştırdım ancak umut verici görünen hiçbir şey bulamadım" demek iyi bir şeydir, çünkü yalnızca aramaların ne kazandırdığını kaydeder.' yardım etme. Ayrıca, arama terimlerini sorununuzun ve çözüm dizinizin ne olacağını umduğunuza bağlayarak, benzer sorunları olan diğer kişileri başlığınıza yönlendirmenize de yardımcı olacaktır.

Acele etmeyin. Birkaç saniyelik Google aramasıyla karmaşık bir sorunu çözmeyi beklemeyin. SSS'leri okuyup anlayın, arkanıza yaslanın, rahatlayın ve uzmanlara başvurmadan önce sorunu biraz düşünün. Bize güvenin, sorularınızdan ne kadar okuduğunuzu ve ne kadar düşündüğünüzü anlayacaklar ve eğer hazırlıklı gelirseniz size yardım etmeye daha istekli olacaklar. İlk aramanızda yanıt bulunamadı (ya da çok fazla) diye tüm soru cephaneliğinizi anında ateşlemeyin.

Sorunuzu hazırlayın. İyice düşünün. Aceleci görünen sorular aceleci yanıtlar alır veya hiç almaz. Yardım aramadan önce sorununuzu çözmek için düşünce ve çaba harcadığınızı ne kadar çok gösterirseniz, gerçekten yardım alma olasılığınız o kadar artar.

Yanlış soruyu sormamaya dikkat edin. Hatalı varsayımlara dayanan bir soru sorarsanız, J. Random Hacker'ın "Aptal soru..." diye düşünürken ve ihtiyacınız olandan ziyade istediğinizi elde etme deneyimini umarak gereksiz derecede gerçekçi bir cevap vermesi muhtemeldir. sana bir ders verecek.

Asla bir cevaba *hakkınız* olduğunu varsaymayın. Sen değilsin; sonuçta hizmet için para ödemiyorsunuz. Eğer hak ederseniz, önemli, ilginç ve düşündürücü bir soru sorarak bir yanıt elde edeceksiniz; başkalarından pasif bir şekilde bilgi talep etmek yerine, topluluğun deneyimine dolaylı olarak katkıda bulunan bir soru.

Öte yandan, çözümün geliştirilmesi sürecinde yardımcı olabileceğinizi ve yardım etmeye istekli olduğunuzu açıkça belirtmek çok iyi bir başlangıçtır. "Biri bir ipucu verebilir mi?", "Örneğimde eksik olan nedir?" ve "Hangi siteyi kontrol etmeliyim?" "Lütfen kullanmam gereken prosedürü tam olarak gönderin" yerine yanıt alma olasılığı daha yüksektir. çünkü birisi sizi doğru yöne yönlendirebilirse, süreci tamamlamaya gerçekten istekli olduğunuzu açıkça belirtiyorsunuz.

## Sorduğunuzda

### Forumunuzu dikkatli seçin

Sorunuzu nerede soracağınızı seçerken hassas olun. Aşağıdaki durumlarda muhtemelen göz ardı edilecek veya kaybeden olarak yazılacaksınız:

- sorunuzu konu dışı olan bir foruma gönderin
- ileri düzey teknik soruların beklendiği bir foruma çok basit bir soru gönderin veya tam tersi
- çok fazla farklı haber grubuna çapraz paylaşım
- ne tanıdığınız ne de probleminizin çözümünden kişisel olarak sorumlu olmayan birine kişisel bir e-posta göndermek

Bilgisayar üstadları, iletişim kanallarını ilgisizlik içinde boğulmaktan korumak için, uygunsuz bir şekilde hedeflenen soruları savururlar. Bunun senin başına gelmesini istemezsin.

Bu nedenle ilk adım doğru forumu bulmaktır. Tekrar ediyorum, Google ve diğer Web arama yöntemleri arkadaşınızdır. Size zorluk çıkaran donanım veya yazılımla en yakından ilişkili proje web sayfasını bulmak için bunları kullanın. Genellikle SSS (Sıkça Sorulan Sorular) listesine ve proje posta listelerine ve bunların arşivlerine bağlantılar bulunur. Bu e-posta listeleri, kendi çabalarınız (bulduğunuz SSS'leri *okumak* da dahil) size bir çözüm bulamazsa, yardım için gidilecek son yerlerdir. Proje sayfası ayrıca bir hata raporlama prosedürünü açıklayabilir veya bir hata raporlama prosedürüne bağlantı içerebilir; eğer öyleyse, takip edin.

Aşina olmadığınız bir kişiye veya foruma e-posta göndermek en iyi ihtimalle risklidir. Örneğin, bilgilendirici bir web sayfasının yazarının ücretsiz danışmanınız olmak istediğini varsaymayın. Sorunuzun hoş karşılanıp karşılanmayacağı konusunda iyimser tahminlerde bulunmayın; emin değilseniz, soruyu başka bir yere gönderin veya göndermekten kaçının.

Bir Web forumu, haber grubu veya e-posta listesi seçerken ismin kendisine çok fazla güvenmeyin; Sorunuzun konuyla ilgili olduğunu doğrulamak için bir SSS veya sözleşme arayın. Göndermeden önce arka trafiğin bir kısmını okuyun, böylece orada işlerin nasıl yapıldığına dair bir fikir edinirsiniz. Aslında, posta göndermeden önce haber grubu veya posta listesi arşivlerinde sorununuzla ilgili kelimeler için anahtar kelime araması yapmak çok iyi bir fikirdir. Size bir cevap bulabilir ve bulamazsanız daha iyi bir soru oluşturmanıza yardımcı olabilir.

Mevcut tüm yardım kanallarını aynı anda bombalamayın, bu bağırmak gibidir ve insanları rahatsız eder. Aralarından yavaşça geçin.

Konunuzun ne olduğunu bilin! Klasik hatalardan biri, bir dile veya kitaplığa veya her ikisinde de taşınabilir bir araca ayrılmış bir forumda Unix veya Windows programlama arayüzü hakkında sorular sormaktır. Bunun neden bir hata olduğunu anlamıyorsanız, anlayana kadar hiçbir soru sormamanız daha iyi olur.

Genel olarak, iyi seçilmiş halka açık bir foruma yöneltilen soruların, özel bir foruma yöneltilen eşdeğer sorulara göre yararlı yanıtlar alma olasılığı daha yüksektir. Bunun birden fazla nedeni var. Bunlardan biri, potansiyel yanıt veren havuzunun büyüklüğüdür. Bir diğeri ise izleyicinin büyüklüğüdür; Bilgisayar üstadları, yalnızca birkaç kişiye hizmet eden soruları yanıtlamak yerine, birçok insanı eğiten soruları yanıtlamayı tercih ediyor.

Anlaşılır bir şekilde, yetenekli bilgisayar üstadları ve popüler yazılım yazarları, zaten yanlış hedeflenmiş mesajlardan paylarına düşenden fazlasını alıyorlar. Seli daha da büyüterek, aşırı durumlarda bardağı taşıran son damla bile olabilirsiniz - pek çok kez, popüler projelere katkıda bulunanlar, kişisel hesaplarına yararsız e-posta trafiği şeklinde ikincil zararlar verdiği için desteklerini geri çekmişlerdir. dayanılmaz hale geldi.

### Stack Overflow

Arayın, *sonra* Stack Exchange'de sorun

Son yıllarda Stack Exchange site topluluğu, teknik ve diğer soruların yanıtlanması için önemli bir kaynak olarak ortaya çıktı ve hatta birçok açık kaynaklı proje için tercih edilen forum haline geldi.

Stack Exchange'e bakmadan önce bir Google aramasıyla başlayın; Google bunu gerçek zamanlı olarak dizine ekler. Birisinin zaten benzer bir soru sormuş olma ihtimali çok yüksektir ve Stack Exchange siteleri genellikle arama sonuçlarının en üst sıralarında yer alır. Google'da herhangi bir şey bulamadıysanız sorunuzla en alakalı sitede tekrar arama yapın (aşağıya bakın). Etiketlerle arama yapmak sonuçları daraltmanıza yardımcı olabilir.

Hâlâ bir şey bulamadıysanız sorunuzu, konuyla en alakalı olan *one* siteye gönderin. Özellikle kod için biçimlendirme araçlarını kullanın ve sorunuzun özüyle ilgili etiketleri ekleyin (özellikle sorun yaşadığınız programlama dilinin, işletim sisteminin veya kitaplığın adı). Bir yorumcu sizden daha fazla bilgi isterse ana gönderinizi düzenleyerek bu bilgiyi ekleyin. Herhangi bir yanıt faydalıysa olumlu oy vermek için yukarı oka tıklayın; Bir cevap sorununuza çözüm sağlıyorsa, cevabı doğru olarak kabul etmek için oylama oklarının altındaki onay işaretine tıklayın.

Stack Exchange [100'den fazla siteye](http://stackexchange.com/sites) ulaştı ancak en olası adaylar şunlardır:

- Süper Kullanıcı genel amaçlı bilgi işlemle ilgili sorular içindir. Sorunuz yalnızca ağ bağlantısı üzerinden konuştuğunuz kod veya programlarla ilgili değilse muhtemelen buraya gelecek.
- Yığın Taşması programlama ile ilgili sorular içindir.
- Sunucu Arızası, sunucu ve ağ yönetimi ile ilgili sorular içindir.

Android, Ubuntu, TeX/LaTeX ve SharePoint dahil olmak üzere birçok projenin kendine özel siteleri vardır. Güncel bir liste için Stack Exchange sitesini kontrol edin.

### Web ve IRC forumları

Yerel kullanıcı grubunuz veya Linux dağıtımınız, yeni başlayanların yardım alabileceği bir Web forumunun veya IRC kanalının reklamını yapabilir. (İngilizce konuşulmayan ülkelerde yeni başlayanlara yönelik forumların hâlâ e-posta listeleri olma olasılığı daha yüksektir.) Bunlar, özellikle nispeten basit veya yaygın bir soruna takılıp kaldığınızı düşünüyorsanız, sorabileceğiniz ilk yerlerdir. Reklamı yapılan bir IRC kanalı, orada soru sormaya ve çoğu zaman gerçek zamanlı olarak yanıt almaya yönelik açık bir davettir.

Aslında, size sorun çıkaran programı bir Linux dağıtımından aldıysanız (günümüzde yaygın olduğu gibi), programın proje forumunu/listesini denemeden önce dağıtımın forumunu/listesini sormak daha iyi olabilir. Projenin bilgisayar üstadları “*bizim* yapımızı kullan” diyebilir.

Herhangi bir Web forumuna mesaj göndermeden önce, Arama özelliğinin olup olmadığını kontrol edin. Eğer öyleyse, sorununuz gibi bir şey için birkaç anahtar kelime araması yapmayı deneyin; sadece yardımcı olabilir. Daha önce genel bir Web araması yaptıysanız (yapmanız gerektiği gibi), yine de forumda arama yapın; Web çapındaki arama motorunuz yakın zamanda bu forumun tamamını dizine eklememiş olabilir.

E-postanın daha çok geliştirme trafiğine ayrılmasıyla, projelerde kullanıcı desteğinin bir Web forumu veya IRC kanalı üzerinden sağlanması yönünde artan bir eğilim vardır. Bu nedenle, projeye özel yardım ararken öncelikle bu kanalları arayın.

IRC'de muhtemelen ilk iş olarak kanala uzun bir sorun açıklaması dökmemek en iyisidir; bazı insanlar bunu kanal taşması olarak yorumluyor. Kanalda bir konuşma başlatmak için tek satırlık bir sorun açıklaması yapmak en iyisidir.

### İkinci adım olarak proje posta listelerini kullanın

Bir projenin geliştirme e-posta listesi varsa, sorunuzu kimin en iyi şekilde yanıtlayabileceğini bildiğinize inansanız bile, bireysel geliştiricilere değil e-posta listesine yazın. Proje posta listesinin adresi için projenin belgelerini ve ana sayfasını kontrol edin ve kullanın. Bu politikanın birkaç iyi nedeni var:

- Bir geliştiriciye sorulabilecek kadar iyi olan herhangi bir soru aynı zamanda tüm grup için de değerli olacaktır. Aksine, sorunuzun bir posta listesi için fazla aptalca olduğundan şüpheleniyorsanız, bu bireysel geliştiricileri taciz etmek için bir mazeret değildir.
- Listedeki soruların sorulması geliştiriciler arasındaki yükü dağıtır. Bireysel geliştirici (özellikle proje lideriyse) sorularınızı yanıtlayamayacak kadar meşgul olabilir.
- Çoğu posta listesi arşivlenir ve arşivler arama motorları tarafından indekslenir. Sorunuzu listede sorarsanız ve yanıtlanırsa, gelecekteki bir soru, sorunuzu ve yanıtını tekrar sormak yerine Web'de bulabilir.
- Belirli soruların sıklıkla sorulduğu görülüyorsa, geliştiriciler bu bilgileri belgeleri geliştirmek veya yazılımın kendisini daha az kafa karıştırıcı hale getirmek için kullanabilirler. Ancak bu sorular özel olarak sorulursa, hiç kimse en sık hangi soruların sorulduğuna dair tam bir resme sahip olamaz.

Bir projede hem "kullanıcı" hem de "geliştirici" (veya "üstad") e-posta listesi veya Web forumu varsa ve kodu hacklemiyorsanız, "kullanıcı" listesine/forumuna sorun. Sorunuzu geliştirici trafiğini bozan bir gürültü olarak algılayacakları geliştirici listesinde hoş karşılanacağınızı varsaymayın.

Ancak, sorunuzun önemsiz olmadığından *eminseniz* ve "kullanıcı" listesinde/forumda birkaç gün boyunca yanıt alamazsanız, "geliştirici" sorusunu deneyin. Birkaç gün orada gizlenmeniz veya en azından arşivlenmiş mesajların son birkaç gününü incelemeniz, göndermeden önce yerel gelenekleri öğrenmeniz tavsiye edilir (aslında bu herhangi bir özel veya yarı özel liste için iyi bir tavsiyedir).

Bir projenin e-posta listesi adresini bulamıyor ancak yalnızca projenin sorumlusunun adresini görüyorsanız, devam edin ve sorumluya yazın. Ancak bu durumda bile e-posta listesinin mevcut olmadığını varsaymayın. E-postanızda uygun e-posta listesini denediğinizi ve bulamadığınızı belirtin. Ayrıca mesajınızın başkalarına iletilmesine itirazınız olmadığını da belirtin. (Birçok kişi, içinde gizli hiçbir şey olmasa bile, özel e-postanın özel kalması gerektiğine inanır. Mesajınızın iletilmesine izin vererek, muhabirinize e-postanızı nasıl yöneteceği konusunda bir seçenek vermiş olursunuz.)

### Anlamlı, spesifik konu başlıkları kullanın

Posta listelerinde, haber gruplarında veya Web forumlarında konu başlığı, yaklaşık 50 veya daha az karakterle nitelikli uzmanların dikkatini çekmek için altın bir fırsattır. "Lütfen bana yardım edin" gibi gevezeliklerle boşa harcamayın ("LÜTFEN YARDIM EDİN!!!!" şöyle dursun; bu tür konuları içeren mesajlar refleks olarak göz ardı edilir). Acınızın derinliğiyle bizi etkilemeye çalışmayın; bunun yerine sorunun çok kısa bir açıklaması için alanı kullanın.

Pek çok teknik destek kuruluşu tarafından konu başlıkları için kullanılan iyi bir kural "nesne - sapma"dır. “Nesne” kısmı hangi şeyin veya bir grup şeyin sorun yaşadığını belirtirken, “sapma” kısmı beklenen davranıştan sapmayı tanımlıyor.
- **Aptal:**

 YARDIM! Video dizüstü bilgisayarımda düzgün çalışmıyor!

- **Akıllı:**

 X.org 6.8.1 şekilsiz fare imleci, Fooware MV1005 vid. yonga seti

- **Daha akıllı:**

 Fooware MV1005 vid'de X.org 6.8.1 fare imleci. yonga seti - şekilsiz
 
Bir "nesne sapması" açıklaması yazma süreci, sorun hakkındaki düşüncelerinizi daha ayrıntılı bir şekilde düzenlemenize yardımcı olacaktır. Ne etkilenir? Yalnızca fare imlecini mi yoksa başka grafikleri de mi kullanıyorsunuz? Bu, X'in X.org sürümüne özel mi? 6.8.1 sürümüne mi? Bu Fooware video yonga setlerine özel mi? MV1005'i modellemek için mi? Sonucu gören bir hacker, neyle ilgili sorun yaşadığınızı *ve* yaşadığınız sorunu bir bakışta anında anlayabilir.

Daha genel olarak, yalnızca konu satırlarının gösterildiği bir soru arşivinin dizinine baktığınızı hayal edin. Konu satırınızın sorunuzu yeterince iyi yansıtmasını sağlayın; böylece arşivde sizinkine benzer bir soruyla arama yapan bir sonraki kişi, soruyu tekrar göndermek yerine başlığı takip ederek bir cevaba ulaşabilecektir.

Yanıt olarak bir soru sorarsanız konu satırını soru sorduğunuzu belirtecek şekilde değiştirmeyi unutmayın. "Yanıt: test" veya "Yanıt: yeni hata" gibi görünen bir Konu satırının yararlı miktarda dikkat çekme olasılığı daha düşüktür. Ayrıca, yeni okuyuculara ipucu sağlamak amacıyla önceki mesajlardan minimum düzeyde alıntı yapın.

Tamamen yeni bir konu başlatmak için liste mesajını yanıtla tuşuna basmayın. Bu kitlenizi sınırlayacaktır. Mutt gibi bazı posta okuyucuları, kullanıcının ileti dizisine göre sıralamasına ve ardından ileti dizisini katlayarak ileti dizisindeki mesajları gizlemesine olanak tanır. Bunu yapan kişiler mesajınızı asla göremez.

Konuyu değiştirmek yeterli değil. Mutt ve muhtemelen diğer posta okuyucuları, konu satırına değil, bir konuya atamak için e-postanın başlıklarındaki diğer bilgilere bakar. Bunun yerine tamamen yeni bir e-posta başlatın.

Web forumlarında iyi uygulama kuralları biraz farklıdır çünkü mesajlar genellikle belirli tartışma başlıklarına çok daha sıkı bir şekilde bağlıdır ve çoğu zaman bu konuların dışında görünmez. Cevap olarak bir soru sorarken konuyu değiştirmek şart değildir. Tüm forumlarda yanıtlarda ayrı konu satırlarına bile izin verilmez ve izin verildiğinde neredeyse hiç kimse bunları okumaz. Ancak cevap olarak soru sormak başlı başına şüpheli bir uygulamadır çünkü bunu yalnızca bu konuyu izleyenler görecektir. Bu nedenle, yalnızca başlıkta aktif olan kişilere sormak *istediğinizden* emin değilseniz, yeni bir başlık başlatın.

### Yanıtlamayı kolaylaştırın

Sorgunuzu "Lütfen yanıtınızı şu adrese gönderin..." şeklinde bitirmek, yanıt alma olasılığınızı oldukça azaltır. Posta aracınızda doğru bir Yanıtla başlığı oluşturmak için gereken birkaç saniyeyi bile ayırma zahmetine giremiyorsanız, sorununuz hakkında düşünmek için birkaç saniye bile ayırma zahmetine giremeyiz. Posta programınız buna izin vermiyorsa [daha iyi bir posta programı edinin](http://linuxmafia.com/faq/Mail/muas.html). İşletim sisteminiz buna izin veren herhangi bir e-posta programını desteklemiyorsa daha iyi bir işletim sistemi edinin.

Web forumlarında, bilginin hassas olabileceğine inanmıyorsanız (ve birileri bilinmeyen bir nedenden dolayı bunu tüm forumun bilmesine değil size bildirecekse) e-postayla yanıt istemek tamamen kabalıktır. Birisi konuya yanıt verdiğinde bir e-posta kopyası istiyorsanız, Web forumunun bunu göndermesini isteyin; bu özellik hemen hemen her yerde "bu konuyu izle", "cevaplarda e-posta gönder" vb. seçenekler altında desteklenir.

### Açık, gramer kurallarına uygun ve doğru yazılmış bir dille yazın

Deneyimlerimiz sonucunda dikkatsiz ve özensiz yazarların aynı zamanda düşünme ve kodlama konusunda da dikkatsiz ve özensiz olduklarını (zaten çoğu zaman üzerine bahse girecek kadar) bulduk. Dikkatsiz ve özensiz düşünenlerin sorularını yanıtlamak ödüllendirici değildir; Zamanımızı başka bir yerde geçirmeyi tercih ederiz.

Bu nedenle sorunuzu açık ve güzel bir şekilde ifade etmeniz önemlidir. Eğer siz bunu yapmaktan rahatsız olamazsanız, biz de dikkat etmekten rahatsız olamayız. Dilinizi geliştirmek için ekstra çaba harcayın. Katı veya resmi olması gerekmez; aslında hacker kültürü, resmi olmayan, argo ve esprili bir dilin titizlikle kullanılmasına değer verir. Ancak kesin *olması* gerekiyor; Düşündüğünüze ve dikkat ettiğinize dair bazı belirtiler olmalı.

Doğru şekilde yazın, noktalayın ve büyük harf kullanın. "Onun"u "o" ile, "gevşek"i "kaybetmek"le veya "ayrık"ı "gizli" ile karıştırmayın. TAMAMI BÜYÜK HARFLERLE YAZMAYIN; bu bağırmak olarak okunur ve kaba kabul edilir. (Tamamen küçükler, okunması zor olduğundan biraz daha az sinir bozucudur. Alan Cox bundan kurtulabilir ama siz yapamazsınız.)

Doğru şekilde yazın, noktalayın ve büyük harf kullanın. "Onun"u "o" ile, "gevşek"i "kaybetmek"le veya "ayrık"ı "gizli" ile karıştırmayın. TAMAMI BÜYÜK HARFLERLE YAZMAYIN; bu bağırmak olarak okunur ve kaba kabul edilir. (Tamamen küçükler, okunması zor olduğundan biraz daha az sinir bozucudur. Alan Cox bundan kurtulabilir ama siz yapamazsınız.)

Ana dilinizi kullanmayan bir forumda soru soruyorsanız, yazım ve dilbilgisi hataları için sınırlı miktarda gevşeklik elde edersiniz; ancak tembellik nedeniyle fazladan gevşeklik olmaz (ve evet, genellikle bu farkı görebiliriz). Ayrıca yanıtladığınız kişinin dilinin ne olduğunu bilmiyorsanız İngilizce yazın. Meşgul bilgisayar üstadları anlamadıkları dillerdeki soruları hemen sormaya eğilimlidirler ve İngilizce, İnternet'in çalışma dilidir. İngilizce yazarak sorunuzun okunmadan atılma olasılığını en aza indirirsiniz.

İngilizce yazıyorsanız ancak bu sizin için ikinci bir dilse, potansiyel katılımcıları olası dil zorlukları ve bunları aşma seçenekleri konusunda uyarmak iyi bir yöntemdir. Örnekler:

- İngilizce benim ana dilim değil; lütfen yazım hatalarını affedin.
- $LANGUAGE konuşuyorsanız lütfen bana e-posta/PM gönderin; Sorumu tercüme ederken yardıma ihtiyacım olabilir.
- Teknik terimlere aşinayım ancak bazı argo ifadeler ve deyimler bana zor geliyor.
- Sorumu $LANGUAGE ve İngilizce dillerinde yayınladım. Yalnızca birini veya diğerini kullanırsanız yanıtları tercüme etmekten memnuniyet duyarım.

### Soruları erişilebilir, standart formatlarda gönderin

Sorunuzu yapay olarak okunmasını zorlaştırırsanız, sorunun, öyle olmayan bir soruyla geçiştirilmesi daha olasıdır. Bu yüzden:

- HTML değil, düz metin postası gönderin. ([HTML'yi kapatmak](http://www.birdhouse.org/etc/evilmail.html) zor değil.)
- MIME ekleri genellikle sorun yaratmaz, ancak bunlar yalnızca gerçek içerikse (ekli bir kaynak dosya veya yama gibi) ve yalnızca posta istemciniz tarafından oluşturulan standart metinler (mesajınızın başka bir kopyası gibi) değillerse.
- Paragrafların tamamının tek satırla çarpıldığı e-postalar göndermeyin. (Bu, mesajın yalnızca bir kısmına yanıt vermeyi çok zorlaştırır.) Yanıtlayanlarınızın postalarını 80 karakter genişliğindeki metin ekranlarında okuyacağını varsayalım ve satır kaydırmanızı buna göre 80'den az bir değere ayarlayın.
- Ancak verileri (günlük dosyası dökümleri veya oturum transkriptleri gibi) herhangi bir sabit sütun genişliğinde *sarmayın*. Veriler olduğu gibi dahil edilmelidir, böylece yanıtlayanlar sizin gördüklerinizi gördüklerine güvenebilirler.
- MIME Alıntı-Yazdırılabilir kodlamasını İngilizce dilindeki bir foruma göndermeyin. Bu kodlama, ASCII'nin kapsamadığı bir dilde posta gönderdiğinizde gerekli olabilir, ancak birçok e-posta aracısı bunu desteklemez. Kırıldıklarında, metne dağılmış tüm bu =20 glif çirkin ve dikkat dağıtıcı olur veya metninizin anlambilimini aktif olarak sabote edebilir.
- Bilgisayar üstadlarının Microsoft Word veya Excel gibi kapalı özel belge formatlarını okuyabilmelerini asla ama asla beklemeyin. Çoğu bilgisayar üstadı bunlara, kapınızın önüne dumanı tüten domuz gübresi atıldığında vereceğiniz tepki kadar tepki verir. Başa çıkabildikleri zaman bile bunu yapmak zorunda olmaktan içerlerler.
- Bir Windows makinesinden e-posta gönderiyorsanız, Microsoft'un sorunlu “Akıllı Alıntılar” özelliğini kapatın (Araçlar > Otomatik Düzeltme Seçenekleri'nden, Yazarken Otomatik Biçimlendir altındaki akıllı tırnaklar onay kutusunun işaretini kaldırın.). Bu, postalarınıza çöp karakterlerin serpilmesini önlemeniz içindir.
- Web forumlarında “gülen yüz” ve “HTML” özelliklerini (varsa) kötüye kullanmayın. Bir veya iki surat genellikle iyidir, ancak renkli süslü metinler insanların sizin topal olduğunuzu düşünmesine neden olur. Suratların, renklerin ve yazı tiplerinin ciddi şekilde aşırı kullanılması, kıkırdayan bir genç kız gibi görünmenize neden olacaktır; bu, cevaplardan çok seksle ilgilenmediğiniz sürece genellikle iyi bir fikir değildir.

Netscape Messenger, MS Outlook veya benzerleri gibi grafik kullanıcı arayüzüne sahip bir posta istemcisi kullanıyorsanız, varsayılan ayarlarıyla kullanıldığında bu kuralları ihlal edebileceğine dikkat edin. Bu tür istemcilerin çoğunda menü tabanlı bir "Kaynağı Görüntüle" komutu bulunur. Bunu, gönderilmiş posta klasörünüzdeki bir şey üzerinde kullanın ve düz metinlerin gereksiz eklemeler olmadan gönderilmesini doğrulayın.

### Sorununuz hakkında kesin ve bilgilendirici olun

- Sorununuzun veya hatanızın belirtilerini dikkatli ve net bir şekilde tanımlayın.
- Oluştuğu ortamı tanımlayın (makine, işletim sistemi, uygulama vb.). Satıcınızın dağıtım ve sürüm düzeyini sağlayın (örneğin: “Fedora Core 7”, “Slackware 9.1” vb.).
- Soruyu sormadan önce sorunu anlamak için yaptığınız araştırmayı açıklayın.
- Soruyu sormadan önce sorunu kendiniz tespit etmeye çalışmak için uyguladığınız teşhis adımlarını açıklayın.
- Bilgisayarınızda veya yazılım yapılandırmanızda olası ilgili son değişiklikleri açıklayın.
- Mümkünse *sorunu kontrollü bir ortamda yeniden oluşturmanın* bir yolunu sağlayın.

Bir bilgisayar üstadının soracağı soruları önceden tahmin etmek için elinizden gelenin en iyisini yapın ve yardım isteğinizde bu soruları önceden yanıtlayın.

Kodda hata olduğunu düşündüğünüz bir şeyi bildiriyorsanız, bilgisayar üstadlarına sorunu kontrollü bir ortamda yeniden oluşturma yeteneği vermek özellikle önemlidir. Bunu yaptığınızda, yararlı bir yanıt alma olasılığınız ve bu yanıtı alma olasılığınızın hızı büyük ölçüde artar.

Simon Tatham, [Hataları Etkili Bir Şekilde Nasıl Bildirebilirsiniz](http://www.chiark.greenend.org.uk/~sgtatham/bugs.html) başlıklı mükemmel bir makale yazmıştır. Okumanızı şiddetle tavsiye ederim.

### Hacim kesin değil

Kesin ve bilgilendirici olmanız gerekir. Bu amaca, büyük miktarda kodun veya verinin bir yardım isteğine aktarılmasıyla ulaşılamaz. Bir programı bozan büyük, karmaşık bir test senaryonuz varsa, onu kırpmaya ve mümkün olduğu kadar küçük yapmaya çalışın.

Bu en az üç nedenden dolayı faydalıdır. Bir: Soruyu basitleştirmek için çaba harcadığınızın görülmesi, yanıt alma olasılığınızı artırır. İki: Soruyu basitleştirmek, *faydalı* bir yanıt alma olasılığınızı artırır. Üç: Hata raporunuzu hassaslaştırma sürecinde kendiniz bir düzeltme veya geçici çözüm geliştirebilirsiniz.

### Bir hata bulduğunuzu iddia etmek için acele etmeyin

Bir yazılımla ilgili sorun yaşadığınızda, sağlamlığınızdan çok *çok* emin olmadığınız sürece bir hata bulduğunuzu iddia etmeyin. İpucu: Sorunu çözen bir kaynak kodu yaması veya yanlış davranış gösteren önceki bir sürüme karşı bir regresyon testi sağlayamadıkça, muhtemelen yeterince emin değilsiniz. Bu, web sayfaları ve belgeler için de geçerlidir; Eğer bir dokümantasyonda “hata” bulduysanız, değiştirilecek metni ve bunun hangi sayfalarda devam etmesi gerektiğini belirtmelisiniz.

Sizin sorununuzu yaşamayan birçok kullanıcı olduğunu unutmayın. Aksi takdirde, belgeleri okurken ve Web'de arama yaparken bunu öğrenmiş olurdunuz (bunu şikayet etmeden önce yaptınız, [değil miydiniz](http://www.catb.org/~esr/faqs/smart-questions.html) #önce)?). Bu, muhtemelen yanlış bir şey yapanın yazılım değil, siz olduğunuz anlamına gelir.

Yazılımı yazan kişiler, yazılımın mümkün olduğu kadar iyi çalışması için çok çalışıyorlar. Bir hata bulduğunuzu iddia ederseniz, onların yetkinliğine itiraz etmiş olursunuz, bu da haklı olsanız bile bazılarını rahatsız edebilir. Konu satırında "böcek" diye bağırmak özellikle diplomatik olmayan bir davranıştır.

Sorunuzu sorarken, gerçek bir hata bulduğunuzdan oldukça emin olsanız bile, *yanlış* bir şey yaptığınızı varsayıyormuş gibi yazmak en iyisidir. Gerçekten bir hata varsa, cevapta bunu duyacaksınız. Eğer hata yaptıysanız onlara bir özür borçlu olmak yerine, bakımcıların hata gerçekse sizden özür dilemek isteyecekleri şekilde oynayın.

### Yere kapanmak ödevinizi yapmanın yerini tutmaz

Bir cevap talep ederek kaba ve kibirli davranmamaları gerektiğini anlayan bazı insanlar, alçalmanın tam tersi bir uçta geri çekilirler. "Sadece zavallı bir acemi olduğumu biliyorum, ama...". Bu dikkat dağıtıcı ve yararsızdır. Asıl sorunla ilgili belirsizlikle birleştiğinde özellikle sinir bozucu oluyor.

Kaba primat politikalarıyla ne kendi zamanınızı, ne de bizim zamanımızı boşa harcamayın. Bunun yerine, arka plandaki gerçekleri ve sorunuzu olabildiğince açık bir şekilde sunun. Bu, kendini konumlandırmanın alçalmaktan daha iyi bir yoludur.

Bazen Web forumlarında yeni başlayanlar için sorular için ayrı yerler bulunur. Yeni başlayanlara yönelik bir sorunuz olduğunu düşünüyorsanız oraya gidin. Ama orada da boyun eğmeyin.

### Tahminlerinizi değil, sorunun belirtilerini açıklayın

Bilgisayar üstadlarına sorununuza neyin neden olduğunu düşündüğünüzü söylemenin faydası yoktur. (Teşhis teorileriniz bu kadar popüler olsaydı, yardım için başkalarına danışır mıydınız?) Bu nedenle, yorumlarınız ve teorileriniz yerine, onlara neyin yanlış gittiğinin ham belirtilerini anlattığınızdan emin olun. Yorumunu, teşhisini onlar yapsın. Tahmininizi belirtmenin önemli olduğunu düşünüyorsanız, bunu açıkça belirtin ve bu cevabın neden işinize yaramadığını açıklayın.

- **Aptal:**

 Çekirdek derlemelerinde arka arkaya SIG11 hataları alıyorum ve anakart izlerinden birinde ince bir çatlak olduğundan şüpheleniyorum. Bunları kontrol etmenin en iyi yolu nedir?

- **Akıllı:**

 256 MB Corsair PC133 SDRAM'lı FIC-PA2007 anakart (VIA Apollo VP2 yonga seti) üzerinde ev yapımı K6/233 cihazım, çekirdek derlemesi sırasında açılıştan yaklaşık 20 dakika sonra sık sık SIG11 hataları almaya başlıyor, ancak asla ilk 20 dakikada değil . Yeniden başlatmak saati yeniden başlatmaz ancak gece boyunca kapatmak bunu yapar. Tüm RAM'in değiştirilmesi işe yaramadı. Tipik bir derleme oturumu günlüğünün ilgili kısmı aşağıdadır.
 
Önceki nokta birçok insan için anlaşılması zor gibi göründüğünden, size hatırlatmak için bir ifade var: "Tüm teşhis uzmanları Missouri'lidir." Bu ABD eyaletinin resmi sloganı "Göster bana"dır (1899'da Kongre Üyesi Willard D. Vandiver'in "Mısır ve pamuk yetiştiren, horoz levreği ve Demokratlar yetiştiren bir ülkeden geliyorum ve köpüklü belagat beni ne ikna ediyor ne de tatmin ediyor. Ben Missouri'den. Bana göstermelisin.") Teşhis uzmanlarının durumunda bu bir şüphecilik meselesi değil, daha ziyade gördüğünüz aynı ham delile mümkün olduğunca yakın olanı görmeye yönelik gerçek, işlevsel bir ihtiyaçtır. tahminlerinizden ve özetlerinizden daha fazla. Bize göster.

### Sorununuzun belirtilerini kronolojik sırayla tanımlayın

Yanlış giden bir şeyin anlaşılmasında en yararlı ipuçları genellikle hemen önceki olaylarda yatmaktadır. Bu nedenle, hesabınız tam olarak ne yaptığınızı ve patlamaya yol açan makine ve yazılımın ne yaptığını açıklamalıdır. Komut satırı süreçlerinde, bir oturum günlüğüne sahip olmak (örneğin, komut dosyası yardımcı programını kullanarak) ve ilgili yirmi veya daha fazla satırı alıntılamak çok faydalıdır.

Karşınıza çıkan programın tanılama seçenekleri varsa (ayrıntılı için -v gibi), transkripte yararlı hata ayıklama bilgileri ekleyecek seçenekleri seçmeye çalışın. Daha fazlasının mutlaka daha iyi olmadığını unutmayın; Okuyucuyu çöplükte boğmak yerine bilgilendirecek bir hata ayıklama düzeyi seçmeye çalışın.

Anlatımınız uzun olursa (yaklaşık dört paragraftan fazla), sorunu en baştan kısaca belirtmek ve ardından kronolojik hikayeyi takip etmek yararlı olabilir. Bu şekilde bilgisayar üstadları hesabınızı okurken nelere dikkat etmeleri gerektiğini bilecekler.

### Adımı değil hedefi açıklayın

Bir şeyin nasıl yapılacağını bulmaya çalışıyorsanız (bir hatayı bildirmek yerine), hedefi tanımlayarak başlayın. Ancak o zaman engellendiğiniz adımı açıklayın.

Çoğu zaman, teknik yardıma ihtiyaç duyan kişilerin akıllarında yüksek düzeyde bir hedef vardır ve hedefe giden belirli bir yol olduğunu düşündükleri yolda takılıp kalırlar. Adım konusunda yardım almaya gelirler ama yolun yanlış olduğunun farkına varmazlar. Bunu aşmak ciddi bir çaba gerektirebilir.

- **Aptal:**

 FooDraw programındaki renk seçicinin onaltılık RGB değerini almasını nasıl sağlayabilirim?

- **Akıllı:**

 Bir görüntüdeki renk tablosunu kendi seçtiğim değerlerle değiştirmeye çalışıyorum. Şu anda bunu yapabilmemin tek yolu her tablo yuvasını düzenlemek, ancak FooDraw'un renk seçicisinin onaltılık bir RGB değeri almasını sağlayamıyorum.

Sorunun ikinci versiyonu akıllıdır. Göreve daha uygun bir araç öneren bir cevaba izin verir.

### İnsanlardan özel e-postayla yanıt vermelerini istemeyin

Bilgisayar üstadları, sorunların çözülmesinin halka açık, şeffaf bir süreç olması gerektiğine inanıyor; bu süreçte, daha bilgili biri yanıtın eksik veya yanlış olduğunu fark ederse, ilk yanıt denemesinde düzeltilebilir ve düzeltilmelidir. Ayrıca yardımcılar, yanıtlayanlar olarak ödüllerinin bir kısmını, akranları tarafından yetkin ve bilgili görülmekten alırlar.

Özel cevap istediğinizde hem süreci hem de ödülü bozuyorsunuz. Bunu yapma. Özel olarak yanıt verip vermemek *yanıtlayanın* tercihidir; eğer cevap verirse bunun nedeni genellikle sorunun başkaları için ilginç olamayacak kadar kötü biçimlendirilmiş veya açık olduğunu düşünmesidir.

Bu kuralın sınırlı bir istisnası vardır. Sorunun, birbirine çok yakın birçok yanıt alacağınızı düşünüyorsanız, o zaman sihirli kelimeler "bana e-posta gönderin, ben de grup için yanıtları özetleyeyim". Posta listesini veya haber grubunu büyük ölçüde aynı gönderilerden oluşan bir selden kurtarmaya çalışmak nezakettir - ancak özetleme sözünü tutmalısınız.

### Sorunuz hakkında açık olun

Açık uçlu sorular, açık uçlu zaman alıcı olarak algılanma eğilimindedir. Size yararlı bir yanıt verme olasılığı en yüksek olan kişiler aynı zamanda en meşgul kişilerdir (en fazla işi kendileri üstlendikleri için de olsa). Bu tür insanların açık uçlu zaman harcamalarına alerjisi vardır, dolayısıyla açık uçlu sorulara da alerjisi olma eğilimindedirler.

Yanıtlayanların ne yapmasını istediğinizi açıkça belirtirseniz (işaretçiler sağlayın, kod gönderin, yamanızı kontrol edin, vb.) yararlı bir yanıt alma olasılığınız daha yüksektir. Bu onların çabalarına odaklanacak ve katılımcının size yardım etmek için ayırması gereken zaman ve enerjiye dolaylı olarak bir üst sınır koyacaktır. Bu iyi.

Uzmanların içinde yaşadığı dünyayı anlamak için uzmanlığı bol bir kaynak, yanıt vermek için gereken zamanı ise kıt bir kaynak olarak düşünün. Örtük olarak ne kadar az zaman taahhüdü isterseniz, gerçekten iyi ve gerçekten meşgul birinden yanıt alma olasılığınız o kadar artar.

Bu nedenle, bir uzmanın konuyu ele alması için gereken süreyi en aza indirecek şekilde sorunuzu çerçevelemek faydalıdır; ancak bu genellikle soruyu basitleştirmekle aynı şey değildir. Bu nedenle, örneğin, "Bana X'in iyi bir açıklamasına dair bir ipucu verir misiniz?" genellikle "X'i açıklar mısınız lütfen?" sorusundan daha akıllıca bir sorudur. Arızalı bir kodunuz varsa, birinden onu düzeltmesini istemek yerine, birinden sorunun ne olduğunu açıklamasını istemek genellikle daha akıllıdır.

### Kod sorulduğunda

Ne tür bir sorun aramaları gerektiğine dair bir ipucu vermeden, başkalarından bozuk kodunuzun hatalarını ayıklamalarını istemeyin. Birkaç yüz satır kod yayınlayıp "işe yaramıyor" diyerek görmezden gelmenize neden olur. Bir düzine kod satırı yayınlayarak "7. satırdan sonra <x>'i görmeyi bekliyordum, ancak onun yerine <y> oluştu" diyerek yanıt alma olasılığınız çok daha yüksektir.

Bir kod sorunu hakkında kesin bilgi sahibi olmanın en etkili yolu, minimum düzeyde hata gösteren bir test senaryosu sağlamaktır. Minimum test senaryosu nedir? Bu sorunun bir örneğidir; yalnızca istenmeyen davranışı sergilemeye yetecek kadar kod var, daha fazlası değil. Minimal test senaryosunu nasıl hazırlarsınız? Sorunlu davranışı üreten kodun hangi satırının veya bölümünün olduğunu biliyorsanız, bunun bir kopyasını alın ve tam bir örnek oluşturmaya yetecek kadar destekleyici kod ekleyin (yani, kaynağın derleyici/yorumlayıcı/hangi uygulama tarafından işlenirse kabul edilebileceği kadar) . Belirli bir bölüme daraltamıyorsanız kaynağın bir kopyasını alın ve sorunlu davranışı etkilemeyen parçaları kaldırmaya başlayın. Minimum test durumunuz ne kadar küçükse o kadar iyidir (bkz. [“Hacim hassas değildir” adlı bölüm](http://www.catb.org/~esr/faqs/smart-questions.html#volume)).

Gerçekten küçük ve minimal bir test senaryosu oluşturmak her zaman mümkün olmayabilir, ancak bunu yapmaya çalışmak iyi bir disiplindir. Sorunu kendi başınıza çözmek için neye ihtiyacınız olduğunu öğrenmenize yardımcı olabilir; öyle olmasa bile bilgisayar üstadları denediğinizi görmekten hoşlanır. Bu onları daha işbirlikçi hale getirecek.

Yalnızca bir kod incelemesi istiyorsanız, bunu önceden söyleyin ve özellikle hangi alanların gözden geçirilmesi gerektiğini düşündüğünüzü ve nedenini belirttiğinizden emin olun.

### Ev ödevi soruları göndermeyin

Bilgisayar üstadları ev ödevi sorularını tespit etmekte iyidir; çoğumuz bunları kendimiz yaptık. Bu sorular *sizin* çözmeniz içindir, böylece deneyimlerden ders alırsınız. İpuçları istemek sorun değil, ancak tüm çözümler için değil.

Bir ev ödevi sorusunun size iletildiğinden şüpheleniyorsanız ancak yine de çözemiyorsanız, bir kullanıcı grubu forumunda veya (son çare olarak) bir projenin “kullanıcı” listesinde/forumunda sormayı deneyin. Bilgisayar üstadları bunu * tespit edecek * olsa da, ileri düzey kullanıcılardan bazıları size en azından bir ipucu verebilir.

### Anlamsız sorguları budama

Yardım talebinizi "Bana yardım edebilecek kimse var mı?" gibi anlamsal olarak boş sorularla kapatma isteğinize karşı koyun. veya “Bir cevap var mı?” Birincisi: Sorun açıklamanızı yarıya kadar yetkin bir şekilde yazdıysanız, bu tür üzerinde durulmuş sorular en iyi ihtimalle gereksizdir. İkincisi: gereksiz oldukları için bilgisayar üstadları onları sinir bozucu buluyor ve mantıksal olarak kusursuz ama küçümseyen yanıtlar veriyorlar: "Evet, sana yardım edilebilir" ve "Hayır, sana yardım yok."

Genel olarak, [evet veya hayır yanıtı](http://homepage.ntlworld.com./jonathan.deboynepollard/FGA/questions-with-) istemediğiniz sürece evet veya hayır şeklinde sorular sormaktan kaçınmak iyi bir şeydir. evet-veya-hayır-cevapları.html).

### Sorunuz size ait olsa bile "Acil" olarak işaretlemeyin

Bu sizin sorununuz, bizim değil. Aciliyet iddiasında bulunmak büyük olasılıkla ters etki yaratacaktır: çoğu bilgisayar üstadı, anında ve özel ilgi çekmeye yönelik kaba ve bencil girişimler nedeniyle bu tür mesajları basitçe siler. Ayrıca, 'Acil' kelimesi (ve konu satırında dikkat çekmeye yönelik diğer benzer girişimler) sıklıkla spam filtrelerini tetikler; hedeflediğiniz alıcılar bunu hiç göremeyebilir!

Bir yarı istisna var. Programı, bilgisayar üstadlarının heyecan duyacağı yüksek profilli bir yerde kullanıyorsanız bahsetmeye değer olabilir; Böyle bir durumda, eğer zaman baskısı altındaysanız ve bunu kibarca söylerseniz, insanlar daha hızlı cevap verecek kadar ilgilenebilirler.

Ancak bu çok riskli bir iştir çünkü bilgisayar üstadlarının neyin heyecan verici olduğuna ilişkin ölçüsü muhtemelen sizinkinden farklıdır. Örneğin, Uluslararası Uzay İstasyonundan gönderilen gönderiler uygun olabilir, ancak kendinizi iyi hissettiren bir hayırseverlik veya siyasi amaç adına gönderi göndermek neredeyse kesinlikle uygun değildir. Aslında, "Acil: Tüylü fok yavrularını kurtarmama yardım edin!" tüylü yavru fokların önemli olduğunu düşünen bilgisayar üstadları tarafından bile güvenilir bir şekilde dışlanmanıza veya ateşlenmenize neden olacaktır.

Bunu gizemli bulursanız, herhangi bir şey yayınlamadan önce, bu nasıl yapılırın geri kalanını anlayana kadar tekrar tekrar okuyun.

### Nezaket asla zarar vermez ve bazen yardımcı olur

Nazik olun. “Lütfen” ve “İlginiz için teşekkürler” veya “Değerlendirdiğiniz için teşekkürler” kullanın. İnsanların size ücretsiz olarak yardım etmek için harcadıkları zamanı takdir ettiğinizi açıkça belirtin.

Dürüst olmak gerekirse bu, dilbilgisel, açık, kesin ve açıklayıcı olmak, özel formatlardan kaçınmak vb. kadar önemli değildir (ve bunların yerini alamaz); Bilgisayar üstadları genel olarak kibar belirsizlikler yerine biraz sert ama teknik açıdan keskin hata raporları almayı tercih ederler. (Eğer bu sizi şaşırtıyorsa, bir soruya bize öğrettikleriyle değer verdiğimizi unutmayın.)

Bununla birlikte, teknik konularda sorun yaşıyorsanız nezaket yararlı bir yanıt alma şansınızı artırır.

(Bu NASIL belgesine yönelik deneyimli bilgisayar üstadlarından aldığımız tek ciddi itirazın, "Şimdiden teşekkür ederiz" ifadesini kullanma yönündeki önceki önerimizle ilgili olduğunu belirtmeliyiz. Bazı bilgisayar üstadları bunun, daha sonra kimseye teşekkür etmeme niyeti anlamına geldiğini düşünüyor. Bizim önerimiz şudur: ya önce "Şimdiden teşekkürler" deyin *ve* yanıtlayanlara daha sonra teşekkür edin ya da "İlginiz için teşekkürler" veya "Düşünceniz için teşekkürler" gibi farklı bir şekilde nezaketinizi ifade edin.)

### Çözüme ilişkin kısa bir notla devam edin

Sorun çözüldükten sonra size yardımcı olan herkese bir not gönderin; nasıl ortaya çıktığını onlara bildirin ve yardımları için onlara tekrar teşekkür edin. Sorun bir e-posta listesinde veya haber grubunda genel ilgi gördüyse, devamını orada yayınlamak uygun olacaktır.

İdeal olarak yanıt, orijinal soru gönderimiyle başlatılan başlığa verilmeli ve konu satırında "DÜZELTİLDİ", "ÇÖZÜLDÜ" veya aynı derecede belirgin bir etiket bulunmalıdır. Hızlı geri dönüş sağlayan posta listelerinde, "Problem X" hakkında "Problem X - DÜZELTİLDİ" ile biten bir ileti dizisi gören potansiyel bir katılımcı, ileti dizisini okuyarak bile zamanını boşa harcamaması gerektiğini bilir (kişisel olarak Sorun X'i ilginç bulmadığı sürece) ) ve dolayısıyla bu zamanı farklı bir sorunu çözerek kullanabilir.

Takibinizin uzun ve kapsamlı olması gerekmez; basit bir "Merhaba - arızalı bir ağ kablosuydu! Herkese teşekkürler. - Bill” hiç yoktan iyidir. Aslında kısa ve tatlı bir özet, çözümün gerçek bir teknik derinliğe sahip olmadığı sürece uzun bir tezden daha iyidir. Hangi eylemin sorunu çözdüğünü söyleyin ancak sorun giderme adımlarının tamamını tekrarlamanıza gerek yoktur.

Biraz derinliğe sahip sorunlar için sorun giderme geçmişinin bir özetini yayınlamak uygundur. Son sorun bildiriminizi açıklayın. Çözüm olarak neyin işe yaradığını açıklayın ve *bundan sonra* önlenebilecek çıkmaz sokakları belirtin. Devamını bir polisiye hikayeye dönüştürmek yerine, çıkmaz sokaklara doğru çözüm ve diğer özet materyaller konulmalıdır. Size yardım eden kişilerin adlarını söyleyin; bu şekilde arkadaş edineceksin.

Nazik ve bilgilendirici olmanın yanı sıra, bu tür bir takip, e-posta listesi/haber grubu/forum arşivinde arama yapan diğer kişilerin tam olarak hangi çözümün size yardımcı olduğunu bilmelerine yardımcı olacaktır ve dolayısıyla onlara da yardımcı olabilir.

Son olarak ve en önemlisi, bu tür bir takip, yardım eden herkesin sorun hakkında tatmin edici bir kapanış duygusu hissetmesine yardımcı olur. Kendiniz bir teknisyen veya bilgisayar üstadı değilseniz, bu duygunun, yardım için başvurduğunuz gurular ve uzmanlar için çok önemli olduğuna güvenin. Çözümlenmemiş hiçliğe doğru sürüklenen sorun anlatıları sinir bozucu şeylerdir; Bilgisayar üstadları bunların çözüldüğünü görmek için can atıyor. Kaşıntıyı kaşımanın size kazandırdığı iyi niyet, bir dahaki sefere soru sormanız gerektiğinde size çok ama çok yardımcı olacaktır.

Gelecekte başkalarının da aynı sorunu yaşamasını nasıl önleyebileceğinizi düşünün. Kendinize bir belgenin veya SSS yamasının yardımcı olup olmayacağını sorun ve cevabınız evet ise bu yamayı bakımcıya gönderin.

Bilgisayar üstadları arasında bu tür iyi takip davranışı aslında geleneksel nezaketten daha önemlidir. Başkalarıyla iyi oynama konusunda bu şekilde itibar kazanırsınız ki bu çok değerli bir varlık olabilir.

## Yanıtlar Nasıl Yorumlanır?

### RTFM ve STFW: Ciddi Bir Şekilde İşi Berbat Ettiğinizi Nasıl Anlarsınız?

Eski ve kutsal bir gelenek vardır: "RTFM" yazan bir yanıt alırsanız, onu gönderen kişi Lanet Kılavuzu Okumanız gerektiğini düşünür. Neredeyse kesinlikle haklıdır. Git oku.

RTFM'nin daha genç bir akrabası var. "STFW" yazan bir yanıt alırsanız, bunu gönderen kişi Lanet Web'de Arama yapmanız gerektiğini düşünüyor. Neredeyse kesinlikle haklıdır. Git araştır. (Bunun daha hafif versiyonu size “Google sizin arkadaşınızdır!” denmesidir.)

Web forumlarında ayrıca forum arşivlerinde arama yapmanız da istenebilir. Aslında birisi bu sorunun çözüldüğü önceki konuya işaret edecek kadar nazik olabilir. Ancak bu düşünceye güvenmeyin; Sormadan önce arşiv aramanızı yapın.

Çoğu zaman, size arama yapmanızı söyleyen kişi, ihtiyacınız olan bilgilerin bulunduğu kılavuzu veya web sayfasını açar ve yazarken bunlara bakmaktadır. Bu yanıtlar, yanıtlayan kişinin (a) ihtiyacınız olan bilgiyi bulmanın kolay olduğunu ve (b) bilgiyi ararsanız, size kaşıkla yedirmekten daha fazlasını öğreneceğinizi düşündüğü anlamına gelir.

Bundan alınmamalısın; Bilgisayar üstadlarının standartlarına göre, yanıtladığınız kişi sizi görmezden gelmeyerek size kaba bir saygı gösteriyor. Bunun yerine bu büyükanne nezaketine minnettar olmalısınız.

### Eğer anlamıyorsan...

Cevabı anlamadıysanız, açıklama talebinizi hemen geri çevirmeyin. Cevabı anlamak için orijinal sorunuzu cevaplamak için kullandığınız araçları (kılavuzlar, SSS'ler, Web, yetenekli arkadaşlar) kullanın. Daha sonra eğer hala açıklama istemeniz gerekiyorsa öğrendiklerinizi sergileyin.

Örneğin, size şunu söylediğimi varsayalım: “Sanki bir noktada sıkışıp kalmışsınız gibi görünüyor; temizlemeniz gerekecek.” Sonra: işte *kötü* bir takip sorusu: "Zentry nedir?" İşte *iyi* bir takip sorusu: “Tamam, man sayfasını okudum ve zentrilerden yalnızca -z ve -p anahtarlarının altında bahsediliyor. İkisi de merkezlerin temizlenmesiyle ilgili bir şey söylemiyor. Bunlardan biri mi yoksa burada bir şeyi mi kaçırıyorum?”

### Kabalıkla baş etmek

Bilgisayar üstadları çevrelerinde kabalık gibi görünen şeylerin çoğu, kimseyi gücendirme amacı taşımaz. Daha ziyade, başkalarının sıcak ve yumuşak hissetmesini sağlamaktan ziyade sorunları çözmekle ilgilenen insanlar için doğal olan doğrudan, saçmalıkları ortadan kaldıran iletişim tarzının ürünüdür.

Kabalık algıladığınızda sakin bir şekilde tepki vermeye çalışın. Birisi gerçekten eylem yapıyorsa, listedeki, haber grubundaki veya forumdaki kıdemli bir kişinin onu bu konuda araması muhtemeldir. Eğer bu *olmazsa* ve öfkenizi kaybederseniz, muhtemelen öfkelendiğiniz kişi hacker topluluğunun normlarına uygun davranıyordu ve *siz* hatalı kabul edileceksiniz. Bu, istediğiniz bilgiyi veya yardımı alma şansınızı zedeleyecektir.

Öte yandan, zaman zaman kabalıklarla ve oldukça yersiz tavırlarla karşılaşacaksınız. Yukarıdakilerin diğer tarafı, gerçek suçluları oldukça sert bir şekilde çarpmanın, kötü davranışlarını keskin bir sözlü neşterle parçalara ayırmanın kabul edilebilir bir biçim olmasıdır. Ancak bunu denemeden önce zemininizden çok ama çok emin olun. Bir kabalığı düzeltmek ile anlamsız bir ateşli savaş başlatmak arasındaki çizgi o kadar incedir ki, bilgisayar üstadlarının kendileri de nadiren bu çizgiyi aşar; eğer yeniyseniz veya yabancıysanız, böyle bir hatadan kaçınma şansınız düşüktür. Eğlenceden çok bilginin peşindeyseniz, bu riski göze almaktansa parmaklarınızı klavyeden uzak tutmak daha iyidir.

(Bazı insanlar, pek çok bilgisayar üstadının hafif bir otizm veya Asperger Sendromu hastası olduğunu ve aslında "normal" insan sosyal etkileşimini sağlayan bazı beyin devrelerinin eksik olduğunu iddia eder. Bu doğru olabilir veya olmayabilir. Eğer kendiniz bir bilgisayar üstadı değilseniz , eğer beynimizin hasar gördüğünü düşünürseniz, bu, tuhaflıklarımızla başa çıkmanıza yardımcı olabilir. Devam edin, umursamayacağız; ne olursak olalım *hoşumuza gidiyor* ve genellikle klinik etiketler konusunda sağlıklı bir şüpheciliğe sahibiz. .)

Jeff Bigler'in [incelik filtreleri](http://www.mit.edu/~jcb/tact.html) hakkındaki gözlemleri de konuyla alakalı ve okumaya değer.

Bir sonraki bölümde farklı bir konuya değineceğiz; *yaramazlık yaptığınızda* göreceğiniz türden bir “kabalık”.

## Kaybeden Gibi Tepki Vermemek Üzerine

Muhtemelen üstadların topluluğu forumlarında bu makalede ayrıntılı olarak açıklanan şekillerde veya benzer şekillerde birkaç kez hata yapacaksınız. Ve size tam olarak nasıl batırdığınız anlatılacak, muhtemelen renkli yanlarıyla. Alenen.

Bu olduğunda, yapabileceğiniz en kötü şey deneyim hakkında sızlanmak, sözlü saldırıya uğradığınızı iddia etmek, özür istemek, çığlık atmak, nefesinizi tutmak, dava açmakla tehdit etmek, insanların işverenlerine şikayette bulunmak, klozet kapağını açık bırakmak vb. işte yaptığınız şey:

Aş bunu. Bu normal. Aslında sağlıklı ve uygundur.

Topluluk standartları kendilerini korumaz: Bu standartları görünür bir şekilde *kamusal alanda* aktif olarak uygulayan insanlar tarafından sürdürülürler. Tüm eleştirilerin özel e-posta yoluyla iletilmesi gerektiğini söyleyerek sızlanmayın: Bu işler böyle yürümüyor. Birisi iddialarınızdan birinin yanlış olduğunu veya görüşlerinin farklı olduğunu söylediğinde kişisel olarak hakarete uğradığınızda ısrar etmenin de faydası yoktur. Bunlar kaybeden tutumlardır.

Yanlış yönlendirilmiş bir hiper-nezaket anlayışından dolayı, katılımcıların başka birinin gönderileriyle ilgili herhangi bir arıza tespitinde bulunmalarının yasaklandığı ve "Kullanıcıya yardım etmek istemiyorsanız hiçbir şey söylemeyin" dendiği hacker forumları olmuştur. Bunun sonucunda bilgili katılımcıların başka yerlere gitmesi, onların anlamsız gevezeliklere sürüklenmesine ve teknik forumlar olarak işe yaramaz hale gelmesine neden olur.

Abartılı bir şekilde "arkadaş canlısı" (bu şekilde) veya faydalı: Birini seçin.

Unutmayın: Bilgisayar üstadı size işi batırdığınızı söylediğinde ve (ne kadar sert olursa olsun) bunu bir daha yapmamanızı söylediğinde, (1) siz ve (2) topluluğu için endişeleniyor demektir. Seni görmezden gelip seni hayatından süzmesi onun için çok daha kolay olurdu. Minnettar olmayı başaramıyorsanız, en azından biraz onurlu olun, sızlanmayın ve sırf teatral olarak aşırı duyarlı bir ruha ve hak kazanma yanılsamasına sahip yeni gelen biri olduğunuz için kırılgan bir oyuncak bebek gibi davranılmayı beklemeyin. .

Bazen, siz batırmasanız bile (ya da sadece onların hayal gücünde batırmış olsanız bile), insanlar size kişisel olarak saldıracak, görünürde bir neden olmadan alev alev yanacaktır. Bu durumda şikayet etmek *gerçekten* batırmanın yoludur.

Bu ateşliler ya hiçbir fikri olmayan ama kendilerini uzman sanan topallar ya da sizin hata yapıp yapmayacağınızı test eden sözde psikologlar. Diğer okuyucular ya bunları görmezden geliyor ya da kendi başlarına baş etmenin yollarını buluyor. Alevcilerin davranışları kendileri için problemler yaratır ve bunların sizi endişelendirmesine gerek yoktur.
	
Kendinizi de bir alev savaşının içine çekmenize izin vermeyin. Çoğu alevin göz ardı edilmesi en iyisidir - bunların gerçekten alev olup olmadığını kontrol ettikten sonra, nasıl batırdığınıza dair işaretler değil ve gerçek sorunuza akıllıca şifrelenmiş yanıtlar değil (bu da olur).

## Sorulmaması Gereken Sorular

İşte bazı klasik aptal sorular ve bilgisayar üstadlarının bu soruları yanıtlamadıklarında ne düşündükleri.

- S: [X programını veya kaynağını nerede bulabilirim?](http://www.catb.org/~esr/faqs/smart-questions.html#idm46060474018960)
- S: [Y'yi yapmak için X'i nasıl kullanabilirim?](http://www.catb.org/~esr/faqs/smart-questions.html#idm46060474016288)
- S: [Kabuk istemimi nasıl yapılandırabilirim?](http://www.catb.org/~esr/faqs/smart-questions.html#idm46060474013936)
- S: [Bass-o-matic dosya dönüştürücüyü kullanarak bir AcmeCorp belgesini TeX dosyasına dönüştürebilir miyim?](http://www.catb.org/~esr/faqs/smart-questions.html#idm46060474011312)
- S: [{Programım, konfigürasyonum, SQL ifadem} çalışmıyor](http://www.catb.org/~esr/faqs/smart-questions.html#idm46060474008752)
- S: [Windows makinemde sorunlar yaşıyorum. Yardım edebilir misiniz?](http://www.catb.org/~esr/faqs/smart-questions.html#idm46060474004672)
- S: [Programım çalışmıyor. Sanırım sistem özelliği X bozuk.](http://www.catb.org/~esr/faqs/smart-questions.html#idm46060474001536)
- S: [Linux veya X'i yüklerken sorun yaşıyorum. Yardım edebilir misiniz?](http://www.catb.org/~esr/faqs/smart-questions.html#idm46060473999136)
- S: [Kökü nasıl kırabilirim/kanal operasyon ayrıcalıklarını nasıl çalabilirim/birinin e-postasını nasıl okuyabilirim?](http://www.catb.org/~esr/faqs/smart-questions.html#idm46060473994832)

| **S:** | X programını veya kaynağını nerede bulabilirim? |
| ------ | -------------------------------------------------- ---------- |
| **C:** | Onu bulacağım yerin aynısı, aptal; internet aramasının diğer ucunda. Tanrım, henüz herkes [Google'ı](http://www.google.com/) nasıl kullanacağını bilmiyor mu? |
| **S:** | Y'yi yapmak için X'i nasıl kullanabilirim? |
| **C:** | Eğer Y yapmak istiyorsanız, uygun olmayabilecek bir yöntemin kullanılacağını varsaymadan bu soruyu sormalısınız. Bu formdaki sorular genellikle yalnızca X hakkında bilgisiz olmakla kalmayıp, aynı zamanda hangi Y problemini çözdüğü konusunda kafası karışık olan ve kendi özel durumunun ayrıntılarına fazla takılıp kalan bir kişiyi gösterir. Sorunlarını daha iyi tanımlayana kadar bu tür insanları görmezden gelmek genellikle en iyisidir. |
| **S:** | Kabuk istemimi nasıl yapılandırabilirim? |
| **C:** | Bu soruyu soracak kadar akıllıysanız, [RTFM](http://www.catb.org/~esr/faqs/smart-questions.html#rtfm) yapacak ve kendiniz keşfedecek kadar akıllısınız demektir. |
| **S:** | Bass-o-matic dosya dönüştürücüyü kullanarak bir AcmeCorp belgesini TeX dosyasına dönüştürebilir miyim? |
| **C:** | Deneyin ve görün. Bunu yapsaydın, (a) cevabı öğrenirdin ve (b) zamanımı boşa harcamayı bırakırdın. |
| **S:** | {Programım, konfigürasyonum, SQL ifadem} çalışmıyor |
| **C:** | Bu bir soru değil ve asıl sorunuzu aklınızdan çıkarmak için Yirmi Soru oynamakla ilgilenmiyorum - yapacak daha iyi işlerim var. Böyle bir şey gördüğümde tepkim normalde aşağıdakilerden biri olur: Buna ekleyecek başka bir şeyin var mı? Ah, bu çok kötü, umarım düzeltirsin. Ve bunun benimle tam olarak ne alakası var? |
| **S:** | Windows makinemde sorunlar yaşıyorum. Yardım edebilir misin? |
| **C:** | Evet. Microsoft'un çöplerini atın ve Linux veya BSD gibi açık kaynaklı bir işletim sistemi yükleyin. Not: Windows makineleriyle ilgili soruları, eğer resmi bir Windows yapısına sahip olan veya Windows makineleriyle etkileşime giren bir program hakkındaysa *sorabilirsiniz*. yani Samba). Sorunun programda değil Windows'ta olduğu yönündeki yanıta şaşırmayın, çünkü Windows genel olarak o kadar bozuk ki bu durum sıklıkla yaşanıyor. |
| **S:** | Programım çalışmıyor. Sanırım sistem tesisi X bozuldu. |
| **C:** | Yüzlerce veya binlerce kişinin yoğun olarak kullandığı sistem çağrıları ve kütüphanelerdeki bariz eksikliği ilk fark eden kişi olmanız mümkün olsa da, tamamen bilgisiz olmanız daha muhtemeldir. Olağanüstü iddialar olağanüstü deliller gerektirir; Bunun gibi bir iddiada bulunduğunuzda, bunu arıza durumuna ilişkin açık ve kapsamlı belgelerle desteklemeniz gerekir. |
| **S:** | Linux veya X'i yüklerken sorun yaşıyorum. Yardım edebilir misiniz? |
| **C:** | Hayır. Bu sorunu gidermek için makinenize uygulamalı erişime ihtiyacım var. Gidip yerel Linux kullanıcı grubunuzdan uygulamalı yardım isteyin. (Kullanıcı gruplarının listesini [burada](http://www.linux.org/groups/index.html) bulabilirsiniz.) Not: Bir forumda veya e-posta listesindeyseniz Linux kurulumuyla ilgili sorular uygun olabilir. belirli bir dağıtımla ilgili ve sorun *o* dağıtımda; veya yerel kullanıcı grupları forumlarında. Bu durumda, arızanın tam ayrıntılarını açıkladığınızdan emin olun. Ancak öncelikle "linux" ve *tüm* şüpheli donanım parçalarıyla dikkatli arama yapın. |
| **S:** | Kökü nasıl kırabilirim/kanal operasyon ayrıcalıklarını nasıl çalabilirim/birinin e-postasını nasıl okuyabilirim? |
| **C:** | Böyle şeyler yapmak istediğin için serserisin, bir bilgisayar üstadından sana yardım etmesini istediğin için de aptalsın. |

## İyi ve Kötü Sorular

Son olarak akıllı bir şekilde nasıl soru sorulabileceğini örnek olarak göstereceğim; Aynı sorun hakkında biri aptalca, diğeri akıllıca sorulan bir çift soru.

- **Aptal:** Foonly Flurbamatic hakkında nereden bilgi edinebilirim?

 Bu soru yalnızca yanıt olarak ["STFW"](http://www.catb.org/~esr/faqs/smart-questions.html#rtfm) için yalvarıyor.

- **Akıllı:** Web'de "Foonly Flurbamatic 2600"ü bulmak için Google'ı kullandım, ancak işe yarar bir sonuç elde edemedim. Bu cihazdaki programlama bilgilerine yönelik bir işaretçi alabilir miyim?

 Bu zaten STFWed'e sahip ve gerçek bir sorun varmış gibi görünüyor.

- **Aptal:** Proje foo'dan derleme kodunu alamıyorum. Neden kırık?

 Soru soran kişi başka birinin işleri batırdığını varsayıyor. Kibirli herif...

- **Akıllı:** Foo projesindeki kod, Nulix sürüm 6.2 altında derlenmiyor. SSS'yi okudum ancak içinde Nulix ile ilgili sorunlarla ilgili hiçbir şey yok. İşte derleme girişimimin bir metni; benim yaptığım bir şey mi?

 Soru soran kişi ortamı belirledi, SSS'yi okudu, hatayı gösteriyor ve sorunlarının başkasının hatası olduğunu varsaymıyor. Bu biraz dikkat etmeye değer olabilir.

- **Aptal:** Anakartımla sorun yaşıyorum. Kimse yardım edebilir mi?

 J. Random Hacker'ın buna yanıtı muhtemelen “Doğru. Geğirmeye ve bebek bezi değiştirmeye de ihtiyacın var mı?” ardından silme tuşuna basılması.

- **Akıllı:** S2464 anakartında X, Y ve Z'yi denedim. Bu işe yaramayınca A, B ve C'yi denedim. C'yi denediğimde ortaya çıkan tuhaf belirtiye dikkat edin. Açıkçası süslü gromitler var, ancak sonuçlar beklendiği gibi değil. Athlon MP anakartlarında grommicking'in genel nedenleri nelerdir? Sorunu belirlemek için yapabileceğim daha fazla test fikri olan var mı?

  Öte yandan bu kişi bir cevaba layık görünüyor. Pasif bir şekilde bir cevabın yukarıdan düşmesini beklemek yerine, problem çözme zekası sergilemiştir.

Son soruda, "Bana bir cevap verin" ile "Lütfen aydınlanmaya ulaşmak için hangi ek teşhisleri uygulayabileceğimi bulmama yardım edin" talebi arasındaki ince ama önemli farka dikkat edin.

Aslında bu son sorunun şekli, Ağustos 2001'de linux çekirdeği posta listesinde (lkml) meydana gelen gerçek bir olaya yakından dayanmaktadır. O zaman soruyu soran kişi bendim (Eric). Tyan S2462 anakartında gizemli kilitlenmeler görüyordum. Liste üyeleri sorunları çözmek için ihtiyacım olan kritik bilgileri sağladı.

Soruyu bu şekilde sorarak insanlara kafa yoracak bir şeyler verdim; Katılmalarını kolay ve çekici hale getirdim. Akranlarımın yeteneklerine saygı gösterdim ve onları bir akran olarak bana danışmaya davet ettim. Ayrıca onlara zaten koştuğum çıkmaz sokakları anlatarak zamanlarının değerine saygı duyduğumu gösterdim.

Daha sonra herkese teşekkür edip sürecin ne kadar iyi işlediğini söylediğimde bir lkml üyesi, o listede bir “isim” olduğum için değil, soruyu doğru biçimde sorduğum için işe yaradığını düşündüğünü gözlemledi.

Bilgisayar üstadları bazı açılardan çok acımasız bir meritokrasidir; Haklı olduğundan eminim ve eğer sünger gibi davransaydım, kim olursam olayım alevlenirdim ya da görmezden gelinirdim. Başkalarına talimat vermek amacıyla tüm olayı yazmam yönündeki önerisi doğrudan bu kılavuzun hazırlanmasına yol açtı.

## Cevap Alamıyorsanız

Bir yanıt alamıyorsanız, lütfen size yardımcı olamayacağımızı düşünmediğimizi kişisel olarak algılamayın. Bazen sorulan grubun üyeleri cevabı bilemeyebilir. Hiçbir yanıt vermemek görmezden gelinmekle aynı şey değildir, ancak itiraf etmek gerekir ki dışarıdan farkı fark etmek zordur.

Genel olarak sorunuzu yeniden göndermek kötü bir fikirdir. Bu anlamsız derecede sinir bozucu olarak görülecektir. Sabırlı olun: Yanıtınızı veren kişi farklı bir saat diliminde ve uyuyor olabilir. Ya da sorunuz başlangıçta iyi biçimlendirilmemiş olabilir.

Başvurabileceğiniz başka yardım kaynakları da vardır; bunlar genellikle aceminin ihtiyaçlarına daha iyi uyarlanmış kaynaklardır.

Kendileri herhangi bir yazılım yazmamış olsalar bile, yazılıma meraklı birçok çevrimiçi ve yerel kullanıcı grubu bulunmaktadır. Bu gruplar genellikle insanların birbirlerine yardım edebilmesi ve yeni kullanıcılara yardım edebilmesi için oluşur.

Ayrıca yardım için anlaşabileceğiniz büyük ve küçük pek çok ticari şirket de bulunmaktadır. Biraz yardım için para ödemek zorunda kalma fikri sizi dehşete düşürmesin! Sonuçta, eğer arabanızın motoru kapak contasını patlatırsa, muhtemelen onu bir tamirhaneye götürüp tamir ettirmek için para ödersiniz. Yazılımın size hiçbir maliyeti olmasa bile bu desteğin her zaman ücretsiz olarak gelmesini bekleyemezsiniz.

Linux gibi popüler yazılımlarda geliştirici başına en az 10.000 kullanıcı vardır. 10.000'den fazla kullanıcıdan gelen destek çağrılarını tek bir kişinin karşılaması mümkün değil. Destek için ödeme yapmak zorunda kalsanız bile, yazılımı da satın almak zorunda kaldığınızda ödeyeceğinizden çok daha azını ödeyeceğinizi unutmayın (ve kapalı kaynak yazılım desteği, açık kaynak yazılım desteğinden genellikle daha pahalı ve daha az yetkindir).

## Sorulara Yararlı Bir Şekilde Nasıl Cevap Verilir?

*Nazik olun.* Sorundan kaynaklanan stres, öyle olmasa bile insanların kaba veya aptal görünmesine neden olabilir.

*İlk suçluya çevrimdışı yanıt verin.* Dürüst bir hata yapmış olabilecek birinin toplum önünde aşağılanmasına gerek yoktur. Gerçek bir acemi, arşivlerde nasıl arama yapılacağını veya SSS'nin nerede saklandığını veya yayınlandığını bilemeyebilir.

*Emin değilseniz, söyleyin!* Yanlış ama otoriter görünen bir cevap, hiç cevap vermemekten daha kötüdür. Bir uzman gibi konuşmak eğlenceli diye kimseyi yanlış yola yönlendirmeyin. Alçakgönüllü ve dürüst olun; hem soruyu soran kişiye hem de akranlarınıza iyi bir örnek oluşturun.

*Yardım edemiyorsanız engellemeyin.* Kullanıcının kurulumunu bozabilecek prosedürler hakkında şaka yapmayın; zavallı aptal bunları talimat olarak yorumlayabilir.

*Daha fazla ayrıntı ortaya çıkarmak için derinlemesine sorular sorun.* Bu konuda iyiyseniz, soruyu soran kişi bir şeyler öğrenecektir - siz de öyle. Kötü soruyu iyi bir soruya dönüştürmeye çalışın; unutmayın hepimiz bir zamanlar acemiydik.

RTFM'yi mırıldanmak bazen tembel bir pasaklı birine yanıt verirken haklı görülse de, belgelere işaret etmek (sadece bir anahtar sözcük için Google'a yapılan bir öneri olsa bile) daha iyidir.

*Eğer soruyu cevaplayacaksanız değeri iyi verin.* Birisi yanlış araç veya yaklaşımı kullanıyorsa, hantal geçici çözümler önermeyin. İyi araçlar önerin. Soruyu yeniden çerçevelendirin.

Asıl soruyu cevapla! Soruyu soran kişi araştırmasını yapacak kadar ayrıntılıysa ve sorguya X, Y, Z, A, B ve C'nin zaten iyi bir sonuç alınmadan denendiğini eklediyse, "Dene" şeklinde yanıt vermek son derece yararsızdır. A veya B" veya yalnızca "X, Y, Z, A, B veya C'yi deneyin" diyen bir şeye bağlantı içeren.

*Topluluğunuzun sorudan ders almasına yardımcı olun.* İyi bir soru sorduğunuz zaman kendinize şu soruyu sorun: "Kimsenin bu soruya bir daha cevap vermek zorunda kalmaması için ilgili dokümanların veya SSS'nin nasıl değişmesi gerekir?" Daha sonra belge bakımcısına bir yama gönderin.

Soruyu cevaplamak için araştırma yaptıysanız, *cevabınızı kıçınızdan çıkarmış gibi yazmak yerine becerilerinizi gösterin.* İyi bir soruyu cevaplamak, aç bir insanı bir öğün doyurmaya benzer, ancak ona araştırma becerilerini örnek olarak öğretmek, göstermektir. onlara ömür boyu yiyecek yetiştirmeyi öğretiyorlar.

## Konuyla ilgili diğer kaynaklar

Kişisel bilgisayarların, Unix'in ve İnternet'in nasıl çalıştığına ilişkin temel bilgiler konusunda eğitime ihtiyacınız varsa, bkz. [Unix ve İnternetin Temelleri NASIL](http://en.tldp.org/HOWTO/Unix-and-Internet-Fundamentals-HOWTO) /).

Yazılımı yayınladığınızda veya yazılım için yamalar yazarken, [Yazılım Sürümü Uygulaması NASIL](http://en.tldp.org/HOWTO/Software-Release-Practice-HOWTO/index.html) belgesindeki yönergeleri izlemeye çalışın.

## Teşekkür

Evelyn Mitchell bazı örnek aptal sorulara katkıda bulundu ve "Nasıl İyi Bir Cevap Verilir" bölümüne ilham verdi. Mikhail Ramendik iyileştirmeler için bazı özellikle değerli önerilerle katkıda bulundu.
