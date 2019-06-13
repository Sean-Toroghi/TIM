TIM application


To facilitate the computation of resilience, we developed the TIM (Toolkit for Resilience Measurement) application. TIM is a stand alone executable application that is developed in two versions for Windows and Machintach operating systems. Both versions shares a similar user interface (Figure II- 1).To run TIM, there is no need to pre-install any other application. Users can enter all required input variables into the TIM and get the results. TIM computes the resilience capacity of the system as well as the fiv resilience dimensions. TIM is divided into three sections: input variables, results, and Other features. This appendix provides a brief manual for using the TIM to compute the resilience dimensios and capacity. Readers can access TIM via the Github depository at www.github.com/Sean-Toroghi/TIM.
 
 
Figure II- 1 - TIM user interface (Top: Windows Operation System, and Bottom: MacintoshOperation System).
In the input variables section, users can enter the information required for computing the resilience dimensions and capacity. Figure II- 2 illustrates the TIM interface with red dashed rectangles highlighting the input section. The system performance level contains five variables in three groups. The performance-level prior to an incident indicates the system performance level under normal operation conditions. The performance level after the incident indicates the system performance level immediately after the incident when it reaches a stable level. The recovery process has not yet started at this point. The three control points, (F_1, F_2, and F_3) represent the system performance level for each end-user type at the time the recovery process is finished for the priority, urgent, and routine categories, respectively. If there exist DG systems in the region under investigation, the users can enter the capacity of the DG systems as a percentage of consumption for each end-user category. 
To compute the Rapidity capacity, users are required to enter the variables in the recovery process section. The unit of time for the three variables in this section (tim scale factor, slack time, and duration of the recovery process) should be consistant. Finally the weight factors for both the end-user types and resilience dimensions provides the capability for user to apply any prioritization according to the results of other complimentary analysis such as life-cycle cost analysis.

 
Figure II- 2 – TIM application: input variables. 
To compute the results, users need to click on the associated buttons in the resilience dimensions and capacity section, highlighted by the green dashed rectangle in Figure II- 3. The computation of results is based on the formulation presented in this paper. Five buttons are allocated to compute the five resilience dimensions, separately. The resilience (R) button computes the system resilience capacity and five resilience dimensions together.
The TIM application is enhaced with some other features to facilitate and aid users’ interaction. Users can reset the input variables to default values by clickig on the reset button. Also at any point, users can save the input variables by clicking the save button and save the input data in the computer. The user can later retrieve the saved data by clicking on the load button. Also, the input data of the notional examples (the three scenarios of the first example and two scenarios of the second example) in this article are provided  thourgh the “input variable: notional examples” section, in which the user can click on any of the five buttons representing the associated scenario and the application will automatically change the input variable to the ones used for that particular scenario. Figure II- 5 thorugh II-8 illustrate the input varibles of the five scenarios. A brief description of each section is available to the users by clicking on the question mark orange buttons.

 
Figure II- 3 - TIMapplication: compute the results.

 
Figure II- 4 -TIM: input variables of the blackout scenario.
 
Figure II- 5 - TIM: input variables of the blackout plus DG scenario.
 
Figure II- 6 - TIM: input variables of the partial blackout scenario.
 
Figure II- 7- TIM: input variables of the targeted incident scenario.
 
Figure II- 8 TIM: input variables of the scattered incident scenario.
