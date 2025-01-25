The purpose of this repository is to enable a relatively simple implementation of Blender in existing mpi structures. As a special feature, Blender is provided as a vanilla version that does not require any special modification. The main target group are HPC clusters with a strong focus on pure cpu performance. Blender is used in the configuration as a Python module which has to be compiled beforehand. Since the render is executed by a single core as a process, it is possible to work with these scripts on shared nodes and especially on more strictly regulated HCP clusters.


As a disclaimer, this repository has no claim to completeness and was only created quickly and easily for a specific project. Nevertheless, since it might help someone else who wants to realize something similar I would like to share my work. 

Translated with DeepL.com (free version)
