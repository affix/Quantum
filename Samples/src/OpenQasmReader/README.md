# OpenQasm Reader Sample #
This sample shows that one can convert OpenQasm 2.0 specifications to Q# methods. 
This allows one to import valid specifications written in OpenQasm 2.0 to be used on the Microsoft Q# Simulator. 
Apart of the barrier gate (which has no meaning in Q# so is written as the Id gate) all gates are converted to Q# constructions.
Usage: OpenQasmReader namespace filename