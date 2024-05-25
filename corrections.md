Общая проблема - ожидаемый результат ты пишешь как некое требование - https://github.com/YuSpbPsb/qa-engineer-project-85/blob/65a5a666d9ada29265fcede887d4f50c9288213b/test-cases.yml#L14

Нужно писать фактом того что происходит после последнего шага воспроизведения "Игра без регистрации успешно создана"
test-cases.yml
1

https://github.com/YuSpbPsb/qa-engineer-project-85/blob/65a5a666d9ada29265fcede887d4f50c9288213b/test-cases.yml#L14 - обсудили выше поправить
2

https://github.com/YuSpbPsb/qa-engineer-project-85/blob/65a5a666d9ada29265fcede887d4f50c9288213b/test-cases.yml#L22 - нам не нужно указывать такие данные при регистрации ведь после первой попытки они станут не валидны Да и доступов к почте нет - зачем они нам?) Удаляем

https://github.com/YuSpbPsb/qa-engineer-project-85/blob/65a5a666d9ada29265fcede887d4f50c9288213b/test-cases.yml#L32 - то что зер переходит на главную страницу не означает что регистрация прошла успешно)

"Пользователь успешно зарегистрирован"
3

https://github.com/YuSpbPsb/qa-engineer-project-85/blob/65a5a666d9ada29265fcede887d4f50c9288213b/test-cases.yml#L47 - обсудили выше сделать по аналогии
4

https://github.com/YuSpbPsb/qa-engineer-project-85/blob/65a5a666d9ada29265fcede887d4f50c9288213b/test-cases.yml#L50 - дубль удалить
5

https://github.com/YuSpbPsb/qa-engineer-project-85/blob/65a5a666d9ada29265fcede887d4f50c9288213b/test-cases.yml#L112 - обсуждали выше
6

https://github.com/YuSpbPsb/qa-engineer-project-85/blob/65a5a666d9ada29265fcede887d4f50c9288213b/test-cases.yml#L127 - обсуждали выше
7

https://github.com/YuSpbPsb/qa-engineer-project-85/blob/65a5a666d9ada29265fcede887d4f50c9288213b/test-cases.yml#L137 - ты указываешь много параметров для выбора - но правда ли мы это проверяем? Мы же можем создать игру с ботом сч теми условиями по умолчанию и это никак не появлияет на проверку

Если только мы не проверяем конкретно выбор парамтеров - поэтому давай сократим шаги и оставим только главное где мы выбираем игру с ботом именно)

https://github.com/YuSpbPsb/qa-engineer-project-85/blob/65a5a666d9ada29265fcede887d4f50c9288213b/test-cases.yml#L145 - можно еще так "Игра с ботом успешно создана"
8

https://github.com/YuSpbPsb/qa-engineer-project-85/blob/65a5a666d9ada29265fcede887d4f50c9288213b/test-cases.yml#L215 - тоже самое про параметры точно ли они нужны нам все для проверки победы в игре?
9

https://github.com/YuSpbPsb/qa-engineer-project-85/blob/65a5a666d9ada29265fcede887d4f50c9288213b/test-cases.yml#L236 - тоже самое про параметры
testing-report.yml

Актуализировать и изменить в соотвествии с изменениями и указаниями выше. 