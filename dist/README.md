# ÁTMENETI mappa — ne ide dolgozz

A buildek 2026-09-05 óta a **`packs/`** mappába kerülnek. Ez a `dist/` csak azért
él még, mert a DEV proxy `txpack/config.properties`-ében a `public-url` a régi
útvonalra mutat, és a config **csak proxy-restartkor** olvasódik újra.

A proxy következő újraindítása után ez a mappa **törölhető**.
