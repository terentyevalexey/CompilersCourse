## Чекпоинт 7. Канонизация IR-дерева

### Уложитесь в конец семестра

Мы создали с вами IR-дерево, теперь необходимо его привести к каноническому виду.

Для этого необходимо построить три visitor-а для IR-деревьев:
* Избавление от двойного CALL-а в ребенке дерева
* Избавление от ESEQ
* Линеаризация

Про детальное описание операций можно прочесть в [https://akht.pl/compilers2020-lecture09](https://akht.pl/compilers2020-lecture09)

Важно продемонстрировать деревья, в которых были такие проблемы, и что эти проблемы были решены!


Успехов!
