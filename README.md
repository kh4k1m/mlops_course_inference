# mlops_course_inference

Инференс состоит из двух частей. 
В первой нам нужно создать базу с людьми и описывающими их эмбедингами. Эмбеддинг предсказывается моделькой. А модельку (для начала) мы возьмем готовую на просторах интернета). Вопрос только как хранить данные, чтоб был быстрый доступ к ним.
Во второй части нужно будет из изображения человека извлечь эмбеддинг. После сопоставить со всеми эмбеддингами в базе и найти к какому человеку ближе всех. Дальше соспоставить с пороговым значением. И тут два варианта: проходит по порогу и мы нашли человека в базе или не проходит по порогу и этого человека нет в базе.