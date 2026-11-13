# Ders 3: Renk ve Isik

Dosyalar:
- `baslangic.html`  -> BURADAN BASLA. Sekiller hazir, renk ve isigi sen ekleyeceksin.
- `index.html`      -> Tam kod. Takilirsan buna bak (once kendin dene!).
- `three.min.js`    -> Three.js kutuphanesi. Dokunma. Hepsi AYNI klasorde kalmali.

Calistirmak: html dosyasina cift tikla, tarayicida acilir.
Degisiklikten sonra: Ctrl+S (kaydet), F5 (yenile).

## Yeni fikir: isik
Renkli ve gercek gibi gorunen nesneler icin 2 sey lazim:
1. `MeshStandardMaterial` (isik alan malzeme)
2. Sahnede isik (`AmbientLight` ve `DirectionalLight`)

Isik yoksa `MeshStandardMaterial` SIYAH gorunur. Bu hata degil, normal!

## Renk kodu
`#ff595e` renk seciciden gelen kodu `0xff595e` diye yaz (`#` yerine `0x`).

## Gorevler (baslangic.html icinde)
1. Kupu `MeshStandardMaterial` ile boya (siyah cikacak!)
2. `AmbientLight` ekle
3. `DirectionalLight` ekle
4. Diger uc sekli de boya
5. Bonus: golge ekle (index.html'deki BONUS satirlarina bak)

## Bozma Oyunu
- `AmbientLight(0xffffff, 0.4)` -> `1.5`
- `DirectionalLight(0xffffff, 0.9)` -> `DirectionalLight(0xff9040, 0.9)`
- `gunes.position.set(5, 10, 7)` -> `(-5, 10, 7)`
- `MeshStandardMaterial({ color: 0xff595e })` -> `MeshStandardMaterial({ color: 0xff595e, roughness: 0.1 })` (parlak olur) ve sonra `roughness: 1` (mat olur)

## Odev: Kendi Renk Paletin
Ders 2'deki kardan adami (ya da robotu) renklendir ve isiklandir.
Bir sonraki derste hangi renkleri neden sectigini anlat.

## Sayfa bos kalirsa
F12 -> Console -> kirmizi yaziyi oku.
