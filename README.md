# Wechat linux native arm64



```
gcc -shared -fPIC activation.c -o libactivation.so -ldl
sudo install -Dm644 libactivation.so -t /usr/lib
```
