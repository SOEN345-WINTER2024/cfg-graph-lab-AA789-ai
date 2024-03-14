# Soen-345-lab7

## Abdullah Amir - 40215286

### Calculator App

#### Step 1: Draw CFG Graph

![image](https://github.com/SOEN345-WINTER2024/cfg-graph-lab-AA789-ai/assets/97749196/5f7a3c5a-0445-4277-9a81-845b3eedbbf7)


#### Step 2: Compute Node coverage for the CFG

TRs = {s, 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20, e} <br>

Test Paths: <br>
[s,0,e] <br>
[s,1,e] <br>
[s,2,e] <br>
[s,3,e] <br>
[s,4,e] <br>
[s,5,e] <br>
[s,6,e] <br>
[s,7,e] <br>
[s,8,e] <br>
[s,9,e] <br>
[s,10,e] <br>
[s,11,e] <br>
[s,12,e] <br>
[s,13,e] <br>
[s,14,e] <br>
[s,15,16,20,e] <br>
[s,15,17,20,e] <br>
[s,15,18,20,e] <br>
[s,15,19,20,e] <br>



#### Step 3: Compute Edge Coverage for the CFG

TRs = { <br>
(s, 0), (s, 1), (s, 2), (s, 3), (s, 4), (s, 5), (s, 6), (s, 7), (s, 8), (s, 9), (s, 10), (s, 11), (s, 12), (s, 13), (s, 14), (s, 15) <br>
(0, e), (1, e), (2, e), (3, e), (4, e), (5, e), (6, e), (7, e), (8, e), (9, e), (10, e), (11, e), (12, e), (13, e), (14, e), (20, e) <br>
(15, 16), (15, 17), (15, 18), (15, 19), <br>
(16, 20), (17, 20), (18, 20), (19, 20) <br>
}<br>


Test Paths:
[s,0,e] <br>
[s,1,e] <br>
[s,2,e] <br>
[s,3,e] <br>
[s,4,e] <br>
[s,5,e] <br>
[s,6,e] <br>
[s,7,e] <br>
[s,8,e] <br>
[s,9,e] <br>
[s,10,e] <br>
[s,11,e] <br>
[s,12,e] <br>
[s,13,e] <br>
[s,14,e] <br>
[s,15,16,20,e] <br>
[s,15,17,20,e] <br>
[s,15,18,20,e] <br>
[s,15,19,20,e] <br>

#### Step 4: Compute Edge-Pair coverage for the CFG

TRs = { <br>
[s,0,e], [s,1,e], [s,2,e], [s,3,e], [s,4,e], [s,5,e], [s,6,e], [s,7,e], [s,8,e], [s,9,e], [s,10,e], [s,11,e], [s,12,e], [s,13,e], <br>
[s,14,15], [s,14,16], [s,14,17], [s,14,18], <br>
[14,15,19], [14,16,19], [14,17,19], [14,18,19], <br>
[15,19,e], [16,19,e], [17,19,e], [18,19,e] <br>
} <br>

Test Paths:

[s,0,e] <br>
[s,1,e] <br>
[s,2,e] <br>
[s,3,e] <br>
[s,4,e] <br>
[s,5,e] <br>
[s,6,e] <br>
[s,7,e] <br>
[s,8,e] <br>
[s,9,e] <br>
[s,10,e] <br>
[s,11,e] <br>
[s,12,e] <br>
[s,13,e] <br>
[s,14,e] <br>
[s,15,16,20,e] <br>
[s,15,17,20,e] <br>
[s,15,18,20,e] <br>
[s,15,19,20,e] <br>


### Step 5: Draw an EFG of the app
![image](https://github.com/SOEN345-WINTER2024/cfg-graph-lab-AA789-ai/assets/97749196/f8abe9e2-7072-4f67-a4f1-c01f5963b9ad)




### Kiss App

java->fr.neamar.kiss->Utils->PickAppWidgetActivity: onCreate()->onClickListener
![image](https://github.com/SOEN345-WINTER2024/cfg-graph-lab-AA789-ai/assets/97749196/0b46290f-e27c-427e-a1e2-a4e6c5545c5e)



#### Step 1: Draw CFG Graph
![image](https://github.com/SOEN345-WINTER2024/cfg-graph-lab-AA789-ai/assets/97749196/dfc2f329-2b39-45d5-959a-2dbad0c405a2)



#### Step 2: Compute Node coverage for the CFG
TRs = {s, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, e}
Test Paths :
[s,1,2,3,4,13,e] <br>
[s,2,4,5,6,8,10,12,e] <br>
[s,2,4,5,7,8,10,12,e] <br>
[s,2,4,5,8,9,10,11,12,e] <br>

#### Step 3: Compute Edge Coverage for the CFG
TRs = {(s, 1), (s,2), (1,2), (2,3), (2,4), (4,5), (4,13), (5,6), (5,7), (5,8), (6,8), (7,8), (8,9), (8,10), (9,10), (10,11), (10,12), (11,12), (12,e), (13,e)} <br>

Test Paths :
[s,1,2,3,4,13,e] <br>
[s,2,4,5,6,8,10,12,e] <br>
[s,2,4,5,7,8,10,12,e] <br>
[s,2,4,5,8,9,10,11,12,e] <br>



#### Step 4: Compute Edge-Pair coverage for the CFG
TRs = {[s,1,2], [s,2,4], [s,2,3], <br>
[1,2,3], [1,2,4], <br> 
[2,3,4], [2,4,5], [2,4,13], <br>
[3,4,5], [3,4,13], <br>
[4,13,e], [4,5,6], [4,5,7], [4,5,8], <br>
[5,6,8], [5,7,8], [5,8,9], [5,8,10], <br>
[6,8,9], [6,8,10], <br>
[7,8,9], [7,8,10], <br>
[8,9,10], [8,10,11], [8,10,12], <br>
[9,10,11], [9,10,12], <br>
[10,11,12], [10,12,e], <br>
[11,12,e] <br>
} <br>

Test Paths: <br>
[s,1,2,4,13,e] <br>
[s,1,2,3,4,13,e] <br>
[s,2,4,5,6,8,10,12,e] <br>
[s,2,3,4,5,7,8,10,12,e] <br>
[s,2,4,5,8,9,10,11,12,e] <br>
[s,2,4,5,8,10,12,e] <br>
[s,2,4,5,6,8,9,10,12,e] <br>
[s,2,4,5,6,8,10,12,e] <br>
[s,2,4,5,7,8,9,10,12,e] <br>
[s,2,4,5,7,8,10,12,e] <br>
[s,2,4,5,7,8,10,11,12,e] <br>


### Step 5: Draw an EFG of the app
![image](https://github.com/SOEN345-WINTER2024/cfg-graph-lab-AA789-ai/assets/97749196/5a0a2155-15c6-462b-975d-23a6a7d17f76)


