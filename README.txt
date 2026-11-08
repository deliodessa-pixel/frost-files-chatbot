# The Frost Files: Render deployment

This folder contains the complete guided Robert Frost chatbot in ONE `index.html` file. It needs no server, API key, database, or registration.

## Quick publish with GitHub and Render

1. On GitHub, create a new repository named `frost-files-chatbot`. A public repo is fine because no student information or secret is included.
2. In that new repository choose **Add file > Upload files** and upload `index.html` (not the ZIP itself). Commit to `main`.
3. In Render choose **New > Static Site**, connect that repository.
4. Enter: Name `the-frost-files`; branch `main`; build command `echo No build needed`; publish directory `.` (a single dot).
5. Create the static site and wait for its first successful deployment. Open the generated HTTPS URL.
6. Share the URL or make a QR code. Students do not need an account.

IMPORTANT: This is an interactive **guided** chatbot using preset replies, not a generative-AI chat. It cannot understand every arbitrary question. The bridging-writing checker checks keywords; it is not an official grade. Student conversations stay in each browser in guided mode.

If ChatGPT's GitHub integration receives write access to a repository, the publishing steps can be done through the connected services instead.
