---
description: 'Social Button determines the standard, solid, button with both label and icon.'
---

# Social Button

## Social Button Full

Default button **shape** set to `GFButtonShape.standard` so that we will able to get standard shaped button with solid background color with slightly rounded corners.

### Solid Social Button

By default, button **type** set to `GFType.solid` so, we able to get buttons have a solid background color with slightly rounded corners.

The callback that is called when the button is tapped. By adding callback to **onPressed** enables the button.

```dart
  GFButton(
    onPressed: (){},
    text: "primary",
    icon: Icon(Icons.share),
  ),
```

### Disabled Button

If this callback and **onPressed** are null, then the button will be disabled. Default GFButton will be disabled because, **onPressed** set to null. 

```dart
GFButton(
    onPressed: null,
    text: "primary",
    icon: Icon(Icons.share),
 ),
```

### Outline  Social Button

Outline Button describes as the Button with a transparent background and a visible border. This button can be easily get in GFButton by adding **type** as **`GFType.outline`**. 

```dart
GFButton(
    onPressed: (){},
    text: "primary",
    icon: Icon(Icons.share),
    type: GFType.outline,
 ),
```

### Outline2x  Social Button

Outline Icon Button describes as the Button with a transparent background and a visible border of 2x border-width. This button can be easily get in GFButton by adding **type** as **`GFType.outline2x`**. 

```dart
GFButton(
    onPressed: (){},
    text: "primary",
    icon: Icon(Icons.share),
    type: GFType.outline2x,
 ),
```

### Transparent  Social Button

In GFButton by adding **type** **`GFType.transparent`**, we able to get transparent button. Default GFButton **type** will be `GFType.solid`. 

```dart
GFButton(
    onPressed: (){},
    text: "primary",
    icon: Icon(Icons.share),
    type: GFType.transparent,
 ),
```

### Pills  Social Button

We will able to get pills shaped button with solid background color with rounded corners by adding property **shape** with  `GFButtonShape.pills` . 

```dart
  GFButton(
    onPressed: (){},
    text: "primary",
    icon: Icon(Icons.share),
    shape: GFButtonShape.pills,
  ),
```

### Square Social Button

We will able to get pills shaped button with solid background color with no rounded corners by adding property **shape** with  `GFButtonShape.square` . 

```dart
  GFButton(
    onPressed: (){},
    text: "primary",
    icon: Icon(Icons.share),
    shape: GFButtonShape.square,
  ),
```

###  Social  Button Size

Button size can be varied using **size** property, which specifies the size of the button. Default button size set to `GFSize.medium`.

```dart
GFButton(
    onPressed: (){},
    text: "primary",
    icon: Icon(Icons.share),
    size: GFSize.small,
 ),
```

### Block Social Button

Block button specify how wide the button should be. By setting **blockButton** state `true`, it will change the button to a full-width block with rounded corners. Default **blockButton** set to `false`.

```dart
GFButton(
    onPressed: (){},
    text: "primary",
    icon: Icon(Icons.share),
    type: GFType.solid,
    blockButton: true,
 ),
```

### Full Width Social Button

Full Width button specify how wide the button should be. By setting **fullWidthButton** state `true`, it will change the button to a Full-width button with square corners and no border on the left or right. Default **fullWidthButton** set to `false`.

```dart
GFButton(
    onPressed: (){},
    text: "primary",
    icon: Icon(Icons.share),
    type: GFType.solid,
    fullWidthButton: true,
 ),
```

## Social Icon Button

Social Icon Button having features of standard, solid button with fill color background and slightly rounded corners and icon as a child.

Default button **shape** set to `GFButtonShape.standard` so that we will able to get standard shaped button with solid background color with slightly rounded corners. By default, button **type** set to `GFType.solid` so, we able to get buttons have a solid background color with slightly rounded corners.

```dart
GFIconButton(
    onPressed: (){},
    icon: Icon(Icons.share),
 ),
```

### Size

Button size can be varied using **size** property, which specifies the size of the button. Default button size set to `GFSize.medium`.

```dart
GFIconButton(
    onPressed: (){},
    text: "primary",
    size: GFSize.small,
 ),
```

### Type

Button type can be changed using property **type** by setting to `GFType.outline`. Default type of the IconButton will be `GFType.solid`.

```dart
GFIconButton(
    onPressed: (){},
    text: "primary",
    type: GFType.outline,
 ),
```

### Shape

Shape of Icon Button can be changed by setting property **shape** to `GFIconButtonShape.circle`. Default shape of the IconButton set to `GFIconButtonShape.standard` which gives square shaped IconButton with slightly rounded corners.

```dart
GFIconButton(
    onPressed: (){},
    text: "primary",
    shape: GFIconButtonShape.pills,
 ),
```
