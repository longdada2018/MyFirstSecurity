# 第四週	加密/解密與破密

課程目標:上完這課程模組後,學生要會
>* 熟悉古典密碼學的凱薩加密與解密
>* 使用線上工具完成古典密碼學的暴力破解法
>* 使用線上工具完成古典密碼學的頻率分析法
>* 熟悉古典密碼學的密碼棒之加密與解密
>* 完成crypto-CTF題目解題

延伸學習:鼓勵學生參加Breakall CTF練習


# 古典密碼學  

https://en.wikipedia.org/wiki/Cryptography#Classic_cryptography

substitution ciphers替換式密碼
transposition ciphers:置換式密碼（轉位式密碼)或(移轉式密碼)

# substitution ciphers替換式密碼
>* https://zh.wikipedia.org/wiki/替換式密碼
>* https://en.wikipedia.org/wiki/Substitution_cipher

>* Caesar cipher
>* 豬圈密碼（Pigpen cipher)亦稱共濟會密碼（masonic cipher）或共濟會員密碼（英語：Freemason's cipher）
https://zh.wikipedia.org/wiki/豬圈密碼

Frequency analysis頻率分析

# substitution ciphers

# Transposition cipher

rearrange the order of letters in a message (e.g., 'hello world' becomes 'ehlol owrdl' in a trivially simple rearrangement scheme)

https://en.wikipedia.org/wiki/Transposition_cipher

>* Rail Fence cipher籬笆式位移密碼
>* Route cipher
>* Scytale 密碼棒  https://zh.wikipedia.org/wiki/密碼棒

明文:'WE ARE DISCOVERED. FLEE AT ONCE'

Rail Fence cipher籬笆式位移密碼

W . . . E . . . C . . . R . . . L . . . T . . . E
. E . R . D . S . O . E . E . F . E . A . O . C .
. . A . . . I . . . V . . . D . . . E . . . N . .

密文: WECRL TEERD SOEEF EAOCA IVDEN

Route cipher
W R I O R F E O E 
E E S V E L A N J 
A D C E D E T C X 

The key might specify "spiral inwards, clockwise, starting from the top right". 

密文:EJXCTEDECDAEWRIORFEONALEVSE



3	Columnar transposition
4	Double transposition
5	Myszkowski transposition
6	Disrupted transposition
7	Grilles
