# golang-quiz
simple golang questions

```go
package main

import "fmt"

func hello(p ...int){
	if p==nil {
	  fmt.Println("nil")
	  return
	}
	fmt.Println("not nil")
}

func main() {	
   hello()
}
```

answer options

```bash
- nil
- not nil
- compilation error
- 5
```


<details>
<summary> click show answer </summary>
<p>
	
```bash
- nil
```

</p>
</details>

***



```go
package main

import "fmt"

func main() {
	i := 0 
	_,i = 5,8
	fmt.Println(i)
}
```

answer options

```bash
- runtime panic
- 8
- compilation error
- 5
```


<details>
<summary> click show answer </summary>
<p>
	
```bash
- 8
```

</p>
</details>

***


```go
package main

import "fmt"

func main() {
	 
	s := make(map[string]int)
	delete(s,"h")
	fmt.Println(s["h"])
}
```

answer options

```bash
- runtime panic
- 0
- compilation error
```


<details>
<summary> click show answer </summary>
<p>
	
```bash
- 0
```

</p>
</details>


***

```go
package main

import "fmt"

func main() {
	fmt.Printf("%%")
}
```

answer options

```bash
- 0.0
- compilation error
- %
- %%
```


<details>
<summary> click show answer </summary>
<p>
	
```bash
- %
```

</p>
</details>


***

```go
package main

import "fmt"

func hello(i int) {
	fmt.Println(i)
}

func main() {
	i := 5
	defer hello(i)
	i = i + 10
}

```

answer options
```bash
- 5
- 15
- 0
```

<details>
<summary> click show answer </summary>
<p>
	
```bash
- 5
```

</p>
</details>

 
***


```go
package main

import "fmt"

func main() {

	var i interface{}

	if i == nil {
		fmt.Println("nil")
		return
	}
	
	fmt.Println("not nil")
	
}

```

<details>
<summary> click show answer </summary>
<p>

```bash
- nil
```
</p>
</details>

***

```go
package main

import "fmt"

func main() {
	a := 5
	b := 8.1
	fmt.Println(a+b) 	
}
```
answer options
```bash
- 13.1
- 13
- compilation error
```
<details>
<summary> click show answer </summary>
<p>

```bash
- compilation error
```
</p>
</details>
