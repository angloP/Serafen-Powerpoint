﻿# Serafen-Powerpoint

## Prerequisites
Installera (Microsoft) Powershell om det inte är installerat.


## Install
Installera genom att köra "install"

Alla powerpoints ska ha ett konfigurerat bildspel med menyer, bilder på maten osv enligt nedan. (SlideShow)

(Gå under "Slide Show" tryck "Setup Slide show". Under "Advance Slides" välj "Using timings, if present".
Under "Show Options" välj "Loop Continuously until 'Esc'". 
Nu sätt timings på alla slides: Tryck "CTRL+a" för att markera alla slides, tryck "Animations" och under "Advance Slides"  
Välj "Automatically After": 00:10.) Nu kommer bildspelet loopa, och byta slide var 10 sekund.


----------------------

## Powerpoint Files
Lägg alla powerpoint-filer (menyer) under ...../Serafen-Powerpoint/powerpoint

Döp powerpoint-filerna efter dag. Exempelvis "2018-01-28.pptx" för den powerpointen som ska köras den 28 Januari 2018. (.pptx talar om att det är en powerpoint-fil, alltså döp bara powerpoint-filen till "2018-01-28").


Se till att varje dag har en powerpoint presentation, om inte programmet hittar presentationen kommer det att öppna presentationen "Default.pptx".
OBS TA INTE BORT Default.pptx (däremot kan den ändras efter behag)

## Run
Ha Powerpoint stängt. Kör "Inedal_Powerpoint_Menu".

När programmet startas kommer det öppna dagens powerpoint presentation.
Programmet tittar på datumet varje minut, och vid ett nytt datum stänger programmet föregående dags presentation och öppnar dagens.

Stäng av programmet genom att stänga "powershell fönstret".
