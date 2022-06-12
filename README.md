# SwiftUI-FAB (Floating Action Button)
[![CI](https://github.com/karamage/SwiftUI-FAB/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/karamage/SwiftUI-FAB/actions/workflows/main.yml)
[![Release](https://img.shields.io/github/v/release/karamage/SwiftUI-FAB)](https://github.com/karamage/SwiftUI-FAB/releases/latest)
[![License](https://img.shields.io/github/license/karamage/SwiftUI-FAB)](https://github.com/karamage/SwiftUI-FAB/blob/main/LICENSE)
[![Twitter](https://img.shields.io/twitter/follow/kara_mage?style=social)](https://twitter.com/kara_mage)

Floating Action Button(FAB) with SwiftUI.

<img width="385" alt="Screen Shot 2022-06-12 at 11 24 21" src="https://user-images.githubusercontent.com/330715/173212044-c0b4b0b5-4416-4845-824d-f39f6b499ead.png">

## Install

### SwiftPM
```
https://github.com/karamage/SwiftUI-FAB.git
```

## Usage
```
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

