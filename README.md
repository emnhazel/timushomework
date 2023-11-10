# 1)JavaScript Nedir,Tarihi?

JavaScript, web geliştirme alanında kullanılan bir tarayıcı tabanlı programlama dilidir ve web sayfalarının etkileşimli ve dinamik hale getirilmesi için kullanılır. Dilin tarihi 1995 yılına dayanır. Brendan Eich, Netscape Communications Corporation'da çalışırken bu dili geliştirdi. İlk sürümü, 1996 yılında Netscape Navigator 2.0'de tanıtıldı. Başlangıçta "LiveScript" olarak adlandırıldı, daha sonra "JavaScript" olarak değiştirildi. ECMAScript standardizasyon süreci 1997 yılında başladı ve dilin evrimini şekillendirdi. Önemli dönüm noktaları arasında ECMAScript 3 (1999) ve ECMAScript 5 (2009) bulunurken, en büyük değişim ECMAScript 2015 (ES6) ile 2015 yılında yaşandı. Bu tarihten itibaren JavaScript sürekli gelişmeye devam ediyor ve web geliştirme alanında temel bir araç haline geldi.

# 2)Java Ve JavaScript Farkı Nedir?

Java ve JavaScript, isim benzerliklerine sahip olsalar da tamamen farklı dillerdir. Java, nesne yönelimli bir dil olup sunucu taraflı uygulamalar ve masaüstü uygulamalar için kullanılırken, JavaScript tarayıcı tabanlı bir betik dilidir ve web sayfalarının etkileşimli hale getirilmesi için kullanılır. Java daha sıkı, derlenmiş bir dildir ve platform bağımsızdır, JavaScript ise tarayıcı bağımlıdır ve dinamik olarak yorumlanır.

# 3)JavaScript'teki Veri Tipleri

JavaScript'te veri tipleri "ilkel" ve "nesne" kategorilerine ayrılır. İlkel veri tipleri arasında metin (String), sayı (Number), mantıksal (Boolean), tanımsız (Undefined), boş (Null) ve sembol (Symbol) yer alır. Nesne veri tipleri ise nesne (Object), dizi (Array), fonksiyon (Function), tarih (Date) ve kullanıcı tanımlı diğer nesneleri içerir.

# 4)Null Ve Undefined Farkı

Null ve Undefined, JavaScript'te farklı değerleri temsil ederler. Undefined, bir değişkenin veya değerinin atanmamış veya tanımlanmamış olduğu durumu ifade ederken, Null bilinçli bir şekilde bir değişkenin veya nesnenin boş veya eksik olduğunu belirtmek için kullanılır.

# 5)NaN Nedir

NaN (Not-a-Number), matematiksel işlemlerde geçersiz veya sayı olmayan bir değeri temsil eden özel bir değerdir.

# 6)JavaScript'te Yorum Satırı

JavaScript'te yorum satırı eklemenin iki farklı yolu vardır: Tek satırlık yorumlar (//) ve çok satırlık yorumlar (/* ... */). Tek satırlık yorumlar tek bir satırı yorum olarak işlerken, çok satırlık yorumlar arasındaki tüm metni yorum olarak kabul ederler.

# 7)Global Değişken Nedir?

Global değişken, bir programın herhangi bir yerinden erişilebilen ve değiştirilebilen bir değişkendir. Genel kapsamda tanımlandığı için programın herhangi bir bölümünde kullanılabilir.

# 8)JavaScript'te this Nedir?

JavaScript'te this, bir fonksiyonun veya bir nesne yönteminin içinde kullanıldığında, o anda geçerli olan bağlamı veya kapsamı temsil eden bir referanstır. this kelimesi, kullanıldığı bağlama (context) ve bağlamın türüne göre farklı değerler temsil edebilir. Özellikle nesne yönelimli programlamada, this sıklıkla nesne içindeki özelliklere ve yöntemlere erişmek için kullanılır.

# 9)== ile === Farkı Nedir?

JavaScript'te == ve === iki farklı karşılaştırma operatörüdür ve farkları şu şekildedir:

== :

