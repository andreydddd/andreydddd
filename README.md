## About me
Приветствую на своем репозитории студента ИТМО - тут будут всякие лабораторные, не гарантирую, что все будет работать как надо, но по крайней мере, я пытался.
- Изучаю С С++ и технологии разработки
- Санкт-Петербург
- Активно изучаю различные алгоритмы и сортировки

## Technologies
В моих проектах используются:
| Язык | Сложность |
|---|---|
| C | Средняя |
| C++ | Средняя |
| Python | Лёгкая |

> программирование - сплошная магия  
> Главное не бояться ошибок!

## Favourite Sort:
``` C++
void QuickSort(int arr[], int left, int right) {
  if (right - left <= 1) {
    return;
  }

  int pivot = left + rand() % (right - left); // index
  int pivotValue = arr[pivot];                     // element massiva
  int i = left;
  int j = right - 1;

  while (i <=
         j) { // даже когда равны индексы, все равно сдвинутся и i будет > j

    while (arr[i] < pivotValue) { // найти слева неподходящий
      i++;                   // двигаем индекс, может стать пивотом
                             // 2 3 |5| 6 9 - в итогe arr[i] = 5
    }
    while (arr[j] > pivotValue) { // найти справа неподходящий
      j--;
    }
    if (i <= j) { // не пересеклись ли левая с правой стороной, если нет -
                  // дальше сортируем
      int current_left = arr[i];
      arr[i] = arr[j];
      arr[j] = current_left;
      i++; // смещаются к "центру"
      j--; // чтобы дальше по вайл пошли
    }
  }
  QuickSort(arr, left, j + 1);
  QuickSort(arr, i, right);
}
```
![VS Code](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)

![C++](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)

## Active card
![GitHub Streak](https://streak-stats.demolab.com?user=andreydddd&theme=radical)
![Top Langs](https://github-readme-stats-ten-gilt.vercel.app/api/top-langs/?username=andreydddd&layout=compact&theme=radical)
<!--
**andreydddd/andreydddd** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
