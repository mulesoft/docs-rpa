# <i class="fs fs-lg fs-dashboard"></i> Dashboard - Widgets - Profit Analysis: Process Frequency

![rpa_Dashboard_Widgets_ProfitAnalysis_ProcessFrequency_Daily](img/rpa_Dashboard_Widgets_ProfitAnalysis_ProcessFrequency_Daily.png)

![rpa_Dashboard_Widgets_ProfitAnalysis_ProcessFrequency_MonthlyAggregated](img/rpa_Dashboard_Widgets_ProfitAnalysis_ProcessFrequency_MonthlyAggregated.png)

The widget **Profit Analysis: Process Frequency** shows how often a Process has been executed productively within a specific interval compared to its previous frequency of execution.

You can see at a glance whether a Process can be executed more frequently by an *X1 Bot* or by a human employee, and to what extent the frequencies differ.


## Data representation

The execution duration of the individual configurations is shown as a [Line Chart](../../X1_Server/X1_Server_Basics/GUI/rpa_X1_Server_Basics_GUI_DataRepresentation_EN.md#linien-diagramme). A colored line corresponds to a configuration.

The time interval is shown on the X axis, the execution duration of the individual runs is shown in seconds on the Y axis.

The manual execution duration in seconds is represented by a horizontal red line.

You can see the exact data if you hover the mouse over any point.

If, in the evaluation of the Process, a value is entered under [**Frequency per month**](../../ProcessEvaluation/ProcessEvaluation/rpa_ProcessEvaluation_ProcessDetails_EN.md#frequency-per-month), this is displayed as a red line in the graphic.

!!! rocket-launch ""

    If you drag the mouse over a bar, you can see the exact number of Process executions on this day or in this month.

!!! rocket-launch ""
    If the display interval is less than one month, the value **Frequency per month** is divided by 30 to enable a comparison of the execution frequency of individual days.

    If the display interval is more than one month, the execution frequencies for each month are aggregated to enable a comparison of the monthly values.


## Configuration

![rpa_Dashboard_Widgets_ProfitAnalysis_ProcessFrequency_Configuration](img/rpa_Dashboard_Widgets_ProfitAnalysis_ProcessFrequency_Configuration.png)

You can select an individual Process, whose execution frequency is to be displayed, from the drop-down list.

The processes are displayed below their category. Categories and processes are sorted alphabetically.

!!! rocket-launch ""
    You can only select from those processes for which you are a member of the [**Process team**](../../ProcessAutomation/ProcessManagement/rpa_processAutomation_ProcessManagement_Category_Projects_EN.md#process-team). Other processes are not displayed.


## Drill-down

This widget does not contain any drill-down data.