İki değeri karşılaştırırken, sadece değerlerin eşit olup olmadığını kontrol eder. Tür dönüşümü yapar, yani veri tiplerini karşılaştırırken dönüştürebilir.
```javascript
5 == "5" // true, değerler eşit, tür dönüşümü yapar
true == 1  // true, değerler eşit, tür dönüşümü yapar
null == undefined // true

```
=== :

İki değeri karşılaştırırken, hem değerlerin hem de veri tiplerinin eşit olup olmadığını kontrol eder. Tür dönüşümü yapmaz.
```javascript
5 === "5" // false, değerler eşit ama türleri farklı
true === 1  // false, türleri farklı
null === undefined // false, türleri farklı
```
# 10)Let,var,const Farkı Nedir?

| Özellik    | `var`               | `let`              | `const`            |
|------------|---------------------|--------------------|--------------------|
| Kapsam     | Function ve Global | Block, Function     | Block, Function    |
| Tekrar Atanabilir | Evet              | Evet               | Hayır              |
| Hızlı Oluşturma | Evet              | Evet               | Hayır              |
| Temporal Dead Zone | Hayır          | Evet               | Evet               |

# 11)Arrow Function Ve Normal Function Arasındaki Fark Nedir?

Arrow fonksiyonlar (=>) ve normal fonksiyonlar (function) JavaScript'te iki farklı fonksiyon tanımlama yöntemidir; Arrow fonksiyonlar daha kısa sözdizimleri ve sabit this bağlamı ile tanınırken, normal fonksiyonlar daha uzun sözdizimi, değişen this bağlamı ve daha fazla esneklik sunar. Arrow fonksiyonları genellikle kısa ve basit fonksiyonlarda tercih edilirken, normal fonksiyonlar daha karmaşık senaryolarda kullanılır.

# 12)Switch Bloku İçinde Değişken Nasıl Tanımlanır?

Switch bloğu içinde değişken tanımlamak yerine değişkeni önceden tanımlamanız gerekir. Değişken tanımlamaları, switch ifadesinin dışında veya öncesinde yapılmalıdır. switch ifadesi, yalnızca değişkenin değerini kontrol eder ve farklı durumları işler. Bu, kodun daha okunaklı ve yönetilebilir olmasını sağlar.

# 13)Pure Function Nedir?

Pure function (saf fonksiyon), aynı girdiye (input) her zaman aynı çıktıyı (output) üreten ve herhangi bir yan etkisi olmayan bir fonksiyon türüdür. Yan etki, bir fonksiyonun dış dünyayı değiştiren veya başka değişkenleri etkileyen işlemler yapması anlamına gelir. Saf fonksiyonlar, kodun daha öngörülebilir ve test edilebilir olmasını sağlar çünkü aynı girdiye verilen her çağrı aynı sonucu üretecektir. Bu, kodun hata ayıklanmasını ve bakımını kolaylaştırır ve işlevselliği daha iyi anlamamıza yardımcı olur.

# 14)Rest Operatör Nedir?

Rest operatörü (...) JavaScript'te, fonksiyonlarda birden fazla argümanı bir diziye toplamak veya dizilerde belirli elemanları bir diziye toplamak için kullanılan bir operatördür.

```javascript
const dizi = [1, 2, 3, 4, 5];

const [ilkEleman, ikinciEleman, ...geriKalanElemanlar] = dizi;

console.log(ilkEleman); // 1
console.log(ikinciEleman); // 2
console.log(geriKalanElemanlar); // [3, 4, 5]

```
# 15)Object Destructuring Nedir?

