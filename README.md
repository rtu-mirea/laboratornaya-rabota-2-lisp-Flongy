# Лабораторная работа №2.
Группа ИКБО-06-17. Журавлев Максим  
1. Работа со списками (lr2-1)
	- **pos_insert**(lst pos val) - вставка **val** в список **lst** на позицию **pos**
	- **pos_delete**(lst pos) - удаление элемента списка **lst** с номером **pos**
	- **find_val**(lst val) - вывод номера элемента/элементов списка **lst** со значением **val**
2. Чтение файла (lr2-2)
	- чтение файла **text.txt**
	- вывод содержимого
3. Сжатие и расжатие списков (lr2-3)
	- **compress**(lst) - сжатие списка **lst**. Например, список (1 1 1 0 1 0 0 0) преобразуется в ((3 1) 0 1 (3 0))
	- **decompress**(lst) - расжатие списка **lst**
