<<<<<<< Arbeitsversionen
# Bearbeitung der eingegangenen Issues innerhalb der Taskforce Prozessmodelle
=======
# Bearbeitung von eingegangenen Issues innerhalb der Taskforce Prozessmodelle 
>>>>>>> main

**Ziel**<br> 
Strukturierte Prüfung, Bearbeitung und Dokumentation von Issues 
  
**Vorgehensweise** 

1. Zuweisung prüfen 
- Nach Eingang eines Issues prüft die verantwortliche Person, ob das Issue (korrekt) zugewiesen wurde.
- Gegebenenfalls weist die verantwortliche Person das Issue sich selbst oder einer zuständigen Person zu.
- Ist die Zuständigkeit unklar, wird das issue in einer Sitzung der TF Prozessmodelle besprochen und zugewiesen. 

2. Status über Label im Issue anpassen

3. Issue bearbeiten<br>
a) **Übernahme der Anmerkung** <br>
i. Prüfen ob eine Vorlage bei den AGs und beim NSG erforderlich  
b) **Ablehnung** (mit Begründung als Kommentar im Issue) 

<<<<<<< Arbeitsversionen
4. Bearbeitung umsetzen – in Signavio o.a. Software zur Modellierung von PM 
- neuer Branch mit Erwähnung der issue-nummer 
- Änderungen in der Datei vornehmen
- Änderung committen mit Erwähnung der issue-nummer
- Branch pushen – nicht auf Main Branch – siehe folgender Schritt “Pull Request” 

5. Pull Request (PR) erstellen
- Auf GitHub einen neuen Pull Request erstellen und das Issue referenzieren
=======
4. Wenn a) - neuen Branch erstellen
- über das Issue gehen und "create new branch" wählen, aus main heraus

6. Bearbeitung umsetzen – in Signavio o.a. Software zur Modellierung von PM 
- Änderungen in der Datei vornehmen
- ggf. Datei hochladen, Änderung committen mit Angabe der issue-nummer
- Branch pushen – nicht auf Main Branch, sondern auf den eigenen branch des issues – siehe folgender Schritt “Pull Request” 

5. Pull Request (PR) erstellen
- Auf GitHub einen neuen Pull Request vom Issue-branch erstellen und das Issue referenzieren
>>>>>>> main
- Kurze Beschreibung der Änderung einfügen
- Verantwortliche Person zuweisen 
- Hinweise:
  - Der main branch enthält ausschließlich beschlossene Modelle
  - Der Arbeitsbranch enthält Arbeitsstände
  - Feature und Änderungen werden in eigenen Branches committed

6. Review und Merge 
- Review des Pull Request nach internem Review-Prozess
<<<<<<< Arbeitsversionen
- Nach Freigabe den Pull Request in den Hauptbranch mergen
=======
- Nach Freigabe den Pull Request in den Arbeitsbranch oder Hauptbranch mergen (je nach Änderung und Beschlussbedarf)
>>>>>>> main
- Release notes und tag für Modellversion vergeben
  - Release notes: Benennung Ebene, betreffendes Prozessmodell und neu vergebene Versionierung
  - Beispiel: 2.A.2_Machbarkeitsanfragen-einfach_v1.0.**3**
  
- Hinweise:
  - Wenn es sich nicht um eine Arbeitsstandversion handelt, in den release notes als pre-release kennzeichnen
  - Dreistufige Versionsnummerierung für Prozessmodelle: [x.y.z]
<Änderungen mit Auswirkungen auf Interoperabilität zu höheren oder niedrigeren Modellebenen>.<Änderungen im Prozessablauf>.<redaktionelle Änderungen>

7. Issue schließen (optional)
- Falls nicht bereits durch pull request geschlossen 
