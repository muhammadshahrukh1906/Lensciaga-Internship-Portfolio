AUTOMATIC 3D PORTFOLIO

Files:
- index.html
- eyeglasses.glb

The 3D model loads automatically. There is no load button.

IMPORTANT FOR LOCAL TESTING
Do not double-click index.html, because browsers commonly block GLB loading from file:// pages.
Use VS Code Live Server, or run this command inside the folder:

python -m http.server 8000

Then open:
http://localhost:8000

FOR HOSTING
Upload index.html and eyeglasses.glb to the same published folder. The model filename must remain exactly:
eyeglasses.glb
