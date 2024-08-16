***->if you are facing issues to install the touch liberary you can use these commands
# Conda
conda install pytorch torchvision cpuonly -c pytorch
# Pip
pip install torch==1.5.0+cpu torchvision==0.6.0+cpu -f https://download.pytorch.org/whl/torch_stable.html


***-> if you face any issue with chroma db installation then
You need to install the required build tools. You can download and install them from the following link:

Microsoft Visual C++ Build Tools:link:(https://visualstudio.microsoft.com/visual-cpp-build-tools/)
During installation, ensure that you include the "Desktop development with C++" workload. This will provide the necessary compilers and libraries needed to build the package.

#code running process
->conda create -p venv python==3.12 -y(create environmental variables)
->conda activate venv/ (to activate env)
->pip install chromadb
->streamlit rum app.py(to run the code)

#Application:
1)Provide the Grooq API key in the GROOQ API KEY SECTION.
2)In the SESSION_ID column you can give any specified section id to remember your history.
3)And ADD the pdf files in the DRAG AND DROP FILES section.
4)Now you can ask questions the LLM Model will refer the pdfs you have submitted and provide the exact answers.
