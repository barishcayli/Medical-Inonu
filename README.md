# 🚀 Medical İnönü - https://medikal.inonu.edu.tr/
Bu proje İnönü Üniversitesi Bilgisayar mühendisliği öğrencileri ile Tıp Fakültesi öğrencilerini, doktorları buluşturmayı temel edinen bir projedir. Proje esasında öğrencilerin yapay zeka entegreli çözümsel modüllerinin sisteme belirli testlere tabii kalarak yüklemesi ve doktorların ve tıp öğrencilerin bu modülleri kullanarak daha kolay bir çalışma ortamına sahip olmalarını hedeflemektedir.

## 🧰 Kullanılan Teknolojiler

- Python
- Django
- Html - css - JavaScript
- PostgreSQL
- Celery
- IIS
  

## ✨Tanıtım
-Kategorize edilmiş bir ana sayfa ile kullanıcı kullanmak istediği modüle rahatlıkla ulaşabilmektedir.
![image](https://github.com/user-attachments/assets/929b600c-de71-479d-a6c4-846436e03515)



-Sisteme giriş yapan öğrencilerin modüllerini görebileceği, düzenleyebileceği, silebileceği bir projelerim sayfası.
![image](https://github.com/user-attachments/assets/000e3d49-e477-4286-b61b-f33ce609722f)

-Öğrencilerin ekleyecekleri modüllerin problemsiz çalışması için önceden test ettirilmesini sağlayan bir code test sayfası. Bu sayfaya öğrenciler kodlarını ve yapay zekalarını yüklüyorlar ve eğer problemsiz bir şekilde çalışıyor ise modülleri sisteme yükleniyor aksi halde terminalden düzenlemeleri gerekiyor.
![image](https://github.com/user-attachments/assets/59f449f0-02bf-4ba2-8f75-22453cbbf0f2)


-Öğrenciler eğer iki kişilik bir ekip halince çalışacaklar ise projeye iki kişinin de düzenleyebilmesi için bir ekip oluşturmaları geerekmektedir bunun için de ekip oluşturma sayfası bulunmaktadır.
![image](https://github.com/user-attachments/assets/f216d978-a9de-4699-b5f6-32e5e17d2204)

-Ana sayfadan çalıştırılmak istenen modül seçildikten sonra eğer 3 boyutlu bir çıktı vericekse ona uygun eğer iki boyutlu bir çıktı vericekse ona uygun dosya yüklenir ve işlem sırasına girer burda işlem sırasını celery ile sağladık.
![image](https://github.com/user-attachments/assets/ddd9b5a0-ff06-4639-b14b-a7ff5d42b0cc)

- Gönderilen işlemin başarılı, başarısız ya da daha işlemde olduğunu gösteren bir sonuç sayfamız vardır bu sayfa kullanıcı id sine özeldir ve bir kullanıcının yaptığı işlem sadece onda gözükür bunun yanında herkses açık da işlem yapılabilir.
 ![image](https://github.com/user-attachments/assets/39e1bb12-6f61-4564-82f3-96345163ab57)

-Çıkan sonuç 2 farklı şekilde gösterilmektedir ilk gönderilen ham görüntü ve teşhis edilen sonuç. Bunların yanında eğer kullanıcı görsel üzerinde bir işaretleme yapmışsa bu bir json ile aktarılmakta ardından görsele çizilmektedir eğer istersek bunu sayfa üzerinden açıp kapatabiliriz.
![image](https://github.com/user-attachments/assets/c854b5e6-a7c5-4456-a8d7-0c13c822a76e)
![image](https://github.com/user-attachments/assets/8cb46ddc-e6c9-46a2-b75d-88bae1ffd4c9)




## ⚙️ Kurulum

