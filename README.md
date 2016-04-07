This is a Python 2 script to dump the encTitleKeys.bin file from a directory of CIA files. You should place the file in your directory of CIA files and run it with no arguments. It will then produce an encTitleKeys.bin file that can be decrypted to decTitleKeys.bin with [Decrypt9WIP's](https://github.com/d0k3/Decrypt9WIP/releases)'s "Titlekey Decryptor Options" -> "Titlekey Decrypt (file)".

The decTitleKeys.bin file can then be checked and printed with [PlaiCDN](https://github.com/Plailect/PlaiCDN).

**Note that illegitimately gotten CIA files (such as those converted from a .3ds instead of dumped from the eShop) usually contain incorrect titlekeys and should be checked with PlaiCDN before trying to use them.**

This script is a modification of [@einstein95's](https://gbatemp.net/threads/release-3ds_ctr_decryptor-void.370684/page-105#post-5245861) original script which only supported getting the key of a single CIA at a time.
