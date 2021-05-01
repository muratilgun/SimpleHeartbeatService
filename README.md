# Simple Windows Service



Windows servicemi debug etmesi daha kolay olduğu için, windows console uygulaması olarak yazıyorum. Uygulamayı ayağa kaldırıp
txt dosyamı kontrol ediyorum çalıştığına emin olduktan sonra, 
önetici olarak cmd'yi açıp service exemin bulunduğu klasörün içerisine giriyorum. 
Daha sonra service "SimpleHeartbeatService.exe install start" yazarak yüklüyorum ve başlatıyorum. 
windows servicelerimden çalıştığını kontrol edip, tekrar loglama dosyasına göz attıktan sonra servicemi durdurup, exemin olduğu klasörün içine girdikten sonra
exemin ismini yazıp  "SimpleHeartbeatService.exe uninstall"  yazıp servicemi siliyorum. Servicelerimi tekrar kontrol ettiğimde silindiğini görüyorum.
