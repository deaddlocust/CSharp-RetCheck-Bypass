# CSharp-RetCheck-Bypass
External C# Retcheck bypass by DeepPain


## Known problems
Any lua functions using a JB opcode for stuff not concerning retcheck will get turned into a JA opcode instead


## Usage

1.Call PatchJBs(<FUNCTION_ADDRESS>);

2.Call the function

3.Call PatchJAs(<FUNCTION_ADDRESS>);
