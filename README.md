# Awesome Behavior Datasets
Open-source datasets for animal behavioral video analysis.


[![Awesome](https://awesome.re/badge.svg)](https://github.com/topics/awesome)
[![Commit](https://img.shields.io/github/last-commit/JackieZhai/awesome-behavior-datasets)](https://github.com/JackieZhai/awesome-behavior-datasets/commits)
[![RepoSize](https://img.shields.io/github/repo-size/JackieZhai/awesome-behavior-datasets)](https://github.com/JackieZhai/awesome-behavior-datasets/archive/refs/heads/master.zip)


## Contents

* [Overview](https://github.com/JackieZhai/awesome-behavior-datasets#overview)
* [Contribution](https://github.com/JackieZhai/awesome-behavior-datasets#contribution)


## Overview

### Mentioned in our papers

<table>
    <tr>
        <th>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Reference&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br><i>first author/year</i></th>
        <th>&nbsp;&nbsp;&nbsp;&nbsp;Name&nbsp;&nbsp;&nbsp;&nbsp;<br><i>for short</i></th>
        <th>Species</th>
        <th>&nbsp;&nbsp;&nbsp;&nbsp;Experiment&nbsp;&nbsp;&nbsp;&nbsp;</th>
        <th>Size<br><i>pixel<sup>2</sup></i></th>
        <th>Resolution<br><i>pixel/mm</i></th>
        <th>Length<br><i>d/h/min/s</i></th>
        <th>Rate<br><i>frame/s</i></th>
        <th>Link</th>
        <th>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Note&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</th>
    </tr>
    <tr>
        <td rowspan="2">Pereira <i>et al.</i> 2022</td>
        <td>flies13</td>
        <td>fly</td>
        <td>freely interacting pairs of virgin male and female</td>
        <td>1024x1024</td>
        <td>30.3</td>
        <td>30min</td>
        <td>200</td>
        <td rowspan="2"><a href="https://doi.org/10.17605/OSF.IO/36HAR">data</a><br><a href="https://sleap.ai/datasets">demo</a></td>
        <td>labeled 2,000 frames with a 13 node skeleton</td>
    </tr>
    <tr>
        <td>mice_hc</td>
        <td>mouse</td>
        <td>pairs of male and female in a home cage with bedding</td>
        <td>1280x1024</td>
        <td>1.9</td>
        <td>5min</td>
        <td>40</td>
        <td>labeled 1,474 frames with a 5 node skeleton</td>
    </tr>
    <tr>
        <td>Lauer <i>et al.</i> 2022</td>
        <td>marmosets</td>
        <td>marmoset</td>
        <td>pairs of male and female (one had light blue dye)</td>
        <td>1080x1080</td>
        <td></td>
        <td>9h</td>
        <td>30</td>
        <td><a href="https://benchmark.deeplabcut.org/">data</a></td>
        <td>used 7,600 labeled frames from 40 individuals with 15 body points</td>
    </tr>
    <tr>
        <td rowspan="3">Sturman <i>et al.</i> 2020</td>
        <td>OFT</td>
        <td rowspan="3">mouse</td>
        <td>open field arena (45×45×40 cm)</td>
        <td></td>
        <td></td>
        <td rowspan="2">10min</td>
        <td></td>
        <td rowspan="3"><a href="https://zenodo.org/record/3608658">data</a><br><a href="https://github.com/ETHZ-INS/DLCAnalyzer">labels</a></td>
        <td>distance, time in center, supported rears and unsupported rears were recorded</td>
    </tr>
    <tr>
        <td>EPM</td>
        <td>arms (65.5×5.5 cm) elevated 61.5 cm</td>
        <td></td>
        <td></td>
        <td></td>
        <td>distance, velocity, time in zone (open/closed arms + center) and head dips were recorded</td>
    </tr>
    <tr>
        <td>FST</td>
        <td>beaker (20 cm diameter, 25 cm deep) filled to 17 cm water</td>
        <td></td>
        <td></td>
        <td>6min</td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>Liu <i>et al.</i> 2020</td>
        <td>a_common_hub</td>
        <td>mouse</td>
        <td></td>
        <td></td>
        <td>30</td>
        <td></td>
        <td></td>
        <td></td>
        <td>labeled ~3,000 random and 5,000 continuous masks, also with EEG and EMG recorded</td>
    </tr>
    <tr>
        <td>Salem <i>et al.</i> 2016</td>
        <td>fisheye_3d</td>
        <td>mouse</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td>labeled 6,500 frames with 4 key-points</td>
    </tr>
</table>

Here we summarize some datasets for animal keypoints tracking

<table>
    <tr>
        <th>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Reference&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br><i>first author/year</i></th>
        <th>&nbsp;&nbsp;&nbsp;&nbsp;Name&nbsp;&nbsp;&nbsp;&nbsp;<br><i>for short</i></th>
        <th>Species</th>
        <th>pictures_num</th>
        <th>Keypoints_num</th>
        <th>have_box</th>
        <th>Link</th>
        <th>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Note&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</th>
    </tr>
    <tr>
        <td>Yu <i>et al.</i> 2021</td>
        <td>AP-10K</td>
        <td>mammals</td>
        <td>10015</td>
        <td>17</td>
        <td>True</td>
        <td><a href="https://openreview.net/forum?id=rH8yliN6C83">data</a></td>        
        <td>23 animal families and 54 species</td>
    </tr>
     <tr>
        <td>Yao <i>et al.</i> 2021</td>
        <td>OMC</td>
        <td>Monkey</td>
        <td>111,529</td>
        <td>17</td>
        <td>True</td>
        <td><a href="https://competitions.codalab.org/competitions/34342#learn_the_details">data</a></td>        
        <td>23 animal families and 54 species</td>
    </tr>
</table>


### Others

<table>
    <tr>
        <th>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Reference&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br><i>first author/year</i></th>
        <th>&nbsp;&nbsp;&nbsp;&nbsp;Name&nbsp;&nbsp;&nbsp;&nbsp;<br><i>for short</i></th>
        <th>Species</th>
        <th>pictures_num</th>
        <th>Keypoints_num</th>
        <th>have_box</th>
        <th>Link</th>
        <th>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Note&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</th>
    </tr>
    <tr>
        <td>Cao <i>et al.</i> 2019</td>
        <td>Animal-Pose</td>
        <td>dog, cat, cow, horse, sheep</td>
        <td> 4,000+</td>
        <td>20</td>
        <td>True</td>
        <td><a href="https://sites.google.com/view/animal-pose/">data</a></td>        
        <td>also contains bounding box annotations for other 7 animal categories</td>
    </tr>
    <tr>
        <td>Mathis <i>et al.</i> 2021</td>
        <td>Horse-10</td>
        <td> horse</td>
        <td> 8,000+</td>
        <td>22</td>
        <td>False</td>
        <td><a href="http://www.mackenziemathislab.org/horse10">data</a></td>        
        <td>30 diverse Thoroughbred horses</td>
    </tr>
    <tr>
        <td>Labuguen <i>et al.</i> 2020</td>
        <td>MacaquePose</td>
        <td> macaque monkeys</td>
        <td> 13，083</td>
        <td>17</td>
        <td>True</td>
        <td><a href="http://www.pri.kyoto-u.ac.jp/datasets/macaquepose/index.html">data</a></td>        
        <td>30 diverse Thoroughbred horses</td>
    </tr>
    <tr>
        <td>Pereira <i>et al.</i> 2019</td>
        <td>Vinegar Fly </td>
        <td> Fly</td>
        <td>1349</td>
        <td>32</td>
        <td>False</td>
        <td><a href="https://github.com/jgraving/DeepPoseKit-Data">data</a></td>        
        <td>frame:192*192</td></td>
    </tr>
    <tr>
        <td>Graving <i>et al.</i> 2019</td>
        <td>Desert Locust</td>
        <td>Desert Locust</td>
        <td> 69</td>
        <td>35</td>
        <td>True</td>
        <td><a href="https://github.com/jgraving/DeepPoseKit-Data">data</a></td>        
        <td>30 diverse Thoroughbred horses</td>
    </tr>
    <tr>
        <td>Graving <i>et al.</i> 2019</td>
        <td>Grévy’s Zebra</td>
        <td>Grévy’s Zebra</td>
        <td>809</td>
        <td>9</td>
        <td>True</td>
        <td><a href="https://github.com/jgraving/DeepPoseKit-Data">data</a></td>        
        <td>30 diverse Thoroughbred horses</td>
    </tr>
    <tr>
        <td>Li <i>et al.</i> 2020</td>
        <td>ATRW</td>
        <td>Amur tiger</td>
        <td>8000+</td>
        <td>17</td>
        <td>True</td>
        <td><a href="https://cvwc2019.github.io/challenge.html">data</a></td>        
        <td>the largest wildlife re-ID dataset to date</td>
    </tr>
     <tr>
        <td>Ng <i>et al.</i> 2022</td>
        <td>Animal Kingdom</td>
        <td>Animal</td>
        <td>8000+</td>
        <td>23</td>
        <td>True</td>
        <td><a href="https://github.com/sutdcv/Animal-Kingdom">data</a></td>  
        <td>140 Action Description, List of >850 animals and classification、Action Recognition、Pose Estimation、Video Grounding</td>
    </tr>
    <tr>
        <td>Yang <i>et al.</i> 2022</td>
        <td>APT-36k</td>
        <td>Animal</td>
        <td>36,000</td>
        <td>17</td>
        <td>True</td>
        <td><a href="https://github.com/pandorgan/APT-36K">data</a></td>  
        <td>2,400 video clips covering 30 different animal species from different scenes</td>
    </tr>
</table>



## Contribution

* [Hao Zhai](https://github.com/JackieZhai)
* [Haiyang Yan](https://github.com/Qingjia0226)

Please [**contribute**](https://github.com/JackieZhai/awesome-em-datasets/pulls) if you think a new dataset or a relevant paper is missing.
