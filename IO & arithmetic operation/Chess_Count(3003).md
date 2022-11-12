<img src="https://user-images.githubusercontent.com/84216838/201454827-d9b5903c-9dd2-4d6b-bba5-ff360fdbd7dd.png" width= 700 height = 400 >

```
import java.util.*

fun main() {
    val array = intArrayOf(1,1,2,2,2,8)
    val sc = Scanner(System.`in`)
    
    for(i in array.indices){
        val num = sc.nextInt()
        val correct = array[i] - num
        println(correct)
    }
}
```