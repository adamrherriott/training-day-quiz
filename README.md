# The Packaging Reality Check

Glass, fibre and metal. Let's see what stuck from the training day.

A light-hearted quiz for UK Packaging Pact colleagues, based on the team training on 15 October 2026 and the completed IS198 workbook. Ten quick rounds, about five minutes, and a certificate at the end. Bragging entirely optional.

## What is included

- Ten multiple-choice questions, with hints and immediate feedback.
- Explanations and an answer review after the final round.
- A score and a best-answer streak.
- A personalised PDF certificate for everyone who finishes, whatever their score.
- UK Packaging Pact branding, WRAP icons and photography, and a Sky 25 globe watermark on the certificate.
- Options to play again, copy a result and share the quiz.

The certificate is an entirely unofficial award, made for a bit of team fun.

## Open the quiz

1. Rename the supplied final HTML file to `index.html`.
2. Open it in a modern browser with JavaScript enabled.
3. Choose an answer by clicking or tapping it, or use keys **1-4** for answers **A-D**.
4. Finish all ten rounds, then enter an optional name and select **Download certificate · PDF**.

If the name is left blank, the certificate is awarded to "A packaging enthusiast".

Everything needed is embedded in the HTML: images, logos, fonts, styles and JavaScript. There are no packages to install, separate image folders to upload or build commands to run. A downloaded copy also works offline.

## Publish with GitHub Pages

1. Create or choose a repository for the quiz.
2. Upload `index.html` and this `README.md` to its top level on the `main` branch.
3. Open **Settings > Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select **main** and **/(root)**, then save.
6. When deployment completes, use **Visit site** in the Pages settings and share that address with colleagues.

The HTML file must be named `index.html`, using lower-case letters. To update the quiz later, replace that file on the publishing branch.

The quiz has no sign-in or access controls. A standard GitHub Pages deployment is publicly accessible, even when the intended audience is colleagues.

Setup references: [GitHub Pages publishing sources](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site) and [creating a GitHub Pages site](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site).

## Names, answers and scores

The quiz itself does not send names, answers or scores to a server. The certificate is generated in the browser, and copying a result is an action the participant chooses.

There are no analytics, tracking cookies or saved score histories added by the quiz. Progress is held only in the current page and resets when it is reloaded. Hosting services such as GitHub operate separately from the quiz.

## Branding and image credits

- Primary colour: **Sky — #94BAFA**.
- Text colour: **Forest — #0B301A**.
- Certificate watermark: **Sky 25 — #E4EDFF**.
- Typeface: **Inter**, with its SIL Open Font License included in the HTML.
- WRAP and UK Packaging Pact logos, icons and supplied photographs retain their respective owners' rights.
- Images for rounds **4, 6 and 10** were generated for this quiz and are labelled in the interface. The other photographs were supplied.

Training examples provide context; they are not universal claims about a material or product's environmental performance.

## Making changes

All quiz content and assets are in `index.html`.

| To change | Look for |
| --- | --- |
| Questions, answers, hints and explanations | `QUESTIONS` |
| Question photographs and alternative text | `QUESTION_PHOTOS` |
| Colours and page layout | CSS variables and styles |
| Certificate wording and layout | `drawCertificate()` |
| Certificate watermark artwork | `CERTIFICATE_WATERMARK` |

After editing, complete a round of the quiz, review the answers and download a certificate. Check the layout on a phone as well as a larger screen.
