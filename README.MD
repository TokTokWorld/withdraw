BUGS:


TODO:

- Make ETH withdraw
- Catch deposit after 1 confirmations
- Confirm withdraw from email and 2-auth


Ввод средств - Каждый блок проверяем на наличие входящих транзакций по нашим адресам из базы
               При этом обновляем достигло ли количество подтверждений 10 и обновляем счетчик в базе
               Как только достигает, помечаем транзакцию успешной

Аккамуляция - Проходит по всем кошелькам и собирает балансы с них в одно место

Вывод - 1) Проверям на кошельке необходимое количество эфиров
        2) Если нет, то проверяем в других кошельках
        3) Если нет, то выводим из горячего кошелька