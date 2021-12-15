# Script_sysbeheer_major_nextcloud

Met dit script kan je de nextcloud container opzetten zodat je lokaal je eigen nextcloud server kan hosten.
Het gebruikt van dit script is zeer simpel.

Je moet zelf een file aanmaken met daarin je eigen gekozen parameters voor je container, bv poortnummer, naam van de container, ...
Je execute het script door sudo ./create_nextcloud_container en dan als argument het path mee te geven van waar je file staat met je eigen variabelen.

In de github staat ook een eigen aangemaakte file die je als voorbeeld kan gebruiken voor hoe de variabelen gedefinieerd moeten worden in dit extern bestand.

voorbeeld van commando is dan ./create_nextcloud_container /path/to/file
