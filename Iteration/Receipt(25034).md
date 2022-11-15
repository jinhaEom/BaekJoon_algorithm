<img src="https://user-images.githubusercontent.com/84216838/201838012-ebda7298-9293-4de9-9258-ce33832f989a.png" width=700 height= 400>

```
import java.util.*

fun main(){
    val sc = Scanner(System.`in`)
    
    var total = sc.nextInt()
    val count = sc.nextInt()
    
    for(i in 1..count){
        var price = sc.nextInt()
        var num = sc.nextInt()
        
        total = total-(price*num)
    }
    if(total == 0){
        println("Yes")
    }else{
        println("No")
    }
}
```