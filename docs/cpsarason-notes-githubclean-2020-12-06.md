# Cleaned up festschrift repo

1. Tagged repo before cleaning/purging
2. rmoved loads of irrelevant stuff related to Jekyll
3. installed reveal.js via git pull
4. did a npm install in that directory

## Log of items 1-4, 2020-12-06 1729 PST
i(base) {17:04} code/festschrift:master ✗ ➭ git tag -a v0.5.2018 -m "State of Festschrift as of Whistler 2018 hack-a-thon"
(base) {17:05} code/festschrift:master ✗ ➭ git tag
v0.5.2018
(base) {17:05} code/festschrift:master ✗ ➭ git show v0.5.2018
(base) {17:05} code/festschrift:master ✗ ➭ git status
On branch master
Your branch is ahead of 'origin/master' by 6 commits.
  (use "git push" to publish your local commits)
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

	modified:   test.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	.DS_Store
	src/.DS_Store
	src/deck.js/

no changes added to commit (use "git add" and/or "git commit -a")
(base) {17:06} code/festschrift:master ✗ ➭ ls
Gemfile                          data                             lib
_config.yml                      demo.html                        src
_layouts                         docs                             test.html
assets                           ignite
cpsarason-notes-whistler-2018-03 index.md
(base) {17:06} code/festschrift:master ✗ ➭ ls ignite
deck.js-latest test644.html   test755.html
(base) {17:06} code/festschrift:master ✗ ➭ cd ignite
(base) {17:06} festschrift/ignite:master ✗ ➭ s
zsh: command not found: s
(base) {17:06} festschrift/ignite:master ✗ ➭ ls
deck.js-latest test644.html   test755.html
(base) {17:06} festschrift/ignite:master ✗ ➭ ls
deck.js-latest test644.html   test755.html
(base) {17:07} festschrift/ignite:master ✗ ➭ cd ..
(base) {17:07} code/festschrift:master ✗ ➭ ls
Gemfile                          data                             lib
_config.yml                      demo.html                        src
_layouts                         docs                             test.html
assets                           ignite
cpsarason-notes-whistler-2018-03 index.md
(base) {17:07} code/festschrift:master ✗ ➭ rm -rf ignite
(base) {17:07} code/festschrift:master ✗ ➭ git rm ignite
fatal: not removing 'ignite' recursively without -r
(base) {17:07} code/festschrift:master ✗ ➭ git rm -r ignite
rm 'ignite/deck.js-latest/.DS_Store'
rm 'ignite/deck.js-latest/CHANGELOG.md'
rm 'ignite/deck.js-latest/MIT-license.txt'
rm 'ignite/deck.js-latest/Makefile'
rm 'ignite/deck.js-latest/README.md'
rm 'ignite/deck.js-latest/Slide01.png'
rm 'ignite/deck.js-latest/Slide02.png'
rm 'ignite/deck.js-latest/Slide03.png'
rm 'ignite/deck.js-latest/Slide04.png'
rm 'ignite/deck.js-latest/Slide05.png'
rm 'ignite/deck.js-latest/Slide06 copy.png'
rm 'ignite/deck.js-latest/Slide06.png'
rm 'ignite/deck.js-latest/Slide07.png'
rm 'ignite/deck.js-latest/Slide08.png'
rm 'ignite/deck.js-latest/Slide09.png'
rm 'ignite/deck.js-latest/boilerplate.html'
rm 'ignite/deck.js-latest/core/deck.core.css'
rm 'ignite/deck.js-latest/core/deck.core.js'
rm 'ignite/deck.js-latest/core/deck.core.scss'
rm 'ignite/deck.js-latest/core/print.css'
rm 'ignite/deck.js-latest/core/print.scss'
rm 'ignite/deck.js-latest/extensions/automatic/VERSION'
rm 'ignite/deck.js-latest/extensions/automatic/deck.automatic.css'
rm 'ignite/deck.js-latest/extensions/automatic/deck.automatic.js'
rm 'ignite/deck.js-latest/extensions/goto/deck.goto.css'
rm 'ignite/deck.js-latest/extensions/goto/deck.goto.html'
rm 'ignite/deck.js-latest/extensions/goto/deck.goto.js'
rm 'ignite/deck.js-latest/extensions/goto/deck.goto.scss'
rm 'ignite/deck.js-latest/extensions/menu/deck.menu.css'
rm 'ignite/deck.js-latest/extensions/menu/deck.menu.js'
rm 'ignite/deck.js-latest/extensions/menu/deck.menu.scss'
rm 'ignite/deck.js-latest/extensions/navigation/deck.navigation.css'
rm 'ignite/deck.js-latest/extensions/navigation/deck.navigation.html'
rm 'ignite/deck.js-latest/extensions/navigation/deck.navigation.js'
rm 'ignite/deck.js-latest/extensions/navigation/deck.navigation.scss'
rm 'ignite/deck.js-latest/extensions/scale/deck.scale.css'
rm 'ignite/deck.js-latest/extensions/scale/deck.scale.js'
rm 'ignite/deck.js-latest/extensions/scale/deck.scale.scss'
rm 'ignite/deck.js-latest/extensions/status/deck.status.css'
rm 'ignite/deck.js-latest/extensions/status/deck.status.html'
rm 'ignite/deck.js-latest/extensions/status/deck.status.js'
rm 'ignite/deck.js-latest/extensions/status/deck.status.scss'
rm 'ignite/deck.js-latest/introduction/index.html'
rm 'ignite/deck.js-latest/jquery.min.js'
rm 'ignite/deck.js-latest/modernizr.custom.js'
rm 'ignite/deck.js-latest/scott.html'
rm 'ignite/deck.js-latest/scott.mp3'
rm 'ignite/deck.js-latest/scott.ogg'
rm 'ignite/deck.js-latest/test/fixtures/empty.html'
rm 'ignite/deck.js-latest/test/fixtures/nesteds.html'
rm 'ignite/deck.js-latest/test/fixtures/standard.html'
rm 'ignite/deck.js-latest/test/index.html'
rm 'ignite/deck.js-latest/test/lib/jasmine-html.js'
rm 'ignite/deck.js-latest/test/lib/jasmine-jquery.js'
rm 'ignite/deck.js-latest/test/lib/jasmine.css'
rm 'ignite/deck.js-latest/test/lib/jasmine.js'
rm 'ignite/deck.js-latest/test/settings.js'
rm 'ignite/deck.js-latest/test/spec.core.js'
rm 'ignite/deck.js-latest/test/spec.goto.js'
rm 'ignite/deck.js-latest/test/spec.menu.js'
rm 'ignite/deck.js-latest/test/spec.navigation.js'
rm 'ignite/deck.js-latest/test/spec.scale.js'
rm 'ignite/deck.js-latest/test/spec.status.js'
rm 'ignite/deck.js-latest/themes/style/_reset.scss'
rm 'ignite/deck.js-latest/themes/style/neon.css'
rm 'ignite/deck.js-latest/themes/style/neon.scss'
rm 'ignite/deck.js-latest/themes/style/swiss.css'
rm 'ignite/deck.js-latest/themes/style/swiss.scss'
rm 'ignite/deck.js-latest/themes/style/web-2.0.css'
rm 'ignite/deck.js-latest/themes/style/web-2.0.scss'
rm 'ignite/deck.js-latest/themes/transition/fade.css'
rm 'ignite/deck.js-latest/themes/transition/fade.scss'
rm 'ignite/deck.js-latest/themes/transition/horizontal-slide.css'
rm 'ignite/deck.js-latest/themes/transition/horizontal-slide.scss'
rm 'ignite/deck.js-latest/themes/transition/vertical-slide.css'
rm 'ignite/deck.js-latest/themes/transition/vertical-slide.scss'
rm 'ignite/test644.html'
rm 'ignite/test755.html'
(base) {17:07} code/festschrift:master ✗ ➭ git status
On branch master
Your branch is ahead of 'origin/master' by 6 commits.
  (use "git push" to publish your local commits)
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

	deleted:    ignite/deck.js-latest/.DS_Store
	deleted:    ignite/deck.js-latest/CHANGELOG.md
	deleted:    ignite/deck.js-latest/MIT-license.txt
	deleted:    ignite/deck.js-latest/Makefile
	deleted:    ignite/deck.js-latest/README.md
	deleted:    ignite/deck.js-latest/Slide01.png
	deleted:    ignite/deck.js-latest/Slide02.png
	deleted:    ignite/deck.js-latest/Slide03.png
	deleted:    ignite/deck.js-latest/Slide04.png
	deleted:    ignite/deck.js-latest/Slide05.png
	deleted:    ignite/deck.js-latest/Slide06 copy.png
	deleted:    ignite/deck.js-latest/Slide06.png
	deleted:    ignite/deck.js-latest/Slide07.png
	deleted:    ignite/deck.js-latest/Slide08.png
	deleted:    ignite/deck.js-latest/Slide09.png
	deleted:    ignite/deck.js-latest/boilerplate.html
	deleted:    ignite/deck.js-latest/core/deck.core.css
	deleted:    ignite/deck.js-latest/core/deck.core.js
	deleted:    ignite/deck.js-latest/core/deck.core.scss
	deleted:    ignite/deck.js-latest/core/print.css
	deleted:    ignite/deck.js-latest/core/print.scss
	deleted:    ignite/deck.js-latest/extensions/automatic/VERSION
	deleted:    ignite/deck.js-latest/extensions/automatic/deck.automatic.css
	deleted:    ignite/deck.js-latest/extensions/automatic/deck.automatic.js
	deleted:    ignite/deck.js-latest/extensions/goto/deck.goto.css
	deleted:    ignite/deck.js-latest/extensions/goto/deck.goto.html
	deleted:    ignite/deck.js-latest/extensions/goto/deck.goto.js
	deleted:    ignite/deck.js-latest/extensions/goto/deck.goto.scss
	deleted:    ignite/deck.js-latest/extensions/menu/deck.menu.css
	deleted:    ignite/deck.js-latest/extensions/menu/deck.menu.js
	deleted:    ignite/deck.js-latest/extensions/menu/deck.menu.scss
	deleted:    ignite/deck.js-latest/extensions/navigation/deck.navigation.css
	deleted:    ignite/deck.js-latest/extensions/navigation/deck.navigation.html
	deleted:    ignite/deck.js-latest/extensions/navigation/deck.navigation.js
	deleted:    ignite/deck.js-latest/extensions/navigation/deck.navigation.scss
	deleted:    ignite/deck.js-latest/extensions/scale/deck.scale.css
	deleted:    ignite/deck.js-latest/extensions/scale/deck.scale.js
	deleted:    ignite/deck.js-latest/extensions/scale/deck.scale.scss
	deleted:    ignite/deck.js-latest/extensions/status/deck.status.css
	deleted:    ignite/deck.js-latest/extensions/status/deck.status.html
	deleted:    ignite/deck.js-latest/extensions/status/deck.status.js
	deleted:    ignite/deck.js-latest/extensions/status/deck.status.scss
	deleted:    ignite/deck.js-latest/introduction/index.html
	deleted:    ignite/deck.js-latest/jquery.min.js
	deleted:    ignite/deck.js-latest/modernizr.custom.js
	deleted:    ignite/deck.js-latest/scott.html
	deleted:    ignite/deck.js-latest/scott.mp3
	deleted:    ignite/deck.js-latest/scott.ogg
	deleted:    ignite/deck.js-latest/test/fixtures/empty.html
	deleted:    ignite/deck.js-latest/test/fixtures/nesteds.html
	deleted:    ignite/deck.js-latest/test/fixtures/standard.html
	deleted:    ignite/deck.js-latest/test/index.html
	deleted:    ignite/deck.js-latest/test/lib/jasmine-html.js
	deleted:    ignite/deck.js-latest/test/lib/jasmine-jquery.js
	deleted:    ignite/deck.js-latest/test/lib/jasmine.css
	deleted:    ignite/deck.js-latest/test/lib/jasmine.js
	deleted:    ignite/deck.js-latest/test/settings.js
	deleted:    ignite/deck.js-latest/test/spec.core.js
	deleted:    ignite/deck.js-latest/test/spec.goto.js
	deleted:    ignite/deck.js-latest/test/spec.menu.js
	deleted:    ignite/deck.js-latest/test/spec.navigation.js
	deleted:    ignite/deck.js-latest/test/spec.scale.js
	deleted:    ignite/deck.js-latest/test/spec.status.js
	deleted:    ignite/deck.js-latest/themes/style/_reset.scss
	deleted:    ignite/deck.js-latest/themes/style/neon.css
	deleted:    ignite/deck.js-latest/themes/style/neon.scss
	deleted:    ignite/deck.js-latest/themes/style/swiss.css
	deleted:    ignite/deck.js-latest/themes/style/swiss.scss
	deleted:    ignite/deck.js-latest/themes/style/web-2.0.css
	deleted:    ignite/deck.js-latest/themes/style/web-2.0.scss
	deleted:    ignite/deck.js-latest/themes/transition/fade.css
	deleted:    ignite/deck.js-latest/themes/transition/fade.scss
	deleted:    ignite/deck.js-latest/themes/transition/horizontal-slide.css
	deleted:    ignite/deck.js-latest/themes/transition/horizontal-slide.scss
	deleted:    ignite/deck.js-latest/themes/transition/vertical-slide.css
	deleted:    ignite/deck.js-latest/themes/transition/vertical-slide.scss
	deleted:    ignite/test644.html
	deleted:    ignite/test755.html

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

	modified:   test.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	.DS_Store
	src/.DS_Store
	src/deck.js/

