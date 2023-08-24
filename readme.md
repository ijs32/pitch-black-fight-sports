<h1 align="center">Hugo + Tailwind CSS Starter and Boilerplate</h1>

<p align="center">Hugoplate is a free starter template built with Hugo, and TailwindCSS, providing everything you need to jumpstart your Hugo project and save valuable time.</p>

<p align="center">Made with ♥ by <a href="https://zeon.studio/"> Zeon Studio</a></p>
<p align=center> If you find this project useful, please give it a ⭐ to show your support. </p>

<h2 align="center"> <a target="_blank" href="https://hugoplate.netlify.app/" rel="nofollow">👀 Demo</a> | <a  target="_blank" href="https://pagespeed.web.dev/analysis/https-hugoplate-netlify-app/6lyxjw6t4r?form_factor=desktop">Page Speed (95+)🚀</a>
</h2>

<p align="center">
  <a href="https://github.com/gohugoio/hugo/releases/tag/v0.115.1" alt="Contributors">
    <img src="https://img.shields.io/static/v1?label=min-HUGO-version&message=0.115.1&color=f00&logo=hugo" />
  </a>

  <a href="https://github.com/zeon-studio/hugoplate/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/zeon-studio/hugoplate" alt="license"></a>

  <img src="https://img.shields.io/github/languages/code-size/zeon-studio/hugoplate" alt="code size">

  <a href="https://github.com/zeon-studio/hugoplate/graphs/contributors">
    <img src="https://img.shields.io/github/contributors/zeon-studio/hugoplate" alt="contributors"></a>
</p>

### ⚙️ Prerequisites

To start using this template, you need to have some prerequisites installed on your machine.

- [Hugo Extended v0.115+](https://gohugo.io/installation/)
- [Node v18+](https://nodejs.org/en/download/)
- [Go v1.20+](https://go.dev/doc/install)

### 👉 Project Setup

We build this custom script to make your project setup easier. It will create a new Hugo theme folder, and clone the Hugoplate theme into it. Then move the exampleSite folder into the root directory. So that you can start your Hugo server without going into the exampleSite folder. Use the following command to setup your project.

```bash
npm run project-setup
```

### 👉 Install Dependencies

Install all the dependencies using the following command.

```bash
npm install
```

### 👉 Development Command

Start the development server using the following command.

```bash
npm run dev
```

### 👉 Site Config

You can change the site title, base URL, language, theme, plugins, and more from the `hugo.toml` file.

### 👉 Site Params

You can customize all the parameters from the `config/_default/params.toml` file. This includes the logo, favicon, search, SEO metadata, and more.

### 👉 Colors and Fonts

You can change the colors and fonts from the `data/theme.json` file. This includes the primary color, secondary color, font family, and font size.

---

## 🛠 Advanced Usage

We have added some custom scripts to make your life easier. You can use these scripts to help you with your development.

### 👉 Update Modules

We have added a lot of modules to this template. You can update all the modules using the following command.

```bash
npm run update-modules
```

### 👉 Remove Dark Mode

If you want to remove dark mode from your project, then you have to do it manually from everywhere. So we build a custom script to do it for you. you can use the following command to remove dark mode from your project.

```bash
npm run remove-darkmode
```

---

## 🚀 Build And Deploy

After you finish your development, you can build or deploy your project almost everywhere. Let's see the process:

### 👉 Build Command

To build your project locally, you can use the following command. It will purge all the unused CSS and minify all the files.

```bash
npm run build
```

### 👉 Deploy Site

We have provided 5 different deploy platform configurations with this template, so you can deploy easily.

- [Netlify](https://www.netlify.com/)
- [Vercel](https://vercel.com/)
- [Github Actions](https://github.com/features/actions)
- [Gitlab Ci](https://docs.gitlab.com/ee/ci/)
- [AWS Amplify](https://aws.amazon.com/amplify/)

And if you want to Host some other hosting platforms. then you can build your project, and you will get a `public` folder. that you can copy and paste on your hosting platform.

> **Note:** You must change the `baseURL` in the `hugo.toml` file. Otherwise, your site will not work properly.


