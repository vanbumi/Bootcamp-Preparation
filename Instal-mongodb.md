/> **Instal Mongodb untuk Windows**, download file installer disini https://www.mongodb.com/download-center/community, setelah download selesai doble click untuk proses instalasi hingga selesai. Note: "Jangan gunakan mongodb cloud!" dan install mongodb dulu, **mongodb compass** belakangan saja.

/> Pengguna windows 7 system 32 gunakan file installer khusus bisa download disini [https://www.mongodb.org/dl/win32/i386](https://www.mongodb.org/dl/win32/i386).

/> Pada pilihan Choose Setup Type > pilih Complete.

Biasanya aplikasi akan tersimpan di folder C:\Program Files\MongodDB\, kemungkinan berbeda pada versi windows lain. Silahkan cari folder bin berada kemudian copy path karena kita akan memasukannya ke dalam Path pada Environment Variable.

/> Selanjutnya setting Environment supaya aplikasi mongoDB terbaca oleh command prompt: <br>

1. Pada Windows 10 buka Start > Search > Ketik "env" > Pilih "Edit the system environement variables".
2. Klik button "Environment Variables".
3. Pada section "System Variables" > Pilih Path > Klik Edit > Ketikan Path letak folder "bin" berada pada folder mongodb di komputer anda, contoh " ..mongodb\..\..\bin

/> **Menjalankan Server Mongodb**.<br>

- Buka Terminal Command (gunakan **Gitbash** bagi pengguna Windows dengan administrator priviledge).
- Kemudian ketikan ```mongod```.
-	Apabila tidak ada error buka tab Terminal baru dan ketikan ```mongo``` untuk membuka mongodb console.

/> Bila ada error seperti ini: <br>
```Data directory C:\data\db\ not found```.

/> **Solusi nya adalah** buat folder di C:\data\db.