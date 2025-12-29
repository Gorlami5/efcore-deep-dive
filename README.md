# EF Core Deep Dive

EF Core’un gerçek hayatta geliştiriciler tarafından sıkça kullanılan (ve yanlış kullanılan) özellikleri; performans, change tracking, ilişki yönetimi ve sorgu davranışları gibi başlıklar altında somut örneklerle ele alınmıştır.
Amaç, EF Core’u sadece “kullanan” değil, nasıl ve neden çalıştığını bilen geliştiriciler için referans niteliğinde bir derinlemesine inceleme sunmaktır.

## Bu repo nedir?

Bu repository, Entity Framework Core’un farklı senaryolardaki davranışlarını incelemek amacıyla hazırlanmış,
odaklanmış örnekler ve deneysel çalışmalar içermektedir.

Temel CRUD işlemleri yerine aşağıdaki konulara odaklanılmıştır:
- EF Core’un iç çalışma davranışları
- Performans ve bellek etkileri
- Yaygın kullanılan ama yanlış anlaşılan özellikler
- Gerçek hayatta karşılaşılan problemler ve tuzaklar

Her konu, tek bir davranışı net şekilde gösterecek küçük ve anlamlı örneklerle ele alınmıştır.

## Neden önemli?



## Repository Yapısı

Amaç, her örneğin tek başına okunup anlaşılabilmesidir.


## Örnekleri Çalıştırma

1. Repository’i klonlayın
2. İncelemek istediğiniz klasöre girin
3. Bağımlılıkları yükleyin ve projeyi çalıştırın

## Uyarı

Bu repository teknik bir derinlemesine inceleme kaynağıdır.
Örnekler production ortamları için doğrudan kullanılabilir şablonlar değildir;
belirli davranışları izole şekilde göstermek amacıyla hazırlanmıştır.


Her klasör, tek bir konuya odaklanacak şekilde düzenlenmiştir.
Örnekler birbirinden bağımsız çalışacak şekilde tasarlanmıştır.
