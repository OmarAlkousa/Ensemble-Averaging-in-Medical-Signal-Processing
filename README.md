# Ensemble Averaging in Medical Signal Processing [**[Code]**](https://github.com/OmarAlkousa/Ensemble-Averaging-in-Medical-Signal-Processing/blob/c1040f12f73a1f0055bcf047b8e29888e33ceec1/Ensemble_Averaging_in_Medical_Signal_Processing.ipynb) [**[Towards Data Science]**](https://medium.com/towards-data-science/ensemble-averaging-in-medical-signal-processing-17116d0cf0d2)

Dealing with data as a researcher, a data scientist/analyst,  or even in any science field is inevitable. Thus, the reliability of the data you're working with is crucial as it decides the reliability of your work.

In this notebook, we will introduce the ensemble averaging method, a simple but powerful method, and its applications on signal data, specifically the medical signals. The image below represent the idea of ensemble averaging method.

<p align="center">
  <img src="https://github.com/OmarAlkousa/Ensemble-Averaging-in-Medical-Signal-Processing/blob/8ae7c2fc08a1759dfdb9adc5845773e58de40a20/Ensemble%20Average.png", width="400">
</p>

With the Ensemble averaging method, we will demonstrate how we can determine the Visual Evoked Response (VER), refer to the [notebook](https://github.com/OmarAlkousa/Ensemble-Averaging-in-Medical-Signal-Processing/blob/8ae7c2fc08a1759dfdb9adc5845773e58de40a20/Ensemble%20Averaging%20in%20Medical%20Signal%20Processing.ipynb) for more details. The figure below is to visualize the first 10 signals of the electrical signals generated in the visual cortex. You can see that you cannot determine the visual response based on these signals individually.

<p align="center">
  <img src="https://github.com/OmarAlkousa/Ensemble-Averaging-in-Medical-Signal-Processing/blob/8ae7c2fc08a1759dfdb9adc5845773e58de40a20/10%20Signals.png">
</p>

Therefore, we use ensemble averaging on 100 signals to get the visual response (VER). The image below represents applying this method.

<p align="center">
  <img src="https://github.com/OmarAlkousa/Ensemble-Averaging-in-Medical-Signal-Processing/blob/8ae7c2fc08a1759dfdb9adc5845773e58de40a20/VER.png">
</p>

## References
[**[1]**](https://doi.org/10.1016/B978-0-12-809395-5.00002-3) Semmlow, J. (2018). Signal Analysis in the Time Domain. In Circuits, Signals and Systems for Bioengineers (pp. 51–110). Elsevier. https://doi.org/10.1016/B978-0-12-809395-5.00002-3

[**[2]**](https://www.ijarcce.com/upload/2016/august-16/IJARCCE%2052.pdf) Thomas, T. (2005). Ensemble Averaging Filter for Noise Reduction. International Journal of Advanced Research in Computer and Communication Engineering, 5(8).

[**[3]**](https://eyewiki.aao.org/Visual_Evoked_Potential/_Response_(VEP/VER)) Tripathy, K.,  Hsu, J., & Lim, J. (2022, November 10). Visual Evoked Potential/ Response (VEP/VER). American Academy of Ophthalmolog.
