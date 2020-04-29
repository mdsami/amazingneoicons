# amazingneoicons

A Package use [Amazing Neo - Icons](https://amazingneo.com/icons) as set of Flutter Icons


## Installation

In the `dependencies:` section of your `pubspec.yaml`, add the following line:

```yaml
  amazingneoicons: ^0.0.2
```

## Usage

```dart
import 'package:amazingneoicons/amazingneoicons.dart';

class MyWidget extends StatelessWidget {
  Widget build(BuildContext context) {
    return new IconButton(
      icon: new Icon(AmazingNeoIcons.beach),
      onPressed: () { print("Amazing"); }
     );
  }
}
```