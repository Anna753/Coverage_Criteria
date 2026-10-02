Computing Coverage Using the Proposed Criteria:

The project assumes a Python 3.X is installed in the user system.
Additionally, the project requires several packages which are listed in requirements.txt file. 
Below, we provide a detailed guide on how to set up a virtual environment and install the necessary packages for running the project:

1. Download the project in your system.

2. Open terminal and navigate to a folder named 'coverage'.

3. Create a virtual environment. Run on terminal:

python3 -m venv coverage

4. Activate the environment.

5. Install required packages:
pip install -r requirements.txt

6. To run the agents from our benchmark, clone the repository and place the coverage directory in the agent's working directory.
	-- Add the corresponding test_inputs.txt file to each agent's working directory.
	-- Install all agent-specific dependencies and configure any required API keys.
	-- In main.py, the parameter k is set to 10 by default. Modify this value if needed.
	-- Run main.py to execute the agent on the provided test inputs and compute the coverage results.