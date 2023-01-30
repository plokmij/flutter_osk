# flutter_osk_x

A package to show/hide virtual keyboard on Windows 10.

## Getting Started

You have to enable touch keyboard on taskbar.
- Right Click on the taskbar.
- Enable "Show touch keyboard button".


## Usage

```dart

import 'package:flutter_osk_x/flutter_osk_x.dart';

void main(){
    // show keyboard
    WindowsOSK.show();

    // close keyboard
    WindowsOSK.close();
}
```
