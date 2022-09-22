# YETGEN-JUMP-PYHTON-PROJE
Selamlar, biz Yetgen Jump Python eğitiminden Takım-21. Adlarımız Nisa Özturhan, Nurefşan
Altın, Zeynep Kocaahmet ve Eda Tosun. Proje haftası gelip projeler açıklandığında; ilk olarak
hazır olan projeleri mi yoksa kendi belirleyeceğimiz projeyi mi yapmak isteriz diye bir
toplantı gerçekleştirdik. Ve süreç içinde kendi seçtiğimiz proje üzerinden ilerledik.

Projemizi seçerken gerçek hayatta işlerimizi kolaylaştıran programlar ve algoritmalar
üzerinden yola çıktık, bunlara; otel rezervasyonu, Getir’den sipariş oluşturma gibi örnekler
verebiliriz. Beyin fırtınası yaptıkça ortaya çok güzel fikirler çıktı, daha sonra bunları not alıp
"nasıl yapılır" diye düşünmeye ve bazı seçenekleri elemeye başladık. Karar kıldığımız proje;
günümüzde çok sık kullanılan ve internet üzerinden sipariş oluşturmanıza yarayan bir
program. Sayı arttırılabilir fakat biz pizzalar, hamburgerler, tatlılar ve içecekler olmak üzere
dört kategori belirledik. Kullanıcı programı açtığında menü sayfasından istediği kategoriyi
seçiyor ve sepetini oluşturmaya başlıyor.

Programımızın sunduğu bazı gelişmiş seçenekler var: Pizza veya hamburger alacak kullanıcı
için programı ek seçeneklerle zenginleştirdik. Örneğin bir pizza size çok lezzetli göründü ama
içerisinde bulunan bir ürüne alerjiniz var ya da onu sevmiyorsunuz. Program size bu ürün
çıkarma opsiyonu sunuyor. Benzer şekilde ekleme yapabiliyor ya da seçiminizden
memnunsanız pas geçip ana menüye tekrar dönebiliyorsunuz. Bu kısım programın en
hoşlandığımız ve bizi en çok zorlayan noktalarından biri oldu. Ama kullanıcıya daha gelişmiş
bir deneyim sunmayı hedefledik.

Kodumuzda çeşitli döngüleri defalarca kullandık ve pek çok fonksiyon oluşturduk. Örneğin
ürün ekleme çıkarmada while döngüsünü kullandık ve bu sayede kullanıcıya istediği kadar
ekleme ve çıkarma yapma imkanı sunmuş olduk. Pizza, hamburger, tatlı ve içecekler olmak
üzere dört farklı kategori için farklı fonksiyonlar oluşturduk. “pizza_islemleri" adlı fonksiyon
kullanıcıdan input alarak istediği pizzayı seçmesini sağlıyor ve malzemeler üzerinde değişiklik
yapma imkanı tanıyor.

Aynı zamanda bir projenin, yazılmaya başladıktan sonra kafamızdaki ilk haliyle kalmadığını
gördük. Satır satır yazdıkça programa yeni fikirler ve özellikler eklendi. Çünkü satırları
çalıştırdıkça bazı problemleri ya da “şu olsa daha iyi olurdu” denilen noktaları fark ettik.
Örneğin “Eğer kullanıcı bir değil birkaç içerik eklemek ya da çıkartmak isterse, programımız
bunu da yapabilmeli” diye düşünüp, yol aramaya başladık. Söz konusu içerikleri bir listede
topladık ve kullandığımız döngü aracılığıyla liste içindeki elemanları expend veya remove
ettik.

Aramızda “kod mümkün olduğunca sade, açık olsun ki, kodumuzu tekrar açtığımızda ne
yaptığımızı kolayca görebilelim, rahat okuyabilelim” gibi konuşmalar geçti, süreçte buna da
dikkat ettik.

Bazı ihtiyaç duyduğumuz özellikler için araştırma yaparken kütüphanelere rastladık. Örneğin
hata kontrol sistemlerinin bir yöntemi olan “try-except” çalıştırmak için “from logging import
exception” komutunu kullanmalısınız.

Class yapısına gelirsek; ürün fiyatları ve ürün adlarının bulunduğu bir dictionary ile sunulan
ürünlerin içeriğinin bulunduğu bir liste tanımladık. Daha sonra pizza_islemleri fonksiyonu
içinde bu iki yapıyı zip metoduyla birleştirerek kullanıcının ürün adı, fiyatı ve içeriğini aynı
satırda görmesini sağladık.

Bundan sonraki işlemler için bazı noktalarda list() metodunu ve keys fonksiyonunu kullandık.
Bundaki amacımız ürünlerin adlarına erişebilmek ve onlar üzerinde işlem yapabilmekti.
İleride yemek sipariş programı geliştirmek isteyen kişilere iyi bir kaynak olduğunu
düşünüyoruz.
