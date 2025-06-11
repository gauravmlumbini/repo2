# repo2
trigger:
- main  # Runs when you push to the main branch

pool:
  vmImage: 'ubuntu-latest'  # Uses a free Microsoft-hosted Linux machine

steps:
- script: echo "Hello, world!"
  displayName: 'Say Hello'
