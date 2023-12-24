# pytest_decorator
Dekoratör, Python'da kullanıcının mevcut bir nesneye yapısını değiştirmeden yeni işlevler eklemesine olanak tanıyan bir tasarım desenidir. Dekoratörler genellikle dekore etmek istediğiniz fonksiyonun tanımından önce çağrılır.Bu decorator'lar, pytest'in esnek test düzenleme ve yürütme yeteneklerini artırmak için kullanılır. Bu örnekler, genelde karşılaşılan durumları kapsar, ancak pytest daha birçok özellik sunar ve kullanıcıların testlerini özelleştirmelerine olanak tanır.

@pytest.fixture: Bir testin önkoşullarını ayarlamak ve temizlemek için kullanılır. Fixture'lar, test fonksiyonlarına özel ortamlar sağlar.

@pytest.mark.parametrize: Test fonksiyonlarını farklı parametre setleriyle çalıştırmak için kullanılır. Parametrize edilmiş testler, belirli girdi değerleriyle birkaç kez çalıştırılabilir.

@pytest.mark.skip ve @pytest.mark.skipif: Belirli bir testi veya koşulu atlamak için kullanılır. @pytest.mark.skipif, belirli bir koşul sağlandığında testin atlanmasını sağlar.

@pytest.mark.xfail: Bir testin beklenen bir başarısızlık olduğunu belirtir. Test başarısız olursa, bu durum bir hata olarak işaretlenmez.

@pytest.mark.timeout: Bir testin belirli bir süre içinde tamamlanması gerektiğini belirtir. Belirtilen süre aşılırsa, test başarısız olur.

@pytest-lazy-fixture: Bu eklenti, parametrize ile kullanılan fixture'ların daha verimli bir şekilde çalışmasını sağlar. Bu, tüm parametre setleri için tüm fixture'ları her seferinde yeniden hesaplamak yerine, sadece gerçekten ihtiyaç duyulan fixture'ları hesaplamak için gerekli olan parametre setleri üzerinde tembel (lazy) bir yaklaşım kullanır.

@using_email_address: Dekoratörün görevi, mesajın hangi e-posta adresinden gönderileceğine karar vermektir 

@using_email_address: dekoratör mesajın hangi e-posta adresinden gönderileceğiyle ilgilenecektir.

@staticmethod ve @classmethod: Bu decorator'lar, sırasıyla bir sınıfın içindeki bir metodu statik bir metot veya bir sınıf metodu haline getirir.

@property: Bu decorator, bir sınıftaki bir metodu özelliğe dönüştürür ve bu özellik gibi çağrılmasını sağlar.

@functools.wraps kullanarak decorator'lar, dekore edilen fonksiyonun ismi, belgeleme metni ve diğer özelliklerini koruyabilir.


