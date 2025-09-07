This dashboard provides a real-time view of threat intelligence datasets by pulling the latest version of threat_intel.py from GitHub.
It automatically refreshes the module each time you run or interact with the Streamlit app, so you’re always working with the freshest data.

⸻

⚡ Features
	•	✅ Always fetches the latest threat_intel.py from GitHub
	•	✅ Displays the dataset as an interactive table
	•	✅ Visualizes threats with bar and pie charts
	•	✅ Ready to extend with new metrics and data sources

⸻

🛠️ Requirements

Make sure you have Python 3.8+ installed.
Install the dependencies with:
pip install streamlit pandas matplotlib requests

⚠️ Important: threat_intel.py Dependency

The dashboard relies on threat_intel.py to fetch or generate the latest datasets.
	•	dashboard.py does not generate data on its own — it imports and executes functions from threat_intel.py.
	•	Specifically, the dashboard expects a function named load_data() inside threat_intel.py that returns a Pandas DataFrame.
	•	If threat_intel.py has not been set up or run, the dashboard will not display any data.

 Workflow:
 1- python threat_intel.py
 2- streamlit run dashboard.py


<img width="2658" height="1340" alt="image" src="https://github.com/user-attachments/assets/0dd77bd8-426a-443d-a0f6-ef16225481ea" />
<img width="2644" height="1272" alt="image" src="https://github.com/user-attachments/assets/f49e4145-0819-4b58-927b-14b45b22af14" />


 
