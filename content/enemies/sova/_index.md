---
title: Sova
resources:
    - name: "sova.png"
      src: "sova.png"
      title: ""
    - name: "fire.png"
      src: "fire.png"
      title: ""
---

{{< columns >}}

Sovas are sometimes called Novas.

Sovas crawl back along walls and slopes, and will turn around once they hit a 90° corner. Depending on their angle, they will either leave trails of fire behind them of drop flames down. Those patterns are as follows:
- When on the ground it will leave 3 trails down every 3.5 seconds, with them being spaced 32 frames apart.
- When on the ceiling, on a left wall or a right wall, they drop a flame every 3 seconds.

Its decompiled code can be found here: https://github.com/metroidret/mf/blob/main/src/sprites_AI/sova.c  

<--->

{{< tabs "sova-data" >}}

{{< tab "Sova" >}}

{{< img name="sova.png" size="origin" >}}

{{< columns >}}

{{< center >}}
**General & Drops**
{{</ center >}}

|                   |      |
|-------------------|-----:|
| Health            | 10 |
| Damage            | 30 |
| Varia Reduction   |  30% |
| Gravity Reduction |  10% |
| Health X          |923/1024 |
| Missile X         |100/1024 |
| Refill X          |1/1024|
| Internal ID       |0x6C (Primary)|

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
{{< tab "Fire Projectile" >}}

{{< img name="fire.png" size="origin" >}}

|                   |      |
|-------------------|-----:|
| Health            | 0 |
| Damage            | 36 |
| Varia Reduction   |  60% |
| Gravity Reduction |  30% |
| Internal ID       |0x39 (Secondary)|
| Weaknesses        | None |

{{< /tab >}}
{{< /tabs >}}

{{</ columns >}}
