# «Исследование методов второго порядка для обучения нейронных сетей»

В ходе работы проводятся эксперементы сравнения метода второго порядка KFAC, реализация которого была взята из https://github.com/gpauloski/kfac-pytorch#developing,
с медотоми Адама и SGD. На первом этапе обучается более простая нейронная сеть и решается задача распознавания цифр, на этом этапе KFAC показывает себя достаточно хорошо и кажется более эффективным. 
На втором этапе используется уже более сложная нейронная сеть resnet18 и решается задача классификации животных на картинках, KFAC показывает хорошие результаты но не сильно лучшие по сравнени с результатами от применения других методов, а работает в несколько раз дольше, на данной задаче это уже сильно заметно и напоминает нам о том почему мы не применяем методы второго порядка на практике. 
