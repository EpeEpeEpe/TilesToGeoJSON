# TilesToGeoJSON
Konverze strava aktivit ze statshunters.com do souboru GeoJSON

V levém menu na statshunters.com bude po načtení stránky přidána nová položka "GoeJSON". Po kliknutí na tuto položku dojde ke stažení souboru "GeoJSON".

## Rozšíření pro Firefox
Aktuální verze rošíření pro Firefox v adresáři web-ext-artifacts
https://github.com/EpeEpeEpe/TilesToGeoJSON/tree/origin/web-ext-artifacts	

## Rozšíření pro Chrome
1. Stáhněte aktuální rošíření pro Firefox v adresáři web-ext-artifacts: https://github.com/EpeEpeEpe/TilesToGeoJSON/tree/origin/web-ext-artifacts	
2. Rozbalte obsah archivu do adresáře např. TilesToGeoJSON
3. V chrome zvolte MENU - DALŠÍ NÁSTROJE - ROZŠÍŘENÍ
4. V pravém horním rohu povolte REŽIM PRO VÝVOJÁŘE
5. Zvolte NAČÍST NEROZBALENÉ a zvolte adresář, ve kterém je rozbalený obsah archivu

*Proč je na tlačítku "nerozbalené" se neptejte. V EN je uvedeno správně "unpacked"*

*Chrome se nelíbí "browser_specific_settings", ničemu to nevadí, ale klidne tento klíč a hodnotu můžete ze souboru manifest.json smazat*

## Bookmarklet pro Firefox
Nevím.. nefunguje.. kdo poradí? :-)

## Bookmarklet pro Chrome
Vytvořte novou záložku a pro adresu uveďte následující URL:

    javascript:$('body').append($("<script src='https://cdn.jsdelivr.net/gh/liskin/locus-graphhopper-gpx@master/locus-graphhopper-gpx.js'></script>"))

## GreaseMonkey/Tampermonkey
Vytvořte nový skript s obsahem
https://github.com/EpeEpeEpe/TilesToGeoJSON/blob/origin/TilesToGeoJSON.js
	
