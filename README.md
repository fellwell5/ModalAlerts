
# ModalAlerts
Generates a bootstrap modal which is removed from body after beeing closed.
## Installation
```
<script src="path/to/ModalAlerts.js"></script>
```

## Examples
```
ModalA.newModal("Title", "Description", function(){ alert("This is a callback function.") });
```
```
ModalA.newModal("Title", "<p>I can use <strong>HTML</strong> here!</p>", function(id){ alert("Modal with ID "+id+" closed.") });
```
