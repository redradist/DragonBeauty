All syntax is inspired by Python and Rust and C++ ;)

Example of syntax:
```
#[feature:static] Staticly Typed feature of language
#[feature:dynamic] Dynamicly Typed feature of language
#[feature:unsafe] Unsafe feature of language
#[feature:library:no-std] For Micro Controllers, only libcore is supported
#[feature:memory:no-gc] No Garbage Collector
#[feature:language:python]
#[feature:language:javascript]
#[feature:language:typescript]

fun some_function()

empty_var? = None

fun some_function2()

type Integer
    fun __add__(self)
    
    fun __sub__(self)


open class Object
	unsafe from "python@os" import read
	fun __init__(self)

	fun __init__(self)


extend Object
	unsafe from "javascript@./cool-library" import cool
	unsafe from "typescript@https://deno.ts" import deno
	fun new_method(self)

	fun two(self)


let x = 8
Object.new_func = fun () # Lambda function
	return x


Object() # Value based object creation

unsafe stack 2424 # Allocate Stack Buffer
unsafe stack[global] 2424 # Allocate Stack Buffer available cross Multi-Thread-s

unsafe alloc 2424 # Buffer allocation
unsafe alloc[global] 2424 # Allocate Buffer available cross Multi-Thread-s

alloc Object() # Reference counting
alloc[global] Object() # Multi-Thread Reference counting

new Object() # new Object(), Garbage Collector
new[global] Object() # Multi-Thread Garbage Collector

obj = new Object() # new Object(), Garbage Collector
new[global] Object() # Multi-Thread Garbage Collector

pub enum Token
	Keyword: str,


pub fun postive()
	return n >= 0


pub fun postive(n)
	return n >= 0


pub fun postive(ref n, t)
	return *n >= 0


pub coro fun !fib(n: int) -> value0:Iterator[int], value1:int; CustomError
    check positive: postive(n)

    raise CustomError()
    let name
    a, b = 0, 1
    while a < n
    	await sfsas
        yield a
        a, b = b, a + b


fun __main__()
	return 8

a, b = 0, 1
```
