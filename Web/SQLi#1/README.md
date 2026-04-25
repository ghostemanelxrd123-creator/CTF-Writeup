# Writeup: SQL injection CTF

**Дата**: 23.04.2026


**Source**: https://2019-10-20-sqlinj.ctf.su/madoka

## Task description
Узнать рост Мадоки через SQLi. База данных: MySQL, WAF: "-- ", "#"

## Solution
Для того, чтобы узнать рост мадоки, необходимо вскрыть базу данных этого сайта методом SQL-инъекции, ведь простым пользователям такая информация недоступна. Первым делом я попробовал классический пейлоад 'OR '1'='1
И это сработало, в ответе отобразилась вся база данных.
Отсюда и решение CTF: рост мадоки -7263876
<img width="1194" height="690" alt="photo_2026-04-24_21-47-35" src="https://github.com/user-attachments/assets/932e8f3f-d682-4c28-9a60-dd334f1e9723" />

## Flag
```
spbctf{I_am_girl_magician!!}
```
By ghostemanelxrd123-create (Дмитрий)
