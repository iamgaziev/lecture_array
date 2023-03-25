# lecture_array
## ARRAY IN JAVASCRIPT

>The Array object, as with arrays in other programming languages, enables storing a collection of multiple items under a single variable name, and has members for performing common array operations.

>In JavaScript, arrays aren't primitives but are instead Array objects with the following core characteristics:
>

>JavaScript arrays are resizable and can contain a mix of different data types. (When those characteristics are undesirable, use typed arrays instead.) 
>
>JavaScript arrays are not associative arrays and so, array elements cannot be accessed using arbitrary strings as indexes, but must be accessed using nonnegative integers (or their respective string form) as indexes.
>
>JavaScript arrays are zero-indexed: the first element of an array is at index 0, the second is at index 1, and so on — and the last element is at the value of the array's length property minus 1.
>
>JavaScript array-copy operations create shallow copies. (All standard built-in copy operations with any JavaScript objects create shallow copies, rather than deep copies).


## ARRAY METHODS

### JavaScript have 18 methods

![](/images/photo_2023-03-24_10-27-37.jpg)


#### Pop()

>The pop() method removes the last element from an array and returns that element. This method changes the length of the array.
>
>Метод pop() удаляет последний элемент из массива и возвращает этот элемент. Этот метод изменяет длину массива.
>

![](/images/pop.jpg)


### Push()

>The push() method adds one or more elements to the end of an array and returns the new length of the array.
>
>Метод push() добавляет один или несколько элементов в конец массива и возвращает новую длину массива.
>

![](/images/push.jpg)

### Shift() 

>The shift() method removes the first element from an array and returns that removed element. This method changes the length of the array.
>
>Метод shift() удаляет первый элемент из массива и возвращает этот удаленный элемент. Этот метод изменяет длину массива.
>

![](/images/shift.jpg)

### Unshift()

>The unshift() method adds one or more elements to the beginning of an array and returns the new length of the array.
>
>Метод unshift() добавляет один или несколько элементов в начало массива и возвращает новую длину массива.
>

![](/images/unshift.jpg)

### ToString()

>The toString() method returns a string representing the specified array and its elements.
>
>Метод toString() возвращает строку, представляющую указанный массив и его элементы.
>


![](/images/toString.jpg)

### Splice()

>The splice() method changes the contents of an array by removing or replacing existing elements and/or adding new elements in place. To access part of an array without modifying it, see slice().
>
>Метод splice() изменяет содержимое массива, удаляя или заменяя существующие элементы и/или добавляя новые элементы на место. Чтобы получить доступ к части массива без его изменения, см. slice().
>


![](/images/splise.jpg)

### Slice

>The slice() method returns a shallow copy of a portion of an array into a new array object selected from start to end (end not included) where start and end represent the index of items in that array. The original array will not be modified.
>
>Метод slice() возвращает неглубокую копию части массива в новый объект массива, выбранный от начала до конца (конец не включен), где начало и конец представляют индекс элементов в этом массиве. Исходный массив не будет изменен.
>

![](/images/slice.jpg)


### Reverse()

>The reverse() method reverses an array in place and returns the reference to the same array, the first array element now becoming the last, and the last array element becoming the first. In other words, elements order in the array will be turned towards the direction opposite to that previously stated.
>
>Метод reverse() переворачивает массив на месте и возвращает ссылку на тот же массив, при этом первый элемент массива становится последним, а последний элемент массива становится первым. Другими словами, порядок элементов в массиве будет повернут в сторону, противоположную указанной ранее.
>

![](/images/reverse.jpg)


### Concat()

>The concat() method is used to merge two or more arrays. This method does not change the existing arrays, but instead returns a new array.
>
>Метод concat() используется для объединения двух или более массивов. Этот метод не изменяет существующие массивы, а вместо этого возвращает новый массив.
>

![](/images/concat.jpg)


### Join()

>The join() method creates and returns a new string by concatenating all of the elements in an array (or an array-like object), separated by commas or a specified separator string. If the array has only one item, then that item will be returned without using the separator.
>
>Метод join() создает и возвращает новую строку путем объединения всех элементов массива (или объекта, подобного массиву), разделенных запятыми или заданной строкой-разделителем. Если в массиве только один элемент, то этот элемент будет возвращен без использования разделителя.
>


![](/images/join.jpg)


### Map()

>The map() method creates a new array populated with the results of calling a provided function on every element in the calling array.
>
>Метод map() создает новый массив, заполненный результатами вызова предоставленной функции для каждого элемента в вызывающем массиве.
>


![](/images/map.jpg)


### Fiter()

>The filter() method creates a shallow copy of a portion of a given array, filtered down to just the elements from the given array that pass the test implemented by the provided function.
>
>Метод filter() создает неглубокую копию части заданного массива, отфильтрованную до тех элементов из заданного массива, которые проходят проверку, реализованную предоставленной функцией.
>

![](/images/filter.jpg)

### Find()

>The find() method returns the first element in the provided array that satisfies the provided testing function. If no values satisfy the testing function, undefined is returned.
>
>Метод find() возвращает первый элемент предоставленного массива, который удовлетворяет предоставленной функции тестирования. Если никакие значения не удовлетворяют функции тестирования, возвращается значение undefined.
>

![](/images/find.jpg.jpg)

### Reduce()

>The reduce() method executes a user-supplied "reducer" callback function on each element of the array, in order, passing in the return value from the calculation on the preceding element. The final result of running the reducer across all elements of the array is a single value.
>
>Метод reduce() выполняет предоставленную пользователем функцию обратного вызова «reducer» для каждого элемента массива по порядку, передавая возвращаемое значение из вычисления предыдущего элемента. Конечным результатом выполнения редуктора для всех элементов массива является одно значение.
>

![]()



### ForEach

>The forEach() method executes a provided function once for each array element.
>
>Метод forEach() выполняет предоставленную функцию один раз для каждого элемента массива.
>


![]()



### Sort()

>The sort() method sorts the elements of an array in place and returns the reference to the same array, now sorted. The default sort order is ascending, built upon converting the elements into strings, then comparing their sequences of UTF-16 code units values.
>
>Метод sort() сортирует элементы массива на месте и возвращает ссылку на тот же массив, теперь отсортированный. Порядок сортировки по умолчанию — восходящий, основанный на преобразовании элементов в строки и последующем сравнении их последовательностей значений кодовых единиц UTF-16.
>

![]()

### IndexOf

>The indexOf() method returns the first index at which a given element can be found in the array, or -1 if it is not present.
>
>Метод indexOf() возвращает первый индекс, по которому данный элемент может быть найден в массиве, или -1, если он отсутствует.
>

![]()


### Includes()


>The includes() method determines whether an array includes a certain value among its entries, returning true or false as appropriate.
>
>Метод include() определяет, содержит ли массив определенное значение среди своих элементов, возвращая true или false в зависимости от ситуации.
>

![]()