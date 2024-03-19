# Zasilacz-stabilizowany-bez-LM317
Zasilacz został wykonany w programie Eagle.
Płytka została wykonan z możliwością wsadzenia jej do obudowy dlatego schemat końcowy może różnić się względem shcematu płytki
bezpiecznik jak i transformator znajdują się poza nią tak samo potencjometry
Głównym zamysłem było wykonanie zasilacza bez użycia LM317, założennie zostało spełnione.
kolejnym założeniem było sterowaniem napięcia w zakresie od 0 do 15 V oraz ograniczeniem prądowym od 0 do 2 A 

Przeiwdziane są dodtakowe wyjście na usprawnienie układu wentylaotrem lub woltomierzem oraz amperomierzem wymagającego dodatkowego zasilania

Rezystory R3(RV) oraz RA służą do ustawienia konkretnego napięcienia/natężenia
Schemat końcowy zasilacza wygląda następująco:
![image](https://github.com/Ptakoninja/Zasilacz-stabilizowany-bez-LM317/assets/164054955/8095e5de-0841-49d7-81fb-665919786744)

schemat wykorzystany do stowrzenia płytki PCB:

![image](https://github.com/Ptakoninja/Zasilacz-stabilizowany-bez-LM317/assets/164054955/44ce08ce-32f7-44fa-8efb-628d72433dcb)

Wygląd końcowy płytki góra:

![image](https://github.com/Ptakoninja/Zasilacz-stabilizowany-bez-LM317/assets/164054955/34817ba8-f4ef-425c-806d-ee9e7ff4a54f)

W przypadku symulacji 
Zasilacz po zmontowaniu działał zadawalająco prąd mieścił się w zakresie 0-1,7A a napięcie od 1,3 do 14,6 dobierając lepszej jakości rezystory można poprawić zakres na bardziej zbliżony do oczekiwanych.
