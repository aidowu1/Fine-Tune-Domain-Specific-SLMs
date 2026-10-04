### Domain-specific Small Language Models
- Data preparation for BERT fine tuning
- reference: [Domain-Specific-Small-Language-Models by Guglielimo Lozzia](https://github.com/virtualramblas/Domain-Specific-Small-Language-Models/tree/main) 

#### Python virtual environment setup:
- conda create -n slm_env python=3.12 -y
- conda activate slm_env
- pip install -r requirements.txt

If Conda reports `CondaSSLError` while connecting to `repo.anaconda.com` on Windows, use the Windows certificate store (Conda 23.9 or newer) and retry:
- conda config --set ssl_verify truststore

For older Conda versions, update Conda and its CA certificates from Anaconda Prompt, or ask your network administrator for the approved proxy/root CA certificate and configure Conda to use that certificate. Do not disable SSL verification (`ssl_verify: false`), as this makes package downloads vulnerable to interception.
