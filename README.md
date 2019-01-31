 VOC grafiken
====================
Grafiken, die beim Streaming Setup der Toolbox verwendet werden.
Das sind u.a. hintergründe, kleine animationen oder andere praktische Bilder, Videos und Vektorgrafiken.


 Primärfarben
------------------
Bei den Menüfarben sollte die Farbauswahl aus dem [Toolbox Presse-Kit](https://github.com/ToolboxBodensee/presskit) berücksichtigt werden. ![#E64F2D](https://placehold.it/15/E64F2D/000000?text=+) `#E64F2D` Orange und ![#9B160F](https://placehold.it/15/9B160F/000000?text=+) `#9B160F` Rot sind hier die Primärfarben.


 Bilder und große Dateien
---------------------------
Für große Dateien haben wir angefangen auf [git-lfs](https://git-lfs.github.com/) zu setzen. Hierbei werden große Dateien nicht mehr ganz so schlimm in die History des git eingebaut.
Das war mit mehreren MB großen Bildern schon schlimm, aber noch verkraftbar. Mit größeren Videos aber... Sollte man das halt echt nicht direkt ins git werden!

Zur verwendung von git-lfs muss die git-lfs command line extention installiert sein!
Die geschieht auf den gängigsten Platformen zB. mit:

```bash
sudo apt install git-lfs
```
oder
```bash
sudo pacman -S git-lfs
```

 Schriftart
------------
Die Schriftart der Toolbox ist [Exo_2](https://github.com/ToolboxBodensee/toolbox-voc_ansible/tree/master/files/Exo_2).


 Dateiformat
-------------
Alle Grafiken nach möglichkeit als Vektorgrafik und als Pixelgrafik abspeichern. Das erleichtert das automatisierte einbinden in das VOC Setup.


 Verwendung
------------

Für den produktiven Einsatz sollten die Grafiken unter folgenden Pfad gespeichert sein:

````bash
/srv/stream/toolbox/streamassets
```` 
