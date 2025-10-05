Ubuntu Image Fetcher 🐧
"I am because we are." – The Wisdom of Ubuntu

This project was created as part of the Power Learn Project (PLP) Python assignment titled Ubuntu-Inspired Image Fetcher.
It is a reflection of Ubuntu values — community, respect, sharing, and practicality — expressed through code.

🌍 Project Overview

The Ubuntu Image Fetcher is a Python tool that connects to the global web community to download and organize shared images.
It allows users to input one or multiple image URLs, fetches the images responsibly, and stores them neatly in a folder called Fetched_Images.

The program practices respect by handling all errors gracefully and verifying that each downloaded file is safe and valid.

✨ Features

Fetches one or multiple image URLs at once.

Automatically creates a folder called Fetched_Images if it doesn’t exist.

Handles connection, timeout, and HTTP errors respectfully without crashing.

Checks HTTP headers to ensure that the file being downloaded is an image.

Prevents duplicate downloads.

Displays friendly and informative terminal messages.

💡 Ubuntu Principles Demonstrated
Principle	Implementation
Community	Connects to multiple sources by supporting several URLs at once.
Respect	Gracefully handles all errors and invalid inputs.
Sharing	Organizes images in a shared, accessible folder.
Practicality	Provides a useful and responsible image collection tool.
🧠 Tools and Technologies

Python 3

Requests library

OS and urllib.parse modules

📚 How It Works

The program welcomes the user with a friendly message.

It asks for one or more image URLs (separated by commas).

It fetches each image responsibly from the internet.

It checks that the file is indeed an image.

It saves all images into a folder named Fetched_Images.

It skips any duplicates or invalid URLs.

Finally, it ends with an Ubuntu-inspired message of connection and community.

🧩 Example Output
Welcome to the Ubuntu Image Fetcher
A tool for mindfully collecting images from the web

Please enter the image URL: https://example.com/ubuntu-wallpaper.jpg
✓ Successfully fetched: ubuntu-wallpaper.jpg
✓ Image saved to Fetched_Images/ubuntu-wallpaper.jpg

Connection strengthened. Community enriched.
Ubuntu reminds us: "A person is a person through other persons."

👩‍💻 Author Information

Name: Hadassa Kimani
Email: wangarikimanih@gmail.com

GitHub Repository: Ubuntu_Requests

Institution: Power Learn Project (PLP)
Date: October 2025
