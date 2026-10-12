# Poddock — Release-Artefakte

Dieses Repository enthält die öffentlich erreichbaren Artefakte der
Poddock-Releases: **Binär-Tarballs** (Daten, x86_64, aarch64) und die
**Screenshots** für die AppStream-Metainfo. Es enthält **keinen Quellcode**;
der Quellcode bleibt privat.

Die Tarballs werden automatisch vom Release-Workflow des privaten
Haupt-Repositories hochgeladen.

## Screenshots (`screenshots/`)

Die AppStream-Metainfo der App verlinkt die Screenshots **tag-gepinnt**:

```
https://raw.githubusercontent.com/tim-gromeyer/poddock-releases/screenshots-1/screenshots/<name>.png
```

Flathub verlangt für in Git gehostete Bilder ausdrücklich einen **Tag oder
Commit — keinen Branch** (MetaInfo-Guidelines). Den Tag `screenshots-1` also
nicht verschieben oder löschen; für neue Bilder einen neuen Tag
(`screenshots-2`) anlegen und die Metainfo im Haupt-Repository nachziehen.
