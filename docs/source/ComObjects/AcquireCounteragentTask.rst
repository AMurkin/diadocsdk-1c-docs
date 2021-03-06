AcquireCounteragentTask
=======================

Объект предназначен для отправки приглашения контрагента к партнерству


.. rubric:: Свойства

:CounteragentBoxId:
  **Строка, чтение/запись** - идентификатор организации-контрагента

:Inn:
  **Строка, чтение/запись** - ИНН организации-контрагента

:Message:
  **Строка, чтение/запись** - текст комментария к операции

:FileName:
  **Строка, чтение/запись** - имя файла с приглашением

:SignatureRequested:
  **Булево, чтение/запись** - запрос подписи контрагента


.. rubric:: Методы

+---------------------------------+--------------------------------------+
| |AcquireCounteragentTask-Send|_ | |AcquireCounteragentTask-SendAsync|_ |
+---------------------------------+--------------------------------------+

.. |AcquireCounteragentTask-Send| replace:: Send()
.. |AcquireCounteragentTask-SendAsync| replace:: SendAsync()



.. _AcquireCounteragentTask-Send:
.. method:: AcquireCounteragentTask.Send()

  Отправляет приглашение контрагента к партнерству



.. _AcquireCounteragentTask-SendAsync:
.. method:: AcquireCounteragentTask.SendAsync()

  Асинхронно отправляет приглашение контрагента к партнерству. Возвращает :doc:`AsyncResult`
