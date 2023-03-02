# netflix_datascience

# Proje Amacı 

Kaggle sitesinde bulduğum Netflix'teki içerikler hakkında değişik verileri tutan veri setini kullanarak birkaç veri görselleştirmesi yaptım. İlgili veri setine ulaşmak için [tıklayınız](https://www.kaggle.com/datasets/shivamb/netflix-shows?resource=download).

# Proje Süreci

İlk olarak gerekli kütüphaneleri aktif hale getirdim (import ettim). Daha sonrasında Kaggle'dan indirmiş olduğum ".csv" uzantılı veri setimi okuyup bir değişkene atadım. Ondan sonra da veri setimi inceledim ve bazı verilerin kayıp olduğunu fark ettim. Sayısal bir veri olmadığı için ortalama alarak veya benzeri bir uygulama ile boş verileri doldurmak yerine bütün boş girdi içeren verileri sildim.

Daha sonrasındaysa artık veri görüntüleme işlemlerine başladım. İlk olarak kayıt türüne göre içerik miktarını görüntülemek istedim. Çıkan sonuç: 

![Çıkan Sonuç](https://user-images.githubusercontent.com/97351958/222572833-d740e353-4c8a-4add-a73d-0be583ab5c86.png)

Ondan sonra da rating derecelerin göre yani "PG-13", "TV-MA" gibi içeriğin uygun olduğu kitleyi belirten etiketlere göre içerik miktarını görüntüledim. Çıkan sonuç:

![Çıkan Sonuç](https://user-images.githubusercontent.com/97351958/222573632-ae0efa36-a6a3-4acd-9fdd-b2d398ad4bce.png)

Ondan sonra da bu iki veri türü hakkında ortak bir görselleştirme yapma adına içerik ve reyting türüne göre içerik miktarını görselleştirdim. Çıkan sonuç:

![Çıkan Sonuç](https://user-images.githubusercontent.com/97351958/222574196-4001afad-554b-4ca9-85e7-96326c18bcea.png)

Bir sonraki aşamada da içerik türlerinin pasta grafiğini gösterdim. Çıkan sonuç: 

![image](https://user-images.githubusercontent.com/97351958/222574381-ad1e1e1b-61d1-4c39-b099-bbb51a838fee.png)

Bir başka pasta grafiğinde de reyting türlerine göre içerik miktarını gösterdim. Çıkan sonuç:

![image](https://user-images.githubusercontent.com/97351958/222574494-db2c370a-aed1-45c0-8c32-bc72d44f2d4b.png)

Son gösterim tarzı olarak da **WordCloud** kütüphanesinin sunmuş olduğu kelime bulutu haritasını kullanarak ülkelerin sahip olduğu film miktarına göre bir harita görselleştirdim. Çıkan sonuç:

![image](https://user-images.githubusercontent.com/97351958/222574772-07f9a13d-79a4-4ab0-8fc6-159dc64748c9.png)

En son olarak da projemi film yönetmenleri adlarının miktarına göre bir kelime bulutu haritası çizdirerek sonlandırdım. Çıkan sonuç: 

![image](https://user-images.githubusercontent.com/97351958/222575078-df482c31-7566-4482-98fb-8aa767fea967.png)
