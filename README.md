# bildil programlama dili

```
// 21.02.2023
temel .eklem ( yazma )

:      a 12 // değişmeyen sayı
:      b 'merhaba' // dizi
: tüm4 c 123 // i32 tüm sayı

// yorum

// el/il yapı (struct)
;:  yön
    ; kay4 güney // float
    ; tüm8 kuzey
    :;  z : tüm4 x
        yazma ( x )

// ön işlev
:;  baş
    ; tam4 d // değişen u32 tam sayı
    ekle ( a c )
    ; d 29
    yazma ( d )

    : tamsayı ışık_hızı 299792458 // usize
    ; güney yön.güney
    ; güney 125,125
    yön.güney .z ( güney )

    :: a = 2 // ya değişmeyen
        yazma ( 2 )
    :: a = 3 // ya da
        yazma ( 3 )
    :: // ve ya
        yazma ( '2 ve ya 3 değil' )

    : mevsimler [ 'yay' 'yaz' 'güz' 'kış' ]
    ;;  mevsimler ,, mevsim // for/in döngü değişebilir
        yazma ( mevsim )
    ;; 1 10 .. e // döngü
        yazma ( e ) // 1 2 3 4 5 6 7 8 9 10 

    ; liste [ 'a' 'b' 'c' 'ç' 'd' 1 2 3 4 5 ]
    ; çift_liste [ : 'a' 1 : 'b' 2 : 'c' 3 : 'ç' 4 : 'd' 5 ]
    yazma ( çift_liste [ 'ç' ] ) // 4
    yazma ( 'mersin' ) .tersine ()

    ; ad kabuğu.oku ()

    yazma ( ' "b arkadaşım " ' ad ) // "merhaba arkadaşim"

// işlev
:;  tüm4 ekle ; tüm4 x ; tüm4 y
    x + y // dönme tüm4

' " . .. , ,, : ; :; ;: :: ;; () [] //

```
