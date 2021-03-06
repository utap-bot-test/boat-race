## Перемога!

--- task ---

Тепер додай іще один блок `якщо`{:class="block3control"} до спрайту човна, щоб гравець перемагав, коли доводив човна до жовтого острова.

Коли човен добирається до острова, гра має сказати "УРА!", після чого вона має завершитися.

--- hints ---
 --- hint ---

Тобі треба додати ще деякі блоки коду всередині циклу `завжди`{:class="block3control"}, щоб твій код постійно перевіряв, чи переміг гравець:

`Якщо`{:class="block3control"} човен `торкається`{:class="block3sensing"} кольору берега, тобі треба `говорити "УРА!" 2 секунди`{:class="block3looks"}, а потім `зупинити все`{:class="block3control"}, щоб завершити гру.

--- /hint --- --- hint ---

Тобі будуть потрібні наступні блоки коду:

![спрайт човна](images/boat_resize.png)

```blocks3
say [УРА!] for (2) seconds

if <touching color [#FFFF99] ?> then
end

stop [all v]

```

--- /hint --- --- hint ---

Ось як має виглядати твій новий код:

![спрайт човна](images/boat_resize.png)

```blocks3
if <touching color [#FFFF99] ?> then
say [УРА!] for (2) seconds
stop [all v]
end
```

Не забувай, що цей код має бути всередині циклу `завжди`{:class="block3control"}.

--- /hint ------ /hints --- --- /task ---