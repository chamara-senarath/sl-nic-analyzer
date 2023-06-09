# Sri Lankan NIC Analyzer

An application developed to analyze personal details of a Sri Lankan person by scanning their National Identity Card (NIC) using image processing techniques in MATLAB.

## Prerequisites for Deployment

Before deploying the Sri Lankan NIC Analyzer, please ensure you have the following prerequisites:

- Verify that the MATLAB runtime is installed on your system and that you have version 8.5 (R2015a) installed.

- If the MATLAB runtime is not installed, follow these steps:
  1. Enter the following command at the MATLAB prompt:
     ```
     >> mcrinstaller
     ```
     The `MCRINSTALLER` command will display the location of the MATLAB runtime installer.
  2. Run the MATLAB runtime installer at the specified location.

- Alternatively, you can download the Windows 64-bit version of the MATLAB runtime for R2015a from the MathWorks website by navigating to the following URL:
  [http://www.mathworks.com/products/compiler/mcr/index.html](http://www.mathworks.com/products/compiler/mcr/index.html)

- For more information about the MATLAB runtime and the MATLAB runtime installer, refer to the "Package and Distribute" section in the MATLAB Compiler documentation available in the MathWorks Documentation Center.

> Note: Administrator rights are required to run the MCRInstaller.

## Files to Deploy and Package

When deploying the Sri Lankan NIC Analyzer, make sure to include the following files:

- `SL_NIC_Identifier.ctf` (component technology file)
- `SL_NIC_Identifier.exe`
- `MCRInstaller.exe`
- If end users are unable to download the MATLAB runtime using the provided link, include it when building your component by clicking the "Runtime downloaded from web" link in the Deployment Tool.
- This `readme` file

## Definitions

For information on deployment terminology and concepts, please refer to the following resources:

- [MATLAB Compiler Documentation Center](http://www.mathworks.com/help)
- Select MATLAB Compiler > Getting Started > About Application Deployment > Application Deployment Terms
