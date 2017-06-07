
安装：
docker pull tomaka/android-rs-glue
使用：
docker run --rm -v <path-to-local-directory-with-Cargo.toml>:/root/src tomaka/android-rs-glue
cargo apk
当前目录:
docker run --rm -v `pwd`:/root/src -w /root/src tomaka/android-rs-glue cargo apk

url: https://hub.docker.com/r/tomaka/android-rs-glue/
