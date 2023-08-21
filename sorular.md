# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular


1. Git nedir?

Git, yazılım geliştirme süreçlerinde kullanılan bir versiyon kontrol sistemidir.

2. Git ile GitHub arasında ne fark var?

Git, bir versiyon takip yazılımıdır. Lokal olarak bilgisayarda çalışır ve github olmadan da Git'i kullanmak mümkündür
Github ise Git repository'lerinin cloud üzerinde saklandığı online bir servistir.Online bir servistir ve offline olarak kullanabilmemiz mümkün değildir.




3. Neden bir branch oluşturuyoruz?

Kullanıcının çalıştığı projenin farklı versiyonlarına erişmesini sağlar.

4. Pull Request'in amacı nedir?

Açık kaynaklı projelere katkıda bulunmak isteyen kullanıcıların, projenin sahibine yaptıkları değişiklikleri inceletmek üzere yaptığı bir taleptir.



5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?

git checkout komutudur. git checkout master komutuyla master'ı geçtikten sonra git merge isim-soyisim komutuyla master'a geçerim

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.

Değişiklikler ile ilgili bilgileri edinmek için fetch, değişiklikleri local branch'inize entegre etmek için merge her ikisinide yapmak için pull komutu kullanılır.

7. Merge conflict nedir?

İki kişi aynı dosyayı ve aynı satırı değiştirirse ve git otomatik olarak merge edemezse bu durumda conflict yani çakışma olacaktır. 

8. Merge conflict'i nasıl çözeriz?

Bu durumda, Git conflict bildirir ve kullanıcının bu çatışmayı manuel olarak çözmesini ister. Git conflict çözmek için, kullanıcının ilk olarak dosyayı açması ve çatışmalı bölümleri bulması gerekir. Daha sonra, çatışmalı bölümleri manuel olarak düzenlemek ve Git'e tekrar birleştirme işlemini yapması gerekir.

