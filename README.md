# bildil programlama dili

```

// 21.02.2023
temel .eklem ( yazma ) // (include)

:      a 12 // değişmeyen sayı (number)
: yaz  b 'merhaba' // yazıt (string)
: kar4 c -123 // karşıt sayı (i32)

// yorum

;:  yön // el/il yapı (struct)
    ; büt4 güney // biten, yetişen sayı (float)
    ; büt4 kuzey
    :;  z : büt4 x
        yazma ( x )

:;  baş // ön işlev (main)
    ; tüm4 d // değişen tüm sayı (u32)
    ekle ( a c )
    ; d 29

    yazma ( d ) // -94

    : tüm ışık_hızı 299792458 // (usize)
    ; güney yön.güney
    ; güney 125,125
    yön.güney .z ( güney ) // 125,125

    :: a = 2 // değişmeyen ya (if)
        yazma ( 2 )
    :: a = 3 // ya da (else if)
        yazma ( 3 )
    :: // ve ya (else)
        yazma ( '2 ve ya 3 değil' )

    : mevsimler [ 'yay' 'yaz' 'güz' 'kış' ]
    ;;  mevsimler ,, mevsim // değişebilir döngü (for/in loop)
        yazma ( mevsim )
    ;; 1 10 .. e // döngü (for ;; loop)
        :: e = 5
            >> // sürdür (continue)
        :: e = 10
            <> // bitir (break)
        yazma ( e ) // 1 2 3 4 6 7 8 9

    ; liste [ 'a' 'b' 'c' 'ç' 'd' 1 2 3 4 5 ]
    ; çift_liste [ : 'a' 1 : 'b' 2 : 'c' 3 : 'ç' 4 : 'd' 5 ]
    yazma ( çift_liste [ 'ç' ] ) // 4
    yazma ( 'mersin' ) .tersine () // "nisrem"

    ; ad kabuğu .oku ()

    yazma ( ' "b arkadaşım " ' ad ) // "merhaba arkadaşım"

:;  kar4 ekle ; kar4 x ; kar4 y // işlev (function)
    << x + y // dönme kar4 (return)

' " . .. , ,, : ; :; ;: :: ;; () [] << >> <> //

yaz                      // string
yar|doğ|boş              // bool/true/false
tüm|tüm1|tüm2|tüm4|tüm8  // usize/u8/u16/u32/u64
kar|kar1|kar2|kar4|kar8  // isize/i8/i16/i32/i64
büt4|büt8                // float/double

```
