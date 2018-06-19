###Tagon Web Client Properties


> **SuccessCallback** (Function)
>
>  Reklam yüklendiğinde geri bildirim yapar.
>
>  *SuccessCallback: function(){ console.log("Ad Loaded!") }*

----------

> **FailCallback** (Function)
>
>  Reklam yüklenmediğinde geri bildirim yapar.
>
>  *SuccessCallback: function(){ console.log("Ad Failed!") }*

----------

> **Placement** (String)
>
>  Reklam tipi. (FULLPAGE ,INREAD ,MASTHEAD, STANDART)
>
>  *Placement: "FULLPAGE"*

----------

> **AvailableFormat** (String)
>
>  İzin verilen formatlar.
Placement | Format | Name
-- | -- | --
FULLPAGE | Popup | POPUP
FULLPAGE | Push Down | PUSHDOWN
FULLPAGE | Scroll Reveal | SCROLLREVEAL
IN-READ | Video | INREAD
IN-READ | Parallax | PARALLAX
IN-READ | Native Scroll | NATIVESCROLL
MASTHEAD | Roll Over Masthead | ROLLOVER
>
>  *AvailableFormat: "POPUP,SCROLLREVEAL"*

----------

> **Container** (String)
>
>  Sadece In-Read reklam modeli için kapsayıcı element.
>
>  *Container: "#ArticleBody"*

----------

> **InReadMinText** (Number)
>
>  Sadece In-Read reklam modeli için içerikteki minimum karakter limiti. Tamamen boş bir alan içerisine konulacak ise "-1" değeri kullanılmalıdır.
>
>  *InReadMinText: -1*

----------

> **CloseTime** (Number)
>
>  Kapat butonu bulunan formatlar için butonun çıkacağı zaman belirtilir. Hemen çıkması isteniyorsa "0" değeri verilmelidir. (Bu değer sadece görselli modellerde 2.5sn, videolu modellerde 3.5sn dir.)
>
>  *CloseTime: "0"*
