# Chat-to-YouTube-Video
Provided a YouTube video link, chat to its content with RAG

## Running Locally
Windows is not supported, so WSL is recommended, especially WSL2.

Clone the repository, create a conda environment, and ```pip install -r requirements.txt```

Create .env file with 


```touch .env```

Edit it with ```vim .env```

[Copy paste your API key you got](https://ai.google.dev/) to .env file as ```GOOGLE_API_KEY=your_api_key```

Open the Jupyter notebook and change the youtube_link_video as you wish. Then, "Run All". At the bottom, you will get a link to the chat UI. Enjoy your talk with the video!

## Running on Cloud
If you do not want to set the environment locally, just go to this [Google Colab Notebook](https://colab.research.google.com/drive/1cABgN0ztqjiUSpnTF9YwFl6zLtZPGS05?usp=sharing), everything is already set.

Create a copy on your drive to use it!

[Get a Google Generative AI API](https://ai.google.dev/), paste it there.

Copy paste your desired YouTube link you want to talk to.

Run All and go to bottom for the chat UI to show up! Enjoy!

![image](https://github.com/user-attachments/assets/c30caab2-cd6a-40b6-8a58-2320d1a3f4b1)

## UI Details and Usage
If you complete one of the two options above and open the UI, talking to the video will be active. You can write anything you want to ask in the **Conversation** tab at "Enter text here" area. Your conversation history will be shown below that. The **"Database"** section on top shows the latest message you asked as "DB query" and below that, "results of DB lookup" shows 3 sections from YouTube video's transcription that are relevant to the question you asked. **"Chat history"** section is same as Conversation tab, just easier to extract and copy if needed. The **"Configure"** section has 2 options. The first one is to write another YouTube video link you want to talk to, just paste it and push Load DB. This will transcript the video and add it to the database to retrieve the relevant documents later on. The second option is "Clear History", which deletes all chat history and also deletes the conversation history in the UI. If you want to start a new topic to talk to, you can choose that. 

You can check the below video for usage examples.

https://github.com/user-attachments/assets/c5a7503f-40d2-46e2-81b0-1ef4da94dc8a

