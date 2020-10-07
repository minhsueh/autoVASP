# autoVASP
automatic working script for VASP<br/>
--------------------------------------------------------------------------------------------<br/>
Server: Taiwania 1<br/> 
National Center for High-performance computing (Taiwan)<br/> 
OS: Red Hat Enterprise Linux 7.3 x86_64<br/> 
Compiler: Intel Parallel Studio XE 2018、PGI Compilers & Tools 2017<br/> 
Workload manager: Altair PBS Professional<br/> 
For more information: https://iservice.nchc.org.tw/nchc_service/nchc_service_hpc.php<br/> 
--------------------------------------------------------------------------------------------<br/>
Introduction:<br/>
While conducting the research for alloy material simulation, the massive calculation is needed for differenct composition and atomic ratio. <br/>
However, most of the calculation is similar except some little modification such as atom, atom position, and atom potential. <br/>
For systemically and consistently input parameters in VASP, these scripts were built for routine calculation for structure relaxation, optical properties calculation, <br/>
and post-processing analysis.<br/>
Also, these script meets PBS workload system requirements. (usually, one job is allocated in 8 CPU and 4 Nodes for time and memory requirement.)<br/>


