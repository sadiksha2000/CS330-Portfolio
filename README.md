# CS-330 Computational Graphics and Visualization Portfolio

**Student:** Sadiksha Pathak

## Project Contents

- **3D Scene ZIP:** A 3D desk scene built in C++ and OpenGL. It has a desk lamp (cylinder base, cylinder arm, and tapered cylinder shade), a notebook, a mug, a glass paperweight, and a pencil on a textured desk. The scene uses three lights, camera navigation with the keyboard and mouse, and a switch between perspective and orthographic views. The ZIP includes the EXE and all project files.
- **Design Decisions document:** A two-page explanation of why I chose the objects, how a user navigates the scene, and the custom functions that keep the code organized.

## Reflection

### How do I approach designing software?

This project taught me to start with a simple picture of the finished result and then break it into small parts. I began with a 2D image of a desk, listed the real objects in it, and decided which basic shape (box, cylinder, sphere, cone, torus, or plane) could stand in for each part. A lamp, for example, became three shapes. The design process I followed was to plan the shapes, place them in the scene, and then add camera control, textures, and lighting one milestone at a time. This approach of breaking a large problem into small, testable pieces can be used in any future project, from a web application to a database, because it keeps a big task manageable.

### How do I approach developing programs?

The biggest new strategy I used was putting repeated work into reusable functions. Functions such as `SetPartTransform()` and the separate render functions for the lamp, notebook, mug, paperweight, and pencil meant I could change or move an object without editing every line. Iteration was a major part of the work because each milestone built on the one before it. I added camera movement, then textures, then lighting, and each step meant going back to earlier code, fixing small problems, and checking that everything still worked. My approach changed from writing code until it ran to organizing the code, commenting it clearly, and checking the full package before I submit it. One lesson I took from instructor feedback is to always include the EXE and all project files in the ZIP and to test the finished package.

### How can computer science help me in reaching my goals?

My long-term goal is a career as a software developer. Computational graphics gave me skills I can use in my education and in a job, such as working with coordinates and transformations, understanding how lighting and textures change how something looks, and reading and organizing a larger codebase. In my educational path, these ideas connect to game development, simulation, and data visualization courses. In my professional path, I can use the same habits (planning, modular code, testing, and clear comments) on any software team, and graphics skills could help me work on visual tools, games, or dashboards that turn data into something people can understand.
