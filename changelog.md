### 0.2.5 TBA

 - **bug**: watchers response ack's could be delivered incorrectly when watching keys concurrently ([#33](https://github.com/mixer/etcd3/pull/33), [#30](https://github.com/mixer/etcd3/issues/30)) thanks to [@styleex](https://github.com/styleex)
 - **bug**: watchers not receiving events after reconnection in rare cases ([#33](https://github.com/mixer/etcd3/pull/33), [#31](https://github.com/mixer/etcd3/issues/31)) thanks to [@styleex](https://github.com/styleex)
 - **bug**: error thrown when the connection pool is drain / no servers are available ([#33](https://github.com/mixer/etcd3/pull/33), [#7](https://github.com/mixer/etcd3/issues/7)) thanks to [@SimonSchick](https://github.com/SimonSchick)

## 0.2.4 2017-08-02

 - **bug**: connections failing when an `https` prefix is provided ([#29](https://github.com/mixer/etcd3/pull/29)) thanks to [@jmreicha](https://github.com/jmreicha)
 - **bug**: connections failing when using SSL without a custom root cert ([#29](https://github.com/mixer/etcd3/pull/29)) thanks to [@jmreicha](https://github.com/jmreicha)
 - **feature**: throw a more meaningful error when using credentials without SSL ([#29](https://github.com/mixer/etcd3/pull/29))
 - **test**: run tests with Node 8 and etcd3.2 ([#27](https://github.com/mixer/etcd3/pull/27)) thanks to [@shakefu](https://github.com/shakefu)

## 0.2.3 2017-07-19

 - **bug**: fix being unable to set lock TTLs ([#26](https://github.com/mixer/etcd3/pull/26))

## 0.2.2 2017-07-10

 - **bug**: fix critical installation issue from 0.2.1 ([#23](https://github.com/mixer/etcd3/issues/23), [#24](https://github.com/mixer/etcd3/pull/24))
 - **chore**: update grpc to 1.4.x ([#24](https://github.com/mixer/etcd3/pull/24))

## ~~0.2.1 2017-07-10~~

 - **breaking**: `client.watch()` is now a function to construct high-level watchers ([#12](https://github.com/mixer/etcd3/pull/12))
 - **feature**: add namespacing capability ([#12](https://github.com/mixer/etcd3/pull/12))
 - **feature**: add high-level watchers ([#16](https://github.com/mixer/etcd3/pull/16))
 - **chore**: use [prettier](https://github.com/prettier/prettier) formatting for all code ([#16](https://github.com/mixer/etcd3/pull/18))

## 0.2.0 2017-06-03

 - **breaking**: return strings from `client.get()` and maps of strings from `client.getAll()` by default ([#6](https://github.com/mixer/etcd3/pull/6))
 - **breaking**: enums (which were not correctly typed in 0.1.x) have had their typings corrected and their capitalization has changed to UpperCameCase to align with TypeScript/JavaScript conventions ([#6](https://github.com/mixer/etcd3/pull/6))
 - **feature**: add transaction builder ([#4](https://github.com/mixer/etcd3/pull/4))
 - **feature**: add distributed locking ([#5](https://github.com/mixer/etcd3/pull/5))
 - **feature**: add support for password auth, TLS, client credentials ([#11](https://github.com/mixer/etcd3/pull/11))
 - **feature**: add high-level role management structures ([#11](https://github.com/mixer/etcd3/pull/11))
 - **bug**: fix enum typings being incorrect ([#11](https://github.com/mixer/etcd3/pull/11))
 - **doc**: update URLs in the readme and package.json

## 0.1.2 2017-04-13

 - **bug**: fix files being incorrectly ignored in the npm package

## 0.1.1

 - Initial release
