# generic-java
# Generic
- Türden bağımsız çalışmamızı sağlar
- Farklı türler ile çalışmamıza olanak tanır

## Type kısaltmaları
T : Type<br>
E : element<br>
K : key<br>
N : Number<br>
V : value<br>


- T veya E primitive tipleri hepsi olabilir
- T veya E geri dönüş tipi'de T olur

## Classlar
- generic olarak gösterilebilir. class adının sonuna <T>,<E> şeklinde yazılır
- non-primitive tipler olur(Integer,String)

- generic kullanılınca derleyicinin anlaması için önüne belirtilmeli ve üstüne açıklama yazılmalı
- notasyon ile de belirtilme @SupperssWarnings("")
- extends ile önceden belirte bilinir tip

- compile time'da tip güvenliği sağlıyor
- autoboxing, unboxing cast işlemlerin önüne geçmemizi sağlar
- daha esnek bir yapı haline gelir
- tip güvenliği sağlar

### Methodlar Syntax
`accessModifier <> dönüşTipi methodAdı(){}`

- Dönüş tipide generic olabilir

- Extends ile tiple güvenliğini sağlamaya çalışırız

## Java Generics WildCards 
- PECS : Producer extends(child) - consumer super(parent)
- <> içinde ? kullanılabilir ve adı joker tiptir
- Bir API tasarlanacağı zaman esneklik için bunlar kullanılır
