# Wash-trading-mechanisms 
This repository consists of the code used in my Master thesis 'Wash trading mechanisms'. <br>

Before we can run the code we have to prepare the data. <br>

For IDEX and EtherDelta, we have to extract the daily wash trading volume by running the file prewash_file.<br>
To run this code, one needs the transaction data of every exchange, which can be found on https://drive.google.com/drive/folders/1iOj2l8ByjxIrLFxMmUcBLv87NQsDeMBL?usp=sharing<br>

For the Google Trends proxies, we have to run the GT_GOX and GT_IDEXED files.<br>
Finally, one can download the additionally files for the remaining data sources. <br>

Now, after completing the preparation steps, one can replicate the code for every analysis.<br>
!Note, to completely replicate the wash trading volume of IDEX/EtherDelta, one can use the code on from https://github.com/friedhelmvictor/lob-dex-wash-trading-paper.<br>
To find out everything about the Mt.Gox transaction data, see https://www.kaggle.com/code/xblock/starter-mt-gox-leaked-transaction/data.<br>


The final analysis files are:<br>
The Mt.Gox analysis is called GOX_analysis.<br>
The EtherDelta analysis is called ED analysis.<br>
The IDEX analysis is called IDEX_analysis.<br>
