# 16 Bit Pipelined Processor Design
16-bit MIPS-like processor with eight 16-bit general-purpose registers.


## Pipelined Processor:
![image_2024-05-13_00-50-23](https://github.com/Sameer-13/16-Bit-Pipelined-Processor-Design/assets/106761486/f969ca9d-f48f-4e8d-acbd-3492429b43b5)


## Single Cycle Processor:
![Single cycle image](https://github.com/Sameer-13/16-Bit-Pipelined-Processor-Design/assets/106761486/98800e9b-3de8-46d6-b484-fcab0870eb3f)


## Instructions Types Format:
![image](https://github.com/Sameer-13/16-Bit-Pipelined-Processor-Design/assets/106761486/363486e7-69ff-4912-a553-85195d099082)


## Instruction Encoding:
![image](https://github.com/Sameer-13/16-Bit-Pipelined-Processor-Design/assets/106761486/503a0e81-1955-40b2-b433-8a5771c36dc6)


## Test Cases:
- Test Case 1: Reverse Array Algorithm:

**Instructions List:**

<details>
  <summary>Click to here to see the instructions</summary>
  <p>
4a00

4c01

d001

044d

6640

6880

1930

16f2

5680

5840

427f

4481

a478

e00d
  </p>
</details>

Input: ```0001, 0002, 0003, 0004, 0005, 0006, 0007, 0008, 0009, 000a, 000b, 000c, 000d, 000e, 000f, fff0, 0011, 0012```

Expected Output: ```0011, fff0, 000f, 000e, 000d, 000c, 000b, 000a, 0009, 0008, 0007, 0006, 0005, 0004, 0003, 0002, 0001, 0012```

- Test Case 2: All Instructions:

Instructions list:
<details>
  <summary>Click to here to see the instructions</summary>
  <p>
    d003
1444
    
467f

1854

0ac8

0cc9

0eca

5200

5401

5602

5803

5a04

5c05

5e06

4e1f

029b

05bc

07f5

08c6

0a1e

0cc7

0e1f

5207

5408

5609

580a

5a0b

5c0c

5e0d

12f0

14f1

17bd

18f2

1bb3

1ccd

2ec3

520e

540f

5610

5811

5a12

5c13

5e14

3a41

38bf

22fe

6dff

5215

5816

5a17

5c18

4200

4402

4600

4804

4a00

4c06

4e06

7f82

4201

8f82

4400

9f82

4603

af82

4800

bf82

4a05

cf82

4c00

5219

541a

561b

581c

5a1d

5c1e

4201

4400

4600

4800

4a05

4c06

4e07

7f82

4200

8f82

4402

9f82

4603

af82

4804

bf82

4a00

cf82

4c00

4e1e

53c1

55c2

57c3

59c4

5bc5

5dc6

4201

4400

4603

4804

4a00

4c00

4e3f

7f82

4200

8f82

4402

9f82

4600

af82

4800

bf82

4a05

cf82

4c06

4e1e

53c7

55c8

57c9

59ca

5bcb

5dcc

f083

5c4e

e082

421e

5e4d

45c8

47c0

1c87

e088

10c6

e08a
  </p>
</details>


Input: ```No Input```

Expected output: ```0030 0030 002f 0000 003f 0020 ffdf 001f 003f ffff 0000 0001 0001 0000 fffe 7fff ffff ffff 8000 ffff 0003 003e 7fff ffff 002f 0001 0002 0003 0004 0005 0006 0001 0002 0003 0004 0005 0006 0001 0002 0003 0004 0005 0006 0081 0088```

## Authors
Sameer Alsabei(Sameer-13) [Github](https://github.com/Sameer-13) [Twitter](https://mobile.twitter.com/Sameer_Alsabei), [Linked in](https://www.linkedin.com/in/sameer-alsabea-610291239/)

Hasan(SultanAbbas0) [Github](), [Twitter](), [Linked in]()

Omar [Github](), [Twitter](), [Linked in]()
