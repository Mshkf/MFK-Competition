# MFK-Competition
9-10 декабря 2023 года проходил хакатон ["МФКатон"](https://intellect-foundation.ru/press-center/news/studentyi-mfk-po-ii-prinyali-uchastie-v-sorevnovanii-po-resheniyu-zada/) для студентов МГУ, где я занял первое место по направлению "Глубокое обучение"

Задача состояла в том, чтобы по интонации определить эмоциональный окрас аудиоотрывка, то есть каждому аудиофайлу поставить в соответствие "Neutral", "Positive", "Sad" или "Angry" (Задача классификации)

Для решения этой задачи я привел все аудиофайлы к одной длине, взял мел-спектограмму, на ней обучил свёрточную нейросеть и получил скор f1 macro = 0.46 на тестовой выборке, что весьма неплохо для несбалансированного датасета

[Смотреть решение](https://github.com/Mshkf/MFK-Competition/blob/main/mfk-competition.ipynb)
