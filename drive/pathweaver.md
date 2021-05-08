# PathWeaver Setup

Setup instructions for PathWeaver.

## Creating a New Project

1. Click **Create Project**
2. Select a project directory, and then make sure your output directory is pointed to `<RobotProject>/src/main/deploy/`, where `RobotProject` is the absolute path to your robot project.

3. You can change your length unit to feet, but WPILib likes to play in meters, so keep the export unit in "Always Meters"
4. Select a REASONABLE max acceleration/velocity
5. Ask mechanical for the wheel base length (they should have it; otherwise spin the robot 10 times and divide the output of the distance by 20$\pi$)
