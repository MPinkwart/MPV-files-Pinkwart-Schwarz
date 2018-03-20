# MPV-files-Pinkwart-Schwarz

--- Author: Marvin Pinkwart, Jacobs University Bremen ---

--- Mail: m.pinkwart [at] jacobs-university.de ---

--- Date: 03/20/2018 ---

--- Content: Description of MPV files ---


-- 1) CONTENT OF MPV FILES --

In this repository we provide four text files containing the MPVs of COMMANDER, NILC, SEVEM and SMICA resp., obtained from Planck second release full mission intensity data (https://irsa.ipac.caltech.edu/data/Planck/release_2/all-sky-maps/matrix_cmb.html) with the MPV calculation program of C.Copi (http://www.phys.cwru.edu/projects/mpvectors/#code). The MPVs start with l=2, end with l=50 and are given in galactic coordinates in degrees. The results obtained with the MPV data can be found in the preprint $LINK$.

-- 2) STRUCTURE OF MPV FILES --

The files contain one MPV per line, given in galactic coordinates "longitude/lattitude" in degrees. The structure is as follows: 

l=2, j=1

l=2, j=2

l=3, j=1

l=3, j=2

l=3, j=3

...

...

...

l=50, j=49

l=50, j=50

That means the j-th vector of a given multipole number l can be found in line l(l-1)/2 - 1 + j. Note that the MPVs of a given l are not naturally ordered among themselves and therefore it is not possible to directly identify the j-th vector of the l-multipole for different maps. One would have to order them according to longitude or lattitude values first.
