# 🏗️ n8n Architect Playbook

An open-source, prompt-driven learning framework and architectural playbook for mastering **n8n** automation using Claude.

![n8n](https://img.shields.io/badge/n8n-FF6D5W?style=for-the-badge&logo=n8n&logoColor=white)
![Claude](https://img.shields.io/badge/Claude_3-D97757?style=for-the-badge&logo=anthropic&logoColor=white)

## 📖 Proje Hakkında

Otomasyon araçlarını öğrenmek genellikle "sürükle ve bırak" eğitimlerinden ibarettir. Ancak sistemler büyüdükçe; hata yönetimi (error handling), modülerlik (sub-workflows) ve performans optimizasyonu gibi gerçek mühendislik standartlarına ihtiyaç duyulur.

**n8n Architect Playbook**, n8n'i sıradan bir kullanıcı gibi değil, bir **Yazılım Mimarı** disipliniyle öğrenmenizi ve kullanmanızı sağlayan yapay zeka (LLM) destekli bir çalışma ortamıdır. Claude'un "Projects" özelliğini kullanarak kendinize 7/24 hizmet veren uzman bir n8n mentoru yaratmanızı sağlar.

## 📂 Depo İçeriği (Proje Hafızası)

Bu repo, Claude'a bağlam (context) sağlamak için özenle hazırlanmış 4 temel dosyadan oluşur:

1. `ruleset.md`: Ekibinizin veya sizin n8n üzerinde uygulayacağınız mimari standartlar, kodlama kuralları ve isimlendirme (naming conventions) gelenekleri.
2. `learning_path.md`: Temel seviyeden başlayarak Agentic AI ve Multi-Agent sistemlere kadar uzanan teorik müfredat.
3. `n8n_practice_list.md`: Teoriyi pratiğe dökeceğiniz, basitten zora doğru sıralanmış laboratuvar görevleri.
4. `learning_experience.md`: Geliştirici günlüğünüz. Karşılaştığınız garip hatalar ("gotchas") ve aşılan kilometre taşları burada birikir.

## 🚀 Nasıl Kullanılır? (Kurulum)

Bu playbook'u kendi ortamınızda çalıştırmak için bir **Claude Pro** (veya Projects özelliğini destekleyen herhangi bir LLM arayüzü) hesabına ihtiyacınız var.

### Adım 1: Claude'da Proje Oluşturun
1. Claude arayüzünde sol menüden **Projects**'e gidin ve yeni bir proje oluşturun (Örn: `n8n Mastery`).
2. Proje ayarlarına (Project Instructions) gidin.
3. Bu repodaki [system_instructions.md](system_instructions.md) dosyasının içeriğini kopyalayıp Claude'un instruction bölümüne yapıştırın. *(Kendi hedeflerinize göre köşeli parantezli `[ ]` alanları özelleştirmeyi unutmayın).*

### Adım 2: Proje Hafızasını Yükleyin
1. Repodaki şu 4 dosyayı bilgisayarınıza indirin (veya klonlayın):
   - `ruleset.md`
   - `learning_path.md`
   - `n8n_practice_list.md`
   - `learning_experience.md`
2. Bu dosyaları Claude projenizin **Files** (Project Knowledge) bölümüne yükleyin.

### Adım 3: Öğrenmeye Başlayın!
Her şey hazır. Artık Claude'a gidip ilk mesajınızı atabilirsiniz:
> *"Başlıyoruz. Learning Path Phase 1'den başlayalım, n8n'in Array of Items yapısını bana bir yazılım mimarına anlatır gibi anlat."*

## 🔄 Çalışma Döngüsü (Workflow)

Bu playbook statik değildir, siz geliştikçe o da gelişir:

* **Pratik Yapın:** Bir konuyu öğrendikten sonra Claude size `n8n_practice_list.md` dosyasındaki ilgili görevi yapmanızı söyleyecektir.
* **Kuralları Güncelleyin:** Birlikte zor bir problemi çözdüğünüzde veya yeni bir mimari karar aldığınızda, Claude size `ruleset.md` veya `learning_experience.md` dosyalarını güncellemeniz için yeni markdown çıktıları verecektir.
* **Dosyaları Değiştirin:** Claude'un verdiği güncel çıktıları yerel bilgisayarınızdaki dosyalara kopyalayın ve Claude Project içindeki eski dosyalarla değiştirin. Böylece mentorunuz her zaman sizinle aynı bilgi seviyesinde kalır.

## 🤝 Katkıda Bulunma (Contributing)

Bu proje açık kaynaktır. Yeni n8n pratik görevleri (özellikle AI ve Advanced seviye için), yeni mimari kurallar veya geliştirilmiş sistem komutları eklemek isterseniz pull request'lerinizi (PR) bekliyoruz!

1. Repoyu forklayın.
2. Feature branch'inizi oluşturun (`git checkout -b feature/AmazingNewRule`).
3. Değişikliklerinizi commit edin (`git commit -m 'Add new rule for Webhook auth'`).
4. Branch'inize pushlayın (`git push origin feature/AmazingNewRule`).
5. Bir Pull Request açın.

---
*Mühendislik disipliniyle otomatize edilmiş günler dileriz! 🚀*
