# 1. Secret Nedir ?

Secret, bir uygulamanın veya sistemin başka bir servise erişmesini sağlayan gizli kimlik doğrulama bilgileridir. Bu bilgiler genellikle uygulamalar arasında güvenli bağlantı kurmak, API servislerini kullanmak veya veritabanlarına erişmek amacıyla kullanılır.

Secret olarak değerlendirilebilecek bazı bilgiler şunlardır:

* API Key: Bir uygulamanın başka bir servisin API'sine erişmesini sağlayan anahtar.
* Access Token: Bir kullanıcının veya uygulamanın belirli kaynaklara erişmesine izin veren token.
* Database Password: Veritabanına bağlanmak için kullanılan parola.
* Private Key: Şifreleme ve kimlik doğrulama işlemlerinde kullanılan özel anahtar.
* Cloud Credentials: AWS, Azure ve benzeri bulut servislerine erişmek için kullanılan kimlik bilgileri.

Bu bilgilerin kaynak kod içerisinde açık şekilde tutulması güvenlik riski oluşturur. Özellikle bir Git deposunun herkese açık olması durumunda bu bilgiler başka kişiler tarafından ele geçirilebilir.

Bu nedenle yazılım projelerinde kaynak kodun yanı sıra Git geçmişi de düzenli olarak taranmalıdır. Secret Scanning araçları bu amaçla kullanılır.

