# Covid-19-cases-analysis-in-India
Covid-19 cases analysis in India

https://www.mohfw.gov.in/data/datanew.json  ---> This is the link from which you can fetch the information.
you can use this link and store the information in pandas dataframe and start your analysis.

"df1=df.iloc[:,1:3]
df1.plot.barh(color={"cured": "red", "positive": "green"},figsize=(10,10))"

received an error for above line of code Error: "ValueError: 'cured' is neither a valid single color nor a color sequence consisting of single character color specifiers such as 'rgb'. Note also that the latter is deprecated."

Instead you can use: "df1.plot.bar(color={"blue": "new_cured", "green": "new_positive", "red": "new_death"},figsize=(16,6))"
