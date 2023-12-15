# Разработка приложения по управлению сценария
Необходимо разработать алгоритм по управлению сценариями при выборе различных действий. Для ориентира можно использовать механики текстовых квестов. Приложение должно уметь переключаться на необходимую ""ветку"" сценария, в зависимости от выбора пользователя. Также, должна быть возможность добавления собственых сценариев пользователя, без редактирования кода. Следовательно, приложение должно работать с текстовыми файлами, а также должен быть текстовый файл и с ""разметкой"" сценария по веткам. Таким образом, в приложении помимо какой-то истории с различными концовками (какая история - совершенно не важно. Главное, чтобы было 5-7 веток дейсвтия истории, в зависимости от выбора пользователя: В какую сторону пойти, что сказать, какой предмет взять и т.д), необходимо реализовать возможность добавления дополнительных ""сценариев"" с вариантами выбора, ветками и управляющим файлом, без перекомпиляции кода. Как один из вариантов реализации: приложение при запуске постоянно ищет в папке из которой оно запускается папку scenarios и проверяет, какие есть в ней папки и файлы. Исходя из полученных данных, предлагает возможные к запуску сценарии пользователю и отрабатывает их

Код написан на IntelliJ IDEA Community Edition 2023.3.1 SDK: correto-16 java version "16.0.2"
