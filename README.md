# JS-Image-Resizer
A javascript based solution for image scaling outside of html5 canvas.

##Troubleshoot
When running index.html on Chrome, only first picture loads, due to Uncaught SecurityError on line 14:
<br />`Uncaught SecurityError: Failed to execute 'getImageData' on 'CanvasRenderingContext2D': The canvas has been tainted by cross-origin data.`

**Solution**:
+ Running on a server instead (eg localhost)

