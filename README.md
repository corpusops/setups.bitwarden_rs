# docker based bitwarden_rs fullstack deployment using ansible

DISCLAIMER
============

**UNMAINTAINED/ABANDONED CODE / DO NOT USE**

Due to the new EU Cyber Resilience Act (as European Union), even if it was implied because there was no more activity, this repository is now explicitly declared unmaintained.

The content does not meet the new regulatory requirements and therefore cannot be deployed or distributed, especially in a European context.

This repository now remains online ONLY for public archiving, documentation and education purposes and we ask everyone to respect this.

As stated, the maintainers stopped development and therefore all support some time ago, and make this declaration on December 15, 2024.

We may also unpublish soon (as in the following monthes) any published ressources tied to the corpusops project (pypi, dockerhub, ansible-galaxy, the repositories).
So, please don't rely on it after March 15, 2025 and adapt whatever project which used this code.





See playbooks, set your variables and enjoy

ETA: WIP/not finished, may not be done

- https://github.com/bitwarden/jslib/issues/52: be sure to go to /admin and setup 2000000 to password iteration on advanced settings
- We do not use internal bitwarden signup block, we block signup at reverse proxy level.<br/>

  Goal is to allow some scripts to reach backend for automation purpose (creating users in advance).


