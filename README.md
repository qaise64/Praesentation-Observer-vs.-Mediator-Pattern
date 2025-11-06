# Praesentation: Observer vs. Mediator Pattern

Hallo! Dies ist eine Praesentation, die ich im September 2025 fuer mein Seminar "Entwurfsmuster" an der Hochschule Niederrhein gehalten habe.

## Worum ging es?

In der Software-Architektur ist **enge Kopplung** eines der groessten Probleme, das zu schwer wartbarem Code fuehrt.

In dieser Praesentation habe ich zwei fundamentale Loesungsansaetze (Verhaltensmuster) analysiert und verglichen, die dieses Problem loesen:

1.  **Das Observer-Muster:** Perfekt fuer 1-zu-N-Beziehungen, bei denen ein Objekt (das Subjekt) viele andere (die Observer) ueber Aenderungen informieren muss, ohne sie direkt zu kennen.
2.  **Das Mediator-Muster:** Ideal, um chaotische "Viele-zu-Viele"-Kommunikation zu buendeln, indem ein zentraler Mediator die gesamte Interaktion steuert.

### Was ich in der Praesentation beleuchte:

* **Der Kern-Unterschied:** Wann verwende ich eine "Broadcast"-Logik (Observer) und wann einen "zentralen Hub" (Mediator)?
* **Praxisbeispiele:** Wie das Observer-Muster im MVC-Pattern funktioniert und wie der Mediator komplexe UI-Dialogfenster vereinfacht.
* **Vor- & Nachteile:** Ich analysiere die Gefahren, wie "kaskadierende Updates" beim Observer oder die "God Object"-Gefahr beim Mediator.
