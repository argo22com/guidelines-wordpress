# Wordpress guidelines sablona

![wp-logo](https://s.w.org/style/images/about/WordPress-logotype-wmark.png)

## Coding standards
- mene dulezite oproti nezavislym aplikacim, presto ma do jiste miry smysl / brat v potaz hranice WPcore
    - mozna inspirace [v nasich CS](https://argo22.atlassian.net/wiki/spaces/ROAS/pages/459276350/PHP+Coding+Standards) (zrejme treba update)
    - nebo fallback na [PSR-2](https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-2-coding-style-guide.md)/[PSR-12](https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-12-extended-coding-style-guide.md) + pripadne nase amendments
- good-practice pluginy, stridmost, guidelines ohledne obrazku, cachovani
- deployment, DBaas? pripadne migracni strategie

## Struktura projektu
- struktura de facto dana WP
- radeji confirm w/ Pavel?
- vetsina dat v DB anyaways

## Podoba readme
- popis nutnych promennych, ktere nejsou pod VCS
- popis, jak projekt rozjet

## Makefile
- pripravene recepty viz bod vyse

## Git flow, nazvy vetvi, commit msg guidelines
- spolecna strategie napric projekty
    - feature vetve, pojmenovane jako kod ticketu
    - commit msg length 50/70, pripadne ... a pokracovani. 2. radek musi obsahovat pouze "\n"
