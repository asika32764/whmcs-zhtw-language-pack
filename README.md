# WHMCS 繁體中文 (zh-TW Chinese) 語言檔

For 5.3 版本

這個語系檔來自 https://code.google.com/p/whmcs-cht/ 並經過重新校對與潤飾。

## 發票 PDF 專用字體

由此下載 https://github.com/asika32764/whmcs-zhtw-language-pack/raw/master/invoice/Droid_Sans_Fallback.zip

``` bash
cd /your/whmcs/includes/classes/TCPDF/fonts
wget https://github.com/asika32764/whmcs-zhtw-language-pack/raw/master/invoice/Droid_Sans_Fallback.zip
unzip Droid_Sans_Fallback.zip
```

接著在 General Setting 的 invoice 分頁，將字體改成 Custom 並填入 `droidsansfallback` 即可發送中文字體的發票

