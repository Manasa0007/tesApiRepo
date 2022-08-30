# testApiRepo
Postman testing and validating for generic host link

### Test Desciption:
The code attached consists of postman Collection to execute for 

1. API- https://api.publicapis.org/entries

#### Environments
This has one Environment "apiTest_v1" and have a host in base_url as https://api.publicapis.org/entries. This is a dynamic host which could be changed when required.

Tests Base URL could be parameterised to execute in different environment

<img width="1131" alt="image" src="https://user-images.githubusercontent.com/112477826/187408079-81143089-a171-47a7-acc2-2589581d7cf0.png">

#### Test Cases:
The above API has been tested with multiple test cases as below:
1. Test-01: Status code is 200
2. Test02: Body matches count number
3. Test03: Validate Schema Check
4. Test04: Response time is less than 1500ms

<img width="726" alt="image" src="https://user-images.githubusercontent.com/112477826/187408582-fb4e204d-7511-4752-942f-35b467386422.png">

 All the above test cases are asserted with presumed values.
