# QS_Testautomation

## Gruppe
 * Marco Lappe
 * Timo Max
 * Robin Wollenschläger

## Scope
 * User <--> PC <--> System <--> DB
 * Scope <--> System <--> DB

## Testziele
Funktionalität der REST-API Endpunkte testen

## Teststufen
Wahrscheinlich Systemtest

## Testobjekte
Jeder Endpunkt ein Testobjekt

## Risiko
 * Kriterien => Auswirkung auf den Kunden, (Anzahl Betroffene), Innen(Wirkung) auf Unternehmen, existiert Workaround (nur für Update vorhanden - delete + create)
 * Health Check von Scope ausschließen (keine Relevanz für Funktionalität) => kaum fachliches Risiko, sehr niedrige Komplexität
 * Auth höchstes fachl. Risiko (sehr hoch), hohe Komplexität
 * Get Endpoint (niedriges Risiko), niedrige Komplexität
 * Create, Update, Delete hohes Risiko (hohes Risiko), niedriges Komplexität

## Toolauswahl
* **Postman**
* einfach benutzbar
* kostenlos für unsere Zwecke
* geringe Programmierkenntnisse (Snippets, GUI)
* kompatibel/integrierbar mit GitHub
* für funktionale Tests geeignet

## Framework
* TF-Design
* Ausführung (TEX)
* Testreporting mit Postman
* Testdatenmngmt. wahrscheinlich auch
* Toolsetup: Konfigurationsmanagement mit Postman + Github Integration (Versionsverwaltung)

