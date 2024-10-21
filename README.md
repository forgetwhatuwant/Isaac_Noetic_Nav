# BRL Chicken 2D Navigation

The `brl_chicken_2dnav` package is a ROS-based navigation system designed for 2D environments. It utilizes the `move_base` package for path planning and navigation, along with AMCL for localization.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Dependencies](#dependencies)
- [License](#license)

## Installation

1. **Clone the repository:**

   ```bash
   git clone <repository-url>
   ```

2. **Navigate to the package directory:**

   ```bash
   cd src/navigation/brl_chicken_2dnav
   ```

3. **Build the package:**

   ```bash
   catkin_make
   ```

4. **Source the setup file:**

   ```bash
   source devel/setup.bash
   ```

## Usage

To launch the navigation system, use the following command:
   ```bash
   roslaunch brl_chicken_2dnav brl_move_base.launch
   ```
