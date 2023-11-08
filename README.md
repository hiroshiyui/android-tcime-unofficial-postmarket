# android-tcime-unofficial-aftermarket

## 「注音倉頡輸入法非官方版」之「副廠料件版」

這是「注音倉頡輸入法非官方版」（[原始網站](https://code.google.com/archive/p/android-tcime-unofficial/)、[原非官方版作者 GitHub 映射站](https://github.com/scribetw/android-tcime-unofficial)）的「副廠料件版」(aftermarket)。我只是[接受個案付費委託](https://github.com/hiroshiyui/android-tcime-unofficial-aftermarket/wiki#%E6%9C%AC%E5%89%AF%E5%BB%A0%E6%96%99%E4%BB%B6%E7%89%88%E4%B9%8B%E4%BB%BB%E4%BD%95%E7%B6%AD%E8%AD%B7%E5%A7%94%E8%A8%97%E5%9D%87%E7%82%BA%E6%9C%89%E5%84%9F%E6%9C%8D%E5%8B%99)，做一些必要的新版 Android 相容維護，恕不接受增加新功能的請求。

本「副廠料件版」亦[僅在此處提供 APK 套件包](https://github.com/hiroshiyui/android-tcime-unofficial-aftermarket/releases)，未放上任何 App 市集。**如在任何 App 市集或第三方網站見到下載檔案，請務必注意是否有安全疑慮。輸入法會攔截您的每一字一句，如有惡意加料的程式，將會竊取您的資料。**

## 本「副廠料件版」之任何維護委託，均為有償服務

**一隻十幾歲、中間全然沒人維護的陳年老程式，只靠修修補補，勉強放到現代的 Android 版本上面跑，本來就會冒出各種花式不相容的毛邊。**

第一次幫人維護的時候，對方豪爽地付了一千元，只因為在 Android 13 底下「看不到候選字列」，但他希望能夠繼續使用這個慣用的輸入法，所以找上門來拜託我幫忙。改好了，他很高興，爽快地付了一千元，還很客氣地說：「賺的不多，只能付這麼多。」

這麼多！足夠讓我吃五天的早餐、午餐啊！

而在 Android 13 看不到候選字列，也是 Google 自己搞的事，我就負責幫忙善後而已。

但是接著呢？維護這隻程式就好像變成我的義務似的，一下子有人要我改這裡，一下子有人要我改那裡，都沒付錢，**好像我改程式不用吃飯喝水不用時間。**

我每改一個地方，花的時間途中至少都得吃一餐，好歹也付我個便當錢吧？我這樣要求不過份吧？一般接案公司都還用人月、工時計價，而我只卑微地要個便當吃而已。

要我改這隻程式，您各位請先報價再說。修老車找副廠料件，您各位也不可能要人免費奉送吧？副廠經營不用錢？殺肉場經營不用錢？您想修老車繼續開繼續騎，每項合用的替換料件都要錢。

我也要生活啊！

## 「可是『注音倉頡輸入法』、『注音倉頡輸入法非官方版』本來都沒有收費！」

授權條款並無禁止我為維護委託收取合理報償。他人有能力無償付出、貢獻社會，我尊敬，但是我不一樣，我需要錢吃飯！

## 「我之前付過一次錢了，為何這次又要收我錢？」

除非此次修改是因為之前我維護過的地方沒有寫好，得因保固原則負責維修，否則皆應按件計酬。

## 「為何被拒絕『加功能』、『改功能』？」

這隻程式的寫法已經與現今 Android InputMethodService 運作方式出入甚大了，現在做 Android 輸入法，連按鍵都要自己刻，沒有 `<Key>` 這種現成元件，其餘改動更是多如牛毛。Android 內部若已完全禁用或不再相容舊版寫法，我也愛莫能助。
