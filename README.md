# chatgpt-connectors-ip-cidr

A simple site that republishes ChatGPT connector IP addresses as a plaintext CIDR
list.

The GitHub Pages workflow generates `chatgpt-connectors.txt` from
<https://openai.com/chatgpt-connectors.json>, including IPv4 and IPv6 prefixes.
It publishes on pushes to `main`, runs daily at 03:17 UTC, and can also be run
manually from the Actions tab.
