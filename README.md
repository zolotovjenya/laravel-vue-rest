Адрес по которому можно визуально посмотреть результат работы -  https://test.studdix.com/

Ссылка кода на github - https://github.com/zolotovjenya/abz

Laravel 7 + vue js
Все доп библиотеки установлены через composer и npm соответственно

1) Rest api в соответствии с предложенным примером
2) Генератор данных и seeder( я уже выполнил seeder чтобы заполнить базу первыми 45 юзерами, если что то код лежит в папке database/seeds/UserSeeder.php )
Для генерации имен использовал библиотеку https://github.com/nubs/random-name-generator
3) Для оптимизации картинок использовал tinify сервис.
Для запроса создания юзера используется header Token.
4) Реализован вывод списка юзеров по пагинации. 
(в задании не совсем понятно указано, в описании задачи, что сделать кнопку "Показать еще", а в примере api запроса про next_link и prev_link указывает на то, что надо реализовать все таки пагинацию. Вообщем "Показать еще" реализовать еще легче, решил сделать пагинацию по параметрам указанным в api запросе).

Сделана форма создания юзера по токену.
Время токена 40 минут.

На задание было потрачено примерно 15 часов