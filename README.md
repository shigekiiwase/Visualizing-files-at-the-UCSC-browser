# Visualizing-files-at-the-UCSC-browser (new server)

#1 Generate new_folder at /scratch/webserver/siwase
#2 Move the bigwig files to the new folder /scratch/webserver/siwase/KDM5C_XCI/H3K4me_XES_rep1_0116_2020
#3 Then go to 
https://hkgateway.med.umich.edu/public/iwaselab/KDM5C_XCI

#4 to see the file is listed in the browser
#5 Go to USCS browser --> custom track 
track type=bigWig name="N0hK4Me1XES1_129_rep1" bigDataUrl=https://hkgateway.med.umich.edu/public/iwaselab/ KDM5C_XCI/H3K4me_XES_rep1_0116_2020/C_SNP_N0hK4Me1XES1_129_rep1.bam.bw visibility=full color=64,0,128 autoScale=off alwaysZero=off gridDefault=off maxHeightPixels=60 graphType=bar viewLimits=0:5 windowingFunction=mean smoothingWindow=2 altColor=0,128,64
