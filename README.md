# Analisa_Efektifitas_Operator


**Deskripsi Topik**

Dataset yang tersedia berisi data tentang penggunaan layanan telepon virtual "CallMeMaybe". Para kliennya adalah perusahaan-perusahaan yang perlu mendistribusikan panggilan masuk dalam jumlah besar di antara sejumlah operator, atau melakukan panggilan keluar melalui operator mereka. Operator tersebut juga bisa melakukan panggilan internal untuk berkomunikasi satu sama lain.

**Tujuan**

Memberikan informasi kepada para supervisor terkait **operator mana yang paling tidak efektif**. 

Seorang operator dianggap tidak efektif jika: 
1. dia memiliki banyak panggilan masuk yang tidak terjawab (baik internal maupun eksternal)
2. waktu tunggu yang lama untuk panggilan masuk. 
3. Apabila seorang operator diharapkan untuk melakukan panggilan keluar, kecilnya jumlah panggilan juga merupakan tanda bahwa operator tersebut tidak efektif.

Terdapat 2 dataset yang nantinya akan digunakan untuk analisa

1. telecom_dataset_us.csv:
 - user_id — ID akun pelanggan
 - date — tanggal data statistik ini diambil
 - direction — arah panggilan (out untuk panggilan keluar, in untuk panggilan masuk)
 - internal — apakah panggilan tersebut internal (berlangung di antara para operator klien)
 - operator_id — ID operator 
 - is_missed_call — apakah panggilan tidak terjawab
 - calls_count — jumlah panggilan
 - call_duration — durasi panggilan (tidak termasuk waktu tunggu) 
 - total_call_duration — durasi panggilan (termasuk waktu tunggu)



2. telecom_clients_us.csv:
 - user_id
 - tariff_plan — paket klien saat ini
 - date_start — tanggal klien melakukan pendaftaran
