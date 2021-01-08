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

func (avg human, genius human) finalResult() {
	fmt.Printf("This, %f, is the difference!", avg.potential() - genius.potential())
}

func main() {
	averageMahanth, geniusMahanth := &mahanth{1.01, 365}, &mahanth{1.03, 365}
	fmt.Println("Hello! I am Mahanth, an avid Mathematician and a Backend Programmer")
	fmt.Println("There is a saying. No matter how talented you may be, you will realize your potential,")
	fmt.Println("without putting in the time to experience what you have!")
	finalResult(averageMahanth, geniusMahanth)
	fmt.Println("Putting your efforts thoughtfully, will uncover who you really are and the things you are good at !")
}
```
