# Was RackWorks schon kann

Stand: **26.10.2026** · Testversion

Alles hier ist in der Testversion spielbar. Was noch gebaut wird, steht in [ROADMAP.md](ROADMAP.md).

---

## Konto & Spielstände

- Konto mit Name + Passwort, **ohne E-Mail**. Bei der Registrierung gibt es einen **Wiederherstellungscode** –
  damit setzt du ein vergessenes Passwort zurück. Gut aufheben!
- Mehrere Spielstände pro Konto. Der Spielstand liegt auf dem Server: auf allen Geräten live derselbe Stand.
- **Export / Import** von Spielständen als Datei (signiert, damit niemand daran herumschraubt).
- Verbindung weg? Das Spiel zeigt einen Hinweis und **verbindet sich automatisch neu**.
- Tempo: Pause, 1×, 2×, 4×. Ohne verbundenes Gerät steht die Spielzeit still.

## Halle & Aufbau

- 3D-Halle mit echten Maßen (Doppelbodenplatten, Schränke in Höheneinheiten), Hell- und Dunkel-Thema.
- **Platzieren mit Vorschau** (grün = passt, rot = belegt), **Drehen mit R**, Verschieben, Abbauen.
- Serverschränke **24 / 42 / 48 HE**, Stromverteiler (auch Drehstrom), USV (klein, groß, Raum-USV),
  Klimageräte, Klimaschrank, Freikühler, In-Row-Kühler, Notstromaggregat.
- **Kabeltrassen** über den Schränken, Kaltgang-Lochplatten, gelochte Schranktüren.
- Kabel-Info beim Drüberfahren (von wo nach wo, was fließt). Verkabeln auch über Hallen hinweg.
- **Mehrere Hallen:** Keller → Gewerbehalle → Rechenzentrum-Neubau → Campus-Erweiterung.

## Server bauen (Werkbank / Konfigurator)

- Server in **3D zusammenbauen**: Gehäuse, Mainboard, CPU, RAM, Laufwerke, Karten, Kühler, Lüfter, Netzteile.
- **Echte Teile** mit Datenblatt-Quelle (Abzeichen „ECHT“): 15 echte Server-Mainboards (ASRock Rack,
  Supermicro, Gigabyte), echte CPUs, Server-RAM, Laufwerke, RAID-Controller, GPUs, Netzwerkkarten, Kühler,
  Lüfter, Netzwerkgeräte. Prozessoren, Laufwerke und RAID-Controller gibt es nur noch als echte Modelle.
- **Kompatibilitätsprüfung:** Sockel, CPU-Freigabe je Mainboard, Speicherkanäle, Steckplätze, Platz für GPUs.
- Einsetzen per Klick oder **Drag & Drop** mit Vorschau am Zielplatz, Ansichten vorn / hinten / oben.
- **Speicher-System:** echte Schachtmaße, Backplanes (SAS/SATA/NVMe), HBA/RAID-Controller,
  RAID 0/1/5/6/10, Kabel mit Biegeradius, Hot-Swap.
- Eigenbau-Platinen (leeres PCB, Leiterbahnen selbst ziehen) als Experten-Modus.
- Fertige Bauten speichern und wiederverwenden.

## Schränke bestücken (Rack-Editor)

- Schrank öffnen und **von vorn und hinten bestücken**: Server und Netzwerkgeräte aus dem Lager auf eine
  Höheneinheit ziehen, verschieben, ausbauen.
- Echte Frontblenden, Patchkabel-Ansicht hinten.
- „Schnell einbauen“ für Eilige.

## Strom, Kühlung, Netz

- Strom: Verteiler, Last je Abgang, **Hausanschluss in Stufen** (bis 43 kW, eigene Trafostation 200 kW).
- **A/B-Einspeisung:** zweiter Hausanschluss mit eigenen Ausfällen, Notstromaggregat als Einspeisung C.
- **Stromtarife und Internetanbieter** wählbar; Strompreis wirkt auf die Kosten.
- Wärme und Kühlung: Temperatur je Schrank, Kaltgang-Einhausung, Freikühler, In-Row-Kühler.
- Netz: Switch, Router, Firewall, Load Balancer, DDoS-Schutz – echte Geräte (MikroTik, FortiGate, FortiDDoS).
- **Internet in Stufen** bis 100 Gbit/s Carrier-Anbindung, Backup-Leitung.
- **Netzwerkschränke:** zentrale Netztechnik, Uplink-Tempo je Verbindung, Engpässe, **Netzplan** im Leitstand.
- DDoS-Angriffe, Störungen, Laufwerksausfälle – die Oberleiste sagt dir, wo der Engpass liegt.

## Aufträge & Wirtschaft

- Kunden-Aufträge mit Anforderungen (Rechenleistung, RAM, Speicher, Netz) – **viele Auftragsarten**,
  auch **Daueraufträge** (unbefristet, gut bezahlt) und **GPU-Aufträge** (KI, Rendering, GPU-Cloud).
- **SLA-Verträge** mit Vertragsstrafe, **HA-Paare** mit Standby-Server für Kunden, die keine Ausfälle dulden.
- **Gebrauchtmarkt:** gebrauchte Komplettserver kaufen, eigene Server anbieten.
- **Click & Collect:** fertige Server und **bestückte Schränke bestellen**, Lieferung, Aufstellen.
- Finanzen mit Tagesergebnis, Miete, Internet- und Servicekosten.

## Firma & Management

- **Management-Abteilung** nimmt Aufträge automatisch an und verteilt sie auf passende Server.
- **Postfach** mit Tagesbericht und Alarmen.
- **Personal:** Techniker reparieren und warten, die Montage baut Server ein – mit Arbeitsprotokoll.

## Fortschritt

- **Level 1–12**, Erfahrung aus Einnahmen.
- **Forschung** mit Ästen (Energie, Anbindung, Gebäude, Kühlung): neue Teile und Ausbauten freischalten,
  Kosten steigen je Stufe.
- Ziele mit Hinweisen für den Einstieg.
- **Standort wirkt:** Solar im Süden, Windstrom im Norden, Peering am Internet-Knoten.

## Überblick behalten

- **Leitstand:** alle Server mit Last, Temperatur, Strom, Zustand, Aufträgen; sortierbar.
- **Kennzahlen** dauerhaft ab Tag 1 (alle 15 Spielminuten): Zeitraum, Zoom, Vergleiche, Ereignisse, CSV-Export.
- **Weltkarte:** Standorte aller Spieler, Kennzahlen, **Bestenliste**, Ebenen für Glasfaser-Backbone und Energie.

## Darstellung & Geräte

- Qualitätsstufen (⚙): Automatisch / Niedrig / Mittel / Hoch. **F3** zeigt FPS und Grafikkarte.
- Selbsttest beim Start: Macht die Grafik Probleme, schaltet das Spiel automatisch auf „sicher“ um.
- Läuft auch auf dem Handy (eingeschränkt).
