Question 1-5：BAM FLAG
1.	Explain BAM FLAG value：143
143=128+8+4+2+1
该对reads都没有比对到参考基因组，这是第二条reads。
2.	Explain BAM FLAG value：99
99=64+32+2+1
该对reads都比对到参考基因组，这是第一条reads，比对到参考基因组正链。
3.	Explain BAM FLAG value：516
516=512+4
该reads没有通过质量控制，没有比对到参考基因组。
4.	Explain BAM FLAG value：2064
2064=2048+16
补充匹配的reads比对到参考基因组负链。
5.	Explain BAM FLAG value：147
147=128+16+2+1
该对reads都比对到参考基因组，这是第二条reads，比对到参考基因组负链。


Question 6-10：BAM CIGAR
6.	Explain BAM CIGAR: 14M2D31M
在比对的时候，该read开头的14bp比对到参考序列上，接下来的2bp被删除，再接下来的31bp比对到参考序列上。
7.	Explain BAM CIGAR: 3S6M1D5M
在比对的时候，该read开头的3bp被跳过了，紧接其后的6bp比对到参考基因组上，接下来的1bp被删除，接下来的5bp比对到参考基因组上。
8.	Explain BAM CIGAR: 6M14N5M
在比对的时候，该read开头的6bp比对到参考序列上，紧接其后的14bp跳过参考序列，接下来的5bp比对到参考基因组上。
9.	Explain BAM CIGAR: 7M5D8M2I14M(小写：7m5d8m2i14m)
在比对的时候，该read开头的7bp比对到参考序列上，接下来的5bp被删除，接下来的8bp比对到参考序列上，接下来有2bp插入，其后的14bp比对到参考序列上。
10.	How long is the read with alignment CIGAR of 7M5D8M2I14M？
34bp
