Alpha Vantage BBB4DAOMC7P538MQ

# Введение

## Клиент-сервер. HTTP. REST API. SOAP

---

## Клиент-сервер

![Клиент-сервер](images/1/1-1.png)

---

## Клиент-сервер

![Клиент-сервер](images/1/1-2.png)

---

## Клиент-сервер

![Клиент-сервер](images/1/1-3.png)

---

## Клиент-сервер

![Клиент-сервер](images/1/1-4.png)

---

## Клиент-сервер

![Клиент-сервер](images/1/1-5.png)

---

## HTTP

Протоколы | Уровень
--- | ---
HTTP, DNS, DHCP, FTP | Уровень приложений
TCP, UDP | Транспортный уровень
IPv4, IPv6, ICMPv4, ICMPv6 | Межсетевой уровень
PPP, Frame Relay, Ethernet | Уровень сетевого доступа

---

## HTTP
<!-- ![Alt text](image-1.png) -->
```html
<html lang="ru">
    <head>
        <meta charset="utf-8" />
        <title>Документ без названия<title>
    </head>
    <body>Контент</body>
</html>
```

---

## HTTP

<!-- ![Alt text](image-2.png) -->
### 1. Тексты
### 2. Файлы
### 3. html/xml/json

---

## HTTP

<!-- ![Alt text](image-3.png) -->
Пример запроса:
```http
POST /login HTTP/1.0
Host: example.com
Content-Type: application/x-www-form-urlencoded; charset=utf-8
Content-Length: 26
{
    login=use
    password=qwerty
}
```

---

## HTTP

<!-- ![Alt text](image-4.png) -->

Пример запроса:

<table>
<tr>
<td>
Стартовая строка (Starting line)
</td>
<td>

```http
POST /login HTTP/1.0
```
</td>
</tr>
<tr>
<td>
Заголовки (Headers)
</td>
<td>

```http
Host: example.com
Content-Type: application/x-www-form-urlencoded; charset=utf-8
Content-Length: 26
```
</td>
</tr>
<tr>
<td>
Тело сообщения (Body)
</td>
<td>

```http
{
 login=use
 password=qwerty
}
```
</td>
</tr>
<table>