(base) {17:07} code/festschrift:master ✗ ➭ git commit
[master f11797d] Removed ignite folder w/ deck.js attempts
 Committer: Christian-home <cpsarason-home@loihi.hsd1.wa.comcast.net>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 78 files changed, 9567 deletions(-)
 delete mode 100644 ignite/deck.js-latest/.DS_Store
 delete mode 100755 ignite/deck.js-latest/CHANGELOG.md
 delete mode 100755 ignite/deck.js-latest/MIT-license.txt
 delete mode 100755 ignite/deck.js-latest/Makefile
 delete mode 100755 ignite/deck.js-latest/README.md
 delete mode 100644 ignite/deck.js-latest/Slide01.png
 delete mode 100644 ignite/deck.js-latest/Slide02.png
 delete mode 100644 ignite/deck.js-latest/Slide03.png
 delete mode 100644 ignite/deck.js-latest/Slide04.png
 delete mode 100644 ignite/deck.js-latest/Slide05.png
 delete mode 100644 ignite/deck.js-latest/Slide06 copy.png
 delete mode 100644 ignite/deck.js-latest/Slide06.png
 delete mode 100644 ignite/deck.js-latest/Slide07.png
 delete mode 100644 ignite/deck.js-latest/Slide08.png
 delete mode 100644 ignite/deck.js-latest/Slide09.png
 delete mode 100755 ignite/deck.js-latest/boilerplate.html
 delete mode 100755 ignite/deck.js-latest/core/deck.core.css
 delete mode 100755 ignite/deck.js-latest/core/deck.core.js
 delete mode 100755 ignite/deck.js-latest/core/deck.core.scss
 delete mode 100755 ignite/deck.js-latest/core/print.css
 delete mode 100755 ignite/deck.js-latest/core/print.scss
 delete mode 100755 ignite/deck.js-latest/extensions/automatic/VERSION
 delete mode 100755 ignite/deck.js-latest/extensions/automatic/deck.automatic.css
 delete mode 100755 ignite/deck.js-latest/extensions/automatic/deck.automatic.js
 delete mode 100755 ignite/deck.js-latest/extensions/goto/deck.goto.css
 delete mode 100755 ignite/deck.js-latest/extensions/goto/deck.goto.html
 delete mode 100755 ignite/deck.js-latest/extensions/goto/deck.goto.js
 delete mode 100755 ignite/deck.js-latest/extensions/goto/deck.goto.scss
 delete mode 100755 ignite/deck.js-latest/extensions/menu/deck.menu.css
 delete mode 100755 ignite/deck.js-latest/extensions/menu/deck.menu.js
 delete mode 100755 ignite/deck.js-latest/extensions/menu/deck.menu.scss
 delete mode 100755 ignite/deck.js-latest/extensions/navigation/deck.navigation.css
 delete mode 100755 ignite/deck.js-latest/extensions/navigation/deck.navigation.html
 delete mode 100755 ignite/deck.js-latest/extensions/navigation/deck.navigation.js
 delete mode 100755 ignite/deck.js-latest/extensions/navigation/deck.navigation.scss
 delete mode 100755 ignite/deck.js-latest/extensions/scale/deck.scale.css
 delete mode 100755 ignite/deck.js-latest/extensions/scale/deck.scale.js
 delete mode 100755 ignite/deck.js-latest/extensions/scale/deck.scale.scss
 delete mode 100755 ignite/deck.js-latest/extensions/status/deck.status.css
 delete mode 100755 ignite/deck.js-latest/extensions/status/deck.status.html
 delete mode 100755 ignite/deck.js-latest/extensions/status/deck.status.js
 delete mode 100755 ignite/deck.js-latest/extensions/status/deck.status.scss
 delete mode 100755 ignite/deck.js-latest/introduction/index.html
 delete mode 100755 ignite/deck.js-latest/jquery.min.js
 delete mode 100755 ignite/deck.js-latest/modernizr.custom.js
 delete mode 100755 ignite/deck.js-latest/scott.html
 delete mode 100644 ignite/deck.js-latest/scott.mp3
 delete mode 100644 ignite/deck.js-latest/scott.ogg
 delete mode 100755 ignite/deck.js-latest/test/fixtures/empty.html
 delete mode 100755 ignite/deck.js-latest/test/fixtures/nesteds.html
 delete mode 100755 ignite/deck.js-latest/test/fixtures/standard.html
 delete mode 100755 ignite/deck.js-latest/test/index.html
 delete mode 100755 ignite/deck.js-latest/test/lib/jasmine-html.js
 delete mode 100755 ignite/deck.js-latest/test/lib/jasmine-jquery.js
 delete mode 100755 ignite/deck.js-latest/test/lib/jasmine.css
 delete mode 100755 ignite/deck.js-latest/test/lib/jasmine.js
 delete mode 100755 ignite/deck.js-latest/test/settings.js
 delete mode 100755 ignite/deck.js-latest/test/spec.core.js
 delete mode 100755 ignite/deck.js-latest/test/spec.goto.js
 delete mode 100755 ignite/deck.js-latest/test/spec.menu.js
 delete mode 100755 ignite/deck.js-latest/test/spec.navigation.js
 delete mode 100755 ignite/deck.js-latest/test/spec.scale.js
 delete mode 100755 ignite/deck.js-latest/test/spec.status.js
 delete mode 100755 ignite/deck.js-latest/themes/style/_reset.scss
 delete mode 100755 ignite/deck.js-latest/themes/style/neon.css
 delete mode 100755 ignite/deck.js-latest/themes/style/neon.scss
 delete mode 100755 ignite/deck.js-latest/themes/style/swiss.css
 delete mode 100755 ignite/deck.js-latest/themes/style/swiss.scss
 delete mode 100755 ignite/deck.js-latest/themes/style/web-2.0.css
 delete mode 100755 ignite/deck.js-latest/themes/style/web-2.0.scss
 delete mode 100755 ignite/deck.js-latest/themes/transition/fade.css
 delete mode 100755 ignite/deck.js-latest/themes/transition/fade.scss
 delete mode 100755 ignite/deck.js-latest/themes/transition/horizontal-slide.css
 delete mode 100755 ignite/deck.js-latest/themes/transition/horizontal-slide.scss
 delete mode 100755 ignite/deck.js-latest/themes/transition/vertical-slide.css
 delete mode 100755 ignite/deck.js-latest/themes/transition/vertical-slide.scss
 delete mode 100644 ignite/test644.html
 delete mode 100755 ignite/test755.html
