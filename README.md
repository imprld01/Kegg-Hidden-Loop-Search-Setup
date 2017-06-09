# Kegg-Hidden-Loop-Search-Setup

You can download the archive file for kegg hidden loop searching.  
If your computer is win 64-bit, you can download from [here](https://goo.gl/MvgANe) directly.

* [Here](https://goo.gl/VKIkOe) you can know more about kegg hidden loop searching
* [Here](https://goo.gl/MvgANe) you can know what is inside the archive file
  * [Here](https://goo.gl/MvgANe) you can find the user guide

# KGI

The searching is based on KGI, an integrated data structure parsed from [kegg](http://www.kegg.jp) database in specific species.

* Find the KGI file immediately
  * **KEGG Orthology**
    1. find the KGI file [here](https://goo.gl/ldhIra)
    2. retrieved on 2017/05/07 from [KEGG](http://www.kegg.jp)
    3. Org Code: *ko*
    4. place *Kgml_Info.ki* in specific directory: ~/Database/Kgml_Information/ko/
  * **Danio rerio (zebrafish)**
    1. find the KGI file [here](https://goo.gl/Y57ulx)
    2. retrieved on 2017/06/09 from [KEGG](http://www.kegg.jp)
    3. Org Code: [*dre*](http://www.genome.jp/kegg-bin/show_organism?org=dre)
    4. place *Kgml_Info.ki* in specific directory: ~/Database/Kgml_Information/dre/
  
# Update Log

* 2017/05/07
  * packed by batch file
  * rearrange file destination, including dataset, report, etc
* 2017/05/31
  * merge CreateReportMain and FilterSearchMain in Step3
  
# Environment

* under windows 32-bit OS
* Java Runtime Environment is needed (developed under jre1.8.0)

# Tool Remark

* Installation System
  * [**Inno Setup**](http://www.jrsoftware.org/isinfo.php)
  * NSIS(Nullsoft Scriptable Install System)
* Java Executable Wrapper
  * [**exe4j**](https://www.ej-technologies.com/download/exe4j/files)
  * Launch4j
