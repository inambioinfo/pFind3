# pFind 3

pFind 3 is developed as an upgrade of pFind 2.8 (<a href=http://pfind.ict.ac.cn/software/pFind/index.html>visit the old version</a>).
Shotgun proteomics has grown rapidly in recent decades, but a large fraction of tandem mass spectrometry data in shotgun proteomics are not successfully identified. Thus we developed a novel database search algorithm, Open-pFind, to efficiently identify peptides even in an ultra-large search space which takes into account unexpected modifications, amino acid mutations, semi- or non-specific digestion and co-eluting peptides. Open-pFind has now been integrated into pFind 3 as the default workflow, and pFind 3 also supports the restricted search mode, which can be switched in the interface.
The paper of Open-pFind has been uploaded to the preprint server of bioRxiv: <a href = https://www.biorxiv.org/content/early/2018/03/20/285395>Open-pFind enables precise, comprehensive and rapid peptide identification in shotgun proteomics</a>

![](http://pfind.ict.ac.cn/software/pFind3/fig1.png)
<p><b>Fig. 1.</b> Workflow of Open-pFind, including the sub-workflow of the open search module. <b>a)</b> The workflow of Open-pFind. MS data are first preprocessed by pParse, and then the MS/MS data are searched by the open search module. Next, the MS data are re-searched by the restricted search module against the refined search space based on the learned information in the reranking step. Finally, the results obtained from both the open and restricted searches are merged, reranked again and reported. <b>b)</b> The default workflow of the open search module. For each spectrum, a few tags are extracted and then searched against the indexed protein database. Peptide candidates are then generated by extending the matched tags in proteins. Finally, peptides are scored with the spectrum and ranked; the mass shift between the precursor ion and each peptide is treated as a modification and localized by testing all valid positions. </p>


## Cite us
1. <a href="https://www.biorxiv.org/content/early/2018/03/20/285395">Open-pFind enables precise, comprehensive and rapid peptide identification in shotgun proteomics</a></h6>
	  Hao Chi, Chao Liu, Hao Yang, Wen-Feng Zeng, Long Wu, Wen-Jing Zhou, Xiu-Nan Niu, Yue-He Ding, Yao Zhang, Rui-Min Wang, Zhao-Wei Wang, Zhen-Lin Chen, Rui-Xiang Sun, Tao Liu, Guang-Ming Tan, Meng-Qiu Dong, Ping Xu, Pei-Heng Zhang, Si-Min He. <b>BioRxiv</b>, Mar. 20, 2018. </a></p>

## Downloads

    
pFind 3 is currently free to use. **[Download pFind 3.1.3](http://pfind.ict.ac.cn/file/3.1/pFind3.1_Setup_20180801.exe)**.

Please download and read [user_guide.pdf](http://pfind.ict.ac.cn/file/3.1/pFind%203%20UserGuide.pdf) before download and use pFind 3.

Notice:
<p>* The expiration date is set on <b>Aug. 1, 2019</b>.</p>
<p>* If RAW file read required, <a href="http://thermo-msfilereader-x86-x64.software.informer.com/3.0/" target="_blank">MSFileReader 3.0</a> or a higher version need be installed first.</p>
<p>* <a href="https://www.microsoft.com/zh-cn/download/details.aspx?id=30653" target="_blank">.NET framework 4.5 </a> or a higher version is required.</p>
<p>* pFind can support Windows 7 or higher, and the operating system should be <b>64-bit</b>.</p>
<p>* For Windows 7 operating system, please run the setup program under administrator authority. If any one program cannot properly run after the installation, please try to right click on the program shortcut or the .exe file, and click on "Run as administrator".</p>

If you have any questions about it, please contact [pfind@ict.ac.cn.](mailto:pfind@ict.ac.cn)

Online discussion: [https://github.com/pFindStudio/pFind3/issues](https://github.com/pFindStudio/pFind3/issues), see [github.pdf](http://pfind.ict.ac.cn/file/github.pdf) for usage.

## pFind Release Notes

#### Version 3.1.3 - August 1 2018
* [IMPORTANT] The new expiration date is August 1, 2019. As the license module is updated, please applied for the new license file.
* [IMPORTANT] Fixed a bug when setting the workspace directory.
* [IMPORTANT] Fixed a bug of the license module which may affect the registration of some users using Win 10 system.
* Fixed a text error in the pFind.spectra file.</li>
* Added a warning when users choose "open search" for low resolution MS/MS data.
* Added the option of retrieving all PSMs by any given protein accession number in pBuild.
* Optimized the appearance of the welcome page.
* Optimized the option of comparing two PSMs.
* Optimized the naming rule of the temporary files output by the kernel program.

#### Version 3.1.2 - April 10 2018
* The first released version.

