# Aufgabe 1 View erstellen

Als erste Aufgabe werdet ihr eine List View anlegen und erweitern.

---

## Teil 1: List View anlegen

Geht in euer BAS und erstellt ein neues Projekt mit Template. Wählt wieder Fiori Generator aus, nur wählt ihr danach <u>nicht</u> eine Freestyle App aus indem ihr das Basic Layout verwendet, sondenr nutzt den Floorplan List Report Page.
Als OData nehmen wir diesmal keinen vom System, sondern wählen einen online verfügbaren Odata aus. Dafür verbindet ihr euch nicht zum System, sondern wählt den zweiten Punkt aus und gebt folgenden Link ein:<br>
https://services.odata.org/V2/Northwind/Northwind.svc/.<br>
Als Entität könnt ihr Categorie verwenden, aber ihr könnt auch gerne andere Entitäten verwenden.
Nutzt eine Responsive Table.

---

## Teil 2: Schaut euch die App an.
Startet die App und schaut sie euch an. Navigiert dafür entweder wieder über die Konsole und startet mitels npm run, oder wählt per Rechtsklick auf der Webapp die Aktion Preview Application aus. Navigiert durch die App und schaut sie euch an. 
Zusätzlich könnt ihr wieder über Rechtsklick die Page Map anzeigen lassen. Dort seht ihr die einzelnen Felder und könnt auch Änderungen vornehmen.

---

## Teil 3: Änderung in der Page Map

Geht nun Per Rechtsklick auf der webapp in die Option Show Page Map. Über den Stift auf dem List Report könnt ihr in die Felder der Tabelle rein navigieren. Wählt hier das Feld Product aus und ändert die beiden Werte.
Setzt den Allign auf Rechts und verkürzt das Feld auf "10rem". Schaut euch am besten vorher die App an udn seht welche Änderungen ihr mit diesen Einstellungen bewirkt.

---

## Teil 4: Guided Development

Geht wieder per Rechtsklick auf der webapp in die Guided Development. Wählt den Guide Add an Action Button aus. Hier habt ihr nun einen guide der euch druchführt und nur noch ein wenig input von euch braucht um Coding zu erzeugen.
Wählt im Inputfeld Entity Type SEPMRA_C_PD_ProductType aus. Weiter unten könnt ihr nun die verfügbaren Functions importieren. Wählt dafür SEPMRA_C_PD_ProductCopy_new_supplier aus. Vergebt einen Namen.
<details>
  <summary>Bonus Sprachenabhängigkeit</summary>
    <blockquote>
    Wenn ihr wollt könnt ihr zusätzlich auf die Weltkugel innerhalb des Namensfeldes drücken. Damit ersetzt ihr den fest definierten Namen mit einer Variablen. Dies wird umgesetzt durch I18N Dateien. Es gibt einen Ordner der I18N heißt. Dort gibt es bereits eine Datei mit dem Namen i18n.properties. (Es kann sein das ihr voher add snippet drücken müsst) Legt zusätzlich die dateien i18n_en.properties und i18n_de.properties per Rechtsklick in den gleichen Ordner an. Dort könnt ihr das eben erstellte i18n Objekt im gleichen Format wie in der ursprünglichen i18n.properties Datei. <br>
      Beispiel: copyToNewSupplier=Copy to new Supplier <br>
      In der de datei könnt ihr dann einen deutschen Namen vergeben, in der en datei den englischen. Das Framework wählt die Sprache entsprechend der Anmeldesprache aus. 
    </blockquote>
</details>
<br>
Drückt zum Schluss Add Snippet udn schaut euch eure neu geladene App an.

