# <i class="fs fs-lg fs-dashboard"></i> Dashboard - Widgets - Current Robot Status

![rpa_Dashboard_Widgets_CurrentRobotStatus](img/rpa_Dashboard_Widgets_CurrentRobotStatus.png)

In the **Current Robot Status** widget, you can see at a glance which of your Robots are ready for use.


## Data representation

The numbers of Robots in each case are [**links**](../../X1_Server/X1_Server_Basics/GUI/rpa_X1_Server_Basics_GUI_Navigation_EN.md#links) displayed together with a graphical representation of the ratio of those Robots ready for use compared to those not ready.

The length of the green line labeled with <i class="fas fa-check-circle"></i> **Ready** corresponds to the number that are ready for use; the length of the red line labeled with <i class="fas fa-exclamation-triangle"></i> **Not Ready** corresponds to the number not ready.


## Configuration

This widget cannot be configured.


## Drill-down

Click on a number to obtain a list of all Robots or only those Robots with a specific status.

![rpa_Dashboard_Widgets_CurrentRobotStatus_Drilldown_Total](img/rpa_Dashboard_Widgets_CurrentRobotStatus_Drilldown_Total.png)

![rpa_Dashboard_Widgets_CurrentRobotStatus_Drilldown_Ready](img/rpa_Dashboard_Widgets_CurrentRobotStatus_Drilldown_Ready.png)

![rpa_Dashboard_Widgets_CurrentRobotStatus_Drilldown_NotReady](img/rpa_Dashboard_Widgets_CurrentRobotStatus_Drilldown_NotReady.png)


### Data representation of the current Robot status

The Robots are displayed in a [list](../../X1_Server/X1_Server_Basics/GUI/rpa_X1_Server_Basics_GUI_DataRepresentation_EN.md#lists).

### Columns of the **Current Robot Status** list

#### Status

##### OK

The Robot is ready for use.

##### Stopped

The Robot is not ready for use because it has been stopped.

##### No License

The Robot is not ready for use because it is not licensed.

#### Robot

Name of the Robot

!!! rocket-launch ""
    Click on the name of the Robot to get to its [Detailed view](../../RobotManagement/Robots/rpa_robotManagement_Robots_RobotDetails_EN.md).

#### Processing

<i class="fas fa-check"></i> A process configuration has been [deployed](../../ProcessAutomation/ProcessManagement/rpa_processAutomation_ProcessManagement_Category_Project_Details_TestPhase_EN.md#x1-bots) for the Robot.

<i class="fas fa-times"></i> No process configuration has been [deployed](../../ProcessAutomation/ProcessManagement/rpa_processAutomation_ProcessManagement_Category_Project_Details_TestPhase_EN.md#x1-bots) for the Robot.
