# rw-tailwind-css-landing-page

This sample is the Typescript variant of the [React components SaaS startup landing with RedwoodJS and Tailwind CSS in 10 minutes](https://dev.to/spanarin/react-components-saas-startup-landing-with-redwoodjs-and-tailwind-css-in-10-minutes-3hc4) written by [Sergey Panarin]((https://github.com/spanarin))

The base application is a clone of [rw-minimal-app](https://github.com/adriatic/rw-minimal-app) created using CLI commands from the [Starting Development](https://redwoodjs.com/docs/tutorial/chapter1/installation) tutorial document:

```
yarn create redwood-app --ts ./minimal-application
cd minimal-application

yarn rw dev
yarn redwood generate page home /
yarn redwood generate page about
```

followed by editing the two newly created pages to be

```
import { MetaTags } from '@redwoodjs/web'

const HomePage = () => {
  return (
    <>
      <MetaTags title="Home" description="Home page" />

      <h1>Home Page</h1>
    </>
  )
}

export default HomePage
```

and

```
import { MetaTags } from '@redwoodjs/web'

const HomePage = () => {
  return (
    <>
      <MetaTags title="Home" description="Home page" />

      <h1>Home Page</h1>
    </>
  )
}

export default HomePage

```

Note that we removed nearly everything from these two pages as all the content and navigation will be created by all supported UI libraries:

- [Chakra UI](https://github.com/adriatic/rw-chakra)

- [Tailwindcss](https://tailwindcss.com/?ref=creativetim)

- [Daisy UI](https://github.com/adriatic/rw-daisyUI)

- [Bootstrap 5](https://github.com/adriatic/rw-Boostrap-5) 

Each of these repositories contains the code from [rw-minimal-app](https://github.com/adriatic/rw-minimal-app) which is subsequently augmented by the code from the respected UI components library.
