# /src/infrastructure/repositories - репозитории (конкретная реализация доменного слоя)

Этот каталог содержит исходные файлы конкретной реализации доменного слоя. Примерная структура для сущности **entity** 
может выглядеть следующим образом:

```
/src/infrastructure/repositories: репозитории (конкретная реализация доменного слоя)
    - /entity
        - InMemoryEntityRepository.php
        - SqlEntityRepository.php
        - FileEntityRepository.php
```

Здесь реализованы 3 вида репозитория: в памяти, sql и файловый.