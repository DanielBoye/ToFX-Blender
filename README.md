# Sofa i Blender

Jeg valgte å lage sofaen vi har i stuen. Her er link til selve sofaen på Bohus:
https://www.bohus.no/stue/sofa/hjoernesofa/vilmers-nordic-hjoernesofa-1

Det var vanskelig å komme i gang med å lære alle keybindingene. Man måtte bare lære de, og alt
ble så mye lettere når alt bare satt. Etter den andre og tredje timen ble Blender veldig kjekt, siden
jeg følte at jeg faktisk fikk til noe, og sluttresultatet ble så bra.  

Selve render bildet er litt rart, siden teksturene rundt selve sofa kantene ble litt rare, og hakkete. Jeg vet ikke helt hvordan jeg skal fikse dem.

Utfordringer jeg møtte på var hvordan jeg skulle rendere bildet. Jeg ville rendere bildet i en
oppløsning på 3840p x 2160p (4k), og jeg ville rendere bildet med GPU-en min jeg har hjemme i
pc-en min, som det går litt raskere. Jeg løste utfordringen med å gå gjennom noen stackexchange
poster med andre som hadde samme problem som meg. For teksturer brukte jeg en plug-in som
heter blenderkit. Flott opensource prosjekt som ligger ute på github. https://github.com/BlenderKit/blenderkit.

-----
Slik ble sluttproduktet:

<br>

![ferdig](https://user-images.githubusercontent.com/83395536/194725861-308f3a6b-ce1e-4c1d-ae1a-167e04ded7a3.png)

-----

Slik ser det ut inne i Blender programmet når jeg var ferdig. Jeg er veldig fornøyd med hvor realistisk sofaen ble. 

<br>

![ferdig2](https://user-images.githubusercontent.com/83395536/194725864-3f859d8e-8c6f-436f-9c91-9762ce17d47b.png)

-----

## Ifra 2x2 bokser til Bohus Sofa

Her modellerer jeg hjørnet på sofaen. For å lage boksene legger jeg bare inn en
cube, og modellerer den ned til riktig størrelse.

<br>

![logg2](https://user-images.githubusercontent.com/83395536/194725909-d242426c-f1b7-457d-a90f-fdcac45182db.png)

Den mest effektive måten å gjør dette på er å duplisere puten jeg allerede har laget
(SHIFT A, G X for å dra den nye puten langs X aksen).

<br>

![logg1](https://user-images.githubusercontent.com/83395536/194725907-999910ff-b045-4e4e-888e-c3954be6ce83.png)

-----

Jeg har falt helt i elsk med å trykke på aksene eller bare holde inne «Alt» og dra
musen til å få kameravinkelen ovenfra, som jeg kan legge inn putene rett ved siden
av hverandre.

<br>

![logg3](https://user-images.githubusercontent.com/83395536/194725910-0a298a39-2de3-42be-9f28-1e14d2f160b9.png)

<br>

![logg4](https://user-images.githubusercontent.com/83395536/194725911-507d3055-90f0-4fb2-8076-bc6a68e925b5.png)

-----

Her er jeg ferdig med å legge inn alle putene. De er laget med å legge inn «Bevel»
og «Subdivision» Modifiers. Segmentene la jeg på 2 og to, og på Bevel brukte jeg
rundt 0.03M og 3 segments for å få en litt glatt overflate.

<br>

![logg11](https://user-images.githubusercontent.com/83395536/194725920-72e58a6e-bbfe-458d-affa-b204af9edab1.png)

<br>

Så bruker jeg Physics Cloth for å få putenene til å blåse seg opp. Jeg setter
«Pressure» til 5 for å skape et indre trykk, og «Gravity» til 0 som den ikke faller på
bakken. Etter alt er satt opp lagrer jeg endringene med å trykke på ^ og «Apply» i
menyen. Der er slik jeg får at putene stikker litt ut, og ser ut som sofaputer

<br>

![logg12](https://user-images.githubusercontent.com/83395536/194725921-32a420c1-b49b-4645-ad6d-a53e1f4b1d7f.png)

-----

Når jeg jobber på laptopen setter jeg render engine
på «Cycles» for at når jeg går i render mode, at
figuren oppdaterer seg selv i sanntid. 

<br>

![logg13](https://user-images.githubusercontent.com/83395536/194725922-7b30cbb7-3f91-4cd1-ad58-3a8f709e5fdb.png)

-----

Her ble putene litt rare osv med å bruke brush mode, så jeg endte opp med å endre
dem, samt den store puten ytterst til høyre, siden den fikk så mange rynker på seg. 

<br>

![logg15](https://user-images.githubusercontent.com/83395536/194725925-20c8f6f1-e8ef-4b41-b265-4b964366488e.png)

-----

For å få til litt fint lys la jeg til en Hue Saturation Value som binder teksturen og
objektet. Jeg bare lekte litt rundt med verdiene til jeg fant noe som lignet fargen på
sofaen hjemme.

<br>

![logg16](https://user-images.githubusercontent.com/83395536/194725926-d711ef2d-8b58-4b91-9173-43a9fc84f255.png)

-----

## Ekstra bilder av prosjektet

<br>

![blender1]https://user-images.githubusercontent.com/83395536/194725946-0a590f43-9b8a-4afc-9732-3b103a7e6960.png)


![blender2](https://user-images.githubusercontent.com/83395536/194725939-ba092542-f0bc-46b7-8096-04c631d2755e.png)

![blender3](https://user-images.githubusercontent.com/83395536/194725943-5d7f7c96-75cb-4186-816c-b5d082b4ef2d.png)


![blender4](https://user-images.githubusercontent.com/83395536/194725952-f561aa38-7639-42bf-a9eb-836bb1d4ed1d.png)


![blender5](https://user-images.githubusercontent.com/83395536/194725951-d824b8e6-e364-42bb-8a4f-a3d59ad9a8f8.png)

![blender6](https://user-images.githubusercontent.com/83395536/194725953-8a1b5089-6b2b-4be3-9adf-f49f1b47b664.png)

![blender7](https://user-images.githubusercontent.com/83395536/194725950-85046dfb-18f3-4fcc-89a4-9bdde94e0d2e.png)

![blender8](https://user-images.githubusercontent.com/83395536/194725956-2b7456f8-4cf1-444b-bc7f-70619c92c2ef.png)

![blender9](https://user-images.githubusercontent.com/83395536/194725955-e8386d10-0dde-4086-8917-fbbd4e1c215f.png)

![blender10](https://user-images.githubusercontent.com/83395536/194725947-69e4aaac-0afb-4248-a6e3-b7ceed4d9bba.png)

![blender11](https://user-images.githubusercontent.com/83395536/194725949-fdaea323-3b28-4ca3-b65d-b0267ad04660.png)

![blender12](https://user-images.githubusercontent.com/83395536/194725958-63b07c12-6cd5-4970-8d3d-95e64c02d053.png)

![blender13](https://user-images.githubusercontent.com/83395536/194725944-9fb7e920-6bf4-4450-9dec-6cb77f581d20.png)

