Si aucune information de geolocalisation apparaît vérifiez votre fichier .gpx.

Un fichier .gpx est un fichier texte que vous pouvez ouvrir et modifier facilement dans un éditeur de texte : il contient plein de tags sous la forme de balises contenant du texte ou d'autres tags : 

&lt;tag&gt;

 .... 

&lt;/tag&gt;




Un fichier gpx a un ou plusieurs 

&lt;trkseg&gt;

 ... 

&lt;/trkseg&gt;

 qui devrait comporter de nombreux points GPS  

&lt;trkpt&gt;

...

&lt;/trkpt&gt;

 qui indique votre position précise à un instant donné. time.

```
...
<trkseg> 
<trkpt lat="48.50517319" lon="7.13916969">
<ele>700.46</ele>
<time>2007-03-04T12:05:16Z</time>
</trkpt>
<trkpt lat="48.50517286" lon="7.13916759">
<ele>704.30</ele>
<time>2007-03-04T12:05:18Z</time>
</trkpt>
<trkpt lat="48.50517294" lon="7.13916550">
<ele>708.15</ele>
<time>2007-03-04T12:05:20Z</time>
</trkpt
 ... ... 
</trkseg>
...
```

Vous pouvez vérifier les informations que GPicSync extrait en utilisant le menu "Tools"->"GPX Inspector".

Utilisez "Tools"->"EXIF Reader" pour vérifiez éventuellement que vos photos contiennent bien un champ 'Date/Time Original'(Exemple: Date/Time Original : 2007:04:06 14:41:02). Certain logiciels de traitement d'image effacent les metadonnées des photos.

Si malgré cela vous n'arrivez toujours pas à obtenir vos photos géolocalisées merci de m'envoyer votre fichier .gpx et une ou deux photos à [cette adresse mail](http://francois.schnell.free.fr/mygmail.png). Merci d'avance pour votre feedback !