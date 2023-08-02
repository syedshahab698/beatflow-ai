# BeatFlow - AI Rap Song Generator

![BeatFlow AI](rapbot_beats_logo.png)

RapBot Beats is an AI-powered rap song generator that combines lyrics with background music to create original rap songs automatically. This project utilizes Python and the PyDub library for audio processing and synthesis. The AI model behind the rap song generator is powered by OpenAI's GPT-3.5 architecture.
## Listen to the Rap Song

Click [here](https://github.com/syedshahab698/beatflow-ai/blob/master/rap_song.mp3) to listen to the rap song!


## Features

- AI-generated rap lyrics synthesis
- Background music selection and mixing
- Adjustable background music volume
- Automatic export of the final rap song in MP3 format

## Getting Started

### Prerequisites

To run RapBot Beats, you will need the following dependencies:

- Python (>= 3.6)
- PyDub library (`pip install pydub`)
- OpenAI GPT-3.5 API access (if using GPT-3.5-based AI model)

### Installation

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/your-username/beatflow-ai.git
   cd beatflow-ai
   ```

### Install the Required Python Packages

   ```bash
   pip install -r requirements.txt
   ```

## Set up OpenAI GPT-3.5 API Access

To use the OpenAI GPT-3.5-based AI model, you'll need access to the OpenAI GPT-3.5 API and an API key. Follow these steps to set the `OPENAI_API_KEY` environment variable manually:

### On Windows:

1. Open the command prompt.

2. To set the environment variable, execute the following command (replace `YOUR_API_KEY` with your actual OpenAI API key):

   ```bash
   set OPENAI_API_KEY "YOUR_API_KEY"
   ```

### On macOS and Linux:

   ```bash
   export OPENAI_API_KEY="YOUR_API_KEY"
   ```

### Customization
You can customize the AI model, adjust volume levels, and fine-tune the generated rap songs. Check the documentation and source code for more details on customization options.

### Contributing
Contributions are welcome! If you find a bug, have an enhancement, or want to suggest a new feature, please open an issue or submit a pull request. For major changes, please discuss them in an issue before making any modifications.

### License
MIT License
