# Regression-Model

This is the Boston Housing data frame with 506 rows and 14 columns. Will be shown modeling using Ridge and Lasso regression.

Setelah data di load, data d split menjadi 2 bagian. yaitu data train dan data test. Ternyata terdapat multicol pada dataset ini. There is multicollinearity in the data we have. It can cause a harmful impact. That is, the coefficient on the training data can become unstable

dengan membuat corelation heatmap kita bisa menentukan featur mana yang perlu dihapus untuk menghilangkan multi col. setelah memastikan lagi tidak ada multi col, maka bisa dilakukan train data. pada dataset ini mengunakan permodelan regressi ridge dan laso maka kita perlu menentukan nilai lambda terbaik. 

swtanjutkan bisa dilakukan diagnostic study untuk melihan nilai r2. hasil yang didapat adalah  pada lasso dan ridge adalah diats 70%
