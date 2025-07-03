# Remote Repository Setup

## Current Remotes
backup  https://github.com/Adskij000Narost/techstart-api-backup.git (fetch)
backup  https://github.com/Adskij000Narost/techstart-api-backup.git (push)
origin  https://github.com/Adskij000Narost/techstart-api.git (fetch)
origin  https://github.com/Adskij000Narost/techstart-api-backup.git (push)
origin  https://github.com/Adskij000Narost/techstart-api.git (push)

## Tracking Branches
  develop 1d99a33 [origin/develop] New version
* main    be6b43e [origin/main] Merge branch 'main' of https://github.com/Adskij000Narost/techstart-api

## Fork Workflow Summary
- Original repository: https://github.com/Adskij000Narost/techstart-api
- Fork repository: https://github.com/Adskij000Narost/techstart-api-backup
- Upstream configuration: git push -u origin main  / git branch --set-upstream-to=origin/main main

## Backup Strategy
- Primary remote: origin
- Backup remote: backup
- Sync command:  git remote set-url --add --push origin https://github.com/Adskij000Narost/techstart-api.git && 
				 git remote set-url --add --push origin https://github.com/Adskij000Narost/techstart-api-backup.git &&
				 git push --all

## Lessons Learned
Имба, и не особо трудно, особенно если из задач убрать двусмысленные пункты