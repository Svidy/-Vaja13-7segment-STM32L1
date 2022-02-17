# -Vaja13-7segment-STM32L1

Vprašanja:

V Pinout & Configuraton pogledu glede na vašo razvojno ploščico postavite 7 prvih prostih pinov skupine A na GPIO_Output.
Pine označite (label) s črkami segmenta: a, b, c, d, e, f in g.
Zapišite izbrane (konfigurirane) pine: Segment a: __PA1__ Segment b: __PA2__ Segment e: __PA5__ Segment c: __PA3__ Segment f: __PA6__Segment d: __PA4__ Segment g: __PA7__

7-segmentni display je lahko v izvedbi skupne anode ali skupne katode. Vaš prikazovalnik testirate tako, da ga zvežete po spodnji (levi ali desni) shemi in preizkusite,
katera polariteta je ustrezna (rdeča 5V, modra GND): Vaš prikazovalnik je s skupno __katodo__.

Kaj dela ukaz GPIOA -> ODR ?
Nastavi odrodr na 16 bitni register

Opazujte delovanje 7-segmentega prikazovalnika. Kaj se zgodi, ko pritisnemo črno tipko na STM32L1? Resetera se in začne šteti od začetka

Komentar: 

Naloga se nama ni zdela tako težka, kot prejšnje naloge, ampak sva imela kar nekaj težav. Najprej sva imela težavo z Debug v programu, zaradi updajta.
Nekaj težav sva imela pri stiku z 7-segmentnim zaslonom. Na koncu nama je vse delovalo, kot mora.
