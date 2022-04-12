# /src/infrastructure/repositories - репозитории (конкретная реализация доменного слоя)

Этот каталог содержит исходные файлы конкретной реализации доменного слоя. Примерная структура для сущности **entity** 
может выглядеть следующим образом:

<pre>
<a href="../README.md">/src/infrastructure</a>: слой реализации доменного слоя (репозитории, модели и прочие элементы) 
    - /repositories: репозитории (конкретная реализация доменного слоя)
        - /entity
            - InMemoryEntityRepository.php
            - SqlEntityRepository.php
            - FileEntityRepository.php
</pre>

Здесь реализованы 3 вида репозитория: в памяти, sql и файловый.