### Programlama Paradigmları 
> 2 kategoriye ayrılmaktadır 
> Bu iki kategori imperative(zorunlu) ve declarative(bildirimsel) programlamadır

> **İmperative** 
>- Nesne Yönelimli Programlama
>- Yapılandırılmış Programlama
>- Prosedürel Programlama


>Program akışı developer tarafından kontrol edilmesi istenir. Odaklanılacak nokta **NASIL**'dır
>Metot içerisinde yapılan bir değişiklik global olarak değişikliyi etkilyebilir. Bu side effect'tir. 
> Kaynak yönetimi developerlar tarafından halledilmelidir.
> Paralel Programlama frameworkler tarafından halledilir.

>
>**Declaritive**
>- Fonksiyonel Programlama
>- Mantıksal  Programlama
>- Veri Odaklı Programlama

>Sonuca odaklıdır. Ne yapmak istiyorsun sorusu ana sorudur. Kontrol developer tarafından değil declaritive programlama tarafından halledirilir. 

> Side effect minimalize edilemeye çalışılmıştır. Tanımlanan değişkenler her zaman aynı sonucu verilmesi için immutable olarak işaretlenmiştir.
> Kaynak yönetimi declaritive programlama tarafından yapılır
> Side effect minimal düzeyde olduğu için parallel programlama çok daha kolay halledirilir. 