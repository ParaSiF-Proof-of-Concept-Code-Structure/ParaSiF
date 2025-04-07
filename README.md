# Dummy ParaSiF
This is (dummy) ParaSiF main code

## For Users
- clone git by:

    `git clone https://github.com/ParaSiF-Proof-of-Concept-Code-Structure/ParaSiF.git`

- Obtain MUI code by:

    `git submodule update --init coupling/MUI/`

- Suppose users want to have the OpenFOAM source code (with MUI enabling), but don't want to have the DualSPHysics code:

    `git submodule update --init thirdParty/OpenFOAM_v2106-MUI_v1.2/`

- Install MUI

- Install MUI-enabled OpenFOAM

- Test the installation by run relevant examples (such as OpenFOAM - OpenFOAM coupling) in examples/ subfolder

## For Developpers
- Ask Wendi before more info appears here