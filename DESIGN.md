# .slt file
### function define
```text
fn ident1(param1 type1, param2 type2) type3 {}
fn ident2() (type3, typ4) {}
```

### variable declare
```text
var ident1 type1;
```

### variable define
```text
var ident1 type1 = variable1;
var ident2 = variable2;
ident3 := variable3;
```

### use
```text
use ident1 "github.com/user/repo1";
```

# type
## primitive type
- bool
- string
- int64
- float64
- list
- dict
## ?
- any
- struct
- error(struct)




# header file
### function declare
```text
decl fn ident1( param1 type1, param2 type2 ) -> type3;
decl fn ident2() -> (type3, typ4);
```
### variable declare
```text
var ident1 typ1;
```