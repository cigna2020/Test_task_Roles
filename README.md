Test_task_Roles

http://ilibrary.ru/text/473/p.1/index.html
Вам дан список ролей в виде массива и сценарий пьесы в виде строки.
Каждая строчка сценария пьесы дана в следующем виде: Роль: текст
Текст может содержать любые символы.
Напишите программу, которая будет группировать строчки по ролям, пронумеровывать их и возвращать результат в виде готового текста (см. пример). Каждая группа выводится в следующем виде:
Роль:
i) текст
j) текст2
...
==перевод строки==
i и j -- номера строк в сценарии. Индексация строчек начинается с единицы, выводить группы следует в соответствии с порядком ролей. Переводы строк между группами обязательны, переводы строк в конце текста не учитываются.
Sample Input:
roles:
[ "Городничий","Аммос Федорович",
"Артемий Филиппович","Лука Лукич"]
textLines:
"Городничий: Я пригласил вас, господа, с тем, чтобы сообщить вам пренеприятное известие: к нам едет ревизор.
Аммос Федорович: Как ревизор?
Артемий Филиппович: Как ревизор?
Городничий: Ревизор из Петербурга, инкогнито. И еще с секретным предписаньем.
Аммос Федорович: Вот те на!
Артемий Филиппович: Вот не было заботы, так подай!
Лука Лукич: Господи боже! еще и с секретным предписаньем!"
Sample Output:
Городничий:

1. Я пригласил вас, господа, с тем, чтобы сообщить вам пренеприятное известие: к нам едет ревизор.
2. Ревизор из Петербурга, инкогнито. И еще с секретным предписаньем.
   Аммос Федорович:
3. Как ревизор?
4. Вот те на!
   Артемий Филиппович:
5. Как ревизор?
6. Вот не было заботы, так подай!  
   Лука Лукич:
7. Господи боже! еще и с секретным предписаньем!
