# Vattensimulering med partikelsystem i OpenGL

### Anna Fredriksson Häägg, David Eriksson
##### Linköpings Universitet, TSBK03, Teknik för avancerade datorspel

## Bygg & Kör

    cd WaterSimulation
    make
    ./master
## Syfte
Syftet med projektet är att implementera en vattensimulation för realtidsrendering med en partikelbaserad metod. OpenGl kommer användas för implementationen och störst fokus läggs på vattnets rörelse. I första hand kommer simuleringen köras på CPUn vilket ger en del begränsningar i hur många partiklar som kan användas men det ger även en mer intuitiv känsla för hur kollisionshanteringen mellan partiklarna görs. För att interagera och främja rörelse i vattnet kommer ett större sfärformat objekt manuellt kunna manövreras. 

Vidare ska partikelsystemet renderas med för att ge ett visuellt intryck av vatten och inte separata bollar. Dvs, enskilda partiklar ska inte renderas utan istället en sammansatt vattenmassa samt eventuella separata stänk. Genom att implementera reflektion och refraktion i vatten-shadern ska vattnet få den transparenta egenskap som ger det dess vattenliknande karaktär.
