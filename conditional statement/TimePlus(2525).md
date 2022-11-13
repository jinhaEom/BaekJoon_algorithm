<img src="https://user-images.githubusercontent.com/84216838/201507900-8181b238-50f1-483c-a546-c699ed5ed1d8.png" width= 700 height= 400>

```
import java.util.*

fun main() = with(Scanner(System.`in`)) {
    var (h, m) = Pair(nextInt(), nextInt())
    val cookingTime = nextInt()
    
    if (m + cookingTime >= 60) {
        val plusHour = (m + cookingTime) / 60
        m = (m + cookingTime) % 60
        if (h + plusHour >= 24) {
            h = (h + plusHour) % 24
        } else {
            h += plusHour
        }
    } else {
        m += cookingTime
    }
    
    println("${h} ${m}")
}
```