# Wash-trading-mechanisms
This repository consists of the code used in my Master thesis 'Wash trading mechanisms'.

Before we can run the code we have to prepare the data.
For Mt.Gox, we have to extract the daily wash trading volume by running the file prewash_file.
For the Google Trends proxies, we have to run the GT_GOX and GT_IDEXED files.

Then, downloading the other data sources, one can replicate the code for every analysis.
!Note, to download complete_edge_v2, see https://www.kaggle.com/code/xblock/starter-mt-gox-leaked-transaction/data.
!Note, to completely replicate the wash trading volume of IDEX/EtherDelta, one can use the code on from https://github.com/friedhelmvictor/lob-dex-wash-trading-paper.

The final analysis files are:
The Mt.Gox analysis is called GOX_analysis
The EtherDelta analysis is called ED analysis
The IDEX analysis is called IDEX_analysis
