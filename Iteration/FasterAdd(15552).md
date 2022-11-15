<img src="https://user-images.githubusercontent.com/84216838/201843971-e926500d-5abc-483a-a0cd-6521b9961daf.png" width=850 height = 500>

```
import java.io.*
import java.util.*

fun main () = with(BufferedReader(InputStreamReader(System.`in`))) {

    val w = BufferedWriter(OutputStreamWriter(System.out))
    
    for(i in 1 ..readLine().toInt()){
    	StringTokenizer(readLine()).run {
        	val a = nextToken().toInt()
            val b = nextToken().toInt()
            
            w.write("${a+b}\n")
          }
      }
   w.flush()
   w.close()
   close()
 }
```
- BufferwsReader & BufferedWriter : 입력된 데이터가 바로 전달되지 않고 Buffer를 거친 후 전달 되므로 Scanner보다 속도가 빠름
- readLine : 입력받은 값을 String으로 변환
- StringTokenizer : 공백을 기준으로 String을 나눔 