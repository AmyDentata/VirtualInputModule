# VirtualInputModule (Unity 5.3.4f1)

A modified StandaloneInputModule that allows UI events to be driven by a virtual mouse cursor. Does not handle cursor movement.

The virtual mouse cursor must be a canvas object.

Setup is simple:
1. Replace StandaloneInputModule with VirtualInputModule on the EventSystem game object.
2. Assign a canvas object to m_VirtualCursor.
3. Assign the canvas camera to m_CanvasCamera.
