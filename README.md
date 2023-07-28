# 🧠 Wrapping Your Brain Around LangChain 🦜🔗

This is a repository that is used in conjunction with a [talk](./talk.md) called "Wrapping Your Brain Around Langchain". It is a beginner friendly code-along talk that explores the super powerful large language model application framework [LangChain](https://langchain.com). 

If you are interested in having Craig deliver it, please reach out!

## Installation

This assumes Python 3.11.

```
python -m venv venv
source ./venv/bin/activate
python -m pip install -r requirements.txt
```

Copy the [env.example](./.env.example) file to [.env]. This requires some keys from [OpenAI](https://platform.openai.com), [Replicate](https://replicate.com/), and [SerpAPI](https://serpapi.com/)

## Some self-exploration

Start in [framework.py](./framework.py) to see the basics.

The talk involves creating a virtual [Nintendo Game Counselor](https://vglegacy.com/pop-culture/game-counselors/). You kind of had to be there.
