# 코드이그나이터4 정리

## 설치

```bash
composer create-project codeigniter4/appstarter project-root
```

## spark 도움말

spark 명령어

```bash
php spark
```

spark 개별 명령어

```bash
php spark help [<command_name>]
php spark help make:controller
```

## 컨트롤러 생성

```bash
php spark make:controller <name> [options]
php spark make:controller UserController
php spark make:controller UserController --restful
php spark make:controller Folder/UserController

```
