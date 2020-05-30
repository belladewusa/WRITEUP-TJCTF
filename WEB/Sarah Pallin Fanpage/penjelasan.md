# Sarah Pallin Fanpage

____________________________________
**Soal**

Are you a true fan of Alaska's most famous governor? Visit the [Sarah Palin fanpage](https://sarah_palin_fanpage.tjctf.org/).


____________________________________
**Penyelesaian**

buka page [VIP area](https://sarah_palin_fanpage.tjctf.org/exclusive) pada web itu. buka cookienya dengan menggunakan tools cookie editor yang menjadi plugin di beberapa browser ., atau dengan menekan F12 untuk inspect element. Pada tab application bagian storage terdapat cookies. Value pada data tersebut dikopi dan di decode dengan base64 menggunakan online encoder-decoder.
Hasil decode tampak seperti ini : `{"1":false,"2":false,"3":false,"4":false,"5":false,"6":false,"7":false,"8":false,"9":false,"10":false}`

Ubah kata `false` menjadi `true` dan lakukan encode kembali dengan base64. Masukkan kembali ke value pada data dan refresh page.

____________________________________
**Flag**

```
tjctf{wkDd2Pi4rxiRaM5lOcLo979rru8MFqVHKdTqPBm4k3iQd8n0sWbBkOfuq9vDTGN9suZgYlH3jq6QTp3tG3EYapzsTHL7ycqRTP5Qf6rQSB33DcQaaqwQhpbuqPBm4k3iQd8n0sWbBkOf}
```