# <i class="fs fs-lg fs-dashboard"></i> Dashboard - Widgets - Trigger Performance

![rpa_Dashboard_Widgets_TriggerPerformance](img/rpa_Dashboard_Widgets_TriggerPerformance.png)

The **Trigger Performance** widget shows for each productive configuration, how many times its trigger workflow has been [**triggered**](../../ProcessAutomation/ProcessManagement/rpa_processAutomation_ProcessManagement_Category_Project_Details_ProductionPhase_EN.md#process-trigger-execution) during the analysis interval, how many times it was then executed, and how long the average execution time was.


## Data representation

The trigger runs of all configurations are displayed in a [**list**](../../X1_Server/X1_Server_Basics/GUI/rpa_X1_Server_Basics_GUI_DataRepresentation_EN.md#lists).

### Columns of the trigger performance list

#### Trigger

Name of the [Trigger workflow](../../ProcessAutomation/ProcessManagement/rpa_processAutomation_ProcessManagement_Category_Project_Details_DesignPhase_EN.md#start-event)

!!! rocket-launch "Drill-down"
    Click on the name of the trigger to see a [Detailed view](#drill-down) of all executions of the trigger workflow in the analysis interval in all configurations.

#### Process

Name of the Process that contains the trigger workflow

#### Configuration

Name of the configuration within which the trigger workflow was started

#### Execution count

Number of executions of the trigger workflow

!!! rocket-launch ""
    This number can be higher than the total of [**Work orders**](#work-orders) and  [**Work orders not found**](#work-orders-not-found) because it includes all trigger workflow executions that were started. If individual trigger workflow executions were terminated due to an error, they are not included in **Work orders** or in **Work orders not found**, but they do appear in the [Detailed view](#drill-down).

#### Work orders

The number of executions of the trigger workflow in which the trigger found pending tasks and initiated execution of the remaining Process.

#### Work orders not found

The number of executions of the trigger workflow in which the trigger did not find any pending tasks and, therefore, did not initiate execution of the remaining Process.

#### Average runtime

Average runtime of the trigger workflow

!!! rocket-launch ""
    Terminated trigger workflows are also included when calculating the average runtimes.

    If many trigger workflows have been terminated with errors, the value **Average runtime** decreases and can even be 0.


## Configuration

This widget cannot be configured.

!!! rocket-launch ""
    Use the sort and filter options of the [**Trigger Performance**](#drill-down) list to highlight the information that is relevant for you.


## Drill-down

Click on the name of the trigger to see details of all executions of the trigger workflow in all configurations.

![rpa_Dashboard_Widgets_TriggerPerformance_Drilldown](img/rpa_Dashboard_Widgets_TriggerPerformance_Drilldown.png)

### Data representation of trigger performance of a Process

The triggers are displayed in a [**list**](../../X1_Server/X1_Server_Basics/GUI/rpa_X1_Server_Basics_GUI_DataRepresentation_EN.md#lists).

### Columns of the list Trigger Performance of a Process

#### Process

Name of the Process that contains the trigger

#### Robot

Name of the Robot that executed the trigger

#### Configuration

Name of the executed configuration that contained the trigger

#### Start time

Time stamp of the start of execution of the trigger workflow

#### End Time

Time stamp of the end of execution of the trigger workflow

#### Duration

Duration of execution of the trigger workflow

#### Result

Result of the execution of the trigger workflow

##### Triggered

The trigger workflow was executed but there was no task pending.

##### Success

The trigger workflow was executed successfully and a task was pending.

##### Execution Failure

An error occurred during execution of the trigger workflow.

#### Analysis Package

If an analysis package was created for the trigger execution, you can download it by clicking on the icon <i class="fas fa-download"></i> **Download**.

!!! rocket-launch ""
    **Analysis packages** are normally only created in the event of errors.

    Robots, for which the option **Analysis Package on OK** is activated in the  *X1 Bot Configurator*, create an analysis package for each run.
