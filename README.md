# C_Sharp_Generics_CovariantContainer

## C#_Generics_CovariantContainer

### Задание «Контрольная точка №29 — обобщённые интерфейсы»

Вариант 1. Контейнер с вариативностью
1. `interface IContainer<out T> { T GetItem(); }`.
2. Классы `Animal` и `Dog : Animal`.
3. `class Box<T> : IContainer<T>`, хранящий и возвращающий значение типа `T`.
4. Создайте `Box<Dog>` и присвойте его переменной типа `IContainer<Animal>` — продемонстрируйте, что это компилируется и работает.
5. Дополнительно продемонстрируйте, что `Box<Dog>` напрямую (без интерфейса) НЕ присваивается переменной `Box<Animal>` — классы инвариантны, в отличие от интерфейса.

<img width="1680" height="474" alt="изображение" src="https://github.com/user-attachments/assets/7163c3da-e02e-464b-9511-750f9e42cb37" />

<img width="1479" height="283" alt="изображение" src="https://github.com/user-attachments/assets/7f7ac20b-cbb3-4bda-8e88-5f5d4a488036" />

