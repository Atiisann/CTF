# caesar cipher 1

## Quetion  

> This is one of the older ciphers in the books, can you decrypt the message? You can find the ciphertext in /problems/caesar-cipher-1_1_6fbf7a9ce0aac23bab1c37836cc20c3b on the shell server.  

## Solution

`"cd /problems/caesar-cipher-1_1_6fbf7a9ce0aac23bab1c37836cc20c3b`"でディレクトリを移動する。　　
`"ls"`でディレクトリの中を表示すると「ciphertext」というファイルがあるから、`"cat ciphertext|grep picoCTF"`で「ciphertext」の中からpicpCTFを含む文字列を探す。すると「picoCTF{vgefmsaapaxpomqemdoubtqdxoaxypeo}」が出てくるがこれはシーザー暗号なのでツールを使ってかデコードする。　　
何個か文字をシフトすると「justagoodoldcaesarciphertobrvmri」となる。　　
（just a good old caesarciphertobrvmri なんか合ってそうだからこれにした。。）　　

# Flag

`picoCTF{justagoodoldcaesarciphertobrvmri}`

