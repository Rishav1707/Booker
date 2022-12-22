<p align="center">
  <a href="https://github.com/Evil-Bees/Booker">
    <img src="https://github.com/Evil-Bees/Booker/blob/67f8b0d6aa679ad7c8d365490921e413c89b12f2/public/assets/booker-logo.png" alt="Booker logo" width="300" />
  </a>
</p>

<h1 align="center">Monitoring all of your important online activity 🖥️</h1>
<br>

<p align="center">
  <img alt="Github Stars" src="https://badgen.net/github/stars/Evil-Bees/Alertit" />
  <a href="https://discord.com/invite/rvxGNrFhNz">
    <img alt="Discord" src="https://img.shields.io/discord/1033387274005663834.svg?label=&logo=discord&logoColor=ffffff&color=7389D8&labelColor=6A7EC2" />
  </a>
</p>

<br />

## Features

- Know if your website is offline right away! Reliable monitoring saves your money, reputation and clients — by alerting you before any major problems arise.

- Utilize one of the instruments that administrators use most frequently to verify the availability of network devices.

- Be informed!
Even the strongest among us have downtime. However, it's crucial to be aware of it before clients are impacted!

## Contributing
Feel like contributing? That's awesome!

Thanks for showing interest to contribute to AlertIt 💖, you rock!

When it comes to open source, there are different ways you can contribute, all of which are valuable. Here are a few guidelines that should help you as you prepare to make your contribution.

- Fork the project
- Take one of active issues
- Make a pull request

If you have any questions, feel free to contact us on Github discussions or issues page.
We are always active on discord server.

### API documentation
All necessary API documentation is available here.

https://documenter.getpostman.com/view/3551458/2s83zcT7GT

## Usage

Edit .env.local file:

```bash
MONGODB_URI="URL FOR MONGO DATABASE" 
SITE_URI="http://localhost:3000"
#FOR AUTH CHANGE THIS WITH RANDOM STRINGS FOR HASHING.
NEXTAUTH_JWT_SECRET="b4ed764b60a9a9be8452f06ca06519f9"
NEXTAUTH_SECRET="b4ed764b60a9a9be8452f06ca06519f9"
```

Run the development server:

```bash
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.