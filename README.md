# Instalaciones
Iniciamos con :
```shell 
symfony new myshop --webapp
´´´

Instalamos la utilidad fixer con:

```shell
composer require cs-fixer-shim
```

Uso de fixer: 

```shell
php vendor/bin/php-cs-fixer fix
```

Instalado Serializer:

```shell
composer require serializer
```

Instalado AssetMapper:

```shell
composer require symfony/asset-mapper
```
Para debuggear Asset :
```shell
php bin/console debug:asset
```

Instalamos tailwind para css:

```shell
composer require symfonycasts/tailwind-bundle
```

Iniciar tailwind para css:
```shell
php bin/console tailwind:init
```
Instalamos stimulus para js:
```shell
composer require symfony/stimulus-bundle
```

Creamos una migración y la ejecutamos:

```shell
symfony console make:migration
symfony console doctrine:migrations:migrate
```