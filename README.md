# Novodo app template

## Making an app

Follow the steps below to create an app

### Fork the repo

Fork this repo

![Fork image](https://raw.githubusercontent.com/NovodoOfficial/novodo/refs/heads/main/other/novodo%20packages/assets/fork.png)

You will see this screen

![Fork UI](./assets/fork%20ui.png)

Add a description (optional)

![Fork description](./assets/fork%20description.png)

Create the fork

![Create fork](./assets/create%20fork.png)

### Configure app

Open the ```app.json``` file, it should look like this:

```json
{
    "details": {
        "name": "My app",
        "description": "Template app",
        "snapshotting": {
            "version": "1.0.0",
            "name": "First release!",
            "notes": "This is the first release of my app"
        }
    },
    "supported": [
        "Windows",
        "Linux",
        "Mac"
    ],
    "buttons": [
        {
            "name": "Run",
            "color": {
                "text": "#ffffff",
                "bg": "9cda4a"
            },
            "file": "run.py"
        },
        {
            "name": "Open UI",
            "color": {
                "text": "fff",
                "bg": "#1aa3e8"
            },
            "file": "ui.py"
        }
    ]
}
```

<button onclick="alert('Button clicked!')">Click Me</button>
