Индивидуальная работа №1. Transaction Analyzer

1. Инструкции по запуску проекта.
  -Необходимо сохранить репозиторий на свой локальный компьютер
   
  -Перейти в директорию проекта в терминале
  
  -Создать файл с транзакциями transactions.json
  
  -В терминале запустить проект через команду node.js

3. Описание индивидуальной работы.
  Индивидуальная работа представляет собой консольное приложение для анализа транзакций, которое состоит из нескольких файлов: index.js, отвечающий за основной код приложения, и transactions.json, содержащий в себе необходимую информацию о транзакциях.

4. Документация к проекту.
   addTransaction(transaction): Добавляет новую транзакцию в массив.

   getAllTransactions(): Возвращает массив всех транзакций.
  
   getUniqueTransactionTypes(): Возвращает массив уникальных типов транзакций.
  
   calculateTotalAmount(): Рассчитывает общую сумму всех транзакций.
  
   calculateTotalAmountByDate(year, month, day): Рассчитывает общую сумму транзакций за указанный год, месяц и/или день.
  
   getTransactionsByType(type): Возвращает массив транзакций указанного типа.
  
   getTransactionsInDateRange(startDate, endDate): Возвращает транзакции, проведенные в указанном диапазоне дат.
  
   getTransactionsByMerchant(merchantName): Возвращает транзакции с указанным торговым местом или компанией.
  
   calculateAverageTransactionAmount(): Возвращает среднее значение транзакций.
  
   getTransactionsByAmountRange(minAmount, maxAmount): Возвращает транзакции в заданном диапазоне суммы.
  
   calculateTotalDebitAmount(): Рассчитывает общую сумму дебетовых транзакций.
  
   findMostTransactionsMonth(): Возвращает месяц с наибольшим количеством транзакций.
  
   findMostDebitTransactionMonth(): Возвращает месяц с наибольшим количеством дебетовых транзакций.
  
   mostTransactionTypes(): Возвращает тип транзакций с наибольшим количеством.
  
   getTransactionsBeforeDate(date): Возвращает транзакции, совершенные до указанной даты.
  
   findTransactionById(id): Возвращает транзакцию по идентификатору.
  
   mapTransactionDescriptions(): Возвращает массив описаний транзакций.

5. Примеры использования проекта Пример использования класса TransactionAnalyzer:

  const analyzer = new TransactionAnalyzer(transactions);

  console.log("Unique Transaction Types:", analyzer.getUniqueTransactionTypes());

  console.log("Total Amount:", analyzer.calculateTotalAmount());

  console.log("Total Amount in January 2019:", analyzer.calculateTotalAmountByDate(2019, 1));

5. Ответы на контрольные вопросы

   -В JavaScript существует несколько примитивных типов данных, которые включают в себя:

      Числа (Numbers): Представляют числовые значения. Могут быть целыми или с плавающей точкой.

      Строки (Strings): Представляют текстовые данные. Обрамляются одинарными или двойными кавычками.

      Логические значения (Booleans): Представляют логические значения true или false, которые используются для условных операций.

      Undefined: Отсутствие значения. Если переменная объявлена, но ей не присвоено значение, она имеет тип undefined.

      Null: Тип данных, представляющий отсутствие значения или пустое значение.

      Символы (Symbols): Представляют уникальные и неизменяемые значения и могут использоваться для создания идентификаторов для свойств объектов.

   -В рамках данного проекта были применены методы массивов, такие как forEach(), reduce(), filter() и map(), для последовательного перебора элементов массива, агрегации данных, фильтрации и преобразования информации о транзакциях.

   -Роль конструктора класса в JavaScript состоит в инициализации объектов, создаваемых на основе этого класса. В конструкторе есть возможность определить начальные значения свойств объекта, настроить его состояние и выполнить другие необходимые инициализации.

   -В JavaScript для создания нового экземпляра класса используется ключевое слово new, за которым следует вызов конструктора класса.

6. Список источников
  https://habr.com/ru/articles/572968/ - Работа с JSDoc

  https://learn.javascript.ru/types - Типы данных JS
  
  https://learn.javascript.ru/constructor-new - Конструктор, оператор new
