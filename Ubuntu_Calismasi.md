MacBook'umda sanal makine olarak Ubuntu kullanmak için öncelikle Ubuntu 24.04 sürümünü indirdim. MacBook'um M3 işlemcili olduğu için ARM64 sürümünü tercih ettim.

Daha sonra Ubuntu'yu çalıştırmak için UTM programını açtım ve yeni bir sanal makine oluşturdum. İşletim sistemi olarak Linux seçtim ve Boot from ISO Image seçeneğinden indirdiğim Ubuntu ISO dosyasını ekledim.

Sanal makinenin RAM'ini 4 GB, CPU'sunu 4 çekirdek ve depolama alanını 64 GB olarak ayarladım. Mimari olarak ARM64 kullandım ve sanallaştırma motorunda QEMU'yu seçtim.

Hardware OpenGL Acceleration seçeneğini kapalı bıraktım çünkü bazı Linux sürücülerinde siyah ekran gibi görüntü sorunlarına neden olabileceği belirtiliyordu.

Ayarları kaydettikten sonra sanal makineyi çalıştırdım. Karşıma çıkan Try or Install Ubuntu seçeneğini seçtim. İlk başta ekranda bazı kod ve sistem yazıları çıktı. Bir süre bekledikten sonra Ubuntu'nun masaüstü açıldı.

Dil seçimini yaptıktan sonra kurulumu tamamladım. Böylece MacBook'um üzerinde UTM kullanarak Ubuntu 24.04 ARM64 sanal makinesini başarıyla kurmuş oldum.