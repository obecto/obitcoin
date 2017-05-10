# Obitcoin

[Актуална версия на проекта за тестване][prj]

##### Моля да обърнете внимание на изискванията за инсталацията на безплатното браузър разширение [Metamask][msk]
То осъществява връзката до Ethereum blockchain мрежата.

За да може да извършвате дейности с договори в мрежата ви трябва акаунт със средства в криптовалутата. Засега се използва Kovan test network като мрежа за тестване и разработване на нашите инстанции на договора. Приготвен е Ethereum акаунт с достатъчно средства (които нямат реална стойност в мрежата) за ваше удобство. Моля, следвайте следните стъпки за настройване и тестване на прототипа:

- Инсталирайте [браузър разжирението][msk]
- Стартирайте го, приемете общите условия за ползване и изберете опцията "Import existing DEN"

![alt tag](https://github.com/KingOfAllChunks/obitcoin/blob/master/screenshots/setup/import_account.png)

- В полето "Wallet seed" въведете следните следните примерни данни за тестовия акаунт: "illegal goat income maid bargain junk bargain child story alone want dismiss" и парола по ваш избор, която ще бъде използвана за криптиране на данните.

![alt tag](https://github.com/KingOfAllChunks/obitcoin/blob/master/screenshots/setup/enter_seed.png)

- Свържете се до "Kovan Test Network" от горния ъгъл вляво.

![alt tag](https://github.com/KingOfAllChunks/obitcoin/blob/master/screenshots/setup/choose_network.png)

- След повторно въвеждане на вашата избрана парола получавате достъп до следния акаунт с ненулев баланс от Ether.

![alt tag](https://github.com/KingOfAllChunks/obitcoin/blob/master/screenshots/setup/done.png)


Настройката е готова. [Можете да посетите тестовата версия на проекта][prj]. Имате възможността да си създадете собствена инстанция на криптодоговора. За ваше удобство е създаден вече настроен тестов криптодоговор в мрежата от името на Ethereum акаунта който преди малко настроихте. Може да го достъпите като въведете следния адрес в login формата (в тестовата версия на уеб приложението това става автоматично):
- 0x546eb1b4361645de25a748bdc9ee95ab42556657

Понеже е от името на вашия акаунт, вие имате правото да извършвате транзакции в договора.
Някои от транзакциите, които можете да създадете, са следните:
- Добавяне / редактиране на член в договора
- Добавяне / редактиране на debt pools (групи от хора, работещи върху същия проект)
- Изпращане на точки на определени членове в определени групи (натрупване на дълг)
- Откупуване на точки в определена група. Откупените точки ще бъдат разпределени по всеки човек от групата спрямо правилата за разпределение

##### Внимание! Kovan test мрежата може да не е стабилна на моменти. Понеже е второстепенна мрежа за тестване без реална стойност на валутата, тя може да бъде атакувана и забавяна. Това може да резултира до много голямо време за изчакване на транзакции. Подобни атаки са теоретически невъзможни главната Ethereum мрежа, за която е предназначен този проект.

[msk]: <https://metamask.io/>
[prj]: <https://kingofallchunks.github.io/obitcoin/>