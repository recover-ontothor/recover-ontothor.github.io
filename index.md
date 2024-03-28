---
title: Recover
---

### Abstract

Recognizing failures during task execution and implementing recovery procedures is challenging in robotics. 
Traditional approaches rely on the availability of extensive data or a tight set of constraints, while more recent approaches leverage large language models (LLMs) to verify task steps and replan accordingly. 
However, these methods often operate offline, necessitating scene resets and incurring in high costs. 
To address this issues, we've developed RECOVER, a neuro-symbolic method combining ontologies, logical rules, and LLM-based planners for real-time failure recovery. 
By leveraging symbolic information, RECOVER enhances LLMs' ability to generate recovery plans and also to decrease the associated costs. 
We demonstrated the capabilities of our method in a simulated kitchen environment, by developing a new ontology, ONTOTHOR, describing the AI2Thor simulator setting. 
Our empirical evaluation shows that ONTOTHOR’s logical rules accurately detect all failures in the analyzed tasks, and that RECOVER considerably outperforms, for both failure detection and recovery, a baseline method reliant solely on LLMs.


## Summary video

<p align="center">
  <video style="width:93%" controls>
    <source src="figures/RECOVER-full_video_with_audio.mp4" type="video/mp4">
  </video>
</p>


## The authors
<table>
   <tr>
      <td >
            <p align="center"><img align="center" width="200vw" src="figures/CC.JPEG" alt="Cristina Cornelio"/> </p> 
              <h3 align="center" ><a href="https://corneliocristina.github.io"> Cristina Cornelio </a> </h3>
              <p align="center"> Samsung AI </p> 
      </td>
      <td >   </td>
      <td > 
            <p align="center"><img align="center" width="200vw" src="figures/MD.jpg" alt="Mohammed Diab"/> </p> 
            <h3 align="center"><a href="https://mdiabphd.wixsite.com/mdiab"> Mohammed Diab </a> </h3>
            <p align="center"> University of Plymouth </p> 
      </td>
   </tr>
</table>



### How to cite

```latex
@inproceedings{cornelio_diab_recover,
  author={Cristina Cornelio and Mohammed Diab},
  booktitle = {ArXiv preprint},
  title={RECOVER: A Neuro-Symbolic Framework for Failure Detection and Recovery},
  Year = {2024}}
```
