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
