# Сервис авторизации на Spring Boot

## 📋 Описание задачи

Реализовать сервис авторизации пользователей по логину и паролю с обработкой 
ошибок через `@ExceptionHandler`:
- **`InvalidCredentials`** → HTTP **400 Bad Request** + сообщение из исключения.
- **`UnauthorizedUser`** → HTTP **401 Unauthorized** + сообщение из исключения 
  + лог в консоль.

## 🎯 Цель

Отработать:
- Создание REST-сервиса на Spring Boot;
- Работу с `@RestController`, `@Service`, `@Repository`;
- Собственные исключения и их обработку через `@ExceptionHandler`;
- Возврат корректных HTTP-статусов при ошибках.

## 🛠️ Используемые технологии

- Java 17+
- Spring Boot
- Spring Web (`@RestController`, `@GetMapping`, `@RequestParam`)
- Spring Context (`@Service`, `@Repository`, `@Component`)
- `@ExceptionHandler` для обработки исключений
- Maven / Gradle
