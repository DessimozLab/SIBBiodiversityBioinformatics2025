## SIB Biodiversity Bioinformatics 2025


## Teachers

* [Natasha Glover](https://lab.dessimoz.org/people/natasha_glover)
* [Stefano Pascarelli](mailto:Stefano.Pascarelli@unil.ch)
* [Nikolai Romashchenko](mailto:nikolai.romashchenko@unil.ch)
* [Christophe Dessimoz](https://www.sib.swiss/christophe-dessimoz-natasha-glover-group)


## Learning outcomes

This course is centered around comparative genomics. After the course, you will be able to:

* Define orthology, paralogy and their subtypes
* Retrieve orthology information from the OMA database
* Map sequences quickly to their Hierarchical Orthologous Groups
* Perform gene annotation quality control with OMArk
* Infer orthologs on custom genomes using the FastOMA pipeline
* Construct and interpret phylogenetic species trees using OMA data

## Course lectures

The pdf for the slides of the course can be found [here] (https://github.com/DessimozLab/SIBBiodiversityBioinformatics2025/blob/main/Biodiversity%20bioinformatics%202025.pdf). 

## The OMA Academy

To complete the course, you will follow the exercises of the OMA Academy on https://omabrowser.org/oma/academy/ for this course. OMA Academy is an e-learning website with a suite of self-learning modules centered around comparative genomics and phylogenetics. The modules are specifically designed to help computational biologists use OMA, a method and database for inferring orthologs. Each module is stand-alone, with a basic introduction and a series of exercises with hints and answers.


## Prerequisites


### _UNIX_

Participants should have a fundamental knowledge of utilizing the command line on UNIX-based systems. To assess your UNIX skills, you can take a quiz available [here](https://docs.google.com/forms/d/e/1FAIpQLSd2BEWeOKLbIRGBT_aDEGPce1FOaVYBbhBiaqcaHoBKNB27MQ/viewform?usp=sf_link). If you lack experience with the UNIX command line or are uncertain about meeting the prerequisites, we recommend completing the SIB [online UNIX tutorial](https://edu.sib.swiss/pluginfile.php/2878/mod_resource/content/4/couselab-html/content.html). 


### _Software_

We will be mainly working on an [GitPod](https://gitpod.io/), an online integrated development environment (IDE) that allows users to write, edit, and run code directly in a web browser. GitPod is cloud-based, meaning that all software, code, and files needed for the course are stored and processed on remote servers; you will not need to install or configure anything locally.

You can access the GitPod here: [https://gitpod.io/#https://github.com/DessimozLab/SIBBiodiversityBioinformatics2025](https://gitpod.io/#https://github.com/DessimozLab/SIBBiodiversityBioinformatics2025) 

Participants need to sign up for a GitPod account via Github and/or LinkedIn to access 10 hours per month for free, which is enough time to complete the exercises. After logging in, create a new workspace by choosing SIBBiodiverstyGenomics2025, Browser Editor, and Large configuration (8 cores, 16 GB RAM, 50 GB storage). 

Notes: 
GitPod might ask you for permission when it comes to pasting in GitPod terminal, you can click on Allow on the top left corner in Google Chrome. The Safari and Firefox browsers are not recommended. 
You can click on OK if you see a box about changes in the git repository.

If you mistakenly close the browser window, you can go to the GitPod Dashboard and enter your workspace again. You might need to reactivate your conda environment with the following commands:
```
source /workspace/conda/bin/activate
conda activate omacademy
```
As each user has limited CPU hours, please make sure that you stop the workspace, once you finish the analysis.   


## Schedule Aug 25 2025


<table>
  <tr>
   <td><strong>Time</strong>
   </td>
   <td><strong>Activity</strong>
   </td>
   <td><strong>In charge</strong>
   </td>
  </tr>
  <tr>
   <td>09:00  - 09:15
   </td>
   <td>Welcome, Introductions
   </td>
   <td>Natasha Glover
   </td>
  </tr>
  <tr>
   <td>09:15 - 09:45
   </td>
   <td>Lecture: Overview, objectives, motivation, concept of orthologs, HOGs
   </td>
   <td>Natasha Glover
   </td>
  </tr>
  <tr>
   <td>09:45 - 10:25
   </td>
   <td><strong>Module 1: The OMA Browser</strong>
   </td>
   <td>Natasha Glover
   </td>
  </tr>
  <tr>
   <td>10:25 - 10:45
   </td>
   <td>Coffee break
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>11:25 - 11:35
   </td>
   <td>Lecture: Fast placement into hierarchical orthologous groups with OMAmer
   </td>
   <td>Nikolai Romashchenko
   </td>
  </tr>
  <tr>
   <td>11:35 - 12:05
   </td>
   <td><strong>Module 2: OMAmer </strong>
   </td>
   <td>Nikolai Romashchenko
   </td>
  </tr>
  <tr>
   <td>12:15 - 13:30
   </td>
   <td>Lunch
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>13:30 - 13:40
   </td>
   <td>Lecture: Protein-coding gene assessment with OMArk 
   </td>
   <td>Natasha Glover
   </td>
  </tr>
  <tr>
   <td>13:40 - 14:10 
   </td>
   <td><strong>Module 3: OMArk</strong>
   </td>
   <td>Natasha Glover
   </td>
  </tr>
  <tr>
   <td>14:10 - 14:15
   </td>
   <td>Quick break
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>14:15 - 14:25
   </td>
   <td>Lecture: Orthology inference with FastOMA 
   </td>
   <td>Stefano Pascarelli
   </td> 
  </tr>
  <tr>
   <td>14:25 - 15:25
   </td>
   <td><strong>Module 4: FastOMA</strong> 
   </td>
   <td>Stefano Pascarelli
   </td>
  </tr>
  <tr>
   <td>15:25 - 15:45
   </td>
   <td>Coffee break
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>15:45 - 16:00
   </td>
   <td>Lecture: Gene trees and species trees
   </td>
   <td>Christophe Dessimoz
   </td>
  </tr>
  <tr>
   <td>16:00 - 16:45
   </td>
   <td><strong>Module 5: Building species trees</strong>
   </td>
   <td>Christophe Dessimoz
   </td>
  </tr>
    <tr>
   <td>16:45 - 17:00
   </td>
   <td>Wrap up
   </td>
   <td>Christophe Dessimoz
   </td>
  </tr>
</table>


