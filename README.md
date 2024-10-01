
# Material 2 vs Material 3 Cheatsheet

## 1. Typography Mapping
| **Material 2 (Old)** | **Material 3 (New)** |
|----------------------|----------------------|
| `headline1`          | `displayLarge`       |
| `headline2`          | `displayMedium`      |
| `headline3`          | `displaySmall`       |
| `headline4`          | `headlineLarge`      |
| `headline5`          | `headlineMedium`     |
| `headline6`          | `titleLarge`         |
| `subtitle1`          | `titleMedium`        |
| `subtitle2`          | `titleSmall`         |
| `bodyText1`          | `bodyLarge`          |
| `bodyText2`          | `bodyMedium`         |
| `caption`            | `bodySmall`          |
| `button`             | `labelLarge`         |
| `overline`           | `labelSmall`         |

## 2. Color System
| **Material 2 (Old)**     | **Material 3 (New)**    |
|--------------------------|-------------------------|
| `primaryColor`           | `primary`               |
| `primaryColorDark`       | `onPrimary`             |
| `accentColor`            | `secondary`             |
| `primaryVariant`         | `primaryContainer`      |
| `secondaryVariant`       | `secondaryContainer`    |
| `onPrimary`              | `onPrimaryContainer`    |
| `onSecondary`            | `onSecondary`           |
| `backgroundColor`        | `background`            |
| `onBackground`           | `onBackground`          |
| `errorColor`             | `error`                 |
| `onError`                | `onErrorContainer`      |

## 3. AppBar & Other Widgets
| **Material 2 (Old)**            | **Material 3 (New)**       |
|----------------------------------|----------------------------|
| `AppBar` (fixed height)          | `AppBar` (flexible)        |
| `RaisedButton`                   | `ElevatedButton`           |
| `FlatButton`                     | `TextButton`               |
| `OutlineButton`                  | `OutlinedButton`           |
| `ButtonBar`                      | Deprecated (use `Flex`)    |
| `FloatingActionButton`           | M3: Updated FAB design     |
| `Chip`                           | M3: Updated with more variants |
| `Dialog`                         | M3: New surfaces for dialogs  |

## 4. Button Styles
| **Material 2 (Old)**           | **Material 3 (New)**     |
|---------------------------------|--------------------------|
| `RaisedButton`                  | `ElevatedButton`         |
| `FlatButton`                    | `TextButton`             |
| `OutlineButton`                 | `OutlinedButton`         |
| `ButtonStyleButton` (abstract)  | `ButtonStyle` (base for all buttons) |

## 5. Elevation and Shape
| **Material 2 (Old)**             | **Material 3 (New)**             |
|----------------------------------|----------------------------------|
| `elevation`                      | `surfaceTintColor` (new shadow model) |
| `ShapeBorder` (like `RoundedRectangleBorder`) | Updated rounded shapes for consistent corners |

## 6. Other Key Updates
- **Icons**: Material 3 introduces **Adaptive Icons** that change based on the theme.
- **Dynamic Color**: Material 3 encourages using dynamic colors derived from a seed color.
- **Components Adaptation**: Widgets like `Checkbox`, `Slider`, and `Switch` have been visually updated with smoother animations and modern styles.

## 7. Surface Colors
| **Material 2 (Old)**    | **Material 3 (New)**     |
|-------------------------|--------------------------|
| `surfaceColor`          | `surface`                |
|                         | `surfaceContainerLow`    |
|                         | `surfaceContainerHigh`   |
|                         | `surfaceVariant`         |
