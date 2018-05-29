bootstrap-table-examples
======================

[Bootstrap Table Examples](http://issues.wenzhixin.net.cn/bootstrap-table)

[jsFiddle Examples](https://github.com/wenzhixin/bootstrap-table-examples/blob/master/jsfiddle_examples.md)

[CRUD Example](https://github.com/wenzhixin/bootstrap-table-examples/blob/master/crud/README.md)

## Usage

### clone & init

```sh
git clone https://github.com/wenzhixin/bootstrap-table-examples.git
cd bootstrap-table-examples
git submodule update --init

npm install
```

### download from zip

* Download [bootstrap-table-examples](https://github.com/wenzhixin/bootstrap-table-examples/archive/master.zip)
* Download [bootstrap-table](https://github.com/wenzhixin/bootstrap-table/archive/master.zip), unzip to `assets/bootstrap-table`
* Download [multiple-select](https://github.com/wenzhixin/multiple-select/archive/master.zip), unzip to `assets/multiple-select`

```
cd bootstrap-table-examples
npm install
```

## run

```sh
node app
```

## reporting issues

All issues need to be submitted to the main project, not this examples repo.

Please read: https://github.com/wenzhixin/bootstrap-table/blob/develop/CONTRIBUTING.md#bug-reports
and post issue to: https://github.com/wenzhixin/bootstrap-table/issues, thanks!


>注意
一、如果直接下载 要[boostrap-table-examples] [bootstrap-table] [multiple-select] 一起都下载了，然后把[bootstrap-table] 解压放入`assets/bootstrap-table`中，[multiple-select]解压放入`assets/multiple-select`中去，
二、`node app` 之后，会cmd中会出现```http://:::3000 ```切记，并非直接打开http://:::3000，需 先搭建本地环境，打开localhost，监听3000，正确打开是`localhost:3000`

