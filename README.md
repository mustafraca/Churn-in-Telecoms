# Churn-in-Telecoms
Churn in Telecoms veri seti bir telekom şirketinin müşterileri hakkında veriler içerir. Her satır bir müşteriyi temsil eder ve sütunlar müşterinin özelliklerini içerir.<br>
state: kullanıcının yaşadığı eyalet
account length: kullanıcının bu hesaba sahip olduğu gün sayısı
area code: kullanıcının yaşadığı alanın kodu
phone number: kullanıcının telefon numarası
international plan: kullanıcı uluslararası plana sahipse True, aksi takdirde False
voice mail plan: kullanıcı sesli posta planına sahipse True, aksi takdirde False
number vmail messages: kullanıcının gönderdiği sesli posta iletilerinin sayısı
total day minutes: kullanıcının gün içinde arama yaptığı toplam dakika sayısı
total day calls: kullanıcının gün içinde yaptığı toplam çağrı sayısı
total day charge: kullanıcının gün içerisinde yaptığı aramalar için Telekom şirketi tarafından alınan toplam para miktarı
total eve minutes: kullanıcının akşam boyunca görüşme yaptığı toplam dakika sayısı
total eve calls: kullanıcının akşam yaptığı toplam çağrı sayısı
total eve charge: kullanıcının akşam aramaları için Telekom şirketi tarafından alınan toplam para miktarı
total night minutes: kullanıcının gece boyunca görüşme yaptığı toplam dakika sayısı
total night calls: kullanıcının gece boyunca yaptığı toplam çağrı sayısı
total night charge: kullanıcının gece aramaları için Telekom şirketi tarafından alınan toplam para miktarı
total intl minutes: kullanıcının uluslararası aramalarda bulunduğu toplam dakika sayısı
total intl calls: kullanıcının yaptığı uluslararası aramaların toplam sayısı
total intl charge: kullanıcının uluslararası aramaları için Telekom şirketi tarafından alınan toplam para miktarı
customer service calls: kullanıcının yaptığı müşteri hizmeti çağrılarının sayısı
churn: kullanıcı sözleşmeyi feshettiğinde True, aksi takdirde False
Veri setinde bağımlı değişken “churn” olmaktadır. Müşteri, aboneliği iptal etti mi sorusunun cevabını içermektedir. Ayrıldı ise True, ayrılmadı ise False değeri olmakta. Yani hedef öznitelik “churn” seçilir ve tahmine dayalı analiz yapılır. Bu bir sınıflandırma problemidir.
