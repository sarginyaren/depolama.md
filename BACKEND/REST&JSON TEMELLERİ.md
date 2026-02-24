### API(Application Programming Interface)
## İki farklı sistemin birbirleriyle güvenli şekilde iletişime geçmesini sağlayan elçi.
## API,yazılım dünyasını hem hızlandırır hem güvenli kılar.Tüm dosyalara erişim sağlamaz sadece belirli isteklere izin verir.Farklı dillerle yazılmış sistemlerin anlaşılmasını sağlar.Python ile yazılmış bir yapay zeka modeli,Javascript ile yazılmış web sitesine API üzerinden veri aktarabilir.

### REST API TEMEL TAŞLARI
## GET
## POST
## PUT
## DELETE

### GET (Okuma/Görüntüleme)
## Sunucudan veri çeker.Sadece bilgiyi istersin sunucu üstünde değişiklik yapmazsın.

### POST
## Sunucuya YENİ veri gönderir.YENİ kaynak OLUŞTURUR.

### PUT 
## Sunucudaki veriyi tamamen değiştirmek veya güncellemek için kullanılır.

### DELETE
## Sunucudaki belirli veriyi siler.

### JSON
## JSON,verileri (anahar-değer) şeklinde saklar.
## Veriler {} içine yazılır.
## Anahtarlar her zaman "" içine alınır.
## Her anahtardan sonra : gelir.
## Veri çiftleri birbirinden , ile ayrılır.

## Az yer kapladığı için API yanıtları daha hızlıdır.

### ENDPOINT 
## Üç ana bileşenden oluşur:
## Method:Ne yapılacağı(GET,POST ..)
## Path:Kaynağın nerede olduğu
## Handler:İstek geldiğinde çalışan kod bloğu

## İyi bir endpoint ismi isimlerden oluşur, fiillerden değil.
## Veri çekeceğin için GET metodunu kullan.