
# Wingive


## basics of Kotlin.
/**fun main() {
    println("Hello, world!!!")*/

/*fun main() {
    println("Tuesday")
    println("Thursday")
    println("Wednesday")
    println("Friday")
    println("Monday")
}*/

// use of variable;


/*fun main() {
    val notificationsEnabled: Boolean = true
    println(notificationsEnabled)
}*/

/*fun main() {
    val notificationsEnabled: Boolean = false
    println("Are notifications enabled? " + notificationsEnabled)
}*/

// Calling a function

/*fun main() {
    birthdayGreeting()
}

fun birthdayGreeting() {
    println("Happy Birthday, Rover!")
    println("You are now 5 years old!")
}*/

/*fun birthdayGreeting(name: String): String {
    val nameGreeting = "Happy Birthday, $name!"
    val ageGreeting = "You are now 5 years old!"
    return "$nameGreeting\n$ageGreeting"
}


fun main() {
    println(birthdayGreeting("Rover"))
}*/


// define multiple parameter to a function

/*fun birthdayGreeting(name: String, age: Int): String {
    val nameGreeting = "Happy Birthday, $name!"
    val ageGreeting = "You are now 5 years old!"
    return "$nameGreeting\n$ageGreeting"
}*/

/*fun birthdayGreeting(name: String, age: Int): String {
    val nameGreeting = "Happy Birthday, $name!"
    val ageGreeting = "You are now $age years old!"
    return "$nameGreeting\n$ageGreeting"
}*/

/*fun main() {
    println(birthdayGreeting("Rover", 5))
    println(birthdayGreeting("Rex", 2))
}*/

/*fun birthdayGreeting(name: String = "Rover", age: Int): String {
    return "Happy Birthday, $name! You are now $age years old!"
}

println(birthdayGreeting(age = 5))
println(birthdayGreeting("Rex", 2))
println(birthdayGreeting(age = 5))
println(birthdayGreeting(age = 2))*/


