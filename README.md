# result.txt

### Задание 1
*Первым моим заданием было убрать все пробелы в Повести Временных Лет. Я это сделала с помощью следующего регулярного выражения: ^\s+. Графа "Replace" была оставлена пустой.* 

![](https://pp.userapi.com/c846520/v846520294/644ff/ATaH3-vS4EQ.jpg)

### Задание 2
*Вторым моим заданием было найти всех князей и города, имя и название которых оканчивается на "слав". В выдаче должны были быть такие слова как "Ярославля, Ростиславъ, Ростиславу, Переяславлъ" и т.п. Но не должно было быть "славу, выславше" и т.п.Для того, чтобы получить такую информацию я использовала следующее регулярное выражение: [А-ЯѢ]+[а-яѣ]+(слав)[а-яѣ]+ . Всего было найдено 564 вхождения.*

![](https://pp.userapi.com/c846520/v846520294/645ea/DxLlOnjJRuc.jpg)

### Задание 3
*Третьим моим заданием было найти все упоминания Новгорода. В выдаче должны были быть такие слова как "Новѣгородѣ, Новъгородъ, Новгородцю, Новагорода, Новугороду". Для этого я использовала следующее регулярное выражение: (Нов)+.(город)[^W] . Всего было найдено 58 упоминаний города."*

![](https://pp.userapi.com/c846520/v846520294/645f4/FhzDAOluBpA.jpg)
