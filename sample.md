# Markdown Plus

![Markdown Plus](icon.png)
Markdown Plus is a lightweight markdown editor. Besides common markdown, GitHub flavored markdown, it also supports task lists, emojis, Font Awesome icons, Ionicons icons, Mathematical formulae, flowcharts and sequence diagrams.


##### Github home page: <a href="https://github.com/tylingsoft/markdown-plus" target="_blank">tylingsoft/markdown-plus</a>.


## GitHub flavored markdown

| Left-Aligned  | Center Aligned  | Right Aligned |
| :------------ |:---------------:| -----:|
| col 3 is      | some wordy text | $1600 |
| col 2 is      | centered        |   $12 |
| zebra stripes | are neat        |    $1 |


## Fenced code blocks

```python
from fabric.api import local

def update():
    local('rm -rf bower_components')
    local('bower cache clean')
    local('bower update')
```


## Task lists

- [ ] a bigger project
  - [x] first subtask
  - [x] follow up subtask
  - [ ] final subtask
- [ ] a separate task


## Emojis

<img src="emoji/smile" width="64"/>
<img src="emoji/whale" width="64"/>
<img src="emoji/santa" width="64"/>
<img src="emoji/panda_face" width="64"/>
<img src="emoji/dog" width="64"/>
<img src="emoji/truck" width="64"/>


## Font Awesome icons

<i class="fa fa-cloud" style="font-size: 64px;"/>
<i class="fa fa-flag" style="font-size: 64px;"/>
<i class="fa fa-car" style="font-size: 64px;"/>
<i class="fa fa-truck" style="font-size: 64px;"/>
<i class="fa fa-heart" style="font-size: 64px;"/>
<i class="fa fa-dollar" style="font-size: 64px;"/>


## Ionicons icons

<i class="icon ion-beer" style="font-size: 96px;"/>
<i class="icon ion-key" style="font-size: 96px;"/>
<i class="icon ion-locked" style="font-size: 96px;"/>
<i class="icon ion-location" style="font-size: 96px;"/>
<i class="icon ion-plane" style="font-size: 96px;"/>
<i class="icon ion-ios-eye" style="font-size: 96px;"/>


## Mathematical formulae

```math
E = mc^2

\dfrac{ \tfrac{1}{2}[1-(\tfrac{1}{2})^n] }{ 1-\tfrac{1}{2} } = s_n

\oint_C x^3\, dx + 4y^2\, dy

2 = \left(
 \frac{\left(3-x\right) \times 2}{3-x}
 \right)

\sum_{m=1}^\infty\sum_{n=1}^\infty\frac{m^2\,n}
 {3^m\left(m\,3^n+n\,3^m\right)}
 
\phi_n(\kappa) =
 \frac{1}{4\pi^2\kappa^2} \int_0^\infty
 \frac{\sin(\kappa R)}{\kappa R}
 \frac{\partial}{\partial R}
 \left[R^2\frac{\partial D_n(R)}{\partial R}\right]\,dR
```


## Flowcharts

```
graph TD
    A[Hard edge] -->|Link text| B(Round edge)
    B --> C{Decision}
    C -->|One| D[Result one]
    C -->|Two| E[Result two]
```


## Sequence diagrams

```
sequenceDiagram
    Alice->>Bob: Hello Bob, how are you?
    alt is sick
        Bob->>Alice: Not so good :(
    else is well
        Bob->>Alice: Feeling fresh like a daisy
    end
    opt Extra response
        Bob->>Alice: Thanks for asking
    end
```
