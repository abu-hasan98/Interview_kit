# Hands-On Coding
# Swift
## Filter Odd Numbers:

```swift
Copy
func filterOddNumbers(_ numbers: [Int]) {
    let oddNumbers = numbers.filter { $0 % 2 != 0 }
    print(oddNumbers)
}
```

### Mutating Function:


```swift
Copy
struct Stack {
    var numbers = [1, 2, 3]

    mutating func append(_ number: Int) {
        numbers.append(number)
    }
}

var intStack = Stack()
intStack.append(4)
print(intStack.numbers)
```

### Equatable Protocol:
```swift
Copy
struct User: Equatable {
    let firstName: String
    let lastName: String

    static func == (lhs: User, rhs: User) -> Bool {
        return lhs.firstName == rhs.firstName && lhs.lastName == rhs.lastName
    }
}
```
