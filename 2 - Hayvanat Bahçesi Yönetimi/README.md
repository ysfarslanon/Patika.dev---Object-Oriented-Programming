# Hayvanat Bahçesi Yönetimi UML Diyagramı
- Hayvanlar:
  - Atlar (atlar, zebralar, eşekler vb.),
  - Kedigiller (kaplanlar, aslanlar vb.),
  - Kemirgenler (sıçanlar, kunduzlar vb.) gibi gruplardaki türlerle karakterize edilir.

- Hayvanlar hakkında depolanan bilgilerin çoğu tüm gruplamalar için aynıdır.
  - tür adı, ağırlığı, yaşı vb.
- Sistem ayrıca her hayvan için belirli ilaçların dozajını alabilmeli => getDosage ()
- Sistem Yem verme zamanlarını hesaplayabilmelidir => getFeedSchedule ()
- Sistemin bu işlevleri yerine getirme mantığı, her gruplama için farklı olacaktır. Örneğin, atlar için yem verme algoritması farklı olup, kaplanlar için farklı olacaktır.

![Hayvanat Bahçesi Yönetimi UML Diyagramı](https://github.com/ysfarslanon/Patika.dev---Object-Oriented-Programming/blob/main/2%20-%20Hayvanat%20Bah%C3%A7esi%20Y%C3%B6netimi/Hayvanat%20Bah%C3%A7esi%20Y%C3%B6netimi.png?raw=true)
