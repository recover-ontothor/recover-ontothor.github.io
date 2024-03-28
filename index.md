---
title: Recover
---

### Abstract

<p align="center" style = "font-size: 8px;" >
Recognizing failures during task execution and implementing recovery procedures is challenging in robotics. 
Traditional approaches rely on the availability of extensive data or a tight set of constraints, while more recent approaches leverage large language models (LLMs) to verify task steps and replan accordingly. 
However, these methods often operate offline, necessitating scene resets and incurring in high costs. 
To address this issues, we've developed RECOVER, a neuro-symbolic method combining ontologies, logical rules, and LLM-based planners for real-time failure recovery. 
By leveraging symbolic information, RECOVER enhances LLMs' ability to generate recovery plans and also to decrease the associated costs. 
We demonstrated the capabilities of our method in a simulated kitchen environment, by developing a new ontology, ONTOTHOR, describing the AI2Thor simulator setting. 
Our empirical evaluation shows that ONTOTHOR’s logical rules accurately detect all failures in the analyzed tasks, and that RECOVER considerably outperforms, for both failure detection and recovery, a baseline method reliant solely on LLMs.
</p>
## Summary video

<p align="center">
  <video ="width:93%" controls>
    <source src="figures/RECOVER-full_video_with_audio.mp4" type="video/mp4">
  </video>
</p>

## Recovery videos

More videos will appear here soon!


## The authors
<table>
   <tr>
      <td >
            <p align="center"><img style="display: block;" align="center" width="200vw" src="figures/CC.JPEG" alt="Cristina Cornelio"/> </p> 
      </td>
      <td > 
            <p align="center"><img style="display: block;" align="center" width="200vw" src="figures/MD.jpg" alt="Mohammed Diab"/> </p> 
      </td>
   </tr>
   <tr>
      <td >
              <h3 align="center" ><a href="https://corneliocristina.github.io"> Cristina Cornelio </a> </h3>
      </td>
      <td > 
            <h3 align="center"><a href="https://mdiabphd.wixsite.com/mdiab"> Mohammed Diab </a> </h3>
      </td>
   </tr>
   <tr>
      <td >
              <p align="center"> Samsung AI </p> 
      </td>
      <td > 
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
