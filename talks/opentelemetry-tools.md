## Titel
Ein Collector ist noch (k)ein Monitoring

## Typ
Talk

## Sprache
Deutsch

## Schlagworte
Monitoring, OpenTelemetry, CNCF

## Level
Fortgeschritten

Viele starten ihre Observability-Reise mit OpenTelemetry: ein paar Konfigurationen, die ersten Daten fließen – doch Daten per Connector sammeln ist noch kein Monitoring. Aus Daten sollen Erkenntnisse und Entscheidungen werden; dazu müssen sie effektiv gespeichert und verarbeitet werden.

In diesem Talk berichte ich praxisnah, wie wir Prometheus als Metrik-Backend mit nativen OpenTelemetry-Features eingesetzt haben. Thanos ergänzt Prometheus für Langzeitspeicherung und Trend-Erkennung (inklusive S3-Integration) und spart dabei Speicherplatz. Für Logs nutzen wir Loki, das besonders effizient ist und ebenfalls S3 zur Speicherung verwenden kann, sodass sich eine skalierbare Infrastruktur aufbauen lässt. Traces erfassen wir mit Jaeger, wodurch Abläufe über Dienste hinweg nachvollziehbar werden. Metrics, Logs und Traces bilden zusammen die Basis für eine schnelle Analyse, und alles zusammen visualisieren wir in Grafana.

Als Ausblick zeige ich, wie Grafana Alloy die Observability-Landschaft vereinfacht, indem es Metriken, Logs und Traces auf einer Plattform zusammenführt und Teams eine kollaborative Oberfläche bietet.

Wenn ihr wissen wollt, wie man aus ersten Daten echtes Monitoring macht, Trends erkennt und die Tool-Landschaft clever kombiniert, dann kommt vorbei – ich teile praxisnahe Tipps, Aha-Momente und sofort nutzbare Erkenntnisse für euren DevOps-Alltag!