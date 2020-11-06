##### Yeni bir Gitthub repository oluştururken, repomuza ekleyebileceğimiz lisanslar nelerdir, bu lisanslar arasındaki farklar nelerdir?

**MIT:** Dünya üzerinde en yaygın kullanılan, Massachusetts Teknoloji Enstitüsü tarafından geliştirilmiş, işlevsel bir lisans türüdür. MIT Lisansı ile yazılıma ait kaynak kodlar hem yazılımı imal edenler hem de açık kaynak kodlara erişerek yazılımı geliştirenler tarafından istenildiği ölçüde değiştirilebilir, yeni versiyonları geliştirilebilir, kopyalanabilir, satılabilir, yayılabilir, alt lisanslama yapılabilir ve dağıtılabilir. Yazılımın tüm kopyalarına ve önemli parçalarına eklenmesi gereken aşağıdaki MIT Lisans Metni incelendiğinde de görülecektir ki, yazılımı imal eden, geliştiren veya sair şekilde yazılımı kullanan tarafların hiçbir hukuki sorumluluğu bulunmamaktadır.

**Apache License: **Apache Lisansı, aynı tür bir yazılım kullanılarak dağıtılması için yazılımın bir türev çalışmasını veya orijinalinde değişiklik yapılmasını gerektirmemesine izin verir. Yine de aynı lisansın değiştirilmemiş tüm parçalara uygulanmasını gerektirir ve her lisanslı dosyada yeniden dağıtılan koddaki orijinal telif hakkı, patent, ticari marka ve atıf bildirimleri korunmalıdır (türev çalışmaların herhangi bir kısmı ile ilgili olmayan bildirimler hariç); ve değiştirilen her lisanslı dosyada bu dosyada değişiklik yapıldığını belirten bir bildirim eklenmelidir.

**GNU:** GNU yada Genel Kamu Lisansı olarak adlandırılan bu lisans sayısız yazılım ve dağıtımın içerisinde kullanılan özgür bir lisans türüdür. Bu lisans türünde hem kullanıcılar hem de yayıncılar için bazı çeşitli özgürlükler tanınmıştır. GNU lisansıyla korunan yazılımlar başkaları tarafından değiştirilebilir ve nasıl çalıştığı anlaşılmak için görülebilir yazılımlardır. GNU lisansı özellikle insanları program geliştirmeye ve tamamen özgür programlardan oluşan bir bilgisayar dünyası oluşturmaya yönelik atılmış bir adımdır.

##### Merge- Squash- Rebase arasındaki farklar nelerdir?
**Git merge** ile yaptığımız birleştirmede yeni bir commit yaratacak ve yeni branch'deki tüm history tarafını kaybetmeden birleştirme işlemi gerçekleşmiş olcaktır.
**Git squash** komutu aslında farklı bir rebase kullanımı olarak değerlendirmek daha doğru olacaktır. Geçmişte atılan commit'leri yeniden düzenlemek, isimlendirmek veya birleştirmek için kullanıyoruz.
**Git rebase** ile birleştirdiğimizde ise branch deki commit'lerimizi tek tek alıp istediğmiz branch üzerine ekleyecektir. Böylelikle tek bir history oluşturacak ve istenmeyen history ortadan kalkacaktır.

##### Agile-Scrum-Kanban kavramlarını araştırınız
**Agile** metodu, yapılacak işlerin önem sırasına göre yapılması gerektiğini öne sürer. Bu metodolojiye göre projenin en iyi şekilde ortaya konulması için kaynaklar ve ekip özenli bir hazırlık süreci geçirmelidir. Agile metodunun temel esasları şöyle sıralanabilir:
- Deneysellik
- Önceliklendirme
- Kendi kendini örgütleme
- Zaman çerçevesi
- İş birliği

Agile yöntemi, bu esaslardan birini atlayarak yönetilen bir projenin başarısız olacağını ileri sürmektedir. Agile yöntemine göre bu esaslar titizlikle uygulandığında; projede risk faktörü azalacak, olası hatalar ortaya çıkacak, hatalar erkenden tespit edilecek ve ürün pazara daha çabuk ulaşacaktır.

