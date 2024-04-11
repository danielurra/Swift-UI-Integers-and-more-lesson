# SwiftUI Integers and more lesson
Swift UI Integers and more lesson

![Screenshot 2024-04-11 at 5 20 19 AM](https://github.com/danielurra/Swift-UI-Integers-and-more-lesson/assets/51704179/587a9638-da3e-433e-986c-749073e1012f)
## Grab the code
```swift
// Integers
var temperature: Int = 85
var someInt = 70

var signedInt01 = 10
var signedInt02 = 0
var signedInt03 = -5

var unSignedInt01 = 0
var unSignedInt02 = 5 // it has no getative sign

/*
 Swift provides signed and unsigned integers in 8, 16, 32, and 64 bit forms.
 An 8-bit unsigned integer is of type UInt8, and
 A 32-bit signed integer is of type Int32
 */

// helpful properties that allow you so know the min and max value of each
let minValue = UInt8.min
let maxValue = UInt8.max

let miniValue = UInt16.min
let maxiValue = UInt16.max

let minimValue = UInt32.min
let maximValue = UInt32.max

let minimumValue = UInt64.min
let maximumValue = UInt64.max

// Floats
var pi: Float = 3.14
var otherFloat: Float = -23.45

/*
 Double has a precision of at least 15 decimal digits, whereas the precision of Float
 can be as little as 6 decimal digits.
 */

// Double (just use Double most of the time)
var someBigNumber: Double = 43543554365463.56

// Conversions
/*
 You can not add/substract/etc different types together
 */
let three = 3 // infered type Integer
let fraction = 0.14159 // infered type Double

//let sumadosFormanPiError = three + fraction --- ERROR different types can not be added!!!!

let sumadosFormanPiOK = Double(three) + fraction // joya!

// Float convetion to an Integer must also be Explicit

let parteEnteraDePi = Int(sumadosFormanPiOK)

// Booleans

let isSunny = true
let isRaining = false

let isSnowing: Bool = false

/*
 Booleans are pretty useful when working with conditional statements (e.g. IF)
 */

if isSunny {
    print("Beach day!")
} else {
    print("Catch up on some reading")
}
```
