Otonom Araç Navigasyon Güvenlik Modülü
​Bu proje, otonom araçların iki farklı engel sınıfı arasından en güvenli şekilde geçmesini sağlayan bir Doğrusal Ayrıştırıcı (Linear Separator) algoritması içermektedir. Projenin temel amacı, sadece sınıfları birbirinden ayırmak değil, her iki sınıfa olan uzaklığı maksimize ederek en geniş "güvenlik koridorunu" oluşturmaktır.
​🚀 Projenin Amacı
​İki boyutlu düzlemde tanımlanmış engellerin koordinatlarını kullanarak, bu engelleri birbirinden en güvenli (optimum) sınır çizgisi ile ayıran matematiksel modeli tasarlamak ve analiz etmektir.
​🛠️ Teknik Özellikler
​Algoritma: Perceptron tabanlı doğrusal sınıflandırma ve ağırlık optimizasyonu.
​Dil: C++ (Modern standartlara ve OOP prensiplerine uygun).
​Mimari: Veri yapıları ve algoritma mantığı birbirinden izole edilerek temiz kod (clean code) ilkeleri uygulanmıştır.
​Bellek Yönetimi: Dinamik bellek kullanımı yerine C++ standart kütüphane yapıları (std::vector) tercih edilerek bellek sızıntıları önlenmiştir.
​📈 Karmaşıklık Analizi (Big-O)
​Eğitim (Training): O(E \cdot N)
(E: İterasyon/Epoch sayısı, N: Veri seti boyutu)
​Karar Verme (Inference): O(1)
Otonom sistemlerde gerçek zamanlı tepki verebilmek için karar mekanizması sabit zamanda çalışmaktadır.
​📋 Nasıl Çalıştırılır?
​Herhangi bir C++ derleyicisi (Dev-C++, Visual Studio, GCC vb.) ile main.cpp dosyasını açın.
​Projeyi derleyin ve çalıştırın.
​Konsol ekranında, iki engel kümesi için hesaplanan Optimum Güvenlik Sınırı denklemini göreceksiniz.
