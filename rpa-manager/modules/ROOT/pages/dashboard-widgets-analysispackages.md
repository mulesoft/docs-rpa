# <i class="fs fs-lg fs-dashboard"></i> Dashboard - Widgets - Analysis Packages

![rpa_Dashboard_Widgets_AnalysisPackages](img/rpa_Dashboard_Widgets_AnalysisPackages.png)

The **Analysis Packages** widget displays the number of analysis packages of all *X1 Bots* collected during the analysis interval.

**Analysis packages** contain data on the sequence of execution of an individual process element of type **Trigger** or **Activity**.

!!! rocket-launch ""
    **Analysis packages** are normally only created in the event of errors.

    Robots, for which the option **Analysis Package on OK** is activated in the  *X1 Bot Configurator*, create an analysis package for each process element during each run.


## Data representation

The number of analysis packages is a [**link**](../../X1_Server/X1_Server_Basics/GUI/rpa_X1_Server_Basics_GUI_Navigation_EN.md#links).


## Configuration

This widget cannot be configured.

!!! rocket-launch ""
    Use the sorting and filter options of the [**Analysis Packages**](#drill-down) list to highlight the information that is relevant for you.


## Drill-down

Click on the number of all collected analysis packages to obtain a list of all analysis packages listed individually.

![rpa_Dashboard_Widgets_AnalysisPackages_Drilldown](img/rpa_Dashboard_Widgets_AnalysisPackages_Drilldown.png)

### Data representation of the analysis packages

The analysis packages are displayed in a [list](../../X1_Server/X1_Server_Basics/GUI/rpa_X1_Server_Basics_GUI_DataRepresentation_EN.md#lists).

### Columns of the **Analysis Packages** list

#### Process

[Name](../../ProcessAutomation/ProcessManagement/rpa_processAutomation_ProcessManagement_Category_Projects_EN.md#process-name) of the process

#### Robot

Name of the *X1 Bot* that carried out configuration of the Process

#### Configuration

Name of the [Configuration](../../ProcessAutomation/ProcessManagement/rpa_processAutomation_ProcessManagement_Category_Project_Details_ProductionPhase_EN.md#erstellen-einer-neuen-production-configuration) in which the Process was executed

#### Category

[Category](../../ProcessAutomation/ProcessManagement/rpa_processAutomation_ProcessManagement_Categories_EN.md) to which the Process belongs.

#### Type

Type of workflow to which the analysis package belongs.

##### Trigger

Trigger workflow

##### Activity

Activity workflow

#### Run Type

Type of process execution

##### Test

The Process was executed during the **Test** phase.

##### Productive

The Process was executed in productive operation.

#### Start time

Time stamp of the start of execution of the process element **Trigger** or **Activity**.

#### End Time

Time stamp of the end of execution of the process element **Trigger** or **Activity**.

#### Duration

Duration of execution of the process element **Trigger** or **Activity**.

#### Result

Result of the process execution

##### Triggered

The trigger workflow was executed successfully but there was no task pending.

##### Success

The activity workflow was executed successfully.

##### Execution Failure

An error occurred during execution of a workflow.

#### Download

If an analysis package was created, you can download it by clicking on the icon <i class="fas fa-download"></i> **Download**.
