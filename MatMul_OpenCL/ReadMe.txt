The code was written in Microsoft Visual studio 2017 on windows 10.

Steps used To Execute OpenCL:

Step 1:
Open native X64 Visual studio command prompt and type
cd Users/ABajpeyi/source/repos
This is where my code was present so navigated to that location.

Step2:  Paste the below Command
cl.exe /EHsc MatMul.cpp /I "C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v10.1\include" /link  "C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v10.1\lib\x64\OpenCL.lib"

