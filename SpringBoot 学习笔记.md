# SpringBoot 学习笔记

## 1.Restful 编写方式

使用PostMapping("/emp")，GetMapping

``` java
@GetMapping("/emp/{id}")
public String toEditPage(@PathVariable("id") Integer id){
}
```

## 设置属性



```htm
<button th:attr="del_uri=@{/emp/}+${emp.id}"></button>
```



