This project is a demo application that showcases how to implement a simple drawing app using Jetpack Compose. The app allows users to draw on a canvas using their fingers, select different colors for drawing, and clear the canvas with a single tap. It highlights the power of Jetpack Compose for building highly interactive and dynamic UIs while following clean architecture principles.
![dr](https://github.com/user-attachments/assets/733320cc-914e-4e92-9307-99a35c42d740)

Key Features:
Drawing on Canvas

Users can draw freehand using their fingers on the canvas.
The app leverages Jetpack Compose's Canvas API for real-time drawing.
Touch inputs are captured and processed to render smooth lines dynamically.
Color Picker

Users can choose from a palette of colors to customize their drawings.
The selected color is applied instantly to the brush for a seamless experience.
Clear Canvas

A dedicated "Clear Canvas" option allows users to erase all drawings, resetting the canvas to its initial state.
This functionality is integrated with minimal latency for a smooth user experience.
State Management

The app uses StateFlow to manage the drawing state efficiently, ensuring reactivity and consistency.
The drawing operations are processed and managed in a dedicated DrawingViewModel, which separates business logic from UI components.
Clean Architecture

The app follows the principles of clean architecture, making it modular and easy to maintain:
ViewModel: Manages the drawing state, selected color, and canvas operations (clear, draw, etc.).
CanvasControl Class: Encapsulates the logic for managing the canvas and interpreting touch inputs.
UI Components: Jetpack Compose-based UI components to provide a modern, intuitive interface.
Jetpack Compose

The project uses the latest Jetpack Compose version, showcasing best practices and up-to-date APIs.
It simplifies building complex UIs like the drawing canvas with minimal boilerplate code.
Why Use This Project?
This project serves as a practical example of building interactive features in Jetpack Compose while maintaining clean and scalable code. It's a great starting point for developers looking to explore touch interaction handling, custom drawing on canvas, and reactive state management in modern Android apps.

Follow Me for More!
If you're interested in exploring more Jetpack Compose projects or want to stay updated with the latest trends in Android development, check out my GitHub:
👉 GitHub Profile

Feel free to explore, star the repository, and share your feedback. Happy coding! 🚀
