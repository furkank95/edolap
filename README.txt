Projede kullanılan teknolojiler;
Web Uygulaması -> ASP.NET MVC
Kiosk Panel Uygulaması -> Java
Arduino uygulaması -> Arduino IDE
Veritabanı -> MSSQL

*Web uygulaması FTP serverde çalışacak hale publish edilerek getirilmiştir. (Web Uygulaması FTP) Bu klasördeki dosyalar FTP sunucusuna atılarak çalıştırılabilir.
*Web uygulamasının ASP.NET MVC üzerindeki kodları. (Web Uygulaması) Bu klasördeki solution üzerinden kodlar değiştirilebilir.
*Kiosk paneldeki PC'ye java uygulaması kurulacaktır. (Kiosk.zip) dosyası Netbeans ortamına yüklenip kodlar görüntülenebilir/düzenlenebilir. Netbeans ortamında uygulama çalıştırılabilir.
*Kiosk paneldeki PC, master arduinoya COM3 portu üzerinden bağlanacaktır. Başka bir port kullanılmak istenirse Java uygulamasındaki (webServer.java) dosyasından değiştirilebilir.
*Master arduino ve slave arduino kodları (Arduino) klasöründe bulunmaktadır. Gerekli pin bağlantılarını kodlar içerisinde yada fritzing çizimlerinde bulabilirsiniz.
*Switchler üzerinden dolapların ID'leri ayarlanabilir. ID'ler ayarlandıktan sonra sisteme enerji verilmelidir.
