# Misyonerler ve Yamyamlar

Misyonerler ve Yamyamlar problemi, Java dilinde genişlik öncelikli arama yöntemi kullanılarak çözülmüştür. 

Ana sınıfa (main class), GenislikOncelikliArama adı verilmiştir. Kıyılara gidip gelme durumlarının kontrolünün sağlanması açısından Durum adında bir sınıf kullanılmıştır. 

Durum sınıfında misyoner ve canavarların sayısı, botun sol/sağ kıyıda olması durumu ve hangi durumdan gelindiği gibi değişkenler tutulur. Ayrıca her tekne seferinde elde edilen sonuçlar döndürülür ve değişken değerlerinde hatalar çıkmaması adına boolean metot ile kontrol edilir. 

Ana sınıfta ise sağ kıyı tamamen boş kalana kadar tekne seferlerinin sağlanması için işlemler yapılır. Misyoner, yamyam ve botun sol/sağda olması ile ilgili bilgiler bir kuyruk yapısında tutulur. Başlangıç durumu olan (3, 3, L)'den (0, 0, R)'ye ulaşacak en kısa yöntem while döngüsü aracılığıyla sağlanır. 
En son olarak kaç tekne seferinde son duruma ulaşıldığının bilgisi verilmektedir.

Daha önceden yapılmış uygulamanın linki: http://cs.calstatela.edu/wiki/index.php/Courses/CS_460/Fall_2006/Shakil,_Farrukh/Missionaries_and_Cannibals_using_Search_Algos
