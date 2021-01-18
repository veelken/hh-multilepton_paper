# hh-multilepton_paper

Draft of public documentation for HH->multilepton analysis with full Run 2 data

# Useful Twikis:
# https://twiki.cern.ch/twiki/bin/viewauth/CMS/Internal/TdrProcessing
# https://twiki.cern.ch/twiki/bin/view/Main/TDRInOverleaf

# To checkout the latex sources:

git clone https://github.com/veelken/hh-multilepton_paper
cd hh-multilepton_paper

mkdir utils
cp -r ../OLD_CMS_PAS_OR_PAPER/utils/* ./utils/
OR
git clone https://gitlab.cern.ch:8443/tdr/utils

# To compile the latex sources:

eval `utils/tdr runtime`
OR
eval `utils/tdr runtime -sh`  ## (echo $SHELL --> bash)
OR
eval `utils/tdr runtime -csh`  ## (echo $SHELL --> csh)
OR
eval `utils/tdr runtime -tcsh`  ## (echo $SHELL --> tcsh)

tdr --style=note b
OR
mkdir ../tmp
tdr --temp_dir=../tmp --style=note b
