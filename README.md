## Miljö
- **Python:** 3.13.7

## Kravkort - Elin (Legal/Compliance)
Elin ansvarar för klagomål och behöver kunna förklara och försvara hur plattformen fattar beslut. Hon accepterar att systemet inte är perfekt, men varje beslut måste vara begripligt, konsekvent och möjligt att motivera på enkel svenska. Oskyldiga användare ska inte drabbas utan tydlig och spårbar förklaring.

## Strategi
Vi bygger en lösning där varje beslut går att förstå och förklara. När något flaggas ska det vara tydligt vilka signaler som låg bakom beslutet. Systemet sparar också information så att man i efterhand kan se varför något flaggades.

Vi presenterar de viktigaste signalerna och förklarar hur de används för att fatta beslut. Vi beskriver också vad som händer efter en flaggning, till exempel att ärendet skickas vidare till manuell granskning eller leder till en varning. Genom tydliga regler för hur signalerna används strävar vi efter att systemet ska bete sig konsekvent i liknande situationer. På så sätt blir det möjligt att granska beslut, förstå varför de togs och förklara dem om någon ifrågasätter utfallet.

## Ansvarsområden
Data & EDA - **Magdalena**  
Pipeline & preprocessing - **Axel**  
Modelljämförelse - **Biljana**  
Optimering - **Simon**  
Threshold/prioritering - **Henri**  
Pitch & risker - **Alla**

```bash
# klona projektet
git clone https://github.com/MagdalenaPersson/Marketplace_Safety.git

cd MARKETPLACE_SAFETY

# Skapa och aktivera virtuell miljö
python -m venv . venv
# Windows PowerShell
.venv\Scripts\Activate

# macOs\ Linux
# source .venv/bin/activate

# installera beroenden
python -m pip install -r requirement.txt
```
