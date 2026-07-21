# 4.0 PERBINCANGAN DAN KESIMPULAN

---

## 4.1 Perbincangan

### 4.1.1 Analisis Keputusan Keseluruhan

Berdasarkan keputusan ujian yang telah dijalankan, sistem keselamatan kanak-kanak ini menunjukkan prestasi yang sangat memuaskan dengan kadar kejayaan **100%** dalam kesemua 20 ujian yang dijalankan. Keputusan ini membuktikan bahawa sistem yang direka bentuk adalah berfungsi dengan baik dan boleh dipercayai untuk digunakan sebagai sistem keselamatan kanak-kanak dalam kenderaan.

Keempat-empat keadaan yang diuji iaitu Keadaan Normal (A), Baby Carseat Kosong + Tangan (B), Beg di Atas Carseat (C), dan Baby Carseat + Beg + Tangan (D) semuanya mencatatkan keputusan **Berjaya**. Ini menunjukkan bahawa sistem tidak memberi amaran palsu dan berjaya mengesan kehadiran manusia dalam pelbagai situasi.

### 4.1.2 Perbandingan Nilai Teori dan Praktikal

| Aspek | Nilai Teori | Nilai Praktikal | Analisis |
|-------|-------------|-----------------|----------|
| Pengesanan Radar | Radar mengesan kehadiran manusia | Radar berjaya mengesan dalam semua ujian | **Sesuai** – radar berfungsi seperti yang dijangkakan |
| Bacaan Berat | Load Cell memberi bacaan tepat | Bacaan tepat (0 kg dan 9.1-9.7 kg) | **Sesuai** – bacaan stabil dan tepat |
| Bacaan Suhu | SHT31 memberi bacaan tepat | Bacaan tepat (29.2°C - 32.0°C) | **Sesuai** – bacaan konsisten |
| Penghantaran Telegram | Telegram dihantar dalam 5-10 saat | Telegram dihantar dalam 5-8 saat | **Sesuai** – lebih cepat daripada jangkaan |
| Pengaktifan Buzzer | Buzzer aktif pada suhu ≥ 30°C | Buzzer aktif pada suhu ≥ 30°C | **Sesuai** – mengikut logik yang ditetapkan |

### 4.1.3 Perbandingan dengan Kajian Lepas

| Kriteria | Kajian Lepas (PIR Sensor) | Kajian Ini (Radar Sensor) |
|----------|---------------------------|---------------------------|
| Pengesanan Manusia Statik | ❌ Tidak dapat | ✅ **Dapat** |
| Pengesanan dalam Gelap | ✅ Dapat | ✅ Dapat |
| Pengesanan Melalui Halangan | ❌ Tidak dapat | ✅ **Dapat** |
| Amaran Palsu | Tinggi | **Rendah (0%)** |
| Kebolehpercayaan | Sederhana | **Tinggi (100%)** |

Berdasarkan perbandingan di atas, sistem yang dibangunkan ini menunjukkan kelebihan berbanding kajian lepas yang menggunakan PIR sensor. Penggunaan **radar LD2410C** membolehkan sistem mengesan manusia walaupun dalam keadaan statik (tidak bergerak) dan melalui halangan, yang tidak dapat dilakukan oleh PIR sensor. Ini menjadikan sistem ini lebih sesuai untuk aplikasi keselamatan kanak-kanak dalam kenderaan.

### 4.1.4 Inovasi Projek

Beberapa inovasi yang terdapat dalam projek ini adalah:

| Inovasi | Penerangan |
|---------|------------|
| **Penggunaan Radar LD2410C** | Menggantikan PIR sensor yang biasa digunakan. Radar boleh mengesan manusia statik dan bergerak, serta melalui halangan. |
| **Gabungan Radar + Load Cell** | Menggunakan radar sebagai penentu utama dan Load Cell sebagai maklumat tambahan. Ini mengurangkan amaran palsu. |
| **Modul 4G A7670C** | Menghantar notifikasi Telegram tanpa memerlukan Wi-Fi. Boleh digunakan di mana-mana sahaja. |
| **Sistem Bateri 18650** | Membolehkan sistem beroperasi tanpa bergantung kepada bekalan kuasa kenderaan. |
| **Ambang Suhu 30°C** | Ditetapkan lebih rendah untuk demonstrasi, tetapi boleh dilaraskan mengikut keperluan. |

### 4.1.5 Kelebihan dan Kekurangan Sistem

**Kelebihan:**

