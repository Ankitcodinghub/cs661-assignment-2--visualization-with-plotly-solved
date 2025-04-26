# cs661-assignment-2--visualization-with-plotly-solved
**TO GET THIS SOLUTION VISIT:** [CS661 Assignment 2 -Visualization with Plotly Solved](https://www.ankitcodinghub.com/product/assignment-2-cs661-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;132070&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS661 Assignment 2 -Visualization with Plotly Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
&nbsp;

In this assignment, you will create a simple interactive interface using Plotly and Jupyter Widgets. Plotly will be used for generating visualizations and Jupyter Widgets will be used to add sliders and buttons.

Reference for Jupyter Widgets: https://ipywidgets.readthedocs.io/en/stable/

Sliders and Buttons: https://ipywidgets.readthedocs.io/en/stable/examples/Widget%20Events.html

Here is what your interface should do:

1. In the left side, your interface should show an interactive Isosurface visualization of the 3D dataset provided with this assignment. Plotly has an API to draw Isosurfaces. [See Fig. 1]

3. Your interface should contain a slider that allows changing the isovalue for the Isosurface. This slider value range should be mapped to the entire data range and by sliding to through different scalar values, the Isosurface plot should get updated automatically. You should also color your Isosurface using a standard Python/Plotly colormap so that the color of your Isosurface changes as you change the isovalue. I have used colormap ‘plasma’ in this example. You can use Jupyter Widgets to add the slider. [See Fig. 1]

4. At the beginning, you should show Isosurface of isovalue=0.0 and the histogram of the entire volume data set as seen in the Figure. [See Fig. 1]

5. When you change your slider, you will also update the histogram plot. Let’s say, you have selected the isovalue = x from the slider by changing it. Then your histogram plot should contain data points with the following conditions: (x – 0.25) &lt;= points with data values in histogram &lt;= (x + 0.25). So, essentially, you will update the histogram plot with data values around (within +/- 0.25) your current selected isovalue from the slider. This will be histogram of a subset of the data and your histogram axes labels should get updated with the new data range. [See Fig. 2]

6. Finally, you will add a button called ‘Reset’. When this button is clicked, the plot will get reset to its initial/beginning configuration, i.e., the slider value should be set back to 0.0, Isosurface plot should get updated with the isovalue = 0.0, the histogram plot should show the histogram of the entire data set and not of a subset. You can use Jupyter Widgets to add the button. [See Fig. 1 and 2]

7. Your interface should be interactive, and users can change the slider value freely to see different isosurfaces and the corresponding histograms.

If you have done everything as suggested, you should see images like the following for volume rendering:

Fig. 2: Plot when the slider is changed. Note the change in surface structure, surface color, and histogram shape, different range for histogram axes.

Dataset for this task:

The dataset that you will use in this assignment is a 3D scalar field volume data of a turbulence mixture simulation. The VTI file is provided with the assignment.

How to submit?

“groupnum_rollnum1_rollnum2_Assignment2.zip”.

** You must ensure you are submitting your correct submission files. If you upload wrong files, you will not be allowed to submit again. We will only grade your submitted version from HelloIITK. No submissions will be accepted after the allowed late days. **
