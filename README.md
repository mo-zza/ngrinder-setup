# nGrinder Setup

## 1. Set environment file

### 1-1. Copy .env.example to .env

```shell
$ cp .env.example .env
```

### 1-2. Set environment variables in .env file

```shell
# .env
TZ=Asiz/Seoul
PORT=9090
AGENT_PORT=16001
```

## 2. Run docker-compose

```shell
$ docker-compose up -d
```

## 3. Access to nGrinder

### 3-1. Access to nGrinder controller

| key | value                 | description                      |
|-----|-----------------------|----------------------------------|
| URL | http://localhost:9090 | nGrinder web controller endpoint |
| ID  | admin                 | nGrinder default username        |
| PW  | admin                 | nGrinder default password        |
