REM BATCH EXECUTION OF IEEE 24 bus system Flat Start in PSSe v33
echo off
REM #------Set environment paths-----------#
SET PSSEPATH=%ProgramFiles(x86)%\PTI\PSSE33\
SET PATH=%PSSEPATH%PSSBIN;C:\Python27;%PATH%;
echo on
REM #-------Make CNV & SNP files----------------#
psse33 -buses 150000 -rspfile "SCRIPTs\MakeCnvSnp.idv" -embed
REM #-------Run flat simulation----------------#
psse33 -buses 150000 -rspfile "SCRIPTs\Runflat.idv" -embed
REM #-------prepare channel max deviations file----------------#
pssplt33 -gnikool -inpdev "SCRIPTs\GetDevs.idv"
