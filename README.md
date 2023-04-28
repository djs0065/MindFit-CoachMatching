# MindFit-CoachMatching
Semi-automated matching of students and coaches within the WVU MindFit Academic Enhancement Program. Helpful user-forms and constantly updating system to track hours and matches between program participants. *Sensitive Information Removed*

# Version History
- V2.0 04/28/23
   - Additions:
       - Added a comment box on the coaches assigned to a student on the "activeMatching" sheet which contains the courses that coach is covering for the student
       - Added a comment box on the coaches in the "coachExport" sheet(s) showing what courses they are covering for the student
       - Added a "Hide?" column to student and coach sheets to allow for "hiding" of specific students/coaches from the matching algorithm
       - Added "Email" and "Phone #" columns to student sheet for the coach packet feature
       - Added "Create Packets" button to the "activeMatching" sheet
           - Will automatically create coach packets (individual PDFs) containing necessary information, within a "coachPackets" folder in the Excel document's directory
   - Fixes:
       - Fixed an unknown error causing the mismatching of comments concerning covered courses. Instead of checking the 1,2,3,4 coach assigned to a student it was checking the 1,2,3,4 coach for the student 1 and the 5,6,7,8 coach for student 2 and so on instead of a constant 1,2,3,4
       
- V1.01 11/15/22
   - Additions:
       - Added userForm allowing for new prospectiveMatches to be made WITHOUT overwriting the activeMatching sheet, optionality to overwrite still exists
   - Fixes: 
       - Fixed error on formatting the student/coach information sheets due to sheet protection
