**# carry-look-ahead-adder**

A carry look-ahead adder reduces the propagation delay by introducing more complex hardware. In this design, the ripple carry design is suitably 
transformed such that the carry logic over fixed groups of bits of the adder is reduced to two-level logic. 


![digital_Logic3](https://github.com/panda12384/carry-look-ahead-adder/assets/160568759/da1d75d7-8c6f-4997-a760-83fbc8fe8bd5)

**LOGIC GATE DESIGN **

![digital_Logic6](https://github.com/panda12384/carry-look-ahead-adder/assets/160568759/24ef63a7-0d5c-45ec-8b77-0f744abbbba2)

THE FORMULA:

C_{1} = G_{0} + P_{0} C_{in} 

C_{2} = G_{1} + P_{1} C_{1} = G_{1} + P_{1} G_{0} + P_{1} P_{0} C_{in}

C_{3} = G_{2} + P_{2} C_{2} = G_{2} + P_{2} G_{1} + P_{2} P_{1} G_{0} + P_{2} P_{1} P_{0} C_{in} 

C_{4} = G_{3} + P_{3} C_{3} = G_{3} + P_{3} G_{2} + P_{3} P_{2} G_{1} + P_{3} P_{2} P_{1} G_{0} + P_{3} P_{2} P_{1} P_{0} C_{in}      


THE OUTPUT:

![Screenshot 2024-07-04 123846](https://github.com/panda12384/carry-look-ahead-adder/assets/160568759/241f3759-df4c-4153-9e7f-8cca36bdbbf3)
