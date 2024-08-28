[2m2xC5O8TSrvV10nQPT0EG-clean.csv](https://github.com/user-attachments/files/16776360/2m2xC5O8TSrvV10nQPT0EG-clean.csv)# soal untuk pretest-data-engineer

## Knowledge Base
1. Apa yang Anda ketahui tentang Data Engineer ?
2. Ceritakan pengalaman Anda dalam mengolah data?
3. Apa yang kamu ketahui tentang AI
4. Mengapa Data menjadi sesuatu yang sangat penting sekarang, dan apa dampak dari kebocoran data
5. Apa yg anda ketahui mengenai model generative AI ? da apa saja penerapannya

Jawaban 

1. Pekerjaan yang berkaitan dengan mengolah data.
2. Saya pernah mengolah data mulai dari penambangan data hingga menganalisisnya untuk diambil keputusan.
3. Suatu program yang bisa sangat membantu umat manusia
4. Karena jumlah data sekarang ini sangat besar, dan data bisa diolah menjadi berbagai macam, seperti inovasi dan pengembangan suatu produk. Dampak dari kebocoran data yaitu, data yang bocor bisa di salah gunakan, dan bisa menyebabkan kerugian seperti kerugian finansial, juga bisa juga merusak reputasi seseorang atau institusi.
5. AI yang bisa menciptakan sesuatu yang baru, contohnya AI ini bisa membuat gambar, bisa juga menulis cerita, menciptakan musik, bahkan film.


## Soal Coding
studi kasus = 
seorang data engineer diharuskan oleh klien untuk membuat
blueprint data orchestration di sebuah tools yaitu Kestra.
klien ingin memproses data review lazada (review-lazada.csv).

kami sudah menyediakan akses kestra di
[Kestra](https://kestra-magang.t-dev.site/) - https://kestra-magang.t-dev.site/ 
silahkan pelajari kestra lihat dokumentasinya 
dan silahkan lakukan proses dibawah ini:

1. satu flows untuk proses data cleansing dimana bersihkan data reviewnya kemudian export ke csv

Flow data cleansing
<img width="400" alt="Screenshot 2024-08-28 at 11 30 48" src="https://github.com/user-attachments/assets/b2a65027-5d11-49c9-975c-c834fa1167e3">

CSV

[Uploading 2m2reviewContent,rating
bagus mantap dah sesui pesanan,5.0
bagus sesuai foto,4.0
okkkkk mantaaaaaaapppp goood,5.0
bagus sesuai,4.0
bima,1.0
baru 10 bulan layarnya dah bergaris,1.0
pesan rabu sore minggu sore sampe barang sesuai specs mantab tks lazada,5.0
mau tanya ini cicilnya pake apa ya cc bkn,1.0
apakah tv tsb suda ada anti gores,5.0
pengirim barang tidak sesuai janji katanya express 1 hari dari hari jumat barang sampai hari rabu semoga barangnya awet saja,1.0
kualitas ok,4.0
bagaimana tv led saya merek sharp 24 hitam lc 24le170i sekarang mati total baru 2 bln kemana saya harus menghubungi dan meminta bantuan mohon kebijakan dan solusinya so alnya masih garansi kepada pihak lazada saya mohon bantuannya terimakasih,1.0
pengiriman super lama tapi datang juga sich,3.0
ok barang sampai dengan baik smoga terus di pertahankan,5.0
kalau mau cicilan gmna cra nya,5.0
barang sudah sampai dan bagus thanks lazada,5.0
pengiriman cepat sipplahhh,5.0
sampe sekarang masih ok ne laptop,5.0
pengiriman cepat packaging good barang oke thnks seller thnks lazada,5.0
barang diterima dengan selamat produk sesuai dengan deskripsi barang nyape 3 hari ke pekanbaru riau terimakasih lazada dan kotakom pucang laptopnya mantap,5.0
senang belanja disini pelayanan oke barang sesuai ekspektasi order senin hari selasa malam udah nyampe di settingin sxan sama kurirnya pokoknya top deh thanks lazada,5.0
belum test barangnya,4.0
sudah cape2 transfer tapi pesanan ditolak,1.0
barang ok kualitas bagus dengan harga yg cukup miring kualitas gambar juga ok pengiriman lumayan ga nyesel pokonya beli tv ini,5.0
saya minat tapi kalau dikirim ke gresik jawa timur bisa gak klo dr info pengiriman bebas tapi takut gk sampai dan tanya apa ini sdh full hd apa blm terima kasih,5.0
pengn tivinya,4.0
mantapppp barang nya,5.0
barang mulusss mantapppppp,3.0
laptop ini memiliki spesifikasi yang bagus dan harga yang terjangkau namun pada tab spesifikasi utama produk itu emang intel core i5 atau salah buat di judul dikatakan core i7,1.0
barang sampai dengan aman kemampuan laptop sesuai dengan yang di iklankan hanya saja laptop datang dengan dos sehingga harus di install sendiri windows nya overall it s worth the money,5.0
barang sampai 2 hari dengan selamat dan sesuai deskripsi,5.0
harga sangat murah mantep banget,5.0
murah banget itu enga salah kasih harga tau2 nati salah kasi info barang nya,3.0
barang udah sampai tapi pas dinyalain g bisa gmn pertanggung jawaban lazada,1.0
klo dp1jt tanpa kartu kredit bisa gk brp bln pembayarannya dan sebulannya brp -terimaksh,4.0
untuk pemasangan di tembok apa ad pihak dari lazada yg memasang a terima kasih,1.0
kapasitas hdd asli 1 tb dan tanpa ada lecet di saat saya pertama kali membuka bungkus bubble nya,5.0
barang sesuai dengan gambar,5.0
hd diterima dg packing bubble bagus hanya tidak tertulis barang elektronik atw keterangan lain agar penanganan lebih hati2 dan istimewa ketika paket dalam perjalanan finally 4bintang lhah,4.0
mantap gan barang sampai dengan selamat packing rapih pokok mantap lah,5.0
oke,5.0
saya sangat puas dengan barang nya kualitas barang sangat membantu hdd saya apabila jatuh dari atas dan pengiriman rapi gk ada lecet kasih bintang 5 dan saya sangat tidak puas dengan peng,5.0
barang diterima dengan kondisi yang baik tapi packagingnya kurang,4.0
suka banget sama barangnya packing nya rapi pokoknya recomended banget buat kalian yg mau beli tas hardisk dengan kulitas bagus yah di sini,5.0
flashdisk ori packing bagus saya suka thx,5.0
aman cepat pula,5.0
bagus ori kok cuma hanya aja 58 gb klo 63 gpp hilang 1 gb,4.0
kapasitasy kurang bagusss aturany klw kosong g bnyakkk firusss tpi nieh bnyakkk firusss sangat kecewe,1.0
baguss bangett kurir nya jga ramah cakep pula wkwk ini 64gb tp cmn 58 sekian gb tp gpp lah yah pokok nya recomended deh,5.0
produk dah sampai kemasan rapih pengiriman cepat barang bagus pembayaran cod tidak perlu diragukan lagi,5.0
barangnya bagus banget sesuai dengan gambar dn deskripsi pengiriman cepat bagus dn recomended bangt,5.0
packing tanpa bubble warp fisik no minus cuma 58 gb bukan 64 ya lumayan,5.0
barang ok packing rapii kurir nya ramahh puass,5.0
produk original mantap semoga awet,5.0
baik sesuai ekspektasi,5.0
,5.0
barang nya oke makasih,5.0
tumben ninja cepat pengirimannya,5.0
barang asli dan original terimakasih maju terus toko jet store,5.0
flashdisk nya bagus sesuai picture barang cepat sampai kurir ramah,5.0
oke mudah2an awet dan ga crash belum sempet d coba,5.0
kapasitas cuma 58 gb ajaaaaa huft,5.0
katanya 64 gb nyatanya cuman 58 gb,4.0
thks ya barang sdh sampai smga cocok,5.0
siippp thank lazada,5.0
udah di trima barang ok moga awet,5.0
josss tenan,5.0
ini ori bagus tahan lama masih saya pake,5.0
kampret kaga kebaca,1.0
barang bagus quick respon hari ini pesan besok sudah sampai,5.0
brang cukup bagus,5.0
sip mantap,5.0
bagus ori,5.0
real good,5.0
bagus,5.0
good,5.0
pengiriman sangat lama tgl 19 di pesan tgl 22 barang baru dikemas tgl 23 baru diambil ekspedisi tgl 25 baru sampai masih dijabotabek tapi lama,2.0
barang tanpa kemasan tanpa pelindung apapun hanya dus tv saja liat dusnya sobek dikit sudah mulai curiga kayaknya pecah ini eeeeellllaaaa pas dibuka pecah beneran bad seller bener bener bad seller mau untung aja tanpa peduli keadaan produk kalo gak ada untung n pelit pakingan ya jgn jualan barang sudah retur mudah mudahan barangnya cepat di kirim lg d,1.0
barang diterima pada hari akhir yg dijadwalkan yaitu malam hari kondisi barang terlindungi dengan packing bawaan unit kualitas unit adalah kualitas sharp semoga awet bila unit ini dikirim dari gudang lazada di bogor mestinya bisa lebih cpt tiba bukan pada hari akhir yg dijadwalkan karena alamat tujuan juga di bogor,4.0
masukan saja klo bisa packingnya jangan asal dikasih buble wrap minimal ini cuma dipacking pakai plastik biasa sempet khawatir pecah tpi untung gk terjadi,4.0
pesanan sesuai dgn yg di gambar skrg sy lg coba smoga awet,4.0
pengiriman tidak sesuai tanggal yang tertera,2.0
sesuai no tipu2,5.0
barang ok packing rapih,5.0
barangnya sampai dengan cepat bagus terimakasih lazada,5.0
pengiriman cepat packirng rapih harga murah free ongkir,5.0
mantapp barang nya sesuai pesanan,5.0
jangan pernah beli disini parah banget barang belum sampe udh 2 mi ggu alesan nya gak jelas gangguan dll,1.0
hati hati ini tv ga bisa pake usb,1.0
puas,5.0
mantap,5.0
sangat puas dengan produknya terimakasih,3.0
memuaskan produk sesuai deskripsi packing bagus dan penerimaan produk cepat untuk saya yg berada di jkt,5.0
kenapa chargernya tidak lengkap g bisa langsung dipakai buat charger kita harus nyari dan beli lagi sambungan buat chargernya tolong d bantu,3.0
ini spek ram nya 2gb atau 4gb,1.0
gan saya sarankan untuk lebih berhati-hati dalam membeli flashdisk yang dikirim ke saya adalah flashdisk rekondisi daur ulang bekas jangan tertipu oleh harga mas dosa mas bohong di flashdisknya ada tulisan nama aryo yang sengaja dihapus tp kurang bersih file yang dikirim ke flashdisk juga error makan duit haram mas kenyang tp ga berkah,1.0
barang cepat sampainya kualitas fd kurang bagus file yang di copy sering corrupt,2.0
palsu,1.0
very good,5.0
korup terus klo di copy ke fd mengecewakan,1.0
hardisknya keren pelindungnya kokoh udah ada aplikasi transcend elitenya di dalam untuk enkripsi thanks seller and lazada,5.0
sampainya agak lama tapi puas packing rapi dan pas dateng warnanya biru seneng banget gan hehe top deh semoga awet barangnya,4.0
trims lazada reseller barang sdh saya terima senin siang penigiriman sesuai dengan yg di informasikan,5.0
sesuai spek yg saya mau jd oke lah,5.0
barangnya bagus rapi tidak mengecewakan akan tetapi bagus kalau ada bonus pouch nya hehhe,5.0
barang udah sampe gunn masih segell dari pabriknya mangstabb,5.0
barang tlah diterima kondisi baik,5.0
barang sesuai deskripsi penjual ramah respon cepat,5.0
packaging rapi flashdiksnya ori kapasitasnya sesuai dengan detail produk yang dicantumkan dan foto dengan barangnya sesuai barangnya datang sesuai tepat waktu makasih ya,5.0
flashdisknya sudah diterima dengan baik kapasitas total 58 544 586 752 bytes dengan fat32 menjadi 62 885 724 160 bytes kalau diformat dengan exfat write speed 10mb s dan read 30 mb s dengan port usb 2 0 belum dicoba dengan port usb 3 0,5.0
terima kasih barang bagus dan respon penjual sgt baik,5.0
barang sudah diterima dgn baik packing rapih tp isinya cuma 58gb selebihnya oke,5.0
pas cocok buat anda semua bgus sesuai deskripsi,5.0
puas,5.0
flashdisk 64gb casing metal baguss,5.0
sesuai deskripsi,5.0
barang dah sampai makasih,5.0
mantap barang gak minus sama sekali,5.0
pengiriman cepat packing cukup bagus,5.0
biarkan bintang yang berbicara,5.0
barangnya ok cepat sampai,5.0
pengirimannya cepat produk baik,5.0
barang sesuai dengan deskripsi dan berfungsi baik,5.0
sampai cepat barang sesuai,5.0
dikirim hari berikutnya dan barang mulus,4.0
oke,5.0
baik,4.0
ram 8gb atau 4gb,2.0
tv led dengan pilihan input yang lengkap hdmi dv vga kami beli untuk keperluan kantor yang penggunaannya bisa multi-source panasonic satu-satunya merk yang menyediakan fasilitas ini sepanjang pengetahuan kami kualitas gambar juga bagus dengan bezel tipis yang memberikan kesan lega extra bracket memudahkan pemasangan di dinding bravo panasonic,5.0
cuma butuh waktu 12 jam unit tiba thks,5.0
mau cicilan gmn caranya6,1.0
nyicil dengan cara mudah prosesnya susah nggak,3.0
pokonya puas,5.0
puas bgt pengiriman sesuai jadwal barang bagus packing rapih buat maen game enak bgt hihii murah lagi tenkyu lazada,5.0
saya igin pesan tapi packingnya kalo bisa harus rapih dan aman jadi barang terlindungi untuk saat ini bintang 3 nanti kalo barangnya udah diterima dan bagis jadi 5 bintang,3.0
saya kurang yakin produk ini genuine karena hologramnya pun tidak ada dan kartu garansinya pun tidak ada hanya keterangan saja di dusnya bahwa barang ini original resmi indonesia bergaransi dengan diberi nomor telpon service centernya memory yang tersedia ternyata juga tidak sampai 2 tb tetapi 1 81 tb selisih 0 19 tb besar banget selisihnya tidak mungkin juga terpakai untuk sistemnya sampai begitu banyak tapi tidak begitu masalah eksternal hardisk ini bekerja bagus cepat dan hadiah hardcase cukup bagus untuk melindungi barang ini dari debu dan benturan sayangnya saat di registrasi ke official webnya wd ternyata identification numbernya tidak dikenal tidak valid alias barang ini bukan asli alias kw seller responsif sayangnya tidak memberitahu asli tidaknya barang ini pengiriman terhitung cepat dalam 2 hari barang sudah di tangan mudah2an saja barang ini awet wslaupun tdk original,3.0
barang bagus peking rapih gua rekomendasikan banget lah klo barangnya cma sayang pengiriman lama kaya ampas jne dioper sana sini barang gua ga ga muncul2 harus di komplen dlu cs ny kali baru ngerti mending buat pengiriman lain deh lbi bgus,3.0
mantab speed konsisten total size asli 1 81gb pas sejauh ini masih normal digunakan nice job seller n lazada,5.0
barang belum terima pihak lazada bilang sidah diterima cek di jne lhoksukon aceh utara barang tidak ada ada masalah petigasnya tdk ramah dan tdk ada solusk mana yg benar email ke cs jne sama cs lazada tdk ada reapon bagaimana nasih barang saya harga 1 jt an,1.0
smuanya mntap,5.0
pengiriman cepat hr ini kirin lusa udh terima packing rapi pake bubble jg kwalitas product oke tq,5.0
saya rekomendasikan beli disini,5.0
sudah sampaiii,5.0
warna sesuai pesanan spek persis ok dah,5.0
thanks respon cepat hdd ext 2tb sampai sesuai pesanan,4.0
original packing rapi,5.0
barang good condition and delivery ok,5.0
barang oke,5.0
foto produk sesuai dengan asli warna birunya bagus saya pesan dan bayar produk ini pada tanggal 21 oktober 2018 dan produk ini datang pada tanggal 23 oktober 2018 dalam kondisi baik dan berfungsi untuk macbook pro saya meskipun saya harus format dahulu saya mendapat bonus poket untuk external hdd saya ini mudah-mudahan produk ini awet terima kasih lazada,4.0
packing rapi dan pengiriman tepat waktu sejauh ini berfungsi dengan baik harapannya semoga awet ni barang,5.0
barangnya bagus kecil compaq dan packing baik,5.0
good product with reasonable price,5.0
packing rapi kualitas oke fitur2 persis seperti deskripsi desain keren cuma yg kurang puas di segi kecepatan transfer hanya mentok di 9-10 mb s,5.0
gmn nih lazada saya liat iklannya flashdisk tapi yg dikirim koq malah flashdrive mohon penjelasannya barang sdh saya buka saya br x ini kecewa,1.0
smua yang di ulasan bener smua apa mreka kata kapasitas terbaca 29 5gb karena terpakai sistem pengiriman lebih cepat dari extimasi,5.0
barang sdh diterima pengirimannya cepat data yg terbaca 29 1gb iya karena space 32gb tdk terbaca 32gb full terima kasih atas fast responnya n barangnya ori,5.0
pengiriman cepet tapi tranfer failnya lemot,5.0
flashdisknya bagus tapi jatoh sama teman akhirnya rusak untuk mengeluarkan nya,4.0
cepet sampai barang asli bagus lah thanks lazada,5.0
barang cepat cuma 2 hari garansi resmi mantabb,5.0
cepet sampai 1 hari udah sampai barang bagus gk cepet panas walau di pake lama pokoknya mantab,4.0
bagus packing rapi modelnya aku suka thanks lazada,5.0
barang bagus pertahankan,5.0
barangnya sudah saya terima kondisi sangat baik trimakasih lazada,4.0
produk oke dan original by datascrip tapi sayang kapasitas bersihnya 29gb,4.0
pengiriman cepet barang bagus transfer data lebih cepat daripada tipe cruzer switch,5.0
produk mantap sesuai deskripsi,5.0
good,5.0
produk sesuai pengiriman cepat,5.0
produk bagus,5.0
barang sangat bagus trimakasih,5.0
barang yg dikirim tidak seperti yang di gambar,2.0
barang yg sampe cruzer yg biasa tidak sesuai di gambar tapi size-nya 64gb,4.0
cukup bagus,5.0
knpa prosesnya lama apa gagal atau sya harus pesan lagi,2.0
barang saya ko gaada ya padahal saya ngasih alamatnya bener dan saya cek di situs jnenya alamat tujuannya kok salah mohon diperiksa kembali saya beli barang bebarengan dengan yang lain yg lainnya udh sampai tapi beli di sini gaada barangnya sampai sekarang,1.0
kecewa alias barang aspal ya lumayan buat isi mp3 sih banyak lagunya,3.0
flashdisk 64gb tpi isi cm 2gb gk bs dipakai,1.0
tidak bisa berfungsi menyimpan data,1.0
barang tidak pernah sampai yg hitam yg putih ga bisa dipake,1.0
pengiriman lama warna yang dateng putih bukan hitam,1.0
krn pesanan tdk sesuai dengan kirimannya dr warna saja saya pesan hitam dikirm putih dan tidak bisa dipakai di labtop anak saya seharusnya tidah seperti itu yah,1.0
flashdisk saat dicopy file yg kebaca setengah doang ud mana beli 2 saya tertipu pantes g garansi hati hati untuk yg mau beli,1.0
ketika barang datang masih di luar kota 2 minggubkemudian baru cek barang dari awal muncul pertanyaan karena di pembungkusnya sendiri tulisannya toshiba kapasitas 8 gb sedangkan di flashdisk memang tertulis 64 gb setelah dicoba untuk kopi file ternyata banyak yang failed dan yang berhasil dikopi ternyata juga tidak dapat dibuka sepertinya ini hanyalah produk gagal buatan oem yang dibuat asal-asalan untuk dijual murah dan pihak toko terlanjur membeli dalam jumlah banyak kemudian berusaha menjual dengan segala cara,1.0
rusak gk bisa dipakai kapok,1.0
ga bisa dipakai,1.0
barangnya lama sekali,1.0
produk jauh dari yang diharapkan sangat kecewa,1.0
kok dapet nya warna biru,1.0
barang diterima cepat seller n lazada pelayanan bagus kemasan rapi kasih plastik tebal lagi good tvnya cakep sesuai gambar n speknya display cukuplah sesuai sempat ada baut casing lepas dikencangkan ternyata bisa recomended buat yang nyari,5.0
ini tv jg bs jadi monitor pc kan,4.0
boleh kredit bang,5.0
1 hari order besok langsung sampai fast respon fast seller,5.0
biar bintang yang berbicara,5.0
bagus barangnya,5.0
mantab reseller nya pengiriman cepat dan pakingan ok thank s reseller dan lazada sukses selalu buat reseller dan lazada,5.0
packing dan barangnya ok namun bonus pouch ukurannya terlalu kecil untuk tempat hardisk nya,5.0
pengiriman cepat kualitas gambar bagus terutama kualitas suaranya oke dvb t2 berfungsi baik cuma remote ada yg error tombol source tidak fungsi jd kalau mau ganti ke usb hdmi atau lainnya mesti pencet tombol fisik di tvnya sudah minta ganti ke seller malah disuruh contact aquanya kata aqua kalau remote rusak dan baru beli bisa minta ganti ke tokonya ribet deh dipingpong,2.0
ini layar sentuh bukan yah,3.0
saya pesan uang sdah d transfer tapi barng tdk sampai,1.0
bagi yang minat order pesan barang kami silahkan add whatsapp wa 085200343400 langsung dari reseller toko terimah kasih,5.0
hi sist gan stocknya masih ready informasi produk kami silahkan chat add whatsapp 0852-5468-9727 respon cepat aman terpercaya pengiriman via jne tiki seller resmi lazada terima kasih,5.0
untuk info buat pelanggan setia kami di karenakan lazada slow respon cepat aman dan terpercaya kami buka orderan pemesanan beli 1 garatis 1 melalui via whatsapp wa 085250720044,5.0
bagi yang minat order pesan barang kami untuk lebih memastikan silahkan add whatsapp wa 085200343400 langsung dari reseller toko terimah kasih,5.0
klu cicilan gmn cranya yah,1.0
saya dari sumba timur-waingapu,4.0
cara kredit nya bagaimana,5.0
bisa di cicil gak,3.0
laptop nya bagus,5.0
tidak bisa di kurangi ya biar jadi 1 000000,1.0
ini berapa inci ya layarnya,3.0
ini bayar di tempat apa tidak,1.0
bayar ditempat,3.0
caranya gmn ya,1.0
rizi,4.0
ditulis khusus jabodetabek tp tersedia diwilyah lampung dibeli tp dicancel krn diluar daerah klo gk bisa harusnya dtulis tdk tersedia diwil anda,1.0
gmana caranya klw mau ikut kredit di lazada,3.0
bisa kiri ke kota blitar tidak,1.0
klw di kirim k karawang bisa gak,2.0
gambarnya tidak keliatan,2.0
terimakasih barang nya memuaskan semoga awet juga,5.0
mantuulll,5.0
makasih gan tapi produk nya saya mesen yang 16gb dateng nya mlh yang 32gb mungkin slh masukin produk,5.0
alhamdulillah puas wlau pengirimannya hmpr mlm tpi semuanya ok,5.0
barangnya bagus suara dan gambar jernih mudah mudahan awet pengepakanya rapi datang tepat waktu kurirnya juga ramah makasih lazadd,5.0
barang cukup memuaskan seller responsif packing aman karena dari kayu yah tpi pengirimannya agak sedikit lama tpi its ok yang penting barang sudah sampai,5.0
packing rapih dan aman banget barangnya pengiriman cepat hari ini order besok langsung dateng pokonya seller recommended dari segi harga juga bersaing d,5.0
tv nya sudah datang alhamdulillah amin,1.0
produknya sesuai dgn gambar puas bgt,5.0
tv a bagus bngt layar a jga jernih bngt,5.0
puas sama produknya bagus n berkualitas,5.0
good job,5.0
bgs,5.0
siip,5.0
aku puas banget sama layanan di lazada pengirimannya cepat barangnya juga gak lecet sedikit pun terimakasih lazada,5.0
min ram nya emang segitu,5.0
barang asli dan sesuai,5.0
wd my passport 4tb harga paling murah dibanding tempat lain sudah cek online dan offline barang bagus sudah di cek total kapasitas 3 64tb original bisa di-register ke web wd nya untuk garansi 3 thn diberi beberapa software utility free diantaranya wd security untuk protect hd agar tdk bisa dibuka orang lain dan ada bonus pouch lumayan buat tempat hd nya,5.0
order mi notebook air gold 12 5 inch sampai sesuai harapan barangnya asli packagingnya aman bagus sellernya informatif cepat dikirimnya dan sudah ready terinstall dengan windows 10 english version terima kasih banyak seller,5.0
pengiriman barang ternyata sangat cepat hari ke-2 barang sudah diterima dalam keadaan baik packing rapih dan setelah dicek laptop bekerja sesuai harapan terima kasih atas layanannya yang sangat baik,5.0
pengirimannya benar-benar top packingnya rapi dan aman barangnya oke windowsnya udah pakai win 10 english version top deh,5.0
lebih keren dari perkiraan awal windows 10 sudah dikonfersi ke bahasa inggris mantab,5.0
gan kok gak dapat di kirm ke nad disitu tertulis barang ini tidak dapat di kirim ke lokasi anda,5.0
mbak mas kabari ya barang kalau udah ready stok saya rencana mau order mkasih,5.0
pelayanannya baik,5.0
pengiriman cepat barang di terima dengan baik dan lengkap langsung coba dapat bonus usb led dll recommended seller,5.0
barang bagus awet sampai sekarang,5.0
pemasangan anti virus oleh pihak wd secara online dibantu memasang juga mantap lazadaterpercaya,5.0
pengiriman cpt smp produk bagus sesuai gambar trims,3.0
saya kira antivirusnya ada kasetnya eh ternyata cuma dikasih nomor serial disuruh download sendiri overall bagus lah pengiriman cepat cuma 1 hari datang,4.0
hrg bersaing bagus,5.0
bagus koq cm gak pake antivirusnya aja ribet sih d,5.0
ntaps,5.0
barang sudah diterima dan pengiriman lumayan cepat tapi ada 2 hal yg harus penjual perhatikan 1 di etalase tv dijual dengan bonus free braket tapi yang datang cuma tv nya doang braketnya ga ada 2 ongkir tercantum rp 200 000 saya kirim sesuai yg tercantum tp pas di cek di resi yang tercantum oleh ekspedisi cobra ternyara cuma 75 000 tetep konsumen yang dirugikan toko ini jadi catatan buat saya kecuali menylesaikannya,2.0
tv nya udh seminggu blm sampai juga sepertinya harus meningkatkan pengiriman nya lebih diperhatikan supaya sampai sesuai estimasi thanks,3.0
ini bisa nonton dengar music liat poto via usb gk,5.0
sesuai pesanan bagus thanks gan,5.0
produk dgn pesanan no 3288859132 sudah diterima,5.0
ok sesuai sm deksripsi,5.0
alhamdulillah barang sampai dengan aman karna peking yang bagus semoga barang awet selalu amanah dan lancar rejekinya amiin,5.0
sesuai dengan pesanan semoga awet ya,5.0
kualitas ori kapasitas sesuao dengan dekripsinya,5.0
barang bagus dengan harga ok,5.0
barang bagus dan berfungsi,4.0
virus shortcut,1.0
packing ok barang sesuai deskripsi,5.0
barangnya tiba dengan selamat cepat tapi kemasan otg nya nggak memuaskan,3.0
siiplah pokonya thanks lazada,5.0
mudah2 n awet barang nya ada hologram nya,5.0
suka bgt barangx mulus lus lus and berfungsi dgan baik thanks lazada,4.0
barang sampe sesuai pada waktu nya packingan rapi terima kasih lazada,5.0
mudah2n awet amin,4.0
warna tidak sesuai,4.0
eliminasi 2 hari packing rapi tapi warna gak sesuai yang di ingini tapi barang normal work,4.0
product oke sesuai destkripsi dapet tas backpack jga recomend seller good dah pkknya,5.0
laptop nya dikirim sangat top modal kaciwa,5.0
sesuai dengan keinginan dan kebutuhan,5.0
paket sudah saya terima terlambat sedikit pengirimannya tapi tidak apa apa thanks lazada,5.0
respon cepat dan pengiriman cepat via go send,5.0
flashdisk baru waktu pas beli lagi diskon packagingnya jga rapih so far so good,5.0
barang cepet sampe thanks,5.0
brg sesuai cuma delivery agak lama,4.0
ok deh mantep,5.0
flashdisk sandisk ok banget ada bonus lagi terima kasih,5.0
barangnya bagus untuk harga semurah ini,5.0
gan saya pesan warna biru kok yang datang warna merah,2.0
8 hari baru sampai sistemnya kosong root saja tampil jadi hrs install ulang packingan rapi dan tersegel,3.0
barang yg di kirim tidak sesuai dengan yang di tampilkan,2.0
barang sudah sampe untuk pengriman ke kupang ntt waktunya termasuk cepat packing safe dan rapi barang sesuai gambar dan spek yang ditawarkan tx lazada kenkez,5.0
tengkyuu barangnya nyampe tepat waktu packing rapi dan savety banget recommended seller,5.0
terlambat satu hari karena kurir sampai dikantor pada malam hari jd besoknya baru bisa saya terima tp barang saya terima dengan baik terima kasih,4.0
barang sesuai pemesanan pengiriman cepat jakarta,5.0
harddisk berjalan dengan baik kelengkapan juga oke,5.0
2bulan pake crashed pdhl ga prnah jatoh,1.0
jum at pesan besoknya nyampai barang bagus tdk ada cacatnya terima kasih lazada,5.0
maaf baru sempat review secara umum cukup puas dengan layanan penjual packing bagus rapih dan aman fisik barang sesuai gambar dan ulasan yang ada di website hanya saya mis-informasi aja karena ternyata hd external wd ini gak dapat sarungnya overall saya rekomendasi sellernya thanks dan tingkatkan selalu pelayanannya sukses,5.0
mantapppp,5.0
bagus sesuai pesanan,5.0
flashdisk nya lucu sesuai dengan gambar pokoknya suka,5.0
cukup memuaskan,2.0
sip,4.0
diresponnya cepat 2 hari datang usb nya gak mengecewakan sama kayak yang digambar,5.0
barang diantar dengan cepat dan sesuai dengan penjelasan yang ada penjual merespondengan cepat,4.0
wkt baca2 di keterangannya ini bkn ori alias kw tp coba krn review yg lain jg ok tp memang ok bgt bs dipakai dgn baik bole yg mau beli,4.0
barang nya sesuai dan mulus di bungkus rapi,3.0
matul bangetz barangnya berfungsi sesuai harapan sukses trus bwt toko dan lazada pengiriman super cepat blum waktunya udah lngsung dikirim mantul dah poko e,5.0
maap bru ksi ulasan barang yampe dengan slamt dan aman tpi belum di coba krna belum sempet moga awet dan dan bagus,5.0
barang sesuai pesanan pengiriman tepat waktu paking rapih puas banget,5.0
ok,5.0
item arrived in perfect condition and still working well until today fast delivery and great customer service communication thanks,3.0
ini cuman my passport biasa bukan my passport ultra tulis deskripsi yang bener ya,1.0
awet,5.0
untuk semua hardisk kah gan,5.0
product ok sesuai dengan foto pengiriman lebih cepat dari estimasi ok,5.0
barang sesuai gambar dan bagus,5.0
tidak sesuai gambar,1.0
3 kali cicilan maksudnya 3 bln ya persyaratan untuk kredit apa aja ya,1.0
kualitas barangny bisa di jamin g ya,2.0
klu saya mau beli tv di lazada di jamin g ya kualitasnya,3.0
gmna,3.0
barang sampai dengan baik packingnya bagus isi kotaknya lengkap ada casing hdd kabel male-to-male obeng kecil baut sama wadah luar alhamdulillaah bisa digunakan dengan baik semoga awet terima kasih,5.0
pengiriman cepat packing rapi dan aman barang sesuai deskripsi mulai dati pemasangan sampai pemakaian tak ada kendala bekerja dengan normal,5.0
packing rapih semoga awet thanks lazada,5.0
packingnya rapi barangnya bagus dan murah tq,5.0
lumayan lah untuk harga segini sayang ngebaca hdd 700gb lemot euy,3.0
cukup puas barang trima ksih lazada,5.0
bagus,5.0
lumayan,3.0
barang bekerja dengan baik harga murah tapi pengiriman agak lama sukses terus lazada,5.0
cepat sampai original sudah di test dan sekarang jd tandem ssd intel saya terima kasih,5.0
pengiriman cepat barang bagus,4.0
recomended thx,5.0
sesuai tapi powerbanknya ringan sekali sesuai harga sih,4.0
barang dipacking kuat dan rapih cepat sampai sesuai estimasi trimakasih kotakom,5.0
barang di pesan tanggal13 juli tgl14 barang sudah di kirim tanggal 26 barang sampai memang sedikit lama tapi saya maklum kok karena barang nya dari luar negri packing rapi barang berfungsi dengan baik,5.0
good dan bisa di pake,5.0
udah hampir 2 minggu barang belum jg nyampe order tgl 27 april 2017 status pesanan masi aja dlm proses gmana ni lazada,1.0
barangnya udah sampai thanks lazada,5.0
mohon bantuan nya kok barangnya belom sampai udh 21hari sy tunggu gag kunjung datang mohon diperhatikan terima kasih,1.0
barang datang cepat mulus semoga tidak ada masalah kedepannya,5.0
hanya bisa menyimpan sedikit file padahal kapasitas 16 gb sebagian besar file lainnya tidak bisa terbaca padahal sudah saya coba beberapa kali,3.0
tidak bisa menyimpan data,1.0
ga kecewa deh barang keren kemasan rapih makasih bos,5.0
barang oke,5.0
karna tidak bisa nyimpan film dan data,1.0
bagus produknya,5.0
pesanan saya yg ini belum saya terima kenapa dibuat sudah saya terima tolong dong ini dicek lagi,5.0
barangnya bagus,5.0
blom keterima,5.0
produk nya mantap,5.0
so far so good,5.0
barang ok kiriman tepat waktu,4.0
sesuai,5.0
barang bagus tapi sayang pengiriman dari pihak j t barangnya kesasar ke kota pamekasan padahal sudah tercantum kota sampang utk j t lebih hati-hati lagi ya untung tidak hilang barangnya utk seller top fast response,5.0
barang nyampai dgn mulus tdk ada cacat,5.0
thanks lazada barang nya sesuai expektasi,5.0
barang good pengiriman cepat kurir mantap ramah makasih lazada,5.0
barang berfungsi normal semoga awet,5.0
barang sesuai deskripsi dan orderan,5.0
falshdisk bagus berfungsi dengan baik,5.0
barang sesuai pesanan mantab,5.0
thx lazada semoga fdnya awet,5.0
pengiriman cepat smoga awet,5.0
pengiriman cepat brgnya mantap,5.0
sampai dgn selamat dan aman,5.0
saya belum terima barangnya,5.0
brg ok sampai cepat,5.0
mantap,5.0
sip,5.0
pengiriman on time cuman packing sederhana sekali tanpa bubble wrap,4.0
kurir baik n bertanggungjawab barang sesuai spesifikasi semoga awet ya,5.0
barang cepat sampai sesuai pesanan,5.0
barang ok kemasan rapih,5.0
mantap sesuai pesanan nih mah pokok nya joss,5.0
bagus dan sangat sesuai dengan kebutuhan,5.0
lumayan dengan harga segitu packing rapih pengiriman cepat semoga tidak ada kendala,4.0
mudah mudahan bisa beli laptop mahals kalo bisa beli asus rog aja wkwk,5.0
pengen beli budget ga cukup,5.0
yah lumayan lah tapi saya ketemu ram 16gb ddr4 pake rx460 i7 6700hq malah 9 jutaan,4.0
tunggu gua jual lepi lama gua ama ngutang tetangga sebelah nanti gua beli,5.0
apa produk aslinya sesuai dgn yg di gambar ini,4.0
dikantong cuma ada 15rb,5.0
,2.0
xC5O8TSrvV10nQPT0EG-clean.csv…]()

SCRIPT
id: cleaning_data
namespace: lokololo

inputs:
  - id: file
    type: FILE


tasks:
  - id: cleaning
    type: io.kestra.plugin.scripts.python.Script
    inputFiles:
      input_csv: "{{ inputs.file }}"

    beforeCommands:
      - pip install pandas

    script: |
      import pandas as pd
      import re
      

      df = pd.read_csv('{{ inputs.file }}', na_values=['null'])

      df.dropna(subset=['rating', 'reviewContent'], inplace=True)

      df = df.drop_duplicates(subset=['reviewContent'])
      
      def clean_text(text):
        text = text.lower()
        text = re.sub('[^a-z A-Z 0-9-]+', ' ', text)
        text = re.sub(r'\s+', ' ', text).strip()
        return text
      
      df_sentiment = df[['reviewContent', 'rating']]
      df_sentiment['reviewContent'] = df_sentiment['reviewContent'].apply(clean_text)

      df = df.dropna(subset=['reviewContent'])

      df_sentiment.to_csv('clean.csv', index=False)

    outputFiles:
      - '*.csv'




3. satu flows untuk proses menghitung sentiment analysis berdasarkan kolom rating

Keterangan :
flow kestra dan script python sertakan dalam git kalian ketika pelaporan
