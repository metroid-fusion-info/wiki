---
title: Choot
resources:
    - name: "choot.png"
      src: "choot.png"
      title: ""
    - name: "spit.png"
      src: "spit.png"
      title: ""
---

{{< columns >}}

Choot's lay still until Samus gets near them, at which point they rise up ~7 tiles into the air, and then spit underneath them approximately every second.

Its decompiled code can be found here: https://github.com/metroidret/mf/blob/main/src/sprites_AI/choot.c

<--->

{{< tabs "choot-data" >}}

{{< tab "Choot" >}}

{{< img name="choot.png" size="origin" >}}

{{< columns >}}

{{< center >}}
**General & Drops**
{{</ center >}}

|                   |      |
|-------------------|-----:|
| Health            | 16 |
| Damage            | 42 |
| Varia Reduction   |  80% |
| Gravity Reduction |  10% |
| Health X          |823/1024 |
| Missile X         |200/1024 |
| Refill X          |1/1024|
| Internal ID       |0x72 (Primary)|

<--->

{{< center >}}
**Weaknesses**
{{</ center >}}

|                              |    |
|------------------------------|---:|
| Beams and Bombs              | ✅ |
| Charge Beam                  | ❌ |
| Missiles                     | ✅ |
| Super Missiles               | ❌ |
| Power Bombs                  | ✅ |
| Speed Booster & Screw Attack | ✅ |
| Freezable                    | ✅ |

{{</ columns >}}

{{< /tab >}}
{{< tab "Spit" >}}

{{< img name="spit.png" size="origin" >}}

|                   |      |
|-------------------|-----:|
| Health            | 0 |
| Damage            | 40 |
| Varia Reduction   |  80% |
| Gravity Reduction |  10% |
| Internal ID       |0x3E (Secondary)|
| Weaknesses        | None |

{{< /tab >}}
{{< /tabs >}}

{{</ columns >}}



