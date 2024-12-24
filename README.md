# T-FLIPFLOP-POSEDGE

**AIM:**

To implement  T flipflop using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**T Flip-Flop**

T flip-flop is the simplified version of JK flip-flop. It is obtained by connecting the same input ‘T’ to both inputs of JK flip-flop. It operates with only positive clock transitions or negative clock transitions. The circuit diagram of T flip-flop is shown in the following figure.

![image](https://github.com/naavaneetha/T-FLIPFLOP-POSEDGE/assets/154305477/458a68fe-2d08-4a9d-ac4f-7ae0480ce0bd)

 
This circuit has single input T and two outputs Qtt & Qtt’. The operation of T flip-flop is same as that of JK flip-flop. Here, we considered the inputs of JK flip-flop as J = T and K = T in order to utilize the modified JK flip-flop for 2 combinations of inputs. So, we eliminated the other two combinations of J & K, for which those two values are complement to each other in T flip-flop. The following table shows the state table of T flip-flop.

Here, Qtt & Qt+1t+1 are present state & next state respectively. So, T flip-flop can be used for one of these two functions such as Hold, & Complement of present state based on the input conditions, when positive transition of clock signal is applied. The following table shows the characteristic table of T flip-flop. Inputs Present State Next State

![image](https://github.com/naavaneetha/T-FLIPFLOP-POSEDGE/assets/154305477/cdd7fb32-539f-4b66-bb8d-f305a153c886)

 
From the above characteristic table, we can directly write the next state equation as Q(t+1)=T′Q(t)+TQ(t)′ ⇒Q(t+1)=T⊕Q(t)

**Procedure**

/* 1.Type the program in Quartus software. 2.Compile and run the program. 3.Generate
the RTL schematic and save the logic diagram. 4.Create nodes for inputs and outputs to
generate the timing diagram. 5.For different input combinations generate
the timing diagram.*/

**PROGRAM**

/* Program for flipflops and verify its truth table in quartus using Verilog programming. Developed by: Akshaay Vardhan RegisterNumber: 24007383
*/
![image](https://github.com/user-attachments/assets/93df1b96-2884-46e2-8ccc-20dbc69da7af)

**RTL LOGIC FOR FLIPFLOPS**
![image](https://github.com/user-attachments/assets/640124b9-7865-42ed-b696-dca7f358a4e6)

**TIMING DIGRAMS FOR FLIP FLOPS**
![image](https://github.com/user-attachments/assets/08ea571e-c11f-4541-ac34-2f7dc499e764)

**RESULTS**
Thus, the T Flip-Flop with positive edge triggering is implemented using Verilog, and its
functionality is validated using the truth table and timing diagrams.
