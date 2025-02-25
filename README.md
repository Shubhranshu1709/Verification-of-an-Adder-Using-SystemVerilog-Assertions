# Verification-of-an-Adder-Using-SystemVerilog-Assertions
These assertions verify the correctness and validity of the adder in SystemVerilog:

-SUM_CHECK ensures that whenever the sum output changes, it must be equal to the expected sum of inputs a + b.
-SUM_VALID checks that the sum output is never unknown (X or Z), ensuring proper signal integrity.
-A_VALID and B_VALID confirm that the input signals a and b are always defined, preventing unexpected behavior due to uninitialized values.
These assertions help detect functional issues early and improve the robustness of the verification process.