| Kelebihan | Penerangan |
|-----------|------------|
| ✅ Kadar Kejayaan 100% | Sistem berfungsi dengan cemerlang dalam semua ujian |
| ✅ Tiada Amaran Palsu | Sistem tidak memberi amaran yang tidak perlu |
| ✅ Pengesanan Tepat | Radar berjaya mengesan kehadiran manusia |
| ✅ Komunikasi 4G | Telegram dihantar tanpa Wi-Fi |
| ✅ Boleh Digunakan di Mana-mana | Sistem mudah alih dengan bateri |

**Kekurangan:**

| Kekurangan | Penerangan |
|------------|------------|
| ❌ Kos Lebih Tinggi | Radar dan modul 4G lebih mahal daripada PIR |
| ❌ Memerlukan Kuasa | Modul 4G memerlukan bekalan kuasa yang mencukupi |
| ❌ Saiz Lebih Besar | Komponen lebih besar berbanding sistem PIR |

---

## 4.2 Kesimpulan

### 4.2.1 Ringkasan Keputusan

Berdasarkan ujian yang telah dijalankan, sistem keselamatan kanak-kanak ini telah mencapai objektif yang ditetapkan.

**Jadual 14: Ringkasan Keputusan Akhir**

| Kriteria | Keputusan |
|----------|-----------|
| Kadar Kejayaan Keseluruhan | **100%** (20/20 ujian berjaya) |
| Pengesanan Radar | **Berjaya** dalam semua ujian |
| Bacaan Berat | **Tepat dan Stabil** |
| Bacaan Suhu | **Tepat dan Konsisten** |
| Penghantaran Telegram | **Berjaya** dalam masa 5-8 saat |
| Pengaktifan Buzzer | **Tepat** mengikut logik yang ditetapkan |
| Amaran Palsu | **Tiada** (0%) |
| Kebolehpercayaan Sistem | **Sangat Tinggi** |

### 4.2.2 Objektif Projek

| Objektif | Pencapaian |
|----------|------------|
| Mengesan kehadiran kanak-kanak dalam kenderaan | ✅ **Tercapai** – radar berjaya mengesan kehadiran |
| Memberi amaran awal melalui Telegram | ✅ **Tercapai** – Telegram dihantar dalam masa 5-8 saat |
| Mengaktifkan buzzer pada suhu berbahaya | ✅ **Tercapai** – buzzer aktif pada suhu ≥ 30°C |
| Mengelakkan amaran palsu | ✅ **Tercapai** – tiada amaran palsu dalam semua ujian |

### 4.2.3 Cadangan Penambahbaikan

Untuk meningkatkan lagi sistem ini pada masa hadapan, beberapa cadangan adalah:

| Cadangan | Penerangan |
|----------|------------|
| **Tambahan Sensor GPS** | Menghantar lokasi kenderaan bersama notifikasi Telegram |
| **Tambahan Sensor CO2** | Mengesan tahap karbon dioksida dalam kabin |
| **Aplikasi Mudah Alih** | Membangunkan aplikasi khas untuk memantau sistem |
| **Integrasi OBD-II** | Membaca data enjin dan status kenderaan |
| **Kawalan Suhu** | Mengaktifkan sistem penghawa dingin secara automatik |
| **Pengesanan Jatuh** | Mengesan jika kanak-kanak jatuh dari kerusi |

### 4.2.4 Kesimpulan Akhir

Secara keseluruhannya, sistem keselamatan kanak-kanak dalam kenderaan yang dibangunkan ini **telah berjaya mencapai semua objektif yang ditetapkan**. Sistem ini mampu mengesan kehadiran kanak-kanak, menghantar notifikasi Telegram, dan mengaktifkan buzzer pada suhu berbahaya dengan **kadar kejayaan 100%**. Sistem ini juga berjaya mengelakkan amaran palsu dalam semua keadaan yang diuji.

Penggunaan **radar LD2410C** sebagai sensor utama memberikan kelebihan berbanding PIR sensor kerana ia boleh mengesan manusia walaupun dalam keadaan statik dan melalui halangan. Modul **4G A7670C** pula memastikan notifikasi dapat dihantar tanpa bergantung kepada Wi-Fi, menjadikan sistem ini sesuai digunakan di mana-mana sahaja.

Dengan kadar kejayaan 100%, tiada amaran palsu, dan masa tindak balas yang cepat (< 15 saat), sistem ini **boleh dipercayai** dan **berkesan** untuk digunakan sebagai sistem keselamatan kanak-kanak dalam kenderaan. Inovasi yang diperkenalkan dalam projek ini berpotensi untuk dikomersialkan dan memberi manfaat kepada masyarakat.

---

*— Tamat —*
