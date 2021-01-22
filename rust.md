## Variable

let
> define variable

```rust
let mut a:bool = false;
```

const
> define constant varible

```rust
const A:i32 = 7;
```

static
> define global varible

```rust
static B: i64 = 77;
```

## Variable Shadowing
```rust
let x: f64 = -20.48; // float
let x: i64 = x.floor() as i64; // int
println!("{}", x); // -21

let s: &str = "hello"; // &str
let s: String = s.to_uppercase(); // String
println!("{}", s) // HELLO
```

```rust

for i in 1..10 {} // for(i = 1; i < 10; i++)
for i in 1..=10 {} // for(i = 1; i <= 10; i++)

'outer: while true {
    'inner: while true {
        break 'outer;
    }

}



```

