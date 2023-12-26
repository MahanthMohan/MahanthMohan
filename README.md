``` go
package main

import (
	"fmt"
	"math"
)

type human interface {
	potential() float32		
}

type mahanth struct {
	time float32
	duration float32
}

func (m mahanth) potential() float32 {
	return Math.Pow(m.time, m.duration)
}

func (avg human, doer human) finalResult() {
	fmt.Printf("This, %f, is the difference!", doer.potential() - avg.potential())
}

func main() {
	mahanth1, mahanth2 := mahanth{1.01, 365}, mahanth{1.03, 365}
	fmt.Println("Hello! I am Mahanth, an avid Mathematician and a Backend Programmer")
	fmt.Println("There is a saying. You only realize your true potential")
	fmt.Println("only when you start doing things.")
	finalResult(mahanth1, mahanth2)
}
```
