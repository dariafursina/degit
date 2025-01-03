# degit
Фурсина Дарья Андреевна
Цель лабораторной работы: изучить назначение распределённой системы управления версиями, освоить процесс создания репозитория и основы управления версиями файлов.

Основные команды Git

1. Инициализация репозитория
git init
Эта команда создает новый локальный репозиторий Git в текущем каталоге.

2. Клонирование репозитория
git clone <URL>
Клонирует удаленный репозиторий на ваш локальный компьютер. Замените <URL> на адрес репозитория.

3. Проверка статуса
git status
Показывает текущее состояние рабочего каталога и индекса, включая изменения, которые не были закоммичены.

4. Подготовка файлов к отправке
git add <имя_файла>
Добавляет указанный файл в индекс для следующего коммита. Чтобы добавить все изменения, используйте:
git add .

5. Создание коммита
git commit -m "Ваш комментарий"
Сохраняет изменения в локальном репозитории с комментарием. Комментарий должен описывать сделанные изменения.

6. Отправка изменений на удаленный репозиторий
git push origin <имя_ветки>
Отправляет ваши коммиты на удаленный репозиторий в указанной ветке.

7. Получение изменений из удаленного репозитория
git pull origin <имя_ветки>
Загружает изменения из удаленного репозитория и объединяет их с вашей текущей веткой.


8. Слияние веток
git merge <имя_ветки>
Объединяет изменения из указанной ветки с вашей текущей веткой.

9. Создание Pull Request
Pull Request создается на платформе GitHub (или другой системе управления версиями) после того, как вы запушите свои изменения в удаленный репозиторий. Это позволяет другим пользователям просмотреть ваши изменения перед их слиянием с основной веткой.