(base) {17:08} code/festschrift:master ✗ ➭ git status
On branch master
Your branch is ahead of 'origin/master' by 7 commits.
  (use "git push" to publish your local commits)
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

	modified:   test.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	.DS_Store
	src/.DS_Store
	src/deck.js/

no changes added to commit (use "git add" and/or "git commit -a")
(base) {17:08} code/festschrift:master ✗ ➭ ls
Gemfile                          cpsarason-notes-whistler-2018-03 index.md
_config.yml                      data                             lib
_layouts                         demo.html                        src
assets                           docs                             test.html
(base) {17:08} code/festschrift:master ✗ ➭ ls docs
index.md
(base) {17:08} code/festschrift:master ✗ ➭ more docs/index.md 
## here is a test
(base) {17:08} code/festschrift:master ✗ ➭ ls lib
reveal.js
(base) {17:08} code/festschrift:master ✗ ➭ rm _config.yml 
(base) {17:09} code/festschrift:master ✗ ➭ git status
On branch master
Your branch is ahead of 'origin/master' by 7 commits.
  (use "git push" to publish your local commits)
Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

	deleted:    _config.yml
	modified:   test.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	.DS_Store
	src/.DS_Store
	src/deck.js/

no changes added to commit (use "git add" and/or "git commit -a")
(base) {17:09} code/festschrift:master ✗ ➭   
(base) {17:09} code/festschrift:master ✗ ➭ ls
Gemfile                          data                             lib
_layouts                         demo.html                        src
assets                           docs                             test.html
cpsarason-notes-whistler-2018-03 index.md
(base) {17:09} code/festschrift:master ✗ ➭ git rm _config.yml
rm '_config.yml'
(base) {17:09} code/festschrift:master ✗ ➭ rm Gemfile 
(base) {17:09} code/festschrift:master ✗ ➭ git rm Gemfile
rm 'Gemfile'
(base) {17:09} code/festschrift:master ✗ ➭ ls
_layouts                         demo.html                        src
assets                           docs                             test.html
cpsarason-notes-whistler-2018-03 index.md
data                             lib
(base) {17:09} code/festschrift:master ✗ ➭ git status
On branch master
Your branch is ahead of 'origin/master' by 7 commits.
  (use "git push" to publish your local commits)
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

	deleted:    Gemfile
	deleted:    _config.yml

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

	modified:   test.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	.DS_Store
	src/.DS_Store
	src/deck.js/

