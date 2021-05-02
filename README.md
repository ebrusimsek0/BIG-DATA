# BIG-DATA

### BÜYÜK VERİ ANALİTİĞİ

  Büyük veri her türlü kaynaktan gelen heterojen ve büyük hacimli veridir. İçerdiği veri tipine göre yapısal, yarı yapısal ve yapısal olmayan veri olarak ayrıştırılabilir. Yapısal veri saklanması,
sorgulanması, işlenmesi kolay olan veritabanında tutulabilen veridir. Yarı yapısal veri, veri açıklamalarını içeren işaretler etiketlerden oluşan XML yada JSON gibi verilerdir. Yapısal
olmayan veri tanımlaması zor olan kitap, makale, belge, e-posta gibi farklı formattaki verilerdir. NoSQL ile işlenebilir. Verinin bu üç biçiminden oluşan ve %95 i yapısal olmayan veri olan
büyük verinin hetorejenliği ve boyutu sebebiyle ilişkisel veritabanı yönetim sistemi ile yönetilememiştir. Bu sebeple dağıtık dosya sistemi geliştirilmiştir.
  
  Dağıtık dosya sistemi çok büyük boyuttaki dosyaları saklayabilme ve işlemeyi sağlayan bilgisayarları birbirine bağlı sunucu gibi kullanarak oluşturulmuş küme (cluster) ile sanal bir disk
oluşturmayı sağlar. Yani ilişkisel veri tabanı yönetim sistemi gibi veriyi tek bilgisayarda değil veriyi kümedeki node (düğüm) denilen bir çok bilgisayara dağıtarak tutar.
Sun Ağ Dosya Sistemi (NFS), Andrew Dosya Sistemi(AFS) ve Google Dosya Sistemi (GFS ) gibi dağıtık dosya sistemleri vardır. Büyük veri alanında en çok Google Dosya Sistemi (GFS )
nin bir türevi olan Hadoop Dosya Sistemi (HDFS) kullanılmaktadır.

### HDFS sisteminde bulunan veriyi işlemek için bir çok büyük veri yazılımı vardır:

●  Apache Hadoop (veri depolama/ işleme)

●  Apache Spark (gerçek zamanlı veri işleme)

●  Apache Hive (veri ambarı)

●  Apache Storm

●  Map-Reduce (Haritala-İndirge veri işleme modeli)

●  Presto

●  HBase (NoSQL veritabanı)

●  HCatalog

●  Ambari

●  Flume

●  Kafka

●  Sqoop

●  Pig

●  HCatalog

●  YARN

●  Flink

●  Heron

●  Kafka Streams

●  Apache TEZ

●  Apache Impala

●  Apache Beam

●  Apache Apex

●  Samza

●  Cassandra

●  XPlenty

●  Kudu

●  Knime

●  Datawrapper

●  MongoDB

●  Lumify

●  Apache SAMOA

●  Talend

●  Rapidminer

●  Qubole

●  Tableau

●  Splunk

  Yukarıdakiler gibi frameworkler kullanılarak büyük veriye erişilir ve büyük veri işlenir ve anlam çıkarılır. Örneğin Hadoop sık kullanılan büyük veri yazılımlarının başında gelir. Her bilgisayarın
işlemcisi ve RAM i olduğu için verinin dağıtılması gibi “sql” sorgularıda node’lara dağıtılır. Hadoop, Map-Reduce (haritala-indirge) ile verileri işler. Map-Reduce’da bütün işlemler
haritalandırılarak ayrı ayrı node larda yani ilgili düğümde yapılır. Daha sonra gelen cevaplar merkeze alınarak toplam sonuç oluşturulur. Böylece veri trafiği oluşturulmasıda engellenerek
veri işlenebilir. Veriler işlenirken zamanın önemli olmadığı “toplu işleme (batch processing)” yada gerçek zamanlı işleme yapan akış işleme(stream processing) kullanılabilir.
  
Büyük veri analitiği kavramıda verinin bu işlenmesi sürecini içerir. Farklı kaynaklardan gelen farklı formattaki çok büyük boyutlu veri incelenerek içerisindeki gizli örüntüler, korelasyonlar,
anlamlar bulunur. Bu anlamı çıkartmak insanın çok fazla zamanını alacağı için makine öğrenmesi teknikleri ile bu örüntüler makineye buldurulur model geliştirtilir. Böylece büyük veri işlenirken uygun analitik toollar kullanılarak veriye erişilip makine öğrenmesi ile veri işleme
işlemi gerçekleştirilip, büyük veriden bir değer üretilir. Anlam yüklenen veri karar oluşturmayı sağlar. Geliştirilen model benzer yeni verilere de uygulanarak yeni kararlar oluşturulur.
Büyük veri analitiği büyük şirketlerin temel işlem sürecini oluşturur. Şirketlerin büyümesi, gelişmesi ve işlerinin kolaylaşmasını sağlar.

  Büyük veri analitiği süreci problem tanımlama ile başlar, analiz için gerekli olan probleme özgü veri belirlenir, veri önişlemden geçirilip temizlenip analize hazır hale getirilir, makine öğrenmesi yöntemleriyle veri analiz edilir örüntüler ortaya çıkarılır, ve son olarak sonuçlar görselleştirilir. Aslında probleme göre tanımlayıcı analitik, tahminleyici analitik, yönlendirici analitik yada tanılayıcı analitik yapılabilir.

● Tanımlayıcı analitik: Tavsiye sistemlerinin yönetilmesini sağlar.

● Tahminleyici analitik: Olası problemlerin çözümünü sağlayabilecek gelecekle ilgili kararlar alınmasını sağlar.

● Yönlendirici analitik: Sürücüsüz otomobil gibi akıllı cihazlara yönlendirme sağlar.

● Tanılayıcı analitik: Başarı yada başarısızlığın sebeplerini bulmayı sağlar.
