# Lirex-A-Package-for-Identification-of-Long-Inverted-Repeats-in-Genomes
Lirex: A Package for Identification of Long Inverted Repeats in Genomes
1. Introduction

    Long inverted repeats explorer (Lirex) is developed for identification of long inverted repeats (LIR) that have arm length >30 bp. Written in Java, the tool has a user-friendly interface, allowing users to define LIR searching criteria. Depending on mismatch rate and internal spacer size, recombinational LIRs can be selected from the list of identified LIRs. Therefore, Lirex is a cross-platform tool for identification of user-defined LIRs in genome, which may help in subsequent experimental design for functional study of LIRs.

2. Download and installation

    Lirex may be downloaded for free in this website. Click here to get Lirex.jar file. The .jar file is an executable by double-clicking on the file if Java running environment (JRE) has been installed. The JRE is available at http://www.java.com. When JRE is not yet properly installed, the jar file sometimes will be unzipped by clicking on it. When a big file is processed, the running will probably meet an OutOfMemory error. The solution is to enlarge the heapsize by launching the tool in terminal.

    java -Xmx12000m -jar Lirex.jar
    
    The number following -Xmx depends on the memo size of your computer.

3. Data and user-interface 


    Data input of Lirex is a DNA sequence in Fasta format. By clicking on Search2 button, a frame for settings of LIR criteria shows up.

    The results will be shown. By clicking the 'Get Arm Motif' under 'Function' menu, the tool will show the sequences of the inverted repeats and right arms are referred to the copies of the inverted repeats). If users are interested in recombinogenic motifs, the LIRs capable of recombination induction will be selected using the item under 'Function' menu.

4. License

    The tool is an open-source software that follows the specifications of the Creative Commons license (CC BY-NC-SA 3.0). Distribution for commerial use is not permitted. For any equiry, please send an email to me at wangy@idsse.ac.cn.
    If you use Lirex in your research, please cite:
    Yong Wang, Jiao-Mei Huang. Lirex: A Package for Identification of Long Inverted Repeats in Genomes. 2017, GPB(15):141-146.

      
