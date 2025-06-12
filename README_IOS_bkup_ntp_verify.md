Awesome! Here's a sample Ansible playbook that targets Cisco IOS devices. This playbook does three key things:

1. Connects to Cisco IOS routers/switches

2. Backs up the current running config

3. Configures NTP settings


✅ Verification Logic
We ping each NTP server and:

Capture the result (ping_results)

Show it (so you can review it like a boss)

Fail gracefully if we don’t get 5 exclamation marks (!!!!!) in the ping output—a rough but effective test for success.
