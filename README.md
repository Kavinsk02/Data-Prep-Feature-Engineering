Task1 Categorical Encoding
Gender: Label Encoding (Male=1, Female=0)
City: One-Hot Encoding with drop_first=True
Size: Ordinal Encoding
Order used: Small=0, Medium=1, Large=2
Task2 Feature Scaling
Used RobustScaler on Age and Fare
Chosen because Fare contains an outlier (450)
RobustScaler handles outliers better than StandardScaler or MinMaxScaler
