# docker based bitwarden_rs fullstack deployment using ansible
See playbooks, set your variables and enjoy

ETA: WIP/not finished, may not be done

- https://github.com/bitwarden/jslib/issues/52: be sure to go to /admin and setup 2000000 to password iteration on advanced settings
- We do not use internal bitwarden signup block, we block signup at reverse proxy level.<br/>

  Goal is to allow some scripts to reach backend for automation purpose (creating users in advance).


