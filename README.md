<div align="center">
  <div>
    <img src="https://img.shields.io/badge/-React_Native-black?style=for-the-badge&logoColor=white&logo=react&color=61DAFB" alt="reactnative" />
    <img src="https://img.shields.io/badge/-Expo-black?style=for-the-badge&logoColor=white&logo=expo&color=000020" alt="expo" />
    <img src="https://img.shields.io/badge/-PostgreSQL-black?style=for-the-badge&logoColor=white&logo=postgresql&color=4169E1" alt="postgresql" />
    <img src="https://shields.io/badge/supabase-black?logo=supabase&style=for-the-badge" alt="supabase"/>
  </div>

  <h3 align="center">Full Stack Hinge Clone</h3>
</div>

## 📋 <a name="table">Table of Contents</a>

1. 🤖 [Introduction](#introduction)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🔋 [Features](#features)
4. 📸 [Screenshots](#screenshots)
5. 🎥 [Demos](#demos)
6. 🤸 [Quick Start](#quick-start)
7. 🕸️ [Snippets](#snippets)
8. 🖇️ [Links](#links)
9. 📦 [Assets](#assets)
10. 🚀 [More](#more)

## <a name="introduction">🤖 Introduction</a>

Built with React Native (Expo) for handling the user interface, Supabase for managing authentication and the backend, and styled with TailwindCSS, this Hinge Clone is the perfect mobile dating app. The primary goal is to demonstrate how to develop a full-stack mobile dating application, showcasing essential features like user profiles, swiping, matches, and messaging. This project highlights the developer's skills in creating scalable, user-friendly apps, ensuring a memorable and impactful experience.

## <a name="tech-stack">⚙️ Tech Stack</a>

- React Native
- Expo
- PostgreSQL
- Supabase
- Sendbird
- Context API
- Tailwind CSS

## <a name="features">🔋 Features</a>

👉 **Phone Authentication with Verification**: Secure login with phone number verification via OTP (One-Time Password).

👉 **Profile Setup & Customization**: Users can add personal details, upload photos, and answer unique prompts to build their profiles.

👉 **Matchmaking Algorithm**: Users are shown profiles based on preferences like gender, location, distance, age and ethnicity.

👉 **Skipping & Liking**: Skip through profiles and "like" the ones you’re interested in for a potential match.

👉 **Message Once Matched**: Chat with users only after you’ve matched with.

👉 **Advanced Filters**: Filter profiles based on attributes.

👉 **Blurred Photos for Non-Premium Users**: Profile photos are blurred until users subscribe to premium membership.

👉 **Dynamic Prompts**: Users can answer engaging and varied prompts to highlight their personality in their profile.

👉 **Media Management**: Upload and manage multiple profile photos with ease.

... and many more, including scalable code architecture, modularity, and reusability.

## 📸 <a name="screenshots">Screenshots</a>

<div style="display: flex; flex-direction: 'row'; gap: 20px">
<img src="./screenshots/1.png" width=30%>
<img src="./screenshots/2.png" width=30%>
<img src="./screenshots/3.png" width=30%>
<img src="./screenshots/4.png" width=30%>
<img src="./screenshots/5.png" width=30%>
<img src="./screenshots/6.png" width=30%>
<img src="./screenshots/7.png" width=30%>
<img src="./screenshots/8.png" width=30%>
<img src="./screenshots/9.png" width=30%>
<img src="./screenshots/10.png" width=30%>
<img src="./screenshots/11.png" width=30%>
<img src="./screenshots/12.png" width=30%>
<img src="./screenshots/13.png" width=30%>
<img src="./screenshots/14.png" width=30%>
<img src="./screenshots/15.png" width=30%>
<img src="./screenshots/16.png" width=30%>
<img src="./screenshots/17.png" width=30%>
<img src="./screenshots/18.png" width=30%>
<img src="./screenshots/19.png" width=30%>
<img src="./screenshots/20.png" width=30%>
<img src="./screenshots/21.png" width=30%>
<img src="./screenshots/22.png" width=30%>
<img src="./screenshots/23.png" width=30%>
<img src="./screenshots/24.png" width=30%>
<img src="./screenshots/25.png" width=30%>
<img src="./screenshots/26.png" width=30%>
<img src="./screenshots/27.png" width=30%>
<img src="./screenshots/28.png" width=30%>
<img src="./screenshots/29.png" width=30%>
<img src="./screenshots/30.png" width=30%>
<img src="./screenshots/31.png" width=30%>
<img src="./screenshots/32.png" width=30%>
<img src="./screenshots/33.png" width=30%>
<img src="./screenshots/34.png" width=30%>
<img src="./screenshots/35.png" width=30%>
<img src="./screenshots/36.png" width=30%>
<img src="./screenshots/37.png" width=30%>
<img src="./screenshots/38.png" width=30%>
<img src="./screenshots/39.png" width=30%>
<img src="./screenshots/40.png" width=30%>
<img src="./screenshots/41.png" width=30%>
<img src="./screenshots/42.png" width=30%>
<img src="./screenshots/43.png" width=30%>
<img src="./screenshots/44.png" width=30%>
</div>

## 📸 <a name="demos">Demos</a>

<div style="display: flex; flex-direction: 'row'; gap: 20px">
<img src="./demos/1.gif" width=30%>
<img src="./demos/2.gif" width=30%>
<img src="./demos/3.gif" width=30%>
<img src="./demos/4.gif" width=30%>
<img src="./demos/5.gif" width=30%>
<img src="./demos/6.gif" width=30%>
<img src="./demos/7.gif" width=30%>

</div>

## <a name="quick-start">🤸 Quick Start</a>

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Node.js](https://nodejs.org/en)
- [Docker Desktop](https://www.docker.com)
- [Visual Studio Code](https://code.visualstudio.com/)
- [Git](https://git-scm.com/)
- [Postman](https://www.postman.com)

**Cloning the Repository**

```bash
git clone https://github.com/javelwill/hinge.git
cd hinge
```

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Set Up Environment Variables**

Create a new file named `.env.development` in the root of your project and add the following content:

```
EXPO_PUBLIC_SUPABASE_URL=
EXPO_PUBLIC_SUPABASE_ANON_KEY=
EXPO_PUBLIC_SENDBIRD_APP_ID=
SUPABASE_AUTH_SMS_TWILIO_AUTH_TOKEN=
```

Replace the placeholder values with your Supabase, Twilio, and Senbird credentials. To obtain the Supabase values, you can run the following command after starting Supabase locally

```bash
npx supabase status
```

**Running Supabase Locally**

```bash
npx supabase start
```

**Running React Native**

```bash
npx expo start
```

Download the [Expo Go](https://expo.dev/go) app and Scan the QR code on your respective device to view the project.

## <a name="snippets">🕸️ Snippets</a>

Here are some code snippets from the project to help you get started quickly.

### VS Code

<details>
<summary><code>.vscode/extensions.json</code></summary>

```json
{
  "recommendations": [
    "bradlc.vscode-tailwindcss",
    "dbaeumer.vscode-eslint",
    "deinsoftware.arrow-function-snippets",
    "denoland.vscode-deno",
    "dsznajder.es7-react-js-snippets",
    "esbenp.prettier-vscode",
    "expo.vscode-expo-tools",
    "formulahendry.auto-close-tag",
    "formulahendry.auto-rename-tag",
    "jock.svg",
    "kisstkondoros.vscode-gutter-preview",
    "mariusalchimavicius.json-to-ts",
    "mikestead.dotenv",
    "msjsdiag.vscode-react-native",
    "naumovs.color-highlight",
    "postman.postman-for-vscode",
    "xabikos.javascriptsnippets"
  ]
}
```

</details>

<details>
<summary><code>.vscode/project.code-snippets</code></summary>

```json
{
  "Expo Router Page": {
    "prefix": "page",
    "body": [
      "import { Text, View } from \"react-native\";",
      "",
      "export default function Page() {",
      "  return (",
      "    <View>",
      "      <Text>${TM_FILENAME_BASE/(.*)/${1:/pascalcase}/}</Text>",
      "    </View>",
      "  );",
      "}",
      ""
    ],
    "description": "Create an Expo Router Page"
  },
  "Expo Router Stack Layout": {
    "prefix": "stack",
    "body": [
      "import { Stack } from \"expo-router\";",
      "",
      "export default function Layout() {",
      "  return <Stack></Stack>;",
      "}",
      ""
    ],
    "description": "Create a Expo Router Stack Layout"
  },
  "Expo Router Tabs Layout": {
    "prefix": "tabs",
    "body": [
      "import { Tabs } from \"expo-router\";",
      "",
      "export default function Layout() {",
      "  return <Tabs></Tabs>;",
      "}",
      ""
    ],
    "description": "Create a Expo Router Tabs Layout"
  },
  "React Native Default Export Functional Component": {
    "prefix": "comp",
    "body": [
      "import { FC } from \"react\";",
      "import { Text, View } from \"react-native\";",
      "",
      "interface Props {}",
      "",
      "export const ${TM_FILENAME_BASE/(.*)/${1:/pascalcase}/}: FC<Props> = () => {",
      "  return (",
      "    <View>",
      "      <Text>${TM_FILENAME_BASE/(.*)/${1:/pascalcase}/}</Text>",
      "    </View>",
      "  );",
      "};",
      ""
    ],
    "description": "Create a React Native Functional Component with TypeScript"
  }
}
```

</details>

<details>
<summary><code>.vscode/settings.json</code></summary>

```json
{
  "explorer.compactFolders": false,
  "editor.wordWrap": "on",
  "editor.tabSize": 2,
  "editor.formatOnSave": true,
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "[typescriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": "explicit",
    "source.organizeImports": "explicit"
  }
}
```

</details>

### Tailwind

<details>
<summary><code>tailwind.config.js</code></summary>

```js
/** @type {import('tailwindcss').Config} */
module.exports = {
  // NOTE: Update this to include the paths to all of your component files.
  content: [
    "./src/app/**/*.{js,jsx,ts,tsx}",
    "./src/components/**/*.{js,jsx,ts,tsx}",
  ],
  presets: [require("nativewind/preset")],
  theme: {
    extend: {
      fontFamily: {
        "playfair-regular": ["PlayfairDisplay-Regular", "serif"],
        "playfair-medium": ["PlayfairDisplay-Medium", "serif"],
        "playfair-semibold": ["PlayfairDisplay-SemiBold", "serif"],
        "playfair-bold": ["PlayfairDisplay-Bold", "serif"],
        "playfair-extrabold": ["PlayfairDisplay-ExtraBold", "serif"],
        "playfair-black": ["PlayfairDisplay-Black", "serif"],
        "poppins-thin": ["Poppins-Thin", "sans-serif"],
        "poppins-extralight": ["Poppins-ExtraLight", "sans-serif"],
        "poppins-light": ["Poppins-Light", "sans-serif"],
        "poppins-regular": ["Poppins-Regular", "sans-serif"],
        "poppins-medium": ["Poppins-Medium", "sans-serif"],
        "poppins-semibold": ["Poppins-SemiBold", "sans-serif"],
        "poppins-bold": ["Poppins-Bold", "sans-serif"],
        "poppins-extrabold": ["Poppins-ExtraBold", "sans-serif"],
        "poppins-black": ["Poppins-Black", "sans-serif"],
      },
    },
  },
  plugins: [],
};

```

</details>

### Supabase

<details>
<summary><code>migrations</code></summary>

```bash
npx supabase migration new migration_name

npx supabase db diff -f initial schema

npx supabase db reset

```

</details>

<details>
<summary><code>sample data</code></summary>

```sql

insert into "public"."children" ("id", "name") values
	(1, 'Don''t have children'),
	(2, 'Have children');

insert into "public"."covid_vaccine" ("id", "name") values
	(1, 'Vaccinated'),
	(2, 'Partially vaccinated'),
	(3, 'Not yet vaccinated');

insert into "public"."ethnicities" ("id", "name") values
	(1, 'Black/African Descent'),
	(2, 'East Asian'),
	(3, 'Hispanic/Latino'),
	(4, 'Middle Eastern'),
	(5, 'Native American'),
	(6, 'Pacific Islander'),
	(7, 'South Asian'),
	(8, 'Southeast Asian'),
	(9, 'White/Caucasian'),
	(10, 'Other');

insert into "public"."family_plans" ("id", "name") values
	(1, 'Don''t want children'),
	(2, 'Want children'),
	(3, 'Open to children'),
	(4, 'Not sure');

insert into "public"."genders" ("id", "name", "plural_name") values
	(1, 'Man', 'Men'),
	(2, 'Woman', 'Women'),
	(3, 'Nonbinary', 'Nonbinary people');

insert into "public"."pets" ("id", "name") values
	(1, 'Dog'),
	(2, 'Cat'),
	(3, 'Bird'),
	(4, 'Fish'),
	(5, 'Reptile');

insert into "public"."prompts" ("id", "question") values
	(1, 'The way to win me over is'),
	(2, 'I go crazy for'),
	(3, 'My greatest strength'),
	(4, 'I recently discovered that'),
	(5, 'A random fact I love is'),
	(6, 'Unusual skills'),
	(7, 'Dating me is like'),
	(8, 'I''m convinced that'),
	(9, 'A life goal of mine'),
	(10, 'Typical Sunday'),
	(11, 'This year, I really want to'),
	(12, 'My most irrational fear'),
	(13, 'My simple pleasures'),
	(14, 'Green flags I look for'),
	(15, 'The hallmark of a good relationship is'),
	(16, 'We''ll get along if'),
	(17, 'We''re the same type of weird if'),
	(18, 'All I ask is that you'),
	(19, 'I''ll fall for you if'),
	(20, 'I''ll brag about you to my friends if'),
	(21, 'I''m weirdly attracted to'),
	(22, 'I want someone who'),
	(23, 'Something that''s non-negotiable for me is'),
	(24, 'I''m looking for'),
	(25, 'I get myself out of a funk by'),
	(26, 'I hype myself up by'),
	(27, 'I wind down by'),
	(28, 'When I need advice, I go to'),
	(29, 'A boundary of mine is'),
	(30, 'To me, relaxation is'),
	(31, 'The last time I cried happy tears was'),
	(32, 'My last journal entry was about'),
	(33, 'My friends ask me for advice about'),
	(34, 'My therapist would say I'),
	(35, 'My self-care routine is'),
	(36, 'Therapy recently taught me'),
	(37, 'My cry-in-the-car song is'),
	(38, 'I feel most supported when'),
	(39, 'I know the best spot in town for'),
	(40, 'The best way to ask me out is by'),
	(41, 'Together, we could'),
	(42, 'What I order for the table'),
	(43, 'First round is on me if'),
	(44, 'Biggest risk I''ve taken'),
	(45, 'Most spontaneous thing I''ve done'),
	(46, 'My biggest date fail'),
	(47, 'Weirdest gift I have given or received'),
	(48, 'Two truths and a lie'),
	(49, 'Never have I ever'),
	(50, 'Best travel story'),
	(51, 'Worst idea I''ve ever had'),
	(52, 'One thing I''ll never do again'),
	(53, 'The dorkiest thing about me is'),
	(54, 'My most controversial opinion is'),
	(55, 'If loving this is wrong, I don''t want to be right'),
	(56, 'What if I told you that'),
	(57, 'You should *not* go out with me if'),
	(58, 'The key to my heart is'),
	(59, 'I won''t shut up about'),
	(60, 'My Love Language is'),
	(61, 'I geek out on'),
	(62, 'The one thing you should know about me is'),
	(63, 'Don''t hate me if I'),
	(64, 'Change my mind about'),
	(65, 'Do you agree or disagree that'),
	(66, 'The one thing I''d love to know about you is'),
	(67, 'Give me travel tips for'),
	(68, 'You should leave a comment if'),
	(69, 'I bet you can''t'),
	(70, 'I''ll pick the topic if you start the conversation'),
	(71, 'Let''s debate this topic'),
	(72, 'Try to guess this about me'),
	(73, 'Teach me something about'),
	(74, 'Let''s make sure we''re on the same page about'),
	(75, 'My BFF''s take on why you should date me'),
	(76, 'A quick rant about'),
	(77, 'I''ll give you the set up, you guess the punchline'),
	(78, 'Guess the song'),
	(79, 'Proof I have musical talent'),
	(80, 'My best Dad Joke'),
	(81, 'Saying "Hi!" in as many languages I know'),
	(82, 'My best celebrity impression'),
	(83, 'Apparently, my life''s soundtrack is'),
	(84, 'I wish more people knew'),
	(85, 'How to pronounce my name'),
	(86, 'A shower thought I recently had'),
	(87, 'My favorite line from a movie');

insert into "public"."pronouns" ("id", "name") values
	(1, 'she'),
	(2, 'her'),
	(3, 'hers'),
	(4, 'he'),
	(5, 'him'),
	(6, 'his'),
	(7, 'they'),
	(8, 'them'),
	(9, 'theirs'),
	(10, 've'),
	(11, 'ver'),
	(12, 'vis'),
	(13, 'ze'),
	(14, 'hir'),
	(15, 'hirs'),
	(16, 'ae'),
	(17, 'aer'),
	(18, 'aers'),
	(19, 'ey'),
	(20, 'em'),
	(21, 'eirs'),
	(22, 'fae'),
	(23, 'faer'),
	(24, 'faers'),
	(25, 'xe'),
	(26, 'xem'),
	(27, 'xyrs'),
	(28, 'zir'),
	(29, 'zirs');

insert into "public"."sexualities" ("id", "name") values
	(1, 'Straight'),
	(2, 'Gay'),
	(3, 'Lesbian'),
	(4, 'Bisexual'),
	(5, 'Allosexual'),
	(6, 'Androsexual'),
	(7, 'Asexual'),
	(8, 'Autosexual'),
	(9, 'Bicurious'),
	(10, 'Demisexual'),
	(11, 'Fliud'),
	(12, 'Graysexual'),
	(13, 'Gynosexual'),
	(14, 'Monosexual'),
	(15, 'Omnisexual'),
	(16, 'Pansexual'),
	(17, 'Polysexual'),
	(18, 'Queer'),
	(19, 'Questioning'),
	(20, 'Skoliosexual'),
	(21, 'Spectrasexual');

insert into "public"."zodiac_signs" ("id", "name") values
	(1, 'Aries'),
	(2, 'Taurus'),
	(3, 'Gemini'),
	(4, 'Cancer'),
	(5, 'Leo'),
	(6, 'Virgo'),
	(7, 'Libra'),
	(8, 'Scorpio'),
	(9, 'Sagittarius'),
	(10, 'Capricorn'),
	(11, 'Aquarius'),
	(12, 'Pisces');

insert into "public"."profiles" ("id", "first_name", "last_name", "dob", "height_cm", "neighborhood", "latitude", "longitude", "children_id", "covid_vaccine_id", "family_plan_id", "gender_id", "zodiac_sign_id", "sexuality_id", "max_distance_km", "min_age", "max_age", "phone") values
	('00000000-0000-0000-0000-000000000000', 'Javel', NULL, '1995-12-25', 180, 'Montego Bay', 18.499634842789888, -77.91729233644581, 1, 1, 2, 1, 9, 1, 160, 18, 100, '18761234567'),
	('00000000-0000-0000-0000-000000000001', 'David', NULL, '2001-11-02', 180, 'Kingston', 17.9374623588942, -76.779836513002, 1, 1, 1, 1, 8, 1, 160, 18, 100, '10000000001'),
	('00000000-0000-0000-0000-000000000002', 'Jess', NULL, '1986-03-06', 180, 'Kingston', 17.9374623588942, -76.779836513002, 1, 1, 3, 2, 12, 1, 160, 18, 100, '10000000002'),
	('00000000-0000-0000-0000-000000000003', 'Randen', NULL, '1982-09-23', 180, 'Kingston', 17.9374623588942, -76.779836513002, 2, 1, 2, 1, 7, 1, 160, 18, 100, '10000000003'),
	('00000000-0000-0000-0000-000000000004', 'Bhanu', NULL, '1982-11-14', 180, 'Kingston', 17.9374623588942, -76.779836513002, 1, 1, 4, 1, 8, 18, 160, 18, 100, '10000000004'),
	('00000000-0000-0000-0000-000000000005', 'Jem', NULL, '1991-12-04', 180, 'Kingston', 17.9374623588942, -76.779836513002, 1, 1, 2, 2, 9, 1, 160, 18, 100, '10000000005'),
	('00000000-0000-0000-0000-000000000006', 'Moriah', NULL, '1995-03-14', 180, 'Kingston', 17.9374623588942, -76.779836513002, 1, 1, 4, 2, 12, 1, 160, 18, 100, '10000000006'),
	('00000000-0000-0000-0000-000000000007', 'Tim', NULL, '1992-07-27', 180, 'Kingston', 17.9374623588942, -76.779836513002, 2, 1, 2, 1, 5, 1, 160, 18, 100, '10000000007'),
	('00000000-0000-0000-0000-000000000008', 'Soda', NULL, '1996-04-04', 180, 'Kingston', 17.9374623588942, -76.779836513002, 1, 1, 4, 2, 1, 1, 160, 18, 100, '10000000008'),
	('00000000-0000-0000-0000-000000000009', 'Tevin', NULL, '1999-04-24', 180, 'Kingston', 17.9374623588942, -76.779836513002, 1, 1, 1, 1, 2, 1, 160, 18, 100, '10000000009'),
	('00000000-0000-0000-0000-000000000010', 'Hunter', NULL, '1996-02-24', 180, 'Montego Bay', 18.4989969343249, -77.9174517446859, 1, 1, 2, 1, 12, 1, 160, 18, 100, '10000000010'),
	('00000000-0000-0000-0000-000000000011', 'Tiffany', NULL, '1991-02-08', 180, 'Montego Bay', 18.4989969343249, -77.9174517446859, 1, 1, 2, 2, 11, 1, 160, 18, 100, '10000000011'),
	('00000000-0000-0000-0000-000000000012', 'Venus', NULL, '1999-02-12', 180, 'Montego Bay', 18.4989969343249, -77.9174517446859, 1, 1, 4, 2, 11, 1, 160, 18, 100, '10000000012'),
	('00000000-0000-0000-0000-000000000013', 'Q', NULL, '1994-03-08', 180, 'Montego Bay', 18.4989969343249, -77.9174517446859, 1, 1, 2, 1, 12, 1, 160, 18, 100, '10000000013'),
	('00000000-0000-0000-0000-000000000014', 'Maria', NULL, '1975-10-13', 180, 'Montego Bay', 18.4989969343249, -77.9174517446859, 2, 1, 2, 2, 7, 1, 160, 18, 100, '10000000014'),
	('00000000-0000-0000-0000-000000000015', 'Liz', NULL, '1988-03-18', 180, 'Montego Bay', 18.4989969343249, -77.9174517446859, 2, 1, 2, 2, 12, 1, 160, 18, 100, '10000000015'),
	('00000000-0000-0000-0000-000000000016', 'Ben', NULL, '1992-03-25', 180, 'Montego Bay', 18.4989969343249, -77.9174517446859, 1, 1, 1, 1, 1, 1, 160, 18, 100, '10000000016'),
	('00000000-0000-0000-0000-000000000017', 'Charlie', NULL, '1997-12-22', 180, 'Montego Bay', 18.4989969343249, -77.9174517446859, 1, 1, 2, 1, 10, 1, 160, 18, 100, '10000000017'),
	('00000000-0000-0000-0000-000000000018', 'Kenzie', NULL, '1994-08-06', 180, 'Montego Bay', 18.4989969343249, -77.9174517446859, 1, 1, 2, 2, 5, 1, 160, 18, 100, '10000000018');

insert into "public"."profile_ethnicities" ("profile_id", "ethnicity_id") values
	('00000000-0000-0000-0000-000000000000', 1),
	('00000000-0000-0000-0000-000000000001', 9),
	('00000000-0000-0000-0000-000000000002', 2),
	('00000000-0000-0000-0000-000000000003', 3),
	('00000000-0000-0000-0000-000000000004', 7),
	('00000000-0000-0000-0000-000000000005', 10),
	('00000000-0000-0000-0000-000000000006', 9),
	('00000000-0000-0000-0000-000000000007', 1),
	('00000000-0000-0000-0000-000000000008', 1),
	('00000000-0000-0000-0000-000000000009', 1),
	('00000000-0000-0000-0000-000000000010', 9),
	('00000000-0000-0000-0000-000000000011', 1),
	('00000000-0000-0000-0000-000000000012', 4),
	('00000000-0000-0000-0000-000000000013', 1),
	('00000000-0000-0000-0000-000000000014', 4),
	('00000000-0000-0000-0000-000000000015', 9),
	('00000000-0000-0000-0000-000000000016', 9),
	('00000000-0000-0000-0000-000000000017', 9),
	('00000000-0000-0000-0000-000000000018', 9);

insert into "public"."profile_pets" ("profile_id", "pet_id") values
	('00000000-0000-0000-0000-000000000000', 1),
	('00000000-0000-0000-0000-000000000000', 2);

insert into "public"."profile_pronouns" ("profile_id", "pronoun_id") values
	('00000000-0000-0000-0000-000000000000', 4),
	('00000000-0000-0000-0000-000000000000', 5),
	('00000000-0000-0000-0000-000000000000', 6);

insert into "public"."profile_gender_preferences" ("profile_id", "gender_id") values
	('00000000-0000-0000-0000-000000000000', 2),
	('00000000-0000-0000-0000-000000000001', 2),
	('00000000-0000-0000-0000-000000000002', 1),
	('00000000-0000-0000-0000-000000000003', 2),
	('00000000-0000-0000-0000-000000000004', 1),
	('00000000-0000-0000-0000-000000000005', 1),
	('00000000-0000-0000-0000-000000000006', 1),
	('00000000-0000-0000-0000-000000000007', 2),
	('00000000-0000-0000-0000-000000000008', 1),
	('00000000-0000-0000-0000-000000000009', 2),
	('00000000-0000-0000-0000-000000000010', 2),
	('00000000-0000-0000-0000-000000000011', 1),
	('00000000-0000-0000-0000-000000000012', 1),
	('00000000-0000-0000-0000-000000000013', 2),
	('00000000-0000-0000-0000-000000000014', 1),
	('00000000-0000-0000-0000-000000000015', 1),
	('00000000-0000-0000-0000-000000000016', 2),
	('00000000-0000-0000-0000-000000000017', 2),
	('00000000-0000-0000-0000-000000000018', 1);

insert into "public"."profile_answers" ("id", "profile_id", "prompt_id", "answer_text", "answer_order", "is_active") values
	('00000000-0000-0000-0000-000000000000', '00000000-0000-0000-0000-000000000000', 1, 'Est debitis esse et neque fugit qui sed porro incidunt internos!', 0, true),
	('10000000-0000-0000-0000-000000000000', '00000000-0000-0000-0000-000000000000', 2, 'Qui eligendi nihil qui doloremque galisum ut maiores Quis.', 1, true),
	('20000000-0000-0000-0000-000000000000', '00000000-0000-0000-0000-000000000000', 3, 'Facere qui veniam accusantium id dolorem omnis.', 2, true),
	('00000000-0000-0000-0000-000000000001', '00000000-0000-0000-0000-000000000001', 4, 'Est debitis esse et neque fugit qui sed porro incidunt internos!', 0, true),
	('10000000-0000-0000-0000-000000000001', '00000000-0000-0000-0000-000000000001', 5, 'Qui eligendi nihil qui doloremque galisum ut maiores Quis.', 1, true),
	('20000000-0000-0000-0000-000000000001', '00000000-0000-0000-0000-000000000001', 6, 'Facere qui veniam accusantium id dolorem omnis.', 2, true),
	('00000000-0000-0000-0000-000000000002', '00000000-0000-0000-0000-000000000002', 7, 'Est debitis esse et neque fugit qui sed porro incidunt internos!', 0, true),
	('10000000-0000-0000-0000-000000000002', '00000000-0000-0000-0000-000000000002', 8, 'Qui eligendi nihil qui doloremque galisum ut maiores Quis.', 1, true),
	('20000000-0000-0000-0000-000000000002', '00000000-0000-0000-0000-000000000002', 9, 'Facere qui veniam accusantium id dolorem omnis.', 2, true),
	('00000000-0000-0000-0000-000000000003', '00000000-0000-0000-0000-000000000003', 10, 'Est debitis esse et neque fugit qui sed porro incidunt internos!', 0, true),
	('10000000-0000-0000-0000-000000000003', '00000000-0000-0000-0000-000000000003', 11, 'Qui eligendi nihil qui doloremque galisum ut maiores Quis.', 1, true),
	('20000000-0000-0000-0000-000000000003', '00000000-0000-0000-0000-000000000003', 12, 'Facere qui veniam accusantium id dolorem omnis.', 2, true),
	('00000000-0000-0000-0000-000000000004', '00000000-0000-0000-0000-000000000004', 13, 'Est debitis esse et neque fugit qui sed porro incidunt internos!', 0, true),
	('10000000-0000-0000-0000-000000000004', '00000000-0000-0000-0000-000000000004', 14, 'Qui eligendi nihil qui doloremque galisum ut maiores Quis.', 1, true),
	('20000000-0000-0000-0000-000000000004', '00000000-0000-0000-0000-000000000004', 15, 'Facere qui veniam accusantium id dolorem omnis.', 2, true),
	('00000000-0000-0000-0000-000000000005', '00000000-0000-0000-0000-000000000005', 16, 'Est debitis esse et neque fugit qui sed porro incidunt internos!', 0, true),
	('10000000-0000-0000-0000-000000000005', '00000000-0000-0000-0000-000000000005', 17, 'Qui eligendi nihil qui doloremque galisum ut maiores Quis.', 1, true),
	('20000000-0000-0000-0000-000000000005', '00000000-0000-0000-0000-000000000005', 18, 'Facere qui veniam accusantium id dolorem omnis.', 2, true),
	('00000000-0000-0000-0000-000000000006', '00000000-0000-0000-0000-000000000006', 19, 'Est debitis esse et neque fugit qui sed porro incidunt internos!', 0, true),
	('10000000-0000-0000-0000-000000000006', '00000000-0000-0000-0000-000000000006', 20, 'Qui eligendi nihil qui doloremque galisum ut maiores Quis.', 1, true),
	('20000000-0000-0000-0000-000000000006', '00000000-0000-0000-0000-000000000006', 21, 'Facere qui veniam accusantium id dolorem omnis.', 2, true),
	('00000000-0000-0000-0000-000000000007', '00000000-0000-0000-0000-000000000007', 22, 'Est debitis esse et neque fugit qui sed porro incidunt internos!', 0, true),
	('10000000-0000-0000-0000-000000000007', '00000000-0000-0000-0000-000000000007', 23, 'Qui eligendi nihil qui doloremque galisum ut maiores Quis.', 1, true),
	('20000000-0000-0000-0000-000000000007', '00000000-0000-0000-0000-000000000007', 24, 'Facere qui veniam accusantium id dolorem omnis.', 2, true),
	('00000000-0000-0000-0000-000000000008', '00000000-0000-0000-0000-000000000008', 25, 'Est debitis esse et neque fugit qui sed porro incidunt internos!', 0, true),
	('10000000-0000-0000-0000-000000000008', '00000000-0000-0000-0000-000000000008', 26, 'Qui eligendi nihil qui doloremque galisum ut maiores Quis.', 1, true),
	('20000000-0000-0000-0000-000000000008', '00000000-0000-0000-0000-000000000008', 27, 'Facere qui veniam accusantium id dolorem omnis.', 2, true),
	('00000000-0000-0000-0000-000000000009', '00000000-0000-0000-0000-000000000009', 28, 'Est debitis esse et neque fugit qui sed porro incidunt internos!', 0, true),
	('10000000-0000-0000-0000-000000000009', '00000000-0000-0000-0000-000000000009', 29, 'Qui eligendi nihil qui doloremque galisum ut maiores Quis.', 1, true),
	('20000000-0000-0000-0000-000000000009', '00000000-0000-0000-0000-000000000009', 30, 'Facere qui veniam accusantium id dolorem omnis.', 2, true),
	('00000000-0000-0000-0000-000000000010', '00000000-0000-0000-0000-000000000010', 31, 'Est debitis esse et neque fugit qui sed porro incidunt internos!', 0, true),
	('10000000-0000-0000-0000-000000000010', '00000000-0000-0000-0000-000000000010', 32, 'Qui eligendi nihil qui doloremque galisum ut maiores Quis.', 1, true),
	('20000000-0000-0000-0000-000000000010', '00000000-0000-0000-0000-000000000010', 33, 'Facere qui veniam accusantium id dolorem omnis.', 2, true),
	('00000000-0000-0000-0000-000000000011', '00000000-0000-0000-0000-000000000011', 34, 'Est debitis esse et neque fugit qui sed porro incidunt internos!', 0, true),
	('10000000-0000-0000-0000-000000000011', '00000000-0000-0000-0000-000000000011', 35, 'Qui eligendi nihil qui doloremque galisum ut maiores Quis.', 1, true),
	('20000000-0000-0000-0000-000000000011', '00000000-0000-0000-0000-000000000011', 36, 'Facere qui veniam accusantium id dolorem omnis.', 2, true),
	('00000000-0000-0000-0000-000000000012', '00000000-0000-0000-0000-000000000012', 37, 'Est debitis esse et neque fugit qui sed porro incidunt internos!', 0, true),
	('10000000-0000-0000-0000-000000000012', '00000000-0000-0000-0000-000000000012', 38, 'Qui eligendi nihil qui doloremque galisum ut maiores Quis.', 1, true),
	('20000000-0000-0000-0000-000000000012', '00000000-0000-0000-0000-000000000012', 39, 'Facere qui veniam accusantium id dolorem omnis.', 2, true),
	('00000000-0000-0000-0000-000000000013', '00000000-0000-0000-0000-000000000013', 40, 'Est debitis esse et neque fugit qui sed porro incidunt internos!', 0, true),
	('10000000-0000-0000-0000-000000000013', '00000000-0000-0000-0000-000000000013', 41, 'Qui eligendi nihil qui doloremque galisum ut maiores Quis.', 1, true),
	('20000000-0000-0000-0000-000000000013', '00000000-0000-0000-0000-000000000013', 42, 'Facere qui veniam accusantium id dolorem omnis.', 2, true),
	('00000000-0000-0000-0000-000000000014', '00000000-0000-0000-0000-000000000014', 43, 'Est debitis esse et neque fugit qui sed porro incidunt internos!', 0, true),
	('10000000-0000-0000-0000-000000000014', '00000000-0000-0000-0000-000000000014', 44, 'Qui eligendi nihil qui doloremque galisum ut maiores Quis.', 1, true),
	('20000000-0000-0000-0000-000000000014', '00000000-0000-0000-0000-000000000014', 45, 'Facere qui veniam accusantium id dolorem omnis.', 2, true),
	('00000000-0000-0000-0000-000000000015', '00000000-0000-0000-0000-000000000015', 46, 'Est debitis esse et neque fugit qui sed porro incidunt internos!', 0, true),
	('10000000-0000-0000-0000-000000000015', '00000000-0000-0000-0000-000000000015', 47, 'Qui eligendi nihil qui doloremque galisum ut maiores Quis.', 1, true),
	('20000000-0000-0000-0000-000000000015', '00000000-0000-0000-0000-000000000015', 48, 'Facere qui veniam accusantium id dolorem omnis.', 2, true),
	('00000000-0000-0000-0000-000000000016', '00000000-0000-0000-0000-000000000016', 49, 'Est debitis esse et neque fugit qui sed porro incidunt internos!', 0, true),
	('10000000-0000-0000-0000-000000000016', '00000000-0000-0000-0000-000000000016', 50, 'Qui eligendi nihil qui doloremque galisum ut maiores Quis.', 1, true),
	('20000000-0000-0000-0000-000000000016', '00000000-0000-0000-0000-000000000016', 51, 'Facere qui veniam accusantium id dolorem omnis.', 2, true),
	('00000000-0000-0000-0000-000000000017', '00000000-0000-0000-0000-000000000017', 52, 'Est debitis esse et neque fugit qui sed porro incidunt internos!', 0, true),
	('10000000-0000-0000-0000-000000000017', '00000000-0000-0000-0000-000000000017', 53, 'Qui eligendi nihil qui doloremque galisum ut maiores Quis.', 1, true),
	('20000000-0000-0000-0000-000000000017', '00000000-0000-0000-0000-000000000017', 54, 'Facere qui veniam accusantium id dolorem omnis.', 2, true),
	('00000000-0000-0000-0000-000000000018', '00000000-0000-0000-0000-000000000018', 55, 'Est debitis esse et neque fugit qui sed porro incidunt internos!', 0, true),
	('10000000-0000-0000-0000-000000000018', '00000000-0000-0000-0000-000000000018', 56, 'Qui eligendi nihil qui doloremque galisum ut maiores Quis.', 1, true),
	('20000000-0000-0000-0000-000000000018', '00000000-0000-0000-0000-000000000018', 57, 'Facere qui veniam accusantium id dolorem omnis.', 2, true);

insert into "public"."profile_photos" ("id", "profile_id", "photo_url", "photo_order", "is_active") values
	('00000000-0000-0000-0000-000000000000', '00000000-0000-0000-0000-000000000000', 'https://www.instagram.com/p/B0cV-XwB2ML/media?size=l', 0, true),
	('10000000-0000-0000-0000-000000000000', '00000000-0000-0000-0000-000000000000', 'https://www.instagram.com/p/BhFvO_Kh036/media?size=l', 1, true),
	('20000000-0000-0000-0000-000000000000', '00000000-0000-0000-0000-000000000000', 'https://www.instagram.com/p/Bb8jR-gj2SF/media?size=l', 2, true),
	('30000000-0000-0000-0000-000000000000', '00000000-0000-0000-0000-000000000000', 'https://www.instagram.com/p/DCrVMrnsdm-/media?size=l', 3, true),
	('40000000-0000-0000-0000-000000000000', '00000000-0000-0000-0000-000000000000', 'https://www.instagram.com/p/DCex002OCLP/media?size=l', 4, true),
	('50000000-0000-0000-0000-000000000000', '00000000-0000-0000-0000-000000000000', 'https://www.instagram.com/p/C_JHSSitBbA/media?size=l', 5, true),
	('00000000-0000-0000-0000-000000000001', '00000000-0000-0000-0000-000000000001', 'https://www.instagram.com/p/C5Ef_4ZvU4D/media?size=l', 0, true),
	('10000000-0000-0000-0000-000000000001', '00000000-0000-0000-0000-000000000001', 'https://www.instagram.com/p/C4oNwMWSHfh/media?size=l', 1, true),
	('20000000-0000-0000-0000-000000000001', '00000000-0000-0000-0000-000000000001', 'https://www.instagram.com/p/C84mL6Vu5Be/media?size=l', 2, true),
	('30000000-0000-0000-0000-000000000001', '00000000-0000-0000-0000-000000000001', 'https://www.instagram.com/p/CzR-v-fvnIt/media?size=l', 3, true),
	('40000000-0000-0000-0000-000000000001', '00000000-0000-0000-0000-000000000001', 'https://www.instagram.com/p/Bv-G5DUhhcP/media?size=l', 4, true),
	('50000000-0000-0000-0000-000000000001', '00000000-0000-0000-0000-000000000001', 'https://www.instagram.com/p/Bo0Gz3KB0bs/media?size=l', 5, true),
	('00000000-0000-0000-0000-000000000002', '00000000-0000-0000-0000-000000000002', 'https://www.instagram.com/p/CxmaD9bLx4T/media?size=l', 0, true),
	('10000000-0000-0000-0000-000000000002', '00000000-0000-0000-0000-000000000002', 'https://www.instagram.com/p/CxW8FqPL_ZN/media?size=l', 1, true),
	('20000000-0000-0000-0000-000000000002', '00000000-0000-0000-0000-000000000002', 'https://www.instagram.com/p/CLOYQ5Rj1_B/media?size=l', 2, true),
	('30000000-0000-0000-0000-000000000002', '00000000-0000-0000-0000-000000000002', 'https://www.instagram.com/p/Ce-IiLGLCz0/media?size=l', 3, true),
	('40000000-0000-0000-0000-000000000002', '00000000-0000-0000-0000-000000000002', 'https://www.instagram.com/p/Cc_t3CUp91Q/media?size=l', 4, true),
	('50000000-0000-0000-0000-000000000002', '00000000-0000-0000-0000-000000000002', 'https://www.instagram.com/p/CSDA8cShOl5/media?size=l', 5, true),
	('00000000-0000-0000-0000-000000000003', '00000000-0000-0000-0000-000000000003', 'https://www.instagram.com/p/C7wN9RTRpxG/media?size=l', 0, true),
	('10000000-0000-0000-0000-000000000003', '00000000-0000-0000-0000-000000000003', 'https://www.instagram.com/p/C7rtohAx2Ev/media?size=l', 1, true),
	('20000000-0000-0000-0000-000000000003', '00000000-0000-0000-0000-000000000003', 'https://www.instagram.com/p/C7OwUyhx9xV/media?size=l', 2, true),
	('30000000-0000-0000-0000-000000000003', '00000000-0000-0000-0000-000000000003', 'https://www.instagram.com/p/C7Ou-c8x7ar/media?size=l', 3, true),
	('40000000-0000-0000-0000-000000000003', '00000000-0000-0000-0000-000000000003', 'https://www.instagram.com/p/C7OgfQgO8tr/media?size=l', 4, true),
	('50000000-0000-0000-0000-000000000003', '00000000-0000-0000-0000-000000000003', 'https://www.instagram.com/p/CyMy8FCsbi1/media?size=l', 5, true),
	('00000000-0000-0000-0000-000000000004', '00000000-0000-0000-0000-000000000004', 'https://www.instagram.com/p/Cv7Y6_mPVHY/media?size=l', 0, true),
	('10000000-0000-0000-0000-000000000004', '00000000-0000-0000-0000-000000000004', 'https://www.instagram.com/p/C0R-B_uxm-4/media?size=l', 1, true),
	('20000000-0000-0000-0000-000000000004', '00000000-0000-0000-0000-000000000004', 'https://www.instagram.com/p/C6Aay_3sTXB/media?size=l', 2, true),
	('30000000-0000-0000-0000-000000000004', '00000000-0000-0000-0000-000000000004', 'https://www.instagram.com/p/CytB17DLxlt/media?size=l', 3, true),
	('40000000-0000-0000-0000-000000000004', '00000000-0000-0000-0000-000000000004', 'https://www.instagram.com/p/CxFoLUNOlZo/media?size=l', 4, true),
	('50000000-0000-0000-0000-000000000004', '00000000-0000-0000-0000-000000000004', 'https://www.instagram.com/p/Cx8Bm0nuQzX/media?size=l', 5, true),
	('00000000-0000-0000-0000-000000000005', '00000000-0000-0000-0000-000000000005', 'https://www.instagram.com/p/C7E4HWmxYCY/media?size=l', 0, true),
	('10000000-0000-0000-0000-000000000005', '00000000-0000-0000-0000-000000000005', 'https://www.instagram.com/p/C7ageT2R5mg/media?size=l', 1, true),
	('20000000-0000-0000-0000-000000000005', '00000000-0000-0000-0000-000000000005', 'https://www.instagram.com/p/C3XZXYYO-Ru/media?size=l', 2, true),
	('30000000-0000-0000-0000-000000000005', '00000000-0000-0000-0000-000000000005', 'https://www.instagram.com/p/C2nXfMCOAoR/media?size=l', 3, true),
	('40000000-0000-0000-0000-000000000005', '00000000-0000-0000-0000-000000000005', 'https://www.instagram.com/p/Clw7VbHvdiX/media?size=l', 4, true),
	('50000000-0000-0000-0000-000000000005', '00000000-0000-0000-0000-000000000005', 'https://www.instagram.com/p/CWQtkGcrYgz/media?size=l', 5, true),
	('00000000-0000-0000-0000-000000000006', '00000000-0000-0000-0000-000000000006', 'https://www.instagram.com/p/C8ckdKXPlzM/media?size=l', 0, true),
	('10000000-0000-0000-0000-000000000006', '00000000-0000-0000-0000-000000000006', 'https://www.instagram.com/p/CL3EFlSFMog/media?size=l', 1, true),
	('20000000-0000-0000-0000-000000000006', '00000000-0000-0000-0000-000000000006', 'https://www.instagram.com/p/C4-TVF3OJeD/media?size=l', 2, true),
	('30000000-0000-0000-0000-000000000006', '00000000-0000-0000-0000-000000000006', 'https://www.instagram.com/p/CPlhN3Xtsds/media?size=l', 3, true),
	('40000000-0000-0000-0000-000000000006', '00000000-0000-0000-0000-000000000006', 'https://www.instagram.com/p/CsMkmhivdw6/media?size=l', 4, true),
	('50000000-0000-0000-0000-000000000006', '00000000-0000-0000-0000-000000000006', 'https://www.instagram.com/p/CbloOf2ph-6/media?size=l', 5, true),
	('00000000-0000-0000-0000-000000000007', '00000000-0000-0000-0000-000000000007', 'https://www.instagram.com/p/Czvvh3PAbcg/media?size=l', 0, true),
	('10000000-0000-0000-0000-000000000007', '00000000-0000-0000-0000-000000000007', 'https://www.instagram.com/p/C2yqzmlgsCT/media?size=l', 1, true),
	('20000000-0000-0000-0000-000000000007', '00000000-0000-0000-0000-000000000007', 'https://www.instagram.com/p/C76jVdjRPw5/media?size=l', 2, true),
	('30000000-0000-0000-0000-000000000007', '00000000-0000-0000-0000-000000000007', 'https://www.instagram.com/p/C8IqQ1wx0nL/media?size=l', 3, true),
	('40000000-0000-0000-0000-000000000007', '00000000-0000-0000-0000-000000000007', 'https://www.instagram.com/p/C6mZJEbgmzM/media?size=l', 4, true),
	('50000000-0000-0000-0000-000000000007', '00000000-0000-0000-0000-000000000007', 'https://www.instagram.com/p/C84cMwSx0f7/media?size=l', 5, true),
	('00000000-0000-0000-0000-000000000008', '00000000-0000-0000-0000-000000000008', 'https://www.instagram.com/p/C8evOL2xjtn/media?size=l', 0, true),
	('10000000-0000-0000-0000-000000000008', '00000000-0000-0000-0000-000000000008', 'https://www.instagram.com/p/C8VZJJRxU5Y/media?size=l', 1, true),
	('20000000-0000-0000-0000-000000000008', '00000000-0000-0000-0000-000000000008', 'https://www.instagram.com/p/C7pqSLGxMsm/media?size=l', 2, true),
	('30000000-0000-0000-0000-000000000008', '00000000-0000-0000-0000-000000000008', 'https://www.instagram.com/p/C7ZOOomx0ut/media?size=l', 3, true),
	('40000000-0000-0000-0000-000000000008', '00000000-0000-0000-0000-000000000008', 'https://www.instagram.com/p/C6RT7DireZ1/media?size=l', 4, true),
	('50000000-0000-0000-0000-000000000008', '00000000-0000-0000-0000-000000000008', 'https://www.instagram.com/p/CScLuFuFzbi/media?size=l', 5, true),
	('00000000-0000-0000-0000-000000000009', '00000000-0000-0000-0000-000000000009', 'https://www.instagram.com/p/Cyns-rouX1i/media?size=l', 0, true),
	('10000000-0000-0000-0000-000000000009', '00000000-0000-0000-0000-000000000009', 'https://www.instagram.com/p/C5MgrDhJ4T-/media?size=l', 1, true),
	('20000000-0000-0000-0000-000000000009', '00000000-0000-0000-0000-000000000009', 'https://www.instagram.com/p/C877m_mSnSv/media?size=l', 2, true),
	('30000000-0000-0000-0000-000000000009', '00000000-0000-0000-0000-000000000009', 'https://www.instagram.com/p/C67T8FhpuyA/media?size=l', 3, true),
	('40000000-0000-0000-0000-000000000009', '00000000-0000-0000-0000-000000000009', 'https://www.instagram.com/p/C6cZSoyJYEF/media?size=l', 4, true),
	('50000000-0000-0000-0000-000000000009', '00000000-0000-0000-0000-000000000009', 'https://www.instagram.com/p/C6J61S4J-CN/media?size=l', 5, true),
	('00000000-0000-0000-0000-000000000010', '00000000-0000-0000-0000-000000000010', 'https://www.instagram.com/p/C8RysHrOn4E/media?size=l', 0, true),
	('10000000-0000-0000-0000-000000000010', '00000000-0000-0000-0000-000000000010', 'https://www.instagram.com/p/C5j9GFcuy8U/media?size=l', 1, true),
	('20000000-0000-0000-0000-000000000010', '00000000-0000-0000-0000-000000000010', 'https://www.instagram.com/p/C0C6ktEOHOU/media?size=l', 2, true),
	('30000000-0000-0000-0000-000000000010', '00000000-0000-0000-0000-000000000010', 'https://www.instagram.com/p/Cu0p4okOsXj/media?size=l', 3, true),
	('40000000-0000-0000-0000-000000000010', '00000000-0000-0000-0000-000000000010', 'https://www.instagram.com/p/CJ5LslhB9L3/media?size=l', 4, true),
	('50000000-0000-0000-0000-000000000010', '00000000-0000-0000-0000-000000000010', 'https://www.instagram.com/p/Cx53vFkODYD/media?size=l', 5, true),
	('00000000-0000-0000-0000-000000000011', '00000000-0000-0000-0000-000000000011', 'https://www.instagram.com/p/CF981zlHS8B/media?size=l', 0, true),
	('10000000-0000-0000-0000-000000000011', '00000000-0000-0000-0000-000000000011', 'https://www.instagram.com/p/C8hP5qMObBP/media?size=l', 1, true),
	('20000000-0000-0000-0000-000000000011', '00000000-0000-0000-0000-000000000011', 'https://www.instagram.com/p/C8Rx8rNOkO8/media?size=l', 2, true),
	('30000000-0000-0000-0000-000000000011', '00000000-0000-0000-0000-000000000011', 'https://www.instagram.com/p/C71oL9NO4sY/media?size=l', 3, true),
	('40000000-0000-0000-0000-000000000011', '00000000-0000-0000-0000-000000000011', 'https://www.instagram.com/p/C7KrFKovPCG/media?size=l', 4, true),
	('50000000-0000-0000-0000-000000000011', '00000000-0000-0000-0000-000000000011', 'https://www.instagram.com/p/C35ItPhOlXa/media?size=l', 5, true),
	('00000000-0000-0000-0000-000000000012', '00000000-0000-0000-0000-000000000012', 'https://www.instagram.com/p/Cm7i4O8go_e/media?size=l', 0, true),
	('10000000-0000-0000-0000-000000000012', '00000000-0000-0000-0000-000000000012', 'https://www.instagram.com/p/C5mYJTUR9W_/media?size=l', 1, true),
	('20000000-0000-0000-0000-000000000012', '00000000-0000-0000-0000-000000000012', 'https://www.instagram.com/p/Cqq0hwygVqA/media?size=l', 2, true),
	('30000000-0000-0000-0000-000000000012', '00000000-0000-0000-0000-000000000012', 'https://www.instagram.com/p/C301lgqgI6H/media?size=l', 3, true),
	('40000000-0000-0000-0000-000000000012', '00000000-0000-0000-0000-000000000012', 'https://www.instagram.com/p/CoYQC07gb8y/media?size=l', 4, true),
	('50000000-0000-0000-0000-000000000012', '00000000-0000-0000-0000-000000000012', 'https://www.instagram.com/p/ChBhrHggI_1/media?size=l', 5, true),
	('00000000-0000-0000-0000-000000000013', '00000000-0000-0000-0000-000000000013', 'https://www.instagram.com/p/Cup2az8v97E/media?size=l', 0, true),
	('10000000-0000-0000-0000-000000000013', '00000000-0000-0000-0000-000000000013', 'https://www.instagram.com/p/CIjuQWZjemG/media?size=l', 1, true),
	('20000000-0000-0000-0000-000000000013', '00000000-0000-0000-0000-000000000013', 'https://www.instagram.com/p/CLfaeQOj4N3/media?size=l', 2, true),
	('30000000-0000-0000-0000-000000000013', '00000000-0000-0000-0000-000000000013', 'https://www.instagram.com/p/CPD3E5CDxyF/media?size=l', 3, true),
	('40000000-0000-0000-0000-000000000013', '00000000-0000-0000-0000-000000000013', 'https://www.instagram.com/p/CX9vbI-vbtz/media?size=l', 4, true),
	('50000000-0000-0000-0000-000000000013', '00000000-0000-0000-0000-000000000013', 'https://www.instagram.com/p/CWfAwJhsQ7a/media?size=l', 5, true),
	('00000000-0000-0000-0000-000000000014', '00000000-0000-0000-0000-000000000014', 'https://www.instagram.com/p/CvfQxE5r6Zg/media?size=l', 0, true),
	('10000000-0000-0000-0000-000000000014', '00000000-0000-0000-0000-000000000014', 'https://www.instagram.com/p/CvfRCfQLKYH/media?size=l', 1, true),
	('20000000-0000-0000-0000-000000000014', '00000000-0000-0000-0000-000000000014', 'https://www.instagram.com/p/C1CmbWCRUgc/media?size=l', 2, true),
	('30000000-0000-0000-0000-000000000014', '00000000-0000-0000-0000-000000000014', 'https://www.instagram.com/p/CyVu3rzLmFM/media?size=l', 3, true),
	('40000000-0000-0000-0000-000000000014', '00000000-0000-0000-0000-000000000014', 'https://www.instagram.com/p/C2XLq_XOVpK/media?size=l', 4, true),
	('50000000-0000-0000-0000-000000000014', '00000000-0000-0000-0000-000000000014', 'https://www.instagram.com/p/C5hU1g0Ra6B/media?size=l', 5, true),
	('00000000-0000-0000-0000-000000000015', '00000000-0000-0000-0000-000000000015', 'https://www.instagram.com/p/B9A-52enLCv/media?size=l', 0, true),
	('10000000-0000-0000-0000-000000000015', '00000000-0000-0000-0000-000000000015', 'https://www.instagram.com/p/B9aC3XhnxDL/media?size=l', 1, true),
	('20000000-0000-0000-0000-000000000015', '00000000-0000-0000-0000-000000000015', 'https://www.instagram.com/p/B8r4XmiHzSP/media?size=l', 2, true),
	('30000000-0000-0000-0000-000000000015', '00000000-0000-0000-0000-000000000015', 'https://www.instagram.com/p/B9G3kbhHgBi/media?size=l', 3, true),
	('40000000-0000-0000-0000-000000000015', '00000000-0000-0000-0000-000000000015', 'https://www.instagram.com/p/B9-kj9Gn1UM/media?size=l', 4, true),
	('50000000-0000-0000-0000-000000000015', '00000000-0000-0000-0000-000000000015', 'https://www.instagram.com/p/B_xguCWHYsH/media?size=l', 5, true),
	('00000000-0000-0000-0000-000000000016', '00000000-0000-0000-0000-000000000016', 'https://www.instagram.com/p/C8uVAtwuQcI/media?size=l', 0, true),
	('10000000-0000-0000-0000-000000000016', '00000000-0000-0000-0000-000000000016', 'https://www.instagram.com/p/CmPBfPIOTap/media?size=l', 1, true),
	('20000000-0000-0000-0000-000000000016', '00000000-0000-0000-0000-000000000016', 'https://www.instagram.com/p/CfWmrJ1DQ1L/media?size=l', 2, true),
	('30000000-0000-0000-0000-000000000016', '00000000-0000-0000-0000-000000000016', 'https://www.instagram.com/p/CWv_kcyLdr_/media?size=l', 3, true),
	('40000000-0000-0000-0000-000000000016', '00000000-0000-0000-0000-000000000016', 'https://www.instagram.com/p/CMSamxzFNNq/media?size=l', 4, true),
	('50000000-0000-0000-0000-000000000016', '00000000-0000-0000-0000-000000000016', 'https://www.instagram.com/p/Cm7mk_vr6_Z/media?size=l', 5, true),
	('00000000-0000-0000-0000-000000000017', '00000000-0000-0000-0000-000000000017', 'https://www.instagram.com/p/C79gc8ARGWt/media?size=l', 0, true),
	('10000000-0000-0000-0000-000000000017', '00000000-0000-0000-0000-000000000017', 'https://www.instagram.com/p/C7XUdq6xV_8/media?size=l', 1, true),
	('20000000-0000-0000-0000-000000000017', '00000000-0000-0000-0000-000000000017', 'https://www.instagram.com/p/C3_MUXmOc-c/media?size=l', 2, true),
	('30000000-0000-0000-0000-000000000017', '00000000-0000-0000-0000-000000000017', 'https://www.instagram.com/p/Cvw2cu0uIUd/media?size=l', 3, true),
	('40000000-0000-0000-0000-000000000017', '00000000-0000-0000-0000-000000000017', 'https://www.instagram.com/p/Bfo1RfqAYDK/media?size=l', 4, true),
	('50000000-0000-0000-0000-000000000017', '00000000-0000-0000-0000-000000000017', 'https://www.instagram.com/p/BNVSRGAhCrM/media?size=l', 5, true),
	('00000000-0000-0000-0000-000000000018', '00000000-0000-0000-0000-000000000018', 'https://www.instagram.com/p/C2tDVkAOzsd/media?size=l', 0, true),
	('10000000-0000-0000-0000-000000000018', '00000000-0000-0000-0000-000000000018', 'https://www.instagram.com/p/C2QpJPsu0JQ/media?size=l', 1, true),
	('20000000-0000-0000-0000-000000000018', '00000000-0000-0000-0000-000000000018', 'https://www.instagram.com/p/CDAOVA0htSL/media?size=l', 2, true),
	('30000000-0000-0000-0000-000000000018', '00000000-0000-0000-0000-000000000018', 'https://www.instagram.com/p/CeugkSIu6zE/media?size=l', 3, true),
	('40000000-0000-0000-0000-000000000018', '00000000-0000-0000-0000-000000000018', 'https://www.instagram.com/p/CUoHPK0sTIM/media?size=l', 4, true),
	('50000000-0000-0000-0000-000000000018', '00000000-0000-0000-0000-000000000018', 'https://www.instagram.com/p/CLAgyMap3Ok/media?size=l', 5, true);

insert into "public"."interaction_status" ("id", "status") values
	(1, 'skip'),
	(2, 'like'),
	(3, 'remove'),
	(4, 'match'),
	(5, 'unmatch'),
	(6, 'review');

```

</details>

<details>
<summary><code>[auth.sms]</code></summary>

```js

[auth.sms]
# Allow/disallow new user signups via SMS to your project.
enable_signup = true
# If enabled, users need to confirm their phone number before signing in.
enable_confirmations = true
# Template for sending OTP to users
template = "Your code is {{ .Code }} ."
# Controls the minimum amount of time that must pass before sending another sms otp.
max_frequency = "5s"

```

</details>


<details>
<summary><code>[auth.sms.twilio_verify]</code></summary>

```js

[auth.sms.twilio_verify]
enabled = true
account_sid = "AC47a33f5d503564d18c2c053923b0c417"
message_service_sid = "VA3d24e98a705ffd8d179c783e31645837"
# DO NOT commit your Twilio auth token to git. Use environment variable substitution instead:
auth_token = "env(SUPABASE_AUTH_SMS_TWILIO_AUTH_TOKEN)"

```

</details>

<details>
<summary><code>[auth.sms.test_otp]</code></summary>

```js

[auth.sms.test_otp]
18761234567 = "111111"
10000000000 = "111111"
10000000001 = "111111"
10000000002 = "111111"
10000000003 = "111111"
10000000004 = "111111"
10000000005 = "111111"
10000000006 = "111111"
10000000007 = "111111"
10000000008 = "111111"
10000000009 = "111111"
10000000010 = "111111"
10000000011 = "111111"
10000000012 = "111111"
10000000014 = "111111"
10000000015 = "111111"
10000000016 = "111111"
10000000017 = "111111"
10000000018 = "111111"
10000000019 = "111111"
10000000020 = "111111"
10000000021 = "111111"
10000000022 = "111111"
10000000023 = "111111"
10000000024 = "111111"
10000000025 = "111111"

```

</details>


<details>
<summary><code>new user trigger function</code></summary>

```sql

create or replace function handle_new_user()
returns trigger
language plpgsql
security definer
as $$
begin
  insert into public.profiles(user_id, phone)
  values (new.id, new.phone)
  on conflict (phone)
  do update set user_id = new.id;
  return new;
end;
$$;

create trigger on_auth_user_created
after insert on auth.users for each row
execute function handle_new_user();

```

</details>


<details>
<summary><code>get_profile function</code></summary>

```sql

create or replace function get_profile()
returns table (
    id uuid,
    first_name text,
    last_name text,
    dob date,
    height_cm int,
    neighborhood text,
    latitude float8,
    longitude float8,
    max_distance_km int,
    min_age int,
    max_age int,
    phone text,
    children jsonb,
    family_plan jsonb,
    covid_vaccine jsonb,
    zodiac_sign jsonb,
    sexuality jsonb,
    gender jsonb,
    ethnicities jsonb,
    pets jsonb,
    pronouns jsonb,
    ethnicity_preferences jsonb,
    gender_preferences jsonb,
    answers jsonb,
    photos jsonb,
    avatar_url text
)
language plpgsql
security definer
as $$
declare profile_id uuid;
begin
  select profiles.id into profile_id
  from profiles where user_id = auth.uid();

  if profile_id is null then
    raise exception 'profile not found for user %', auth.uid();
  end if;

  return query
  select
    profiles.id,
    profiles.first_name,
    profiles.last_name,
    profiles.dob,
    profiles.height_cm,
    profiles.neighborhood,
    profiles.latitude,
    profiles.longitude,
    profiles.max_distance_km,
    profiles.min_age,
    profiles.max_age,
    profiles.phone,
    row_to_json(children.*)::jsonb as children,
    row_to_json(family_plans.*)::jsonb as family_plan,
    row_to_json(covid_vaccine.*)::jsonb as covid_vaccine,
    row_to_json(zodiac_signs.*)::jsonb as zodiac_sign,
    row_to_json(sexualities.*)::jsonb as sexuality,
    json_build_object('id', genders.id, 'name', genders.name)::jsonb as gender,
    (
      select coalesce(jsonb_agg(ethnicities.*), '[]'::jsonb) 
      from profile_ethnicities
      left join ethnicities on ethnicities.id = profile_ethnicities.ethnicity_id
      where profile_ethnicities.profile_id = profiles.id
    ) as ethnicities,
    (
      select coalesce(jsonb_agg(pets.*), '[]'::jsonb) 
      from profile_pets
      left join pets on pets.id = profile_pets.pet_id
      where profile_pets.profile_id = profiles.id
    ) as pets,
    (
      select coalesce(jsonb_agg(pronouns.*), '[]'::jsonb) 
      from profile_pronouns
      left join pronouns on pronouns.id = profile_pronouns.pronoun_id
      where profile_pronouns.profile_id = profiles.id
    ) as pronouns,
    (
      select coalesce(jsonb_agg(ethnicities.*), '[]'::jsonb) 
      from profile_ethnicity_preferences
      left join ethnicities on ethnicities.id = profile_ethnicity_preferences.ethnicity_id
      where profile_ethnicity_preferences.profile_id = profiles.id
    ) as ethnicity_preferences,
    (
      select coalesce(jsonb_agg(json_build_object('id', genders.id, 'name', genders.plural_name)), '[]'::jsonb) 
      from profile_gender_preferences
      left join genders on genders.id = profile_gender_preferences.gender_id
      where profile_gender_preferences.profile_id = profiles.id
    ) as gender_preferences,
    (
      select coalesce(jsonb_agg(json_build_object(
        'id', profile_answers.id,
        'answer_text', profile_answers.answer_text,
        'answer_order', profile_answers.answer_order,
        'prompt_id', profile_answers.prompt_id,
        'question', prompts.question
      ) order by profile_answers.answer_order), '[]'::jsonb)
      from profile_answers
      left join prompts on prompts.id = profile_answers.prompt_id
      where profile_answers.profile_id = profiles.id and profile_answers.is_active = true
    ) as answers,
    (
      select coalesce(jsonb_agg(json_build_object(
        'id', profile_photos.id,
        'photo_url', profile_photos.photo_url,
        'photo_order', profile_photos.photo_order
      ) order by profile_photos.photo_order), '[]'::jsonb)
      from profile_photos
      where profile_photos.profile_id = profiles.id and profile_photos.is_active = true
    ) as photos,
    (
      select photo_url
      from profile_photos
      where profile_photos.profile_id = profiles.id and profile_photos.is_active = true
      order by profile_photos.photo_order
      limit 1
    ) as avatar_url
    from profiles
    left join children on children.id = profiles.children_id
    left join family_plans on family_plans.id = profiles.family_plan_id
    left join covid_vaccine on covid_vaccine.id = profiles.covid_vaccine_id
    left join zodiac_signs on zodiac_signs.id = profiles.zodiac_sign_id
    left join sexualities on sexualities.id = profiles.sexuality_id
    left join genders on genders.id = profiles.gender_id
    where profiles.id = profile_id;
end;
$$;

```

</details>


<details>
<summary><code>update profile request</code></summary>

```json
{
    "first_name": "Javel",
    "last_name": null,
    "dob": "1995-12-25",
    "height_cm": 180,
    "neighborhood": "Montego Bay",
    "latitude": 18.4996348427899,
    "longitude": -77.9172923364458,
    "children": 1,
    "family_plan": 2,
    "covid_vaccine": 1,
    "zodiac_sign": 9,
    "sexuality": 1,
    "gender": 1,
    "ethnicities": [
        1
    ],
    "pets": [
        1,
        2
    ],
    "pronouns": [
        4,
        5,
        6
    ],
    "gender_preferences": [
        2
    ],
    "answers": [
        {
            "id": "00000000-0000-0000-0000-000000000000",
            "prompt_id": 1,
            "answer_text": "Est debitis esse et neque fugit qui sed porro incidunt internos!",
            "answer_order": 0
        },
        {
            "id": "10000000-0000-0000-0000-000000000000",
            "prompt_id": 2,
            "answer_text": "Qui eligendi nihil qui doloremque galisum ut maiores Quis.",
            "answer_order": 1
        },
        {
            "id": "20000000-0000-0000-0000-000000000000",
            "prompt_id": 3,
            "answer_text": "Facere qui veniam accusantium id dolorem omnis.",
            "answer_order": 2
        }
    ],
    "photos": [
        {
            "id": "00000000-0000-0000-0000-000000000000",
            "photo_url": "https://www.instagram.com/p/B0cV-XwB2ML/media?size=l",
            "photo_order": 0
        },
        {
            "id": "10000000-0000-0000-0000-000000000000",
            "photo_url": "https://www.instagram.com/p/BhFvO_Kh036/media?size=l",
            "photo_order": 1
        },
        {
            "id": "20000000-0000-0000-0000-000000000000",
            "photo_url": "https://www.instagram.com/p/Bb8jR-gj2SF/media?size=l",
            "photo_order": 2
        },
        {
            "id": "30000000-0000-0000-0000-000000000000",
            "photo_url": "https://www.instagram.com/p/DCrVMrnsdm-/media?size=l",
            "photo_order": 3
        },
        {
            "id": "40000000-0000-0000-0000-000000000000",
            "photo_url": "https://www.instagram.com/p/DCex002OCLP/media?size=l",
            "photo_order": 4
        },
        {
            "id": "50000000-0000-0000-0000-000000000000",
            "photo_url": "https://www.instagram.com/p/C_JHSSitBbA/media?size=l",
            "photo_order": 5
        }
    ]
}

```

</details>


<details>
<summary><code>update_profile function</code></summary>

```sql

create or replace function update_profile(
  first_name text default null,
  last_name text default null,
  dob date default null,
  height_cm integer default null,
  neighborhood text default null,
  latitude float8 default null,
  longitude float8 default null,
  children integer default null,
  family_plan integer default null,
  covid_vaccine integer default null,
  zodiac_sign integer default null,
  sexuality integer default null,
  gender integer default null,
  ethnicities integer[] default null,
  pets integer[] default null,
  pronouns integer[] default null,
  gender_preferences integer[] default null,
  answers jsonb default null,
  photos jsonb default null
)
returns void
language plpgsql
security definer
as $$
declare
  v_profile_id uuid;
  declare answer jsonb;
  declare existing_answer record;
  declare new_answer_id uuid;
  declare active_answer_ids uuid[] := '{}';
  declare photo jsonb;
  declare existing_photo record;
  declare new_photo_id uuid;
  declare active_photo_ids uuid[] := '{}';
begin

select profiles.id into v_profile_id
from profiles where user_id = auth.uid();

if v_profile_id is null then
  raise exception 'profile not found for user %', auth.uid();
end if;

update profiles
set
first_name = coalesce(update_profile.first_name, profiles.first_name),
last_name = update_profile.last_name,
dob = coalesce(update_profile.dob, profiles.dob),
height_cm = coalesce(update_profile.height_cm, profiles.height_cm),
neighborhood = coalesce(update_profile.neighborhood, profiles.neighborhood),
latitude = coalesce(update_profile.latitude, profiles.latitude),
longitude = coalesce(update_profile.longitude, profiles.longitude),
children_id = coalesce(update_profile.children, profiles.children_id),
family_plan_id = coalesce(update_profile.family_plan, profiles.family_plan_id),
covid_vaccine_id = coalesce(update_profile.covid_vaccine, profiles.covid_vaccine_id),
zodiac_sign_id = coalesce(update_profile.zodiac_sign, profiles.zodiac_sign_id),
sexuality_id = coalesce(update_profile.sexuality, profiles.sexuality_id),
gender_id = coalesce(update_profile.gender, profiles.gender_id),
updated_at = now()
where id = v_profile_id;

if ethnicities is not null then
  delete from profile_ethnicities
  where profile_ethnicities.profile_id = v_profile_id;  

  insert into profile_ethnicities (profile_id, ethnicity_id)
  select v_profile_id, unnest(ethnicities);  
end if;

if pets is not null then
  delete from profile_pets
  where profile_pets.profile_id = v_profile_id;

  insert into profile_pets (profile_id, pet_id)
  select v_profile_id, unnest(pets);
end if;

if pronouns is not null then
  delete from profile_pronouns
  where profile_pronouns.profile_id = v_profile_id;

  insert into profile_pronouns (profile_id, pronoun_id)
  select v_profile_id, unnest(pronouns);
end if;

if gender_preferences is not null then
  delete from profile_gender_preferences
  where profile_id = v_profile_id;

  insert into profile_gender_preferences (profile_id, gender_id)
  select v_profile_id, unnest(gender_preferences);
end if;


if answers is not null then
  for answer in (select * from jsonb_array_elements(update_profile.answers))
  loop
    if answer->>'id' is not null then
      select id, answer_text, prompt_id, is_active into existing_answer
      from profile_answers
      where id = (answer->>'id')::uuid and profile_answers.profile_id = v_profile_id;

      if found then
        if existing_answer.answer_text is distinct from (answer->>'answer_text') or existing_answer.prompt_id is distinct from (answer->>'prompt_id')::integer then
          update profile_answers
          set is_active = false
          where id = existing_answer.id;

          new_answer_id := gen_random_uuid();
          insert into profile_answers (id, profile_id, answer_text, prompt_id, answer_order, is_active)
          values (
            new_answer_id,
            v_profile_id,
            (answer->>'answer_text'),
            (answer->>'prompt_id')::integer,
            (answer->>'answer_order')::integer,
            true
          );
          active_answer_ids := array_append(active_answer_ids, new_answer_id);
        else 
          update profile_answers
          set 
            is_active = true,
            answer_order = (answer->>'answer_order')::integer
          where id = existing_answer.id;
          active_answer_ids := array_append(active_answer_ids, existing_answer.id);
        end if;
      end if;
    else
      new_answer_id := gen_random_uuid();
      insert into profile_answers (id, profile_id, answer_text, prompt_id, answer_order, is_active)
      values (
        new_answer_id,
        v_profile_id,
        (answer->>'answer_text'),
        (answer->>'prompt_id')::integer,
        (answer->>'answer_order')::integer,
        true
      );
      active_answer_ids := array_append(active_answer_ids, new_answer_id);

    end if;
  end loop;
  if jsonb_array_length(update_profile.answers) = 0 then
    update profile_answers
    set is_active = false
    where profile_answers.profile_id = v_profile_id and is_active = true;
  else
    update profile_answers
    set is_active = false
    where profile_answers.profile_id = v_profile_id
    and is_active = true
    and id <> all (active_answer_ids);
  end if;
end if;

if photos is not null then
  for photo in (select * from jsonb_array_elements(update_profile.photos))
  loop
    if photo->>'id' is not null then
      select id, photo_url, is_active into existing_photo
      from profile_photos
      where id = (photo->>'id')::uuid and profile_photos.profile_id = v_profile_id;

      if found then
        if existing_photo.photo_url is distinct from (photo->>'photo_url') then
          update profile_photos
          set is_active = false
          where id = existing_photo.id;

          new_photo_id := gen_random_uuid();
          insert into profile_photos (id, profile_id, photo_url, photo_order, is_active)
          values (
            new_photo_id,
            v_profile_id,
            (photo->>'photo_url'),
            (photo->>'photo_order')::integer,
            true
          );
          active_photo_ids := array_append(active_photo_ids, new_photo_id);
        else 
          update profile_photos
          set 
            is_active = true,
            photo_order = (photo->>'photo_order')::integer
          where id = existing_photo.id;
          active_photo_ids := array_append(active_photo_ids, existing_photo.id);
        end if;
      end if;
    else
      new_photo_id := gen_random_uuid();
      insert into profile_photos (id, profile_id, photo_url, photo_order, is_active)
      values (
        new_photo_id,
        v_profile_id,
        (photo->>'photo_url'),
        (photo->>'photo_order')::integer,
        true
      );
      active_photo_ids := array_append(active_photo_ids, new_photo_id);

    end if;
  end loop;
  if jsonb_array_length(update_profile.photos) = 0 then
    update profile_photos
    set is_active = false
    where profile_photos.profile_id = v_profile_id and is_active = true;
  else
    update profile_photos
    set is_active = false
    where profile_photos.profile_id = v_profile_id
    and is_active = true
    and id <> all (active_photo_ids);
  end if;
end if;
end;
$$;

```

</details>


<details>
<summary><code>dating preferences functions</code></summary>

```sql

create or replace function update_gender_preferences(
  gender_preferences integer[]
)
returns void
language plpgsql
security definer
as $$
declare
  v_profile_id uuid;
begin

select id into v_profile_id
from profiles where user_id = auth.uid();

if v_profile_id is null then
  raise exception 'profile not found for user %', auth.uid();
end if;

delete from profile_gender_preferences
where profile_id = v_profile_id;

insert into profile_gender_preferences (profile_id, gender_id)
select v_profile_id, unnest(gender_preferences);

end;
$$;

create or replace function update_location(
  latitude float8,
  longitude float8,
  neighborhood text
)
returns void
language plpgsql
security definer
as $$
declare
  profile_id uuid;
begin

select id into profile_id
from profiles where user_id = auth.uid();

if profile_id is null then
  raise exception 'profile not found for user %', auth.uid();
end if;

update profiles
set 
  latitude = update_location.latitude, 
  longitude = update_location.longitude, 
  neighborhood = update_location.neighborhood, 
  updated_at = now()
where id = profile_id;

end;
$$;

create or replace function update_distance(
  distance integer
)
returns void
language plpgsql
security definer
as $$
declare
  profile_id uuid;
begin

select id into profile_id
from profiles where user_id = auth.uid();

if profile_id is null then
  raise exception 'profile not found for user %', auth.uid();
end if;

update profiles
set 
  max_distance_km = distance, 
  updated_at = now()
where id = profile_id;

end;
$$;

create or replace function update_age_range(
  min_age integer,
  max_age integer
)
returns void
language plpgsql
security definer
as $$
declare
  profile_id uuid;
begin

select id into profile_id
from profiles where user_id = auth.uid();

if profile_id is null then
  raise exception 'profile not found for user %', auth.uid();
end if;

update profiles
set 
  min_age = update_age_range.min_age, 
  max_age = update_age_range.max_age, 
  updated_at = now()
where id = profile_id;

end;
$$;

create or replace function update_ethnicity_preferences(
  ethnicity_preferences integer[]
)
returns void
language plpgsql
security definer
as $$
declare
  v_profile_id uuid;
begin

select id into v_profile_id
from profiles where user_id = auth.uid();

if v_profile_id is null then
  raise exception 'profile not found for user %', auth.uid();
end if;

delete from profile_ethnicity_preferences
where profile_id = v_profile_id;

insert into profile_ethnicity_preferences (profile_id, ethnicity_id)
select v_profile_id, unnest(ethnicity_preferences);
end;
$$;

```

</details>

<details>
<summary><code>test locations</code></summary>

```
18.4996348427899 -77.9172923364458 Montego Bay
17.9374623588942 -76.779836513002 Kingston

```

</details>

<details>
<summary><code>get_profiles function</code></summary>

```sql

create or replace function get_profiles(
  page_size integer
)
returns table (
  id uuid,
  first_name text,
  age integer,
  height_cm integer,
  neighborhood text,
  children text,
  family_plan text,
  covid_vaccine text,
  zodiac_sign text,
  gender text, 
  sexuality text, 
  ethnicities text[], 
  pets text[], 
  pronouns text[], 
  photos jsonb, 
  answers jsonb
)
language plpgsql
security definer
as $$
declare
  v_profile_id uuid;
  current_profile profiles%rowtype;
  like_status int := 2;
  match_status int := 4;
  unmatch_status int := 5;
  review_status int := 6;
begin

select profiles.id into v_profile_id 
from profiles where profiles.user_id = auth.uid();
  
if v_profile_id is null then
  raise exception 'profile not found for user %', auth.uid();
end if;

select * into current_profile 
from profiles where profiles.id = v_profile_id;

return query
with filtered_profiles as (
  select p.*
  from profiles p
  where p.id <> v_profile_id
    and extract(year from age(p.dob)) between current_profile.min_age and current_profile.max_age
    and extract(year from age(current_profile.dob)) between p.min_age and p.max_age
    and st_dwithin(p.location, current_profile.location, current_profile.max_distance_km * 1000)
)
select
  p.id,
  p.first_name,
  extract(year from age(p.dob))::int as age,
  p.height_cm,
  p.neighborhood,
  children.name as children,
  family_plans.name as family_plan,
  covid_vaccine.name as covid_vaccine,
  zodiac_signs.name as zodiac_sign,
  genders.name as gender,
  sexualities.name as sexuality,
  (
    select coalesce(array_agg(ethnicities.name), '{}')
    from profile_ethnicities
    left join ethnicities on ethnicities.id = profile_ethnicities.ethnicity_id
    where profile_ethnicities.profile_id = p.id
  ) as ethnicities,
  (
    select coalesce(array_agg(pets.name), '{}')
    from profile_pets
    left join pets on pets.id = profile_pets.pet_id
    where profile_pets.profile_id = p.id
  ) as pets,
  (
    select coalesce(array_agg(pronouns.name), '{}')
    from profile_pronouns
    left join pronouns on pronouns.id = profile_pronouns.pronoun_id
    where profile_pronouns.profile_id = p.id
  ) as pronouns,
  (
    select coalesce(jsonb_agg(json_build_object(
      'id', profile_photos.id, 
      'photo_url', profile_photos.photo_url, 
      'photo_order', profile_photos.photo_order
    ) order by profile_photos.photo_order)::jsonb, '[]'::jsonb ) 
    from profile_photos
    where profile_photos.profile_id = p.id and profile_photos.is_active = true
  ) as photos,
  (
    select coalesce(jsonb_agg(json_build_object(
      'id', profile_answers.id, 
      'answer_text', profile_answers.answer_text, 
      'answer_order', profile_answers.answer_order, 
      'question', prompts.question
    ) order by profile_answers.answer_order)::jsonb, '[]'::jsonb ) 
    from profile_answers
    left join prompts on prompts.id = profile_answers.prompt_id
    where profile_answers.profile_id = p.id and profile_answers.is_active = true
  ) as answers
from filtered_profiles p
left join children on children.id = p.children_id
left join family_plans on family_plans.id = p.family_plan_id
left join covid_vaccine on covid_vaccine.id = p.covid_vaccine_id
left join zodiac_signs on zodiac_signs.id = p.zodiac_sign_id
left join genders on genders.id = p.gender_id
left join sexualities on sexualities.id = p.sexuality_id
left join profile_gender_preferences pgp_cp on pgp_cp.profile_id = v_profile_id
left join profile_gender_preferences pgp_p on pgp_p.profile_id = p.id
left join profile_ethnicity_preferences pep_cp on pep_cp.profile_id = v_profile_id
left join profile_ethnicity_preferences pep_p on pep_p.profile_id = p.id
left join interactions i_cp on i_cp.target_id = p.id and i_cp.actor_id = v_profile_id
left join interactions i_p on i_p.target_id = v_profile_id and i_p.actor_id = p.id
where (p.gender_id = pgp_cp.gender_id or pgp_cp.gender_id is null) 
  and (current_profile.gender_id = pgp_p.gender_id or pgp_p.gender_id is null)
  and (pep_cp.ethnicity_id in (
    select profile_ethnicities.ethnicity_id 
    from profile_ethnicities
    where profile_ethnicities.profile_id = p.id
  ) or pep_cp.ethnicity_id is null)
  and (pep_p.ethnicity_id in (
    select profile_ethnicities.ethnicity_id
    from profile_ethnicities
    where profile_ethnicities.profile_id = v_profile_id
  ) or pep_p.ethnicity_id is null)
  and (i_cp.status_id is null or i_cp.status_id in (review_status, unmatch_status))
  and (i_p.status_id is null or i_p.status_id not in (like_status, match_status))
limit get_profiles.page_size;
end;
$$;

```

</details>

<details>
<summary><code>postgis</code></summary>

```sql

create extension postgis with schema "extensions";

alter table profiles
add column location geography
generated always as (st_point(longitude, latitude))
stored;

create index profiles_geo_index
on public.profiles
using gist (location);

```

</details>

<details>
<summary><code>skip_profile function</code></summary>

```sql

create or replace function skip_profile(
  profile uuid
)
returns uuid
language plpgsql
security definer
as $$
declare
  actor uuid;
  interaction_id uuid;
  skip_status int := 1;
  review_status int := 6;
  like_status int := 2;
begin

select profiles.id into actor
from profiles where profiles.user_id = auth.uid();

if actor is null then
  raise exception 'profile not found user %', auth.uid();
end if;

select interactions.id into interaction_id
from interactions
where interactions.actor_id = actor 
  and interactions.target_id = profile
  and interactions.status_id in (skip_status, review_status, like_status);

if found then
  update interactions
  set status_id = skip_status,
      updated_at = now(),
      updated_by = actor,
      photo_id = null,
      answer_id = null
  where interactions.id = interaction_id;

  return interaction_id;
end if;

insert into interactions (actor_id, target_id, updated_by, status_id)
values (actor, profile, actor, skip_status)
returning interactions.id into interaction_id;

return interaction_id;
end;
$$;

```

</details>


<details>
<summary><code>review_profile function</code></summary>

```sql

create or replace function review_profiles()
returns void
language plpgsql
security definer
as $$
declare
  actor uuid;
  loc geography;
  max_distance int;
  skip_status int := 1;
  review_status int := 6;
begin

select profiles.id into actor
from profiles where profiles.user_id = auth.uid();

if actor is null then
  raise exception 'profile not found for user %', auth.uid();
end if;

select location, max_distance_km into loc, max_distance
from profiles
where id = actor;

update interactions
set status_id = review_status, updated_at = now()
where actor_id = actor
  and status_id = skip_status
  and st_dwithin(
    (select location from profiles where profiles.id = interactions.target_id),
    loc,
    max_distance * 1000
  );
end;
$$;

```

</details>


<details>
<summary><code>like_profile function</code></summary>

```sql

create or replace function like_profile(
  profile uuid,
  photo uuid default null,
  answer uuid default null
)
returns uuid
language plpgsql
security definer
as $$
declare
  actor uuid;
  interaction_id uuid;
  skip_status int := 1;
  review_status int := 6;
  like_status int := 2;
begin

select profiles.id into actor
from profiles where profiles.user_id = auth.uid();

if actor is null then
  raise exception 'profile not found for user %', auth.uid() ;
end if;

select interactions.id into interaction_id
from interactions
where interactions.actor_id = actor 
  and interactions.target_id = profile
  and interactions.status_id in (skip_status, review_status, like_status);

if found then
  update interactions
  set status_id = like_status,
      updated_at = now(),
      photo_id = photo,
      answer_id = answer
  where interactions.id = interaction_id;

  return interaction_id;
end if;

insert into interactions (actor_id, target_id, updated_by, status_id, photo_id, answer_id)
values (actor, profile, actor, like_status, photo, answer)
returning interactions.id into interaction_id;

return interaction_id;
end;
$$;

```

</details>


<details>
<summary><code>get_likes function</code></summary>

```sql

create or replace function get_likes()
returns table (
  id uuid,
  photo_url text,
  answer_text text,
  question text,
  profile jsonb
)
language plpgsql
security definer
as $$
declare 
  v_profile_id uuid;
  like_status int := 2;
begin
  
select profiles.id into v_profile_id
from profiles where profiles.user_id = auth.uid();

if v_profile_id is null then
  raise exception 'profile not found for user %', auth.uid();
end if;

return query
select 
  i.id,
  profile_photos.photo_url,
  profile_answers.answer_text,
  prompts.question,
  (select jsonb_build_object (
    'id', p.id,
    'first_name', p.first_name,
    'age', extract(year from age(p.dob))::int,
    'height_cm', p.height_cm,
    'neighborhood', p.neighborhood,
    'children', children.name,
    'family_plan', family_plans.name,
    'covid_vaccine', covid_vaccine.name,
    'zodiac_sign', zodiac_signs.name,
    'gender', genders.name,
    'sexuality', sexualities.name,
    'ethnicities', (
      select coalesce(array_agg(ethnicities.name), '{}')
      from profile_ethnicities
      left join ethnicities on ethnicities.id = profile_ethnicities.ethnicity_id
      where profile_ethnicities.profile_id = p.id
    ),
    'pets', (
      select coalesce(array_agg(pets.name), '{}')
      from profile_pets
      left join pets on pets.id = profile_pets.pet_id
      where profile_pets.profile_id = p.id
    ),
    'pronouns', (
      select coalesce(array_agg(pronouns.name), '{}')
      from profile_pronouns
      left join pronouns on pronouns.id = profile_pronouns.pronoun_id
      where profile_pronouns.profile_id = p.id
    ),
    'photos', (
      select coalesce(jsonb_agg(json_build_object(
        'id', profile_photos.id, 
        'photo_url', profile_photos.photo_url, 
        'photo_order', profile_photos.photo_order
      ) order by profile_photos.photo_order)::jsonb, '{}' ) 
      from profile_photos
      where profile_photos.profile_id = p.id and profile_photos.is_active = true
    ),
    'answers', (
      select coalesce(jsonb_agg(json_build_object(
        'id', profile_answers.id, 
        'answer_text', profile_answers.answer_text, 
        'answer_order', profile_answers.answer_order, 
        'question', prompts.question
      ) order by profile_answers.answer_order)::jsonb, '{}' ) 
      from profile_answers
      left join prompts on prompts.id = profile_answers.prompt_id
      where profile_answers.profile_id = p.id and profile_answers.is_active = true
    )
  )) as profile
from interactions i
join profiles p on p.id = i.actor_id
left join profile_photos on profile_photos.id = i.photo_id
left join profile_answers on profile_answers.id = i.answer_id
left join prompts on prompts.id = profile_answers.prompt_id
left join children on children.id = p.children_id
left join family_plans on family_plans.id = p.family_plan_id
left join covid_vaccine on covid_vaccine.id = p.covid_vaccine_id
left join zodiac_signs on zodiac_signs.id = p.zodiac_sign_id
left join genders on genders.id = p.gender_id
left join sexualities on sexualities.id = p.sexuality_id
where i.status_id = like_status
  and i.target_id = v_profile_id
order by i.created_at desc;
end;
$$;

```

</details>


<details>
<summary><code>remove_like function</code></summary>

```sql

create or replace function remove_like(
  interaction uuid
)
returns void
language plpgsql
security definer
as $$
declare
  v_profile_id uuid;
  interaction_id uuid;
  status int;
  target uuid;
  like_status int := 2;
  remove_status int := 3;
begin

select profiles.id into v_profile_id
from profiles where profiles.user_id = auth.uid();

if v_profile_id is null then
  raise exception 'profile not found for user %', auth.uid();
end if;

select id, status_id, target_id into interaction_id, status, target
from interactions
where id = interaction;

if not found then
  raise exception 'interaction % not found', interaction;
end if;

if status != like_status then
  raise exception 'interaction % is not a like', interaction;
end if; 

if target != v_profile_id then
  raise exception 'unauthorized access to interaction % by user %', interaction, auth.uid();
end if;

update interactions
set status_id = remove_status, updated_at = now()
where id = interaction; 
end;
$$;

```

</details>


<details>
<summary><code>enable http extension</code></summary>

```sql

create extension http with schema extensions;

```

</details>



<details>
<summary><code>supabase vault secrets</code></summary>

```sql
select vault.create_secret('***', 'sendbird_app_id', 'Sendbird application id');
select vault.create_secret('***', 'sendbird_api_token', 'Sendbird api token');

```

</details>

</details>


<details>
<summary><code>custom chat schema</code></summary>

```sql

create schema chat

```

</details>


<details>
<summary><code>create_channel function</code></summary>

```sql

create or replace function chat.create_channel(
  channel uuid,
  user1 uuid,
  user2 uuid
)
returns void
language plpgsql
as $$
declare
  sendbird_app_id text;
  sendbird_api_token text;
  sendbird_api_url text;
  sendbird_status int;
  sendbird_content jsonb;
begin
  select decrypted_secret into sendbird_app_id
  from vault.decrypted_secrets
  where name = 'sendbird_app_id';

  select decrypted_secret into sendbird_api_token
  from vault.decrypted_secrets
  where name = 'sendbird_api_token';

  sendbird_api_url := 'https://api-' || sendbird_app_id || '.sendbird.com/v3/group_channels/';

  select status, content::jsonb into sendbird_status, sendbird_content
  from http((
    'POST',
    sendbird_api_url,
    array[http_header('Api-Token',sendbird_api_token)],
    'application/json',
    json_build_object(
      'user_ids', array[user1::text, user2::text],
      'channel_url', channel
    )::text
  )::http_request);

  if sendbird_status != 200 then
      if (sendbird_content->>'code')::int != 400202 then
        raise exception 'sendbird error: %', sendbird_content;
      end if;
    end if;
end;
$$;

```

</details>

<details>
<summary><code>delete_channel function</code></summary>

```sql

create or replace function chat.delete_channel(
  channel uuid
)
returns void
language plpgsql
as $$
declare
  sendbird_app_id text;
  sendbird_api_token text;
  sendbird_api_url text;
  sendbird_status int;
  sendbird_content jsonb;
begin
  select decrypted_secret into sendbird_app_id
  from vault.decrypted_secrets
  where name = 'sendbird_app_id';

  select decrypted_secret into sendbird_api_token
  from vault.decrypted_secrets
  where name = 'sendbird_api_token';

  sendbird_api_url := 'https://api-' || sendbird_app_id || '.sendbird.com/v3/group_channels/' || channel;

  select status, content::jsonb into sendbird_status, sendbird_content
  from http((
    'DELETE',
    sendbird_api_url,
    array[http_header('Api-Token',sendbird_api_token)],
    'application/json',
    null
  )::http_request);

  if sendbird_status != 200 then
    raise exception 'sendbird error: %', sendbird_content;
  end if;
end;
$$;

```

</details>

<details>
<summary><code>match function</code></summary>

```sql

create or replace function match(
  interaction uuid
)
returns void
language plpgsql
security definer
as $$
declare
  v_profile_id uuid;
  actor uuid;
  target uuid;
  interaction_id uuid;
  status int;
  like_status int := 2;
  remove_status int := 3;
  match_status int := 4;
begin

select profiles.id into v_profile_id
from profiles where profiles.user_id = auth.uid();

if v_profile_id is null then
  raise exception 'profile not found for user %', auth.uid() ;
end if;

select id, status_id, actor_id, target_id into interaction_id, status, actor, target
from interactions
where id = interaction;

if not found then
  raise exception 'interaction % not found', interaction;
end if;

if status not in (like_status, remove_status) then
  raise exception 'interaction % is not a like or remove', interaction;
end if; 

if target != v_profile_id then
  raise exception 'unauthorized access to interaction % by user %', interaction, auth.uid();
end if;

perform chat.create_channel(interaction_id, actor, target);

update interactions
set status_id = match_status, updated_at = now(), updated_by = v_profile_id
where id = interaction; 
end;
$$;

```

</details>

<details>
<summary><code>unmatch function</code></summary>

```sql

create or replace function unmatch(
  interaction uuid
)
returns void
language plpgsql
security definer
as $$
declare
  v_profile_id uuid;
  interaction_id uuid;
  status int;
  actor uuid;
  target uuid;
  match_status int := 4;
  unmatch_status int := 5;
begin

select profiles.id into v_profile_id
from profiles where profiles.user_id = auth.uid();

if v_profile_id is null then
  raise exception 'profile not found for user %', auth.uid() ;
end if;

select id, status_id, actor_id, target_id into interaction_id, status, actor, target
from interactions
where id = interaction;

if not found then
  raise exception 'interaction % not found', interaction;
end if;

if status != match_status then
  raise exception 'interaction % is not a match', interaction;
end if; 

if v_profile_id not in (actor, target) then
  raise exception 'unauthorized access to interaction % by user %', interaction, auth.uid();
end if;

perform chat.delete_channel(interaction_id);

update interactions
set status_id = unmatch_status, updated_at = now(), updated_by = v_profile_id
where id = interaction; 
end;
$$;


```

</details>

<details>
<summary><code>policies</code></summary>

```sql

create policy "select_children_public"
on "public"."children"
as permissive
for select
to public
using (true);

create policy "select_family_plans_public"
on "public"."family_plans"
as permissive
for select
to public
using (true);

create policy "select_covid_vaccine_public"
on "public"."covid_vaccine"
as permissive
for select
to public
using (true);


create policy "select_zodiac_signs_public"
on "public"."zodiac_signs"
as permissive
for select
to public
using (true);

create policy "select_genders_public"
on "public"."genders"
as permissive
for select
to public
using (true);

create policy "select_sexualities_public"
on "public"."sexualities"
as permissive
for select
to public
using (true);


create policy "select_ethnicities_public"
on "public"."ethnicities"
as permissive
for select
to public
using (true);

create policy "select_pronouns_public"
on "public"."pronouns"
as permissive
for select
to public
using (true);

create policy "select_pets_public"
on "public"."pets"
as permissive
for select
to public
using (true);

create policy "select_prompts_public"
on "public"."prompts"
as permissive
for select
to public
using (true);

```

</details>


<details>
<summary><code>storage</code></summary>

```sql

insert into storage.buckets (id, name, public) values ('profiles', 'profiles', true);

create policy "insert_profiles_bucket_authenticated"
on storage.objects for insert to authenticated with check (
    bucket_id = 'profiles'
);

```

</details>

<details>
<summary><code>ip address update (local development)</code></summary>

```sql
update profile_photos
set photo_url = replace(photo_url, 'http://192.168.1.199:54321', 'http://192.168.1.224:54321')
where photo_url like 'http://192.168.1.199:54321%';

```

</details>

### Postman

<details>
<summary><code>verify otp request script</code></summary>

```js
var jsonData = pm.response.json();
pm.collectionVariables.set("token", jsonData.access_token);
```

</details>

<details>
<summary><code>update dating preferences requests</code></summary>

```
curl --location 'http://127.0.0.1:54321/rest/v1/rpc/update_gender_preferences' \
--header 'Content-Type: application/json' \
--data '{
    "gender_preferences": [
        2
    ]
}'

curl --location 'http://127.0.0.1:54321/rest/v1/rpc/update_location' \
--header 'Content-Type: application/json' \
--data '{
    "neighborhood": "Montego Bay",
    "latitude": 18.4996348427899,
    "longitude": -77.9172923364458
}'

curl --location 'http://127.0.0.1:54321/rest/v1/rpc/update_distance' \
--header 'Content-Type: application/json' \
--data '{
    "distance": 160
}'

curl --location 'http://127.0.0.1:54321/rest/v1/rpc/update_age_range' \
--header 'Content-Type: application/json' \
--data '{
    "min_age": 18,
    "max_age": 100
}'

curl --location 'http://127.0.0.1:54321/rest/v1/rpc/update_ethnicity_preferences' \
--header 'Content-Type: application/json' \
--data '{
    "ethnicity_preferences": [
        
    ]
}'
```

</details>

<details>
<summary><code>get_profiles request</code></summary>

```
curl --location --request GET 'http://127.0.0.1:54321/rest/v1/rpc/get_profiles' \
--header 'Content-Type: application/json' \
--data '{
    "page_size": 10
}'
```

</details>


### React Native

<details>
<summary><code>VideoBackground component</code></summary>

```js
import { useVideoPlayer, VideoSource, VideoView } from "expo-video";
import { FC } from "react";
import { View } from "react-native";

interface Props {
  source: VideoSource;
  children?: React.ReactNode;
}

export const VideoBackground: FC<Props> = ({ source, children }) => {
  const player = useVideoPlayer(source, (player) => {
    player.loop = true;
    player.play();
  });

  return (
    <View className="flex-1">
      <View className="absolute top-0 right-0 bottom-0 left-0">
        <VideoView className="flex-1" player={player} contentFit="cover" />
        <View className="absolute top-0 right-0 bottom-0 left-0">
          {children}
        </View>
      </View>
    </View>
  );
};

```

</details>

<details>
<summary><code>Nativewind cssInterops</code></summary>

```js
cssInterop(VideoView, { className: { target: "style" } });
cssInterop(Ionicons, { className: { target: "style" } });

```

</details>

<details>
<summary><code>eslint-import-resolver-typescript</code></summary>

```js
// https://docs.expo.dev/guides/using-eslint/
module.exports = {
  extends: "expo",
  ignorePatterns: ["/dist/*"],
  plugins: ["import"],
  rules: {
    "import/no-unresolved": "error",
  },
  settings: {
    "import/parsers": {
      "@typescript-eslint/parser": [".ts", ".tsx"],
    },
    "import/resolver": {
      typescript: {
        alwaysTryTypes: true,
        project: "./",
      },
    },
  },
};
```
</details>


<details>
<summary><code>metro.config.js</code></summary>

```js
const { getDefaultConfig } = require("expo/metro-config");
const { withNativeWind } = require("nativewind/metro");

const config = getDefaultConfig(__dirname);

const { transformer, resolver } = config;

config.transformer = {
  ...transformer,
  babelTransformerPath: require.resolve("react-native-svg-transformer/expo"),
};
config.resolver = {
  ...resolver,
  assetExts: resolver.assetExts.filter((ext) => ext !== "svg"),
  sourceExts: [...resolver.sourceExts, "svg"],
};

module.exports = withNativeWind(config, { input: "./global.css" });

```
</details>

<details>
<summary><code>useFonts</code></summary>

```js
  const [loaded, error] = useFonts(fonts);

  useEffect(() => {
    if (loaded || error) {
      SplashScreen.hideAsync();
    }
  }, [loaded, error]);

  if (!loaded && !error) {
    return null;
  }
```
</details>

<details>
<summary><code>Fab component</code></summary>

```js
import { cn } from "@/utils/cn";
import { Ionicons } from "@expo/vector-icons";
import React, { FC } from "react";
import { ActivityIndicator, Pressable, View } from "react-native";

interface Props {
  disabled?: boolean;
  onPress?: () => void;
  loading?: boolean;
  iconName?: keyof typeof Ionicons.glyphMap;
  className?: string;
  iconClassName?: string;
  loaderClassName?: string;
}

export const Fab: FC<Props> = ({
  disabled = false,
  onPress,
  loading = false,
  iconName = "chevron-forward",
  className,
  iconClassName,
  loaderClassName,
}) => {
  return (
    <Pressable
      className={cn(
        "h-16 aspect-square rounded-full justify-center items-center bg-fuchsia-900",
        {
          "bg-neutral-200": disabled && !loading,
          "opacity-50": disabled,
        },
        className
      )}
      onPress={onPress}
      disabled={disabled}
    >
      {loading ? (
        <ActivityIndicator className={cn(" text-white", loaderClassName)} />
      ) : (
        <View
          className={cn(
            "text-white",
            { "text-neutral-400": disabled },
            iconClassName
          )}
        >
          <Ionicons
            name={iconName}
            className={cn(
              "text-2xl text-white",
              { "text-neutral-400": disabled },
              iconClassName
            )}
          />
        </View>
      )}
    </Pressable>
  );
};


```

</details>


<details>
<summary><code>phone number validation</code></summary>

```js
  const isValid = useMemo(() => {
    return /^\+[1-9]\d{1,14}$/.test(phone);
  }, [phone]);

```
</details>

<details>
<summary><code>Auth Context Provider</code></summary>

```js
import { supabase } from "@/lib/supabase";
import { Session } from "@supabase/supabase-js";
import {
  PropsWithChildren,
  createContext,
  useContext,
  useEffect,
  useState,
} from "react";

type AuthContextType = {
  session: Session | null;
  isLoading: boolean;
};

const AuthContext = createContext<AuthContextType>({
  session: null,
  isLoading: true,
});

export const AuthProvider = ({ children }: PropsWithChildren) => {
  const [session, setSession] = useState<Session | null>(null);
  const [isLoading, setIsLoading] = useState(true);

  useEffect(() => {
    supabase.auth.getSession().then(({ data: { session } }) => {
      setSession(session);
      setIsLoading(false);
    });

    supabase.auth.onAuthStateChange((_event, session) => {
      setSession(session);
    });
  }, []);

  return (
    <AuthContext.Provider value={{ session, isLoading }}>
      {children}
    </AuthContext.Provider>
  );
};

export const useAuth = () => {
  const context = useContext(AuthContext);

  if (!context) {
    throw new Error("useAuth must be used within an AuthProvider");
  }

  return context;
};
```
</details>


<details>
<summary><code>PrivateProfile Type</code></summary>

```js
export interface PrivateProfile {
  id: string;
  first_name: string;
  last_name: string;
  dob: string;
  height_cm: number;
  neighborhood: string;
  latitude: number;
  longitude: number;
  max_distance_km: number;
  min_age: number;
  max_age: number;
  phone: string;
  children: Option | null;
  family_plan: Option | null;
  covid_vaccine: Option | null;
  zodiac_sign: Option | null;
  sexuality: Option | null;
  gender: Option | null;
  ethnicities: Option[];
  pets: Option[];
  pronouns: Option[];
  ethnicity_preferences: Option[];
  gender_preferences: Option[];
  answers: Answer[];
  photos: Photo[];
  avatar_url: string;
}

interface Photo {
  id: string;
  photo_url: string;
  photo_order: number;
}

interface Answer {
  id: string;
  question: string;
  prompt_id: number;
  answer_text: string;
  answer_order: number;
}

interface Option {
  id: number;
  name: string;
  plural_name?: string;
}



```
</details>


<details>
<summary><code>PublicProfile Type</code></summary>

```js
export interface Like {
  id: string;
  photo_url: string | null;
  answer_text: string | null;
  question: string | null;
  profile: PublicProfile;
}

export interface PublicProfile {
  id: string;
  age: number;
  pets: string[];
  gender: string;
  photos: Photo[];
  answers: Answer[];
  children: string;
  pronouns: string[];
  height_cm: number;
  sexuality: string;
  first_name: string;
  ethnicities: string[];
  family_plan: string;
  zodiac_sign: string;
  neighborhood: string;
  covid_vaccine: string;
}

export interface Answer {
  id: string;
  question: string;
  answer_text: string;
  answer_order: number;
}

export interface Photo {
  id: string;
  photo_url: string;
  photo_order: number;
}



```
</details>


<details>
<summary><code>profile preferences mutations</code></summary>

```js
export const useUpdateAgeRange = () => {
  const queryClient = useQueryClient();

  return useMutation({
    mutationFn: async ({
      min_age,
      max_age,
    }: {
      min_age: number;
      max_age: number;
    }) => {
      const { error } = await supabase.rpc("update_age_range", {
        min_age: min_age,
        max_age: max_age,
      });

      if (error) {
        throw error;
      }
    },
    onSuccess: async () => {
      await queryClient.invalidateQueries({ queryKey: ["myProfile"] });
    },
  });
};

export const useUpdateDistance = () => {
  const queryClient = useQueryClient();

  return useMutation({
    mutationFn: async ({ distance }: { distance: number }) => {
      const { error } = await supabase.rpc("update_distance", {
        distance: distance,
      });

      if (error) {
        throw error;
      }
    },
    onSuccess: async () => {
      await queryClient.invalidateQueries({ queryKey: ["myProfile"] });
    },
  });
};

export const useUpdateEthnicityPreferences = () => {
  const queryClient = useQueryClient();

  return useMutation({
    mutationFn: async ({ ethnicities }: { ethnicities: number[] }) => {
      const { error } = await supabase.rpc("update_ethnicity_preferences", {
        ethnicity_preferences: ethnicities,
      });

      if (error) {
        throw error;
      }
    },
    onSuccess: async () => {
      await queryClient.invalidateQueries({ queryKey: ["myProfile"] });
    },
  });
};

export const useUpdateGenderPreferences = () => {
  const queryClient = useQueryClient();

  return useMutation({
    mutationFn: async ({
      genders,
    }: {
      profileId: string;
      genders: number[];
    }) => {
      const { error } = await supabase.rpc("update_gender_preferences", {
        gender_preferences: genders,
      });

      if (error) {
        throw error;
      }
    },
    onSuccess: async () => {
      await queryClient.invalidateQueries({ queryKey: ["myProfile"] });
    },
  });
};

export const useUpdateLocation = () => {
  const queryClient = useQueryClient();

  return useMutation({
    mutationKey: ["update-location"],
    mutationFn: async ({
      latitude,
      longitude,
      neighborhood,
    }: {
      latitude: number;
      longitude: number;
      neighborhood: string;
    }) => {
      const { error } = await supabase.rpc("update_location", {
        latitude: latitude,
        longitude: longitude,
        neighborhood: neighborhood,
      });

      if (error) {
        throw error;
      }
    },
    onSuccess: async () => {
      await queryClient.invalidateQueries({ queryKey: ["myProfile"] });
    },
  });
};

```
</details>


<details>
<summary><code>option queries</code></summary>

```js
import { supabase } from "@/lib/supabase";
import { useQuery } from "@tanstack/react-query";

export const usePrompts = () => {
  return useQuery({
    queryKey: ["prompts"],
    queryFn: async () => {
      const { data, error } = await supabase.from("prompts").select("*");

      if (error) {
        throw error;
      }

      return data;
    },
    initialData: [],
  });
};

export const useChildren = () => {
  return useQuery({
    queryKey: ["children"],
    queryFn: async () => {
      const { data, error } = await supabase.from("children").select("*");

      if (error) {
        throw error;
      }

      return data;
    },
    initialData: [],
  });
};

export const useCovidVaccine = () => {
  return useQuery({
    queryKey: ["covid_vaccine"],
    queryFn: async () => {
      const { data, error } = await supabase.from("covid_vaccine").select("*");

      if (error) {
        throw error;
      }

      return data;
    },
    initialData: [],
  });
};

export const useEthnicities = () => {
  return useQuery({
    queryKey: ["ethnicities"],
    queryFn: async () => {
      const { data, error } = await supabase.from("ethnicities").select("*");

      if (error) {
        throw error;
      }

      return data;
    },
    initialData: [],
  });
};

export const useFamilyPlans = () => {
  return useQuery({
    queryKey: ["family_plans"],
    queryFn: async () => {
      const { data, error } = await supabase.from("family_plans").select("*");

      if (error) {
        throw error;
      }

      return data;
    },
    initialData: [],
  });
};

export const useGenders = () => {
  return useQuery({
    queryKey: ["genders"],
    queryFn: async () => {
      const { data, error } = await supabase.from("genders").select("*");

      if (error) {
        throw error;
      }

      return data;
    },
    initialData: [],
  });
};

export const usePets = () => {
  return useQuery({
    queryKey: ["pets"],
    queryFn: async () => {
      const { data, error } = await supabase.from("pets").select("*");

      if (error) {
        throw error;
      }

      return data;
    },
    initialData: [],
  });
};

export const usePronouns = () => {
  return useQuery({
    queryKey: ["pronouns"],
    queryFn: async () => {
      const { data, error } = await supabase.from("pronouns").select("*");

      if (error) {
        throw error;
      }

      return data;
    },
    initialData: [],
  });
};

export const useSexualities = () => {
  return useQuery({
    queryKey: ["sexualities"],
    queryFn: async () => {
      const { data, error } = await supabase.from("sexualities").select("*");

      if (error) {
        throw error;
      }

      return data;
    },
    initialData: [],
  });
};

export const useZodiacSigns = () => {
  return useQuery({
    queryKey: ["zodiac_signs"],
    queryFn: async () => {
      const { data, error } = await supabase.from("zodiac_signs").select("*");

      if (error) {
        throw error;
      }

      return data;
    },
    initialData: [],
  });
};


```
</details>

<details>
<summary><code>profile queries and mutations</code></summary>

```js
import { supabase } from "@/lib/supabase";
import { useMutation, useQuery, useQueryClient } from "@tanstack/react-query";
import { Like, PublicProfile } from "./types";

export const useProfiles = (page_size: number) => {
  return useQuery<PublicProfile[]>({
    queryKey: ["profiles", page_size],
    queryFn: async () => {
      const { data, error } = await supabase
        .rpc("get_profiles", {
          page_size,
        })
        .returns<PublicProfile[]>();

      if (error) {
        throw error;
      }

      return data;
    },
    initialData: [],
  });
};

export const useSkipProfile = () => {
  return useMutation({
    mutationFn: async (profile: string) => {
      const { error } = await supabase.rpc("skip_profile", {
        profile,
      });

      if (error) {
        throw error;
      }
    },
  });
};

export const useLikeProfile = () => {
  return useMutation({
    mutationFn: async ({
      profile,
      answer,
      photo,
    }: {
      profile: string;
      answer: string | undefined;
      photo: string | undefined;
    }) => {
      const { error } = await supabase.rpc("like_profile", {
        profile,
        answer,
        photo,
      });

      if (error) {
        throw error;
      }
    },
  });
};

export const useReviewProfiles = () => {
  return useMutation({
    mutationFn: async () => {
      const { error } = await supabase.rpc("review_profiles");

      if (error) {
        throw error;
      }
    },
  });
};

export const useLikes = () => {
  return useQuery<Like[]>({
    queryKey: ["likes"],
    queryFn: async () => {
      const { data, error } = await supabase.rpc("get_likes").returns<Like[]>();

      if (error) {
        throw error;
      }

      return data;
    },
    initialData: [],
  });
};

export const useRemoveLike = () => {
  const queryClient = useQueryClient();

  return useMutation({
    mutationFn: async (interaction: string) => {
      const { error } = await supabase.rpc("remove_like", {
        interaction,
      });

      if (error) {
        throw error;
      }
    },
    onSuccess: async () => {
      await queryClient.invalidateQueries({ queryKey: ["likes"] });
    },
  });
};

export const useMatch = () => {
  const queryClient = useQueryClient();

  return useMutation({
    mutationFn: async (interaction: string) => {
      const { error } = await supabase.rpc("match", {
        interaction,
      });

      if (error) {
        throw error;
      }
    },
    onSuccess: async () => {
      await queryClient.invalidateQueries({ queryKey: ["likes"] });
    },
  });
};

export const useUnmatch = () => {
  return useMutation({
    mutationFn: async (interaction: string) => {
      const { error } = await supabase.rpc("unmatch", {
        interaction,
      });

      if (error) {
        throw error;
      }
    },
  });
};



```
</details>


<details>
<summary><code>Card component</code></summary>

```js
import React, { FC, ReactNode, forwardRef } from "react";
import { Pressable, PressableProps, Text, View } from "react-native";

interface Props extends PressableProps {
  icon: ReactNode;
  title: string;
  subtitle: string;
}

export const Card: FC<Props> = forwardRef<View, Props>(
  ({ icon, title, subtitle, ...rest }, ref) => {
    return (
      <Pressable
        ref={ref}
        {...rest}
        className="flex-row items-center gap-4 border border-neutral-300 rounded-md p-3"
      >
        <View className="bg-zinc-300 h-12 aspect-square rounded-full items-center justify-center">
          {icon}
        </View>
        <View>
          <Text className="text-base font-poppins-medium">{title}</Text>
          <Text className="text-sm font-poppins-light">{subtitle}</Text>
        </View>
      </Pressable>
    );
  }
);

Card.displayName = "Card";


```

</details>

<details>
<summary><code>Card component usage</code></summary>

```js
<Card
  key={"help"}
  icon={<Ionicons name="help" className="text-2xl" />}
  title="Help Center"
  subtitle="Safety, Security, and more"
/>
<Card
  key={"what-works"}
  icon={<Ionicons name="bulb-outline" className="text-2xl" />}
  title="What Works"
  subtitle="Check out our expert dating tips"
/>


```

</details>


<details>
<summary><code>settings page</code></summary>

```js
import { useSignOut } from "@/api/auth";
import { StackHeaderV2 } from "@/components/stack-header-v2";
import { Text, TouchableOpacity, View } from "react-native";

const Page = () => {
  const { mutate } = useSignOut();

  return (
    <View className="flex-1 bg-white p-5">
      <StackHeaderV2 title="Settings" />
      <TouchableOpacity
        className="p-3 border-y border-neutral-300"
        onPress={async () => mutate()}
      >
        <Text className="text-base text-center font-poppins-regular">
          Log Out
        </Text>
      </TouchableOpacity>
    </View>
  );
};

export default Page;

```
</details>

<details>
<summary><code>StackHeaderV2 Component</code></summary>

```js
import { Ionicons } from "@expo/vector-icons";
import { Stack, router } from "expo-router";
import { FC } from "react";

interface Props {
  title: string;
}

export const StackHeaderV2: FC<Props> = ({ title }) => {
  return (
    <Stack.Screen
      options={{
        title,
        headerTitleAlign: "center",
        headerBackVisible: false,
        headerRight: () => (
          <Ionicons
            name="close"
            className="text-2xl"
            onPress={router.back}
            suppressHighlighting
          />
        ),
      }}
    />
  );
};


```
</details>


<details>
<summary><code>StackHeaderV3 component</code></summary>

```js
import { Stack } from "expo-router";
import { FC } from "react";
import { Pressable, Text } from "react-native";

interface Props {
  title?: string;
  onPressCancel?: () => void;
  onPressDone?: () => void;
}

export const StackHeaderV3: FC<Props> = ({
  title,
  onPressCancel,
  onPressDone,
}) => {
  return (
    <Stack.Screen
      options={{
        headerShown: true,
        title: title,
        headerTitleAlign: "center",
        headerLeft: () => (
          <Pressable onPress={onPressCancel}>
            <Text className="font-semibold text-fuchsia-900">Cancel</Text>
          </Pressable>
        ),
        headerRight: () => (
          <Pressable onPress={onPressDone}>
            <Text className="font-semibold text-fuchsia-900">Done</Text>
          </Pressable>
        ),

        headerShadowVisible: false,
      }}
    />
  );
};


```
</details>


<details>
<summary><code>StackHeaderV4 component</code></summary>

```js
import {Ionicons} from '@expo/vector-icons';
import {Stack} from 'expo-router';
import {FC} from 'react';

interface Props {
  title: string;
  onPressBack?: () => void;
}

export const StackHeaderV4: FC<Props> = ({title, onPressBack}) => {
  return (
    <Stack.Screen
      options={{
        title,
        headerTitleAlign: 'center',
        headerLeft: () => (
          <Ionicons
            name="chevron-back"
            className="text-2xl"
            onPress={onPressBack}
            suppressHighlighting
          />
        ),
      }}
    />
  );
};


```
</details>





<details>
<summary><code>Edit Context Provider</code></summary>

```js
import { useMyProfile } from "@/api/my-profile";
import { PrivateProfile } from "@/api/my-profile/types";
import {
  PropsWithChildren,
  createContext,
  useContext,
  useEffect,
  useState,
} from "react";

type EditContextType = {
  edits: PrivateProfile | null;
  setEdits: (profile: PrivateProfile | null) => void;
  gridActive: boolean;
  setGridActive: (active: boolean) => void;
};

const EditContext = createContext<EditContextType>({
  edits: null,
  setEdits: () => {},
  gridActive: false,
  setGridActive: () => {},
});

export const EditProvider = ({ children }: PropsWithChildren) => {
  const { data: myProfile } = useMyProfile();
  const [edits, setEdits] = useState<PrivateProfile | null>(myProfile);
  const [gridActive, setGridActive] = useState(false);

  useEffect(() => {
    setEdits(myProfile);
  }, [myProfile]);

  return (
    <EditContext.Provider
      value={{
        edits: edits,
        setEdits: setEdits,
        gridActive,
        setGridActive,
      }}
    >
      {children}
    </EditContext.Provider>
  );
};

export const useEdit = () => {
  const context = useContext(EditContext);
  if (!context) {
    throw new Error("useEdit must be used within a EditProvider");
  }
  return context;
};


```
</details>


<details>
<summary><code>pickPhoto function</code></summary>

```js
const pickPhoto = async () => {
    let result = await ImagePicker.launchImageLibraryAsync({
      mediaTypes: ["images"],
      allowsMultipleSelection: true,
      selectionLimit: slots - data.filter((item) => item.photo).length,
      aspect: [4, 3],
      quality: 1,
    });

    if (!result.canceled) {
      const updatedData = data.map((item, index) => {
        if (!item.photo && result.assets?.length) {
          const currentAsset = result.assets.shift();

          if (currentAsset) {
            return {
              ...item,
              photo: {
                id: "temp_" + Crypto.randomUUID(),
                photo_url: currentAsset.uri,
                photo_order: index,
              },
              disabledDrag: false,
              disabledReSorted: false,
            };
          }
        }
        return item;
      });

      const updatedPhotos = updatedData
        .map((item, index) => {
          return {
            ...item?.photo,
            photo_order: index,
          } as Photo;
        })
        .filter((item) => item.photo_url);

      setData(updatedData as Item[]);
      setEdits({
        ...profile,
        photos: updatedPhotos,
      });
    }
  };



```
</details>

<details>
<summary><code>replacePhoto function</code></summary>

```js
const replacePhoto = async (item: Item) => {
    let result = await ImagePicker.launchImageLibraryAsync({
      mediaTypes: ["images"],
      allowsEditing: true,
      aspect: [4, 3],
      quality: 1,
    });

    if (!result.canceled) {
      const updatedData = data.map((i, index) => {
        if (item.key === i.key && result.assets?.length) {
          const currentAsset = result.assets.shift();

          if (currentAsset) {
            return {
              ...i,
              photo: {
                ...i.photo,
                photo_url: currentAsset.uri,
              },
              disabledDrag: false,
              disabledReSorted: false,
            };
          }
        }
        return i;
      });

      const updatedPhotos = updatedData
        .map((item, index) => {
          return {
            ...item?.photo,
            photo_order: index,
          } as Photo;
        })
        .filter((item) => item.photo_url);

      setData(updatedData as Item[]);
      setEdits({
        ...profile,
        photos: updatedPhotos,
      });
    }
  };


```
</details>


<details>
<summary><code>AnswerList component</code></summary>

```js
import { Answer, PrivateProfile } from "@/api/my-profile/types";
import { useEdit } from "@/store/edit";
import { router } from "expo-router";
import { FC, useEffect, useState } from "react";
import { Dimensions, Text, View } from "react-native";
import { DraggableGrid } from "react-native-draggable-grid";

type Item = {
  key: string;
  answer: Answer;
  disabledDrag?: boolean;
  disabledReSorted?: boolean;
};

interface Props {
  profile: PrivateProfile;
  columns?: number;
  spacing?: number;
  margin?: number;
  height?: number;
  slots?: number;
}

export const AnswerList: FC<Props> = ({
  profile,
  columns = 1,
  spacing = 10,
  margin = 10,
  height = 120,
  slots = 3,
}) => {
  const width = Dimensions.get("window").width - margin * 2;
  const size = width / columns - spacing;

  const [data, setData] = useState<Item[]>([]);
  const { setEdits: setMyProfileChanges, setGridActive } = useEdit();

  useEffect(() => {
    if (!data.length) {
      const initialData: Item[] = Array(slots)
        .fill(null)
        .map((_, index) => {
          const answer = profile?.answers[index] || null;
          return {
            key: index.toString(),
            answer: answer,
            disabledDrag: answer === null,
            disabledReSorted: answer === null,
          };
        });
      setData(initialData);
    } else {
      const newData = data.map((item, index) => {
        const answer = profile?.answers[index] || null;
        return {
          ...item,
          answer: answer,
          disabledDrag: answer === null,
          disabledReSorted: answer === null,
        };
      });
      setData(newData);
    }
    // eslint-disable-next-line react-hooks/exhaustive-deps
  }, [profile]);

  const renderItem = (item: Item) => {
    return (
      <View
        style={{
          width: size,
          height: height,
          paddingVertical: spacing / 2,
        }}
        key={item.key}
      >
        {item.answer ? (
          <View className="flex-1 rounded-md overflow-hidden border border-neutral-200 p-5">
            <Text className="text-base font-poppins-regular">
              {item.answer.question}
            </Text>
            <Text
              className="text-base font-poppins-regular text-neutral-400"
              numberOfLines={3}
            >
              {item.answer.answer_text}
            </Text>
          </View>
        ) : (
          <View className="flex-1 rounded-md border border-red-600 border-dashed" />
        )}
      </View>
    );
  };

  const onDragRelease = (data: Item[]) => {
    const answers = data
      .map((item, index) => {
        return {
          ...item.answer,
          answer_order: index,
        };
      })
      .filter((item) => item.answer_text != null);

    setMyProfileChanges({
      ...profile,
      answers,
    });
    setData(data);
    setGridActive(false);
  };

  const onDragItemActive = () => {
    setGridActive(true);
  };

  const onItemPress = (item: Item) => {
    if (item.answer) {
      router.push({
        pathname: "/(app)/write-answer",
        params: {
          itemId: item.answer.id,
          promptId: item.answer.prompt_id,
        },
      });
    } else {
      router.push("/(app)/prompts");
    }
    return;
  };

  return (
    <View>
      <View
        style={{
          width: width,
          alignSelf: "center",
        }}
      >
        <DraggableGrid
          numColumns={1}
          renderItem={renderItem}
          data={data}
          onDragRelease={onDragRelease}
          onDragItemActive={onDragItemActive}
          onItemPress={onItemPress}
          itemHeight={120}
        />
      </View>
    </View>
  );
};


```
</details>


<details>
<summary><code>custom profile type</code></summary>

```js
export interface Profile {
  id: string;
  first_name: string;
  photos: Photo[];
  answers: Answer[];
  traits: Trait[];
}

export interface Trait {
  key: string;
  icon: string;
  label: string | null;
}

export interface Photo {
  id: string;
  photo_url: string;
  photo_order: number;
}

export interface Answer {
  id: string;
  question: string;
  answer_text: string;
  answer_order: number;
}

};
```

</details>


<details>
<summary><code>ProfilePhoto component</code></summary>

```js
import { Photo } from "@/types/profile";
import { Image } from "expo-image";
import { FC } from "react";
import { View } from "react-native";

interface Props {
  photo: Photo;
}

export const ProfilePhoto: FC<Props> = ({ photo }) => {
  return (
    <View className="w-full aspect-square rounded-md overflow-hidden ">
      <Image
        source={photo.photo_url}
        className="flex-1 w-full bg-neutral-200"
      />
    </View>
  );
};


};
```

</details>

<details>
<summary><code>ProfileAnswer component</code></summary>

```js
import { Answer } from "@/types/profile";
import { FC } from "react";
import { Text, View } from "react-native";

interface Props {
  answer: Answer;
}

export const ProfileAnswer: FC<Props> = ({ answer }) => {
  return (
    <View className="bg-white rounded-md px-5 pt-14 pb-20 gap-5 border border-neutral-200">
      <Text className="text-base font-poppins-medium">{answer?.question}</Text>
      <Text className="text-3xl font-playfair-semibold">
        {answer?.answer_text}
      </Text>
    </View>
  );
};



};
```

</details>

<details>
<summary><code>List component</code></summary>

```js
import { PrivateProfile } from "@/api/my-profile/types";
import { cn } from "@/utils/cn";
import { Ionicons } from "@expo/vector-icons";
import { Href, Link } from "expo-router";
import { FC } from "react";
import { FlatList, Pressable, Text, View } from "react-native";

interface Props {
  data: {
    title: string;
    getValue: (profile: PrivateProfile) => string;
    route: string;
  }[];
  title: string;
  profile: PrivateProfile;
}

export const List: FC<Props> = ({ title, data, profile }) => {
  return (
    <FlatList
      scrollEnabled={false}
      data={data}
      keyExtractor={(item) => item.title}
      ListHeaderComponent={() => {
        return (
          <Text className="text-base font-poppins-semibold mb-2">{title}</Text>
        );
      }}
      renderItem={({ item }) => {
        return (
          <Link href={item.route as Href} asChild>
            <Pressable className="flex-row items-center justify-between pr-5 border-b border-neutral-200 py-3">
              <View>
                <Text
                  className={cn("text-base font-poppins-regular", {
                    "text-red-700":
                      ["Name", "Age", "Location", "Gender"].includes(
                        item.title
                      ) && item.getValue(profile) === "None",
                  })}
                >
                  {item.title}
                </Text>
                <Text
                  className={cn("text-base font-poppins-light", {
                    "text-red-700":
                      ["Name", "Age", "Location", "Gender"].includes(
                        item.title
                      ) && item.getValue(profile) === "None",
                  })}
                >
                  {item.getValue(profile!)}
                </Text>
              </View>
              <Ionicons name="chevron-forward" className="text-base  " />
            </Pressable>
          </Link>
        );
      }}
    />
  );
};

```

</details>


<details>
<summary><code>RadioList component</code></summary>

```js
import { Option } from "@/api/my-profile/types";
import Checkbox from "expo-checkbox";
import React, { useState } from "react";
import { FlatList, Pressable, Text, View } from "react-native";
import colors from "tailwindcss/colors";

interface Props {
  options: Option[];
  initialSelection: Option | null;
  onChange: (selected: Option | null) => void;
}

export const RadioList: React.FC<Props> = ({
  options,
  initialSelection,
  onChange,
}) => {
  const [selected, setSelected] = useState<Option | null>(initialSelection);

  const handleSelection = (item: Option) => {
    const updatedSelection = selected?.id === item.id ? null : item;

    setSelected(updatedSelection);
    onChange(updatedSelection);
  };

  return (
    <FlatList
      data={options}
      showsVerticalScrollIndicator={false}
      keyExtractor={(item) => item.id.toString()}
      ItemSeparatorComponent={() => <View className="h-px bg-neutral-200" />}
      renderItem={({ item }) => {
        const isChecked = selected?.id === item.id;

        return (
          <Pressable
            className="py-5 flex-row justify-between"
            onPress={() => handleSelection(item)}
          >
            <Text className="text-base font-poppins-regular">{item.name}</Text>
            <Checkbox
              value={isChecked}
              color={isChecked ? colors.fuchsia[950] : colors.neutral[400]}
              className="h-5 w-5"
              pointerEvents="none"
            />
          </Pressable>
        );
      }}
    />
  );
};



```
</details>


<details>
<summary><code>uploadPhoto function</code></summary>

```js
const uploadPhoto = async (photoUrl: string) => {
        const arraybuffer = await fetch(photoUrl).then((res) =>
          res.arrayBuffer()
        );
        const fileExt = photoUrl.split(".").pop()?.toLowerCase() ?? "jpeg";
        const filePath = `${
          profile.id
        }/photos/${Crypto.randomUUID()}.${fileExt}`;

        const { error } = await supabase.storage
          .from("profiles")
          .upload(filePath, arraybuffer, {
            contentType: `image/${fileExt}`,
          });


        if (error) {
          throw  error
        }

        const { data } = supabase.storage
          .from("profiles")
          .getPublicUrl(filePath);

        if (!data?.publicUrl) {
 
          throw error
        }

        return data.publicUrl;
      };


```
</details>


<details>
<summary><code>maximum distance preference page</code></summary>

```js
import { useUpdateDistance } from "@/api/my-profile";
import { StackHeaderV4 } from "@/components/stack-header-v4";
import { useEdit } from "@/store/edit";
import { Slider } from "@miblanchard/react-native-slider";
import { router } from "expo-router";
import { useState } from "react";
import { Alert, Text, View } from "react-native";

const Page = () => {
  const { edits } = useEdit();
  const [distance, setDistance] = useState(edits?.max_distance_km || 160);

  const { mutate, reset } = useUpdateDistance();

  const handlePress = () => {
    mutate(
      { distance: distance },
      {
        onSuccess: () => {
          router.back();
        },
        onError: () => {
          Alert.alert("Error", "Something went wrong, please try again later.");
          reset();
          router.back();
        },
      }
    );
  };

  return (
    <View className="bg-white flex-1 px-5 py-20 ">
      <StackHeaderV4 title="Maximum distance" onPressBack={handlePress} />
      <Slider
        minimumValue={1}
        maximumValue={160}
        step={1}
        value={distance}
        onValueChange={(value) => setDistance(value[0])}
        renderAboveThumbComponent={() => {
          return (
            <View className="items-center justify-center w-16 -left-8">
              <Text className="text-center ">{distance} km</Text>
            </View>
          );
        }}
      />
    </View>
  );
};
export default Page;
```
</details>


<details>
<summary><code>age preference page</code></summary>

```js
import { useUpdateAgeRange } from "@/api/my-profile";
import { StackHeaderV4 } from "@/components/stack-header-v4";
import { useEdit } from "@/store/edit";
import { Slider } from "@miblanchard/react-native-slider";
import { router } from "expo-router";
import { useState } from "react";
import { Alert, Text, View } from "react-native";

const Page = () => {
  const { edits } = useEdit();
  const [ageRange, setAgeRange] = useState([
    edits?.min_age || 18,
    edits?.max_age || 100,
  ]);

  const { mutate, reset } = useUpdateAgeRange();

  const handlePress = () => {
    mutate(
      { min_age: ageRange[0], max_age: ageRange[1] },
      {
        onSuccess: () => {
          router.back();
        },
        onError: () => {
          Alert.alert("Error", "Something went wrong, please try again later.");
          reset();
          router.back();
        },
      }
    );
  };

  return (
    <View className="bg-white flex-1 px-5 py-20 ">
      <StackHeaderV4 title="Age range" onPressBack={handlePress} />
      <Slider
        minimumValue={18}
        maximumValue={100}
        step={1}
        value={ageRange}
        onValueChange={(value) => setAgeRange(value)}
        renderAboveThumbComponent={(_index, value) => {
          return (
            <View className="items-center justify-center w-16 -left-8">
              <Text className="text-center ">{value}</Text>
            </View>
          );
        }}
      />
    </View>
  );
};
export default Page;

```
</details>


<details>
<summary><code>ethnicity preference page</code></summary>

```js
import { useUpdateEthnicityPreferences } from "@/api/my-profile";
import { Option, PrivateProfile } from "@/api/my-profile/types";
import { useEthnicities } from "@/api/options";
import { CheckboxList } from "@/components/checkbox-list";
import { StackHeaderV4 } from "@/components/stack-header-v4";
import { useEdit } from "@/store/edit";
import { router } from "expo-router";
import { useState } from "react";
import { Alert, View } from "react-native";

const Page = () => {
  const { edits, setEdits } = useEdit();
  const { data } = useEthnicities();
  const [selected, setSelected] = useState<Option[]>(
    edits?.ethnicity_preferences || []
  );

  const { mutate, reset } = useUpdateEthnicityPreferences();

  const handlePress = () => {
    setEdits({ ...edits, ethnicity_preferences: selected } as PrivateProfile);
    mutate(
      { ethnicities: selected.map((i) => i.id) },
      {
        onSuccess: () => {
          router.back();
        },
        onError: () => {
          Alert.alert("Error", "Something went wrong, please try again later.");
          reset();
          router.back();
        },
      }
    );
  };

  return (
    <View className="bg-white flex-1 p-5">
      <StackHeaderV4 title="Ethnicity" onPressBack={handlePress} />
      <CheckboxList
        options={data}
        initialSelection={selected}
        onChange={setSelected}
      />
    </View>
  );
};
export default Page;
```
</details>

<details>
<summary><code>Empty component</code></summary>

```js
import { FC } from "react";
import { Pressable, Text, View } from "react-native";
import { SafeAreaView } from "react-native-safe-area-context";

interface Props {
  title: string;
  subTitle: string;
  primaryText?: string;
  secondaryText?: string;
  onPrimaryPress?: () => void;
  onSecondaryPress?: () => void;
}

export const Empty: FC<Props> = ({
  title,
  subTitle,
  onPrimaryPress,
  onSecondaryPress,
  primaryText,
  secondaryText,
}) => {
  return (
    <SafeAreaView className="flex-1 p-5 bg-white justify-center gap-8">
      <View className="gap-2">
        <Text className="text-2xl font-playfair-semibold text-center">
          {title}
        </Text>
        <Text className="text-base font-poppins-light text-center">
          {subTitle}
        </Text>
      </View>
      <View className="gap-2 px-5">
        {primaryText && (
          <Pressable
            className="h-14 bg-black items-center justify-center rounded-full w-full"
            onPress={onPrimaryPress}
          >
            <Text className="text-white text-base font-poppins-medium">
              {primaryText}
            </Text>
          </Pressable>
        )}
        {secondaryText && (
          <Pressable
            className="h-14 bg-white items-center justify-center rounded-full border border-neutral-400"
            onPress={onSecondaryPress}
          >
            <Text className="text-black text-base font-poppins-medium ">
              {secondaryText}
            </Text>
          </Pressable>
        )}
      </View>
    </SafeAreaView>
  );
};

```
</details>

<details>
<summary><code>ProfileItem component</code></summary>

```js
import {Answer, Photo} from '@/types/profile';
import {FC, ReactNode} from 'react';
import {View} from 'react-native';
import {Fab} from './fab';

interface Props {
  children: ReactNode;
  item: Photo | Answer;
  type: 'photo' | 'answer';
  onLike?: (id: string, type: 'photo' | 'answer') => void;
}

export const ProfileItem: FC<Props> = ({children, item, type, onLike}) => {
  return (
    <View>
      {children}
      {onLike && (
        <Fab
          className="absolute bottom-5 right-5 bg-white shadow-sm"
          iconName="heart-outline"
          iconClassName="text-fuchsia-900 text-4xl"
          onPress={() => onLike(item.id, type)}
        />
      )}
    </View>
  );
};
```
</details>

<details>
<summary><code>Loader component</code></summary>

```js
import LottieView from "lottie-react-native";
import { FC } from "react";
import { View } from "react-native";

interface Props {}

export const Loader: FC<Props> = () => {
  return (
    <View className="flex-1 bg-white">
      <LottieView
        autoPlay
        // @ts-ignore
        className="w-full h-full bg-white mt-12"
        source={require("~/assets/images/loading.json")}
      />
    </View>
  );
};
```
</details>


<details>
<summary><code>likes seed</code></summary>

```js
insert into interactions (actor_id, target_id, updated_by, status_id, photo_id, answer_id)
values 
('00000000-0000-0000-0000-000000000002', '00000000-0000-0000-0000-000000000000', '00000000-0000-0000-0000-000000000002', 2, '00000000-0000-0000-0000-000000000000', null),
('00000000-0000-0000-0000-000000000005', '00000000-0000-0000-0000-000000000000', '00000000-0000-0000-0000-000000000005', 2, null, '00000000-0000-0000-0000-000000000000'),
('00000000-0000-0000-0000-000000000006', '00000000-0000-0000-0000-000000000000', '00000000-0000-0000-0000-000000000006', 2, '10000000-0000-0000-0000-000000000000', null),
('00000000-0000-0000-0000-000000000008', '00000000-0000-0000-0000-000000000000', '00000000-0000-0000-0000-000000000008', 2, null, '10000000-0000-0000-0000-000000000000'),
('00000000-0000-0000-0000-000000000011', '00000000-0000-0000-0000-000000000000', '00000000-0000-0000-0000-000000000011', 2, '20000000-0000-0000-0000-000000000000', null),
('00000000-0000-0000-0000-000000000012', '00000000-0000-0000-0000-000000000000', '00000000-0000-0000-0000-000000000012', 2, null, '20000000-0000-0000-0000-000000000000'),
('00000000-0000-0000-0000-000000000014', '00000000-0000-0000-0000-000000000000', '00000000-0000-0000-0000-000000000014', 2, '30000000-0000-0000-0000-000000000000', null),
('00000000-0000-0000-0000-000000000015', '00000000-0000-0000-0000-000000000000', '00000000-0000-0000-0000-000000000015', 2, '40000000-0000-0000-0000-000000000000', null),
('00000000-0000-0000-0000-000000000018', '00000000-0000-0000-0000-000000000000', '00000000-0000-0000-0000-000000000018', 2, '50000000-0000-0000-0000-000000000000', null)

select * from get_likes()
```
</details>


<details>
<summary><code>LikeCard component</code></summary>

```js
import { Like } from "@/api/profiles/types";
import { BlurView } from "expo-blur";
import { Image } from "expo-image";
import { FC } from "react";
import { Text, View } from "react-native";

interface Props {
  like: Like;
}

export const LikeCard: FC<Props> = ({ like: { photo_url, profile } }) => {
  return (
    <View className="bg-white flex-1 rounded-lg overflow-hidden border border-neutral-200">
      <View className="p-4 gap-5">
        <Text className="text-base font-poppins-light">{`Liked your ${
          photo_url ? "photo" : "answer"
        }`}</Text>
        <Text className="text-xl font-poppins-medium">
          {profile.first_name}
        </Text>
      </View>
      <View className="flex-1 bg-neutral-200 aspect-square w-full">
        <Image source={profile.photos[0].photo_url} className="flex-1" />
        <BlurView
          className="absolute top-0 right-0 bottom-0 left-0"
          intensity={30}
          tint="light"
        ></BlurView>
      </View>
    </View>
  );
};
```
</details>


<details>
<summary><code>renderHeader function</code></summary>

```js
  const renderHeader = () => {
    return (
      <View className="gap-5 bg-white ">
        <Text className="text-3xl font-poppins-semibold">Likes You</Text>
        {data.length > 0 && (
          <>
            <Link href={`/likes/${data[0].id}`} asChild>
              <Pressable className="bg-white flex-1 rounded-lg overflow-hidden border border-neutral-200">
                <View className="p-4 gap-5">
                  <Text className="text-base font-poppins-light">{`Liked your ${
                    data[0].photo_url ? "photo" : "answer"
                  }`}</Text>
                  <Text className="text-xl font-poppins-medium">
                    {data[0].profile.first_name}
                  </Text>
                </View>
                <View className="p-4">
                  <View className="rounded-lg flex-1 bg-neutral-200 aspect-square w-full overflow-hidden">
                    <Image
                      source={data[0].profile.photos[0].photo_url}
                      className="flex-1"
                    />
                  </View>
                </View>
              </Pressable>
            </Link>
          </>
        )}
      </View>
    );
  };
```
</details>


<details>
<summary><code>renderEmpty function</code></summary>

```js
const renderEmpty = () => {
    if (data.length === 1) {
      return null;
    }

    if (isFetching) {
      return <Loader />;
    }

    if (isError) {
      return (
        <Empty
          title="Something went wrong"
          subTitle=" We ran into a problem loading your likes, sorry about that!"
          primaryText="Try again"
          onPrimaryPress={() => refetch()}
        />
      );
    }

    return (
      <Empty
        title="No likes yet"
        subTitle="We can help you get your first one sooner."
      />
    );
  };
```
</details>

<details>
<summary><code>like details page</code></summary>

```js
import { useLikes, useMatch, useRemoveLike } from "@/api/profiles";
import { Fab } from "@/components/fab";
import { ProfileView } from "@/components/profile-view";
import { transformPublicProfile } from "@/utils/profile";
import { Image } from "expo-image";
import { Redirect, Stack, router, useLocalSearchParams } from "expo-router";
import { Alert, ScrollView, Text, View } from "react-native";

const Page = () => {
  const { id } = useLocalSearchParams();
  const { mutate: remove, isPending: removePending } = useRemoveLike();
  const { mutate: match, isPending: matchPending } = useMatch();

  const { data } = useLikes();
  const like = data.find((like) => like.id === id);
  let profile;

  const handleRemove = () => {
    if (like) {
      remove(like.id, {
        onSuccess: () => {
          router.back();
        },
        onError: (error) => {
          Alert.alert("Error", error.message);
        },
      });
    }
  };

  const handleMatch = () => {
    if (like) {
      match(like.id, {
        onSuccess: () => {
          router.back();
        },
        onError: (error) => {
          Alert.alert("Error", error.message);
        },
      });
    }
  };

  if (!like) {
    return <Redirect href={"/likes"} />;
  }

  profile = transformPublicProfile(like.profile);

  return (
    <View className="flex-1 px-5 bg-white">
      <Stack.Screen
        options={{
          headerLeft: () => (
            <Text
              className="text-base font-poppins-medium"
              onPress={() => router.back()}
              suppressHighlighting
            >
              All
            </Text>
          ),
          title: "",
          headerShadowVisible: false,
        }}
      />
      <ScrollView showsVerticalScrollIndicator={false}>
        <View className="h-28 bg-neutral-200 overflow-hidden rounded-md ">
          {like?.photo_url ? (
            <Image source={like?.photo_url} className="aspect-square w-full" />
          ) : (
            <View className="flex-1 justify-center p-5">
              <Text className="text-xl font-playfair-semibold">
                {like?.answer_text}
              </Text>
            </View>
          )}
        </View>
        <ProfileView profile={profile} />
      </ScrollView>

      <Fab
        className="absolute bottom-5 left-5 bg-white  shadow-sm h-20"
        iconClassName="text-black text-4xl"
        iconName="close"
        onPress={handleRemove}
        loading={removePending}
        loaderClassName="text-black"
        disabled={removePending || matchPending}
      />
      <Fab
        className="absolute bottom-5 right-5 bg-white  shadow-sm h-20"
        iconClassName="text-black text-4xl"
        iconName="chatbox-outline"
        onPress={handleMatch}
        loading={matchPending}
        loaderClassName="text-black"
        disabled={removePending || matchPending}
      />
    </View>
  );
};

export default Page;
```
</details>

<details>
<summary><code>Channel CustomHeader</code></summary>

```js
const CustomHeader = () => {
  const { headerTitle } = useContext(GroupChannelContexts.Fragment);
  const { mutate } = useUnmatch();
  const { id } = useLocalSearchParams<{ id: string }>();

  return (
    <Stack.Screen
      options={{
        headerLeft: () => (
          <View className="flex-row items-center gap-2">
            <Ionicons
              name="chevron-back"
              className="text-2xl"
              onPress={() => router.back()}
              suppressHighlighting
            />
            <Text className="text-lg font-poppins-medium">{headerTitle}</Text>
          </View>
        ),
        title: "",
        headerRight: () => (
          <Ionicons
            name="cut-outline"
            className="text-2xl"
            onPress={() => {
              Alert.alert(
                "Are you sure?",
                `Unmatching will delete the match for both you and ${headerTitle}`,
                [
                  {
                    text: "Cancel",
                    style: "cancel",
                  },
                  {
                    text: "Unmatch",
                    onPress: () => {
                      mutate(id, {
                        onSuccess: () => {
                          router.navigate("/matches/");
                        },
                        onError: () => {
                          Alert.alert(
                            "Error",
                            "Something went wrong, please try again later."
                          );
                        },
                      });
                    },
                  },
                ]
              );
            }}
            suppressHighlighting
          />
        ),
      }}
    />
  );
};
```
</details>


### Constants

<details>
<summary><code>src/constants/countries</code></summary>

```js
export const countries = [
  {name: 'Jamaica', code: 'JM', dialCode: '+1', flag: '🇯🇲'},
  {name: 'Afghanistan', code: 'AF', dialCode: '+93', flag: '🇦🇫'},
  {name: 'Albania', code: 'AL', dialCode: '+355', flag: '🇦🇱'},
  {name: 'Algeria', code: 'DZ', dialCode: '+213', flag: '🇩🇿'},
  {name: 'American Samoa', code: 'AS', dialCode: '+1', flag: '🇦🇸'},
  {name: 'Andorra', code: 'AD', dialCode: '+376', flag: '🇦🇩'},
  {name: 'Angola', code: 'AO', dialCode: '+244', flag: '🇦🇴'},
  {name: 'Anguilla', code: 'AI', dialCode: '+1', flag: '🇦🇮'},
  {name: 'Antigua & Barbuda', code: 'AG', dialCode: '+1', flag: '🇦🇬'},
  {name: 'Argentina', code: 'AR', dialCode: '+54', flag: '🇦🇷'},
  {name: 'Armenia', code: 'AM', dialCode: '+374', flag: '🇦🇲'},
  {name: 'Aruba', code: 'AW', dialCode: '+297', flag: '🇦🇼'},
  {name: 'Ascension Island', code: 'AC', dialCode: '+247', flag: '🇦🇨'},
  {name: 'Australia', code: 'AU', dialCode: '+61', flag: '🇦🇺'},
  {name: 'Austria', code: 'AT', dialCode: '+43', flag: '🇦🇹'},
  {name: 'Azerbaijan', code: 'AZ', dialCode: '+994', flag: '🇦🇿'},
  {name: 'Bahamas', code: 'BS', dialCode: '+1', flag: '🇧🇸'},
  {name: 'Bahrain', code: 'BH', dialCode: '+973', flag: '🇧🇭'},
  {name: 'Bangladesh', code: 'BD', dialCode: '+880', flag: '🇧🇩'},
  {name: 'Barbados', code: 'BB', dialCode: '+1', flag: '🇧🇧'},
  {name: 'Belarus', code: 'BY', dialCode: '+375', flag: '🇧🇾'},
  {name: 'Belgium', code: 'BE', dialCode: '+32', flag: '🇧🇪'},
  {name: 'Belize', code: 'BZ', dialCode: '+501', flag: '🇧🇿'},
  {name: 'Benin', code: 'BJ', dialCode: '+229', flag: '🇧🇯'},
  {name: 'Bermuda', code: 'BM', dialCode: '+1', flag: '🇧🇲'},
  {name: 'Bhutan', code: 'BT', dialCode: '+975', flag: '🇧🇹'},
  {name: 'Bolivia', code: 'BO', dialCode: '+591', flag: '🇧🇴'},
  {name: 'Bosnia & Herzegovina', code: 'BA', dialCode: '+387', flag: '🇧🇦'},
  {name: 'Botswana', code: 'BW', dialCode: '+267', flag: '🇧🇼'},
  {name: 'Brazil', code: 'BR', dialCode: '+55', flag: '🇧🇷'},
  {name: 'British Virgin Islands', code: 'VG', dialCode: '+1', flag: '🇻🇬'},
  {name: 'Brunei', code: 'BN', dialCode: '+673', flag: '🇧🇳'},
  {name: 'Bulgaria', code: 'BG', dialCode: '+359', flag: '🇧🇬'},
  {name: 'Burkina Faso', code: 'BF', dialCode: '+226', flag: '🇧🇫'},
  {name: 'Burundi', code: 'BI', dialCode: '+257', flag: '🇧🇮'},
  {name: 'Cambodia', code: 'KH', dialCode: '+855', flag: '🇰🇭'},
  {name: 'Cameroon', code: 'CM', dialCode: '+237', flag: '🇨🇲'},
  {name: 'Canada', code: 'CA', dialCode: '+1', flag: '🇨🇦'},
  {name: 'Cape Verde', code: 'CV', dialCode: '+238', flag: '🇨🇻'},
  {name: 'Caribbean Netherlands', code: 'BQ', dialCode: '+599', flag: '🇧🇶'},
  {name: 'Cayman Islands', code: 'KY', dialCode: '+1', flag: '🇰🇾'},
  {
    name: 'Central African Republic',
    code: 'CF',
    dialCode: '+236',
    flag: '🇨🇫',
  },
  {name: 'Chad', code: 'TD', dialCode: '+235', flag: '🇹🇩'},
  {name: 'Chagos Archipelago', code: 'IO', dialCode: '+246', flag: '🇮🇴'},
  {name: 'Chile', code: 'CL', dialCode: '+56', flag: '🇨🇱'},
  {name: 'China mainland', code: 'CN', dialCode: '+86', flag: '🇨🇳'},
  {name: 'Christmas Island', code: 'CX', dialCode: '+61', flag: '🇨🇽'},
  {name: 'Cocos (Keeling) Islands', code: 'CC', dialCode: '+61', flag: '🇨🇨'},
  {name: 'Colombia', code: 'CO', dialCode: '+57', flag: '🇨🇴'},
  {name: 'Comoros', code: 'KM', dialCode: '+269', flag: '🇰🇲'},
  {name: 'Congo - Brazzaville', code: 'CG', dialCode: '+242', flag: '🇨🇬'},
  {name: 'Congo - Kinshasa', code: 'CD', dialCode: '+243', flag: '🇨🇩'},
  {name: 'Cook Islands', code: 'CK', dialCode: '+682', flag: '🇨🇰'},
  {name: 'Costa Rica', code: 'CR', dialCode: '+506', flag: '🇨🇷'},
  {name: 'Croatia', code: 'HR', dialCode: '+385', flag: '🇭🇷'},
  {name: 'Cuba', code: 'CU', dialCode: '+53', flag: '🇨🇺'},
  {name: 'Curaçao', code: 'CW', dialCode: '+599', flag: '🇨🇼'},
  {name: 'Cyprus', code: 'CY', dialCode: '+357', flag: '🇨🇾'},
  {name: 'Czechia', code: 'CZ', dialCode: '+420', flag: '🇨🇿'},
  {name: 'Côte d’Ivoire', code: 'CI', dialCode: '+225', flag: '🇨🇮'},
  {name: 'Denmark', code: 'DK', dialCode: '+45', flag: '🇩🇰'},
  {name: 'Djibouti', code: 'DJ', dialCode: '+253', flag: '🇩🇯'},
  {name: 'Dominica', code: 'DM', dialCode: '+1', flag: '🇩🇲'},
  {name: 'Dominican Republic', code: 'DO', dialCode: '+1', flag: '🇩🇴'},
  {name: 'Ecuador', code: 'EC', dialCode: '+593', flag: '🇪🇨'},
  {name: 'Egypt', code: 'EG', dialCode: '+20', flag: '🇪🇬'},
  {name: 'El Salvador', code: 'SV', dialCode: '+503', flag: '🇸🇻'},
  {name: 'Equatorial Guinea', code: 'GQ', dialCode: '+240', flag: '🇬🇶'},
  {name: 'Eritrea', code: 'ER', dialCode: '+291', flag: '🇪🇷'},
  {name: 'Estonia', code: 'EE', dialCode: '+372', flag: '🇪🇪'},
  {name: 'Eswatini', code: 'SZ', dialCode: '+268', flag: '🇸🇿'},
  {name: 'Ethiopia', code: 'ET', dialCode: '+251', flag: '🇪🇹'},
  {name: 'Falkland Islands', code: 'FK', dialCode: '+500', flag: '🇫🇰'},
  {name: 'Faroe Islands', code: 'FO', dialCode: '+298', flag: '🇫🇴'},
  {name: 'Fiji', code: 'FJ', dialCode: '+679', flag: '🇫🇯'},
  {name: 'Finland', code: 'FI', dialCode: '+358', flag: '🇫🇮'},
  {name: 'France', code: 'FR', dialCode: '+33', flag: '🇫🇷'},
  {name: 'French Guiana', code: 'GF', dialCode: '+594', flag: '🇬🇫'},
  {name: 'French Polynesia', code: 'PF', dialCode: '+689', flag: '🇵🇫'},
  {name: 'Gabon', code: 'GA', dialCode: '+241', flag: '🇬🇦'},
  {name: 'Gambia', code: 'GM', dialCode: '+220', flag: '🇬🇲'},
  {name: 'Georgia', code: 'GE', dialCode: '+995', flag: '🇬🇪'},
  {name: 'Germany', code: 'DE', dialCode: '+49', flag: '🇩🇪'},
  {name: 'Ghana', code: 'GH', dialCode: '+233', flag: '🇬🇭'},
  {name: 'Gibraltar', code: 'GI', dialCode: '+350', flag: '🇬🇮'},
  {name: 'Greece', code: 'GR', dialCode: '+30', flag: '🇬🇷'},
  {name: 'Greenland', code: 'GL', dialCode: '+299', flag: '🇬🇱'},
  {name: 'Grenada', code: 'GD', dialCode: '+1', flag: '🇬🇩'},
  {name: 'Guadeloupe', code: 'GP', dialCode: '+590', flag: '🇬🇵'},
  {name: 'Guam', code: 'GU', dialCode: '+1', flag: '🇬🇺'},
  {name: 'Guatemala', code: 'GT', dialCode: '+502', flag: '🇬🇹'},
  {name: 'Guernsey', code: 'GG', dialCode: '+44', flag: '🇬🇬'},
  {name: 'Guinea', code: 'GN', dialCode: '+224', flag: '🇬🇳'},
  {name: 'Guinea-Bissau', code: 'GW', dialCode: '+245', flag: '🇬🇼'},
  {name: 'Guyana', code: 'GY', dialCode: '+592', flag: '🇬🇾'},
  {name: 'Haiti', code: 'HT', dialCode: '+509', flag: '🇭🇹'},
  {
    name: 'Heard & McDonald Islands',
    code: 'HM',
    dialCode: '+672',
    flag: '🇭🇲',
  },
  {name: 'Honduras', code: 'HN', dialCode: '+504', flag: '🇭🇳'},
  {name: 'Hong Kong', code: 'HK', dialCode: '+852', flag: '🇭🇰'},
  {name: 'Hungary', code: 'HU', dialCode: '+36', flag: '🇭🇺'},
  {name: 'Iceland', code: 'IS', dialCode: '+354', flag: '🇮🇸'},
  {name: 'India', code: 'IN', dialCode: '+91', flag: '🇮🇳'},
  {name: 'Indonesia', code: 'ID', dialCode: '+62', flag: '🇮🇩'},
  {name: 'Iran', code: 'IR', dialCode: '+98', flag: '🇮🇷'},
  {name: 'Iraq', code: 'IQ', dialCode: '+964', flag: '🇮🇶'},
  {name: 'Ireland', code: 'IE', dialCode: '+353', flag: '🇮🇪'},
  {name: 'Isle of Man', code: 'IM', dialCode: '+44', flag: '🇮🇲'},
  {name: 'Israel', code: 'IL', dialCode: '+972', flag: '🇮🇱'},
  {name: 'Italy', code: 'IT', dialCode: '+39', flag: '🇮🇹'},
  {name: 'Japan', code: 'JP', dialCode: '+81', flag: '🇯🇵'},
  {name: 'Jersey', code: 'JE', dialCode: '+44', flag: '🇯🇪'},
  {name: 'Jordan', code: 'JO', dialCode: '+962', flag: '🇯🇴'},
  {name: 'Kazakhstan', code: 'KZ', dialCode: '+7', flag: '🇰🇿'},
  {name: 'Kenya', code: 'KE', dialCode: '+254', flag: '🇰🇪'},
  {name: 'Kiribati', code: 'KI', dialCode: '+686', flag: '🇰🇮'},
  {name: 'Kosovo', code: 'XK', dialCode: '+377', flag: '🇽🇰'},
  {name: 'Kuwait', code: 'KW', dialCode: '+965', flag: '🇰🇼'},
  {name: 'Kyrgyzstan', code: 'KG', dialCode: '+996', flag: '🇰🇬'},
  {name: 'Laos', code: 'LA', dialCode: '+856', flag: '🇱🇦'},
  {name: 'Latvia', code: 'LV', dialCode: '+371', flag: '🇱🇻'},
  {name: 'Lebanon', code: 'LB', dialCode: '+961', flag: '🇱🇧'},
  {name: 'Lesotho', code: 'LS', dialCode: '+266', flag: '🇱🇸'},
  {name: 'Liberia', code: 'LR', dialCode: '+231', flag: '🇱🇷'},
  {name: 'Libya', code: 'LY', dialCode: '+218', flag: '🇱🇾'},
  {name: 'Liechtenstein', code: 'LI', dialCode: '+423', flag: '🇱🇮'},
  {name: 'Lithuania', code: 'LT', dialCode: '+370', flag: '🇱🇹'},
  {name: 'Luxembourg', code: 'LU', dialCode: '+352', flag: '🇱🇺'},
  {name: 'Macao', code: 'MO', dialCode: '+853', flag: '🇲🇴'},
  {name: 'Madagascar', code: 'MG', dialCode: '+261', flag: '🇲🇬'},
  {name: 'Malawi', code: 'MW', dialCode: '+265', flag: '🇲🇼'},
  {name: 'Malaysia', code: 'MY', dialCode: '+60', flag: '🇲🇾'},
  {name: 'Maldives', code: 'MV', dialCode: '+960', flag: '🇲🇻'},
  {name: 'Mali', code: 'ML', dialCode: '+223', flag: '🇲🇱'},
  {name: 'Malta', code: 'MT', dialCode: '+356', flag: '🇲🇹'},
  {name: 'Marshall Islands', code: 'MH', dialCode: '+692', flag: '🇲🇭'},
  {name: 'Martinique', code: 'MQ', dialCode: '+596', flag: '🇲🇶'},
  {name: 'Mauritania', code: 'MR', dialCode: '+222', flag: '🇲🇷'},
  {name: 'Mauritius', code: 'MU', dialCode: '+230', flag: '🇲🇺'},
  {name: 'Mayotte', code: 'YT', dialCode: '+262', flag: '🇾🇹'},
  {name: 'Mexico', code: 'MX', dialCode: '+52', flag: '🇲🇽'},
  {name: 'Micronesia', code: 'FM', dialCode: '+691', flag: '🇫🇲'},
  {name: 'Moldova', code: 'MD', dialCode: '+373', flag: '🇲🇩'},
  {name: 'Monaco', code: 'MC', dialCode: '+377', flag: '🇲🇨'},
  {name: 'Mongolia', code: 'MN', dialCode: '+976', flag: '🇲🇳'},
  {name: 'Montenegro', code: 'ME', dialCode: '+382', flag: '🇲🇪'},
  {name: 'Montserrat', code: 'MS', dialCode: '+1664', flag: '🇲🇸'},
  {name: 'Morocco', code: 'MA', dialCode: '+212', flag: '🇲🇦'},
  {name: 'Mozambique', code: 'MZ', dialCode: '+258', flag: '🇲🇿'},
  {name: 'Myanmar (Burma)', code: 'MM', dialCode: '+95', flag: '🇲🇲'},
  {name: 'Namibia', code: 'NA', dialCode: '+264', flag: '🇳🇦'},
  {name: 'Nauru', code: 'NR', dialCode: '+674', flag: '🇳🇷'},
  {name: 'Nepal', code: 'NP', dialCode: '+977', flag: '🇳🇵'},
  {name: 'Netherlands', code: 'NL', dialCode: '+31', flag: '🇳🇱'},
  {name: 'New Caledonia', code: 'NC', dialCode: '+687', flag: '🇳🇨'},
  {name: 'New Zealand', code: 'NZ', dialCode: '+64', flag: '🇳🇿'},
  {name: 'Nicaragua', code: 'NI', dialCode: '+505', flag: '🇳🇮'},
  {name: 'Niger', code: 'NE', dialCode: '+227', flag: '🇳🇪'},
  {name: 'Nigeria', code: 'NG', dialCode: '+234', flag: '🇳🇬'},
  {name: 'Niue', code: 'NU', dialCode: '+683', flag: '🇳🇺'},
  {name: 'Norfolk Island', code: 'NF', dialCode: '+672', flag: '🇳🇫'},
  {name: 'North Korea', code: 'KP', dialCode: '+850', flag: '🇰🇵'},
  {
    name: 'Northern Mariana Islands',
    code: 'MP',
    dialCode: '+1670',
    flag: '🇲🇵',
  },
  {name: 'Norway', code: 'NO', dialCode: '+47', flag: '🇳🇴'},
  {name: 'Oman', code: 'OM', dialCode: '+968', flag: '🇴🇲'},
  {name: 'Pakistan', code: 'PK', dialCode: '+92', flag: '🇵🇰'},
  {name: 'Palau', code: 'PW', dialCode: '+680', flag: '🇵🇼'},
  {name: 'Palestine Territories', code: 'PS', dialCode: '+970', flag: '🇵🇸'},
  {name: 'Panama', code: 'PA', dialCode: '+507', flag: '🇵🇦'},
  {name: 'Papua New Guinea', code: 'PG', dialCode: '+675', flag: '🇵🇬'},
  {name: 'Paraguay', code: 'PY', dialCode: '+595', flag: '🇵🇾'},
  {name: 'Peru', code: 'PE', dialCode: '+51', flag: '🇵🇪'},
  {name: 'Philippines', code: 'PH', dialCode: '+63', flag: '🇵🇭'},
  {name: 'Poland', code: 'PL', dialCode: '+48', flag: '🇵🇱'},
  {name: 'Portugal', code: 'PT', dialCode: '+351', flag: '🇵🇹'},
  {name: 'Puerto Rico', code: 'PR', dialCode: '+1939', flag: '🇵🇷'},
  {name: 'Qatar', code: 'QA', dialCode: '+974', flag: '🇶🇦'},
  {name: 'Romania', code: 'RO', dialCode: '+40', flag: '🇷🇴'},
  {name: 'Russia', code: 'RU', dialCode: '+7', flag: '🇷🇺'},
  {name: 'Rwanda', code: 'RW', dialCode: '+250', flag: '🇷🇼'},
  {name: 'Réunion', code: 'RE', dialCode: '+262', flag: '🇷🇪'},
  {name: 'Samoa', code: 'WS', dialCode: '+685', flag: '🇼🇸'},
  {name: 'San Marino', code: 'SM', dialCode: '+378', flag: '🇸🇲'},
  {name: 'Saudi Arabia', code: 'SA', dialCode: '+966', flag: '🇸🇦'},
  {name: 'Senegal', code: 'SN', dialCode: '+221', flag: '🇸🇳'},
  {name: 'Serbia', code: 'RS', dialCode: '+381', flag: '🇷🇸'},
  {name: 'Seychelles', code: 'SC', dialCode: '+248', flag: '🇸🇨'},
  {name: 'Sierra Leone', code: 'SL', dialCode: '+232', flag: '🇸🇱'},
  {name: 'Singapore', code: 'SG', dialCode: '+65', flag: '🇸🇬'},
  {name: 'Sint Maarten', code: 'SX', dialCode: '+1', flag: '🇸🇽'},
  {name: 'Slovakia', code: 'SK', dialCode: '+421', flag: '🇸🇰'},
  {name: 'Slovenia', code: 'SI', dialCode: '+386', flag: '🇸🇮'},
  {
    name: 'So. Georgia & So. Sandwich Isl.',
    code: 'GS',
    dialCode: '+500',
    flag: '🇬🇸',
  },
  {name: 'Solomon Islands', code: 'SB', dialCode: '+677', flag: '🇸🇧'},
  {name: 'Somalia', code: 'SO', dialCode: '+252', flag: '🇸🇴'},
  {name: 'South Africa', code: 'ZA', dialCode: '+27', flag: '🇿🇦'},
  {name: 'South Korea', code: 'KR', dialCode: '+82', flag: '🇰🇷'},
  {name: 'South Sudan', code: 'SS', dialCode: '+211', flag: '🇸🇸'},
  {name: 'Spain', code: 'ES', dialCode: '+34', flag: '🇪🇸'},
  {name: 'Sri Lanka', code: 'LK', dialCode: '+94', flag: '🇱🇰'},
  {name: 'St. Barthelemy', code: 'BL', dialCode: '+590', flag: '🇧🇱'},
  {name: 'St. Helena', code: 'SH', dialCode: '+290', flag: '🇸🇭'},
  {name: 'St. Kitts & Nevis', code: 'KN', dialCode: '+1', flag: '🇰🇳'},
  {name: 'St. Lucia', code: 'LC', dialCode: '+1', flag: '🇱🇨'},
  {name: 'St. Martin', code: 'MF', dialCode: '+590', flag: '🇲🇫'},
  {name: 'St. Pierre & Miquelon', code: 'PM', dialCode: '+508', flag: '🇵🇲'},
  {name: 'St. Vincent & Grenadines', code: 'VC', dialCode: '+1', flag: '🇻🇨'},
  {name: 'Sudan', code: 'SD', dialCode: '+249', flag: '🇸🇩'},
  {name: 'Suriname', code: 'SR', dialCode: '+597', flag: '🇸🇷'},
  {name: 'Svalbard & Jan Mayen', code: 'SJ', dialCode: '+47', flag: '🇸🇯'},
  {name: 'Sweden', code: 'SE', dialCode: '+46', flag: '🇸🇪'},
  {name: 'Switzerland', code: 'CH', dialCode: '+41', flag: '🇨🇭'},
  {name: 'Syria', code: 'SY', dialCode: '+963', flag: '🇸🇾'},
  {name: 'São Tomé & Príncipe', code: 'ST', dialCode: '+239', flag: '🇸🇹'},
  {name: 'Taiwan', code: 'TW', dialCode: '+886', flag: '🇹🇼'},
  {name: 'Tajikistan', code: 'TJ', dialCode: '+992', flag: '🇹🇯'},
  {name: 'Tanzania', code: 'TZ', dialCode: '+255', flag: '🇹🇿'},
  {name: 'Thailand', code: 'TH', dialCode: '+66', flag: '🇹🇭'},
  {name: 'Timor-Leste', code: 'TL', dialCode: '+670', flag: '🇹🇱'},
  {name: 'Togo', code: 'TG', dialCode: '+228', flag: '🇹🇬'},
  {name: 'Tokelau', code: 'TK', dialCode: '+690', flag: '🇹🇰'},
  {name: 'Tonga', code: 'TO', dialCode: '+676', flag: '🇹🇴'},
  {name: 'Trinidad & Tobago', code: 'TT', dialCode: '+1', flag: '🇹🇹'},
  {name: 'Tunisia', code: 'TN', dialCode: '+216', flag: '🇹🇳'},
  {name: 'Turkey', code: 'TR', dialCode: '+90', flag: '🇹🇷'},
  {name: 'Turkmenistan', code: 'TM', dialCode: '+993', flag: '🇹🇲'},
  {name: 'Turks & Caicos Islands', code: 'TC', dialCode: '+1', flag: '🇹🇨'},
  {name: 'Tuvalu', code: 'TV', dialCode: '+688', flag: '🇹🇻'},
  {name: 'U.S Virgin Islands', code: 'VI', dialCode: '+1', flag: '🇻🇮'},
  {name: 'Uganda', code: 'UG', dialCode: '+256', flag: '🇺🇬'},
  {name: 'Ukraine', code: 'UA', dialCode: '+380', flag: '🇺🇦'},
  {name: 'United Arab Emirates', code: 'AE', dialCode: '+971', flag: '🇦🇪'},
  {name: 'United Kingdom', code: 'GB', dialCode: '+44', flag: '🇬🇧'},
  {name: 'United States', code: 'US', dialCode: '+1', flag: '🇺🇸'},
  {name: 'Uruguay', code: 'UY', dialCode: '+598', flag: '🇺🇾'},
  {name: 'Uzbekistan', code: 'UZ', dialCode: '+998', flag: '🇺🇿'},
  {name: 'Vanuatu', code: 'VU', dialCode: '+678', flag: '🇻🇺'},
  {name: 'Vatican City', code: 'VA', dialCode: '+379', flag: '🇻🇦'},
  {name: 'Venezuela', code: 'VE', dialCode: '+58', flag: '🇻🇪'},
  {name: 'Vietnam', code: 'VN', dialCode: '+84', flag: '🇻🇳'},
  {name: 'Wallis & Futuna', code: 'WF', dialCode: '+681', flag: '🇼🇫'},
  {name: 'Western Sahara', code: 'EH', dialCode: '+212', flag: '🇪🇭'},
  {name: 'Yemen', code: 'YE', dialCode: '+967', flag: '🇾🇪'},
  {name: 'Zambia', code: 'ZM', dialCode: '+260', flag: '🇿🇲'},
  {name: 'Zimbabwe', code: 'ZW', dialCode: '+263', flag: '🇿🇼'},
  {name: 'Åland Islands', code: 'AX', dialCode: '+358', flag: '🇦🇽'},
];
```

</details>

<details>
<summary><code>src/constants/fonts</code></summary>

```js
export const fonts = {
  'PlayfairDisplay-Regular': require('~/assets/fonts/PlayfairDisplay-Regular.ttf'),
  'PlayfairDisplay-Medium': require('~/assets/fonts/PlayfairDisplay-Medium.ttf'),
  'PlayfairDisplay-SemiBold': require('~/assets/fonts/PlayfairDisplay-SemiBold.ttf'),
  'PlayfairDisplay-Bold': require('~/assets/fonts/PlayfairDisplay-Bold.ttf'),
  'PlayfairDisplay-ExtraBold': require('~/assets/fonts/PlayfairDisplay-ExtraBold.ttf'),
  'PlayfairDisplay-Black': require('~/assets/fonts/PlayfairDisplay-Black.ttf'),
  'Poppins-Thin': require('~/assets/fonts/Poppins-Thin.ttf'),
  'Poppins-ExtraLight': require('~/assets/fonts/Poppins-ExtraLight.ttf'),
  'Poppins-Light': require('~/assets/fonts/Poppins-Light.ttf'),
  'Poppins-Regular': require('~/assets/fonts/Poppins-Regular.ttf'),
  'Poppins-Medium': require('~/assets/fonts/Poppins-Medium.ttf'),
  'Poppins-SemiBold': require('~/assets/fonts/Poppins-SemiBold.ttf'),
  'Poppins-Bold': require('~/assets/fonts/Poppins-Bold.ttf'),
  'Poppins-ExtraBold': require('~/assets/fonts/Poppins-ExtraBold.ttf'),
  'Poppins-Black': require('~/assets/fonts/Poppins-Black.ttf'),
};
```

</details>


<details>
<summary><code>src/constants/vitals</code></summary>

```js
import {PrivateProfile} from '@/api/my-profile/types';
import {age} from '@/utils/age';

export const vitals = [
  {
    title: 'Name',
    getValue: (profile: PrivateProfile) => {
      return profile?.first_name || 'None';
    },
    route: '/profile/name',
  },
  {
    title: 'Age',
    getValue: (profile: PrivateProfile) => {
      return profile?.dob ? age(profile?.dob) : 'None';
    },
    route: '/profile/age',
  },
  {
    title: 'Height',
    getValue: (profile: PrivateProfile) => {
      return profile?.height_cm ? profile?.height_cm + ' cm' : 'None';
    },
    route: '/profile/height',
  },
  {
    title: 'Location',
    getValue: (profile: PrivateProfile) => {
      return profile?.neighborhood || 'None';
    },
    route: '/profile/location',
  },
  {
    title: 'Ethnicity',
    getValue: (profile: PrivateProfile) => {
      return (
        profile?.ethnicities.map((ethnicity) => ethnicity.name).join(', ') ||
        'None'
      );
    },
    route: '/profile/ethnicity',
  },
  {
    title: 'Children',
    getValue: (profile: PrivateProfile) => {
      return profile?.children?.name || 'None';
    },
    route: '/profile/children',
  },
  {
    title: 'Family Plans',
    getValue: (profile: PrivateProfile) => {
      return profile?.family_plans?.name || 'None';
    },
    route: '/profile/family-plans',
  },
  {
    title: 'Covid Vaccine',
    getValue: (profile: PrivateProfile) => {
      return profile?.covid_vaccine?.name || 'None';
    },
    route: '/profile/covid-vaccine',
  },
  {
    title: 'Pets',
    getValue: (profile: PrivateProfile) => {
      return profile?.pets.map((pet) => pet.name).join(', ') || 'None';
    },
    route: '/profile/pets',
  },
  {
    title: 'Zodiac Sign',
    getValue: (profile: PrivateProfile) => {
      return profile?.zodiac_sign?.name || 'None';
    },
    route: '/profile/zodiac-sign',
  },
];

```

</details>

<details>
<summary><code>src/constants/identity</code></summary>

```js
import {PrivateProfile} from '@/api/my-profile/types';

export const identity = [
  {
    title: 'Pronouns',
    getValue: (profile: PrivateProfile) => {
      return (
        profile?.pronouns.map((pronoun) => pronoun.name).join(', ') || 'None'
      );
    },
    route: '/profile/pronouns',
  },
  {
    title: 'Gender',
    getValue: (profile: PrivateProfile) => {
      return profile?.gender?.name || 'None';
    },
    route: '/profile/gender',
  },
  {
    title: 'Sexuality',
    getValue: (profile: PrivateProfile) => {
      return profile?.sexuality?.name || 'None';
    },
    route: '/profile/sexuality',
  },
  {
    title: "I'm interested in",
    getValue: (profile: PrivateProfile) => {
      return (
        profile?.gender_preferences.map((gender) => gender.name).join(', ') ||
        'Everyone'
      );
    },
    route: '/profile/gender-preferences',
  },
];


```

</details>


<details>
<summary><code>src/constants/preferences</code></summary>

```js
import { PrivateProfile } from "@/api/my-profile/types";

export const memberPreferences = [
  {
    title: "I'm interested in",
    getValue: (profile: PrivateProfile) => {
      return (
        profile?.gender_preferences.map((gender) => gender.name).join(", ") ||
        "Everyone"
      );
    },
    route: "/preferences/gender",
  },
  {
    title: "My neighborhood",
    getValue: (profile: PrivateProfile) => {
      return profile?.neighborhood || "None";
    },
    route: "/preferences/neighborhood",
  },
  {
    title: "Maximum distance",
    getValue: (profile: PrivateProfile) => {
      return `${profile?.max_distance_km} km`;
    },
    route: "/preferences/distance",
  },
  {
    title: "Age range",
    getValue: (profile: PrivateProfile) => {
      return `${profile?.min_age} - ${profile?.max_age}`;
    },
    route: "/preferences/age",
  },
  {
    title: "Ethnicity",
    getValue: (profile: PrivateProfile) => {
      return (
        profile?.ethnicity_preferences
          .map((ethnicity) => ethnicity.name)
          .join(", ") || "Open to all"
      );
    },
    route: "/preferences/ethnicity",
  },
];


```
</details>

### Utils

<details>
<summary><code>src/utils/cn</code></summary>

```js
import {clsx, type ClassValue} from 'clsx';
import {twMerge} from 'tailwind-merge';

export const cn = (...inputs: ClassValue[]) => {
  return twMerge(clsx(inputs));
};
```

</details>

<details>
<summary><code>src/utils/age</code></summary>

```js
import {differenceInYears} from 'date-fns';

export const age = (dob: string) => {
  return differenceInYears(new Date(), new Date(dob)).toString();
};
```

</details>

<details>
<summary><code>src/utils/profile</code></summary>

```js
import { PrivateProfile } from "@/api/my-profile/types";
import { PublicProfile } from "@/api/profiles/types";
import { Profile } from "@/types/profile";
import { age } from "./age";

const traitsMapping = [
  {
    key: "dob",
    icon: "calendar-outline",
    privateLabel: (profile: PrivateProfile) =>
      profile.dob ? `${age(profile.dob)}` : null,
    publicLabel: (profile: PublicProfile) =>
      profile.age ? `${profile.age.toString()}` : null,
  },
  {
    key: "gender",
    icon: "male-female-outline",
    privateLabel: (profile: PrivateProfile) => profile.gender?.name,
    publicLabel: (profile: PublicProfile) => profile.gender || null,
  },
  {
    key: "sexuality",
    icon: "heart-outline",
    privateLabel: (profile: PrivateProfile) => profile.sexuality?.name,
    publicLabel: (profile: PublicProfile) => profile.sexuality || null,
  },
  {
    key: "height_cm",
    icon: "resize-outline",
    privateLabel: (profile: PrivateProfile) =>
      profile.height_cm ? `${profile.height_cm} cm` : null,
    publicLabel: (profile: PublicProfile) =>
      profile.height_cm ? `${profile.height_cm} cm` : null,
  },
  {
    key: "location",
    icon: "location-outline",
    privateLabel: (profile: PrivateProfile) => profile.neighborhood,
    publicLabel: (profile: PublicProfile) => profile.neighborhood,
  },
  {
    key: "ethnicities",
    icon: "globe-outline",
    privateLabel: (profile: PrivateProfile) =>
      profile.ethnicities?.map((item) => item.name).join(", "),
    publicLabel: (profile: PublicProfile) => profile.ethnicities?.join(", "),
  },
  {
    key: "children",
    icon: "cart-outline",
    privateLabel: (profile: PrivateProfile) => profile.children?.name,
    publicLabel: (profile: PublicProfile) => profile.children || null,
  },
  {
    key: "family_plans",
    icon: "cart-outline",
    privateLabel: (profile: PrivateProfile) => profile.family_plan?.name,
    publicLabel: (profile: PublicProfile) => profile.family_plan || null,
  },
  {
    key: "pets",
    icon: "paw-outline",
    privateLabel: (profile: PrivateProfile) =>
      profile.pets?.map((item) => item.name).join(", "),
    publicLabel: (profile: PublicProfile) =>
      profile.pets?.map((item) => item).join(", "),
  },
  {
    key: "zodiac_sign",
    icon: "star-outline",
    privateLabel: (profile: PrivateProfile) => profile.zodiac_sign?.name,
    publicLabel: (profile: PublicProfile) => profile.zodiac_sign || null,
  },
];

export const transformPrivateProfile = (profile: PrivateProfile): Profile => {
  return {
    id: profile.id,
    first_name: profile.first_name,
    photos: profile.photos,
    answers: profile.answers,
    traits: traitsMapping.map((trait) => {
      const label = trait.privateLabel(profile);
      return {
        key: trait.key,
        icon: trait.icon,
        label: label || null,
      };
    }),
  };
};

export const transformPublicProfile = (profile: PublicProfile): Profile => {
  return {
    id: profile.id,
    first_name: profile.first_name,
    photos: profile.photos,
    answers: profile.answers,
    traits: traitsMapping.map((trait) => {
      const label = trait.publicLabel(profile);
      return {
        key: trait.key,
        icon: trait.icon,
        label: label || null,
      };
    }),
  };
};



```

</details>

## <a name="links">🔗 Links</a>

You can find important links mentioned in the YouTube video below:

- <a href="https://supabase.com/" target="_blank">Supabase</a>
- <a href="https://supabase.com/docs" target="_blank">Supabase Docs</a>
- <a href="https://supabase.com/docs/guides/getting-started" target="_blank">Supabase Getting Started</a>
- <a href="https://supabase.com/docs/guides/local-development/cli/getting-started?queryGroups=platform&platform=npx" target="_blank">Supabase Local Dev/CLI</a>
- <a href="https://docs.docker.com/desktop/" target="_blank">Docker Desktop</a>

## <a name="assets">📦 Assets</a>

Assets used in the project can be found [here](https://drive.google.com/file/d/1dCdAg7__CNuwT9rB9mJoS-mQv1V0BPw0/view?usp=sharing)

## <a name="more">🚀 More</a>
