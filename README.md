# Day 4: vh, vw, vmax, and vmin

Viewport height (`vh`) is used to set the height of an element or container based on the height of the specified viewport. Similarly, viewport width (`vw`) is used to set the width based on the width of the viewport. The difference between setting height and width in percentage and using `vh` or `vw` is that percentage is relative to the size of the parent, while `vh` and `vw` are relative to the viewport.

Additionally, we have `vmax` and `vmin`, which take into account both the viewport width and height. `vmin` takes the minimum value of the two, while `vmax` takes the maximum value. 

For example, if you set the size of an element with `vmin` to be `10vmin`, it will shrink and grow along with the minimum value of the viewport. If the width is smaller, it will take 10% of the viewport width (`10vw`), and if the height is smaller, it will take 10% of the viewport height (`10vh`). If the width reaches a point where it can no longer be stretched and it's the smaller of the two dimensions, it will remain at `10vw` and won't grow further, even if the height is expanded.

Using these units provides a flexible way to make elements responsive to different viewport sizes, allowing them to adapt and scale accordingly. It is particularly useful when designing layouts that need to adjust dynamically based on the available space within the viewport.
