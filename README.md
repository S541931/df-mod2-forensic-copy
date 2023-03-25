# df-mod2-forensic-copy
44-386-80 Digital Forensics P2

1. In this project we will be practicing the creation of forensically sound copies. To start I will create some evidence and place it in an Evidence Folder inside the Github Repository, df-mod2-forensic-copy Folder. Through a script ran in VS Codes PowerShell Terminal I collected the SHA256 Hash Values.
2. My Evidence Files were
    1. 08-sudoers.pptx
    2. CCC2021AnnualReport.pdf 
    3. HillIB12e_HistoricCase_ABInBevBeerGlobally_FNL.doc
    4. Industry_6_FIR_Year_10.csv
    5. mssql_tcp_error_strace.txt
3. To obtain Forensically Sound Copies of the Evidence, in Windows File Explorer I copied the entire Evidence Folder at the same time and the paste it. The only change made was to the name of the folder which I changed from "EvidenceFiles" to "EvidenceFiles-Copy-2023-03-24"
4. I have Confirmed that the Copied Files Hash Values match the Original Files Hash Values
# Original Files Results:
File : 08-sudoers.pptx
Hash      : 375CD94A2FC2FA346BD2FEEBF35224A75075BE5104582F165F30D0E021A864F8

File : CCC2021AnnualReport.pdf
Hash      : CE968515A937C060172EC454A4D04294A87F48EE5021E522B69D33A84E11BF64

File : HillIB12e_HistoricCase_ABInBevBeerGlobally_FNL.doc
Hash      : 8A5BB107B220BF7BFF34399A07ADEB1FA941C21F29360F580D73D5AF09B21412

File : Industry_6_FIR_Year_10.csv
Hash      : 3E7882684B6BEB8BB339CDD39EA8AA32EFFE97316300ADDDB3A79BA0ED51D3C5

File : mssql_tcp_error_strace.txt
Hash      : 999ADFA23752597A151B99D481B73AF5FBA45F0B481376EB432BFB9510777EC0

# Copied File Results:
File : 08-sudoers.pptx
Hash      : 375CD94A2FC2FA346BD2FEEBF35224A75075BE5104582F165F30D0E021A864F8

File : CCC2021AnnualReport.pdf
Hash      : CE968515A937C060172EC454A4D04294A87F48EE5021E522B69D33A84E11BF64

File : HillIB12e_HistoricCase_ABInBevBeerGlobally_FNL.doc
Hash      : 8A5BB107B220BF7BFF34399A07ADEB1FA941C21F29360F580D73D5AF09B21412

File : Industry_6_FIR_Year_10.csv
Hash      : 3E7882684B6BEB8BB339CDD39EA8AA32EFFE97316300ADDDB3A79BA0ED51D3C5

File : mssql_tcp_error_strace.txt
Hash      : 999ADFA23752597A151B99D481B73AF5FBA45F0B481376EB432BFB9510777EC0
