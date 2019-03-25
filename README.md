# Лабораторная работа 7

## Задание

1. Реализуйте аналог `std::vector`.
1. Обеспечте **амортизированную сложность O(1)** добавления элемента в конец вектора.
1. Реализуте модульные тесты для вашего класса.
1. Проверьте код на наличие утечек памяти.
1. **Использовать `std::vector` запрещается.**
1. Следует использовать стандартные типы исключений из библиотеки `<stdexcept>`.

### Методы для реализации
```cc
template <class T>
class vector
{
public:
    vector();
    Конструктор копирования
    vector(size_t, const T&);
    ~vector();
    оператор присваивания
    
    operator[]
    at
    front
    back
    data
    
    begin
    end
    
    empty
    size
    reserve
    capacity
    
    clear
    insert
    push_back
    pop_back
    swap
};
```

## Ссылки
- [Выделение памяти под vector](http://alenacpp.blogspot.com/2005/06/vector_30.html)
- [Амортизированная сложность](https://www.coursera.org/lecture/c-plus-plus-red/amortizirovannaia-slozhnost-sGVxq)