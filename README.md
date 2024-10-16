# golib
`(Golang Library)`
Dalam repositori ini kita rangkum semua `dependensi` yang kita butuhkan untuk `development` software lebih `efisien` dan lebih `maksimal`.


>Untuk bisa menggunakan perintah perintah yang terdapat dalam repositori ini silahkan jalankan perintah di bawah ini dalam folder atau direktori project anda.

```bash
go get git@github.com:herumitra/golib.git
```

>Setelah library tersebut masuk dan tercantum dalam fil `g.mod` anda, langkah selanjutnya adalah inisiasi library tersebut dalam file yang akan menggunakan atau memanggil fungsi-fungsi golib tersebut dengan memasukkannya ke dalam alias sesuai yang anda harapkan seperti contoh di bawah ini.

```bash
import (
    golib "github.com/herumitra/golib"
)

func main() {
    golib.ResFormat("example")
}
```