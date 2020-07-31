# Churn-in-Telecoms
Churn in Telecoms veri seti bir telekom şirketinin müşterileri hakkında veriler içerir. Her satır bir müşteriyi temsil eder ve sütunlar müşterinin özelliklerini içerir.<br>
state: kullanıcının yaşadığı eyalet<br>
account length: kullanıcının bu hesaba sahip olduğu gün sayısı<br>
area code: kullanıcının yaşadığı alanın kodu<br>
phone number: kullanıcının telefon numarası<br>
international plan: kullanıcı uluslararası plana sahipse True, aksi takdirde False<br>
voice mail plan: kullanıcı sesli posta planına sahipse True, aksi takdirde False<br>
number vmail messages: kullanıcının gönderdiği sesli posta iletilerinin sayısı<br>
total day minutes: kullanıcının gün içinde arama yaptığı toplam dakika sayısı<br>
total day calls: kullanıcının gün içinde yaptığı toplam çağrı sayısı<br>
total day charge: kullanıcının gün içerisinde yaptığı aramalar için telekom şirketi tarafından alınan toplam para miktarı<br>
total eve minutes: kullanıcının akşam boyunca görüşme yaptığı toplam dakika sayısı<br>
total eve calls: kullanıcının akşam yaptığı toplam çağrı sayısı<br>
total eve charge: kullanıcının akşam aramaları için telekom şirketi tarafından alınan toplam para miktarı<br>
total night minutes: kullanıcının gece boyunca görüşme yaptığı toplam dakika sayısı<br>
total night calls: kullanıcının gece boyunca yaptığı toplam çağrı sayısı<br>
total night charge: kullanıcının gece aramaları için Telekom şirketi tarafından alınan toplam para miktarı<br>
total intl minutes: kullanıcının uluslararası aramalarda bulunduğu toplam dakika sayısı<br>
total intl calls: kullanıcının yaptığı uluslararası aramaların toplam sayısı<br>
total intl charge: kullanıcının uluslararası aramaları için telekom şirketi tarafından alınan toplam para miktarı<br>
customer service calls: kullanıcının yaptığı müşteri hizmeti çağrılarının sayısı<br>
churn: kullanıcı sözleşmeyi feshettiğinde True, aksi takdirde False<br><br>
Veri setinde bağımlı değişken “churn” olmaktadır. Müşteri, aboneliği iptal etti mi sorusunun cevabını içermektedir. Ayrıldı ise True, ayrılmadı ise False değeri olmakta. Yani hedef öznitelik “churn” seçilir ve tahmine dayalı analiz yapılır. Bu bir sınıflandırma problemidir.
