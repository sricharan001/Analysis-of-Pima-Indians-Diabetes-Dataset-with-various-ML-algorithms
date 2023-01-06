# Analysis-of-Pima-Indians-Diabetes-Dataset-with-various-ML-algorithms
<h3>
Using various machine learning algorithms to predict the onset of diabetes in pima people
</h3>

This extract is from https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8943493/ :
<br>
<q>Pima Indians are a Native American group that lives in Mexico and Arizona, USA. This group was deemed to have a high incidence rate of diabetes mellitus. Thus, research around them was thought to be significant to and representative of global health. The Pima Indian Diabetes dataset consisting of Pima Indian females 21 years and older is a popular benchmark dataset. This group is also significant to members of underrepresented minority or indigenous groups.</q>
<br>
<h4>salient features of my analysis</h4>
<ul>
<li>Any data that has invalid values (for example, '0' for Blood Pressure) was excluded.</li>
<li>I, as a physician, first analysed the data for trends with various plots.</li>
<li>Then, I have used various machine learning alogorithms at varying split sizes and sensitivity, specificity and accuracy were plot against each split size.</li>
<li>Best split size in most of the models was around 0.11.</li>
<li>Best model was Random Forest</li>
<li>maximum of sensitivity was 85.7%, specificity 100% (could be due to small dataset or overfitting) and accuracy 91.4% </li>
</ul>
<b>For more in-depth information of my analysis, checkout the jupyternotebook in the repository</b>
<br>
<b>More about me:</b><span><a target="_blank" href="https://sricharan.info">sricharan.info</a>
