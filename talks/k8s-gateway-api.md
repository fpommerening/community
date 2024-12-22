## Titel
Kubernetes Gateway API

## Untertitel
Alles, was Ingress immer sein wollte

## Typ
Talk

## Sprache
Deutsch

## Schlagworte
Kubernetes, Traefik, Gateway API

## Level
Fortgeschritten

Ingress war als das zentrale Konzept für den Zugriff auf Anwendungen in Kubernetes gedacht – herstellerunabhängig und flexibel. Doch in der Praxis führten die Konfiguration per Annotations sowie Custom Resource Definitions (CRDs) zu fehlende Interoperabilität zwischen verschiedenen Implementierungen.

In diesem Vortrag folgen wir der Entwicklung der Kubernetes Gateway API, die von der Kubernetes SIG-Network (Special Interest Group Networking) ins Leben gerufen wurde, um diese Herausforderungen von Ingress zu adressieren. Wir betrachten, wie die ersten Ideen zur Gateway API entstanden und wie sie sich bis zur stabilen Version 1.0 im Jahr 2023 weiterentwickelt hat. Dabei gehen wir auf zentrale Konzepte wie die klare Trennung von Verantwortlichkeiten und die Einführung von rollenbasierten Architekturen ein, die sie zu einer flexiblen und erweiterbaren Lösung machen.

Im praktischen Teil zeige ich anhand konkreter Beispiele mit Traefik, wie die Gateway API heute in realen Kubernetes-Clustern implementiert werden kann und welche Vorteile sie dabei bietet. Zusätzlich vergleiche ich die neue Gateway API mit den bisherigen Ingress-Definitionen, um die Verbesserungen und Unterschiede zu verdeutlichen.

Der Vortrag richtet sich an alle, die Kubernetes-Umgebungen verwalten, sei es aus einer Operations- oder DevOps-Perspektive. Seid dabei und erhaltet einen leicht verständlichen und praxisorientierten Einblick in die Möglichkeiten der Gateway API sowie Lösungsideen für den eigenen Arbeitsalltag.