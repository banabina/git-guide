# Git - Commit Message Convention
깃 커밋 메세지 컨벤션입니다. 유다시티의 커밋 메세지 컨벤션을 참조한 자료입니다.

## Message Structure

```
type : subject

body

footer

```
## Commit Type

- feat : A new feature
- fix : A bug fix
- docs : changes to documentation
- style : Formatting, missing semi colons, etc; no code change
- refactor : Refactoring production code
- test : Adding tests, refactoring test; no production code chage
- chore : Updating build tasks, package manager configs, etc; no production code change
## Subject

- 제목은 50자를 넘기지 않고, 대문자로 시작하고 마침표를 붙이지 않는다.
- 명령어를사용한다.    

## Body

- 선택사항이
- 방법이 아닌 커멋의 내용과 이유를 설명하기 위해 작성한다.
- title과 body는 한 줄을 띄어주고 72자를 넘기지 않는다.
## footer

- 선택사항
- issue tracker id를 참조하는 데 사용한다.
## Example

```
feat: Summarize changes in around 50 characters or less

More detailed explanatory text, if necessary. Wrap it to about 72
characters or so. In some contexts, the first line is treated as the
subject of the commit and the rest of the text as the body. The
blank line separating the summary from the body is critical (unless
you omit the body entirely); various tools like `log`, `shortlog`
and `rebase` can get confused if you run the two together.

Explain the problem that this commit is solving. Focus on why you
are making this change as opposed to how (the code explains that).
Are there side effects or other unintuitive consequenses of this
change? Here's the place to explain them.

Further paragraphs come after blank lines.

 - Bullet points are okay, too

 - Typically a hyphen or asterisk is used for the bullet, preceded
   by a single space, with blank lines in between, but conventions
   vary here

If you use an issue tracker, put references to them at the bottom,
like this:

Resolves: #123
See also: #456, #789

```




Reference 
https://udacity.github.io/git-styleguide/
