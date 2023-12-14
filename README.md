# debitsystem
## İÇERİĞİ
Bir organizasyonun demirbaş varlıklarını etkin bir şekilde yönetebilmesi için çalışanların üzerine zimmetlenen demirbaşların listesinin tutulduğu ve bu listeye kolayca erişim sağlanan bir web uygulaması tasarlamak gerekmektedir. 
## GEREKSİNİMLER
Problemin Ana Unsurları: Demirbaş Kaydı ve Takibi: Uygulama, organizasyon içerisindeki her bir demirbaşın (örneğin, bilgisayarlar, mobilyalar, cihazlar) ayrıntılarını (adı, seri numarası, modeli, alım tarihi, maliyeti vb.) kaydetmeli ve güncellemelidir.

Çalışan Bilgileri Yönetimi: Uygulama, organizasyon içindeki her bir çalışanın (adı, pozisyonu, departmanı vb.) bilgilerini kaydedebilmeli ve gerektiğinde güncelleyebilmelidir. 

Zimmetleme İşlemleri: Çalışanlar demirbaşları üzerlerine zimmetleyebilmelidir. Bu işlem sırasında demirbaşın hangi çalışana ait olduğu ve hangi tarihte zimmetlendiği kaydedilmelidir. Zimmet Çözme İşlemleri: Çalışanlar demirbaşları üzerlerinden çözebilmelidir. Bu durumda 
demirbaşın zimmeti çözülen çalışana veya depoya geri döndüğüne dair kayıtlar güncellenmelidir.

Demirbaş Listesi Görüntüleme: Uygulama, demirbaşların anlık bir listesini sunabilmelidir. Bu liste üzerinde filtreme ve arama gibi işlevlerle istenilen demirbaşların hızlıca bulunabilmesi sağlanmalıdır. 
Raporlama: Uygulama, belirli bir tarih aralığındaki demirbaş hareketlerine (zimmetleme, zimmet çözme) dair raporlar üretebilmelidir. Bu raporlar yöneticilere veya ilgili birimlere sunulabilir. 

Kullanıcı Yetkilendirmesi: Kullanıcılar, sadece yetkili oldukları alanlara (örneğin, sadece kendi departmanlarının demirbaşlarına) erişim sağlayabilmelidir. Bu, gizliliği ve güvenliği sağlamak için önemlidir. 

Veri Güvenliği: Uygulama, demirbaş ve çalışan bilgilerini güvenli bir şekilde saklamalı ve yetkisiz erişime karşı korumalıdır. 

Kullanıcı Dostu Arayüz: Uygulama, kullanıcıların kolayca demirbaşları yönetebileceği, bilgileri güncelleyebileceği ve raporlara erişebileceği kullanıcı dostu bir arayüz sunmalıdır. 

![image](https://github.com/xryal/debitsystem/assets/81656700/17eced3c-f1ae-4952-b36c-d74801cc3bec)

![image](https://github.com/xryal/debitsystem/assets/81656700/6c77f2b8-7ec0-4382-a2d8-bab76f7ef87f)

## RELATIONS

![image](https://github.com/xryal/debitsystem/assets/81656700/75451640-4fed-4ede-be7f-15af2e3cc4a5)

## MİMARİ

![image](https://github.com/xryal/debitsystem/assets/81656700/9d0e84be-3df9-451b-8e4a-a6b02e1ccf82)

Katmanlı mimariyi tercih etmemin nedeni, projenin sağlamlığı, sürdürülebilirliği ve geliştirme süreçlerinin etkin yönetimi için stratejik bir yaklaşım olmasını gözlemlemekteyim. Bu mimari yaklaşım, aşağıdaki nedenlerle projenin başarılı bir şekilde yönetilmesine ve uzun vadede değer sağlamasına yardımcı oluyor.

Katmanlı mimari, ilk olarak sağladığı modülerlik sayesinde projenin farklı işlevlerini mantıklı ve bağımsız bileşenlere ayırmamı sağlıyor. Bu sayede, değişikliklerin belirli bir katmanda yapılması diğer katmanları etkilemeksizin mümkün oluyor. Bu modüler yapının yanı sıra, her bir katmanın belirli bir sorumluluğu olduğundan sorumluluk ayrımı da daha net oluyor. 

Ayrıca, katmanlı mimari projenin bakım ve geliştirme süreçlerini optimize ediyor. Örneğin, iş mantığını değiştirmek gerektiğinde, bu katmanda yapılan güncellemeler diğer katmanları etkilemiyor ve bu da hataların yayılmasını engelliyor. Bu da bize yüksek cohesion ve düşük coupling imkanı veriyor ve uzun vadede projenin daha sürdürülebilir olmasını sağlıyor. 

Projemizin karmaşıklığı arttıkça, katmanlı mimari projenin daha iyi ölçeklenebilirlik sunmasına yardımcı oluyor. Veri tabanı, iş mantığı ve kullanıcı arayüzü gibi farklı katmanları bağımsız olarak ölçeklendirebiliyoruz. Bu sayede yüksek trafikli uygulamalarda da performansı sağlayabiliriz. Katmanlı mimari aynı zamanda, farklı ekiplerin aynı anda çalışmasını kolaylaştırarak işbirliğini artırıyor. Her katman kendi başına geliştirilebildiği için, front-end, back-end ve veri tabanı ekipleri aynı projede sorunsuzca işlerini yapabilirler.
Sonuç olarak, katmanlı mimari, projemizin daha yönetilebilir, sürdürülebilir ve ölçeklenebilir olmasını sağlayarak uzun vadede değer katmayı hedefliyor. Bu mimari yaklaşımın projemize sağladığı modülerlik, sorumluluk ayrımı, bakım kolaylığı ve işbirliği fırsatları, proje hedeflerimize daha etkin bir şekilde ulaşmamıza yardımcı oluyor.

## YAZILIM İÇERİSİNDEN GÖRÜNTÜLER

## ![1](https://github.com/xryal/debitsystem/assets/81656700/fae5cff9-dbeb-426e-a2e4-cce3d7b7445d)


## ![2 (2)](https://github.com/xryal/debitsystem/assets/81656700/c6a9f56d-c36d-400f-9784-a0dea915ab3e)


## ![3](https://github.com/xryal/debitsystem/assets/81656700/e1a1e808-f2bc-4bb2-8b28-c3c71feee2fe)


## ![4](https://github.com/xryal/debitsystem/assets/81656700/65981d87-0a6e-4e18-8d81-9be8bc6de03b)


## ![5](https://github.com/xryal/debitsystem/assets/81656700/70fb72f4-6cfa-47b0-bc23-d9ff1211915c)

## ![6](https://github.com/xryal/debitsystem/assets/81656700/7425fd06-b95b-4cec-bd10-50816018c533)

## ![7](https://github.com/xryal/debitsystem/assets/81656700/b7abf4dd-cc3f-42e5-a6d8-85a2199466e3)






