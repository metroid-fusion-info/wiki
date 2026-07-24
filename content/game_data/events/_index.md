---
title: List of Events

---

A list of all event states in the game, with descriptions how they're seen in the debug menu.  
The decompiled code can be found here: https://github.com/metroidret/mf/blob/main/include/constants/event.h

| Dec | Hex | Text          | Text             | Translation                       | Description                                             |
|-----|-----|---------------|------------------|-----------------------------------|---------------------------------------------------------|
| 000 | 00  | TOHOKANKO     | トクベツホカンコヘ ムカエ    | go to special vault               | Start of game                                           |
| 001 | 01  | TOHOKANKO2    | トクベツホカンコノ チョウサ   | investigation of special vault    | Navigation room before quarantine bay                   |
| 002 | 02  | HOKANKO       | ナビヘ モドレ          | return to navigation              | Quarantine bay hornoad dead                             |
| 003 | 03  | TOMARUKARA    | キョダイセイブツヲ タオセ    | defeat huge creature              | Navigation room after quarantine bay [Level 0 unlocked] |
| 004 | 04  | TOMISSILE     | ミサイルヲ ニュウシュセヨ    | obtain missiles                   | Navigation room before elevator                         |
| 005 | 05  | DATA3         | トナリノ ヘヤヘ         | to next room                      | Skipped by not talking to computer                      |
| 006 | 06  | TODATA        | データルームニ ハイル      | enter data room                   | Entered missile data room                               |
| 007 | 07  | MISSILE       | データルームデ ミサイルヲ    | get missiles in data room         | Missile data downloaded                                 |
| 008 | 08  | DOWNENE       | デンゲンガ オチタ        | power lost                        | Entered navigation room [power outage]                  |
| 009 | 09  | TOMARUKARA2   | キョダイセイブツヲ タオセ2   | defeat huge creature 2            | Navigation room after missiles                          |
| 010 | 0A  | DOWNBOSS1     | ナビヘ ムカエ          | go to navigation                  | Morph ball ability recovered                            |
| 011 | 0B  | TOKUTYOU      | SR388ヘ ムカエ       | go to SR388                       | Navigation room after morph ball                        |
| 012 | 0C  | ELESTART      | エレデモ SR388ヘムカエ   | elevator demo, go to SR388        | Entered elevator room                                   |
| 013 | 0D  | ELEEND        | デモエンド SR388ヘ     | demo end, to SR388                | SA-X cutscene ends                                      |
| 014 | 0E  | TOKUTYOU2     | クウチョウメロンヲ タオセ    | defeat air conditioning melon     | Navigation room entering SRX                            |
| 015 | 0F  | POWERB        | コアXゴ ノコリハカイセヨ    | after core-x destroy remaining    | Charge beam ability recovered                           |
| 016 | 10  | KUTYOU        | ハカイゴ ナビヘ ムカエ     | after destroying go to navigation | All stabilizers online                                  |
| 017 | 11  | TOBOM         | ボムヲ ニュウシュセヨ      | obtain bombs                      | Navigation room leaving SRX                             |
| 018 | 12  | TOLV1KEY      | レベル1ヲ カイジョセヨ     | unlock level 1                    | Navigation room entering TRO                            |
| 019 | 13  | LV1KEY        | レベル1カイジョ         | level 1 unlocked                  | Security level 1 unlocked                               |
| 020 | 14  | TOBOM2        | カイジョゴ ボムデータヘ     | after unlocked, to bomb data      | Skipped by not talking to computer                      |
| 021 | 15  | DATATRO       | データルームニ ハイル      | enter data room                   | Entered bomb data room                                  |
| 022 | 16  | BOM           | ネッタイカラ ダッシュツセヨ   | escape from tropics               | Bomb data downloaded                                    |
| 023 | 17  | BOMQUAKE      | ボムゴ ジシン          | earthquake after bombs            | SA-X quake                                              |
| 024 | 18  | BOMQUAKE2     | ジシン シュウリョウ       | end of earthquake                 | Left SA-X quake room                                    |
| 025 | 19  | DOWNBOSS2     | ボスノノチ ダッシュツ      | escape after boss                 | Hi-jump ability recovered                               |
| 026 | 1A  | TROSAX        | SAXカラ ニゲル        | escape from SA-X                  | Escaped TRO SA-X                                        |
| 027 | 1B  | TOWATER       | スイチュウセクションヘ      | to underwater section             | Navigation room leaving TRO                             |
| 028 | 1C  | WATER         | スイイヲ サゲロ         | lower water level                 | Navigation room entering AQA                            |
| 029 | 1D  | DOWNBOSS3     | ボスノノチ スイイヲサゲロ    | lower water level after boss      | Speed booster power regained                            |
| 030 | 1E  | TOWATSWITCH   | ダッシュノ セツメイ       | dash explanation                  | Skipped by not talking to computer ("Empty")            |
| 031 | 1F  | WATSWTROOM    | スイイヘンコウヘヤ        | change water level room           | Entered pump control unit                               |
| 032 | 20  | WATSWITCH     | スイイヘンコウ          | change water level                | Water level lowered                                     |
| 033 | 21  | TOPWMISSILE   | パワーミサイルヲ テニイレロ   | obtain power missiles             | Navigation room leaving AQA                             |
| 034 | 22  | TOLV2KEY      | レベル2ヲ カイジョセヨ     | unlock level 2                    | Navigation room entering PYR                            |
| 035 | 23  | LV2KEY        | レベル2カイジョ         | level 2 unlocked                  | Security level 2 unlocked                               |
| 036 | 24  | TOPWMISSILE2  | Pミサイルヘ カイジョゴ     | to power missiles after unlock    | Skipped by not talking to computer                      |
| 037 | 25  | DATABUR       | データルームニ ハイル      | enter data room                   | Entered super missile data room                         |
| 038 | 26  | PWMISSILE     | パワーミサイル カンリョウ    | completed power missiles          | Super missile data downloaded                           |
| 039 | 27  | DOTADOTA      | オートデモゴニ モドレ      | return after auto demo            | Triggered BOX rumble                                    |
| 040 | 28  | DOWNBOSSA1    | ボスA タオス          | defeated boss A                   | BOX defeated                                            |
| 041 | 29  | TOENEGAS      | アンコクセクションヘ ムカエ   | go to dark section                | Navigation room leaving PYR                             |
| 042 | 2A  | ADAMRENPO     | アダム レンポウ         | Adam and federation               | Left navigation room                                    |
| 043 | 2B  | ADAMRENPODEMO | アダムレンポウチュ        | during Adam and federation        | Secret conversation                                     |
| 044 | 2C  | ADAMRENPOEND  | アダムレンポエンド        | Adam and federation end           | Secret conversation over                                |
| 045 | 2D  | TOANKOKU      | アンコク イガイデ コウシン   | except dark update                | Skipped by using NOC navigation room                    |
| 046 | 2E  | DARNAVI       | アンコクナビニ ハイル      | enter dark navigation             | Entered NOC navigation room                             |
| 047 | 2F  | TOENEGAS2     | ボス4ヲ タオセ         | defeat boss 4                     | Navigation room entering NOC                            |
| 048 | 30  | DARSAX        | SAXニ アウ          | encounter SA-X                    | NOC SA-X encounter                                      |
| 049 | 31  | DARSAXESC     | SAXカラ ニゲキル       | escape from SA-X                  | Escaped NOC SA-X                                        |
| 050 | 32  | BARILOSS      | バリア スワレル         | varia absorbed                    | NOC data room destroyed                                 |
| 051 | 33  | DOWNBOSS4     | ナビヘ モドレ          | return to navigation              | Varia suit effect recovered                             |
| 052 | 34  | CXESCAPE      | コールドX ニゲル        | cold X flee                       | Reached top of room after Mega-X [Blue X flee]          |
| 053 | 35  | TOFREEZEM     | ゴッカンセクションヘ ムカエ   | go to cold section                | Navigation room leaving NOC                             |
| 054 | 36  | TOLV3KEY      | レベル3ヲ カイジョセヨ     | unlock level 3                    | Navigation room entering ARC                            |
| 055 | 37  | LV3KEY        | レベル3カイジョ         | level 3 unlocked                  | Security Level 3 unlocked                               |
| 056 | 38  | TOFREEZEM2    | アイスミサイルヲ ニュウシュセヨ | obtain ice missiles               | Skipped by not talking to computer                      |
| 057 | 39  | DATAFRI       | データルームニ ハイル      | enter data room                   | Entered ice missile data room                           |
| 058 | 3A  | FREEZEM       | アイスミサイル カンリョウ    | completed ice missiles            | Ice effect added to missiles                            |
| 059 | 3B  | TOENEBALL     | ネツボウソウ カイシ       | overheating start                 | Navigation room leaving ARC                             |
| 060 | 3C  | WIDEB         | コンソールヲ オセ        | use console                       | Wide beam ability recovered                             |
| 061 | 3D  | ENEBALL       | ナビヘ モドレ          | return to navigation              | Cooling unit operational                                |
| 062 | 3E  | TOETEKON      | キョジュウクヘ ムカエ      | go to residential area            | Navigation room leaving PYR                             |
| 063 | 3F  | ETEKON        | ナビヘ キュウシュツゴ      | to navigation after rescue        | Animals released                                        |
| 064 | 40  | TOPBOM        | パワーボムヲ ニュウシュセヨ   | obtain power bombs                | Navigation room after animals                           |
| 065 | 41  | TOPBOM2       | ゴッカン コウシン        | cold update                       | Navigation room entering ARC                            |
| 066 | 42  | PBOM          | パワーボム カンリョウ      | completed ice missiles            | Power bomb data downloaded                              |
| 067 | 43  | FRISAX        | SAXニ デアウ         | encounter SA-X                    | ARC SA-X encounter                                      |
| 068 | 44  | FRISAXESC     | SAXカラ ニゲキル       | escape from SA-X                  | Escaped ARC SA-X                                        |
| 069 | 45  | TOSTARSHIP    | スペースシップヘ ムカエ     | to spaceship                      | Navigation room leaving ARC                             |
| 070 | 46  | ENGDOWN       | スペースシップヘムカエ      | to spaceship                      | Power outage                                            |
| 071 | 47  | TODOURYOKU    | ホジョ デンゲンヲ イレロ    | turn on auxiliary power           | Entered ship                                            |
| 072 | 48  | BOSS5ROOM     | ボス ヘヤ            | boss room                         | Entered Yakuza's room                                   |
| 073 | 49  | DOWNBOSS5     | ホジョデンゲンヲイレロ      | turn on auxiliary power           | Space jump ability recovered                            |
| 074 | 4A  | SUBENG        | ホジョデンゲン カンリョウ    | completed auxiliary power         | Auxiliary power engaged                                 |
| 075 | 4B  | TOPLASMAB     | ネッタイセクションヘ ムカエ   | to tropical section               | Navigation room after Yakuza                            |
| 076 | 4C  | TROSAX2       | SAXニ デアウ         | encounter SA-X                    | Engaged TRO SA-X                                        |
| 077 | 4D  | TROSAX2ESC    | SAXカラ ニゲキル       | escape from SA-X                  | Escaped TRO SA-X                                        |
| 078 | 4E  | PLASMAB       | ドウリョク カイフク ナビヘ   | power restored, to navigation     | Plasma beam ability recovered                           |
| 079 | 4F  | TOGOKAN       | ゴッカン ボスヲ タオセ     | defeat cold boss                  | Navigation room leaving TRO                             |
| 080 | 50  | TOGOKAN2      | ゴッカンナビデ コウシン     | cold navigation update            | Navigation room entering ARC                            |
| 081 | 51  | DOWNBOSS6     | ボス タオス ナビヘ       | defeated boss, to navigation      | Gravity suit effect recovered                           |
| 082 | 52  | TOLV4KEY      | レベル4ヲ カイジョセヨ     | unlock level 4                    | Entered level 4 security room                           |
| 083 | 53  | LV4KEY        | レベル4カイジョ         | level 4 unlocked                  | Security level 4 unlocked                               |
| 084 | 54  | TOKAKUSAN2    | カクサンヲ ニュウシュセヨ2   | obtain diffusion 2                | Secret message                                          |
| 085 | 55  | DATAWAT       | データルームニ ハイル      | enter data room                   | Entered diffusion missile data room                     |
| 086 | 56  | KAKUSAN       | カクサン ニュウシュ ナビヘ   | diffusion obtained, to navigation | Diffusion missile data downloaded                       |
| 087 | 57  | TOANKOKUOKU   | アンコク カクシヲ サガセ    | find dark hidden                  | Navigation room leaving AQA                             |
| 088 | 58  | TOSHUTTER     | アンコクナビデ コウシン     | dark navigation update            | Navigation room entering NOC                            |
| 089 | 59  | SHUTTER       | アンコクノ オクヘ        | to dark interior                  | Restricted Zone warning                                 |
| 090 | 5A  | SHUTTER2      | シャッター ジシン        | shutter earthquake                | Triggered BOX 2 rumble                                  |
| 091 | 5B  | WAVEB         | アンコクノ オクヘ2       | to dark interior 2                | Wave beam ability recovered                             |
| 092 | 5C  | TOGOKUHIKEN   | ゴクヒ デモ           | secrecy demo                      | Restricted Laboratory explosion                         |
| 093 | 5D  | RANSHA        | ランシャ アンド タイマー    | random shooting and timer         | 60 seconds to detachment                                |
| 094 | 5E  | TOKIRIHANA    | キリハナシ            | detachment                        | Escaped Restricted Laboratory                           |
| 095 | 5F  | KIRIHANA      | カサイゴ コウシン        | after fire update                 | Navigation room after Restricted Laboratory             |
| 096 | 60  | DOWNBOSS7     | ボス7 タオシ ダッシュツ    | defeated boss 7, escape           | Screw attack ability regained                           |
| 097 | 61  | TOOPE         | シンジツ             | truth                             | Navigation room leaving SRX                             |
| 098 | 62  | TOOPEMONO     | モノローグ            | monologue                         | End of first conversation                               |
| 099 | 63  | TOOPE2        | キドウヲ カエロ         | change orbit                      | Second conversation                                     |
| 100 | 64  | TOOPE3        | アダム サイド コウシン     | adam second update                | Skipped by not talking to computer                      |
| 101 | 65  | INTOOPE       | オペレーションニ ハイル     | enter operation                   | Entered operations deck                                 |
| 102 | 66  | DOWNSAX       | SAXヲ タオス         | defeated SA-X                     | SA-X defeated                                           |
| 103 | 67  | KIDOUKAE      | キドウヲ カエル         | orbit changed                     | Orbit changed                                           |
| 104 | 68  | ESCAPE        | キドウヘンコウゴ コウシン    | update after orbit change         | Skipped by not talking to computer [unused]             |
| 105 | 69  | OMEGA         | メトロイド ト セントウ     | fight with metroid                | Entered ship room                                       |
| 106 | 6A  | DOWNSAX2      | オメガ SAXヲ タオス     | omega killed SA-X                 | SA-X killed by Omega Metroid                            |
| 107 | 6B  | ICEBEAM       | アイスビーム カクトク      | ice beam aquired                  | Ice beam ability recovered                              |
| 108 | 6C  | DOWNOMEGA     | メトロイド ヲ タオス      | defeated Metroid                  | Omega Metroid defeated                                  |
| 109 | 6D  | END           | エンド              | end                               | Escaped on ship                                         |
