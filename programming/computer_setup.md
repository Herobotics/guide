
# Computer Setup

##### FRC Game Tools

Use:
> FRC Game Tools are used to control and configure the robot.

Contains:
* National Instruments
* Driver Station
* Robo-Rio Imaging Tool
* Radio Configuration Tool

Steps:

1. Remove all old version of the above software
2. Download and run [installer](https://www.ni.com/en-us/support/downloads/drivers/download.frc-game-tools.html)
3. Run though wizard
[more...](https://docs.wpilib.org/en/latest/docs/getting-started/getting-started-frc-control-system/frc-game-tools.html)

##### Java Development Environment (JDK)

Use:
> A JDK is needed to compile robot code. If the computer is only a drive computer then the JDK is not required.

Steps:

1. Download OpenJDK ([JDK-13](https://jdk.java.net/13/))
2. Extract OpenJDK to C:\Program Files\Java\
3. Add JDK to path
> 1. search Environment Variables and open it
 2. edit PATH in "System Variables"  
 3. add C:\Program Files\Java\\*JDK-Folder-Name*\bin
4. Add Java_Home System Variable
> 1. search Environment Variables and open it
 2. Click "new" under "System Variables"
 3. enter ' "C:\Program Files\Java\\*JDK-Folder-Name*" '
5. (optional) open command line and run java -version to test if JDK is installed

##### Integrated Development Environment (IDE)

Use:
> A IDE is a code editor. It handles code highlighting, error checking, auto complete, and code compile and deploy.

1. Download and install [VScode](https://code.visualstudio.com/Download)
2. Open plugin tab and search and install "[Java Extension Pack](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-pack)"
3. Open plugin tab and search and install "[WPILib](https://marketplace.visualstudio.com/items?itemName=wpilibsuite.vscode-wpilib)"

##### Git

Use:
> git is version control software to help development between several people computers and changes.

1. Download and run git [installer](https://git-scm.com/downloads)
