# What is Electrode?

> Electrode is a platform for building universal React/Node.js applications with a standardized structure, best practices, and modern technologies baked in. Electrode focuses on performance, component reusability, and simple deployment to multiple cloud providers—so you can focus on what makes your app unique.


### Core: Quick + Easy
Electrode Core gets you up and running quickly by providing build scripts to streamline development and deployment and [Electrode Archetypes](https://github.com/electrode-io?utf8=%E2%9C%93&query=archetype%20only%3Asources%20) to standardize the structure of your app and its associated React components. Electrode's archetype system establishes common patterns across projects and components, helping teams standardize on development best practices.

**It only takes a minute to get your new Electrode application running and a
few more minutes to deploy your app to the cloud. See our [Getting Started:
Quick Guide](https://electrode-io.github.io/docs/get_started.html) to get started now.**

<hr>

### Stand Alone Modules: Optimize Where You Want
As part of the Electrode Platform, we have a number of modules to help with a
variety of common tasks and features, from [above the fold rendering](https://electrode-io.github.io/docs/above_fold_rendering.html), [server-side render
caching](https://electrode-io.github.io/docs/server_side_render_cache.html) to [flexible configuration
management](https://electrode-io.github.io/docs/confippet.html). These modules can be used independently of
Electrode Core, which means you can [integrate them into your existing
apps](https://electrode-io.github.io/docs/stand_alone_modules.html).

**Start using these modules in your existing application with our [guide](https://electrode-io.github.io/docs/stand_alone_modules.html).**

<hr>

### Tools: Power Up Your Existing Applications
The Electrode Platform also has tools that can be consumed by existing
applications using other platforms (though with
Electrode core, these tools are either bundled directly or require far less configuration). There are currently
two powerful tools: one which enables [discovery of reusable
components](https://electrode-io.github.io/docs/electrode_explorer.html) and another to help optimize your
[JavaScript bundles](https://github.com/electrode-io/electrode-electrify)

**Start using these tools in your existing applications [Electrode Explorer](https://electrode-io.github.io/docs/electrode_explorer.html) and [Electrify](https://github.com/electrode-io/electrode-electrify).**

##Features
[Electrode Boilerplate](https://github.com/electrode-io/electrode-boilerplate-universal-react-node) comes fully loaded with the best technologies available:

*  [React](https://facebook.github.io/react/index.html) is an awesome JavaScript library for building user interfaces, created by Facebook.

*  [Redux](http://redux.js.org/docs/basics/UsageWithReact.html) a predictable state container for JavaScript apps. #game-changer.

*  [React Router](https://github.com/ReactTraining/react-router/tree/master/docs) is a powerful routing library built on top of React.

*  [CSS Modules](https://github.com/css-modules/css-modules) a CSS file in which all class names and animation names are scoped locally by default. Fixes the problem of the global scope in CSS. #winning

*  [Universal rendering](https://medium.com/@mjackson/universal-javascript-4761051b7ae9#.xjxr5yj5z) built in.

*  [Webpack](https://webpack.github.io/docs/motivation.html) a powerful module bundler.

*  [Webpack Isomorphic Loader](https://github.com/jchip/isomorphic-loader) a powerful tool that makes NodeJS `require` understand files such as images for SSR.

*  [Babel](https://babeljs.io/) transpiles ES6 + 7.

*  [ESLint](http://eslint.org/) a pluggable linting utility for Javascript.

*  [Mocha](https://mochajs.org/) a feature-rich Javascript testing framework.

*  [Enzyme](https://github.com/airbnb/enzyme) a Javascript testing utility for React, created by airbnb.

*  [TravisCI](https://travis-ci.org/) a continuous integration service to build and test software projects.

*  [Gulp](http://gulpjs.com/) a Javascript build tool that lets us automate tasks.

*  [Yeoman](http://yeoman.io/) a Scaffolding tool for modern webapps.

*  [History](https://www.npmjs.com/package/history) a Javascript library for managing session history.

*  [Bluebird](http://bluebirdjs.com/docs/why-promises.html) a great Javascript promise library.

*  [Electrode Confippet](https://github.com/electrode-io/electrode-confippet) Confippet is a versatile and flexible utility for managing configurations of Node.js applications.

*  [Electrode JWT CSRF](https://github.com/electrode-io/electrode-csrf-jwt) Cross-Site Request Forgery (CSRF) protection with JWT.

*  [Electrode-Redux-Router-Engine](https://github.com/electrode-io/redux-router-engine) An Electrode routing and rendering engine using react-router and redux.

*  [Component Caching](https://github.com/electrode-io/electrode-react-ssr-caching) Optimize React SSR with profiling and component caching.

*  [Electrode-Server](https://github.com/electrode-io/electrode-server) A configurable web server using Hapi.js on top of Node.js.

*  [Electrify](https://github.com/electrode-io/electrode-electrify) Tool for analyzing the module tree of webpack projects.

*  [Electrode-Docgen](https://github.com/electrode-io/electrode-docgen) A custom metadata extractor for the Electrode framework, automates component documentation.

### Docs
Start creating cool web applications with React and Node.js today with [Electrode](https://github.com/electrode-io/electrode-boilerplate-universal-react-node). We can't wait to see what you build!

# Why use Electrode?

> If you're writing a universal React/Node.js application, then Electrode is for you!

[@WalmartLabs](http://www.walmartlabs.com/), we recently migrated [walmart.com](http://walmart.com) to a [Universal JavaScript](https://medium.com/@mjackson/universal-javascript-4761051b7ae9#.k3j9fruyn)
stack using React/Node.js. Along the way, we hit a few stumbling blocks that
might sound familiar if you've worked on a large, complex web app before.

### Universal JavaScript
Universal JavaScript allows us to use the same view rendering code from the
server and client. When a user requests a page, they immediately receive
the fully rendered HTML on initial page load. They will not have to wait
for the client side JavaScript code to load and render the page.

Rich app like experiences are possible without requiring a full page load
when navigating or responding to user actions within the same page.
The client side code will handle all the rendering of the view changes within
the page. Only the data changes will be sent between the client and the server.

This approach provides for an optimized user experience resulting in fast
page loads and even faster navigation experience. In the world of eCommerce
where every millisecond counts, we believe this is the best way forward.

### Code/UI Reuse

We reuse React components across all of our brands, which means our developers
need to be able to search through thousands of components, view their
documentation and see them rendered, and use another developer's component
secure in the knowledge that its structure and implementation are consistent
with our standards. We needed a way to ensure that all components were built
according to modern best practices, without slowing our developers down with a
lot of manual configuration.

### Server Side Rendering (SSR) Performance

We serve millions of customers a day, so performance is critical to our business.
React's SSR support is vital for SEO (Search Engine Optimization) and has the potential to improve performance,
but it's intensive on the server CPUs. We needed a platform with SSR built-in with
a default configuration that's optimized for performance.

### Fast Startup and Deployment

We don't have time to create an application structure, configuration files, and
Docker containers from scratch every time we start a project. We need to start
fast and to deploy fast, with a consistent structure and optimal configuration every
time.

### Three Pillars

To solve these problems, we created the Electrode platform. Electrode consists
of three pillars: Electrode Core, Electrode Modules, and Electrode Tools.

***Electrode Core*** provides a set of modules that get you started with a simple,
consistent structure that follows modern best practices. When you're ready to
take your app into production, Electrode automatically deploys to your favorite
cloud provider.

***Electrode Modules*** improve performance, efficiency, and security by adding
features like [above the fold rendering](https://electrode-io.github.io/docs/above_fold_rendering.html), [configuration management](https://electrode-io.github.io/docs/confippet.html), and [cross-site request forgery protection](https://electrode-io.github.io/docs/stateless_csrf_validation.html). These modules can even be used with your existing React/Node.js application—so there's no need to migrate to Electrode Core.

***Electrode Tools*** help [organize](https://electrode-io.github.io/docs/electrode_explorer.html) reusable components and [optimize large
JavaScript bundles](https://github.com/electrode-io/electrode-electrify). Like the modules, our tools can be used with any
React/Node.js app.

### Future Investment

[Electrode](https://github.com/electrode-io) will continue to improve as we continue to solve problems like these at [@WalmartLabs](http://www.walmartlabs.com/). Future enhancements will include more [progressive web app
features](https://developers.google.com/web/progressive-web-apps/) for web and mobile, bigger investments in performance, and much more.

We're committed to open source, which means our investment is your investment.

Built with :heart: by [Team Electrode](https://github.com/orgs/electrode-io/people) @WalmartLabs.

