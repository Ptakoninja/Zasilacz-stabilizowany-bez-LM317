# Zasilacz-stabilizowany-bez-wykorzystania-LM317
# Regulated power supply without using LM317.
Zasilacz został wykonany w programie Eagle.
Płytka została wykonan z możliwością wsadzenia jej do obudowy dlatego schemat końcowy może różnić się względem shcematu płytki
bezpiecznik jak i transformator znajdują się poza nią tak samo potencjometry
Głównym zamysłem było wykonanie zasilacza bez użycia LM317, założennie zostało spełnione.
kolejnym założeniem było sterowaniem napięcia w zakresie od 0 do 15 V oraz ograniczeniem prądowym od 0 do 2 A 

Przeiwdziane są dodtakowe wyjście na usprawnienie układu wentylaotrem lub woltomierzem oraz amperomierzem wymagającego dodatkowego zasilania

Rezystory R3(RV) oraz RA służą do ustawienia konkretnego napięcienia/natężenia
Schemat końcowy zasilacza wygląda następująco:

**ENG**
The power supply was designed in Eagle software. The PCB was designed to fit into a housing, so the final schematic may differ from the PCB schematic. The fuse and transformer are located outside the PCB. The main idea was to design a power supply without using LM317, and this assumption has been met. Another requirement was to control the voltage in the range of 0 to 15 V and limit the current from 0 to 2 A.

Additional outputs are provided for improving the system with a fan or adding a voltmeter and ammeter requiring extra power supply.

Resistors R3 (RV) and RA are used to set specific voltage/current values. The final schematic of the power supply looks as follows:

![image](https://github.com/Ptakoninja/Zasilacz-stabilizowany-bez-LM317/assets/164054955/8095e5de-0841-49d7-81fb-665919786744)

schemat wykorzystany do stowrzenia płytki PCB:

**ENG**
The schematic used to create the PCB board is as follows:

![image](https://github.com/Ptakoninja/Zasilacz-stabilizowany-bez-LM317/assets/164054955/44ce08ce-32f7-44fa-8efb-628d72433dcb)

Wygląd końcowy płytki z góry:

**ENG**
The final appearance of the PCB from the top:

![image](https://github.com/Ptakoninja/Zasilacz-stabilizowany-bez-LM317/assets/164054955/34817ba8-f4ef-425c-806d-ee9e7ff4a54f)

W przypadku symulacji 
Zasilacz po zmontowaniu działał zadawalająco prąd mieścił się w zakresie 0-1,7A a napięcie od 1,3 do 14,6 dobierając lepszej jakości rezystory można poprawić zakres na bardziej zbliżony do oczekiwanych.
W przypadku Symulacji należy oddzielnie przeprowadić dla stabilizaci  napięcia jak i natężenia bo inaczej trwa długo
dodatkowo w przypadku nateżenia trzeba dodać rezystor na wyjściu układu

**ENG**
In the case of simulation:
After assembly, the power supply worked satisfactorily, with the current ranging from 0 to 1.7A and the voltage from 1.3 to 14.6V. By selecting higher quality resistors, the range can be adjusted to be closer to the expected values.
For simulation purposes, it is advisable to conduct separate simulations for voltage stabilization and current limitation, as combining them can prolong the simulation time. Additionally, for current limitation, a resistor needs to be added at the output of the circuit.
