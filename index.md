---
layout: default
---

<img src="./assets/images/IMG_3170.jpg" alt="tractor">

# Project Statement

I am conducting an analysis of sensor data collected during corn planting on a 12 row ExactEmerge planter. I am interested in learning the causes of variation in closing wheel performance. In general, when comparing conservation-tilled fields, closing performance increases as closing wheel average acceleration decreases. This is only to a certain point, however, since overcompaction can also lead to negative effects. Therefore, for a specific field and pressure, I will observe the influence of depth, speed, soil characteristics, draft force, and power availability on overall closing performance.

# Data Acquisition

Our control system utilizes a MicroAutoBox connected to a high-speed CAN bus to send and receive signals that read sensor inputs and manage the electronic depth actuators, pneumatic controllers and user interface. This CAN bus also to a gateway which we use as a diagnostic port to log these signals in an ASCII text format.

Here is a list of relevant non-native sensors installed for this project:

**Rotary encoders for cleaning and closing wheels**

<img src="./assets/images/encoders.jpg" alt="encoders">

**Inertial Measurement Units (IMU) for acceleration data on row unit**

<img src="./assets/images/IMU.png" alt="encoders">

## Header 2

> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

### Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

<img src="./assets/images/kdeplot.png" alt="kdeplot">

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```
