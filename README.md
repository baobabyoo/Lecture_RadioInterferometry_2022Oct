# Lecture: Radio Interferometry
* Time: (2022O October 05 - November 30) 2:20-5:20 pm, Wednesday
* Lecturer: [Hauyu Baobab Liu](https://baobabyoo.github.io/) (呂浩宇)
* Location: NTNU, College of Science, Building B413 (理學院B413)
* Language: English
* Off-class communication interface: this github page

<img src="./images/Lecture_RadioInterferometry_2022Oct_QR.png" alt="QRcode" width="200px"/>

## Syllabus:
1. (October 05) Principle of radiation; basic observational parameters; how to check [ALMA data archive](https://almascience.nao.ac.jp/aq/) and produce publication-level figures.
2. (October 12) Single-dish telescope; SMA proposal preparation
3. (October 19) Interferometer; SMA proposal discussion
4. (October 26) Principle of data calibration; SMA observing script preparation
5. (November 02) Participate observations as a post mid-term party (date and time TBD; **likely on Friday, from 7 pm to 10 pm; food will be served**)
6. (November 09) Error recognition; Hands-on data calibration
7. (November 16) Noise; Hands-on data calibration
8. (November 23) Principle of imaging; hands-on imaging session
9. (November 30) Final (group) presentation

## Goal:
1. Being able to download archival ALMA data, examine images, and produce figures.
  * Installing [CASA software package](https://casa.nrao.edu/)
  * Trying [ALMA data archive](https://almascience.nao.ac.jp/aq/)
  * Using the [APLpy python package](https://aplpy.github.io/) to create PDF figures.
2. Knowing the principles of radio interferometry.
3. Knowing how to use the [Submillimeter Array](http://sma1.sma.hawaii.edu/)
  * Proposing (for some instruction see [my webpage](https://baobabyoo.github.io/pages/students_topics/UsingTelescope_SMA.html))
  * Calibrating data using either the [CASA software package](https://casa.nrao.edu/) or [MIR IDL software package](https://lweb.cfa.harvard.edu/~cqi/mircook.html) (requiring an access to [IDL](https://www.l3harrisgeospatial.com/docs/idl_programming.html))

## Expectation:
1. This is a 3-credits' course. The expected weekly workload for you is 2 hours on average if you have no experience and knowledge in this area.
2. There is no final exams. The workload for you to produce your final report may be 10~15 hours if you have no experience and knowledge in this area.

## Assessment (tentative):
Students will be divided in to groups (3 groups in total, ~3 members in each group).
1. **(30 points)** Each group is expected to hand in an SMA proposal (Abstract, 1 page text for technical setup, and 1 page figure) **for the observations that can be carried out at night time in late October or early November** before October 26. If there is no error then everybody in the group will get 30 points. In case of small errors (e.g., over optimistic or pessimistic sensitivity estimates or no sensitivity estimate at all) you may get 15~30 points. You may get **0 point** in case of inattentive errors (e.g., your proposed observations can only be carried out during daytime, the proposed observing frequency is not supported by the SMA, requiring infeasibly fine angular resolution or unreasonably large mosaic field of view, etc). **You can bring up your proposal for a discussion in the lecture on October 19 during when we can screen most of the inattentive errors.**
2. **(70 points)** Demo your data reduction in the final presentation (1 hr for each group). The presentation will be led by only 1 person I randomly select. You get **55~70 points** if you can obtain an image and if the signal-to-noise is within 50% of my calibration (the exact grade depends on how well the presenter explain the data calibration); you get **40~55 pointgs** if you obtain an image but the signal-to-noise or absolute flux is way off; you get **0 points** in case of not being able to obtain an image. *We will calibrate your data during the hands-on sessions on November 09 and 23. We may track down your problem in the data reduction unless you are really unprepared. But if one of the member in a group stays inattentive and he happens to be selected as the one who is going to lead the final presentation, then, that is the bitter part of the life...*

There is no roll call. If you are confident that you can prepare and submit a proper proposal and you can reduce SMA data and yield an image, you do not have to show up.

## Software:
1. [MIR IDL](https://lweb.cfa.harvard.edu/~cqi/mircook.html) (recommended but not required)
2. [Miriad](https://lweb.cfa.harvard.edu/sma/miriad/) (recommended but not required)
3. [CASA](https://casa.nrao.edu/) You better install it.
4. If you need a workstation to host the archival ALMA data or to calibrate your SMA observations to be taken, please reply to [Issue 1](https://github.com/baobabyoo/Lecture_RadioInterferometry_2022Oct/issues/1). We will create a tentative account for you to login to the powerful workstations at [ASIAA](http://www.asiaa.sinica.edu.tw/). I will let you know how to use VPN to connect to our internal network. If your OS is Microsoft Windows, you may ssh to a Linux workstation using the [PuTTY](https://www.putty.org/) interface (I used to use this one although that was 2 decades ago... there may be newer ones).
5. If you do not know how to use Linux and if you read Chinese, this webpage  [鳥站](https://linux.vbird.org/linux_basic/redhat6.1/linux_06command.php) may help.

## Suggested Textbooks:
1. [Synthesis Imaging in Radio Astronomy II](https://www.aspbooks.org/a/volumes/table_of_contents/?book_id=292) (primary; free to download)
2. [Interferometry and Synthesis in Radio Astronomy](https://link.springer.com/book/10.1007/978-3-319-44431-4) (advanced reference)
3. [Tools of Radio Astronomy](https://link.springer.com/book/10.1007/978-3-540-85122-6) (handy but buggy)
4. All qualitative introduction is given in [my webpage](https://baobabyoo.github.io/pages/students_topics/AstroBasic_RadioInterferometer.html)
