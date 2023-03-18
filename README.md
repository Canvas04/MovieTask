# Movies App - Рейтинг и жанры
[Итоговый макет](https://www.figma.com/file/3Byrf7DtfhBjSBBLDo5WI8/Movies?node-id=9590%3A342&t=NMAwiMHed8pKzIpd-0)

Используя [MovieDB API](https://developers.themoviedb.org/3/getting-started/introduction) и [Antd](https://ant.design/) разработайте приложение для поиска фильмов.

Добавим функционал добавления в избранное и отображение жанров.

При запуске вашего приложения создаем новую гостевую сессию по апи
Разделяем приложение на 2 таба - Search и Rated, в табе Rated выводим только список тех фильмов, которы оценивали (см апи) без строки поиска - в остальном макет идетичен.
Добавляем звезды для голосования (компонент Rate). Если вы не голосовали за фильм - все звезды должны быть пустыми, если голосовали - тот рейтинг, что вы проставили фильму.
Добавить блок с текущим рейтингом в правом-верхнем углу блока, сделать изменение цвета круга в зависимости от рейтинга (см ниже).
При старте приложения получать список жанров, хранить данные с помощью React.Context, отображать по соотвествующим ID в списке жанров карточки.
Цвета в зависимости от оценки:

От 0 до 3 - #E90000\
От 3 до 5 - #E97E00\
От 5 до 7 - #E9D100\
Выше 7 - #66E900\

Новое задание: 
1) Использую вышенаписанное Api реализовать функционал поиска фильмов.
2) Добавить индикатор загрузки - возьмите из библиотеки Antd компонент Spin.
3) Использовать debouce для инпута(debounce использоввать для запроса фильмов)
