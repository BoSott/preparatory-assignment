

## Task 2 - Best Practices in Scientific Computing
1. The paper describes several problems scientist face when performing scientific data analyses. From your experience in performing GIS and general data analyses, which of these problems seem familiar to you? Have you faced other problems not mentioned in the paper? (~100 words)

    The main problem described in the paper is the lack of knowledge about basic software development practices as a scientist which seems quite familiar to me in a lot of ways. For me the problem or lack of knowledge starts even before I write the first line of code with setting up the right environment and getting all dependencies working (yes you GDAL). Writing maintainable code is something I can't relate to as I did not write and maintained a bigger project so far. But already in smaller programs I struggle with setting up the right architecture and manage data writing / reading in an efficient and organized way (naming etc.).

2. Which methods described in the paper or which other skills, tools etc. would you like to learn to help you avoid these problems in the future? (~100 words)

    I'd like to get better with setting up environments and understanding more about the background of required system libraries etc. to get to know more about the surroundings of writing code and thus having better educated guesses when something breaks for "no obvious reasons"... Getting used to another package manager than pip - e.g. poetry or something like that would be good. Learning about e.g. templates for good architecture / design for maintainable and efficient code as well as testing (!!) would be great. A more thorougly introduction into debugging would also help a lot. So in short, best practices in: setting things up and understanding errors of the environment and code through more indept knowledge of the surroundings, as well as direct debugging and testing would be highly appreciated.

3. One of the recommendations by Wilson et al. (2014) for scientists is to use a Version Control System (VCS). Briefly explain in your own words, what the benefits of VCS are in the context of scientific analyses. (~100 words)

    The most important benefits in using a VCS in scientific analyses are IMHO the change / version control and the possibility to easily collaborate and simultaniuously work on different areas in the same project through e.g. branches. Issue trackers are also a mayor offset but those are not necessarily part of a VCS but often incorporated into the workflow (e.g. github / gitlab). The enforcement of codestyles (e.g. black) when commiting code can also helop to be consistent with the code style.
