ALU_test
========

這是一支用以產生計組Lab01 ALU測資的程式
用C++寫成，可以自行下載compile使用。

若需要Shifter的測資產生程式請參考[Shifter測資產生程式](http://cyl.femi.tw/co_test.html)

使用方式
========

此程式可以一次產生多筆測資，並輸出至txt檔中，程式啟動後：

1. 將提示選擇產生何種功能的測資（ex加、減），選擇後...
2. 將提示是否亂數產生Src1，輸入y以亂數產生，或輸入n自行輸入...
3. 提示是否亂數產生Src2...
4. 重複步驟1，直到在步驟1選擇-1

程式結束後將會顯示所有測資以及答案，並將測資及答案輸出至檔案中。

建議使用方式
============

為專心測試某一功能(ex加法)，建議程式啟動後，連續輸入15(或更多)次
`1 [Enter] y [Enter] y [Enter]`後輸入-1結束程式。
確認該功能沒有錯誤後，再測其他功能。

Overflow的爭議
==============

根據助教的解釋，overflow只看加法器的結果，而不管operation是什麼。

參考資料
========

程式設計皆參考助教的pdf。

Bugs
====

我本身已經測試過大致上沒有問題，但畢竟ALU與測資程式都是由我一個人寫的，
也許會發生一些題意上的誤解，而我自己也沒發現。

若發現程式有任何bug，請直接跟我講、Email or FB告知我、或開一個issue以便一同討論，
謝謝！
