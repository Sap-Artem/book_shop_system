# Вариант 5. БД «Издательство компьютерной литературы» 
#### Описание предметной области: Издательство занимается выпуском литературы по различным областям ИТ. Покупатели (юридические лица) приобретают книги на базе издательства. 
#### Когда на базе заканчиваются книги, издается дополнительный тираж. 
#### В каждом заказе заказчик может заказать разную литературу. Для покупки заключается договор, который сопровождает менеджер издательства. По каждому проекту составляется договор с Заказчиком (в 2-х экземплярах для каждой стороны). По каждому договору оформляется два счета – на предоплату и остаток. После выполнения проекта подписывается Акт выполненных работ (в 2-х экземплярах для каждой стороны). 
#### Каждое издание относится к определенной области ИТ, имеет тип (учебник, учебное пособие и т.п.), номер издания (если есть), может иметь одного или нескольких авторов, выпускаться под редакцией одного или нескольких авторов и т.п. При формировании списка авторов или списка “под редакцией” важен порядок авторов.
#### На каждое издание составляется Техническое задание, в котором могут участвовать несколько редакторов, один из которых является главным редактором. На каждую книгу может быть несколько ТЗ, в зависимости от переплета, типа бумаги, наличия иллюстраций и т.д. 
#### БД должна содержать следующий минимальный набор сведений: Фамилия автора. Имя автора. Отчество автора. Код автора. E-mail автора. Код ISBN. Название книги. Количество страниц. Наличие иллюстраций. Код категории книги. Категория книги. Количество страниц. Год начала издания. Розничная цена книги. Тираж. Дата тиража. Количество экземпляров на базе издательства. Код заказчика. Фамилия заказчика. Имя заказчика. Отчество заказчика. Адрес заказчика. Телефон заказчика. Код заказа. Дата заказа. Срок заказа. Количество экземпляров книги в заказе.  Статус заказа. Должность сотрудника. Количество ставок (по штатному расписанию).
#### Дополните состав атрибутов на основе анализа предметной области.
