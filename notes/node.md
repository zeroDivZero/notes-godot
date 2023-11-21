# NODE

Atomic building block. Each performs specialize function (shows image, plays sound, displays 3D model, etc.). Common attributes:

* name
* editable properties
* can receive callback to update every frame
* can be extended (to have more functions)
* can be added to another node as child; each node can have multiple children

Godot provides library of base node types to combine and extend to build more powerful ones.

Child node inherits all properties and features of parent nodes, not like components in other game engines.
