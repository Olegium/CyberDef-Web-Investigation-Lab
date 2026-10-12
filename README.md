## WEB INVESTIGATION

# ВОПРОСЫ

<img width="529" height="1178" alt="image" src="https://github.com/user-attachments/assets/6e4b2dad-127d-4aa5-8bf5-da868ea651a2" />

Тут нам сканят порты 170.40.150.126 отправлял tcp пакеты и нашел порты 80 и 54587 куда подключился

<img width="1520" height="798" alt="image" src="https://github.com/user-attachments/assets/a7cf4d26-48af-4caf-affc-30f935d4c4eb" />

Посмотрим кто отправлял больше всего syn пакетов это 111.224.250.131
 
<img width="1570" height="1285" alt="image" src="https://github.com/user-attachments/assets/e951494b-a1c6-4ec6-8a92-e9c1822ee634" />

Пробиваем и находим город 

<img width="796" height="300" alt="image" src="https://github.com/user-attachments/assets/cac6a8d7-ccf1-48b6-9026-0142f74a0423" />

Находим скрипт.php через который взаимодействие происходит

<img width="1051" height="314" alt="image" src="https://github.com/user-attachments/assets/1352bb60-1a48-40f9-97ee-01e8e2609580" />

вот тут 1ая sql иньекция

<img width="1087" height="325" alt="image" src="https://github.com/user-attachments/assets/f5d65e9d-2111-4b7b-8990-a80cfcb20d91" />

1520 запрос обращался к схеме бд и поэтому нужен именно он

<img width="2370" height="415" alt="image" src="https://github.com/user-attachments/assets/9921f373-3d36-498b-88d7-cce56242f1b3" />

у нас был запрос со схемой который мы отправили и получили ответ названия бд и столбов

<img width="2555" height="647" alt="image" src="https://github.com/user-attachments/assets/9b33f4b2-92a2-42c4-b120-6b189811808b" />

нашли каталог админа 

<img width="869" height="1342" alt="image" src="https://github.com/user-attachments/assets/aa2936a6-f5f5-486d-84b9-25821d0625e5" />

ищем под какими данными логинились и вот admin

<img width="1114" height="602" alt="image" src="https://github.com/user-attachments/assets/bd9b9e92-a3cd-40d4-82a5-11888bd0df7e" />
