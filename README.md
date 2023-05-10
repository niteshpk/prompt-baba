# PromptBaba

PromptBaba is an open-source AI prompting tool that helps you discover, create, and share creative prompts for the modern world. With the increasing use of chatbots powered by AI, PromptBaba makes it easy to find and share prompts that you can use to charge up your AI-powered chatbot.

## Live Demo

https://prompt-baba.vercel.app/

## Features

- Discover and share AI-powered prompts
- Login using NextAuth and Google authentication
- Browse prompts by tags, usernames, and content
- Search for prompts by keyword
- Copy prompts to clipboard
- Edit/Delete prompts (if you are a creator of that prompt)
- View profiles of other prompt creators and their prompts

Sure, here's an example of how you could add instructions in your README.md file to create a .env file and add the constants:

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
