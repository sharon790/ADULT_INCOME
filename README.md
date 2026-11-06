# ADULT_INCOME
Removed useless columns 
Replaced the "?" with "Unknown" for columns like 'Workclass,occupation,Relationship,Native.Country'
Trim,clean & capitalized each word for columns
Converted every columns starting letter to capital using "M" language {  #"Capitalized Column Names" =Table.TransformColumnNames( #"Renamed Columns",Text.Proper)  }