(base) {17:09} code/festschrift:master ✗ ➭ ls _layouts 
default.html post.html
(base) {17:09} code/festschrift:master ✗ ➭ git rm _layouts/
fatal: not removing '_layouts/' recursively without -r
(base) {17:10} code/festschrift:master ✗ ➭ git rm -r _layouts/
rm '_layouts/default.html'
rm '_layouts/post.html'
(base) {17:10} code/festschrift:master ✗ ➭ ls
assets                           demo.html                        lib
cpsarason-notes-whistler-2018-03 docs                             src
data                             index.md                         test.html
(base) {17:10} code/festschrift:master ✗ ➭ ls assets 
whistler-festschrift.jpg
(base) {17:10} code/festschrift:master ✗ ➭ ls data
processed raw
(base) {17:10} code/festschrift:master ✗ ➭ rm index.md
(base) {17:10} code/festschrift:master ✗ ➭ ls
assets                           demo.html                        src
cpsarason-notes-whistler-2018-03 docs                             test.html
data                             lib
(base) {17:10} code/festschrift:master ✗ ➭ git status
On branch master
Your branch is ahead of 'origin/master' by 7 commits.
  (use "git push" to publish your local commits)
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

	deleted:    Gemfile
	deleted:    _config.yml
	deleted:    _layouts/default.html
	deleted:    _layouts/post.html

Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

	deleted:    index.md
	modified:   test.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	.DS_Store
	src/.DS_Store
	src/deck.js/

(base) {17:10} code/festschrift:master ✗ ➭ git rm index.md
rm 'index.md'
(base) {17:10} code/festschrift:master ✗ ➭ git status
On branch master
Your branch is ahead of 'origin/master' by 7 commits.
  (use "git push" to publish your local commits)
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

	deleted:    Gemfile
	deleted:    _config.yml
	deleted:    _layouts/default.html
	deleted:    _layouts/post.html
	deleted:    index.md

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

	modified:   test.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	.DS_Store
	src/.DS_Store
	src/deck.js/

(base) {17:10} code/festschrift:master ✗ ➭ ls
assets                           demo.html                        src
cpsarason-notes-whistler-2018-03 docs                             test.html
data                             lib
(base) {17:10} code/festschrift:master ✗ ➭ rm *.html
(base) {17:10} code/festschrift:master ✗ ➭ rm cpsarason-notes-whistler-2018-03 
(base) {17:10} code/festschrift:master ✗ ➭ git status
On branch master
Your branch is ahead of 'origin/master' by 7 commits.
  (use "git push" to publish your local commits)
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

	deleted:    Gemfile
	deleted:    _config.yml
	deleted:    _layouts/default.html
	deleted:    _layouts/post.html
	deleted:    index.md

Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

	deleted:    cpsarason-notes-whistler-2018-03
	deleted:    demo.html
	deleted:    test.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	.DS_Store
	src/.DS_Store
	src/deck.js/

(base) {17:11} code/festschrift:master ✗ ➭ git rm cpsarason-notes-whistler-2018-03
rm 'cpsarason-notes-whistler-2018-03'
(base) {17:11} code/festschrift:master ✗ ➭ git rm demo.html
rm 'demo.html'
(base) {17:11} code/festschrift:master ✗ ➭ git rm test.html
rm 'test.html'
(base) {17:11} code/festschrift:master ✗ ➭ git status
On branch master
Your branch is ahead of 'origin/master' by 7 commits.
  (use "git push" to publish your local commits)
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

	deleted:    Gemfile
	deleted:    _config.yml
	deleted:    _layouts/default.html
	deleted:    _layouts/post.html
	deleted:    cpsarason-notes-whistler-2018-03
	deleted:    demo.html
	deleted:    index.md
	deleted:    test.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	.DS_Store
	src/.DS_Store
	src/deck.js/

(base) {17:11} code/festschrift:master ✗ ➭ git commit
[master fd30cf9] Removed remnant bits of Jekyll config files not needed using Reveal node-js install
 Committer: Christian-home <cpsarason-home@loihi.hsd1.wa.comcast.net>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 8 files changed, 574 deletions(-)
 delete mode 100644 Gemfile
 delete mode 100644 _config.yml
 delete mode 100644 _layouts/default.html
 delete mode 100644 _layouts/post.html
 delete mode 100644 cpsarason-notes-whistler-2018-03
 delete mode 100644 demo.html
 delete mode 100644 index.md
 delete mode 100644 test.html
(base) {17:12} code/festschrift:master ✗ ➭ git status
On branch master
Your branch is ahead of 'origin/master' by 8 commits.
  (use "git push" to publish your local commits)
Untracked files:
  (use "git add <file>..." to include in what will be committed)

	.DS_Store
	src/.DS_Store
	src/deck.js/

nothing added to commit but untracked files present (use "git add" to track)
(base) {17:12} code/festschrift:master ✗ ➭ git push
Counting objects: 6, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 815 bytes | 0 bytes/s, done.
Total 6 (delta 3), reused 0 (delta 0)
remote: Resolving deltas: 100% (3/3), completed with 1 local object.
To git@github.com:cpsarason/festschrift.git
   dc9db7a..fd30cf9  master -> master
(base) {17:12} code/festschrift:master ✗ ➭ ls
assets data   docs   lib    src
(base) {17:12} code/festschrift:master ✗ ➭ ls src
deck.js js
(base) {17:12} code/festschrift:master ✗ ➭ cd src
(base) {17:12} festschrift/src:master ✗ ➭ ls
deck.js js
(base) {17:13} festschrift/src:master ✗ ➭ ls deck.js 
CHANGELOG.md        README.md           core                jquery.min.js       themes
MIT-license.txt     audio-all.ogg       extensions          modernizr.custom.js
Makefile            boilerplate.html    introduction        test
(base) {17:13} festschrift/src:master ✗ ➭ ls js 
reveal.js
(base) {17:13} festschrift/src:master ✗ ➭ ls
deck.js js
(base) {17:13} festschrift/src:master ✗ ➭ rm -rf *
zsh: sure you want to delete all 2 files in /Users/cpsarason-home/code/festschrift/src [yn]? y
(base) {17:13} festschrift/src:master ✗ ➭ ls
(base) {17:13} festschrift/src:master ✗ ➭ git status
On branch master
Your branch is up-to-date with 'origin/master'.
Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

	deleted:    js/reveal.js

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	../.DS_Store
	.DS_Store

no changes added to commit (use "git add" and/or "git commit -a")
(base) {17:13} festschrift/src:master ✗ ➭ ls
(base) {17:13} festschrift/src:master ✗ ➭ git rm js/reveal.js
rm 'src/js/reveal.js'
(base) {17:13} festschrift/src:master ✗ ➭ git status
On branch master
Your branch is up-to-date with 'origin/master'.
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

	deleted:    js/reveal.js

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	../.DS_Store
	./

(base) {17:13} festschrift/src:master ✗ ➭ git status
On branch master
Your branch is up-to-date with 'origin/master'.
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

	deleted:    js/reveal.js

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	../.DS_Store
	./

(base) {17:14} festschrift/src:master ✗ ➭ git commit 
[master 11505b6] removing deck.js and reveal remnants before installing Reveal circa 2020-12-06
 Committer: Christian-home <cpsarason-home@loihi.hsd1.wa.comcast.net>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 5241 deletions(-)
 delete mode 100644 src/js/reveal.js
