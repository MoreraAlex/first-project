#Тренировочный README  

##Подзаголовок для проверки размера  
---


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
