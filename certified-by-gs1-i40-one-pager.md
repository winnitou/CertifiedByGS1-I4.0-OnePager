
![Logo](pics/Certified_by_GS1_Logo.png#logo)

# Sichere Idente für die Industrie 4.0 Certified by GS1

Sicherheitsfragen können in industriellen Anwendungen Missionskritisch werden, das gilt insbesondere wenn das Industrial Internet of Things (IIOT) Maschinen miteinander vernetzt und deren Steuerung und Konfiguration zunehmend über Netzwerkschnittstellen erfolgt. Eine gesicherte automatische Identifizierung und Authentifizierung ist für die Lösung dieser Fragen absolut notwendig.

**Wollen Sie mit uns an der Lösung der Sicherheitsfrage Arbeiten?**

## Use Case: Wandlungsfähige Fabrik

Im Anwendungsszenario "Wandlungsfähige Fabrik" der Plattform Industrie 4.0 wird die moderne Fabrik von vielfältigen Maschinen (Robotern, Werkzeuge, Fördertechnik, etc.) bevölkert, die im *Internet of Things (IoT)* miteinander Kommunizieren.
Die Maschinen selbst sind dynamisch in ihren Fähigkeiten, z.B. können Roboter und Werkzeuge umkonfiguriert werden um verschiedene Aufgaben auszuführen. Vor allem aber kommen verschiedene Maschinen verschiedener Hersteller gemeinsam in einer Fertigung zum Einsatz und müssen sich möglichst direkt untereinander abstimmen, um den aktuellen Auftrag zu fertigen. Hierdurch wird ein modularer und dadurch wandlungsfähiger Aufbau der Produktion innerhalb einer Fabrik realisiert.

![Anwendungszenario WFF aus [1]](pics/anwendungszenario-wff.png "Anwendungszenario WFF aus [1]")


Eine essentielle Voraussetzung hierfür ist, dass die Maschinen sich untereinander individuell identifizieren und Daten austauschen können, wie in der folgenden Grafik (angelehnt an die Veröffentlichung des VDMA [2]) dargestellt:

![Abgeleitet von: Werkzeugkaste Industrie 4.0 aus [2,3]](pics/werkzeugkaste-i40-vdma-part.png "Abgeleitet von: Werkzeugkaste Industrie 4.0 aus [2,3]")

Hervorgehoben sind die Identifikation und Einbindung von Industrial IoT (IIoT) Devices und der Datenaustausch als notwendige Voraussetzung für die Industrie 4.0.

Ein Standard für die automatische Identifikation und Authentifizierung ist unabdingbar, um die Abhängigkeit von einem zentralen Plattformanbieter zu vermeiden. Zudem sind Sicherheitsfragen, insbesondere Vertrauensfragen, äußerst relevant, um zu verhindern, dass unautorisierte Maschinen in die Fertigungsstraße eingebracht, gefälschte Daten eingeschleust werden oder gar ein unautorisierter zugriff über das Internet erfolgen kann.


## Certified by GS1

Im Rahmen des Certified by GS1 Projektes entwickelt GS1 Germany gemeinsam mit interessierten Industrieunternehmen eine Lösung für das Problem der eindeutigen und authentifizierten Identifikation von Dingen im IIoT, basierend auf den etablierten GS1 Standards und Identen und unter Einbindung der technischen Expertise von GS1 Solution Providern mit langjährigem IoT-Know How.

### IDs

GS1 vergibt bereits heute weltweit eindeutige Idente nach einem anerkannten Standard.
Bekanntestes Beispiel sind die im Einzelhandel in den Barcodes (EAN) codierten Global Trade Item Numbers (GTINs). **[TODO: Wie viele GS1 Idente sind im Umlauf? Referenzkunden im Technischen/Industriellen Bereich? weitere generische Fakten?]** Die insgesamt 12 verfügbaren GS1 Keys werden bereits bei 60.000 Kunden branchenübergreifend eingesetzt, z.B. auch bei der Deutschen Bahn oder der Bundeswehr.

Neben handelsspezifischen Identen gibt es Idente speziell für das Asset Management z.B. von Maschinen (Global Individual Asset Identifier, GIAI) und von (Maschinen-)Bauteilen (Component / Part Identifier, CPI).

Grundsätzlich vergibt GS1 einen Namensraum solcher Idente (konkret ein numerisches Präfix) an Unternehmen, die daraus dann die eigenen Idente nach dem standardisierten Schema ableiten. Ähnlich wie bei Internet Domain Names besteht der große Vorteil einer zentralen Registratur in der garantierten globalen Eindeutigkeit der Idente und der Zuordnung der Idente zum ausstellenden Unternehmen.

Besonders interessant sind in vielen Use Cases serialisierte Idente mit deren Hilfe individuelle Teile und Maschinen identifiziert werden können. Ein solches Ident kann, ähnlich wie die Personalausweisnummer, eine Maschine oder einen Sensor eindeutig identifizieren und von baugleichen Maschinen unterscheiden, um z.B. Wartungen und Umkonfiguration eindeutig zuordnen zu können.


### Zertifikate

Im Certified by GS1 Projekt wird aktuell ein System entwickelt, dass es Firmen ermöglicht, nicht nur weltweit eindeutige IDs für Ihre Produkte zu erzeugen, sondern gleichzeitig auch Zertifikate zu erstellen, welche die Echtheit der IDs beglaubigen. So wird verhindert, dass Idente von einer unberechtigten Partei generiert werden können. Durch physikalische Schutzmaßnahmen wie Hardware Security Modules (HSMs) kann so auch Markenschutz implementiert werden, d.h. Produktfälschung wird erheblich erschwert.

Besonders interessant im Kontext Industrie 4.0 ist, dass sich IIoT Geräte mit Hilfe der Zertifikate untereinander eindeutig und sicher identifizieren und sichere Kommunikationskanäle aufbauen oder Messdaten signieren können. So wird sichergestellt, dass nur Maschinen die den Anforderungen genügen in die Fertigung eingebaut und Messwerte nicht gefälscht oder manipuliert werden können.
![Zertifikatskette](pics/Certificate-Chain.png "Zertifikatskette")
Durch kryptografische Signatur und Zertifikatsketten kann sich ein (I)IoT Device, etwa eine neue Maschine in einer Fabrik, eindeutig und fälschungssicher ausweisen.


## Quellen/Referenzen
- [1] [Fortschreibung der Anwendungsszenarien der Plattform Industrie 4.0](https://www.plattform-i40.de/PI40/Redaktion/DE/Downloads/Publikation/fortschreibung-anwendungsszenarien.html)
- [2] [Leitfaden Industrie 4.0 (VDMA - Forum Industrie 4.0)](https://industrie40.vdma.org/viewer/-/v2article/render/15540546)
- [3] [Wandlungsfähige, menschzentrierte Strukturen in Fabriken und Netzwerken der Industrie 4.0 (acatech Studie), München: Herbert Utz Verlage 2018.](https://www.plattform-i40.de/PI40/Redaktion/DE/Downloads/Publikation/hm-2018-fb-wandlung.html)
