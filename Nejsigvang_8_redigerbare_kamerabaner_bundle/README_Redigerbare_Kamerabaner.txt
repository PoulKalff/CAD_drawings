REDIGERBARE KAMERABANER I NEJSIGVANG-MODELLEN
==============================================

FreeCAD-fil:
Nejsigvang_8_original_med_redigerbare_kamerabaner.FCStd

Nye objekter i modellen:
1. CameraPath 360 - REDIGERBAR
   Internt navn: CameraPath360
   Stor oval rundt om hele modellen, ca. 8,5 m over modellens nulniveau.
   24 redigerbare Draft-punkter.

2. FocusPath - REDIGERBAR
   Internt navn: FocusPath
   Mindre oval omkring huset, ca. 1,9 m over modellens nulniveau.
   20 redigerbare Draft-punkter.

Sådan ændrer du banerne:
- Skift til Draft Workbench.
- Markér CameraPath eller FocusPath i modeltræet.
- Brug Draft Edit / redigering af Draft-objektet, så knudepunkterne vises.
- Flyt punkterne til de ønskede positioner.
- Gem modellen.

Testmakro:
Follow_Editable_Camera_Focus_Paths.FCMacro

Makroen læser de aktuelle punkter fra begge baner, hver gang den startes.
Derfor behøver du ikke ændre makroen, bare fordi du flytter punkterne.
Den udglatter bevægelsen mellem Draft-punkterne med Catmull-Rom interpolation.
