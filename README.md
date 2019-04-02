# BDTMongoDBAtlas
<h1>Registrasi ke MongoDB Atlas</h1>

1. Registrasi dan Login ke https://cloud.mongodb.com/user#/atlas/login <br>
2. Membuat cluster pada mongodb atlas
<br>
<img src="https://github.com/TommyHalim/BDTMongoDBAtlas/blob/master/Screenshoot/1.JPG">
<br>
3. Mengimpor file JSON <a href="https://www.kaggle.com/gjbroughton/christmas-recipes">Christmas Recipes</a>
<br>
Download mongodb shell pada mongodb atlas, lalu melakukan perintah

~~~
mongoimport --host cluster0-shard-00-00-1plxb.mongodb.net:27017 --db recipes --type json --file recipes.json --authenticationDatabase admin --ssl --username TommyBDT --password admin
~~~

<img src="https://github.com/TommyHalim/BDTMongoDBAtlas/blob/master/Screenshoot/import.JPG"><br>
Setelah berhasil diimpor, cek koneksi mongodb pada shell(didapatkan dengan mangklik connect mongodb shell pada mongodb atlas):
<br>
<img src="https://github.com/TommyHalim/BDTMongoDBAtlas/blob/master/Screenshoot/cek1.JPG"><br>

4. Mengakses data menggunakan Mongodb Compass<br>
Mengklik connect--> mongodb compass pada mongodb atlas untuk mendapatkan akses mongodb compass. Sebelum itu download terlebih dahulu mongodb compass apabila masih belum ada di komputer. 
Buka mongodb compass lalu kopikan string akses yang didapat pada mongodb atlas. Setelah itu konek mongodb compass dengan cluster yang diinginkan.
Apabila sudah terkonek akan terlihat tampilan sebagai berikut: <br>
<img src="https://github.com/TommyHalim/BDTMongoDBAtlas/blob/master/Screenshoot/compass1.JPG"><br>
<img src="https://github.com/TommyHalim/BDTMongoDBAtlas/blob/master/Screenshoot/compass2.JPG"><br>

