ZexyWing — Gelişmiş ElytraTarget Hile Önleme Sistemi
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

ZexyWing, hava savaşı sırasında hile istemcisi kullanan oyuncuları yakalamak için tasarlanmış güçlü ve hafif bir Elytra odaklı hile önleme eklentisidir. Genel amaçlı hile önleme sistemlerinin aksine ZexyWing yalnızca elytra tabanlı hilelere odaklanır; genel eklentilerin kaçırdığı tespitleri derin ve hedefli biçimde yapar.

⚡ Tespit Modülleri
──────────────────────────────────────────────
▸ AimLock        — Birden fazla tick boyunca şüpheli açılarla hedefe kilitlenen oyuncuları tespit eder
▸ ElytraFollow   — Her iki oyuncu da havadayken mükemmel hız kopyalamasını yakalar
▸ Stalker        — Fişekle uçuş sırasında hassas mesafe koruyarak takibi bayraklar
▸ WingAura       — Görüş alanı dışındaki hedeflere yapılan vuruşları tespit eder
▸ Snap           — Anlık aimbot tarzı yaw (yatay dönüş) hamlelerini tanımlar
▸ SmoothAim      — Robotik sıfır-pitch hareket kalıplarını yakalar
▸ WingVariance   — Savaşta imkânsız sabit mesafe davranışını bayraklar
▸ ElytraTarget   — Tam elytra uçuş hareketi analizi (hız, havada asılı kalma, imkânsız virajlar)
▸ Reach          — Yüksek ping veya elytra uçuş ivmesinde bile imkânsız vuruş mesafelerini yakalar
▸ OverRun        — Uçuş momentumunu bozmadan, gidilen yönün tam tersine yapılan vuruşları yakalar

⚙️ Temel Özellikler
──────────────────────────────────────────────
▸ ProtocolLib Entegrasyonu    — Maksimum doğruluk ve sıfır gecikme için paket düzeyinde analiz
▸ Tekrar İzleme Sistemi       — Bayraklanan oyuncunun son 10 saniyesini oyun içinde izle
▸ Canlı İnceleme              — Herhangi bir çevrimiçi oyuncuyu anlık olarak takip et
▸ GUI Paneli                  — /zw gui komutuyla kolay yönetim için oyun içi arayüz
▸ Discord Webhook             — Oyuncu bayraklandığında anında Discord bildirimi
▸ Gecikmeli Ceza              — Ceza atlatmayı önlemek için ayarlanabilir tick tabanlı gecikmeli ceza
▸ Lag Koruması                — TPS eşiğin altına düştüğünde yanlış pozitifi önlemek için tespit durur
▸ Çoklu Dil Desteği           — Türkçe, İngilizce, Almanca, Rusça dil dosyaları
▸ Bypass İzni                 — Güvenilen yetkili/VIP oyuncular için bypass desteği
▸ Uyarı Geçmişi               — Oyuncu başına ayarlanabilir otomatik sıfırlamalı flag hafızası
▸ Güncelleme Denetleyici      — Sunucu başlangıcında otomatik güncelleme bildirimleri

Komutlar
──────────────────────────────────────────────
/zw help                — Yardım menüsünü göster
/zw reload              — Yapılandırma ve dil dosyalarını yeniden yükle
/zw status              — Modül durumlarını görüntüle
/zw gui                 — Yönetim arayüzünü aç
/zw alerts              — Kendi hile uyarılarını aç/kapat
/zw bypass <oyuncu>     — Bir oyuncu için bypass'ı aç/kapat
/zw clear <oyuncu>      — Bir oyuncunun flaglarını temizle
/zw inspect <oyuncu>    — Bir oyuncuyu canlı takip et
/zw replay <oyuncu>     — Oyuncunun son 10 saniyesini tekrar izle

Yetkiler
──────────────────────────────────────────────
zexywing.admin      — Tam eklenti erişimi (varsayılan: op)
zexywing.alerts     — Hile uyarı mesajlarını al (varsayılan: op)
zexywing.bypass     — Tüm tespitleri atla (varsayılan: false)
zexywing.replay     — Tekrar izleme sistemini kullan (varsayılan: op)
zexywing.inspect    — Oyuncuları canlı incele (varsayılan: op)
zexywing.actionbar  — Flag uyarılarını action bar'da görüntüle (varsayılan: op)

Gereksinimler
──────────────────────────────────────────────
▸ Spigot / Paper 1.18+
▸ Java 17+
▸ ProtocolLib
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
Geliştirici: KuroSBey | Sürüm: 3.0.1
