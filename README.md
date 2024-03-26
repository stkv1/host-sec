# Домашнее задание к занятию «Защита хоста»

## Козлов Станислав

### Задание 1
Установите eCryptfs.
Добавьте пользователя cryptouser.
Зашифруйте домашний каталог пользователя с помощью eCryptfs.
В качестве ответа пришлите снимки экрана домашнего каталога пользователя с исходными и зашифрованными данными.

*Исходные данные под пользователем Cryptouser*

![07](https://github.com/stkv1/host-sec/assets/145263196/3ea0ea7a-0c4f-4753-b6a7-bc56a5dd5ed5)


*Зашифрованные данные*

![08](https://github.com/stkv1/host-sec/assets/145263196/2367d057-04ea-4395-b819-228ca0942e16)


### Задание 2
Установите поддержку LUKS.
Создайте небольшой раздел, например, 100 Мб.
Зашифруйте созданный раздел с помощью LUKS.
В качестве ответа пришлите снимки экрана с поэтапным выполнением задания.

*Размеченный раздел*

![12](https://github.com/stkv1/host-sec/assets/145263196/221c3920-cbd5-424b-8c5f-548606fc5365)


*Привязка раздела в LUKS*

![15](https://github.com/stkv1/host-sec/assets/145263196/3916155d-051d-4300-8139-af013461bdf2)

![16](https://github.com/stkv1/host-sec/assets/145263196/78c98d85-3ec3-4677-9d09-d9cc0cf8ffe9)



*Перезапись раздела нулями и переразметка ext4*

![17](https://github.com/stkv1/host-sec/assets/145263196/0a3609df-9ac5-4fac-bcab-693966633fc5)

![18](https://github.com/stkv1/host-sec/assets/145263196/66639483-1cd4-4016-899c-31fe3610db1d)

*Монтирование зашифрованного раздела*

![19](https://github.com/stkv1/host-sec/assets/145263196/9f310ba3-912b-4dcf-b8c9-0d538894dcf0)


*Размонтирование раздела и отключение LUKS*

![20](https://github.com/stkv1/host-sec/assets/145263196/8ae01811-9e15-4a2b-b6be-a5f7222ee879)




### Задание 3 *
Установите apparmor.

![21](https://github.com/stkv1/host-sec/assets/145263196/600f59ba-5fb0-4e8b-882c-86947052b7bc)

Повторите эксперимент, указанный в лекции.

![25](https://github.com/stkv1/host-sec/assets/145263196/a1421898-7338-4f6a-a5ba-53f88e000a36)

![26](https://github.com/stkv1/host-sec/assets/145263196/3d1f78e3-6d50-46c6-b53f-72e39f23fc95)

![27](https://github.com/stkv1/host-sec/assets/145263196/85e54a12-543f-4288-8ca6-a329ebf1fe5e)

Отключите (удалите) apparmor.

![28](https://github.com/stkv1/host-sec/assets/145263196/2b638c71-4acc-495e-9449-02f5cc1df993)

![29](https://github.com/stkv1/host-sec/assets/145263196/63fc9760-999c-408e-bff2-afa7fa13b81b)

В качестве ответа пришлите снимки экрана с поэтапным выполнением задания.


