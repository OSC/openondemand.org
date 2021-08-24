---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default
---

<!---
<div class="alert alert-info">
  <strong>Extraordinary Open OnDemand support for HPC centers supporting COVID-19 research</strong>
  <p>The Open OnDemand team encourages any HPC center supporting COVID-19 research that could benefit from extraordinary platform development and support to engage with us. For more information, please contact Alan Chalker, Ph.D., Open OnDemand co-PI, by email at alanc@osc.edu or by phone at: (614)247-8672.
</p>
</div>
--->

<div class="alert alert-info">
  <strong>OSC has a job opening for a software developer on the Open OnDemand team!</strong> The posting is available at https://osu.wd1.myworkdayjobs.com/OSUCareers/job/Columbus-Campus/Web---Interface-App-Lead-Engineer_R17290
</div>


## Overview

### An intuitive, innovative, and interactive interface to remote computing resources

Open OnDemand helps computational researchers and students efficiently utilize remote computing resources by making them easy to access from any device.  It helps computer center staff support a wide range of clients by simplifying the user interface and experience.

### Key Benefits & Impact

* Key benefit to you, the end user:  You can use any web browser to access resources at a computing service provider.
* Key benefit to you, the computer center staff:  A wide range of clients/needs can utilize your computing resources.
* Overall impact:  Users are able to use remote computing resources faster and more efficiently.

### Features & More Information

Open OnDemand is an NSF-funded open-source HPC portal based on OSC's original
OnDemand portal.  The goal of Open OnDemand is to provide an easy way for
system administrators to provide web access to their HPC resources, including,
but not limited to:

- Plugin-free web experience
- Easy file management
- Command-line shell access
- Job management and monitoring across different batch servers and resource managers
- Graphical desktop environments and desktop applications

