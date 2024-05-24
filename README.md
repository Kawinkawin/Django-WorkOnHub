

# WorkOnHub

WorkOnHub is a social media application built with Django where users can publish images to their followers or friends, send messages, and interact with posts through likes, dislikes, and comments. Additionally, the application has a unique feature that notifies users about nearby friends or followers, enabling them to meet in person.

## Features

- **Image Publishing**: Users can share images with their followers or friends.
- **Messaging**: Real-time chat functionality to send messages to friends and followers.
- **Post Interactions**: Users can like, dislike, and comment on posts.
- **Proximity Notifications**: Notifies users when their friends or followers are nearby.

## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/yourusername/WorkOnHub.git
    ```

2. **Navigate to the project directory:**

    ```bash
    cd WorkOnHub
    ```

3. **Create a virtual environment:**

    ```bash
    python3 -m venv env
    ```

4. **Activate the virtual environment:**

    - On Windows:

        ```bash
        .\env\Scripts\activate
        ```

    - On macOS and Linux:

        ```bash
        source env/bin/activate
        ```

5. **Install the required dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

6. **Apply migrations:**

    ```bash
    python manage.py migrate
    ```

7. **Run the development server:**

    ```bash
    python manage.py runserver
    ```

## Usage

1. **Sign up for a new account or log in with existing credentials.**
2. **Start publishing images and interact with posts.**
3. **Use the chat feature to message friends and followers.**
4. **Receive notifications when friends or followers are nearby and arrange to meet.**

## Contributing

We welcome contributions! Please follow these steps:

1. **Fork the repository.**
2. **Create a new branch:**

    ```bash
    git checkout -b feature-branch-name
    ```

3. **Make your changes and commit them:**

    ```bash
    git commit -m 'Add some feature'
    ```

4. **Push to the branch:**

    ```bash
    git push origin feature-branch-name
    ```



