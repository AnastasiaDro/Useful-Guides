# Start-android-mobile гайд по ведению документации с помощью Kdoc

## Зачем
Kdoc позволит не только добавлять описание файла или метода, но также:
- Указывать параметры класса / функции и позволять ходить по ним, нажимая непосредственно на название упомянутого параметра / класса
- При наводе курсора на метод в коде увидеть доку к нему

## Подробнее про Kdok:
- https://kotlinlang.org/docs/kotlin-doc.html

## Договоренности

- Комментарии пишем на **английском** (или на русском??? я за русский)

- Описание классов/методов обязательно и должно подчиняться следующему шаблону:
    - Для классов:
  ```
  /**
   * [SomeStarFeatureImpl] - реализация интерфейса [SomeStarFeature]
   *
   * @see SomeStarCoreFeature
   * @see SomeStarCoreFactiry
   * 
   * @author Thomas A. Anderson
   * @since 12.09.2022
   */
  ```
    - Для методов:
  ```
  /**
   * Описание SomeMethod
   *
   * @param path - путь к конфигу
   *
   * @see SomeFeature 
   */
  ```