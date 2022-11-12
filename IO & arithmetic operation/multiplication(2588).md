<img src="https://user-images.githubusercontent.com/84216838/201457130-7bf50f27-bb34-4c96-b3be-e845368d9978.png"  width=650 height= 400>

```
import java.util.Scanner

fun main() = with(Scanner(System.`in`)){
    
    var a = nextInt()
    var b = next()
    
    println(a * (b[2] - '0'))
    println(a * (b[1] - '0'))
    println(a * (b[0] - '0'))
    println(a * b.toInt())
    
}
```
- -0을 해주는 이유는 아스키코드값이 아닌 실제숫자값을 보기 위해 