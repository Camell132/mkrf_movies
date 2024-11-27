# Исследование данных о российском кинопрокате

Заказчик этого исследования — Министерство культуры Российской Федерации.
Вам нужно изучить рынок российского кинопроката и выявить текущие тренды. Уделите внимание фильмам, которые получили государственную поддержку. Попробуйте ответить на вопрос, насколько такие фильмы интересны зрителю.
Вы будете работать с данными, опубликованными на портале открытых данных Министерства культуры. Набор данных содержит информацию о прокатных удостоверениях, сборах и государственной поддержке фильмов, а также информацию с сайта КиноПоиск.

**Цель исследования** — изучение рынка российского кинопроката.

**Ход исследования**

Данные о прокатных удостверениях, выданных фильмам находятся в файле `mkrf_movies.csv`, а данные о сборах по соответствующим прокатным удостверениям `mkrf_shows.csv`. О качестве данных ничего не известно. Поэтому перед проверкой гипотез понадобится обзор данных. 

На этапе предобработки необходимо будет определить и обработать пропуски, проверить наличие дубликатов, привести данные в столбцах к нужным типам, оценить данные на наличие в них аномалий.

На этапе дополнения таблицы необходимо добавить столбец с информацией о годе проката, именем и фамилией главного режиссёра, основным жанром фильма и долей государственной поддержки от общего бюджета фильма.