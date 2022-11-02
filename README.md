# Faceit Solidity App

Приложение представляет собой сайт и блокчейн структуру, реализующую рейтинговую таблицу игроков - пользователей [faceit](https://www.faceit.com/ru/home).
С наградой в виде криптовалюты для топа игроков. Приложение будет использовать учётную запись faceit и с разрешения пользователя, будет следить за результами
матчей в течении следующего ладдера (дневного, недельного, месячного). По окончанию ладдера, подсчитываются очки и игрокам с наибольшим количеством очков
начисляется криптовалюта. При записи на участие в ладдер, будет учитываться следующий ладдер, а не текущий.

## Команда

![This is an image](https://sun9-42.userapi.com/impg/v8UK8yo6c-JxvPfytns_KlhuzSmcexC-STblmg/xyHkzFPkv0Y.jpg?size=598x604&quality=95&sign=f332c3bf21d01b1e781042507f79d783&type=album)

Даниил "Шлюшка" Бурцев

Павел "Mystical WISE 3" Константинов

Алексей "Mystical WISE 2" Белкин

Глеб "Mystical WISE 1" Зеленский

```shell
npx hardhat help
npx hardhat test
REPORT_GAS=true npx hardhat test
npx hardhat node
npx hardhat run scripts/deploy.ts
```
