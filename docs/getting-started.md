* [TypeScript'e Başlarken](#typescripte-başlarken)
* [TypeScript Sürümleri](#typescript-sürümleri)
* [Örneklerin Kaynak Kodlarını İndirmek](#Örneklerin-kaynak-kodlarını-İndirmek)

# TypeScript'e Başlarken

TypeScript, JavaScript'e derlenmektedir. Aslında JavaScript sunucu tarafında ya da tarayıcıda çalışacak olan kodun kendisidir. Dolayısıyla uygulamanızı çalıştırabilmek için aşağıdaki kurulumları tamamlamanız gerekmektedir:

* TypeScript derleyicisi ([Kaynak Kodu](https://github.com/Microsoft/TypeScript/) ve [NPM](https://www.npmjs.com/package/typescript) paketi mevcuttur.)
* Bir TypeScript editörü (Notepad ya da diğer birçok editörden bir tanesini kullanabilirsiniz. Örneğin bulut tabanlı olan [alm](http://alm.tools)'nin güzel bir örnek olması yanında [bir çok farklı editör de mevcuttur]( https://github.com/Microsoft/TypeScript/wiki/TypeScript-Editor-Support).)


![](https://raw.githubusercontent.com/alm-tools/alm-tools.github.io/master/screens/main.png)


## TypeScript Sürümleri

Kitapta anlatacağımız bazı yeni özellikler henüz *kararlı* bir TypeScript derleyicisi tarafından desteklenmemektedir. Hatta bazıları henüz bir sürüm numarası ile bile ilişkilendirilmemiş olabilir.

TypeScript derleyicisini aşağıdaki komut ile bilgisayarınıza kurabilirsiniz,

```
npm install -g typescript@next
```

Bundan sonra komut satırına yazılacak olan `tsc` komutu, en son ve en iyi versiyonu olarak kullanılabilir olacaktır. Birçok editör bu sürümü desteklemektedir. Örneğin,

* `alm` her zaman son sürümünde en güncel TypeScript sürümü ile yayınlanmaktadır.
* Eğer `vscode` kullanıyorsanız aşağıdaki içeriğe sahip bir `.vscode/settings.json` dosyası oluşturursanız son sürümü kullanacaktır:

```json
{
  "typescript.tsdk": "./node_modules/typescript/lib"
}
```

## Örneklerin Kaynak Kodlarını İndirmek
Kitabın içerisindeki örneklerin kaynak kodlarına GitHub üzerinden https://github.com/Codefiction/typescript-book/tree/master/code adresinden ulaşabilirsiniz. Kodların büyük bir kısmı alm'ye kopyalandığında hemen çalıştırılabilir durumdadır.
Ek bir kurulum gerektiren örnekler (örneğin npm modülleri) için kod bloğu anlatılmadan önce ilişkili kod ile ilgili aşağıdaki gibi bir referans verilecektir.

`bu/referans/olacak/kodun/adresi.ts`
```ts
// Örneklerde anlatılan kodun kendisi
```

Geliştirme ortamının kurulumunu tamamladığımıza göre artık TypeScript diline giriş yapabiliriz.
