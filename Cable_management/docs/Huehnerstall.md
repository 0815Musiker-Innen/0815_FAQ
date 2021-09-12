# Hühnerstall

## Besonderheiten

!!! important "IP Adresse:"
    192.168.2.13

- Es gibt eine [analoge Stagebox](../devices/#analoge-stagebox) und Kabelpeitschen
- Ein [Mehrfachkopfhörerverstärker](/devices/#kopfhorervestarker) ist im Einsatz

## Verkabelung

### [XR18](/devices/#XR18)

#### XR18_Input

|             |   1   |   2   |   3   |   4   |   5   |   6   |   7   |   8   |    9     |  10   |  11   |    12     |    13     |    14    |    15    |  16   |  17   |  18   |
| :---------: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :------: | :---: | :---: | :-------: | :-------: | :------: | :------: | :---: | :---: | :---: |
| **Stecker** | Kick  | Snare | Tom 1 | Tom 2 | Tom 3 | HiHat | OH L  | OH R  | Drums DI |       | SBA 1 |   SBA 2   |   SBA 3   |  Voc 1   |  SBA 5   | SBA 6 |       |       |
|  **Ziel**   | Kick  | Snare | Tom 1 | Tom 2 | Tom 3 | HiHat | OH L  | OH R  | Drums DI |       | Bass  | Gitarre 1 | Gitarre 2 | Vocals 1 | Vocals 2 | Bonus |       |       |

#### XR18_Output

|             |   1   |                       2                       |                      3                      |                      4                      |   5   |     6     |                     Main L                      |                      Main R                       |
| :---------: | :---: | :-------------------------------------------: | :-----------------------------------------: | :-----------------------------------------: | :---: | :-------: | :---------------------------------------------: | :-----------------------------------------------: |
| **Stecker** | Drums | <span style="color:#ffc800">KP1 Orange</span> | <span style="color:#0008ff">KP1 Blau</span> | <span style="color:#f6ff00">KP1 Gelb</span> | Voc 1 | KP1 Clear | <span style="color:#33FF00">KP1 Hellgrün</span> | <span style="color:#003300">KP2 Dunkelgrün</span> |
|  **Ziel**   | Drums |                     Bass                      |                    Git 1                    |                    Git 2                    | Voc 1 |   Voc 2   |                      FOH L                      |                       FOH R                       |

### [Kopfhörerverstärker](/devices/#kopfhorervestarker)

Der [Kopfhörerverstärker](/devices/#kopfhorervestarker) hat vier Eingänge die beliebig auf sechs Ausgänge geroutet werden können. Siehe Bild

#### HA_Input

| **Klinkenbuchse** |                       1 L                       |                        1 R                        |                     2 L                     |  2 R  |    3 L    |  3 R  |  4 L  |  4 R  |
| :---------------: | :---------------------------------------------: | :-----------------------------------------------: | :-----------------------------------------: | :---: | :-------: | :---: | :---: | :---: |
|    **Klinke**     | <span style="color:#33FF00">KP2 Hellgrün</span> | <span style="color:#003300">KP2 Dunkelgrün</span> | <span style="color:#f6ff00">KP2 Gelb</span> |       | KP2 Clear |       |       |       |
|     **Ziel**      |                      FOH L                      |                       FOH R                       |                    Git 2                    |       |   Voc 2   |       |       |       |

#### HA_Output

Die Wahl der [Buchse](/devices/#buchse) ist egal, mit der Wahl des [Channel](/devices/#channel) kann eine Quelle ausgewählt werden

| **Channel** |   1   |   2   |   3   |   4   |
| :---------: | :---: | :---: | :---: | :---: |
|  **Ziel**   |  FOH  | Git 2 | Voc 2 |       |

### [SBA, analoge 6 Wege Stagebox](/devices/#analoge-stagebox)

> Die Stagebox wird genutzt um Inputs an das XR18 weiterzureichen

#### SBA_Input

XLR Female Stecker

|                 |    1    |     2     |     3     |   4   |    5     |    6    |
| :-------------: | :-----: | :-------: | :-------: | :---: | :------: | :-----: |
| **XLR_Stecker** | XR18 11 |  XR18 12  |  XR18 13  |       | XR18 15  | XR18 16 |
|    **Ziel**     |  Bass   | Gitarre 1 | Gitarre 2 |       | Vocals 2 |  Bonus  |

#### SBA_Output

XLR Male Buchse

|                |   1   |     2     |     3     |   4   |    5     |   6   |
| :------------: | :---: | :-------: | :-------: | :---: | :------: | :---: |
| **XLR_Buchse** | Bass  | Gitarre 1 | Gitarre 2 |       | Vocals 2 | Bonus |
|    **Ziel**    | Bass  | Gitarre 1 | Gitarre 2 |       | Vocals 2 | Bonus |

### [KP1 XLR -> XLR Kabelpeitsche](/devices/#kabelpeitsche-xlr-xlr)

#### KP1_Input

XLR Female

|                | <span style="color:#33FF00">KP1 Hellgrün</span> | <span style="color:#003300">KP2 Dunkelgrün</span> | <span style="color:#f6ff00">KP1 Gelb</span> | KP1 Clear | <span style="color:#ffc800">KP1 Orange</span> | <span style="color:#0008ff">KP1 Blau</span> |   7   |   8   |
| :------------: | :---------------------------------------------: | :-----------------------------------------------: | :-----------------------------------------: | :-------: | :-------------------------------------------: | :-----------------------------------------: | :---: | :---: |
| **XLR_Buchse** |                   XR18 Main L                   |                    XR18 Main R                    |                   XR18 4                    |  XR18 6   |                    XR18 2                     |                   XR18 3                    |       |       |
|    **Ziel**    |                      FOH L                      |                       FOL R                       |                    Git 2                    |   Voc 2   |                     Bass                      |                    Git 1                    |       |       |

#### KP1_Output

XLR Male

|                 | <span style="color:#33FF00">KP1 Hellgrün</span> | <span style="color:#003300">KP2 Dunkelgrün</span> | <span style="color:#f6ff00">KP1 Gelb</span> | KP1 Clear | <span style="color:#ffc800">KP1 Orange</span> | <span style="color:#0008ff">KP1 Blau</span> |   7   |   8   |
| :-------------: | :---------------------------------------------: | :-----------------------------------------------: | :-----------------------------------------: | :-------: | :-------------------------------------------: | :-----------------------------------------: | :---: | :---: |
| **XLR_Stecker** | <span style="color:#33FF00">KP2 Hellgrün</span> | <span style="color:#003300">KP2 Dunkelgrün</span> | <span style="color:#f6ff00">KP2 Gelb</span> | KP2 Clear |                     Bass                      |                    Git 1                    |       |       |
|    **Ziel**     |                      FOH L                      |                       FOL R                       |                    Git 2                    |   Voc 2   |                     Bass                      |                    Git 1                    |       |       |

### [KP2 XLR -> Klinke Kabelpeitsche](/devices/#kabelpeitsche-xlr-trsklinke)

#### KP2_Input

XLR Female

|                | <span style="color:#33FF00">KP2 Hellgrün</span> | <span style="color:#003300">KP2 Dunkelgrün</span> | <span style="color:#f6ff00">KP2 Gelb</span> | KP2 Clear |
| :------------: | :---------------------------------------------: | :-----------------------------------------------: | :-----------------------------------------: | :-------: |
| **XLR_Buchse** | <span style="color:#33FF00">KP1 Hellgrün</span> | <span style="color:#003300">KP2 Dunkelgrün</span> | <span style="color:#f6ff00">KP1 Gelb</span> | KP1 Clear |
|    **Ziel**    |                      FOH L                      |                       FOL R                       |                    Git 2                    |   Voc 2   |

#### KP2_Output

Klinke Male TRS symmetrisch

|                    | <span style="color:#33FF00">KP2 Hellgrün</span> | <span style="color:#003300">KP2 Dunkelgrün</span> | <span style="color:#f6ff00">KP2 Gelb</span> | KP2 Clear |
| :----------------: | :---------------------------------------------: | :-----------------------------------------------: | :-----------------------------------------: | :-------: |
| **Klinkenstecker** |                      HA 1L                      |                       HA 1R                       |                    HA 2L                    |   HA 3L   |
|      **Ziel**      |                     FOH  L                      |                      FOH  R                       |                    Git 2                    |   Voc 2   |

