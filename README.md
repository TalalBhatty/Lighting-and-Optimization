**Project Structure**

**Assets:** Contains all game assets.
**Materials:** Folder for material files.
**Prefabs:** Folder for prefabricated game objects.
**Scenes:** Folder for scene files.
**Textures:** Folder for texture files.

**Lighting Setup**
**Directional Light:** Simulates sunlight.


**Post-Processing Enhancements:**
I've enhanced the visual quality of our Unity project using post-processing effects. 
****These include:****

**Bloom:** Adding a soft glow to bright areas, like how light might naturally spread in a camera lens.

**Color Grading:** Adjusting colors to create a specific mood or atmosphere, enhancing the overall visual appeal.

**Vignette:** Darkening the edges of the screen, focusing attention on the center and creating a cinematic feel.

**Ambient Occlusion:** Simulating subtle shadows in corners and crevices, adding depth and realism.

**Anti-Aliasing:** Smoothing out jagged edges, making lines and edges appear smoother and more natural.


To optimize performance, I've used light baking. This technique precomputes how light interacts with static objects in the scene:

**Efficiency:** By calculating lighting beforehand, we reduce the need for real-time computations during gameplay.

**Stability:** It ensures consistent lighting across different devices and viewing conditions, improving visual fidelity.

**Suitability:** Ideal for scenes with mostly static lighting, such as architectural visualizations or environments with minimal changes in lighting.
Occlusion Culling

Implementing occlusion culling has further optimized our project by:

**Visibility Management:** Determining which objects are visible to the camera at any given time.

**Performance Benefits:** By not rendering objects blocked from view by others or the environment, we reduce GPU workload.

**Enhanced Frame Rates:** This approach significantly improves performance in complex scenes or large environments, maintaining smooth gameplay.


**Conclusion:**
By combining these techniques—enhancing visuals with post-processing effects, leveraging light baking for static scenes, and implementing occlusion culling for efficient rendering—we've achieved both visual fidelity and optimal performance in our Unity project.
