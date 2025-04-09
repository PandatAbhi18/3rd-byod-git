# GitHub Collaboration Workflow Summary

## Overview
This project demonstrates GitHub collaboration using two accounts: Account A (repo owner) and Account B (contributor via fork and pull request).

---

## Steps Taken

### Account A:
1. Created a **public repository** with a descriptive README.
2. Added an initial commit (index.html).
3. Made the repository visible for others to fork.

### Account B:
1. Forked the repository from Account A.
2. Cloned the forked repository locally.
3. Created a new branch: `feature-update`.
4. Made changes:
   - Updated README.md with a contributor note.
   - Added a new file: `contributor.txt`.
5. Committed and pushed changes to the forked repository.
6. Opened a **pull request** to Account A's repository.

### Account A:
1. Reviewed the pull request.
2. Approved and **merged the pull request** into the main branch.

---

## Challenges & Resolutions

- **Branch confusion**: Initially committed to `main` instead of a feature branch. Fixed by creating `feature-update` and transferring changes.
- **Push errors**: Faced an authentication issue with Git CLI. Resolved by configuring Git with the correct GitHub username and using a Personal Access Token.

---

## Contributors
- Account A: Repository Owner
- Account B: Contributor via Fork

