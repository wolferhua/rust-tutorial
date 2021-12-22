# rust学习第一天

> 想它、想它、想它……哈哈。


今天我们需要学会安装和使用rust写一个`你好，rust！`的程序。

## 安装rust

rust安装炒鸡简单，一条命令就可以了。

```shell

# 执行安装

curl --proto '=https' --tlsv1.2 https://sh.rustup.rs -sSf | sh



# 验证安装情况
cargo version 
# cargo 1.53.0 (4369396ce 2021-04-27)

rustc -V
#rustc 1.53.0 (53cb7b09b 2021-06-17)


rustup show   
#Default host: x86_64-apple-darwin
#rustup home:  /Users/wolferhua/.rustup
#
#stable-x86_64-apple-darwin (default)
#rustc 1.53.0 (53cb7b09b 2021-06-17)

# 升级rust
rustup update 
```




## 你好, rust!

### 创建项目

#### 项目不存在
```shell
cargo new day001

# 项目目录
#.
#├── Cargo.toml
#└── src
#    └── main.rs

```


#### 项目目录已经存在
```shell
# 进入项目目录 
cd day001
# 初始化项目
cargo init

# 项目目录
#.
#├── Cargo.toml
#└── src
#    └── main.rs

```


### 运行项目

```bash
cargo run 
#   Compiling day001 v0.1.0 (path/to/rust-tutorial/day001)
#    Finished dev [unoptimized + debuginfo] target(s) in 2.75s
#     Running `target/debug/day001`
#Hello, world!

```


