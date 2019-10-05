::: warning Nedir?
Bu site, **Eric Steven Raymond** tarafından yazılan, Türkçe çevirisi **Yalçın Kolukısa**, **Osman Yüksel** ve **Necdet Yücel** tarafından yapılan ["How To Ask Questions The Smart Way"](http://www.catb.org/~esr/faqs/smart-questions.html) metninin alternatif bir yansısıdır. [GNU GPL](https://en.wikipedia.org/wiki/GNU_General_Public_License)'e sadık kalınarak mobil cihazlarla uyumluluk, kolay okunabilirlik gibi endişelerle [Türkçe çevirisinden](http://docs.comu.edu.tr/howto/smart-questions.html) kopyalanmıştır. Kaynak kodlarına GitHub'daki [şu depodan](http://github.com/tugsanunlu/nasil-akillica-soru-sorulur) ulaşılabilir. 
:::

### Nasıl Akıllıca Soru Sorulur?
---

|Yazan|Site|E-Posta Adresi|
|:---|:---|:---|
|Eric Steven Raymond|[Thyrsus Enterprises](http://www.catb.org/~esr/)|<esr (at) thyrsus.com>|
|Rick Moen|[Linux Mafia](http://linuxmafia.com/~rick/)|<rick (at) linuxmafia.com>|

|Çeviren|E-Posta Adresi|
|:---|:---|
|Necdet Yücel|<nyucel (at) comu.edu.tr>|
|Osman Yüksel|<yuxel (at) sonsuzdongu.com>|
|Yalçın Kolukısa|<yalcin (at) belgeler.org>|

**Bu çevirinin sürüm bilgileri:**
|Gelişim|Tarih|Çevirmenler|
|:---|:---|:---|
|Sürüm 1.2: Özgün belgenin 3.6 sürümüne güncellendi.|Ekim 2008|Necdet Yücel|
|Sürüm 1.1: Özgün belgenin 3.2 sürümüne güncellendi.|Mayıs 2006|Necdet Yücel|
|Sürüm 1.0: İlk çeviri.|Şubat 2004|Osman Yüksel, Yalçın Kolukısa|

**Özgün belgenin sürüm bilgileri:**
|Gelişim|||
|:---|---|---|
|Sürüm 3.6: Küçük güncellemeler ve yeni bağlantılar|19 Mart 2008|esr|

Telif Hakkı © 2006-2008 Necdet Yücel (Türkçe çeviri 1.1 ve 1.2 sürümleri)

Telif Hakkı © 2004 Osman Yüksel ve Yalçın Kolukısa (Türkçe çeviri 1.0 sürümü)

Telif Hakkı © 2001-2006 Eric S. Raymond, Rick Moen

### Özet

[Üstatların](http://docs.comu.edu.tr/howto/hacker-howto.html) dünyasında, sormuş olduğunuz teknik sorulara aldığınız cevaplar, cevap verilirken karşılaşılan zorluğa bağlı olduğu kadar sizin soruyu nasıl sorduğunuza da bağlıdır. Bu kılavuz size tatmin edici bir cevap alabilmeniz için nasıl soru sormanız gerektiğini öğretecektir.

Çeviriler: [Almanca](http://www.tty1.net/smart-questions_de.html), [Bahasa Endonezya Dili](http://bulsara.host.sk/index.php?p=2005), [Brezilya Portekizcesi](http://www.istf.com.br/perguntas/), [Çince](http://www.lat30n.cn/doc/oss/smart-questions.html), [Çekçe](http://www.stare.cz/otazky.html), [Danca](http://www.usenet.dk/netikette/udvdebatteknik.html), [Estonyaca](http://linux.ee/~kala/smart-questions.html), [Fince](http://lumpio.no-ip.com/fiksut-kysymykset.html), [Fransızca](http://www.gnurou.org/documents/smart-questions-fr.html), [Gürcüce](http://maxo127.narod.ru/Geo/Articles/smart-questions_ge.html), [Hollandaca](http://docs.jaspervries.nl/smart-questions/), [İbranice](http://www.penguin.org.il/essays/smart-questions-he.html), [İspanyolca](http://www.sindominio.net/ayuda/preguntas-inteligentes.html), [İsveçce](http://se.linux.org/dokumentation/artiklar/kunskap/smartafragor) [İtalyanca](http://xoomer.virgilio.it/army1987k), [Japonca](http://www.ranvis.com/articles/smart-questions.ja.html), [Lehçe](http://rtfm.killfile.pl/), [Macarca](http://www.no.info.hu/~kryss/gnu/esr/smart-questions_hu.html), [Portekizce](http://www.celiojunior.com.br/comofazerperguntas.htm), [Romence](http://wiki.lug.ro/mediawiki/index.php/Cum_se_pun_%C3%AEntreb%C4%83ri_%C3%AEn_mod_inteligent), [Rusça](http://www.linuxrsp.ru/artic/smart-questions-ru.html), [Sırpça](http://solair.eunet.yu/~fangorn/smart_questions/smart-questions.sr.html), [Tayca](http://wiki.opentle.org/Smart-questions), [Türkçe](http://docs.comu.edu.tr/howto/smart-questions.html), [Yunanca](http://www.dionyziz.com/howto-smart-questions-gr/). Belgenin ingilizce orjinaline [buradan](http://www.catb.org/~esr/faqs/smart-questions.html) ulaşabilirsiniz. Eğer bu belgeden alıntı yapmak, kopyalamak, yansılamak veya çevirmek istiyorsanız, [lütfen kopyalama şartlarına](http://www.catb.org/~esr/copying.html) gözatınız.

### Rica

Pek çok projenin İnternet sitesindeki nasıl yardım bulunacağını anlatan kısımlarda, bu kılavuza bağ verilmiştir. Bu çok iyi, zaten amaçımızda buydu ama lütfen vermiş olduğunuz bağın yanına küçük bir not iliştirin: **Biz sizin projenizin destek bölümü değiliz!**

Bu tür bir uyarı olmadığı durumlarda, bazı gerizekalılar, bizim bu tür bir kılavuz yazmakla, bütün dünyanın teknik problemlerini çözmeyi iş edindiğimizi sanmaktadır. Bunu oldukça zor yoldan, defalarca rahatsız edilerek öğrendik.

Bu kılavuzu yardıma ihtiyacınız olduğu için okuyorsanız ve bu belgenin yazarlarından sorunuzun cevabını alıp gidebileceğinizi düşünüyorsanız, siz de gerizekalının birisiniz demektir. Bize soru sormayın. Sorularınızı görmezden geleceğiz. Biz burada, size başınız derde girince nasıl yardım alabileceğinizi söylemek için bulunuyoruz; sizin donanımlarla ve yazılımlarla olan problemlerinizi çözmek için değil. Yazarlarımızdan birisinin, ilgilendiğiniz konu hakkında uzman olduğundan emin değilseniz, lütfen bizi rahat bırakın. Böylece herkes mutlu olsun.