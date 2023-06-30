# Worldbuilding Service

## Overview

This service is a chatbot designed to generate immersive worldbuilding scenarios for users. The chatbot takes on the role of renowned worldbuilders suchs as Alec McDowell, responding to user requests for new worlds and providing detailed descriptions and rules for these worlds.


## Features

- **Worldbuilding Conversations**: The chatbot can engage in detailed conversations with users about the kind of world they want to create. This includes discussions about the physical environment, the societies and cultures that inhabit it, and the laws that govern it.

- **Detailed World Descriptions**: The chatbot can generate detailed descriptions of the worlds it creates, including the physical environment, the societies and cultures that inhabit it, and the laws that govern it.

- **User Requests**: Users can send requests to the chatbot asking for a new world. The chatbot will then generate a detailed description of this world and the rules that govern it.

- **Selectable Worldbuilders**: In addition to Alec McDowell, the service offers a variety of worldbuilders that users can choose from. Each worldbuilder has their own unique style and approach to creating worlds, allowing users to choose the one that best fits their needs.

- **Story Analysis**: The service also includes a story analysis feature. Users can submit a story they have written, and the assistant will analyze the story to identify the rules that govern its world and provide a detailed description of the world.


## Usage

Users interact with the chatbot through a series of messages. Each message has a role (either "system", "user", or "assistant") and a content field that contains the actual text of the message. The "system" role is used for messages that set the context of the conversation, the "user" role is for messages from the user, and the "assistant" role is for messages from the chatbot.

Here is an example of a typical conversation:

```json
[
    {
        "role": "system",
        "content": "You are Alec McDowell, a renowned worldbuilder. Users will ask you to create unique and immersive worlds for their stories."
    },
    {
        "role": "user",
        "name": "Alice",
        "content": "Hello Alec, I need a world for my next sci-fi novel. Can you help me with that?"
    },
    {
        "role": "assistant",
        "name": "Alec McDowell",
        "content": "Of course, Alice. Could you tell me a bit more about the kind of world you're envisioning? For example, is it a future Earth, a completely alien planet, or something else?"
    },
    // ... and so on
]
```

## Story Analysis

The service also includes a story analysis feature. Users can submit a story they have written, and the assistant will analyze the story to identify the rules that govern its world and provide a detailed description of the world.

This feature is designed to help users gain a better understanding of the worlds they are creating through their stories. By explicitly identifying the rules and characteristics of the world, users can ensure that their worldbuilding is consistent and immersive.

Here's an example of how this might work:

```json
[
    {
        "role": "system",
        "content": "You are Alec McDowell, a renowned worldbuilder. The user will submit a story, and you will analyze the story to identify the rules that govern its world and provide a detailed description of the world."
    },
    {
        "role": "user",
        "name": "Alice",
        "content": "Here's my story: [insert story here]"
    },
    {
        "role": "assistant",
        "name": "Alec McDowell",
        "content": "Based on your story, the world is [insert world description here]. The rules that govern this world are [insert rules here]."
    }
]
```

## Choose a Worldbuilder

In addition to Alec McDowell, the service offers a variety of worldbuilders that users can choose from. Each worldbuilder has their own unique style and approach to creating worlds, allowing users to choose the one that best fits their needs.

Upon starting a conversation, the system will present the user with a list of available worldbuilders. The user can then select the worldbuilder they want to work with for that session. The selected worldbuilder will then take on the role of the assistant for the duration of the conversation.

Here's an example of how this might look in a conversation:

```json
[
    {
        "role": "system",
        "content": "Welcome to the Worldbuilding Chatbot Service. Please select a worldbuilder from the following list: Alec McDowell, J.R.R. Tolkien, George R.R. Martin, Ursula K. Le Guin, Isaac Asimov."
    },
    {
        "role": "user",
        "name": "Alice",
        "content": "I choose Alec McDowell."
    },
    {
        "role": "system",
        "content": "You have selected Alec McDowell. You can now start your worldbuilding conversation."
    },
    // ... and so on
]
```

# Development
This service is built using OpenAI's GPT-4 model. Developers should familiarize themselves with the OpenAI API and the specific requirements for chat models.

# Contributing
Contributions are welcome! Please read the contributing guidelines before making any changes.

# License
This project is licensed under the terms of the MIT license.
