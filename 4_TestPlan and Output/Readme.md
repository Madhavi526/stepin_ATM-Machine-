## TEST PLAN

## Table no:HIGH LEVEL TEST PLAN
|Test ID|Description|Exp I/P|Exp O/P|Actual I/P|Actual O/P|
|--------|----------|-------|-------|----------|-----------|
|HLT1|checking all the functions are working correcty|Call the functions|All functions execute correctly|All functions are executed correctly|Requirement based|
|HLT2|Checking whether called functions are executed|Call a specific function|Call function execute|Called function is executed|Scenario based|
|HLT3|Check for features other than specified|Choosing other values|No output displayed|No output is displayed|Boundary based|

## Table No: LOW LEVEL TEST PLAN
|Test ID|Description|Exp IN|Exp OUT|Actual I/P|Actual O/P|
|------|------------|------|-------|----------|----------|
|LLT1|Checking accept function is accepting users information|user details|accept the details|accept the details|Requirement based|
|LLT2|Checking deposit method is able to update balance|amount to be deposited|updated balance|updated balance|Scenario based|
|LLT3|checking withdraw method display insufficient balance if balance is low|amount to withdraw|low balance|low balance|Boundary based|
|LLT4|search for record not present|No information displayed|user id|No information displayed|No information displayed|
|LLT5|checking withdraw method is able to withdraw for sufficient balance|amount to be withdrawn|updated balance|updated balance|Scenario based|
|LLT6|search for record present|information displayed|user id|information displayed|information displayed|
|LLT7|display the users|information displayed|choosing display option|information displayed|information displayed|
