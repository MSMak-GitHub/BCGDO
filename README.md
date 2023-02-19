# DCGDO
## Better Cvolton Geometry Dash by OffNik
Basically a Geometry Dash Server Emulator

Supported version of Geometry Dash: 1.0 - 2.11

(See [the backwards compatibility section of this article](https://github.com/Cvolton/GMDprivateServer/wiki/Deliberate-differences-from-real-GD) for more information)

Required version of PHP: 5.5+ (tested up to 8.1.2)****

### What's added in DCGDO?

1. Panel! (Yeah, you can make an account for the panel in the database and change the GDPS there!)
2. Better Tools (Minimalistic design)
3. Fast tools!
4. (Comming Soon) Auto CP

### Setup
1) Upload the files on a webserver
2) Import database.sql into a MySQL/MariaDB database
3) Edit the links in GeometryDash.exe (some are base64 encoded since 2.1, remember that)

### Updating the server
1) Upload all files with replacement
2) Import database.sql into MySQL/MariaDB database with replace

### Credits

Original: https://github.com/Cvolton/GMDprivateServer

Modifications and edits by OffNik (Me)

Panel by Seecomp: https://github.com/Seecomp/GDPSPanel

Base for account settings and the private messaging system by someguy28

Using this for XOR encryption - https://github.com/sathoro/php-xor-cipher - (incl/lib/XORCipher.php)

Using this for cloud save encryption - https://github.com/defuse/php-encryption - (incl/lib/defuse-crypto.phar)

Most of the stuff in generateHash.php has been figured out by pavlukivan and Italian APK Downloader, so credits to them
