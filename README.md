# Promptopia (NextJS 13)

A prompt generation website, that provides the user with prompts from different users to be used as input for their favourite AI powered bots such as ChatGPT, Midjourney, Dall-E etc. The website is based on the powerful NextJS 13's technology to provide responsive, serverless and lightening-fast connectivity, and TailwindCSS for efficient styling. It uses a MongoDB database, and Google Cloud for its APIs and Services.

#### Notable Features:

- Responsive design for any screen
- Login via Google account
- Account, Keyword or Hashtag based search
- Create & Edit pages to work on your posts
- Ability to interact with another user's profile page
- Minimal and attractive user interface

---

## Steps to run this project:

1. Clone this repository in a new project directory on your PC using `git clone https://github.com/aryan-mehta05/promptopia-nextjs.git`.
2. Download and install all the dependencies required for this project using `npm install`.
3. Configure your environment variables namely:<br>
   _a) Google Client ID_<br>
   _b) Google client Secret_<br>
   _c) MongoDB URI (from Atlas)_<br>
   _d) Next Auth URL (website domain link)_<br>
   _e) Next Auth Internal URL (website domain link)_<br>
   _f) Next Auth Custom Secret key_<br><br>
   You can generate your Next Auth Custom Secret key by visiting (https://www.cryptool.org/en/cto/openssl)[https://www.cryptool.org/en/cto/openssl] and entering the following command.
   `openssl rand -base64 32`

Copy the output key and paste it as your variable for **_f)_** above.

4. Once all of this is done, simply run the project using `npm run dev` _in your root route._

---

The screenshots for this project are available in the `app-screenshots` folder.
