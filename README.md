# Xp sistemlerde TLS 1.2 update

Xp bilgisayarlarda tls 1.2 güncellemesi olmadığı için outlook 2007 sürümü office 365 veya tls 1.2 bağlantısını kabul eden sistemlere bağlantı gerçekleştirilemiyor.

Bunun için altaki adımları takip etmeniz gerekmekte.

İlk önce tls12-0.reg dosyasını çalıştırın.

Daha sonra sırasıyla windowsxp-kb4019276-x86.exe ve windowsxp-kb4467770-x86.exe kurulumunu yapalım.

Kurulumları yaparken yeniden başlatma seçeneğini seçip ikisini bir kurabilirsiniz.

Daha sonra tls12-1.reg dosyasını çalıştırın.

En son olarak da tls12Winhttp-2.reg dosyasını çalıştırın.

Sisteminizi yeniden başlattığınızda bağlantı sağlandığını göreceksiniz.

Not : Dosyalar zip dosyasının içinde bulunmakta