# 🎯 Task Planner (Notion Style)

Tamamen tarayıcı üzerinde çalışan, Notion'ın minimalist tasarım dilinden ilham alan kişisel görev ve haftalık planlama uygulaması. 

Bu proje, karmaşık backend kurulumlarına ihtiyaç duymadan, modern frontend teknolojileri kullanılarak veri mimarisinin ve kullanıcı deneyiminin (UX) nasıl optimize edilebileceğini göstermek amacıyla geliştirilmiştir.

## 🔗 Canlı Demo
Uygulamayı hemen test etmek için: **[Live Demo: Task Planner](https://sarpyuksel.github.io/Task-Planner/)**

## ✨ Öne Çıkan Özellikler

- **Single Source of Truth Mimarisi:** Görevler ve haftalık plan arasındaki veri senkronizasyonu tek bir state üzerinden yönetilir. 
- **Inline Editing (Satır İçi Düzenleme):** Tıpkı Notion'daki gibi görev başlıkları, detayları ve alt görevleri (subtasks) ekstra bir forma ihtiyaç duymadan doğrudan üzerlerine tıklanarak düzenlenebilir.
- **Gelişmiş Durum (Status) Yönetimi:** Haftalık plana eklenen aynı görevin farklı günlerdeki kopyaları birbirlerinden bağımsız olarak "In Progress" veya "Done" statülerinde yönetilebilir. 
- **Master Checkbox (Tümünü Bitir):** Ana görev tamamlandığında tek bir tıklama ile tüm alt görevler dahil olmak üzere görev havuzunda ve haftalık planda tamamen "Tamamlandı" olarak işaretlenir.
- **Native Drag & Drop (Sürükle-Bırak):** Görevler haftalık çizelgede gün içi veya günler arası HTML5 Drag & Drop API kullanılarak pürüzsüzce taşınabilir.
- **Side Peek (Detay Paneli):** Sağdan kayarak açılan görev detay paneli sayesinde ana bağlamdan kopmadan alt görevler düzenlenebilir.
- **Modern UX ve Animasyonlar:** Ayrıştırılmış CSS mimarisi ile kart hover (kalkma) efektleri, buton basma (tactile) hissiyatı ve yumuşak geçişli modallar (fade-in) entegre edilmiştir.
- **Veri Kalıcılığı:** Sunucuya ihtiyaç duymadan tüm veriler tarayıcının `LocalStorage` alanında güvenle saklanır.

## 🛠️ Kullanılan Teknolojiler

- **Kütüphane:** React 18 (CDN üzerinden Hook mimarisi kullanılarak)
- **Stil / Arayüz:** Tailwind CSS & Özel CSS3 Animasyonları
- **Veri Yönetimi:** LocalStorage API
- **Etkileşim:** HTML5 Drag and Drop API & React `useRef`
- **Derleme:** Babel (Standalone)

## 🚀 Kurulum ve Çalıştırma

Proje statik dosyalardan oluştuğu için herhangi bir `npm install` veya sunucu kurulumu gerektirmez.

1. Repoyu bilgisayarınıza klonlayın:
   ```bash
   git clone [https://github.com/sarpyuksel/Task-Planner.git](https://github.com/sarpyuksel/Task-Planner.git)