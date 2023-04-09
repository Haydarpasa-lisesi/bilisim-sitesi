### Başlangıç

İyi bir commit atmak, kod katkılarınızın diğer geliştiriciler tarafından anlaşılır ve yönetilebilir olmasını sağlar. İşte iyi bir commit atmanız için bazı ipuçları:

- Commit mesajınızı açıklayıcı ve özlü tutun: Commit mesajınızda ne yaptığınızı açıklayın, neden yaptığınızı belirtin ve bunu birkaç kelimeyle yapın. Mesajlarınızın okunabilir ve anlaşılır olması, diğer geliştiricilerin kodunuzu yönetmesine yardımcı olur.

- Değişiklikleri mantıksal bir şekilde gruplayın: İlgili değişiklikleri bir arada tutun. Eğer birden fazla farklı değişiklik yaptıysanız, bunları mantıklı bir şekilde ayırarak ayrı commitlerde kaydedin.

- Kod düzeninizi ve stilinizi koruyun: Commitlerinizi olabildiğince okunaklı ve stil sahibi hale getirin. Kodunuzun yazım ve formatlama kurallarına uygun olduğundan emin olun.

- Etkilenebilecek diğer dosyaları kontrol edin: Değişikliklerinizin başka dosyaları etkileyip etkilemediğini kontrol edin. Böylece gerekli tüm değişiklikleri kaydedebilirsiniz.

- İyi bir commit mesajı yazın: İyi bir commit mesajı, commit'inizin ne yaptığını açıklayan ve diğer geliştiricilerin bu değişikliği kolayca anlamasına yardımcı olan bir açıklama olmalıdır. Mesajınız, kısa ve öz olmalı ve birinci tekil kişi yerine üçüncü tekil kişi kullanılmalıdır.




### commit Biçimi
- `feat`: Yeni bir özellik eklemek için
- `fix`: Bir hatayı ya da bug'ı düzeltmek için
- `style`: Sadece stil değişikliği varsa
- `refactor`: İçeriğe etki etmeyecek bir değişiklik varsa / örneğin gereksiz kullanılan bir divin kaldırılması

#### Örnek Commit

- feat:iletişim sayfasının ana kısmı eklendi

- fix: mobil versiyondaki yazıların küçülmeme sorunu düzeltildi.

- style: Resimler arasına boşluk eklendi

- refactor: Ana sayfada gereksiz kullanılan div kaldırıldı.

### Pull Request
- İyi bir pull request oluşturmak, projenize katkıda bulunmanın önemli bir parçasıdır. İşte iyi bir pull request oluşturmak için bazı ipuçları:

- Pull request açmadan önce değişikliklerinizi test edin: Değişikliklerinizi test edin ve her şeyin doğru çalıştığından emin olun. Bu, zaman kaybını önleyeceği gibi, proje sahipleri ve diğer geliştiriciler tarafından da takdir edilir.

- Pull request'inizi küçük tutun: Pull request'inizi, küçük ve sade tutun. Büyük pull request'ler, incelemeleri zorlaştırabilir ve projenin kararlılığını etkileyebilir.

- Açıklayıcı bir başlık ve açıklama yazın: Pull request'iniz için açıklayıcı bir başlık ve açıklama yazın. Başlık, diğer geliştiricilerin değişikliğin ne hakkında olduğunu anlamasına yardımcı olmalıdır. Açıklama, değişikliklerinizi daha ayrıntılı bir şekilde açıklamalı ve projenin genel amacına nasıl katkıda bulunduğunu belirtmelidir.

- Kodunuzu okunaklı ve stil sahibi hale getirin: Kodunuzu okunaklı ve stil sahibi hale getirin. Kodunuz, projenin stil ve yazım kurallarına uygun olmalıdır. Bu, diğer geliştiricilerin kodunuzu daha kolay anlamalarına yardımcı olur.

- Tartışmaya açık bir şekilde sorunlarınızı belirtin: Pull request'inizdeki sorunları tartışmaya açık bir şekilde belirtin. Eğer sorunlarınız varsa, diğer geliştiricilerin bu sorunları çözmesine yardımcı olacak şekilde açıklama yapın.

- Değişikliklerinizi belgeleyin: Değişikliklerinizi belgeleyin. Bu, diğer geliştiricilerin projenin genel gelişimine katkıda bulunmalarına yardımcı olabilir.

- İnceleme için bekleyin ve düzenlemeleri yapın: Pull request'iniz, proje sahipleri ve diğer geliştiriciler tarafından incelenecektir. İncelemeler sonrasında, yapmanız gereken düzenlemeleri yapın.

### Örnek Pull Request

Başlık: Navbar üzerindeki logo boyutunu güncelledim

Açıklama:

Bu pull request, navbar üzerindeki logo boyutunu güncelliyor. Önceki boyut oldukça küçüktü ve mobil cihazlar üzerinde okunması zordu. Yeni boyut, logo'nun daha görünür olmasını sağlıyor ve mobil uyumlu hale getiriyor.

Değişiklikler:

styles.css: Logo boyutu güncellendi.
index.html: Navbar'a yeni boyut için uygun alan eklendi.
Testler:

Değişiklikleri yerel ortamda test ettim. Logo boyutunun artık daha görünür olduğunu ve mobil cihazlar üzerinde de düzgün göründüğünü doğruladım.

Bu pull request, projeye değer katacağına inandığım bir değişiklik içeriyor. Gözden geçirip birleştirmenizi rica ediyorum. Teşekkürler.
