Тренировочный README  

##Подзаголовок для проверки размера  
---

Шпаргалка по Git

- Инициализация репозитория: git init
- Клонирование удалённого репозитория: git clone <URL_репозитория>
- Просмотр состояния файлов: git status
- Добавление изменений в индекс: git add . (все файлы), git add <filename> (конкретный файл)
- Фиксация изменений: git commit -m "<сообщение>", git commit -am "<сообщение>" (добавляет изменения и коммитит сразу)
- Просмотр истории коммитов: git log, git log --oneline (упрощённый вывод)
- Отмена локальных изменений файла: git checkout -- <filename>
- Переход между ветками/коммитами: git checkout <branch/commit>
- Создание новой ветки: git branch <название_ветки>
- Удалённая работа:
  * Отправка изменений на сервер: git push origin <branch_name>
  * Получение обновлений с сервера: git pull origin <branch_name>
- Объединение веток: git merge <branch_name>
- Разрешение конфликтов слияния вручную, используя редакторы типа VS Code, Vim или Nano
- Проверка внесённых изменений перед отправкой: git diff
- Игнорирование определённых типов файлов: использование .gitignore
- Работа с тегами: создание тега — git tag <tagname>, просмотр всех тегов — git tag
- Перезагрузка удалённой ветки: git reset --hard origin/<branch_name>
- Изменение последнего коммита: git commit --amend


**Тема номер один**  
*возможности markdown*  
1. Нумерация
2. Списков
3. И
4. Чеклистов
---
- Тезисные
- Разметки
- Текста
---
Добавление блока кода, например на ==JAVA==
```java
public static void main(String[] args) {
        OrdersManager ordersManager = new OrdersManager();

        ordersManager.printAllOrders();
        System.out.println("Всего заказов на сумму: " + ordersManager.getOrdersSum());

        String maxOrderCustomerName = ordersManager.getMaxOrderCustomerName();
        System.out.println("Самая большая сумма заказов у " + maxOrderCustomerName);
        ordersManager.printCustomerOrders(maxOrderCustomerName);

        ordersManager.removeUnprofitableOrders();
    }
```


###Чеклисты
- [x] Заполнить тренировочный README
- [ ] Продолжать
- [ ] И еще


~~Конец~~
