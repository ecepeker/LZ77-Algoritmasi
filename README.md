# LZ77-Algoritmasi
Algoritma bulunduğu klasördeki txt dosyasını fgetc() yardımıyla karakter karakter okuduktan sonra, sag ve sol adında iki temel kısım oluşturur. LZ77 algoritmasının çalışmasına göre, malloc ve realloc yardımıyla oluşturulan sağ tarafa, karakterleri atar. Sağ taraftan sol tarafa doğru metnin ilk indisini atarak sağ taraftaki metni sol tarafta arar.
Ekrandaki çıktı ise [uzaklik,benzerlik,C(karakter)] şeklindedir.Herhangi bir benzerlik bulunmazsa çıktı [0,0,C(karakter)] şeklinde olur.

1. Build&Run işleminden önce kodun içinde bulunan fopen kısmına sıkıştırmak istediğiniz dosyanın adını giriniz.
2. Build&Run işleminden sonra konsol ekranında verilen metnin LZ77'ye göre sıkıştırılmış halini göreceksiniz.
3. Alt kısımda metnin sıkıştırıldıktan sonraki kısa hali de bulunmaktadır.
4. Programı kapattıktan sonra sıkıştırılmış hali içeren çıktıyı output.txt dosyasında bulabilirsiniz.
