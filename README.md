
## Kurulu Olması Gerekenler
Projeyi kendi localinizde çalıştırmak için gerekli olan kurulumları tamamlamalısınız.

- Node.js
- Angular cli 13.1.1 versiyonu
- VS Code 


## To-Do's With AngularJS
Bu proje, AngularJS kullanılarak hem angularjs syntax'i hakkında fikir sahibi olmak hemde bir angular projesinde kullanılabilecek bir kaç özelliğin projeye nasıl dahil edilebileceği hakkında bilgi sahibi olmak amacı ile hazırlandı.

## Proje
Proje genel hatları ile kullanıcı tarafından girilen verilerin .json formatındaki bir dosya içerisinde tutularak kullanıcıya daha önceden girdiği verilerin gösterilmesi, girilen verilerin silinebilmesi ve hatırlatıcı gibi özellikleri barındırmaktadır.

Projede dahilinde AngularJS tarafında bulunan ve kullanılan geliştirmecilere kolaylıklar sağlayan component ve module'ler yer almaktadır bu gibi component ve modelleri oluşturmak için proje dosyasının içerisinde olmak şartı ile açılan terminal'e aşağıdaki gibi yazılarak oluşturulabilir.




```bash
ng generate component component-name
```


Kısa gösterimler şeklinde de kabul etmektedir. Örneğin;

```bash
ng g c component-name
```

ComponentFolder adında bir klasör içerisinde oluşturulmak istendiğinde

```bash
ng g c ComponentFolder/component-name
```

Module'ler için tek bir değişiklik yerli olmaktadır. Yukarıdaki örneklerde yer alan 'c' parametresinin yerinde 'm' harfi veya 'module' yazmanız yeterli olacaktır.

```bash
ng g m module-name
```

  
## Bilgisayarınızda Çalıştırın

İndirme işlemleri ve gerkli kurulumlardan sonrasında klasörü açtıktan sonrasında terminale 
aşağıdaki kodu yazarak projenin local host üzerinde açılması sağlanmaktadır fakat yeterli değildir. Önceden de belirttiğim gibi verilen json formatındaki bir dosya içerinde tutulmaktadır. Bu neden ile bu dosyada çalıştırılmalıdır.
Proje çalışması için ;

```bash
ng serve
```
db.json Dosyası için ;

```bash
npm run server
```


## Ekran Çıktısı

https://user-images.githubusercontent.com/66949465/220906306-99b013ea-4528-405e-96e5-68f2ed3e8d4f.mp4

