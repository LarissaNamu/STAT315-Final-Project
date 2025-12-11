# STAT315-Final-Project

Opening the report:
1. clone this repo by doing git clone https://github.com/LarissaNamu/STAT315-Final-Project.git
2. navigate to the folder where you cloned the repo by doing cd <insert\path\to\repo>
3. once you know you are at the folder location where the dockerfile exists, do docker build -t lego-analysis .
4. then run the container by doing docker run -p 8888:8888 lego-analysis
5. notebook will be available for view in the url specified by the terminal (should be port 8888)
