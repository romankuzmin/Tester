OrderApp - v 1.1.0
=======================

Aplikace pro zasílání objednávek.

- - -

Zákazník:

Pavel Němec

- - -

Seznam změn: [changelog.md](https://bitbucket.org/romankuzmin/antihelm.cz/src/08ad1bc820734c8dc6de1089e15d81bbda604c5a/changelog.md?at=master)

Popis
--------------------------------------------

Aplikace umožnuje po přihlášení pod určitým poradcem vytvořit objednávku, 
která je zaslána na email palon@email.cz


Instalace
----------

Nainstaloval lze pomocí služby Composer:

1. Instalace Composer: (informace http://getcomposer.org/download)

  	curl -s http://getcomposer.org/installer | php

2. Vytvoření projektu pomocí Composer:

		php composer.phar create-project orderapp/orderapp orderapp
		cd orderapp

Adresáře `temp` a `log` musí mít právo pro zápis.
