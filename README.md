# House-Prices-Advanced-Regression-Techniques

This project is about predicting house prices based on the features of the house.

I have explored the data, performed feature engineering and trained it on some keras and tensorflow algorithms whose results are shown below.

<table>
    <thead>
      <tr>
        <th>Models</th>
        <th>
Root Mean Square Error</th>
<!--         <th>Validation-Accuracy</th> -->
      </tr>
    </thead>
    <tbody>
        <tr>
            <td>RandomForestRegressor</td>
            <td>0.0529</td>
<!--             <td>89.560000</td> -->
        </tr>
      <tr>
            <td>KNeighborsRegressor</td>
            <td>0.2026</td>
<!--             <td></td> -->
        </tr>
      <tr>
            <td>Neural network</td>
            <td>0.2751</td>
<!--             <td></td> -->
        </tr>
      <tr>
            <td>LinearSVR</td>
            <td>0.2751</td>
<!--             <td></td> -->
        </tr>
      <tr>
            <td>SVR</td>
            <td>0.3021</td>
<!--             <td></td> -->
        </tr>
      <tr>
            <td>Ridge</td>
            <td>0.11589743355970451</td>
<!--             <td></td> -->
        </tr>
      <tr>
            <td>lasso</td>
            <td>0.10778109879684361</td>
<!--             <td></td> -->
        </tr>
      <tr>
            <td>XGBRegressor</td>
            <td>0.3021</td>
<!--             <td></td> -->
        </tr>
    </tbody>
</table>

Overall RMS error on test data using combined results of VotingRegressor and StackingRegressor and lasso: 0.12343
