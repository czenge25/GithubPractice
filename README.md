# GithubPractice

1. It sets Origin to the remote repository
2. The command allows you to set the default remote branch for your current local branch. Remote tracking means that your local branch is aware of its counterpart on the remote repository.
3. It fetches the changes from the origin branch called master. Then, it merges these changes into the current local branch
4. No, git is designed to preserve commits
5. The command is a merge by default
6. Yes, the local main branch is also updated and in line with the remote main
7. No, the local copy was not deleted

Person A: 
*   commit 38d1c2b1b79ea6867443b8fd4f154f439b201fe7 (HEAD -> main, origin/main, origin/HEAD)
|\  Merge: 920a5bb 1f9cf51
| | Author: czenge25 <czenge25@kentdenver.org>
| | Date:   Tue Oct 3 11:06:01 2023 -0600
| | 
| |     no changes
| | 
| * commit 1f9cf518e843b00e03fd6bc2072d6ae1766b3583
| | Author: John Karmozyn <hughkarmozyn@icloud.com>
| | Date:   Tue Oct 3 10:55:46 2023 -0600
| | 
| |     new commit hooray
| | 
* | commit 920a5bb0144cd826c40f27035cc1d02815dc0ff1
|/  Author: czenge25 <czenge25@kentdenver.org>
|   Date:   Tue Oct 3 11:03:22 2023 -0600
|   
|       deleted random text files
|   
| * commit d4c40bdc10fc27a87b6176d77b48f8a57409f9ca (origin/Feature2)
|/  Author: czenge25 <czenge25@kentdenver.org>
|   Date:   Tue Oct 3 10:50:07 2023 -0600
|   
|       made feature 2 inside of Text.rtf
| 
* commit a5643fed5062c5646baaec1a9dfd1ee3239ca7db
| Author: czenge25 <117951387+czenge25@users.noreply.github.com>
| Date:   Tue Oct 3 10:44:58 2023 -0600
| 
|     Update README.md
| 
* commit 7bc8c0e7de0dd12e7afec45660a7408760359f51
| Author: John Karmozyn <hughkarmozyn@icloud.com>
| Date:   Mon Oct 2 08:55:57 2023 -0600
| 
|     trying to return to main branch
| 
* commit 832d2aea36b8059553a30066a57eb1e545d46c65
| Author: John Karmozyn <hughkarmozyn@icloud.com>
| Date:   Mon Oct 2 08:57:11 2023 -0600
| 
|     trying to return to main - merge conflict resolved
| 
* commit 53b6db5b024a5e46d711e911dd835390f3069f4a
| Author: czenge25 <117951387+czenge25@users.noreply.github.com>
| Date:   Mon Oct 2 08:39:59 2023 -0600
| 
|     Update README.md
| 
* commit e23597f03d20978d6ab1b155a1cb102bcf9b6227
| Author: czenge25 <czenge25@kentdenver.org>
| Date:   Wed Sep 27 14:29:47 2023 -0600
| 
|     Edited text file
| 
* commit e55eea049e2f53d6fc2a42d2c3af4c96fc760e34
| Author: czenge25 <117951387+czenge25@users.noreply.github.com>
| Date:   Wed Sep 27 14:02:25 2023 -0600
| 
|     Answered questions 1 and 2 in README
| 
* commit c946bb1308b4ac3ec2d06bdd39bec7a8156c5b16

Person B: 
*   commit 38d1c2b1b79ea6867443b8fd4f154f439b201fe7 (HEAD -> main, origin/main, origin/HEAD)
|\  Merge: 920a5bb 1f9cf51
| | Author: czenge25 <czenge25@kentdenver.org>
| | Date:   Tue Oct 3 11:06:01 2023 -0600
| | 
| |     no changes
| | 
| * commit 1f9cf518e843b00e03fd6bc2072d6ae1766b3583
| | Author: John Karmozyn <hughkarmozyn@icloud.com>
| | Date:   Tue Oct 3 10:55:46 2023 -0600
| | 
| |     new commit hooray
| | 
* | commit 920a5bb0144cd826c40f27035cc1d02815dc0ff1
|/  Author: czenge25 <czenge25@kentdenver.org>
|   Date:   Tue Oct 3 11:03:22 2023 -0600
|   
|       deleted random text files
|   
| * commit d4c40bdc10fc27a87b6176d77b48f8a57409f9ca (origin/Feature2)
|/  Author: czenge25 <czenge25@kentdenver.org>
|   Date:   Tue Oct 3 10:50:07 2023 -0600
|   
|       made feature 2 inside of Text.rtf
| 
* commit a5643fed5062c5646baaec1a9dfd1ee3239ca7db
| Author: czenge25 <117951387+czenge25@users.noreply.github.com>
| Date:   Tue Oct 3 10:44:58 2023 -0600
| 
|     Update README.md
| 
* commit 7bc8c0e7de0dd12e7afec45660a7408760359f51
| Author: John Karmozyn <hughkarmozyn@icloud.com>
| Date:   Mon Oct 2 08:55:57 2023 -0600
| 
|     trying to return to main branch
| 
* commit 832d2aea36b8059553a30066a57eb1e545d46c65
| Author: John Karmozyn <hughkarmozyn@icloud.com>
| Date:   Mon Oct 2 08:57:11 2023 -0600
| 
|     trying to return to main - merge conflict resolved
| 
* commit 53b6db5b024a5e46d711e911dd835390f3069f4a
| Author: czenge25 <117951387+czenge25@users.noreply.github.com>
| Date:   Mon Oct 2 08:39:59 2023 -0600
| 
|     Update README.md
|   
| * commit b0dc91b259ae4de4dbf37dabb90631d0c066a11e (origin/side)
|/  Author: John Karmozyn <hughkarmozyn@icloud.com>
|   Date:   Mon Oct 2 08:28:52 2023 -0600
|   
|       DocTwo
|   
| * commit 66cf054f100a66f3dfac5c55df7bd6c3d9530e2a (refs/stash)
|/| Merge: e23597f 136c48f
| | Author: John Karmozyn <hughkarmozyn@icloud.com>
| | Date:   Mon Oct 2 08:25:17 2023 -0600
| | 
| |     WIP on (no branch): e23597f Edited text file
| | 
| * commit 136c48fb1c50a3fcd525161a36c47bc8955c0650
|/  Author: John Karmozyn <hughkarmozyn@icloud.com>
|   Date:   Mon Oct 2 08:25:17 2023 -0600
|   
:

