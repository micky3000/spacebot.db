# spacebot.db

spacebot.db açık kaynaklı veri depolama modülüdür. Space Bot için yazılmıştır.

## Kurulum

```bash
npm install space.db
```

Main dosyanıza bunu ekleyin

```javascript
const db = require("space.db")
```

Tüm veriler `database.json` adlı dosyaya kaydedilecek.

## Fonksiyonlar

```javascript
// Ayarlama
    db.set('prefix', '!')
    db.yaz('prefix', '!')
```

```javascript
// Kaydetme    
    db.push('prefix', '!')
    db.depola('prefix', '!')
```
    
```javascript
// Bulma
    db.fetch('prefix')
    db.bul('prefix')
```

```javascript
// Kontrol
    db.has('prefix')
    db.kontrol('prefix')
```

```javascript
// Sil
    db.delete('prefix')
    db.sil('prefix')
```

```javascript
// Yedekleme 
    db.backup('veri.json')
    db.yedekle('veri.json')
```
    
```javascript
// Ekle
    db.add('puan', 5)
    db.topla('puan', 5)
```

```javascript
// Çıkarma
    db.substr('puan', 5)
    db.çıkar('puan', 5)
```

```javascript
// Sıfırlama
    db.sıfırla()
```