# minimal-flask-app
Minimal code for Flask app making calls to the OpenAI API


```
# Create virtual environment
python3 -m venv ./venv

# Activate your virtual environment
source venv/bin/activate

# Install the required packages. For example
pip3 install flask openai python-dotenv

# Rename the file .env-bup to .env 
# Add your OPENAI_API_KEY to the .env file.

# Run the app
python3 app.py
```

# Project Report 
Jungian psychology, with its concepts of archetypes, the collective unconcious, and symbolism, provides a representation for understanding dreams and generating meaningful images. These dream analysis prompts uncover deep psychological meanings behind dreams:
“What figures appear in your dream? Do they represent archetypes like the Shadow, Anima/Animus, or Wise Old Man?”

“What emotions surfaced? Could they reflect inner conflicts or a path to self-integration?”

“Describe the setting—does it resemble Jungian symbols like a labyrinth (self-discovery) or water (the unconscious)?”

In order to integrate Jungian ideas in this project, both dream analysis and image generation become tools for inspirational self-exploration: 
“A mystical forest with an ancient figure, embodying the Sage archetype.”

“A shadowy figure behind a mirror, representing the Jungian Shadow.”

“A glowing mandala in space, symbolizing individuation.”

USER GUIDE FOR WEB APP: 
To use the web app, I've used the flask app, a template from Github, to deploy the project. The app is straight forward and let's the user type in a dream description they wish to implement. They have the option to submit the description to "Create a Jugian Dream". Though it is not a full-stylized web page I wished to customize to my liking, it is very user-friendly and clear to understand that the prompts are descriptive-based from the user's perspective. 

# REFLECTION
In this project, it was challenging because it involved layers of preparing and setting up in terms of the basic flask app.py setup, making sure render web runner was good, and making sure my terminal installed and setup relevant steps. 

In the beginning, I ran into errors after errors which I did not commit in my Github Repository. This lead to having to basically restart my whole project again because I could not back track my progress - lesson learned! Aside from this, I was able to connect the flask and render wbe setup without any errors in my terminal. However, I ran into a major issue with my web's error message stating an Error 403; I cannot connect with the model. Despite it being a dall-e-3 model, I decided to put a model i have used before to test if I have an permissions at all. Surprisingly, none of the models I have listed in my open ai account can be registered at all. I went to go check my account to see if they are enabled for usage and have any limits preventing access, and seems like everything is clear on my open ai account. From this issue, I was unable to generate any images at all. I am not sure if it is an open ai account issue or something I completely missed. 
