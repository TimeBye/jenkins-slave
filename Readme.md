# Jenkins-slave

## 构建

```
docker build -t jenkins-slave .
```

## 使用

- 环境变量
    - `TZ`: 时区
    - `ROOT_PASSWORD`: root用户密码

- 运行

    ```
    docker run -d --name jenkins-slave -e ROOT_PASSWORD=root setzero/jenkins-slave:latest
    ```