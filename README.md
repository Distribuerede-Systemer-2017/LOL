# LOL

Kravspecifikation

Server

S1: Serveren skal kunne validere login baseret på et hashet password.

S2: Serveren skal kunne oprette en bruger. 

S3: Serveren skal udstille et API, som gør det nemt at udarbejde klienter der kan trække på serverens funktionalitet. Som skal dække følgende funktioner:
- a.	En bruger skal kunne logge ind og ud.
- b.	En bruger skal kunne oprette sig som bruger.
- c.	En bruger skal kunne hente informationer af vare.
- d.	En bruger skal kunne sende en forespørgsel på en vare og modtage et odre ID.
- e.	En bruger skal kunne finde information om sine tidligere køb.

S4: Serveren skal udstille et interface som lister alle varer – 1. Drikkevarer og  2. Mad.

S5: Serveren skal udstille et interface som lister alle brugerens tidligere køb.

S6: Serveren skal udstille et interface hvori der udstedes et ordre ID til klienten(kunden)
				
Klienten

K1: Klienten skal udstille en log ind side som gør det muligt for brugeren at logge ind.  

K2: Klienten skal kunne oprette en bruger.

K3: Klienten skal kunne se en menu som indeholder følgende:
-	Drikkevarer: Juice/Smoothie
-	Mad: Bagel/Baguette
-	Historik: Tidligere køb
-	Kurv
-	Log ud

K4: Klienten skal kunne se items tilføjet til sin kurv. 

K5: Klienten skal kunne bestille items i sin kurv.

K6: Klienten skal kunne se sine tidligere køb.

K7: Klienten skal kunne modtage et ordre ID når der blivet lavet en forespørgsel.