Object destructuring, JavaScript'te bir nesnenin içindeki özellikleri (properties) ayrıştırarak ayrı değişkenlere atama yapmayı sağlayan bir özelliktir. Bu, nesne içeriğini daha erişilebilir hale getirir ve kodu daha okunaklı kılar. Object destructuring, özellikle fonksiyonların dönüş değerlerini ve nesneleri işlerken kullanışlıdır.
```javascript
const kullanici = {
    ad: "John",
    soyad: "Doe",
    yas: 30
};

// Object destructuring kullanarak nesnenin özelliklerini ayrıştırma
const { ad, soyad, yas } = kullanici;

console.log(ad); // "John"
console.log(soyad); // "Doe"
console.log(yas); // 30
```
# 16)2 Elemanlı Bir Objeyi 6 Farklı Şekilde Oluşturma
Object Literal:
```javascript
const object1 = { key1: "value1", key2: "value2" };
```
 Object Constructor Function:
 ```javascript
function CreateObject(key1, key2) {
  this.key1 = key1;
  this.key2 = key2;
}
const object2 = new CreateObject("value1", "value2");
```
Object Method:
```javascript
const object3 = Object.create(null);
object3.key1 = "value1";
object3.key2 = "value2";
```
 Object Literal and Object Method:
 ```javascript
const key1 = "value1";
const key2 = "value2";

const object4 = {
  [key1]: "value1",
  [key2]: "value2"
};
```
Object.assign:
 ```javascript
const object5 = Object.assign({}, { key1: "value1", key2: "value2" });
```
Object Literal and Rest Operator:
 ```javascript
const { key1, key2 } = { key1: "value1", key2: "value2" };
const object6 = { key1, key2 };
```
# 17) 2 Elemanlı Bir Objenin Key Ve Value Değerlerinin Karakter Sayısı İle 2 Farklı Döngü Methodu Kullanarak Yeni Bir Obje Oluşturma

 ```javascript
const originalObj = {
  key1: "value1",
  key2: "value22"
};

const newObj = {};

// Using Object.entries() and forEach
Object.entries(originalObj).forEach(([key, value]) => {
  const newKey = key + "_char";
  const newValue = value.length;
  newObj[newKey] = newValue;
});

console.log(newObj);
```
# 18) Cookie, Local Storage Ve Session Storage Farkı

| Özellikler          | Çerezler (Cookies)                   | Local Storage                        | Session Storage                      |
| ------------------- | ----------------------------------- | ------------------------------------ | ------------------------------------ |
| Ömür Süresi         | Belirli bir süre veya süresiz         | Kalıcı, elle silinene kadar         | Oturum sona erdikten sonra otomatik silinir |
| Kullanım Amaçları   | Oturum kimlikleri, tercihler, izleme | Veri saklamak için tercih edilir     | Geçici verilerin saklanması için tercih edilir |
| Veri Erişimi        | Sunucu ve istemci tarafından erişilebilir | Sadece istemci tarafından erişilebilir | Sadece istemci tarafından erişilebilir |
| Veri Saklama Kapasitesi | Genellikle 4 KB boyutunda veri saklama kapasitesine sahiptir | Genellikle en az 5 MB boyutunda veri saklama kapasitesine sahiptir | Genel

# 19)Asenkron Ve Senkron İşlem Farkı Nedir?

Asenkron işlem ve senkron işlem arasındaki temel fark, işlemlerin nasıl çalıştığı ve tamamlandığı zaman dilimindedir. Senkron işlemler sırasıyla ve adım adım gerçekleştirilirken, asenkron işlemler işlemleri sıraya bağlı kalmadan başlatır ve diğer işlemleri beklemeksizin devam ettirir. Asenkron işlemler özellikle uzun süren işlemleri veya giriş/çıkış işlemlerini daha verimli bir şekilde yönetmek için kullanılır ve uygulamanın yanıt vermesini hızlandırır. Senkron işlemler ise sıraya bağlı kalmakla karakterizedir ve bir işlem tamamlanmadan diğerine geçer. Bu temel farklar, işlem yönetimi ve uygulama performansını etkiler.

# 20)Promise Nedir?
Promise, JavaScript'te asenkron işlemleri düzenlemek ve işlem sonuçlarını işlemek için kullanılan bir yapıdır. İşlem sonucunu beklerken hata yönetimi yapmayı, kod okunabilirliğini artırmayı ve çoklu asenkron işlemleri kolayca yönetmeyi sağlar. Promise, asenkron görevlerle çalışırken JavaScript uygulamalarını daha etkili hale getiren önemli bir araçtır.

