# SIMULATION-FRAME-V-S-DELTA-ENERGY-MMPBSA
This code is creating a bar chart of the data contained in the data.csv file. The chart is generated using the px.bar function from the plotly.express library, which creates a bar chart with x and y axis values specified by the x and y parameters, respectively. In this case, the x-axis is Simulation Frames and the y-axis is ∆E Binding (KJ/mol).

The color of each bar is set based on the ∆E Binding (KJ/mol) value, with the color parameter set to this column. The color gradient used is set with the color_continuous_scale parameter to px.colors.sequential.Plasma. The range_color parameter sets the range of the color gradient to be between -150 and 100.

The chart is then updated with additional information using the update_layout function, such as x and y axis labels, title, and background color, which is set to white using the plot_bgcolor parameter. Finally, the chart is displayed using the show function.

