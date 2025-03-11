# environments

How to get a list of Your Anaconda Environments:
-	Open Anaconda prompt and activate your anaconda environment typing: conda activate your-environment-name
-	Open your environment file typing: notepad environment.yml

How to share a list of Anaconda Environments:
-	Upload the environment.yml file to GitHub repository 
-	Share the link to the file

How to get someone else's list of Anaconda Environment: 
-	Users can run the following command to download the environment directly from GitHub:
in GitBash:
1. To disable SSL checks: git config --global http.sslbackend schannel 
2. To clone the environment: git clone https://github.com/BeNeuroLIN/environments
in Anaconda/Miniconda:
3. Create/Activate the GitHub environment in Anaconda: conda env create -f environment.yml

