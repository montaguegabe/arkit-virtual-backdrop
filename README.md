# arkit-virtual-backdrop
Superimposes your image into a 3D world using Metal+ARKit

This example calculates depth to viewer's face, and uses it to remove the background behind the viewer's head and body, replacing it with a 3D scene rendered in Metal. The viewer's image is rendered as a plane in front of the geometry using a Metal shader that passes through when the depth is beyond a threshold.

Current issues to be resolved:
- Border around head and body is noisy
- Depth images are not recieved consistently
