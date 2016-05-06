
Malware Behavior Analyzer, MBA [![Build Status](https://travis-ci.org/misterlihao/MBA.svg?branch=temp-demo-travis-ci)](https://travis-ci.org/misterlihao/MBA)

MBA is a QEMU-based, sandbox system dedicated to malware analysis for Windows x64
Currently, MBA supports the following features:

    1. De-coupled Information Flow Tracking (DIFT)
       It is also known as taint analysis.
       Leveraging the DIFT feature, the contamination 
       conducted by malware to the guest OS can be identified.

       We would like to thank Chi-Wei, Wang, who developed the 
       initial version of DIFT, for sharing his source code. The
       original DIFT is mainly for x86 platform. In this project,
       the DIFT is upgraded to support modern x86_64 platform.

       For the academic paper published by Chi-Wei, Wang, please cite
       C. W. Wang and S. P. Shieh, "SWIFT: Decoupled System-Wide 
       Information Flow Tracking and its Optimizations," Journal of 
       Information Science and Engineering, JISE, 2015.
       http://www.iis.sinica.edu.tw/page/jise/2015/201507_15.pdf

More features are under development.


- MBA Team,
    Chi-Wei, Wang       cwwangabc@gmail.com
    Chia-Wei, Wang      chiaweiw@cs.nctu.edu.tw
    Chong-Kuan, Chen    ckchen@cs.nctu.edu.tw
    Hao, Li             misterlihao@gmail.com
    Jui-Chien, Jai      jcjao0120@gmail.com
    Chuan-Hua, Cheng    newchengxx@gmail.com
    E-Lin, Ho           dennisieur210@gmail.com

  Network Security Lab,
  National Chiao-Tung University, Taiwan