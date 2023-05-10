# PromptBaba

PromptBaba is an open-source AI prompting tool that helps you discover, create, and share creative prompts for the modern world. With the increasing use of chatbots powered by AI, PromptBaba makes it easy to find and share prompts that you can use to charge up your AI-powered chatbot.

## Live Demo

https://prompt-baba-niteshpk.vercel.app/

## Screenshots

### Website

![website-page](https://github.com/niteshpk/prompt-baba/assets/25909806/9b149c61-4cec-4c91-ba15-05918c2d2da5)

### Mobile

![mobile-view](https://github.com/niteshpk/prompt-baba/assets/25909806/212daf24-797e-4544-af2c-239a50e75de5)

## Features

- Discover and share AI-powered prompts
- Login using NextAuth and Google authentication
- Browse prompts by tags, usernames, and content
- Search for prompts by keyword
- Copy prompts to clipboard
- Edit/Delete prompts (if you are a creator of that prompt)
- View profiles of other prompt creators and their prompts

## Getting started

1. Clone the repository:

```sh
git clone https://github.com/your-username/promptbaba.git
cd promptbaba
```

2. Create a `.env` file in the root of your project:

```sh
touch .env
```

3. Add the following constants to your `.env` file:

```sh
GOOGLE_ID=your-google-id
GOOGLE_CLIENT_SECRET=your-google-client-secret
MONGODB_URI=your-mongodb-uri
NEXTAUTH_URL=your-nextauth-url
NEXTAUTH_URL_INTERNAL=your-nextauth-internal-url
NEXTAUTH_SECRET=your-nextauth-secret
```

Replace the `your-google-id`, `your-google-client-secret`, `your-mongodb-uri`, `your-nextauth-url`, `your-nextauth-internal-url`, and `your-nextauth-secret` placeholders with the appropriate values for your project.

4. Install the dependencies and start the development server:

```sh
npm install
npm run dev
```

By following these steps, you will have created a `.env` file and added the necessary constants to it. Now you can run your PromptBaba application locally.

## Contributing

We welcome contributions from the community! If you'd like to contribute to PromptBaba, please fork the repository and submit a pull request with your changes.

## License

PromptBaba is released under the MIT License.
