# USER-PROJECT

##   Базовые сущности Кubernetes: Service, Ingress

#### Endpoint curl http://arch.homework/user

- Развертывание из каталога \otus_users\helm\. Манифесты развертываются в namespace user

      helm -n user upgrade --install --create-namespace user .
- Удаление развернутых ресурсов

      kubectl delete namespace user
- Проверить можно с помощью Postman (user_api.json)

