# Task-SurveyConfigurator
Desktop App to add questions and edit previously created ones.
Edit Connection parameters in App.config before starting.

Naming Conventions:
- private members of class are not capitalized - their setters and getters are -> to be accessed outside
- classes of objects are preceded with cls
- instants of objects are named exactly like their class without "cls"
- procedures in SQL are named as: P_ProcedureName
- constants are capitalized CONSTANT_VARIABLE

Return Codes:
- 1 success
- 3 failed database connection
- 2 no type
- 4 no text 
- 5 failed insertion
-6 failed deleetion
-7 failed update
 
-20 invalid num of smileys
-21 invalid num of stars
-22 invalid start value (<0)
-23 end value >100
-24 end value < start value
-25 start caption too long
-26 end caption too long
 