# Array Methodları
# 1)
```javascript
var dolap=["Shirt", "Pant" ,"TShirt"];
dolap.pop();
console.log(dolap);
```
# 2)
```javascript
var dolap=["Shirt", "Pant" ,"TShirt"];
dolap.splice(0,1,'Hat');
console.log(dolap);
```
# 3)
```javascript
var dolap=["Shirt", "Pant" ,"TShirt"];
console.log(Array.isArray(dolap));
```
# 4)
## includes()
```javascript
var dolap=["Shirt", "Pant" ,"TShirt"];

const varMi="Pant";
if(dolap.includes(varMi)){
    console.log(`${varMi} elemanı dizide bulunuyor`);
}else {
    console.log(`${varMi} elemanı dizide bulunmuyor`)};
```
## indexOf()
```javascript
var dolap=["Shirt", "Pant" ,"TShirt"];
const indexofElement=1;
if(dolap.indexOf(indexofElement) !== -1){
    console.log(`${indexofElement} elemanı dizide bulunuyor`);
}else {
    console.log(`${indexofElement} elemanı dizide bulunmuyor`)};
```
## find()
```javascript
var dolap = ["Shirt", "Pant", "TShirt"];
const arananEleman = "Pant";

const bulunanEleman = dolap.find(eleman => eleman === arananEleman);

if (bulunanEleman !== undefined) {
    console.log(`${arananEleman} bulundu.`);
} else {
    console.log(`${arananEleman} bulunamadı.`);
}
```
# 5)
```javascript
var dolap = ["Shirt", "Pant", "TShirt"];
 
const elemanTopla=()=>{
    let toplam=0;
    for(i=0;i<dolap.length;i++){
        toplam+=dolap[i].length;
    }
    return toplam;
}

const sonuc=elemanTopla();
console.log(sonuc);
```
# 6)
## map()
```javascript
var dolap = ["Shirt", "Pant", "TShirt"];

const buyukHarf=dolap.map(eleman=>eleman.toUpperCase());
console.log(buyukHarf);
```
## forEach()
```javascript
var dolap = ["Shirt", "Pant", "TShirt"];

const buyukHarf2 = [];
dolap.forEach(eleman => buyukHarf2.push(eleman.toUpperCase()));

console.log(buyukHarf2);
```
## for
```javascript
var dolap = ["Shirt", "Pant", "TShirt"];

const buyukHarf3=[];
for(i=0;i<dolap.length;i++){
    buyukHarf3.push(dolap[i].toUpperCase());
}
console.log(buyukHarf3);
```
# 7)
```javascript
var dolap = ["Shirt", "Pant", "TShirt"];

const dolapObj=[];

dolap.forEach((eleman,index)=>{
    dolapObj[index]=eleman;
}
)
console.log(dolapObj);
```
# 8)Slice Splice Farkı

Slice metodu, bir dizinin belirli bir bölümünü seçmek için kullanılır ve orijinal diziyi değiştirmez. Splice metodu ise bir dizinin içeriğini değiştirmek için kullanılır, belirli bir bölgesini silebilir veya yeni elemanlar ekleyebilir. Splice metodu orijinal diziyi değiştirir.

# 1.Kod Çıktısı
* Error 1
* Success 4

Bu JavaScript kodu, bir Promise nesnesi oluşturan job fonksiyonunu içerir. Bu promise hemen reddedilir (reject). Daha sonra gelen promise.then() zinciri, bu reddedilme durumunu takip eden bir catch bloğu içerir. Dolayısıyla, promise reddedildiğinde, catch bloğu çalışır ve "Error 1" yazdırılır. Daha sonra gelen herhangi bir .then() bloğu bu durumdan bağımsız olarak çalışır, bu nedenle "Success 4" yazdırılır. Bu durum, Promiselerin zincirleme ve ardışık işlemlerin kontrolü sağlayan özelliklerinden birini gösterir.

# 2.Kod Çıktısı
* success
* Defeat
* error
* Success: test

Bu JavaScript kodu, bir dizi Promise zinciri oluşturur. İlk promise başarıyla tamamlanır ve "success" değeri yazdırılır. Ancak, ikinci promise zincirinde "victory" olmayan bir durum oluşturularak "Defeat" hatası catch bloğuna yönlendirilir ve yazdırılır. Daha sonra, bir reject durumunu simgeliyerek "error" yazdıran bir promise, bir .catch() bloğu içinden geçirilir. Ardından bir string ("Error caught") yazdırılır. Sonrasında, bir hata oluşturulup yakalanarak "Error: test" yazdırılır. Bu durumda, başarılı ve hata durumları sırayla "success", "Defeat", "error", ve "Error: test" çıktısını üretir.
