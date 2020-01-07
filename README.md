# EthosTest
short scripts that read and publish to Ethos

APIKey -- add your Ethos API key to the apiKey variable in this file<br>
bearer -- run getKey to populate a security key into this file<br>
consume -- after running getKey, run this to get seme users from Ellucian's Ethos sand box<br>
createPerson -- Add Ron Weasly to Banner :-)<br>
createPersonMweasley -- Add Molly Weasley<br>
createPersonPweasley -- Add Percy Weasly<br>
getEmployee -- Get all users with the employee role, unfortunatley, there are only students<br>
getKey -- use the APIKey to get a bearer key -- run this first!<br>
getRole -- get persons with a student role<br>
getSpecificPerson -- look up a user by SPRIDEN id, Ethos calls it the Banner ID<br>
<br>
Quick demo:<br>
<br>
Create a file named APIKey, it needs one line that sets a shell variable named apiKey, it should look something like:
<br>
apiKey=9839acb-2820bf88-abcdef123456-098765fedcba<br>
<br>
mbrookov@myrddin EthosTest % ./getKey <br>
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current<br>
                                 Dload  Upload   Total   Spent    Left  Speed<br>
100   409  100   409    0     0   1019      0 --:--:-- --:--:-- --:--:--  1017<br>
mbrookov@myrddin EthosTest % ./consume<br>
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current<br>
                                 Dload  Upload   Total   Spent    Left  Speed<br>
100 22204  100 22204    0     0  47042      0 --:--:-- --:--:-- --:--:-- 46942<br>
mbrookov@myrddin EthosTest % <br>
<br>
Look in the file named consume.json.<br>


