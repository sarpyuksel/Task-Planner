# 🎯 Task Planner (Notion Style)

Tamamen tarayıcı üzerinde çalışan, Notion'ın minimalist tasarım dilinden ilham alan kişisel görev ve haftalık planlama uygulaması. 

Bu proje, karmaşık backend kurulumlarına ihtiyaç duymadan, modern frontend teknolojileri kullanılarak veri mimarisinin ve kullanıcı deneyiminin (UX) nasıl optimize edilebileceğini göstermek amacıyla geliştirilmiştir.

## 🔗 Canlı Demo
Uygulamayı hemen test etmek için: **[Live Demo: Task Planner](https://sarpyuksel.github.io/Task-Planner/)**

## ✨ Öne Çıkan Özellikler

- **Single Source of Truth Mimarisi:** Görevler ve haftalık plan arasındaki veri senkronizasyonu tek bir state üzerinden yönetilir. Planda yapılan bir değişiklik ana listeye anında yansır.
- **Native Drag & Drop (Sürükle-Bırak):** Görevler haftalık çizelgede gün içi veya günler arası HTML5 Drag & Drop API kullanılarak pürüzsüzce taşınabilir.
- **Side Peek (Detay Paneli):** Notion tarzı sağdan kayarak açılan görev detay paneli sayesinde ana bağlamdan kopmadan alt görevler (subtasks) düzenlenebilir.
- **Dinamik Kategorizasyon:** Kullanıcılar kendi kategorilerini oluşturabilir, sistem tarafından atanan pastel renklerle görsel hiyerarşi sağlanır.
- **Durum ve Öncelik Yönetimi:** Görevlere özel "Status" (Not Started, In Progress, Done) ve "Priority" etiketleri atanabilir.
- **Veri Kalıcılığı:** Sunucuya ihtiyaç duymadan tüm veriler tarayıcının `LocalStorage` alanında güvenle saklanır.

## 🛠️ Kullanılan Teknolojiler

- **Kütüphane:** React 18 (CDN üzerinden Hook mimarisi kullanılarak)
- **Stil / CSS:** Tailwind CSS
- **Veri Yönetimi:** LocalStorage API
- **Etkileşim:** HTML5 Drag and Drop API & React `useRef`
- **Derleme:** Babel (Standalone)

## 🚀 Kurulum ve Çalıştırma

Proje statik tek bir dosyadan oluştuğu için herhangi bir `npm install` veya sunucu kurulumu gerektirmez.

1. Repoyu bilgisayarınıza klonlayın:
   ```bash
   git clone [https://github.com/sarpyuksel/Task-Planner.git](https://github.com/sarpyuksel/Task-Planner.git)