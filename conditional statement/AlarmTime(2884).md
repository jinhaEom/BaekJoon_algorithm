<img src="https://user-images.githubusercontent.com/84216838/201507245-10c01dc1-d40c-4dc2-bba3-eb04ba0056ad.png" width=700 height=400>

```
import java.util.*
import java.time.LocalTime

fun main() {
    val sc= Scanner(System.`in`)
    val hour = sc.nextInt()
    val minute = sc.nextInt()
    
   val time = LocalTime.of(hour,minute).minusMinutes(45)
    
    print("${time.hour} ${time.minute}")
}
```