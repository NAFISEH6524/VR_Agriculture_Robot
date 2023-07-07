# VR_Agriculture_Robot

Unreal Engine Steps
In Unreal Engine, we created drone and navigate the drone in the same platform. Also, the recontruction model we obtained from the Reality Capture we imported in the Unreal Engine for the navigation of the dron.

Creating a drone in Unreal Engine using Blueprints involves several steps. Here's a detailed breakdown of the process:

Set up the Project:

Launch Unreal Engine and create a new Blueprint project.
Choose a project template or start with a blank project.
Specify the project settings, including project name and directory.
Import Drone Assets:

Find or create 3D models for the drone's body, rotors, and any other components.
Import the models into Unreal Engine by using the "Import" option in the Content Browser.
Ensure the models are properly scaled and positioned for later use.


Drone Blueprint

Figure above shows drone blueprint.

Create the Drone Blueprint:
Find or create 3D models for the drone's body, rotors, and any other components.
Open the Blueprint Editor by double-clicking on the Content Browser or right-clicking and selecting "Create Blueprint Class."
Choose the desired parent class for the drone. You can start with a Pawn or Character class, depending on your requirements.
In the Blueprint Editor, you will see the Construction Script, Event Graph, and other sections.
Figure below shows the drone skeleton.



Drone Skeleton

Now, we attached camera to our drone as show in figure below.



Camera to Drone Skeleton



Drone Activation

Here, we going to activated our dron as shown in figure above and later we going to deactivate our drone as shown below.



Drone Deactivation

Later, we attaching altitude meters to drone as shown in figure below.



Drone: Get Altitude Meters (pure, const)

At the end, we get distance meters as described in figure below.



Drone: Get Distance Meters 0 (pure, const)

Design the Drone's Behavior:

Use the Construction Script to set up the initial positioning and attachment of the drone components.
In the Event Graph, add nodes and script the desired behavior for the drone.
Use input events (e.g., keyboard or gamepad inputs) to control the drone's movement, such as changing its location, rotation, or velocity.
Implement logic for drone actions like taking off, landing, hovering, and rotating.
Add collision detection and response to avoid obstacles or trigger specific events.
Add Drone Physics:

Enable physics simulation for the drone by enabling the "Simulate Physics" option in the Details panel.
Configure the drone's collision properties, such as collision channels, collision responses, and physical materials.
Adjust the drone's mass, drag, and other physical parameters to mimic realistic flight dynamics.
Use constraints or physics joints to connect the drone's components, such as the rotors to the body.
Implement Camera and View:

Add a camera component to the drone Blueprint to simulate the drone's perspective.
Configure the camera's position, rotation, field of view, and any other desired settings.
Set up camera controls to allow the player to switch between different camera views or perspectives.
Test and Refine:

Compile and save the drone Blueprint.
Place an instance of the drone Blueprint in the game world or level.
Launch the game or simulation to test the drone's behavior and controls.
Iterate on the design, making adjustments and refinements as needed.
Test the drone in different scenarios and environments to ensure its functionality and performance.
Moreover, we setup of environment blueprint as shown in figure below.



Environment setup Blueprint

Remember that this is a general outline of the process, and specific implementation details may vary based on your project requirements and the level of complexity you wish to achieve. The Blueprint system in Unreal Engine offers flexibility, allowing you to customize the drone's behavior and interactions according to your specific needs.

Creation of Forest Environment in Unreal Engine
To create a forest environment in Unreal Engine, you'll start by setting up the project and creating the terrain using the engine's terrain tools. Then, you'll place vegetation such as trees and bushes using foliage painting tools. Apply realistic materials to the terrain and foliage assets to add detail and variation. Set up appropriate lighting and atmospheric effects to enhance the visual appeal. Add sound effects to create an immersive auditory experience. Figure below shows the forest environment in unreal engine.



Forest Environment Angle1

Include additional details like rocks and streams, and incorporate interactive elements for engagement. Test and optimize the scene to ensure optimal performance. By following these steps, you can quickly create a captivating and realistic forest environment in Unreal Engine. Figure below shows the forest environment view from different angel in unreal engine.



Forest Environment Angle2

In conclusion, creating a forest environment in Unreal Engine involves setting up the project, designing the terrain, placing vegetation, applying realistic materials, setting up lighting and atmospheric effects, adding sound effects, incorporating small details, and optimizing the scene for performance. By following these steps, you can create a visually stunning and immersive forest environment in Unreal Engine that transports users into a realistic and captivating virtual forest setting.

Result
The result of the project on Photogrammetry and 3D Model Reconstruction in terms of Virtual Reality for Robotics is a highly immersive and realistic virtual environment that integrates photogrammetry-based 3D models with virtual reality technology. This integration brings several benefits and outcomes to the field of robotics:

Accurate and Detailed Virtual Representations: The project enables the creation of precise and detailed 3D models of real-world objects and scenes using photogrammetry techniques. These models capture intricate details and provide an accurate representation of the physical environment. When integrated into the virtual reality environment, they create a highly immersive experience for the users.

Realistic Training and Simulation: The resulting virtual reality environment allows for realistic training and simulation of robotic systems. Users can interact with virtual representations of robots and perform various tasks, such as manipulating objects, navigating through the virtual space, or testing different scenarios. This provides a safe and cost-effective way to train robot operators, test algorithms, and evaluate system performance.

Enhanced Visualization and Understanding: The combination of photogrammetry-based 3D models and virtual reality technology offers improved visualization and understanding of the physical environment for robotics applications. Users can explore and analyze the virtual representation of the environment, gaining insights into the spatial layout, object relationships, and potential obstacles. This aids in planning and decision-making processes for robotics tasks.

Seamless Human-Robot Interaction: The project's outcome facilitates seamless human-robot interaction within the virtual reality environment. Users can intuitively control and communicate with virtual robots, providing commands or performing actions through natural gestures or user interfaces. This enables the development and testing of human-robot interaction algorithms and enhances the overall user experience.

Robust System Development and Evaluation: The virtual reality environment resulting from the project serves as a valuable platform for the development and evaluation of robotic systems. Researchers and developers can test and refine algorithms, control strategies, and sensor configurations within the virtual environment, prior to real-world implementation. This helps in identifying and addressing potential issues or limitations before deployment.

Collaborative Robotics Research: The virtual reality environment allows for collaborative research and development in the field of robotics. Multiple users can connect to the same virtual space simultaneously, enabling collaboration, knowledge sharing, and joint experimentation. This fosters interdisciplinary collaboration and accelerates innovation in robotics.

Figure below shows the content browser folder which is obtained at end of our project.



Content Browser Folder

Figure below depicts when the game starts in Unreal Engine.



Game Start

Figure below highlights with the drone's camera view which shows our model which we imported from reality Capture.



Drone: Camera View of 3D Model from Reality Capture

Figure below explains about the drone camera which shows the environment.



Drone Camera: Environment View

Overall, the project's result combines the power of photogrammetry and 3D model reconstruction with virtual reality technology to enhance robotics applications. The outcome is a realistic and immersive virtual environment that facilitates training, simulation, visualization, and interaction with robotic systems. It opens up new possibilities for research, development, and deployment of robotics technologies in various domains, including manufacturing, healthcare, exploration, and more.
