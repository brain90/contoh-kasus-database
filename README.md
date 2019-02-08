# contoh-kasus-database
Contoh kasus desain database.

# Disdukcapil
Eksperimen Desain Database kependudukan Indonesia

= Ide & Fitur
* Single Identity Number (SIN)
* Setiap RT dibekali apps, sehingga sensus bisa dilaksanakan secara realtime
* Data kependudukan meliputi (propinsi, kabupaten, kecamatan, desa, rt, rw)
* Mengcover pergerakan penduduk
* Monitoring status (Kelahiran, Kematian, Kesehatan, Kesejahteraan)
* Web Service & Sertifikat untuk berbagi data antar instansi
  (Kepolisian, Pajak, Bank, Rumah Sakit, Sekolah, Imigrasi, Zakat, dsb)
* Ketika ada kelahiran, pihak terkait cukup masukkan sin kepala keluarga
  dengan otomatis akta kelahiran tergenerate.
* Ketika ada kematian, pihak terkait cukup masukkan sin, status hidup dan akta kematian 
  penduduk otomatis terupdate.
* Macam-macam event

= Sumber Data
* http://bps.go.id/Subjek/view/id/12#subjekViewTab3|accordion-daftar-subjek1

= Konsep simulasi
* Generate random data penduduk beserta hubungan keluarganya (240 juta orang)
* Generate random event kelahiran dan kematian
* Generate random event mutasi penduduk
* Akses web service
* Performance testing