(base) {17:14} festschrift/src:master ✗ ➭ git status
On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)
Untracked files:
  (use "git add <file>..." to include in what will be committed)

	../.DS_Store
	./

nothing added to commit but untracked files present (use "git add" to track)
(base) {17:15} festschrift/src:master ✗ ➭ git push 
Counting objects: 2, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 280 bytes | 0 bytes/s, done.
Total 2 (delta 1), reused 0 (delta 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To git@github.com:cpsarason/festschrift.git
   fd30cf9..11505b6  master -> master
(base) {17:15} festschrift/src:master ✗ ➭ ls
(base) {17:15} festschrift/src:master ✗ ➭ cd ..
(base) {17:15} code/festschrift:master ✗ ➭ ls
assets data   docs   lib    src
(base) {17:15} code/festschrift:master ✗ ➭ ls *
assets:
whistler-festschrift.jpg

data:
processed raw

docs:
index.md

lib:
reveal.js

src:
(base) {17:15} code/festschrift:master ✗ ➭ ls lib
reveal.js
(base) {17:15} code/festschrift:master ✗ ➭ ls lib/reveal.js 
CONTRIBUTING.md README.md       demo.html       lib             test
Gruntfile.js    bower.json      index.html      package.json
LICENSE         css             js              plugin
(base) {17:15} code/festschrift:master ✗ ➭ rm -rf lib/reveal.js
(base) {17:16} code/festschrift:master ✗ ➭ git rm lib/reveal.js
fatal: not removing 'lib/reveal.js' recursively without -r
(base) {17:16} code/festschrift:master ✗ ➭ git rm -r lib/reveal.js
rm 'lib/reveal.js/.gitignore'
rm 'lib/reveal.js/.travis.yml'
rm 'lib/reveal.js/CONTRIBUTING.md'
rm 'lib/reveal.js/Gruntfile.js'
rm 'lib/reveal.js/LICENSE'
rm 'lib/reveal.js/README.md'
rm 'lib/reveal.js/bower.json'
rm 'lib/reveal.js/css/print/paper.css'
rm 'lib/reveal.js/css/print/pdf.css'
rm 'lib/reveal.js/css/reveal.css'
rm 'lib/reveal.js/css/reveal.scss'
rm 'lib/reveal.js/css/theme/README.md'
rm 'lib/reveal.js/css/theme/beige.css'
rm 'lib/reveal.js/css/theme/black.css'
rm 'lib/reveal.js/css/theme/blood.css'
rm 'lib/reveal.js/css/theme/league.css'
rm 'lib/reveal.js/css/theme/moon.css'
rm 'lib/reveal.js/css/theme/night.css'
rm 'lib/reveal.js/css/theme/serif.css'
rm 'lib/reveal.js/css/theme/simple.css'
rm 'lib/reveal.js/css/theme/sky.css'
rm 'lib/reveal.js/css/theme/solarized.css'
rm 'lib/reveal.js/css/theme/source/beige.scss'
rm 'lib/reveal.js/css/theme/source/black.scss'
rm 'lib/reveal.js/css/theme/source/blood.scss'
rm 'lib/reveal.js/css/theme/source/league.scss'
rm 'lib/reveal.js/css/theme/source/moon.scss'
rm 'lib/reveal.js/css/theme/source/night.scss'
rm 'lib/reveal.js/css/theme/source/serif.scss'
rm 'lib/reveal.js/css/theme/source/simple.scss'
rm 'lib/reveal.js/css/theme/source/sky.scss'
rm 'lib/reveal.js/css/theme/source/solarized.scss'
rm 'lib/reveal.js/css/theme/source/white.scss'
rm 'lib/reveal.js/css/theme/template/mixins.scss'
rm 'lib/reveal.js/css/theme/template/settings.scss'
rm 'lib/reveal.js/css/theme/template/theme.scss'
rm 'lib/reveal.js/css/theme/white.css'
rm 'lib/reveal.js/demo.html'
rm 'lib/reveal.js/index.html'
rm 'lib/reveal.js/js/reveal.js'
rm 'lib/reveal.js/lib/css/zenburn.css'
rm 'lib/reveal.js/lib/font/league-gothic/LICENSE'
rm 'lib/reveal.js/lib/font/league-gothic/league-gothic.css'
rm 'lib/reveal.js/lib/font/league-gothic/league-gothic.eot'
rm 'lib/reveal.js/lib/font/league-gothic/league-gothic.ttf'
rm 'lib/reveal.js/lib/font/league-gothic/league-gothic.woff'
rm 'lib/reveal.js/lib/font/source-sans-pro/LICENSE'
rm 'lib/reveal.js/lib/font/source-sans-pro/source-sans-pro-italic.eot'
rm 'lib/reveal.js/lib/font/source-sans-pro/source-sans-pro-italic.ttf'
rm 'lib/reveal.js/lib/font/source-sans-pro/source-sans-pro-italic.woff'
rm 'lib/reveal.js/lib/font/source-sans-pro/source-sans-pro-regular.eot'
rm 'lib/reveal.js/lib/font/source-sans-pro/source-sans-pro-regular.ttf'
rm 'lib/reveal.js/lib/font/source-sans-pro/source-sans-pro-regular.woff'
rm 'lib/reveal.js/lib/font/source-sans-pro/source-sans-pro-semibold.eot'
rm 'lib/reveal.js/lib/font/source-sans-pro/source-sans-pro-semibold.ttf'
rm 'lib/reveal.js/lib/font/source-sans-pro/source-sans-pro-semibold.woff'
rm 'lib/reveal.js/lib/font/source-sans-pro/source-sans-pro-semibolditalic.eot'
rm 'lib/reveal.js/lib/font/source-sans-pro/source-sans-pro-semibolditalic.ttf'
rm 'lib/reveal.js/lib/font/source-sans-pro/source-sans-pro-semibolditalic.woff'
rm 'lib/reveal.js/lib/font/source-sans-pro/source-sans-pro.css'
rm 'lib/reveal.js/lib/js/classList.js'
rm 'lib/reveal.js/lib/js/head.min.js'
rm 'lib/reveal.js/lib/js/html5shiv.js'
rm 'lib/reveal.js/package.json'
rm 'lib/reveal.js/plugin/highlight/highlight.js'
rm 'lib/reveal.js/plugin/markdown/example.html'
rm 'lib/reveal.js/plugin/markdown/example.md'
rm 'lib/reveal.js/plugin/markdown/markdown.js'
rm 'lib/reveal.js/plugin/markdown/marked.js'
rm 'lib/reveal.js/plugin/math/math.js'
rm 'lib/reveal.js/plugin/multiplex/client.js'
rm 'lib/reveal.js/plugin/multiplex/index.js'
rm 'lib/reveal.js/plugin/multiplex/master.js'
rm 'lib/reveal.js/plugin/multiplex/package.json'
rm 'lib/reveal.js/plugin/notes-server/client.js'
rm 'lib/reveal.js/plugin/notes-server/index.js'
rm 'lib/reveal.js/plugin/notes-server/notes.html'
rm 'lib/reveal.js/plugin/notes/notes.html'
rm 'lib/reveal.js/plugin/notes/notes.js'
rm 'lib/reveal.js/plugin/print-pdf/print-pdf.js'
rm 'lib/reveal.js/plugin/search/search.js'
rm 'lib/reveal.js/plugin/zoom-js/zoom.js'
rm 'lib/reveal.js/test/examples/assets/image1.png'
rm 'lib/reveal.js/test/examples/assets/image2.png'
rm 'lib/reveal.js/test/examples/barebones.html'
rm 'lib/reveal.js/test/examples/embedded-media.html'
rm 'lib/reveal.js/test/examples/math.html'
rm 'lib/reveal.js/test/examples/slide-backgrounds.html'
rm 'lib/reveal.js/test/examples/slide-transitions.html'
rm 'lib/reveal.js/test/qunit-1.12.0.css'
rm 'lib/reveal.js/test/qunit-1.12.0.js'
rm 'lib/reveal.js/test/simple.md'
rm 'lib/reveal.js/test/test-markdown-element-attributes.html'
rm 'lib/reveal.js/test/test-markdown-element-attributes.js'
rm 'lib/reveal.js/test/test-markdown-external.html'
rm 'lib/reveal.js/test/test-markdown-external.js'
rm 'lib/reveal.js/test/test-markdown-options.html'
rm 'lib/reveal.js/test/test-markdown-options.js'
rm 'lib/reveal.js/test/test-markdown-slide-attributes.html'
rm 'lib/reveal.js/test/test-markdown-slide-attributes.js'
rm 'lib/reveal.js/test/test-markdown.html'
rm 'lib/reveal.js/test/test-markdown.js'
rm 'lib/reveal.js/test/test-pdf.html'
rm 'lib/reveal.js/test/test-pdf.js'
rm 'lib/reveal.js/test/test.html'
rm 'lib/reveal.js/test/test.js'
(base) {17:16} code/festschrift:master ✗ ➭ ls
assets data   docs   lib    src
(base) {17:16} code/festschrift:master ✗ ➭ git status
On branch master
Your branch is up-to-date with 'origin/master'.
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

	deleted:    lib/reveal.js/.gitignore
	deleted:    lib/reveal.js/.travis.yml
	deleted:    lib/reveal.js/CONTRIBUTING.md
	deleted:    lib/reveal.js/Gruntfile.js
	deleted:    lib/reveal.js/LICENSE
	deleted:    lib/reveal.js/README.md
	deleted:    lib/reveal.js/bower.json
	deleted:    lib/reveal.js/css/print/paper.css
	deleted:    lib/reveal.js/css/print/pdf.css
	deleted:    lib/reveal.js/css/reveal.css
	deleted:    lib/reveal.js/css/reveal.scss
	deleted:    lib/reveal.js/css/theme/README.md
	deleted:    lib/reveal.js/css/theme/beige.css
	deleted:    lib/reveal.js/css/theme/black.css
	deleted:    lib/reveal.js/css/theme/blood.css
	deleted:    lib/reveal.js/css/theme/league.css
	deleted:    lib/reveal.js/css/theme/moon.css
	deleted:    lib/reveal.js/css/theme/night.css
	deleted:    lib/reveal.js/css/theme/serif.css
	deleted:    lib/reveal.js/css/theme/simple.css
	deleted:    lib/reveal.js/css/theme/sky.css
	deleted:    lib/reveal.js/css/theme/solarized.css
	deleted:    lib/reveal.js/css/theme/source/beige.scss
	deleted:    lib/reveal.js/css/theme/source/black.scss
	deleted:    lib/reveal.js/css/theme/source/blood.scss
	deleted:    lib/reveal.js/css/theme/source/league.scss
	deleted:    lib/reveal.js/css/theme/source/moon.scss
	deleted:    lib/reveal.js/css/theme/source/night.scss
	deleted:    lib/reveal.js/css/theme/source/serif.scss
	deleted:    lib/reveal.js/css/theme/source/simple.scss
	deleted:    lib/reveal.js/css/theme/source/sky.scss
	deleted:    lib/reveal.js/css/theme/source/solarized.scss
	deleted:    lib/reveal.js/css/theme/source/white.scss
	deleted:    lib/reveal.js/css/theme/template/mixins.scss
	deleted:    lib/reveal.js/css/theme/template/settings.scss
	deleted:    lib/reveal.js/css/theme/template/theme.scss
	deleted:    lib/reveal.js/css/theme/white.css
	deleted:    lib/reveal.js/demo.html
	deleted:    lib/reveal.js/index.html
	deleted:    lib/reveal.js/js/reveal.js
	deleted:    lib/reveal.js/lib/css/zenburn.css
	deleted:    lib/reveal.js/lib/font/league-gothic/LICENSE
	deleted:    lib/reveal.js/lib/font/league-gothic/league-gothic.css
	deleted:    lib/reveal.js/lib/font/league-gothic/league-gothic.eot
	deleted:    lib/reveal.js/lib/font/league-gothic/league-gothic.ttf
	deleted:    lib/reveal.js/lib/font/league-gothic/league-gothic.woff
	deleted:    lib/reveal.js/lib/font/source-sans-pro/LICENSE
	deleted:    lib/reveal.js/lib/font/source-sans-pro/source-sans-pro-italic.eot
	deleted:    lib/reveal.js/lib/font/source-sans-pro/source-sans-pro-italic.ttf
	deleted:    lib/reveal.js/lib/font/source-sans-pro/source-sans-pro-italic.woff
	deleted:    lib/reveal.js/lib/font/source-sans-pro/source-sans-pro-regular.eot
	deleted:    lib/reveal.js/lib/font/source-sans-pro/source-sans-pro-regular.ttf
	deleted:    lib/reveal.js/lib/font/source-sans-pro/source-sans-pro-regular.woff
	deleted:    lib/reveal.js/lib/font/source-sans-pro/source-sans-pro-semibold.eot
	deleted:    lib/reveal.js/lib/font/source-sans-pro/source-sans-pro-semibold.ttf
	deleted:    lib/reveal.js/lib/font/source-sans-pro/source-sans-pro-semibold.woff
	deleted:    lib/reveal.js/lib/font/source-sans-pro/source-sans-pro-semibolditalic.eot
	deleted:    lib/reveal.js/lib/font/source-sans-pro/source-sans-pro-semibolditalic.ttf
	deleted:    lib/reveal.js/lib/font/source-sans-pro/source-sans-pro-semibolditalic.woff
	deleted:    lib/reveal.js/lib/font/source-sans-pro/source-sans-pro.css
	deleted:    lib/reveal.js/lib/js/classList.js
	deleted:    lib/reveal.js/lib/js/head.min.js
	deleted:    lib/reveal.js/lib/js/html5shiv.js
	deleted:    lib/reveal.js/package.json
	deleted:    lib/reveal.js/plugin/highlight/highlight.js
	deleted:    lib/reveal.js/plugin/markdown/example.html
	deleted:    lib/reveal.js/plugin/markdown/example.md
	deleted:    lib/reveal.js/plugin/markdown/markdown.js
	deleted:    lib/reveal.js/plugin/markdown/marked.js
	deleted:    lib/reveal.js/plugin/math/math.js
	deleted:    lib/reveal.js/plugin/multiplex/client.js
	deleted:    lib/reveal.js/plugin/multiplex/index.js
	deleted:    lib/reveal.js/plugin/multiplex/master.js
	deleted:    lib/reveal.js/plugin/multiplex/package.json
	deleted:    lib/reveal.js/plugin/notes-server/client.js
	deleted:    lib/reveal.js/plugin/notes-server/index.js
	deleted:    lib/reveal.js/plugin/notes-server/notes.html
	deleted:    lib/reveal.js/plugin/notes/notes.html
	deleted:    lib/reveal.js/plugin/notes/notes.js
	deleted:    lib/reveal.js/plugin/print-pdf/print-pdf.js
	deleted:    lib/reveal.js/plugin/search/search.js
	deleted:    lib/reveal.js/plugin/zoom-js/zoom.js
	deleted:    lib/reveal.js/test/examples/assets/image1.png
	deleted:    lib/reveal.js/test/examples/assets/image2.png
	deleted:    lib/reveal.js/test/examples/barebones.html
	deleted:    lib/reveal.js/test/examples/embedded-media.html
	deleted:    lib/reveal.js/test/examples/math.html
	deleted:    lib/reveal.js/test/examples/slide-backgrounds.html
	deleted:    lib/reveal.js/test/examples/slide-transitions.html
	deleted:    lib/reveal.js/test/qunit-1.12.0.css
	deleted:    lib/reveal.js/test/qunit-1.12.0.js
	deleted:    lib/reveal.js/test/simple.md
	deleted:    lib/reveal.js/test/test-markdown-element-attributes.html
	deleted:    lib/reveal.js/test/test-markdown-element-attributes.js
	deleted:    lib/reveal.js/test/test-markdown-external.html
	deleted:    lib/reveal.js/test/test-markdown-external.js
	deleted:    lib/reveal.js/test/test-markdown-options.html
	deleted:    lib/reveal.js/test/test-markdown-options.js
	deleted:    lib/reveal.js/test/test-markdown-slide-attributes.html
	deleted:    lib/reveal.js/test/test-markdown-slide-attributes.js
	deleted:    lib/reveal.js/test/test-markdown.html
	deleted:    lib/reveal.js/test/test-markdown.js
	deleted:    lib/reveal.js/test/test-pdf.html
	deleted:    lib/reveal.js/test/test-pdf.js
	deleted:    lib/reveal.js/test/test.html
	deleted:    lib/reveal.js/test/test.js

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	.DS_Store
	src/

(base) {17:16} code/festschrift:master ✗ ➭ git commit
[master f7f69c0] removal of Reveal code in prep for installing Reveal circa 2020-12-06
 Committer: Christian-home <cpsarason-home@loihi.hsd1.wa.comcast.net>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 106 files changed, 22368 deletions(-)
 delete mode 100644 lib/reveal.js/.gitignore
 delete mode 100644 lib/reveal.js/.travis.yml
 delete mode 100644 lib/reveal.js/CONTRIBUTING.md
 delete mode 100644 lib/reveal.js/Gruntfile.js
 delete mode 100644 lib/reveal.js/LICENSE
 delete mode 100644 lib/reveal.js/README.md
 delete mode 100644 lib/reveal.js/bower.json
 delete mode 100644 lib/reveal.js/css/print/paper.css
 delete mode 100644 lib/reveal.js/css/print/pdf.css
 delete mode 100644 lib/reveal.js/css/reveal.css
 delete mode 100644 lib/reveal.js/css/reveal.scss
 delete mode 100644 lib/reveal.js/css/theme/README.md
 delete mode 100644 lib/reveal.js/css/theme/beige.css
 delete mode 100644 lib/reveal.js/css/theme/black.css
 delete mode 100644 lib/reveal.js/css/theme/blood.css
 delete mode 100644 lib/reveal.js/css/theme/league.css
 delete mode 100644 lib/reveal.js/css/theme/moon.css
 delete mode 100644 lib/reveal.js/css/theme/night.css
 delete mode 100644 lib/reveal.js/css/theme/serif.css
 delete mode 100644 lib/reveal.js/css/theme/simple.css
 delete mode 100644 lib/reveal.js/css/theme/sky.css
 delete mode 100644 lib/reveal.js/css/theme/solarized.css
 delete mode 100644 lib/reveal.js/css/theme/source/beige.scss
 delete mode 100644 lib/reveal.js/css/theme/source/black.scss
 delete mode 100644 lib/reveal.js/css/theme/source/blood.scss
 delete mode 100644 lib/reveal.js/css/theme/source/league.scss
 delete mode 100644 lib/reveal.js/css/theme/source/moon.scss
 delete mode 100644 lib/reveal.js/css/theme/source/night.scss
 delete mode 100644 lib/reveal.js/css/theme/source/serif.scss
 delete mode 100644 lib/reveal.js/css/theme/source/simple.scss
 delete mode 100644 lib/reveal.js/css/theme/source/sky.scss
 delete mode 100644 lib/reveal.js/css/theme/source/solarized.scss
 delete mode 100644 lib/reveal.js/css/theme/source/white.scss
 delete mode 100644 lib/reveal.js/css/theme/template/mixins.scss
 delete mode 100644 lib/reveal.js/css/theme/template/settings.scss
 delete mode 100644 lib/reveal.js/css/theme/template/theme.scss
 delete mode 100644 lib/reveal.js/css/theme/white.css
 delete mode 100644 lib/reveal.js/demo.html
 delete mode 100644 lib/reveal.js/index.html
 delete mode 100644 lib/reveal.js/js/reveal.js
 delete mode 100644 lib/reveal.js/lib/css/zenburn.css
 delete mode 100644 lib/reveal.js/lib/font/league-gothic/LICENSE
 delete mode 100644 lib/reveal.js/lib/font/league-gothic/league-gothic.css
 delete mode 100755 lib/reveal.js/lib/font/league-gothic/league-gothic.eot
 delete mode 100755 lib/reveal.js/lib/font/league-gothic/league-gothic.ttf
 delete mode 100755 lib/reveal.js/lib/font/league-gothic/league-gothic.woff
 delete mode 100644 lib/reveal.js/lib/font/source-sans-pro/LICENSE
 delete mode 100755 lib/reveal.js/lib/font/source-sans-pro/source-sans-pro-italic.eot
 delete mode 100755 lib/reveal.js/lib/font/source-sans-pro/source-sans-pro-italic.ttf
 delete mode 100755 lib/reveal.js/lib/font/source-sans-pro/source-sans-pro-italic.woff
 delete mode 100755 lib/reveal.js/lib/font/source-sans-pro/source-sans-pro-regular.eot
 delete mode 100755 lib/reveal.js/lib/font/source-sans-pro/source-sans-pro-regular.ttf
 delete mode 100755 lib/reveal.js/lib/font/source-sans-pro/source-sans-pro-regular.woff
 delete mode 100755 lib/reveal.js/lib/font/source-sans-pro/source-sans-pro-semibold.eot
 delete mode 100755 lib/reveal.js/lib/font/source-sans-pro/source-sans-pro-semibold.ttf
 delete mode 100755 lib/reveal.js/lib/font/source-sans-pro/source-sans-pro-semibold.woff
 delete mode 100755 lib/reveal.js/lib/font/source-sans-pro/source-sans-pro-semibolditalic.eot
 delete mode 100755 lib/reveal.js/lib/font/source-sans-pro/source-sans-pro-semibolditalic.ttf
 delete mode 100755 lib/reveal.js/lib/font/source-sans-pro/source-sans-pro-semibolditalic.woff
 delete mode 100644 lib/reveal.js/lib/font/source-sans-pro/source-sans-pro.css
 delete mode 100644 lib/reveal.js/lib/js/classList.js
 delete mode 100644 lib/reveal.js/lib/js/head.min.js
 delete mode 100644 lib/reveal.js/lib/js/html5shiv.js
 delete mode 100644 lib/reveal.js/package.json
 delete mode 100644 lib/reveal.js/plugin/highlight/highlight.js
 delete mode 100644 lib/reveal.js/plugin/markdown/example.html
 delete mode 100644 lib/reveal.js/plugin/markdown/example.md
 delete mode 100755 lib/reveal.js/plugin/markdown/markdown.js
 delete mode 100644 lib/reveal.js/plugin/markdown/marked.js
 delete mode 100755 lib/reveal.js/plugin/math/math.js
 delete mode 100644 lib/reveal.js/plugin/multiplex/client.js
 delete mode 100644 lib/reveal.js/plugin/multiplex/index.js
 delete mode 100644 lib/reveal.js/plugin/multiplex/master.js
 delete mode 100644 lib/reveal.js/plugin/multiplex/package.json
 delete mode 100644 lib/reveal.js/plugin/notes-server/client.js
 delete mode 100644 lib/reveal.js/plugin/notes-server/index.js
 delete mode 100644 lib/reveal.js/plugin/notes-server/notes.html
 delete mode 100644 lib/reveal.js/plugin/notes/notes.html
 delete mode 100644 lib/reveal.js/plugin/notes/notes.js
 delete mode 100644 lib/reveal.js/plugin/print-pdf/print-pdf.js
 delete mode 100644 lib/reveal.js/plugin/search/search.js
 delete mode 100644 lib/reveal.js/plugin/zoom-js/zoom.js
 delete mode 100644 lib/reveal.js/test/examples/assets/image1.png
 delete mode 100644 lib/reveal.js/test/examples/assets/image2.png
 delete mode 100644 lib/reveal.js/test/examples/barebones.html
 delete mode 100644 lib/reveal.js/test/examples/embedded-media.html
 delete mode 100644 lib/reveal.js/test/examples/math.html
 delete mode 100644 lib/reveal.js/test/examples/slide-backgrounds.html
 delete mode 100644 lib/reveal.js/test/examples/slide-transitions.html
 delete mode 100644 lib/reveal.js/test/qunit-1.12.0.css
 delete mode 100644 lib/reveal.js/test/qunit-1.12.0.js
 delete mode 100644 lib/reveal.js/test/simple.md
 delete mode 100644 lib/reveal.js/test/test-markdown-element-attributes.html
 delete mode 100644 lib/reveal.js/test/test-markdown-element-attributes.js
 delete mode 100644 lib/reveal.js/test/test-markdown-external.html
 delete mode 100644 lib/reveal.js/test/test-markdown-external.js
 delete mode 100644 lib/reveal.js/test/test-markdown-options.html
 delete mode 100644 lib/reveal.js/test/test-markdown-options.js
 delete mode 100644 lib/reveal.js/test/test-markdown-slide-attributes.html
 delete mode 100644 lib/reveal.js/test/test-markdown-slide-attributes.js
 delete mode 100644 lib/reveal.js/test/test-markdown.html
 delete mode 100644 lib/reveal.js/test/test-markdown.js
 delete mode 100644 lib/reveal.js/test/test-pdf.html
 delete mode 100644 lib/reveal.js/test/test-pdf.js
 delete mode 100644 lib/reveal.js/test/test.html
 delete mode 100644 lib/reveal.js/test/test.js
(base) {17:17} code/festschrift:master ✗ ➭ ls
assets data   docs   lib    src
(base) {17:17} code/festschrift:master ✗ ➭ git push
Counting objects: 2, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 275 bytes | 0 bytes/s, done.
Total 2 (delta 1), reused 0 (delta 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To git@github.com:cpsarason/festschrift.git
   11505b6..f7f69c0  master -> master
(base) {17:17} code/festschrift:master ✗ ➭ ls
assets data   docs   lib    src
(base) {17:17} code/festschrift:master ✗ ➭ ls
assets data   docs   lib    src
(base) {17:18} code/festschrift:master ✗ ➭ npm install reveal.js
npm WARN saveError ENOENT: no such file or directory, open '/Users/cpsarason-home/code/festschrift/package.json'
npm notice created a lockfile as package-lock.json. You should commit this file.
npm WARN enoent ENOENT: no such file or directory, open '/Users/cpsarason-home/code/festschrift/package.json'
npm WARN festschrift No description
npm WARN festschrift No repository field.
npm WARN festschrift No README data
npm WARN festschrift No license field.

+ reveal.js@4.1.0
added 1 package from 1 contributor and audited 1 package in 1.122s
found 0 vulnerabilities

(base) {17:19} code/festschrift:master ✗ ➭ git clone https://github.com/hakimel/reveal.js.git
Cloning into 'reveal.js'...
remote: Enumerating objects: 14223, done.
remote: Total 14223 (delta 0), reused 0 (delta 0), pack-reused 14223
Receiving objects: 100% (14223/14223), 13.68 MiB | 5.01 MiB/s, done.
Resolving deltas: 100% (8125/8125), done.
Checking connectivity... done.
(base) {17:21} code/festschrift:master ✗ ➭ ls
assets            docs              node_modules      reveal.js
data              lib               package-lock.json src
(base) {17:21} code/festschrift:master ✗ ➭ cd reveal.js 
(base) {17:21} festschrift/reveal.js:master ✓ ➭ ls
CONTRIBUTING.md   css               examples          js                plugin
LICENSE           demo.html         gulpfile.js       package-lock.json test
README.md         dist              index.html        package.json
(base) {17:21} festschrift/reveal.js:master ✓ ➭ npm install
git clone https://github.com/hakimel/reveal.js.git⸨            ░░░░░░⸩ ⠇ refresh-package-json:type-fe
> fsevents@1.2.12 install /Users/cpsarason-home/code/festschrift/reveal.js/node_modules/fsevents
> node-gyp rebuild

  SOLINK_MODULE(target) Release/.node
  CXX(target) Release/obj.target/fse/fsevents.o
  SOLINK_MODULE(target) Release/fse.node

> node-sass@4.14.1 install /Users/cpsarason-home/code/festschrift/reveal.js/node_modules/node-sass
> node scripts/install.js

Cached binary found at /Users/cpsarason-home/.npm/node-sass/4.14.1/darwin-x64-67_binding.node

> puppeteer@2.1.1 install /Users/cpsarason-home/code/festschrift/reveal.js/node_modules/puppeteer
> node install.js

Downloading Chromium r722234 - 116.4 Mb [====================] 100% 0.0s 
Chromium downloaded to /Users/cpsarason-home/code/festschrift/reveal.js/node_modules/puppeteer/.local-chromium/mac-722234

> node-sass@4.14.1 postinstall /Users/cpsarason-home/code/festschrift/reveal.js/node_modules/node-sass
> node scripts/build.js

Binary found at /Users/cpsarason-home/code/festschrift/reveal.js/node_modules/node-sass/vendor/darwin-x64-67/binding.node
Testing binary
Binary is fine

> core-js@3.6.5 postinstall /Users/cpsarason-home/code/festschrift/reveal.js/node_modules/core-js
> node -e "try{require('./postinstall')}catch(e){}"

Thank you for using core-js ( https://github.com/zloirock/core-js ) for polyfilling JavaScript standard library!

The project needs your help! Please consider supporting of core-js on Open Collective or Patreon: 
> https://opencollective.com/core-js 
> https://www.patreon.com/zloirock 

Also, the author of core-js ( https://github.com/zloirock ) is looking for a good job -)

added 926 packages from 765 contributors and audited 927 packages in 65.019s

20 packages are looking for funding
  run `npm fund` for details

found 1 low severity vulnerability
  run `npm audit fix` to fix them, or `npm audit` for details
(base) {17:23} festschrift/reveal.js:master ✗ ➭                                                   



