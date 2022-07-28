# <i class="fs fs-lg fs-dashboard"></i> Dashboard - Widgets - Business Process Performance

![rpa_Dashboard_Widgets_BusinessProcessPerformance](img/rpa_Dashboard_Widgets_BusinessProcessPerformance.png)

The **Business Process Performance** widget shows for each Process of a Customer, how often the Process has been triggered within the analysis interval and how long the average execution time was.

!!! rocket-launch ""
    A Process is carried out if its **Trigger Workflow** has identified the prerequisites for it. You [configure](../../ProcessAutomation/ProcessManagement/rpa_processAutomation_ProcessManagement_Category_Project_Details_ProductionPhase_EN.md#process-trigger-execution) the frequency of execution of the **Trigger Workflow** in the **Process Management** module.

!!! rocket-launch ""
    The number and average runtimes of this widget only take account of processes that have been completed successfully.


## Data representation

The Processes are displayed in a [**list**](../../X1_Server/X1_Server_Basics/GUI/rpa_X1_Server_Basics_GUI_DataRepresentation_EN.md#lists).

### Columns of the list of Business Process Performance of all processes

#### Process

Name of the process

!!! rocket-launch ""
    Click on the name of a Process to see [Details of the individual process runs](#drill-down).

#### Execution count

Number of successful executions of the Process in the defined time period

#### Average runtime

Average runtime of all successful executions of the Process in the defined time period


## Configuration

This widget cannot be configured.

!!! rocket-launch ""
    Use the sort and filter options of the [**Business Process Performance of an individual Process**](#drill-down) list to highlight the information that is relevant for you.


## Drill-down

If you click on the name of a Process, you can view details of the individual runs of this Process.

![rpa_Dashboard_Widgets_BusinessProcessPerformance_Drilldown](img/rpa_Dashboard_Widgets_BusinessProcessPerformance_Drilldown.png)

### Data representation of the list of Business Process Performance of an individual Process

The Process runs are displayed in a [**list**](../../X1_Server/X1_Server_Basics/GUI/rpa_X1_Server_Basics_GUI_DataRepresentation_EN.md#lists).

### Columns of the list of Business Process Performance of an individual Process

#### Robot

Name of the Robot that executed the Process run successfully.

#### Configuration

Name of the [Configuration](../../ProcessAutomation/ProcessManagement/rpa_processAutomation_ProcessManagement_Category_Project_Details_ProductionPhase_EN.md#liste-aller-production-configurations) that was used for the successful run

#### Type

Type of Process run

##### Test

The Process was executed as a test run

##### Productive

The Process was executed as a productive run

#### Start time

Time stamp of the start of the Process execution

#### End Time

Time stamp of the end of the Process execution

#### Duration

Duration of the Process execution

#### Result

Result of the process execution

##### Success

The Process run was executed successfully
