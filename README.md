﻿# Convers-o-de-Moedas
 --------------------------------------------------------------------
 PS C:\test> php -S localhost:8000 src/index.php
[Sat May 13 16:33:41 2023] PHP 7.4.26 Development Server (http://localhost:8000) started
[Sat May 13 16:33:54 2023] [::1]:59826 Accepted
[Sat May 13 16:33:54 2023] [::1]:59826 Closing
--------------------------------------------------------------------
PS C:\test> composer test
> phpunit
PHPUnit 9.6.0 by Sebastian Bergmann and contributors.

.                                                                   1 / 1 (100%)  

Time: 00:00.016, Memory: 6.00 MB

OK (1 test, 4 assertions)
--------------------------------------------------------------------
PS C:\test> composer lint
> for /r src %f in (*.php) do @(echo Verifying %f & php -l %f)
Verifying C:\test\src\index.php 
No syntax errors detected in C:\test\src\index.php
--------------------------------------------------------------------
