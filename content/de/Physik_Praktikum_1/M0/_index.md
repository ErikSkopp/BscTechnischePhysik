---
title: Praktikum - M0 - Messabweichungen
toc: true
type: docs
math: true
---

{{< callout type="warning" >}}
Das Praktikum findet am 21.10.2024 statt
{{< /callout >}}

## Links

{{< cards >}}
{{< card title="Praktikums Website" link="https://www.tu-ilmenau.de/universitaet/fakultaeten/fakultaet-mathematik-und-naturwissenschaften/profil/institute-und-fachgebiete/institut-fuer-physik/profil/physikalisches-grundpraktikum/uebersicht/mechanik" tag="Website TU-Ilmenau" >}}
{{< card link="../M0.pdf" title="Versuchsanleitung" tag="PDF" >}}
{{< card link="#" title="Messdaten" tag="nocht nicht verfügbar" >}}
{{< card link="#" title="Protokoll" tag="nocht nicht verfügbar" >}}
{{< /cards >}}

## Versuchsanleitung

### Aufgabenstellung

#### Aufgabestellung

1. Die Periodendauer eines Fadenpendels ist mehrmals zu messen. Die Häufigkeitsverteilung der Messwerte ist in Abhängigkeit von der Anzahl $n$ der Messungen in geeigneten Histogrammen darzustellen.

2. Für $n = 200$ Messwerte sind Schätzwerte für die Standardabweichung $\sigma$ und den wahren Wert $\mu$ der Messgröße anzugeben und mit grafisch ermittelten Ergebnissen zu vergleichen.

3. Aus Periodendauer und Länge des Pendels ist die Schwerebeschleunigung der Erde einschließlich ihrer kombinierten Unsicherheit zu berechnen.

#### Kontrollfragen

1. Was versteht man unter einer Messabweichung? In welche beiden Kategorien werden sie unterteilt?

2. Wie sieht die Dichtefunktion der Normalverteilung aus? Wie sieht das zugehörige Integral aus und was kann man daraus ablesen?

3. Was gibt die Standardabweichung an?

| Intervall-Nr. | Intervallmitte $T_k$ (s) | Häufigkeiten                         | Häufigkeitssummen                    |
|---------------|--------------------------|--------------------------------------|--------------------------------------|
| $k$           |                          | $H_{k,10}$ | $H_{k,25}$ | $H_{k,50}$ | $H_{k,100}$ | $H_{k,200}$ | $HS_{k,200}$ | $HS_{k,200,rel}$ (%) |
| 0             | $T_i < T_a$              |                                      |                                        |
| 1             | $T_1$                    |                                      | $H_{1,200}$                           |
| 2             | $T_2$                    |                                      | $H_{1,200} + H_{2,200}$               |
| $\vdots$      | $\vdots$                 |                                      | $\vdots$                              |
| $r+1$         | $T_i > T_e$              |                                      |                                        |
