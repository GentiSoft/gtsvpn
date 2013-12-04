# GtsVPN

Scripts para configurar una VPN privada usando tinc, basado en el proyecto [LibreVPN](http://librevpn.org.ar)

## Diferencias con LibreVPN

Esta herramienta fue adaptada a las necesidades de [GentiSoft](http://gentisoft.com) para propositos internos, como esto es Software Libre, lo dejamos publicado.

Las diferencias a nivel tecnico son solamente que se cambio el rango de ip 192.168.9.0/24 que usaba lvpn, por 10.26.0.0/16 para poder crear rangos significativos.

Si tu proposito es armar una VPN abierta o *friend to friend* te recomendamos que uses LibreVPN

## Continuidad con el proyecto

GtsVPN **NO** sigue continuo a LibreVPN, es un fork que se continua aparte.

## I18n

    mkdir -p locale/en/LC_MESSAGES
    msgfmt -o locale/en/LC_MESSAGES/lvpn.mo locale/en.po
    export TEXTDOMAINDIR=$PWD/locale

