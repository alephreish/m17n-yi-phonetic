# yi-phonetic

IBus m17n phonetic Yiddish layout for English keyboards. The layout targets all Yiddish orthographies, including Hareidish, Klal Takones and YIVO, as well as Hebrew with or without niqqud.

## Layout


| Q | W | E | R | T | Y | U | I | O | P |
|---|---|---|---|---|---|---|---|---|---|
| ק | װ | ע | ר | ת | א | ו | י | אָ | פּ |
| כּ | ױ |  ֶ |  ֿ | תּ |  ְ | וּ | יִ |  ָ | פֿ |

| A | S | D | F | G | H | J | K | K |
|---|---|---|---|---|---|---|---|---|
| אַ | ש | ד | פ | ג | ה | ײ | כ | ל |
| ַ  | שׁ |  ּ | ף |  ִ | ח | ײַ | ך |  ֫|

| Z | X | C | V | B | N | M |
|---|---|---|---|---|---|---|
|   ז | ס | צ | ט | ב | נ | מ |
|   ₪ | שׂ | ץ |  ֻ | בֿ | ן | ם |

| Y+E | Y+O | Y+A | O+O | E+E | L+L | ` | `` | - | -- |
|-----|-----|-----|-----|-----|-----|---|----|---|----|
|  ֱ |   ֳ |   ֲ |   ֹ |   ֵ |   ֽ | ׳ | ״ | ־ | - |

## Installation

### Ubuntu 16.04

* Install ibus and m17n with `apt-get install ibus-m17n`
* Copy yi-phonetic.mim to `/usr/share/m17n`
* Restart ibus with `ibus restart`
* Go to Text Entry Settings and add `Yiddish (phonetic (m17n)) (IBus)`
