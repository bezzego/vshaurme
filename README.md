# Vshaurme

Инновационная социальная сеть для любителей лучшего блюда на свете! Вместо групп, как в большинстве социальных сетей, мы будем объединяться
относительно точек продажи! Вы сможете найти новые знакомства среди людей, которые покупают еду неподалёку от вас,
обмениваться отзывами о любимых сочетаниях мяса и овощей и ставить звёзды продавцам!

### Проект находится в разработке

Поэтому приветствуется любая помощь от знающих программистов! Построим социальную сеть будущего вместе!

Для того чтобы обновить код, вам достаточно сделать fork репозитория, внести изменения, запушить их в fork, а затем создать Pull Request с описанием проделанных изменений.

### Как помогать

Проект работает на [Django 1.11.1](https://www.djangoproject.com).  
Сейчас очень нужна помощь с моделированием системы, почитать о которой можно [здесь](https://docs.djangoproject.com/en/1.11/intro/tutorial02/#creating-models).

### Как запускать
Создайте файл `local.py` в папке `vshaurme/settings/` и положите туда переменную `SECRET_KEY` с любым содержимым.  
После этого установите зависимости из `requirements.txt` любым удобным вам способом.  
Далее создайте базу данных командой ```python manage.py migrate```. Эту команду нужно будет повторять, если вы скачаете обновления нашего кода, в которых изменяется структура базы данных.

Затем соберите статические файлы командой ```python manage.py collectstatic```. Эту команду также нужно повторять всякий раз, когда вы скачаете обновления, в которых изменены шаблоны проекта.

Сервер запускается командой ```python manage.py runserver```.

Код написан в образовательных целях на курсах для веб-разработчиков [dvmn.org](https://dvmn.org/).
