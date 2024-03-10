# Ai-Deep-Learning-2024

This project aims to address the common issue faced by students of finding books that interest them in libraries, particularly school libraries. Often, many books remain unused due to students struggling to find ones that suit their taste or pique their interest. To alleviate this problem, we've developed a solution leveraging generative AI to provide summaries of books along with visually stimulating imagery to help students comprehend the content better.

## Functionality
1. **Scan the barcode of the book:** Start by scanning the barcode of the book you're interested in. This will provide the ISBN of the book.

2. **Retrieve book summary:** Use the obtained ISBN to fetch the summary of the book from the Google Books API. This summary will give you a concise overview of the book's content.

3. **Generate visualizations:** With the help of the Leonardo AI API, each sentence of the book summary will be used to generate an image depicting its contents. These images aim to provide visual aids to help students better understand the content.

4. **Listen to the summary:** The Elevenlabs API is then utilized to read out the summary sentence by sentence. This audio narration, coupled with visual aids, enhances the comprehension of the book's content.

## Requirements
- Python 3.x
- Jupyter Notebook
- ffmpeg
- numpy
- googlebooks API (please do have an API Key)
- leonardo API (please do have an API Key)
- elevenlabs API (please do have an API Key)

Note: numpy and elevenlabs will be installed upon running the Jupyter Notebook. Please do ensure an up-to-date version of [ffmpeg](https://ffmpeg.org) is installed on your system to allow the ElevenLabs API to output audio.

## Installation
clone the repository
`git clone https://github.com/yourusername/generative-book-visualization.git`

# Contributing
[ProjektKevin](https://github.com/ProjektKevin)
[GabrielxKuek](https://github.com/GabrielxKuek)
[Arnav Salkade](https://github.com/Arnie016)
