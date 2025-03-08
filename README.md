# Sözlük Sitesi Projesi

Bu proje, modern web teknolojileri ve yazılım mimarileri kullanılarak geliştirilmiş bir sözlük sitesidir. Proje, Blazor, RabbitMQ, .NET 6, Entity Framework 6 gibi teknolojilerin yanı sıra CQRS, Onion Architecture ve MediatR gibi yaklaşımları kullanmaktadır.

## Teknolojiler ve Yaklaşımlar

- **Blazor**: Projenin kullanıcı arayüzü Blazor ile geliştirilmiştir. Blazor, .NET ile modern ve interaktif web uygulamaları oluşturmak için kullanılan bir framework'tür.
  
- **RabbitMQ**: Sistemdeki mesajlaşma ve event-driven mimari için RabbitMQ kullanılmıştır. Bu sayede, uygulama içindeki farklı bileşenler arasında asenkron iletişim sağlanmaktadır.

- **.NET 6**: Proje, .NET 6 platformu üzerine inşa edilmiştir. .NET 6, yüksek performans ve modern yazılım geliştirme özellikleri sunar.

- **Entity Framework 6 (EF6)**: Veritabanı işlemleri için Entity Framework 6 kullanılmıştır. EF6, ORM (Object-Relational Mapping) olarak veritabanı ile nesne yönelimli programlama arasında köprü kurar.

- **CQRS (Command Query Responsibility Segregation)**: CQRS mimarisi, komut (command) ve sorgu (query) işlemlerini birbirinden ayırarak sistemin daha ölçeklenebilir ve bakımı kolay hale gelmesini sağlar.

- **Onion Architecture**: Proje, Onion Architecture (Soğan Mimarisi) prensiplerine göre tasarlanmıştır. Bu mimari, katmanlar arası bağımlılıkları azaltarak daha esnek ve test edilebilir bir yapı sunar.

- **MediatR**: MediatR, CQRS pattern'ini uygulamak ve mediator pattern'ini kullanarak komut ve sorguları yönetmek için kullanılmıştır. Bu, uygulama içindeki bileşenler arasında daha az bağımlılık sağlar.
