# Angle of Repose deployed on Azure
The model was trained on augmented set of 49 angle of repose simulations performed in Ansys Rocky. The augmentation was performed on inside of the convex hull of 6 dimensional data with the use of linear interpolation of model, as the sensitivity analysis proven to have rather linear behavior of most parameters. The initial simulations parameters were chosen on basis of Morris Method, which optimizes trajectories between change in parameters to cover the most of the multi-dimensional space <insert  link  to  publication>.
The character of this model is to provide general initial guess used to start the calibration process, speeding it up substantialy. Model was trained with the use of Random Forsest Regressor, R2 error on data avaiable reached 0.988, while Mean Absolute Error was equal to 0.427 and Mean Squared Error to 0.3.
## How to use:
- To use the tool simply input the selected DEM parameters.
- Proceed with clicking the "Predict" button.


Feel free to send an email to: akolusz@agh.edu.pl for more information.


