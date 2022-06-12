# SwiftUI-FAB (Floating Action Button)
[![CI](https://github.com/karamage/SwiftUI-FAB/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/karamage/SwiftUI-FAB/actions/workflows/main.yml)
[![Release](https://img.shields.io/github/v/release/karamage/SwiftUI-FAB)](https://github.com/karamage/SwiftUI-FAB/releases/latest)
[![License](https://img.shields.io/github/license/karamage/SwiftUI-FAB)](https://github.com/karamage/SwiftUI-FAB/blob/main/LICENSE)
[![Twitter](https://img.shields.io/twitter/follow/kara_mage?style=social)](https://twitter.com/kara_mage)

Floating Action Button(FAB) with SwiftUI.

<img src="https://user-images.githubusercontent.com/330715/173220298-6e1795f0-398c-41f4-ab7d-42e449bb0524.gif" width="250" />

## Install

### SwiftPM
```
https://github.com/karamage/SwiftUI-FAB.git
```

## Usage
```Swift
import SwiftUI
import SwiftUI_FAB

struct ExampleScreen: View {
    var body: some View {
        NavigationView {
            VStack {
                Text("Floating Action Button(FAB) with SwiftUI")
            }
            .floatingActionButton(color: Color.blue, image: Image(systemName: "plus").foregroundColor(.white)) {
                // action
                print("Tap Button")
            }
            .navigationTitle("Sample")
            .navigationBarTitleDisplayMode(.inline)
        }
    }
}
```

