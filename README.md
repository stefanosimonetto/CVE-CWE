The methodology implemented in this repo help to automate the process of mapping Common Vulnerabilities and Exposures (CVEs) to CWEs, leveraging a vector database containing embeddings of CWE descriptions. This approach involves embedding CVE descriptions and employing a nearest neighbor search to associate them with the appropriate CWE.
This framework can be extended to cover any text-to-weakness mapping, including but not limited to misconfigurations, Cyber Threat Intelligence (CTI) reports, security blogs, and other sources of security-related information.

### SETUP

1. Add OpenAI API key to the first part of the code'
2. Create python environment with requirements.txt
3. Launch docker 'docker compose up -d' in directory
4. Run the code in 'paper.ipynb'
