# Documentation Rodeo


- Doc should live as close to the code it documents as possible. API doc should live IN the code it documents.

- Doc builds should be part of the regular product build.

- Doc is an artifact of the build just as CSS, JavaScript, images, etc. are.

- Do not implement any process that requires a human turning the crank to generate doc.

- Doc should be ready to build at any time.

- Nothing is to pushed to the production branch unless it’s ready for customer eyes.

- Doc should live in the same source code control system that code lives in.

- Changes to doc should be made using the same techniques and mechanisms used to make changes in code: branches, pull requests, merges.

- Doc should be editable in a plain text editor. Special purpose editors create a choke point.

- Anyone in the organization should be able to make edits to the doc on a branch.

- No one edits the production branch directly. Not even you.

- The markup language used to create documentation should be easy to remember and easy to use.

- The markup language we use may not be your favorite markup language. I really like Markdown, but we may have to use Sphinx sometimes.


