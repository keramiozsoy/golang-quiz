# golang-quiz
simple golang questions


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
