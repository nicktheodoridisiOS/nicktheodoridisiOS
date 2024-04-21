### aboutme.swift

> Write a Swift struct that serves as a template for a personal biography. This struct should encapsulate personal details and include a method to display a formatted biography. The details should be set upon initialization and should be read-only from outside the struct.

```swift
struct Developer {

  let firstName = "Nick"
  let lastName = "Theodoridis"
  let role = "iOS Developer"
  let age = 22
  let location = "Greece 🇬🇷"
  let languages = ["el_GR", "en_US"]
  let skills = ["Swift", "Flutter"]
  
  func exploreMyAccount() {
    print("Hey, thanks for visiting, feel free to explore my work!")
  }

}

let me = Developer()
me.exploreMyAccount()
```
