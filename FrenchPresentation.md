![![](http://farm2.static.flickr.com/1309/780629458_535628537b.jpg)](http://farm2.static.flickr.com/1309/780629458_6e21c96ac5_o.jpg)

( [Debuter](Debuter.md) ) ( ScreenShots ) ( ChangeLog ) ( [English version](http://code.google.com/p/gpicsync) )


**4 avril 2008**: Version 1.26 disponible (voir ChangeLog)

Pour une version la plus à jour du site consultez [la version anglaise](http://code.google.com/p/gpicsync/).

GPicSync insère automatiquement les coordonnées latitude/longitude/altitude dans les métadonnées de de vos photos qui peuvent alors aussi être utilisées par tout logiciel ou site sachant lire ces informations comme Picasa/Google Earth, Flickr, loc.alize.us, etc.

**Caractéristiques:**

  * geocode automatiquement vos photos JPG ou RAW (en-tête EXIF et IPTC)
  * utilise n'importe quels parcours GPS (track log) au format universel  [GPX](http://www.topografix.com/gpx_for_users.asp) ou NMEA
  * gestion de l'altitude si présent dans le fichier GPS et modes aviation
  * visualisation directe des photos et parcours dans Google Earth (fichier KML)
  * export Google Maps possible pour publication sur un site web
  * association automatique de fichiers audio et vidéo à vos photos géolocalisées
  * possibilité de créer une archive Google Earth KMZ
  * support de métadonnées supplémentaires geonames (pays, région, lieu le plus proche...) et "geotagged"
  * possibilité d'inscrire  manuellement les coordonnées géographiques
  * configuration fine et enregistrement de ses préférences dans un fichier de configuration
  * utilitaires (correction temporelle, lecteur EXIF, inspecteur GPX, géo-renommage de photos, etc.)
  * possibilité de faire une exploration spatio-temporelle dans Google Earth ("TimeStamp")
  * logiciel en Anglais traduit dans plus de dix langues (Français, Espagnol, Catalan, Italien, Allemand, Polonais, Néerlandais, Tchèque, Portugais, Chinois simplifié et Chinois traditionnel)

**Prêt à géocoder vos photos?**

  * [Debuter](Debuter.md) avec GPicSync
  * Une formation réalisée par Nicolas Moyroud (Unité Mixte de Recherche Cemagref) avec photos et trace GPS : ["Initiation à la géo-localisation d'images avec GPicSync et Google Earth"](http://libreavous.teledetection.fr/geomatique/18-formation-geolocalisation-dimages-avec-gpicsync)

GPicSync signifie G:GPS Pic:Pictures Sync:Synchronization et est un logiciel libre et Open Source.

**Quelques exemples de photos géolocalisées avec GPicSync:**

  * Ajout de fichier audios: [un premier test](http://local.google.com/maps?f=q&hl=en&q=http%3A%2F%2Ffrancois.schnell.free.fr%2Fgeo%2Faudio-test%2Fdoc-web.kml&ie=UTF8&ll=48.534056,8.189406&spn=0.011708,0.029182&t=h&z=15&om=1)
  * Export Google Maps depuis GPicSync: [une ballade vélo](http://maps.google.com/maps?f=q&hl=en&q=http%3A%2F%2Ffrancois.schnell.free.fr%2Fgeo%2F29Apr07%2Fdoc-web.kml&ie=UTF8&ll=48.520925,8.146706&spn=0.102329,0.233459&t=h&z=12&om=1) (voir GoogleMapsExport)
  * Une sortie vélo dans le vignoble alsacien [vu dans Yahoo maps / Flickr](http://www.flickr.com/photos/frenchy/sets/72157600057036260/map/) ou  [le fichier kmz exporté depuis Picasa](http://francois.schnell.free.fr/geo/8-avr-07-riquewhir.kmz) (à ouvrir dans Google Earth)
  * Pause de midi [géolocalisée ](http://loc.alize.us/#/user:Francois%20Schnell/geo:48.58412,7.76409,17,k/) (visualisée dans loc.alize.us qui utilise Flickr et Google maps)
  * [utilisation dans 'My maps'](http://maps.google.com/maps/ms?ie=UTF8&hl=en&z=9&ll=48.443778,7.597046&spn=0.668648,1.867676&t=h&om=1&msid=100273353392671595172.00000111f1333a196b094&msa=0)(voir [tutorial](http://code.google.com/p/gpicsync/wiki/PicasaToKmz))
  * A fichier Google Earth [KMZ ](http://francois.schnell.free.fr/geo/testGpicsync.kmz) autour de Strasbourg (généré via l'outil 'KMZ Generator' de GPicSync)
  * [Tout premier test lors d'une sortie VTT](http://loc.alize.us/#/user:Francois%20Schnell/geo:48.45095,7.03726,13,k/) (visualisée dans loc.alize.us)

[Des exemples d'utilisation](http://code.google.com/p/gpicsync/wiki/GeolocalizedExamples) par des utilisateurs de GPicSync.

Merci pour [les contributions et feedback.](http://code.google.com/p/gpicsync/wiki/Contributions)
GPicSync intègre également deux excellents outils libres: [EXIFTool](http://www.sno.phy.queensu.ca/~phil/exiftool/) et [GPSBabel](http://www.gpsbabel.org/) (merci à leurs auteurs!)