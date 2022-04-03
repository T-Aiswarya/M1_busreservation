# TEST PLAN and Corresponding Output

## High Level Test Plan

| Test ID | Description | Exp.i/p |	Exp.o/p | Actual o/p | Type of Test |
| :------:|:-----------:|:-------:|:-------:| :---------:| :-----------:|
| H_01 | Check if the welcoming page is displayed properly | Program execution | Formatted Welcome Page | Formatted Welcome Page | Requirement |
| H_02 | Check if the menu is displayed properly | Login Credentials| Formatted Menu Page | Formatted Menu Page | Requirement |
| H_03 | Not Stuck inside any Function | Function call | Proper function execution with return type and message | Proper function execution with return type and message | Requirement |

## Low Level Test Plan

| Test ID | Description | Exp.i/p |	Exp.o/p | Actual o/p | Type of Test |
| :------:|:-----------:|:-------:|:-------:| :---------:| :-----------:|
| L_01 | Verify user credentials | Password  | Success->Menu; Failure->exit  | Success->Menu; Failure->exit  | Scenario |
| L_02 | Display Menu  | Details of options   | Details Added Successfully  | Details Added Successfully   | Technical  |
| L_03 | Contact details Entry s | Details of the individual  | ->Enter; details  | ->Enter; details   | Technical  |
| L_04 | Modify Entry | Details of the individual   | ->modify; details | ->modify; details | Technical  |
| L_05 | List All  | - | If entries present->List them; else display "empty file"   | If entries present->List them; else display "empty file"   | Technical  |
