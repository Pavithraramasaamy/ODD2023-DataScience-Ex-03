# EX03- UNIVARIATE ANALYSIS

## AIM:
  To read the given data and perform the univariate analysis with different types of plots.

## ALGORITHM:

# STEP 1:
Read the given data.

# STEP 2:
Get the informations and type of datas.

# STEP 3:
Count the values using value_counts().

# STEP 4:
Describe the dataframe.

# STEP 5:
Do plots like boxplots,countplot,distribution plot,histogram plot.

## PROGRAM:
```
Developed by:PAVITHRA R
Register number:212222230106

FOR DIABETES:
import pandas as pd
df=pd.read_csv("/content/diabetes.csv")
df
df.info()
df.dtypes
df['DiabetesPedigreeFunction'].value_counts()
df.describe()
import seaborn as sns
sns.boxplot(x='SkinThickness',data=df)
sns.countplot(x="SkinThickness",data=df)
sns.distplot(df['SkinThickness'])
sns.histplot(x="SkinThickness",data=df)
df.skew()
sns.histplot(x='Insulin',data=df)
sns.distplot(df['BloodPressure'])
df.kurtosis()
sns.boxplot(x='Insulin',data=df)
sns.boxplot(x='SkinThickness',data=df)

FOR EMPLOYEESAL:

import pandas as pd
df=pd.read_csv("/content/employeesal.csv")
df
df.info()
df.dtypes
df['Salary'].value_counts()
df.describe()
import seaborn as sns
sns.boxplot(x='Experience_Years',data=df)
sns.countplot(x="Experience_Years",data=df)
sns.distplot(df['Experience_Years'])
sns.histplot(x="Experience_Years",data=df)
df.skew()
sns.histplot(x='Salary',data=df)
sns.distplot(df['ID'])
df.kurtosis()
sns.boxplot(x='Salary',data=df)
sns.boxplot(x='Experience_Years',data=df)

FOR SUPERSTORES:

import pandas as pd
df=pd.read_csv("/content/SuperStore.csv")
df
df.info()
df.dtypes
df['Sales'].value_counts()
df.describe()
import seaborn as sns
sns.boxplot(x='Postal Code',data=df)
sns.countplot(x="Postal Code",data=df)
sns.distplot(df['Postal Code'])
sns.histplot(x="Postal Codes",data=df)
df.skew()
sns.histplot(x='Sales',data=df)
sns.distplot(df['Postal Code'])
df.kurtosis()
sns.boxplot(x='Sales',data=df)
sns.boxplot(x='Row ID',data=df)
```

## OUTPUT:

## FOR DIABETES:

DATASET:

