# ADXL335

Here is the repository of one of my electronic projects, a rather simple electronic card around a MEMS accelerometer : ADXL335. MEMS accelerometers are compact devices that exploit microfabrication technology to integrate mechanical elements, sensors, actuators, and electronics on a tiny silicon chip. At the core of these devices lies a MEMS structure, often composed of microstructures such as beams or cantilevers, which respond to external forces.

![ADXL335](./extra/main-image.jpeg)

This entire project is documented on my [personal website](https://albanpetit.com/posts/adxl-335-accelerometer/), from the electronic card to the code necessary for its operation, including its manufacturing itself. 

## Project structure and usage

Project structure :
- **ecad** : ecad kicad source files, gerber and ibom
- **mcad** : mechanical part of the project, using Fusion360 older than : v.2.0.18477
- **firware** : Arduino script, any version of the programming work, no extra library needed

This project use the latest at this date version of kicad : 8.0.2. 

## Contribution

If you're interested in contributing, i'd love to have your input. Here's how you can get started:

1. **Fork the Repository:** Click on the "Fork" button at the top right of this repository to create your own copy.
2. **Clone Your Fork:** Clone your forked repository to your local machine using the following command:
   ```bash
   git clone https://github.com/albanpetit/adxl335
   ```
3. **Create a New Branch:** Switch to a new branch for your contributions.
   ```bash
   git checkout -b feature/your-feature-name
   ```
4. **Make Changes:** Make the necessary changes or additions to improve the website.
5. **Commit Your Changes:** Commit your changes with descriptive commit messages.
   ```bash
   git commit -m "feat: description of the new feature"
   ```
6. **Push to Your Fork:** Push your changes to your forked repository.
   ```bash
   git push origin feature/your-feature-name
   ```
7. **Open a Pull Request:** Once you've pushed your changes to your fork, open a pull request in our repository. Provide a detailed description of your changes and any relevant information.

### Commit naming convention

To make the commit history as readable as possible, I try to adhere as closely as I can to the following naming convention :

```
<type> <sujet>

<description>
```

- **Type** defines the type of commit
  - **git**: gitignore modification. submodule update, merging
  - **docs**: Documentation
  - **feat**: Add firmware feature
  - **fix**: Bug fix on firmware
  - **perf**: Code performance improvement
  - **ecad**: Electronic Computer Aided Design
  - **mcad**: Mechanical Computer Aided Design
  - **refactor**: Code changement which does not change the usage
- **Sujet** contains a brief description of the changes
  Using the present imperative ("change", not "changed" or "changes")
  Without capital letter at the beginning
  No "." at the end of the description
- **Description** allows to detail in more detail the motivations behind
  the change. The rules are the same as for the Subject part.

I invite you to follow this convention to contribute more easily to this repository.

### Feedback and Issues

If you encounter any issues, have suggestions, or want to discuss new features,
please open an issue on the GitHub repository. Your feedback is highly valued!

Thank you for considering contributing.