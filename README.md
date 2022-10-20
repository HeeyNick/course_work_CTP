# It's My STP Course progect // Этом мой курсовой проект по СТП
## By HeeyNick ( Patrushev Nikita ) // Выполнен HeeyNick ( Патрушев Никита )
## IS-941 // ИС-941
## 13 variant // 13 вариант
## PackedVctor

___

## Introduction // Введение

  PackedVector - a vector that uses N given bits to store one element. 
  //  
  PackedVector - вектор, использующий для хранения одного элемента N заданных бит.  

___
  
## Buiding project // Сборка проекта

  mkdir build  
  cd build  
  cmake ..  
  cmake --build .  
  ./bin/libcsc_test  

___

## Documentation // Документация
  
  libcsc::PackedVector<unsigned short, 5> vec;  
  Иницифализация путого вектора с длиной элемента 5 // Path vector initialization with element length 5
    
  libcsc::PackedVector<unsigned short, 5> vec (5, 17);  
  Инициализация вектора с 5 элементами размером 17 // Initializing a vector with 5 elements of size 17  
    
  vec[1] = 4
  vec.at(1) = 4;
  Получение элемента // Get element  
    
  vec.assign(2, 4);  
  Изменеие значение элемента ( Индекс элемента, значение ) // Change value of element ( element's index, new value )
    
  vec.push_back(4);
  Помещение нового элемента в вектор // to put new element to vector  
    
  pop_back();
  Удаление // remove
    
  vec.resize(3)
  Изменеие длины вектора // Change vector size  
    
  vec.reserve(6)
  Изменение размерности вектора // change capacity of vector  
    
  vec.size()
  Получение кол-ва элементов в векторе // Get numbers of elements  
    
  vec.bits()  
  Получение количесва бит для одного элемента // get number of bits for one element  
    
  vec.used_bytes() 
  Получить количество байтов вектора, используемого для хранения используемых элементов // to get number of bytes vector's using to store it's used elements  
    
  vec.clear()  
  Очистка количесва бит для хранения в векторе // set all element to 0  
    
  vec.erase()  
  Очитска всей памяти вектора // free all vector's memory

