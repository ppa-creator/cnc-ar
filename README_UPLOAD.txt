CNC AR CLEAN v104

Nahraj vsetky subory priamo do rootu GitHub repository cnc-ar.

Hlavna stranka:
https://ppa-creator.github.io/cnc-ar/?v=104

Hlavna oprava:
- AR orientacia X/Y/Z sa fyzicky aplikuje na vertex data kazdej mesh/edge geometrie
- vysledny GLB ma identity root transform
- potom sa model polozi spodnou hranou na Y=0
- material, farebne plochy a AR hrany zostavaju zachovane

Odporucany test:
X +90 -> pockat na AR model: pripraveny -> ZOBRAZIT V AR
potom porovnat s RESET a X 0.

Subory nepremenovavaj.
