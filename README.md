# 2022_Kernel_Study
2022 DKU System Software Lab Kernel Study <br>
*Keywords* __*Kernel Module*__, __*Device Driver*__, __*File System*__, __*FEMU*__

<br>

 
"Linus started a revolution in 1991, but it hasten't ended. In fact, it's just getting started."(...) <br> 늘 새로운 리눅스, 이것이 리눅스를 더욱 매력적이게 한다.(...) 
<br><div style="text-align:right"> *백승재, 최종무 저 『리눅스 커널 내부구조』中*</div>

<br>

* *Members*
    - *Professor* 최 종무<br>
        - Main interest : *Device Driver*
            - 김한얼
        - Main interest : *FileSystem*
            - 이정원
        - Main interest : *FEMU*
            - 송인호, 한예진, 최민국
        - Hasnt decided yet
            - 이용운(좌오꾸와쒼), 신수환, 박종기

<br>

* *References, Background material*

    - [Kernel Modules, linux-kernel-labs](https://linux-kernel-labs.github.io/refs/heads/master/labs/kernel_modules.html) <br>
    - [Device Driver](https://hyeyoo.com/85)<br>
    - [File System, VFS](https://linux-kernel-labs.github.io/refs/heads/master/labs/filesystems_part1.html)<br>
    - [FEMU git (FAST'18)](https://github.com/ucare-uchicago/FEMU)
    - Huaicheng Li, et al. <B>[The CASE of FEMU: Cheap, Accurate, Scalable and Extensible Flash Emulator](https://www.usenix.org/conference/fast18/presentation/li)</B>, 16th USENIX Conference on File and Storage Technologies (FAST'18)


<br>

* *Textbook*
    - [1] 백승재, 최종무 저 『<B>리눅스 커널 내부구조</B>』, 아티오
    - [2] Robert M. Love , 『<B>Linux Kernel Development</B>』(리눅스 커널 심층분석), 에이콘
    - [3] Daniel P. Bovet , 『<B>Understanding the Linux Kernel</B>』(리눅스 커널의 이해), O'REILLY(한빛미디어)

<br>

* *Study Goal*

* *Study Plan*
    
    __[#주차]_[내용]_[발표자]_PPT_Template.pptx 파일 참고__

    <table border="0" align="center" width=100%>
    <tr align="center">
        <td><B>날짜</td>
        <td><B>내용</td>
        <td><B>발표자</td>
        <td><B>참고자료</td>
    </tr>
    <tr>
        <td rowspan="2">1주(1월 4일)</td>
        <td>리눅스 커널 전체 구조</td>
        <td>한예진</td>
        <td>리눅스 커널 내부구조 2장</td>
    </tr>
    <tr>
        <td>리눅스 커널 모듈 프로그래밍</td>
        <td>송인호</td>
        <td>리눅스 커널 내부구조 7장</td>
    </tr>
    <tr>
        <td rowspan="2">2주(1월 11일)</td>
        <td>리눅스 커널 태스크 관리</td>
        <td>이용운<br>(좌오꾸와쒼)</td>
        <td>리눅스 커널 내부구조 3장</td>
    </tr>
    <tr>
        <td>리눅스 커널 모듈 프로그래밍 실습</td>
        <td>-</td>
        <td>실제 리눅스 실습 내용,<br> 2명이 발표해도 좋을듯</td>
    </tr>
    <tr>
        <td rowspan="3">3주(1월 18일)</td>
        <td>리눅스 커널 메모리 관리</td>
        <td>-</td>
        <td>리눅스 커널 내부구조 4장</td>
    </tr>
    <tr>
        <td>리눅스 커널 디바이스 드라이버(Character)</td>
        <td>김한얼</td>
        <td>리눅스 커널 내부구조 8장</td>
    </tr>
        <tr>
        <td>리눅스 커널 디바이스 드라이버(Block)</td>
        <td>최민국</td>
        <td>리눅스 커널 내부구조 8장</td>
    </tr>
    <tr>
        <td rowspan="2"><B>4주(1월 25일)</td>
        <td><B>리눅스 커널 Device Driver 실습 1</td>
        <td>김한얼</td>
        <td><B>실제 실습 내용</td>
    </tr>
    <tr>
        <td><B>리눅스 커널 Device Driver 실습 2</td>
        <td>최민국</td>
        <td><B>실제 실습 내용</td>
    </tr>
        <tr>
        <td rowspan="2">5주(2월 8일)</td>
        <td>리눅스 커널 파일 시스템</td>
        <td>이정원</td>
        <td>리눅스 커널 내부구조 5장</td>
    </tr>
    <tr>
        <td>리눅스 커널 인터럽트</td>
        <td>-</td>
        <td>리눅스 커널 내부구조 6장</td>
    </tr>
    <tr>
        <td rowspan="2"><B>6주(2월 15일)</td>
        <td><B>리눅스 커널 파일 시스템 실습 1</td>
        <td>이정원</td>
        <td><B>실제 실습 내용</td>
    </tr>
    <tr>
        <td><B>리눅스 커널 파일 시스템 실습 2</td>
        <td>송인호</td>
        <td><B>실제 실습 내용</td>
    </tr>
        <tr>
        <td rowspan="2">7주(2월 22일)</td>
        <td> 플래시 메모리 특성과 FTL</td>
        <td>이용운<br>(좌오꾸와쒼)</td>
        <td>플래시 메모리/FTL 논문</td>
    </tr>
    <tr>
        <td>FEMU 구조</td>
        <td>송인호</td>
        <td>FEMU 논문</td>
    </tr>
        <tr>
        <td rowspan="2"><B>8주(2월 28일,월)</td>
        <td><B>FEMU 실습 1</td>
        <td>한예진</td>
        <td>FEMU 논문+@</td>
    </tr>
    <tr>
        <td><B>FEMU 실습 2</td>
        <td>송인호</td>
        <td>FEMU 논문+@</td>
    </tr>
    </table>+

## License
(Linux Kernel Module Programming Guide License)
The Linux Kernel Module Programming Guide is a free book; you may reproduce and/or modify it under the terms of the [Open Software License](https://opensource.org/licenses/OSL-3.0).
Use of this work is governed by a copyleft license that can be found in the `LICENSE` file.

The complementary sample code is licensed under GNU GPL version 2, as same as Linux kernel.