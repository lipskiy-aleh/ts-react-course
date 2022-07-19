# Array Methods  

## Part 1
Implement custom version of map, reduce, filter, forEach method of Array.  
Custom methods must have the same syntax as native implementation.  
  
```js
// https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map
Array.map
Array.prototype.customMap = () => { }

// https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/reduce
Array.reduce
Array.prototype.customReduce = () => { }

// https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter
Array.filter
Array.prototype.customFilter = () => { }

// https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/forEach
Array.forEach
Array.prototype.customForEach = () => { }
```

## Part 2
1. Создать строку из названий предметов написаных через запятую
2. Посчитать общее количнство студентов и учителей на всех предметах
3. Получить среднее количество студентов на всех пердметах
4. Создать массив из объектов предметов
5. Получить массив из предметов и отсортировать по количеству преподавателей на факультете от большего к меньшему


```javascript
    const subjects = {
        mathematics: {
            students: 200,
            teachers: 6
        },
        biology: {
            students: 120,
            teachers: 6
        },
        geography: {
            students: 60,
            teachers: 2
        },
        chemistry: {
            students: 100,
            teachers: 3
        }
    }
```