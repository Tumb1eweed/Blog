# typeid().name()

可以用`c++filt -t`转成human-readable的形式[^1]，比如：

```shell
c++filt -t m
unsigned long
```

[^1]: [std::type_info::name - cppreference.com](https://en.cppreference.com/w/cpp/types/type_info/name)
