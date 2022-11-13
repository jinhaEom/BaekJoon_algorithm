<img src="https://user-images.githubusercontent.com/84216838/201506824-22d42106-f86e-423c-8540-a78d3f51b840.png" width=700 height=500>

```
import java.util.*

fun main() {
    val sc = Scanner(System.`in`)
    
    val a= sc.nextInt()
    val b= sc.nextInt()
    val q = intArrayOf(1,2,3,4)
    if(a>0 && b>0){
        println(q[0])
    }else if(a<0 && b>0){
        println(q[1])
    }else if(a<0 && b<0){
        println(q[2])
    }else{
        println(q[3])
    }
}
```