Написать небольшой сервис на языке Python, имитирующий работу банка со счетами клиентов.


Требования к сервису:
     
     ● работа с сервисом должна осуществляться через Interactive CLI
     
     ● состояние счетов хранится только в рамках одной сессии
     
     ● у клиента может быть только один счет
     
     ● валюта у всех счетов одинаковая - USD
     
     ● поддерживаемые операции:

          ○ deposit - операция пополнения счета на сумму, аргументы: client, amount, description

          ○ withdraw - операция снятия со счета, аргументы: client, amount, description

          ○ show_bank_statement - вывод на экран выписки со счета за период, аргументы:
            client, since, till

![Example](https://user-images.githubusercontent.com/79754440/117973174-b9189780-b334-11eb-9dc8-237aa0fa69d5.PNG)
