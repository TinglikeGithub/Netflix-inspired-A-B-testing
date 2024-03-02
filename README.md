**About Me**

My name is Ting Pan. I am currently pursuing a Master's degree in Data Science, complemented by a rich foundation in Economics, Finance, and Law. My keen interest lies in utilizing data science to address tangible real-world challenges.

**Project Description**


The objective of these Netflix-inspired experiments is to enhance the Netflix homepage by reducing browsing time, which refers to the duration users spend navigating the platform. Extended browsing periods can negatively impact user engagement by inundating users with choices, potentially diminishing their interest in viewing content. 

The experiments involve assessing four key design factors—Tile Size, Match Score, Preview Length, and Preview Type—to identify their influence on browsing time. By conducting a series of experiments, I aim to determine the significant factors affecting browsing time and identify the optimal configuration that minimizes expected browsing time.

Tile Size: The ratio of a tile’s height to the overall screen height. Region of Operability = [0.1, 0.5]

Match Score: A prediction of how much you will enjoy watching the show or movie. Region of Operability = [0, 100]

Preview Length: The duration (in seconds) of a show or movie’s preview. Region of Operability = [30, 120]

Preview Type: The type of preview that is autoplayed. Region of Operability = {TT, AC}: TT stands for teaser/trailer and AC stands for actual content

**Outcome**

The location of the minimum browse time when viewing Netflix suggestions was when the preview length = 75, match score = 75, tile size = 0.2, and preview type = TT.
