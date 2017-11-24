[![Build Status](https://travis-ci.org/n0k8t/lab10.svg?branch=master)](https://travis-ci.org/n0k8t/lab13)
## Laboratory work XIII

### Задание

Написать программы на **C++** для сериализации и десериализации структуры `Person`.

Структура `Person` определяется следующим образом:

```cpp
struct Email {
  std::string nickname;
  std::string server;
};

struct Person {
  std::string  first_name;
  std::string  last_name;
  Email        email;
  size_t       age;
  std::string  phone;
};
```
