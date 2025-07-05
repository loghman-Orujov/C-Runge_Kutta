Kullanıcının girdiği bir diferansiyel denklemin çözümünü, belirli bir başlangıç noktasından itibaren Runge-Kutta-4 yöntemiyle adım adım hesaplar ve her adımda yaklaşık çözümü, gerçek değeri ve hatayı gösterir.
Analitik (doğrudan) çözümün zor veya imkânsız olduğu diferansiyel denklemler için sayısal çözüm elde etmek gerekir. Bu program, RK4 yöntemini kullanarak bu sayısal çözümü sağlamayı amaçlar.
Kullanıcıdan denklemdeki terimlerin katsayı ve derecelerini alır → denklem.katsayilar[], denklem.dereceler[]
Başlangıç değerlerini (x0, y0), adım boyutunu (h), iterasyon sayısını ve gerçek çözüm değerini alır.
rungeKutta(...) fonksiyonu:
RK4 formülünü uygulayarak yeni y değerini hesaplar.Her adımda:Güncel x,y değerlerini, gerçek çözümü, gerçek ve yaklaşık çözüm arasındaki hatayı hesaplayıp yazdırır.
