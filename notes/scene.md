# SCENE

Composed of group of nodes organized hierarchically (as tree). Can be character, weapon, UI menu, entire level, etc. Can be nested as tree. Fills role of prefab and scene in other game engines.

Furthermore, scene:

* always has only one root node
* can be saved to disk and loaded back
* can be instanced
* can inherit from another scene (object-oriented)

Running game means running scene. Project can have multiple scenes, but to start game, one scene must be started as main scene.

Godot is scene editor. Nodes and scenes look same in editor. When saving node tree as scene, shown as single node, with internal structure hidden.
