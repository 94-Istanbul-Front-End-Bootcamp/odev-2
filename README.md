# Ödev 2

## Özet açıklama:
Hafta 2 Gün 2 örneğindeki filtre özelliğini geliştirmeniz beklenmektedir.
İlgili repo ve branch'e aşağıdaki link ile ulaşabilirsiniz.
https://github.com/94-Istanbul-Front-End-Bootcamp/examples-in-lessons/tree/hafta-2-gun-2

## Filtreleme seçenekleri: 
    * Reşit olan kullanıcıları listlemek.
        - Checkbox kullanılmalı.
    * Aktif durumda olan kullanıcıları listelemek.
        - Checkbox kullanılmalı.
    * İsim baş harfine göre filtreleme: 
        - Kullanıcıların isimlerinin baş harflerine göre filtreleme yapılabilmeli.
        - İsim filtrelemesi için bir adet text input kullanılmalı.
        - Text input max karakter sayısı 1 olmalı.
            - Kaynak: https://www.w3schools.com/tags/att_input_maxlength.asp
        - Input'a placeholder eklenmeli.
        - Girilen harf, kullanıcıların isimlerinin baş harfleri ile kıyaslanmalı.
            - Bir string'in baş harfini seçebilmek için birden fazla javascript string fonksiyonu mevcuttur, istediğiniz fonksiyonu kullanabilirsiniz. (charAt, substring, slice)

Checkbox kullanımı için kaynak: 
https://www.w3schools.com/howto/howto_js_display_checkbox_text.asp

## Kurallar:
    - Tüm değişiklikler, derste tanımladığımız filterData fonksiyonunu tetikleyen butona tıklandığında gerçekleşmelidir.
    Yani kullanıcı öncelikle checkbox'lar veya isim filtrelemesi için sunulmuş text input üzerinde değişiklikler yapmalı, sonrasında da filtrele butonuna tıklamalıdır. Checkbox'lar tikli değilse ve text input boş işe hiçbir işlem yapılmamalıdır.

    - Eğer veri okuma sırasında bir hata ile karşılaşılırsa kullanıcıya alert ile "Bir hata oluştu!" mesajı gösterilecektir.
    (try catch)
    Kaynak: https://www.w3schools.com/jsref/met_win_alert.asp

## İsterlerin tam olarak anlaşılabilmesi için kullanıcı gözünden bir senaryo adım adım aşağıda belirtilmiştir.
- Kullanıcı sayfa yüklendiğinde sadece "Getir" butonunu görecektir.
- Getir butonu tıklandığında veri, json dosyasından okunur ve ilgili "ul" tag'inin içerisine, her bir user verisi bir liste olacak şekilde ve "li" tag'i içerisinde bir HTML elementi olarak dönülür.
- Kullanıcı veriler ile birlikte aynı zamanda filtreleme seçeneklerini de görebilecektir.
* (Buraya kadar olan kısım derste yapılmıştır.)
- Filtreleme seçeneklerini istediği gibi değiştiren kullanıcı, "Filtrele" butonuna tıklayarak, filtrelenmiş verileri görebilecektir.
- Örnek filtreleme: 
    - Kullanıcı yaşa göre(reşit olanlar) filtrele checkbox'ını     checked yapar.
    - Kullanıcı isim filtrelemesi için text input'a "A"harfini    girer.
    - Kullanıcı filtrele butonuna tıkladığında yaptığı seçimlere   uygun verileri listeler.
    - Bu durumda kullanıcı 18 yaşından büyük ve isminin baş harfi "A"    olan kişileri listelemiş olur.


Style konusu size kalmış, sayfayı istediğiniz şekilde tasarlayabilirsiniz.
