<img src="https://user-images.githubusercontent.com/84216838/201456443-a5e5d4e2-bd61-43b8-b523-27cbfa8166ab.png" width=700 height = 450>

```
import java.util.*

fun main() {
    val sc = Scanner(System.`in`)
    
        val a = sc.nextInt()
        val b = sc.nextInt()
        val c = sc.nextInt()

        println((a+b)%c)
        println(((a%c)+(b%c))%c)
        println((a*b)%c)
        println(a%c*(b%c)%c)
}
```