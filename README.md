# MSBD5001_Project

20729535 Cheng Ka Wai<br />
**Language:** Python <br />
**File format:** .ipynb <br />
**Package/Library:** numpy, pandas, datetime, holidays, sklearn, xgboost, catboost, hyperopt <br />
pip install holidays <br />
pip install numpy <br />
pip install pandas <br />
pip install datetime <br />
pip install sklearn <br />
pip install xgboost <br />
pip install catboost <br />
pip install hyperopt <br />

If for macOS, please be reminded to install first: <br />
brew install libomp<br />



**Features Selection:** <br />
(1) Year <br />
(2) Month <br />
(3) Day <br />
(4) Hour <br />
(5) Weekday <br />
  -Range: 0-6, indicate Monday to Sunday, e.g. Monday = 0, Sunday = 6 <br />
(6) Holiday <br />
  -Hong Kong Public Holiday, e.g. Holiday = 1, Others = 0 <br />
(7) Rainfall <br />
  -Daily Total Rainfall (mm) at the Hong Kong Observatory <br />

**Final Algorithm: XGBoost** <br />

**Testing Algorithm:** <br />
(1) Linear Regression <br />
(2) Random Forest Regression <br />
(3) XGBoost <br />
(4) CatBoost <br />

**Evaluation Method:** <br />
(1) Mean Squared Error (MSE) <br />
(2) Score from Kaggle <br />


**Reference:** <br />
[1] Daily Total Rainfall (mm) at the Hong Kong Observatory 2017, Hong Kong Observatory, https://www.hko.gov.hk/en/cis/dailyElement.htm?ele=RF&y=2017 <br />
[2] Daily Total Rainfall (mm) at the Hong Kong Observatory 2018, Hong Kong Observatory, https://www.hko.gov.hk/en/cis/dailyElement.htm?ele=RF&y=2018 <br />
