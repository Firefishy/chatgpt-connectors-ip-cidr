# chatgpt-connectors-ip-cidr

A simple site that republishes ChatGPT connector IP addresses as a plaintext CIDR
list.

The published list is available at
<https://firefishy.github.io/chatgpt-connectors-ip-cidr/chatgpt-connectors.txt>.

The GitHub Pages workflow generates `chatgpt-connectors.txt` from
<https://openai.com/chatgpt-connectors.json>, including IPv4 and IPv6 prefixes.
The list includes a UTC generation timestamp; deployments are skipped when the
CIDR data is unchanged. The workflow runs on pushes to `main`, daily at 03:17
UTC, and can also be run manually from the Actions tab.
