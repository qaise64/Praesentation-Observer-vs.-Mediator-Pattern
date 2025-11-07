# Praesentation: Observer vs. Mediator Pattern

Dies ist eine Praesentation, die ich im September 2025 fuer mein Seminar "Entwurfsmuster" an der Hochschule Niederrhein gehalten habe.

[**Hier geht's direkt zur vollstaendigen Praesentation (PDF) – sie oeffnet im Browser.**](./Entwurfmuster.pdf)

## Worum ging es?

In der Software-Architektur ist **enge Kopplung** ein bekanntes Problem, das zu schwer wartbarem Code fuehren kann.

Diese Praesentation stellt zwei Loesungsansaetze (Verhaltensmuster) vor und vergleicht sie:

1.  **Das Observer-Muster:** Definiert eine 1-zu-N-Beziehung, bei der ein Objekt (das Subjekt) viele andere (die Observer) ueber Aenderungen informiert, ohne sie direkt zu kennen.
2.  **Das Mediator-Muster:** Buendelt "Viele-zu-Viele"-Kommunikation, indem ein zentraler Mediator die gesamte Interaktion steuert.

### Behandelte Themen:

* **Der Kern-Unterschied:** Wann wird eine "Broadcast"-Logik (Observer) verwendet und wann ein "zentraler Hub" (Mediator)?
* **Praxisbeispiele:** Die Anwendung des Observer-Musters im MVC-Pattern und der Einsatz des Mediators zur Vereinfachung von UI-Dialogfenstern.
* **Vor- & Nachteile:** Eine Gegenueberstellung der potenziellen Risiken, wie "kaskadierende Updates" (Observer) oder die "God Object"-Gefahr (Mediator).
