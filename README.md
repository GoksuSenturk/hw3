# hw3
Geliştirilen algoritma 0-1 knapsack problemini çözmektedir.

Algoritma ilk olarak random bir popülasyon oluşturmakta sonrasında bu popülasyondan random seçtiği iki ebeveyinden crossover yaparak çocuk çözümler üreetmektedir. Oluşturduğu çocuk çözümler ve önceki jenerasyondan aktarılanlar ile yeni bir populasyon oluşturmaktadır.

Algoritma çalışırken o popülasyonda bulunan en iyi fitness değeri hep akılda tutulmaktadır. Sonuç olarak başlangıç çözümünü her popülasyondaki en iyi en kötü ve ortalama çözümlere göre elde edilmiş grafiği, tüm iterasyonlarda bulduğu en iyi çözümü ve bulduğu en iyi çözümler arasındaki en iyiyi sonuç olarak göstermektedir.

fit() = kromozomların fitness değerlerini tutmaktadır.

population () = populasyonları tutmaktadır.

perfect() = o zamana kadar bulunmuş en iyi fitness değerini saklamakatdır.

pop_size, number_of_generations, surv_size , child_proc , mut_prob kullanıcının doğrudan girdiği değerlerdir.

pop_size=popülasyonun büyüklüğünü
number_of_generations = jenerasyon sayısını
surv_size= kromozomların ne kadarının bir sonraki yeni popülasyona direk aktarılacağı oranını
child_proc= ne kadar yeni çocuk üretileceği oranını
mut_prob= popülasyonun yüzde kaçına mutasyon uygulanacağını göstermektedir.
