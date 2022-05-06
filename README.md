[![Watch the video](https://i.ibb.co/rGWbzHq/2022-05-06-13-51-17.png)](https://youtu.be/vt5fpE0bzSY)

# “Классическая” rogue-like игра
## Вариант A0
**Рекомендую просто склонировать репозиторий с [гитхаба](https://github.com/pandao/editor.md ), там все есть**
### Базовая часть (10 баллов)
1. Добавлено 2 уровня
2. Чтение карты из текстового файла
3. Размер карты не менее 1600 тайлов
4. Раелизован весь базовый набор тайлов
5. Релизована стена, которую можно разрушить
6. Карта визуализирована (не уверен, что задействовано больше 50% карты, но если это очень критично, то я могу передизайнить уровни)
7. Игрок движется на кнопки WASD, взаимодействие через кнопку E
8. Игрок не проходит сквозь стены
9. Пустота(в моем случае лава) убивает игрока
10. Переход на следующий уровень сопровождается сообщением

**Таким образом реализована вся базовя часть**

### Дополнительная часть (до 15 баллов)
1. Релазиован графический эффект перехода между уровнями в виде плавного затемнения (применялся переход из RGB в HСV и обратно) **(3 балла)**
2. Эффект пост-обработки всего изображения в виде плавного блюра при смерти игрока (применялся стандартный фильтр размытия) **(3 балла)**
4. Анимация виде развевающегося портала, лавы, шипов, разрушаемой стены, ключа **(2 балла)**
5. Плавная спрайтовая анимация динамических объектов в виде игрока, шипов, двери **(2-5 баллов)**
6. Дополнительно реализовал механику шипов и двери (они у 1-ого и 2-ого варианта соответственно) (можно еще баллов 🙏)
7. Добавил здоровье у игрока(правый верхний угол) и время восстановления после получения урона

### Сборка
ресурсы я достаю через ../resources, поэтому сборка такая
```bash
cmake ./
make
cd ./bin
./main
```
### Геймплей
В видео есть основные механики геймплея, а также видно сборку

**Если что-то сломалось в игре, то, пожалуйста, напишите мне на почту vladtytskiy@gmail.com, я быстро все исправлю!**

