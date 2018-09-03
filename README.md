# yhBrainExt.sh

The script for the best brain extraction using ANTs (http://stnava.github.io/ANTs/).

  Description:
  This script is modified using previous antsBrainExtraction.sh script and other
  ants commands.
  The script is very well working in human brains regardless of shapes and ages.
  However, it is not perfectly working sometimes in B1-bias field affected brains.
  For example, too much extraction in temporal cortex in 7 Tesla T1w images.

  Development History:
    Version 0.2: changed strategy (2018.8.24) \
    Version 0.1: the script release (2018.7.20)

  Example Usage:
  yhBrainExt.sh -i input -o input_Brain -p 1

  (Optional)
  yhBrainExt.sh -version (see the version)

  Compulsory arguments:
      -i:  input image (nifti file)
      -o:  final output name
      -p:  intermediate files (1: remain / 0: remove)

--------------------------------------------------------------------------------------
  Requirement: ANTs pre-installation
--------------------------------------------------------------------------------------
  This method was created by:

  Uksu, Choi (uschoi@nict.go.jp)
  Center for Information and Neural Networks
  National Institute of Information and Communications Technology

--------------------------------------------------------------------------------------
                      Script writing and modification by Uksu
                      Do not modify without a permission.
--------------------------------------------------------------------------------------
