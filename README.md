### Hi there! I'm Austin!

![Visitors](https://visitor-badge.laobi.icu/badge?page_id=riigess.riigess)

- I’m currently learning about low-level system design.
- I’m looking for help with learning more about Objective-C and C++ development. Looking for communities to join for iOS, macOS, and kernel-level development.
- Looking for cool opportunities to build something awesome. I'm not about that HomeLab life, but I do want to prevent society from using excessively more power than we need to. (Limited resources, environmentalism, and all that.)
- Pronouns: he/him, open to they/them

### A little more about me...
```swift
enum PlatformPreference: String {
    case Desktop = "Desktop"
    case Mobile = "Mobile"
    case ALL = "ALL"
}

enum PlatformChooser: String {
    case Mac = "Darwin"
    case Windows = "NT"
    case Linux = "Linux" // 🐧
}

extension String {
    func fromBase64() -> String? {
        guard let data = Data(base64Encoded: self) else {
            return nil
        }
        return String(data: data, encoding: .utf8)
    }
}

enum DevOpsTools {
    case AWS, Azure, DigitalOcean, GCP
    case Docker, containerd, Colima, Apple/Container
    case k8s, k3s
}

struct SoftwareEngineer {
    let name = "Austin"
    let progammingLanguages = [ "Python", "Java", "Kotlin", "Swift" ] //Learning Objective-C, C, and C++
    let developmentPreference:PlatformPreference = .ALL
    let platformDevPreference:[PlatformChooser] = [ .Mac, .Linux]
    let tools:String = String("WyJWU0NvZGUiLCAiUHVsc2FyIiwgIlplZCIsICJYY29kZSIsICJEb2NrZXIiXQ==").fromBase64()!
    // tools = "[\"VSCode\", \"Pulsar\", \"Zed\", \"Xcode\", \"Docker\"]"

    let devOpsToolsUsed:DevOpsTools = [.AWS, .Azure, .DigitalOcean, .GCP, .Docker, .Colima]
}

let swe_self = SoftwareEngineer()
print("Hello! I'm \(swe_self.name)!")
print("I'm learning C and C++, focusing on working with Python and Swift currently.")
print("I currently use \(swe_self.tools), and would love to find new tools to use.") 
```

## Technologies & Tools
Preferred OSes/Distros: 
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?logo=ubuntu&logoColor=white)
![iOS](https://img.shields.io/badge/iOS-000000?&logo=apple&logoColor=white)
![macOS](https://img.shields.io/badge/macOS-000000?logo=apple&logoColor=F0F0F0)

Editors: 
![IntelliJ IDEA](https://img.shields.io/badge/IntelliJIDEA-000000.svg?logo=intellij-idea&logoColor=white)
![V S Codium](https://img.shields.io/badge/VSCodium-2F80ED?logo=vscodium&logoColor=fff)
![Xcode](https://img.shields.io/badge/Xcode-007ACC?logo=Xcode&logoColor=white)

Languages: 
![JSON](https://img.shields.io/badge/JSON-000?logo=json&logoColor=fff)
![Kotlin](https://img.shields.io/badge/Kotlin-%237F52FF.svg?logo=kotlin&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=fff)
![Swift](https://img.shields.io/badge/Swift-F54A2A?logo=swift&logoColor=white)

Other Tools / Technologies: 
![MariaDB](https://img.shields.io/badge/MariaDB-003545?logo=mariadb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=fff)
![Postgres](https://img.shields.io/badge/Postgres-%23316192.svg?logo=postgresql&logoColor=white)
![Slack](https://img.shields.io/badge/Slack-4A154B?logo=slack&logoColor=fff)
![SQLite](https://img.shields.io/badge/SQLite-%2307405e.svg?logo=sqlite&logoColor=white)
