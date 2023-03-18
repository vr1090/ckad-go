## types, method and interface
- types are executable documentation

```
type Katroer interface{
    // notice without func
    Apalah() string
}
``` 
- variable bisa di convert automatic to pointer
- tapi engga bisa kalau di passing ke function


```
var once sync.Once
once.Do ( func() {
    initFunction
})
```