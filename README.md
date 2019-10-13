# Cross-Language-Transferring-Experience
Dataset we collected and used in the paper.

1. 1161 issue-pairs with helpful level and issue classes.

   Description：
   
   NEW_LANGUAGE_ISSUE:Link of R issues	
   
   PARTICIPANTS:Number of participants in R issues
   
   DURATION:The duration from created to closed of R issues
   
   OLD_LANGUAGE_ISSUE:Corresponding Python issues	
   
   RELATED_LEVEL: (Helpful level) W-"not related" Y-"Direction-related level" O-"Problem-related level" R-"Solution-related"
   
   RELATED_CLASS: (Distribution of R issues)R-"Buggy" O-"Enhancement" Y-"CPC" G-"Installation" B-"I/O" P-"Misussing"
   
   ISSUE_ASKER: The issues reporters from R issues
   
   PYTHON_USER: Whether the reporter owns Python repository
   
   R_USER: Whether the reporter owns R repository
   
   MULTI-LANGUAGE_USER: Whether the reporter owns repositories in different languages

2. Tag list.

3. Helpful way list

   Description:
   
   HELPFUL_WAY: Manual judgement of the  knowledge type. A-"Code" B-"Reference" C-"Description" D-"Code Document" E-"Outer Link" F-"Related Issue"
   
   The last 6 columns (CODE, REFERENCE, DESCRIPTION, CODE DOCUMENT, OUTER LINK, RELATED ISSUE) show the knowledge types which are existed in the newer language issues. "0" represents the knowledge type is not existed, and "1" represents the knowledge type is existed.

#Updating date: 2019/10/13
