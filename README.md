# Sprint_Four_Project
 This is a sample project per assignment
 
This is the URL for this project:

https://sprint-4-project-first-draft.onrender.com/

Apparently, the plotly_express extension doesn't exist. I'm using this README text extension to document my findings.

In my Terminal in the VSCode Document, I've keyed in the streamlit run app.py command, and the result URL was this:

http://127.0.0.1:10000/

I'm looking forward to feedback in completing this Project.

UPDATE FOR PROJECT REVISION:
- Even with 'plotly.express' the app does't run. HOOWWWW?!?!

  -Because there wasn't a requirements.txt file in the main directory to begin with...
  
- I've updated the EDA assessment from the inital Jupyter notebook as well as the csv path into the directory, and not from my local machine.
- As I understand, the config.toml does reside within the .streamlit folder.
- Draft subject to change...

...how can you run this particular program:
- streamlit run app.py

Thus far with the directory pieces in place, the only problem remaining is the failed efforts in building the app via Render. This command:
-pip install streamlit & pip install -r requirements.txt
...just doesn't seem to suffice. By adding in this command after it:
- & pip install --upgrade pip
...appears as if the build is somewhat successfull, but the last line of code appears as:

bash: streamlit: command not found

...Why is that?