**Scrum**, projeyi küçük parçalara ayırarak yönetmeyi önerir. Bu sayede her parça tek tek incelenip gerekli değişiklikler yapılabilir. Bir parçada olan sorun daha kolay bulunabilir. Scrum’a göre proje yönetilirken müşteri ile daima iletişim halinde olunması gerekir. Scrum’un projeyi küçük parçalara ayırmasındaki en temel sebeplerden birisi, müşterilerin isteklerine göre projenin şekillendirilmesini kolaylaştırmaktır. Scrum 3 temel üzerine oturtulmuştur:

- Şeffaflık
- Kontrol edilebilme
- Uyumluluk

**Kanban**, bir süreçten geçerken işi yönetmek için malzeme hareketlerinin kontrolü amacıyla kullanılan ve çizelgelerden oluşan görsel bir sistemdir. Kanban hem süreci (iş akışı) hem de o süreçten geçen gerçek işi görselleştirir. Kanban'ın amacı, sürecinizdeki aksaklıkları tanımlamak ve bunları düzeltmektir, böylece iş en uygun hızda veya verimde gerçekleşebilir. 

##### Github Flow'un alternatifleri nelerdir? Artılarını ve eksilerini karşılaştırınız.Github Flow'un alternatifleri nelerdir? Artılarını ve eksilerini karşılaştırınız.
- Git
- pre-commit
- Atlassian Stash
- Diff So Fancy
- TortoiseGit
- Git-Repo
- GVFS
- pre-commit by Yelp

##### Gang of Four(GOF) araştırınız.
**Gang of Four** topluluğu tarafından yayınlanan tasarım desenleri, Nesne Yönelimli Programlamada karşılaşılmış tasarım sorunlarına üretilmiş optimum  çözümler olarak tanımlanabilir. Tasarım desenleri bizlere daha yönetilebilir ve okunabilir kod yazmak konusunda avantajlar sağlar. Bunun yanında performans ve geliştirilebilirlik konusunda da katkıları vardır. Tasarım desenleri genel olarak 3 başlık altında toplanır. Bunlar;
**Creational Patterns-Kurucu Desenler:** Nesnelerin oluşturulması ile ilgili patternlerdir.
**Structural Patterns – Yapısal Desenler:** Nesnelerin birbiri ile olan ilişkisini konu alır.
**Behavioral Patterns – Davranışsal Desenler:** Sınıfların bir görevi yerine getirirken nasıl davranacağı ile ilgili desenlerdir.

##### Interface ve Abstract sınıflar arasındaki farklar nelerdir?
**Abstract:**
Yazdığımız sınıflar arasında inheritance(kalıtım) uygularken kullanırız. Alt sınıflar abstractsınıfı inherit alırlar. Abstract class içindeki implement edilmiş tüm method’lar diğer class'da da geçerlidir.

Abstract classdan implement ettiğimiz bir class içerisinde, sadece abstract class içerisinde abstract olarak tanımlanmış method, property gibi vb.lerini implement etmek mecburidir. Diğer method'lar zaten tanımlıdır ve implement edilmesi mecburi değildir.

Abstract sınıflar genelde **is-a** ilişkilerinde kullanılır.
Örnek vermek gerekirse;

*+Ferrari is-a Araba*

Ferrari bir arabadır ve arabanın sahip olduğu tüm özelliklere sahiptir.

**Interface:**
Interface sınıfında sadece method tanımları bulunur. İçlerine kod parçacığı yazılmaz. İçerisinde tanımlanan method tanımları bu interface'i implemente edecek diğer sınıflar tarafından implement edilmesi zorunludur.

Interfaceler başka bir interface den inherit olabilirler.
Interface’ler genelde **can-do** ilişkisi vardır.

Örnek vermek gerekirse;

*+Ferrari can-do drive itself*

Ferrari kendi kendini sürebilir. Gibi yapabileceği ek özellikler interface olarak tanımlanıp, implemente edilebilir.