See the [documentation](https://osc.github.io/ood-documentation/latest/) for installation directions, app development tutorials, and an overview of the components and applications that make up OnDemand.  We also have a [walkthrough video](https://www.youtube.com/watch?v=4-w-4wjlnPk&list=PLiHVyvLHAIcw2sM_MYNVX9B1vBmJgEmW3) showing the various components of an Open OnDemand instance available.

### Available Applications

Most of the most popular scientific applications as easilier made available to clients via Open OnDemand. A regularly updated list of these is available in the [documentation](https://osc.github.io/ood-documentation/latest/install-ihpc-apps.html) and includes software such as:
* Abaqus
* ANSYS
* COMSOL
* MATLAB
* Jupyter
* RStudio
* QGIS
* Paraview
* STATA
* Tensorboard

## Organizations using or exploring OnDemand
Below is a list of organizations that have deployed or are looking at deploying Open OnDemand.  Please contact us via the [news list](https://lists.osu.edu/mailman/listinfo/ood-users) if your organization is not on this list and should be included!

[We also have a page with testimonial comments from many of these organizations](Testimonials.md)

<iframe src="https://widgets.figshare.com/articles/6890636/embed?show_title=0" width="500" height="375" frameborder="0"></iframe>

## Run your own live demo

There are three ways you can have a demo Open OnDemand instance running in minutes:
1. Using [Docker](https://www.docker.com/).  Just follow the instructions in the [HPC Toolset Tutorial](https://github.com/ubccr/hpc-toolset-tutorial)
2. Using [Vagrant](https://www.vagrantup.com/). Just follow the steps listed in the [ood-images-full](https://github.com/OSC/ood-images-full) README.
3. Using the [Science Gateways](https://sciencegateways.org/) hosting service.  Instructions are listed in the [sgci-ood-image](https://github.com/OSC/sgci-ood-image/blob/master/how_to_setup_ood_on_sgci_with_the_image/index.md) README.

## Project and Feature Roadmap
### Upcoming Releases
[Click here for a list of upcoming planned releases](Releases.md)

### Open OnDemand 2.0 Project
[Click here for details on the Open OnDemand 2.0 project](OOD2Overview.md)

### Tell us what features you want to be added to OnDemand!

* Add new feature requests or bug reports on the [project issues page](https://github.com/OSC/Open-OnDemand/issues) (requires free GitHub account)
* Post a suggestion or review existing suggestions on our [Discourse instance](https://discourse.osc.edu/c/open-ondemand) 
* Send an email to us on the [news list](https://lists.osu.edu/mailman/listinfo/ood-users)

[See a list and comment on community requested features](
https://github.com/issues?utf8=%E2%9C%93&q=is%3Aopen+is%3Aissue+org%3Aosc+label%3A%22community+request%22
) we are already planning on working.  Note - you must be logged in to GitHub to see this list.

### Collaboration and Financial Model
The Open OnDemand team welcomes and encourages opportunities to collaborate on proposals with members of our community in response a variety of solicitations. Examples of potential collaboration roles our team can have include developing and delivering related client education and training programs, and providing extended support services for software deployment and custom workflow development. Please contact us via the news list if you would like to discuss a potential collaboration.

Please consider contributing to the code repository on Github.  Since January 2016 there have been over 8,000 commits to the code base, but we can always use additional development help!

Currently, the primary source of funding for the development of Open OnDemand is via an NSF award.  The long term sustainability model for Open OnDemand is to get support from a variety of sources and types as listed the below, with current examples in parentheses.  Please free free to contact the Open OnDemand team with additional suggestions or for more details.
* Direct grants (e.g. NSF, Google)
* Institutional adopters contributions (e.g. Texas A&M code contributions)
* Institutional service / development contracts (no current ones)
* Software / hardware provider engagements (e.g. Intel case studies, NVIDIA GTC presentations)

## Project Cybersecurity
[Trusted CI](https://trustedci.org/) , the NSF Cybersecurity Center of Excellence conducted an in-depth vulnerability assessment of Open OnDemand, completing it in December 2018. This assessment included a careful review of the code, increasing our confidence in its security. The Ohio Supercomputer Center addressed the implementation issues (bugs) that were found during this review, producing a more robust revision of Open OnDemand.

In January, 2021, The Open OnDemand team and Trusted CI began another engagement to to accomplish three distinct objectives:Integration of security automation into DevOps flows; Skills transfer for vulnerability assessment; Development of needed security policies, practices, and procedures.  Upon completion of this project later in 2021, the Open OnDemand team will be much better positioned with regards to security dev ops.

If you have security concerns or think you have found a vulnerability in Open OnDemand that you want to responsibly disclose, please contact us directly via email on the news list linked above or utilizing the ["Report a Potential Security Incident"](https://www.osc.edu/contact/security) form on the OSC website. 

## Where to Learn More!

### Webinars / Videos

| Date   | Publisher/Event    | Title                                                                              | Slides                                                                                  | Media                                                                                                                                                                      |
| :----:   | :----:    | :-----:                                                                            | :------:                                                                                | :-----:                                                                                                                                                                    |
| 2021-08-11 | Dell Technologies HPC Community Event | Simplifying HPC Usage with Open OnDemand | [Download](https://www.dellhpc.org/uploads/7/2/9/8/72981523/open_ondemand_dell_preso_210810.pdf) | [Video](https://www.dellhpc.org/event_8-11-2021.html)  |
| 2020-10-20 | IBM User Group Meeting | Power plus Open OnDemand: facilitating the transition from new to Power user | [Download](https://figshare.com/articles/presentation/Power_plus_Open_OnDemand_facilitating_the_transition_from_new_to_Power_user/13161266) | [Video](https://www.youtube.com/watch?v=IEXcJ2KM33g)  |
| 2020-7-08 | SGCI Monthly Webinars | Supercomputing. Seamlessly. Interactive computing via Open OnDemand. Everywhere.  | [Download](https://figshare.com/articles/presentation/Open_OnDemand_SGCI_Preso_200701/12597512) | [Video](https://youtu.be/bnDl7Tht1wc)  |
| 2020-7-02 | NVIDIA HPC Summit 2020 | Integrating Cloud Tools to HPC Workflows  | [Download](https://figshare.com/articles/presentation/NVIDIA_HPC_Summit_2020_-_Integrating_Cloud_Tools_to_HPC_Workflows/12597521) | Video  |
| 2020-3-18 | CaRRC Emerging Centers Track | Open OnDemand Project Summary | [Download](https://figshare.com/articles/Open_OnDemand_CaRRC_Preso_200317/12006030) | [Video](https://www.youtube.com/watch?v=0jUAUlcUfYg&feature=youtu.be) |
| 2020-1-17 | OOD Team | Open OnDemand Live Demo | N/A | [Video](https://www.youtube.com/watch?v=4-w-4wjlnPk&list=PLiHVyvLHAIcw2sM_MYNVX9B1vBmJgEmW3) |
| 2019-11-07 | Ohio Supercomputer Center | OSC in the Classroom | N/A | [Video](https://vimeo.com/showcase/3166426/video/371705899) |
| 2019-8-20 | OOD Team | Open OnDemand and OpenHPC             | [Download](https://figshare.com/articles/Open_OnDemand_and_OpenHPC/9693260) | [Video](https://vimeo.com/355385200) |
| 2019-4-17 | OOD Team | Open OnDemand Project Recap and Roadmap             | [Download](https://figshare.com/articles/Open_OnDemand_Project_Recap_and_Roadmap/8009687) | [Video](https://www.youtube.com/watch?v=aO679rz1PsE) |
| 2018-10-17 | OOD Team |  Using Open OnDemand for Training and Education             | [Download](https://figshare.com/articles/Using_Open_OnDemand_for_Training_and_Education/7224779) | [Video](https://www.youtube.com/watch?v=OXwfER4NVrQ) |
| 2018-03-28 | Ohio Supercomputer Center | OSC OnDemand | N/A | [Video](https://vimeo.com/showcase/3166426/video/262284498) |
| 2018-01-29 | OOD Team | Customizing and Extending Open OnDemand                     | [Download](https://figshare.com/articles/Customizing_and_Extending_OnDemand/6225803)                      | [Video](https://www.youtube.com/watch?v=OxNBSk5_sTw)                                                                                                    |
| 2017-09-06 | OOD Team | Open OnDemand – Jupyter, iHPC, and Authentication           | [Download](https://figshare.com/articles/Open_OnDemand_1_0_Jupyter_App_Development_Authentication/6225791)            | [Video - Missing 1st 9.5 min](https://vimeo.com/album/4960657/video/253850063) [Audio – Complete](http://www.osc.edu/sites/osc.edu/files/media/2017_0906_OpenOnDemand_Jupyter.m4a) |
| 2017-06-07 | OOD Team | Open OnDemand: Supporting your HPC needs now more than ever | [Download](https://figshare.com/articles/Open_OnDemand_Supporting_your_HPC_needs_now_more_than_ever/6225788) | [Video](https://vimeo.com/album/4960657/video/253852832)                                                                            |
| 2017-03-08 | OOD Team | Introducing Open OnDemand                                   | [Download](https://figshare.com/articles/Open_OnDemand_Open_Source_General_Purpose_HPC_Portal/6225785)                                    | [Video](https://vimeo.com/album/4960657/video/253847906)                                                                                                               |

### Conferences / Publications

| Date | Publisher/Event | Title | Content Access |
| :----: | :----: | :----: | :----: |
| 2021-08-03 | Trusted CI | Initial Findings of the 2021 Trusted CI Annual Challenge on Software Assurance | [Download](https://blog.trustedci.org/2021/08/initial-findings-of-2021-trusted-ci.html) |
| 2021-07-20 | PEARC'21 | Open OnDemand User Group BoF | [Download](https://figshare.com/articles/presentation/Open_OnDemand_PEARC_User_Group_BoF/15048225) |
| 2021-07-19 | PEARC'21 | HPC Toolset Tutorial | [Download](https://figshare.com/articles/presentation/Open_OnDemand_PEARC_User_Group_BoF/15048225)  |
| 2021-07-12 | Microsoft | Azure HPC OnDemand Platform: Cloud HPC made easy. | [Download](https://techcommunity.microsoft.com/t5/azure-global/azure-hpc-ondemand-platform-cloud-hpc-made-easy/ba-p/2537338) |
| 2021-06-18 | HPCwire | OSC Enables On-Demand HPC for Automotive Engineering Firm | [Download](https://www.hpcwire.com/2021/06/18/osc-enables-on-demand-hpc-for-automotive-engineering-firm/) |
| 2021-04-28 | HPCSIG | Open OnDemand Overview | [Download](https://figshare.com/articles/presentation/Open_OnDemand_HPCSIG_Presentation/14501892) |
| 2021-02-16 | Trusted CI | Trusted CI Begins Engagement with Open OnDemand | [Download](https://blog.trustedci.org/2021/02/trusted-ci-begins-engagement-with-open.html) |
| 2021-02-15 | Kent State | KSU architecture students access supercomputers to help with coursework | [Download](http://www.kentwired.com/latest_updates/article_0bf46058-6e50-11eb-8aee-f334e4dc53b2.html) |
| 2021-02-02 | Google | Introducing HPC VM images—pre-tuned for optimal performance | [Download](https://cloud.google.com/blog/topics/hpc/introducing-hpc-vm-images) |
| 2021-02-01 | HPCWire | Ohio Supercomputing Center Provides Students Remote Access to Clusters During COVID-19 Crisis | [Download](https://www.hpcwire.com/off-the-wire/ohio-supercomputing-center-provides-students-remote-access-to-clusters-during-covid-19-crisis/) |
| 2021-01-19 | Intel | Case Study: Ohio Supercomputer Center OnDemand Portal Accelerates Remote Learning | [Download](https://www.intel.com/content/dam/www/public/us/en/documents/case-studies/ohio-supercomputer-center-ondemand-portal-case-study.pdf) |
| 2021-01-07 | ICICT 2021 | Open OnDemand as a platform for Virtual Learning in Higher Education | [Download](https://figshare.com/articles/journal_contribution/Open_OnDemand_as_a_platform_for_Virtual_Learning_in_Higher_Education/13542026) |
| 2020-12-22 | HPCWire | OnDemand Portal Accelerates HPC Work for Academic and Industrial Users | [Download](https://www.hpcwire.com/2020/12/21/ondemand-portal-accelerates-hpc-work-for-academic-and-industrial-users/) |
| 2020-12-03 | Concurrency and Computation: Practice and Experience | Open OnDemand: State of the Platform, Project and the Future | [Download](https://figshare.com/articles/journal_contribution/Open_OnDemand_State_of_the_Platform_Project_and_the_Future/13161248) |
| 2020-10-19 | Gateways'20 | Cloud HPC with Open OnDemand and Cloudy Cluster | [Download](https://figshare.com/articles/poster/Cloud_HPC_with_Open_OnDemand_and_Cloudy_Cluster/13150703) |
| 2020-10-13 | Gateways'20 | Open OnDemand, Open XDMoD, and ColdFront: An HPC center management toolset | [Download](https://figshare.com/articles/presentation/UntitledOpen_OnDemand_Open_XDMoD_and_ColdFront_An_HPC_center_management_toolset_Item/13150676) |
| 2020-08-25 | OOD Advisory Group Quarterly | Open OnDemand Update | [Download](https://figshare.com/articles/presentation/Open_OnDemand_Advisory_Group_update/13150649) |
| 2020-07-28 | PEARC'20 | Open OnDemand User Group BOF | [Download](https://figshare.com/articles/presentation/Open_OnDemand_User_Group_BoF/13150619) |
| 2020-07-27 | PEARC'20 | Open OnDemand, Open XDMoD, and ColdFront: An HPC center management toolset | [Download](https://figshare.com/articles/presentation/Open_OnDemand_Open_XDMoD_and_ColdFront_An_HPC_center_management_toolset/13150691) |
| 2020-07-16 | Big Ten Academic Alliance Research Computing Group | Open OnDemand Overview | [Download](https://figshare.com/articles/presentation/Enabling_AI_DL_via_Containers_and_Open_OnDemand/13161254) |
| 2020-06-18 | HPC Knowledge Meeting'20 | Enabling AI/DL via Containers and Open OnDemand | [Download](https://figshare.com/articles/presentation/Open_OnDemand_overview/13150628) |
| 2020-04-30 | OOD Advisory Group Quarterly | Open OnDemand Update | [Download](https://figshare.com/articles/presentation/Open_OnDemand_update/13150661) |
| 2020-03-26 | Tools and Techniques for High Performance Computing - Selected Workshops | Portals for Interactive Steering of HPC Workflows | [Download](https://link.springer.com/chapter/10.1007/978-3-030-44728-1_11) |
| 2020-03-25 | GTC'20 | Supercomputing. Seamlessly. Interactive computing with GPUs via Open OnDemand. Everywhere. | [Download](https://figshare.com/articles/presentation/Supercomputing_Seamlessly_Interactive_computing_with_GPUs_via_Open_OnDemand_Everywhere_/13160849) |
| 2020-02-26 | Lenovo User Meeting | HPC at VT | [Download](https://figshare.com/articles/presentation/HPC_at_VT/13160840) |
| 2020-02-13 | 2020 NSF CSSI PI Meeting | Better access to HPC with Open OnDemand | [Download](https://figshare.com/articles/Better_access_to_HPC_with_Open_OnDemand/11632173) |
| 2020-02-13 | 2020 NSF CSSI PI Meeting | Open OnDemand Project Summary | [Download](https://figshare.com/articles/Open_OnDemand_Project_Summary/11632335) |
| 2020-02-10 | OOD Advisory Group Quarterly | Open OnDemand Update | [Download](https://figshare.com/articles/presentation/Untitled_Item/13160819) |
| 2020-01-13 | GIR Research Technology Work Group Monthly Call | Open OnDemand Project Summary | [Download](https://figshare.com/articles/presentation/Open_OnDemand_Overview/13150604) |
| 2019-12-10 | Proceedings of the ISC19 Workshop on Interactive High-Performance Computing | Open OnDemand: HPC for Everyone | [Download](https://figshare.com/articles/Open_OnDemand_HPC_for_Everyone/11350130) |
| 2019-11-13 | Nor-Tech | Southwest Research Institute Takes Advantage of Nor-Tech’s Trailblazing Cluster Utility | [Download](https://www.nor-tech.com/wp-content/uploads/2019/11/nor-tech-case-study-swri.pdf)
| 2019-11-20 | SC'19 | Open OnDemand User Group BoF | [Download](https://figshare.com/articles/Open_OnDemand_SC19_User_Group_BoF_Presentation/10315982) |
| 2019-11-18 | Third Workshop on Interactive High-Performance Computing | Portals for Interactive Steering of HPC Workflows | [Download](https://figshare.com/articles/presentation/Portals_for_interactive_sterring_of_HPC_workflows/13162043)  |
| 2019-11-01 | OSC Annual Research Report | Processing Power | [Download](https://www.osc.edu/research/research-reports/2019/processing_power) |
| 2019-11-01 | OSC Annual Research Report | Process Automation | [Download](https://www.osc.edu/research/research-reports/2019/process_automation) |
| 2019-09-23 | Gateways 19 | Open OnDemand: State of the Platform and the Project | [Download](https://figshare.com/articles/Open_OnDemand_Gateways_2019_Presentation/9892124) |
| 2019-07-30 | PEARC 19 | Open OnDemand User Group BoF | [Download](https://figshare.com/articles/Open_OnDemand_User_Group_BoF/9170768) |
| 2019-07-30 | PEARC 19 | Scaling R Shiny Apps to Multiple Concurrent Users in a Secured HPC Environment Using Open OnDemand |  [Download](https://figshare.com/articles/Scaling_R_Shiny_Apps_to_Multiple_Concurrent_Users_in_a_Secured_HPC_Environment_Using_Open_OnDemand/9169955) |
| 2019-07-29 | ACM SIGHPC SYSPROS Symposium / PEARC 19 | Deploying and Managing an OnDemand Instance | [Download](https://figshare.com/articles/Deploying_and_Managing_an_OnDemand_Instance/9170585) |
| 2019-06-19 | ISC19 Workshop on Interactive High-Performance Computing | Open OnDemand Pre-conference Paper | [Download](https://figshare.com/articles/Open_OnDemand_ISC19_Workshop_on_Interactive_High-Performance_Computing_Pre-conference_Paper/8300639) |
| 2019-06-19 | ISC19 Workshop on Interactive High-Performance Computing | Open OnDemand Presentation | [Download](https://figshare.com/articles/Open_OnDemand_ISC19_Workshop_on_Interactive_High-Performance_Computing_Presentation/8300603) |
| 2019-06-05 | NITRD Middleware And Grid Interagency Coordination (MAGIC) Meeting | Open OnDemand Overview | [Download](https://figshare.com/articles/Open_OnDemand_Project_Overview/8233421) |
| 2018-09-26 | Gateways 2018 Presentation | Accessing Distributed Jupyter/Spark in OnDemand | [Download](https://figshare.com/articles/Accessing_Distributed_Jupyter_Spark_in_OnDemand/7137995) |
| 2018-09-10 | Gateways 2018 Poster | Open OnDemand:  Access Clusters, Gateways and Interactive Apps | [Download](https://figshare.com/articles/Open_OnDemand_Access_Clusters_Gateways_and_Interactive_Apps/7069691) |
| 2018-09-10 | Gateways 2018 Paper | Accessing Distributed Jupyter / Spark in OnDemand | [Download](https://figshare.com/articles/Accessing_Distributed_Jupyter_Spark_in_OnDemand/7069679) |
| 2018-07-25 | PEARC 18 Paper | Supporting distributed, interactive Jupyter and RStudio in a scheduled HPC environment with Spark using Open OnDemand | [Download](https://figshare.com/articles/Supporting_distributed_interactive_Jupyter_and_RStudio_in_a_scheduled_HPC_environment_with_Spark_using_Open_OnDemand/6887693) |
| 2018-07-24 | PEARC 18 BOF | Open OnDemand – Present and Future Plans | [Download](https://figshare.com/articles/Open_OnDemand_PEARC18_BOF_Slides/6856832) |
| 2018-07-23 | PEARC 18 Exhibit | Open OnDemand Overview | [Download](https://figshare.com/articles/Open_On_Demand_Overview/6856847) |
| 2018-07-20 | Flier | Open OnDemand General Flier | [Download](https://figshare.com/articles/Open_OnDemand_Overview_Flier/6887546) |
| 2018-05-17 | HPCwire Article | Democratizing HPC: OSC Releases Version 1.3 of OnDemand, Seeks Grant for 2.0 | [Download](https://www.hpcwire.com/2018/05/16/democratizing-hpc-osc-releases-version-1-3-of-ondemand-seeks-grant-for-2-0/) |
| 2018-05-15 | Journal of Open Source Software (JOSS) | Open OnDemand: A web-based client portal for HPC centers | [Download](http://joss.theoj.org/papers/10.21105/joss.00622) |
| 2018-04-30 | NSF SI2 PI Workshop | Open OnDemand: Access Clusters, Gateways and Interactive Apps | [Download](https://figshare.com/articles/Open_OnDemand_Access_Clusters_Gateways_and_Interactive_Apps/6173918/1) |
| 2017-10-10 | CASC Meeting | Open OnDemand 1.1: Web and Interactive HPC Access | [Download](https://figshare.com/articles/Open_OnDemand_1_1_Web_and_Interactive_HPC_Access/6225734) |
| 2017-10-09 | Gateways17 | Demo: Developing Apps to Extend Open OnDemand - Paper | [Download](https://figshare.com/articles/Demo_Developing_Apps_to_Extend_Open_OnDemand/6225746) |
| 2017-10-09 | Gateways17 | Demo: Developing Apps to Extend Open OnDemand - Slides | [Download](https://figshare.com/articles/Open_OnDemand_Gateways/8236367) |
| 2017-07-12 | PEARC17 | Open OnDemand: Current Status and Future Plans | [Download](https://figshare.com/articles/Open_OnDemand_Current_Status_and_Future_Plans/6225749) |
| 2017-05-02 | SIGHPC Education | Open OnDemand: A Web Platform for HPC with applications in the classroom | [Download](https://figshare.com/articles/Open_OnDemand_A_Web_Platform_for_HPC_with_applications_in_the_classroom/6225770) |
| 2017-01-19 | NSF SI2 PI Workshop | Open OnDemand: Access Clusters, Gateways and Interactive Apps | [Download](https://figshare.com/articles/Open_OnDemand_Access_Clusters_Gateways_and_Interactive_Apps/6225758) |
| 2016-10-07 | Gateways16 | Open OnDemand: A Unified Platform for Science Gateway Apps | [Download](https://figshare.com/articles/Open_OnDemand_A_Unified_Platform_for_Science_Gateway_Apps/6225755) |
| 2016-10-07 | XSEDE16 | Open OnDemand: Transforming Computational Science Through Omnidisciplinary Software Cyberinfrastructure | [Download](https://figshare.com/articles/Open_OnDemand_Transforming_Computational_Science_Through_Omnidisciplinary_Software_Cyberinfrastructure/6225779) |
| 2013-06-13 | XSEDE13 | OSC OnDemand: A Web Platform Integrating Access to HPC Systems, Web and VNC Applications | [Download](https://figshare.com/articles/OSC_OnDemand_A_Web_Platform_Integrating_Access_to_HPC_Systems_Web_and_VNC_Applications/6225776) |

### Branding
Open OnDemand branding assets are available in the [GitHub repository](https://github.com/OSC/Open-OnDemand/tree/gh-pages/assets/images/2017_1108%20Open%20OnDemand%20logo).  Organizations are encouraged to utilize them in their own presentations and installations.

### Software Licensing
Open OnDemand code is released under the [MIT License](https://opensource.org/licenses/MIT).  Documentation and most publications are released under the [CC BY 4.0 License](https://creativecommons.org/licenses/by/4.0/)

### Maintained by OSC

This project is maintained by the [Ohio Supercomputer Center (OSC)](https://www.osc.edu), 
a member of the [Ohio Technology Consortium](https://www.oh-tech.org/), the technology and information
division of the [Ohio Department of Higher Education](https://education.ohio.gov/).
