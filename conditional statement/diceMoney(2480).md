<img src="https://user-images.githubusercontent.com/84216838/201649943-6a6a7aa6-e6f7-49e5-89f7-a21088bceef2.png" width= 700 height = 400>

```
import java.util.*
import java.math.*
fun main() {
    val sc = Scanner(System.`in`)
    
    val one= sc.nextInt()
    val two = sc.nextInt()
    val three = sc.nextInt()
    
    val number = listOf(one,two,three)
    
    if(one==two && two==three){
        println(10000+one*1000)
    }else if(one==two && two!=three){
        println(1000+one*100)
    }else if(one==three && two != three){
        println(1000+one*100)
    }else if(one!=two && two==three){
        println(1000+three*100)
    }else if(one!=two && two!=three && three!=one){
        println(Collections.max(number)*100)
    }
}

```