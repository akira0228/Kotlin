# Kotlin
코틀린을 공부하며 기록하기

👋 Kotlin Basic 함수 선언 방법

```jsx
fun main() {
val kotlin = "🙂"
val test = 1
val test2 = 3
println(kotlin)
println(test)
println(test2)
println(test+test2)

println("1과 10중 최댓값은 ${maxOf(1,10)}입니다.");
//함수 선언1
println("함수 선언 방법 1번 결과값 : ${sum(10,20)}")
//함수 선언2
println("함수 선언 방법 2번 결과값 : ${sum2(5,3)}")

}
//함수 선언방법 1
fun sum(a:Int, b:Int): Int {
return a + b
}
//함수 선언방법 2
fun sum2(a: Int, b: Int) = a + b
```
