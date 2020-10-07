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
While conducting the research for alloy material simulation, the massive calculation is needed for differenct composition and atomic ratio. However, most of the calculation is similar except some little modification such as atom, atom position, and atom potential. For systemically and consistently input parameters in VASP, these scripts were built for routine calculation for structure relaxation, optical properties calculation, and post-processing analysis. Also, these script meets PBS workload system requirements. (usually, one job is allocated in 8 CPU and 4 Nodes for time and memory requirement.)<br/>
--------------------------------------------------------------------------------------------<br/>
Folder structre:<br/>
                                                  Taiwania 1<br/>
                                                      |<br/>
                               -------------------------------------------------<br/>
                              /                                                 \<br/>
                            home                                               work<br/>
                              |                                                  |<br/>
                            UserID                                            UserID  <br/>
                              |<br/>
                            script<br/>
                              |<br/>
                 -----------------------------------<br/>
                /                                   \<br/>
               VASP                               gunplot <br/>
                |<br/>
   ---------------------------<br/>
  /      /      |      \      \<br/>
auto2    opt    band   DOS    thinfilm<br/>
  

--------------------------------------------------------------------------------------------<br/>
Usage: <br/>
The route of post-analysis script, POTCAR, and work record should be modified by user.



<img src="https://github.com/minhsueh/autoVASP/blob/main/results/aumo_im_nm.jpg" width="400" height="250" />Some results by using autoVASP
