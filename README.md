# &#x1F6A9; STREAMLIT


&#x1F535; Definition : 

Streamlit is a free and open-source framework to rapidly build and share beautiful machine learning and data science web apps. It is a Python-based library specifically designed for machine learning engineers. Data scientists or machine learning engineers are not web developers and they're not interested in spending weeks learning to use these frameworks to build web apps. Instead, they want a tool that is easier to learn and to use, as long as it can display data and collect needed parameters for modeling. Streamlit allows you to create a stunning-looking application with only a few lines of code.



&#x1F535; Reference : 

	https://streamlit.io


### &#x1F680; project [test-streamlit-helloworld]

Begin :

	❯ python -m venv venv

	❯ source ./venv/bin/activate

	❯ pip install streamlit


Code : 

	❯ vim streamlit_app.py

		import streamlit as st
		print("hello")
		st.write("Hello world, perubahan ke-2")