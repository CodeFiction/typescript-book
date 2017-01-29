* [TypeScript ile Başlamak](#typescripte-baslarken)
* [TypeScript Sürümleri](#typescript-sürümleri)
* [Örneklerin Kaynak Kodlarını İndirmek](#kitabın-kaynak-kodlarını-indirmek)

# TypeScript'e Başlarken

TypeScript, JavaScript'e derlenmektedir. Aslinda JavaScript sunucu tarafında ya da tarayıcıda çalışacak olan kodun kendisidir. Dolayısıyla uygulamanızı çalıştırabilmek için aşağıdakilere ihtiyacınız vardır:

* TypeScript derleyicisi (Açık Kaynak Kodlu olarak dağıtılmaktadır. Kodlarina [buradan](https://github.com/Microsoft/TypeScript/) erişebilirsiniz. NPM üzerinden kurmak için ise [buraya](https://www.npmjs.com/package/typescript) tıklayabilirsiniz.)
* Bir TypeScript editörü (Notepad ya da diğer bir çok editörden bir tanesini kullanabilirsiniz. Örneğin bulut tabanlı olan [alm](http://alm.tools)'nin güzel bir örnek olması yanında [bir çok farklı editör de mevcuttur]( https://github.com/Microsoft/TypeScript/wiki/TypeScript-Editor-Support).)


![](https://raw.githubusercontent.com/alm-tools/alm-tools.github.io/master/screens/main.png)


## TypeScript Sürümleri

Kitapta anlatacağımız bazı yeni özellikler henüz *kararlı* bir TypeScript derleyicisi tarafından desteklenmemektedir. Hatta bazıları henüz bir sürüm numarası ile bile ilişkilendirilmemiş olabilir.

TypeScript derleyicisini aşağıdaki komut ile bilgisayarınıza kurabilirsiniz,

```
npm install -g typescript@next
```

Bundan sonra komut satırına yazılacak olan `tsc` komutu, en son ve en iyi versiyonu olarak kullanılabilir olacaktır. Bir çok editör bu sürümü desteklemektedir örneğin,

* `alm` her zaman son sürümünde en güncel TypeScript sürümü ile yayınlanmaktadır.
* Eğer `vscode` kullanıyorsanız aşağıdaki içeriğe sahip bir `.vscode/settings.json` dosyası oluşturursanız son sürümü kullanacaktır:

```json
{
  "typescript.tsdk": "./node_modules/typescript/lib"
}
```

## Örneklerin Kaynak Kodlarını İndirmek
Kitabın içerisindeki örneklerin kaynak kodlarına github üzerinden https://github.com/Codefiction/typescript-book/tree/master/code adresinden ulaşabilirsiniz. Kodların büyük bir kısmı alm'ye kopyalandığında hemen çalıştırılabilir durumdadir.
Ek bir kurulum gerektiren örnekler (örneğin, npm modülleri) için kod bloğu anlatılmadan önce ilişkili kod ile ilgili aşağıdaki gibi bir referans verilecektir.

`bu/referans/olacak/kodun/adresi.ts`
```ts
// Örneklerde anlatılan kodun kendisi
```

Geliştirme ortamının kurulumu yolumuzdan çekildiğine göre artık TypeScript diline giriş yapabiliriz.
