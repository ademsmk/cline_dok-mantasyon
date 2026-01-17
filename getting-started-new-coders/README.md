# Cline ile Başlangıç ​​| Yeni Kodlayıcılar

Cline'a hoş geldiniz! Bu kılavuz, kurulumunuzu yapmanıza ve ilk projenizi oluşturmak için Cline'ı kullanmaya başlamanıza yardımcı olacaktır.

## İhtiyacınız Olanlar

Başlamadan önce şunlara sahip olduğunuzdan emin olun:

- **VS Code:** Ücretsiz, güçlü bir kod editörü.

- [VS Code'u İndirin](https://code.visualstudio.com/)
- **Geliştirme Araçları:** Kodlama için gerekli yazılımlar (Homebrew, Node.js, Git, vb.).

- Bunları Cline'ın yardımıyla kurmak için [Temel Geliştirme Araçlarını Kurma](installing-dev-essentials.md) kılavuzumuzu izleyin (burada kurulumu tamamladıktan sonra).

- Cline, ihtiyacınız olan her şeyi kurmanızda size rehberlik edecektir.
- **Cline Projeleri Klasörü:** Tüm Cline projeleriniz için ayrılmış bir klasör.

- macOS'ta: Belgeler klasörünüzde "Cline" adında bir klasör oluşturun
- Yol: `/Users/[kullanıcı-adınız]/Documents/Cline`

- Windows'ta: Belgeler klasörünüzde "Cline" adında bir klasör oluşturun

- Yol: `C:\Users\[kullanıcı-adınız]\Documents\Cline`

- Bu Cline klasörünün içinde, her proje için ayrı klasörler oluşturun
- Örnek: Egzersiz takip uygulaması için `Documents/Cline/workout-app`
- Örnek: Portfolyonuz için `Documents/Cline/portfolio-website`
- **VS Code'da Cline Uzantısı:** VS Code'a yüklenen Cline uzantısı.

## Adım Adım Kurulum

Cline'ı çalışır hale getirmek için şu adımları izleyin:

1. **VS Code'u Açın:** VS Code uygulamasını başlatın. VS Code "Çalışan uzantılar..." gösteriyorsa, "İzin Ver"e tıklayın.

2. **Cline Klasörünüzü Açın:** VS Code'da, Belgeler'de oluşturduğunuz Cline klasörünü açın.

3. **Uzantılara Gidin:** VS Code'un yan tarafındaki Etkinlik Çubuğunda Uzantılar simgesine tıklayın.

4. **'Cline' Araması Yapın:** Uzantılar arama çubuğuna "Cline" yazın.

5. **Uzantıyı Yükleyin:** Cline uzantısının yanındaki "Yükle" düğmesine tıklayın.

6. **Cline'ı Açın:** Yüklendikten sonra, Cline'ı birkaç şekilde açabilirsiniz:

- Etkinlik Çubuğundaki Cline simgesine tıklayın.

- Komut paletini (`CMD/CTRL + Shift + P`) kullanın ve Cline'ı düzenleyicinizde bir sekme olarak açmak için "Cline: Yeni Sekmede Aç" yazın. Daha iyi bir görünüm için bu önerilir.

- **Sorun Giderme:** Cline simgesini görmüyorsanız, VS Code'u yeniden başlatmayı deneyin.
- **Görecekleriniz:** VS Code düzenleyicinizde Cline sohbet penceresinin göründüğünü görmelisiniz.

![gettingStartedVsCodeCline](https://github.com/user-attachments/assets/622b4bb7-859b-4c2e-b87b-c12e3eabefb8)

## OpenRouter API Anahtarını Kurma

Cline'ı kurduktan sonra, Cline'ın tüm özelliklerini kullanmak için OpenRouter API anahtarınızı kurmanız gerekecek.

1. **OpenRouter API Anahtarınızı Alın:**

- [OpenRouter API Anahtarınızı Alın](https://openrouter.ai/)
2. **OpenRouter API Anahtarınızı Girin:**

- Cline uzantısındaki ayarlar düğmesine gidin.

- OpenRouter API anahtarınızı girin.

- Tercih ettiğiniz API modelini seçin.

- **Kodlama İçin Önerilen Modeller:**

- `anthropic/claude-3.5-sonnet`: Kodlama görevleri için en çok kullanılan model.

- `google/gemini-2.0-flash-exp:free`: Kodlama için ücretsiz bir seçenek.

- `deepseek/deepseek-chat`: ÇOK UCUZ, neredeyse 3.5 sonnet kadar iyi.

- [OpenRouter Model Sıralamaları](https://openrouter.ai/rankings/programming)

## Cline ile İlk Etkileşiminiz

Artık Cline ile bir şeyler geliştirmeye hazırsınız. İlk proje klasörünüzü oluşturalım ve bir şeyler yapalım! Aşağıdaki komutu Cline sohbet penceresine kopyalayıp yapıştırın:

``` `Merhaba Cline! Cline dizinimde "hello-world" adında yeni bir proje klasörü oluşturmama ve büyük mavi yazı tipiyle "Merhaba Dünya" yazan basit bir web sayfası yapmama yardımcı olabilir misin?

``` ```

**Neler Göreceksiniz:** Cline, proje klasörünüzü oluşturmanıza ve ilk web sayfanızı kurmanıza yardımcı olacaktır.

## Cline ile Çalışma İpuçları

- **Sorular Sorun:** Bir şeyden emin değilseniz, Cline'a sormaktan çekinmeyin!

- **Ekran Görüntüleri Kullanın:** Cline görüntüleri anlayabilir, bu nedenle üzerinde çalıştığınız şeyi ona göstermek için ekran görüntüleri kullanmaktan çekinmeyin.

- **Hataları Kopyala ve Yapıştır:** Hatalarla karşılaşırsanız, hata mesajlarını Cline'ın sohbetine kopyalayıp yapıştırın. Bu, sorunu anlamasına ve bir çözüm sunmasına yardımcı olacaktır.

- **Basitçe Konuşun:** Cline, basit, teknik olmayan dili anlamak üzere tasarlanmıştır. Fikirlerinizi kendi kelimelerinizle anlatmaktan çekinmeyin ve Cline bunları koda çevirecektir.

## Sıkça Sorulan Sorular

- **Terminal Nedir?** Terminal, bilgisayarınızla etkileşim kurmak için metin tabanlı bir arayüzdür. Çeşitli görevleri gerçekleştirmek için komutlar çalıştırmanıza olanak tanır; örneğin paket yükleme, komut dosyaları çalıştırma ve dosyaları yönetme. Cline, komutları yürütmek ve geliştirme ortamınızla etkileşim kurmak için terminali kullanır.

- **Kod Tabanı Nasıl Çalışır?** (Bu bölüm, yeni kodlayıcılardan gelen yaygın sorulara göre genişletilecektir)

## Hala Zorlanıyor musunuz?

Bana ulaşmaktan çekinmeyin, Cline ile başlamanıza yardımcı olacağım.

nick | 608-558-2410

Discord topluluğumuza katılın: [https://discord.gg/YmtKFD2f](https://discord.gg/YmtKFD2f)
