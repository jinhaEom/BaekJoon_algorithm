<img src="https://user-images.githubusercontent.com/84216838/202214430-11271a7c-d2e1-4c0c-9619-cdd11db4ca07.png" width=700 height=500>

```
import java.util.*

fun main(args: Array<String>) {
    val sc = Scanner(System.`in`)

    val num = sc.nextInt()
    val array = IntArray(num)
    if (num in 1..1000000) {
        for (i in 0 until num) {
            array[i] = sc.nextInt()
        }
    }

   println("${min(array)} ${max(array)}")
}

fun max(array: IntArray): Int {
    var max = array[0]

    for (i in array.indices) {
        if (max < array[i]) {
            max = array[i]
        }
    }

    return max
}

fun min(array: IntArray): Int {
    var min = array[0]

    for (i in array.indices) {
        if (min > array[i]) {
            min = array[i]
        }
    }

    return min
}
```