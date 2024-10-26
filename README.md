# Dijital Ajanda ve Görev Yöneticisi

Bu proje, günlük görevlerinizi planlayabileceğiniz ve yönetebileceğiniz, takvim ile entegre çalışan bir Dijital Ajanda ve Görev Yöneticisidir. Görevlerinizi kategorize edebilir, teslim tarihlerini belirleyebilir ve takvim üzerinde görüntüleyebilirsiniz. Bu, hem kişisel hem de iş amaçlı kullanılabilir ve esnek bir görev yönetim deneyimi sunar.

## İçindekiler
1. [Özellikler](#özellikler)
2. [Kullanılan Teknolojiler](#kullanılan-teknolojiler)
3. [Kurulum](#kurulum)
4. [Kullanım](#kullanım)
5. [Dosya Yapısı](#dosya-yapısı)

### Özellikler

- **Görev Yönetimi**: Görevlerin adını, teslim tarihini, kategorisini ve etiketlerini ekleyin.
- **Takvim Entegrasyonu**: Görevlerinizi takvimde tarih bazlı olarak görüntüleyin.
- **Kategori ve Etiketler**: Görevlerinizi kategorilere ayırarak daha düzenli yönetim sağlayın.
- **Görev Silme**: Görevlerinizi görev listesinden ve takvimden kolayca kaldırın.

### Kullanılan Teknolojiler

- **HTML**: Yapısal düzen ve içerik oluşturmak için.
- **CSS**: Görsel tasarım ve düzenlemeler için.
- **JavaScript & jQuery**: Dinamik işlevler, etkileşimler ve takvim entegrasyonu için.
- **FullCalendar Kütüphanesi**: Takvim görüntüleme ve görev entegrasyonu.

### Kurulum

1. Bu projeyi klonlayın:
   ```bash
   git clone https://github.com/kullanıcıadınız/dijital-ajanda.git
   ```
2. Proje dizinine gidin:
   ```bash
   cd dijital-ajanda
   ```
3. Proje dosyalarını açın ve `index.html` dosyasını bir tarayıcıda görüntüleyin.

### Kullanım

- **Görev Ekleme**: "Görev adı", "Teslim Tarihi", "Kategori" ve "Etiketler" alanlarını doldurun ve **Ekle** butonuna tıklayın.
- **Görev Silme**: Görev listesindeki silme butonuna tıklayarak görevi kaldırabilirsiniz; bu işlem aynı zamanda takvimden de görevi kaldıracaktır.
- **Takvim Görüntüleme**: Görevler otomatik olarak takvimde listelenir ve görevlerin tarihine göre sıralanır.

### Dosya Yapısı

- **index.html**: Ana HTML dosyası, görev yönetimi ve takvim entegrasyonu için temel yapıyı sağlar.
- **styles.css**: Uygulamanın tüm stil ve tasarım ögelerini içerir.
- **script.js**: Görev ekleme, takvim entegrasyonu ve etkileşim işlevlerini içerir.
