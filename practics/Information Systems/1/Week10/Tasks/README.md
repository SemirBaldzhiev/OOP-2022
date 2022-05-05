# Седмица 10 - Множествено наследяване. Виртуални базови класове

Задача 1:
=
Напишете програма, която има клас определящ характеристиките на шоколад: процент на какао, произход и калории. Нека конструктора да приема процент на какао и произход.

Напишете метод, който пресмята калориите като измислите формула, която се съобразява с това, че колкото повече какао има, толкова по-малко са калориите.
Напишете клас млечен шоколад, който има процент съдържание на мляко.
Напишете клас млечен шоколад със специален вкус като добавите характеристика за специална добавка. Напишете метод, който връща общите калориите на млечния шоколад с добавка като функцията приема калориите на специалната добавка.

Задача 2:
=
Напишете програма, която има клас Date, който определя коректна дата чрез ден, месец и година и клас Time, който указва час, минути и секунди.
Класът DateTime обединява характеристиките на Date и Time и има метод, който връща като стринг датата и времето.

Задача 3:
=
В една софтуерна фирма има разработчици и системни администратори, но понякога системните администратори могат да има знания като разарботчиците.
Напише клас, който описва характеристиките на работник: има, телефон, адрес, години стаж, заплата.
Напишете два класа Разработчик и Системен Администратор, които имат метод за увеличаване на заплатата. На разработчик заплатата се вдига с 500лв, а на системен администратор с 250лв.
Напишете клас РазработчикСистеменАдминистратор, който има метод за увеличаване на заплатата като я увеличава със сумата за увеличаване при разработчик(извикайте правилната функция)

Задача 4:
=
Вие работите за определяне на печалбата в различни видове ресторанти. Видовете ресторанти могат да бъдат: класически ресторант, специализиран ресторант, ресторант с национална кухня и атракционно-тематичен ресторант.
Всички видове ресторанти имат следните характеристики: капацитет на свободни места, средна печалба за ден и средна печалба за година. Спрямо свободните места се изчислява средната стойност, която заплаща клиент.
Напишете метод, който връща тази средна стойност като имайте предвид, че тя се оценява спрямо средната стойност за ден и средната стойност за година(може да измислите подходяща формула).
Оказва се, че специализирания ресторант е и класически и ресторант с национална кухня.
Напишете програма, която създава обекти, от всички видове ресторанти, в main функцията и отпечатва средната стойност, която заплаща клиент.