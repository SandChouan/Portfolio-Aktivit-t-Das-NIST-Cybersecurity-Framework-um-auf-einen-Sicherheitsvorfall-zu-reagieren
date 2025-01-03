# Portfolio-Aktivit-t-Das-NIST-Cybersecurity-Framework-um-auf-einen-Sicherheitsvorfall-zu-reagieren
 Schritt-für-Schritt-Anweisungen ausführen
Als Cybersicherheitsanalytiker für ein Multimedia-Unternehmen, das Webdesign, Grafikdesign und Social Media Marketing-Lösungen für kleine Unternehmen anbietet. Das Unternehmen wurde vor kurzem Opfer eines DDoS-Angriffs, der das interne Netzwerk zwei Stunden lang beeinträchtigte, bis er behoben war.

Während des Angriffs reagierten die Netzwerkdienste des Unternehmens plötzlich nicht mehr, weil eine Flut von ICMP-Paketen eintraf. Der normale interne Netzwerkverkehr konnte auf keine Netzwerkressourcen zugreifen. Das Incident Management Team reagierte, indem es eingehende ICMP-Pakete blockierte, alle nicht kritischen Netzwerkdienste offline schaltete und kritische Netzwerkdienste wiederherstellte.

Das Cybersicherheitsteam des Unternehmens untersuchte daraufhin das Sicherheitsereignis. Es stellte fest, dass ein böswilliger Akteur eine Flut von ICMP-Pings über eine unkonfigurierte Firewall in das Unternehmensnetzwerk gesendet hatte. Diese Schwachstelle ermöglichte es dem böswilligen Angreifer, das Netzwerk des Unternehmens durch einen verteilten Denial-of-Service-Angriff (DDoS) zu überwältigen.

Um dieses Sicherheitsereignis zu beheben, implementierte das Netzwerksicherheitsteam:

Eine neue Firewall-Regel zur Begrenzung der Rate eingehender ICMP-Pakete

Überprüfung der Quell-IP-Adresse auf der Firewall, um die eingehenden ICMP-Pakete auf gefälschte IP-Adressen zu überprüfen

Netzwerküberwachungssoftware zur Erkennung abnormaler Verkehrsmuster

Ein IDS/IPS-System, um einen Teil des ICMP-Verkehrs auf der Grundlage verdächtiger Merkmale herauszufiltern

Als Cybersecurity-Analysten habe ich die Aufgabe, auf der Grundlage dieses Sicherheitsereignisses einen Plan zur Verbesserung der Netzwerksicherheit in dem Unternehmen zu erstellen und dabei das Cybersecurity Framework (CSF) des National Institute of Standards and Technology (NIST) zu berücksichtigen. Sie werden das CSF verwenden, um sich durch die verschiedenen Schritte der Analyse dieses Cybersecurity-Ereignisses zu bewegen und Ihre Analyse in eine allgemeine Sicherheitsstrategie zu integrieren. In der folgenden Vorlage wurde die Analyse in verschiedene Teile unterteilt:

Identifizieren Sie Sicherheitsrisiken durch regelmäßige Überprüfungen interner Netzwerke, Systeme, Geräte und Zugriffsrechte, um potenzielle Sicherheitslücken zu ermitteln.

Schutz interner Vermögenswerte durch die Umsetzung von Richtlinien, Verfahren, Schulungen und Tools, die zur Eindämmung von Cybersecurity-Bedrohungen beitragen.

Erkennung potenzieller Sicherheitsvorfälle und Verbesserung der Überwachungsfunktionen, um die Geschwindigkeit und Effizienz der Erkennung zu erhöhen.

Reagieren auf die Eindämmung, Neutralisierung und Analyse von Sicherheitsvorfällen; Implementierung von Verbesserungen im Sicherheitsprozess.

Wiederherstellung des Normalbetriebs betroffener Systeme und Wiederherstellung von Systemdaten und/oder Assets, die von einem Vorfall betroffen sind. 
