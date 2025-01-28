# T-Lab 2025. Multimodal LLMs - test task
Проанализируйте работу мультимодальных моделей с использованием идеи из библиотеки TransformerLens.
Для выполнения задания вы можете использовать вычислительные ресурсы Google Colab или Kaggle Notebooks. Подготовьте код и отчёт с подробным описанием экспериментов и результатов. На выполнение задания даётся **7 дней** с момента получения.
Этапы выполнения задания:
1. Изучение подхода Logit Lens
  - Разберитесь, как работает метод Logit Lens.
  - Кратко опишите, что такое Logit Lens и как этот подход помогает анализировать модели.
4. Применение фреймворка к мультимодальным моделям
  - Проанализируйте выбранные модели при помощи подхода logit lens, вы можете дописать фреймворк transformerslens или имплементировать подход самостоятельно. Вы можете сами выбрать тип модели и ее размер (например взять llava-onevision на 1.5b или qwen2-vl на 2b).
  - Выберите несколько датасетов для тестирования (например, изображения с разными объектами, цветами, формами и т.д.). Это могут быть как бенчмарки, так и любые другие датасеты.
  - Исследуйте динамику логитов на различных этапах работы модели.
  - Попробуйте выявить интересные паттерны, такие как появление или исчезновение признаков (например, цвета, формы, текстуры).
  - Расскажите что вам удалось найти: какие изменения происходят в логитах? На каких блоках модели они возникают?
10. Анализ проблем и предложение решений

Проанализируйте выявленные вами проблемы или особенности поведения моделей:
- Предложите возможные способы решения обнаруженных проблем.
- Опишите сильные и слабые стороны предложенных подходов.

Далее вы можете провести исследование существующих научных работ, которые описывают похожие проблемы в мультимодальных моделях:
- Сравните подходы из работ с вашими.
- Опишите различия в подходах и способах решения проблемы.
- Подумайте, как можно объединить ваш подход с найденными решениями для улучшения результата.
  
Советы по выполнению задания:
- Структурируйте код и выводы так, чтобы их было легко понять проверяющему.
- Используйте визуализации для наглядного представления результатов.
  
Если столкнулись с трудностями можете спросить у ChatGPT, главное понять и суметь рассказать что было сделано.
Правила:
- Проанализируйте полученные результаты. Это самый важный пункт, потому что хочется увидеть не только числа с полученными метриками. Как вы объясняете увиденное поведение? Напишите отчет о проведенных экспериментах. Что получилось? Что нет?
- Нет правильного способа решить задачу. Не стоит беспокоиться, что вы делаете что-то неправильно. Мы хотим увидеть ваши способности к исследованиям, а не какое-то конкретное решение задачи. Возможно, вы придумаете то, о чем мы даже не задумывались изначально – это будет высший класс.
- Убедитесь, что результатам можно доверять. Исключите вариант случайности, etc.
- Присылайте решение в виде репозитория на github с отчетом по решению и чёткими инструкциями, как запустить ваш код. Убедитесь, что мы сможем запустить ваше решение по этим инструкциям.
- Вы можете использовать любые библиотеки и фреймворки, которые вам могут быть необходимы.
- Сфокусируйтесь на том, чтобы код был чист и понятен. Если вы считаете, что какая-то его часть может быть непонятна, то добавьте комментарии. Мы очень сильно ценим хорошо написанный код, поэтому если решение задачи будет оформлено грязно, то мы можем отклонить заявку.
