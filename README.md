CCPBioSim Enhanced Sampling Workshop
====================================

[![build1](https://github.com/jimboid/biosim-enhanced-sampling-workshop/actions/workflows/build-container1.yaml/badge.svg?branch=main)](https://github.com/jimboid/biosim-enhanced-sampling-workshop/actions/workflows/build-container1.yaml)
[![test1](https://github.com/jimboid/biosim-enhanced-sampling-workshop/actions/workflows/test-container1.yaml/badge.svg?branch=main)](https://github.com/jimboid/biosim-enhanced-sampling-workshop/actions/workflows/test-container1.yaml)
[![latest1](https://img.shields.io/badge/dynamic/xml?url=https%3A%2F%2Fgithub.com%2Fjimboid%2Fbackage%2Fraw%2Findex%2Fjimboid%2Fbiosim-enhanced-sampling-workshop%2Fbiosim-enhanced-sampling-workshop-part1.xml&query=xml%2Fversion%5B.%2Fnewest%5B.%3D%22true%22%5D%5D%2Ftags%5B.!%3D%22latest%22%5D%5B.!%3D%22dev%22%5D&logo=github&label=latest&color=purple)](https://github.com/jimboid/biosim-enhanced-sampling-workshop)
[![size1](https://img.shields.io/badge/dynamic/xml?url=https%3A%2F%2Fgithub.com%2Fjimboid%2Fbackage%2Fraw%2Findex%2Fjimboid%2Fbiosim-enhanced-sampling-workshop%2Fbiosim-enhanced-sampling-workshop-part1.xml&query=xml%2Fsize&logo=github&label=size&color=orange)](https://github.com/jimboid/biosim-enhanced-sampling-workshop)
[![pulls1](https://img.shields.io/badge/dynamic/xml?url=https%3A%2F%2Fgithub.com%2Fjimboid%2Fbackage%2Fraw%2Findex%2Fjimboid%2Fbiosim-enhanced-sampling-workshop%2Fbiosim-enhanced-sampling-workshop-part1.xml&query=xml%2Fdownloads&logo=github&label=pulls&color=blue)](https://github.com/jimboid/biosim-enhanced-sampling-workshop)

[![build2](https://github.com/jimboid/biosim-enhanced-sampling-workshop/actions/workflows/build-container2.yaml/badge.svg?branch=main)](https://github.com/jimboid/biosim-enhanced-sampling-workshop/actions/workflows/build-container2.yaml)
[![test2](https://github.com/jimboid/biosim-enhanced-sampling-workshop/actions/workflows/test-container2.yaml/badge.svg?branch=main)](https://github.com/jimboid/biosim-enhanced-sampling-workshop/actions/workflows/test-container2.yaml)
[![latest2](https://img.shields.io/badge/dynamic/xml?url=https%3A%2F%2Fgithub.com%2Fjimboid%2Fbackage%2Fraw%2Findex%2Fjimboid%2Fbiosim-enhanced-sampling-workshop%2Fbiosim-enhanced-sampling-workshop-part2.xml&query=xml%2Fversion%5B.%2Fnewest%5B.%3D%22true%22%5D%5D%2Ftags%5B.!%3D%22latest%22%5D%5B.!%3D%22dev%22%5D&logo=github&label=latest&color=purple)](https://github.com/jimboid/biosim-enhanced-sampling-workshop)
[![size2](https://img.shields.io/badge/dynamic/xml?url=https%3A%2F%2Fgithub.com%2Fjimboid%2Fbackage%2Fraw%2Findex%2Fjimboid%2Fbiosim-enhanced-sampling-workshop%2Fbiosim-enhanced-sampling-workshop-part2.xml&query=xml%2Fsize&logo=github&label=size&color=orange)](https://github.com/jimboid/biosim-enhanced-sampling-workshop)
[![pulls2](https://img.shields.io/badge/dynamic/xml?url=https%3A%2F%2Fgithub.com%2Fjimboid%2Fbackage%2Fraw%2Findex%2Fjimboid%2Fbiosim-enhanced-sampling-workshop%2Fbiosim-enhanced-sampling-workshop-part2.xml&query=xml%2Fdownloads&logo=github&label=pulls&color=blue)](https://github.com/jimboid/biosim-enhanced-sampling-workshop)

This container is derived from the CCPBioSim JupyterHub image. This container
adds the necessary software packages and notebook content to form a deployable
course container. The source content for this course can be found at
https://github.com/rostaresearch/enhanced-sampling-workshop-2022

How to Use
----------

In our containers we are using the JupyterHub default port 8888, so you should
forward this port when deploying locally::

    docker run -p 8888:8888 ghcr.io/jimboid/biosim-enhanced-sampling-workshop-part1:latest
    docker run -p 8888:8888 ghcr.io/jimboid/biosim-enhanced-sampling-workshop-part2:latest
