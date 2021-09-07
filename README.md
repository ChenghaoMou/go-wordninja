# go-wordninja
## Getting Start
```bash
go get github.com/ChenghaoMou/go-wordninja
```

## Usage
```go
package main

import (
	"github.com/ChenghaoMou/go-wordninja"
	"fmt"
)

func main()  {
	// only English characters
	eng := "thisisatest"
	fmt.Println(wordninja.CutEnglish(eng))
	
	// multi characters
	mul := "this哈isa,test"
	fmt.Println(wordninja.Cut(mul))
}
```
## reference
> 1. https://stackoverflow.com/questions/8870261
> 2. https://github.com/keredson/wordninja
