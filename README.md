# hh-multilepton_paper

Draft of public documentation for HH->multilepton analysis with full Run 2 data

# To checkout the latex sources:

git clone https://github.com/veelken/hh-multilepton_paper

mkdir utils

cp -r ../OLD_CMS_PAS_OR_PAPER/utils/* ./utils/

# To compile the latex sources:

eval `utils/tdr runtime`

tdr --style=note b
