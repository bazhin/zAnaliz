# zAnaliz
Tool for Aveva System Platform using instead of original option to collect data (RAM, CPU, counters) 


1.	На узлах AS создать папку c:\temp или определить другую в которую будут сохраняться логи в атрибуте LogDataFilePath в формате c:\[ПУТЬ]\
2.	Импортировать шаблон zAnaliz он будет в toolbox zAnaliz
3.	Сделать экземпляры по кол-ву задеплоинных AppEngine (для ViewEngine не пока требуется)
4.	Развернуть (Задеплоить) по одному экземпляру на каждый задеплоиный AppEngine
 



Тестировалось под AVEVA (Wonderware) Application Server 2014 R2   4.1 SP1 P02     cdiversion="3735.0233.0776.0085"