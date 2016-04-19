# Multi-Language configurations for pmt.mcpe.me

## English
We hope that you can help translating pmt.mcpe.me into your locale for us.

### NEW, Join our translation project on **[Zanata](https://translate.zanata.org/project/view/pmt.mcpe.me-languages)**!

We use gettext function to make pmt.mcpe.me to multi-language supported. `.po` file is used for translating, `.mo` file is for our system to read the translations. In the **_Translation templates** folder, there is a file which the filename extension is `.pot`. That is a language template for you to translate the language inside.

### How to convert `.po` to `.mo`
We don't totally request you to summit `.mo` file to us, but we hope you can help us if you have the ability.

You can use **[Poedit](https://poedit.net/)** to help you to translate the `.po` file. The `.mo` file will be auto-generated when you save the `.po` file.

If you're using Linux OS, you can use `msgfmt` command to convert `.po` into `.mo` or merge it to the old version of the translation.
Here is the usage:
* Convert: `msgfmt -o Filename.mo Filename.po`
* Merge: `msgmerge -o (FilenameAfterMerge).po (OldFile).po (NewFile).po`

### Attention! You also need to create a folder named `LC_MESSAGES` in the language folder.


## 繁體中文
我們隨時歡迎您為 pmt.mcpe.me 貢獻翻譯！

### 新，加入我們的 **[Zanata](https://translate.zanata.org/project/view/pmt.mcpe.me-languages)** 翻譯專案！

我們是採用 gettext 來製作多國語言，`.po` 檔為翻譯用，`.mo` 檔為系統讀取用，在 **_Translation templates** 資料夾內有副檔名為 `.pot` 的文件，那是語言模板，可利用 `.pot` 檔創建新語言。

### 如何編譯
我們不要求您一定要編譯翻譯檔，但希望您能編譯完再提交。

翻譯 `.po` 文件時可以利用 **[Poedit](https://poedit.net/)** 這個軟體進行翻譯，存檔後會自動編譯成 `.mo` 文件。

Linux 作業系統還可以於終端將 `.po` 文件編譯成 `.mo` 文件或合併舊有的翻譯，用法如下：
* 編譯： `msgfmt -o 文件名稱.mo 文件名稱.po`
* 合併翻譯： `msgmerge -o 合併完要存的檔名.po 要跟新檔合併的.po 新的檔案.po`

### 請注意，在語系資料夾內還要創建 `LC_MESSAGES` 資料夾。
