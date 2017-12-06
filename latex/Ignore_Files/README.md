# Information

Allgemeine gitignore ...

Zwei verschiedene ignore-Files:

1. Keine PDF erlaubt (gitignore_No-PDF):

   - Für den Fall, dass ihr keine Graphiken, Bilddateien, die vom Format PDF sind,  oder andere relevante PDFs habt, die ihr in das Dokument einfügen müsst, könnt ihr diese gitignore nehmen.

2. Alle PDF sind für den upload erlaubt (gitignore_PDF-Allowed):

   - Für den Fall, dass ihr Bilder, Graphiken, oder andere relevante PDFs in euer Dokument einfügen müsst, die vom Datentyp PDF sind, ist diese Datei die richtige. 

   - WICHTIG: Ihr könnt hier eure eigene generierte PDF (Das fertige Dokument) auslassen in dem ihr diese in dem Bereich ...

     *————————————————————

     "## Generated if empty string is given at 'Please type another file name for output:'"

     "#-- the Name of your generated PDF --

     *————————————————————

     … bei —the Nameof your generated PDF — eintragen. Bitte dann die Raute am Anfang entfernen!

Eigentlich ist alles damit abgedeckt ...



## Zum hinzufügen zum LaTeX-Projekt:

- Punkt "." vor dem Namen einfügen
- In die Projektordner einfügen (1. Ebene) 
- Git verwenden wie gewohnt … 