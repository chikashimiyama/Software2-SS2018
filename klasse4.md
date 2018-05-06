# UI

## Kommunikation zwischen zwei Containers

### out + in
![](K4/inout.png)

### CHOP/select
![](K4/send.png)
![](K4/receive.png)

## User Interface in TD

![](K4/3ui.png)

## Button
![](K4/btn.png)

### Umbenennen

in Button Comp änderbar
![](K4/btnname.png)

### Position auf Container
![](K4/container.png)

### Mehrere Buttons und Align Order
![](K4/many.png)

#### Align Order
![](K4/alignment.png)

#### Sort
![](K4/sort.png)

## Video Switcher Project (1)
Ein Button funktionert als Selector


### COMP/button
Button Type: Momentary 
![](K4/momentary.png)

### CHOP/count

![](K4/count.png)

- Limit : Loop Min/Max
- Limit Minimum : 0
- Limit Maximum : 2


![](K4/change.png)


## Video Switcher Project (2)
Wiedergabegeschwindigkeitssteuerung mit einem Slider 

### Button und Slider
![](K4/bands.png)

![](K4/two_controls.png)

## Video Switcher Project (3)
Zwei Bildschirme. (Video + UI)

```
Perform Mode is an optimized mode that only renders one specific controlpanel.
To maintain the optimized properties of perform mode, all windows should be rendered as a single canvas. 
```
### Trennung
#### Kontrol
![](K4/control.png)

#### Rendering
![](K4/rendering.png)

### Lösung
Zwei Container + Align Order

![](K4/solution.png)

![](K4/twocontainers.png)


## Andere UI Komponenten
### OPViewer
funktioniert wie "bpatcher". OpViewer zeigt ein ausgewählte Operator im Panel

![](K4/opviewer.png)

### Field
Text input auf Perform Window

![](K4/field.png)

#### 3D Text In Echtzeit


![](K4/3dtext.png)
![](K4/3dtext_perf.png)