![1](https://github.com/Pavithraramasaamy/ODD2023-DataScience-Ex-03/assets/118596964/e4e9c147-0251-401e-9f5f-587bb90c5745)


INFO:

![2](https://github.com/Pavithraramasaamy/ODD2023-DataScience-Ex-03/assets/118596964/bd05c4c6-3644-464d-822f-3c75d6d1116e)


DTYPES:

![3](https://github.com/Pavithraramasaamy/ODD2023-DataScience-Ex-03/assets/118596964/ec7e97ac-dfde-45f8-9801-ee4d85609078)


VALUE COUNTS:

![4](https://github.com/Pavithraramasaamy/ODD2023-DataScience-Ex-03/assets/118596964/4b961f2b-306f-42cd-8008-96f498dc01b4)


DESCRIBE:

![5](https://github.com/Pavithraramasaamy/ODD2023-DataScience-Ex-03/assets/118596964/f77c773f-3968-453b-a6d8-34f21ecf1bcc)


SKINTHICKNESS BOXPLOT:

![6](https://github.com/Pavithraramasaamy/ODD2023-DataScience-Ex-03/assets/118596964/9d0c914a-5bd1-4526-b262-344827612f96)


SKINTHICKNESS COUNTPLOT:

![7](https://github.com/Pavithraramasaamy/ODD2023-DataScience-Ex-03/assets/118596964/eb86a6b9-ec54-4c46-bac1-1da60acdbae9)



SKINTHICKNESS DISTPLOT:

![8](https://github.com/Pavithraramasaamy/ODD2023-DataScience-Ex-03/assets/118596964/0d5a997d-5627-431f-8fff-6325e3d47c53)



SKINTHICKNESS HISPLOT:

![9](https://github.com/Pavithraramasaamy/ODD2023-DataScience-Ex-03/assets/118596964/6b856c35-9d53-4887-a472-a85127c799f9)


SKEW:

![10](https://github.com/Pavithraramasaamy/ODD2023-DataScience-Ex-03/assets/118596964/5cbb6ab9-6ede-4ed6-8a83-03cfdb13ece1)


INSULIN HISPLOT:

![11](https://github.com/Pavithraramasaamy/ODD2023-DataScience-Ex-03/assets/118596964/ec3c9e4f-8fff-4824-9c5b-f56b17bfa003)


BLOODPRESSURE DISPLOT:

![12](https://github.com/Pavithraramasaamy/ODD2023-DataScience-Ex-03/assets/118596964/3c6be5bb-1599-413d-8503-7e3deaa775b4)


KURTOSIS:

![13](https://github.com/Pavithraramasaamy/ODD2023-DataScience-Ex-03/assets/118596964/ddcc247b-35ae-4d85-84c0-2c56e64cf734)


INSULIN BOXPLOT:

![14](https://github.com/Pavithraramasaamy/ODD2023-DataScience-Ex-03/assets/118596964/b50a91ec-80e9-4a91-ba95-db8d41be40d7)


## FOR EMPLOYEESAL:

DATASET:

![1](https://github.com/Pavithraramasaamy/ODD2023-DataScience-Ex-03/assets/118596964/708b3d3a-19a2-4eeb-8a2c-90ef73f89afd)


INFO:

![2](https://github.com/Pavithraramasaamy/ODD2023-DataScience-Ex-03/assets/118596964/79fc7454-88d6-4aff-aa90-9fbd8f02fa98)


DTYPES:

![3](https://github.com/Pavithraramasaamy/ODD2023-DataScience-Ex-03/assets/118596964/bfb9acce-74a7-4149-a5c1-e40fcc04833c)



SALARY VALUE COUNTS:

![4](https://github.com/Pavithraramasaamy/ODD2023-DataScience-Ex-03/assets/118596964/e0dbf27a-d2b4-4d27-a745-c08c0ebd6df7)


DESCRIBE:

![5](https://github.com/Pavithraramasaamy/ODD2023-DataScience-Ex-03/assets/118596964/52101999-c0c2-4f50-9ddc-b84c2740af67)


EXPERIANCE YEARS BOXPLOT:

![6](https://github.com/Pavithraramasaamy/ODD2023-DataScience-Ex-03/assets/118596964/55027953-fe8e-43f5-9cc8-a2d5e4ba153b)


EXPERIANCE YEARS COUNTPLOTS:

![7](https://github.com/Pavithraramasaamy/ODD2023-DataScience-Ex-03/assets/118596964/095398f1-bbc7-4323-8696-405b9ebb0ad5)


EXPERIANCE YEARS DISTPLOTS:

![8](https://github.com/Pavithraramasaamy/ODD2023-DataScience-Ex-03/assets/118596964/a00e1798-81b9-405b-bb02-2752665f4157)


EXPERIANCE YEARS HISTPLOT:

![9](https://github.com/Pavithraramasaamy/ODD2023-DataScience-Ex-03/assets/118596964/38624490-7a74-46b5-bd4b-d64a25117c7e)


SKEW:

![10](https://github.com/Pavithraramasaamy/ODD2023-DataScience-Ex-03/assets/118596964/86a465a5-7e55-4474-98de-5a86f05e7624)



SALARY HISTPLOTS:

![11](https://github.com/Pavithraramasaamy/ODD2023-DataScience-Ex-03/assets/118596964/6c4ac7d3-e319-4643-a6a2-83ae00cc4099)


ID DISTPLOTS:

![12](https://github.com/Pavithraramasaamy/ODD2023-DataScience-Ex-03/assets/118596964/b4c26b6d-3735-4b55-96c2-5bce035e5eaa)


KURTOSIS:

![13](https://github.com/Pavithraramasaamy/ODD2023-DataScience-Ex-03/assets/118596964/41a3d759-0989-43a1-9a7b-5ff238f82f2c)


SALARY BOXPLOTS:

![14](https://github.com/Pavithraramasaamy/ODD2023-DataScience-Ex-03/assets/118596964/3fc39a83-1beb-42c4-b57d-2462d20b5859)



## SUPERSTORES:

DATASET:

![1](https://github.com/Pavithraramasaamy/ODD2023-DataScience-Ex-03/assets/118596964/868201f7-52d6-41dd-a1a9-3a997621b991)


INFO:

![2](https://github.com/Pavithraramasaamy/ODD2023-DataScience-Ex-03/assets/118596964/24dac146-4f27-4cf4-be59-0ad919a1bbf8)


DTYPES:

![3](https://github.com/Pavithraramasaamy/ODD2023-DataScience-Ex-03/assets/118596964/87b81694-2826-4038-b762-354f1ba7398d)


SALES VALUE COUNTS:

![4](https://github.com/Pavithraramasaamy/ODD2023-DataScience-Ex-03/assets/118596964/f539bc31-6c75-405c-94a7-7f857c2637b8)


DESCRIBE:

![5](https://github.com/Pavithraramasaamy/ODD2023-DataScience-Ex-03/assets/118596964/1487971c-1db8-4da1-b29b-dbbd979f51fb)


POSTAL CODE BOXPLOT:

![6](https://github.com/Pavithraramasaamy/ODD2023-DataScience-Ex-03/assets/118596964/be3421fb-98d7-409c-990d-cb472e4c983d)


POSTAL CODE COUNTPLOT:

![7](https://github.com/Pavithraramasaamy/ODD2023-DataScience-Ex-03/assets/118596964/72ac94ce-b6a0-4420-ba02-b66b31da079b)


POSTAL CODE DISTPLOT:

![8](https://github.com/Pavithraramasaamy/ODD2023-DataScience-Ex-03/assets/118596964/27367eb7-e22c-489d-a6d4-32b8843168ae)


POSTAL CODE HISTPLOT:

![9](https://github.com/Pavithraramasaamy/ODD2023-DataScience-Ex-03/assets/118596964/15326651-b8fb-4176-acaa-1d36573da006)

SALES HISTPLOT:

![10](https://github.com/Pavithraramasaamy/ODD2023-DataScience-Ex-03/assets/118596964/19a459e7-ac1c-4958-8ce9-33dedb042b2c)


POSTAL CODE DISTPLOT:

![11](https://github.com/Pavithraramasaamy/ODD2023-DataScience-Ex-03/assets/118596964/971c2753-edaf-48dd-86b8-e734a553b8c3)

KURTOSIS:

![12](https://github.com/Pavithraramasaamy/ODD2023-DataScience-Ex-03/assets/118596964/a3ebe909-0ff6-4b64-a02e-77253e0dbdc3)

SALES BOXPLOT:

![13](https://github.com/Pavithraramasaamy/ODD2023-DataScience-Ex-03/assets/118596964/f70eebd9-a7f9-429a-b15b-4dc9d8e9d457)

ROWID BOXPLOT:

![14](https://github.com/Pavithraramasaamy/ODD2023-DataScience-Ex-03/assets/118596964/d1be0c06-ca9c-4520-91d2-022ed457224e)


## RESULT:
   Thus the univariate analysis with different types of plots are verified successfully.
