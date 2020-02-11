# todoListApi
- Node.js RESTful API

## Reference
- <https://www.codementor.io/@olatundegaruba/nodejs-restful-apis-in-10-minutes-q0sgsfhbd>

## Spec
- node
```cmd
C:\Users\7040_64bit>node -v
v12.14.0
```

- npm
```cmd
C:\Users\7040_64bit>npm -version
6.13.4
```

- mongoDB
환경 변수 - Path에 {MongoDB_설치경로}/bin 등록

```cmd
C:\Users\7040_64bit>mongo --version
MongoDB shell version v4.2.3
git version: 6874650b362138df74be53d366bbefc321ea32d4
allocator: tcmalloc
modules: none
build environment:
    distmod: 2012plus
    distarch: x86_64
    target_arch: x86_64
```

## Dependencies
```bash
$ npm install --save-dev nodemon
```

```bash
$ npm install express --save
```

```bash
$ npm install mongoose --save
```

## Run
```cmd
C:\Users\7040_64bit>mongod
2020-02-11T10:23:05.535+0900 I  CONTROL  [main] Automatically disabling TLS 1.0, to force-enable TLS 1.0 specify --sslDisabledProtocols 'none'
2020-02-11T10:23:05.543+0900 I  CONTROL  [initandlisten] MongoDB starting : pid=20508 port=27017 dbpath=C:\data\db\ 64-bit host=dhyang02PC
2020-02-11T10:23:05.543+0900 I  CONTROL  [initandlisten] targetMinOS: Windows 7/Windows Server 2008 R2
2020-02-11T10:23:05.544+0900 I  CONTROL  [initandlisten] db version v4.2.3
2020-02-11T10:23:05.544+0900 I  CONTROL  [initandlisten] git version: 6874650b362138df74be53d366bbefc321ea32d4
2020-02-11T10:23:05.545+0900 I  CONTROL  [initandlisten] allocator: tcmalloc
2020-02-11T10:23:05.546+0900 I  CONTROL  [initandlisten] modules: none
2020-02-11T10:23:05.547+0900 I  CONTROL  [initandlisten] build environment:
2020-02-11T10:23:05.547+0900 I  CONTROL  [initandlisten]     distmod: 2012plus
2020-02-11T10:23:05.548+0900 I  CONTROL  [initandlisten]     distarch: x86_64
2020-02-11T10:23:05.549+0900 I  CONTROL  [initandlisten]     target_arch: x86_64
2020-02-11T10:23:05.551+0900 I  CONTROL  [initandlisten] options: {}
2020-02-11T10:23:05.560+0900 I  STORAGE  [initandlisten] exception in initAndListen: NonExistentPath: Data directory C:\data\db\ not found., terminating
2020-02-11T10:23:05.560+0900 I  NETWORK  [initandlisten] shutdown: going to close listening sockets...
2020-02-11T10:23:05.562+0900 I  -        [initandlisten] Stopping further Flow Control ticket acquisitions.
2020-02-11T10:23:05.563+0900 I  CONTROL  [initandlisten] now exiting
2020-02-11T10:23:05.565+0900 I  CONTROL  [initandlisten] shutting down with code:100
```

```bash
$ npm run start
```
