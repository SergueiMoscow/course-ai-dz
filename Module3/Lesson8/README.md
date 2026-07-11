В качестве субагента решил добавить анализатора web страниц.
Для этого создал отдельный сценарий, который прпнимает на вход url и запрос от основного агента.
## Тестирование субагента
### Параметры запроса
![img](img/01-test-subagent-prompt.png)

### Ответ субагента
![img](img/02-test-subagent-response.png)

## Тестирование из телеграм
### Как отработал агент
![img](img/03-agent-calls-subagent.png)

### Промпт субагенту
![img](img/04-subagent-prompt.png)

### Ответ субагента
![img](img/05-subagent-response.png)

### Результат в телеграм
![img](img/06-result-in-telegram.png)