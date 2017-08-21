# Contraster
A before and after slider with zoom and pan functionality using [Cocoen](https://github.com/koenoe/cocoen).

## Usage
![](images/how_to_details.jpg)

In the cocoen-container ```<div>```, include the ```data-scale="x"``` attribute and specify the desired zoom distance. Each attribute is uinique to the current element.
```html
<div class="cocoen" data-scale="2">
  <img src="image/path" alt="Before">
  <img src="image/path" alt="After">
</div>
```
## Mobile Controls
TAP and DRAG slider bar to compare.  DOUBLE TAP and DRAG to zoom and pan image.

# License
The code and the documentation are released under the [MIT License](LICENSE).
