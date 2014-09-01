polygons
========
(07:14:59 PM) Kateřina Zemene: Ahoj, potřebovala bych na jednu performanci naprogramovat živě generovanou grafiku, reagující na hudbu... uměl bys to nebbo nevíš o někom? Skladatel kterej to vymyslel o tom píše:"
Geneze zvuku v části "mnohoúhelníky" probíhá v programu MAX/MSP. Jsem v programu úplný nováček, ale jsem si jistý, že umí komunikovat s dalšími simultánně běžícími programy přes midi nebo jiným způsobem.

Teď k těm mnohoúhelníkům -
Do MAXu zadávám:

- počet úhlů/stran pravidelného N-úhelníku (N=3 -> trojúhelník, N=4-> čtverec, N=6 -> šestiúhelník, N=256 -> 256úhelník atd...)
- počet vepsaných pravidelných N-úhelníků (mám pevně nastavené na 1024)

Během performance měním číslo N z 1024 do nuly (varianta do čtyřky). (projdu všechny celočíselné hodnoty mezi těmito dvěma čísly) a obsahy obrazců přepočítávám na zvuk.

V příloze posílám, jak proces vypadá graficky (je to bohužel nepřesně a navíc zaokrouhleno na několik málo kroků, ale pro ilustraci stačí).
Na obrázku č.1 je 1024 vepsaných 1024-úhelníků - vypadá to jako prázdná kružnice. Čím míň úhlů má N-úhelník, tím blíže do středu se černota dostává. Někde kolem N=50 až 100 lze už rozlišovat jednotlivé vepsané N-úhelníky a na posledním obrázku jsou už úplně jasně rozeznatelné vepsané čtverce."

(07:15:21 PM) Kateřina Zemene: je to v říjnu v kostele na bílý hoře
(07:16:00 PM) Kateřina Zemene: a asi na to máme i nějakej rozpočet ale miliony to neudou
(07:26:21 PM) Kateřina Zemene: Sraz v neděli ve dvě na bílé hoře před kostelíkem
