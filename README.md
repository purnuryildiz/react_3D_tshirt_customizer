<h1>React-3D-Tshirt-Customizer</h1>

<p>3D Customization App is a React-based application designed to provide a rich, interactive 3D experience where users can fully customize a 3D model of a shirt. It offers various tools and features that allow for dynamic changes in colors, textures, and more, giving users complete control over the final appearance of the model.</p>

<h2>Features</h2>

<list>

3D Components:

- Backdrop: Creates a dynamic shadow backdrop with randomized lights, enhancing the 3D visualization experience.

- CameraRig: Manages camera positioning and rotation to ensure a responsive experience across different devices and user interactions.

- CanvasModel: Configures the 3D canvas environment using @react-three/fiber and @react-three/drei for advanced 3D rendering.

- Shirt: Loads a 3D shirt model, allowing users to apply textures such as logos or full decals.

Customization Tools:

- ColorPicker: A user-friendly color picker utilizing react-color, enabling easy selection of colors.

- CustomButton: Offers customizable buttons with various styles to enhance user interaction.

- FilePicker: Manages file uploads, enabling users to apply their own textures or images to the 3D model.

- Tab Component: Provides a tabbed navigation interface for selecting different customization options like colors or textures.

Helper Functions and Animations:

- reader: Reads files as base64 encoded data URLs, essential for applying custom textures.

- getContrastingColor: Determines the optimal contrasting color (black or white) for any selected background.

- Animation Helpers: Uses Framer Motion to create smooth animations and transitions, delivering an engaging user experience.

Configuration and State Management:

- Configuration: Manages different backend URLs for development and production environments using a configuration object.

- State Management: Utilizes valtio for reactive state management, ensuring a seamless and responsive user experience.

</list>

<h2>Preview:</h2>

![](image.gif)
