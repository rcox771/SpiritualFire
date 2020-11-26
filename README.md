<!-- omit in toc -->
# SpiritualFire 
This repo aims to provide some heavy calculation lifting for tt4x game [StarFire](https://en.wikipedia.org/wiki/Starfire_(board_wargame)).

- [Intent](#intent)
- [Getting Started](#getting-started)
  - [Install Locally](#install-locally)
    - [Prerequisites](#prerequisites)
  - [Install with Docker-Compose](#install-with-docker-compose)

# Intent
- This repo recognizes the wishes of the owner of the StarFire property in regards to their wishes about third party computer support. In order to comply with those wishes, I, the owner of this repo, will take these actions:
1) There will be no open source licensing for this repo
   - This repo does not give permission to modify, distribute, redistribute, or general use of the programs contained within.
   - Programs contained within that have licenses to freely distribute, modify, or use do no affect the license of this repo. Those programs themselves may be freely modified, distributed, or used without the code within this repository.
2) When the repo gets closer to completion, this repo will be pulled from the public eye.
   - The repo is currently open to the public to facilitate easier communication among project contributors in the early stages
   - Before any code that contains any calculation of, or references the rules of StarFire is contributed, the project will be pulled from being a public repository.
3) If the owner of the StarFire property or a member of the StarFire team wishes for the repository to be removed sooner, they may reach out to me here and I will be more than happy to remove it.

# Getting Started
## Install Locally
### Prerequisites
 - Python >= 3.9.0
 - pip

Then run:
```bash
pip install -r requirements.txt
python SpiritFire/manage.py runserver
```

## Install with Docker-Compose

Assuming you already have docker and docker-compose installed on your system:
```bash
docker-compose up
```
Then, simply go to http://localhost:8000 in your browser!

